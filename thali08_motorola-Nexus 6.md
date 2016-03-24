#### Test 639107040172e2e_thali08_motorola-Nexus 6 Logs


```
--------- beginning of main
,03-24 22:21:36.923  1261  1261 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-24 22:21:37.004  1261  1280 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
03-24 22:21:37.005  1261  1280 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 22:21:37.005  1261  1280 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 22:21:37.005  1261  1280 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
03-24 22:21:37.016  1261  1280 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-24 22:21:37.044  2764  2764 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
03-24 22:21:37.045  2764  2764 D Finsky  : [1] 5.onFinished: Installation state replication failed.
03-24 22:21:37.045  2764  2764 D Finsky  : [1] 5.onFinished: Scheduling replication attempt 5.
03-24 22:21:37.223  3267  3267 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
03-24 22:21:37.226  3267  3267 D AndroidRuntime: CheckJNI is OFF
03-24 22:21:37.350  3267  3267 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
03-24 22:21:37.354   821  1259 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
03-24 22:21:37.361   821  1259 V WindowManager: addAppToken: AppWindowToken{23c5aaca token=Token{5357635 ActivityRecord{105ef06c u0 com.test.thalitest/.MainActivity t17}}} to stack=1 task=17 at 0
03-24 22:21:37.367   821   860 V WindowManager: Adding window Window{31bb36ed u0 Starting com.test.thalitest} at 2 of 7 (after Window{14150912 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
03-24 22:21:37.373  3267  3267 D AndroidRuntime: Shutting down VM
03-24 22:21:37.382  1510  1768 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.u@2f8ed454
03-24 22:21:37.382  1510  1510 I HotwordDetector: Closing mic
03-24 22:21:37.420   821   837 I ActivityManager: Start proc 3282:com.test.thalitest/u0a95 for activity com.test.thalitest/.MainActivity
03-24 22:21:37.436   356  1774 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
03-24 22:21:37.440   356  1774 D audio_hw_primary: disable_snd_device: snd_device(55: voice-rec-mic)
03-24 22:21:37.452   356  1027 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
03-24 22:21:37.455  1510  1770 I HotwordRecognitionRnr: Stopping hotword detection.
03-24 22:21:37.455  1510  1771 I HotwordRecognitionRnr: Hotword detection finished
03-24 22:21:37.486   821  1416 I ActivityManager: Killing 2891:com.google.android.apps.messaging/u0a75 (adj 15): empty #17
03-24 22:21:37.527   821  1252 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1659995411
03-24 22:21:37.527   821  1252 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
03-24 22:21:37.597   821  1416 I ActivityManager: Killing 2723:com.google.android.apps.fitness/u0a51 (adj 15): empty #18
,03-24 22:21:37.612   871   871 I kickstart: STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
03-24 22:21:37.612   871   871 I kickstart: STATUS: Wrote to /sys/power/wake_lock
,03-24 22:21:37.654   871   871 E kickstart: ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1
03-24 22:21:37.654   871   871 I kickstart: STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1' for writing
,03-24 22:21:37.873  3282  3282 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,03-24 22:21:37.886  3282  3282 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 2276-2279)
03-24 22:21:37.887  3282  3282 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-24 22:21:37.915  3282  3282 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2ca2333f}
,03-24 22:21:37.916  3282  3282 I LibraryLoader: Expected native library version number "",actual native library version number "",
03-24 22:21:37.916  3282  3282 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,03-24 22:21:37.928  3282  3282 I BrowserStartupController: Initializing chromium process, singleProcess=true
,03-24 22:21:37.928  3282  3282 W art     : Attempt to remove local handle scope entry from IRT, ignoring,
03-24 22:21:37.929  3282  3282 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-24 22:21:37.937  3282  3306 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,03-24 22:21:37.951  3282  3282 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,03-24 22:21:37.960  3282  3282 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-24 22:21:37.961  3282  3282 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,03-24 22:21:37.961  3282  3282 I Adreno  : EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,03-24 22:21:38.039   821   859 D BluetoothManagerService: Message: 20
,03-24 22:21:38.039   821   859 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1c91bed2:true
,03-24 22:21:38.092  3282  3282 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-24 22:21:38.101  3282  3282 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-24 22:21:38.115  3282  3282 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,03-24 22:21:38.123  3282  3282 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-24 22:21:38.123  3282  3282 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-24 22:21:38.188  3282  3329 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,03-24 22:21:38.205  3282  3282 D Atlas   : Validating map...
,03-24 22:21:38.220   821   836 V WindowManager: Adding window Window{e238082 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{31bb36ed u0 Starting com.test.thalitest})
,03-24 22:21:38.223  3282  3315 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,03-24 22:21:38.261  3282  3329 I OpenGLRenderer: Initialized EGL, version 1.4
,03-24 22:21:38.270  3282  3329 D OpenGLRenderer: Enabling debug mode 0
,03-24 22:21:38.335   821   860 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +962ms
,03-24 22:21:38.341  1234  1234 I Keyboard.Facilitator: onFinishInput()
,03-24 22:21:38.354  3282  3282 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3282
,03-24 22:21:38.530  3282  3282 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-24 22:21:38.613   821   862 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...,
,03-24 22:21:38.629   821   862 I Adreno  : EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,03-24 22:21:38.641   871   871 I kickstart: STATUS: Received file 'm9kefs1'
03-24 22:21:38.641   871   871 I kickstart: STATUS: 950272 bytes transferred in 0.986643 seconds
03-24 22:21:38.641   871   871 I kickstart: STATUS: Successfully downloaded files from target 
03-24 22:21:38.641   871   871 I kickstart: STATUS: Wrote to /sys/power/wake_unlock
,03-24 22:21:38.644   871   871 I kickstart: STATUS: Sahara protocol completed
,03-24 22:21:38.650   278   992 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (141 us)
03-24 22:21:38.650  3282  3330 D jxcore_app_log: JniHelper::setJavaVM(0xb489d200), pthread_self() = -1575603456
,03-24 22:21:38.658  3282  3330 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-24 22:21:38.658  3282  3330 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-24 22:21:38.658  3282  3330 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-24 22:21:38.658  3282  3330 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-24 22:21:38.658  3282  3330 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-24 22:21:38.658  3282  3330 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@112e18b1 added. We now have 1 listener(s)
03-24 22:21:38.659   821  1415 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 22:21:38.661  3282  3330 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,03-24 22:21:38.664  3282  3330 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,03-24 22:21:38.665  3282  3330 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,03-24 22:21:38.666  3282  3330 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,03-24 22:21:38.669  3282  3330 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-24 22:21:38.669  3282  3330 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-24 22:21:38.669  3282  3330 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-24 22:21:38.669  3282  3330 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
03-24 22:21:38.669  3282  3330 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-24 22:21:38.669  3282  3330 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-24 22:21:38.669  3282  3330 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
03-24 22:21:38.669  3282  3330 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-24 22:21:38.669  3282  3330 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-24 22:21:38.669  3282  3330 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-24 22:21:38.669  3282  3330 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-24 22:21:38.669  3282  3330 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@352a9904 added. We now have 1 listener(s)
03-24 22:21:38.669  3282  3330 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-24 22:21:38.672   821  1011 D WifiService: New client listening to asynchronous messages
,03-24 22:21:38.673  3282  3330 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,03-24 22:21:38.676  3282  3330 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,03-24 22:21:38.678  3282  3330 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
,03-24 22:21:38.679  3282  3330 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
03-24 22:21:38.679  3282  3330 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,03-24 22:21:38.681  3282  3330 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-24 22:21:38.682   821  1370 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 22:21:38.682  3282  3330 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,03-24 22:21:38.687  3282  3330 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 22:21:38.687  3282  3330 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 22:21:38.687  3282  3330 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 22:21:38.687  3282  3330 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 22:21:38.687  3282  3330 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 22:21:38.687  3282  3330 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
03-24 22:21:38.687  3282  3330 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
03-24 22:21:38.687  3282  3330 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
03-24 22:21:38.687  3282  3330 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-24 22:21:38.687  3282  3330 D io.jxcore.node.ConnectivityMonitor: start: OK
,03-24 22:21:38.688  3282  3330 I io.jxcore.node.LifeCycleMonitor: start: OK
,03-24 22:21:38.803  3282  3282 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-24 22:21:38.805  3282  3282 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-24 22:21:39.165   821   860 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,03-24 22:21:39.167   278   278 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6482000
,03-24 22:21:39.167   821   821 V ActivityManager: Display changed displayId=0
,03-24 22:21:39.168   278   278 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,03-24 22:21:39.392  3282  3339 W jxcore-log: Initializing JXcore engine
03-24 22:21:39.392  3282  3339 W jxcore-log: JXcore engine is ready
,03-24 22:21:39.421  3339  3339 W Thread-349: type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[12983]" dev="sockfs" ino=12983 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
03-24 22:21:39.421  3339  3339 W Thread-349: type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
03-24 22:21:39.421  3339  3339 W Thread-349: type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[10748]" dev="sockfs" ino=10748 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,03-24 22:21:39.421  3339  3339 W Thread-349: type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[21876]" dev="sockfs" ino=21876 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,03-24 22:21:39.441  3282  3339 W jxcore-log: Starting JXcore engine
,03-24 22:21:39.472   278   318 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,03-24 22:21:39.474   278   278 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
03-24 22:21:39.474   821  1042 D SurfaceControl: Excessive delay in setPowerMode(): 309ms
,03-24 22:21:39.479   821   862 I DreamManagerService: Entering dreamland.
03-24 22:21:39.481   356  1028 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
03-24 22:21:39.481   356  1028 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
03-24 22:21:39.483   821   857 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,03-24 22:21:39.487   821   862 I PowerManagerService: Dozing...
,03-24 22:21:39.494   821  1010 E WifiStateMachine: cancelDelayedScan -> 17
03-24 22:21:39.499   821  1010 E native  : do suspend false
,03-24 22:21:39.545  3282  3339 W jxcore-log: Platform android
03-24 22:21:39.545  3282  3339 W jxcore-log: 
03-24 22:21:39.545  3282  3339 W jxcore-log: Process ARCH arm
03-24 22:21:39.545  3282  3339 W jxcore-log: 
,03-24 22:21:39.587   821  1415 I art     : Explicit concurrent mark sweep GC freed 44010(2MB) AllocSpace objects, 1(16KB) LOS objects, 32% free, 33MB/49MB, paused 1.123ms total 65.582ms
,03-24 22:21:39.601   821  1010 E WifiStateMachine: cancelDelayedScan -> 19
,03-24 22:21:39.607  1234  1234 I Keyboard.Facilitator: onFinishInput()
,03-24 22:21:39.610   821  1010 E native  : do suspend true
,03-24 22:21:39.664   356  1211 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
03-24 22:21:39.664   356  1211 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,03-24 22:21:39.699   821  1010 E WifiStateMachine: WifiStateMachine Disconnected CMD_START_SCAN source -2 18, 19 -> obsolete
,03-24 22:21:39.753  3282  3339 I jxcore-log: JXcore Cordova bridge is ready!,
03-24 22:21:39.753  3282  3339 I jxcore-log: 
03-24 22:21:39.753  3282  3339 W jxcore-log: JXcore engine is started
,03-24 22:21:39.758  3282  3330 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-24 22:21:39.760  3282  3282 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,03-24 22:21:39.948  2156  2221 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 22:21:40.700  1148  1148 I wpa_supplicant: wlan0: Reject scan trigger since one is already pending
,03-24 22:21:40.700  1148  1148 W wpa_supplicant: wlan0: Failed to initiate AP scan
,03-24 22:21:41.701  1148  1148 I wpa_supplicant: wlan0: Reject scan trigger since one is already pending
03-24 22:21:41.701  1148  1148 W wpa_supplicant: wlan0: Failed to initiate AP scan
,03-24 22:21:42.702  1148  1148 I wpa_supplicant: wlan0: Reject scan trigger since one is already pending
03-24 22:21:42.702  1148  1148 W wpa_supplicant: wlan0: Failed to initiate AP scan
,03-24 22:21:43.704  1148  1148 I wpa_supplicant: wlan0: Reject scan trigger since one is already pending
,03-24 22:21:43.704  1148  1148 W wpa_supplicant: wlan0: Failed to initiate AP scan
,03-24 22:21:44.705  1148  1148 I wpa_supplicant: wlan0: Reject scan trigger since one is already pending
03-24 22:21:44.705  1148  1148 W wpa_supplicant: wlan0: Failed to initiate AP scan
,03-24 22:21:45.706  1148  1148 I wpa_supplicant: wlan0: Reject scan trigger since one is already pending
03-24 22:21:45.706  1148  1148 W wpa_supplicant: wlan0: Failed to initiate AP scan
,03-24 22:21:46.707  1148  1148 I wpa_supplicant: wlan0: Reject scan trigger since one is already pending
03-24 22:21:46.707  1148  1148 W wpa_supplicant: wlan0: Failed to initiate AP scan
,03-24 22:21:47.708  1148  1148 I wpa_supplicant: wlan0: Reject scan trigger since one is already pending
03-24 22:21:47.709  1148  1148 W wpa_supplicant: wlan0: Failed to initiate AP scan
,03-24 22:21:48.710  1148  1148 I wpa_supplicant: wlan0: Reject scan trigger since one is already pending
03-24 22:21:48.710  1148  1148 W wpa_supplicant: wlan0: Failed to initiate AP scan
,03-24 22:21:48.924  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 22:21:48.924  3282  3339 I jxcore-log: 
,03-24 22:21:48.926  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 22:21:48.926  3282  3339 I jxcore-log: 
,03-24 22:21:48.933  3282  3339 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
03-24 22:21:48.933  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 22:21:48.933  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 22:21:48.933  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 22:21:48.933  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true,
03-24 22:21:48.933  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
03-24 22:21:48.933  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
03-24 22:21:48.933  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,03-24 22:21:48.938  3282  3339 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null,
,03-24 22:21:48.941  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,03-24 22:21:48.941  3282  3339 I jxcore-log: 
,03-24 22:21:48.944  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native,
03-24 22:21:48.944  3282  3339 I jxcore-log: 
,03-24 22:21:49.416   821  1010 E WifiStateMachine: WifiStateMachine Disconnected CMD_START_SCAN source -2 16, 19 -> obsolete
,03-24 22:21:49.518  3282  3339 I jxcore-log: Unit Test app is loaded
03-24 22:21:49.518  3282  3339 I jxcore-log: 
,03-24 22:21:49.525  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
,03-24 22:21:49.525  3282  3339 I jxcore-log: 
,03-24 22:21:49.535  3282  3339 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,03-24 22:21:49.535  3282  3282 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,03-24 22:21:49.539  3282  3339 I jxcore-log: INFO testUtils: BLE multiple advertisement supported,
03-24 22:21:49.539  3282  3339 I jxcore-log: 
,03-24 22:21:49.541  3282  3339 I jxcore-log: My device name is: motorola-Nexus 6,
03-24 22:21:49.541  3282  3339 I jxcore-log: 
,03-24 22:21:51.038  1148  1148 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,03-24 22:21:51.460  1148  1148 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e,
,03-24 22:21:51.492  1148  1148 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
03-24 22:21:51.492  1148  1148 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,03-24 22:21:51.505   821  1010 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
,03-24 22:21:51.506   821  1012 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,03-24 22:21:51.506   821  1010 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,03-24 22:21:51.508   821  1010 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,03-24 22:21:51.512   352   812 D CommandListener: Setting iface cfg
,03-24 22:21:51.518   821  1010 E WifiStateMachine: Start Dhcp Watchdog 1
,03-24 22:21:51.520   821  1010 E WifiStateMachine:  WifiLinkLayerStats: 
03-24 22:21:51.520   821  1010 E WifiStateMachine:  my bss beacon rx: 0
03-24 22:21:51.520   821  1010 E WifiStateMachine:  RSSI mgmt: -43
03-24 22:21:51.520   821  1010 E WifiStateMachine:  BE :  rx=0 tx=3 lost=0 retries=0
03-24 22:21:51.520   821  1010 E WifiStateMachine:  BK :  rx=0 tx=0 lost=0 retries=0
03-24 22:21:51.520   821  1010 E WifiStateMachine:  VI :  rx=0 tx=0 lost=0 retries=0
03-24 22:21:51.520   821  1010 E WifiStateMachine:  VO :  rx=2 tx=0 lost=0 retries=0
03-24 22:21:51.520   821  1010 E WifiStateMachine:  on_time : 0 tx_time=66 rx_time=102 scan_time=0
,03-24 22:21:51.609   821  1010 E native  : do suspend false
,03-24 22:21:51.615   821  1010 E WifiStateMachine: scanCount==0 - aborting
,03-24 22:21:51.863  3351  3351 I dhcpcd  : version 5.5.6 starting
,03-24 22:21:51.984  3351  3351 I dhcpcd  : wlan0: rebinding lease of 192.168.1.125
,03-24 22:21:52.129  3351  3351 I dhcpcd  : wlan0: acknowledged 192.168.1.125 from 192.168.1.1,
,03-24 22:21:52.278  3351  3351 I dhcpcd  : wlan0: leased 192.168.1.125 for 172800 seconds
,03-24 22:21:52.636   821  1010 E native  : do suspend true
,03-24 22:21:52.678   821  1012 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
03-24 22:21:52.680   821  1012 D ConnectivityService: Adding iface wlan0 to network 100
,03-24 22:21:52.686   821  1010 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,03-24 22:21:52.711   821  1012 E ConnectivityService: Unexpected mtu value: 0, wlan0
03-24 22:21:52.711   821  1012 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 100
,03-24 22:21:52.712   821  1012 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100,
03-24 22:21:52.713   821  1012 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,03-24 22:21:52.714   821  1012 D ConnectivityService: Setting Dns servers for network 100 to [/192.168.1.1]
,03-24 22:21:52.725   821  1012 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100],
,03-24 22:21:52.729   821  1012 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100],
03-24 22:21:52.729   821  3349 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler },
03-24 22:21:52.729   821  3349 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Connected
03-24 22:21:52.729   821  3349 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler },
03-24 22:21:52.730   821  3349 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
03-24 22:21:52.730   821  1012 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
,03-24 22:21:52.730   821  1012 D ConnectivityService:    accepting network in place of null
03-24 22:21:52.731   821  1012 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.125/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} },
03-24 22:21:52.733   821  1012 D ConnectivityService: Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
,03-24 22:21:52.736   821  1012 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
03-24 22:21:52.736   821  1012 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
03-24 22:21:52.737   821  1012 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
03-24 22:21:52.737   821  1012 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
03-24 22:21:52.737  1062  1567 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
03-24 22:21:52.739   821   859 D Tethering: MasterInitialState.processMessage what=3
,03-24 22:21:52.745  1329  1548 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
03-24 22:21:52.746  1329  1548 E PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,03-24 22:21:52.749   821  1416 V BackupManagerService: Scheduling immediate backup pass
03-24 22:21:52.750   821   854 D TelephonyManager: getDataEnabled: retVal=false
,03-24 22:21:52.751   821   821 V BackupManagerService: Running a backup pass
,03-24 22:21:52.752   821  1041 V BackupManagerService: clearing pending backups
,03-24 22:21:52.754  2950  2950 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,03-24 22:21:52.764  3282  3282 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
03-24 22:21:52.764  3282  3282 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 22:21:52.764  3282  3282 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 22:21:52.764  3282  3282 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 22:21:52.764  3282  3282 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 22:21:52.764  3282  3282 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 22:21:52.764  3282  3282 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 22:21:52.764  3282  3282 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 22:21:52.768  3282  3282 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 22:21:52.770  1510  1510 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,03-24 22:21:52.771   821  1041 V PerformBackupTask: Beginning backup of 14 targets
,03-24 22:21:52.774  2950  2950 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
03-24 22:21:52.774   821  1041 D PerformBackupTask: invokeAgentForBackup on @pm@
,03-24 22:21:52.776   821   854 E GpsLocationProvider: No APN found to select.
,03-24 22:21:52.783   821  1041 V BackupServiceBinder: doBackup() invoked
03-24 22:21:52.785   821  1041 I PMBA    : Previous metadata 1570415 mismatch vs 1860966 - rewriting
,03-24 22:21:52.811   821  1041 I BackupRestoreController: Getting widget state for user: 0
,03-24 22:21:52.835   821  1328 I ActivityManager: Start proc 3394:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.steen.receiver.ConnectivityChangeReceiver
,03-24 22:21:52.845   821  1283 D AlarmManagerService: Setting time of day to sec=1458854513
03-24 22:21:53.451   821  1283 W AlarmManagerService: Unable to set rtc to 1458854513: Invalid argument
,03-24 22:21:53.455   368   368 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 210us total 14.466ms
,03-24 22:21:53.476  1261  1261 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 22:21:53.479   368   368 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 285us total 21.159ms
,03-24 22:21:53.490   368   368 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 210us total 10.551ms
,03-24 22:21:53.492   821  3404 D GpsLocationProvider: NTP server returned: 1458854513451 (Thu Mar 24 22:21:53 GMT+01:00 2016) reference: 177238 certainty: 18 system time offset: -41
,03-24 22:21:53.502   821  3349 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 24 Mar 2016 21:21:53 GMT], X-Android-Received-Millis=[1458854513502], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1458854513459]}
,03-24 22:21:53.503   821  3349 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Validated
03-24 22:21:53.503   821  1012 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
03-24 22:21:53.503   821  1012 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 100]
03-24 22:21:53.503   821  1012 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
,03-24 22:21:53.503   821  1012 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
03-24 22:21:53.503   821  1012 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
03-24 22:21:53.504   821  1012 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,03-24 22:21:53.504  1062  1567 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,03-24 22:21:53.555  1261  3421 I VacuumService: Vacuum at: now=1458854513555 tag=VacuumService
,03-24 22:21:53.574  1803  1818 W GmsBackupTransport: Unknown package in backup request: @pm@
,03-24 22:21:53.576  1803  1818 V GmsBackupTransport: starting performBackup for @pm@
,03-24 22:21:53.580  1803  1818 V GmsBackupTransport: performBackup done for @pm@
,03-24 22:21:53.597  1776  3415 E Auth.Api.Credentials: [CredentialSyncAdapter] Unknown sync event.
,03-24 22:21:53.619  1261  1261 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 22:21:53.643  1261  1280 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: android
03-24 22:21:53.643  1261  1280 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> android without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 22:21:53.643  1261  1280 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 22:21:53.643  1261  1280 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 22:21:53.653   821  1416 I ActivityManager: Start proc 3430:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,03-24 22:21:53.658  1261  1280 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 22:21:53.682  1776  3440 W DriveInitializer: Background init thread started
,03-24 22:21:53.686  1261  1280 W GLSActivity: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-24 22:21:53.686  1261  1280 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-24 22:21:53.686  1261  1280 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-24 22:21:53.686  1261  1280 W GLSActivity: 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
03-24 22:21:53.686  1261  1280 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
03-24 22:21:53.686  1261  1280 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
03-24 22:21:53.686  1261  1280 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:446)
,03-24 22:21:53.703  1803  2137 W GmsBackupTransport: Error sending final backup to server: 
03-24 22:21:53.703  1803  2137 W GmsBackupTransport: com.google.android.gms.backup.d.d: Can not get client auth token
03-24 22:21:53.703  1803  2137 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:1080)
03-24 22:21:53.703  1803  2137 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:65)
03-24 22:21:53.703  1803  2137 W GmsBackupTransport: 	at com.google.android.gms.backup.aa.finishBackup(SourceFile:409)
03-24 22:21:53.703  1803  2137 W GmsBackupTransport: 	at android.app.backup.BackupTransport$TransportImpl.finishBackup(BackupTransport.java:547)
03-24 22:21:53.703  1803  2137 W GmsBackupTransport: 	at com.android.internal.backup.IBackupTransport$Stub.onTransact(IBackupTransport.java:162)
03-24 22:21:53.703  1803  2137 W GmsBackupTransport: 	at android.os.Binder.execTransact(Binder.java:446)
03-24 22:21:53.703  1803  2137 W GmsBackupTransport: Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
03-24 22:21:53.703  1803  2137 W GmsBackupTransport: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
03-24 22:21:53.703  1803  2137 W GmsBackupTransport: 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
03-24 22:21:53.703  1803  2137 W GmsBackupTransport: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
03-24 22:21:53.703  1803  2137 W GmsBackupTransport: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
03-24 22:21:53.703  1803  2137 W GmsBackupTransport: 	... 1 more
,03-24 22:21:53.705   821  1041 D BackupManagerService: Now staging backup of com.google.android.talk
,03-24 22:21:53.713   821  1041 D BackupManagerService: Now staging backup of com.google.android.dialer
,03-24 22:21:53.716  3430  3430 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,03-24 22:21:53.719   821  1041 D BackupManagerService: Now staging backup of com.android.providers.settings
,03-24 22:21:53.724  3430  3430 D SprintDMHelper: simOperator:  IMSI: null
03-24 22:21:53.724  3430  3430 D SprintDMReceiver: Not Sprint UICC, don't do anything.
03-24 22:21:53.726   821  1041 D BackupManagerService: Now staging backup of com.android.sharedstoragebackup
,03-24 22:21:53.727  1776  1776 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,03-24 22:21:53.732  1776  1776 D SystemUpdateService: onCreate
,03-24 22:21:53.733   821  1041 D BackupManagerService: Now staging backup of com.google.android.gm
03-24 22:21:53.733  1776  3442 W DriveInitializer: Awaiting to be initialized
,03-24 22:21:53.735  1776  1776 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,03-24 22:21:53.739   821  1041 D BackupManagerService: Now staging backup of com.android.providers.userdictionary
,03-24 22:21:53.743   821  1041 D BackupManagerService: Now staging backup of com.android.nfc
,03-24 22:21:53.753   821  1041 D BackupManagerService: Now staging backup of com.google.android.apps.genie.geniewidget
,03-24 22:21:53.758   821  1041 D BackupManagerService: Now staging backup of com.google.android.marvin.talkback
,03-24 22:21:53.760   821  1041 D BackupManagerService: Now staging backup of com.google.android.inputmethod.latin
,03-24 22:21:53.763   821  1041 D BackupManagerService: Now staging backup of com.google.android.calendar
,03-24 22:21:53.765  1776  3451 I SystemUpdateService: active receiver: enabled
,03-24 22:21:53.767   821  1041 D BackupManagerService: Now staging backup of com.android.vending
,03-24 22:21:53.771   821  1041 D BackupManagerService: Now staging backup of android
,03-24 22:21:53.773  1776  3451 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,03-24 22:21:53.774   821  1041 D BackupManagerService: Now staging backup of com.google.android.googlequicksearchbox
,03-24 22:21:53.775  1261  1869 I art     : Explicit concurrent mark sweep GC freed 23781(1349KB) AllocSpace objects, 0(0B) LOS objects, 38% free, 26MB/42MB, paused 1.052ms total 24.458ms
,03-24 22:21:53.782  1803  1818 I GmsBackupTransport: Next backup will happen in 43199907 millis.
,03-24 22:21:53.785  1776  3451 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]; metered: false; mobile allowed: true
03-24 22:21:53.785  1776  3451 I SystemUpdateService: now status is 0 (complete)
,03-24 22:21:53.786  1776  3451 I SystemUpdateService: processDownloadedFile /data/data/com.google.android.gms/app_download/update.zip
03-24 22:21:53.786  1776  3451 I SystemUpdateService: file has been verified
03-24 22:21:53.786  1776  3451 I SystemUpdateService: OTA package size = 25802302
,03-24 22:21:53.792  1261  3458 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-24 22:21:53.792  1261  3458 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 22:21:53.792  1261  3458 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 22:21:53.792  1261  3458 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 22:21:53.798  1261  3458 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 22:21:53.800  1776  3451 I SystemUpdateService: showing system update notification
,03-24 22:21:53.804   821  1041 I BackupManagerService: Backup pass finished.
,03-24 22:21:53.813  3113  3419 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
03-24 22:21:53.813  3113  3419 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-24 22:21:53.813  3113  3419 E HttpOperation: 	at jdm.a(PG:82)
03-24 22:21:53.813  3113  3419 E HttpOperation: 	at jcs.o(PG:406)
03-24 22:21:53.813  3113  3419 E HttpOperation: 	at jcn.a(PG:1379)
03-24 22:21:53.813  3113  3419 E HttpOperation: 	at jcs.i(PG:143)
03-24 22:21:53.813  3113  3419 E HttpOperation: 	at blb.a(PG:3937)
03-24 22:21:53.813  3113  3419 E HttpOperation: 	at czp.a(PG:18188)
03-24 22:21:53.813  3113  3419 E HttpOperation: 	at czp.a(PG:9081)
03-24 22:21:53.813  3113  3419 E HttpOperation: 	at czq.run(PG:1686)
03-24 22:21:53.813  3113  3419 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-24 22:21:53.813  3113  3419 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 22:21:53.813  3113  3419 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 22:21:53.813  3113  3419 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 22:21:53.813  3113  3419 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-24 22:21:53.813  3113  3419 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-24 22:21:53.813  3113  3419 E HttpOperation: 	at jdj.a(PG:4091)
03-24 22:21:53.813  3113  3419 E HttpOperation: 	at jdj.a(PG:1125)
03-24 22:21:53.813  3113  3419 E HttpOperation: 	at jdm.a(PG:77)
03-24 22:21:53.813  3113  3419 E HttpOperation: 	... 12 more
03-24 22:21:53.813  3113  3419 E HttpOperation: Caused by: faj: BadAuthentication
03-24 22:21:53.813  3113  3419 E HttpOperation: 	at fal.a(PG:38)
03-24 22:21:53.813  3113  3419 E HttpOperation: 	at jdj.a(PG:4089)
03-24 22:21:53.813  3113  3419 E HttpOperation: 	... 14 more
,03-24 22:21:53.817  3394  3439 V GoogleAuthProtoRequest: [340] a.<init>: mAccountName set to: thalitester@gmail.com
03-24 22:21:53.827  1776  3440 W DriveInitializer: Background init thread ended
03-24 22:21:53.840   821   821 I ValidateNoPeople: skipping global notification
,03-24 22:21:53.851  1261  2597 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-24 22:21:53.851  1261  2597 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 22:21:53.851  1261  2597 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 22:21:53.851  1261  2597 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 22:21:53.853  1261  2597 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 22:21:53.862  3113  3419 E HttpOperation: [getmobileexperiments] Unexpected exception
03-24 22:21:53.862  3113  3419 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-24 22:21:53.862  3113  3419 E HttpOperation: 	at jdm.a(PG:82)
03-24 22:21:53.862  3113  3419 E HttpOperation: 	at jcs.o(PG:406)
03-24 22:21:53.862  3113  3419 E HttpOperation: 	at jcn.a(PG:1379)
03-24 22:21:53.862  3113  3419 E HttpOperation: 	at jcs.i(PG:143)
03-24 22:21:53.862  3113  3419 E HttpOperation: 	at hec.a(PG:42)
03-24 22:21:53.862  3113  3419 E HttpOperation: 	at hee.a(PG:102)
03-24 22:21:53.862  3113  3419 E HttpOperation: 	at czr.a(PG:65)
03-24 22:21:53.862  3113  3419 E HttpOperation: 	at kka.a(PG:108)
03-24 22:21:53.862  3113  3419 E HttpOperation: 	at czp.a(PG:19176)
03-24 22:21:53.862  3113  3419 E HttpOperation: 	at czp.a(PG:9081)
03-24 22:21:53.862  3113  3419 E HttpOperation: 	at czq.run(PG:1686)
03-24 22:21:53.862  3113  3419 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-24 22:21:53.862  3113  3419 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 22:21:53.862  3113  3419 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 22:21:53.862  3113  3419 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 22:21:53.862  3113  3419 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-24 22:21:53.862  3113  3419 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-24 22:21:53.862  3113  3419 E HttpOperation: 	at jdj.a(PG:4091)
03-24 22:21:53.862  3113  3419 E HttpOperation: 	at jdj.a(PG:1125)
03-24 22:21:53.862  3113  3419 E HttpOperation: 	at jdm.a(PG:77)
03-24 22:21:53.862  3113  3419 E HttpOperation: 	... 15 more
03-24 22:21:53.862  3113  3419 E HttpOperation: Caused by: faj: BadAuthentication
03-24 22:21:53.862  3113  3419 E HttpOperation: 	at fal.a(PG:38)
03-24 22:21:53.862  3113  3419 E HttpOperation: 	at jdj.a(PG:4089)
03-24 22:21:53.862  3113  3419 E HttpOperation: 	... 17 more
03-24 22:21:53.863  3113  3419 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
03-24 22:21:53.863  3113  3419 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
03-24 22:21:53.863  3113  3419 E ExperimentLoader: 	at jdm.a(PG:82)
03-24 22:21:53.863  3113  3419 E ExperimentLoader: 	at jcs.o(PG:406)
03-24 22:21:53.863  3113  3419 E ExperimentLoader: 	at jcn.a(PG:1379)
03-24 22:21:53.863  3113  3419 E ExperimentLoader: 	at jcs.i(PG:143)
03-24 22:21:53.863  3113  3419 E ExperimentLoader: 	at hec.a(PG:42)
03-24 22:21:53.863  3113  3419 E ExperimentLoader: 	at hee.a(PG:102)
03-24 22:21:53.863  3113  3419 E ExperimentLoader: 	at czr.a(PG:65)
03-24 22:21:53.863  3113  3419 E ExperimentLoader: 	at kka.a(PG:108)
03-24 22:21:53.863  3113  3419 E ExperimentLoader: 	at czp.a(PG:19176)
03-24 22:21:53.863  3113  3419 E ExperimentLoader: 	at czp.a(PG:9081)
03-24 22:21:53.863  3113  3419 E ExperimentLoader: 	at czq.run(PG:1686)
03-24 22:21:53.863  3113  3419 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-24 22:21:53.863  3113  3419 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 22:21:53.863  3113  3419 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 22:21:53.863  3113  3419 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 22:21:53.863  3113  3419 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
03-24 22:21:53.863  3113  3419 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-24 22:21:53.863  3113  3419 E ExperimentLoader: 	at jdj.a(PG:4091)
03-24 22:21:53.863  3113  3419 E ExperimentLoader: 	at jdj.a(PG:1,125)
03-24 22:21:53.863  3113  3419 E ExperimentLoader: 	at jdm.a(PG:77)
03-24 22:21:53.863  3113  3419 E ExperimentLoader: 	... 15 more
03-24 22:21:53.863  3113  3419 E ExperimentLoader: Caused by: faj: BadAuthentication
03-24 22:21:53.863  3113  3419 E ExperimentLoader: 	at fal.a(PG:38)
03-24 22:21:53.863  3113  3419 E ExperimentLoader: 	at jdj.a(PG:4089)
03-24 22:21:53.863  3113  3419 E ExperimentLoader: 	... 17 more
03-24 22:21:53.876  1261  1723 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
03-24 22:21:53.876  1261  1723 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 22:21:53.876  1261  1723 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 22:21:53.876  1261  1723 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
03-24 22:21:53.879  1261  1723 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 22:21:53.905  3394  3439 W ExperimentUpdateService: [340] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,03-24 22:21:53.906  3394  3439 W ExperimentUpdateService: [340] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-24 22:21:53.906  3394  3439 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-24 22:21:53.906  3394  3439 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-24 22:21:53.906  3394  3439 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-24 22:21:53.906  3394  3439 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-24 22:21:53.906  3394  3439 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-24 22:21:53.906  3394  3439 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-24 22:21:53.906  3394  3439 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-24 22:21:53.906  3394  3439 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-24 22:21:53.906  3394  3439 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-24 22:21:53.906  3394  3439 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-24 22:21:53.951  1776  3474 I iu.SyncManager: SYNC; picasa accounts
,03-24 22:21:53.959  1776  1776 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,03-24 22:21:53.961  1776  1776 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,03-24 22:21:53.968  1261  3475 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,03-24 22:21:53.974  1776  3474 I iu.UploadsManager: num queued entries: 0
03-24 22:21:53.974  1776  3474 I iu.UploadsManager: num updated entries: 0
03-24 22:21:53.975  1776  3474 I iu.SyncManager: NEXT; no task
,03-24 22:21:53.977  1776  1776 D SystemUpdateService: onDestroy
,03-24 22:21:53.979  1261  3475 W Uploader: No account for auth token provided
,03-24 22:21:53.983   821  1370 I ActivityManager: Killing 2927:com.android.settings/1000 (adj 15): empty #17
,03-24 22:21:53.983  1776  1776 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,03-24 22:21:53.984  1776  1776 I Kids    : [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
03-24 22:21:53.987   821   854 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 37497, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,03-24 22:21:54.073   821  1082 I ActivityManager: Start proc 3482:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,03-24 22:21:54.145   821   854 I ActivityManager: Start proc 3499:com.google.android.keep/u0a79 for service com.google.android.keep/.syncadapter.KeepSyncAdapterService
,03-24 22:21:54.199  3282  3339 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
03-24 22:21:54.199  3282  3339 I jxcore-log: 
,03-24 22:21:54.206   821   854 I ActivityManager: Start proc 3520:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,03-24 22:21:54.229  3482  3482 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
03-24 22:21:54.229  3482  3482 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-24 22:21:54.229  3482  3482 I GAv4    :   adb logcat -s GAv4
,03-24 22:21:54.241  3482  3482 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,03-24 22:21:54.249  3482  3482 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,03-24 22:21:54.264  3482  3543 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,03-24 22:21:54.383  3161  3479 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,03-24 22:21:54.384   821  1414 I ActivityManager: Killing 2443:com.google.android.apps.maps/u0a65 (adj 15): empty #17
,03-24 22:21:54.388   821  1393 I art     : Explicit concurrent mark sweep GC freed 57068(2MB) AllocSpace objects, 8(168KB) LOS objects, 32% free, 33MB/49MB, paused 1.333ms total 55.204ms
,03-24 22:21:54.476  1261  3532 D GCM     : Connected
,03-24 22:21:54.509  1261  3532 D GCM     : Message class com.google.f.a.a.p
,03-24 22:21:54.538  3482  3482 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,03-24 22:21:54.547  3482  3482 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 8333-8334)
03-24 22:21:54.547  3482  3482 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-24 22:21:54.548  3499  3562 V KeepSync: Connecting to GoogleApiClient
,03-24 22:21:54.551  3482  3482 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {12c836d2}
03-24 22:21:54.551  3482  3482 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-24 22:21:54.551  3482  3482 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,03-24 22:21:54.565  3482  3482 I BrowserStartupController: Initializing chromium process, singleProcess=true
,03-24 22:21:54.566  3482  3482 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-24 22:21:54.570  3482  3482 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-24 22:21:54.584  3482  3482 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,03-24 22:21:54.589  3482  3482 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-24 22:21:54.589  3482  3482 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-24 22:21:54.589  3482  3482 I Adreno  : EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,03-24 22:21:54.603  1776  3565 W BaseAppContext: Using Auth Proxy for data requests.
,03-24 22:21:54.617  1261  3475 W Uploader: No account for auth token provided
,03-24 22:21:54.623  1776  3565 W BaseAppContext: Using Auth Proxy for data requests.
,03-24 22:21:54.650  1261  2597 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,03-24 22:21:54.650  1261  2597 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 22:21:54.651  1261  2597 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 22:21:54.651  1261  2597 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 22:21:54.654  1261  2597 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 22:21:54.663  3482  3579 W AudioManagerAndroid: Requires BLUETOOTH permission
,03-24 22:21:54.667  3482  3482 I NSApplication: Starting up...
,03-24 22:21:54.686  3282  3339 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
03-24 22:21:54.686  3282  3339 I jxcore-log: 
,03-24 22:21:54.689   821  1328 I ActivityManager: Start proc 3585:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,03-24 22:21:54.690  1261  3459 I art     : Explicit concurrent mark sweep GC freed 24976(1425KB) AllocSpace objects, 7(417KB) LOS objects, 38% free, 26MB/42MB, paused 951us total 33.395ms
,03-24 22:21:54.708  3282  3339 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
03-24 22:21:54.708  3282  3339 I jxcore-log: 
,03-24 22:21:54.712  1776  3565 E ClientConnectionOperation: Handling authorization failure
03-24 22:21:54.712  1776  3565 E ClientConnectionOperation: com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
03-24 22:21:54.712  1776  3565 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
03-24 22:21:54.712  1776  3565 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
03-24 22:21:54.712  1776  3565 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
03-24 22:21:54.712  1776  3565 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
03-24 22:21:54.712  1776  3565 E ClientConnectionOperation: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-24 22:21:54.712  1776  3565 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 22:21:54.712  1776  3565 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 22:21:54.712  1776  3565 E ClientConnectionOperation: 	at java.lang.Thread.run(Thread.java:818)
03-24 22:21:54.712  1776  3565 E ClientConnectionOperation: Caused by: com.google.android.gms.auth.ad: BadAuthentication
03-24 22:21:54.712  1776  3565 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.b(SourceFile:442)
03-24 22:21:54.712  1776  3565 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:365)
03-24 22:21:54.712  1776  3565 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:310)
03-24 22:21:54.712  1776  3565 E ClientConnectionOperation: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
03-24 22:21:54.712  1776  3565 E ClientConnectionOperation: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
03-24 22:21:54.712  1776  3565 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:30)
03-24 22:21:54.712  1776  3565 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:370)
03-24 22:21:54.712  1776  3565 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:340)
03-24 22:21:54.712  1776  3565 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:319)
03-24 22:21:54.712  1776  3565 E ClientConnectionOperation: 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
03-24 22:21:54.712  1776  3565 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
03-24 22:21:54.712  1776  3565 E ClientConnectionOperation: 	... 7 more
,03-24 22:21:54.714  3282  3339 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
03-24 22:21:54.714  3282  3339 I jxcore-log: 
,03-24 22:21:54.717  3499  3562 V KeepSync: GoogleApiClient failed to connect with error code: 4
,03-24 22:21:54.722  3499  3562 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-24 22:21:54.728  3499  3562 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
03-24 22:21:54.728  3499  3562 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-24 22:21:54.751  3520  3520 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,03-24 22:21:54.758  3520  3520 I BooksApp: Created application version: 3.6.8 (30608)
,03-24 22:21:54.770  3282  3339 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
03-24 22:21:54.770  3282  3339 I jxcore-log: 
,03-24 22:21:54.771  1261  3475 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,03-24 22:21:54.772  1261  3475 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-24 22:21:54.772  1261  3475 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 22:21:54.772  1261  3475 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
03-24 22:21:54.775  1261  3475 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 22:21:54.789  3282  3339 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
03-24 22:21:54.789  3282  3339 I jxcore-log: 
,03-24 22:21:54.794  3282  3339 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
03-24 22:21:54.794  3282  3339 I jxcore-log: 
,03-24 22:21:54.797  1261  3475 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-24 22:21:54.797  1261  3475 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-24 22:21:54.797  1261  3475 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-24 22:21:54.797  1261  3475 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-24 22:21:54.797  1261  3475 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-24 22:21:54.797  1261  3475 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-24 22:21:54.797  1261  3475 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-24 22:21:54.797  1261  3475 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-24 22:21:54.797  1261  3475 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-24 22:21:54.797  1261  3475 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-24 22:21:54.797  1261  3475 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-24 22:21:54.797  1261  3475 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-24 22:21:54.797  1261  3475 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-24 22:21:54.812  3520  3608 I BooksSync: Starting books sync for 61035162, extras: ade
,03-24 22:21:54.868  1261  3460 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
03-24 22:21:54.868  1261  3460 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 22:21:54.868  1261  3460 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 22:21:54.868  1261  3460 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 22:21:54.872  1261  3460 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 22:21:54.909  1261  3475 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
03-24 22:21:54.909  1261  3475 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 22:21:54.909  1261  3475 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 22:21:54.909  1261  3475 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 22:21:54.917  1261  3475 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 22:21:54.925  3499  3562 E KeepSync: IOException
03-24 22:21:54.925  3499  3562 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
03-24 22:21:54.925  3499  3562 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
03-24 22:21:54.925  3499  3562 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
03-24 22:21:54.925  3499  3562 E KeepSync: 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
03-24 22:21:54.925  3499  3562 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
03-24 22:21:54.925  3499  3562 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
03-24 22:21:54.925  3499  3562 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
03-24 22:21:54.925  3499  3562 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
03-24 22:21:54.925  3499  3562 E KeepSync: 	at com.google.android.keep.util.m.a(SourceFile:207)
03-24 22:21:54.925  3499  3562 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
03-24 22:21:54.925  3499  3562 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
03-24 22:21:54.925  3499  3562 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
03-24 22:21:54.925  3499  3562 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
03-24 22:21:54.925  3499  3562 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
03-24 22:21:54.925  3499  3562 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
03-24 22:21:54.925  3499  3562 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
03-24 22:21:54.925  3499  3562 E KeepSync: 	... 10 more
03-24 22:21:54.925  3499  3562 W KeepSync: Sync result 2
,03-24 22:21:54.930   821   854 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 37504, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
03-24 22:21:54.931   821   836 I ActivityManager: Killing 3020:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,03-24 22:21:54.946  1261  3475 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-24 22:21:54.946  1261  3475 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-24 22:21:54.946  1261  3475 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-24 22:21:54.946  1261  3475 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-24 22:21:54.946  1261  3475 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-24 22:21:54.946  1261  3475 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-24 22:21:54.946  1261  3475 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-24 22:21:54.946  1261  3475 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-24 22:21:54.946  1261  3475 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-24 22:21:54.946  1261  3475 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-24 22:21:54.946  1261  3475 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-24 22:21:54.946  1261  3475 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-24 22:21:54.946  1261  3475 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-24 22:21:55.011  3520  3617 I BooksConfig: GmsCore Version = 7.8.99 (2134222-430)
,03-24 22:21:55.172  1261  3475 W Uploader: No account for auth token provided
,03-24 22:21:55.181  1261  1869 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-24 22:21:55.181  1261  1869 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 22:21:55.181  1261  1869 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 22:21:55.181  1261  1869 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 22:21:55.186  1261  1869 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 22:21:55.241  1261  1280 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-24 22:21:55.241  1261  1280 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 22:21:55.241  1261  1280 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 22:21:55.241  1261  1280 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 22:21:55.252   821  1370 I ActivityManager: Start proc 3622:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,03-24 22:21:55.253   821  1370 I ActivityManager: Killing 3041:com.android.musicfx/u0a18 (adj 15): empty #17
,03-24 22:21:55.474  1261  1280 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 22:21:55.494  1261  3475 W Uploader: No account for auth token provided
,03-24 22:21:55.505  3520  3617 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,03-24 22:21:55.506  3520  3608 E BooksSync: Soft error
03-24 22:21:55.506  3520  3608 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-24 22:21:55.506  3520  3608 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-24 22:21:55.506  3520  3608 E BooksSync: Sync error
03-24 22:21:55.506  3520  3608 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-24 22:21:55.506  3520  3608 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-24 22:21:55.506  3520  3608 I BooksSync: Finished books sync
,03-24 22:21:55.516   821  1416 I ActivityManager: Killing 2460:android.process.acore/u0a5 (adj 15): empty #17
,03-24 22:21:55.517   821   854 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 37504, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-24 22:21:55.621   821  1416 I ActivityManager: Killing 3070:com.google.android.apps.docs/u0a46 (adj 15): empty #18
,03-24 22:21:55.750  1261  3475 W Uploader: No account for auth token provided
,03-24 22:21:55.934  1261  3475 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
03-24 22:21:55.934  1261  3475 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-24 22:21:55.934  1261  3475 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 22:21:55.934  1261  3475 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 22:21:55.945  1261  3475 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 22:21:55.994  1261  3475 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-24 22:21:55.994  1261  3475 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-24 22:21:55.994  1261  3475 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-24 22:21:55.994  1261  3475 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-24 22:21:55.994  1261  3475 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-24 22:21:55.994  1261  3475 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-24 22:21:55.994  1261  3475 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-24 22:21:55.994  1261  3475 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-24 22:21:55.994  1261  3475 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-24 22:21:55.994  1261  3475 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-24 22:21:55.994  1261  3475 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-24 22:21:55.994  1261  3475 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-24 22:21:55.994  1261  3475 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-24 22:21:56.104  1261  3475 W Uploader: No account for auth token provided,
,03-24 22:21:56.225  1261  3475 W Uploader: No account for auth token provided
,03-24 22:21:56.291   821  1375 I ActivityManager: Killing 2825:com.google.android.gm/u0a78 (adj 15): empty #17
,03-24 22:21:56.432  1261  3475 W Uploader: No account for auth token provided
,03-24 22:21:56.459   821  1393 I ActivityManager: Start proc 3640:com.qualcomm.timeservice/1000 for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver
,03-24 22:21:56.496  3640  3640 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1458854516496
03-24 22:21:56.496  3640  3640 D         : TimeServiceNative: User Time to be set is 1458854516496
03-24 22:21:56.496  3640  3640 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
03-24 22:21:56.496  3640  3640 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
03-24 22:21:56.496  3640  3640 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1458854516496
03-24 22:21:56.496  3640  3640 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
03-24 22:21:56.496   371   881 D QC-time-services: Daemon: Connection accepted:time_genoff
03-24 22:21:56.497   371  3657 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1458854516496
03-24 22:21:56.497   371  3657 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1458854516496, operation = 0
03-24 22:21:56.497   371  3657 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS7/10/70 17:33:39
,03-24 22:21:56.497   371  3657 D QC-time-services: Daemon:Value read from RTC seconds = 19157619000
03-24 22:21:56.497   371  3657 D QC-time-services: Daemon:new time 1458854516496 
03-24 22:21:56.497   371  3657 D QC-time-services: Daemon: delta 1439696897496 genoff 1439696897496 
03-24 22:21:56.497   371  3657 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1439696897496 to memory
03-24 22:21:56.497   371  3657 D QC-time-services: Daemon:Opening File: /data/time/ats_2
03-24 22:21:56.497   371  3657 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,03-24 22:21:56.499   371  3657 D QC-time-services: Updating the TOD offset
,03-24 22:21:56.499   371  3657 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1439696897496 to memory
03-24 22:21:56.499   371  3657 D QC-time-services: Daemon:Opening File: /data/time/ats_1
03-24 22:21:56.499   371  3657 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,03-24 22:21:56.502   371  3657 E QC-time-services: Daemon:Update to modem bit set,
03-24 22:21:56.502  3640  3640 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
03-24 22:21:56.502   371  3657 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
03-24 22:21:56.502   371  3657 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1142889716496
,03-24 22:21:56.553  1261  3475 W Uploader: No account for auth token provided,
,03-24 22:21:56.570   371   881 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,03-24 22:21:56.576   371   876 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,03-24 22:21:56.662   821  1375 I art     : Explicit concurrent mark sweep GC freed 22462(993KB) AllocSpace objects, 2(32KB) LOS objects, 31% free, 34MB/50MB, paused 1.380ms total 79.564ms
,03-24 22:21:56.685  1261  3475 W Uploader:  no longer exists, so no auth token.
,03-24 22:21:56.692   821  1414 I ActivityManager: Start proc 3659:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver
,03-24 22:21:56.704   821  1328 I ActivityManager: Killing 1844:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,03-24 22:21:56.826  3659  3659 I GAv4    : Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
03-24 22:21:56.826  3659  3659 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-24 22:21:56.826  3659  3659 I GAv4    :   adb logcat -s GAv4
,03-24 22:21:56.848  3659  3659 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,03-24 22:21:56.863  3659  3659 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,03-24 22:21:56.868  1261  3475 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,03-24 22:21:56.869  1261  3475 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-24 22:21:56.869  1261  3475 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 22:21:56.869  1261  3475 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 22:21:56.876  1261  3475 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 22:21:56.880  3659  3679 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,03-24 22:21:56.902  1261  3475 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-24 22:21:56.902  1261  3475 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-24 22:21:56.902  1261  3475 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-24 22:21:56.902  1261  3475 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-24 22:21:56.902  1261  3475 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-24 22:21:56.902  1261  3475 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-24 22:21:56.902  1261  3475 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-24 22:21:56.902  1261  3475 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-24 22:21:56.902  1261  3475 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-24 22:21:56.902  1261  3475 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-24 22:21:56.902  1261  3475 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-24 22:21:56.902  1261  3475 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-24 22:21:56.902  1261  3475 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-24 22:21:56.920   821  1370 I ActivityManager: Killing 3140:com.android.providers.calendar/u0a3 (adj 15): empty #17
,03-24 22:21:57.022  3282  3339 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
03-24 22:21:57.022  3282  3339 I jxcore-log: 
,03-24 22:21:57.038  1261  3475 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
03-24 22:21:57.038  1261  3475 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 22:21:57.038  1261  3475 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 22:21:57.038  1261  3475 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 22:21:57.041  3282  3339 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
03-24 22:21:57.041  3282  3339 I jxcore-log: 
,03-24 22:21:57.044  1261  3475 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 22:21:57.052  3282  3339 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
03-24 22:21:57.052  3282  3339 I jxcore-log: 
,03-24 22:21:57.077  1776  1776 V Herrevad: NQAS connected
,03-24 22:21:57.094  1261  3475 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-24 22:21:57.094  1261  3475 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-24 22:21:57.094  1261  3475 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-24 22:21:57.094  1261  3475 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-24 22:21:57.094  1261  3475 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-24 22:21:57.094  1261  3475 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-24 22:21:57.094  1261  3475 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-24 22:21:57.094  1261  3475 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-24 22:21:57.094  1261  3475 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-24 22:21:57.094  1261  3475 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-24 22:21:57.094  1261  3475 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-24 22:21:57.094  1261  3475 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-24 22:21:57.094  1261  3475 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-24 22:21:57.096  3161  3161 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-24 22:21:57.096  3161  3161 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-24 22:21:57.127  1776  3683 I art     : Explicit concurrent mark sweep GC freed 15581(1204KB) AllocSpace objects, 18(288KB) LOS objects, 35% free, 28MB/44MB, paused 1.109ms total 41.403ms
,03-24 22:21:57.154   821  1082 I ActivityManager: Start proc 3689:com.android.providers.calendar/u0a3 for content provider com.android.providers.calendar/.CalendarProvider2
,03-24 22:21:57.162   821  1011 D WifiService: New client listening to asynchronous messages
,03-24 22:21:57.213  3689  3689 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,03-24 22:21:57.232  3282  3339 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
03-24 22:21:57.232  3282  3339 I jxcore-log: 
,03-24 22:21:57.279  3689  3689 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@1807b35e(com.android.providers.calendar.CalendarProvider2@2ca2333f)
,03-24 22:21:57.296  1261  3458 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
03-24 22:21:57.296  1261  3458 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 22:21:57.296  1261  3458 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 22:21:57.296  1261  3458 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 22:21:57.300  1261  3458 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 22:21:57.306  3282  3339 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
03-24 22:21:57.306  3282  3339 I jxcore-log: 
,03-24 22:21:57.334  3161  3685 E Babel   : UserRecoverableAuthException.
03-24 22:21:57.334  3161  3685 E Babel   : eei: BadAuthentication
03-24 22:21:57.334  3161  3685 E Babel   : 	at eeg.a(Unknown Source)
03-24 22:21:57.334  3161  3685 E Babel   : 	at eeg.a(Unknown Source)
03-24 22:21:57.334  3161  3685 E Babel   : 	at eeg.a(Unknown Source)
03-24 22:21:57.334  3161  3685 E Babel   : 	at g.a(Unknown Source)
03-24 22:21:57.334  3161  3685 E Babel   : 	at cae.a(SourceFile:3089)
03-24 22:21:57.334  3161  3685 E Babel   : 	at cae.a(SourceFile:1131)
03-24 22:21:57.334  3161  3685 E Babel   : 	at cws.a(SourceFile:4333)
03-24 22:21:57.334  3161  3685 E Babel   : 	at cws.a(SourceFile:1419)
03-24 22:21:57.334  3161  3685 E Babel   : 	at crl.a(SourceFile:492)
03-24 22:21:57.334  3161  3685 E Babel   : 	at crl.a(SourceFile:1468)
03-24 22:21:57.334  3161  3685 E Babel   : 	at cqu.a(SourceFile:4416)
03-24 22:21:57.334  3161  3685 E Babel   : 	at cas.b(SourceFile:106)
03-24 22:21:57.334  3161  3685 E Babel   : 	at cap.d(SourceFile:335)
03-24 22:21:57.334  3161  3685 E Babel   : 	at caq.run(SourceFile:81)
03-24 22:21:57.334  3161  3685 E Babel   : Error getting auth token
03-24 22:21:57.334  3161  3685 E Babel   : dvm
03-24 22:21:57.334  3161  3685 E Babel   : 	at g.a(Unknown Source)
03-24 22:21:57.334  3161  3685 E Babel   : 	at cae.a(SourceFile:3089)
03-24 22:21:57.334  3161  3685 E Babel   : 	at cae.a(SourceFile:1131)
03-24 22:21:57.334  3161  3685 E Babel   : 	at cws.a(SourceFile:4333)
03-24 22:21:57.334  3161  3685 E Babel   : 	at cws.a(SourceFile:1419)
03-24 22:21:57.334  3161  3685 E Babel   : 	at crl.a(SourceFile:492)
03-24 22:21:57.334  3161  3685 E Babel   : 	at crl.a(SourceFile:1468)
03-24 22:21:57.334  3161  3685 E Babel   : 	at cqu.a(SourceFile:4416)
03-24 22:21:57.334  3161  3685 E Babel   : 	at cas.b(SourceFile:106)
03-24 22:21:57.334  3161  3685 E Babel   : 	at cap.d(SourceFile:335)
03-24 22:21:57.334  3161  3685 E Babel   : 	at caq.run(SourceFile:81)
,03-24 22:21:57.337  3161  3685 E Babel   : Account registration failed 1-Redacted-21
,03-24 22:21:57.337  3161  3685 E Babel   : cyp: null -- null
03-24 22:21:57.337  3161  3685 E Babel   : 	at cae.a(SourceFile:3121)
03-24 22:21:57.337  3161  3685 E Babel   : 	at cae.a(SourceFile:1131)
03-24 22:21:57.337  3161  3685 E Babel   : 	at cws.a(SourceFile:4333)
03-24 22:21:57.337  3161  3685 E Babel   : 	at cws.a(SourceFile:1419)
03-24 22:21:57.337  3161  3685 E Babel   : 	at crl.a(SourceFile:492)
03-24 22:21:57.337  3161  3685 E Babel   : 	at crl.a(SourceFile:1468)
03-24 22:21:57.337  3161  3685 E Babel   : 	at cqu.a(SourceFile:4416)
03-24 22:21:57.337  3161  3685 E Babel   : 	at cas.b(SourceFile:106)
03-24 22:21:57.337  3161  3685 E Babel   : 	at cap.d(SourceFile:335)
03-24 22:21:57.337  3161  3685 E Babel   : 	at caq.run(SourceFile:81)
,03-24 22:21:57.343  3161  3685 I art     : Note: end time exceeds epoch: 
,03-24 22:21:57.360  1261  3459 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
03-24 22:21:57.360  1261  3459 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 22:21:57.360  1261  3459 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 22:21:57.360  1261  3459 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 22:21:57.362  3282  3339 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
03-24 22:21:57.362  3282  3339 I jxcore-log: 
,03-24 22:21:57.362  1261  3459 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 22:21:57.372  1261  3459 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-24 22:21:57.376  1261  1261 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 22:21:57.389  3161  3716 E Babel   : Unexpected exception while authenticating.
,03-24 22:21:57.389  3161  3716 E Babel   : eej: User intervention required. Notification has been pushed.
03-24 22:21:57.389  3161  3716 E Babel   : 	at eeg.b(Unknown Source)
03-24 22:21:57.389  3161  3716 E Babel   : 	at eeg.b(Unknown Source)
03-24 22:21:57.389  3161  3716 E Babel   : 	at g.a(Unknown Source)
03-24 22:21:57.389  3161  3716 E Babel   : 	at cae.b(SourceFile:1146)
03-24 22:21:57.389  3161  3716 E Babel   : 	at dcg.run(SourceFile:5617)
03-24 22:21:57.389  3161  3716 E Babel   : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 22:21:57.389  3161  3716 E Babel   : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 22:21:57.389  3161  3716 E Babel   : 	at java.lang.Thread.run(Thread.java:818)
,03-24 22:21:57.403  1261  3460 I art     : Explicit concurrent mark sweep GC freed 43092(2MB) AllocSpace objects, 1(33KB) LOS objects, 36% free, 28MB/44MB, paused 1.004ms total 22.769ms
,03-24 22:21:57.416  1261  3460 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
03-24 22:21:57.416  1261  3460 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 22:21:57.416  1261  3460 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 22:21:57.416  1261  3460 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 22:21:57.419  1261  3460 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 22:21:57.428  2764  2764 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,03-24 22:21:57.428  2764  2764 D Finsky  : [1] 5.onFinished: Installation state replication failed.
03-24 22:21:57.429  2764  2764 D Finsky  : [1] 5.onFinished: Giving up after 6 failures.
,03-24 22:21:57.502  3282  3339 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
03-24 22:21:57.502  3282  3339 I jxcore-log: 
,03-24 22:21:57.506  3282  3339 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
03-24 22:21:57.506  3282  3339 I jxcore-log: 
,03-24 22:21:57.511  3282  3339 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
03-24 22:21:57.511  3282  3339 I jxcore-log: 
,03-24 22:21:57.525  3282  3339 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,03-24 22:21:57.525  3282  3339 I jxcore-log: 
,03-24 22:21:57.543  3282  3339 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
03-24 22:21:57.543  3282  3339 I jxcore-log: 
,03-24 22:21:57.638  3282  3339 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
03-24 22:21:57.638  3282  3339 I jxcore-log: 
,03-24 22:21:57.643  3282  3339 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
03-24 22:21:57.643  3282  3339 I jxcore-log: 
,03-24 22:21:57.667  3282  3339 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
03-24 22:21:57.667  3282  3339 I jxcore-log: 
,03-24 22:21:57.719  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 22:21:57.719  3282  3339 I jxcore-log: 
,03-24 22:21:58.333  3689  3689 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
03-24 22:21:58.334  3689  3689 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,03-24 22:21:58.531  3689  3728 E SQLiteLog: (284) automatic index on view_events(_id)
,03-24 22:21:58.969  3282  3339 I jxcore-log: TAP version 13
03-24 22:21:58.969  3282  3339 I jxcore-log: 
,03-24 22:21:58.972  3282  3339 I jxcore-log: # setup
03-24 22:21:58.972  3282  3339 I jxcore-log: 
,03-24 22:21:59.200  3282  3339 I jxcore-log: # 1. calling createNativeListener directly rejects
03-24 22:21:59.200  3282  3339 I jxcore-log: 
,03-24 22:21:59.551  3282  3339 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 22:21:59.551  3282  3339 I jxcore-log: 
,03-24 22:21:59.556  3282  3339 I jxcore-log: DEBUG createNativeListener: listening 48669
03-24 22:21:59.556  3282  3339 I jxcore-log: 
,03-24 22:21:59.562  3282  3339 I jxcore-log: ok 1 Should throw
03-24 22:21:59.562  3282  3339 I jxcore-log: 
,03-24 22:21:59.564  3282  3339 I jxcore-log: # teardown
03-24 22:21:59.564  3282  3339 I jxcore-log: 
,03-24 22:21:59.755  3282  3339 I jxcore-log: # setup
03-24 22:21:59.755  3282  3339 I jxcore-log: 
,03-24 22:21:59.769  3520  3606 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,03-24 22:21:59.945  3282  3339 I jxcore-log: # 2. emits incomingConnectionState
03-24 22:21:59.945  3282  3339 I jxcore-log: 
,03-24 22:22:00.321  3282  3339 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 22:22:00.321  3282  3339 I jxcore-log: 
,03-24 22:22:00.327  3282  3339 I jxcore-log: DEBUG createNativeListener: listening 34354
03-24 22:22:00.327  3282  3339 I jxcore-log: 
,03-24 22:22:00.337  3282  3339 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 22:22:00.337  3282  3339 I jxcore-log: 
,03-24 22:22:00.340  3282  3339 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 22:22:00.340  3282  3339 I jxcore-log: 
,03-24 22:22:00.348  3282  3339 I jxcore-log: DEBUG createNativeListener: new mux
03-24 22:22:00.348  3282  3339 I jxcore-log: 
,03-24 22:22:00.353  3282  3339 I jxcore-log: ok 2 initial connection state should be CONNECTED
03-24 22:22:00.353  3282  3339 I jxcore-log: 
,03-24 22:22:00.371  3282  3339 I jxcore-log: DEBUG createNativeListener: incoming socket close,
03-24 22:22:00.371  3282  3339 I jxcore-log: 
03-24 22:22:00.372  3282  3339 I jxcore-log: ok 3 final connection state should be DISCONNECTED
03-24 22:22:00.372  3282  3339 I jxcore-log: 
,03-24 22:22:00.380  3282  3339 I jxcore-log: # teardown
03-24 22:22:00.380  3282  3339 I jxcore-log: 
,03-24 22:22:00.725  3282  3339 I jxcore-log: # setup
03-24 22:22:00.725  3282  3339 I jxcore-log: 
,03-24 22:22:01.097  3282  3339 I jxcore-log: # 3. emits routerPortConnectionFailed
03-24 22:22:01.097  3282  3339 I jxcore-log: 
,03-24 22:22:01.706  3282  3339 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 22:22:01.706  3282  3339 I jxcore-log: 
,03-24 22:22:01.709  3282  3339 I jxcore-log: DEBUG createNativeListener: listening 57447
,03-24 22:22:01.709  3282  3339 I jxcore-log: 
,03-24 22:22:01.717  3282  3339 I jxcore-log: DEBUG createNativeListener: new incoming socket
,03-24 22:22:01.717  3282  3339 I jxcore-log: 
,03-24 22:22:01.719  3282  3339 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 22:22:01.719  3282  3339 I jxcore-log: ,
,03-24 22:22:01.722  3282  3339 I jxcore-log: DEBUG createNativeListener: new mux
,03-24 22:22:01.722  3282  3339 I jxcore-log: 
,03-24 22:22:01.750  3282  3339 I jxcore-log: DEBUG createNativeListener: new stream: 
,03-24 22:22:01.750  3282  3339 I jxcore-log: 
,03-24 22:22:01.756  3282  3339 I jxcore-log: DEBUG createNativeListener: new outgoing socket
,03-24 22:22:01.756  3282  3339 I jxcore-log: 
,03-24 22:22:01.767  3282  3339 I jxcore-log: DEBUG createNativeListener: 
,03-24 22:22:01.767  3282  3339 I jxcore-log: 
,03-24 22:22:01.770  3282  3339 I jxcore-log: ok 4 tried to connect to right port,
03-24 22:22:01.770  3282  3339 I jxcore-log: 
,03-24 22:22:01.773  3282  3339 I jxcore-log: ok 5 failed due to refused connection
03-24 22:22:01.773  3282  3339 I jxcore-log: ,
,03-24 22:22:01.774  3282  3339 I jxcore-log: ok 6 routerPortConnectionFailed is emitted
03-24 22:22:01.774  3282  3339 I jxcore-log: 
,03-24 22:22:01.778  3282  3339 I jxcore-log: # teardown
03-24 22:22:01.778  3282  3339 I jxcore-log: 
03-24 22:22:01.781  3282  3339 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 22:22:01.781  3282  3339 I jxcore-log: 
,03-24 22:22:01.900  3282  3339 I jxcore-log: DEBUG createNativeListener: mux close
03-24 22:22:01.900  3282  3339 I jxcore-log: 
,03-24 22:22:01.905  3282  3339 I jxcore-log: # setup
03-24 22:22:01.905  3282  3339 I jxcore-log: 
,03-24 22:22:01.906  3282  3339 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 22:22:01.906  3282  3339 I jxcore-log: 
,03-24 22:22:02.514  3282  3339 I jxcore-log: # 4. native server connections all up
03-24 22:22:02.514  3282  3339 I jxcore-log: 
,03-24 22:22:02.711  3282  3339 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 22:22:02.711  3282  3339 I jxcore-log: 
,03-24 22:22:02.721  3282  3339 I jxcore-log: DEBUG createNativeListener: listening 35714
03-24 22:22:02.721  3282  3339 I jxcore-log: 
,03-24 22:22:02.730  3282  3339 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 22:22:02.730  3282  3339 I jxcore-log: 
,03-24 22:22:02.731  3282  3339 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 22:22:02.731  3282  3339 I jxcore-log: 
,03-24 22:22:02.733  3282  3339 I jxcore-log: DEBUG createNativeListener: new mux
03-24 22:22:02.733  3282  3339 I jxcore-log: 
,03-24 22:22:02.759  3282  3339 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 22:22:02.759  3282  3339 I jxcore-log: 
,03-24 22:22:02.763  3282  3339 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 22:22:02.763  3282  3339 I jxcore-log: 
,03-24 22:22:02.766  3282  3339 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 22:22:02.766  3282  3339 I jxcore-log: 
,03-24 22:22:02.768  3282  3339 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 22:22:02.768  3282  3339 I jxcore-log: 
,03-24 22:22:02.788  3282  3339 I jxcore-log: ok 7 Send/recvd #1 should be equal length
03-24 22:22:02.788  3282  3339 I jxcore-log: 
,03-24 22:22:02.788  3282  3339 I jxcore-log: ok 8 Send/recvd #1 should be same
03-24 22:22:02.788  3282  3339 I jxcore-log: 
,03-24 22:22:02.798  3282  3339 I jxcore-log: ok 9 Send/recvd #2 should be equal length
03-24 22:22:02.798  3282  3339 I jxcore-log: 
,03-24 22:22:02.799  3282  3339 I jxcore-log: ok 10 Send/recvd #2 should be same
03-24 22:22:02.799  3282  3339 I jxcore-log: 
,03-24 22:22:02.802  3282  3339 I jxcore-log: ok 11 Should be exactly 2 client sockets
03-24 22:22:02.802  3282  3339 I jxcore-log: 
,03-24 22:22:02.809  3282  3339 I jxcore-log: # teardown
03-24 22:22:02.809  3282  3339 I jxcore-log: 
,03-24 22:22:03.044  3282  3339 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 22:22:03.044  3282  3339 I jxcore-log: 
,03-24 22:22:03.047  3282  3339 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 22:22:03.047  3282  3339 I jxcore-log: 
,03-24 22:22:03.050  3282  3339 I jxcore-log: DEBUG createNativeListener: mux close
03-24 22:22:03.050  3282  3339 I jxcore-log: 
,03-24 22:22:03.054  3282  3339 I jxcore-log: # setup
03-24 22:22:03.054  3282  3339 I jxcore-log: 
,03-24 22:22:03.055  3282  3339 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 22:22:03.055  3282  3339 I jxcore-log: 
,03-24 22:22:03.340  2156  2221 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 22:22:03.530   821  1082 I ActivityManager: Killing 1510:com.google.android.googlequicksearchbox:search/u0a28 (adj 15): empty #17
,03-24 22:22:03.539  3282  3339 I jxcore-log: # 5. native server - closing incoming stream cleans outgoing socket
03-24 22:22:03.539  3282  3339 I jxcore-log: 
,03-24 22:22:03.593   821  1011 D WifiService: Client connection lost with reason: 4
,03-24 22:22:03.794  3282  3339 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 22:22:03.794  3282  3339 I jxcore-log: 
,03-24 22:22:03.804  3282  3339 I jxcore-log: DEBUG createNativeListener: listening 41707
03-24 22:22:03.804  3282  3339 I jxcore-log: 
,03-24 22:22:03.810  3282  3339 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 22:22:03.810  3282  3339 I jxcore-log: 
,03-24 22:22:03.812  3282  3339 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 22:22:03.812  3282  3339 I jxcore-log: 
,03-24 22:22:03.814  3282  3339 I jxcore-log: DEBUG createNativeListener: new mux
03-24 22:22:03.814  3282  3339 I jxcore-log: 
,03-24 22:22:03.827  3282  3339 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 22:22:03.827  3282  3339 I jxcore-log: 
,03-24 22:22:03.830  3282  3339 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 22:22:03.830  3282  3339 I jxcore-log: 
,03-24 22:22:03.844  3282  3339 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 22:22:03.844  3282  3339 I jxcore-log: 
,03-24 22:22:03.858  3282  3339 I jxcore-log: ok 12 socket shouldn't close until after stream
03-24 22:22:03.858  3282  3339 I jxcore-log: 
,03-24 22:22:03.859  3282  3339 I jxcore-log: ok 13 incoming remains open
03-24 22:22:03.859  3282  3339 I jxcore-log: 
,03-24 22:22:03.865  3282  3339 I jxcore-log: # teardown
03-24 22:22:03.865  3282  3339 I jxcore-log: 
,03-24 22:22:04.561  3282  3339 I jxcore-log: DEBUG createNativeListener: mux close
03-24 22:22:04.561  3282  3339 I jxcore-log: 
,03-24 22:22:04.569  3282  3339 I jxcore-log: # setup
03-24 22:22:04.569  3282  3339 I jxcore-log: 
,03-24 22:22:04.570  3282  3339 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 22:22:04.570  3282  3339 I jxcore-log: 
,03-24 22:22:04.708  3282  3339 I jxcore-log: # 6. native server - closing incoming connection cleans outgoing socket
03-24 22:22:04.708  3282  3339 I jxcore-log: 
,03-24 22:22:04.846  2764  2779 D Finsky  : [254] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,03-24 22:22:04.868  1261  1261 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 22:22:04.960  1261  1869 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
03-24 22:22:04.961  1261  1869 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 22:22:04.961  1261  1869 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 22:22:04.961  1261  1869 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 22:22:04.974  1261  1869 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 22:22:05.025  2764  2779 D Finsky  : [254] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,03-24 22:22:05.273  3282  3339 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 22:22:05.273  3282  3339 I jxcore-log: 
03-24 22:22:05.282  3282  3339 I jxcore-log: DEBUG createNativeListener: listening 34758
03-24 22:22:05.282  3282  3339 I jxcore-log: 
,03-24 22:22:05.290  3282  3339 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 22:22:05.290  3282  3339 I jxcore-log: 
03-24 22:22:05.291  3282  3339 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 22:22:05.291  3282  3339 I jxcore-log: 
,03-24 22:22:05.293  3282  3339 I jxcore-log: DEBUG createNativeListener: new mux
03-24 22:22:05.293  3282  3339 I jxcore-log: 
,03-24 22:22:05.303  3282  3339 I jxcore-log: ok 14 we should not have gotten an error
03-24 22:22:05.303  3282  3339 I jxcore-log: 
,03-24 22:22:05.308  3282  3339 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 22:22:05.308  3282  3339 I jxcore-log: 
,03-24 22:22:05.317  3282  3339 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 22:22:05.317  3282  3339 I jxcore-log: 
,03-24 22:22:05.344  3282  3339 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 22:22:05.344  3282  3339 I jxcore-log: 
,03-24 22:22:05.348  3282  3339 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 22:22:05.348  3282  3339 I jxcore-log: 
,03-24 22:22:05.356  3282  3339 I jxcore-log: ok 15 socket shouldn't close until after incoming
,03-24 22:22:05.356  3282  3339 I jxcore-log: 
03-24 22:22:05.357  3282  3339 I jxcore-log: ok 16 incoming is cleaned up
03-24 22:22:05.357  3282  3339 I jxcore-log: 
,03-24 22:22:05.365  3282  3339 I jxcore-log: # teardown
03-24 22:22:05.365  3282  3339 I jxcore-log: 
,03-24 22:22:05.507  3282  3339 I jxcore-log: # setup
03-24 22:22:05.507  3282  3339 I jxcore-log: 
,03-24 22:22:05.664  3282  3339 I jxcore-log: # 7. native server - closing outgoing socket cleans associated mux stream
03-24 22:22:05.664  3282  3339 I jxcore-log: 
,03-24 22:22:05.790  3282  3339 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 22:22:05.790  3282  3339 I jxcore-log: 
,03-24 22:22:05.798  3282  3339 I jxcore-log: DEBUG createNativeListener: listening 37701
03-24 22:22:05.798  3282  3339 I jxcore-log: 
,03-24 22:22:05.808  3282  3339 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 22:22:05.808  3282  3339 I jxcore-log: 
,03-24 22:22:05.809  3282  3339 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 22:22:05.809  3282  3339 I jxcore-log: 
03-24 22:22:05.812  3282  3339 I jxcore-log: DEBUG createNativeListener: new mux
03-24 22:22:05.812  3282  3339 I jxcore-log: 
,03-24 22:22:05.824  3282  3339 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 22:22:05.824  3282  3339 I jxcore-log: 
,03-24 22:22:05.827  3282  3339 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 22:22:05.827  3282  3339 I jxcore-log: 
,03-24 22:22:05.841  3282  3339 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 22:22:05.841  3282  3339 I jxcore-log: 
,03-24 22:22:05.851  3282  3339 I jxcore-log: ok 17 stream was closed
03-24 22:22:05.851  3282  3339 I jxcore-log: 
,03-24 22:22:05.851  3282  3339 I jxcore-log: ok 18 incoming should survive
03-24 22:22:05.851  3282  3339 I jxcore-log: 
03-24 22:22:05.852  3282  3339 I jxcore-log: ok 19 mux should have no streams
03-24 22:22:05.852  3282  3339 I jxcore-log: 
,03-24 22:22:05.868  3282  3339 I jxcore-log: # teardown
03-24 22:22:05.868  3282  3339 I jxcore-log: 
,03-24 22:22:05.986  3282  3339 I jxcore-log: DEBUG createNativeListener: mux close
03-24 22:22:05.986  3282  3339 I jxcore-log: 
,03-24 22:22:05.998  3282  3339 I jxcore-log: # setup
03-24 22:22:05.998  3282  3339 I jxcore-log: 
,03-24 22:22:05.999  3282  3339 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 22:22:05.999  3282  3339 I jxcore-log: 
,03-24 22:22:06.119  3282  3339 I jxcore-log: # 8. native server - closing the whole server cleans everything up
03-24 22:22:06.119  3282  3339 I jxcore-log: ,
,03-24 22:22:06.234  3282  3339 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 22:22:06.234  3282  3339 I jxcore-log: 
,03-24 22:22:06.238  3282  3339 I jxcore-log: DEBUG createNativeListener: listening 50365
03-24 22:22:06.238  3282  3339 I jxcore-log: 
,03-24 22:22:06.243  3282  3339 I jxcore-log: DEBUG createNativeListener: new incoming socket
,03-24 22:22:06.243  3282  3339 I jxcore-log: 
03-24 22:22:06.245  3282  3339 I jxcore-log: DEBUG createNativeListener: creating incoming mux
,03-24 22:22:06.245  3282  3339 I jxcore-log: 
03-24 22:22:06.247  3282  3339 I jxcore-log: DEBUG createNativeListener: new mux
03-24 22:22:06.247  3282  3339 I jxcore-log: 
,03-24 22:22:06.256  3282  3339 I jxcore-log: ok 20 we should not have gotten an error
03-24 22:22:06.256  3282  3339 I jxcore-log: 
,03-24 22:22:06.263  3282  3339 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 22:22:06.263  3282  3339 I jxcore-log: 
,03-24 22:22:06.266  3282  3339 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 22:22:06.266  3282  3339 I jxcore-log: 
,03-24 22:22:06.275  3282  3339 I jxcore-log: ok 21 Buffers are identical
03-24 22:22:06.275  3282  3339 I jxcore-log: 
,03-24 22:22:06.277  3282  3339 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 22:22:06.277  3282  3339 I jxcore-log: 
,03-24 22:22:06.280  3282  3339 I jxcore-log: DEBUG createNativeListener: mux close
03-24 22:22:06.280  3282  3339 I jxcore-log: 
,03-24 22:22:06.284  3282  3339 I jxcore-log: ok 22 native server is nulled out
03-24 22:22:06.284  3282  3339 I jxcore-log: 
,03-24 22:22:06.284  3282  3339 I jxcore-log: ok 23 native server should be closed
03-24 22:22:06.284  3282  3339 I jxcore-log: 
,03-24 22:22:06.284  3282  3339 I jxcore-log: ok 24 incoming has been removed
03-24 22:22:06.284  3282  3339 I jxcore-log: 
03-24 22:22:06.285  3282  3339 I jxcore-log: ok 25 Incoming should be done
03-24 22:22:06.285  3282  3339 I jxcore-log: 
03-24 22:22:06.285  3282  3339 I jxcore-log: ok 26 The mux object should be closed
03-24 22:22:06.285  3282  3339 I jxcore-log: 
,03-24 22:22:06.285  3282  3339 I jxcore-log: ok 27 The mux stream should be closed
03-24 22:22:06.285  3282  3339 I jxcore-log: 
03-24 22:22:06.286  3282  3339 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 22:22:06.286  3282  3339 I jxcore-log: 
,03-24 22:22:06.301  3282  3339 I jxcore-log: # teardown
03-24 22:22:06.301  3282  3339 I jxcore-log: 
,03-24 22:22:06.417  3282  3339 I jxcore-log: # setup
03-24 22:22:06.417  3282  3339 I jxcore-log: 
,03-24 22:22:06.554  3282  3339 I jxcore-log: # 9. native server - we can get a ton of connections and data through and still clean up the server completely
03-24 22:22:06.554  3282  3339 I jxcore-log: 
,03-24 22:22:06.655  3282  3339 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 22:22:06.655  3282  3339 I jxcore-log: 
03-24 22:22:06.658  3282  3339 I jxcore-log: DEBUG createNativeListener: listening 57048
03-24 22:22:06.658  3282  3339 I jxcore-log: 
,03-24 22:22:06.698  3282  3339 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 22:22:06.698  3282  3339 I jxcore-log: 
,03-24 22:22:06.699  3282  3339 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 22:22:06.699  3282  3339 I jxcore-log: ,
03-24 22:22:06.701  3282  3339 I jxcore-log: DEBUG createNativeListener: new mux
03-24 22:22:06.701  3282  3339 I jxcore-log: 
,03-24 22:22:06.704  3282  3339 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 22:22:06.704  3282  3339 I jxcore-log: 
,03-24 22:22:06.705  3282  3339 I jxcore-log: DEBUG createNativeListener: creating incoming mux,
03-24 22:22:06.705  3282  3339 I jxcore-log: 
03-24 22:22:06.706  3282  3339 I jxcore-log: DEBUG createNativeListener: new mux
03-24 22:22:06.706  3282  3339 I jxcore-log: 
03-24 22:22:06.709  3282  3339 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 22:22:06.709  3282  3339 I jxcore-log: 
,03-24 22:22:06.710  3282  3339 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 22:22:06.710  3282  3339 I jxcore-log: 
03-24 22:22:06.711  3282  3339 I jxcore-log: DEBUG createNativeListener: new mux
03-24 22:22:06.711  3282  3339 I jxcore-log: 
,03-24 22:22:06.714  3282  3339 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 22:22:06.714  3282  3339 I jxcore-log: 
03-24 22:22:06.715  3282  3339 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 22:22:06.715  3282  3339 I jxcore-log: 
,03-24 22:22:06.717  3282  3339 I jxcore-log: DEBUG createNativeListener: new mux
03-24 22:22:06.717  3282  3339 I jxcore-log: 
,03-24 22:22:06.720  3282  3339 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 22:22:06.720  3282  3339 I jxcore-log: 
03-24 22:22:06.721  3282  3339 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 22:22:06.721  3282  3339 I jxcore-log: 
,03-24 22:22:06.722  3282  3339 I jxcore-log: DEBUG createNativeListener: new mux
03-24 22:22:06.722  3282  3339 I jxcore-log: 
,03-24 22:22:06.729  3282  3339 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 22:22:06.729  3282  3339 I jxcore-log: 
03-24 22:22:06.730  3282  3339 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 22:22:06.730  3282  3339 I jxcore-log: 
03-24 22:22:06.731  3282  3339 I jxcore-log: DEBUG createNativeListener: new mux
03-24 22:22:06.731  3282  3339 I jxcore-log: 
,03-24 22:22:06.735  3282  3339 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 22:22:06.735  3282  3339 I jxcore-log: 
,03-24 22:22:06.736  3282  3339 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 22:22:06.736  3282  3339 I jxcore-log: 
,03-24 22:22:06.736  3282  3339 I jxcore-log: DEBUG createNativeListener: new mux
03-24 22:22:06.736  3282  3339 I jxcore-log: 
,03-24 22:22:06.738  3282  3339 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 22:22:06.738  3282  3339 I jxcore-log: 
03-24 22:22:06.739  3282  3339 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 22:22:06.739  3282  3339 I jxcore-log: 
,03-24 22:22:06.740  3282  3339 I jxcore-log: DEBUG createNativeListener: new mux
03-24 22:22:06.740  3282  3339 I jxcore-log: 
,03-24 22:22:06.741  3282  3339 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 22:22:06.741  3282  3339 I jxcore-log: 
03-24 22:22:06.742  3282  3339 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 22:22:06.742  3282  3339 I jxcore-log: 
03-24 22:22:06.743  3282  3339 I jxcore-log: DEBUG createNativeListener: new mux
03-24 22:22:06.743  3282  3339 I jxcore-log: 
,03-24 22:22:06.745  3282  3339 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 22:22:06.745  3282  3339 I jxcore-log: 
03-24 22:22:06.745  3282  3339 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 22:22:06.745  3282  3339 I jxcore-log: 
03-24 22:22:06.746  3282  3339 I jxcore-log: DEBUG createNativeListener: new mux
03-24 22:22:06.746  3282  3339 I jxcore-log: 
,03-24 22:22:06.834  3282  3339 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 22:22:06.834  3282  3339 I jxcore-log: 
,03-24 22:22:06.837  3282  3339 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 22:22:06.837  3282  3339 I jxcore-log: 
,03-24 22:22:06.839  3282  3339 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 22:22:06.839  3282  3339 I jxcore-log: 
,03-24 22:22:06.841  3282  3339 I jxcore-log: DEBUG createNativeListener: new outgoing socket
,03-24 22:22:06.841  3282  3339 I jxcore-log: 
,03-24 22:22:06.842  3282  3339 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 22:22:06.842  3282  3339 I jxcore-log: 
,03-24 22:22:06.844  3282  3339 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 22:22:06.844  3282  3339 I jxcore-log: 
,03-24 22:22:06.845  3282  3339 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 22:22:06.845  3282  3339 I jxcore-log: 
03-24 22:22:06.847  3282  3339 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 22:22:06.847  3282  3339 I jxcore-log: 
,03-24 22:22:06.850  3282  3339 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 22:22:06.850  3282  3339 I jxcore-log: 
,03-24 22:22:06.851  3282  3339 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 22:22:06.851  3282  3339 I jxcore-log: 
,03-24 22:22:06.853  3282  3339 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 22:22:06.853  3282  3339 I jxcore-log: 
,03-24 22:22:06.854  3282  3339 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 22:22:06.854  3282  3339 I jxcore-log: 
,03-24 22:22:06.856  3282  3339 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 22:22:06.856  3282  3339 I jxcore-log: 
,03-24 22:22:06.857  3282  3339 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 22:22:06.857  3282  3339 I jxcore-log: 
,03-24 22:22:06.858  3282  3339 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 22:22:06.858  3282  3339 I jxcore-log: 
,03-24 22:22:06.860  3282  3339 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 22:22:06.860  3282  3339 I jxcore-log: 
,03-24 22:22:06.862  3282  3339 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 22:22:06.862  3282  3339 I jxcore-log: 
,03-24 22:22:06.863  3282  3339 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 22:22:06.863  3282  3339 I jxcore-log: 
,03-24 22:22:06.865  3282  3339 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 22:22:06.865  3282  3339 I jxcore-log: 
,03-24 22:22:06.869  3282  3339 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 22:22:06.869  3282  3339 I jxcore-log: 
,03-24 22:22:06.871  3282  3339 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 22:22:06.871  3282  3339 I jxcore-log: 
,03-24 22:22:06.872  3282  3339 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 22:22:06.872  3282  3339 I jxcore-log: 
,03-24 22:22:06.874  3282  3339 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 22:22:06.874  3282  3339 I jxcore-log: 
,03-24 22:22:06.875  3282  3339 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 22:22:06.875  3282  3339 I jxcore-log: 
,03-24 22:22:06.877  3282  3339 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 22:22:06.877  3282  3339 I jxcore-log: 
,03-24 22:22:06.879  3282  3339 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 22:22:06.879  3282  3339 I jxcore-log: 
,03-24 22:22:06.880  3282  3339 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 22:22:06.880  3282  3339 I jxcore-log: 
,03-24 22:22:06.881  3282  3339 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 22:22:06.881  3282  3339 I jxcore-log: 
,03-24 22:22:06.882  3282  3339 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 22:22:06.882  3282  3339 I jxcore-log: 
,03-24 22:22:06.884  3282  3339 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 22:22:06.884  3282  3339 I jxcore-log: ,
,03-24 22:22:06.885  3282  3339 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 22:22:06.885  3282  3339 I jxcore-log: 
,03-24 22:22:06.886  3282  3339 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 22:22:06.886  3282  3339 I jxcore-log: 
,03-24 22:22:06.888  3282  3339 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 22:22:06.888  3282  3339 I jxcore-log: 
,03-24 22:22:06.889  3282  3339 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 22:22:06.889  3282  3339 I jxcore-log: 
03-24 22:22:06.890  3282  3339 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 22:22:06.890  3282  3339 I jxcore-log: 
,03-24 22:22:06.892  3282  3339 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 22:22:06.892  3282  3339 I jxcore-log: 
,03-24 22:22:06.893  3282  3339 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 22:22:06.893  3282  3339 I jxcore-log: 
,03-24 22:22:06.894  3282  3339 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 22:22:06.894  3282  3339 I jxcore-log: 
,03-24 22:22:06.895  3282  3339 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 22:22:06.895  3282  3339 I jxcore-log: 
,03-24 22:22:06.897  3282  3339 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 22:22:06.897  3282  3339 I jxcore-log: 
,03-24 22:22:06.899  3282  3339 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 22:22:06.899  3282  3339 I jxcore-log: 
,03-24 22:22:06.900  3282  3339 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 22:22:06.900  3282  3339 I jxcore-log: 
,03-24 22:22:06.901  3282  3339 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 22:22:06.901  3282  3339 I jxcore-log: 
,03-24 22:22:06.903  3282  3339 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 22:22:06.903  3282  3339 I jxcore-log: 
,03-24 22:22:06.904  3282  3339 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 22:22:06.904  3282  3339 I jxcore-log: 
,03-24 22:22:06.905  3282  3339 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 22:22:06.905  3282  3339 I jxcore-log: 
,03-24 22:22:06.906  3282  3339 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 22:22:06.906  3282  3339 I jxcore-log: 
,03-24 22:22:06.908  3282  3339 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 22:22:06.908  3282  3339 I jxcore-log: 
,03-24 22:22:06.916  3282  3339 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 22:22:06.916  3282  3339 I jxcore-log: 
,03-24 22:22:06.917  3282  3339 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 22:22:06.917  3282  3339 I jxcore-log: 
,03-24 22:22:06.919  3282  3339 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 22:22:06.919  3282  3339 I jxcore-log: 
,03-24 22:22:06.920  3282  3339 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 22:22:06.920  3282  3339 I jxcore-log: 
,03-24 22:22:06.921  3282  3339 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 22:22:06.921  3282  3339 I jxcore-log: 
,03-24 22:22:06.922  3282  3339 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 22:22:06.922  3282  3339 I jxcore-log: 
,03-24 22:22:06.924  3282  3339 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 22:22:06.924  3282  3339 I jxcore-log: 
,03-24 22:22:06.925  3282  3339 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 22:22:06.925  3282  3339 I jxcore-log: 
,03-24 22:22:06.928  3282  3339 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 22:22:06.928  3282  3339 I jxcore-log: 
,03-24 22:22:06.930  3282  3339 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 22:22:06.930  3282  3339 I jxcore-log: 
,03-24 22:22:06.931  3282  3339 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 22:22:06.931  3282  3339 I jxcore-log: 
,03-24 22:22:06.932  3282  3339 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 22:22:06.932  3282  3339 I jxcore-log: 
,03-24 22:22:06.933  3282  3339 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 22:22:06.933  3282  3339 I jxcore-log: 
,03-24 22:22:06.934  3282  3339 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 22:22:06.934  3282  3339 I jxcore-log: 
,03-24 22:22:06.935  3282  3339 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 22:22:06.935  3282  3339 I jxcore-log: 
,03-24 22:22:06.937  3282  3339 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 22:22:06.937  3282  3339 I jxcore-log: 
,03-24 22:22:06.938  3282  3339 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 22:22:06.938  3282  3339 I jxcore-log: 
,03-24 22:22:06.940  3282  3339 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 22:22:06.940  3282  3339 I jxcore-log: 
,03-24 22:22:06.941  3282  3339 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 22:22:06.941  3282  3339 I jxcore-log: 
,03-24 22:22:06.942  3282  3339 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 22:22:06.942  3282  3339 I jxcore-log: 
,03-24 22:22:06.943  3282  3339 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 22:22:06.943  3282  3339 I jxcore-log: 
03-24 22:22:06.944  3282  3339 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 22:22:06.944  3282  3339 I jxcore-log: 
,03-24 22:22:06.945  3282  3339 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 22:22:06.945  3282  3339 I jxcore-log: 
,03-24 22:22:06.947  3282  3339 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 22:22:06.947  3282  3339 I jxcore-log: 
,03-24 22:22:06.948  3282  3339 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 22:22:06.948  3282  3339 I jxcore-log: 
,03-24 22:22:06.950  3282  3339 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 22:22:06.950  3282  3339 I jxcore-log: 
,03-24 22:22:06.951  3282  3339 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 22:22:06.951  3282  3339 I jxcore-log: 
03-24 22:22:06.952  3282  3339 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 22:22:06.952  3282  3339 I jxcore-log: 
,03-24 22:22:06.953  3282  3339 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 22:22:06.953  3282  3339 I jxcore-log: 
03-24 22:22:06.954  3282  3339 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 22:22:06.954  3282  3339 I jxcore-log: 
,03-24 22:22:06.955  3282  3339 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 22:22:06.955  3282  3339 I jxcore-log: 
03-24 22:22:06.956  3282  3339 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 22:22:06.956  3282  3339 I jxcore-log: 
,03-24 22:22:07.029  3282  3339 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 22:22:07.029  3282  3339 I jxcore-log: 
,03-24 22:22:07.031  3282  3339 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 22:22:07.031  3282  3339 I jxcore-log: 
03-24 22:22:07.032  3282  3339 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 22:22:07.032  3282  3339 I jxcore-log: 
03-24 22:22:07.033  3282  3339 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 22:22:07.033  3282  3339 I jxcore-log: 
,03-24 22:22:07.035  3282  3339 I jxcore-log: DEBUG createNativeListener: mux close
03-24 22:22:07.035  3282  3339 I jxcore-log: 
,03-24 22:22:07.036  3282  3339 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 22:22:07.036  3282  3339 I jxcore-log: 
,03-24 22:22:07.037  3282  3339 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 22:22:07.037  3282  3339 I jxcore-log: 
,03-24 22:22:07.038  3282  3339 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 22:22:07.038  3282  3339 I jxcore-log: 
03-24 22:22:07.039  3282  3339 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 22:22:07.039  3282  3339 I jxcore-log: 
03-24 22:22:07.039  3282  3339 I jxcore-log: DEBUG createNativeListener: mux close
03-24 22:22:07.039  3282  3339 I jxcore-log: 
,03-24 22:22:07.042  3282  3339 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 22:22:07.042  3282  3339 I jxcore-log: 
03-24 22:22:07.043  3282  3339 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 22:22:07.043  3282  3339 I jxcore-log: 
03-24 22:22:07.044  3282  3339 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 22:22:07.044  3282  3339 I jxcore-log: 
,03-24 22:22:07.045  3282  3339 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 22:22:07.045  3282  3339 I jxcore-log: 
,03-24 22:22:07.047  3282  3339 I jxcore-log: DEBUG createNativeListener: mux close
03-24 22:22:07.047  3282  3339 I jxcore-log: 
03-24 22:22:07.048  3282  3339 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 22:22:07.048  3282  3339 I jxcore-log: 
,03-24 22:22:07.049  3282  3339 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 22:22:07.049  3282  3339 I jxcore-log: ,
03-24 22:22:07.049  3282  3339 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 22:22:07.049  3282  3339 I jxcore-log: 
03-24 22:22:07.050  3282  3339 I jxcore-log: DEBUG createNativeListener: stream close:
,03-24 22:22:07.050  3282  3339 I jxcore-log: 
,03-24 22:22:07.051  3282  3339 I jxcore-log: DEBUG createNativeListener: mux close
03-24 22:22:07.051  3282  3339 I jxcore-log: 
03-24 22:22:07.052  3282  3339 I jxcore-log: DEBUG createNativeListener: stream close:
,03-24 22:22:07.052  3282  3339 I jxcore-log: 
03-24 22:22:07.053  3282  3339 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 22:22:07.053  3282  3339 I jxcore-log: 
03-24 22:22:07.054  3282  3339 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 22:22:07.054  3282  3339 I jxcore-log: 
03-24 22:22:07.054  3282  3339 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 22:22:07.054  3282  3339 I jxcore-log: 
,03-24 22:22:07.056  3282  3339 I jxcore-log: DEBUG createNativeListener: mux close
03-24 22:22:07.056  3282  3339 I jxcore-log: 
03-24 22:22:07.057  3282  3339 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 22:22:07.057  3282  3339 I jxcore-log: 
03-24 22:22:07.057  3282  3339 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 22:22:07.057  3282  3339 I jxcore-log: 
,03-24 22:22:07.058  3282  3339 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 22:22:07.058  3282  3339 I jxcore-log: 
03-24 22:22:07.059  3282  3339 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 22:22:07.059  3282  3339 I jxcore-log: 
03-24 22:22:07.060  3282  3339 I jxcore-log: DEBUG createNativeListener: mux close
03-24 22:22:07.060  3282  3339 I jxcore-log: 
03-24 22:22:07.061  3282  3339 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 22:22:07.061  3282  3339 I jxcore-log: 
03-24 22:22:07.061  3282  3339 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 22:22:07.061  3282  3339 I jxcore-log: 
,03-24 22:22:07.062  3282  3339 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 22:22:07.062  3282  3339 I jxcore-log: 
03-24 22:22:07.063  3282  3339 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 22:22:07.063  3282  3339 I jxcore-log: 
03-24 22:22:07.064  3282  3339 I jxcore-log: DEBUG createNativeListener: mux close
03-24 22:22:07.064  3282  3339 I jxcore-log: 
,03-24 22:22:07.065  3282  3339 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 22:22:07.065  3282  3339 I jxcore-log: 
03-24 22:22:07.066  3282  3339 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 22:22:07.066  3282  3339 I jxcore-log: 
03-24 22:22:07.067  3282  3339 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 22:22:07.067  3282  3339 I jxcore-log: 
,03-24 22:22:07.067  3282  3339 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 22:22:07.067  3282  3339 I jxcore-log: 
03-24 22:22:07.068  3282  3339 I jxcore-log: DEBUG createNativeListener: mux close
03-24 22:22:07.068  3282  3339 I jxcore-log: 
03-24 22:22:07.069  3282  3339 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 22:22:07.069  3282  3339 I jxcore-log: 
,03-24 22:22:07.070  3282  3339 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 22:22:07.070  3282  3339 I jxcore-log: 
03-24 22:22:07.071  3282  3339 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 22:22:07.071  3282  3339 I jxcore-log: 
03-24 22:22:07.071  3282  3339 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 22:22:07.071  3282  3339 I jxcore-log: 
,03-24 22:22:07.073  3282  3339 I jxcore-log: DEBUG createNativeListener: mux close
,03-24 22:22:07.073  3282  3339 I jxcore-log: 
03-24 22:22:07.073  3282  3339 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 22:22:07.073  3282  3339 I jxcore-log: 
,03-24 22:22:07.074  3282  3339 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 22:22:07.074  3282  3339 I jxcore-log: 
03-24 22:22:07.075  3282  3339 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 22:22:07.075  3282  3339 I jxcore-log: ,
03-24 22:22:07.076  3282  3339 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 22:22:07.076  3282  3339 I jxcore-log: 
03-24 22:22:07.077  3282  3339 I jxcore-log: DEBUG createNativeListener: mux close
03-24 22:22:07.077  3282  3339 I jxcore-log: 
,03-24 22:22:07.080  3282  3339 I jxcore-log: ok 28 native server is nulled out
03-24 22:22:07.080  3282  3339 I jxcore-log: 
03-24 22:22:07.080  3282  3339 I jxcore-log: ok 29 native server should be closed
03-24 22:22:07.080  3282  3339 I jxcore-log: 
,03-24 22:22:07.080  3282  3339 I jxcore-log: ok 30 incoming has been removed
03-24 22:22:07.080  3282  3339 I jxcore-log: 
03-24 22:22:07.081  3282  3339 I jxcore-log: DEBUG createNativeListener: incoming socket close
,03-24 22:22:07.081  3282  3339 I jxcore-log: 
03-24 22:22:07.082  3282  3339 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 22:22:07.082  3282  3339 I jxcore-log: 
,03-24 22:22:07.083  3282  3339 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 22:22:07.083  3282  3339 I jxcore-log: 
03-24 22:22:07.084  3282  3339 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 22:22:07.084  3282  3339 I jxcore-log: ,
03-24 22:22:07.084  3282  3339 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 22:22:07.084  3282  3339 I jxcore-log: 
03-24 22:22:07.084  3282  3339 I jxcore-log: DEBUG createNativeListener: incoming socket close,
03-24 22:22:07.084  3282  3339 I jxcore-log: 
03-24 22:22:07.085  3282  3339 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 22:22:07.085  3282  3339 I jxcore-log: 
,03-24 22:22:07.085  3282  3339 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 22:22:07.085  3282  3339 I jxcore-log: 
03-24 22:22:07.085  3282  3339 I jxcore-log: DEBUG createNativeListener: incoming socket close
,03-24 22:22:07.085  3282  3339 I jxcore-log: 
03-24 22:22:07.086  3282  3339 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 22:22:07.086  3282  3339 I jxcore-log: 
,03-24 22:22:07.191  3282  3339 I jxcore-log: # teardown
03-24 22:22:07.191  3282  3339 I jxcore-log: 
,03-24 22:22:07.287  3282  3339 I jxcore-log: # setup
03-24 22:22:07.287  3282  3339 I jxcore-log: 
,03-24 22:22:07.434  3282  3339 I jxcore-log: # 10. native server - simulate mux failure, make sure everything is cleaned up
03-24 22:22:07.434  3282  3339 I jxcore-log: 
,03-24 22:22:07.628  3282  3339 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 22:22:07.628  3282  3339 I jxcore-log: 
,03-24 22:22:07.637  3282  3339 I jxcore-log: DEBUG createNativeListener: listening 45662
03-24 22:22:07.637  3282  3339 I jxcore-log: 
,03-24 22:22:07.647  3282  3339 I jxcore-log: DEBUG createNativeListener: new incoming socket
,03-24 22:22:07.647  3282  3339 I jxcore-log: 
,03-24 22:22:07.649  3282  3339 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 22:22:07.649  3282  3339 I jxcore-log: 
,03-24 22:22:07.652  3282  3339 I jxcore-log: DEBUG createNativeListener: new mux
,03-24 22:22:07.652  3282  3339 I jxcore-log: 
03-24 22:22:07.660  3282  3339 I jxcore-log: ok 31 we should not have gotten an error
03-24 22:22:07.660  3282  3339 I jxcore-log: 
,03-24 22:22:07.665  3282  3339 I jxcore-log: DEBUG createNativeListener: new stream: ,
03-24 22:22:07.665  3282  3339 I jxcore-log: 
,03-24 22:22:07.667  3282  3339 I jxcore-log: DEBUG createNativeListener: new outgoing socket,
03-24 22:22:07.667  3282  3339 I jxcore-log: 
,03-24 22:22:07.676  3282  3339 I jxcore-log: ok 32 Buffers are identical,
03-24 22:22:07.676  3282  3339 I jxcore-log: 
03-24 22:22:07.677  3282  3339 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 22:22:07.677  3282  3339 I jxcore-log: 
,03-24 22:22:07.679  3282  3339 I jxcore-log: DEBUG createNativeListener: mux close
03-24 22:22:07.679  3282  3339 I jxcore-log: 
,03-24 22:22:07.691  3282  3339 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 22:22:07.691  3282  3339 I jxcore-log: ,
03-24 22:22:07.692  3282  3339 I jxcore-log: ok 33 server should be fine
03-24 22:22:07.692  3282  3339 I jxcore-log: 
03-24 22:22:07.693  3282  3339 I jxcore-log: ok 34 server should be open
,03-24 22:22:07.693  3282  3339 I jxcore-log: 
03-24 22:22:07.693  3282  3339 I jxcore-log: ok 35 incoming has been removed
03-24 22:22:07.693  3282  3339 I jxcore-log: 
,03-24 22:22:07.693  3282  3339 I jxcore-log: ok 36 The mux object should be closed
03-24 22:22:07.693  3282  3339 I jxcore-log: 
,03-24 22:22:07.695  3282  3339 I jxcore-log: ok 37 The mux stream should be closed
03-24 22:22:07.695  3282  3339 I jxcore-log: 
,03-24 22:22:07.703  3282  3339 I jxcore-log: # teardown
,03-24 22:22:07.703  3282  3339 I jxcore-log: 
,03-24 22:22:07.866  3282  3339 I jxcore-log: # setup
,03-24 22:22:07.866  3282  3339 I jxcore-log: 
,03-24 22:22:08.007  3282  3339 I jxcore-log: # 11. native server - timing out the incoming connection cleans everything up
,03-24 22:22:08.007  3282  3339 I jxcore-log: 
,03-24 22:22:08.195  3282  3339 I jxcore-log: DEBUG createNativeListener: creating native server
,03-24 22:22:08.195  3282  3339 I jxcore-log: 
,03-24 22:22:08.206  3282  3339 I jxcore-log: DEBUG createNativeListener: listening 46341
,03-24 22:22:08.206  3282  3339 I jxcore-log: 
,03-24 22:22:08.213  3282  3339 I jxcore-log: DEBUG createNativeListener: new incoming socket
,03-24 22:22:08.213  3282  3339 I jxcore-log: 
03-24 22:22:08.214  3282  3339 I jxcore-log: DEBUG createNativeListener: creating incoming mux
,03-24 22:22:08.214  3282  3339 I jxcore-log: 
,03-24 22:22:08.217  3282  3339 I jxcore-log: DEBUG createNativeListener: new mux
,03-24 22:22:08.217  3282  3339 I jxcore-log: 
,03-24 22:22:08.225  3282  3339 I jxcore-log: ok 38 we should not have gotten an error
,03-24 22:22:08.225  3282  3339 I jxcore-log: 
,03-24 22:22:08.230  3282  3339 I jxcore-log: DEBUG createNativeListener: new stream: ,
03-24 22:22:08.230  3282  3339 I jxcore-log: 
,03-24 22:22:08.234  3282  3339 I jxcore-log: DEBUG createNativeListener: new outgoing socket
,03-24 22:22:08.234  3282  3339 I jxcore-log: 
,03-24 22:22:08.241  3282  3339 I jxcore-log: ok 39 Buffers are identical
,03-24 22:22:08.241  3282  3339 I jxcore-log: 
,03-24 22:22:08.247  3282  3339 I jxcore-log: DEBUG createNativeListener: incoming socket timeout
,03-24 22:22:08.247  3282  3339 I jxcore-log: 
,03-24 22:22:08.248  3282  3339 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 22:22:08.248  3282  3339 I jxcore-log: 
,03-24 22:22:08.252  3282  3339 I jxcore-log: DEBUG createNativeListener: mux close
,03-24 22:22:08.252  3282  3339 I jxcore-log: 
,03-24 22:22:08.257  3282  3339 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 22:22:08.257  3282  3339 I jxcore-log: 
,03-24 22:22:08.258  3282  3339 I jxcore-log: ok 40 server should be fine
03-24 22:22:08.258  3282  3339 I jxcore-log: 
03-24 22:22:08.258  3282  3339 I jxcore-log: ok 41 server should be open
03-24 22:22:08.258  3282  3339 I jxcore-log: ,
03-24 22:22:08.258  3282  3339 I jxcore-log: ok 42 incoming has been removed
03-24 22:22:08.258  3282  3339 I jxcore-log: 
03-24 22:22:08.259  3282  3339 I jxcore-log: ok 43 The mux object should be closed,
03-24 22:22:08.259  3282  3339 I jxcore-log: 
03-24 22:22:08.259  3282  3339 I jxcore-log: ok 44 The mux stream should be closed
03-24 22:22:08.259  3282  3339 I jxcore-log: 
,03-24 22:22:08.271  3282  3339 I jxcore-log: # teardown,
03-24 22:22:08.271  3282  3339 I jxcore-log: 
,03-24 22:22:08.424  3282  3339 I jxcore-log: # setup,
,03-24 22:22:08.424  3282  3339 I jxcore-log: ,
,03-24 22:22:08.704  3282  3339 I jxcore-log: # 12. closeAll can close even when connections open
03-24 22:22:08.704  3282  3339 I jxcore-log: 
,03-24 22:22:08.858  3282  3339 I jxcore-log: ok 45 not possible to connect to the server anymore
03-24 22:22:08.858  3282  3339 I jxcore-log: 
,03-24 22:22:08.863  3282  3339 I jxcore-log: # teardown
03-24 22:22:08.863  3282  3339 I jxcore-log: 
,03-24 22:22:09.007  3282  3339 I jxcore-log: # setup
03-24 22:22:09.007  3282  3339 I jxcore-log: 
,03-24 22:22:09.129  3282  3339 I jxcore-log: # 13. closeAll with promise,
03-24 22:22:09.129  3282  3339 I jxcore-log: 
,03-24 22:22:09.256  3282  3339 I jxcore-log: ok 46 not possible to connect to the server anymore,
03-24 22:22:09.256  3282  3339 I jxcore-log: 
,03-24 22:22:09.260  3282  3339 I jxcore-log: # teardown
03-24 22:22:09.260  3282  3339 I jxcore-log: 
,03-24 22:22:09.429  3282  3339 I jxcore-log: # setup
03-24 22:22:09.429  3282  3339 I jxcore-log: 
,03-24 22:22:09.540  3282  3339 I jxcore-log: # 14. closeAll properly throws when closing a non open server with eatNotRunning set to false
03-24 22:22:09.540  3282  3339 I jxcore-log: 
,03-24 22:22:09.695  3282  3339 I jxcore-log: ok 47 Got the right error,
03-24 22:22:09.695  3282  3339 I jxcore-log: 
,03-24 22:22:09.701  3282  3339 I jxcore-log: # teardown
03-24 22:22:09.701  3282  3339 I jxcore-log: 
,03-24 22:22:09.824  3282  3339 I jxcore-log: # setup
03-24 22:22:09.824  3282  3339 I jxcore-log: 
,03-24 22:22:10.006  3282  3339 I jxcore-log: # 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true
03-24 22:22:10.006  3282  3339 I jxcore-log: 
,03-24 22:22:10.103  3282  3339 I jxcore-log: # teardown
03-24 22:22:10.103  3282  3339 I jxcore-log: 
,03-24 22:22:10.331  3282  3339 I jxcore-log: # setup
03-24 22:22:10.331  3282  3339 I jxcore-log: 
,03-24 22:22:10.444  3282  3339 I jxcore-log: # 16. multiplex can send data
03-24 22:22:10.444  3282  3339 I jxcore-log: 
,03-24 22:22:10.592  3282  3339 I jxcore-log: ok 48 String should be length:200
,03-24 22:22:10.592  3282  3339 I jxcore-log: 
,03-24 22:22:10.600  3282  3339 I jxcore-log: # teardown
03-24 22:22:10.600  3282  3339 I jxcore-log: 
,03-24 22:22:10.714  3282  3339 I jxcore-log: # setup
03-24 22:22:10.714  3282  3339 I jxcore-log: 
,03-24 22:22:10.853  3282  3339 I jxcore-log: # 17. enqueue and run in order
03-24 22:22:10.853  3282  3339 I jxcore-log: 
,03-24 22:22:11.068  3282  3339 I jxcore-log: ok 49 firstPromise setTimeout
03-24 22:22:11.068  3282  3339 I jxcore-log: 
,03-24 22:22:11.070  3282  3339 I jxcore-log: ok 50 firstPromise result
03-24 22:22:11.070  3282  3339 I jxcore-log: 
,03-24 22:22:11.072  3282  3339 I jxcore-log: ok 51 firstPromise testValue
03-24 22:22:11.072  3282  3339 I jxcore-log: 
,03-24 22:22:11.175  3282  3339 I jxcore-log: ok 52 secondPromise setTimeout
03-24 22:22:11.175  3282  3339 I jxcore-log: 
,03-24 22:22:11.180  3282  3339 I jxcore-log: ok 53 secondPromise result
03-24 22:22:11.180  3282  3339 I jxcore-log: 
,03-24 22:22:11.182  3282  3339 I jxcore-log: ok 54 secondPromise testValue
03-24 22:22:11.182  3282  3339 I jxcore-log: 
,03-24 22:22:11.185  3282  3339 I jxcore-log: ok 55 thirdPromise in promise
03-24 22:22:11.185  3282  3339 I jxcore-log: 
,03-24 22:22:11.188  3282  3339 I jxcore-log: ok 56 thirdPromise result
03-24 22:22:11.188  3282  3339 I jxcore-log: 
,03-24 22:22:11.191  3282  3339 I jxcore-log: ok 57 thirdPromise testValue
03-24 22:22:11.191  3282  3339 I jxcore-log: 
,03-24 22:22:11.205  3282  3339 I jxcore-log: # teardown
03-24 22:22:11.205  3282  3339 I jxcore-log: 
,03-24 22:22:11.592  3282  3339 I jxcore-log: # setup
03-24 22:22:11.592  3282  3339 I jxcore-log: 
,03-24 22:22:12.405  3282  3339 I jxcore-log: # 18. enqueueAtTop and run backwards
03-24 22:22:12.405  3282  3339 I jxcore-log: 
,03-24 22:22:12.556  3282  3339 I jxcore-log: ok 58 thirdPromise - first to run,
03-24 22:22:12.556  3282  3339 I jxcore-log: 
,03-24 22:22:12.560  3282  3339 I jxcore-log: ok 59 thirdPromise - in resolve
03-24 22:22:12.560  3282  3339 I jxcore-log: 
,03-24 22:22:12.562  3282  3339 I jxcore-log: ok 60 secondPromise - second to run
03-24 22:22:12.562  3282  3339 I jxcore-log: 
,03-24 22:22:12.564  3282  3339 I jxcore-log: ok 61 secondPromise - in catch
03-24 22:22:12.564  3282  3339 I jxcore-log: 
,03-24 22:22:12.565  3282  3339 I jxcore-log: ok 62 firstPromise - third to run
03-24 22:22:12.565  3282  3339 I jxcore-log: 
,03-24 22:22:12.565  3282  3339 I jxcore-log: ok 63 firstPromise - in then
03-24 22:22:12.565  3282  3339 I jxcore-log: 
,03-24 22:22:12.566  3282  3339 I jxcore-log: ok 64 testing promises
03-24 22:22:12.566  3282  3339 I jxcore-log: 
03-24 22:22:12.568  3282  3339 I jxcore-log: # teardown
03-24 22:22:12.568  3282  3339 I jxcore-log: 
,03-24 22:22:12.990  3282  3339 I jxcore-log: # setup
03-24 22:22:12.990  3282  3339 I jxcore-log: 
,03-24 22:22:18.278  3282  3339 I jxcore-log: # 19. mix enqueue and enqueueAtTop
03-24 22:22:18.278  3282  3339 I jxcore-log: 
,03-24 22:22:18.515  3282  3339 I jxcore-log: ok 65 fourth
03-24 22:22:18.515  3282  3339 I jxcore-log: ,
03-24 22:22:18.516  3282  3339 I jxcore-log: ok 66 fourth
03-24 22:22:18.516  3282  3339 I jxcore-log: 
,03-24 22:22:18.518  3282  3339 I jxcore-log: ok 67 second
,03-24 22:22:18.518  3282  3339 I jxcore-log: 
,03-24 22:22:18.520  3282  3339 I jxcore-log: ok 68 secondPromise - in then
,03-24 22:22:18.520  3282  3339 I jxcore-log: 
,03-24 22:22:18.624  3282  3339 I jxcore-log: ok 69 first
03-24 22:22:18.624  3282  3339 I jxcore-log: 
,03-24 22:22:18.627  3282  3339 I jxcore-log: ok 70 firstPromise - in catch
03-24 22:22:18.627  3282  3339 I jxcore-log: 
03-24 22:22:18.629  3282  3339 I jxcore-log: ok 71 third
03-24 22:22:18.629  3282  3339 I jxcore-log: 
03-24 22:22:18.631  3282  3339 I jxcore-log: ok 72 thirdPromise - in then
03-24 22:22:18.631  3282  3339 I jxcore-log: 
,03-24 22:22:18.638  3282  3339 I jxcore-log: ok 73 testingPromises
03-24 22:22:18.638  3282  3339 I jxcore-log: 
,03-24 22:22:18.655  3282  3339 I jxcore-log: # teardown,
03-24 22:22:18.655  3282  3339 I jxcore-log: 
,03-24 22:22:20.273  3282  3339 I jxcore-log: # setup
03-24 22:22:20.273  3282  3339 I jxcore-log: 
,03-24 22:22:22.513  3282  3339 I jxcore-log: # 20. queues handled independently
03-24 22:22:22.513  3282  3339 I jxcore-log: 
,03-24 22:22:23.106  3282  3339 I jxcore-log: ok 74 all short operations completed before the long resolves
03-24 22:22:23.106  3282  3339 I jxcore-log: 
,03-24 22:22:23.120  3282  3339 I jxcore-log: # teardown
03-24 22:22:23.120  3282  3339 I jxcore-log: 
,03-24 22:22:25.035  3282  3339 I jxcore-log: # setup
03-24 22:22:25.035  3282  3339 I jxcore-log: 
,03-24 22:22:26.391  3282  3339 I jxcore-log: # 21. basic
03-24 22:22:26.391  3282  3339 I jxcore-log: 
,03-24 22:22:27.380  3394  3736 V GoogleAuthProtoRequest: [341] a.<init>: mAccountName set to: thalitester@gmail.com
,03-24 22:22:27.428  1261  2597 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
03-24 22:22:27.429  1261  2597 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 22:22:27.429  1261  2597 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-24 22:22:27.429  1261  2597 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 22:22:27.436  1261  2597 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 22:22:27.449  3394  3736 W ExperimentUpdateService: [341] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,03-24 22:22:27.450  3394  3736 W ExperimentUpdateService: [341] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-24 22:22:27.450  3394  3736 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-24 22:22:27.450  3394  3736 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-24 22:22:27.450  3394  3736 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-24 22:22:27.450  3394  3736 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-24 22:22:27.450  3394  3736 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-24 22:22:27.450  3394  3736 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-24 22:22:27.450  3394  3736 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-24 22:22:27.450  3394  3736 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-24 22:22:27.450  3394  3736 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-24 22:22:27.450  3394  3736 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-24 22:22:28.218  3282  3339 I jxcore-log: ok 75 sane
03-24 22:22:28.218  3282  3339 I jxcore-log: 
,03-24 22:22:28.227  3282  3339 I jxcore-log: # teardown
03-24 22:22:28.227  3282  3339 I jxcore-log: 
,03-24 22:22:29.452  3282  3339 I jxcore-log: # setup
03-24 22:22:29.452  3282  3339 I jxcore-log: 
,03-24 22:22:30.796  3282  3339 I jxcore-log: # 22. another
03-24 22:22:30.796  3282  3339 I jxcore-log: 
,03-24 22:22:32.176  3282  3339 I jxcore-log: ok 76 sane
03-24 22:22:32.176  3282  3339 I jxcore-log: 
,03-24 22:22:32.186  3282  3339 I jxcore-log: # teardown
03-24 22:22:32.186  3282  3339 I jxcore-log: 
,03-24 22:22:32.321  3282  3339 I jxcore-log: # setup
03-24 22:22:32.321  3282  3339 I jxcore-log: 
,03-24 22:22:32.447  3282  3339 I jxcore-log: # 23. can pass data in setup
03-24 22:22:32.447  3282  3339 I jxcore-log: 
,03-24 22:22:32.629  3282  3339 I jxcore-log: ok 77 test participant has uuid
03-24 22:22:32.629  3282  3339 I jxcore-log: 
03-24 22:22:32.631  3282  3339 I jxcore-log: ok 78 participant data matches
03-24 22:22:32.631  3282  3339 I jxcore-log: 
03-24 22:22:32.632  3282  3339 I jxcore-log: ok 79 test participant has uuid
03-24 22:22:32.632  3282  3339 I jxcore-log: 
,03-24 22:22:32.634  3282  3339 I jxcore-log: ok 80 participant data matches
03-24 22:22:32.634  3282  3339 I jxcore-log: 
,03-24 22:22:32.637  3282  3339 I jxcore-log: ok 81 test participant has uuid
03-24 22:22:32.637  3282  3339 I jxcore-log: 
,03-24 22:22:32.639  3282  3339 I jxcore-log: ok 82 participant data matches
03-24 22:22:32.639  3282  3339 I jxcore-log: 
,03-24 22:22:32.645  3282  3339 I jxcore-log: # teardown
,03-24 22:22:32.645  3282  3339 I jxcore-log: 
,03-24 22:22:32.758  3282  3339 I jxcore-log: # setup
03-24 22:22:32.758  3282  3339 I jxcore-log: 
,03-24 22:22:32.872  3282  3339 I jxcore-log: # 24. #startListeningForAdvertisements should fail if start not called
03-24 22:22:32.872  3282  3339 I jxcore-log: 
,03-24 22:22:32.988  3282  3339 I jxcore-log: ok 83 specific error should be returned
03-24 22:22:32.988  3282  3339 I jxcore-log: 
,03-24 22:22:32.994  3282  3339 I jxcore-log: # teardown
03-24 22:22:32.994  3282  3339 I jxcore-log: 
,03-24 22:22:33.136  3282  3339 I jxcore-log: ok 84 error should be null
03-24 22:22:33.136  3282  3339 I jxcore-log: 
,03-24 22:22:33.137  3282  3339 I jxcore-log: ok 85 error should be null
03-24 22:22:33.137  3282  3339 I jxcore-log: 
03-24 22:22:33.139  3282  3339 I jxcore-log: # setup
03-24 22:22:33.139  3282  3339 I jxcore-log: 
,03-24 22:22:33.259  3282  3339 I jxcore-log: # 25. #startUpdateAdvertisingAndListening should fail if start not called
03-24 22:22:33.259  3282  3339 I jxcore-log: 
,03-24 22:22:33.435  3282  3339 I jxcore-log: ok 86 specific error should be returned
03-24 22:22:33.435  3282  3339 I jxcore-log: 
,03-24 22:22:33.437  3282  3339 I jxcore-log: # teardown
03-24 22:22:33.437  3282  3339 I jxcore-log: 
,03-24 22:22:33.565  3282  3339 I jxcore-log: ok 87 error should be null
03-24 22:22:33.565  3282  3339 I jxcore-log: 
,03-24 22:22:33.567  3282  3339 I jxcore-log: ok 88 error should be null
03-24 22:22:33.567  3282  3339 I jxcore-log: 
03-24 22:22:33.572  3282  3339 I jxcore-log: # setup
03-24 22:22:33.572  3282  3339 I jxcore-log: 
,03-24 22:22:33.674  3282  3339 I jxcore-log: # 26. should be able to call #stopListeningForAdvertisements many times
03-24 22:22:33.674  3282  3339 I jxcore-log: 
,03-24 22:22:33.843  3282  3339 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 22:22:33.843  3282  3339 I jxcore-log: 
,03-24 22:22:33.845  3282  3339 I jxcore-log: DEBUG createNativeListener: listening 43829
03-24 22:22:33.845  3282  3339 I jxcore-log: 
03-24 22:22:33.847  3282  3339 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 22:22:33.848  3282  3339 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 22:22:33.848  3282  3339 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 22:22:33.853  3282  3339 I jxcore-log: ok 89 error should be null
03-24 22:22:33.853  3282  3339 I jxcore-log: 
,03-24 22:22:33.854  3282  3339 I jxcore-log: ok 90 error should be null
03-24 22:22:33.854  3282  3339 I jxcore-log: 
03-24 22:22:33.855  3282  3339 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 22:22:33.855  3282  3339 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 22:22:33.855  3282  3339 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 22:22:33.857  3282  3339 I jxcore-log: ok 91 error should be null
03-24 22:22:33.857  3282  3339 I jxcore-log: 
03-24 22:22:33.857  3282  3339 I jxcore-log: ok 92 error should be null,
03-24 22:22:33.857  3282  3339 I jxcore-log: 
03-24 22:22:33.860  3282  3339 I jxcore-log: # teardown
03-24 22:22:33.860  3282  3339 I jxcore-log: 
,03-24 22:22:33.934  3282  3339 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-24 22:22:33.934  3282  3339 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
03-24 22:22:33.934  3282  3339 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 22:22:33.936  3282  3339 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 22:22:33.936  3282  3339 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 22:22:33.936  3282  3339 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 22:22:33.939  3282  3339 I jxcore-log: ok 93 error should be null
03-24 22:22:33.939  3282  3339 I jxcore-log: 
,03-24 22:22:33.939  3282  3339 I jxcore-log: ok 94 error should be null
03-24 22:22:33.939  3282  3339 I jxcore-log: 
,03-24 22:22:33.942  3282  3339 I jxcore-log: # setup
03-24 22:22:33.942  3282  3339 I jxcore-log: 
,03-24 22:22:34.083  3282  3339 I jxcore-log: # 27. should be able to call #startListeningForAdvertisements many times
03-24 22:22:34.083  3282  3339 I jxcore-log: 
,03-24 22:22:34.200  3282  3339 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 22:22:34.200  3282  3339 I jxcore-log: 
,03-24 22:22:34.202  3282  3339 I jxcore-log: DEBUG createNativeListener: listening 46390
03-24 22:22:34.202  3282  3339 I jxcore-log: 
,03-24 22:22:34.211  3282  3339 I io.jxcore.node.ConnectionHelper: start: Port number: 0, start advertisements: false
03-24 22:22:34.211  3282  3339 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-24 22:22:34.211  3282  3339 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 22:22:34.211  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
03-24 22:22:34.211  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 22:22:34.211  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-24 22:22:34.223  3282  3339 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-24 22:22:34.224   821  1328 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 22:22:34.239  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
,03-24 22:22:34.251  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 22:22:34.251  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-24 22:22:34.251  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 22:22:34.252  3282  3339 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 22:22:34.262  2156  2175 D BtGatt.GattService: registerClient() - UUID=f5e9e760-cc11-4f8d-8bc7-1fb5fa125534,
03-24 22:22:34.264  2156  2219 D BtGatt.GattService: onClientRegistered() - UUID=f5e9e760-cc11-4f8d-8bc7-1fb5fa125534, clientIf=5
03-24 22:22:34.265  3282  3300 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-24 22:22:34.267  2156  2397 D BtGatt.GattService: start scan with filters
,03-24 22:22:34.269  2156  2229 D BtGatt.ScanManager: handling starting scan
03-24 22:22:34.270  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 22:22:34.270  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 22:22:34.270  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-24 22:22:34.270  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-24 22:22:34.270  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false,
03-24 22:22:34.272  3282  3282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-24 22:22:34.272  2156  2229 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e67340c
03-24 22:22:34.273  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 22:22:34.274   821   837 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 22:22:34.280  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 22:22:34.280  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-24 22:22:34.281  3282  3282 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 22:22:34.281  3282  3282 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 22:22:34.282  3282  3282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 22:22:34.284  3282  3339 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 22:22:34.287  2156  2219 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,03-24 22:22:34.287  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 22:22:34.291  2156  2219 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 22:22:34.291  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:22:34.292  2156  2229 D BtGatt.ScanManager: Starting BLE batch scan
03-24 22:22:34.292  2156  2229 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-24 22:22:34.295  2156  2219 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 22:22:34.296  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 22:22:34.297  2156  2219 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,03-24 22:22:34.297  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 22:22:34.302  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 22:22:34.302  3282  3339 I jxcore-log: 
,03-24 22:22:34.303  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 22:22:34.303  3282  3339 I jxcore-log: 
,03-24 22:22:34.305  3282  3339 I jxcore-log: ok 95 error should be null
03-24 22:22:34.305  3282  3339 I jxcore-log: 
,03-24 22:22:34.305  3282  3339 I jxcore-log: ok 96 error should be null
03-24 22:22:34.305  3282  3339 I jxcore-log: 
,03-24 22:22:34.311  3282  3339 I io.jxcore.node.ConnectionHelper: start: Port number: 0, start advertisements: false
,03-24 22:22:34.311  3282  3339 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 22:22:34.311  3282  3339 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 22:22:34.311  3282  3339 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 22:22:34.312  3282  3339 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 22:22:34.314  3282  3339 I jxcore-log: ok 97 error should be null
03-24 22:22:34.314  3282  3339 I jxcore-log: 
,03-24 22:22:34.315  3282  3339 I jxcore-log: ok 98 error should be null
03-24 22:22:34.315  3282  3339 I jxcore-log: 
,03-24 22:22:34.324  3282  3339 I jxcore-log: # teardown
03-24 22:22:34.324  3282  3339 I jxcore-log: 
,03-24 22:22:34.609  3282  3339 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 22:22:34.609  3282  3339 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
03-24 22:22:34.609  3282  3339 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
03-24 22:22:34.610  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-24 22:22:34.610  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-24 22:22:34.610  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 22:22:34.610  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,03-24 22:22:34.612  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-24 22:22:34.613  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-24 22:22:34.616  2156  2174 D BtGatt.GattService: stopScan() - queue size =1
,03-24 22:22:34.617  2156  2175 D BtGatt.GattService: unregisterClient() - clientIf=5,
,03-24 22:22:34.617  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 22:22:34.617  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 22:22:34.617  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,03-24 22:22:34.617  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-24 22:22:34.617  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-24 22:22:34.617  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 22:22:34.620  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
03-24 22:22:34.620  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 22:22:34.620  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-24 22:22:34.621  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-24 22:22:34.621  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 22:22:34.621  2156  2219 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 22:22:34.621  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:22:34.621  3282  3282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 22:22:34.621  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 22:22:34.621  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-24 22:22:34.621  2156  2229 D BtGatt.ScanManager: stopping BLe Batch
03-24 22:22:34.626  2156  2219 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 22:22:34.626  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:22:34.627  2156  2229 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 22:22:34.627  3282  3282 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-24 22:22:34.630  2156  2219 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 22:22:34.630  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:22:34.630   821  1259 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 22:22:34.635  3282  3339 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).,
03-24 22:22:34.635  3282  3339 I jxcore-log: 
03-24 22:22:34.637  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-24 22:22:34.637  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 22:22:34.638  3282  3282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 22:22:34.642  3282  3282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-24 22:22:34.642  3282  3282 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 22:22:34.642  3282  3282 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 22:22:34.642  3282  3282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-24 22:22:34.644  3282  3339 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 22:22:34.645  3282  3339 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 22:22:34.645  3282  3339 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 22:22:34.647  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
,03-24 22:22:34.647  3282  3339 I jxcore-log: 
,03-24 22:22:34.649  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 22:22:34.649  3282  3339 I jxcore-log: 
,03-24 22:22:34.658  3282  3339 I jxcore-log: ok 99 error should be null
03-24 22:22:34.658  3282  3339 I jxcore-log: 
,03-24 22:22:34.659  3282  3339 I jxcore-log: ok 100 error should be null
03-24 22:22:34.659  3282  3339 I jxcore-log: 
,03-24 22:22:34.667  3282  3339 I jxcore-log: # setup
,03-24 22:22:34.667  3282  3339 I jxcore-log: 
,03-24 22:22:34.825  3282  3339 I jxcore-log: # 28. should be able to call #startUpdateAdvertisingAndListening many times
03-24 22:22:34.825  3282  3339 I jxcore-log: 
,03-24 22:22:34.983  3282  3339 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 22:22:34.983  3282  3339 I jxcore-log: 
,03-24 22:22:34.987  3282  3339 I jxcore-log: DEBUG createNativeListener: listening 35833
03-24 22:22:34.987  3282  3339 I jxcore-log: 
,03-24 22:22:35.002  3282  3339 I io.jxcore.node.ConnectionHelper: start: Port number: 35833, start advertisements: true
,03-24 22:22:35.002  3282  3339 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 22:22:35.002  3282  3339 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-24 22:22:35.002  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-24 22:22:35.007  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-24 22:22:35.007  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 22:22:35.007  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 22:22:35.007  3282  3339 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 22:22:35.012  2156  2396 D BtGatt.GattService: registerClient() - UUID=9438ab9b-d8fa-4072-93a7-b1ed6295c4ff
,03-24 22:22:35.013  2156  2219 D BtGatt.GattService: onClientRegistered() - UUID=9438ab9b-d8fa-4072-93a7-b1ed6295c4ff, clientIf=5
03-24 22:22:35.013  3282  3299 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 22:22:35.014  2156  2175 D BtGatt.GattService: start scan with filters
,03-24 22:22:35.015  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 22:22:35.015  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 22:22:35.015  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-24 22:22:35.015  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-24 22:22:35.015  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 22:22:35.016  2156  2229 D BtGatt.ScanManager: handling starting scan
,03-24 22:22:35.016  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 22:22:35.016  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 22:22:35.016  3282  3282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 22:22:35.017  3282  3339 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
,03-24 22:22:35.018  3282  3339 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 22:22:35.018  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 22:22:35.018  3282  3339 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-24 22:22:35.020  2156  2219 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 22:22:35.021  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 22:22:35.023  2156  2219 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15,
03-24 22:22:35.023  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:22:35.024  2156  2229 D BtGatt.ScanManager: Starting BLE batch scan
03-24 22:22:35.024  2156  2229 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 22:22:35.026  2156  2175 D BtGatt.GattService: registerClient() - UUID=fca3cbd9-431c-4098-acd0-b3e1abdc0f3e
03-24 22:22:35.027  2156  2219 D BtGatt.GattService: onClientRegistered() - UUID=fca3cbd9-431c-4098-acd0-b3e1abdc0f3e, clientIf=6
03-24 22:22:35.027  3282  3300 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-24 22:22:35.027  2156  2219 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 22:22:35.028  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:22:35.029  2156  2219 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 22:22:35.029  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 22:22:35.034  2156  2228 D BtGatt.AdvertiseManager: message : 0,
,03-24 22:22:35.040  2156  2228 D BtGatt.AdvertiseManager: starting multi advertising,
,03-24 22:22:35.045  2156  2219 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0,
,03-24 22:22:35.049  2156  2219 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 22:22:35.051  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-24 22:22:35.051  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 22:22:35.052   821  1082 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 22:22:35.056  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 22:22:35.056  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-24 22:22:35.056  3282  3339 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-24 22:22:35.057  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-24 22:22:35.058  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-24 22:22:35.059  3282  3339 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-24 22:22:35.059  3282  3339 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-24 22:22:35.059  3282  3339 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-24 22:22:35.059  3282  3339 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 22:22:35.059  3282  3282 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-24 22:22:35.060  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 22:22:35.060  3282  3282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-24 22:22:35.060  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-24 22:22:35.060  3282  3282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-24 22:22:35.061  3282  3282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-24 22:22:35.061  3282  3282 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 22:22:35.061  3282  3282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 22:22:35.061  3282  3282 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-24 22:22:35.061  3282  3282 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 22:22:35.062  3282  3282 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-24 22:22:35.062  3282  3282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 22:22:35.065   821  1416 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 22:22:35.067  3282  3739 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-24 22:22:35.073  3282  3739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-24 22:22:35.087  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 22:22:35.087  3282  3339 I jxcore-log: 
,03-24 22:22:35.091  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 22:22:35.091  3282  3339 I jxcore-log: 
,03-24 22:22:35.093  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-24 22:22:35.093  3282  3339 I jxcore-log: 
,03-24 22:22:35.098  3282  3339 I jxcore-log: ok 101 error should be null
03-24 22:22:35.098  3282  3339 I jxcore-log: 
,03-24 22:22:35.100  3282  3339 I jxcore-log: ok 102 error should be null
03-24 22:22:35.100  3282  3339 I jxcore-log: 
,03-24 22:22:35.110  3282  3339 I io.jxcore.node.ConnectionHelper: start: Port number: 35833, start advertisements: true
03-24 22:22:35.110  3282  3339 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-24 22:22:35.110  3282  3339 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-24 22:22:35.110  3282  3339 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 22:22:35.111  3282  3339 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 22:22:35.120  3282  3339 I jxcore-log: ok 103 error should be null
03-24 22:22:35.120  3282  3339 I jxcore-log: 
03-24 22:22:35.120  3282  3339 I jxcore-log: ok 104 error should be null
03-24 22:22:35.120  3282  3339 I jxcore-log: 
,03-24 22:22:35.127  3282  3339 I jxcore-log: # teardown
03-24 22:22:35.127  3282  3339 I jxcore-log: 
,03-24 22:22:35.533  2156  2156 D BtGatt.ScanManager: awakened up at time 219320,
,03-24 22:22:35.535  2156  2229 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5,
,03-24 22:22:35.546  2156  2219 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
,03-24 22:22:35.546  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:22:35.546  2156  2219 D BtGatt.GattService: current time is 219333844290
03-24 22:22:35.547  2156  2219 D BtGatt.GattService: Batch record : [-75, -37, -121, -67, -92, 69, 1, -128, -77, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -63, 7, 0, 0, 0, -127, -59, 40, 32, -73, -32, 1, -128, -63, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0],
03-24 22:22:35.548  2156  2219 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,03-24 22:22:35.552  2156  2219 D BtGatt.GattService: ScanRecord : [],
03-24 22:22:35.553  2156  2219 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
,03-24 22:22:35.562  3282  3282 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> E0:DB:10:14:E2:C0], added - the peer count is 1
,03-24 22:22:35.563  3282  3282 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 2
03-24 22:22:35.563  3282  3282 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> E0:DB:10:14:E2:C0], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 
03-24 22:22:35.564  3282  3282 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
,03-24 22:22:35.566  3282  3339 I jxcore-log: DEBUG createPeerListener: createPeerListener
03-24 22:22:35.566  3282  3339 I jxcore-log: 
,03-24 22:22:35.570  3282  3339 I jxcore-log: DEBUG createPeerListener: pleaseConnect= false
,03-24 22:22:35.570  3282  3339 I jxcore-log: 
,03-24 22:22:35.573  3282  3339 I jxcore-log: DEBUG createPeerListener: createPeerListener
,03-24 22:22:35.573  3282  3339 I jxcore-log: 
03-24 22:22:35.575  3282  3339 I jxcore-log: DEBUG createPeerListener: pleaseConnect= false
03-24 22:22:35.575  3282  3339 I jxcore-log: 
,03-24 22:22:35.798  3282  3339 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 22:22:35.799  3282  3339 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-24 22:22:35.799  3282  3339 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-24 22:22:35.799  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-24 22:22:35.799  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-24 22:22:35.803  3282  3339 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-24 22:22:35.803  3282  3739 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-24 22:22:35.803  3282  3739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-24 22:22:35.803  3282  3739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,03-24 22:22:35.804  3282  3282 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-24 22:22:35.804  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-24 22:22:35.805  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-24 22:22:35.805  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 22:22:35.805  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 22:22:35.805  3282  3282 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-24 22:22:35.805  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-24 22:22:35.805  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-24 22:22:35.808  2156  2175 D BtGatt.GattService: stopScan() - queue size =1
,03-24 22:22:35.810  2156  2219 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 22:22:35.810  2156  2396 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-24 22:22:35.810  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:22:35.810  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 22:22:35.810  2156  2229 D BtGatt.ScanManager: stopping BLe Batch
03-24 22:22:35.811  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 22:22:35.811  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-24 22:22:35.811  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-24 22:22:35.811  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
,03-24 22:22:35.811  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 22:22:35.812  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-24 22:22:35.814  2156  2219 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 22:22:35.814  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 22:22:35.814  2156  2229 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 22:22:35.816  2156  2228 D BtGatt.AdvertiseManager: message : 1
03-24 22:22:35.817  2156  2228 D BtGatt.AdvertiseManager: stop advertise for client 6
03-24 22:22:35.817  2156  2219 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-24 22:22:35.817  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:22:35.817  2156  2219 D BtGatt.GattService: current time is 219605103560
03-24 22:22:35.818  2156  2219 D BtGatt.GattService: Batch record : [-75, -37, -121, -67, -92, 69, 1, -128, -78, 3, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -62, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-24 22:22:35.818  2156  2219 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 22:22:35.819  2156  2219 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
,03-24 22:22:35.821  2156  2219 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 22:22:35.821  2156  2219 D BtGatt.GattService: Client app is not null!
,03-24 22:22:35.832  2156  2175 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-24 22:22:35.833  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 22:22:35.833  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-24 22:22:35.833  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-24 22:22:35.833  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-24 22:22:35.833  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,03-24 22:22:35.833  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 22:22:35.833  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 22:22:35.833  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-24 22:22:35.834  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-24 22:22:35.834  3282  3339 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-24 22:22:35.834  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 22:22:35.834  3282  3282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 22:22:35.834  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 22:22:35.834  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-24 22:22:35.841  3282  3282 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-24 22:22:35.841   821  1415 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 22:22:35.841  3282  3339 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-24 22:22:35.841  3282  3339 I jxcore-log: 
,03-24 22:22:35.847  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-24 22:22:35.848  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 22:22:35.848  3282  3282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 22:22:35.852  3282  3282 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-24 22:22:35.852  3282  3282 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 22:22:35.852  3282  3282 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 22:22:35.852  3282  3282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 22:22:35.852  3282  3282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 22:22:35.852  3282  3282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 22:22:35.853  3282  3339 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 22:22:35.853  3282  3339 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 22:22:35.853  3282  3339 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 22:22:35.856  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-24 22:22:35.856  3282  3339 I jxcore-log: 
,03-24 22:22:35.857  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 22:22:35.857  3282  3339 I jxcore-log: 
,03-24 22:22:35.859  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 22:22:35.859  3282  3339 I jxcore-log: 
,03-24 22:22:35.866  3282  3339 I jxcore-log: ok 105 error should be null
03-24 22:22:35.866  3282  3339 I jxcore-log: 
,03-24 22:22:35.866  3282  3339 I jxcore-log: ok 106 error should be null
03-24 22:22:35.866  3282  3339 I jxcore-log: 
,03-24 22:22:35.874  3282  3339 I jxcore-log: # setup
03-24 22:22:35.874  3282  3339 I jxcore-log: 
,03-24 22:22:36.160  3282  3339 I jxcore-log: # 29. should be able to call #stopAdvertisingAndListening many times
03-24 22:22:36.160  3282  3339 I jxcore-log: 
,03-24 22:22:36.320  3282  3339 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 22:22:36.320  3282  3339 I jxcore-log: 
,03-24 22:22:36.322  3282  3339 I jxcore-log: DEBUG createNativeListener: listening 47945
03-24 22:22:36.322  3282  3339 I jxcore-log: 
,03-24 22:22:36.327  3282  3339 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 22:22:36.328  3282  3339 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 22:22:36.328  3282  3339 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 22:22:36.330  3282  3339 I jxcore-log: ok 107 error should be null
03-24 22:22:36.330  3282  3339 I jxcore-log: 
03-24 22:22:36.331  3282  3339 I jxcore-log: ok 108 error should be null
03-24 22:22:36.331  3282  3339 I jxcore-log: 
,03-24 22:22:36.334  3282  3339 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 22:22:36.334  3282  3339 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 22:22:36.334  3282  3339 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 22:22:36.336  3282  3339 I jxcore-log: ok 109 error should be null
03-24 22:22:36.336  3282  3339 I jxcore-log: 
,03-24 22:22:36.337  3282  3339 I jxcore-log: ok 110 error should be null
03-24 22:22:36.337  3282  3339 I jxcore-log: 
,03-24 22:22:36.343  3282  3339 I jxcore-log: # teardown
03-24 22:22:36.343  3282  3339 I jxcore-log: 
,03-24 22:22:36.435  3282  3339 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 22:22:36.435  3282  3339 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 22:22:36.435  3282  3339 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 22:22:36.438  3282  3339 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 22:22:36.438  3282  3339 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 22:22:36.438  3282  3339 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 22:22:36.444  3282  3339 I jxcore-log: ok 111 error should be null
03-24 22:22:36.444  3282  3339 I jxcore-log: 
,03-24 22:22:36.445  3282  3339 I jxcore-log: ok 112 error should be null
03-24 22:22:36.445  3282  3339 I jxcore-log: 
,03-24 22:22:36.451  3282  3339 I jxcore-log: # setup
03-24 22:22:36.451  3282  3339 I jxcore-log: 
,03-24 22:22:36.544  3282  3339 I jxcore-log: # 30. #start should fail if called twice in a row
03-24 22:22:36.544  3282  3339 I jxcore-log: 
,03-24 22:22:36.690  3282  3339 I jxcore-log: DEBUG createNativeListener: creating native server,
03-24 22:22:36.690  3282  3339 I jxcore-log: 
,03-24 22:22:36.692  3282  3339 I jxcore-log: DEBUG createNativeListener: listening 35370
,03-24 22:22:36.692  3282  3339 I jxcore-log: 
03-24 22:22:36.694  3282  3339 I jxcore-log: ok 113 first call should succeed
,03-24 22:22:36.694  3282  3339 I jxcore-log: 
,03-24 22:22:36.695  3282  3339 I jxcore-log: ok 114 first call should succeed
03-24 22:22:36.695  3282  3339 I jxcore-log: 
03-24 22:22:36.698  3282  3339 I jxcore-log: ok 115 specific error should be returned
03-24 22:22:36.698  3282  3339 I jxcore-log: ,
,03-24 22:22:36.700  3282  3339 I jxcore-log: # teardown
03-24 22:22:36.700  3282  3339 I jxcore-log: 
,03-24 22:22:36.844  3282  3339 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 22:22:36.844  3282  3339 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 22:22:36.845  3282  3339 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 22:22:36.846  3282  3339 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 22:22:36.846  3282  3339 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 22:22:36.846  3282  3339 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 22:22:36.852  3282  3339 I jxcore-log: ok 116 error should be null
,03-24 22:22:36.852  3282  3339 I jxcore-log: 
03-24 22:22:36.852  3282  3339 I jxcore-log: ok 117 error should be null
03-24 22:22:36.852  3282  3339 I jxcore-log: 
,03-24 22:22:36.857  3282  3339 I jxcore-log: # setup
03-24 22:22:36.857  3282  3339 I jxcore-log: 
,03-24 22:22:36.957  3282  3339 I jxcore-log: # 31. does not emit duplicate discoveryAdvertisingStateUpdate
03-24 22:22:36.957  3282  3339 I jxcore-log: 
,03-24 22:22:37.128  3282  3339 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 22:22:37.128  3282  3339 I jxcore-log: 
,03-24 22:22:37.131  3282  3339 I jxcore-log: DEBUG createNativeListener: listening 50790
03-24 22:22:37.131  3282  3339 I jxcore-log: 
,03-24 22:22:37.139  3282  3339 I io.jxcore.node.ConnectionHelper: start: Port number: 35833, start advertisements: false
03-24 22:22:37.139  3282  3339 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-24 22:22:37.139  3282  3339 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 22:22:37.139  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-24 22:22:37.143  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-24 22:22:37.143  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 22:22:37.143  3282  3339 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 22:22:37.147  2156  2174 D BtGatt.GattService: registerClient() - UUID=e03a55e1-4aba-455c-acaf-dc3b3e366dd0
,03-24 22:22:37.147  2156  2219 D BtGatt.GattService: onClientRegistered() - UUID=e03a55e1-4aba-455c-acaf-dc3b3e366dd0, clientIf=5
,03-24 22:22:37.148  3282  3299 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-24 22:22:37.148  2156  2396 D BtGatt.GattService: start scan with filters
03-24 22:22:37.149  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 22:22:37.149  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 22:22:37.149  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-24 22:22:37.149  2156  2229 D BtGatt.ScanManager: handling starting scan
03-24 22:22:37.149  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,03-24 22:22:37.149  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 22:22:37.149  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 22:22:37.150  3282  3282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 22:22:37.150   821  1414 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 22:22:37.153  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-24 22:22:37.153  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 22:22:37.153  3282  3339 I io.jxcore.node.ConnectionHelper: start: OK
03-24 22:22:37.153  3282  3282 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 22:22:37.153  3282  3282 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 22:22:37.153  3282  3282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-24 22:22:37.158  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 22:22:37.158  3282  3339 I jxcore-log: 
,03-24 22:22:37.159  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 22:22:37.159  3282  3339 I jxcore-log: 
,03-24 22:22:37.171  3282  3339 I io.jxcore.node.ConnectionHelper: start: Port number: 50790, start advertisements: true
,03-24 22:22:37.171  3282  3339 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-24 22:22:37.171  3282  3339 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-24 22:22:37.171  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-24 22:22:37.174  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
03-24 22:22:37.175  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
,03-24 22:22:37.175  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 22:22:37.175  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 22:22:37.175  3282  3339 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 22:22:37.175  3282  3339 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-24 22:22:37.175  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 22:22:37.175  3282  3339 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-24 22:22:37.179  2156  2396 D BtGatt.GattService: registerClient() - UUID=3006d682-f4e0-401e-aede-a3a019ef2478
,03-24 22:22:37.252   821  1082 I art     : Explicit concurrent mark sweep GC freed 20392(937KB) AllocSpace objects, 5(551KB) LOS objects, 31% free, 34MB/50MB, paused 2.879ms total 95.057ms
03-24 22:22:37.253  2156  2219 D BtGatt.GattService: onClientRegistered() - UUID=3006d682-f4e0-401e-aede-a3a019ef2478, clientIf=6
03-24 22:22:37.254  2156  2219 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 22:22:37.254  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:22:37.254  3282  3300 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-24 22:22:37.255  2156  2219 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 22:22:37.255  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:22:37.256  2156  2229 D BtGatt.ScanManager: Starting BLE batch scan
03-24 22:22:37.256  2156  2229 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 22:22:37.256  2156  2228 D BtGatt.AdvertiseManager: message : 0
03-24 22:22:37.258  2156  2219 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,03-24 22:22:37.258  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:22:37.260  2156  2219 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 22:22:37.260  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 22:22:37.264  2156  2228 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 22:22:37.267  2156  2219 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 22:22:37.270  2156  2219 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 22:22:37.273  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,03-24 22:22:37.273  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-24 22:22:37.273  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 22:22:37.273  3282  3282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-24 22:22:37.274  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-24 22:22:37.274  3282  3282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-24 22:22:37.274  3282  3282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-24 22:22:37.274   821   836 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 22:22:37.280  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true,
03-24 22:22:37.281  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 22:22:37.281  3282  3339 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-24 22:22:37.281  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 22:22:37.281  3282  3282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-24 22:22:37.294  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-24 22:22:37.294  3282  3339 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-24 22:22:37.294  3282  3339 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-24 22:22:37.294  3282  3339 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-24 22:22:37.295  3282  3339 I io.jxcore.node.ConnectionHelper: start: OK
03-24 22:22:37.295  3282  3282 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-24 22:22:37.295  3282  3282 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 22:22:37.295  3282  3282 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,03-24 22:22:37.301  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-24 22:22:37.301  3282  3339 I jxcore-log: 
,03-24 22:22:37.304   821  1259 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 22:22:37.306  3282  3740 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-24 22:22:37.307  3282  3740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-24 22:22:37.309  3282  3339 I jxcore-log: ok 118 called only once
03-24 22:22:37.309  3282  3339 I jxcore-log: 
,03-24 22:22:37.309  3282  3339 I jxcore-log: ok 119 discovery state matches
03-24 22:22:37.309  3282  3339 I jxcore-log: 
,03-24 22:22:37.309  3282  3339 I jxcore-log: ok 120 advertising state matches
03-24 22:22:37.309  3282  3339 I jxcore-log: 
,03-24 22:22:37.316  3282  3339 I jxcore-log: # teardown
03-24 22:22:37.316  3282  3339 I jxcore-log: 
,03-24 22:22:38.271  2156  2156 D BtGatt.ScanManager: awakened up at time 222058
,03-24 22:22:38.273  2156  2229 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 22:22:38.283  2156  2219 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2,
03-24 22:22:38.283  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:22:38.284  2156  2219 D BtGatt.GattService: current time is 222071304288
03-24 22:22:38.284  2156  2219 D BtGatt.GattService: Batch record : [20, -48, -99, -31, 20, 105, 1, -128, -78, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -59, 3, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-24 22:22:38.285  2156  2219 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 22:22:38.285  2156  2219 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-24 22:22:38.288  3282  3282 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 1
,03-24 22:22:38.289  3282  3282 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> E0:DB:10:14:E2:C0], added - the peer count is 2,
03-24 22:22:38.289  3282  3282 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
03-24 22:22:38.290  3282  3282 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> E0:DB:10:14:E2:C0], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 
,03-24 22:22:38.304  3282  3339 I jxcore-log: DEBUG createPeerListener: createPeerListener,
03-24 22:22:38.304  3282  3339 I jxcore-log: 
,03-24 22:22:38.313  3282  3339 I jxcore-log: DEBUG createPeerListener: pleaseConnect= false,
03-24 22:22:38.313  3282  3339 I jxcore-log: 
,03-24 22:22:38.315  3282  3339 I jxcore-log: DEBUG createPeerListener: createPeerListener
03-24 22:22:38.315  3282  3339 I jxcore-log: 
,03-24 22:22:38.318  3282  3339 I jxcore-log: DEBUG createPeerListener: pleaseConnect= false
03-24 22:22:38.318  3282  3339 I jxcore-log: 
,03-24 22:22:38.969  3282  3339 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 22:22:38.969  3282  3339 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-24 22:22:38.969  3282  3339 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-24 22:22:38.969  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-24 22:22:38.969  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-24 22:22:38.971  3282  3339 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-24 22:22:38.972  3282  3740 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-24 22:22:38.972  3282  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-24 22:22:38.973  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-24 22:22:38.973  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,03-24 22:22:38.973  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 22:22:38.973  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 22:22:38.972  3282  3740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-24 22:22:38.973  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-24 22:22:38.973  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-24 22:22:38.973  3282  3282 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-24 22:22:38.974  3282  3282 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,03-24 22:22:38.979  2156  2396 D BtGatt.GattService: stopScan() - queue size =1
03-24 22:22:38.983  2156  2219 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 22:22:38.983  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:22:38.983  2156  2229 D BtGatt.ScanManager: stopping BLe Batch
03-24 22:22:38.984  2156  2174 D BtGatt.GattService: unregisterClient() - clientIf=5
03-24 22:22:38.985  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 22:22:38.985  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 22:22:38.985  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-24 22:22:38.985  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-24 22:22:38.985  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-24 22:22:38.985  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 22:22:38.985  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-24 22:22:38.986  2156  2219 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 22:22:38.986  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:22:38.986  2156  2229 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 22:22:38.989  2156  2228 D BtGatt.AdvertiseManager: message : 1
,03-24 22:22:38.989  2156  2228 D BtGatt.AdvertiseManager: stop advertise for client 6
03-24 22:22:38.991  2156  2219 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-24 22:22:38.991  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 22:22:38.992  2156  2219 D BtGatt.GattService: current time is 222779329549
03-24 22:22:38.992  2156  2219 D BtGatt.GattService: Batch record : [20, -48, -99, -31, 20, 105, 1, -128, -78, 4, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -59, 4, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-24 22:22:38.993  2156  2219 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 22:22:38.993  2156  2219 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
,03-24 22:22:38.995  2156  2219 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 22:22:38.995  2156  2219 D BtGatt.GattService: Client app is not null!
,03-24 22:22:38.996  2156  2396 D BtGatt.GattService: unregisterClient() - clientIf=6
03-24 22:22:38.996  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 22:22:38.996  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-24 22:22:38.996  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-24 22:22:38.997  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-24 22:22:38.997  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,03-24 22:22:38.997  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 22:22:38.997  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,03-24 22:22:38.997  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-24 22:22:38.997  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,03-24 22:22:38.997  3282  3339 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-24 22:22:38.997  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 22:22:38.998  3282  3282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 22:22:38.998  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 22:22:38.998  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-24 22:22:39.003  3282  3339 I jxcore-log: INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
03-24 22:22:39.003  3282  3339 I jxcore-log: 
03-24 22:22:39.004  3282  3339 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-24 22:22:39.004  3282  3339 I jxcore-log: 
03-24 22:22:39.006  3282  3282 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-24 22:22:39.007   821  1375 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 22:22:39.007  3282  3339 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-24 22:22:39.007  3282  3339 I jxcore-log: 
,03-24 22:22:39.015  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-24 22:22:39.016  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 22:22:39.016  3282  3282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 22:22:39.019  3282  3282 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-24 22:22:39.019  3282  3282 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-24 22:22:39.019  3282  3282 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 22:22:39.019  3282  3282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 22:22:39.019  3282  3282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 22:22:39.020  3282  3282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 22:22:39.020  3282  3339 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 22:22:39.020  3282  3339 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-24 22:22:39.020  3282  3339 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 22:22:39.022  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-24 22:22:39.022  3282  3339 I jxcore-log: 
03-24 22:22:39.023  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 22:22:39.023  3282  3339 I jxcore-log: 
,03-24 22:22:39.024  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 22:22:39.024  3282  3339 I jxcore-log: 
,03-24 22:22:39.029  3282  3339 I jxcore-log: ok 121 error should be null
03-24 22:22:39.029  3282  3339 I jxcore-log: 
,03-24 22:22:39.029  3282  3339 I jxcore-log: ok 122 error should be null
03-24 22:22:39.029  3282  3339 I jxcore-log: 
,03-24 22:22:39.034  3282  3339 I jxcore-log: # setup
03-24 22:22:39.034  3282  3339 I jxcore-log: 
,03-24 22:22:39.316  3282  3339 I jxcore-log: # 32. does not send duplicate availability changes
03-24 22:22:39.316  3282  3339 I jxcore-log: 
,03-24 22:22:39.510  3282  3339 I jxcore-log: ok 123 should be called once
03-24 22:22:39.510  3282  3339 I jxcore-log: 
03-24 22:22:39.511  3282  3339 I jxcore-log: ok 124 should not have been called more than once
03-24 22:22:39.511  3282  3339 I jxcore-log: 
,03-24 22:22:39.516  3282  3339 I jxcore-log: # teardown
03-24 22:22:39.516  3282  3339 I jxcore-log: 
,03-24 22:22:39.635  3282  3339 I jxcore-log: ok 125 error should be null
03-24 22:22:39.635  3282  3339 I jxcore-log: 
,03-24 22:22:39.636  3282  3339 I jxcore-log: ok 126 error should be null
03-24 22:22:39.636  3282  3339 I jxcore-log: 
,03-24 22:22:39.643  3282  3339 I jxcore-log: # setup
03-24 22:22:39.643  3282  3339 I jxcore-log: 
,03-24 22:22:39.744  3282  3339 I jxcore-log: # 33. can get the network status
03-24 22:22:39.744  3282  3339 I jxcore-log: 
,03-24 22:22:39.944  3282  3339 I jxcore-log: ok 127 network status should have certain non-empty properties
03-24 22:22:39.944  3282  3339 I jxcore-log: 
03-24 22:22:39.946  3282  3339 I jxcore-log: # teardown
03-24 22:22:39.946  3282  3339 I jxcore-log: 
,03-24 22:22:40.058  3282  3339 I jxcore-log: ok 128 error should be null
03-24 22:22:40.058  3282  3339 I jxcore-log: 
,03-24 22:22:40.059  3282  3339 I jxcore-log: ok 129 error should be null
03-24 22:22:40.059  3282  3339 I jxcore-log: 
,03-24 22:22:40.070  3282  3339 I jxcore-log: # setup
,03-24 22:22:40.070  3282  3339 I jxcore-log: 
,03-24 22:22:40.192  3282  3339 I jxcore-log: # 34. wifi peer is marked unavailable if announcements stop
03-24 22:22:40.192  3282  3339 I jxcore-log: 
,03-24 22:22:40.253  1234  1472 I Keyboard.Facilitator.LanguageModelFlusher: run()
03-24 22:22:40.253  1234  1472 I Keyboard.Facilitator: flushDynamicLanguageModels()
,03-24 22:22:40.292  1261  1261 I ConfigService: onCreate
,03-24 22:22:40.408  3282  3339 I jxcore-log: ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined
03-24 22:22:40.408  3282  3339 I jxcore-log: 
,03-24 22:22:40.437  3282  3339 I jxcore-log: ok 130 host address should match
03-24 22:22:40.437  3282  3339 I jxcore-log: 
03-24 22:22:40.438  3282  3339 I jxcore-log: ok 131 port should match
03-24 22:22:40.438  3282  3339 I jxcore-log: 
,03-24 22:22:40.724  2156  2221 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 22:22:42.404  3282  3339 I jxcore-log: ok 132 host address should be null
03-24 22:22:42.404  3282  3339 I jxcore-log: 
,03-24 22:22:42.406  3282  3339 I jxcore-log: ok 133 port should should be null
03-24 22:22:42.406  3282  3339 I jxcore-log: 
,03-24 22:22:42.426  3282  3339 I jxcore-log: # teardown
03-24 22:22:42.426  3282  3339 I jxcore-log: 
,03-24 22:22:42.584  3282  3339 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-24 22:22:42.584  3282  3339 I jxcore-log: 
,03-24 22:22:42.586  3282  3339 I jxcore-log: ok 134 error should be null
03-24 22:22:42.586  3282  3339 I jxcore-log: 
,03-24 22:22:42.586  3282  3339 I jxcore-log: ok 135 error should be null
03-24 22:22:42.586  3282  3339 I jxcore-log: 
,03-24 22:22:42.588  3282  3339 I jxcore-log: # setup
03-24 22:22:42.588  3282  3339 I jxcore-log: 
,03-24 22:22:42.715  3282  3339 I jxcore-log: # 35. Can call start/stopListeningForAdvertisements
03-24 22:22:42.715  3282  3339 I jxcore-log: 
,03-24 22:22:42.817  3282  3339 I io.jxcore.node.ConnectionHelper: start: Port number: 50790, start advertisements: false
03-24 22:22:42.817  3282  3339 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 22:22:42.817  3282  3339 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 22:22:42.818  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-24 22:22:42.826  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-24 22:22:42.827  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-24 22:22:42.827  3282  3339 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 22:22:42.836  2156  2174 D BtGatt.GattService: registerClient() - UUID=6ec2eec4-7167-47c5-960b-a08802a9799f
03-24 22:22:42.837  2156  2219 D BtGatt.GattService: onClientRegistered() - UUID=6ec2eec4-7167-47c5-960b-a08802a9799f, clientIf=5
03-24 22:22:42.838  3282  3299 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 22:22:42.839  2156  2397 D BtGatt.GattService: start scan with filters
,03-24 22:22:42.843  2156  2229 D BtGatt.ScanManager: handling starting scan
03-24 22:22:42.843  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-24 22:22:42.843  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 22:22:42.843  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-24 22:22:42.843  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-24 22:22:42.843  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 22:22:42.844  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 22:22:42.844  3282  3282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 22:22:42.846   821  1375 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 22:22:42.856  2156  2219 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,03-24 22:22:42.856  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 22:22:42.859  2156  2219 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 22:22:42.859  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:22:42.860  2156  2229 D BtGatt.ScanManager: Starting BLE batch scan
03-24 22:22:42.860  2156  2229 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-24 22:22:42.861  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-24 22:22:42.861  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 22:22:42.863  3282  3282 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,03-24 22:22:42.863  3282  3282 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-24 22:22:42.864  2156  2219 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,03-24 22:22:42.864  3282  3282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false,
03-24 22:22:42.864  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:22:42.865  3282  3339 I io.jxcore.node.ConnectionHelper: start: OK
03-24 22:22:42.866  2156  2219 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 22:22:42.866  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 22:22:42.871  3282  3339 I jxcore-log: ok 136 Can call startListeningForAdvertisements without error
03-24 22:22:42.871  3282  3339 I jxcore-log: 
03-24 22:22:42.873  3282  3339 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 22:22:42.873  3282  3339 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only,
03-24 22:22:42.873  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-24 22:22:42.873  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-24 22:22:42.875  2156  2174 D BtGatt.GattService: stopScan() - queue size =1
03-24 22:22:42.876  2156  2397 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-24 22:22:42.877  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
,03-24 22:22:42.877  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-24 22:22:42.877  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-24 22:22:42.878  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-24 22:22:42.878  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,03-24 22:22:42.878  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 22:22:42.878  2156  2219 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 22:22:42.878  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 22:22:42.878  2156  2229 D BtGatt.ScanManager: stopping BLe Batch
03-24 22:22:42.880  3282  3282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 22:22:42.880  3282  3282 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-24 22:22:42.880  3282  3282 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 22:22:42.881  2156  2219 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 22:22:42.881  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 22:22:42.881  2156  2229 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 22:22:42.882  2156  2219 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 22:22:42.882  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 22:22:42.884  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 22:22:42.884  3282  3339 I jxcore-log: 
,03-24 22:22:42.886  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
,03-24 22:22:42.886  3282  3339 I jxcore-log: 
03-24 22:22:42.888  3282  3339 I jxcore-log: ok 137 Can call stopListeningForAdvertisements without error
03-24 22:22:42.888  3282  3339 I jxcore-log: 
,03-24 22:22:42.894  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
,03-24 22:22:42.894  3282  3339 I jxcore-log: 
,03-24 22:22:42.895  3282  3339 I jxcore-log: # teardown
03-24 22:22:42.895  3282  3339 I jxcore-log: 
,03-24 22:22:43.077  3282  3339 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 22:22:43.077  3282  3339 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 22:22:43.077  3282  3339 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 22:22:43.084  3282  3339 I jxcore-log: ok 138 Should be able to call stopListeningForAdvertisments in teardown
,03-24 22:22:43.084  3282  3339 I jxcore-log: 
03-24 22:22:43.085  3282  3339 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 22:22:43.085  3282  3339 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
03-24 22:22:43.085  3282  3339 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
03-24 22:22:43.086  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-24 22:22:43.086  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...,
03-24 22:22:43.086  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,03-24 22:22:43.086  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 22:22:43.088  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-24 22:22:43.089  3282  3339 D BluetoothLeScanner: could not find callback wrapper,
03-24 22:22:43.089  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 22:22:43.090  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-24 22:22:43.090  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped,
03-24 22:22:43.090  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-24 22:22:43.091  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-24 22:22:43.092  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,03-24 22:22:43.092  3282  3282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 22:22:43.092  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 22:22:43.092  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-24 22:22:43.103  3282  3282 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-24 22:22:43.103   821  1375 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 22:22:43.111  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-24 22:22:43.113  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0,
03-24 22:22:43.113  3282  3282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 22:22:43.121  3282  3282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false,
03-24 22:22:43.121  3282  3282 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 22:22:43.121  3282  3282 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-24 22:22:43.126  3282  3339 I jxcore-log: ok 139 Should be able to call stopAdvertisingAndListening in teardown,
03-24 22:22:43.126  3282  3339 I jxcore-log: 
,03-24 22:22:43.137  3282  3339 I jxcore-log: # setup,
03-24 22:22:43.137  3282  3339 I jxcore-log: 
03-24 22:22:43.139  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 22:22:43.139  3282  3339 I jxcore-log: 
,03-24 22:22:43.265  3282  3339 I jxcore-log: # 36. Calling startListeningForAdvertisements twice is NOT an error
03-24 22:22:43.265  3282  3339 I jxcore-log: 
,03-24 22:22:43.454  3282  3339 I io.jxcore.node.ConnectionHelper: start: Port number: 50790, start advertisements: false
,03-24 22:22:43.454  3282  3339 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 22:22:43.455  3282  3339 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 22:22:43.455  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-24 22:22:43.462  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 22:22:43.462  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 22:22:43.463  3282  3339 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 22:22:43.471  2156  2397 D BtGatt.GattService: registerClient() - UUID=b27d5b91-fa2d-404f-9a8c-b575be22f83e,
03-24 22:22:43.472  2156  2219 D BtGatt.GattService: onClientRegistered() - UUID=b27d5b91-fa2d-404f-9a8c-b575be22f83e, clientIf=5
,03-24 22:22:43.472  3282  3299 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 22:22:43.473  2156  2174 D BtGatt.GattService: start scan with filters
,03-24 22:22:43.476  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-24 22:22:43.476  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 22:22:43.476  2156  2229 D BtGatt.ScanManager: handling starting scan
03-24 22:22:43.476  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,03-24 22:22:43.476  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-24 22:22:43.476  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
,03-24 22:22:43.477  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK,
03-24 22:22:43.477  3282  3282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false,
03-24 22:22:43.478   821  1416 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 22:22:43.480  2156  2219 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 22:22:43.480  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:22:43.482  2156  2219 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 22:22:43.483  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:22:43.483  2156  2229 D BtGatt.ScanManager: Starting BLE batch scan
03-24 22:22:43.483  2156  2229 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-24 22:22:43.486  2156  2219 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 22:22:43.486  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:22:43.487  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 22:22:43.488  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 22:22:43.488  3282  3339 I io.jxcore.node.ConnectionHelper: start: OK
03-24 22:22:43.488  3282  3282 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 22:22:43.488  3282  3282 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 22:22:43.489  3282  3282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 22:22:43.489  2156  2219 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 22:22:43.489  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 22:22:43.495  3282  3339 I jxcore-log: ok 140 Can call startListeningForAdvertisements without error
03-24 22:22:43.495  3282  3339 I jxcore-log: 
,03-24 22:22:43.501  3282  3339 I io.jxcore.node.ConnectionHelper: start: Port number: 50790, start advertisements: false
,03-24 22:22:43.501  3282  3339 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 22:22:43.501  3282  3339 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 22:22:43.502  3282  3339 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 22:22:43.502  3282  3339 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 22:22:43.505  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 22:22:43.505  3282  3339 I jxcore-log: 
,03-24 22:22:43.507  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 22:22:43.507  3282  3339 I jxcore-log: 
,03-24 22:22:43.511  3282  3339 I jxcore-log: ok 141 Can call startListeningForAdvertisements twice without error
03-24 22:22:43.511  3282  3339 I jxcore-log: 
,03-24 22:22:43.523  3282  3339 I jxcore-log: # teardown
03-24 22:22:43.523  3282  3339 I jxcore-log: 
,03-24 22:22:43.729  3282  3339 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 22:22:43.730  3282  3339 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 22:22:43.730  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,03-24 22:22:43.730  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-24 22:22:43.734  2156  2397 D BtGatt.GattService: stopScan() - queue size =1
,03-24 22:22:43.735  2156  2174 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-24 22:22:43.737  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-24 22:22:43.739  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-24 22:22:43.739  2156  2219 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 22:22:43.739  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:22:43.739  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-24 22:22:43.740  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,03-24 22:22:43.740  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-24 22:22:43.740  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 22:22:43.740  2156  2229 D BtGatt.ScanManager: stopping BLe Batch
03-24 22:22:43.741  3282  3282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false,
03-24 22:22:43.741  3282  3282 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 22:22:43.741  3282  3282 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 22:22:43.745  2156  2219 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,03-24 22:22:43.745  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:22:43.745  2156  2229 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 22:22:43.747  2156  2219 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 22:22:43.747  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:22:43.749  3282  3339 I jxcore-log: ok 142 Should be able to call stopListeningForAdvertisments in teardown
03-24 22:22:43.749  3282  3339 I jxcore-log: 
03-24 22:22:43.751  3282  3339 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-24 22:22:43.751  3282  3339 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-24 22:22:43.751  3282  3339 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
03-24 22:22:43.751  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
03-24 22:22:43.751  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-24 22:22:43.751  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 22:22:43.751  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode,
03-24 22:22:43.751  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-24 22:22:43.756  3282  3339 D BluetoothLeScanner: could not find callback wrapper
03-24 22:22:43.757  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-24 22:22:43.759  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-24 22:22:43.760  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped,
,03-24 22:22:43.760  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...,
03-24 22:22:43.761  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-24 22:22:43.761  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,03-24 22:22:43.762  3282  3282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
,03-24 22:22:43.762  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 22:22:43.762  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-24 22:22:43.763  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
,03-24 22:22:43.763  3282  3339 I jxcore-log: 
,03-24 22:22:43.768  3282  3282 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-24 22:22:43.769   821  1082 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 22:22:43.777  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
,03-24 22:22:43.778  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 22:22:43.778  3282  3282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 22:22:43.782  3282  3282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-24 22:22:43.782  3282  3282 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 22:22:43.782  3282  3282 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 22:22:43.784  3282  3339 I jxcore-log: ok 143 Should be able to call stopAdvertisingAndListening in teardown
03-24 22:22:43.784  3282  3339 I jxcore-log: 
,03-24 22:22:43.790  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 22:22:43.790  3282  3339 I jxcore-log: 
,03-24 22:22:43.792  3282  3339 I jxcore-log: # setup
03-24 22:22:43.792  3282  3339 I jxcore-log: 
,03-24 22:22:43.954  3282  3339 I jxcore-log: # 37. Can call start/stopUpdateAdvertisingAndListening
03-24 22:22:43.954  3282  3339 I jxcore-log: 
,03-24 22:22:44.089  3282  3339 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: true
03-24 22:22:44.089  3282  3339 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-24 22:22:44.089  3282  3339 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-24 22:22:44.089  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-24 22:22:44.095  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-24 22:22:44.095  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 22:22:44.095  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 22:22:44.095  3282  3339 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 22:22:44.101  2156  2397 D BtGatt.GattService: registerClient() - UUID=d612bda7-08ae-4b51-8d7b-cd883e88e880
,03-24 22:22:44.101  2156  2219 D BtGatt.GattService: onClientRegistered() - UUID=d612bda7-08ae-4b51-8d7b-cd883e88e880, clientIf=5
,03-24 22:22:44.102  3282  3299 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-24 22:22:44.102  2156  2175 D BtGatt.GattService: start scan with filters
,03-24 22:22:44.103  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 22:22:44.103  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 22:22:44.103  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-24 22:22:44.103  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-24 22:22:44.103  2156  2229 D BtGatt.ScanManager: handling starting scan
03-24 22:22:44.104  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
,03-24 22:22:44.104  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 22:22:44.104  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 22:22:44.104  3282  3282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 22:22:44.104  3282  3339 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 22:22:44.105  3282  3339 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 22:22:44.105  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 22:22:44.105  3282  3339 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-24 22:22:44.112  2156  2219 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 22:22:44.112  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 22:22:44.114  2156  2219 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 22:22:44.115  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:22:44.115  2156  2175 D BtGatt.GattService: registerClient() - UUID=84f27ef6-63fe-4efb-88d2-734cb9448ff2
,03-24 22:22:44.115  2156  2219 D BtGatt.GattService: onClientRegistered() - UUID=84f27ef6-63fe-4efb-88d2-734cb9448ff2, clientIf=6
03-24 22:22:44.115  2156  2229 D BtGatt.ScanManager: Starting BLE batch scan
03-24 22:22:44.115  2156  2229 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 22:22:44.116  3282  3300 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-24 22:22:44.118  2156  2228 D BtGatt.AdvertiseManager: message : 0
,03-24 22:22:44.119  2156  2219 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 22:22:44.119  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:22:44.121  2156  2219 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 22:22:44.121  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 22:22:44.124  2156  2228 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 22:22:44.128  2156  2219 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 22:22:44.130  2156  2219 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 22:22:44.131  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-24 22:22:44.131  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-24 22:22:44.132   821  1393 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 22:22:44.138  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-24 22:22:44.138  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 22:22:44.138  3282  3339 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-24 22:22:44.138  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 22:22:44.139  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-24 22:22:44.140  3282  3339 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-24 22:22:44.140  3282  3339 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-24 22:22:44.140  3282  3339 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-24 22:22:44.140  3282  3339 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 22:22:44.141  3282  3282 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-24 22:22:44.141   821   837 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 22:22:44.141  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 22:22:44.142  3282  3282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-24 22:22:44.142  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-24 22:22:44.142  3282  3282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-24 22:22:44.142  3282  3282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-24 22:22:44.143  3282  3282 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 22:22:44.143  3282  3282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 22:22:44.143  3282  3282 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-24 22:22:44.143  3282  3282 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 22:22:44.144  3282  3282 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-24 22:22:44.144  3282  3282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-24 22:22:44.147  3282  3743 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-24 22:22:44.148  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 22:22:44.148  3282  3339 I jxcore-log: 
,03-24 22:22:44.153  3282  3339 I jxcore-log: ok 144 Can call startUpdateAdvertisingAndListening without error
03-24 22:22:44.153  3282  3339 I jxcore-log: 
03-24 22:22:44.153  3282  3743 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-24 22:22:44.154  3282  3339 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-24 22:22:44.154  3282  3339 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-24 22:22:44.154  3282  3339 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,03-24 22:22:44.154  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,03-24 22:22:44.154  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,03-24 22:22:44.154  3282  3339 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-24 22:22:44.154  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-24 22:22:44.154  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-24 22:22:44.154  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,03-24 22:22:44.154  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 22:22:44.154  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-24 22:22:44.154  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-24 22:22:44.155  3282  3743 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-24 22:22:44.155  3282  3743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread,
03-24 22:22:44.155  3282  3743 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-24 22:22:44.156  2156  2397 D BtGatt.GattService: stopScan() - queue size =1
03-24 22:22:44.157  2156  2175 D BtGatt.GattService: unregisterClient() - clientIf=5
03-24 22:22:44.157  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 22:22:44.157  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 22:22:44.157  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-24 22:22:44.158  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-24 22:22:44.158  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-24 22:22:44.158  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 22:22:44.158  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-24 22:22:44.158  2156  2219 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 22:22:44.158  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:22:44.159  2156  2229 D BtGatt.ScanManager: stopping BLe Batch
03-24 22:22:44.160  2156  2228 D BtGatt.AdvertiseManager: message : 1
03-24 22:22:44.161  2156  2228 D BtGatt.AdvertiseManager: stop advertise for client 6
03-24 22:22:44.162  2156  2219 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 22:22:44.162  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:22:44.163  2156  2229 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 22:22:44.165  2156  2219 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,03-24 22:22:44.165  2156  2219 D BtGatt.GattService: Client app is not null!
03-24 22:22:44.166  2156  2397 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-24 22:22:44.167  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 22:22:44.167  2156  2219 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 22:22:44.167  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED,
03-24 22:22:44.167  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:22:44.167  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-24 22:22:44.167  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,03-24 22:22:44.167  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-24 22:22:44.167  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 22:22:44.167  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 22:22:44.167  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-24 22:22:44.168  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-24 22:22:44.168  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,03-24 22:22:44.168  3282  3282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 22:22:44.168  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 22:22:44.168  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-24 22:22:44.172  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 22:22:44.172  3282  3339 I jxcore-log: 
03-24 22:22:44.175  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-24 22:22:44.175  3282  3339 I jxcore-log: 
,03-24 22:22:44.176  3282  3282 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-24 22:22:44.176   821  1370 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 22:22:44.182  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
03-24 22:22:44.183  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 22:22:44.183  3282  3282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 22:22:44.194  3282  3282 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-24 22:22:44.194  3282  3282 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,03-24 22:22:44.195  3282  3282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 22:22:44.195  3282  3282 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 22:22:44.195  3282  3282 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 22:22:44.195  3282  3282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-24 22:22:44.195  3282  3282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false,
03-24 22:22:44.195  3282  3282 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-24 22:22:44.197  3282  3339 I jxcore-log: ok 145 Can call stopAdvertisingAndListening without error
03-24 22:22:44.197  3282  3339 I jxcore-log: 
03-24 22:22:44.203  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
,03-24 22:22:44.203  3282  3339 I jxcore-log: 
,03-24 22:22:44.204  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 22:22:44.204  3282  3339 I jxcore-log: 
03-24 22:22:44.205  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 22:22:44.205  3282  3339 I jxcore-log: 
,03-24 22:22:44.206  3282  3339 I jxcore-log: # teardown
,03-24 22:22:44.206  3282  3339 I jxcore-log: 
,03-24 22:22:44.638  3282  3339 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 22:22:44.639  3282  3339 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 22:22:44.639  3282  3339 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 22:22:44.647  3282  3339 I jxcore-log: ok 146 Should be able to call stopListeningForAdvertisments in teardown
03-24 22:22:44.647  3282  3339 I jxcore-log: 
,03-24 22:22:44.649  3282  3339 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 22:22:44.649  3282  3339 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 22:22:44.649  3282  3339 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 22:22:44.654  3282  3339 I jxcore-log: ok 147 Should be able to call stopAdvertisingAndListening in teardown
03-24 22:22:44.654  3282  3339 I jxcore-log: 
,03-24 22:22:44.659  3282  3339 I jxcore-log: # setup
03-24 22:22:44.659  3282  3339 I jxcore-log: 
,03-24 22:22:44.793  3282  3339 I jxcore-log: # 38. Calling startUpdateAdvertisingAndListening twice is NOT an error
03-24 22:22:44.793  3282  3339 I jxcore-log: 
,03-24 22:22:44.948  3282  3339 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: true,
,03-24 22:22:44.948  3282  3339 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 22:22:44.949  3282  3339 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-24 22:22:44.949  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-24 22:22:44.958  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-24 22:22:44.958  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 22:22:44.958  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 22:22:44.958  3282  3339 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 22:22:44.968  2156  2397 D BtGatt.GattService: registerClient() - UUID=26e112de-d618-4e9b-a0a7-fcaef25722c3
,03-24 22:22:44.969  2156  2219 D BtGatt.GattService: onClientRegistered() - UUID=26e112de-d618-4e9b-a0a7-fcaef25722c3, clientIf=5
,03-24 22:22:44.970  3282  3300 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 22:22:44.971  2156  2175 D BtGatt.GattService: start scan with filters
,03-24 22:22:44.973  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 22:22:44.974  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 22:22:44.974  2156  2229 D BtGatt.ScanManager: handling starting scan
03-24 22:22:44.974  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,03-24 22:22:44.974  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-24 22:22:44.974  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 22:22:44.975  3282  3282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 22:22:44.976  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 22:22:44.976  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 22:22:44.976  3282  3339 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 22:22:44.977  3282  3339 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-24 22:22:44.977  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 22:22:44.977  3282  3339 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-24 22:22:44.980  2156  2219 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 22:22:44.980  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 22:22:44.983  2156  2219 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15,
03-24 22:22:44.983  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:22:44.983  2156  2229 D BtGatt.ScanManager: Starting BLE batch scan
03-24 22:22:44.983  2156  2229 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-24 22:22:44.988  2156  2219 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 22:22:44.988  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 22:22:44.991  2156  2219 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,03-24 22:22:44.991  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 22:22:44.992  2156  2175 D BtGatt.GattService: registerClient() - UUID=f8a9ca3f-a2d6-4d6e-870c-ff001a36db8a,
03-24 22:22:44.993  2156  2219 D BtGatt.GattService: onClientRegistered() - UUID=f8a9ca3f-a2d6-4d6e-870c-ff001a36db8a, clientIf=6
03-24 22:22:44.994  3282  3299 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-24 22:22:44.995  2156  2228 D BtGatt.AdvertiseManager: message : 0
,03-24 22:22:44.999  2156  2228 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 22:22:45.002  2156  2219 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0,
,03-24 22:22:45.005  2156  2219 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 22:22:45.006  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-24 22:22:45.006  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK,
03-24 22:22:45.006   821  1416 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 22:22:45.009  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-24 22:22:45.009  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 22:22:45.009  3282  3339 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections,
03-24 22:22:45.009  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-24 22:22:45.010  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-24 22:22:45.010  3282  3339 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-24 22:22:45.010  3282  3339 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-24 22:22:45.010  3282  3339 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-24 22:22:45.011  3282  3282 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,03-24 22:22:45.011  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 22:22:45.011  3282  3282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-24 22:22:45.011  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-24 22:22:45.011  3282  3282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-24 22:22:45.011  3282  3282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
,03-24 22:22:45.011  3282  3282 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 22:22:45.011  3282  3282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 22:22:45.011  3282  3282 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything,
03-24 22:22:45.011  3282  3282 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 22:22:45.011  3282  3282 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-24 22:22:45.012  3282  3282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-24 22:22:45.012  3282  3339 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 22:22:45.013   821  1370 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 22:22:45.014  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 22:22:45.014  3282  3339 I jxcore-log: ,
03-24 22:22:45.015  3282  3744 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-24 22:22:45.016  3282  3339 I jxcore-log: ok 148 Can call startUpdateAdvertisingAndListening without error
03-24 22:22:45.016  3282  3339 I jxcore-log: 
,03-24 22:22:45.020  3282  3339 I io.jxcore.node.ConnectionHelper: start: Port number: 4243, start advertisements: true
,03-24 22:22:45.020  3282  3339 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 22:22:45.020  3282  3339 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-24 22:22:45.020  3282  3339 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 22:22:45.020  3282  3744 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-24 22:22:45.020  3282  3339 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 22:22:45.021  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 22:22:45.021  3282  3339 I jxcore-log: 
03-24 22:22:45.022  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-24 22:22:45.022  3282  3339 I jxcore-log: 
,03-24 22:22:45.024  3282  3339 I jxcore-log: ok 149 Can call startUpdateAdvertisingAndListening twice without error
,03-24 22:22:45.024  3282  3339 I jxcore-log: 
,03-24 22:22:45.030  3282  3339 I jxcore-log: # teardown
,03-24 22:22:45.030  3282  3339 I jxcore-log: 
,03-24 22:22:45.389  1261  1261 I ConfigService: onDestroy
,03-24 22:22:45.497  2156  2156 D BtGatt.ScanManager: awakened up at time 229284
03-24 22:22:45.499  2156  2229 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 22:22:45.508  2156  2219 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,03-24 22:22:45.508  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
03-24 22:22:45.509  2156  2219 D BtGatt.GattService: current time is 229296433609
03-24 22:22:45.509  2156  2219 D BtGatt.GattService: Batch record : [87, 62, 2, -70, 126, 98, 1, -128, -78, 4, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -66, 3, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-24 22:22:45.510  2156  2219 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81],
03-24 22:22:45.510  2156  2219 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-24 22:22:45.514  3282  3282 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> E0:DB:10:14:E2:C0], added - the peer count is 1
,03-24 22:22:45.515  3282  3282 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 2
03-24 22:22:45.515  3282  3282 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> E0:DB:10:14:E2:C0], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 
,03-24 22:22:45.516  3282  3282 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
,03-24 22:22:45.523  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
03-24 22:22:45.523  3282  3339 I jxcore-log: 
,03-24 22:22:45.527  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
03-24 22:22:45.527  3282  3339 I jxcore-log: 
,03-24 22:22:45.614  3282  3339 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 22:22:45.614  3282  3339 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
03-24 22:22:45.615  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-24 22:22:45.615  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-24 22:22:45.619  2156  2396 D BtGatt.GattService: stopScan() - queue size =1
,03-24 22:22:45.621  2156  2174 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-24 22:22:45.623  2156  2219 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,03-24 22:22:45.623  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-24 22:22:45.623  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:22:45.624  2156  2229 D BtGatt.ScanManager: stopping BLe Batch
,03-24 22:22:45.623  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 22:22:45.625  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-24 22:22:45.625  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-24 22:22:45.625  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
,03-24 22:22:45.625  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 22:22:45.626  3282  3282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 22:22:45.626  3282  3282 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
03-24 22:22:45.626  3282  3282 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 22:22:45.627  2156  2219 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0,
03-24 22:22:45.627  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:22:45.628  2156  2229 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 22:22:45.630  2156  2219 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
03-24 22:22:45.630  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 22:22:45.634  3282  3339 I jxcore-log: ok 150 Should be able to call stopListeningForAdvertisments in teardown
,03-24 22:22:45.634  3282  3339 I jxcore-log: 
,03-24 22:22:45.635  3282  3339 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-24 22:22:45.635  3282  3339 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
03-24 22:22:45.635  3282  3339 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-24 22:22:45.635  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-24 22:22:45.635  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-24 22:22:45.636  3282  3339 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-24 22:22:45.636  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-24 22:22:45.636  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-24 22:22:45.636  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 22:22:45.636  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,03-24 22:22:45.636  3282  3744 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-24 22:22:45.636  3282  3744 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-24 22:22:45.637  3282  3744 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-24 22:22:45.638  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-24 22:22:45.640  3282  3339 D BluetoothLeScanner: could not find callback wrapper
03-24 22:22:45.640  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-24 22:22:45.640  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-24 22:22:45.644  2156  2228 D BtGatt.AdvertiseManager: message : 1
,03-24 22:22:45.645  2156  2228 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-24 22:22:45.648  2156  2219 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,03-24 22:22:45.648  2156  2219 D BtGatt.GattService: Client app is not null!
,03-24 22:22:45.650  2156  2174 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-24 22:22:45.651  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-24 22:22:45.651  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,03-24 22:22:45.652  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-24 22:22:45.652  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-24 22:22:45.652  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,03-24 22:22:45.652  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 22:22:45.652  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 22:22:45.653  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-24 22:22:45.654  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
03-24 22:22:45.654  3282  3339 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-24 22:22:45.654  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 22:22:45.654  3282  3282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 22:22:45.654  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 22:22:45.654  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-24 22:22:45.661  3282  3282 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-24 22:22:45.662   821  1414 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 22:22:45.669  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-24 22:22:45.669  3282  3339 I jxcore-log: 
,03-24 22:22:45.672  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-24 22:22:45.673  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 22:22:45.673  3282  3282 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-24 22:22:45.673  3282  3282 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-24 22:22:45.673  3282  3282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 22:22:45.677  3282  3282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false,
,03-24 22:22:45.678  3282  3282 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
03-24 22:22:45.678  3282  3282 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-24 22:22:45.678  3282  3282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 22:22:45.678  3282  3282 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-24 22:22:45.680  3282  3339 I jxcore-log: ok 151 Should be able to call stopAdvertisingAndListening in teardown
03-24 22:22:45.680  3282  3339 I jxcore-log: 
,03-24 22:22:45.689  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false},
03-24 22:22:45.689  3282  3339 I jxcore-log: 
,03-24 22:22:45.691  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 22:22:45.691  3282  3339 I jxcore-log: 
,03-24 22:22:45.692  3282  3339 I jxcore-log: # setup,
03-24 22:22:45.692  3282  3339 I jxcore-log: 
,03-24 22:22:46.090  3282  3339 I jxcore-log: # 39. peerAvailabilityChange is called,
03-24 22:22:46.090  3282  3339 I jxcore-log: 
,03-24 22:22:46.320  3282  3339 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: true
,03-24 22:22:46.320  3282  3339 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 22:22:46.320  3282  3339 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-24 22:22:46.320  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-24 22:22:46.329  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-24 22:22:46.330  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 22:22:46.330  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 22:22:46.330  3282  3339 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 22:22:46.339  2156  2174 D BtGatt.GattService: registerClient() - UUID=c81f46da-17d4-42c9-a91e-88f3f83c8297
,03-24 22:22:46.340  2156  2219 D BtGatt.GattService: onClientRegistered() - UUID=c81f46da-17d4-42c9-a91e-88f3f83c8297, clientIf=5
,03-24 22:22:46.341  3282  3300 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 22:22:46.342  2156  2397 D BtGatt.GattService: start scan with filters
,03-24 22:22:46.345  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-24 22:22:46.345  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 22:22:46.345  2156  2229 D BtGatt.ScanManager: handling starting scan
03-24 22:22:46.345  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-24 22:22:46.345  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-24 22:22:46.346  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 22:22:46.346  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,03-24 22:22:46.346  3282  3282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 22:22:46.346  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 22:22:46.347  3282  3339 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 22:22:46.347  3282  3339 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 22:22:46.348  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-24 22:22:46.348  3282  3339 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-24 22:22:46.350  2156  2219 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 22:22:46.350  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:22:46.353  2156  2219 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 22:22:46.353  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
03-24 22:22:46.353  2156  2229 D BtGatt.ScanManager: Starting BLE batch scan
,03-24 22:22:46.354  2156  2229 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-24 22:22:46.358  2156  2219 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 22:22:46.358  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:22:46.361  2156  2219 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 22:22:46.361  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 22:22:46.364  2156  2397 D BtGatt.GattService: registerClient() - UUID=59d20c6e-7797-4911-8852-dbc9dce5aec1
03-24 22:22:46.364  2156  2219 D BtGatt.GattService: onClientRegistered() - UUID=59d20c6e-7797-4911-8852-dbc9dce5aec1, clientIf=6
03-24 22:22:46.366  3282  3299 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-24 22:22:46.371  2156  2228 D BtGatt.AdvertiseManager: message : 0
,03-24 22:22:46.377  2156  2228 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 22:22:46.381  2156  2219 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 22:22:46.384  2156  2219 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0,
,03-24 22:22:46.386  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-24 22:22:46.386  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-24 22:22:46.386   821  1082 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 22:22:46.394  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-24 22:22:46.395  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 22:22:46.395  3282  3339 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,03-24 22:22:46.395  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-24 22:22:46.397  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-24 22:22:46.399  3282  3339 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-24 22:22:46.400  3282  3339 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,03-24 22:22:46.400  3282  3339 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-24 22:22:46.401  3282  3339 I io.jxcore.node.ConnectionHelper: start: OK
03-24 22:22:46.401  3282  3282 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,03-24 22:22:46.401   821  1416 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 22:22:46.401  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 22:22:46.401  3282  3282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-24 22:22:46.401  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-24 22:22:46.402  3282  3282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-24 22:22:46.402  3282  3282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
,03-24 22:22:46.402  3282  3282 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 22:22:46.402  3282  3282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 22:22:46.402  3282  3282 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-24 22:22:46.402  3282  3282 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 22:22:46.403  3282  3282 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-24 22:22:46.403  3282  3282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 22:22:46.404  3282  3745 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-24 22:22:46.406  3282  3745 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-24 22:22:46.414  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 22:22:46.414  3282  3339 I jxcore-log: 
,03-24 22:22:46.427  3282  3339 I jxcore-log: ok 152 Can call startUpdateAdvertisingAndListeningwithout error
03-24 22:22:46.427  3282  3339 I jxcore-log: 
,03-24 22:22:46.432  3282  3339 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: false
03-24 22:22:46.432  3282  3339 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 22:22:46.432  3282  3339 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should affect listening to advertisements only
03-24 22:22:46.433  3282  3339 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 22:22:46.433  3282  3339 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 22:22:46.435  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
,03-24 22:22:46.435  3282  3339 I jxcore-log: 
,03-24 22:22:46.439  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
,03-24 22:22:46.439  3282  3339 I jxcore-log: 
,03-24 22:22:46.444  3282  3339 I jxcore-log: ok 153 Can call startListeningForAdvertisements without error,
03-24 22:22:46.444  3282  3339 I jxcore-log: 
,03-24 22:22:46.866  2156  2156 D BtGatt.ScanManager: awakened up at time 230653,
,03-24 22:22:46.870  2156  2229 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 22:22:46.879  2156  2219 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,03-24 22:22:46.880  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 22:22:46.880  2156  2219 D BtGatt.GattService: current time is 230667727983
,03-24 22:22:46.880  2156  2219 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -58, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0, -10, 1, 48, 47, 6, 69, 1, -128, -61, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,03-24 22:22:46.881  2156  2219 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
,03-24 22:22:46.882  2156  2219 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,03-24 22:22:46.885  3282  3282 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 1
,03-24 22:22:46.885  3282  3282 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> E0:DB:10:14:E2:C0], added - the peer count is 2
,03-24 22:22:46.886  3282  3282 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
03-24 22:22:46.886  3282  3282 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> E0:DB:10:14:E2:C0], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 
,03-24 22:22:46.891  3282  3339 I jxcore-log: ok 154 peers must be an array
03-24 22:22:46.891  3282  3339 I jxcore-log: 
03-24 22:22:46.892  3282  3339 I jxcore-log: ok 155 peers must not be zero-length
03-24 22:22:46.892  3282  3339 I jxcore-log: 
,03-24 22:22:46.894  3282  3339 I jxcore-log: ok 156 peer must have peerIdentifier
03-24 22:22:46.894  3282  3339 I jxcore-log: 
03-24 22:22:46.895  3282  3339 I jxcore-log: ok 157 peerIdentifier must be a string
03-24 22:22:46.895  3282  3339 I jxcore-log: 
03-24 22:22:46.897  3282  3339 I jxcore-log: ok 158 peer must have peerAvailable,
03-24 22:22:46.897  3282  3339 I jxcore-log: 
03-24 22:22:46.898  3282  3339 I jxcore-log: ok 159 peer must have pleaseConnect
03-24 22:22:46.898  3282  3339 I jxcore-log: 
,03-24 22:22:46.908  3282  3339 I jxcore-log: # teardown
03-24 22:22:46.908  3282  3339 I jxcore-log: 
,03-24 22:22:47.892  3282  3339 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 22:22:47.892  3282  3339 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
,03-24 22:22:47.892  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-24 22:22:47.893  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-24 22:22:47.897  2156  2156 D BtGatt.ScanManager: awakened up at time 231685
,03-24 22:22:47.901  2156  2396 D BtGatt.GattService: stopScan() - queue size =1
03-24 22:22:47.901  2156  2229 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 22:22:47.904  2156  2175 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-24 22:22:47.907  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
03-24 22:22:47.907  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 22:22:47.907  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-24 22:22:47.907  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-24 22:22:47.907  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-24 22:22:47.907  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-24 22:22:47.907  3282  3282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 22:22:47.908  3282  3282 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
03-24 22:22:47.908  3282  3282 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-24 22:22:47.910  2156  2219 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,03-24 22:22:47.910  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
03-24 22:22:47.910  2156  2219 D BtGatt.GattService: current time is 231698029337,
03-24 22:22:47.910  2156  2219 D BtGatt.GattService: Batch record : [-10, 1, 48, 47, 6, 69, 1, -128, -78, 3, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -59, 12, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-24 22:22:47.911  2156  2219 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 22:22:47.911  2156  2219 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
,03-24 22:22:47.911  2156  2219 E BtGatt.ContextMap: Context not found for ID 5
03-24 22:22:47.913  3282  3339 I jxcore-log: ok 160 Should be able to call stopListeningForAdvertisments in teardown
03-24 22:22:47.913  3282  3339 I jxcore-log: 
03-24 22:22:47.915  2156  2219 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 22:22:47.915  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:22:47.915  3282  3339 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 22:22:47.915  3282  3339 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
03-24 22:22:47.915  2156  2229 D BtGatt.ScanManager: stopping BLe Batch
03-24 22:22:47.915  3282  3339 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,03-24 22:22:47.915  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-24 22:22:47.915  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,03-24 22:22:47.916  3282  3339 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-24 22:22:47.917  2156  2219 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 22:22:47.917  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:22:47.917  2156  2229 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 22:22:47.917  3282  3745 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-24 22:22:47.917  3282  3745 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-24 22:22:47.917  3282  3745 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,03-24 22:22:47.917  3282  3282 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-24 22:22:47.918  2156  2219 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 22:22:47.918  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 22:22:47.918  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-24 22:22:47.919  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-24 22:22:47.919  3282  3282 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-24 22:22:47.919  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,03-24 22:22:47.919  3282  3282 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-24 22:22:47.919  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,03-24 22:22:47.919  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-24 22:22:47.920  3282  3339 D BluetoothLeScanner: could not find callback wrapper
03-24 22:22:47.920  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-24 22:22:47.921  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-24 22:22:47.924  2156  2228 D BtGatt.AdvertiseManager: message : 1
03-24 22:22:47.924  2156  2228 D BtGatt.AdvertiseManager: stop advertise for client 6
03-24 22:22:47.926  2156  2219 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 22:22:47.926  2156  2219 D BtGatt.GattService: Client app is not null!,
03-24 22:22:47.927  2156  2175 D BtGatt.GattService: unregisterClient() - clientIf=6
03-24 22:22:47.928  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 22:22:47.928  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-24 22:22:47.928  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,03-24 22:22:47.928  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-24 22:22:47.928  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-24 22:22:47.928  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 22:22:47.928  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 22:22:47.928  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-24 22:22:47.929  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-24 22:22:47.929  3282  3339 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-24 22:22:47.929  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,03-24 22:22:47.929  3282  3282 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-24 22:22:47.929  3282  3282 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 22:22:47.930  3282  3282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 22:22:47.930  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-24 22:22:47.930  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-24 22:22:47.933  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-24 22:22:47.933  3282  3339 I jxcore-log: 
03-24 22:22:47.935  3282  3282 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-24 22:22:47.936   821  1414 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 22:22:47.939  3282  3339 I jxcore-log: ok 161 Should be able to call stopAdvertisingAndListening in teardown
03-24 22:22:47.939  3282  3339 I jxcore-log: 
03-24 22:22:47.942  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-24 22:22:47.943  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 22:22:47.943  3282  3282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 22:22:47.947  3282  3282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false,
03-24 22:22:47.947  3282  3282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-24 22:22:47.950  3282  3339 I jxcore-log: # setup
03-24 22:22:47.950  3282  3339 I jxcore-log: 
,03-24 22:22:47.954  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
,03-24 22:22:47.954  3282  3339 I jxcore-log: 
03-24 22:22:47.955  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 22:22:47.955  3282  3339 I jxcore-log: 
,03-24 22:22:48.104  3282  3339 I jxcore-log: # 40. Can connect to a remote peer
03-24 22:22:48.104  3282  3339 I jxcore-log: 
,03-24 22:22:48.429  3282  3339 I io.jxcore.node.ConnectionHelper: start: Port number: 37745, start advertisements: true
,03-24 22:22:48.429  3282  3339 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 22:22:48.429  3282  3339 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-24 22:22:48.429  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-24 22:22:48.435  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-24 22:22:48.435  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 22:22:48.435  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 22:22:48.435  3282  3339 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 22:22:48.441  2156  2175 D BtGatt.GattService: registerClient() - UUID=a8bf148d-1a27-4cf4-af59-f5bb510ea110,
03-24 22:22:48.442  2156  2219 D BtGatt.GattService: onClientRegistered() - UUID=a8bf148d-1a27-4cf4-af59-f5bb510ea110, clientIf=5
,03-24 22:22:48.444  3282  3300 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-24 22:22:48.444  2156  2174 D BtGatt.GattService: start scan with filters
03-24 22:22:48.445  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 22:22:48.445  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-24 22:22:48.446  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-24 22:22:48.446  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-24 22:22:48.446  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 22:22:48.446  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 22:22:48.446  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61",
03-24 22:22:48.446  3282  3339 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 22:22:48.446  3282  3282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 22:22:48.446  2156  2229 D BtGatt.ScanManager: handling starting scan
,03-24 22:22:48.446  3282  3339 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 22:22:48.446  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 22:22:48.446  3282  3339 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...,
03-24 22:22:48.449  2156  2219 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 22:22:48.449  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:22:48.451  2156  2219 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,03-24 22:22:48.452  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:22:48.452  2156  2229 D BtGatt.ScanManager: Starting BLE batch scan
03-24 22:22:48.452  2156  2229 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 22:22:48.455  2156  2219 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 22:22:48.455  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 22:22:48.458  2156  2219 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 22:22:48.458  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 22:22:48.462  2156  2397 D BtGatt.GattService: registerClient() - UUID=7508f9f7-1c2a-4e95-8fd4-020116cd4e53
,03-24 22:22:48.463  2156  2219 D BtGatt.GattService: onClientRegistered() - UUID=7508f9f7-1c2a-4e95-8fd4-020116cd4e53, clientIf=6
,03-24 22:22:48.464  3282  3299 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-24 22:22:48.466  2156  2228 D BtGatt.AdvertiseManager: message : 0
,03-24 22:22:48.472  2156  2228 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 22:22:48.477  2156  2219 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 22:22:48.480  2156  2219 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 22:22:48.481  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-24 22:22:48.481  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-24 22:22:48.482   821  1259 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 22:22:48.487  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-24 22:22:48.487  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 22:22:48.487  3282  3339 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-24 22:22:48.487  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 22:22:48.488  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-24 22:22:48.489  3282  3339 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,03-24 22:22:48.489  3282  3339 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING,
03-24 22:22:48.489  3282  3339 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-24 22:22:48.489  3282  3339 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 22:22:48.489  3282  3282 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-24 22:22:48.490  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 22:22:48.490  3282  3282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,03-24 22:22:48.490  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-24 22:22:48.490  3282  3282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
,03-24 22:22:48.490  3282  3282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-24 22:22:48.490  3282  3282 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 22:22:48.490  3282  3282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-24 22:22:48.491  3282  3282 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-24 22:22:48.491  3282  3282 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 22:22:48.491  3282  3282 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-24 22:22:48.491  3282  3282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-24 22:22:48.491  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 22:22:48.491  3282  3339 I jxcore-log: 
03-24 22:22:48.492   821  1375 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 22:22:48.494  3282  3339 I jxcore-log: ok 162 Can call startUpdateAdvertisingAndListening without error
03-24 22:22:48.494  3282  3339 I jxcore-log: 
03-24 22:22:48.495  3282  3747 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-24 22:22:48.500  3282  3747 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-24 22:22:48.503  3282  3339 I io.jxcore.node.ConnectionHelper: start: Port number: 37745, start advertisements: false
,03-24 22:22:48.503  3282  3339 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 22:22:48.503  3282  3339 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should affect listening to advertisements only
03-24 22:22:48.503  3282  3339 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 22:22:48.504  3282  3339 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 22:22:48.506  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 22:22:48.506  3282  3339 I jxcore-log: 
,03-24 22:22:48.510  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-24 22:22:48.510  3282  3339 I jxcore-log: 
,03-24 22:22:48.513  3282  3339 I jxcore-log: ok 163 Can call startListeningForAdvertisements without error
03-24 22:22:48.513  3282  3339 I jxcore-log: 
,03-24 22:22:48.961  2156  2156 D BtGatt.ScanManager: awakened up at time 232749,
,03-24 22:22:48.964  2156  2229 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 22:22:48.974  2156  2219 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2,
03-24 22:22:48.974  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 22:22:48.975  2156  2219 D BtGatt.GattService: current time is 232762447201
,03-24 22:22:48.975  2156  2219 D BtGatt.GattService: Batch record : [10, 97, 73, 0, 66, 118, 1, -128, -77, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -59, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-24 22:22:48.976  2156  2219 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 22:22:48.977  2156  2219 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-24 22:22:48.980  3282  3282 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 1
,03-24 22:22:48.980  3282  3282 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> E0:DB:10:14:E2:C0], added - the peer count is 2
03-24 22:22:48.981  3282  3282 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
03-24 22:22:48.981  3282  3282 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> E0:DB:10:14:E2:C0], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 
,03-24 22:22:48.986  3282  3339 I jxcore-log: INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"pleaseConnect":false}]
03-24 22:22:48.986  3282  3339 I jxcore-log: 
,03-24 22:22:49.000  3282  3339 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID F8:95:C7:87:3C:51
,03-24 22:22:49.000  3282  3339 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> F8:95:C7:87:3C:51]
,03-24 22:22:49.005  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address F8:95:C7:87:3C:51
,03-24 22:22:49.007  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
,03-24 22:22:49.007  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,03-24 22:22:49.008  3282  3339 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null F8:95:C7:87:3C:51,
03-24 22:22:49.008  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address F8:95:C7:87:3C:51
03-24 22:22:49.008  3282  3339 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: F8:95:C7:87:3C:51)
,03-24 22:22:49.011  3282  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address F8:95:C7:87:3C:51 (thread ID: 356)
03-24 22:22:49.012  3282  3748 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-24 22:22:49.012  3282  3339 I jxcore-log: INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"E0:DB:10:14:E2:C0","peerAvailable":true,"pleaseConnect":false}]
03-24 22:22:49.012  3282  3339 I jxcore-log: 
03-24 22:22:49.016  2156  2175 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,03-24 22:22:51.817  2156  2230 W bt-btif : info:x10
03-24 22:22:51.817  2156  2219 D         : remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,03-24 22:22:51.818  2156  2219 E BluetoothRemoteDevices: aclStateChangeCallback: Device is NULL
,03-24 22:22:51.854  2156  2230 W bt-sdp  : process_service_search_attr_rsp,
,03-24 22:22:52.705  2156  2219 D btif_config: btif_get_device_type: Device [f8:95:c7:87:3c:51] type 1
,03-24 22:22:52.715  2156  2219 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
,03-24 22:22:52.716  2156  2219 E bt-btif : check_cod: remote_cod = 0x5a020c
,03-24 22:22:52.721  2156  2220 I BluetoothBondStateMachine: Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
,03-24 22:22:52.721  2156  2220 I BluetoothBondStateMachine: Entering PendingCommandState State
,03-24 22:22:52.795   821   855 I ActivityManager: Start proc 3749:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.BluetoothPairingRequest
,03-24 22:22:52.879   821   859 D BluetoothManagerService: Message: 20
03-24 22:22:52.880   821   859 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@28b8ccd6:true
,03-24 22:22:52.882   821  1415 I ActivityManager: Killing 2950:com.google.android.music:main/u0a66 (adj 15): empty #17
,03-24 22:22:52.956  2156  2219 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,03-24 22:22:52.957  2156  2220 D BluetoothAdapterProperties: Failed to remove device: F8:95:C7:87:3C:51
,03-24 22:22:53.055  2156  2230 W bt-btif : new conn_srvc id:26, app_id:1
03-24 22:22:53.055  2156  2230 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:1
03-24 22:22:53.055  2156  2230 W bt-btif : bta_dm_pm_ssr:2, lat:1200
03-24 22:22:53.056  3282  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onSocketConnected: [<no peer name> F8:95:C7:87:3C:51] (thread ID: 356)
,03-24 22:22:53.056  3282  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 356)
,03-24 22:22:53.062  3282  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesWritten: 15 bytes successfully written (thread ID: 357)
,03-24 22:22:53.062  3282  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Outgoing connection initialized (*handshake* thread ID: 357)
,03-24 22:22:53.063  3282  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 356)
,03-24 22:22:53.071  3282  3766 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 357)
,03-24 22:22:53.097  2156  2220 I BluetoothBondStateMachine: Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,03-24 22:22:53.139  2156  2220 I BluetoothBondStateMachine: StableState(): Entering Off State
,03-24 22:22:53.143  3282  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesRead: Read 15 bytes successfully (thread ID: 357)
,03-24 22:22:53.144  3282  3766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Handshake succeeded with [<no peer name> F8:95:C7:87:3C:51]
03-24 22:22:53.144  3282  3766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onHandshakeSucceeded: [<no peer name> F8:95:C7:87:3C:51] (thread ID: 356)
03-24 22:22:53.144  3282  3766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: handleSuccessfulClientThread: [<no peer name> F8:95:C7:87:3C:51] (thread ID: 356)
03-24 22:22:53.145  3282  3766 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 357)
03-24 22:22:53.145  3282  3282 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> F8:95:C7:87:3C:51]
03-24 22:22:53.146  3282  3282 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing connection to peer [<no peer name> F8:95:C7:87:3C:51]
03-24 22:22:53.146  3282  3282 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
03-24 22:22:53.148  3282  3282 I io.jxcore.node.ConnectionHelper: lowerBleDiscoveryPowerAndStartResetTimer: Lowering the power settings
03-24 22:22:53.148  3282  3282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 2 -> 0
,03-24 22:22:53.149  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 22:22:53.149  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 22:22:53.149  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-24 22:22:53.149  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-24 22:22:53.149  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
,03-24 22:22:53.149  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-24 22:22:53.157  2156  2228 D BtGatt.AdvertiseManager: message : 1
,03-24 22:22:53.158  2156  2228 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-24 22:22:53.162  2156  2219 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0,
03-24 22:22:53.162  2156  2219 D BtGatt.GattService: Client app is not null!
03-24 22:22:53.164  2156  2396 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-24 22:22:53.164  3282  3282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 22:22:53.165  3282  3282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-24 22:22:53.165  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 3, timeout: 0, is connectable: false
03-24 22:22:53.165  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 22:22:53.165  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 22:22:53.165  3282  3282 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 22:22:53.165  3282  3282 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-24 22:22:53.165  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 22:22:53.165  3282  3282 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-24 22:22:53.172  2156  2396 D BtGatt.GattService: registerClient() - UUID=9cba5443-fbda-4eb7-9fb3-476bfd75b087
,03-24 22:22:53.172  2156  2219 D BtGatt.GattService: onClientRegistered() - UUID=9cba5443-fbda-4eb7-9fb3-476bfd75b087, clientIf=6
,03-24 22:22:53.173  3282  3299 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-24 22:22:53.175  2156  2228 D BtGatt.AdvertiseManager: message : 0
,03-24 22:22:53.178  2156  2228 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 22:22:53.181  2156  2219 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 22:22:53.184  2156  2219 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 22:22:53.185  3282  3282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-24 22:22:53.193  2156  2175 D BtGatt.GattService: stopScan() - queue size =1
03-24 22:22:53.195  2156  2396 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-24 22:22:53.195  2156  2219 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 22:22:53.195  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:22:53.195  2156  2229 D BtGatt.ScanManager: stopping BLe Batch
03-24 22:22:53.196  3282  3282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 22:22:53.196  3282  3282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 22:22:53.196  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 22:22:53.196  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 22:22:53.196  3282  3282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-24 22:22:53.196  3282  3282 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 22:22:53.198  2156  2219 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 22:22:53.198  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:22:53.199  2156  2229 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 22:22:53.202  2156  2219 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,03-24 22:22:53.202  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:22:53.202  2156  2219 D BtGatt.GattService: current time is 236989712199
03-24 22:22:53.202  2156  2219 D BtGatt.GattService: Batch record : [10, 97, 73, 0, 66, 118, 1, -128, -72, 52, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -56, 52, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-24 22:22:53.203  2156  2219 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 22:22:53.203  2156  2396 D BtGatt.GattService: registerClient() - UUID=77c889ea-0c0a-43db-b9c4-661336a5da1c
03-24 22:22:53.203  2156  2219 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-24 22:22:53.204  2156  2219 D BtGatt.GattService: onClientRegistered() - UUID=77c889ea-0c0a-43db-b9c4-661336a5da1c, clientIf=5
03-24 22:22:53.204  3282  3299 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 22:22:53.205  2156  2397 D BtGatt.GattService: start scan with filters
03-24 22:22:53.206  3282  3282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 22:22:53.206  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 22:22:53.206  3282  3282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 3 -> 1
,03-24 22:22:53.206  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 22:22:53.206  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 22:22:53.206  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-24 22:22:53.206  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-24 22:22:53.206  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-24 22:22:53.206  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-24 22:22:53.208  2156  2228 D BtGatt.AdvertiseManager: message : 1
03-24 22:22:53.209  2156  2228 D BtGatt.AdvertiseManager: stop advertise for client 6
03-24 22:22:53.210  2156  2229 D BtGatt.ScanManager: handling starting scan
,03-24 22:22:53.213  2156  2219 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 22:22:53.213  2156  2219 D BtGatt.GattService: Client app is not null!
,03-24 22:22:53.215  2156  2396 D BtGatt.GattService: unregisterClient() - clientIf=6
03-24 22:22:53.216  2156  2219 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 22:22:53.216  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:22:53.216  3282  3282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 22:22:53.216  3282  3282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-24 22:22:53.217  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-24 22:22:53.217  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 22:22:53.217  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 22:22:53.217  3282  3282 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 22:22:53.218  3282  3282 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 22:22:53.218  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 22:22:53.218  3282  3282 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-24 22:22:53.218  2156  2219 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 22:22:53.218  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:22:53.219  2156  2229 D BtGatt.ScanManager: Starting BLE batch scan
03-24 22:22:53.219  2156  2229 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 22:22:53.221  2156  2219 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 22:22:53.221  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:22:53.222  2156  2219 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 22:22:53.222  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:22:53.225  2156  2396 D BtGatt.GattService: registerClient() - UUID=84b77ca9-7361-4e90-90dd-a357a562aade
03-24 22:22:53.225  2156  2219 D BtGatt.GattService: onClientRegistered() - UUID=84b77ca9-7361-4e90-90dd-a357a562aade, clientIf=6
03-24 22:22:53.226  3282  3299 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-24 22:22:53.227  2156  2228 D BtGatt.AdvertiseManager: message : 0
,03-24 22:22:53.232  2156  2228 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 22:22:53.236  2156  2219 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 22:22:53.239  2156  2219 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 22:22:53.240  3282  3282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-24 22:22:53.241  2156  2174 D BtGatt.GattService: stopScan() - queue size =1
,03-24 22:22:53.243  2156  2396 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-24 22:22:53.244  3282  3282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 22:22:53.244  3282  3282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 22:22:53.244  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 22:22:53.244  2156  2219 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 22:22:53.244  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 22:22:53.244  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:22:53.244  3282  3282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 22:22:53.244  3282  3282 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-24 22:22:53.244  2156  2229 D BtGatt.ScanManager: stopping BLe Batch
,03-24 22:22:53.247  2156  2219 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 22:22:53.247  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:22:53.247  2156  2229 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 22:22:53.248  2156  2219 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 22:22:53.249  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 22:22:53.250  2156  2396 D BtGatt.GattService: registerClient() - UUID=8e9e3767-20ed-4ae5-878e-006621bb5f7e
03-24 22:22:53.250  2156  2219 D BtGatt.GattService: onClientRegistered() - UUID=8e9e3767-20ed-4ae5-878e-006621bb5f7e, clientIf=5
03-24 22:22:53.250  3282  3299 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 22:22:53.251  2156  2397 D BtGatt.GattService: start scan with filters
,03-24 22:22:53.253  3282  3282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 22:22:53.253  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 22:22:53.254  3282  3282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 2 -> 0
03-24 22:22:53.254  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 22:22:53.254  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE,
03-24 22:22:53.254  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-24 22:22:53.254  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-24 22:22:53.254  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-24 22:22:53.254  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-24 22:22:53.260  2156  2228 D BtGatt.AdvertiseManager: message : 1
,03-24 22:22:53.261  2156  2229 D BtGatt.ScanManager: handling starting scan,
03-24 22:22:53.261  2156  2228 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-24 22:22:53.265  2156  2219 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 22:22:53.265  2156  2219 D BtGatt.GattService: Client app is not null!
03-24 22:22:53.266  2156  2396 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-24 22:22:53.266  2156  2219 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,03-24 22:22:53.267  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:22:53.267  3282  3282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 22:22:53.267  3282  3282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-24 22:22:53.267  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
,03-24 22:22:53.267  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 22:22:53.268  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 22:22:53.268  3282  3282 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 22:22:53.268  3282  3282 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 22:22:53.268  2156  2219 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 22:22:53.268  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:22:53.268  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 22:22:53.269  2156  2229 D BtGatt.ScanManager: Starting BLE batch scan
03-24 22:22:53.269  3282  3282 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-24 22:22:53.269  2156  2229 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 22:22:53.271  2156  2219 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 22:22:53.271  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:22:53.272  2156  2219 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 22:22:53.272  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 22:22:53.275  2156  2396 D BtGatt.GattService: registerClient() - UUID=cd0a1537-cc37-48b1-ba97-32a937d22104,
03-24 22:22:53.276  2156  2219 D BtGatt.GattService: onClientRegistered() - UUID=cd0a1537-cc37-48b1-ba97-32a937d22104, clientIf=6
03-24 22:22:53.276  3282  3299 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-24 22:22:53.277  2156  2228 D BtGatt.AdvertiseManager: message : 0
,03-24 22:22:53.281  2156  2228 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 22:22:53.284  2156  2219 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 22:22:53.286  2156  2219 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0,
03-24 22:22:53.287  3282  3282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-24 22:22:53.289  2156  2175 D BtGatt.GattService: stopScan() - queue size =1
03-24 22:22:53.289  2156  2396 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-24 22:22:53.290  3282  3282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
03-24 22:22:53.290  3282  3282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-24 22:22:53.290  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-24 22:22:53.290  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 22:22:53.290  3282  3282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-24 22:22:53.290  2156  2219 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,03-24 22:22:53.290  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:22:53.290  3282  3282 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-24 22:22:53.291  2156  2229 D BtGatt.ScanManager: stopping BLe Batch
03-24 22:22:53.293  2156  2219 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 22:22:53.293  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
03-24 22:22:53.293  2156  2229 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 22:22:53.295  2156  2219 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 22:22:53.295  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:22:53.296  2156  2396 D BtGatt.GattService: registerClient() - UUID=dc885865-5b7d-4691-95db-8b839311d140
03-24 22:22:53.296  2156  2219 D BtGatt.GattService: onClientRegistered() - UUID=dc885865-5b7d-4691-95db-8b839311d140, clientIf=5
,03-24 22:22:53.299  3282  3299 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 22:22:53.299  2156  2397 D BtGatt.GattService: start scan with filters
,03-24 22:22:53.300  3282  3282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-24 22:22:53.300  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 22:22:53.300  3282  3282 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing socket thread, for peer [<no peer name> F8:95:C7:87:3C:51], created successfully
03-24 22:22:53.301  3282  3282 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 1
,03-24 22:22:53.301  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,03-24 22:22:53.301  3282  3282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING,
,03-24 22:22:53.301  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-24 22:22:53.301  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 22:22:53.301  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 22:22:53.301  2156  2229 D BtGatt.ScanManager: handling starting scan
,03-24 22:22:53.301  3282  3770 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 358)
03-24 22:22:53.303  2156  2219 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,03-24 22:22:53.303  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 22:22:53.304  3282  3770 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 56708
,03-24 22:22:53.304  3282  3770 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
03-24 22:22:53.304  3282  3770 I io.jxcore.node.ConnectionHelper: onListeningForIncomingConnections: Outgoing connection is using port 56708 (peer ID: F8:95:C7:87:3C:51)
03-24 22:22:53.305  2156  2219 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 22:22:53.305  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:22:53.305  2156  2229 D BtGatt.ScanManager: Starting BLE batch scan
03-24 22:22:53.305  2156  2229 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-24 22:22:53.305  3282  3770 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "F8:95:C7:87:3C:51" removed
03-24 22:22:53.307  2156  2219 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 22:22:53.307  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:22:53.308  2156  2219 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 22:22:53.308  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 22:22:53.310  3282  3339 I jxcore-log: INFO testThaliMobileNative: 
03-24 22:22:53.310  3282  3339 I jxcore-log: 
03-24 22:22:53.311  3282  3339 I jxcore-log: ok 164 Must have listeningPort
03-24 22:22:53.311  3282  3339 I jxcore-log: 
,03-24 22:22:53.313  3282  3339 I jxcore-log: ok 165 listeningPort must be a number
03-24 22:22:53.313  3282  3339 I jxcore-log: 
,03-24 22:22:53.313  3282  3339 I jxcore-log: ok 166 Connection must have clientPort
03-24 22:22:53.313  3282  3339 I jxcore-log: 
03-24 22:22:53.314  3282  3339 I jxcore-log: ok 167 clientPort must be a number
03-24 22:22:53.314  3282  3339 I jxcore-log: 
03-24 22:22:53.315  3282  3339 I jxcore-log: ok 168 Connection must have serverPort
03-24 22:22:53.315  3282  3339 I jxcore-log: 
03-24 22:22:53.316  3282  3339 I jxcore-log: ok 169 serverPort must be a number
03-24 22:22:53.316  3282  3339 I jxcore-log: 
,03-24 22:22:53.317  3282  3339 I jxcore-log: ok 170 forward connection must have clientPort == 0
03-24 22:22:53.317  3282  3339 I jxcore-log: 
03-24 22:22:53.318  3282  3339 I jxcore-log: ok 171 forward connection must have serverPort == 0
03-24 22:22:53.318  3282  3339 I jxcore-log: 
,03-24 22:22:53.329  3282  3339 I jxcore-log: # teardown
03-24 22:22:53.329  3282  3339 I jxcore-log: ,
,03-24 22:22:53.582  3499  3771 V KeepSync: Connecting to GoogleApiClient
,03-24 22:22:53.663  1261  3458 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-24 22:22:53.664  1261  3458 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 22:22:53.664  1261  3458 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 22:22:53.664  1261  3458 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 22:22:53.672  1261  3458 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 22:22:53.685  1261  1280 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,03-24 22:22:53.685  1261  1280 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 22:22:53.686  1261  1280 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 22:22:53.686  1261  1280 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 22:22:53.695  1261  1280 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 22:22:53.711  3113  3773 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
03-24 22:22:53.711  3113  3773 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-24 22:22:53.711  3113  3773 E HttpOperation: 	at jdm.a(PG:82)
03-24 22:22:53.711  3113  3773 E HttpOperation: 	at jcs.o(PG:406)
03-24 22:22:53.711  3113  3773 E HttpOperation: 	at jcn.a(PG:1379)
03-24 22:22:53.711  3113  3773 E HttpOperation: 	at jcs.i(PG:143)
03-24 22:22:53.711  3113  3773 E HttpOperation: 	at blb.a(PG:3937)
03-24 22:22:53.711  3113  3773 E HttpOperation: 	at czp.a(PG:18188)
03-24 22:22:53.711  3113  3773 E HttpOperation: 	at czp.a(PG:9081)
03-24 22:22:53.711  3113  3773 E HttpOperation: 	at czq.run(PG:1686)
03-24 22:22:53.711  3113  3773 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-24 22:22:53.711  3113  3773 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 22:22:53.711  3113  3773 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 22:22:53.711  3113  3773 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 22:22:53.711  3113  3773 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-24 22:22:53.711  3113  3773 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-24 22:22:53.711  3113  3773 E HttpOperation: 	at jdj.a(PG:4091)
03-24 22:22:53.711  3113  3773 E HttpOperation: 	at jdj.a(PG:1125)
03-24 22:22:53.711  3113  3773 E HttpOperation: 	at jdm.a(PG:77)
03-24 22:22:53.711  3113  3773 E HttpOperation: 	... 12 more
03-24 22:22:53.711  3113  3773 E HttpOperation: Caused by: faj: BadAuthentication
03-24 22:22:53.711  3113  3773 E HttpOperation: 	at fal.a(PG:38)
03-24 22:22:53.711  3113  3773 E HttpOperation: 	at jdj.a(PG:4089)
03-24 22:22:53.711  3113  3773 E HttpOperation: 	... 14 more
,03-24 22:22:53.728  1776  3774 E ClientConnectionOperation: Handling authorization failure,
,03-24 22:22:53.728  1776  3774 E ClientConnectionOperation: com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
03-24 22:22:53.728  1776  3774 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
03-24 22:22:53.728  1776  3774 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
03-24 22:22:53.728  1776  3774 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
03-24 22:22:53.728  1776  3774 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
03-24 22:22:53.728  1776  3774 E ClientConnectionOperation: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-24 22:22:53.728  1776  3774 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 22:22:53.728  1776  3774 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 22:22:53.728  1776  3774 E ClientConnectionOperation: 	at java.lang.Thread.run(Thread.java:818)
03-24 22:22:53.728  1776  3774 E ClientConnectionOperation: Caused by: com.google.android.gms.auth.ad: BadAuthentication
03-24 22:22:53.728  1776  3774 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.b(SourceFile:442)
03-24 22:22:53.728  1776  3774 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:365)
03-24 22:22:53.728  1776  3774 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:310)
03-24 22:22:53.728  1776  3774 E ClientConnectionOperation: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
03-24 22:22:53.728  1776  3774 E ClientConnectionOperation: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
03-24 22:22:53.728  1776  3774 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:30)
03-24 22:22:53.728  1776  3774 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:370)
03-24 22:22:53.728  1776  3774 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:340)
03-24 22:22:53.728  1776  3774 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:319)
03-24 22:22:53.728  1776  3774 E ClientConnectionOperation: 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
03-24 22:22:53.728  1776  3774 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
03-24 22:22:53.728  1776  3774 E ClientConnectionOperation: 	... 7 more
,03-24 22:22:53.734  3499  3771 V KeepSync: GoogleApiClient failed to connect with error code: 4
,03-24 22:22:53.740  3499  3771 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-24 22:22:53.752  3499  3771 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
03-24 22:22:53.753  3499  3771 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-24 22:22:53.790  1261  1723 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,03-24 22:22:53.790  1261  1723 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-24 22:22:53.790  1261  1723 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 22:22:53.791  1261  1723 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 22:22:53.797  1261  1723 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 22:22:53.816  3113  3773 E HttpOperation: [getmobileexperiments] Unexpected exception
03-24 22:22:53.816  3113  3773 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-24 22:22:53.816  3113  3773 E HttpOperation: 	at jdm.a(PG:82)
03-24 22:22:53.816  3113  3773 E HttpOperation: 	at jcs.o(PG:406)
03-24 22:22:53.816  3113  3773 E HttpOperation: 	at jcn.a(PG:1379)
03-24 22:22:53.816  3113  3773 E HttpOperation: 	at jcs.i(PG:143)
03-24 22:22:53.816  3113  3773 E HttpOperation: 	at hec.a(PG:42)
03-24 22:22:53.816  3113  3773 E HttpOperation: 	at hee.a(PG:102)
03-24 22:22:53.816  3113  3773 E HttpOperation: 	at czr.a(PG:65)
03-24 22:22:53.816  3113  3773 E HttpOperation: 	at kka.a(PG:108)
03-24 22:22:53.816  3113  3773 E HttpOperation: 	at czp.a(PG:19176)
03-24 22:22:53.816  3113  3773 E HttpOperation: 	at czp.a(PG:9081)
03-24 22:22:53.816  3113  3773 E HttpOperation: 	at czq.run(PG:1686)
03-24 22:22:53.816  3113  3773 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-24 22:22:53.816  3113  3773 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 22:22:53.816  3113  3773 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 22:22:53.816  3113  3773 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 22:22:53.816  3113  3773 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-24 22:22:53.816  3113  3773 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-24 22:22:53.816  3113  3773 E HttpOperation: 	at jdj.a(PG:4091)
03-24 22:22:53.816  3113  3773 E HttpOperation: 	at jdj.a(PG:1125)
03-24 22:22:53.816  3113  3773 E HttpOperation: 	at jdm.a(PG:77)
03-24 22:22:53.816  3113  3773 E HttpOperation: 	... 15 more
03-24 22:22:53.816  3113  3773 E HttpOperation: Caused by: faj: BadAuthentication
03-24 22:22:53.816  3113  3773 E HttpOperation: 	at fal.a(PG:38)
03-24 22:22:53.816  3113  3773 E HttpOperation: 	at jdj.a(PG:4089)
03-24 22:22:53.816  3113  3773 E HttpOperation: 	... 17 more
,03-24 22:22:53.817  3113  3773 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
03-24 22:22:53.817  3113  3773 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
03-24 22:22:53.817  3113  3773 E ExperimentLoader: 	at jdm.a(PG:82)
03-24 22:22:53.817  3113  3773 E ExperimentLoader: 	at jcs.o(PG:406)
03-24 22:22:53.817  3113  3773 E ExperimentLoader: 	at jcn.a(PG:1379)
03-24 22:22:53.817  3113  3773 E ExperimentLoader: 	at jcs.i(PG:143)
03-24 22:22:53.817  3113  3773 E ExperimentLoader: 	at hec.a(PG:42)
03-24 22:22:53.817  3113  3773 E ExperimentLoader: 	at hee.a(PG:102)
03-24 22:22:53.817  3113  3773 E ExperimentLoader: 	at czr.a(PG:65)
03-24 22:22:53.817  3113  3773 E ExperimentLoader: 	at kka.a(PG:108)
03-24 22:22:53.817  3113  3773 E ExperimentLoader: 	at czp.a(PG:19176)
03-24 22:22:53.817  3113  3773 E ExperimentLoader: 	at czp.a(PG:9081)
03-24 22:22:53.817  3113  3773 E ExperimentLoader: 	at czq.run(PG:1686)
03-24 22:22:53.817  3113  3773 E ExperimentLoader: 	,at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-24 22:22:53.817  3113  3773 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 22:22:53.817  3113  3773 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 22:22:53.817  3113  3773 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 22:22:53.817  3113  3773 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
03-24 22:22:53.817  3113  3773 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-24 22:22:53.817  3113  3773 E ExperimentLoader: ,	at jdj.a(PG:4091)
03-24 22:22:53.817  3113  3773 E ExperimentLoader: 	at jdj.a(PG:1125)
03-24 22:22:53.817  3113  3773 E ExperimentLoader: 	at jdm.a(PG:77)
03-24 22:22:53.817  3113  3773 E ExperimentLoader: 	... 15 more
03-24 22:22:53.817  3113  3773 E ExperimentLoader: Caused by: faj: BadAuthentication
03-24 22:22:53.817  3113  3773 E ExperimentLoader: 	,at fal.a(PG:38)
03-24 22:22:53.817  3113  3773 E ExperimentLoader: 	at jdj.a(PG:4089)
03-24 22:22:53.817  3113  3773 E ExperimentLoader: 	... 17 more
,03-24 22:22:53.846  1261  3458 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,03-24 22:22:53.846  1261  3458 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
03-24 22:22:53.847  1261  3458 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-24 22:22:53.847  1261  3458 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 22:22:53.853  1261  3458 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,03-24 22:22:53.901  3499  3771 E KeepSync: IOException
03-24 22:22:53.901  3499  3771 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
03-24 22:22:53.901  3499  3771 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
03-24 22:22:53.901  3499  3771 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
03-24 22:22:53.901  3499  3771 E KeepSync: 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
03-24 22:22:53.901  3499  3771 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
03-24 22:22:53.901  3499  3771 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
03-24 22:22:53.901  3499  3771 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
03-24 22:22:53.901  3499  3771 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
03-24 22:22:53.901  3499  3771 E KeepSync: 	at com.google.android.keep.util.m.a(SourceFile:207)
03-24 22:22:53.901  3499  3771 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
03-24 22:22:53.901  3499  3771 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
03-24 22:22:53.901  3499  3771 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
03-24 22:22:53.901  3499  3771 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
03-24 22:22:53.901  3499  3771 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
03-24 22:22:53.901  3499  3771 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
03-24 22:22:53.901  3499  3771 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
03-24 22:22:53.901  3499  3771 E KeepSync: 	... 10 more
03-24 22:22:53.901  3499  3771 W KeepSync: Sync result 2
,03-24 22:22:53.911   821   854 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 209838, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-24 22:22:53.948   821   854 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 210645, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,03-24 22:22:53.963  3520  3778 I BooksSync: Starting books sync for 61035162, extras: ade
,03-24 22:22:53.993  3520  3779 I BooksConfig: GmsCore Version = 7.8.99 (2134222-430)
,03-24 22:22:54.067  1261  3460 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,03-24 22:22:54.068  1261  3460 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 22:22:54.068  1261  3460 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 22:22:54.068  1261  3460 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 22:22:54.080  1261  3460 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 22:22:54.212  1261  3459 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-24 22:22:54.212  1261  3459 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 22:22:54.212  1261  3459 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 22:22:54.212  1261  3459 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 22:22:54.219  1261  3459 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 22:22:54.248  3520  3779 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-24 22:22:54.250  3520  3778 E BooksSync: Soft error
03-24 22:22:54.250  3520  3778 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-24 22:22:54.250  3520  3778 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-24 22:22:54.251  3520  3778 E BooksSync: Sync error
03-24 22:22:54.251  3520  3778 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-24 22:22:54.251  3520  3778 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-24 22:22:54.251  3520  3778 I BooksSync: Finished books sync
,03-24 22:22:54.265   821   854 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 211516, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-24 22:22:57.820  2156  2216 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,03-24 22:22:58.080  2156  2230 W bt-btif : dm_pm_timer expires
03-24 22:22:58.080  2156  2230 W bt-btif : dm_pm_timer expires 0
,03-24 22:22:58.080  2156  2230 W bt-btif : proc dm_pm_timer expires
,03-24 22:22:58.199  2156  2156 D BtGatt.ScanManager: awakened up at time 241987
,03-24 22:22:58.202  2156  2229 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 22:22:58.213  2156  2219 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,03-24 22:22:58.213  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:22:58.213  2156  2219 D BtGatt.GattService: current time is 242000819177
03-24 22:22:58.213  2156  2219 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -59, 57, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0, 67, 118, -82, 60, 22, 126, 1, -128, -90, 60, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-24 22:22:58.214  2156  2219 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
,03-24 22:22:58.215  2156  2219 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 22:22:58.219  3282  3282 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
03-24 22:22:58.220  3282  3282 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> E0:DB:10:14:E2:C0] updated - the peer count is 2,
,03-24 22:22:59.227  2156  2156 D BtGatt.ScanManager: awakened up at time 243015
,03-24 22:22:59.229  2156  2229 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 22:22:59.239  2156  2219 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,03-24 22:22:59.239  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 22:23:00.257  2156  2156 D BtGatt.ScanManager: awakened up at time 244044
,03-24 22:23:00.260  2156  2229 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 22:23:00.267  2156  2219 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 22:23:00.267  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 22:23:01.284  2156  2156 D BtGatt.ScanManager: awakened up at time 245070
,03-24 22:23:01.288  2156  2229 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 22:23:01.297  2156  2219 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,03-24 22:23:01.297  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 22:23:01.388  3282  3339 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 22:23:01.388  3282  3339 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
03-24 22:23:01.388  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-24 22:23:01.388  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-24 22:23:01.394  2156  2175 D BtGatt.GattService: stopScan() - queue size =1
03-24 22:23:01.395  2156  2396 D BtGatt.GattService: unregisterClient() - clientIf=5
03-24 22:23:01.396  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 22:23:01.396  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 22:23:01.396  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-24 22:23:01.396  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
,03-24 22:23:01.396  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-24 22:23:01.396  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 22:23:01.397  2156  2219 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 22:23:01.397  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:23:01.397  3282  3282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 22:23:01.397  3282  3282 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
03-24 22:23:01.397  2156  2229 D BtGatt.ScanManager: stopping BLe Batch
03-24 22:23:01.397  3282  3282 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-24 22:23:01.399  2156  2219 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 22:23:01.399  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:23:01.400  2156  2229 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 22:23:01.400  3282  3339 I jxcore-log: ok 172 Should be able to call stopListeningForAdvertisments in teardown
03-24 22:23:01.400  3282  3339 I jxcore-log: 
,03-24 22:23:01.402  2156  2219 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 22:23:01.402  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:23:01.402  3282  3339 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-24 22:23:01.402  3282  3339 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> F8:95:C7:87:3C:51]
03-24 22:23:01.403  3282  3339 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 358)
,03-24 22:23:01.403  3282  3339 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 358)
,03-24 22:23:01.403  3282  3339 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
,03-24 22:23:01.403  3282  3339 D io.jxcore.node.OutgoingSocketThread: closeLocalSocketAndStreams: Nothing to close (thread ID: 358)
03-24 22:23:01.403  3282  3339 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 358)
03-24 22:23:01.403  3282  3339 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
03-24 22:23:01.404  3282  3339 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-24 22:23:01.404  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-24 22:23:01.404  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-24 22:23:01.404  3282  3339 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-24 22:23:01.404  3282  3747 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
,03-24 22:23:01.404  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-24 22:23:01.404  3282  3747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-24 22:23:01.404  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-24 22:23:01.404  3282  3747 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-24 22:23:01.404  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 22:23:01.404  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 22:23:01.404  3282  3282 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-24 22:23:01.404  3282  3282 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-24 22:23:01.405  3282  3282 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-24 22:23:01.405  3282  3770 D io.jxcore.node.OutgoingSocketThread: Exiting thread (ID: 358)
03-24 22:23:01.405  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-24 22:23:01.408  3282  3339 D BluetoothLeScanner: could not find callback wrapper
,03-24 22:23:01.408  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 22:23:01.408  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,03-24 22:23:01.414  2156  2228 D BtGatt.AdvertiseManager: message : 1
,03-24 22:23:01.414  2156  2228 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-24 22:23:01.418  2156  2219 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,03-24 22:23:01.418  2156  2219 D BtGatt.GattService: Client app is not null!
03-24 22:23:01.419  2156  2396 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-24 22:23:01.420  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 22:23:01.420  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,03-24 22:23:01.420  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-24 22:23:01.420  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-24 22:23:01.420  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-24 22:23:01.420  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 22:23:01.421  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 22:23:01.421  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-24 22:23:01.422  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,03-24 22:23:01.422  3282  3339 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-24 22:23:01.422  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 22:23:01.423  3282  3282 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 22:23:01.423  3282  3282 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 22:23:01.423  3282  3282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 22:23:01.423  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 22:23:01.423  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-24 22:23:01.428  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-24 22:23:01.428  3282  3339 I jxcore-log: 
,03-24 22:23:01.430  3282  3339 I jxcore-log: ok 173 Should be able to call stopAdvertisingAndListening in teardown
03-24 22:23:01.430  3282  3339 I jxcore-log: 
,03-24 22:23:01.431  3282  3282 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-24 22:23:01.432   821  1375 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 22:23:01.439  3282  3339 I jxcore-log: # setup
03-24 22:23:01.439  3282  3339 I jxcore-log: 
,03-24 22:23:01.440  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-24 22:23:01.441  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-24 22:23:01.441  3282  3282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 22:23:01.447  3282  3282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 22:23:01.447  3282  3282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-24 22:23:01.451  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 22:23:01.451  3282  3339 I jxcore-log: 
,03-24 22:23:01.455  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 22:23:01.455  3282  3339 I jxcore-log: 
,03-24 22:23:01.917  3282  3339 I jxcore-log: # 41. Can shift large amounts of data
03-24 22:23:01.917  3282  3339 I jxcore-log: 
,03-24 22:23:01.977  2156  2230 W bt-btif : bta_jv_rfc_port_to_cb(port_handle:0xd):jv handle:0x0 not FOUND
,03-24 22:23:02.703  3282  3339 I io.jxcore.node.ConnectionHelper: start: Port number: 37974, start advertisements: true,
03-24 22:23:02.703  3282  3339 I io.jxcore.node.ConnectionHelper: restoreDefaultBleDiscoverySettings: Powering the BLE discovery back up
03-24 22:23:02.703  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 0 -> 2
03-24 22:23:02.703  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 22:23:02.703  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 22:23:02.703  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-24 22:23:02.703  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-24 22:23:02.703  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-24 22:23:02.703  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-24 22:23:02.703  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 1, timeout: 0, is connectable: false
03-24 22:23:02.703  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-24 22:23:02.703  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 1 -> 3
,03-24 22:23:02.703  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 22:23:02.703  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 22:23:02.703  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-24 22:23:02.703  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-24 22:23:02.703  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-24 22:23:02.703  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-24 22:23:02.703  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-24 22:23:02.703  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-24 22:23:02.703  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 0 -> 2
03-24 22:23:02.703  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 22:23:02.703  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 22:23:02.703  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-24 22:23:02.703  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-24 22:23:02.703  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-24 22:23:02.703  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-24 22:23:02.703  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-24 22:23:02.703  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 22:23:02.703  3282  3339 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 22:23:02.703  3282  3339 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-24 22:23:02.703  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-24 22:23:02.710  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser,
03-24 22:23:02.710  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 22:23:02.710  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 22:23:02.710  3282  3339 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 22:23:02.718  2156  2175 D BtGatt.GattService: registerClient() - UUID=7b9b268d-8db9-4b8d-8f73-99bf4eadadae
03-24 22:23:02.718  2156  2219 D BtGatt.GattService: onClientRegistered() - UUID=7b9b268d-8db9-4b8d-8f73-99bf4eadadae, clientIf=5
03-24 22:23:02.718  3282  3299 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-24 22:23:02.719  2156  2397 D BtGatt.GattService: start scan with filters,
,03-24 22:23:02.723  2156  2229 D BtGatt.ScanManager: handling starting scan,
,03-24 22:23:02.723  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 22:23:02.723  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-24 22:23:02.723  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING],
,03-24 22:23:02.723  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-24 22:23:02.724  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
,03-24 22:23:02.725  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 22:23:02.725  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 22:23:02.725  3282  3339 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 22:23:02.725  3282  3282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 22:23:02.725  3282  3339 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 22:23:02.725  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-24 22:23:02.725  3282  3339 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-24 22:23:02.726  2156  2219 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 22:23:02.726  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:23:02.728  2156  2219 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 22:23:02.728  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:23:02.729  2156  2229 D BtGatt.ScanManager: Starting BLE batch scan
03-24 22:23:02.729  2156  2229 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 22:23:02.731  2156  2219 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 22:23:02.731  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:23:02.731  2156  2397 D BtGatt.GattService: registerClient() - UUID=310e16b3-155b-4b59-8e57-0a09bd1165c0
03-24 22:23:02.731  2156  2219 D BtGatt.GattService: onClientRegistered() - UUID=310e16b3-155b-4b59-8e57-0a09bd1165c0, clientIf=6
,03-24 22:23:02.731  3282  3300 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-24 22:23:02.732  2156  2219 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 22:23:02.732  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:23:02.734  2156  2228 D BtGatt.AdvertiseManager: message : 0
,03-24 22:23:02.736  2156  2228 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 22:23:02.738  2156  2219 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 22:23:02.741  2156  2219 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 22:23:02.741  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-24 22:23:02.741  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 22:23:02.741   821  1416 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 22:23:02.743  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-24 22:23:02.743  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 22:23:02.744  3282  3339 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-24 22:23:02.744  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 22:23:02.744  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-24 22:23:02.744  3282  3339 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-24 22:23:02.744  3282  3339 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-24 22:23:02.744  3282  3339 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,03-24 22:23:02.745  3282  3282 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-24 22:23:02.745  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 22:23:02.745  3282  3282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,03-24 22:23:02.745  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-24 22:23:02.745  3282  3282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-24 22:23:02.745  3282  3282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-24 22:23:02.745  3282  3282 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 22:23:02.745   821  1259 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 22:23:02.745  3282  3282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 22:23:02.745  3282  3282 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-24 22:23:02.745  3282  3282 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 22:23:02.746  3282  3282 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,03-24 22:23:02.746  3282  3282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 22:23:02.746  3282  3783 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-24 22:23:02.746  3282  3339 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 22:23:02.748  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 22:23:02.748  3282  3339 I jxcore-log: 
03-24 22:23:02.748  3282  3783 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
03-24 22:23:02.749  3282  3339 I jxcore-log: ok 174 Can call startUpdateAdvertisingAndListening without error
03-24 22:23:02.749  3282  3339 I jxcore-log: 
,03-24 22:23:02.752  3282  3339 I io.jxcore.node.ConnectionHelper: start: Port number: 37974, start advertisements: false
,03-24 22:23:02.752  3282  3339 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 22:23:02.752  3282  3339 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should affect listening to advertisements only
03-24 22:23:02.752  3282  3339 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 22:23:02.752  3282  3339 I io.jxcore.node.ConnectionHelper: start: OK,
03-24 22:23:02.753  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 22:23:02.753  3282  3339 I jxcore-log: 
03-24 22:23:02.754  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-24 22:23:02.754  3282  3339 I jxcore-log: 
03-24 22:23:02.755  3282  3339 I jxcore-log: ok 175 Can call startListeningForAdvertisements without error
03-24 22:23:02.755  3282  3339 I jxcore-log: 
,03-24 22:23:03.340  2156  2221 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 22:23:04.075  3394  3785 V GoogleAuthProtoRequest: [342] a.<init>: mAccountName set to: thalitester@gmail.com
,03-24 22:23:04.128  1261  1281 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
03-24 22:23:04.128  1261  1281 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 22:23:04.128  1261  1281 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-24 22:23:04.128  1261  1281 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 22:23:04.135  1261  1281 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 22:23:04.159  3394  3785 W ExperimentUpdateService: [342] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,03-24 22:23:04.160  3394  3785 W ExperimentUpdateService: [342] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-24 22:23:04.160  3394  3785 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-24 22:23:04.160  3394  3785 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-24 22:23:04.160  3394  3785 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-24 22:23:04.160  3394  3785 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-24 22:23:04.160  3394  3785 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-24 22:23:04.160  3394  3785 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-24 22:23:04.160  3394  3785 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-24 22:23:04.160  3394  3785 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-24 22:23:04.160  3394  3785 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-24 22:23:04.160  3394  3785 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-24 22:23:04.188  2156  2156 D BtGatt.ScanManager: awakened up at time 247975
,03-24 22:23:04.190  2156  2229 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 22:23:04.195  2156  2219 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
,03-24 22:23:04.195  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:23:04.196  2156  2219 D BtGatt.GattService: current time is 247983458862
,03-24 22:23:04.196  2156  2219 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -60, 6, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0, 119, 114, 110, -43, -84, 107, 1, -128, -78, 8, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, 73, -71, -41, -75, 104, 84, 1, -128, -73, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -51, 80, -10, 108, 39, 113, 1, -128, -86, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,03-24 22:23:04.197  2156  2219 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-24 22:23:04.197  2156  2219 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,03-24 22:23:04.198  2156  2219 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 22:23:04.199  2156  2219 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,03-24 22:23:04.201  3282  3282 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 1
03-24 22:23:04.202  3282  3282 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> E0:DB:10:14:E2:C0], added - the peer count is 2
,03-24 22:23:04.202  3282  3282 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
03-24 22:23:04.203  3282  3282 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
03-24 22:23:04.203  3282  3282 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
03-24 22:23:04.204  3282  3282 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> E0:DB:10:14:E2:C0], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 
,03-24 22:23:04.215  3282  3339 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID F8:95:C7:87:3C:51,
,03-24 22:23:04.215  3282  3339 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> F8:95:C7:87:3C:51],
,03-24 22:23:04.218  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to G4-1 in address F8:95:C7:87:3C:51
,03-24 22:23:04.218  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
03-24 22:23:04.218  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
03-24 22:23:04.218  3282  3339 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: G4-1 F8:95:C7:87:3C:51
03-24 22:23:04.218  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to G4-1 in address F8:95:C7:87:3C:51
03-24 22:23:04.218  3282  3339 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: F8:95:C7:87:3C:51),
03-24 22:23:04.219  3282  3786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address F8:95:C7:87:3C:51 (thread ID: 360)
03-24 22:23:04.219  3282  3786 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-24 22:23:04.221  2156  2175 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,03-24 22:23:04.696  2156  2230 W bt-sdp  : process_service_search_attr_rsp
,03-24 22:23:05.532  2156  2230 W bt-btif : new conn_srvc id:26, app_id:1
,03-24 22:23:05.533  3282  3786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onSocketConnected: [<no peer name> F8:95:C7:87:3C:51] (thread ID: 360)
03-24 22:23:05.533  3282  3786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 360)
,03-24 22:23:05.534  3282  3786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesWritten: 15 bytes successfully written (thread ID: 361)
03-24 22:23:05.535  3282  3786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Outgoing connection initialized (*handshake* thread ID: 361)
03-24 22:23:05.535  3282  3786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 360)
,03-24 22:23:05.541  3282  3787 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 361),
,03-24 22:23:05.841  3282  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesRead: Read 15 bytes successfully (thread ID: 361)
,03-24 22:23:05.845  3282  3787 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Handshake succeeded with [<no peer name> F8:95:C7:87:3C:51]
03-24 22:23:05.845  3282  3787 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onHandshakeSucceeded: [<no peer name> F8:95:C7:87:3C:51] (thread ID: 360)
,03-24 22:23:05.845  3282  3787 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: handleSuccessfulClientThread: [<no peer name> F8:95:C7:87:3C:51] (thread ID: 360)
03-24 22:23:05.846  3282  3787 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 361)
,03-24 22:23:05.846  3282  3282 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> F8:95:C7:87:3C:51]
03-24 22:23:05.846  3282  3282 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing connection to peer [<no peer name> F8:95:C7:87:3C:51]
,03-24 22:23:05.847  3282  3282 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
03-24 22:23:05.847  3282  3282 I io.jxcore.node.ConnectionHelper: lowerBleDiscoveryPowerAndStartResetTimer: Lowering the power settings
03-24 22:23:05.847  3282  3282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 2 -> 0
03-24 22:23:05.847  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 22:23:05.847  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 22:23:05.847  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-24 22:23:05.847  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-24 22:23:05.847  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-24 22:23:05.847  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-24 22:23:05.853  2156  2228 D BtGatt.AdvertiseManager: message : 1
03-24 22:23:05.855  2156  2228 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-24 22:23:05.860  2156  2219 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0,
03-24 22:23:05.860  2156  2219 D BtGatt.GattService: Client app is not null!,
03-24 22:23:05.864  2156  2174 D BtGatt.GattService: unregisterClient() - clientIf=6,
03-24 22:23:05.865  3282  3282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 22:23:05.865  3282  3282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-24 22:23:05.866  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 3, timeout: 0, is connectable: false
03-24 22:23:05.866  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 22:23:05.866  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 22:23:05.866  3282  3282 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 22:23:05.867  3282  3282 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-24 22:23:05.867  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 22:23:05.867  3282  3282 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-24 22:23:05.877  2156  2174 D BtGatt.GattService: registerClient() - UUID=1fd5e886-a884-4c87-b80e-9f4fe70794d6
03-24 22:23:05.877  2156  2219 D BtGatt.GattService: onClientRegistered() - UUID=1fd5e886-a884-4c87-b80e-9f4fe70794d6, clientIf=6
,03-24 22:23:05.878  3282  3300 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-24 22:23:05.879  2156  2228 D BtGatt.AdvertiseManager: message : 0
,03-24 22:23:05.884  2156  2228 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 22:23:05.887  2156  2219 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 22:23:05.890  2156  2219 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 22:23:05.891  3282  3282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-24 22:23:05.894  2156  2396 D BtGatt.GattService: stopScan() - queue size =1
,03-24 22:23:05.896  2156  2219 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 22:23:05.896  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 22:23:05.896  2156  2174 D BtGatt.GattService: unregisterClient() - clientIf=5,
03-24 22:23:05.896  2156  2229 D BtGatt.ScanManager: stopping BLe Batch
,03-24 22:23:05.897  3282  3282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 22:23:05.897  3282  3282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 22:23:05.897  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 22:23:05.897  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 22:23:05.897  3282  3282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 22:23:05.897  3282  3282 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 22:23:05.897  2156  2219 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 22:23:05.897  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:23:05.898  2156  2229 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 22:23:05.900  2156  2219 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-24 22:23:05.900  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 22:23:05.900  2156  2219 D BtGatt.GattService: current time is 249687850111
,03-24 22:23:05.900  2156  2219 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -69, 4, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0, -64, -64, 127, -48, -79, 68, 1, -128, -86, 13, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-24 22:23:05.901  2156  2219 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-24 22:23:05.901  2156  2219 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,03-24 22:23:05.906  2156  2174 D BtGatt.GattService: registerClient() - UUID=292436e8-796a-4b76-9a75-181a28312eff
,03-24 22:23:05.906  2156  2219 D BtGatt.GattService: onClientRegistered() - UUID=292436e8-796a-4b76-9a75-181a28312eff, clientIf=5
03-24 22:23:05.907  3282  3300 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 22:23:05.907  2156  2175 D BtGatt.GattService: start scan with filters
03-24 22:23:05.908  3282  3282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
03-24 22:23:05.908  2156  2229 D BtGatt.ScanManager: handling starting scan
03-24 22:23:05.908  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 22:23:05.908  3282  3282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 3 -> 1
,03-24 22:23:05.909  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 22:23:05.909  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 22:23:05.909  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-24 22:23:05.909  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-24 22:23:05.909  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-24 22:23:05.909  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-24 22:23:05.910  2156  2219 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 22:23:05.910  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:23:05.912  2156  2219 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 22:23:05.912  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:23:05.913  2156  2229 D BtGatt.ScanManager: Starting BLE batch scan
,03-24 22:23:05.914  2156  2229 D BtGatt.ScanManager: configuring batch scan storage, appIf 5,
03-24 22:23:05.914  2156  2228 D BtGatt.AdvertiseManager: message : 1
03-24 22:23:05.915  2156  2219 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,03-24 22:23:05.916  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 22:23:05.916  2156  2228 D BtGatt.AdvertiseManager: stop advertise for client 6
03-24 22:23:05.917  2156  2219 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 22:23:05.917  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 22:23:05.923  2156  2219 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 22:23:05.923  2156  2219 D BtGatt.GattService: Client app is not null!
,03-24 22:23:05.925  2156  2174 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-24 22:23:05.926  3282  3282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 22:23:05.926  3282  3282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-24 22:23:05.926  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-24 22:23:05.926  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 22:23:05.926  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 22:23:05.926  3282  3282 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
,03-24 22:23:05.926  3282  3282 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false],
03-24 22:23:05.926  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 22:23:05.926  3282  3282 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...,
,03-24 22:23:05.934  2156  2174 D BtGatt.GattService: registerClient() - UUID=97524119-dfa6-4190-8d33-46cac2592d4d
03-24 22:23:05.935  2156  2219 D BtGatt.GattService: onClientRegistered() - UUID=97524119-dfa6-4190-8d33-46cac2592d4d, clientIf=6
03-24 22:23:05.935  3282  3300 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-24 22:23:05.936  2156  2228 D BtGatt.AdvertiseManager: message : 0
,03-24 22:23:05.939  2156  2228 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 22:23:05.941  2156  2219 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 22:23:05.944  2156  2219 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 22:23:05.944  3282  3282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-24 22:23:05.946  2156  2396 D BtGatt.GattService: stopScan() - queue size =1
,03-24 22:23:05.946  2156  2174 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-24 22:23:05.947  3282  3282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-24 22:23:05.947  3282  3282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 22:23:05.947  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-24 22:23:05.947  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 22:23:05.947  3282  3282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 22:23:05.947  3282  3282 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 22:23:05.949  2156  2219 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 22:23:05.949  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:23:05.949  2156  2229 D BtGatt.ScanManager: stopping BLe Batch
03-24 22:23:05.951  2156  2174 D BtGatt.GattService: registerClient() - UUID=45e8f188-68c8-4db1-9ef8-713a3cb7c6f3
03-24 22:23:05.951  2156  2219 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 22:23:05.951  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
03-24 22:23:05.951  2156  2219 D BtGatt.GattService: onClientRegistered() - UUID=45e8f188-68c8-4db1-9ef8-713a3cb7c6f3, clientIf=5
03-24 22:23:05.951  2156  2229 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 22:23:05.951  3282  3300 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 22:23:05.952  2156  2175 D BtGatt.GattService: start scan with filters
03-24 22:23:05.952  2156  2219 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,03-24 22:23:05.952  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:23:05.953  3282  3282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 22:23:05.953  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true,
,03-24 22:23:05.953  3282  3282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 2 -> 0
03-24 22:23:05.953  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 22:23:05.953  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
,03-24 22:23:05.953  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0,
03-24 22:23:05.953  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-24 22:23:05.953  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-24 22:23:05.953  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-24 22:23:05.956  2156  2229 D BtGatt.ScanManager: handling starting scan
03-24 22:23:05.957  2156  2228 D BtGatt.AdvertiseManager: message : 1
03-24 22:23:05.957  2156  2228 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-24 22:23:05.959  2156  2219 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 22:23:05.959  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:23:05.960  2156  2219 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,03-24 22:23:05.960  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:23:05.960  2156  2229 D BtGatt.ScanManager: Starting BLE batch scan
03-24 22:23:05.960  2156  2229 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-24 22:23:05.961  2156  2219 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 22:23:05.961  2156  2219 D BtGatt.GattService: Client app is not null!
03-24 22:23:05.962  2156  2174 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-24 22:23:05.962  3282  3282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-24 22:23:05.963  3282  3282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-24 22:23:05.963  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-24 22:23:05.963  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 22:23:05.963  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 22:23:05.963  3282  3282 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
,03-24 22:23:05.963  3282  3282 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 22:23:05.963  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 22:23:05.963  3282  3282 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-24 22:23:05.964  2156  2219 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 22:23:05.964  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 22:23:05.965  2156  2219 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 22:23:05.965  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 22:23:05.967  2156  2175 D BtGatt.GattService: registerClient() - UUID=9b314deb-6825-4c1e-b281-c605a2f20421
,03-24 22:23:05.968  2156  2219 D BtGatt.GattService: onClientRegistered() - UUID=9b314deb-6825-4c1e-b281-c605a2f20421, clientIf=6
03-24 22:23:05.968  3282  3300 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-24 22:23:05.969  2156  2228 D BtGatt.AdvertiseManager: message : 0
,03-24 22:23:05.972  2156  2228 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 22:23:05.974  2156  2219 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 22:23:05.976  2156  2219 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 22:23:05.977  3282  3282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-24 22:23:05.978  2156  2174 D BtGatt.GattService: stopScan() - queue size =1,
03-24 22:23:05.979  2156  2175 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-24 22:23:05.979  3282  3282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-24 22:23:05.980  3282  3282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 22:23:05.980  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-24 22:23:05.980  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 22:23:05.980  3282  3282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true,
03-24 22:23:05.980  2156  2219 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16,
,03-24 22:23:05.980  3282  3282 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 22:23:05.980  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 22:23:05.981  2156  2229 D BtGatt.ScanManager: stopping BLe Batch
,03-24 22:23:05.983  2156  2219 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,03-24 22:23:05.983  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:23:05.984  2156  2229 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5,
03-24 22:23:05.984  2156  2175 D BtGatt.GattService: registerClient() - UUID=d1f976a7-0c47-4975-bc13-72e4cd8594e2
,03-24 22:23:05.984  2156  2219 D BtGatt.GattService: onClientRegistered() - UUID=d1f976a7-0c47-4975-bc13-72e4cd8594e2, clientIf=5,
03-24 22:23:05.984  3282  3300 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 22:23:05.984  2156  2397 D BtGatt.GattService: start scan with filters,
03-24 22:23:05.985  2156  2219 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 22:23:05.985  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
03-24 22:23:05.985  3282  3282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 22:23:05.985  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-24 22:23:05.986  3282  3282 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing socket thread, for peer [<no peer name> F8:95:C7:87:3C:51], created successfully
03-24 22:23:05.986  3282  3282 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 1
03-24 22:23:05.986  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess,
03-24 22:23:05.986  3282  3282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-24 22:23:05.986  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-24 22:23:05.986  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess,
03-24 22:23:05.986  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 22:23:05.986  3282  3788 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 362)
03-24 22:23:05.987  3282  3788 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 37227,
03-24 22:23:05.987  3282  3788 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
03-24 22:23:05.987  3282  3788 I io.jxcore.node.ConnectionHelper: onListeningForIncomingConnections: Outgoing connection is using port 37227 (peer ID: F8:95:C7:87:3C:51)
,03-24 22:23:05.987  3282  3788 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "F8:95:C7:87:3C:51" removed
03-24 22:23:05.988  2156  2229 D BtGatt.ScanManager: handling starting scan
,03-24 22:23:05.990  2156  2219 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 22:23:05.990  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 22:23:05.991  2156  2219 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 22:23:05.991  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:23:05.991  2156  2229 D BtGatt.ScanManager: Starting BLE batch scan
03-24 22:23:05.991  2156  2229 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 22:23:05.991  3282  3339 I jxcore-log: INFO testThaliMobileNative: 
,03-24 22:23:05.991  3282  3339 I jxcore-log: 
03-24 22:23:05.992  2156  2219 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 22:23:05.992  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:23:05.993  3282  3339 I jxcore-log: INFO testThaliMobileNative: Forward connection
03-24 22:23:05.993  3282  3339 I jxcore-log: 
,03-24 22:23:05.993  2156  2219 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 22:23:05.993  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:23:05.999  3282  3339 I jxcore-log: INFO testThaliMobileNative: forwardSend
03-24 22:23:05.999  3282  3339 I jxcore-log: 
03-24 22:23:06.001  3282  3788 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 37227
,03-24 22:23:06.002  3282  3788 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
03-24 22:23:06.002  3282  3788 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-24 22:23:06.002  3282  3788 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-24 22:23:06.003  3282  3789 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 363, name: Sender)
,03-24 22:23:06.003  3282  3788 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 362)
03-24 22:23:06.003  3282  3788 D io.jxcore.node.OutgoingSocketThread: Exiting thread (ID: 362)
03-24 22:23:06.005  3282  3790 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 364, name: Receiver)
,03-24 22:23:06.161  3282  3339 I jxcore-log: INFO testThaliMobileNative: forwardData
03-24 22:23:06.161  3282  3339 I jxcore-log: 
,03-24 22:23:06.559  3282  3339 I jxcore-log: INFO testThaliMobileNative: forwardData
03-24 22:23:06.559  3282  3339 I jxcore-log: 
,03-24 22:23:06.636  3282  3339 I jxcore-log: INFO testThaliMobileNative: forwardData
03-24 22:23:06.636  3282  3339 I jxcore-log: 
,03-24 22:23:06.709  3282  3339 I jxcore-log: INFO testThaliMobileNative: forwardData
03-24 22:23:06.709  3282  3339 I jxcore-log: 
,03-24 22:23:06.801  3282  3339 I jxcore-log: INFO testThaliMobileNative: forwardData
03-24 22:23:06.801  3282  3339 I jxcore-log: 
,03-24 22:23:06.803  3282  3339 I jxcore-log: ok 176 received should match sent forward
03-24 22:23:06.803  3282  3339 I jxcore-log: 
,03-24 22:23:06.821  3282  3339 I jxcore-log: # teardown
03-24 22:23:06.821  3282  3339 I jxcore-log: 
,03-24 22:23:07.430  3282  3339 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 22:23:07.431  3282  3339 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
03-24 22:23:07.431  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-24 22:23:07.431  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-24 22:23:07.434  2156  2174 D BtGatt.GattService: stopScan() - queue size =1
,03-24 22:23:07.436  2156  2175 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-24 22:23:07.438  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-24 22:23:07.438  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 22:23:07.438  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false,
03-24 22:23:07.438  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-24 22:23:07.438  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING],
03-24 22:23:07.438  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 22:23:07.439  2156  2219 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 22:23:07.439  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 22:23:07.439  3282  3282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 22:23:07.439  2156  2229 D BtGatt.ScanManager: stopping BLe Batch
03-24 22:23:07.439  3282  3282 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
03-24 22:23:07.439  3282  3282 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed,
,03-24 22:23:07.442  3282  3339 I jxcore-log: ok 177 Should be able to call stopListeningForAdvertisments in teardown
03-24 22:23:07.442  3282  3339 I jxcore-log: 
03-24 22:23:07.443  2156  2219 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,03-24 22:23:07.443  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 22:23:07.443  2156  2229 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 22:23:07.444  3282  3339 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 22:23:07.444  3282  3339 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> F8:95:C7:87:3C:51]
03-24 22:23:07.444  3282  3339 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 362)
03-24 22:23:07.444  3282  3339 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 362)
03-24 22:23:07.444  3282  3339 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed,
03-24 22:23:07.444  3282  3339 D io.jxcore.node.OutgoingSocketThread: close: Stopping receiving thread...
,03-24 22:23:07.444  3282  3339 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 364,
,03-24 22:23:07.444  3282  3339 D io.jxcore.node.OutgoingSocketThread: close: Stopping sending thread...
03-24 22:23:07.444  3282  3339 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 363,
,03-24 22:23:07.445  3282  3339 D io.jxcore.node.OutgoingSocketThread: closeLocalSocketAndStreams: Closing... (thread ID: 362),
,03-24 22:23:07.445  3282  3789 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 363, thread name: Sender): Socket closed
03-24 22:23:07.445  3282  3789 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 363, name: Sender)
03-24 22:23:07.446  3282  3790 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 364, thread name: Receiver): bt socket closed, read return: -1
,03-24 22:23:07.446  3282  3790 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 364, name: Receiver)
03-24 22:23:07.447  3282  3339 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 362)
03-24 22:23:07.447  3282  3339 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
03-24 22:23:07.447  3282  3339 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-24 22:23:07.447  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-24 22:23:07.447  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,03-24 22:23:07.447  2156  2219 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,03-24 22:23:07.447  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:23:07.448  2156  2219 D BtGatt.GattService: current time is 251235259590
03-24 22:23:07.448  2156  2219 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -71, 14, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-24 22:23:07.448  2156  2219 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-24 22:23:07.448  3282  3339 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-24 22:23:07.449  3282  3783 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
,03-24 22:23:07.449  3282  3783 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-24 22:23:07.449  3282  3783 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-24 22:23:07.450  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-24 22:23:07.450  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-24 22:23:07.450  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 22:23:07.450  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 22:23:07.450  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-24 22:23:07.451  3282  3339 D BluetoothLeScanner: could not find callback wrapper
,03-24 22:23:07.451  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 22:23:07.451  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-24 22:23:07.452  3282  3282 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-24 22:23:07.453  3282  3282 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-24 22:23:07.453  2156  2228 D BtGatt.AdvertiseManager: message : 1
03-24 22:23:07.454  2156  2228 D BtGatt.AdvertiseManager: stop advertise for client 6
03-24 22:23:07.458  2156  2219 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 22:23:07.458  2156  2219 D BtGatt.GattService: Client app is not null!,
03-24 22:23:07.461  2156  2175 D BtGatt.GattService: unregisterClient() - clientIf=6
03-24 22:23:07.463  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 22:23:07.463  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-24 22:23:07.463  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-24 22:23:07.463  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-24 22:23:07.463  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-24 22:23:07.463  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-24 22:23:07.463  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 22:23:07.464  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-24 22:23:07.464  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-24 22:23:07.464  3282  3339 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-24 22:23:07.464  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 22:23:07.464  3282  3282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 22:23:07.464  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 22:23:07.464  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-24 22:23:07.469  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true},
03-24 22:23:07.469  3282  3339 I jxcore-log: 
03-24 22:23:07.471  3282  3282 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-24 22:23:07.471   821  1415 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 22:23:07.476  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
,03-24 22:23:07.477  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-24 22:23:07.477  3282  3282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 22:23:07.492  3282  3282 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-24 22:23:07.492  3282  3282 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 22:23:07.492  3282  3282 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 22:23:07.493  3282  3282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 22:23:07.493  3282  3282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-24 22:23:07.499  2156  2230 W bt-btif : bta_jv_rfc_port_to_cb(port_handle:0xf):jv handle:0x0 not FOUND
,03-24 22:23:07.500  3282  3339 I jxcore-log: ok 178 Should be able to call stopAdvertisingAndListening in teardown
03-24 22:23:07.500  3282  3339 I jxcore-log: 
,03-24 22:23:07.505  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 22:23:07.505  3282  3339 I jxcore-log: 
,03-24 22:23:07.506  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 22:23:07.506  3282  3339 I jxcore-log: 
,03-24 22:23:07.507  3282  3339 I jxcore-log: # setup
03-24 22:23:07.507  3282  3339 I jxcore-log: 
,03-24 22:23:07.944  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 22:23:07.944  3282  3339 I jxcore-log: 
,03-24 22:23:07.945  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 22:23:07.945  3282  3339 I jxcore-log: 
,03-24 22:23:07.954  3282  3339 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 22:23:07.954  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 22:23:07.954  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 22:23:07.954  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 22:23:07.954  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 22:23:07.954  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 22:23:07.954  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 22:23:07.954  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 22:23:07.958  3282  3339 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 22:23:07.964  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 22:23:07.964  3282  3339 I jxcore-log: 
,03-24 22:23:07.970  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 22:23:07.970  3282  3339 I jxcore-log: 
,03-24 22:23:07.977  3282  3339 I jxcore-log: # 42. #startListeningForAdvertisements should fail if start not called
03-24 22:23:07.977  3282  3339 I jxcore-log: 
,03-24 22:23:07.983  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 22:23:07.983  3282  3339 I jxcore-log: 
,03-24 22:23:08.561  3282  3339 I jxcore-log: ok 179 specific error should be returned
03-24 22:23:08.561  3282  3339 I jxcore-log: 
,03-24 22:23:08.566  3282  3339 I jxcore-log: # teardown
03-24 22:23:08.566  3282  3339 I jxcore-log: 
,03-24 22:23:08.705  3282  3339 I jxcore-log: # setup
03-24 22:23:08.705  3282  3339 I jxcore-log: 
,03-24 22:23:09.273  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 22:23:09.273  3282  3339 I jxcore-log: 
,03-24 22:23:09.277  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 22:23:09.277  3282  3339 I jxcore-log: 
,03-24 22:23:09.291  3282  3339 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 22:23:09.291  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 22:23:09.291  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 22:23:09.291  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 22:23:09.291  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 22:23:09.291  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 22:23:09.291  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 22:23:09.291  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 22:23:09.295  3282  3339 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 22:23:09.300  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,03-24 22:23:09.300  3282  3339 I jxcore-log: 
,03-24 22:23:09.305  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,03-24 22:23:09.305  3282  3339 I jxcore-log: 
,03-24 22:23:09.312  3282  3339 I jxcore-log: # 43. #startUpdateAdvertisingAndListening should fail if start not called
,03-24 22:23:09.312  3282  3339 I jxcore-log: 
,03-24 22:23:09.317  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
,03-24 22:23:09.317  3282  3339 I jxcore-log: 
,03-24 22:23:09.556  3282  3339 I jxcore-log: ok 180 specific error should be returned
03-24 22:23:09.556  3282  3339 I jxcore-log: 
,03-24 22:23:09.566  3282  3339 I jxcore-log: # teardown
03-24 22:23:09.566  3282  3339 I jxcore-log: 
,03-24 22:23:12.045  3282  3339 I jxcore-log: # setup
03-24 22:23:12.045  3282  3339 I jxcore-log: 
,03-24 22:23:12.196  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 22:23:12.196  3282  3339 I jxcore-log: 
,03-24 22:23:12.197  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 22:23:12.197  3282  3339 I jxcore-log: 
,03-24 22:23:12.204  3282  3339 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 22:23:12.204  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
,03-24 22:23:12.204  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 22:23:12.204  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 22:23:12.204  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 22:23:12.204  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 22:23:12.204  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 22:23:12.204  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 22:23:12.208  3282  3339 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 22:23:12.209  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 22:23:12.209  3282  3339 I jxcore-log: 
,03-24 22:23:12.211  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 22:23:12.211  3282  3339 I jxcore-log: 
,03-24 22:23:12.214  3282  3339 I jxcore-log: # 44. should be able to call #stopListeningForAdvertisements many times
03-24 22:23:12.214  3282  3339 I jxcore-log: 
,03-24 22:23:12.216  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 22:23:12.216  3282  3339 I jxcore-log: 
,03-24 22:23:12.546  2156  2230 E bt-btm  : btm_sec_disconnected - Clearing Pending flag
,03-24 22:23:12.554  2156  2156 D BluetoothMapService: onReceive
,03-24 22:23:12.636   821  1082 I ActivityManager: Start proc 3792:com.google.android.googlequicksearchbox:search/u0a28 for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver
,03-24 22:23:12.653   368   368 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 350us total 16.611ms
,03-24 22:23:12.669   368   368 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 349us total 15.761ms
,03-24 22:23:12.685   368   368 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 233us total 14.689ms
,03-24 22:23:12.744   821   859 D BluetoothManagerService: Message: 20
03-24 22:23:12.744   821   859 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@34218115:true
,03-24 22:23:12.756  3792  3792 I BTConnectionReceiver: onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,03-24 22:23:12.884  3282  3339 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 22:23:12.884  3282  3339 I jxcore-log: 
,03-24 22:23:12.888  3282  3339 I jxcore-log: DEBUG createNativeListener: listening 39808
03-24 22:23:12.888  3282  3339 I jxcore-log: 
,03-24 22:23:12.889  3282  3339 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 22:23:12.889  3282  3339 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 22:23:12.889  3282  3339 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 22:23:12.891  3282  3339 I jxcore-log: ok 181 no errors
03-24 22:23:12.891  3282  3339 I jxcore-log: 
,03-24 22:23:12.892  3282  3339 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 22:23:12.892  3282  3339 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 22:23:12.892  3282  3339 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 22:23:12.896  3282  3339 I jxcore-log: ok 182 still no errors
,03-24 22:23:12.896  3282  3339 I jxcore-log: 
,03-24 22:23:12.901  3282  3339 I jxcore-log: # teardown
,03-24 22:23:12.901  3282  3339 I jxcore-log: 
,03-24 22:23:12.923   821  1370 I ActivityManager: Start proc 3816:com.google.android.partnersetup/u0a16 for content provider com.google.android.partnersetup/.RlzAppProvider
,03-24 22:23:12.934  3792  3792 I BluetoothClassifier: Bluetooth Device Name: G4-1
,03-24 22:23:12.951   821  1328 I ActivityManager: Killing 3482:com.google.android.apps.magazines/u0a67 (adj 15): empty #17
,03-24 22:23:13.003  3282  3339 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-24 22:23:13.004  3282  3339 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-24 22:23:13.004  3282  3339 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 22:23:13.005  3282  3339 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 22:23:13.006  3282  3339 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 22:23:13.006  3282  3339 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 22:23:13.012  3282  3339 I jxcore-log: # setup
03-24 22:23:13.012  3282  3339 I jxcore-log: 
,03-24 22:23:13.160   821  1328 I ActivityManager: Killing 3430:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #18
,03-24 22:23:13.408   821  1082 I art     : Explicit concurrent mark sweep GC freed 29152(1400KB) AllocSpace objects, 7(394KB) LOS objects, 32% free, 33MB/49MB, paused 1.431ms total 99.263ms
,03-24 22:23:13.752  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 22:23:13.752  3282  3339 I jxcore-log: 
,03-24 22:23:13.758  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native,
03-24 22:23:13.758  3282  3339 I jxcore-log: 
,03-24 22:23:13.769  3282  3339 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 22:23:13.769  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 22:23:13.769  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 22:23:13.769  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 22:23:13.769  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 22:23:13.769  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 22:23:13.769  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 22:23:13.769  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 22:23:13.773  3282  3339 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 22:23:13.775  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 22:23:13.775  3282  3339 I jxcore-log: 
,03-24 22:23:13.777  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 22:23:13.777  3282  3339 I jxcore-log: 
,03-24 22:23:13.781  3282  3339 I jxcore-log: # 45. should be able to call #startListeningForAdvertisements many times
03-24 22:23:13.781  3282  3339 I jxcore-log: 
,03-24 22:23:13.783  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 22:23:13.783  3282  3339 I jxcore-log: 
,03-24 22:23:13.913  3282  3339 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 22:23:13.913  3282  3339 I jxcore-log: 
,03-24 22:23:13.915  3282  3339 I jxcore-log: DEBUG createNativeListener: listening 47600
03-24 22:23:13.915  3282  3339 I jxcore-log: 
,03-24 22:23:13.922  3282  3339 I io.jxcore.node.ConnectionHelper: start: Port number: 37974, start advertisements: false
,03-24 22:23:13.922  3282  3339 I io.jxcore.node.ConnectionHelper: restoreDefaultBleDiscoverySettings: Powering the BLE discovery back up
03-24 22:23:13.922  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 0 -> 2
,03-24 22:23:13.924  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 22:23:13.924  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 22:23:13.924  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-24 22:23:13.924  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-24 22:23:13.924  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-24 22:23:13.924  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-24 22:23:13.924  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 1, timeout: 0, is connectable: false
03-24 22:23:13.925  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
,03-24 22:23:13.925  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 1 -> 3
03-24 22:23:13.925  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 22:23:13.925  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 22:23:13.925  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
,03-24 22:23:13.925  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-24 22:23:13.925  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-24 22:23:13.925  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-24 22:23:13.925  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-24 22:23:13.925  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-24 22:23:13.925  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 0 -> 2
03-24 22:23:13.926  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 22:23:13.926  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 22:23:13.926  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-24 22:23:13.926  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
,03-24 22:23:13.926  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-24 22:23:13.926  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-24 22:23:13.926  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-24 22:23:13.926  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 22:23:13.926  3282  3339 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-24 22:23:13.926  3282  3339 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 22:23:13.926  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
03-24 22:23:13.935  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-24 22:23:13.935  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 22:23:13.935  3282  3339 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 22:23:13.945  2156  2396 D BtGatt.GattService: registerClient() - UUID=3cc18d67-1a89-4b0c-922d-c93df70c07ca
,03-24 22:23:13.946  2156  2219 D BtGatt.GattService: onClientRegistered() - UUID=3cc18d67-1a89-4b0c-922d-c93df70c07ca, clientIf=5
03-24 22:23:13.946  3282  3299 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 22:23:13.947  2156  2397 D BtGatt.GattService: start scan with filters
,03-24 22:23:13.949  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 22:23:13.949  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 22:23:13.949  2156  2229 D BtGatt.ScanManager: handling starting scan
03-24 22:23:13.950  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,03-24 22:23:13.951  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING],
03-24 22:23:13.951  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 22:23:13.953  3282  3282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false,
03-24 22:23:13.953  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 22:23:13.954   821  1393 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 22:23:13.955  2156  2219 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1,
03-24 22:23:13.955  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:23:13.957  2156  2219 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 22:23:13.957  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:23:13.957  2156  2229 D BtGatt.ScanManager: Starting BLE batch scan
,03-24 22:23:13.957  2156  2229 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-24 22:23:13.959  2156  2219 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 22:23:13.959  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 22:23:13.961  2156  2219 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 22:23:13.961  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 22:23:13.964  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
03-24 22:23:13.964  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-24 22:23:13.965  3282  3282 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,03-24 22:23:13.965  3282  3282 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-24 22:23:13.965  3282  3282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 22:23:13.966  3282  3339 I io.jxcore.node.ConnectionHelper: start: OK
03-24 22:23:13.970  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 22:23:13.970  3282  3339 I jxcore-log: 
,03-24 22:23:13.973  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 22:23:13.973  3282  3339 I jxcore-log: 
03-24 22:23:13.975  3282  3339 I jxcore-log: ok 183 no errors
03-24 22:23:13.975  3282  3339 I jxcore-log: 
,03-24 22:23:13.982  3282  3339 I io.jxcore.node.ConnectionHelper: start: Port number: 37974, start advertisements: false
,03-24 22:23:13.982  3282  3339 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 22:23:13.983  3282  3339 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 22:23:13.983  3282  3339 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 22:23:13.983  3282  3339 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 22:23:13.985  3282  3339 I jxcore-log: ok 184 still no errors
03-24 22:23:13.985  3282  3339 I jxcore-log: 
,03-24 22:23:13.994  3282  3339 I jxcore-log: # teardown
03-24 22:23:13.994  3282  3339 I jxcore-log: 
,03-24 22:23:14.235  3282  3339 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-24 22:23:14.235  3282  3339 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,03-24 22:23:14.235  3282  3339 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,03-24 22:23:14.235  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-24 22:23:14.235  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-24 22:23:14.235  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 22:23:14.235  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 22:23:14.236  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-24 22:23:14.236  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-24 22:23:14.241  2156  2174 D BtGatt.GattService: stopScan() - queue size =1
,03-24 22:23:14.246  2156  2397 D BtGatt.GattService: unregisterClient() - clientIf=5
03-24 22:23:14.247  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 22:23:14.247  2156  2219 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 22:23:14.247  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:23:14.247  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 22:23:14.247  2156  2229 D BtGatt.ScanManager: stopping BLe Batch
03-24 22:23:14.247  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-24 22:23:14.247  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED],
03-24 22:23:14.248  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-24 22:23:14.248  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 22:23:14.250  2156  2219 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 22:23:14.250  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:23:14.250  2156  2229 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 22:23:14.251  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 22:23:14.251  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,03-24 22:23:14.251  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-24 22:23:14.252  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,03-24 22:23:14.252  2156  2219 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 22:23:14.252  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:23:14.252  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 22:23:14.253  3282  3282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 22:23:14.253  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 22:23:14.253  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-24 22:23:14.261  3282  3282 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-24 22:23:14.262   821  1414 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 22:23:14.270  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-24 22:23:14.271  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 22:23:14.271  3282  3282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 22:23:14.276  3282  3282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-24 22:23:14.276  3282  3282 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 22:23:14.276  3282  3282 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 22:23:14.276  3282  3282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false,
03-24 22:23:14.278  3282  3339 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 22:23:14.278  3282  3339 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-24 22:23:14.278  3282  3339 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 22:23:14.279  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 22:23:14.279  3282  3339 I jxcore-log: 
,03-24 22:23:14.280  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 22:23:14.280  3282  3339 I jxcore-log: 
,03-24 22:23:14.289  3282  3339 I jxcore-log: # setup
03-24 22:23:14.289  3282  3339 I jxcore-log: 
,03-24 22:23:14.393  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 22:23:14.393  3282  3339 I jxcore-log: 
,03-24 22:23:14.397  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 22:23:14.397  3282  3339 I jxcore-log: 
,03-24 22:23:14.409  3282  3339 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 22:23:14.409  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 22:23:14.409  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 22:23:14.409  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 22:23:14.409  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 22:23:14.409  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 22:23:14.409  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 22:23:14.409  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 22:23:14.415  3282  3339 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 22:23:14.419  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 22:23:14.419  3282  3339 I jxcore-log: 
,03-24 22:23:14.425  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 22:23:14.425  3282  3339 I jxcore-log: 
,03-24 22:23:14.433  3282  3339 I jxcore-log: # 46. should be able to call #startUpdateAdvertisingAndListening many times
03-24 22:23:14.433  3282  3339 I jxcore-log: 
,03-24 22:23:14.438  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 22:23:14.438  3282  3339 I jxcore-log: 
,03-24 22:23:14.568  3282  3339 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 22:23:14.568  3282  3339 I jxcore-log: 
,03-24 22:23:14.571  3282  3339 I jxcore-log: DEBUG createNativeListener: listening 50866
03-24 22:23:14.571  3282  3339 I jxcore-log: 
,03-24 22:23:14.578  3282  3339 I io.jxcore.node.ConnectionHelper: start: Port number: 50866, start advertisements: true
,03-24 22:23:14.578  3282  3339 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-24 22:23:14.578  3282  3339 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-24 22:23:14.578  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-24 22:23:14.584  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-24 22:23:14.584  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 22:23:14.584  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-24 22:23:14.584  3282  3339 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 22:23:14.591  2156  2396 D BtGatt.GattService: registerClient() - UUID=7ad9d43f-92b2-42c7-83c1-bda9fb18e8ed
,03-24 22:23:14.591  2156  2219 D BtGatt.GattService: onClientRegistered() - UUID=7ad9d43f-92b2-42c7-83c1-bda9fb18e8ed, clientIf=5
03-24 22:23:14.592  3282  3299 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-24 22:23:14.592  2156  2174 D BtGatt.GattService: start scan with filters,
,03-24 22:23:14.594  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-24 22:23:14.595  2156  2229 D BtGatt.ScanManager: handling starting scan
,03-24 22:23:14.595  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 22:23:14.595  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,03-24 22:23:14.595  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,03-24 22:23:14.595  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 22:23:14.596  3282  3282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-24 22:23:14.596  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,03-24 22:23:14.597  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 22:23:14.597  3282  3339 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 22:23:14.597  2156  2219 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,03-24 22:23:14.597  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
,03-24 22:23:14.598  3282  3339 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 22:23:14.598  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-24 22:23:14.598  3282  3339 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-24 22:23:14.599  2156  2219 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,03-24 22:23:14.599  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:23:14.599  2156  2229 D BtGatt.ScanManager: Starting BLE batch scan
,03-24 22:23:14.599  2156  2229 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 22:23:14.602  2156  2219 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 22:23:14.602  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 22:23:14.604  2156  2219 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 22:23:14.604  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:23:14.609  2156  2174 D BtGatt.GattService: registerClient() - UUID=198b99a6-9077-48d7-91a1-efaa196757a6,
03-24 22:23:14.609  2156  2219 D BtGatt.GattService: onClientRegistered() - UUID=198b99a6-9077-48d7-91a1-efaa196757a6, clientIf=6
,03-24 22:23:14.610  3282  3300 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-24 22:23:14.612  2156  2228 D BtGatt.AdvertiseManager: message : 0
,03-24 22:23:14.617  2156  2228 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 22:23:14.621  2156  2219 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 22:23:14.625  2156  2219 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 22:23:14.626  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-24 22:23:14.626  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-24 22:23:14.627   821  1370 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 22:23:14.634  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 22:23:14.634  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-24 22:23:14.634  3282  3339 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,03-24 22:23:14.634  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-24 22:23:14.636  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-24 22:23:14.637  3282  3339 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-24 22:23:14.637  3282  3339 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-24 22:23:14.637  3282  3339 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK,
,03-24 22:23:14.637  3282  3282 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,03-24 22:23:14.638  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 22:23:14.638  3282  3282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,03-24 22:23:14.638  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-24 22:23:14.638  3282  3282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
,03-24 22:23:14.638  3282  3282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
,03-24 22:23:14.638  3282  3282 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 22:23:14.639  3282  3282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-24 22:23:14.639  3282  3282 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-24 22:23:14.639  3282  3282 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed,
,03-24 22:23:14.639  3282  3282 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-24 22:23:14.639  3282  3282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 22:23:14.639   821  1393 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 22:23:14.640  3282  3339 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 22:23:14.641  3282  3839 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-24 22:23:14.647  3282  3839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
03-24 22:23:14.647  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 22:23:14.647  3282  3339 I jxcore-log: ,
,03-24 22:23:14.651  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 22:23:14.651  3282  3339 I jxcore-log: 
,03-24 22:23:14.653  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-24 22:23:14.653  3282  3339 I jxcore-log: 
,03-24 22:23:14.655  3282  3339 I jxcore-log: ok 185 no errors
03-24 22:23:14.655  3282  3339 I jxcore-log: 
,03-24 22:23:14.661  3282  3339 I io.jxcore.node.ConnectionHelper: start: Port number: 50866, start advertisements: true
,03-24 22:23:14.662  3282  3339 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-24 22:23:14.662  3282  3339 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything,
03-24 22:23:14.662  3282  3339 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 22:23:14.662  3282  3339 I io.jxcore.node.ConnectionHelper: start: OK
03-24 22:23:14.666  3282  3339 I jxcore-log: ok 186 still no errors,
03-24 22:23:14.666  3282  3339 I jxcore-log: 
,03-24 22:23:14.672  3282  3339 I jxcore-log: # teardown
03-24 22:23:14.672  3282  3339 I jxcore-log: 
,03-24 22:23:15.107  2156  2156 D BtGatt.ScanManager: awakened up at time 258895
,03-24 22:23:15.111  2156  2229 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5,
,03-24 22:23:15.121  2156  2219 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,03-24 22:23:15.121  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:23:15.121  2156  2219 D BtGatt.GattService: current time is 258909137764
,03-24 22:23:15.122  2156  2219 D BtGatt.GattService: Batch record : [-40, 125, -47, -59, -86, 84, 1, -128, -78, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -63, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-24 22:23:15.123  2156  2219 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 22:23:15.123  2156  2219 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-24 22:23:15.126  3282  3282 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 1
,03-24 22:23:15.127  3282  3282 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> E0:DB:10:14:E2:C0], added - the peer count is 2
03-24 22:23:15.128  3282  3282 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
03-24 22:23:15.128  3282  3282 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> E0:DB:10:14:E2:C0], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 
,03-24 22:23:15.133  3282  3339 I jxcore-log: DEBUG createPeerListener: createPeerListener
03-24 22:23:15.133  3282  3339 I jxcore-log: 
,03-24 22:23:15.141  3282  3339 I jxcore-log: DEBUG createPeerListener: pleaseConnect= false
03-24 22:23:15.141  3282  3339 I jxcore-log: 
,03-24 22:23:15.149  3282  3339 I jxcore-log: DEBUG createPeerListener: createPeerListener
03-24 22:23:15.149  3282  3339 I jxcore-log: 
,03-24 22:23:15.155  3282  3339 I jxcore-log: DEBUG createPeerListener: pleaseConnect= false
03-24 22:23:15.155  3282  3339 I jxcore-log: 
,03-24 22:23:16.135  2156  2156 D BtGatt.ScanManager: awakened up at time 259922
,03-24 22:23:16.136  2156  2229 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 22:23:16.143  2156  2219 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,03-24 22:23:16.143  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:23:16.143  2156  2219 D BtGatt.GattService: current time is 259930677034
03-24 22:23:16.143  2156  2219 D BtGatt.GattService: Batch record : [-40, 125, -47, -59, -86, 84, 1, -128, -78, 18, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -62, 19, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0],
03-24 22:23:16.143  2156  2219 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 22:23:16.143  2156  2219 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
,03-24 22:23:16.145  3282  3282 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> E0:DB:10:14:E2:C0] updated - the peer count is 2
03-24 22:23:16.146  3282  3282 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
,03-24 22:23:16.254  3282  3339 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-24 22:23:16.254  3282  3339 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-24 22:23:16.255  3282  3339 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,03-24 22:23:16.255  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,03-24 22:23:16.255  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-24 22:23:16.256  3282  3339 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-24 22:23:16.256  3282  3839 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-24 22:23:16.256  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-24 22:23:16.256  3282  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-24 22:23:16.256  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,03-24 22:23:16.256  3282  3839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-24 22:23:16.256  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,03-24 22:23:16.256  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 22:23:16.257  3282  3282 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-24 22:23:16.257  3282  3282 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-24 22:23:16.257  3282  3282 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-24 22:23:16.260  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-24 22:23:16.260  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...,
03-24 22:23:16.265  2156  2174 D BtGatt.GattService: stopScan() - queue size =1
03-24 22:23:16.267  2156  2174 D BtGatt.GattService: unregisterClient() - clientIf=5
03-24 22:23:16.268  2156  2219 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,03-24 22:23:16.269  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:23:16.269  2156  2229 D BtGatt.ScanManager: stopping BLe Batch
03-24 22:23:16.269  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 22:23:16.269  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 22:23:16.269  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false,
03-24 22:23:16.269  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-24 22:23:16.269  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
,03-24 22:23:16.269  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 22:23:16.269  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,03-24 22:23:16.271  2156  2228 D BtGatt.AdvertiseManager: message : 1
03-24 22:23:16.271  2156  2228 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-24 22:23:16.271  2156  2219 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 22:23:16.271  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 22:23:16.273  2156  2229 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 22:23:16.274  2156  2219 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 22:23:16.274  2156  2219 D BtGatt.GattService: Client app is not null!
03-24 22:23:16.275  2156  2397 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-24 22:23:16.276  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 22:23:16.276  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-24 22:23:16.276  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-24 22:23:16.276  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-24 22:23:16.276  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-24 22:23:16.276  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-24 22:23:16.276  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 22:23:16.276  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-24 22:23:16.276  2156  2219 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 22:23:16.277  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 22:23:16.277  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
03-24 22:23:16.277  3282  3339 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-24 22:23:16.277  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false,
03-24 22:23:16.278  3282  3282 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-24 22:23:16.278  3282  3282 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 22:23:16.279  3282  3282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 22:23:16.279  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
03-24 22:23:16.279  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-24 22:23:16.281  3282  3339 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements,
03-24 22:23:16.281  3282  3339 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 22:23:16.281  3282  3339 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 22:23:16.306  3282  3282 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
,03-24 22:23:16.306   821  1416 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 22:23:16.311  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
,03-24 22:23:16.312  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0,
03-24 22:23:16.313  3282  3282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 22:23:16.316  3282  3282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true,
,03-24 22:23:16.316  3282  3282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 22:23:16.316  3282  3282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-24 22:23:16.318  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
,03-24 22:23:16.318  3282  3339 I jxcore-log: 
03-24 22:23:16.319  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 22:23:16.319  3282  3339 I jxcore-log: 
,03-24 22:23:16.320  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
,03-24 22:23:16.320  3282  3339 I jxcore-log: 
,03-24 22:23:16.330  3282  3339 I jxcore-log: # setup
03-24 22:23:16.330  3282  3339 I jxcore-log: 
,03-24 22:23:16.710  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 22:23:16.710  3282  3339 I jxcore-log: 
03-24 22:23:16.711  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 22:23:16.711  3282  3339 I jxcore-log: 
,03-24 22:23:16.719  3282  3339 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 22:23:16.719  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 22:23:16.719  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 22:23:16.719  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 22:23:16.719  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 22:23:16.719  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 22:23:16.719  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 22:23:16.719  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 22:23:16.722  3282  3339 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 22:23:16.724  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 22:23:16.724  3282  3339 I jxcore-log: 
03-24 22:23:16.725  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 22:23:16.725  3282  3339 I jxcore-log: 
,03-24 22:23:16.728  3282  3339 I jxcore-log: # 47. should be able to call #stopAdvertisingAndListening many times
03-24 22:23:16.728  3282  3339 I jxcore-log: 
03-24 22:23:16.730  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 22:23:16.730  3282  3339 I jxcore-log: 
,03-24 22:23:18.191  3282  3339 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 22:23:18.191  3282  3339 I jxcore-log: 
,03-24 22:23:18.193  3282  3339 I jxcore-log: DEBUG createNativeListener: listening 44771,
03-24 22:23:18.193  3282  3339 I jxcore-log: 
,03-24 22:23:18.195  3282  3339 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 22:23:18.195  3282  3339 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 22:23:18.195  3282  3339 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 22:23:18.197  3282  3339 I jxcore-log: ok 187 no errors
03-24 22:23:18.197  3282  3339 I jxcore-log: 
03-24 22:23:18.198  3282  3339 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-24 22:23:18.198  3282  3339 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 22:23:18.198  3282  3339 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 22:23:18.200  3282  3339 I jxcore-log: ok 188 still no errors
03-24 22:23:18.200  3282  3339 I jxcore-log: 
,03-24 22:23:18.206  3282  3339 I jxcore-log: # teardown
03-24 22:23:18.206  3282  3339 I jxcore-log: 
,03-24 22:23:18.311  3282  3339 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 22:23:18.311  3282  3339 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 22:23:18.311  3282  3339 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 22:23:18.315  3282  3339 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 22:23:18.315  3282  3339 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 22:23:18.315  3282  3339 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 22:23:18.330  3282  3339 I jxcore-log: # setup
03-24 22:23:18.330  3282  3339 I jxcore-log: 
,03-24 22:23:18.440  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 22:23:18.440  3282  3339 I jxcore-log: 
,03-24 22:23:18.444  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 22:23:18.444  3282  3339 I jxcore-log: 
,03-24 22:23:18.453  3282  3339 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 22:23:18.453  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 22:23:18.453  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 22:23:18.453  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 22:23:18.453  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 22:23:18.453  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 22:23:18.453  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 22:23:18.453  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 22:23:18.457  3282  3339 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 22:23:18.460  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 22:23:18.460  3282  3339 I jxcore-log: 
,03-24 22:23:18.464  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 22:23:18.464  3282  3339 I jxcore-log: 
,03-24 22:23:18.470  3282  3339 I jxcore-log: # 48. can get the network status before starting
03-24 22:23:18.470  3282  3339 I jxcore-log: 
,03-24 22:23:18.474  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 22:23:18.474  3282  3339 I jxcore-log: 
,03-24 22:23:18.584  3282  3339 I jxcore-log: ok 189 network status should have certain non-empty properties
03-24 22:23:18.584  3282  3339 I jxcore-log: 
,03-24 22:23:18.586  3282  3339 I jxcore-log: # teardown
03-24 22:23:18.586  3282  3339 I jxcore-log: 
,03-24 22:23:18.772  3282  3339 I jxcore-log: # setup
03-24 22:23:18.772  3282  3339 I jxcore-log: 
,03-24 22:23:18.896  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 22:23:18.896  3282  3339 I jxcore-log: 
,03-24 22:23:18.900  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 22:23:18.900  3282  3339 I jxcore-log: 
,03-24 22:23:18.909  3282  3339 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 22:23:18.909  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
,03-24 22:23:18.909  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 22:23:18.909  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 22:23:18.909  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 22:23:18.909  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 22:23:18.909  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 22:23:18.909  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 22:23:18.914  3282  3339 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 22:23:18.915  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 22:23:18.915  3282  3339 I jxcore-log: 
,03-24 22:23:18.917  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 22:23:18.917  3282  3339 I jxcore-log: 
,03-24 22:23:18.919  3282  3339 I jxcore-log: # 49. error returned with bad router
03-24 22:23:18.919  3282  3339 I jxcore-log: 
03-24 22:23:18.921  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 22:23:18.921  3282  3339 I jxcore-log: 
,03-24 22:23:19.068  3282  3339 I jxcore-log: ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a string
03-24 22:23:19.068  3282  3339 I jxcore-log: 
,03-24 22:23:19.070  3282  3339 I jxcore-log: ok 190 specific error expected
03-24 22:23:19.070  3282  3339 I jxcore-log: 
,03-24 22:23:19.072  3282  3339 I jxcore-log: # teardown
03-24 22:23:19.072  3282  3339 I jxcore-log: 
,03-24 22:23:19.194  3282  3339 I jxcore-log: # setup
03-24 22:23:19.194  3282  3339 I jxcore-log: 
,03-24 22:23:19.330  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 22:23:19.330  3282  3339 I jxcore-log: 
,03-24 22:23:19.334  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 22:23:19.334  3282  3339 I jxcore-log: 
,03-24 22:23:19.346  3282  3339 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 22:23:19.346  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 22:23:19.346  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 22:23:19.346  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 22:23:19.346  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 22:23:19.346  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
,03-24 22:23:19.346  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 22:23:19.346  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 22:23:19.349  3282  3339 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 22:23:19.350  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 22:23:19.350  3282  3339 I jxcore-log: 
,03-24 22:23:19.352  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 22:23:19.352  3282  3339 I jxcore-log: 
,03-24 22:23:19.355  3282  3339 I jxcore-log: # 50. all services are stopped when we call stop
,03-24 22:23:19.355  3282  3339 I jxcore-log: 
,03-24 22:23:19.357  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
,03-24 22:23:19.357  3282  3339 I jxcore-log: 
,03-24 22:23:20.248  3282  3339 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 22:23:20.248  3282  3339 I jxcore-log: 
03-24 22:23:20.250  3282  3339 I jxcore-log: DEBUG createNativeListener: listening 48495
03-24 22:23:20.250  3282  3339 I jxcore-log: 
,03-24 22:23:20.256  3282  3339 I io.jxcore.node.ConnectionHelper: start: Port number: 50866, start advertisements: false,
03-24 22:23:20.256  3282  3339 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 22:23:20.256  3282  3339 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,03-24 22:23:20.256  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-24 22:23:20.260  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 22:23:20.260  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-24 22:23:20.260  3282  3339 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 22:23:20.264  2156  2175 D BtGatt.GattService: registerClient() - UUID=dd41f652-fc8b-4cf1-9ea3-b021c902eadd
,03-24 22:23:20.265  2156  2219 D BtGatt.GattService: onClientRegistered() - UUID=dd41f652-fc8b-4cf1-9ea3-b021c902eadd, clientIf=5
,03-24 22:23:20.266  3282  3300 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5,
,03-24 22:23:20.266  2156  2174 D BtGatt.GattService: start scan with filters
03-24 22:23:20.268  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 22:23:20.268  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 22:23:20.268  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,03-24 22:23:20.268  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-24 22:23:20.268  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 22:23:20.268  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 22:23:20.269   821  1082 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 22:23:20.269  3282  3282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 22:23:20.269  2156  2229 D BtGatt.ScanManager: handling starting scan
,03-24 22:23:20.289  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 22:23:20.289  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 22:23:20.289  3282  3282 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,03-24 22:23:20.289  3282  3282 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 22:23:20.290  3282  3282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 22:23:20.290  3282  3339 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 22:23:20.294  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 22:23:20.294  3282  3339 I jxcore-log: 
,03-24 22:23:20.295  2156  2219 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 22:23:20.295  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 22:23:20.296  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 22:23:20.296  3282  3339 I jxcore-log: 
03-24 22:23:20.296  2156  2219 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15,
,03-24 22:23:20.296  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:23:20.297  2156  2229 D BtGatt.ScanManager: Starting BLE batch scan
03-24 22:23:20.297  2156  2229 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 22:23:20.300  2156  2219 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 22:23:20.300  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 22:23:20.304  2156  2219 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 22:23:20.304  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:23:20.304  3282  3339 I io.jxcore.node.ConnectionHelper: start: Port number: 48495, start advertisements: true
03-24 22:23:20.304  3282  3339 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 22:23:20.304  3282  3339 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-24 22:23:20.304  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-24 22:23:20.307  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-24 22:23:20.307  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
03-24 22:23:20.307  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 22:23:20.307  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 22:23:20.308  3282  3339 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
,03-24 22:23:20.308  3282  3339 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 22:23:20.308  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 22:23:20.308  3282  3339 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-24 22:23:20.312  2156  2397 D BtGatt.GattService: registerClient() - UUID=7cc81689-f7c9-4091-b6c1-751b69e0c541
03-24 22:23:20.312  2156  2219 D BtGatt.GattService: onClientRegistered() - UUID=7cc81689-f7c9-4091-b6c1-751b69e0c541, clientIf=6
,03-24 22:23:20.313  3282  3299 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-24 22:23:20.314  2156  2228 D BtGatt.AdvertiseManager: message : 0
,03-24 22:23:20.318  2156  2228 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 22:23:20.322  2156  2219 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 22:23:20.325  2156  2219 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
03-24 22:23:20.325  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-24 22:23:20.325  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 22:23:20.325  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 22:23:20.325  3282  3282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-24 22:23:20.325  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-24 22:23:20.325  3282  3282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
,03-24 22:23:20.325  3282  3282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-24 22:23:20.326   821   836 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 22:23:20.328  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-24 22:23:20.328  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 22:23:20.328  3282  3339 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-24 22:23:20.328  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 22:23:20.329  3282  3282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-24 22:23:20.329  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-24 22:23:20.330  3282  3339 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true,
03-24 22:23:20.330  3282  3339 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-24 22:23:20.330  3282  3339 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-24 22:23:20.330  3282  3339 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 22:23:20.330  3282  3282 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-24 22:23:20.330  3282  3282 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed,
03-24 22:23:20.330  3282  3282 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-24 22:23:20.333   821  1416 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 22:23:20.333  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-24 22:23:20.333  3282  3339 I jxcore-log: 
03-24 22:23:20.334  3282  3841 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-24 22:23:20.336  3282  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-24 22:23:20.343  3282  3339 I jxcore-log: DEBUG createNativeListener: new incoming socket
,03-24 22:23:20.343  3282  3339 I jxcore-log: 
,03-24 22:23:20.346  3282  3339 I jxcore-log: DEBUG createNativeListener: creating incoming mux
,03-24 22:23:20.346  3282  3339 I jxcore-log: 
,03-24 22:23:20.350  3282  3339 I jxcore-log: DEBUG createNativeListener: new mux
,03-24 22:23:20.350  3282  3339 I jxcore-log: 
,03-24 22:23:20.355  3282  3339 I jxcore-log: ok 191 connection to servers manager should succeed after starting
,03-24 22:23:20.355  3282  3339 I jxcore-log: 
,03-24 22:23:20.365  3282  3339 I jxcore-log: ok 192 connection to router server should succeed after starting
,03-24 22:23:20.365  3282  3339 I jxcore-log: 
,03-24 22:23:20.367  3282  3339 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections,
03-24 22:23:20.367  3282  3339 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
,03-24 22:23:20.367  3282  3339 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,03-24 22:23:20.368  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-24 22:23:20.368  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-24 22:23:20.368  3282  3339 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed,
03-24 22:23:20.369  3282  3841 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-24 22:23:20.369  3282  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,03-24 22:23:20.369  3282  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-24 22:23:20.369  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-24 22:23:20.369  3282  3282 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-24 22:23:20.369  3282  3282 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-24 22:23:20.369  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,03-24 22:23:20.369  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 22:23:20.369  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,03-24 22:23:20.369  3282  3282 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-24 22:23:20.369  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-24 22:23:20.369  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-24 22:23:20.372  2156  2174 D BtGatt.GattService: stopScan() - queue size =1
03-24 22:23:20.373  2156  2397 D BtGatt.GattService: unregisterClient() - clientIf=5
03-24 22:23:20.374  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-24 22:23:20.374  2156  2219 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 22:23:20.374  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 22:23:20.374  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 22:23:20.374  2156  2229 D BtGatt.ScanManager: stopping BLe Batch
,03-24 22:23:20.374  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-24 22:23:20.374  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-24 22:23:20.374  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING],
03-24 22:23:20.374  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true,
03-24 22:23:20.374  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-24 22:23:20.376  2156  2228 D BtGatt.AdvertiseManager: message : 1
,03-24 22:23:20.377  2156  2228 D BtGatt.AdvertiseManager: stop advertise for client 6
03-24 22:23:20.377  2156  2219 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 22:23:20.377  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 22:23:20.378  2156  2229 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 22:23:20.379  2156  2219 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,03-24 22:23:20.379  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:23:20.380  2156  2219 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 22:23:20.380  2156  2219 D BtGatt.GattService: Client app is not null!
03-24 22:23:20.382  2156  2174 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-24 22:23:20.382  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 22:23:20.383  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-24 22:23:20.383  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,03-24 22:23:20.383  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-24 22:23:20.383  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-24 22:23:20.383  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 22:23:20.383  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 22:23:20.384  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-24 22:23:20.385  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-24 22:23:20.385  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,03-24 22:23:20.386  3282  3282 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 22:23:20.386  3282  3282 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 22:23:20.386  3282  3282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 22:23:20.386  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 22:23:20.386  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-24 22:23:20.391  3282  3282 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-24 22:23:20.391   821  1375 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 22:23:20.391  3282  3339 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 22:23:20.391  3282  3339 I jxcore-log: 
,03-24 22:23:20.394  3282  3339 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 22:23:20.394  3282  3339 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-24 22:23:20.394  3282  3339 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 22:23:20.397  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-24 22:23:20.397  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 22:23:20.397  3282  3282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 22:23:20.400  3282  3282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-24 22:23:20.400  3282  3282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-24 22:23:20.400  3282  3282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 22:23:20.402  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-24 22:23:20.402  3282  3339 I jxcore-log: 
,03-24 22:23:20.404  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 22:23:20.404  3282  3339 I jxcore-log: 
,03-24 22:23:20.405  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 22:23:20.405  3282  3339 I jxcore-log: 
,03-24 22:23:20.409  3282  3339 I jxcore-log: ok 193 is stopped after calling stop
03-24 22:23:20.409  3282  3339 I jxcore-log: 
,03-24 22:23:20.414  3282  3339 I jxcore-log: ok 194 connection to servers manager should fail after stopping
03-24 22:23:20.414  3282  3339 I jxcore-log: 
,03-24 22:23:20.418  3282  3339 I jxcore-log: ok 195 connection to router server should fail after stopping
03-24 22:23:20.418  3282  3339 I jxcore-log: 
,03-24 22:23:20.422  3282  3339 I jxcore-log: # teardown
03-24 22:23:20.422  3282  3339 I jxcore-log: 
,03-24 22:23:20.525  3282  3339 I jxcore-log: # setup
03-24 22:23:20.525  3282  3339 I jxcore-log: 
,03-24 22:23:21.159  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 22:23:21.159  3282  3339 I jxcore-log: 
,03-24 22:23:21.164  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 22:23:21.164  3282  3339 I jxcore-log: 
,03-24 22:23:21.172  3282  3339 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 22:23:21.172  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 22:23:21.172  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 22:23:21.172  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 22:23:21.172  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 22:23:21.172  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 22:23:21.172  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 22:23:21.172  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 22:23:21.177  3282  3339 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 22:23:21.178  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 22:23:21.178  3282  3339 I jxcore-log: 
,03-24 22:23:21.180  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 22:23:21.180  3282  3339 I jxcore-log: 
,03-24 22:23:21.183  3282  3339 I jxcore-log: # 51. make sure terminateConnection is properly hooked up
03-24 22:23:21.183  3282  3339 I jxcore-log: 
,03-24 22:23:21.184  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 22:23:21.184  3282  3339 I jxcore-log: 
,03-24 22:23:21.312  3282  3339 I jxcore-log: ok 196 called with right arguments
03-24 22:23:21.312  3282  3339 I jxcore-log: 
,03-24 22:23:21.314  3282  3339 I jxcore-log: # teardown
03-24 22:23:21.314  3282  3339 I jxcore-log: 
,03-24 22:23:21.466  3282  3339 I jxcore-log: # setup
03-24 22:23:21.466  3282  3339 I jxcore-log: 
,03-24 22:23:21.644  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 22:23:21.644  3282  3339 I jxcore-log: 
,03-24 22:23:21.645  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 22:23:21.645  3282  3339 I jxcore-log: 
,03-24 22:23:21.653  3282  3339 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 22:23:21.653  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 22:23:21.653  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 22:23:21.653  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 22:23:21.653  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 22:23:21.653  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 22:23:21.653  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 22:23:21.653  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 22:23:21.657  3282  3339 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 22:23:21.659  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 22:23:21.659  3282  3339 I jxcore-log: 
,03-24 22:23:21.661  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 22:23:21.661  3282  3339 I jxcore-log: 
,03-24 22:23:21.665  3282  3339 I jxcore-log: # 52. make sure terminateListener is properly hooked up
03-24 22:23:21.665  3282  3339 I jxcore-log: 
,03-24 22:23:21.666  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 22:23:21.666  3282  3339 I jxcore-log: 
,03-24 22:23:21.848  3282  3339 I jxcore-log: ok 197 called with right arguments
03-24 22:23:21.848  3282  3339 I jxcore-log: 
,03-24 22:23:21.850  3282  3339 I jxcore-log: # teardown
03-24 22:23:21.850  3282  3339 I jxcore-log: 
,03-24 22:23:22.024  3282  3339 I jxcore-log: # setup
03-24 22:23:22.024  3282  3339 I jxcore-log: 
,03-24 22:23:22.123  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 22:23:22.123  3282  3339 I jxcore-log: 
,03-24 22:23:22.125  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 22:23:22.125  3282  3339 I jxcore-log: 
,03-24 22:23:22.133  3282  3339 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 22:23:22.133  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 22:23:22.133  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 22:23:22.133  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 22:23:22.133  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 22:23:22.133  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 22:23:22.133  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 22:23:22.133  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 22:23:22.135  3282  3339 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 22:23:22.139  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 22:23:22.139  3282  3339 I jxcore-log: 
,03-24 22:23:22.143  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 22:23:22.143  3282  3339 I jxcore-log: 
,03-24 22:23:22.149  3282  3339 I jxcore-log: # 53. make sure we actually call kill connections properly
03-24 22:23:22.149  3282  3339 I jxcore-log: 
,03-24 22:23:22.153  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 22:23:22.153  3282  3339 I jxcore-log: 
,03-24 22:23:22.304  3282  3339 I jxcore-log: ok 198 specific error expected
03-24 22:23:22.304  3282  3339 I jxcore-log: 
,03-24 22:23:22.306  3282  3339 I jxcore-log: # teardown
03-24 22:23:22.306  3282  3339 I jxcore-log: 
,03-24 22:23:22.569  3282  3339 I jxcore-log: # setup
03-24 22:23:22.569  3282  3339 I jxcore-log: 
,03-24 22:23:22.671  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 22:23:22.671  3282  3339 I jxcore-log: 
,03-24 22:23:22.676  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 22:23:22.676  3282  3339 I jxcore-log: 
,03-24 22:23:22.690  3282  3339 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 22:23:22.690  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 22:23:22.690  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 22:23:22.690  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
,03-24 22:23:22.690  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 22:23:22.690  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 22:23:22.690  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 22:23:22.690  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 22:23:22.698  3282  3339 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 22:23:22.701  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 22:23:22.701  3282  3339 I jxcore-log: 
,03-24 22:23:22.706  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 22:23:22.706  3282  3339 I jxcore-log: 
,03-24 22:23:22.715  3282  3339 I jxcore-log: # 54. thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
03-24 22:23:22.715  3282  3339 I jxcore-log: 
,03-24 22:23:22.720  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 22:23:22.720  3282  3339 I jxcore-log: 
,03-24 22:23:22.872  3282  3339 I jxcore-log: DEBUG createNativeListener: creating native server
,03-24 22:23:22.872  3282  3339 I jxcore-log: 
03-24 22:23:22.874  3282  3339 I jxcore-log: DEBUG createNativeListener: listening 54128
,03-24 22:23:22.874  3282  3339 I jxcore-log: 
,03-24 22:23:22.878  3282  3339 I jxcore-log: INFO thaliMobileNativeWrapper: routerPortConnectionFailed - {"routerPort":56560,"error":{}}
03-24 22:23:22.878  3282  3339 I jxcore-log: 
,03-24 22:23:22.879  3282  3339 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-24 22:23:22.879  3282  3339 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 22:23:22.879  3282  3339 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
03-24 22:23:22.881  3282  3339 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 22:23:22.881  3282  3339 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 22:23:22.881  3282  3339 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 22:23:22.887  3282  3339 I jxcore-log: ok 199 failure reason is as expected,
03-24 22:23:22.887  3282  3339 I jxcore-log: 
03-24 22:23:22.887  3282  3339 I jxcore-log: ok 200 error description is as expected
03-24 22:23:22.887  3282  3339 I jxcore-log: 
03-24 22:23:22.888  3282  3339 I jxcore-log: ok 201 must be stopped
03-24 22:23:22.888  3282  3339 I jxcore-log: 
,03-24 22:23:22.895  3282  3339 I jxcore-log: # teardown,
03-24 22:23:22.895  3282  3339 I jxcore-log: 
,03-24 22:23:23.052  3282  3339 I jxcore-log: # setup,
03-24 22:23:23.052  3282  3339 I jxcore-log: 
,03-24 22:23:23.272  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 22:23:23.272  3282  3339 I jxcore-log: 
,03-24 22:23:23.278  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 22:23:23.278  3282  3339 I jxcore-log: 
,03-24 22:23:23.289  3282  3339 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 22:23:23.289  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true,
03-24 22:23:23.289  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 22:23:23.289  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 22:23:23.289  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 22:23:23.289  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 22:23:23.289  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 22:23:23.289  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 22:23:23.293  3282  3339 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 22:23:23.296  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,03-24 22:23:23.296  3282  3339 I jxcore-log: 
,03-24 22:23:23.299  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,03-24 22:23:23.299  3282  3339 I jxcore-log: 
,03-24 22:23:23.306  3282  3339 I jxcore-log: # 55. We repeat failedConnection event when we get it from thaliTcpServersManager
,03-24 22:23:23.306  3282  3339 I jxcore-log: 
,03-24 22:23:23.310  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
,03-24 22:23:23.310  3282  3339 I jxcore-log: 
,03-24 22:23:23.513  3282  3339 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 22:23:23.513  3282  3339 I jxcore-log: 
,03-24 22:23:23.515  3282  3339 I jxcore-log: DEBUG createNativeListener: listening 47437
03-24 22:23:23.515  3282  3339 I jxcore-log: 
03-24 22:23:23.519  3282  3339 I jxcore-log: ok 202 peerIdentifier matches
03-24 22:23:23.519  3282  3339 I jxcore-log: 
03-24 22:23:23.520  3282  3339 I jxcore-log: ok 203 error description matches
03-24 22:23:23.520  3282  3339 I jxcore-log: 
03-24 22:23:23.524  3282  3339 I jxcore-log: # teardown
03-24 22:23:23.524  3282  3339 I jxcore-log: 
,03-24 22:23:23.663  3282  3339 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 22:23:23.664  3282  3339 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 22:23:23.664  3282  3339 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 22:23:23.665  3282  3339 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 22:23:23.665  3282  3339 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 22:23:23.665  3282  3339 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 22:23:23.674  3282  3339 I jxcore-log: # setup
03-24 22:23:23.674  3282  3339 I jxcore-log: 
,03-24 22:23:23.816  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 22:23:23.816  3282  3339 I jxcore-log: 
03-24 22:23:23.821  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,03-24 22:23:23.821  3282  3339 I jxcore-log: 
,03-24 22:23:23.833  3282  3339 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 22:23:23.833  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 22:23:23.833  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 22:23:23.833  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 22:23:23.833  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 22:23:23.833  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 22:23:23.833  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 22:23:23.833  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 22:23:23.837  3282  3339 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 22:23:23.838  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 22:23:23.838  3282  3339 I jxcore-log: 
03-24 22:23:23.840  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 22:23:23.840  3282  3339 I jxcore-log: 
,03-24 22:23:23.849  3282  3339 I jxcore-log: # 56. we successfully receive and replay discoveryAdvertisingStateUpdate
03-24 22:23:23.849  3282  3339 I jxcore-log: ,
03-24 22:23:23.851  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 22:23:23.851  3282  3339 I jxcore-log: 
,03-24 22:23:24.009  3282  3339 I jxcore-log: DEBUG createNativeListener: creating native server,
03-24 22:23:24.009  3282  3339 I jxcore-log: 
,03-24 22:23:24.011  3282  3339 I jxcore-log: DEBUG createNativeListener: listening 57692
03-24 22:23:24.011  3282  3339 I jxcore-log: 
,03-24 22:23:24.018  3282  3339 I io.jxcore.node.ConnectionHelper: start: Port number: 48495, start advertisements: false
,03-24 22:23:24.018  3282  3339 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 22:23:24.018  3282  3339 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 22:23:24.018  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-24 22:23:24.023  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 22:23:24.023  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 22:23:24.023  3282  3339 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 22:23:24.029  2156  2397 D BtGatt.GattService: registerClient() - UUID=45868ed3-edfe-4d25-8765-f8f299b1bec8
03-24 22:23:24.029  2156  2219 D BtGatt.GattService: onClientRegistered() - UUID=45868ed3-edfe-4d25-8765-f8f299b1bec8, clientIf=5
03-24 22:23:24.030  3282  3299 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 22:23:24.030  2156  2175 D BtGatt.GattService: start scan with filters
,03-24 22:23:24.033  2156  2229 D BtGatt.ScanManager: handling starting scan
03-24 22:23:24.034  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 22:23:24.034  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-24 22:23:24.034  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-24 22:23:24.034  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-24 22:23:24.034  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
,03-24 22:23:24.035  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 22:23:24.035  3282  3282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 22:23:24.036   821   837 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 22:23:24.040  2156  2219 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 22:23:24.040  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 22:23:24.040  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 22:23:24.040  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 22:23:24.040  3282  3339 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 22:23:24.041  3282  3282 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 22:23:24.041  3282  3282 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 22:23:24.041  3282  3282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-24 22:23:24.043  2156  2219 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 22:23:24.043  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:23:24.043  2156  2229 D BtGatt.ScanManager: Starting BLE batch scan
03-24 22:23:24.043  2156  2229 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 22:23:24.044  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 22:23:24.044  3282  3339 I jxcore-log: 
,03-24 22:23:24.045  3282  3339 I jxcore-log: ok 204 discoveryActive matches
03-24 22:23:24.045  3282  3339 I jxcore-log: 
03-24 22:23:24.046  3282  3339 I jxcore-log: ok 205 advertisingActive matches
03-24 22:23:24.046  3282  3339 I jxcore-log: 
03-24 22:23:24.046  2156  2219 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 22:23:24.046  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:23:24.048  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 22:23:24.048  3282  3339 I jxcore-log: 
,03-24 22:23:24.048  2156  2219 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 22:23:24.048  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 22:23:24.055  3282  3339 I jxcore-log: not ok 206 discoveryActive matches,
03-24 22:23:24.055  3282  3339 I jxcore-log: ,
03-24 22:23:24.055  3282  3339 I jxcore-log:   ---
03-24 22:23:24.055  3282  3339 I jxcore-log: 
,03-24 22:23:24.055  3282  3339 I jxcore-log:     operator: equal
03-24 22:23:24.055  3282  3339 I jxcore-log: 
03-24 22:23:24.055  3282  3339 I jxcore-log:     expected: false
03-24 22:23:24.055  3282  3339 I jxcore-log: 
03-24 22:23:24.055  3282  3339 I jxcore-log:     actual:   true
03-24 22:23:24.055  3282  3339 I jxcore-log: 
03-24 22:23:24.056  3282  3339 I jxcore-log:   ...
03-24 22:23:24.056  3282  3339 I jxcore-log: 
03-24 22:23:24.056  3282  3339 I jxcore-log: ok 207 advertisingActive matches
03-24 22:23:24.056  3282  3339 I jxcore-log: 
03-24 22:23:24.058  3282  3339 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-24 22:23:24.058  3282  3339 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
03-24 22:23:24.058  3282  3339 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
03-24 22:23:24.058  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-24 22:23:24.058  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,03-24 22:23:24.058  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 22:23:24.058  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 22:23:24.058  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-24 22:23:24.058  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-24 22:23:24.060  2156  2175 D BtGatt.GattService: stopScan() - queue size =1
03-24 22:23:24.062  2156  2175 D BtGatt.GattService: unregisterClient() - clientIf=5
03-24 22:23:24.063  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 22:23:24.063  2156  2219 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 22:23:24.064  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:23:24.064  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 22:23:24.064  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false,
03-24 22:23:24.064  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-24 22:23:24.064  2156  2229 D BtGatt.ScanManager: stopping BLe Batch
,03-24 22:23:24.065  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-24 22:23:24.066  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 22:23:24.067  2156  2219 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 22:23:24.067  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:23:24.067  2156  2229 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 22:23:24.067  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 22:23:24.067  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 22:23:24.067  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-24 22:23:24.068  2156  2219 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 22:23:24.069  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:23:24.069  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-24 22:23:24.069  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 22:23:24.069  3282  3282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 22:23:24.069  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 22:23:24.069  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-24 22:23:24.076  3282  3282 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-24 22:23:24.076   821  1082 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 22:23:24.082  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-24 22:23:24.083  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 22:23:24.083  3282  3282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 22:23:24.087  3282  3282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 22:23:24.087  3282  3282 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 22:23:24.087  3282  3282 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-24 22:23:24.087  3282  3282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 22:23:24.091  3282  3339 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 22:23:24.092  3282  3339 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 22:23:24.092  3282  3339 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 22:23:24.095  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 22:23:24.095  3282  3339 I jxcore-log: 
,03-24 22:23:24.097  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 22:23:24.097  3282  3339 I jxcore-log: 
,03-24 22:23:24.112  3282  3339 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 22:23:24.112  3282  3339 I jxcore-log: 
,03-24 22:23:24.114  3282  3339 I jxcore-log: DEBUG createNativeListener: listening 57035
03-24 22:23:24.114  3282  3339 I jxcore-log: 
,03-24 22:23:24.119  3282  3339 I io.jxcore.node.ConnectionHelper: start: Port number: 57035, start advertisements: true
03-24 22:23:24.119  3282  3339 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 22:23:24.119  3282  3339 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-24 22:23:24.119  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-24 22:23:24.122  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
03-24 22:23:24.122  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 22:23:24.122  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 22:23:24.122  3282  3339 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 22:23:24.125  2156  2396 D BtGatt.GattService: registerClient() - UUID=6b443614-9ccb-4b05-b684-0716e70e3ac5
,03-24 22:23:24.126  2156  2219 D BtGatt.GattService: onClientRegistered() - UUID=6b443614-9ccb-4b05-b684-0716e70e3ac5, clientIf=5
03-24 22:23:24.126  3282  3299 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5,
03-24 22:23:24.127  2156  2397 D BtGatt.GattService: start scan with filters
,03-24 22:23:24.128  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 22:23:24.128  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 22:23:24.128  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-24 22:23:24.128  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,03-24 22:23:24.128  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 22:23:24.128  2156  2229 D BtGatt.ScanManager: handling starting scan
03-24 22:23:24.128  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 22:23:24.128  3282  3282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 22:23:24.128  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 22:23:24.128  3282  3339 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 22:23:24.128  3282  3339 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-24 22:23:24.128  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 22:23:24.128  3282  3339 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-24 22:23:24.131  2156  2219 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 22:23:24.131  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
03-24 22:23:24.133  2156  2219 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15,
03-24 22:23:24.133  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 22:23:24.133  2156  2397 D BtGatt.GattService: registerClient() - UUID=30be15d3-14da-48ec-8a63-66dc58812740
03-24 22:23:24.134  2156  2219 D BtGatt.GattService: onClientRegistered() - UUID=30be15d3-14da-48ec-8a63-66dc58812740, clientIf=6
03-24 22:23:24.134  3282  3300 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-24 22:23:24.134  2156  2229 D BtGatt.ScanManager: Starting BLE batch scan
,03-24 22:23:24.134  2156  2229 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-24 22:23:24.135  2156  2228 D BtGatt.AdvertiseManager: message : 0
03-24 22:23:24.137  2156  2219 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 22:23:24.137  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:23:24.138  2156  2219 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 22:23:24.139  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:23:24.141  2156  2228 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 22:23:24.144  2156  2219 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 22:23:24.147  2156  2219 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 22:23:24.148  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-24 22:23:24.148  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 22:23:24.148   821  1414 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 22:23:24.150  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 22:23:24.151  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 22:23:24.151  3282  3339 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,03-24 22:23:24.151  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-24 22:23:24.151  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...,
03-24 22:23:24.152  3282  3339 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-24 22:23:24.152  3282  3339 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-24 22:23:24.152  3282  3339 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,03-24 22:23:24.152  3282  3339 I io.jxcore.node.ConnectionHelper: start: OK
03-24 22:23:24.152  3282  3282 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-24 22:23:24.152  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 22:23:24.152  3282  3282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-24 22:23:24.152  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-24 22:23:24.152  3282  3282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-24 22:23:24.152  3282  3282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-24 22:23:24.152  3282  3282 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 22:23:24.153  3282  3282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 22:23:24.153  3282  3282 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-24 22:23:24.153  3282  3282 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 22:23:24.153  3282  3282 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-24 22:23:24.153  3282  3282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-24 22:23:24.154  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 22:23:24.154  3282  3339 I jxcore-log: 
03-24 22:23:24.154   821  1082 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 22:23:24.156  3282  3842 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-24 22:23:24.159  3282  3339 I jxcore-log: not ok 208 discoveryActive matches,
03-24 22:23:24.159  3282  3339 I jxcore-log: 
03-24 22:23:24.159  3282  3339 I jxcore-log:   ---
03-24 22:23:24.159  3282  3339 I jxcore-log: 
03-24 22:23:24.159  3282  3339 I jxcore-log:     operator: equal
03-24 22:23:24.159  3282  3339 I jxcore-log: 
03-24 22:23:24.159  3282  3842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
03-24 22:23:24.159  3282  3339 I jxcore-log:     expected: false
03-24 22:23:24.159  3282  3339 I jxcore-log: 
03-24 22:23:24.159  3282  3339 I jxcore-log:     actual:   true
03-24 22:23:24.159  3282  3339 I jxcore-log: 
03-24 22:23:24.159  3282  3339 I jxcore-log:   ...
03-24 22:23:24.159  3282  3339 I jxcore-log: 
,03-24 22:23:24.162  3282  3339 I jxcore-log: not ok 209 advertisingActive matches
03-24 22:23:24.162  3282  3339 I jxcore-log: 
03-24 22:23:24.162  3282  3339 I jxcore-log:   ---
03-24 22:23:24.162  3282  3339 I jxcore-log: 
,03-24 22:23:24.162  3282  3339 I jxcore-log:     operator: equal
03-24 22:23:24.162  3282  3339 I jxcore-log: 
,03-24 22:23:24.163  3282  3339 I jxcore-log:     expected: true
03-24 22:23:24.163  3282  3339 I jxcore-log: 
03-24 22:23:24.163  3282  3339 I jxcore-log:     actual:   false
03-24 22:23:24.163  3282  3339 I jxcore-log: 
03-24 22:23:24.163  3282  3339 I jxcore-log:   ...
03-24 22:23:24.163  3282  3339 I jxcore-log: 
03-24 22:23:24.165  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 22:23:24.165  3282  3339 I jxcore-log: 
,03-24 22:23:24.168  3282  3339 I jxcore-log: not ok 210 discoveryActive matches
03-24 22:23:24.168  3282  3339 I jxcore-log: 
03-24 22:23:24.168  3282  3339 I jxcore-log:   ---
03-24 22:23:24.168  3282  3339 I jxcore-log: 
03-24 22:23:24.168  3282  3339 I jxcore-log:     operator: equal
03-24 22:23:24.168  3282  3339 I jxcore-log: 
03-24 22:23:24.168  3282  3339 I jxcore-log:     expected: false
03-24 22:23:24.168  3282  3339 I jxcore-log: 
03-24 22:23:24.168  3282  3339 I jxcore-log:     actual:   true
03-24 22:23:24.168  3282  3339 I jxcore-log: 
,03-24 22:23:24.168  3282  3339 I jxcore-log:   ...
03-24 22:23:24.168  3282  3339 I jxcore-log: 
03-24 22:23:24.169  3282  3339 I jxcore-log: ok 211 advertisingActive matches
03-24 22:23:24.169  3282  3339 I jxcore-log: 
03-24 22:23:24.170  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-24 22:23:24.170  3282  3339 I jxcore-log: 
03-24 22:23:24.171  3282  3339 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 22:23:24.171  3282  3339 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-24 22:23:24.171  3282  3339 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-24 22:23:24.171  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-24 22:23:24.171  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-24 22:23:24.171  3282  3339 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-24 22:23:24.172  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-24 22:23:24.172  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-24 22:23:24.172  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 22:23:24.172  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 22:23:24.172  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-24 22:23:24.172  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-24 22:23:24.172  3282  3842 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-24 22:23:24.172  3282  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,03-24 22:23:24.172  3282  3842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-24 22:23:24.173  2156  2396 D BtGatt.GattService: stopScan() - queue size =1
03-24 22:23:24.174  2156  2397 D BtGatt.GattService: unregisterClient() - clientIf=5
03-24 22:23:24.175  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 22:23:24.175  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 22:23:24.175  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-24 22:23:24.175  2156  2219 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 22:23:24.175  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:23:24.175  2156  2229 D BtGatt.ScanManager: stopping BLe Batch
03-24 22:23:24.175  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-24 22:23:24.175  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
,03-24 22:23:24.175  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 22:23:24.175  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-24 22:23:24.177  2156  2228 D BtGatt.AdvertiseManager: message : 1
03-24 22:23:24.177  2156  2228 D BtGatt.AdvertiseManager: stop advertise for client 6
03-24 22:23:24.177  2156  2219 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,03-24 22:23:24.177  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:23:24.177  2156  2229 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 22:23:24.179  2156  2219 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 22:23:24.179  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:23:24.180  2156  2219 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 22:23:24.180  2156  2219 D BtGatt.GattService: Client app is not null!
,03-24 22:23:24.181  2156  2396 D BtGatt.GattService: unregisterClient() - clientIf=6
03-24 22:23:24.182  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 22:23:24.183  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-24 22:23:24.183  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,03-24 22:23:24.184  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-24 22:23:24.184  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-24 22:23:24.184  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 22:23:24.184  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,03-24 22:23:24.185  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-24 22:23:24.186  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-24 22:23:24.186  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 22:23:24.186  3282  3282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 22:23:24.187  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 22:23:24.187  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-24 22:23:24.191  3282  3282 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-24 22:23:24.192   821  1393 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 22:23:24.197  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-24 22:23:24.198  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-24 22:23:24.198  3282  3282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 22:23:24.201  3282  3282 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false,
03-24 22:23:24.201  3282  3282 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,03-24 22:23:24.201  3282  3282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 22:23:24.201  3282  3282 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 22:23:24.201  3282  3282 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 22:23:24.201  3282  3282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 22:23:24.201  3282  3282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 22:23:24.202  3282  3282 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-24 22:23:24.202  3282  3339 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 22:23:24.202  3282  3339 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 22:23:24.202  3282  3339 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 22:23:24.204  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-24 22:23:24.204  3282  3339 I jxcore-log: 
03-24 22:23:24.205  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 22:23:24.205  3282  3339 I jxcore-log: 
03-24 22:23:24.205  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 22:23:24.205  3282  3339 I jxcore-log: 
,03-24 22:23:24.214  3282  3339 I jxcore-log: DEBUG createNativeListener: creating native server,
03-24 22:23:24.214  3282  3339 I jxcore-log: 
,03-24 22:23:24.216  3282  3339 I jxcore-log: DEBUG createNativeListener: listening 54311
03-24 22:23:24.216  3282  3339 I jxcore-log: 
,03-24 22:23:24.223  3282  3339 I jxcore-log: # teardown
03-24 22:23:24.223  3282  3339 I jxcore-log: 
,03-24 22:23:24.836  3282  3339 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-24 22:23:24.837  3282  3339 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 22:23:24.837  3282  3339 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 22:23:24.841  3282  3339 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 22:23:24.841  3282  3339 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 22:23:24.841  3282  3339 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 22:23:24.852  3282  3339 I jxcore-log: # setup,
03-24 22:23:24.852  3282  3339 I jxcore-log: 
,03-24 22:23:24.979  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native,
03-24 22:23:24.979  3282  3339 I jxcore-log: 
,03-24 22:23:24.984  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 22:23:24.984  3282  3339 I jxcore-log: 
,03-24 22:23:24.991  3282  3339 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 22:23:24.991  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 22:23:24.991  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 22:23:24.991  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 22:23:24.991  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 22:23:24.991  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 22:23:24.991  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 22:23:24.991  3282  3339 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 22:23:24.995  3282  3339 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 22:23:24.997  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 22:23:24.997  3282  3339 I jxcore-log: 
,03-24 22:23:25.009  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 22:23:25.009  3282  3339 I jxcore-log: 
,03-24 22:23:25.012  3282  3339 I jxcore-log: # 57. can do HTTP requests between peers
03-24 22:23:25.012  3282  3339 I jxcore-log: 
,03-24 22:23:25.014  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 22:23:25.014  3282  3339 I jxcore-log: 
,03-24 22:23:25.309  3282  3339 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 22:23:25.309  3282  3339 I jxcore-log: 
,03-24 22:23:25.315  3282  3339 I jxcore-log: DEBUG createNativeListener: listening 37733
,03-24 22:23:25.315  3282  3339 I jxcore-log: 
,03-24 22:23:25.334  3282  3339 I io.jxcore.node.ConnectionHelper: start: Port number: 57035, start advertisements: false
03-24 22:23:25.334  3282  3339 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 22:23:25.334  3282  3339 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 22:23:25.334  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-24 22:23:25.338  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...,
03-24 22:23:25.338  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-24 22:23:25.338  3282  3339 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 22:23:25.344  2156  2175 D BtGatt.GattService: registerClient() - UUID=708547f5-e3a3-405d-ae39-1bd3689f9844
03-24 22:23:25.345  2156  2219 D BtGatt.GattService: onClientRegistered() - UUID=708547f5-e3a3-405d-ae39-1bd3689f9844, clientIf=5
,03-24 22:23:25.345  3282  3299 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 22:23:25.346  2156  2397 D BtGatt.GattService: start scan with filters
,03-24 22:23:25.347  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
03-24 22:23:25.347  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 22:23:25.347  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,03-24 22:23:25.347  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-24 22:23:25.347  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 22:23:25.347  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 22:23:25.347  3282  3282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 22:23:25.347  2156  2229 D BtGatt.ScanManager: handling starting scan
03-24 22:23:25.347   821  1393 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 22:23:25.350  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 22:23:25.350  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 22:23:25.350  3282  3339 I io.jxcore.node.ConnectionHelper: start: OK
03-24 22:23:25.350  3282  3282 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 22:23:25.350  3282  3282 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-24 22:23:25.351  3282  3282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 22:23:25.353  2156  2219 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 22:23:25.353  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 22:23:25.355  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 22:23:25.355  3282  3339 I jxcore-log: 
,03-24 22:23:25.355  2156  2219 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 22:23:25.356  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:23:25.356  2156  2229 D BtGatt.ScanManager: Starting BLE batch scan
03-24 22:23:25.356  2156  2229 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 22:23:25.357  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 22:23:25.357  3282  3339 I jxcore-log: 
,03-24 22:23:25.358  2156  2219 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,03-24 22:23:25.358  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 22:23:25.360  2156  2219 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 22:23:25.360  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 22:23:25.367  3282  3339 I io.jxcore.node.ConnectionHelper: start: Port number: 37733, start advertisements: true
,03-24 22:23:25.367  3282  3339 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 22:23:25.367  3282  3339 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-24 22:23:25.367  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-24 22:23:25.371  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
03-24 22:23:25.371  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running,
03-24 22:23:25.372  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 22:23:25.372  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 22:23:25.372  3282  3339 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 22:23:25.372  3282  3339 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-24 22:23:25.372  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 22:23:25.372  3282  3339 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-24 22:23:25.379  2156  2174 D BtGatt.GattService: registerClient() - UUID=40a80395-a8fa-4ec5-a7d9-d0beee4aff88,
03-24 22:23:25.379  2156  2219 D BtGatt.GattService: onClientRegistered() - UUID=40a80395-a8fa-4ec5-a7d9-d0beee4aff88, clientIf=6
,03-24 22:23:25.380  3282  3300 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-24 22:23:25.383  2156  2228 D BtGatt.AdvertiseManager: message : 0,
,03-24 22:23:25.387  2156  2228 D BtGatt.AdvertiseManager: starting multi advertising,
,03-24 22:23:25.391  2156  2219 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0,
,03-24 22:23:25.394  2156  2219 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
03-24 22:23:25.394  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-24 22:23:25.394  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 22:23:25.394  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 22:23:25.395  3282  3282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-24 22:23:25.395  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-24 22:23:25.395  3282  3282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-24 22:23:25.395   821   836 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 22:23:25.395  3282  3282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
,03-24 22:23:25.402  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-24 22:23:25.402  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 22:23:25.402  3282  3282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-24 22:23:25.403  3282  3339 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,03-24 22:23:25.403  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-24 22:23:25.404  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-24 22:23:25.405  3282  3339 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-24 22:23:25.405  3282  3339 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-24 22:23:25.405  3282  3339 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-24 22:23:25.406  3282  3282 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-24 22:23:25.406  3282  3282 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-24 22:23:25.406  3282  3282 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,03-24 22:23:25.407  3282  3339 I io.jxcore.node.ConnectionHelper: start: OK
03-24 22:23:25.411   821  1375 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 22:23:25.411  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-24 22:23:25.411  3282  3339 I jxcore-log: 
,03-24 22:23:25.413  3282  3843 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-24 22:23:25.418  3282  3843 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-24 22:23:26.369  2156  2156 D BtGatt.ScanManager: awakened up at time 270156
,03-24 22:23:26.371  2156  2229 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 22:23:26.381  2156  2219 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2,
,03-24 22:23:26.381  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 22:23:26.381  2156  2219 D BtGatt.GattService: current time is 270168897499
,03-24 22:23:26.382  2156  2219 D BtGatt.GattService: Batch record : [31, -48, -66, 45, -54, 90, 1, -128, -78, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -60, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-24 22:23:26.382  2156  2219 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,03-24 22:23:26.383  2156  2219 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-24 22:23:26.386  3282  3282 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> E0:DB:10:14:E2:C0], added - the peer count is 1
03-24 22:23:26.387  3282  3282 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 2
03-24 22:23:26.387  3282  3282 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> E0:DB:10:14:E2:C0], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: ,
03-24 22:23:26.388  3282  3282 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
,03-24 22:23:26.394  3282  3339 I jxcore-log: DEBUG createPeerListener: createPeerListener
03-24 22:23:26.394  3282  3339 I jxcore-log: 
,03-24 22:23:26.401  3282  3339 I jxcore-log: DEBUG createPeerListener: pleaseConnect= false
03-24 22:23:26.401  3282  3339 I jxcore-log: 
,03-24 22:23:26.404  3282  3339 I jxcore-log: ok 212 found a peer! {"peerIdentifier":"E0:DB:10:14:E2:C0","portNumber":38798,"hostAddress":"127.0.0.1"}
03-24 22:23:26.404  3282  3339 I jxcore-log: 
,03-24 22:23:26.410  3282  3339 I jxcore-log: DEBUG createPeerListener: createPeerListener
03-24 22:23:26.410  3282  3339 I jxcore-log: 
,03-24 22:23:26.416  3282  3339 I jxcore-log: DEBUG createPeerListener: pleaseConnect= false
03-24 22:23:26.416  3282  3339 I jxcore-log: 
,03-24 22:23:26.420  3282  3339 I jxcore-log: DEBUG createPeerListener: first connection
03-24 22:23:26.420  3282  3339 I jxcore-log: 
,03-24 22:23:26.424  3282  3339 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID E0:DB:10:14:E2:C0
03-24 22:23:26.424  3282  3339 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> E0:DB:10:14:E2:C0]
,03-24 22:23:26.426  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address E0:DB:10:14:E2:C0
,03-24 22:23:26.426  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
,03-24 22:23:26.426  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
03-24 22:23:26.426  3282  3339 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null E0:DB:10:14:E2:C0
03-24 22:23:26.426  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address E0:DB:10:14:E2:C0
03-24 22:23:26.426  3282  3339 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: E0:DB:10:14:E2:C0)
03-24 22:23:26.427  3282  3844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address E0:DB:10:14:E2:C0 (thread ID: 369)
03-24 22:23:26.427  3282  3844 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-24 22:23:26.428  2156  2175 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,03-24 22:23:28.808  2156  2230 W bt-btif : No ag scb for peer addr
,03-24 22:23:28.832  2156  2230 W bt-btif : info:x10
03-24 22:23:28.832  2156  2219 D         : remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,03-24 22:23:28.833  2156  2219 E BluetoothRemoteDevices: aclStateChangeCallback: Device is NULL
,03-24 22:23:28.873  2156  2230 W bt-sdp  : process_service_search_attr_rsp
,03-24 22:23:29.023  2156  2219 D btif_config: btif_get_device_type: Device [e0:db:10:14:e2:c0] type 1
,03-24 22:23:29.030  2156  2219 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 1
,03-24 22:23:29.031  2156  2219 E bt-btif : check_cod: remote_cod = 0x5a020c
,03-24 22:23:29.034  2156  2220 I BluetoothBondStateMachine: Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 10 NewState: 11
,03-24 22:23:29.035  2156  2220 I BluetoothBondStateMachine: Entering PendingCommandState State
,03-24 22:23:29.079  2156  2219 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 0
03-24 22:23:29.080  2156  2220 D BluetoothAdapterProperties: Failed to remove device: E0:DB:10:14:E2:C0
,03-24 22:23:29.083  2156  2220 I BluetoothBondStateMachine: Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 11 NewState: 10
,03-24 22:23:29.100  2156  2220 I BluetoothBondStateMachine: StableState(): Entering Off State
,03-24 22:23:31.387  2156  2156 D BtGatt.ScanManager: awakened up at time 275174
,03-24 22:23:31.390  2156  2229 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 22:23:31.394  2156  2219 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2,
03-24 22:23:31.395  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:23:31.395  2156  2219 D BtGatt.GattService: current time is 275182583122
,03-24 22:23:31.395  2156  2219 D BtGatt.GattService: Batch record : [31, -48, -66, 45, -54, 90, 1, -128, -78, 67, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -59, 68, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
,03-24 22:23:31.397  2156  2219 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 22:23:31.397  2156  2219 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
,03-24 22:23:31.401  3282  3282 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> E0:DB:10:14:E2:C0] updated - the peer count is 2
03-24 22:23:31.401  3282  3282 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
,03-24 22:23:33.456  2156  2230 W bt-l2cap: L2CAP - no CCB for conn rsp, LCID: 70 RCID: 74
,03-24 22:23:33.794  2156  2230 W bt-btif : new conn_srvc id:26, app_id:255
03-24 22:23:33.794  2156  2230 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:255
03-24 22:23:33.794  2156  2230 W bt-btif : bta_dm_pm_ssr:2, lat:1200
03-24 22:23:33.795  3282  3843 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection accepted
03-24 22:23:33.796  3282  3843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection initialized (thread ID: 370)
03-24 22:23:33.797  3282  3843 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-24 22:23:33.797  2156  2230 W bt-btif : new conn_srvc id:26, app_id:1
03-24 22:23:33.797  2156  2230 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:255
,03-24 22:23:33.797  2156  2230 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:1
03-24 22:23:33.797  2156  2230 W bt-btif : bta_dm_pm_ssr:2, lat:1200
,03-24 22:23:33.798  3282  3844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onSocketConnected: [<no peer name> E0:DB:10:14:E2:C0] (thread ID: 369)
03-24 22:23:33.798  3282  3844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 369)
03-24 22:23:33.798   821  1415 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 22:23:33.800  3282  3844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesWritten: 15 bytes successfully written (thread ID: 371)
03-24 22:23:33.800  3282  3844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Outgoing connection initialized (*handshake* thread ID: 371)
03-24 22:23:33.800  3282  3844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 369)
03-24 22:23:33.802  3282  3846 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 370)
,03-24 22:23:33.802  3282  3843 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-24 22:23:33.806  3282  3847 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 371)
03-24 22:23:33.808  3282  3843 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-24 22:23:34.068  3282  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesRead: Read 15 bytes successfully (thread ID: 370)
,03-24 22:23:34.070  3282  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesRead: Read 15 bytes successfully (thread ID: 371)
,03-24 22:23:34.072  3282  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Got valid identity from [<no peer name> E0:DB:10:14:E2:C0]
,03-24 22:23:34.073  3282  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesWritten: 15 bytes successfully written (thread ID: 370),
03-24 22:23:34.073  3282  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: removeThreadFromList: Removing thread with ID 370
03-24 22:23:34.073  3282  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Handshake thread disposed (thread ID: 370)
,03-24 22:23:34.073  3282  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onIncomingConnectionConnected: [<no peer name> E0:DB:10:14:E2:C0]
03-24 22:23:34.074  3282  3846 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 370)
03-24 22:23:34.074  3282  3282 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> E0:DB:10:14:E2:C0]
03-24 22:23:34.075  3282  3282 I io.jxcore.node.ConnectionHelper: onConnected: Incoming connection to peer [<no peer name> E0:DB:10:14:E2:C0]
03-24 22:23:34.075  3282  3282 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> E0:DB:10:14:E2:C0] updated - the peer count is 2
,03-24 22:23:34.076  3282  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Handshake succeeded with [<no peer name> E0:DB:10:14:E2:C0]
03-24 22:23:34.076  3282  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onHandshakeSucceeded: [<no peer name> E0:DB:10:14:E2:C0] (thread ID: 369)
03-24 22:23:34.077  3282  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: handleSuccessfulClientThread: [<no peer name> E0:DB:10:14:E2:C0] (thread ID: 369)
03-24 22:23:34.077  3282  3847 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 371)
03-24 22:23:34.077  3282  3282 I io.jxcore.node.ConnectionHelper: lowerBleDiscoveryPowerAndStartResetTimer: Lowering the power settings
03-24 22:23:34.077  3282  3282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 2 -> 0
03-24 22:23:34.078  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 22:23:34.078  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 22:23:34.078  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-24 22:23:34.078  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-24 22:23:34.078  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-24 22:23:34.078  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-24 22:23:34.083  2156  2228 D BtGatt.AdvertiseManager: message : 1
03-24 22:23:34.084  2156  2228 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-24 22:23:34.088  2156  2219 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 22:23:34.089  2156  2219 D BtGatt.GattService: Client app is not null!
03-24 22:23:34.090  2156  2175 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-24 22:23:34.091  3282  3282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-24 22:23:34.091  3282  3282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-24 22:23:34.092  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 3, timeout: 0, is connectable: false
03-24 22:23:34.092  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 22:23:34.092  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 22:23:34.092  3282  3282 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 22:23:34.093  3282  3282 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 22:23:34.093  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-24 22:23:34.093  3282  3282 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-24 22:23:34.104  2156  2175 D BtGatt.GattService: registerClient() - UUID=11dc7035-f0c8-4dbe-aa73-f938c4b57e31
03-24 22:23:34.104  2156  2219 D BtGatt.GattService: onClientRegistered() - UUID=11dc7035-f0c8-4dbe-aa73-f938c4b57e31, clientIf=6
,03-24 22:23:34.105  3282  3299 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-24 22:23:34.107  2156  2228 D BtGatt.AdvertiseManager: message : 0
,03-24 22:23:34.112  2156  2228 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 22:23:34.117  2156  2219 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 22:23:34.120  2156  2219 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 22:23:34.121  3282  3282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-24 22:23:34.125  2156  2397 D BtGatt.GattService: stopScan() - queue size =1
,03-24 22:23:34.127  2156  2219 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16,
03-24 22:23:34.127  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:23:34.127  2156  2229 D BtGatt.ScanManager: stopping BLe Batch
03-24 22:23:34.127  2156  2397 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-24 22:23:34.129  2156  2219 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,03-24 22:23:34.129  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:23:34.129  3282  3282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 22:23:34.129  3282  3282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 22:23:34.130  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 22:23:34.130  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 22:23:34.130  2156  2229 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 22:23:34.130  3282  3282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 22:23:34.130  3282  3282 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 22:23:34.132  2156  2219 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-24 22:23:34.132  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:23:34.132  2156  2219 D BtGatt.GattService: current time is 277919705205
,03-24 22:23:34.132  2156  2219 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -69, 20, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0, 46, 14, 29, 126, 3, 66, 1, -128, -87, 20, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-24 22:23:34.133  2156  2219 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-24 22:23:34.134  2156  2219 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 22:23:34.135  2156  2397 D BtGatt.GattService: registerClient() - UUID=ebf1aa3a-5a49-4234-9fc3-6480b44cabd5
03-24 22:23:34.136  2156  2219 D BtGatt.GattService: onClientRegistered() - UUID=ebf1aa3a-5a49-4234-9fc3-6480b44cabd5, clientIf=5
,03-24 22:23:34.136  3282  3299 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-24 22:23:34.137  2156  2175 D BtGatt.GattService: start scan with filters,
03-24 22:23:34.137  3282  3282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 22:23:34.137  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 22:23:34.137  3282  3282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 3 -> 1
03-24 22:23:34.138  2156  2229 D BtGatt.ScanManager: handling starting scan
03-24 22:23:34.138  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 22:23:34.138  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 22:23:34.138  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-24 22:23:34.138  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-24 22:23:34.138  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-24 22:23:34.138  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-24 22:23:34.140  2156  2219 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,03-24 22:23:34.140  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:23:34.140  2156  2228 D BtGatt.AdvertiseManager: message : 1
03-24 22:23:34.141  2156  2228 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-24 22:23:34.142  2156  2219 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,03-24 22:23:34.142  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:23:34.142  2156  2229 D BtGatt.ScanManager: Starting BLE batch scan
,03-24 22:23:34.142  2156  2229 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 22:23:34.144  2156  2219 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 22:23:34.144  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 22:23:34.145  2156  2219 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 22:23:34.145  2156  2219 D BtGatt.GattService: Client app is not null!
,03-24 22:23:34.146  2156  2174 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-24 22:23:34.147  3282  3282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 22:23:34.147  3282  3282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-24 22:23:34.147  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-24 22:23:34.147  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 22:23:34.147  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 22:23:34.147  2156  2219 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 22:23:34.147  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 22:23:34.147  3282  3282 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 22:23:34.147  3282  3282 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 22:23:34.147  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-24 22:23:34.147  3282  3282 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-24 22:23:34.153  2156  2174 D BtGatt.GattService: registerClient() - UUID=36fe685a-749e-4732-a4df-94c5e4ae2cd3
03-24 22:23:34.153  2156  2219 D BtGatt.GattService: onClientRegistered() - UUID=36fe685a-749e-4732-a4df-94c5e4ae2cd3, clientIf=6
03-24 22:23:34.153  3282  3299 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-24 22:23:34.154  2156  2228 D BtGatt.AdvertiseManager: message : 0
,03-24 22:23:34.156  2156  2228 D BtGatt.AdvertiseManager: starting multi advertising,
,03-24 22:23:34.159  2156  2219 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 22:23:34.161  2156  2219 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 22:23:34.161  3282  3282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING,
,03-24 22:23:34.163  2156  2397 D BtGatt.GattService: stopScan() - queue size =1
,03-24 22:23:34.163  2156  2175 D BtGatt.GattService: unregisterClient() - clientIf=5
03-24 22:23:34.164  3282  3282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 22:23:34.164  3282  3282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 22:23:34.164  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-24 22:23:34.164  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 22:23:34.164  3282  3282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 22:23:34.164  3282  3282 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-24 22:23:34.164  2156  2219 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 22:23:34.164  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:23:34.164  2156  2229 D BtGatt.ScanManager: stopping BLe Batch
03-24 22:23:34.167  2156  2175 D BtGatt.GattService: registerClient() - UUID=f83925bc-1047-4c01-85d3-1a6fd025b54d
03-24 22:23:34.167  2156  2219 D BtGatt.GattService: onClientRegistered() - UUID=f83925bc-1047-4c01-85d3-1a6fd025b54d, clientIf=5
03-24 22:23:34.167  3282  3299 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-24 22:23:34.167  2156  2396 D BtGatt.GattService: start scan with filters
03-24 22:23:34.167  2156  2219 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0,
03-24 22:23:34.167  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:23:34.167  2156  2229 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 22:23:34.168  3282  3282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 22:23:34.168  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 22:23:34.168  3282  3282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 2 -> 0
03-24 22:23:34.168  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 22:23:34.168  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 22:23:34.168  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-24 22:23:34.168  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-24 22:23:34.168  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-24 22:23:34.168  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-24 22:23:34.168  2156  2219 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 22:23:34.168  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:23:34.172  2156  2229 D BtGatt.ScanManager: handling starting scan
,03-24 22:23:34.172  2156  2228 D BtGatt.AdvertiseManager: message : 1
03-24 22:23:34.172  2156  2228 D BtGatt.AdvertiseManager: stop advertise for client 6
03-24 22:23:34.174  2156  2219 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 22:23:34.174  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 22:23:34.175  2156  2219 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 22:23:34.175  2156  2219 D BtGatt.GattService: Client app is not null!
,03-24 22:23:34.176  2156  2175 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-24 22:23:34.176  3282  3282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 22:23:34.176  3282  3282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-24 22:23:34.176  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-24 22:23:34.176  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 22:23:34.176  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 22:23:34.176  3282  3282 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 22:23:34.177  3282  3282 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 22:23:34.177  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 22:23:34.177  3282  3282 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-24 22:23:34.177  2156  2219 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 22:23:34.177  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:23:34.177  2156  2229 D BtGatt.ScanManager: Starting BLE batch scan
03-24 22:23:34.177  2156  2229 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 22:23:34.179  2156  2219 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 22:23:34.179  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:23:34.180  2156  2219 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 22:23:34.180  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 22:23:34.180  2156  2175 D BtGatt.GattService: registerClient() - UUID=b29ba530-e7cf-497e-a93f-eb7a5da6f464
03-24 22:23:34.180  2156  2219 D BtGatt.GattService: onClientRegistered() - UUID=b29ba530-e7cf-497e-a93f-eb7a5da6f464, clientIf=6
03-24 22:23:34.181  3282  3299 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-24 22:23:34.182  2156  2228 D BtGatt.AdvertiseManager: message : 0
,03-24 22:23:34.184  2156  2228 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 22:23:34.186  2156  2219 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 22:23:34.189  2156  2219 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 22:23:34.190  3282  3282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-24 22:23:34.192  2156  2174 D BtGatt.GattService: stopScan() - queue size =1
03-24 22:23:34.193  2156  2175 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-24 22:23:34.193  3282  3282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 22:23:34.193  3282  3282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 22:23:34.193  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-24 22:23:34.193  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 22:23:34.193  3282  3282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-24 22:23:34.193  3282  3282 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-24 22:23:34.194  2156  2219 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 22:23:34.194  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:23:34.194  2156  2229 D BtGatt.ScanManager: stopping BLe Batch
,03-24 22:23:34.197  2156  2175 D BtGatt.GattService: registerClient() - UUID=25400ba6-2303-47fc-8c62-338a41d56449
03-24 22:23:34.197  2156  2219 D BtGatt.GattService: onClientRegistered() - UUID=25400ba6-2303-47fc-8c62-338a41d56449, clientIf=5
03-24 22:23:34.197  3282  3299 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 22:23:34.197  2156  2396 D BtGatt.GattService: start scan with filters
,03-24 22:23:34.198  3282  3282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 22:23:34.198  2156  2219 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 22:23:34.198  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 22:23:34.198  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:23:34.198  3282  3282 I io.jxcore.node.ConnectionHelper: onConnected: Incoming socket thread, for peer [<no peer name> E0:DB:10:14:E2:C0], created successfully
03-24 22:23:34.198  3282  3282 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 1
03-24 22:23:34.198  3282  3282 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> E0:DB:10:14:E2:C0]
03-24 22:23:34.198  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 22:23:34.198  3282  3282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-24 22:23:34.198  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-24 22:23:34.198  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 22:23:34.198  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,03-24 22:23:34.199  3282  3282 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing connection to peer [<no peer name> E0:DB:10:14:E2:C0],
03-24 22:23:34.199  3282  3282 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> E0:DB:10:14:E2:C0] updated - the peer count is 2
03-24 22:23:34.199  3282  3849 D io.jxcore.node.IncomingSocketThread: Entering thread (ID: 372)
03-24 22:23:34.199  3282  3282 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing socket thread, for peer [<no peer name> E0:DB:10:14:E2:C0], created successfully
03-24 22:23:34.199  3282  3282 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 2
03-24 22:23:34.199  2156  2229 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 22:23:34.200  2156  2219 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 22:23:34.200  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:23:34.201  3282  3850 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 373)
03-24 22:23:34.202  3282  3850 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 34879
03-24 22:23:34.202  3282  3850 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
03-24 22:23:34.202  3282  3850 I io.jxcore.node.ConnectionHelper: onListeningForIncomingConnections: Outgoing connection is using port 34879 (peer ID: E0:DB:10:14:E2:C0)
03-24 22:23:34.202  3282  3850 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "E0:DB:10:14:E2:C0" removed
03-24 22:23:34.204  3282  3849 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 37733
,03-24 22:23:34.204  3282  3849 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
03-24 22:23:34.204  3282  3849 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-24 22:23:34.204  3282  3339 I jxcore-log: DEBUG createPeerListener: forward connection
03-24 22:23:34.204  3282  3339 I jxcore-log: 
03-24 22:23:34.204  3282  3849 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-24 22:23:34.204  3282  3849 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 372)
,03-24 22:23:34.204  3282  3849 D io.jxcore.node.IncomingSocketThread: Exiting thread (ID: 372)
03-24 22:23:34.204  2156  2229 D BtGatt.ScanManager: handling starting scan
03-24 22:23:34.207  2156  2219 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 22:23:34.207  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 22:23:34.208  3282  3853 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 375, name: Receiver)
03-24 22:23:34.208  2156  2219 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 22:23:34.208  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:23:34.208  2156  2229 D BtGatt.ScanManager: Starting BLE batch scan
03-24 22:23:34.208  2156  2229 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-24 22:23:34.209  3282  3850 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 34879
03-24 22:23:34.209  3282  3850 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
03-24 22:23:34.209  3282  3850 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-24 22:23:34.210  2156  2219 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 22:23:34.210  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 22:23:34.211  2156  2219 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 22:23:34.211  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 22:23:34.212  3282  3850 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
,03-24 22:23:34.212  3282  3850 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 373)
03-24 22:23:34.212  3282  3850 D io.jxcore.node.OutgoingSocketThread: Exiting thread (ID: 373)
03-24 22:23:34.213  3282  3852 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 374, name: Sender)
03-24 22:23:34.214  3282  3339 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 22:23:34.214  3282  3339 I jxcore-log: 
03-24 22:23:34.215  3282  3855 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 377, name: Receiver)
,03-24 22:23:34.216  3282  3339 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 22:23:34.216  3282  3339 I jxcore-log: 
,03-24 22:23:34.218  3282  3854 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 376, name: Sender),
03-24 22:23:34.218  3282  3339 I jxcore-log: DEBUG createNativeListener: new mux
03-24 22:23:34.218  3282  3339 I jxcore-log: 
,03-24 22:23:34.222  3394  3856 V GoogleAuthProtoRequest: [343] a.<init>: mAccountName set to: thalitester@gmail.com
,03-24 22:23:34.235  3282  3339 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 22:23:34.235  3282  3339 I jxcore-log: 
,03-24 22:23:34.237  3282  3339 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 22:23:34.237  3282  3339 I jxcore-log: 
,03-24 22:23:34.241  3394  3857 V GoogleAuthProtoRequest: [344] a.<init>: mAccountName set to: thalitester@gmail.com
,03-24 22:23:34.273  3282  3339 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 22:23:34.273  3282  3339 I jxcore-log: 
03-24 22:23:34.273  1261  3458 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
03-24 22:23:34.273  1261  3458 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 22:23:34.273  1261  3458 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 22:23:34.273  1261  3458 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 22:23:34.277  1261  3458 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 22:23:34.281  1261  1723 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,03-24 22:23:34.281  1261  1723 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 22:23:34.281  1261  1723 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 22:23:34.282  1261  1723 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 22:23:34.285  1261  1723 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 22:23:34.288  3394  3856 W ExperimentUpdateService: [343] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,03-24 22:23:34.288  3394  3856 W ExperimentUpdateService: [343] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-24 22:23:34.288  3394  3856 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-24 22:23:34.288  3394  3856 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-24 22:23:34.288  3394  3856 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-24 22:23:34.288  3394  3856 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-24 22:23:34.288  3394  3856 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-24 22:23:34.288  3394  3856 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-24 22:23:34.288  3394  3856 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-24 22:23:34.288  3394  3856 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-24 22:23:34.288  3394  3856 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-24 22:23:34.288  3394  3856 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-24 22:23:34.296  3394  3857 W ExperimentUpdateService: [344] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,03-24 22:23:34.296  3394  3857 W ExperimentUpdateService: [344] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-24 22:23:34.296  3394  3857 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-24 22:23:34.296  3394  3857 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-24 22:23:34.296  3394  3857 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-24 22:23:34.296  3394  3857 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-24 22:23:34.296  3394  3857 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-24 22:23:34.296  3394  3857 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-24 22:23:34.296  3394  3857 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-24 22:23:34.296  3394  3857 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-24 22:23:34.296  3394  3857 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-24 22:23:34.296  3394  3857 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-24 22:23:34.459  3282  3339 I jxcore-log: ok 213 server should return 200
03-24 22:23:34.459  3282  3339 I jxcore-log: 
,03-24 22:23:34.470  3282  3339 I jxcore-log: ok 214 response body should match testData
03-24 22:23:34.470  3282  3339 I jxcore-log: 
,03-24 22:23:34.488  3282  3339 I jxcore-log: # teardown
03-24 22:23:34.488  3282  3339 I jxcore-log: 
03-24 22:23:34.489  3282  3854 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 376, thread name: Sender)
03-24 22:23:34.489  3282  3854 E io.jxcore.node.OutgoingSocketThread: The sending thread failed with error: Input stream got -1 on read
,03-24 22:23:34.489  3282  3854 W io.jxcore.node.ConnectionHelper: onDisconnected: Outgoing connection, peer [<no peer name> E0:DB:10:14:E2:C0] disconnected: Input stream got -1 on read
,03-24 22:23:34.489  3282  3854 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: E0:DB:10:14:E2:C0
03-24 22:23:34.489  3282  3854 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 373)
03-24 22:23:34.490  3282  3854 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 373)
03-24 22:23:34.491  3282  3854 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed,
03-24 22:23:34.491  3282  3854 D io.jxcore.node.OutgoingSocketThread: close: Stopping receiving thread...
03-24 22:23:34.491  3282  3854 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 377
,03-24 22:23:34.491  3282  3854 D io.jxcore.node.OutgoingSocketThread: close: Stopping sending thread...
,03-24 22:23:34.491  3282  3854 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 376
,03-24 22:23:34.491  3282  3854 D io.jxcore.node.OutgoingSocketThread: closeLocalSocketAndStreams: Closing... (thread ID: 373)
03-24 22:23:34.491  3282  3855 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 377, thread name: Receiver): bt socket closed, read return: -1
,03-24 22:23:34.491  3282  3855 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 377, name: Receiver)
,03-24 22:23:34.492  3282  3854 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 373)
,03-24 22:23:34.492  3282  3854 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,03-24 22:23:34.492  3282  3854 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 376, name: Sender)
,03-24 22:23:34.504  2156  2358 W bt-btif : invalid rfc slot id: 16,
03-24 22:23:34.505  3282  3853 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 375, thread name: Receiver): bt socket closed, read return: -1
03-24 22:23:34.505  3282  3853 E io.jxcore.node.IncomingSocketThread: The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
03-24 22:23:34.505  3282  3853 W io.jxcore.node.ConnectionHelper: onDisconnected: Incoming connection, peer [<no peer name> E0:DB:10:14:E2:C0] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
03-24 22:23:34.505  3282  3853 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 372
,03-24 22:23:34.505  3282  3853 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 372)
,03-24 22:23:34.506  3282  3853 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
03-24 22:23:34.506  3282  3853 D io.jxcore.node.IncomingSocketThread: close: Stopping receiving thread...
03-24 22:23:34.506  3282  3853 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 375
03-24 22:23:34.506  3282  3853 D io.jxcore.node.IncomingSocketThread: close: Stopping sending thread...
,03-24 22:23:34.506  3282  3853 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 374
03-24 22:23:34.506  3282  3853 D io.jxcore.node.IncomingSocketThread: closeLocalSocketAndStreams: Closing... (thread ID: 372)
03-24 22:23:34.506  3282  3852 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 374, thread name: Sender): Socket closed
03-24 22:23:34.506  3282  3852 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 374, name: Sender)
03-24 22:23:34.507  3282  3853 I io.jxcore.node.IncomingSocketThread: close: Complete (thread ID: 372)
03-24 22:23:34.507  3282  3853 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
03-24 22:23:34.508  3282  3853 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 375, name: Receiver)
,03-24 22:23:34.512  3282  3339 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 22:23:34.512  3282  3339 I jxcore-log: 
,03-24 22:23:34.514  3282  3339 I jxcore-log: INFO thaliMobileNativeWrapper: incomingConnectionToPortNumberFailed: %s
03-24 22:23:34.514  3282  3339 I jxcore-log: 
03-24 22:23:34.515  3282  3339 I jxcore-log: INFO thaliMobileNativeWrapper: got incomingConnectionToPortNumberFailed for port [object Object] but we are listening on 37733
03-24 22:23:34.515  3282  3339 I jxcore-log: 
,03-24 22:23:34.639  3282  3339 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 22:23:34.640  3282  3339 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-24 22:23:34.640  3282  3339 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-24 22:23:34.640  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-24 22:23:34.640  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,03-24 22:23:34.643  3282  3339 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-24 22:23:34.643  3282  3843 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-24 22:23:34.643  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-24 22:23:34.643  3282  3843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-24 22:23:34.643  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,03-24 22:23:34.644  3282  3843 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-24 22:23:34.644  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,03-24 22:23:34.644  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 22:23:34.646  3282  3282 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-24 22:23:34.646  3282  3282 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-24 22:23:34.647  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-24 22:23:34.647  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-24 22:23:34.651  2156  2174 D BtGatt.GattService: stopScan() - queue size =1
,03-24 22:23:34.655  2156  2175 D BtGatt.GattService: unregisterClient() - clientIf=5,
,03-24 22:23:34.656  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 22:23:34.656  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 22:23:34.656  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,03-24 22:23:34.656  2156  2219 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 22:23:34.657  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:23:34.657  2156  2229 D BtGatt.ScanManager: stopping BLe Batch
03-24 22:23:34.657  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
,03-24 22:23:34.657  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-24 22:23:34.657  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 22:23:34.658  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,03-24 22:23:34.660  2156  2228 D BtGatt.AdvertiseManager: message : 1
03-24 22:23:34.661  2156  2228 D BtGatt.AdvertiseManager: stop advertise for client 6
03-24 22:23:34.661  2156  2219 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,03-24 22:23:34.662  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 22:23:34.662  2156  2229 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 22:23:34.667  2156  2219 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,03-24 22:23:34.667  2156  2219 D BtGatt.GattService: Client app is not null!
03-24 22:23:34.668  2156  2174 D BtGatt.GattService: unregisterClient() - clientIf=6,
03-24 22:23:34.669  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 22:23:34.669  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-24 22:23:34.669  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-24 22:23:34.669  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-24 22:23:34.669  3282  3339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-24 22:23:34.669  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-24 22:23:34.669  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 22:23:34.669  3282  3339 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-24 22:23:34.670  3282  3339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-24 22:23:34.671  3282  3339 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-24 22:23:34.671  3282  3339 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 22:23:34.671  3282  3282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 22:23:34.671  2156  2219 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
03-24 22:23:34.671  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 22:23:34.671  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-24 22:23:34.671  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 22:23:34.671  2156  2219 D BtGatt.GattService: current time is 278458990517
03-24 22:23:34.671  2156  2219 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -76, 8, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-24 22:23:34.672  2156  2219 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
,03-24 22:23:34.683  3282  3282 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-24 22:23:34.683   821  1415 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 22:23:34.690  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
,03-24 22:23:34.691  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
,03-24 22:23:34.691  3282  3282 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED,
03-24 22:23:34.691  3282  3282 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-24 22:23:34.691  3282  3282 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 22:23:34.691  3282  3282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 22:23:34.695  3282  3282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-24 22:23:34.696  3282  3282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 22:23:34.696  3282  3282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-24 22:23:34.696  3282  3339 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 22:23:34.696  3282  3339 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 22:23:34.696  3282  3339 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 22:23:34.699  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-24 22:23:34.699  3282  3339 I jxcore-log: 
,03-24 22:23:34.701  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 22:23:34.701  3282  3339 I jxcore-log: 
03-24 22:23:34.703  3282  3339 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 22:23:34.703  3282  3339 I jxcore-log: 
03-24 22:23:34.720  3282  3339 I jxcore-log: # setup
03-24 22:23:34.720  3282  3339 I jxcore-log: 
,03-24 22:23:34.830  2156  2230 W bt-btif : bta_jv_rfc_port_to_cb(port_handle:0x14):jv handle:0x0 not FOUND
,03-24 22:23:34.835  2156  2216 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,03-24 22:23:36.015  2156  2230 W bt-rfcomm: rfc_find_lcid_mcb LCID reused LCID:0x47 current:0x0
,03-24 22:23:36.015  2156  2230 W bt-rfcomm: RFCOMM_DisconnectInd LCID:0x47
,03-24 22:23:37.628  3282  3339 I jxcore-log: # 58. Test BEACONS_RETRIEVED_AND_PARSED locally
03-24 22:23:37.628  3282  3339 I jxcore-log: 
,03-24 22:23:37.853  3282  3339 I jxcore-log: ok 215 peerIdentifier should be identifier
03-24 22:23:37.853  3282  3339 I jxcore-log: 
,03-24 22:23:37.853  3282  3339 I jxcore-log: ok 216 Response should be BEACONS_RETRIEVED_AND_PARSED
03-24 22:23:37.853  3282  3339 I jxcore-log: 
03-24 22:23:37.854  3282  3339 I jxcore-log: ok 217 good beacon
03-24 22:23:37.854  3282  3339 I jxcore-log: 
,03-24 22:23:37.855  3282  3339 I jxcore-log: ok 218 good preAmble
03-24 22:23:37.855  3282  3339 I jxcore-log: 
03-24 22:23:37.855  3282  3339 I jxcore-log: ok 219 public keys match!
03-24 22:23:37.855  3282  3339 I jxcore-log: 
,03-24 22:23:37.857  3282  3339 I jxcore-log: ok 220 must return null after successful call
03-24 22:23:37.857  3282  3339 I jxcore-log: 
,03-24 22:23:37.865  3282  3339 I jxcore-log: # teardown
03-24 22:23:37.865  3282  3339 I jxcore-log: 
,03-24 22:23:38.456  3282  3339 I jxcore-log: # setup
03-24 22:23:38.456  3282  3339 I jxcore-log: 
,03-24 22:23:38.653  3282  3339 I jxcore-log: # 59. Test HTTP_BAD_RESPONSE locally
03-24 22:23:38.653  3282  3339 I jxcore-log: 
,03-24 22:23:38.795  3282  3339 I jxcore-log: ok 221 Response should be HTTP_BAD_RESPONSE
03-24 22:23:38.795  3282  3339 I jxcore-log: 
,03-24 22:23:38.797  3282  3339 I jxcore-log: ok 222 must return null after successful call
03-24 22:23:38.797  3282  3339 I jxcore-log: 
,03-24 22:23:38.807  3282  3339 I jxcore-log: # teardown
03-24 22:23:38.807  3282  3339 I jxcore-log: 
,03-24 22:23:38.956  3282  3339 I jxcore-log: # setup
03-24 22:23:38.956  3282  3339 I jxcore-log: 
,03-24 22:23:39.249  3282  3339 I jxcore-log: # 60. Test NETWORK_PROBLEM locally
03-24 22:23:39.249  3282  3339 I jxcore-log: 
,03-24 22:23:39.659  2156  2230 E bt-btm  : btm_sec_disconnected - Clearing Pending flag
,03-24 22:23:39.665  2156  2156 D BluetoothMapService: onReceive
,03-24 22:23:39.696  3792  3792 I BTConnectionReceiver: onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,03-24 22:23:39.700  3792  3792 I BluetoothClassifier: Bluetooth Device Name: Note4-1
,03-24 22:23:40.583  3282  3339 I jxcore-log: ok 223 Response should be NETWORK_PROBLEM
,03-24 22:23:40.583  3282  3339 I jxcore-log: 
,03-24 22:23:40.590  3282  3339 I jxcore-log: ok 224 reject reason should be: Could not establish TCP connection
,03-24 22:23:40.590  3282  3339 I jxcore-log: 
,03-24 22:23:40.604  3282  3339 I jxcore-log: # teardown
,03-24 22:23:40.604  3282  3339 I jxcore-log: 
,03-24 22:23:40.764  3282  3339 I jxcore-log: # setup
03-24 22:23:40.764  3282  3339 I jxcore-log: 
,03-24 22:23:40.882  2156  2221 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 22:23:40.998  3282  3339 I jxcore-log: # 61. Test timeout locally
03-24 22:23:40.998  3282  3339 I jxcore-log: 
,03-24 22:23:42.223  3282  3339 I jxcore-log: ok 225 Should be NETWORK_PROBLEM caused by timeout
03-24 22:23:42.223  3282  3339 I jxcore-log: 
,03-24 22:23:42.230  3282  3339 I jxcore-log: ok 226 reject reason should be Could not establish TCP connection
03-24 22:23:42.230  3282  3339 I jxcore-log: 
,03-24 22:23:42.239  3282  3339 I jxcore-log: # teardown
03-24 22:23:42.239  3282  3339 I jxcore-log: 
,03-24 22:23:42.365  3282  3339 I jxcore-log: # setup
03-24 22:23:42.365  3282  3339 I jxcore-log: 
,03-24 22:23:42.551  3282  3339 I jxcore-log: # 62. Call the start two times
03-24 22:23:42.551  3282  3339 I jxcore-log: 
,03-24 22:23:42.749  3282  3339 I jxcore-log: ok 227 Call start once
03-24 22:23:42.749  3282  3339 I jxcore-log: 
,03-24 22:23:42.798  3282  3339 I jxcore-log: ok 228 Response should be BEACONS_RETRIEVED_AND_PARSED,
03-24 22:23:42.798  3282  3339 I jxcore-log: 
03-24 22:23:42.799  3282  3339 I jxcore-log: ok 229 must return null after successful call.
03-24 22:23:42.799  3282  3339 I jxcore-log: 
,03-24 22:23:42.808  3282  3339 I jxcore-log: # teardown,
03-24 22:23:42.808  3282  3339 I jxcore-log: 
,03-24 22:23:42.960  3282  3339 I jxcore-log: # setup,
03-24 22:23:42.960  3282  3339 I jxcore-log: 
,03-24 22:23:43.218  3282  3339 I jxcore-log: # 63. Call the kill before calling the start,
03-24 22:23:43.218  3282  3339 I jxcore-log: 
,03-24 22:23:43.412  3282  3339 I jxcore-log: ok 230 Should be Killed,
03-24 22:23:43.412  3282  3339 I jxcore-log: 
,03-24 22:23:43.417  3282  3339 I jxcore-log: ok 231 Start after killed,
03-24 22:23:43.417  3282  3339 I jxcore-log: 
,03-24 22:23:43.423  3282  3339 I jxcore-log: # teardown,
03-24 22:23:43.423  3282  3339 I jxcore-log: 
,03-24 22:23:43.554  3282  3339 I jxcore-log: # setup,
03-24 22:23:43.554  3282  3339 I jxcore-log: 
,03-24 22:23:43.729  3282  3339 I jxcore-log: # 64. Call the kill immediately after the start,
03-24 22:23:43.729  3282  3339 I jxcore-log: 
,03-24 22:23:43.986  3282  3339 I jxcore-log: ok 232 Should be KILLED
03-24 22:23:43.986  3282  3339 I jxcore-log: 
,03-24 22:23:43.988  3282  3339 I jxcore-log: ok 233 must return null after successful kill
03-24 22:23:43.988  3282  3339 I jxcore-log: 
,03-24 22:23:43.995  3282  3339 I jxcore-log: # teardown
03-24 22:23:43.995  3282  3339 I jxcore-log: 
,03-24 22:23:44.244  3282  3339 I jxcore-log: # setup
03-24 22:23:44.244  3282  3339 I jxcore-log: 
,03-24 22:23:44.476  3282  3339 I jxcore-log: # 65. Call the kill while waiting a response from the server
03-24 22:23:44.476  3282  3339 I jxcore-log: 
,03-24 22:23:46.917  3282  3339 I jxcore-log: ok 234 Should be KILLED
03-24 22:23:46.917  3282  3339 I jxcore-log: 
,03-24 22:23:46.920  3282  3339 I jxcore-log: ok 235 must return null after successful kill
03-24 22:23:46.920  3282  3339 I jxcore-log: 
,03-24 22:23:46.943  3282  3339 I jxcore-log: # teardown
03-24 22:23:46.943  3282  3339 I jxcore-log: 
,03-24 22:23:47.041  3282  3339 I jxcore-log: # setup
03-24 22:23:47.041  3282  3339 I jxcore-log: ,
,03-24 22:23:47.246  3282  3339 I jxcore-log: # 66. Test to exceed the max content size locally
03-24 22:23:47.246  3282  3339 I jxcore-log: 
,03-24 22:23:47.350  3282  3339 I jxcore-log: ok 236 HTTP_BAD_RESPONSE should be response when content size is exceeded
03-24 22:23:47.350  3282  3339 I jxcore-log: 
,03-24 22:23:47.353  3282  3339 I jxcore-log: ok 237 must return null after successful call
03-24 22:23:47.353  3282  3339 I jxcore-log: 
,03-24 22:23:47.360  3282  3339 I jxcore-log: # teardown
03-24 22:23:47.360  3282  3339 I jxcore-log: 
,03-24 22:23:47.710  3282  3339 I jxcore-log: # setup
03-24 22:23:47.710  3282  3339 I jxcore-log: 
,03-24 22:23:47.929  3282  3339 I jxcore-log: # 67. Close the server socket while the client is waiting a response from the server. Local test.
03-24 22:23:47.929  3282  3339 I jxcore-log: 
,03-24 22:23:49.500  3282  3282 I io.jxcore.node.ConnectionHelper: restoreDefaultBleDiscoverySettings: Powering the BLE discovery back up
03-24 22:23:49.500  3282  3282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 0 -> 2
03-24 22:23:49.500  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 22:23:49.500  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 22:23:49.500  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-24 22:23:49.500  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-24 22:23:49.500  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-24 22:23:49.500  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-24 22:23:49.501  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 1, timeout: 0, is connectable: false
03-24 22:23:49.501  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0,
03-24 22:23:49.501  3282  3282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 1 -> 3
03-24 22:23:49.501  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 22:23:49.501  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 22:23:49.501  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-24 22:23:49.501  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-24 22:23:49.501  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-24 22:23:49.501  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-24 22:23:49.502  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-24 22:23:49.502  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-24 22:23:49.502  3282  3282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 0 -> 2
03-24 22:23:49.502  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 22:23:49.502  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 22:23:49.502  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-24 22:23:49.502  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-24 22:23:49.502  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-24 22:23:49.502  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-24 22:23:49.503  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-24 22:23:49.503  3282  3282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-24 22:23:50.135  3282  3339 I jxcore-log: ok 238 Should be NETWORK_PROBLEM caused closing server socket
03-24 22:23:50.135  3282  3339 I jxcore-log: 
03-24 22:23:50.137  3282  3339 I jxcore-log: ok 239 Should be Could not establish TCP connection
03-24 22:23:50.137  3282  3339 I jxcore-log: 
,03-24 22:23:50.151  3282  3339 I jxcore-log: # teardown
03-24 22:23:50.151  3282  3339 I jxcore-log: 
,03-24 22:23:50.312  3282  3339 I jxcore-log: # setup
03-24 22:23:50.312  3282  3339 I jxcore-log: 
,03-24 22:23:50.572  3282  3339 I jxcore-log: # 68. Close the client socket while the client is waiting a response from the server. Local test.
,03-24 22:23:50.572  3282  3339 I jxcore-log: 
,03-24 22:23:52.734  3282  3339 I jxcore-log: ok 240 Should be NETWORK_PROBLEM caused closing client socket
03-24 22:23:52.734  3282  3339 I jxcore-log: 
,03-24 22:23:52.747  3282  3339 I jxcore-log: ok 241 Should be Could not establish TCP connection
03-24 22:23:52.747  3282  3339 I jxcore-log: 
,03-24 22:23:52.756  3282  3339 I jxcore-log: # teardown
03-24 22:23:52.756  3282  3339 I jxcore-log: 
,03-24 22:23:52.905  3282  3339 I jxcore-log: # setup
03-24 22:23:52.905  3282  3339 I jxcore-log: 
,03-24 22:23:53.073  3282  3339 I jxcore-log: # 69. #generatePreambleAndBeacons bad args
03-24 22:23:53.073  3282  3339 I jxcore-log: 
,03-24 22:23:53.215  3282  3339 I jxcore-log: ok 242 publicKeysToNotify cannot be null,
03-24 22:23:53.215  3282  3339 I jxcore-log: 
03-24 22:23:53.217  3282  3339 I jxcore-log: ok 243 ecdh for local device cannot be null,
03-24 22:23:53.217  3282  3339 I jxcore-log: 
03-24 22:23:53.219  3282  3339 I jxcore-log: ok 244 milliseconds cannot be less than 0,
03-24 22:23:53.219  3282  3339 I jxcore-log: 
03-24 22:23:53.220  3282  3339 I jxcore-log: ok 245 milliseconds cannot be 0
03-24 22:23:53.220  3282  3339 I jxcore-log: 
03-24 22:23:53.222  3282  3339 I jxcore-log: ok 246 milliseconds cannot be greater than one_day
03-24 22:23:53.222  3282  3339 I jxcore-log: 
,03-24 22:23:53.224  3282  3339 I jxcore-log: # teardown
03-24 22:23:53.224  3282  3339 I jxcore-log: 
,03-24 22:23:55.359  3282  3339 I jxcore-log: # setup
03-24 22:23:55.359  3282  3339 I jxcore-log: 
,03-24 22:23:56.285  3499  3861 V KeepSync: Connecting to GoogleApiClient
,03-24 22:23:56.390  1261  2597 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
03-24 22:23:56.390  1261  2597 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 22:23:56.390  1261  2597 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 22:23:56.391  1261  2597 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 22:23:56.394  1261  2597 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 22:23:56.408  1776  3862 E ClientConnectionOperation: Handling authorization failure
03-24 22:23:56.408  1776  3862 E ClientConnectionOperation: com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
03-24 22:23:56.408  1776  3862 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
03-24 22:23:56.408  1776  3862 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
03-24 22:23:56.408  1776  3862 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
03-24 22:23:56.408  1776  3862 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
03-24 22:23:56.408  1776  3862 E ClientConnectionOperation: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-24 22:23:56.408  1776  3862 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 22:23:56.408  1776  3862 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 22:23:56.408  1776  3862 E ClientConnectionOperation: 	at java.lang.Thread.run(Thread.java:818)
03-24 22:23:56.408  1776  3862 E ClientConnectionOperation: Caused by: com.google.android.gms.auth.ad: BadAuthentication
03-24 22:23:56.408  1776  3862 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.b(SourceFile:442)
03-24 22:23:56.408  1776  3862 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:365)
03-24 22:23:56.408  1776  3862 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:310)
03-24 22:23:56.408  1776  3862 E ClientConnectionOperation: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
03-24 22:23:56.408  1776  3862 E ClientConnectionOperation: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
03-24 22:23:56.408  1776  3862 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:30)
03-24 22:23:56.408  1776  3862 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:370)
03-24 22:23:56.408  1776  3862 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:340)
03-24 22:23:56.408  1776  3862 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:319)
03-24 22:23:56.408  1776  3862 E ClientConnectionOperation: 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
03-24 22:23:56.408  1776  3862 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
03-24 22:23:56.408  1776  3862 E ClientConnectionOperation: 	... 7 more
,03-24 22:23:56.411  3499  3861 V KeepSync: GoogleApiClient failed to connect with error code: 4
,03-24 22:23:56.416  3499  3861 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-24 22:23:56.425  3499  3861 E SQLiteLog: (284) automatic index on blob_node(is_deleted),
,03-24 22:23:56.428  3499  3861 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-24 22:23:56.476  1261  1723 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
03-24 22:23:56.476  1261  1723 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 22:23:56.476  1261  1723 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 22:23:56.476  1261  1723 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 22:23:56.480  1261  1723 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 22:23:56.513  3499  3861 E KeepSync: IOException
03-24 22:23:56.513  3499  3861 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
03-24 22:23:56.513  3499  3861 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
03-24 22:23:56.513  3499  3861 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
03-24 22:23:56.513  3499  3861 E KeepSync: 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
03-24 22:23:56.513  3499  3861 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
03-24 22:23:56.513  3499  3861 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
03-24 22:23:56.513  3499  3861 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
03-24 22:23:56.513  3499  3861 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
03-24 22:23:56.513  3499  3861 E KeepSync: 	at com.google.android.keep.util.m.a(SourceFile:207)
03-24 22:23:56.513  3499  3861 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
03-24 22:23:56.513  3499  3861 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
03-24 22:23:56.513  3499  3861 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
03-24 22:23:56.513  3499  3861 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
03-24 22:23:56.513  3499  3861 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
03-24 22:23:56.513  3499  3861 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
03-24 22:23:56.513  3499  3861 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
03-24 22:23:56.513  3499  3861 E KeepSync: 	... 10 more
,03-24 22:23:56.514  3499  3861 W KeepSync: Sync result 2,
03-24 22:23:56.518   821   854 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 299938, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-24 22:23:56.896  3282  3339 I jxcore-log: # 70. #generatePreambleAndBeacons empty keys to notify
03-24 22:23:56.896  3282  3339 I jxcore-log: 
,03-24 22:23:58.264  3282  3339 I jxcore-log: ok 247 should be equal,
03-24 22:23:58.264  3282  3339 I jxcore-log: 
03-24 22:23:58.266  3282  3339 I jxcore-log: # teardown
03-24 22:23:58.266  3282  3339 I jxcore-log: 
,03-24 22:23:58.534  3282  3339 I jxcore-log: # setup
03-24 22:23:58.534  3282  3339 I jxcore-log: 
,03-24 22:23:59.482  3282  3339 I jxcore-log: # 71. #generatePreambleAndBeacons multiple keys to notify,
03-24 22:23:59.482  3282  3339 I jxcore-log: 
,03-24 22:23:59.880  3282  3339 I jxcore-log: ok 248 should be equal
03-24 22:23:59.880  3282  3339 I jxcore-log: 
,03-24 22:23:59.881  3282  3339 I jxcore-log: ok 249 should be equal
03-24 22:23:59.881  3282  3339 I jxcore-log: 
03-24 22:23:59.881  3282  3339 I jxcore-log: ok 250 (unnamed assert)
03-24 22:23:59.881  3282  3339 I jxcore-log: 
,03-24 22:23:59.881  3282  3339 I jxcore-log: ok 251 should be equal
03-24 22:23:59.881  3282  3339 I jxcore-log: 
03-24 22:23:59.884  3282  3339 I jxcore-log: # teardown
03-24 22:23:59.884  3282  3339 I jxcore-log: 
,03-24 22:24:00.076  3282  3339 I jxcore-log: # setup
03-24 22:24:00.076  3282  3339 I jxcore-log: 
,03-24 22:24:00.466  3282  3339 I jxcore-log: # 72. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
03-24 22:24:00.466  3282  3339 I jxcore-log: 
,03-24 22:24:00.771  3282  3339 I jxcore-log: ok 252 should throw
03-24 22:24:00.771  3282  3339 I jxcore-log: 
,03-24 22:24:00.774  3282  3339 I jxcore-log: # teardown
03-24 22:24:00.774  3282  3339 I jxcore-log: 
,03-24 22:24:01.020  3282  3339 I jxcore-log: # setup
03-24 22:24:01.020  3282  3339 I jxcore-log: 
,03-24 22:24:01.445  3282  3339 I jxcore-log: # 73. #parseBeacons invalid expiration in beaconStreamWithPreAmble
,03-24 22:24:01.445  3282  3339 I jxcore-log: 
,03-24 22:24:01.685  3282  3339 I jxcore-log: ok 253 Preamble expiration must be a 64 bit integer
03-24 22:24:01.685  3282  3339 I jxcore-log: 
03-24 22:24:01.687  3282  3339 I jxcore-log: # teardown
03-24 22:24:01.687  3282  3339 I jxcore-log: 
,03-24 22:24:01.861  3282  3339 I jxcore-log: # setup
03-24 22:24:01.861  3282  3339 I jxcore-log: 
,03-24 22:24:02.128  3282  3339 I jxcore-log: # 74. #parseBeacons expiration out of range lower
03-24 22:24:02.128  3282  3339 I jxcore-log: 
,03-24 22:24:02.419  3282  3339 I jxcore-log: ok 254 Expiration out of range
03-24 22:24:02.419  3282  3339 I jxcore-log: 
03-24 22:24:02.420  3282  3339 I jxcore-log: # teardown
03-24 22:24:02.420  3282  3339 I jxcore-log: 
,03-24 22:24:03.314  3282  3339 I jxcore-log: # setup
03-24 22:24:03.314  3282  3339 I jxcore-log: 
,03-24 22:24:03.337  2156  2221 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 22:24:03.469  3282  3339 I jxcore-log: # 75. #parseBeacons expiration out of range lower
03-24 22:24:03.469  3282  3339 I jxcore-log: 
,03-24 22:24:03.728  3282  3339 I jxcore-log: ok 255 Expiration out of range
03-24 22:24:03.728  3282  3339 I jxcore-log: 
,03-24 22:24:03.731  3282  3339 I jxcore-log: # teardown
03-24 22:24:03.731  3282  3339 I jxcore-log: 
,03-24 22:24:04.169  3282  3339 I jxcore-log: # setup
03-24 22:24:04.169  3282  3339 I jxcore-log: 
,03-24 22:24:05.112  3282  3339 I jxcore-log: # 76. #parseBeacons no beacons returns null
03-24 22:24:05.112  3282  3339 I jxcore-log: 
,03-24 22:24:05.622  3282  3339 I jxcore-log: ok 256 should be equal
03-24 22:24:05.622  3282  3339 I jxcore-log: 
,03-24 22:24:05.625  3282  3339 I jxcore-log: # teardown
03-24 22:24:05.625  3282  3339 I jxcore-log: 
,03-24 22:24:07.434  3282  3339 I jxcore-log: # setup
03-24 22:24:07.434  3282  3339 I jxcore-log: 
,03-24 22:24:09.289  3282  3339 I jxcore-log: # 77. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
03-24 22:24:09.289  3282  3339 I jxcore-log: 
,03-24 22:24:10.454  3282  3339 I jxcore-log: ok 257 Malformed encrypted beacon key ID
03-24 22:24:10.454  3282  3339 I jxcore-log: 
,03-24 22:24:10.456  3282  3339 I jxcore-log: # teardown
03-24 22:24:10.456  3282  3339 I jxcore-log: 
,03-24 22:24:11.884  3282  3339 I jxcore-log: # setup
03-24 22:24:11.884  3282  3339 I jxcore-log: 
,03-24 22:24:12.092  3282  3339 I jxcore-log: # 78. #parseBeacons addressBookCallback fails decrypt
03-24 22:24:12.092  3282  3339 I jxcore-log: 
,03-24 22:24:13.285  3282  3339 I jxcore-log: ok 258 should be equal
03-24 22:24:13.285  3282  3339 I jxcore-log: 
,03-24 22:24:13.287  3282  3339 I jxcore-log: # teardown
03-24 22:24:13.287  3282  3339 I jxcore-log: 
,03-24 22:24:14.501  3282  3339 I jxcore-log: # setup
03-24 22:24:14.501  3282  3339 I jxcore-log: 
,03-24 22:24:15.815  3282  3339 I jxcore-log: # 79. #parseBeacons addressBookCallback returns no matches
03-24 22:24:15.815  3282  3339 I jxcore-log: 
,03-24 22:24:17.498  3282  3339 I jxcore-log: ok 259 should be equal
03-24 22:24:17.498  3282  3339 I jxcore-log: 
,03-24 22:24:17.498  3282  3339 I jxcore-log: ok 260 should be equal
03-24 22:24:17.498  3282  3339 I jxcore-log: 
,03-24 22:24:17.502  3282  3339 I jxcore-log: # teardown
03-24 22:24:17.502  3282  3339 I jxcore-log: 
,03-24 22:24:20.036  3282  3339 I jxcore-log: # setup
03-24 22:24:20.036  3282  3339 I jxcore-log: 
,03-24 22:24:22.309  3282  3339 I jxcore-log: # 80. #parseBeacons addressBookCallback returns spurious match
03-24 22:24:22.309  3282  3339 I jxcore-log: 
,03-24 22:24:24.152  3282  3339 I jxcore-log: ok 261 should be equal
03-24 22:24:24.152  3282  3339 I jxcore-log: 
03-24 22:24:24.152  3282  3339 I jxcore-log: ok 262 should be equal
03-24 22:24:24.152  3282  3339 I jxcore-log: 
,03-24 22:24:24.154  3282  3339 I jxcore-log: # teardown
03-24 22:24:24.154  3282  3339 I jxcore-log: 
,03-24 22:24:26.231  3520  3873 I BooksSync: Starting books sync for 61035162, extras: ade
,03-24 22:24:26.280  3520  3876 I BooksConfig: GmsCore Version = 7.8.99 (2134222-430)
,03-24 22:24:26.378  1261  1261 I art     : Explicit concurrent mark sweep GC freed 45708(2MB) AllocSpace objects, 19(2MB) LOS objects, 37% free, 27MB/43MB, paused 1.071ms total 61.764ms
,03-24 22:24:26.395  1261  3460 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-24 22:24:26.395  1261  3460 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 22:24:26.395  1261  3460 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 22:24:26.395  1261  3460 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 22:24:26.400  1261  3460 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 22:24:26.403  1261  1280 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,03-24 22:24:26.403  1261  1280 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 22:24:26.403  1261  1280 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 22:24:26.404  1261  1280 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 22:24:26.408  1261  1280 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 22:24:26.426  3113  3875 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
03-24 22:24:26.426  3113  3875 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-24 22:24:26.426  3113  3875 E HttpOperation: 	at jdm.a(PG:82)
03-24 22:24:26.426  3113  3875 E HttpOperation: 	at jcs.o(PG:406)
03-24 22:24:26.426  3113  3875 E HttpOperation: 	at jcn.a(PG:1379)
03-24 22:24:26.426  3113  3875 E HttpOperation: 	at jcs.i(PG:143)
03-24 22:24:26.426  3113  3875 E HttpOperation: 	at blb.a(PG:3937)
03-24 22:24:26.426  3113  3875 E HttpOperation: 	at czp.a(PG:18188)
03-24 22:24:26.426  3113  3875 E HttpOperation: 	at czp.a(PG:9081)
03-24 22:24:26.426  3113  3875 E HttpOperation: 	at czq.run(PG:1686)
03-24 22:24:26.426  3113  3875 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-24 22:24:26.426  3113  3875 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 22:24:26.426  3113  3875 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 22:24:26.426  3113  3875 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 22:24:26.426  3113  3875 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-24 22:24:26.426  3113  3875 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-24 22:24:26.426  3113  3875 E HttpOperation: 	at jdj.a(PG:4091)
03-24 22:24:26.426  3113  3875 E HttpOperation: 	at jdj.a(PG:1125)
03-24 22:24:26.426  3113  3875 E HttpOperation: 	at jdm.a(PG:77)
03-24 22:24:26.426  3113  3875 E HttpOperation: 	... 12 more
03-24 22:24:26.426  3113  3875 E HttpOperation: Caused by: faj: BadAuthentication
03-24 22:24:26.426  3113  3875 E HttpOperation: 	at fal.a(PG:38)
03-24 22:24:26.426  3113  3875 E HttpOperation: 	at jdj.a(PG:4089)
03-24 22:24:26.426  3113  3875 E HttpOperation: 	... 14 more
,03-24 22:24:26.462  1261  2597 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-24 22:24:26.462  1261  2597 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 22:24:26.462  1261  2597 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-24 22:24:26.463  1261  2597 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 22:24:26.465  1261  2597 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 22:24:26.467  1261  1722 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-24 22:24:26.467  1261  1722 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 22:24:26.467  1261  1722 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 22:24:26.467  1261  1722 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 22:24:26.470  1261  1722 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,03-24 22:24:26.479  3520  3876 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,03-24 22:24:26.479  3520  3873 E BooksSync: Soft error
03-24 22:24:26.479  3520  3873 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-24 22:24:26.479  3520  3873 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-24 22:24:26.479  3520  3873 E BooksSync: Sync error
03-24 22:24:26.479  3520  3873 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-24 22:24:26.479  3520  3873 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-24 22:24:26.479  3520  3873 I BooksSync: Finished books sync
,03-24 22:24:26.483  3113  3875 E HttpOperation: [getmobileexperiments] Unexpected exception
03-24 22:24:26.483  3113  3875 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-24 22:24:26.483  3113  3875 E HttpOperation: 	at jdm.a(PG:82)
03-24 22:24:26.483  3113  3875 E HttpOperation: 	at jcs.o(PG:406)
03-24 22:24:26.483  3113  3875 E HttpOperation: 	at jcn.a(PG:1379)
03-24 22:24:26.483  3113  3875 E HttpOperation: 	at jcs.i(PG:143)
03-24 22:24:26.483  3113  3875 E HttpOperation: 	at hec.a(PG:42)
03-24 22:24:26.483  3113  3875 E HttpOperation: 	at hee.a(PG:102)
03-24 22:24:26.483  3113  3875 E HttpOperation: 	at czr.a(PG:65)
03-24 22:24:26.483  3113  3875 E HttpOperation: 	at kka.a(PG:108)
03-24 22:24:26.483  3113  3875 E HttpOperation: 	at czp.a(PG:19176)
03-24 22:24:26.483  3113  3875 E HttpOperation: 	at czp.a(PG:9081)
03-24 22:24:26.483  3113  3875 E HttpOperation: 	at czq.run(PG:1686)
03-24 22:24:26.483  3113  3875 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-24 22:24:26.483  3113  3875 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 22:24:26.483  3113  3875 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 22:24:26.483  3113  3875 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 22:24:26.483  3113  3875 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-24 22:24:26.483  3113  3875 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-24 22:24:26.483  3113  3875 E HttpOperation: 	at jdj.a(PG:4091)
03-24 22:24:26.483  3113  3875 E HttpOperation: 	at jdj.a(PG:1125)
03-24 22:24:26.483  3113  3875 E HttpOperation: 	at jdm.a(PG:77)
03-24 22:24:26.483  3113  3875 E HttpOperation: 	... 15 more
03-24 22:24:26.483  3113  3875 E HttpOperation: Caused by: faj: BadAuthentication
03-24 22:24:26.483  3113  3875 E HttpOperation: 	at fal.a(PG:38)
03-24 22:24:26.483  3113  3875 E HttpOperation: 	at jdj.a(PG:4089)
03-24 22:24:26.483  3113  3875 E HttpOperation: 	... 17 more
,03-24 22:24:26.485  3113  3875 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
03-24 22:24:26.485  3113  3875 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
03-24 22:24:26.485  3113  3875 E ExperimentLoader: 	at jdm.a(PG:82)
03-24 22:24:26.485  3113  3875 E ExperimentLoader: 	at jcs.o(PG:406)
03-24 22:24:26.485  3113  3875 E ExperimentLoader: 	at jcn.a(PG:1379)
03-24 22:24:26.485  3113  3875 E ExperimentLoader: 	at jcs.i(PG:143)
03-24 22:24:26.485  3113  3875 E ExperimentLoader: 	at hec.a(PG:42)
03-24 22:24:26.485  3113  3875 E ExperimentLoader: 	at hee.a(PG:102)
03-24 22:24:26.485  3113  3875 E ExperimentLoader: 	at czr.a(PG:65)
03-24 22:24:26.485  3113  3875 E ExperimentLoader: 	at kka.a(PG:108)
03-24 22:24:26.485  3113  3875 E ExperimentLoader: 	at czp.a(PG:19176)
03-24 22:24:26.485  3113  3875 E ExperimentLoader: 	at czp.a(PG:9081)
03-24 22:24:26.485  3113  3875 E ExperimentLoader: 	at czq.run(PG:1686)
03-24 22:24:26.485  3113  3875 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-24 22:24:26.485  3113  3875 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 22:24:26.485  3113  3875 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 22:24:26.485  3113  3875 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 22:24:26.485  3113  3875 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
03-24 22:24:26.485  3113  3875 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-24 22:24:26.485  3113  3875 E ExperimentLoader: 	at jdj.a(PG:4091)
03-24 22:24:26.485  3113  3875 E ExperimentLoader: 	at jdj.a(PG:1125)
03-24 22:24:26.485  3113  3875 E ExperimentLoader: 	at jdm.a(PG:77)
03-24 22:24:26.485  3113  3875 E ExperimentLoader: 	... 15 more
03-24 22:24:26.485  3113  3875 E ExperimentLoader: Caused by: faj: BadAuthentication
03-24 22:24:26.485  3113  3875 E ExperimentLoader: 	at fal.a(PG:38)
03-24 22:24:26.485  3113  3875 E ExperimentLoader: 	at jdj.a(PG:4089)
03-24 22:24:26.485  3113  3875 E ExperimentLoader: 	... 17 more
,03-24 22:24:26.486   821   854 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 302476, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-24 22:24:26.552   821   854 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 303478, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,03-24 22:24:29.200  3282  3339 I jxcore-log: # setup
03-24 22:24:29.200  3282  3339 I jxcore-log: 
,03-24 22:24:29.468  3282  3339 I jxcore-log: # 81. #parseBeacons addressBookCallback returns public key
03-24 22:24:29.468  3282  3339 I jxcore-log: 
,03-24 22:24:31.015  3282  3339 I jxcore-log: ok 263 right number of calls to address book
03-24 22:24:31.015  3282  3339 I jxcore-log: 
,03-24 22:24:31.016  3282  3339 I jxcore-log: ok 264 good preAmble
03-24 22:24:31.016  3282  3339 I jxcore-log: 
03-24 22:24:31.016  3282  3339 I jxcore-log: ok 265 good unencryptedKeyId
03-24 22:24:31.016  3282  3339 I jxcore-log: 
03-24 22:24:31.016  3282  3339 I jxcore-log: ok 266 good beacon
03-24 22:24:31.016  3282  3339 I jxcore-log: 
03-24 22:24:31.019  3282  3339 I jxcore-log: # teardown
03-24 22:24:31.019  3282  3339 I jxcore-log: 
,03-24 22:24:33.541  3282  3339 I jxcore-log: # setup
03-24 22:24:33.541  3282  3339 I jxcore-log: 
,03-24 22:24:34.907  3282  3339 I jxcore-log: # 82. validate generatePskIdentityField
03-24 22:24:34.907  3282  3339 I jxcore-log: 
,03-24 22:24:38.165  3282  3339 I jxcore-log: ok 267 decoded buffers match
03-24 22:24:38.165  3282  3339 I jxcore-log: 
,03-24 22:24:38.168  3282  3339 I jxcore-log: # teardown
03-24 22:24:38.168  3282  3339 I jxcore-log: 
,03-24 22:24:41.044  2156  2221 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 22:24:43.890  3282  3339 I jxcore-log: # setup
03-24 22:24:43.890  3282  3339 I jxcore-log: 
,03-24 22:24:44.503  3282  3339 I jxcore-log: # 83. validate generatePskSecret
03-24 22:24:44.503  3282  3339 I jxcore-log: ,
,03-24 22:24:44.734  3282  3339 I jxcore-log: ok 268 secrets match
03-24 22:24:44.734  3282  3339 I jxcore-log: 
,03-24 22:24:44.736  3282  3339 I jxcore-log: # teardown
03-24 22:24:44.736  3282  3339 I jxcore-log: 
,03-24 22:24:44.974  3282  3339 I jxcore-log: # setup
03-24 22:24:44.974  3282  3339 I jxcore-log: 
,03-24 22:24:45.108  1261  1261 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 22:24:45.173  1261  2597 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,03-24 22:24:45.174  1261  2597 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 22:24:45.174  1261  2597 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 22:24:45.174  1261  2597 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 22:24:45.184  1261  2597 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 22:24:45.249  1261  2597 W GLSActivity: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-24 22:24:45.249  1261  2597 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-24 22:24:45.249  1261  2597 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-24 22:24:45.249  1261  2597 W GLSActivity: 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
03-24 22:24:45.249  1261  2597 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
03-24 22:24:45.249  1261  2597 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
03-24 22:24:45.249  1261  2597 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:446)
,03-24 22:24:45.254  2764  2798 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.,
03-24 22:24:45.254  2764  2798 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
03-24 22:24:45.254  2764  2798 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
03-24 22:24:45.254  2764  2798 E PlayEventLogger: 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
03-24 22:24:45.254  2764  2798 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
03-24 22:24:45.254  2764  2798 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
03-24 22:24:45.254  2764  2798 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:446)
,03-24 22:24:45.284  2764  2798 W System  : Ignoring header User-Agent because its value was null.
,03-24 22:24:45.304  3282  3339 I jxcore-log: # 84. Add two Peers.
03-24 22:24:45.304  3282  3339 I jxcore-log: 
,03-24 22:24:45.440  3282  3339 I jxcore-log: _peerAvailabilityChanged
03-24 22:24:45.440  3282  3339 I jxcore-log: 
03-24 22:24:45.440  3282  3339 I jxcore-log: peerIdentifier:id123
03-24 22:24:45.440  3282  3339 I jxcore-log: 
,03-24 22:24:45.440  3282  3339 I jxcore-log: connectionType:AndroidBluetooth
03-24 22:24:45.440  3282  3339 I jxcore-log: 
03-24 22:24:45.441  3282  3339 I jxcore-log: hostAddress:anything
03-24 22:24:45.441  3282  3339 I jxcore-log: 
,03-24 22:24:45.441  3282  3339 I jxcore-log: portNumber:8080
03-24 22:24:45.441  3282  3339 I jxcore-log: 
,03-24 22:24:45.441  3282  3339 I jxcore-log: _peerAvailabilityChanged - end
03-24 22:24:45.441  3282  3339 I jxcore-log: 
,03-24 22:24:45.448  3282  3339 I jxcore-log: ok 269 should be equal
03-24 22:24:45.448  3282  3339 I jxcore-log: 
,03-24 22:24:45.448  3282  3339 I jxcore-log: _peerAvailabilityChanged
03-24 22:24:45.448  3282  3339 I jxcore-log: 
03-24 22:24:45.448  3282  3339 I jxcore-log: peerIdentifier:id3212
03-24 22:24:45.448  3282  3339 I jxcore-log: 
03-24 22:24:45.448  3282  3339 I jxcore-log: connectionType:tcp
03-24 22:24:45.448  3282  3339 I jxcore-log: 
,03-24 22:24:45.449  3282  3339 I jxcore-log: hostAddress:anything
03-24 22:24:45.449  3282  3339 I jxcore-log: 
03-24 22:24:45.449  3282  3339 I jxcore-log: portNumber:8080
03-24 22:24:45.449  3282  3339 I jxcore-log: 
03-24 22:24:45.449  3282  3339 I jxcore-log: _peerAvailabilityChanged - end
03-24 22:24:45.449  3282  3339 I jxcore-log: 
,03-24 22:24:45.451  3282  3339 I jxcore-log: ok 270 should be equal
03-24 22:24:45.451  3282  3339 I jxcore-log: 
03-24 22:24:45.452  3282  3339 I jxcore-log: ok 271 should be equal
03-24 22:24:45.452  3282  3339 I jxcore-log: 
03-24 22:24:45.452  3282  3339 I jxcore-log: ok 272 should be equal
03-24 22:24:45.452  3282  3339 I jxcore-log: 
,03-24 22:24:45.454  3282  3339 I jxcore-log: ok 273 should be equal
03-24 22:24:45.454  3282  3339 I jxcore-log: 
03-24 22:24:45.456  3282  3339 I jxcore-log: # teardown
03-24 22:24:45.456  3282  3339 I jxcore-log: 
,03-24 22:24:45.566  3282  3339 I jxcore-log: killed
03-24 22:24:45.566  3282  3339 I jxcore-log: 
,03-24 22:24:45.574  3282  3339 I jxcore-log: # setup
03-24 22:24:45.574  3282  3339 I jxcore-log: 
,03-24 22:24:45.928  3282  3339 I jxcore-log: # 85. TCP_NATIVE peer loses DNS
03-24 22:24:45.928  3282  3339 I jxcore-log: 
,03-24 22:24:46.064  3282  3339 I jxcore-log: _peerAvailabilityChanged
03-24 22:24:46.064  3282  3339 I jxcore-log: 
03-24 22:24:46.065  3282  3339 I jxcore-log: peerIdentifier:id124
03-24 22:24:46.065  3282  3339 I jxcore-log: 
03-24 22:24:46.065  3282  3339 I jxcore-log: connectionType:tcp
03-24 22:24:46.065  3282  3339 I jxcore-log: 
03-24 22:24:46.065  3282  3339 I jxcore-log: hostAddress:127.0.0.1
03-24 22:24:46.065  3282  3339 I jxcore-log: 
,03-24 22:24:46.065  3282  3339 I jxcore-log: portNumber:60610
03-24 22:24:46.065  3282  3339 I jxcore-log: 
03-24 22:24:46.065  3282  3339 I jxcore-log: _peerAvailabilityChanged - end
03-24 22:24:46.065  3282  3339 I jxcore-log: 
,03-24 22:24:46.076  3282  3339 I jxcore-log: ok 274 should be equal
03-24 22:24:46.076  3282  3339 I jxcore-log: 
,03-24 22:24:46.077  3282  3339 I jxcore-log: _peerAvailabilityChanged
03-24 22:24:46.077  3282  3339 I jxcore-log: 
03-24 22:24:46.077  3282  3339 I jxcore-log: peerIdentifier:id124
03-24 22:24:46.077  3282  3339 I jxcore-log: 
,03-24 22:24:46.077  3282  3339 I jxcore-log: connectionType:tcp
03-24 22:24:46.077  3282  3339 I jxcore-log: 
03-24 22:24:46.077  3282  3339 I jxcore-log: hostAddress:undefined
03-24 22:24:46.077  3282  3339 I jxcore-log: 
,03-24 22:24:46.078  3282  3339 I jxcore-log: portNumber:60610
03-24 22:24:46.078  3282  3339 I jxcore-log: 
03-24 22:24:46.078  3282  3339 I jxcore-log: _peerAvailabilityChanged - end
03-24 22:24:46.078  3282  3339 I jxcore-log: 
,03-24 22:24:46.080  3282  3339 I jxcore-log: ok 275 should be equal
03-24 22:24:46.080  3282  3339 I jxcore-log: 
,03-24 22:24:46.088  3282  3339 I jxcore-log: # teardown
03-24 22:24:46.088  3282  3339 I jxcore-log: 
,03-24 22:24:46.222  3282  3339 I jxcore-log: killed
03-24 22:24:46.222  3282  3339 I jxcore-log: 
,03-24 22:24:46.231  3282  3339 I jxcore-log: # setup
03-24 22:24:46.231  3282  3339 I jxcore-log: 
,03-24 22:24:46.420  3282  3339 I jxcore-log: # 86. Resolves an action locally
03-24 22:24:46.420  3282  3339 I jxcore-log: 
,03-24 22:24:46.760  3282  3339 I jxcore-log: _peerAvailabilityChanged
03-24 22:24:46.760  3282  3339 I jxcore-log: ,
03-24 22:24:46.760  3282  3339 I jxcore-log: peerIdentifier:id124
03-24 22:24:46.760  3282  3339 I jxcore-log: 
03-24 22:24:46.760  3282  3339 I jxcore-log: connectionType:tcp
03-24 22:24:46.760  3282  3339 I jxcore-log: 
03-24 22:24:46.760  3282  3339 I jxcore-log: hostAddress:127.0.0.1
03-24 22:24:46.760  3282  3339 I jxcore-log: 
,03-24 22:24:46.760  3282  3339 I jxcore-log: portNumber:57365
03-24 22:24:46.760  3282  3339 I jxcore-log: 
03-24 22:24:46.760  3282  3339 I jxcore-log: _peerAvailabilityChanged - end
03-24 22:24:46.760  3282  3339 I jxcore-log: 
,03-24 22:24:46.819  3282  3339 I jxcore-log: ok 276 Host address must match
03-24 22:24:46.819  3282  3339 I jxcore-log: 
,03-24 22:24:46.820  3282  3339 I jxcore-log: ok 277 suggestedTCPTimeout must match
03-24 22:24:46.820  3282  3339 I jxcore-log: 
,03-24 22:24:46.820  3282  3339 I jxcore-log: ok 278 connectionType must match
03-24 22:24:46.820  3282  3339 I jxcore-log: 
03-24 22:24:46.821  3282  3339 I jxcore-log: ok 279 portNumber must match
03-24 22:24:46.821  3282  3339 I jxcore-log: 
,03-24 22:24:46.827  3282  3339 I jxcore-log: # teardown
03-24 22:24:46.827  3282  3339 I jxcore-log: 
,03-24 22:24:46.994  3282  3339 I jxcore-log: killed
03-24 22:24:46.994  3282  3339 I jxcore-log: 
,03-24 22:24:47.005  3282  3339 I jxcore-log: # setup
03-24 22:24:47.005  3282  3339 I jxcore-log: 
,03-24 22:24:47.651  3282  3339 I jxcore-log: # 87. Resolves an action locally using ThaliPeerPoolDefault
03-24 22:24:47.651  3282  3339 I jxcore-log: 
,03-24 22:24:48.604  3282  3339 I jxcore-log: _peerAvailabilityChanged
03-24 22:24:48.604  3282  3339 I jxcore-log: ,
03-24 22:24:48.605  3282  3339 I jxcore-log: peerIdentifier:id124
03-24 22:24:48.605  3282  3339 I jxcore-log: 
03-24 22:24:48.605  3282  3339 I jxcore-log: connectionType:tcp
03-24 22:24:48.605  3282  3339 I jxcore-log: ,
03-24 22:24:48.605  3282  3339 I jxcore-log: hostAddress:127.0.0.1
03-24 22:24:48.605  3282  3339 I jxcore-log: 
03-24 22:24:48.605  3282  3339 I jxcore-log: portNumber:42811
03-24 22:24:48.605  3282  3339 I jxcore-log: 
03-24 22:24:48.605  3282  3339 I jxcore-log: _peerAvailabilityChanged - end,
03-24 22:24:48.605  3282  3339 I jxcore-log: 
,03-24 22:24:48.658  3282  3339 I jxcore-log: ok 280 Host address must match
03-24 22:24:48.658  3282  3339 I jxcore-log: ,
03-24 22:24:48.659  3282  3339 I jxcore-log: ok 281 suggestedTCPTimeout must match
03-24 22:24:48.659  3282  3339 I jxcore-log: 
03-24 22:24:48.659  3282  3339 I jxcore-log: ok 282 connectionType must match
,03-24 22:24:48.659  3282  3339 I jxcore-log: 
03-24 22:24:48.659  3282  3339 I jxcore-log: ok 283 portNumber must match
03-24 22:24:48.659  3282  3339 I jxcore-log: 
,03-24 22:24:48.674  3282  3339 I jxcore-log: # teardown
03-24 22:24:48.674  3282  3339 I jxcore-log: 
,03-24 22:24:48.818  3282  3339 I jxcore-log: killed
03-24 22:24:48.818  3282  3339 I jxcore-log: 
,03-24 22:24:48.826  3282  3339 I jxcore-log: # setup
03-24 22:24:48.826  3282  3339 I jxcore-log: 
,03-24 22:24:52.312  3282  3339 I jxcore-log: # 88. Action fails because of a bad hostname.
03-24 22:24:52.312  3282  3339 I jxcore-log: 
,03-24 22:24:53.897  3282  3339 I jxcore-log: _peerAvailabilityChanged
03-24 22:24:53.897  3282  3339 I jxcore-log: 
,03-24 22:24:53.897  3282  3339 I jxcore-log: peerIdentifier:id123
03-24 22:24:53.897  3282  3339 I jxcore-log: 
03-24 22:24:53.897  3282  3339 I jxcore-log: connectionType:tcp
03-24 22:24:53.897  3282  3339 I jxcore-log: 
03-24 22:24:53.898  3282  3339 I jxcore-log: hostAddress:address-that-does-not-exists
03-24 22:24:53.898  3282  3339 I jxcore-log: 
,03-24 22:24:53.898  3282  3339 I jxcore-log: portNumber:123
03-24 22:24:53.898  3282  3339 I jxcore-log: 
03-24 22:24:53.898  3282  3339 I jxcore-log: _peerAvailabilityChanged - end
03-24 22:24:53.898  3282  3339 I jxcore-log: 
,03-24 22:24:58.907  3282  3339 I jxcore-log: ok 284 should be equal
03-24 22:24:58.907  3282  3339 I jxcore-log: 
,03-24 22:24:58.909  3282  3339 I jxcore-log: ok 285 should be equal
03-24 22:24:58.909  3282  3339 I jxcore-log: 
,03-24 22:24:58.910  3282  3339 I jxcore-log: ok 286 should be equal
03-24 22:24:58.910  3282  3339 I jxcore-log: 
,03-24 22:24:58.927  3282  3339 I jxcore-log: # teardown
,03-24 22:24:58.927  3282  3339 I jxcore-log: 
,03-24 22:24:59.682  3282  3339 I jxcore-log: killed
03-24 22:24:59.682  3282  3339 I jxcore-log: 
,03-24 22:24:59.688  3282  3339 I jxcore-log: # setup
03-24 22:24:59.688  3282  3339 I jxcore-log: 
,03-24 22:25:00.122   821  1375 D WifiService: acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@15d3847f}
,03-24 22:25:00.129   821  1010 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=1.25 rxSuccessRate=0.50 targetRoamBSSID=any RSSI=-127
,03-24 22:25:00.174  3394  3890 V GoogleAuthProtoRequest: [345] a.<init>: mAccountName set to: thalitester@gmail.com
,03-24 22:25:00.238  1261  1280 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,03-24 22:25:00.239  1261  1280 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 22:25:00.239  1261  1280 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-24 22:25:00.239  1261  1280 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 22:25:00.245  1261  1280 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 22:25:00.263  3394  3890 W ExperimentUpdateService: [345] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,03-24 22:25:00.265  3394  3890 W ExperimentUpdateService: [345] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-24 22:25:00.265  3394  3890 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-24 22:25:00.265  3394  3890 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-24 22:25:00.265  3394  3890 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-24 22:25:00.265  3394  3890 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-24 22:25:00.265  3394  3890 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-24 22:25:00.265  3394  3890 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-24 22:25:00.265  3394  3890 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-24 22:25:00.265  3394  3890 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-24 22:25:00.265  3394  3890 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-24 22:25:00.265  3394  3890 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-24 22:25:00.357   821  1393 I art     : Explicit concurrent mark sweep GC freed 32679(1516KB) AllocSpace objects, 5(268KB) LOS objects, 31% free, 34MB/50MB, paused 1.269ms total 69.396ms
,03-24 22:25:01.787   821  1375 D WifiService: releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@15d3847f}
,03-24 22:25:01.858   821  1252 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::injectLocation(GpsExtLocation):857]: error! inject position failed
,03-24 22:25:01.936   871   871 I kickstart: STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
03-24 22:25:01.937   871   871 I kickstart: STATUS: Wrote to /sys/power/wake_lock
,03-24 22:25:01.978   871   871 E kickstart: ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2
03-24 22:25:01.978   871   871 I kickstart: STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2' for writing
,03-24 22:25:02.963   871   871 I kickstart: STATUS: Received file 'm9kefs2'
03-24 22:25:02.964   871   871 I kickstart: STATUS: 950272 bytes transferred in 0.984991 seconds
03-24 22:25:02.964   871   871 I kickstart: STATUS: Successfully downloaded files from target 
,03-24 22:25:02.964   871   871 I kickstart: STATUS: Wrote to /sys/power/wake_unlock
,03-24 22:25:02.967   871   871 I kickstart: STATUS: Sahara protocol completed
,03-24 22:25:03.341  2156  2221 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 22:25:05.678  3282  3339 I jxcore-log: # 89. hostaddress is removed when the action is running. 
03-24 22:25:05.678  3282  3339 I jxcore-log: 
,03-24 22:25:10.370  3282  3339 I jxcore-log: _peerAvailabilityChanged
03-24 22:25:10.370  3282  3339 I jxcore-log: 
03-24 22:25:10.370  3282  3339 I jxcore-log: peerIdentifier:id124
03-24 22:25:10.370  3282  3339 I jxcore-log: 
03-24 22:25:10.371  3282  3339 I jxcore-log: connectionType:tcp
03-24 22:25:10.371  3282  3339 I jxcore-log: 
,03-24 22:25:10.371  3282  3339 I jxcore-log: hostAddress:127.0.0.1
03-24 22:25:10.371  3282  3339 I jxcore-log: 
03-24 22:25:10.371  3282  3339 I jxcore-log: portNumber:40186
03-24 22:25:10.371  3282  3339 I jxcore-log: 
03-24 22:25:10.371  3282  3339 I jxcore-log: _peerAvailabilityChanged - end
03-24 22:25:10.371  3282  3339 I jxcore-log: 
,03-24 22:25:12.378  3282  3339 I jxcore-log: _peerAvailabilityChanged
03-24 22:25:12.378  3282  3339 I jxcore-log: 
,03-24 22:25:12.379  3282  3339 I jxcore-log: peerIdentifier:id124
03-24 22:25:12.379  3282  3339 I jxcore-log: 
,03-24 22:25:12.379  3282  3339 I jxcore-log: connectionType:tcp
03-24 22:25:12.379  3282  3339 I jxcore-log: 
,03-24 22:25:12.380  3282  3339 I jxcore-log: hostAddress:undefined
03-24 22:25:12.380  3282  3339 I jxcore-log: 
03-24 22:25:12.380  3282  3339 I jxcore-log: portNumber:40186
03-24 22:25:12.380  3282  3339 I jxcore-log: 
03-24 22:25:12.380  3282  3339 I jxcore-log: _peerAvailabilityChanged - end
03-24 22:25:12.380  3282  3339 I jxcore-log: 
03-24 22:25:12.386  3282  3339 I jxcore-log: ok 287 should be equal
03-24 22:25:12.386  3282  3339 I jxcore-log: 
,03-24 22:25:12.407  3282  3339 I jxcore-log: # teardown
03-24 22:25:12.407  3282  3339 I jxcore-log: 
,03-24 22:25:14.780  3282  3339 I jxcore-log: killed
03-24 22:25:14.780  3282  3339 I jxcore-log: 
,03-24 22:25:14.788  3282  3339 I jxcore-log: # setup
03-24 22:25:14.788  3282  3339 I jxcore-log: 
,03-24 22:25:34.348  3394  3900 V GoogleAuthProtoRequest: [346] a.<init>: mAccountName set to: thalitester@gmail.com
,03-24 22:25:34.455  1261  1281 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,03-24 22:25:34.456  1261  1281 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 22:25:34.456  1261  1281 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 22:25:34.456  1261  1281 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 22:25:34.470  1261  1281 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 22:25:34.512  3394  3900 W ExperimentUpdateService: [346] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,03-24 22:25:34.513  3394  3900 W ExperimentUpdateService: [346] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.,
03-24 22:25:34.513  3394  3900 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-24 22:25:34.513  3394  3900 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-24 22:25:34.513  3394  3900 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-24 22:25:34.513  3394  3900 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-24 22:25:34.513  3394  3900 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-24 22:25:34.513  3394  3900 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-24 22:25:34.513  3394  3900 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-24 22:25:34.513  3394  3900 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-24 22:25:34.513  3394  3900 W ExperimentUpdateService: ,	at com.a.a.a.a.a(SourceFile:93)
03-24 22:25:34.513  3394  3900 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-24 22:25:41.203  2156  2221 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 22:25:41.831  3282  3339 I jxcore-log: # 90. Start and stop ThaliNotificationServer
03-24 22:25:41.831  3282  3339 I jxcore-log: 
,03-24 22:25:44.761  3282  3339 I jxcore-log: ok 288 ThaliMobile.StartUpdateAdvertisingAndListening should be called once
,03-24 22:25:44.761  3282  3339 I jxcore-log: 
03-24 22:25:44.762  3282  3339 I jxcore-log: ok 289 ThaliMobile.StopAdvertisingAndListeningshould be called once
03-24 22:25:44.762  3282  3339 I jxcore-log: 
03-24 22:25:44.763  3282  3339 I jxcore-log: # teardown
03-24 22:25:44.763  3282  3339 I jxcore-log: 
,03-24 22:25:46.529  3282  3339 I jxcore-log: # setup
03-24 22:25:46.529  3282  3339 I jxcore-log: 
,03-24 22:25:48.159  3282  3339 I jxcore-log: # 91. Pass an empty array to ThaliNotificationServer.start
,03-24 22:25:48.159  3282  3339 I jxcore-log: 
,03-24 22:25:54.372  3282  3339 I jxcore-log: ok 290 StartUpdateAdvertisingAndListening should not be called
03-24 22:25:54.372  3282  3339 I jxcore-log: 
,03-24 22:25:54.387  3282  3339 I jxcore-log: ok 291 ThaliMobile.StopAdvertisingAndListening should be called once
03-24 22:25:54.387  3282  3339 I jxcore-log: 
,03-24 22:25:54.426  3282  3339 I jxcore-log: ok 292 no error
03-24 22:25:54.426  3282  3339 I jxcore-log: 
,03-24 22:25:54.427  3282  3339 I jxcore-log: ok 293 should be 204
03-24 22:25:54.427  3282  3339 I jxcore-log: 
,03-24 22:25:54.433  3282  3339 I jxcore-log: # teardown
03-24 22:25:54.433  3282  3339 I jxcore-log: 
,03-24 22:26:03.342  2156  2221 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 22:26:26.125  3499  3909 V KeepSync: Connecting to GoogleApiClient
,03-24 22:26:26.252  1261  1723 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,03-24 22:26:26.252  1261  1723 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 22:26:26.252  1261  1723 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 22:26:26.253  1261  1723 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 22:26:26.262  1261  1723 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 22:26:26.297  1776  3910 E ClientConnectionOperation: Handling authorization failure
03-24 22:26:26.297  1776  3910 E ClientConnectionOperation: com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
03-24 22:26:26.297  1776  3910 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
03-24 22:26:26.297  1776  3910 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
03-24 22:26:26.297  1776  3910 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
03-24 22:26:26.297  1776  3910 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
03-24 22:26:26.297  1776  3910 E ClientConnectionOperation: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-24 22:26:26.297  1776  3910 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 22:26:26.297  1776  3910 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 22:26:26.297  1776  3910 E ClientConnectionOperation: 	at java.lang.Thread.run(Thread.java:818)
03-24 22:26:26.297  1776  3910 E ClientConnectionOperation: Caused by: com.google.android.gms.auth.ad: BadAuthentication
03-24 22:26:26.297  1776  3910 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.b(SourceFile:442)
03-24 22:26:26.297  1776  3910 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:365)
03-24 22:26:26.297  1776  3910 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:310)
03-24 22:26:26.297  1776  3910 E ClientConnectionOperation: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
03-24 22:26:26.297  1776  3910 E ClientConnectionOperation: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
03-24 22:26:26.297  1776  3910 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:30)
03-24 22:26:26.297  1776  3910 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:370)
03-24 22:26:26.297  1776  3910 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:340)
03-24 22:26:26.297  1776  3910 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:319)
03-24 22:26:26.297  1776  3910 E ClientConnectionOperation: 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
03-24 22:26:26.297  1776  3910 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
03-24 22:26:26.297  1776  3910 E ClientConnectionOperation: 	... 7 more
,03-24 22:26:26.302  3499  3909 V KeepSync: GoogleApiClient failed to connect with error code: 4
,03-24 22:26:26.307  3499  3909 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-24 22:26:26.323  3499  3909 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-24 22:26:26.325  3499  3909 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-24 22:26:26.443  1261  1869 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,03-24 22:26:26.444  1261  1869 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-24 22:26:26.444  1261  1869 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 22:26:26.444  1261  1869 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 22:26:26.458  1261  1869 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 22:26:26.542  3499  3909 E KeepSync: IOException
03-24 22:26:26.542  3499  3909 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
03-24 22:26:26.542  3499  3909 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
03-24 22:26:26.542  3499  3909 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
03-24 22:26:26.542  3499  3909 E KeepSync: 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
03-24 22:26:26.542  3499  3909 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
03-24 22:26:26.542  3499  3909 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
03-24 22:26:26.542  3499  3909 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
03-24 22:26:26.542  3499  3909 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
03-24 22:26:26.542  3499  3909 E KeepSync: 	at com.google.android.keep.util.m.a(SourceFile:207)
03-24 22:26:26.542  3499  3909 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
03-24 22:26:26.542  3499  3909 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
03-24 22:26:26.542  3499  3909 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
03-24 22:26:26.542  3499  3909 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
03-24 22:26:26.542  3499  3909 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
03-24 22:26:26.542  3499  3909 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
03-24 22:26:26.542  3499  3909 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
03-24 22:26:26.542  3499  3909 E KeepSync: 	... 10 more
03-24 22:26:26.542  3499  3909 W KeepSync: Sync result 2
,03-24 22:26:26.550   821   854 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 424786, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-24 22:26:41.361  2156  2221 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 22:26:56.208  3520  3919 I BooksSync: Starting books sync for 61035162, extras: ade
,03-24 22:26:56.256  3520  3922 I BooksConfig: GmsCore Version = 7.8.99 (2134222-430)
,03-24 22:26:56.316  1261  1722 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,03-24 22:26:56.317  1261  1722 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-24 22:26:56.318  1261  1722 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 22:26:56.318  1261  1722 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
03-24 22:26:56.319  1261  3460 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-24 22:26:56.319  1261  3460 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 22:26:56.319  1261  3460 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-24 22:26:56.319  1261  3460 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 22:26:56.326  1261  1722 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 22:26:56.330  1261  3460 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 22:26:56.358  3113  3921 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
03-24 22:26:56.358  3113  3921 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-24 22:26:56.358  3113  3921 E HttpOperation: 	at jdm.a(PG:82)
03-24 22:26:56.358  3113  3921 E HttpOperation: 	at jcs.o(PG:406)
03-24 22:26:56.358  3113  3921 E HttpOperation: 	at jcn.a(PG:1379)
03-24 22:26:56.358  3113  3921 E HttpOperation: 	at jcs.i(PG:143)
03-24 22:26:56.358  3113  3921 E HttpOperation: 	at blb.a(PG:3937)
03-24 22:26:56.358  3113  3921 E HttpOperation: 	at czp.a(PG:18188)
03-24 22:26:56.358  3113  3921 E HttpOperation: 	at czp.a(PG:9081)
03-24 22:26:56.358  3113  3921 E HttpOperation: 	at czq.run(PG:1686)
03-24 22:26:56.358  3113  3921 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-24 22:26:56.358  3113  3921 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 22:26:56.358  3113  3921 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 22:26:56.358  3113  3921 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 22:26:56.358  3113  3921 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-24 22:26:56.358  3113  3921 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-24 22:26:56.358  3113  3921 E HttpOperation: 	at jdj.a(PG:4091)
03-24 22:26:56.358  3113  3921 E HttpOperation: 	at jdj.a(PG:1125)
03-24 22:26:56.358  3113  3921 E HttpOperation: 	at jdm.a(PG:77)
03-24 22:26:56.358  3113  3921 E HttpOperation: 	... 12 more
03-24 22:26:56.358  3113  3921 E HttpOperation: Caused by: faj: BadAuthentication
03-24 22:26:56.358  3113  3921 E HttpOperation: 	at fal.a(PG:38)
03-24 22:26:56.358  3113  3921 E HttpOperation: 	at jdj.a(PG:4089)
03-24 22:26:56.358  3113  3921 E HttpOperation: 	... 14 more
,03-24 22:26:56.424  1261  1281 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-24 22:26:56.424  1261  1281 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 22:26:56.424  1261  1281 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 22:26:56.424  1261  1281 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 22:26:56.427  1261  1281 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 22:26:56.436  1261  1280 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-24 22:26:56.436  1261  1280 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 22:26:56.436  1261  1280 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 22:26:56.436  1261  1280 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 22:26:56.440  3113  3921 E HttpOperation: [getmobileexperiments] Unexpected exception
03-24 22:26:56.440  3113  3921 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-24 22:26:56.440  3113  3921 E HttpOperation: 	at jdm.a(PG:82)
03-24 22:26:56.440  3113  3921 E HttpOperation: 	at jcs.o(PG:406)
03-24 22:26:56.440  3113  3921 E HttpOperation: 	at jcn.a(PG:1379)
03-24 22:26:56.440  3113  3921 E HttpOperation: 	at jcs.i(PG:143)
03-24 22:26:56.440  3113  3921 E HttpOperation: 	at hec.a(PG:42)
03-24 22:26:56.440  3113  3921 E HttpOperation: 	at hee.a(PG:102)
03-24 22:26:56.440  3113  3921 E HttpOperation: 	at czr.a(PG:65)
03-24 22:26:56.440  3113  3921 E HttpOperation: 	at kka.a(PG:108)
03-24 22:26:56.440  3113  3921 E HttpOperation: 	at czp.a(PG:19176)
03-24 22:26:56.440  3113  3921 E HttpOperation: 	at czp.a(PG:9081)
03-24 22:26:56.440  3113  3921 E HttpOperation: 	at czq.run(PG:1686)
03-24 22:26:56.440  3113  3921 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-24 22:26:56.440  3113  3921 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 22:26:56.440  3113  3921 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 22:26:56.440  3113  3921 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 22:26:56.440  3113  3921 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-24 22:26:56.440  3113  3921 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-24 22:26:56.440  3113  3921 E HttpOperation: 	at jdj.a(PG:4091)
03-24 22:26:56.440  3113  3921 E HttpOperation: 	at jdj.a(PG:1125)
03-24 22:26:56.440  3113  3921 E HttpOperation: 	at jdm.a(PG:77)
03-24 22:26:56.440  3113  3921 E HttpOperation: 	... 15 more
03-24 22:26:56.440  3113  3921 E HttpOperation: Caused by: faj: BadAuthentication
03-24 22:26:56.440  3113  3921 E HttpOperation: 	at fal.a(PG:38)
03-24 22:26:56.440  3113  3921 E HttpOperation: 	at jdj.a(PG:4089)
03-24 22:26:56.440  3113  3921 E HttpOperation: 	... 17 more
03-24 22:26:56.441  3113  3921 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
03-24 22:26:56.441  3113  3921 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
03-24 22:26:56.441  3113  3921 E ExperimentLoader: 	at jdm.a(PG:82)
03-24 22:26:56.441  3113  3921 E ExperimentLoader: 	at jcs.o(PG:406)
03-24 22:26:56.441  3113  3921 E ExperimentLoader: 	at jcn.a(PG:1379)
03-24 22:26:56.441  3113  3921 E ExperimentLoader: 	at jcs.i(PG:143)
03-24 22:26:56.441  3113  3921 E ExperimentLoader: 	at hec.a(PG:42)
03-24 22:26:56.441  3113  3921 E ExperimentLoader: 	at hee.a(PG:102)
03-24 22:26:56.441  3113  3921 E ExperimentLoader: 	at czr.a(PG:65)
03-24 22:26:56.441  3113  3921 E ExperimentLoader: 	at kka.a(PG:108)
03-24 22:26:56.441  3113  3921 E ExperimentLoader: 	at czp.a(PG:19176)
03-24 22:26:56.441  3113  3921 E ExperimentLoader: 	at czp.a(PG:9081)
03-24 22:26:56.441  3113  3921 E ExperimentLoader: 	at czq.run(PG:1686)
03-24 22:26:56.441  3113  3921 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-24 22:26:56.441  3113  3921 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 22:26:56.441  3113  3921 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 22:26:56.441  3113  3921 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 22:26:56.441  3113  3921 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
03-24 22:26:56.441  3113  3921 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-24 22:26:56.441  3113  3921 E ExperimentLoader: 	at jdj.a(PG:4091)
03-24 22:26:56.441  3113  3921 E ExperimentLoader: 	at jdj.a(PG:1,125)
03-24 22:26:56.441  3113  3921 E ExperimentLoader: 	at jdm.a(PG:77)
03-24 22:26:56.441  3113  3921 E ExperimentLoader: 	... 15 more
03-24 22:26:56.441  3113  3921 E ExperimentLoader: Caused by: faj: BadAuthentication
03-24 22:26:56.441  3113  3921 E ExperimentLoader: 	at fal.a(PG:38)
03-24 22:26:56.441  3113  3921 E ExperimentLoader: 	at jdj.a(PG:4089)
03-24 22:26:56.441  3113  3921 E ExperimentLoader: 	... 17 more
03-24 22:26:56.442  1261  1280 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 22:26:56.457  3520  3922 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,03-24 22:26:56.458  3520  3919 E BooksSync: Soft error
03-24 22:26:56.458  3520  3919 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-24 22:26:56.458  3520  3919 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,03-24 22:26:56.458  3520  3919 E BooksSync: Sync error
03-24 22:26:56.458  3520  3919 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-24 22:26:56.458  3520  3919 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-24 22:26:56.458  3520  3919 I BooksSync: Finished books sync
,03-24 22:26:56.464   821   854 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 459121, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-24 22:26:56.534   821   854 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 461824, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,03-24 22:27:00.380  3394  3925 V GoogleAuthProtoRequest: [347] a.<init>: mAccountName set to: thalitester@gmail.com
,03-24 22:27:00.487  1261  3458 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
03-24 22:27:00.488  1261  3458 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 22:27:00.488  1261  3458 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 22:27:00.488  1261  3458 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 22:27:00.499  1261  3458 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 22:27:00.532  3394  3925 W ExperimentUpdateService: [347] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,03-24 22:27:00.534  3394  3925 W ExperimentUpdateService: [347] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-24 22:27:00.534  3394  3925 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-24 22:27:00.534  3394  3925 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-24 22:27:00.534  3394  3925 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-24 22:27:00.534  3394  3925 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-24 22:27:00.534  3394  3925 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-24 22:27:00.534  3394  3925 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-24 22:27:00.534  3394  3925 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-24 22:27:00.534  3394  3925 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-24 22:27:00.534  3394  3925 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-24 22:27:00.534  3394  3925 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-24 22:27:06.784  3282  3339 I jxcore-log: Disconnected from the test server
03-24 22:27:06.784  3282  3339 I jxcore-log: 
,03-24 22:27:41.530  2156  2221 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 22:27:50.376  3282  3339 I jxcore-log: Reconnected to the test server
03-24 22:27:50.376  3282  3339 I jxcore-log: 
,03-24 22:28:41.684  2156  2221 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 22:29:03.341  2156  2221 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 22:29:34.556  2764  2764 D Finsky  : [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,03-24 22:29:34.631  3394  3953 V GoogleAuthProtoRequest: [348] a.<init>: mAccountName set to: thalitester@gmail.com
,03-24 22:29:34.652  1261  1261 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 22:29:34.692  1261  1723 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,03-24 22:29:34.693  1261  1723 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 22:29:34.693  1261  1723 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 22:29:34.693  1261  1723 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 22:29:34.699  1261  1723 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 22:29:34.722  2764  2764 W Finsky  : [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,03-24 22:29:34.730  1261  1280 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
03-24 22:29:34.730  1261  1280 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 22:29:34.730  1261  1280 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 22:29:34.730  1261  1280 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 22:29:34.731  1261  1261 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 22:29:34.737  1261  1280 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 22:29:34.823  1261  1281 I art     : Explicit concurrent mark sweep GC freed 59528(3MB) AllocSpace objects, 9(992KB) LOS objects, 36% free, 27MB/43MB, paused 3.726ms total 75.407ms
,03-24 22:29:34.849  1261  2597 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
03-24 22:29:34.849  1261  2597 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 22:29:34.849  1261  2597 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 22:29:34.849  1261  2597 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 22:29:34.853  3394  3953 W ExperimentUpdateService: [348] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.,
03-24 22:29:34.853  1261  2597 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 22:29:34.858  3394  3953 W ExperimentUpdateService: [348] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.,
03-24 22:29:34.858  3394  3953 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-24 22:29:34.858  3394  3953 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-24 22:29:34.858  3394  3953 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-24 22:29:34.858  3394  3953 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-24 22:29:34.858  3394  3953 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-24 22:29:34.858  3394  3953 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-24 22:29:34.858  3394  3953 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-24 22:29:34.858  3394  3953 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-24 22:29:34.858  3394  3953 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-24 22:29:34.858  3394  3953 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-24 22:29:34.932   821   837 I art     : Explicit concurrent mark sweep GC freed 35547(1604KB) AllocSpace objects, 7(394KB) LOS objects, 32% free, 33MB/49MB, paused 2.464ms total 67.840ms,
,03-24 22:29:34.992  1261  1261 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 22:29:35.018  1261  1280 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
03-24 22:29:35.018  1261  1280 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 22:29:35.018  1261  1280 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 22:29:35.018  1261  1280 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 22:29:35.021  1261  1280 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 22:29:35.039  2764  2764 W Finsky  : [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,03-24 22:29:35.317  1261  1261 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 22:29:35.367  1261  3460 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,03-24 22:29:35.367  1261  3460 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-24 22:29:35.368  1261  3460 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-24 22:29:35.368  1261  3460 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 22:29:35.374  1261  3460 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 22:29:35.398  2764  2764 W Finsky  : [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,03-24 22:29:35.401  2764  2764 D Finsky  : [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,03-24 22:29:35.407  2764  2764 D Finsky  : [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,03-24 22:29:35.410  2764  2764 D Finsky  : [1] DailyHygiene.reschedule: Scheduling new run in 29 minutes (failures=2)
,03-24 22:29:35.416  1803  1818 D DeviceConnectionService: client connected with version: 7571000
,03-24 22:29:41.841  2156  2221 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 22:29:50.224  1261  1261 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 22:29:50.260  1261  1281 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
03-24 22:29:50.260  1261  1281 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-24 22:29:50.260  1261  1281 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 22:29:50.260  1261  1281 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 22:29:50.267  1261  1281 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 22:29:50.283  2764  2764 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,03-24 22:29:50.284  2764  2764 D Finsky  : [1] 5.onFinished: Installation state replication failed.
03-24 22:29:50.284  2764  2764 D Finsky  : [1] 5.onFinished: Scheduling replication attempt 1.
,03-24 22:30:03.346  2156  2221 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 22:30:10.603  1261  1261 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 22:30:10.697  1261  3460 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,03-24 22:30:10.698  1261  3460 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 22:30:10.698  1261  3460 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 22:30:10.699  1261  3460 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 22:30:10.710  1261  3460 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 22:30:10.755  2764  2764 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
03-24 22:30:10.757  2764  2764 D Finsky  : [1] 5.onFinished: Installation state replication failed.
,03-24 22:30:10.757  2764  2764 D Finsky  : [1] 5.onFinished: Scheduling replication attempt 2.
,03-24 22:30:31.030  1261  1261 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 22:30:31.089  1261  2597 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
03-24 22:30:31.089  1261  2597 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-24 22:30:31.089  1261  2597 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 22:30:31.089  1261  2597 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 22:30:31.098  1261  2597 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 22:30:31.132  2764  2764 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,03-24 22:30:31.133  2764  2764 D Finsky  : [1] 5.onFinished: Installation state replication failed.
,03-24 22:30:31.134  2764  2764 D Finsky  : [1] 5.onFinished: Scheduling replication attempt 3.
,03-24 22:30:35.631  3499  3966 V KeepSync: Connecting to GoogleApiClient
,03-24 22:30:35.746  1261  1722 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,03-24 22:30:35.747  1261  1722 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 22:30:35.747  1261  1722 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 22:30:35.747  1261  1722 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 22:30:35.759  1261  1722 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 22:30:35.793  1776  3967 E ClientConnectionOperation: Handling authorization failure
03-24 22:30:35.793  1776  3967 E ClientConnectionOperation: com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
03-24 22:30:35.793  1776  3967 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
03-24 22:30:35.793  1776  3967 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
03-24 22:30:35.793  1776  3967 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
03-24 22:30:35.793  1776  3967 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
03-24 22:30:35.793  1776  3967 E ClientConnectionOperation: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-24 22:30:35.793  1776  3967 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 22:30:35.793  1776  3967 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 22:30:35.793  1776  3967 E ClientConnectionOperation: 	at java.lang.Thread.run(Thread.java:818)
03-24 22:30:35.793  1776  3967 E ClientConnectionOperation: Caused by: com.google.android.gms.auth.ad: BadAuthentication
03-24 22:30:35.793  1776  3967 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.b(SourceFile:442)
03-24 22:30:35.793  1776  3967 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:365)
03-24 22:30:35.793  1776  3967 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:310)
03-24 22:30:35.793  1776  3967 E ClientConnectionOperation: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
03-24 22:30:35.793  1776  3967 E ClientConnectionOperation: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
03-24 22:30:35.793  1776  3967 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:30)
03-24 22:30:35.793  1776  3967 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:370)
03-24 22:30:35.793  1776  3967 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:340)
03-24 22:30:35.793  1776  3967 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:319)
03-24 22:30:35.793  1776  3967 E ClientConnectionOperation: 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
03-24 22:30:35.793  1776  3967 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
03-24 22:30:35.793  1776  3967 E ClientConnectionOperation: 	... 7 more
,03-24 22:30:35.798  3499  3966 V KeepSync: GoogleApiClient failed to connect with error code: 4
,03-24 22:30:35.807  3499  3966 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-24 22:30:35.825  3499  3966 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
03-24 22:30:35.825  3499  3966 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-24 22:30:35.881  1261  1869 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
03-24 22:30:35.882  1261  1869 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 22:30:35.882  1261  1869 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 22:30:35.882  1261  1869 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 22:30:35.888  1261  1869 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 22:30:35.957  3499  3966 E KeepSync: IOException
03-24 22:30:35.957  3499  3966 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
03-24 22:30:35.957  3499  3966 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
03-24 22:30:35.957  3499  3966 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
03-24 22:30:35.957  3499  3966 E KeepSync: 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
03-24 22:30:35.957  3499  3966 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
03-24 22:30:35.957  3499  3966 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
03-24 22:30:35.957  3499  3966 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
03-24 22:30:35.957  3499  3966 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
03-24 22:30:35.957  3499  3966 E KeepSync: 	at com.google.android.keep.util.m.a(SourceFile:207)
03-24 22:30:35.957  3499  3966 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
03-24 22:30:35.957  3499  3966 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
03-24 22:30:35.957  3499  3966 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
03-24 22:30:35.957  3499  3966 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
03-24 22:30:35.957  3499  3966 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
03-24 22:30:35.957  3499  3966 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
03-24 22:30:35.957  3499  3966 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
03-24 22:30:35.957  3499  3966 E KeepSync: 	... 10 more
03-24 22:30:35.958  3499  3966 W KeepSync: Sync result 2
,03-24 22:30:35.969   821   854 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 699297, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-24 22:30:42.002  2156  2221 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 22:31:00.646  3394  3975 V GoogleAuthProtoRequest: [349] a.<init>: mAccountName set to: thalitester@gmail.com
,03-24 22:31:00.715  1261  1869 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,03-24 22:31:00.715  1261  1869 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 22:31:00.715  1261  1869 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 22:31:00.715  1261  1869 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 22:31:00.722  1261  1869 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 22:31:00.737  3394  3975 W ExperimentUpdateService: [349] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
03-24 22:31:00.738  3394  3975 W ExperimentUpdateService: [349] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-24 22:31:00.738  3394  3975 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-24 22:31:00.738  3394  3975 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-24 22:31:00.738  3394  3975 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-24 22:31:00.738  3394  3975 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-24 22:31:00.738  3394  3975 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-24 22:31:00.738  3394  3975 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-24 22:31:00.738  3394  3975 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-24 22:31:00.738  3394  3975 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-24 22:31:00.738  3394  3975 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-24 22:31:00.738  3394  3975 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-24 22:31:00.851  1261  1261 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 22:31:00.900  1261  2597 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,03-24 22:31:00.900  1261  2597 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 22:31:00.901  1261  2597 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 22:31:00.901  1261  2597 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 22:31:00.909  1261  2597 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 22:31:00.939  2764  2764 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,03-24 22:31:00.940  2764  2764 D Finsky  : [1] 5.onFinished: Installation state replication failed.
03-24 22:31:00.940  2764  2764 D Finsky  : [1] 5.onFinished: Scheduling replication attempt 4.
,03-24 22:31:03.340  2156  2221 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 22:31:21.358  1261  1261 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 22:31:21.419  1261  1281 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,03-24 22:31:21.420  1261  1281 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 22:31:21.420  1261  1281 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-24 22:31:21.420  1261  1281 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 22:31:21.431  1261  1281 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 22:31:21.466  2764  2764 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,03-24 22:31:21.467  2764  2764 D Finsky  : [1] 5.onFinished: Installation state replication failed.
03-24 22:31:21.467  2764  2764 D Finsky  : [1] 5.onFinished: Scheduling replication attempt 5.
,03-24 22:31:35.673   821   854 I art     : Explicit concurrent mark sweep GC freed 25430(1040KB) AllocSpace objects, 3(236KB) LOS objects, 31% free, 34MB/50MB, paused 2.216ms total 61.982ms
,03-24 22:31:35.675  3520  3983 I BooksSync: Starting books sync for 61035162, extras: ade
,03-24 22:31:35.726  3520  3986 I BooksConfig: GmsCore Version = 7.8.99 (2134222-430)
,03-24 22:31:35.780  1261  3458 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-24 22:31:35.780  1261  3458 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-24 22:31:35.780  1261  3458 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 22:31:35.780  1261  3458 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 22:31:35.784  1261  3458 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 22:31:35.792  1261  1869 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,03-24 22:31:35.793  1261  1869 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-24 22:31:35.793  1261  1869 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 22:31:35.793  1261  1869 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 22:31:35.804  1261  1869 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 22:31:35.808  3113  3985 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
03-24 22:31:35.808  3113  3985 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-24 22:31:35.808  3113  3985 E HttpOperation: 	at jdm.a(PG:82)
03-24 22:31:35.808  3113  3985 E HttpOperation: 	at jcs.o(PG:406)
03-24 22:31:35.808  3113  3985 E HttpOperation: 	at jcn.a(PG:1379)
03-24 22:31:35.808  3113  3985 E HttpOperation: 	at jcs.i(PG:143)
03-24 22:31:35.808  3113  3985 E HttpOperation: 	at blb.a(PG:3937)
03-24 22:31:35.808  3113  3985 E HttpOperation: 	at czp.a(PG:18188)
03-24 22:31:35.808  3113  3985 E HttpOperation: 	at czp.a(PG:9081)
03-24 22:31:35.808  3113  3985 E HttpOperation: 	at czq.run(PG:1686)
03-24 22:31:35.808  3113  3985 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-24 22:31:35.808  3113  3985 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 22:31:35.808  3113  3985 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 22:31:35.808  3113  3985 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 22:31:35.808  3113  3985 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-24 22:31:35.808  3113  3985 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-24 22:31:35.808  3113  3985 E HttpOperation: 	at jdj.a(PG:4091)
03-24 22:31:35.808  3113  3985 E HttpOperation: 	at jdj.a(PG:1125)
03-24 22:31:35.808  3113  3985 E HttpOperation: 	at jdm.a(PG:77)
03-24 22:31:35.808  3113  3985 E HttpOperation: 	... 12 more
03-24 22:31:35.808  3113  3985 E HttpOperation: Caused by: faj: BadAuthentication
03-24 22:31:35.808  3113  3985 E HttpOperation: 	at fal.a(PG:38)
03-24 22:31:35.808  3113  3985 E HttpOperation: 	,at jdj.a(PG:4089)
03-24 22:31:35.808  3113  3985 E HttpOperation: 	... 14 more
,03-24 22:31:35.854  1261  1722 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,03-24 22:31:35.855  1261  1722 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 22:31:35.855  1261  1722 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 22:31:35.855  1261  1722 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 22:31:35.861  1261  1722 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 22:31:35.885  3113  3985 E HttpOperation: [getmobileexperiments] Unexpected exception
03-24 22:31:35.885  3113  3985 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-24 22:31:35.885  3113  3985 E HttpOperation: 	at jdm.a(PG:82)
03-24 22:31:35.885  3113  3985 E HttpOperation: 	at jcs.o(PG:406)
03-24 22:31:35.885  3113  3985 E HttpOperation: 	at jcn.a(PG:1379)
03-24 22:31:35.885  3113  3985 E HttpOperation: 	at jcs.i(PG:143)
03-24 22:31:35.885  3113  3985 E HttpOperation: 	at hec.a(PG:42)
03-24 22:31:35.885  3113  3985 E HttpOperation: 	at hee.a(PG:102)
03-24 22:31:35.885  3113  3985 E HttpOperation: 	at czr.a(PG:65)
03-24 22:31:35.885  3113  3985 E HttpOperation: 	at kka.a(PG:108)
03-24 22:31:35.885  3113  3985 E HttpOperation: 	at czp.a(PG:19176)
03-24 22:31:35.885  3113  3985 E HttpOperation: 	at czp.a(PG:9081)
03-24 22:31:35.885  3113  3985 E HttpOperation: 	at czq.run(PG:1686)
03-24 22:31:35.885  3113  3985 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-24 22:31:35.885  3113  3985 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 22:31:35.885  3113  3985 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 22:31:35.885  3113  3985 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 22:31:35.885  3113  3985 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-24 22:31:35.885  3113  3985 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-24 22:31:35.885  3113  3985 E HttpOperation: 	at jdj.a(PG:4091)
03-24 22:31:35.885  3113  3985 E HttpOperation: 	at jdj.a(PG:1125)
03-24 22:31:35.885  3113  3985 E HttpOperation: 	at jdm.a(PG:77)
03-24 22:31:35.885  3113  3985 E HttpOperation: 	... 15 more
03-24 22:31:35.885  3113  3985 E HttpOperation: Caused by: faj: BadAuthentication
03-24 22:31:35.885  3113  3985 E HttpOperation: 	at fal.a(PG:38)
03-24 22:31:35.885  3113  3985 E HttpOperation: 	at jdj.a(PG:4089)
03-24 22:31:35.885  3113  3985 E HttpOperation: 	... 17 more
03-24 22:31:35.886  3113  3985 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
03-24 22:31:35.886  3113  3985 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
03-24 22:31:35.886  3113  3985 E ExperimentLoader: 	at jdm.a(PG:82)
03-24 22:31:35.886  3113  3985 E ExperimentLoader: 	at jcs.o(PG:406)
03-24 22:31:35.886  3113  3985 E ExperimentLoader: 	at jcn.a(PG:1379)
03-24 22:31:35.886  3113  3985 E ExperimentLoader: 	at jcs.i(PG:143)
03-24 22:31:35.886  3113  3985 E ExperimentLoader: 	at hec.a(PG:42)
03-24 22:31:35.886  3113  3985 E ExperimentLoader: 	at hee.a(PG:102)
03-24 22:31:35.886  3113  3985 E ExperimentLoader: 	at czr.a(PG:65)
03-24 22:31:35.886  3113  3985 E ExperimentLoader: 	at kka.a(PG:108)
03-24 22:31:35.886  3113  3985 E ExperimentLoader: 	at czp.a(PG:19176)
03-24 22:31:35.886  3113  3985 E ExperimentLoader: 	at czp.a(PG:9081)
03-24 22:31:35.886  3113  3985 E ExperimentLoader: 	at czq.run(PG:1686)
03-24 22:31:35.886  3113  3985 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-24 22:31:35.886  3113  3985 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 22:31:35.886  3113  3985 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 22:31:35.886  3113  3985 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 22:31:35.886  3113  3985 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
03-24 22:31:35.886  3113  3985 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-24 22:31:35.886  3113  3985 E ExperimentLoader: 	at jdj.a(PG:4091)
03-24 22:31:35.886  3113  3985 E ExperimentLoader: 	at jdj.a(PG:1,125)
03-24 22:31:35.886  3113  3985 E ExperimentLoader: 	at jdm.a(PG:77)
03-24 22:31:35.886  3113  3985 E ExperimentLoader: 	... 15 more
03-24 22:31:35.886  3113  3985 E ExperimentLoader: Caused by: faj: BadAuthentication
03-24 22:31:35.886  3113  3985 E ExperimentLoader: 	at fal.a(PG:38)
03-24 22:31:35.886  3113  3985 E ExperimentLoader: 	at jdj.a(PG:4089)
03-24 22:31:35.886  3113  3985 E ExperimentLoader: 	... 17 more
,03-24 22:31:35.895  1261  1869 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-24 22:31:35.895  1261  1869 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 22:31:35.895  1261  1869 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 22:31:35.895  1261  1869 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 22:31:35.899  1261  1869 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 22:31:35.909  3520  3986 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,03-24 22:31:35.910  3520  3983 E BooksSync: Soft error
03-24 22:31:35.910  3520  3983 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-24 22:31:35.910  3520  3983 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-24 22:31:35.910  3520  3983 E BooksSync: Sync error
03-24 22:31:35.910  3520  3983 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-24 22:31:35.910  3520  3983 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-24 22:31:35.910  3520  3983 I BooksSync: Finished books sync
,03-24 22:31:35.917   821   854 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 737948, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-24 22:31:35.965   821   854 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 743289, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,03-24 22:31:41.712  1261  1261 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 22:31:41.780  1261  1723 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
03-24 22:31:41.780  1261  1723 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-24 22:31:41.780  1261  1723 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 22:31:41.781  1261  1723 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 22:31:41.792  1261  1723 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 22:31:41.828  2764  2764 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
03-24 22:31:41.829  2764  2764 D Finsky  : [1] 5.onFinished: Installation state replication failed.
,03-24 22:31:41.830  2764  2764 D Finsky  : [1] 5.onFinished: Giving up after 6 failures.
,03-24 22:31:42.161  2156  2221 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 22:32:36.203  1261  2079 I art     : Explicit concurrent mark sweep GC freed 47977(2MB) AllocSpace objects, 11(1213KB) LOS objects, 37% free, 26MB/42MB, paused 1.643ms total 44.180ms
,03-24 22:32:42.323  2156  2221 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 22:33:03.341  2156  2221 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 22:33:42.482  2156  2221 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 22:34:03.340  2156  2221 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 22:34:42.643  2156  2221 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 22:35:03.341  2156  2221 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 22:36:42.962  2156  2221 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 22:37:03.340  2156  2221 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 22:37:43.124  2156  2221 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 22:38:03.340  2156  2221 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 22:38:34.206  2156  2230 W bt-btm  : Stopping oneshot timer
,03-24 22:38:43.283  2156  2221 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 22:38:54.102  3499  4063 V KeepSync: Connecting to GoogleApiClient
,03-24 22:38:54.169  1261  3458 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
03-24 22:38:54.169  1261  3458 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 22:38:54.169  1261  3458 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 22:38:54.169  1261  3458 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 22:38:54.173  1261  3458 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 22:38:54.189  1776  4064 E ClientConnectionOperation: Handling authorization failure
03-24 22:38:54.189  1776  4064 E ClientConnectionOperation: com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
03-24 22:38:54.189  1776  4064 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
03-24 22:38:54.189  1776  4064 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
03-24 22:38:54.189  1776  4064 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
03-24 22:38:54.189  1776  4064 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
03-24 22:38:54.189  1776  4064 E ClientConnectionOperation: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-24 22:38:54.189  1776  4064 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 22:38:54.189  1776  4064 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 22:38:54.189  1776  4064 E ClientConnectionOperation: 	at java.lang.Thread.run(Thread.java:818)
03-24 22:38:54.189  1776  4064 E ClientConnectionOperation: Caused by: com.google.android.gms.auth.ad: BadAuthentication
03-24 22:38:54.189  1776  4064 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.b(SourceFile:442)
03-24 22:38:54.189  1776  4064 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:365)
03-24 22:38:54.189  1776  4064 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:310)
03-24 22:38:54.189  1776  4064 E ClientConnectionOperation: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
03-24 22:38:54.189  1776  4064 E ClientConnectionOperation: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
03-24 22:38:54.189  1776  4064 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:30)
03-24 22:38:54.189  1776  4064 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:370)
03-24 22:38:54.189  1776  4064 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:340)
03-24 22:38:54.189  1776  4064 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:319)
03-24 22:38:54.189  1776  4064 E ClientConnectionOperation: 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
03-24 22:38:54.189  1776  4064 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
03-24 22:38:54.189  1776  4064 E ClientConnectionOperation: 	... 7 more
,03-24 22:38:54.190  3499  4063 V KeepSync: GoogleApiClient failed to connect with error code: 4
,03-24 22:38:54.192  3499  4063 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-24 22:38:54.198  3499  4063 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
03-24 22:38:54.198  3499  4063 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-24 22:38:54.291  1261  3460 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
03-24 22:38:54.292  1261  3460 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 22:38:54.292  1261  3460 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 22:38:54.293  1261  3460 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 22:38:54.305  1261  3460 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 22:38:54.406  3499  4063 E KeepSync: IOException
,03-24 22:38:54.406  3499  4063 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
03-24 22:38:54.406  3499  4063 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
03-24 22:38:54.406  3499  4063 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
03-24 22:38:54.406  3499  4063 E KeepSync: 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
03-24 22:38:54.406  3499  4063 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
,03-24 22:38:54.406  3499  4063 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
03-24 22:38:54.406  3499  4063 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
03-24 22:38:54.406  3499  4063 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
03-24 22:38:54.406  3499  4063 E KeepSync: 	at com.google.android.keep.util.m.a(SourceFile:207)
03-24 22:38:54.406  3499  4063 E KeepSync: 	,at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
03-24 22:38:54.406  3499  4063 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
03-24 22:38:54.406  3499  4063 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
03-24 22:38:54.406  3499  4063 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
03-24 22:38:54.406  3499  4063 E KeepSync: 	,at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
03-24 22:38:54.406  3499  4063 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
03-24 22:38:54.406  3499  4063 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
03-24 22:38:54.406  3499  4063 E KeepSync: 	... 10 more
,03-24 22:38:54.406  3499  4063 W KeepSync: Sync result 2
,03-24 22:38:54.419   821   854 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 1197677, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-24 22:39:03.339  2156  2221 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 22:39:27.348   821   854 I UsageStatsService: User[0] Flushing usage stats to disk
,03-24 22:39:43.441  2156  2221 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 22:40:11.415  3520  4082 I BooksSync: Starting books sync for 61035162, extras: ade
,03-24 22:40:11.452  3520  4083 I BooksConfig: GmsCore Version = 7.8.99 (2134222-430)
,03-24 22:40:11.516  1261  3459 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-24 22:40:11.517  1261  3459 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 22:40:11.517  1261  3459 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 22:40:11.517  1261  3459 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 22:40:11.528  1261  3459 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 22:40:11.674  1261  1281 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-24 22:40:11.675  1261  1281 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 22:40:11.676  1261  1281 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-24 22:40:11.677  1261  1281 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 22:40:11.690  1261  1281 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 22:40:11.739  3520  4083 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,03-24 22:40:11.744  3520  4082 E BooksSync: Soft error
03-24 22:40:11.744  3520  4082 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-24 22:40:11.744  3520  4082 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,03-24 22:40:11.744  3520  4082 E BooksSync: Sync error
03-24 22:40:11.744  3520  4082 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-24 22:40:11.744  3520  4082 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-24 22:40:11.745  3520  4082 I BooksSync: Finished books sync
,03-24 22:40:11.768   821   854 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1275097, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-24 22:40:41.586  1261  3458 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-24 22:40:41.587  1261  3458 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-24 22:40:41.587  1261  3458 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 22:40:41.587  1261  3458 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 22:40:41.591  1261  3458 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 22:40:41.660   821  1416 I art     : Explicit concurrent mark sweep GC freed 47449(2MB) AllocSpace objects, 11(270KB) LOS objects, 31% free, 34MB/50MB, paused 1.578ms total 59.619ms
,03-24 22:40:41.697  3113  4090 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
03-24 22:40:41.697  3113  4090 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-24 22:40:41.697  3113  4090 E HttpOperation: 	at jdm.a(PG:82)
03-24 22:40:41.697  3113  4090 E HttpOperation: 	at jcs.o(PG:406)
03-24 22:40:41.697  3113  4090 E HttpOperation: 	at jcn.a(PG:1379)
03-24 22:40:41.697  3113  4090 E HttpOperation: 	at jcs.i(PG:143)
03-24 22:40:41.697  3113  4090 E HttpOperation: 	at blb.a(PG:3937)
03-24 22:40:41.697  3113  4090 E HttpOperation: 	at czp.a(PG:18188)
03-24 22:40:41.697  3113  4090 E HttpOperation: 	at czp.a(PG:9081)
03-24 22:40:41.697  3113  4090 E HttpOperation: 	at czq.run(PG:1686)
03-24 22:40:41.697  3113  4090 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-24 22:40:41.697  3113  4090 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 22:40:41.697  3113  4090 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 22:40:41.697  3113  4090 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 22:40:41.697  3113  4090 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-24 22:40:41.697  3113  4090 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-24 22:40:41.697  3113  4090 E HttpOperation: 	at jdj.a(PG:4091)
03-24 22:40:41.697  3113  4090 E HttpOperation: 	at jdj.a(PG:1125)
03-24 22:40:41.697  3113  4090 E HttpOperation: 	at jdm.a(PG:77)
03-24 22:40:41.697  3113  4090 E HttpOperation: 	... 12 more
03-24 22:40:41.697  3113  4090 E HttpOperation: Caused by: faj: BadAuthentication
03-24 22:40:41.697  3113  4090 E HttpOperation: 	at fal.a(PG:38)
03-24 22:40:41.697  3113  4090 E HttpOperation: 	at jdj.a(PG:4089)
03-24 22:40:41.697  3113  4090 E HttpOperation: 	... 14 more
,03-24 22:40:41.741  1261  2597 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,03-24 22:40:41.741  1261  2597 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 22:40:41.741  1261  2597 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 22:40:41.741  1261  2597 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 22:40:41.746  1261  2597 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 22:40:41.758  3113  4090 E HttpOperation: [getmobileexperiments] Unexpected exception
03-24 22:40:41.758  3113  4090 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-24 22:40:41.758  3113  4090 E HttpOperation: 	at jdm.a(PG:82)
03-24 22:40:41.758  3113  4090 E HttpOperation: 	at jcs.o(PG:406)
03-24 22:40:41.758  3113  4090 E HttpOperation: 	at jcn.a(PG:1379)
03-24 22:40:41.758  3113  4090 E HttpOperation: 	at jcs.i(PG:143)
03-24 22:40:41.758  3113  4090 E HttpOperation: 	at hec.a(PG:42)
03-24 22:40:41.758  3113  4090 E HttpOperation: 	at hee.a(PG:102)
03-24 22:40:41.758  3113  4090 E HttpOperation: 	at czr.a(PG:65)
03-24 22:40:41.758  3113  4090 E HttpOperation: 	at kka.a(PG:108)
03-24 22:40:41.758  3113  4090 E HttpOperation: 	at czp.a(PG:19176)
03-24 22:40:41.758  3113  4090 E HttpOperation: 	at czp.a(PG:9081)
03-24 22:40:41.758  3113  4090 E HttpOperation: 	at czq.run(PG:1686)
03-24 22:40:41.758  3113  4090 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-24 22:40:41.758  3113  4090 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 22:40:41.758  3113  4090 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 22:40:41.758  3113  4090 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 22:40:41.758  3113  4090 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-24 22:40:41.758  3113  4090 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-24 22:40:41.758  3113  4090 E HttpOperation: 	at jdj.a(PG:4091)
03-24 22:40:41.758  3113  4090 E HttpOperation: 	at jdj.a(PG:1125)
03-24 22:40:41.758  3113  4090 E HttpOperation: 	at jdm.a(PG:77)
03-24 22:40:41.758  3113  4090 E HttpOperation: 	... 15 more
03-24 22:40:41.758  3113  4090 E HttpOperation: Caused by: faj: BadAuthentication
03-24 22:40:41.758  3113  4090 E HttpOperation: 	at fal.a(PG:38)
03-24 22:40:41.758  3113  4090 E HttpOperation: 	at jdj.a(PG:4089)
03-24 22:40:41.758  3113  4090 E HttpOperation: 	... 17 more
03-24 22:40:41.758  3113  4090 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
03-24 22:40:41.758  3113  4090 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
03-24 22:40:41.758  3113  4090 E ExperimentLoader: 	at jdm.a(PG:82)
03-24 22:40:41.758  3113  4090 E ExperimentLoader: 	at jcs.o(PG:406)
03-24 22:40:41.758  3113  4090 E ExperimentLoader: 	at jcn.a(PG:1379)
03-24 22:40:41.758  3113  4090 E ExperimentLoader: 	at jcs.i(PG:143)
03-24 22:40:41.758  3113  4090 E ExperimentLoader: 	at hec.a(PG:42)
03-24 22:40:41.758  3113  4090 E ExperimentLoader: 	at hee.a(PG:102)
03-24 22:40:41.758  3113  4090 E ExperimentLoader: 	at czr.a(PG:65)
03-24 22:40:41.758  3113  4090 E ExperimentLoader: 	at kka.a(PG:108)
03-24 22:40:41.758  3113  4090 E ExperimentLoader: 	at czp.a(PG:19176)
03-24 22:40:41.758  3113  4090 E ExperimentLoader: 	at czp.a(PG:9081)
03-24 22:40:41.758  3113  4090 E ExperimentLoader: 	at czq.run(PG:1686)
03-24 22:40:41.758  3113  4090 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-24 22:40:41.758  3113  4090 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 22:40:41.758  3113  4090 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 22:40:41.758  3113  4090 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 22:40:41.758  3113  4090 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
03-24 22:40:41.758  3113  4090 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-24 22:40:41.758  3113  4090 E ExperimentLoader: 	at jdj.a(PG:4091)
03-24 22:40:41.758  3113  4090 E ExperimentLoader: 	at jdj.a(PG:1,125)
03-24 22:40:41.758  3113  4090 E ExperimentLoader: 	at jdm.a(PG:77)
03-24 22:40:41.758  3113  4090 E ExperimentLoader: 	... 15 more
03-24 22:40:41.758  3113  4090 E ExperimentLoader: Caused by: faj: BadAuthentication
03-24 22:40:41.758  3113  4090 E ExperimentLoader: 	at fal.a(PG:38)
03-24 22:40:41.758  3113  4090 E ExperimentLoader: 	at jdj.a(PG:4089)
03-24 22:40:41.758  3113  4090 E ExperimentLoader: 	... 17 more
,03-24 22:40:41.876   821   854 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 1285688, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,03-24 22:40:43.606  2156  2221 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 22:41:03.341  2156  2221 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 22:41:18.578  3394  4097 V GoogleAuthProtoRequest: [350] a.<init>: mAccountName set to: thalitester@gmail.com
,03-24 22:41:18.599  1261  3532 D GCM     : Message class com.google.f.a.a.i
,03-24 22:41:18.689  3394  4098 V GoogleAuthProtoRequest: [351] a.<init>: mAccountName set to: thalitester@gmail.com
,03-24 22:41:18.772  1776  4100 I EventLogService: Opted in for usage reporting
,03-24 22:41:18.772  1776  4100 I EventLogService: Aggregate from 1458853878348 (log), 1458853878348 (data)
,03-24 22:41:18.828  1261  1281 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,03-24 22:41:18.828  1261  1281 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 22:41:18.828  1261  1281 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 22:41:18.829  1261  1281 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 22:41:18.833  1261  1722 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
03-24 22:41:18.833  1261  1722 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 22:41:18.834  1261  1722 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 22:41:18.834  1261  1722 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 22:41:18.835  1261  1281 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 22:41:18.837  1261  1722 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 22:41:18.869  1776  4100 W EventLogAggregator: Unknown tag: snet_gcore
03-24 22:41:18.869  1776  4100 W EventLogAggregator: Unknown tag: snet_launch_service
,03-24 22:41:18.875  3394  4097 W ExperimentUpdateService: [350] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
03-24 22:41:18.876  3394  4097 W ExperimentUpdateService: [350] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-24 22:41:18.876  3394  4097 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-24 22:41:18.876  3394  4097 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-24 22:41:18.876  3394  4097 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-24 22:41:18.876  3394  4097 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-24 22:41:18.876  3394  4097 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-24 22:41:18.876  3394  4097 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-24 22:41:18.876  3394  4097 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-24 22:41:18.876  3394  4097 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-24 22:41:18.876  3394  4097 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-24 22:41:18.876  3394  4097 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-24 22:41:18.883  3394  4098 W ExperimentUpdateService: [351] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
03-24 22:41:18.883  3394  4098 W ExperimentUpdateService: [351] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-24 22:41:18.883  3394  4098 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-24 22:41:18.883  3394  4098 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-24 22:41:18.883  3394  4098 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-24 22:41:18.883  3394  4098 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-24 22:41:18.883  3394  4098 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-24 22:41:18.883  3394  4098 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-24 22:41:18.883  3394  4098 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-24 22:41:18.883  3394  4098 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-24 22:41:18.883  3394  4098 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-24 22:41:18.883  3394  4098 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-24 22:41:18.918  1776  4100 I ServiceDumpSys: dumping service [account]
,03-24 22:41:43.763  2156  2221 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 22:42:03.341  2156  2221 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 22:43:03.341  2156  2221 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 22:43:44.085  2156  2221 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 22:44:03.341  2156  2221 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 22:44:44.242  2156  2221 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 22:45:03.341  2156  2221 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,TIME-OUT KILL (timeout was 1400000ms)
```
