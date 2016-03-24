#### Test 63968542e6bfc69_thali08_motorola-Nexus 6 Logs


```
--------- beginning of main
,03-24 21:16:16.073  2145  2211 D HeadsetStateMachine: Disconnected process message: 10, size: 0
03-24 21:16:16.349  3244  3244 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
03-24 21:16:16.351  3244  3244 D AndroidRuntime: CheckJNI is OFF
03-24 21:16:16.466  3244  3244 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
03-24 21:16:16.471   820  1113 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
03-24 21:16:16.487   820  1113 V WindowManager: addAppToken: AppWindowToken{23636f8b token=Token{f8a415a ActivityRecord{2e0b0d05 u0 com.test.thalitest/.MainActivity t17}}} to stack=1 task=17 at 0
03-24 21:16:16.491  3244  3244 D AndroidRuntime: Shutting down VM
03-24 21:16:16.493   820   859 V WindowManager: Adding window Window{2d8fa1b2 u0 Starting com.test.thalitest} at 2 of 7 (after Window{3db36e9b u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
03-24 21:16:16.512  1515  1515 I HotwordDetector: Closing mic
03-24 21:16:16.512  1515  1793 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.u@2c4356a6
03-24 21:16:16.563   820  3100 I ActivityManager: Start proc 3258:com.test.thalitest/u0a95 for activity com.test.thalitest/.MainActivity
03-24 21:16:16.567   357  1799 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
03-24 21:16:16.569   357  1799 D audio_hw_primary: disable_snd_device: snd_device(55: voice-rec-mic)
03-24 21:16:16.576   357  1009 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
03-24 21:16:16.577  1515  1795 I HotwordRecognitionRnr: Stopping hotword detection.
03-24 21:16:16.578  1515  1796 I HotwordRecognitionRnr: Hotword detection finished
03-24 21:16:16.633   820  1332 I ActivityManager: Killing 2871:com.google.android.apps.messaging/u0a75 (adj 15): empty #17
03-24 21:16:16.701   820  1256 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1657656595
03-24 21:16:16.701   820  1256 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,03-24 21:16:16.786   870   870 I kickstart: STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
03-24 21:16:16.786   870   870 I kickstart: STATUS: Wrote to /sys/power/wake_lock
,03-24 21:16:16.810   870   870 E kickstart: ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1
03-24 21:16:16.811   870   870 I kickstart: STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1' for writing
,03-24 21:16:16.841   820  1332 I ActivityManager: Killing 2707:com.google.android.apps.fitness/u0a51 (adj 15): empty #18
,03-24 21:16:17.131  3258  3258 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,03-24 21:16:17.152  3258  3258 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 9026-9029)
03-24 21:16:17.152  3258  3258 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-24 21:16:17.163  3258  3258 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {212cabd9}
03-24 21:16:17.163  3258  3258 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-24 21:16:17.163  3258  3258 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,03-24 21:16:17.172  3258  3258 I BrowserStartupController: Initializing chromium process, singleProcess=true
03-24 21:16:17.172  3258  3258 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-24 21:16:17.173  3258  3258 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-24 21:16:17.179  3258  3282 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,03-24 21:16:17.183  3258  3258 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,03-24 21:16:17.187  3258  3258 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-24 21:16:17.187  3258  3258 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,03-24 21:16:17.187  3258  3258 I Adreno  : EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,03-24 21:16:17.243   820   858 D BluetoothManagerService: Message: 20
03-24 21:16:17.243   820   858 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ba474f3:true
,03-24 21:16:17.311  3258  3258 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-24 21:16:17.322  3258  3258 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-24 21:16:17.356  3258  3258 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,03-24 21:16:17.366  3258  3258 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-24 21:16:17.366  3258  3258 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-24 21:16:17.443  3258  3304 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,03-24 21:16:17.454  3258  3258 D Atlas   : Validating map...,
,03-24 21:16:17.474   820  1362 V WindowManager: Adding window Window{85480e3 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{2d8fa1b2 u0 Starting com.test.thalitest})
,03-24 21:16:17.478  3258  3291 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,03-24 21:16:17.540  3258  3304 I OpenGLRenderer: Initialized EGL, version 1.4
,03-24 21:16:17.573  3258  3304 D OpenGLRenderer: Enabling debug mode 0,
,03-24 21:16:17.634   820   859 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +1s112ms
,03-24 21:16:17.641  1234  1234 I Keyboard.Facilitator: onFinishInput()
,03-24 21:16:17.687  3258  3258 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3258
,03-24 21:16:17.804   870   870 I kickstart: STATUS: Received file 'm9kefs1'
03-24 21:16:17.805   870   870 I kickstart: STATUS: 950272 bytes transferred in 0.993463 seconds
03-24 21:16:17.805   870   870 I kickstart: STATUS: Successfully downloaded files from target 
03-24 21:16:17.805   870   870 I kickstart: STATUS: Wrote to /sys/power/wake_unlock
03-24 21:16:17.808   870   870 I kickstart: STATUS: Sahara protocol completed
,03-24 21:16:17.811  3258  3258 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-24 21:16:17.944  3258  3306 D jxcore_app_log: JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576405504
,03-24 21:16:17.949  3258  3306 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-24 21:16:17.949  3258  3306 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-24 21:16:17.949  3258  3306 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-24 21:16:17.949  3258  3306 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-24 21:16:17.949  3258  3306 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-24 21:16:17.949  3258  3306 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8ff2d0a added. We now have 1 listener(s)
,03-24 21:16:17.949   820   836 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 21:16:17.952  3258  3306 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
03-24 21:16:17.953  3258  3306 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 21:16:17.954  3258  3306 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
03-24 21:16:17.954  3258  3306 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,03-24 21:16:17.960  3258  3306 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-24 21:16:17.960  3258  3306 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
,03-24 21:16:17.960  3258  3306 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-24 21:16:17.960  3258  3306 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
03-24 21:16:17.960  3258  3306 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-24 21:16:17.960  3258  3306 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-24 21:16:17.960  3258  3306 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
03-24 21:16:17.960  3258  3306 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-24 21:16:17.960  3258  3306 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-24 21:16:17.960  3258  3306 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-24 21:16:17.960  3258  3306 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-24 21:16:17.960  3258  3306 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@266457f1 added. We now have 1 listener(s)
03-24 21:16:17.960  3258  3306 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-24 21:16:17.965   820  1022 D WifiService: New client listening to asynchronous messages
,03-24 21:16:17.967  3258  3306 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,03-24 21:16:17.969  3258  3306 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
03-24 21:16:17.969  3258  3306 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
03-24 21:16:17.969  3258  3306 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
03-24 21:16:17.969  3258  3306 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,03-24 21:16:17.972  3258  3306 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 21:16:17.973   820  2348 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 21:16:17.974  3258  3306 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,03-24 21:16:17.979  3258  3306 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 21:16:17.979  3258  3306 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 21:16:17.979  3258  3306 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 21:16:17.979  3258  3306 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 21:16:17.979  3258  3306 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 21:16:17.979  3258  3306 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
03-24 21:16:17.979  3258  3306 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
03-24 21:16:17.979  3258  3306 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
03-24 21:16:17.979  3258  3306 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-24 21:16:17.979  3258  3306 D io.jxcore.node.ConnectivityMonitor: start: OK
,03-24 21:16:17.980  3258  3258 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
03-24 21:16:17.981  3258  3306 I io.jxcore.node.LifeCycleMonitor: start: OK
,03-24 21:16:18.019  3258  3258 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-24 21:16:18.741  3258  3314 W jxcore-log: Initializing JXcore engine
03-24 21:16:18.741  3258  3314 W jxcore-log: JXcore engine is ready
,03-24 21:16:18.776  3314  3314 W Thread-344: type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[11553]" dev="sockfs" ino=11553 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
03-24 21:16:18.776  3314  3314 W Thread-344: type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
03-24 21:16:18.776  3314  3314 W Thread-344: type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[13060]" dev="sockfs" ino=13060 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
03-24 21:16:18.776  3314  3314 W Thread-344: type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[22541]" dev="sockfs" ino=22541 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,03-24 21:16:18.800  3258  3314 W jxcore-log: Starting JXcore engine
,03-24 21:16:18.880  3258  3314 W jxcore-log: Platform android
03-24 21:16:18.880  3258  3314 W jxcore-log: 
03-24 21:16:18.881  3258  3314 W jxcore-log: Process ARCH arm
03-24 21:16:18.881  3258  3314 W jxcore-log: 
,03-24 21:16:19.102  3258  3314 I jxcore-log: JXcore Cordova bridge is ready!
03-24 21:16:19.102  3258  3314 I jxcore-log: 
03-24 21:16:19.102  3258  3314 W jxcore-log: JXcore engine is started
,03-24 21:16:19.111  3258  3306 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-24 21:16:19.114  3258  3258 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,03-24 21:16:21.188   820   861 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,03-24 21:16:21.200   820   861 I Adreno  : EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,03-24 21:16:21.246   259  1013 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (229 us)
,03-24 21:16:21.792   820   859 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,03-24 21:16:21.792   820   820 V ActivityManager: Display changed displayId=0
,03-24 21:16:21.796   259   259 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6482000
03-24 21:16:21.797   259   259 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,03-24 21:16:22.060   259   319 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,03-24 21:16:22.062   259   259 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,03-24 21:16:22.065   820  1043 D SurfaceControl: Excessive delay in setPowerMode(): 273ms,
,03-24 21:16:22.072   820   861 I DreamManagerService: Entering dreamland.
,03-24 21:16:22.073   357  1010 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,03-24 21:16:22.073   357  1010 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,03-24 21:16:22.075   820   861 I PowerManagerService: Dozing...,
,03-24 21:16:22.076   820   856 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,03-24 21:16:22.083   820  1021 E WifiStateMachine: cancelDelayedScan -> 16
,03-24 21:16:22.085   820  1021 E native  : do suspend false
,03-24 21:16:22.115  1234  1234 I Keyboard.Facilitator: onFinishInput()
,03-24 21:16:22.125   820  1021 E WifiStateMachine: cancelDelayedScan -> 18
,03-24 21:16:22.171   820  1021 E native  : do suspend true
,03-24 21:16:22.243   357  1030 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
03-24 21:16:22.243   357  1030 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,03-24 21:16:22.288   820  1021 E WifiStateMachine: WifiStateMachine Disconnected CMD_START_SCAN source -2 17, 18 -> obsolete
,03-24 21:16:22.404  1266  1266 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 21:16:22.459  1266  1722 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,03-24 21:16:22.460  1266  1722 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 21:16:22.460  1266  1722 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 21:16:22.460  1266  1722 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 21:16:22.469  1266  1722 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 21:16:22.489  2748  2748 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
03-24 21:16:22.489  2748  2748 D Finsky  : [1] 5.onFinished: Installation state replication failed.
03-24 21:16:22.489  2748  2748 D Finsky  : [1] 5.onFinished: Scheduling replication attempt 5.
,03-24 21:16:22.846   820  1021 E WifiStateMachine: WifiStateMachine Disconnected CMD_START_SCAN source -2 15, 18 -> obsolete
,03-24 21:16:24.644  1176  1176 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700',
,03-24 21:16:25.071  1176  1176 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,03-24 21:16:25.107  1176  1176 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,03-24 21:16:25.108  1176  1176 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,03-24 21:16:25.133   820  1021 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
03-24 21:16:25.134   820  1021 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,03-24 21:16:25.135   820  1023 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,03-24 21:16:25.141   820  1021 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,03-24 21:16:25.148   353   813 D CommandListener: Setting iface cfg
,03-24 21:16:25.154   820  1021 E WifiStateMachine: Start Dhcp Watchdog 1
,03-24 21:16:25.158   820  1021 E WifiStateMachine:  WifiLinkLayerStats: 
03-24 21:16:25.158   820  1021 E WifiStateMachine:  my bss beacon rx: 0
03-24 21:16:25.158   820  1021 E WifiStateMachine:  RSSI mgmt: -43
03-24 21:16:25.158   820  1021 E WifiStateMachine:  BE :  rx=0 tx=3 lost=0 retries=1
03-24 21:16:25.158   820  1021 E WifiStateMachine:  BK :  rx=0 tx=0 lost=0 retries=0
03-24 21:16:25.158   820  1021 E WifiStateMachine:  VI :  rx=0 tx=0 lost=0 retries=0
03-24 21:16:25.158   820  1021 E WifiStateMachine:  VO :  rx=2 tx=0 lost=0 retries=0
03-24 21:16:25.158   820  1021 E WifiStateMachine:  on_time : 0 tx_time=61 rx_time=87 scan_time=0
,03-24 21:16:25.255   820  1021 E native  : do suspend false
,03-24 21:16:25.270   820  1021 E WifiStateMachine: scanCount==0 - aborting
,03-24 21:16:25.509  3324  3324 I dhcpcd  : version 5.5.6 starting
,03-24 21:16:25.600  3324  3324 I dhcpcd  : wlan0: rebinding lease of 192.168.1.125
,03-24 21:16:25.704  3324  3324 I dhcpcd  : wlan0: acknowledged 192.168.1.125 from 192.168.1.1,
,03-24 21:16:25.832  3324  3324 I dhcpcd  : wlan0: leased 192.168.1.125 for 172800 seconds
,03-24 21:16:26.292   820  1021 E native  : do suspend true
,03-24 21:16:26.335   820  1023 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,03-24 21:16:26.339   820  1023 D ConnectivityService: Adding iface wlan0 to network 100
,03-24 21:16:26.347   820  1021 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,03-24 21:16:26.365   820  1023 E ConnectivityService: Unexpected mtu value: 0, wlan0
,03-24 21:16:26.366   820  1023 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 100
,03-24 21:16:26.369   820  1023 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,03-24 21:16:26.372   820  1023 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,03-24 21:16:26.373   820  1023 D ConnectivityService: Setting Dns servers for network 100 to [/192.168.1.1]
,03-24 21:16:26.381   820  1023 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,03-24 21:16:26.385   820  1023 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
03-24 21:16:26.385   820  3322 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
03-24 21:16:26.385   820  3322 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Connected
03-24 21:16:26.385   820  3322 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
03-24 21:16:26.386   820  3322 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
03-24 21:16:26.386   820  1023 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
03-24 21:16:26.386   820  1023 D ConnectivityService:    accepting network in place of null
03-24 21:16:26.388   820  1023 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.125/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
,03-24 21:16:26.389   820  1023 D ConnectivityService: Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
,03-24 21:16:26.393   820  1023 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,03-24 21:16:26.393  1064  1545 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
03-24 21:16:26.394   820  1023 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
03-24 21:16:26.394   820  1023 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
03-24 21:16:26.394   820  1023 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
03-24 21:16:26.401   820   858 D Tethering: MasterInitialState.processMessage what=3
,03-24 21:16:26.410   820  1460 V BackupManagerService: Scheduling immediate backup pass
,03-24 21:16:26.414   820   820 V BackupManagerService: Running a backup pass
,03-24 21:16:26.415   820  1042 V BackupManagerService: clearing pending backups
03-24 21:16:26.417  1515  1515 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,03-24 21:16:26.421  2926  2926 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,03-24 21:16:26.427  1348  1546 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
03-24 21:16:26.427  1348  1546 E PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,03-24 21:16:26.428   820   853 D TelephonyManager: getDataEnabled: retVal=false
,03-24 21:16:26.430  3258  3258 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
03-24 21:16:26.430  3258  3258 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 21:16:26.430  3258  3258 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 21:16:26.430  3258  3258 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 21:16:26.430  3258  3258 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 21:16:26.430  3258  3258 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 21:16:26.430  3258  3258 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 21:16:26.430  3258  3258 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-24 21:16:26.430  3258  3258 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-24 21:16:26.432  2926  2926 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,03-24 21:16:26.440   820  1042 V PerformBackupTask: Beginning backup of 14 targets
,03-24 21:16:26.441   820   853 E GpsLocationProvider: No APN found to select.
,03-24 21:16:26.450   820  1042 D PerformBackupTask: invokeAgentForBackup on @pm@
,03-24 21:16:26.454   820  1042 V BackupServiceBinder: doBackup() invoked
,03-24 21:16:26.456   820  1042 I PMBA    : Previous metadata 1570415 mismatch vs 1860966 - rewriting
,03-24 21:16:26.475   820  1333 I ActivityManager: Start proc 3364:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.steen.receiver.ConnectivityChangeReceiver
03-24 21:16:26.475   820  1042 I BackupRestoreController: Getting widget state for user: 0
,03-24 21:16:26.482  1801  1801 I ConfigFetchService: onStartCommand Intent { act=com.google.android.gms.gcm.ACTION_TASK_READY cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,03-24 21:16:26.487  1801  3377 I ConfigFetchService: running network task: configservice_periodic
,03-24 21:16:26.489  1801  3377 E WakeLock: callingPackage is not supposed to be empty for wakelock Config Service fetch!
,03-24 21:16:26.493  1266  1266 I ConfigService: onCreate
,03-24 21:16:26.495  1801  3377 I ConfigFetchService: launchTask
,03-24 21:16:26.508  1801  1801 I ConfigFetchService: service connected
,03-24 21:16:26.511  1801  1801 D ConfigFetchService: ConfigApi connection successful.
,03-24 21:16:26.556  1829  1844 W GmsBackupTransport: Unknown package in backup request: @pm@
03-24 21:16:26.556  1829  1844 V GmsBackupTransport: starting performBackup for @pm@
,03-24 21:16:26.573  1829  1844 V GmsBackupTransport: performBackup done for @pm@
,03-24 21:16:26.582   820  3386 D GpsLocationProvider: NTP server returned: 1458850586817 (Thu Mar 24 21:16:26 GMT+01:00 2016) reference: 168460 certainty: 32 system time offset: 235
,03-24 21:16:26.585   820  1293 D AlarmManagerService: Setting time of day to sec=1458850586
03-24 21:16:26.826   820  1293 W AlarmManagerService: Unable to set rtc to 1458850586: Invalid argument
,03-24 21:16:26.853   820  2348 I art     : Explicit concurrent mark sweep GC freed 60378(3MB) AllocSpace objects, 3(48KB) LOS objects, 32% free, 33MB/49MB, paused 1.776ms total 74.508ms
,03-24 21:16:26.868  1266  1266 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 21:16:26.893  1266  1290 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: android
03-24 21:16:26.893  1266  1290 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> android without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 21:16:26.893  1266  1290 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 21:16:26.893  1266  1290 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 21:16:26.899  1266  1290 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 21:16:26.903   820  3322 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 24 Mar 2016 20:16:26 GMT], X-Android-Received-Millis=[1458850586902], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1458850586832]}
03-24 21:16:26.903   820  3322 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Validated
03-24 21:16:26.903   820  1023 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
03-24 21:16:26.904   820  1023 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 100]
03-24 21:16:26.904   820  1023 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
03-24 21:16:26.904   820  1023 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
03-24 21:16:26.904   820  1023 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
03-24 21:16:26.904  1064  1545 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
03-24 21:16:26.904   820  1023 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,03-24 21:16:26.907  1801  3389 E Auth.Api.Credentials: [CredentialSyncAdapter] Unknown sync event.
,03-24 21:16:26.937  1266  1290 W GLSActivity: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-24 21:16:26.937  1266  1290 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-24 21:16:26.937  1266  1290 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-24 21:16:26.937  1266  1290 W GLSActivity: 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
03-24 21:16:26.937  1266  1290 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
03-24 21:16:26.937  1266  1290 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
03-24 21:16:26.937  1266  1290 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:446)
,03-24 21:16:26.947  1829  1845 W GmsBackupTransport: Error sending final backup to server: 
03-24 21:16:26.947  1829  1845 W GmsBackupTransport: com.google.android.gms.backup.d.d: Can not get client auth token
03-24 21:16:26.947  1829  1845 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:1080)
03-24 21:16:26.947  1829  1845 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:65)
03-24 21:16:26.947  1829  1845 W GmsBackupTransport: 	at com.google.android.gms.backup.aa.finishBackup(SourceFile:409)
03-24 21:16:26.947  1829  1845 W GmsBackupTransport: 	at android.app.backup.BackupTransport$TransportImpl.finishBackup(BackupTransport.java:547)
03-24 21:16:26.947  1829  1845 W GmsBackupTransport: 	at com.android.internal.backup.IBackupTransport$Stub.onTransact(IBackupTransport.java:162)
03-24 21:16:26.947  1829  1845 W GmsBackupTransport: 	at android.os.Binder.execTransact(Binder.java:446)
03-24 21:16:26.947  1829  1845 W GmsBackupTransport: Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
03-24 21:16:26.947  1829  1845 W GmsBackupTransport: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
03-24 21:16:26.947  1829  1845 W GmsBackupTransport: 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
03-24 21:16:26.947  1829  1845 W GmsBackupTransport: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
03-24 21:16:26.947  1829  1845 W GmsBackupTransport: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
03-24 21:16:26.947  1829  1845 W GmsBackupTransport: 	... 1 more
,03-24 21:16:26.950   820  1042 D BackupManagerService: Now staging backup of com.google.android.talk
03-24 21:16:26.955  1801  3404 W DriveInitializer: Background init thread started
03-24 21:16:26.966   820  1042 D BackupManagerService: Now staging backup of com.google.android.dialer
03-24 21:16:26.971   820  1042 D BackupManagerService: Now staging backup of com.android.providers.settings
03-24 21:16:26.975   820  1042 D BackupManagerService: Now staging backup of com.android.sharedstoragebackup
,03-24 21:16:26.981   820  1042 D BackupManagerService: Now staging backup of com.google.android.gm
,03-24 21:16:26.985   820  1042 D BackupManagerService: Now staging backup of com.android.providers.userdictionary
,03-24 21:16:26.991   820  1042 D BackupManagerService: Now staging backup of com.android.nfc
,03-24 21:16:26.997   820  1042 D BackupManagerService: Now staging backup of com.google.android.apps.genie.geniewidget
,03-24 21:16:27.001  1266  1296 I art     : Explicit concurrent mark sweep GC freed 24323(1308KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 861us total 28.911ms
,03-24 21:16:27.002   820  1042 D BackupManagerService: Now staging backup of com.google.android.marvin.talkback
,03-24 21:16:27.008   820  1042 D BackupManagerService: Now staging backup of com.google.android.inputmethod.latin
,03-24 21:16:27.017   820  1042 D BackupManagerService: Now staging backup of com.google.android.calendar
,03-24 21:16:27.041   820  1042 D BackupManagerService: Now staging backup of com.android.vending
,03-24 21:16:27.051   820  1042 D BackupManagerService: Now staging backup of android
,03-24 21:16:27.056   820  1042 D BackupManagerService: Now staging backup of com.google.android.googlequicksearchbox
,03-24 21:16:27.062   820   835 I ActivityManager: Start proc 3413:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,03-24 21:16:27.069  1829  1846 I GmsBackupTransport: Next backup will happen in 43199871 millis.
,03-24 21:16:27.071   820  1042 I BackupManagerService: Backup pass finished.
,03-24 21:16:27.078   369   369 I art     : Explicit concurrent mark sweep GC freed 704(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 21MB/36MB, paused 216us total 14.065ms
,03-24 21:16:27.088   369   369 I art     : Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 214us total 8.979ms
,03-24 21:16:27.097   369   369 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 294us total 8.798ms
,03-24 21:16:27.120  1801  3411 W DriveInitializer: Awaiting to be initialized
,03-24 21:16:27.124  3413  3413 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,03-24 21:16:27.128  1801  3404 W DriveInitializer: Background init thread ended
,03-24 21:16:27.141  3413  3413 D SprintDMHelper: simOperator:  IMSI: null
03-24 21:16:27.141  3413  3413 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,03-24 21:16:27.168  1801  1801 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,03-24 21:16:27.173  1801  1801 D SystemUpdateService: onCreate
,03-24 21:16:27.176  1801  1801 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,03-24 21:16:27.186  1801  3439 I SystemUpdateService: active receiver: enabled
,03-24 21:16:27.188  1801  3439 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,03-24 21:16:27.196  1801  3439 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]; metered: false; mobile allowed: true
03-24 21:16:27.196  1801  3439 I SystemUpdateService: now status is 0 (complete)
03-24 21:16:27.196  1801  3439 I SystemUpdateService: processDownloadedFile /data/data/com.google.android.gms/app_download/update.zip
03-24 21:16:27.196  1801  3439 I SystemUpdateService: file has been verified
03-24 21:16:27.196  1801  3439 I SystemUpdateService: OTA package size = 25802302
,03-24 21:16:27.205  1801  3439 I SystemUpdateService: showing system update notification
,03-24 21:16:27.230  1266  2545 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-24 21:16:27.230  1266  2545 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 21:16:27.230  1266  2545 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 21:16:27.230  1266  2545 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 21:16:27.233  1266  2545 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 21:16:27.239   820   820 I ValidateNoPeople: skipping global notification
03-24 21:16:27.239  1801  3445 I iu.SyncManager: SYNC; picasa accounts
,03-24 21:16:27.246  1801  1801 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,03-24 21:16:27.247  3082  3406 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
03-24 21:16:27.247  3082  3406 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-24 21:16:27.247  3082  3406 E HttpOperation: 	at jdm.a(PG:82)
03-24 21:16:27.247  3082  3406 E HttpOperation: 	at jcs.o(PG:406)
03-24 21:16:27.247  3082  3406 E HttpOperation: 	at jcn.a(PG:1379)
03-24 21:16:27.247  3082  3406 E HttpOperation: 	at jcs.i(PG:143)
03-24 21:16:27.247  3082  3406 E HttpOperation: 	at blb.a(PG:3937)
03-24 21:16:27.247  3082  3406 E HttpOperation: 	at czp.a(PG:18188)
03-24 21:16:27.247  3082  3406 E HttpOperation: 	at czp.a(PG:9081)
03-24 21:16:27.247  3082  3406 E HttpOperation: 	at czq.run(PG:1686)
03-24 21:16:27.247  3082  3406 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-24 21:16:27.247  3082  3406 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 21:16:27.247  3082  3406 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 21:16:27.247  3082  3406 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 21:16:27.247  3082  3406 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-24 21:16:27.247  3082  3406 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-24 21:16:27.247  3082  3406 E HttpOperation: 	at jdj.a(PG:4091)
03-24 21:16:27.247  3082  3406 E HttpOperation: 	at jdj.a(PG:1125)
03-24 21:16:27.247  3082  3406 E HttpOperation: 	at jdm.a(PG:77)
03-24 21:16:27.247  3082  3406 E HttpOperation: 	... 12 more
03-24 21:16:27.247  3082  3406 E HttpOperation: Caused by: faj: BadAuthentication
03-24 21:16:27.247  3082  3406 E HttpOperation: 	at fal.a(PG:38)
03-24 21:16:27.247  3082  3406 E HttpOperation: 	at jdj.a(PG:4089)
03-24 21:16:27.247  3082  3406 E HttpOperation: 	... 14 more
,03-24 21:16:27.249  1801  1801 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
03-24 21:16:27.252  1801  3445 I iu.UploadsManager: num queued entries: 0
03-24 21:16:27.255  1801  3445 I iu.UploadsManager: num updated entries: 0
03-24 21:16:27.256  1801  3445 I iu.SyncManager: NEXT; no task
03-24 21:16:27.261  1801  1801 D SystemUpdateService: onDestroy
03-24 21:16:27.275  1801  1801 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
03-24 21:16:27.278  1801  1801 I Kids    : [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
03-24 21:16:27.282  1266  1722 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-24 21:16:27.282  1266  1722 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 21:16:27.282  1266  1722 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 21:16:27.282  1266  1722 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 21:16:27.302   820   853 I ActivityManager: Start proc 3448:com.google.android.keep/u0a79 for service com.google.android.keep/.syncadapter.KeepSyncAdapterService
,03-24 21:16:27.305  1266  1722 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 21:16:27.339   820   836 I ActivityManager: Start proc 3468:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,03-24 21:16:27.348  3082  3406 E HttpOperation: [getmobileexperiments] Unexpected exception
03-24 21:16:27.348  3082  3406 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-24 21:16:27.348  3082  3406 E HttpOperation: 	at jdm.a(PG:82)
03-24 21:16:27.348  3082  3406 E HttpOperation: 	at jcs.o(PG:406)
03-24 21:16:27.348  3082  3406 E HttpOperation: 	at jcn.a(PG:1379)
03-24 21:16:27.348  3082  3406 E HttpOperation: 	at jcs.i(PG:143)
03-24 21:16:27.348  3082  3406 E HttpOperation: 	at hec.a(PG:42)
03-24 21:16:27.348  3082  3406 E HttpOperation: 	at hee.a(PG:102)
03-24 21:16:27.348  3082  3406 E HttpOperation: 	at czr.a(PG:65)
03-24 21:16:27.348  3082  3406 E HttpOperation: 	at kka.a(PG:108)
03-24 21:16:27.348  3082  3406 E HttpOperation: 	at czp.a(PG:19176)
03-24 21:16:27.348  3082  3406 E HttpOperation: 	at czp.a(PG:9081)
03-24 21:16:27.348  3082  3406 E HttpOperation: 	at czq.run(PG:1686)
03-24 21:16:27.348  3082  3406 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-24 21:16:27.348  3082  3406 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 21:16:27.348  3082  3406 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 21:16:27.348  3082  3406 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 21:16:27.348  3082  3406 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-24 21:16:27.348  3082  3406 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-24 21:16:27.348  3082  3406 E HttpOperation: 	at jdj.a(PG:4091)
03-24 21:16:27.348  3082  3406 E HttpOperation: 	at jdj.a(PG:1125)
03-24 21:16:27.348  3082  3406 E HttpOperation: 	at jdm.a(PG:77)
03-24 21:16:27.348  3082  3406 E HttpOperation: 	... 15 more
03-24 21:16:27.348  3082  3406 E HttpOperation: Caused by: faj: BadAuthentication
03-24 21:16:27.348  3082  3406 E HttpOperation: 	at fal.a(PG:38)
03-24 21:16:27.348  3082  3406 E HttpOperation: 	at jdj.a(PG:4089)
03-24 21:16:27.348  3082  3406 E HttpOperation: 	... 17 more
03-24 21:16:27.348  3082  3406 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
03-24 21:16:27.348  3082  3406 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
03-24 21:16:27.348  3082  3406 E ExperimentLoader: 	at jdm.a(PG:82)
03-24 21:16:27.348  3082  3406 E ExperimentLoader: 	at jcs.o(PG:406)
03-24 21:16:27.348  3082  3406 E ExperimentLoader: 	at jcn.a(PG:1379)
03-24 21:16:27.348  3082  3406 E ExperimentLoader: 	at jcs.i(PG:143)
03-24 21:16:27.348  3082  3406 E ExperimentLoader: 	at hec.a(PG:42)
03-24 21:16:27.348  3082  3406 E ExperimentLoader: 	at hee.a(PG:102)
03-24 21:16:27.348  3082  3406 E ExperimentLoader: 	at czr.a(PG:65)
03-24 21:16:27.348  3082  3406 E ExperimentLoader: 	at kka.a(PG:108)
03-24 21:16:27.348  3082  3406 E ExperimentLoader: 	at czp.a(PG:19176)
03-24 21:16:27.348  3082  3406 E ExperimentLoader: 	at czp.a(PG:9081)
03-24 21:16:27.348  3082  3406 E ExperimentLoader: 	at czq.run(PG:1686)
03-24 21:16:27.348  3082  3406 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-24 21:16:27.348  3082  3406 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 21:16:27.348  3082  3406 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 21:16:27.348  3082  3406 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 21:16:27.348  3082  3406 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
03-24 21:16:27.348  3082  3406 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-24 21:16:27.348  3082  3406 E ExperimentLoader: 	at jdj.a(PG:4091)
03-24 21:16:27.348  3082  3406 E ExperimentLoader: 	at jdj.a(PG:1,125)
03-24 21:16:27.348  3082  3406 E ExperimentLoader: 	at jdm.a(PG:77)
03-24 21:16:27.348  3082  3406 E ExperimentLoader: 	... 15 more
03-24 21:16:27.348  3082  3406 E ExperimentLoader: Caused by: faj: BadAuthentication
03-24 21:16:27.348  3082  3406 E ExperimentLoader: 	at fal.a(PG:38)
03-24 21:16:27.348  3082  3406 E ExperimentLoader: 	at jdj.a(PG:4089)
03-24 21:16:27.348  3082  3406 E ExperimentLoader: 	... 17 more
,03-24 21:16:27.453   820   853 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 38718, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,03-24 21:16:27.467  3468  3468 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
03-24 21:16:27.467  3468  3468 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-24 21:16:27.467  3468  3468 I GAv4    :   adb logcat -s GAv4
,03-24 21:16:27.489   820   853 I ActivityManager: Start proc 3494:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,03-24 21:16:27.492  3468  3468 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,03-24 21:16:27.509  3468  3468 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,03-24 21:16:27.530  3468  3512 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,03-24 21:16:27.574  3448  3517 V KeepSync: Connecting to GoogleApiClient
,03-24 21:16:27.583  3364  3513 V GoogleAuthProtoRequest: [335] a.<init>: mAccountName set to: thalitester@gmail.com
,03-24 21:16:27.590  3148  3463 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,03-24 21:16:27.614  1266  1296 I art     : Explicit concurrent mark sweep GC freed 12598(748KB) AllocSpace objects, 5(362KB) LOS objects, 38% free, 25MB/41MB, paused 1.781ms total 22.260ms
,03-24 21:16:27.659  1266  1722 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
03-24 21:16:27.659  1266  1722 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 21:16:27.659  1266  1722 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 21:16:27.659  1266  1722 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 21:16:27.663  1266  1722 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 21:16:27.666  1801  3532 W BaseAppContext: Using Auth Proxy for data requests.
,03-24 21:16:27.676  3364  3513 W ExperimentUpdateService: [335] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
03-24 21:16:27.677  3364  3513 W ExperimentUpdateService: [335] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-24 21:16:27.677  3364  3513 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-24 21:16:27.677  3364  3513 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-24 21:16:27.677  3364  3513 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-24 21:16:27.677  3364  3513 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-24 21:16:27.677  3364  3513 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-24 21:16:27.677  3364  3513 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-24 21:16:27.677  3364  3513 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-24 21:16:27.677  3364  3513 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-24 21:16:27.677  3364  3513 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-24 21:16:27.677  3364  3513 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-24 21:16:27.678  1801  3532 W BaseAppContext: Using Auth Proxy for data requests.
,03-24 21:16:27.682   820  1333 I ActivityManager: Killing 2905:com.android.settings/1000 (adj 15): empty #17
,03-24 21:16:27.726  1266  3504 D GCM     : Connected
,03-24 21:16:27.751  1266  3504 D GCM     : Message class com.google.f.a.a.p
,03-24 21:16:27.764  1266  1296 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
03-24 21:16:27.764  1266  1296 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 21:16:27.764  1266  1296 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 21:16:27.764  1266  1296 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 21:16:27.768  1266  1296 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 21:16:27.783  3468  3468 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,03-24 21:16:27.799  3468  3468 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 9434-9436)
03-24 21:16:27.799  3468  3468 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-24 21:16:27.803  1266  1266 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 21:16:27.808  3468  3468 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {8749374}
,03-24 21:16:27.809  3468  3468 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-24 21:16:27.809  3468  3468 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,03-24 21:16:27.816  1801  3532 E ClientConnectionOperation: Handling authorization failure
03-24 21:16:27.816  1801  3532 E ClientConnectionOperation: com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
03-24 21:16:27.816  1801  3532 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
03-24 21:16:27.816  1801  3532 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
03-24 21:16:27.816  1801  3532 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
03-24 21:16:27.816  1801  3532 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
03-24 21:16:27.816  1801  3532 E ClientConnectionOperation: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-24 21:16:27.816  1801  3532 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 21:16:27.816  1801  3532 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 21:16:27.816  1801  3532 E ClientConnectionOperation: 	at java.lang.Thread.run(Thread.java:818)
03-24 21:16:27.816  1801  3532 E ClientConnectionOperation: Caused by: com.google.android.gms.auth.ad: BadAuthentication
03-24 21:16:27.816  1801  3532 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.b(SourceFile:442)
03-24 21:16:27.816  1801  3532 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:365)
03-24 21:16:27.816  1801  3532 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:310)
03-24 21:16:27.816  1801  3532 E ClientConnectionOperation: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
03-24 21:16:27.816  1801  3532 E ClientConnectionOperation: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
03-24 21:16:27.816  1801  3532 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:30)
03-24 21:16:27.816  1801  3532 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:370)
03-24 21:16:27.816  1801  3532 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:340)
03-24 21:16:27.816  1801  3532 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:319)
03-24 21:16:27.816  1801  3532 E ClientConnectionOperation: 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
03-24 21:16:27.816  1801  3532 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
03-24 21:16:27.816  1801  3532 E ClientConnectionOperation: 	... 7 more
,03-24 21:16:27.820  3448  3517 V KeepSync: GoogleApiClient failed to connect with error code: 4
,03-24 21:16:27.828  3468  3468 I BrowserStartupController: Initializing chromium process, singleProcess=true
,03-24 21:16:27.838  3468  3468 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-24 21:16:27.841  3468  3468 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-24 21:16:27.843  3448  3517 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-24 21:16:27.854  3468  3468 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
03-24 21:16:27.858  3468  3468 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-24 21:16:27.858  3468  3468 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-24 21:16:27.858  3468  3468 I Adreno  : EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,03-24 21:16:27.860  3448  3517 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
03-24 21:16:27.860  3448  3517 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-24 21:16:27.906  3468  3552 W AudioManagerAndroid: Requires BLUETOOTH permission
,03-24 21:16:27.917  3468  3468 I NSApplication: Starting up...
,03-24 21:16:27.938  3494  3494 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,03-24 21:16:27.946  3494  3494 I BooksApp: Created application version: 3.6.8 (30608)
,03-24 21:16:27.972   820  1113 I art     : Explicit concurrent mark sweep GC freed 31268(1485KB) AllocSpace objects, 5(120KB) LOS objects, 32% free, 33MB/49MB, paused 1.075ms total 48.617ms
,03-24 21:16:28.001   820  1362 I ActivityManager: Start proc 3560:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
03-24 21:16:28.002   820  1362 I ActivityManager: Killing 2435:com.google.android.apps.maps/u0a65 (adj 15): empty #17
,03-24 21:16:28.309  1266  2545 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
03-24 21:16:28.309  1266  2545 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 21:16:28.309  1266  2545 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-24 21:16:28.309  1266  2545 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 21:16:28.320  1266  2545 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 21:16:28.349  3494  3577 I BooksSync: Starting books sync for 61035162, extras: ade
,03-24 21:16:28.395  3448  3517 E KeepSync: IOException
03-24 21:16:28.395  3448  3517 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
03-24 21:16:28.395  3448  3517 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
03-24 21:16:28.395  3448  3517 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
03-24 21:16:28.395  3448  3517 E KeepSync: 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
03-24 21:16:28.395  3448  3517 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
03-24 21:16:28.395  3448  3517 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
03-24 21:16:28.395  3448  3517 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
03-24 21:16:28.395  3448  3517 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
03-24 21:16:28.395  3448  3517 E KeepSync: 	at com.google.android.keep.util.m.a(SourceFile:207)
03-24 21:16:28.395  3448  3517 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
03-24 21:16:28.395  3448  3517 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
03-24 21:16:28.395  3448  3517 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
03-24 21:16:28.395  3448  3517 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
03-24 21:16:28.395  3448  3517 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
03-24 21:16:28.395  3448  3517 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
03-24 21:16:28.395  3448  3517 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
03-24 21:16:28.395  3448  3517 E KeepSync: 	... 10 more
03-24 21:16:28.395  3448  3517 W KeepSync: Sync result 2
,03-24 21:16:28.403   820   853 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 38724, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-24 21:16:28.403   820  2348 I ActivityManager: Killing 2991:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,03-24 21:16:28.504  3494  3585 I BooksConfig: GmsCore Version = 7.8.99 (2134222-430)
,03-24 21:16:28.571  1266  1726 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,03-24 21:16:28.571  1266  1726 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 21:16:28.571  1266  1726 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 21:16:28.571  1266  1726 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 21:16:28.575  1266  1726 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 21:16:28.615  1266  2545 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-24 21:16:28.615  1266  2545 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 21:16:28.615  1266  2545 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 21:16:28.616  1266  2545 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 21:16:28.634   820  1332 I ActivityManager: Start proc 3590:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
03-24 21:16:28.634   820  1332 I ActivityManager: Killing 3011:com.android.musicfx/u0a18 (adj 15): empty #17
,03-24 21:16:28.741  1266  2545 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 21:16:28.781  3494  3585 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,03-24 21:16:28.783  3494  3577 E BooksSync: Soft error
03-24 21:16:28.783  3494  3577 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-24 21:16:28.783  3494  3577 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,03-24 21:16:28.783  3494  3577 E BooksSync: Sync error
03-24 21:16:28.783  3494  3577 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-24 21:16:28.783  3494  3577 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-24 21:16:28.783  3494  3577 I BooksSync: Finished books sync
03-24 21:16:28.790   820   853 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 38724, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-24 21:16:28.792   820  1113 I ActivityManager: Killing 3040:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,03-24 21:16:29.247  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 21:16:29.247  3258  3314 I jxcore-log: 
,03-24 21:16:29.250  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,03-24 21:16:29.250  3258  3314 I jxcore-log: 
,03-24 21:16:29.255  3258  3314 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
,03-24 21:16:29.255  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 21:16:29.255  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 21:16:29.255  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
,03-24 21:16:29.255  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 21:16:29.255  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 21:16:29.255  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true,
03-24 21:16:29.255  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 21:16:29.258  3258  3314 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 21:16:29.260  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native,
03-24 21:16:29.260  3258  3314 I jxcore-log: 
,03-24 21:16:29.262  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,03-24 21:16:29.262  3258  3314 I jxcore-log: 
,03-24 21:16:29.698   820  2348 I ActivityManager: Killing 1462:android.process.acore/u0a5 (adj 15): empty #17
,03-24 21:16:29.805  3258  3314 I jxcore-log: Unit Test app is loaded
03-24 21:16:29.805  3258  3314 I jxcore-log: 
,03-24 21:16:29.811  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 21:16:29.811  3258  3314 I jxcore-log: 
,03-24 21:16:29.821  3258  3314 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
03-24 21:16:29.823  3258  3314 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
03-24 21:16:29.823  3258  3314 I jxcore-log: 
,03-24 21:16:29.825  3258  3314 I jxcore-log: My device name is: motorola-Nexus 6
03-24 21:16:29.825  3258  3314 I jxcore-log: 
,03-24 21:16:29.834  3258  3258 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,03-24 21:16:30.013   820  1333 I ActivityManager: Start proc 3608:com.qualcomm.timeservice/1000 for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver
,03-24 21:16:30.047  3608  3608 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1458850590047
03-24 21:16:30.047  3608  3608 D         : TimeServiceNative: User Time to be set is 1458850590047
03-24 21:16:30.047  3608  3608 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
03-24 21:16:30.047  3608  3608 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
03-24 21:16:30.047  3608  3608 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1458850590047
03-24 21:16:30.048  3608  3608 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
03-24 21:16:30.048   372   878 D QC-time-services: Daemon: Connection accepted:time_genoff
03-24 21:16:30.048   372  3625 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1458850590047
03-24 21:16:30.048   372  3625 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1458850590047, operation = 0
03-24 21:16:30.048   372  3625 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS7/10/70 16:28:12
03-24 21:16:30.048   372  3625 D QC-time-services: Daemon:Value read from RTC seconds = 19153692000
03-24 21:16:30.048   372  3625 D QC-time-services: Daemon:new time 1458850590047 
03-24 21:16:30.048   372  3625 D QC-time-services: Daemon: delta 1439696898047 genoff 1439696898047 
03-24 21:16:30.048   372  3625 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1439696898047 to memory
03-24 21:16:30.048   372  3625 D QC-time-services: Daemon:Opening File: /data/time/ats_2
03-24 21:16:30.048   372  3625 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,03-24 21:16:30.050   372  3625 D QC-time-services: Updating the TOD offset
,03-24 21:16:30.050   372  3625 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1439696898047 to memory
03-24 21:16:30.050   372  3625 D QC-time-services: Daemon:Opening File: /data/time/ats_1
03-24 21:16:30.050   372  3625 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,03-24 21:16:30.051   372  3625 E QC-time-services: Daemon:Update to modem bit set
03-24 21:16:30.051   372  3625 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
,03-24 21:16:30.051  3608  3608 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0,
03-24 21:16:30.051   372  3625 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1142885790047
03-24 21:16:30.052   820  1332 I ActivityManager: Killing 2808:com.google.android.gm/u0a78 (adj 15): empty #17
,03-24 21:16:30.120   372   878 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,03-24 21:16:30.126   372   876 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40,
,03-24 21:16:30.427   820  2348 I ActivityManager: Start proc 3627:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver
,03-24 21:16:30.475  3627  3627 I GAv4    : Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
03-24 21:16:30.475  3627  3627 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-24 21:16:30.475  3627  3627 I GAv4    :   adb logcat -s GAv4
,03-24 21:16:30.488  3627  3627 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,03-24 21:16:30.500  3627  3627 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,03-24 21:16:30.521  3627  3646 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,03-24 21:16:30.616   820  1460 I ActivityManager: Killing 1868:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,03-24 21:16:30.797   820  1022 D WifiService: New client listening to asynchronous messages
,03-24 21:16:30.820  1801  1931 I art     : Explicit concurrent mark sweep GC freed 16405(1248KB) AllocSpace objects, 18(288KB) LOS objects, 35% free, 28MB/44MB, paused 1.590ms total 42.349ms
,03-24 21:16:30.826  3148  3148 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,03-24 21:16:30.827  3148  3148 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-24 21:16:30.827  1801  1801 V Herrevad: NQAS connected
,03-24 21:16:30.953  1266  1296 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
03-24 21:16:30.953  1266  1296 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 21:16:30.953  1266  1296 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 21:16:30.953  1266  1296 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 21:16:30.956  1266  1296 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 21:16:30.967  3148  3656 E Babel   : UserRecoverableAuthException.
,03-24 21:16:30.968  3148  3656 E Babel   : eei: BadAuthentication
03-24 21:16:30.968  3148  3656 E Babel   : 	at eeg.a(Unknown Source),
03-24 21:16:30.968  3148  3656 E Babel   : 	at eeg.a(Unknown Source)
03-24 21:16:30.968  3148  3656 E Babel   : 	at eeg.a(Unknown Source)
03-24 21:16:30.968  3148  3656 E Babel   : 	at g.a(Unknown Source)
03-24 21:16:30.968  3148  3656 E Babel   : 	at cae.a(SourceFile:3089)
03-24 21:16:30.968  3148  3656 E Babel   : 	at cae.a(SourceFile:1131)
03-24 21:16:30.968  3148  3656 E Babel   : 	at cws.a(SourceFile:4333)
03-24 21:16:30.968  3148  3656 E Babel   : 	at cws.a(SourceFile:1419)
03-24 21:16:30.968  3148  3656 E Babel   : 	at crl.a(SourceFile:492)
03-24 21:16:30.968  3148  3656 E Babel   : 	at crl.a(SourceFile:1468)
03-24 21:16:30.968  3148  3656 E Babel   : 	at cqu.a(SourceFile:4416)
03-24 21:16:30.968  3148  3656 E Babel   : 	at cas.b(SourceFile:106)
03-24 21:16:30.968  3148  3656 E Babel   : 	at cap.d(SourceFile:335)
03-24 21:16:30.968  3148  3656 E Babel   : 	,at caq.run(SourceFile:81)
03-24 21:16:30.968  3148  3656 E Babel   : Error getting auth token
03-24 21:16:30.968  3148  3656 E Babel   : dvm
03-24 21:16:30.968  3148  3656 E Babel   : 	at g.a(Unknown Source)
03-24 21:16:30.968  3148  3656 E Babel   : 	at cae.a(SourceFile:3089)
03-24 21:16:30.968  3148  3656 E Babel   : 	at cae.a(SourceFile:1131)
03-24 21:16:30.968  3148  3656 E Babel   : 	,at cws.a(SourceFile:4333)
03-24 21:16:30.968  3148  3656 E Babel   : 	at cws.a(SourceFile:1419)
03-24 21:16:30.968  3148  3656 E Babel   : 	at crl.a(SourceFile:492)
03-24 21:16:30.968  3148  3656 E Babel   : 	at crl.a(SourceFile:1468)
03-24 21:16:30.968  3148  3656 E Babel   : 	at cqu.a(SourceFile:4416)
03-24 21:16:30.968  3148  3656 E Babel   : 	at cas.b(SourceFile:106)
03-24 21:16:30.968  3148  3656 E Babel   : 	at cap.d(SourceFile:335)
03-24 21:16:30.968  3148  3656 E Babel   : 	at caq.run(SourceFile:81)
,03-24 21:16:30.973  3148  3656 E Babel   : Account registration failed 1-Redacted-21
,03-24 21:16:30.975  3148  3656 E Babel   : cyp: null -- null
03-24 21:16:30.975  3148  3656 E Babel   : 	at cae.a(SourceFile:3121)
03-24 21:16:30.975  3148  3656 E Babel   : 	at cae.a(SourceFile:1131)
03-24 21:16:30.975  3148  3656 E Babel   : 	at cws.a(SourceFile:4333)
03-24 21:16:30.975  3148  3656 E Babel   : 	at cws.a(SourceFile:1419)
03-24 21:16:30.975  3148  3656 E Babel   : 	at crl.a(SourceFile:492)
03-24 21:16:30.975  3148  3656 E Babel   : 	at crl.a(SourceFile:1468)
03-24 21:16:30.975  3148  3656 E Babel   : 	at cqu.a(SourceFile:4416)
03-24 21:16:30.975  3148  3656 E Babel   : 	at cas.b(SourceFile:106)
03-24 21:16:30.975  3148  3656 E Babel   : 	at cap.d(SourceFile:335)
03-24 21:16:30.975  3148  3656 E Babel   : 	at caq.run(SourceFile:81)
,03-24 21:16:30.982  3148  3656 I art     : Note: end time exceeds epoch: 
,03-24 21:16:30.998  1266  1726 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
,03-24 21:16:30.998  1266  1726 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 21:16:30.998  1266  1726 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 21:16:30.998  1266  1726 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 21:16:31.001  1266  1726 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 21:16:31.012  1266  1726 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-24 21:16:31.029  3148  3663 E Babel   : Unexpected exception while authenticating.
03-24 21:16:31.030  3148  3663 E Babel   : eej: User intervention required. Notification has been pushed.
03-24 21:16:31.030  3148  3663 E Babel   : 	at eeg.b(Unknown Source)
03-24 21:16:31.030  3148  3663 E Babel   : 	at eeg.b(Unknown Source)
03-24 21:16:31.030  3148  3663 E Babel   : 	at g.a(Unknown Source)
03-24 21:16:31.030  3148  3663 E Babel   : 	at cae.b(SourceFile:1146)
03-24 21:16:31.030  3148  3663 E Babel   : 	at dcg.run(SourceFile:5617)
03-24 21:16:31.030  3148  3663 E Babel   : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 21:16:31.030  3148  3663 E Babel   : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 21:16:31.030  3148  3663 E Babel   : 	at java.lang.Thread.run(Thread.java:818)
,03-24 21:16:32.958  3494  3558 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,03-24 21:16:33.817  3258  3314 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
03-24 21:16:33.817  3258  3314 I jxcore-log: 
,03-24 21:16:34.155  3258  3314 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
03-24 21:16:34.155  3258  3314 I jxcore-log: 
,03-24 21:16:34.168  3258  3314 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
03-24 21:16:34.168  3258  3314 I jxcore-log: 
,03-24 21:16:34.172  3258  3314 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
03-24 21:16:34.172  3258  3314 I jxcore-log: 
,03-24 21:16:34.209  3258  3314 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
03-24 21:16:34.209  3258  3314 I jxcore-log: 
,03-24 21:16:34.226  3258  3314 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
03-24 21:16:34.226  3258  3314 I jxcore-log: 
,03-24 21:16:34.230  3258  3314 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
03-24 21:16:34.230  3258  3314 I jxcore-log: 
,03-24 21:16:36.152  3258  3314 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
03-24 21:16:36.152  3258  3314 I jxcore-log: 
,03-24 21:16:36.169  3258  3314 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
03-24 21:16:36.169  3258  3314 I jxcore-log: 
,03-24 21:16:36.178  3258  3314 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
03-24 21:16:36.178  3258  3314 I jxcore-log: 
,03-24 21:16:36.299  3258  3314 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
03-24 21:16:36.299  3258  3314 I jxcore-log: 
,03-24 21:16:36.353  3258  3314 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
03-24 21:16:36.353  3258  3314 I jxcore-log: 
,03-24 21:16:36.486  3258  3314 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
03-24 21:16:36.486  3258  3314 I jxcore-log: 
,03-24 21:16:36.491  3258  3314 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
03-24 21:16:36.491  3258  3314 I jxcore-log: 
,03-24 21:16:36.498  3258  3314 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
03-24 21:16:36.498  3258  3314 I jxcore-log: 
,03-24 21:16:36.517  3258  3314 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
03-24 21:16:36.517  3258  3314 I jxcore-log: 
,03-24 21:16:36.537  3258  3314 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
03-24 21:16:36.537  3258  3314 I jxcore-log: 
,03-24 21:16:36.637  3258  3314 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
03-24 21:16:36.637  3258  3314 I jxcore-log: 
,03-24 21:16:36.644  3258  3314 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
03-24 21:16:36.644  3258  3314 I jxcore-log: 
,03-24 21:16:36.669  3258  3314 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
03-24 21:16:36.669  3258  3314 I jxcore-log: ,
,03-24 21:16:36.783  1801  3382 V ConfigFetchTask: ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1XMs4nb20eq7yee1FMHZAcE-6sUSd0fICyCXrDj8I_DMVSlwv1LPVyv_UsBeMUQ_mQrnMGIRrNYOczgs7Oe45dqo9YdxeOOVHfqRuVfeqYSh2JFEG3-YTH82jCzZdXZ7lJdeN3WIwLiUtY1my7C_W5v5ZoOUmmBwRMKGnuf0rsQLaJRZ3YWP3OPzL09w_QUseZkjXM_
,03-24 21:16:36.854  1801  3382 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,03-24 21:16:38.392   820   836 I art     : Explicit concurrent mark sweep GC freed 19209(841KB) AllocSpace objects, 2(32KB) LOS objects, 32% free, 33MB/49MB, paused 1.634ms total 78.603ms
,03-24 21:16:38.414  2748  2764 D Finsky  : [250] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,03-24 21:16:38.427  1266  1266 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 21:16:38.448  1266  1290 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,03-24 21:16:38.448  1266  1290 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 21:16:38.448  1266  1290 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 21:16:38.448  1266  1290 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 21:16:38.451  1266  1290 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 21:16:38.463  2748  2764 D Finsky  : [250] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,03-24 21:16:40.980  1801  3382 I ConfigFetchTask: updating config table for com.google.android.gms
,03-24 21:16:41.010  1801  1801 I ConfigFetchService: PackageReceiver: Intent { act=com.google.android.gms.config.CHANGED cat=[com.google.android.gms] flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver }
,03-24 21:16:41.017  1801  1801 I ConfigFetchService: fetch service done; releasing wakelock
03-24 21:16:41.017  1801  1801 I ConfigFetchService: stopping self
,03-24 21:16:41.019  1801  1801 I ConfigFetchService: onStartCommand Intent { act=com.google.android.gms.config.CHANGED cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
03-24 21:16:41.019  1801  1801 I ConfigFetchService: GmsCore config value changed; rescheduling
,03-24 21:16:41.025   820  2348 I ActivityManager: Killing 2926:com.google.android.music:main/u0a66 (adj 15): empty #17
,03-24 21:16:41.406  3258  3314 I jxcore-log: TAP version 13
03-24 21:16:41.406  3258  3314 I jxcore-log: 
,03-24 21:16:41.410  3258  3314 I jxcore-log: # setup
03-24 21:16:41.410  3258  3314 I jxcore-log: 
,03-24 21:16:41.455  1266  3682 I VacuumService: Vacuum at: now=1458850601455 tag=VacuumService
,03-24 21:16:41.461  1266  3683 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,03-24 21:16:41.501  1266  3683 W Uploader: No account for auth token provided
,03-24 21:16:41.540  1266  3683 I art     : Explicit concurrent mark sweep GC freed 29693(1734KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 1.231ms total 34.012ms
,03-24 21:16:41.753  3258  3314 I jxcore-log: # 1. calling createNativeListener directly rejects
03-24 21:16:41.753  3258  3314 I jxcore-log: 
,03-24 21:16:42.486  3258  3314 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 21:16:42.486  3258  3314 I jxcore-log: 
,03-24 21:16:42.491  3258  3314 I jxcore-log: DEBUG createNativeListener: listening 32802
03-24 21:16:42.491  3258  3314 I jxcore-log: 
,03-24 21:16:42.498  3258  3314 I jxcore-log: ok 1 Should throw,
03-24 21:16:42.498  3258  3314 I jxcore-log: 
03-24 21:16:42.502  3258  3314 I jxcore-log: # teardown
03-24 21:16:42.502  3258  3314 I jxcore-log: 
,03-24 21:16:42.918  1266  1266 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 21:16:42.990  1266  1296 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,03-24 21:16:42.991  1266  1296 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 21:16:42.991  1266  1296 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 21:16:42.991  1266  1296 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 21:16:43.001  1266  1296 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 21:16:43.043  2748  2748 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,03-24 21:16:43.045  2748  2748 D Finsky  : [1] 5.onFinished: Installation state replication failed.
,03-24 21:16:43.047  2748  2748 D Finsky  : [1] 5.onFinished: Giving up after 6 failures.
,03-24 21:16:43.883  1266  3683 W Uploader: No account for auth token provided
,03-24 21:16:45.096  1266  3683 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
03-24 21:16:45.096  1266  3683 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 21:16:45.096  1266  3683 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 21:16:45.096  1266  3683 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 21:16:45.102  1266  3683 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 21:16:45.157  1266  3683 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-24 21:16:45.157  1266  3683 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.,
03-24 21:16:45.157  1266  3683 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-24 21:16:45.157  1266  3683 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-24 21:16:45.157  1266  3683 E Uploader: 	,at com.google.android.gms.auth.p.c(SourceFile:550)
03-24 21:16:45.157  1266  3683 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-24 21:16:45.157  1266  3683 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508),
03-24 21:16:45.157  1266  3683 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-24 21:16:45.157  1266  3683 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-24 21:16:45.157  1266  3683 E Uploader: ,	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-24 21:16:45.157  1266  3683 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-24 21:16:45.157  1266  3683 E Uploader: ,	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-24 21:16:45.157  1266  3683 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-24 21:16:45.379  3258  3314 I jxcore-log: # setup
03-24 21:16:45.379  3258  3314 I jxcore-log: 
,03-24 21:16:45.437  1266  3683 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,03-24 21:16:45.438  1266  3683 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 21:16:45.438  1266  3683 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 21:16:45.438  1266  3683 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 21:16:45.449  1266  3683 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 21:16:45.529  1266  3683 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-24 21:16:45.529  1266  3683 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-24 21:16:45.529  1266  3683 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-24 21:16:45.529  1266  3683 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-24 21:16:45.529  1266  3683 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-24 21:16:45.529  1266  3683 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-24 21:16:45.529  1266  3683 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-24 21:16:45.529  1266  3683 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-24 21:16:45.529  1266  3683 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-24 21:16:45.529  1266  3683 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-24 21:16:45.529  1266  3683 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-24 21:16:45.529  1266  3683 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-24 21:16:45.529  1266  3683 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-24 21:16:45.650  2145  2211 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 21:16:46.033  1266  1266 I ConfigService: onDestroy
,03-24 21:16:46.324  1266  3683 W Uploader: No account for auth token provided
,03-24 21:16:46.526  3258  3314 I jxcore-log: # 2. emits incomingConnectionState
03-24 21:16:46.526  3258  3314 I jxcore-log: ,
,03-24 21:16:47.351  1266  3683 W Uploader: No account for auth token provided
,03-24 21:16:48.855  3258  3314 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 21:16:48.855  3258  3314 I jxcore-log: 
,03-24 21:16:48.862  3258  3314 I jxcore-log: DEBUG createNativeListener: listening 55843
03-24 21:16:48.862  3258  3314 I jxcore-log: 
,03-24 21:16:48.872  3258  3314 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 21:16:48.872  3258  3314 I jxcore-log: 
,03-24 21:16:48.876  3258  3314 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 21:16:48.876  3258  3314 I jxcore-log: 
,03-24 21:16:48.886  3258  3314 I jxcore-log: DEBUG createNativeListener: new mux
03-24 21:16:48.886  3258  3314 I jxcore-log: 
,03-24 21:16:48.891  3258  3314 I jxcore-log: ok 2 initial connection state should be CONNECTED
03-24 21:16:48.891  3258  3314 I jxcore-log: 
,03-24 21:16:48.906  3258  3314 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 21:16:48.906  3258  3314 I jxcore-log: 
,03-24 21:16:48.907  3258  3314 I jxcore-log: ok 3 final connection state should be DISCONNECTED
03-24 21:16:48.907  3258  3314 I jxcore-log: 
,03-24 21:16:48.909  1266  3683 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,03-24 21:16:48.909  1266  3683 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-24 21:16:48.909  1266  3683 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-24 21:16:48.910  1266  3683 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 21:16:48.915  3258  3314 I jxcore-log: # teardown
03-24 21:16:48.915  3258  3314 I jxcore-log: 
,03-24 21:16:48.917  1266  3683 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 21:16:48.975  1266  3683 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-24 21:16:48.975  1266  3683 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-24 21:16:48.975  1266  3683 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-24 21:16:48.975  1266  3683 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-24 21:16:48.975  1266  3683 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-24 21:16:48.975  1266  3683 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-24 21:16:48.975  1266  3683 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-24 21:16:48.975  1266  3683 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-24 21:16:48.975  1266  3683 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-24 21:16:48.975  1266  3683 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-24 21:16:48.975  1266  3683 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-24 21:16:48.975  1266  3683 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-24 21:16:48.975  1266  3683 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-24 21:16:49.325  1266  3683 W Uploader: No account for auth token provided
,03-24 21:16:49.338  3258  3314 I jxcore-log: # setup
03-24 21:16:49.338  3258  3314 I jxcore-log: 
,03-24 21:16:49.998  1266  3683 W Uploader: No account for auth token provided,
,03-24 21:16:50.086  3258  3314 I jxcore-log: # 3. emits routerPortConnectionFailed
03-24 21:16:50.086  3258  3314 I jxcore-log: 
,03-24 21:16:51.862  1266  3683 W Uploader: No account for auth token provided
,03-24 21:16:52.525  3258  3314 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 21:16:52.525  3258  3314 I jxcore-log: 
03-24 21:16:52.526  1266  3683 W Uploader:  no longer exists, so no auth token.
,03-24 21:16:52.528  3258  3314 I jxcore-log: DEBUG createNativeListener: listening 54771
03-24 21:16:52.528  3258  3314 I jxcore-log: 
,03-24 21:16:52.534  3258  3314 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 21:16:52.534  3258  3314 I jxcore-log: 
,03-24 21:16:52.535  3258  3314 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 21:16:52.535  3258  3314 I jxcore-log: 
,03-24 21:16:52.537  3258  3314 I jxcore-log: DEBUG createNativeListener: new mux
03-24 21:16:52.537  3258  3314 I jxcore-log: 
,03-24 21:16:52.562  3258  3314 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 21:16:52.562  3258  3314 I jxcore-log: 
,03-24 21:16:52.564  3258  3314 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 21:16:52.564  3258  3314 I jxcore-log: 
,03-24 21:16:52.575  3258  3314 I jxcore-log: DEBUG createNativeListener: 
03-24 21:16:52.575  3258  3314 I jxcore-log: 
,03-24 21:16:52.576  3258  3314 I jxcore-log: ok 4 tried to connect to right port
03-24 21:16:52.576  3258  3314 I jxcore-log: 
03-24 21:16:52.577  3258  3314 I jxcore-log: ok 5 failed due to refused connection
03-24 21:16:52.577  3258  3314 I jxcore-log: 
03-24 21:16:52.577  3258  3314 I jxcore-log: ok 6 routerPortConnectionFailed is emitted
03-24 21:16:52.577  3258  3314 I jxcore-log: 
,03-24 21:16:52.580  3258  3314 I jxcore-log: # teardown
03-24 21:16:52.580  3258  3314 I jxcore-log: 
,03-24 21:16:52.581  3258  3314 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 21:16:52.581  3258  3314 I jxcore-log: 
,03-24 21:16:52.957  1266  3683 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,03-24 21:16:52.957  1266  3683 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 21:16:52.958  1266  3683 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-24 21:16:52.958  1266  3683 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 21:16:52.972  1266  3683 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 21:16:53.055  1266  3683 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-24 21:16:53.055  1266  3683 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-24 21:16:53.055  1266  3683 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-24 21:16:53.055  1266  3683 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-24 21:16:53.055  1266  3683 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-24 21:16:53.055  1266  3683 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-24 21:16:53.055  1266  3683 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-24 21:16:53.055  1266  3683 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-24 21:16:53.055  1266  3683 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-24 21:16:53.055  1266  3683 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-24 21:16:53.055  1266  3683 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-24 21:16:53.055  1266  3683 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-24 21:16:53.055  1266  3683 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-24 21:16:53.387  3258  3314 I jxcore-log: DEBUG createNativeListener: mux close
,03-24 21:16:53.387  3258  3314 I jxcore-log: 
,03-24 21:16:53.394  3258  3314 I jxcore-log: # setup
03-24 21:16:53.394  3258  3314 I jxcore-log: ,
03-24 21:16:53.396  3258  3314 I jxcore-log: DEBUG createNativeListener: incoming socket close
,03-24 21:16:53.396  3258  3314 I jxcore-log: 
,03-24 21:16:53.458  1266  3683 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,03-24 21:16:53.459  1266  3683 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-24 21:16:53.459  1266  3683 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 21:16:53.460  1266  3683 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 21:16:53.471  1266  3683 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 21:16:53.553  1266  3683 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-24 21:16:53.553  1266  3683 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-24 21:16:53.553  1266  3683 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-24 21:16:53.553  1266  3683 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-24 21:16:53.553  1266  3683 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-24 21:16:53.553  1266  3683 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-24 21:16:53.553  1266  3683 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-24 21:16:53.553  1266  3683 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-24 21:16:53.553  1266  3683 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-24 21:16:53.553  1266  3683 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-24 21:16:53.553  1266  3683 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-24 21:16:53.553  1266  3683 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-24 21:16:53.553  1266  3683 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-24 21:16:55.088  1266  3683 W Uploader: No account for auth token provided
,03-24 21:16:59.429  3258  3314 I jxcore-log: # 4. native server connections all up
03-24 21:16:59.429  3258  3314 I jxcore-log: 
,03-24 21:16:59.437  1266  3683 W Uploader: No account for auth token provided
,03-24 21:16:59.459  3364  3691 V GoogleAuthProtoRequest: [336] a.<init>: mAccountName set to: thalitester@gmail.com
,03-24 21:16:59.531  1266  2545 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,03-24 21:16:59.532  1266  2545 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 21:16:59.532  1266  2545 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 21:16:59.532  1266  2545 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 21:16:59.540  1266  2545 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 21:16:59.565  3364  3691 W ExperimentUpdateService: [336] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,03-24 21:16:59.567  3364  3691 W ExperimentUpdateService: [336] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-24 21:16:59.567  3364  3691 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-24 21:16:59.567  3364  3691 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-24 21:16:59.567  3364  3691 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-24 21:16:59.567  3364  3691 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-24 21:16:59.567  3364  3691 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-24 21:16:59.567  3364  3691 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-24 21:16:59.567  3364  3691 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-24 21:16:59.567  3364  3691 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-24 21:16:59.567  3364  3691 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-24 21:16:59.567  3364  3691 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-24 21:17:01.606  3258  3314 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 21:17:01.606  3258  3314 I jxcore-log: 
,03-24 21:17:01.609  3258  3314 I jxcore-log: DEBUG createNativeListener: listening 47806,
03-24 21:17:01.609  3258  3314 I jxcore-log: 
,03-24 21:17:01.620  3258  3314 I jxcore-log: DEBUG createNativeListener: new incoming socket
,03-24 21:17:01.620  3258  3314 I jxcore-log: 
,03-24 21:17:01.624  3258  3314 I jxcore-log: DEBUG createNativeListener: creating incoming mux
,03-24 21:17:01.624  3258  3314 I jxcore-log: 
,03-24 21:17:01.628  3258  3314 I jxcore-log: DEBUG createNativeListener: new mux
,03-24 21:17:01.628  3258  3314 I jxcore-log: 
,03-24 21:17:01.667  3258  3314 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 21:17:01.667  3258  3314 I jxcore-log: 
,03-24 21:17:01.671  3258  3314 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 21:17:01.671  3258  3314 I jxcore-log: 
,03-24 21:17:01.675  3258  3314 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 21:17:01.675  3258  3314 I jxcore-log: 
03-24 21:17:01.678  3258  3314 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 21:17:01.678  3258  3314 I jxcore-log: 
,03-24 21:17:01.719  3258  3314 I jxcore-log: ok 7 Send/recvd #1 should be equal length
03-24 21:17:01.719  3258  3314 I jxcore-log: 
,03-24 21:17:01.719  3258  3314 I jxcore-log: ok 8 Send/recvd #1 should be same
03-24 21:17:01.719  3258  3314 I jxcore-log: 
,03-24 21:17:01.722  3258  3314 I jxcore-log: ok 9 Send/recvd #2 should be equal length
03-24 21:17:01.722  3258  3314 I jxcore-log: 
,03-24 21:17:01.722  3258  3314 I jxcore-log: ok 10 Send/recvd #2 should be same
03-24 21:17:01.722  3258  3314 I jxcore-log: 
03-24 21:17:01.726  3258  3314 I jxcore-log: ok 11 Should be exactly 2 client sockets
03-24 21:17:01.726  3258  3314 I jxcore-log: 
,03-24 21:17:01.741  3258  3314 I jxcore-log: # teardown
03-24 21:17:01.741  3258  3314 I jxcore-log: 
,03-24 21:17:03.228  3258  3314 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 21:17:03.228  3258  3314 I jxcore-log: 
,03-24 21:17:03.231  3258  3314 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 21:17:03.231  3258  3314 I jxcore-log: 
,03-24 21:17:03.234  3258  3314 I jxcore-log: DEBUG createNativeListener: mux close
03-24 21:17:03.234  3258  3314 I jxcore-log: 
,03-24 21:17:03.239  3258  3314 I jxcore-log: # setup
03-24 21:17:03.239  3258  3314 I jxcore-log: 
,03-24 21:17:03.241  3258  3314 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 21:17:03.241  3258  3314 I jxcore-log: 
,03-24 21:17:04.945  3258  3314 I jxcore-log: # 5. native server - closing incoming stream cleans outgoing socket
03-24 21:17:04.945  3258  3314 I jxcore-log: 
,03-24 21:17:11.257  1801  3681 I ConfigFetchService: self-hosted config:fetch_interval = 43200
,03-24 21:17:11.305  1801  3681 I ConfigFetchService: stopping self
,03-24 21:17:15.629  3258  3314 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 21:17:15.629  3258  3314 I jxcore-log: 
,03-24 21:17:15.640  3258  3314 I jxcore-log: DEBUG createNativeListener: listening 56661
03-24 21:17:15.640  3258  3314 I jxcore-log: 
,03-24 21:17:15.647  3258  3314 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 21:17:15.647  3258  3314 I jxcore-log: 
,03-24 21:17:15.648  3258  3314 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 21:17:15.648  3258  3314 I jxcore-log: 
,03-24 21:17:15.650  3258  3314 I jxcore-log: DEBUG createNativeListener: new mux
03-24 21:17:15.650  3258  3314 I jxcore-log: 
,03-24 21:17:15.663  3258  3314 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 21:17:15.663  3258  3314 I jxcore-log: 
,03-24 21:17:15.666  3258  3314 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 21:17:15.666  3258  3314 I jxcore-log: 
,03-24 21:17:15.680  3258  3314 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 21:17:15.680  3258  3314 I jxcore-log: 
,03-24 21:17:15.693  3258  3314 I jxcore-log: ok 12 socket shouldn't close until after stream,
03-24 21:17:15.693  3258  3314 I jxcore-log: 
03-24 21:17:15.693  3258  3314 I jxcore-log: ok 13 incoming remains open
03-24 21:17:15.693  3258  3314 I jxcore-log: 
,03-24 21:17:15.699  3258  3314 I jxcore-log: # teardown,
03-24 21:17:15.699  3258  3314 I jxcore-log: 
,03-24 21:17:16.017  3258  3314 I jxcore-log: DEBUG createNativeListener: mux close
03-24 21:17:16.017  3258  3314 I jxcore-log: 
,03-24 21:17:16.022  3258  3314 I jxcore-log: # setup
03-24 21:17:16.022  3258  3314 I jxcore-log: 
,03-24 21:17:16.023  3258  3314 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 21:17:16.023  3258  3314 I jxcore-log: 
,03-24 21:17:16.240  3258  3314 I jxcore-log: # 6. native server - closing incoming connection cleans outgoing socket
03-24 21:17:16.240  3258  3314 I jxcore-log: 
,03-24 21:17:16.380  3258  3314 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 21:17:16.380  3258  3314 I jxcore-log: 
,03-24 21:17:16.391  3258  3314 I jxcore-log: DEBUG createNativeListener: listening 56796
03-24 21:17:16.391  3258  3314 I jxcore-log: 
,03-24 21:17:16.399  3258  3314 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 21:17:16.399  3258  3314 I jxcore-log: 
,03-24 21:17:16.401  3258  3314 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 21:17:16.401  3258  3314 I jxcore-log: 
03-24 21:17:16.402  3258  3314 I jxcore-log: DEBUG createNativeListener: new mux
03-24 21:17:16.402  3258  3314 I jxcore-log: 
,03-24 21:17:16.412  3258  3314 I jxcore-log: ok 14 we should not have gotten an error
03-24 21:17:16.412  3258  3314 I jxcore-log: 
,03-24 21:17:16.418  3258  3314 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 21:17:16.418  3258  3314 I jxcore-log: 
,03-24 21:17:16.424  3258  3314 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 21:17:16.424  3258  3314 I jxcore-log: 
,03-24 21:17:16.452  3258  3314 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 21:17:16.452  3258  3314 I jxcore-log: 
,03-24 21:17:16.457  3258  3314 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 21:17:16.457  3258  3314 I jxcore-log: 
,03-24 21:17:16.466  2145  2211 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 21:17:16.474  3258  3314 I jxcore-log: ok 15 socket shouldn't close until after incoming
03-24 21:17:16.474  3258  3314 I jxcore-log: 
,03-24 21:17:16.476  3258  3314 I jxcore-log: ok 16 incoming is cleaned up
03-24 21:17:16.476  3258  3314 I jxcore-log: 
,03-24 21:17:16.492  3258  3314 I jxcore-log: # teardown
03-24 21:17:16.492  3258  3314 I jxcore-log: 
,03-24 21:17:16.648  3258  3314 I jxcore-log: # setup
03-24 21:17:16.648  3258  3314 I jxcore-log: 
,03-24 21:17:16.896  3258  3314 I jxcore-log: # 7. native server - closing outgoing socket cleans associated mux stream
03-24 21:17:16.896  3258  3314 I jxcore-log: 
,03-24 21:17:18.849  3258  3314 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 21:17:18.849  3258  3314 I jxcore-log: 
,03-24 21:17:18.856  3258  3314 I jxcore-log: DEBUG createNativeListener: listening 55448
03-24 21:17:18.856  3258  3314 I jxcore-log: 
,03-24 21:17:18.861  3258  3314 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 21:17:18.861  3258  3314 I jxcore-log: 
,03-24 21:17:18.863  3258  3314 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 21:17:18.863  3258  3314 I jxcore-log: 
,03-24 21:17:18.865  3258  3314 I jxcore-log: DEBUG createNativeListener: new mux
03-24 21:17:18.865  3258  3314 I jxcore-log: 
,03-24 21:17:18.877  3258  3314 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 21:17:18.877  3258  3314 I jxcore-log: 
,03-24 21:17:18.880  3258  3314 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 21:17:18.880  3258  3314 I jxcore-log: 
,03-24 21:17:18.894  3258  3314 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 21:17:18.894  3258  3314 I jxcore-log: 
,03-24 21:17:18.904  3258  3314 I jxcore-log: ok 17 stream was closed
03-24 21:17:18.904  3258  3314 I jxcore-log: 
,03-24 21:17:18.905  3258  3314 I jxcore-log: ok 18 incoming should survive
03-24 21:17:18.905  3258  3314 I jxcore-log: 
03-24 21:17:18.905  3258  3314 I jxcore-log: ok 19 mux should have no streams
03-24 21:17:18.905  3258  3314 I jxcore-log: 
,03-24 21:17:18.912  3258  3314 I jxcore-log: # teardown
03-24 21:17:18.912  3258  3314 I jxcore-log: 
,03-24 21:17:21.455  3258  3314 I jxcore-log: DEBUG createNativeListener: mux close
03-24 21:17:21.455  3258  3314 I jxcore-log: 
03-24 21:17:21.460  3258  3314 I jxcore-log: # setup
03-24 21:17:21.460  3258  3314 I jxcore-log: 
03-24 21:17:21.461  3258  3314 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 21:17:21.461  3258  3314 I jxcore-log: 
,03-24 21:17:22.357  1234  1490 I Keyboard.Facilitator.LanguageModelFlusher: run()
03-24 21:17:22.358  1234  1490 I Keyboard.Facilitator: flushDynamicLanguageModels()
,03-24 21:17:22.399  1266  1266 I ConfigService: onCreate
,03-24 21:17:22.668  3258  3314 I jxcore-log: # 8. native server - closing the whole server cleans everything up
03-24 21:17:22.668  3258  3314 I jxcore-log: 
,03-24 21:17:22.766  3258  3314 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 21:17:22.766  3258  3314 I jxcore-log: 
,03-24 21:17:22.769  3258  3314 I jxcore-log: DEBUG createNativeListener: listening 47626
03-24 21:17:22.769  3258  3314 I jxcore-log: 
,03-24 21:17:22.778  3258  3314 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 21:17:22.778  3258  3314 I jxcore-log: 
,03-24 21:17:22.781  3258  3314 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 21:17:22.781  3258  3314 I jxcore-log: 
,03-24 21:17:22.785  3258  3314 I jxcore-log: DEBUG createNativeListener: new mux
03-24 21:17:22.785  3258  3314 I jxcore-log: 
,03-24 21:17:22.806  3258  3314 I jxcore-log: ok 20 we should not have gotten an error
03-24 21:17:22.806  3258  3314 I jxcore-log: 
,03-24 21:17:22.812  3258  3314 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 21:17:22.812  3258  3314 I jxcore-log: 
,03-24 21:17:22.815  3258  3314 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 21:17:22.815  3258  3314 I jxcore-log: 
,03-24 21:17:22.825  3258  3314 I jxcore-log: ok 21 Buffers are identical
03-24 21:17:22.825  3258  3314 I jxcore-log: 
,03-24 21:17:22.827  3258  3314 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 21:17:22.827  3258  3314 I jxcore-log: 
,03-24 21:17:22.831  3258  3314 I jxcore-log: DEBUG createNativeListener: mux close,
03-24 21:17:22.831  3258  3314 I jxcore-log: 
,03-24 21:17:22.835  3258  3314 I jxcore-log: ok 22 native server is nulled out
03-24 21:17:22.835  3258  3314 I jxcore-log: 
,03-24 21:17:22.836  3258  3314 I jxcore-log: ok 23 native server should be closed
03-24 21:17:22.836  3258  3314 I jxcore-log: 
03-24 21:17:22.836  3258  3314 I jxcore-log: ok 24 incoming has been removed
03-24 21:17:22.836  3258  3314 I jxcore-log: 
03-24 21:17:22.836  3258  3314 I jxcore-log: ok 25 Incoming should be done
03-24 21:17:22.836  3258  3314 I jxcore-log: 
03-24 21:17:22.837  3258  3314 I jxcore-log: ok 26 The mux object should be closed
03-24 21:17:22.837  3258  3314 I jxcore-log: 
03-24 21:17:22.837  3258  3314 I jxcore-log: ok 27 The mux stream should be closed,
03-24 21:17:22.837  3258  3314 I jxcore-log: 
,03-24 21:17:22.838  3258  3314 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 21:17:22.838  3258  3314 I jxcore-log: 
,03-24 21:17:22.852  3258  3314 I jxcore-log: # teardown
03-24 21:17:22.852  3258  3314 I jxcore-log: 
,03-24 21:17:22.945  3258  3314 I jxcore-log: # setup
03-24 21:17:22.945  3258  3314 I jxcore-log: 
,03-24 21:17:23.088  3258  3314 I jxcore-log: # 9. native server - we can get a ton of connections and data through and still clean up the server completely
03-24 21:17:23.088  3258  3314 I jxcore-log: 
,03-24 21:17:26.838  3494  3698 I BooksSync: Starting books sync for 61035162, extras: ade
,03-24 21:17:26.858  3448  3697 V KeepSync: Connecting to GoogleApiClient
,03-24 21:17:26.888  3494  3699 I BooksConfig: GmsCore Version = 7.8.99 (2134222-430)
,03-24 21:17:26.939  1266  2545 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,03-24 21:17:26.939  1266  2545 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 21:17:26.939  1266  2545 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 21:17:26.939  1266  2545 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 21:17:26.945  1266  2545 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 21:17:26.946  1266  1726 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,03-24 21:17:26.946  1266  1726 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 21:17:26.946  1266  1726 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-24 21:17:26.947  1266  1726 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 21:17:26.956  1266  1726 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 21:17:26.968  1801  3700 E ClientConnectionOperation: Handling authorization failure
03-24 21:17:26.968  1801  3700 E ClientConnectionOperation: com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
03-24 21:17:26.968  1801  3700 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
03-24 21:17:26.968  1801  3700 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
03-24 21:17:26.968  1801  3700 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
03-24 21:17:26.968  1801  3700 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
03-24 21:17:26.968  1801  3700 E ClientConnectionOperation: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-24 21:17:26.968  1801  3700 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 21:17:26.968  1801  3700 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 21:17:26.968  1801  3700 E ClientConnectionOperation: 	at java.lang.Thread.run(Thread.java:818)
03-24 21:17:26.968  1801  3700 E ClientConnectionOperation: Caused by: com.google.android.gms.auth.ad: BadAuthentication
03-24 21:17:26.968  1801  3700 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.b(SourceFile:442)
03-24 21:17:26.968  1801  3700 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:365)
03-24 21:17:26.968  1801  3700 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:310)
03-24 21:17:26.968  1801  3700 E ClientConnectionOperation: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
03-24 21:17:26.968  1801  3700 E ClientConnectionOperation: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
03-24 21:17:26.968  1801  3700 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:30)
03-24 21:17:26.968  1801  3700 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:370)
03-24 21:17:26.968  1801  3700 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:340)
03-24 21:17:26.968  1801  3700 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:319)
03-24 21:17:26.968  1801  3700 E ClientConnectionOperation: 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
03-24 21:17:26.968  1801  3700 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
03-24 21:17:26.968  1801  3700 E ClientConnectionOperation: 	... 7 more
,03-24 21:17:26.971  3448  3697 V KeepSync: GoogleApiClient failed to connect with error code: 4
,03-24 21:17:26.978  3448  3697 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-24 21:17:26.990  3448  3697 E SQLiteLog: (284) automatic index on blob_node(is_deleted),
,03-24 21:17:26.992  3448  3697 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-24 21:17:27.040  1266  1715 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,03-24 21:17:27.040  1266  1715 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 21:17:27.040  1266  1715 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 21:17:27.040  1266  1715 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 21:17:27.046  1266  1715 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 21:17:27.060  3494  3699 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,03-24 21:17:27.062  3494  3698 E BooksSync: Soft error
03-24 21:17:27.062  3494  3698 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-24 21:17:27.062  3494  3698 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-24 21:17:27.062  3494  3698 E BooksSync: Sync error
03-24 21:17:27.062  3494  3698 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-24 21:17:27.062  3494  3698 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-24 21:17:27.062  3494  3698 I BooksSync: Finished books sync
,03-24 21:17:27.069  1266  1726 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,03-24 21:17:27.069  1266  1726 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 21:17:27.069  1266  1726 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 21:17:27.069  1266  1726 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 21:17:27.075   820   853 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 201042, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-24 21:17:27.077  1266  1726 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 21:17:27.121  3448  3697 E KeepSync: IOException
03-24 21:17:27.121  3448  3697 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
03-24 21:17:27.121  3448  3697 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
03-24 21:17:27.121  3448  3697 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
03-24 21:17:27.121  3448  3697 E KeepSync: 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
03-24 21:17:27.121  3448  3697 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
03-24 21:17:27.121  3448  3697 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
03-24 21:17:27.121  3448  3697 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
03-24 21:17:27.121  3448  3697 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
03-24 21:17:27.121  3448  3697 E KeepSync: 	at com.google.android.keep.util.m.a(SourceFile:207)
03-24 21:17:27.121  3448  3697 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
03-24 21:17:27.121  3448  3697 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
03-24 21:17:27.121  3448  3697 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
03-24 21:17:27.121  3448  3697 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
03-24 21:17:27.121  3448  3697 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
03-24 21:17:27.121  3448  3697 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
03-24 21:17:27.121  3448  3697 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
03-24 21:17:27.121  3448  3697 E KeepSync: 	... 10 more
03-24 21:17:27.121  3448  3697 W KeepSync: Sync result 2
,03-24 21:17:27.203   820   853 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 200492, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-24 21:17:27.297   820  1362 I art     : Explicit concurrent mark sweep GC freed 30404(1309KB) AllocSpace objects, 5(362KB) LOS objects, 31% free, 34MB/50MB, paused 1.601ms total 95.596ms
,03-24 21:17:27.371  3258  3314 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 21:17:27.371  3258  3314 I jxcore-log: 
,03-24 21:17:27.376  3258  3314 I jxcore-log: DEBUG createNativeListener: listening 42872
03-24 21:17:27.376  3258  3314 I jxcore-log: 
,03-24 21:17:27.379  1266  1726 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-24 21:17:27.379  1266  1726 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 21:17:27.379  1266  1726 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 21:17:27.379  1266  1726 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 21:17:27.386  1266  1726 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 21:17:27.392  3258  3314 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 21:17:27.392  3258  3314 I jxcore-log: 
,03-24 21:17:27.393  3258  3314 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 21:17:27.393  3258  3314 I jxcore-log: 
,03-24 21:17:27.394  3258  3314 I jxcore-log: DEBUG createNativeListener: new mux
03-24 21:17:27.394  3258  3314 I jxcore-log: 
,03-24 21:17:27.396  3258  3314 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 21:17:27.396  3258  3314 I jxcore-log: 
,03-24 21:17:27.397  3258  3314 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 21:17:27.397  3258  3314 I jxcore-log: 
03-24 21:17:27.400  3258  3314 I jxcore-log: DEBUG createNativeListener: new mux
03-24 21:17:27.400  3258  3314 I jxcore-log: 
03-24 21:17:27.403  3258  3314 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 21:17:27.403  3258  3314 I jxcore-log: 
03-24 21:17:27.403  3258  3314 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 21:17:27.403  3258  3314 I jxcore-log: 
03-24 21:17:27.404  3258  3314 I jxcore-log: DEBUG createNativeListener: new mux
03-24 21:17:27.404  3258  3314 I jxcore-log: 
03-24 21:17:27.407  3258  3314 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 21:17:27.407  3258  3314 I jxcore-log: 
03-24 21:17:27.407  3082  3705 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
03-24 21:17:27.407  3082  3705 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-24 21:17:27.407  3082  3705 E HttpOperation: 	at jdm.a(PG:82)
03-24 21:17:27.407  3082  3705 E HttpOperation: 	at jcs.o(PG:406)
03-24 21:17:27.407  3082  3705 E HttpOperation: 	at jcn.a(PG:1379)
03-24 21:17:27.407  3082  3705 E HttpOperation: 	at jcs.i(PG:143)
03-24 21:17:27.407  3082  3705 E HttpOperation: 	at blb.a(PG:3937)
03-24 21:17:27.407  3082  3705 E HttpOperation: 	at czp.a(PG:18188)
03-24 21:17:27.407  3082  3705 E HttpOperation: 	at czp.a(PG:9081)
03-24 21:17:27.407  3082  3705 E HttpOperation: 	at czq.run(PG:1686)
03-24 21:17:27.407  3082  3705 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-24 21:17:27.407  3082  3705 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 21:17:27.407  3082  3705 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 21:17:27.407  3082  3705 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 21:17:27.407  3082  3705 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-24 21:17:27.407  3082  3705 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-24 21:17:27.407  3082  3705 E HttpOperation: 	at jdj.a(PG:4091)
03-24 21:17:27.407  3082  3705 E HttpOperation: 	at jdj.a(PG:1125)
03-24 21:17:27.407  3082  3705 E HttpOperation: 	at jdm.a(PG:77)
03-24 21:17:27.407  3082  3705 E HttpOperation: 	... 12 more
03-24 21:17:27.407  3082  3705 E HttpOperation: Caused by: faj: BadAuthentication
03-24 21:17:27.407  3082  3705 E HttpOperation: 	at fal.a(PG:38)
03-24 21:17:27.407  3082  3705 E HttpOperation: 	at jdj.a(PG:4089)
03-24 21:17:27.407  3082  3705 E HttpOperation: 	... 14 more
03-24 21:17:27.407  3258  3314 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 21:17:27.407  3258  3314 I jxcore-log: 
03-24 21:17:27.408  3258  3314 I jxcore-log: DEBUG createNativeListener: new mux
03-24 21:17:27.408  3258  3314 I jxcore-log: 
03-24 21:17:27.410  3258  3314 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 21:17:27.410  3258  3314 I jxcore-log: 
03-24 21:17:27.411  3258  3314 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 21:17:27.411  3258  3314 I jxcore-log: 
03-24 21:17:27.411  3258  3314 I jxcore-log: DEBUG createNativeListener: new mux
03-24 21:17:27.411  3258  3314 I jxcore-log: 
03-24 21:17:27.414  3258  3314 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 21:17:27.414  3258  3314 I jxcore-log: 
03-24 21:17:27.414  3258  3314 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 21:17:27.414  3258  3314 I jxcore-log: 
03-24 21:17:27.415  3258  3314 I jxcore-log: DEBUG createNativeListener: new mux
03-24 21:17:27.415  3258  3314 I jxcore-log: 
,03-24 21:17:27.417  3258  3314 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 21:17:27.417  3258  3314 I jxcore-log: 
03-24 21:17:27.417  3258  3314 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 21:17:27.417  3258  3314 I jxcore-log: 
03-24 21:17:27.418  3258  3314 I jxcore-log: DEBUG createNativeListener: new mux
03-24 21:17:27.418  3258  3314 I jxcore-log: 
03-24 21:17:27.420  3258  3314 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 21:17:27.420  3258  3314 I jxcore-log: 
03-24 21:17:27.420  3258  3314 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 21:17:27.420  3258  3314 I jxcore-log: 
03-24 21:17:27.421  3258  3314 I jxcore-log: DEBUG createNativeListener: new mux
03-24 21:17:27.421  3258  3314 I jxcore-log: 
03-24 21:17:27.423  3258  3314 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 21:17:27.423  3258  3314 I jxcore-log: 
,03-24 21:17:27.424  3258  3314 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 21:17:27.424  3258  3314 I jxcore-log: 
03-24 21:17:27.425  3258  3314 I jxcore-log: DEBUG createNativeListener: new mux
03-24 21:17:27.425  3258  3314 I jxcore-log: 
,03-24 21:17:27.427  3258  3314 I jxcore-log: DEBUG createNativeListener: new incoming socket,
03-24 21:17:27.427  3258  3314 I jxcore-log: 
03-24 21:17:27.428  3258  3314 I jxcore-log: DEBUG createNativeListener: creating incoming mux
,03-24 21:17:27.428  3258  3314 I jxcore-log: 
,03-24 21:17:27.428  3258  3314 I jxcore-log: DEBUG createNativeListener: new mux
03-24 21:17:27.428  3258  3314 I jxcore-log: 
,03-24 21:17:27.451  1266  1296 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native,
03-24 21:17:27.451  1266  1296 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 21:17:27.451  1266  1296 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-24 21:17:27.451  1266  1296 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 21:17:27.455  1266  1296 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,03-24 21:17:27.466  3082  3705 E HttpOperation: [getmobileexperiments] Unexpected exception,
03-24 21:17:27.466  3082  3705 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-24 21:17:27.466  3082  3705 E HttpOperation: ,	at jdm.a(PG:82)
03-24 21:17:27.466  3082  3705 E HttpOperation: 	at jcs.o(PG:406)
,03-24 21:17:27.466  3082  3705 E HttpOperation: 	at jcn.a(PG:1379)
03-24 21:17:27.466  3082  3705 E HttpOperation: 	,at jcs.i(PG:143)
03-24 21:17:27.466  3082  3705 E HttpOperation: 	at hec.a(PG:42)
03-24 21:17:27.466  3082  3705 E HttpOperation: 	at hee.a(PG:102)
03-24 21:17:27.466  3082  3705 E HttpOperation: 	at czr.a(PG:65)
03-24 21:17:27.466  3082  3705 E HttpOperation: 	at kka.a(PG:108)
03-24 21:17:27.466  3082  3705 E HttpOperation: 	at czp.a(PG:19176)
03-24 21:17:27.466  3082  3705 E HttpOperation: 	at czp.a(PG:9081)
03-24 21:17:27.466  3082  3705 E HttpOperation: ,	at czq.run(PG:1686)
03-24 21:17:27.466  3082  3705 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-24 21:17:27.466  3082  3705 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 21:17:27.466  3082  3705 E HttpOperation: 	,at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 21:17:27.466  3082  3705 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 21:17:27.466  3082  3705 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-24 21:17:27.466  3082  3705 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-24 21:17:27.466  3082  3705 E HttpOperation: 	,at jdj.a(PG:4091)
03-24 21:17:27.466  3082  3705 E HttpOperation: 	at jdj.a(PG:1125)
,03-24 21:17:27.466  3082  3705 E HttpOperation: 	at jdm.a(PG:77)
03-24 21:17:27.466  3082  3705 E HttpOperation: 	... 15 more
03-24 21:17:27.466  3082  3705 E HttpOperation: Caused by: faj: BadAuthentication,
03-24 21:17:27.466  3082  3705 E HttpOperation: 	at fal.a(PG:38)
03-24 21:17:27.466  3082  3705 E HttpOperation: 	,at jdj.a(PG:4089)
03-24 21:17:27.466  3082  3705 E HttpOperation: 	... 17 more
03-24 21:17:27.467  3082  3705 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
03-24 21:17:27.467  3082  3705 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
03-24 21:17:27.467  3082  3705 E ExperimentLoader: 	at jdm.a(PG:82)
,03-24 21:17:27.467  3082  3705 E ExperimentLoader: 	at jcs.o(PG:406)
03-24 21:17:27.467  3082  3705 E ExperimentLoader: 	at jcn.a(PG:1379)
03-24 21:17:27.467  3082  3705 E ExperimentLoader: ,	at jcs.i(PG:143)
03-24 21:17:27.467  3082  3705 E ExperimentLoader: 	at hec.a(PG:42)
03-24 21:17:27.467  3082  3705 E ExperimentLoader: 	at hee.a(PG:102)
03-24 21:17:27.467  3082  3705 E ExperimentLoader: 	at czr.a(PG:65),
03-24 21:17:27.467  3082  3705 E ExperimentLoader: 	at kka.a(PG:108)
03-24 21:17:27.467  3082  3705 E ExperimentLoader: 	at czp.a(PG:19176)
03-24 21:17:27.467  3082  3705 E ExperimentLoader: 	at czp.a(PG:9081)
03-24 21:17:27.467  3082  3705 E ExperimentLoader: 	at czq.run(PG:1686)
,03-24 21:17:27.467  3082  3705 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-24 21:17:27.467  3082  3705 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 21:17:27.467  3082  3705 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 21:17:27.467  3082  3705 E ExperimentLoader: 	,at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 21:17:27.467  3082  3705 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
03-24 21:17:27.467  3082  3705 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-24 21:17:27.467  3082  3705 E ExperimentLoader: 	at jdj.a(PG:4091)
03-24 21:17:27.467  3082  3705 E ExperimentLoader: 	at jdj.a(PG:1125)
,03-24 21:17:27.467  3082  3705 E ExperimentLoader: 	at jdm.a(PG:77)
03-24 21:17:27.467  3082  3705 E ExperimentLoader: 	... 15 more
03-24 21:17:27.467  3082  3705 E ExperimentLoader: Caused by: faj: BadAuthentication
03-24 21:17:27.467  3082  3705 E ExperimentLoader: 	at fal.a(PG:38),
03-24 21:17:27.467  3082  3705 E ExperimentLoader: 	at jdj.a(PG:4089)
03-24 21:17:27.467  3082  3705 E ExperimentLoader: 	... 17 more
,03-24 21:17:27.486  1266  1266 I ConfigService: onDestroy
,03-24 21:17:27.546  3258  3314 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 21:17:27.546  3258  3314 I jxcore-log: 
,03-24 21:17:27.549  3258  3314 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 21:17:27.549  3258  3314 I jxcore-log: 
,03-24 21:17:27.551  3258  3314 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 21:17:27.551  3258  3314 I jxcore-log: 
,03-24 21:17:27.553  3258  3314 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 21:17:27.553  3258  3314 I jxcore-log: 
,03-24 21:17:27.555  3258  3314 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 21:17:27.555  3258  3314 I jxcore-log: 
,03-24 21:17:27.559  3258  3314 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 21:17:27.559  3258  3314 I jxcore-log: 
,03-24 21:17:27.568   820   853 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 201544, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,03-24 21:17:27.568  3258  3314 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 21:17:27.568  3258  3314 I jxcore-log: 
,03-24 21:17:27.575  3258  3314 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 21:17:27.575  3258  3314 I jxcore-log: 
03-24 21:17:27.582  3258  3314 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 21:17:27.582  3258  3314 I jxcore-log: 
,03-24 21:17:27.585  3258  3314 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 21:17:27.585  3258  3314 I jxcore-log: 
,03-24 21:17:27.586  3258  3314 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 21:17:27.586  3258  3314 I jxcore-log: 
,03-24 21:17:27.588  3258  3314 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 21:17:27.588  3258  3314 I jxcore-log: 
,03-24 21:17:27.589  3258  3314 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 21:17:27.589  3258  3314 I jxcore-log: 
,03-24 21:17:27.591  3258  3314 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 21:17:27.591  3258  3314 I jxcore-log: 
,03-24 21:17:27.592  3258  3314 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 21:17:27.592  3258  3314 I jxcore-log: 
,03-24 21:17:27.594  3258  3314 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 21:17:27.594  3258  3314 I jxcore-log: 
,03-24 21:17:27.596  3258  3314 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 21:17:27.596  3258  3314 I jxcore-log: 
,03-24 21:17:27.597  3258  3314 I jxcore-log: DEBUG createNativeListener: new outgoing socket
,03-24 21:17:27.597  3258  3314 I jxcore-log: 
03-24 21:17:27.599  3258  3314 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 21:17:27.599  3258  3314 I jxcore-log: 
03-24 21:17:27.600  3258  3314 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 21:17:27.600  3258  3314 I jxcore-log: 
,03-24 21:17:27.605  3258  3314 I jxcore-log: DEBUG createNativeListener: new stream: ,
03-24 21:17:27.605  3258  3314 I jxcore-log: 
,03-24 21:17:27.607  3258  3314 I jxcore-log: DEBUG createNativeListener: new outgoing socket,
03-24 21:17:27.607  3258  3314 I jxcore-log: 
,03-24 21:17:27.609  3258  3314 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 21:17:27.609  3258  3314 I jxcore-log: 
,03-24 21:17:27.610  3258  3314 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 21:17:27.610  3258  3314 I jxcore-log: 
,03-24 21:17:27.612  3258  3314 I jxcore-log: DEBUG createNativeListener: new stream: 
,03-24 21:17:27.612  3258  3314 I jxcore-log: 
,03-24 21:17:27.614  3258  3314 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 21:17:27.614  3258  3314 I jxcore-log: 
,03-24 21:17:27.616  3258  3314 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 21:17:27.616  3258  3314 I jxcore-log: 
,03-24 21:17:27.617  3258  3314 I jxcore-log: DEBUG createNativeListener: new outgoing socket,
03-24 21:17:27.617  3258  3314 I jxcore-log: 
,03-24 21:17:27.618  3258  3314 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 21:17:27.618  3258  3314 I jxcore-log: 
,03-24 21:17:27.620  3258  3314 I jxcore-log: DEBUG createNativeListener: new outgoing socket,
03-24 21:17:27.620  3258  3314 I jxcore-log: 
,03-24 21:17:27.621  3258  3314 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 21:17:27.621  3258  3314 I jxcore-log: 
,03-24 21:17:27.623  3258  3314 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 21:17:27.623  3258  3314 I jxcore-log: 
,03-24 21:17:27.625  3258  3314 I jxcore-log: DEBUG createNativeListener: new stream: ,
03-24 21:17:27.625  3258  3314 I jxcore-log: 
,03-24 21:17:27.626  3258  3314 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 21:17:27.626  3258  3314 I jxcore-log: 
,03-24 21:17:27.627  3258  3314 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 21:17:27.627  3258  3314 I jxcore-log: 
,03-24 21:17:27.628  3258  3314 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 21:17:27.628  3258  3314 I jxcore-log: 
,03-24 21:17:27.630  3258  3314 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 21:17:27.630  3258  3314 I jxcore-log: 
,03-24 21:17:27.631  3258  3314 I jxcore-log: DEBUG createNativeListener: new outgoing socket
,03-24 21:17:27.631  3258  3314 I jxcore-log: 
,03-24 21:17:27.632  3258  3314 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 21:17:27.632  3258  3314 I jxcore-log: 
,03-24 21:17:27.633  3258  3314 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 21:17:27.633  3258  3314 I jxcore-log: 
03-24 21:17:27.635  3258  3314 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 21:17:27.635  3258  3314 I jxcore-log: 
03-24 21:17:27.637  3258  3314 I jxcore-log: DEBUG createNativeListener: new outgoing socket
,03-24 21:17:27.637  3258  3314 I jxcore-log: 
03-24 21:17:27.638  3258  3314 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 21:17:27.638  3258  3314 I jxcore-log: 
,03-24 21:17:27.639  3258  3314 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 21:17:27.639  3258  3314 I jxcore-log: 
,03-24 21:17:27.640  3258  3314 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 21:17:27.640  3258  3314 I jxcore-log: 
,03-24 21:17:27.641  3258  3314 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 21:17:27.641  3258  3314 I jxcore-log: 
,03-24 21:17:27.642  3258  3314 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 21:17:27.642  3258  3314 I jxcore-log: 
,03-24 21:17:27.644  3258  3314 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 21:17:27.644  3258  3314 I jxcore-log: 
,03-24 21:17:27.651  3258  3314 I jxcore-log: DEBUG createNativeListener: new stream: 
,03-24 21:17:27.651  3258  3314 I jxcore-log: 
,03-24 21:17:27.653  3258  3314 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 21:17:27.653  3258  3314 I jxcore-log: 
,03-24 21:17:27.654  3258  3314 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 21:17:27.654  3258  3314 I jxcore-log: 
,03-24 21:17:27.655  3258  3314 I jxcore-log: DEBUG createNativeListener: new outgoing socket,
03-24 21:17:27.655  3258  3314 I jxcore-log: 
03-24 21:17:27.656  3258  3314 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 21:17:27.656  3258  3314 I jxcore-log: 
,03-24 21:17:27.657  3258  3314 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 21:17:27.657  3258  3314 I jxcore-log: 
,03-24 21:17:27.658  3258  3314 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 21:17:27.658  3258  3314 I jxcore-log: 
03-24 21:17:27.659  3258  3314 I jxcore-log: DEBUG createNativeListener: new outgoing socket
,03-24 21:17:27.659  3258  3314 I jxcore-log: 
,03-24 21:17:27.661  3258  3314 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 21:17:27.661  3258  3314 I jxcore-log: 
,03-24 21:17:27.663  3258  3314 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 21:17:27.663  3258  3314 I jxcore-log: 
,03-24 21:17:27.665  3258  3314 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 21:17:27.665  3258  3314 I jxcore-log: 
,03-24 21:17:27.666  3258  3314 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 21:17:27.666  3258  3314 I jxcore-log: 
,03-24 21:17:27.667  3258  3314 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 21:17:27.667  3258  3314 I jxcore-log: 
,03-24 21:17:27.668  3258  3314 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 21:17:27.668  3258  3314 I jxcore-log: 
03-24 21:17:27.669  3258  3314 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 21:17:27.669  3258  3314 I jxcore-log: 
,03-24 21:17:27.670  3258  3314 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 21:17:27.670  3258  3314 I jxcore-log: 
,03-24 21:17:27.672  3258  3314 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 21:17:27.672  3258  3314 I jxcore-log: 
,03-24 21:17:27.673  3258  3314 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 21:17:27.673  3258  3314 I jxcore-log: 
,03-24 21:17:27.674  3258  3314 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 21:17:27.674  3258  3314 I jxcore-log: 
,03-24 21:17:27.675  3258  3314 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 21:17:27.675  3258  3314 I jxcore-log: 
,03-24 21:17:27.676  3258  3314 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 21:17:27.676  3258  3314 I jxcore-log: 
,03-24 21:17:27.678  3258  3314 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 21:17:27.678  3258  3314 I jxcore-log: 
,03-24 21:17:27.678  3258  3314 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 21:17:27.678  3258  3314 I jxcore-log: 
,03-24 21:17:27.680  3258  3314 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 21:17:27.680  3258  3314 I jxcore-log: 
,03-24 21:17:27.681  3258  3314 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 21:17:27.681  3258  3314 I jxcore-log: 
,03-24 21:17:27.683  3258  3314 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 21:17:27.683  3258  3314 I jxcore-log: 
,03-24 21:17:27.684  3258  3314 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 21:17:27.684  3258  3314 I jxcore-log: 
,03-24 21:17:27.685  3258  3314 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 21:17:27.685  3258  3314 I jxcore-log: 
,03-24 21:17:27.686  3258  3314 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 21:17:27.686  3258  3314 I jxcore-log: 
03-24 21:17:27.688  3258  3314 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 21:17:27.688  3258  3314 I jxcore-log: 
,03-24 21:17:27.689  3258  3314 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 21:17:27.689  3258  3314 I jxcore-log: 
,03-24 21:17:27.690  3258  3314 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 21:17:27.690  3258  3314 I jxcore-log: 
,03-24 21:17:27.764  3258  3314 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 21:17:27.764  3258  3314 I jxcore-log: 
,03-24 21:17:27.765  3258  3314 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 21:17:27.765  3258  3314 I jxcore-log: 
,03-24 21:17:27.766  3258  3314 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 21:17:27.766  3258  3314 I jxcore-log: 
,03-24 21:17:27.767  3258  3314 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 21:17:27.767  3258  3314 I jxcore-log: 
03-24 21:17:27.768  3258  3314 I jxcore-log: DEBUG createNativeListener: mux close
03-24 21:17:27.768  3258  3314 I jxcore-log: 
,03-24 21:17:27.770  3258  3314 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 21:17:27.770  3258  3314 I jxcore-log: 
,03-24 21:17:27.770  3258  3314 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 21:17:27.770  3258  3314 I jxcore-log: 
03-24 21:17:27.771  3258  3314 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 21:17:27.771  3258  3314 I jxcore-log: 
03-24 21:17:27.772  3258  3314 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 21:17:27.772  3258  3314 I jxcore-log: 
03-24 21:17:27.773  3258  3314 I jxcore-log: DEBUG createNativeListener: mux close
03-24 21:17:27.773  3258  3314 I jxcore-log: 
,03-24 21:17:27.776  3258  3314 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 21:17:27.776  3258  3314 I jxcore-log: 
,03-24 21:17:27.777  3258  3314 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 21:17:27.777  3258  3314 I jxcore-log: 
03-24 21:17:27.778  3258  3314 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 21:17:27.778  3258  3314 I jxcore-log: 
03-24 21:17:27.778  3258  3314 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 21:17:27.778  3258  3314 I jxcore-log: 
,03-24 21:17:27.780  3258  3314 I jxcore-log: DEBUG createNativeListener: mux close
03-24 21:17:27.780  3258  3314 I jxcore-log: 
,03-24 21:17:27.781  3258  3314 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 21:17:27.781  3258  3314 I jxcore-log: 
,03-24 21:17:27.782  3258  3314 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 21:17:27.782  3258  3314 I jxcore-log: 
,03-24 21:17:27.783  3258  3314 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 21:17:27.783  3258  3314 I jxcore-log: 
,03-24 21:17:27.784  3258  3314 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 21:17:27.784  3258  3314 I jxcore-log: 
03-24 21:17:27.785  3258  3314 I jxcore-log: DEBUG createNativeListener: mux close
03-24 21:17:27.785  3258  3314 I jxcore-log: 
,03-24 21:17:27.786  3258  3314 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 21:17:27.786  3258  3314 I jxcore-log: 
,03-24 21:17:27.787  3258  3314 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 21:17:27.787  3258  3314 I jxcore-log: 
03-24 21:17:27.787  3258  3314 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 21:17:27.787  3258  3314 I jxcore-log: 
,03-24 21:17:27.788  3258  3314 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 21:17:27.788  3258  3314 I jxcore-log: ,
03-24 21:17:27.789  3258  3314 I jxcore-log: DEBUG createNativeListener: mux close
03-24 21:17:27.789  3258  3314 I jxcore-log: 
,03-24 21:17:27.790  3258  3314 I jxcore-log: DEBUG createNativeListener: stream close:,
03-24 21:17:27.790  3258  3314 I jxcore-log: 
03-24 21:17:27.791  3258  3314 I jxcore-log: DEBUG createNativeListener: stream close:
,03-24 21:17:27.791  3258  3314 I jxcore-log: 
03-24 21:17:27.792  3258  3314 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 21:17:27.792  3258  3314 I jxcore-log: 
03-24 21:17:27.792  3258  3314 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 21:17:27.792  3258  3314 I jxcore-log: 
03-24 21:17:27.794  3258  3314 I jxcore-log: DEBUG createNativeListener: mux close
03-24 21:17:27.794  3258  3314 I jxcore-log: 
03-24 21:17:27.795  3258  3314 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 21:17:27.795  3258  3314 I jxcore-log: 
03-24 21:17:27.795  3258  3314 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 21:17:27.795  3258  3314 I jxcore-log: 
03-24 21:17:27.796  3258  3314 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 21:17:27.796  3258  3314 I jxcore-log: 
03-24 21:17:27.797  3258  3314 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 21:17:27.797  3258  3314 I jxcore-log: 
03-24 21:17:27.798  3258  3314 I jxcore-log: DEBUG createNativeListener: mux close
03-24 21:17:27.798  3258  3314 I jxcore-log: 
03-24 21:17:27.799  3258  3314 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 21:17:27.799  3258  3314 I jxcore-log: 
,03-24 21:17:27.799  3258  3314 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 21:17:27.799  3258  3314 I jxcore-log: 
03-24 21:17:27.800  3258  3314 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 21:17:27.800  3258  3314 I jxcore-log: 
03-24 21:17:27.801  3258  3314 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 21:17:27.801  3258  3314 I jxcore-log: 
03-24 21:17:27.802  3258  3314 I jxcore-log: DEBUG createNativeListener: mux close
03-24 21:17:27.802  3258  3314 I jxcore-log: 
,03-24 21:17:27.802  3258  3314 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 21:17:27.802  3258  3314 I jxcore-log: 
03-24 21:17:27.803  3258  3314 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 21:17:27.803  3258  3314 I jxcore-log: 
03-24 21:17:27.804  3258  3314 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 21:17:27.804  3258  3314 I jxcore-log: 
03-24 21:17:27.805  3258  3314 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 21:17:27.805  3258  3314 I jxcore-log: 
,03-24 21:17:27.806  3258  3314 I jxcore-log: DEBUG createNativeListener: mux close
03-24 21:17:27.806  3258  3314 I jxcore-log: 
03-24 21:17:27.807  3258  3314 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 21:17:27.807  3258  3314 I jxcore-log: 
03-24 21:17:27.808  3258  3314 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 21:17:27.808  3258  3314 I jxcore-log: 
03-24 21:17:27.808  3258  3314 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 21:17:27.808  3258  3314 I jxcore-log: 
,03-24 21:17:27.809  3258  3314 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 21:17:27.809  3258  3314 I jxcore-log: 
03-24 21:17:27.810  3258  3314 I jxcore-log: DEBUG createNativeListener: mux close
03-24 21:17:27.810  3258  3314 I jxcore-log: 
03-24 21:17:27.813  3258  3314 I jxcore-log: ok 28 native server is nulled out
03-24 21:17:27.813  3258  3314 I jxcore-log: 
03-24 21:17:27.813  3258  3314 I jxcore-log: ok 29 native server should be closed
03-24 21:17:27.813  3258  3314 I jxcore-log: 
,03-24 21:17:27.814  3258  3314 I jxcore-log: ok 30 incoming has been removed
03-24 21:17:27.814  3258  3314 I jxcore-log: 
03-24 21:17:27.815  3258  3314 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 21:17:27.815  3258  3314 I jxcore-log: 
03-24 21:17:27.816  3258  3314 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 21:17:27.816  3258  3314 I jxcore-log: 
03-24 21:17:27.816  3258  3314 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 21:17:27.816  3258  3314 I jxcore-log: 
,03-24 21:17:27.816  3258  3314 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 21:17:27.816  3258  3314 I jxcore-log: 
03-24 21:17:27.817  3258  3314 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 21:17:27.817  3258  3314 I jxcore-log: 
03-24 21:17:27.817  3258  3314 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 21:17:27.817  3258  3314 I jxcore-log: 
03-24 21:17:27.817  3258  3314 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 21:17:27.817  3258  3314 I jxcore-log: 
,03-24 21:17:27.818  3258  3314 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 21:17:27.818  3258  3314 I jxcore-log: 
03-24 21:17:27.818  3258  3314 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 21:17:27.818  3258  3314 I jxcore-log: 
03-24 21:17:27.818  3258  3314 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 21:17:27.818  3258  3314 I jxcore-log: 
,03-24 21:17:27.920  3258  3314 I jxcore-log: # teardown
03-24 21:17:27.920  3258  3314 I jxcore-log: 
,03-24 21:17:28.512  3258  3314 I jxcore-log: # setup
03-24 21:17:28.512  3258  3314 I jxcore-log: 
,03-24 21:17:28.667  3258  3314 I jxcore-log: # 10. native server - simulate mux failure, make sure everything is cleaned up
03-24 21:17:28.667  3258  3314 I jxcore-log: 
,03-24 21:17:28.825  3258  3314 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 21:17:28.825  3258  3314 I jxcore-log: 
,03-24 21:17:28.828  3258  3314 I jxcore-log: DEBUG createNativeListener: listening 53503
03-24 21:17:28.828  3258  3314 I jxcore-log: 
,03-24 21:17:28.833  3258  3314 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 21:17:28.833  3258  3314 I jxcore-log: 
,03-24 21:17:28.835  3258  3314 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 21:17:28.835  3258  3314 I jxcore-log: 
,03-24 21:17:28.836  3258  3314 I jxcore-log: DEBUG createNativeListener: new mux
03-24 21:17:28.836  3258  3314 I jxcore-log: 
,03-24 21:17:28.844  3258  3314 I jxcore-log: ok 31 we should not have gotten an error
03-24 21:17:28.844  3258  3314 I jxcore-log: 
,03-24 21:17:28.847  3258  3314 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 21:17:28.847  3258  3314 I jxcore-log: 
,03-24 21:17:28.850  3258  3314 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 21:17:28.850  3258  3314 I jxcore-log: 
,03-24 21:17:28.857  3258  3314 I jxcore-log: ok 32 Buffers are identical
03-24 21:17:28.857  3258  3314 I jxcore-log: ,
,03-24 21:17:28.858  3258  3314 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 21:17:28.858  3258  3314 I jxcore-log: 
,03-24 21:17:28.860  3258  3314 I jxcore-log: DEBUG createNativeListener: mux close
03-24 21:17:28.860  3258  3314 I jxcore-log: 
,03-24 21:17:28.871  3258  3314 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 21:17:28.871  3258  3314 I jxcore-log: 
,03-24 21:17:28.872  3258  3314 I jxcore-log: ok 33 server should be fine
03-24 21:17:28.872  3258  3314 I jxcore-log: 
03-24 21:17:28.872  3258  3314 I jxcore-log: ok 34 server should be open
03-24 21:17:28.872  3258  3314 I jxcore-log: 
,03-24 21:17:28.873  3258  3314 I jxcore-log: ok 35 incoming has been removed
03-24 21:17:28.873  3258  3314 I jxcore-log: 
03-24 21:17:28.874  3258  3314 I jxcore-log: ok 36 The mux object should be closed
03-24 21:17:28.874  3258  3314 I jxcore-log: 
,03-24 21:17:28.874  3258  3314 I jxcore-log: ok 37 The mux stream should be closed
03-24 21:17:28.874  3258  3314 I jxcore-log: 
,03-24 21:17:28.881  3258  3314 I jxcore-log: # teardown
03-24 21:17:28.881  3258  3314 I jxcore-log: 
,03-24 21:17:29.056  3258  3314 I jxcore-log: # setup
,03-24 21:17:29.056  3258  3314 I jxcore-log: 
,03-24 21:17:29.176  3258  3314 I jxcore-log: # 11. native server - timing out the incoming connection cleans everything up
,03-24 21:17:29.176  3258  3314 I jxcore-log: 
,03-24 21:17:29.309  3258  3314 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 21:17:29.309  3258  3314 I jxcore-log: 
,03-24 21:17:29.317  3258  3314 I jxcore-log: DEBUG createNativeListener: listening 58599
03-24 21:17:29.317  3258  3314 I jxcore-log: 
,03-24 21:17:29.325  3258  3314 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 21:17:29.325  3258  3314 I jxcore-log: 
,03-24 21:17:29.328  3258  3314 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 21:17:29.328  3258  3314 I jxcore-log: 
,03-24 21:17:29.332  3258  3314 I jxcore-log: DEBUG createNativeListener: new mux
03-24 21:17:29.332  3258  3314 I jxcore-log: 
,03-24 21:17:29.347  3258  3314 I jxcore-log: ok 38 we should not have gotten an error
03-24 21:17:29.347  3258  3314 I jxcore-log: 
,03-24 21:17:29.355  3258  3314 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 21:17:29.355  3258  3314 I jxcore-log: 
,03-24 21:17:29.358  3258  3314 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 21:17:29.358  3258  3314 I jxcore-log: 
,03-24 21:17:29.365  3258  3314 I jxcore-log: ok 39 Buffers are identical
03-24 21:17:29.365  3258  3314 I jxcore-log: 
,03-24 21:17:29.369  3258  3314 I jxcore-log: DEBUG createNativeListener: incoming socket timeout
03-24 21:17:29.369  3258  3314 I jxcore-log: 
,03-24 21:17:29.370  3258  3314 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 21:17:29.370  3258  3314 I jxcore-log: 
,03-24 21:17:29.372  3258  3314 I jxcore-log: DEBUG createNativeListener: mux close
03-24 21:17:29.372  3258  3314 I jxcore-log: 
,03-24 21:17:29.377  3258  3314 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 21:17:29.377  3258  3314 I jxcore-log: 
,03-24 21:17:29.377  3258  3314 I jxcore-log: ok 40 server should be fine
03-24 21:17:29.377  3258  3314 I jxcore-log: 
03-24 21:17:29.378  3258  3314 I jxcore-log: ok 41 server should be open
03-24 21:17:29.378  3258  3314 I jxcore-log: 
,03-24 21:17:29.378  3258  3314 I jxcore-log: ok 42 incoming has been removed
03-24 21:17:29.378  3258  3314 I jxcore-log: 
,03-24 21:17:29.379  3258  3314 I jxcore-log: ok 43 The mux object should be closed
03-24 21:17:29.379  3258  3314 I jxcore-log: 
03-24 21:17:29.379  3258  3314 I jxcore-log: ok 44 The mux stream should be closed
03-24 21:17:29.379  3258  3314 I jxcore-log: 
,03-24 21:17:29.388  3258  3314 I jxcore-log: # teardown
03-24 21:17:29.388  3258  3314 I jxcore-log: 
,03-24 21:17:29.561  3258  3314 I jxcore-log: # setup
03-24 21:17:29.561  3258  3314 I jxcore-log: 
,03-24 21:17:29.668  3258  3314 I jxcore-log: # 12. closeAll can close even when connections open
03-24 21:17:29.668  3258  3314 I jxcore-log: 
,03-24 21:17:29.803  3258  3314 I jxcore-log: ok 45 not possible to connect to the server anymore
03-24 21:17:29.803  3258  3314 I jxcore-log: 
,03-24 21:17:29.808  3258  3314 I jxcore-log: # teardown
03-24 21:17:29.808  3258  3314 I jxcore-log: 
,03-24 21:17:29.924  3258  3314 I jxcore-log: # setup
03-24 21:17:29.924  3258  3314 I jxcore-log: 
,03-24 21:17:30.108  3258  3314 I jxcore-log: # 13. closeAll with promise
03-24 21:17:30.108  3258  3314 I jxcore-log: 
,03-24 21:17:30.241  3258  3314 I jxcore-log: ok 46 not possible to connect to the server anymore
03-24 21:17:30.241  3258  3314 I jxcore-log: 
,03-24 21:17:30.246  3258  3314 I jxcore-log: # teardown
03-24 21:17:30.246  3258  3314 I jxcore-log: 
,03-24 21:17:30.394  3258  3314 I jxcore-log: # setup
03-24 21:17:30.394  3258  3314 I jxcore-log: 
,03-24 21:17:30.529  3258  3314 I jxcore-log: # 14. closeAll properly throws when closing a non open server with eatNotRunning set to false
03-24 21:17:30.529  3258  3314 I jxcore-log: 
,03-24 21:17:30.647  3258  3314 I jxcore-log: ok 47 Got the right error
03-24 21:17:30.647  3258  3314 I jxcore-log: 
,03-24 21:17:30.652  3258  3314 I jxcore-log: # teardown
03-24 21:17:30.652  3258  3314 I jxcore-log: 
,03-24 21:17:30.756  3258  3314 I jxcore-log: # setup
03-24 21:17:30.756  3258  3314 I jxcore-log: 
,03-24 21:17:30.859  3258  3314 I jxcore-log: # 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true
03-24 21:17:30.859  3258  3314 I jxcore-log: 
,03-24 21:17:30.988  3258  3314 I jxcore-log: # teardown
03-24 21:17:30.988  3258  3314 I jxcore-log: 
,03-24 21:17:31.138  3258  3314 I jxcore-log: # setup
03-24 21:17:31.138  3258  3314 I jxcore-log: 
,03-24 21:17:31.254  3258  3314 I jxcore-log: # 16. multiplex can send data
03-24 21:17:31.254  3258  3314 I jxcore-log: 
,03-24 21:17:31.376  3258  3314 I jxcore-log: ok 48 String should be length:200
03-24 21:17:31.376  3258  3314 I jxcore-log: 
,03-24 21:17:31.385  3258  3314 I jxcore-log: # teardown
03-24 21:17:31.385  3258  3314 I jxcore-log: 
,03-24 21:17:31.525  3258  3314 I jxcore-log: # setup
03-24 21:17:31.525  3258  3314 I jxcore-log: 
,03-24 21:17:31.658  3258  3314 I jxcore-log: # 17. enqueue and run in order
03-24 21:17:31.658  3258  3314 I jxcore-log: 
,03-24 21:17:31.913  3258  3314 I jxcore-log: ok 49 firstPromise setTimeout
03-24 21:17:31.913  3258  3314 I jxcore-log: 
,03-24 21:17:31.916  3258  3314 I jxcore-log: ok 50 firstPromise result
03-24 21:17:31.916  3258  3314 I jxcore-log: 
,03-24 21:17:31.918  3258  3314 I jxcore-log: ok 51 firstPromise testValue
03-24 21:17:31.918  3258  3314 I jxcore-log: 
,03-24 21:17:32.023  3258  3314 I jxcore-log: ok 52 secondPromise setTimeout
03-24 21:17:32.023  3258  3314 I jxcore-log: 
,03-24 21:17:32.028  3258  3314 I jxcore-log: ok 53 secondPromise result
03-24 21:17:32.028  3258  3314 I jxcore-log: 
,03-24 21:17:32.029  3258  3314 I jxcore-log: ok 54 secondPromise testValue
03-24 21:17:32.029  3258  3314 I jxcore-log: 
,03-24 21:17:32.032  3258  3314 I jxcore-log: ok 55 thirdPromise in promise
03-24 21:17:32.032  3258  3314 I jxcore-log: 
,03-24 21:17:32.035  3258  3314 I jxcore-log: ok 56 thirdPromise result
03-24 21:17:32.035  3258  3314 I jxcore-log: 
,03-24 21:17:32.038  3258  3314 I jxcore-log: ok 57 thirdPromise testValue
03-24 21:17:32.038  3258  3314 I jxcore-log: 
,03-24 21:17:32.048  3258  3314 I jxcore-log: # teardown
03-24 21:17:32.048  3258  3314 I jxcore-log: 
,03-24 21:17:32.397  3258  3314 I jxcore-log: # setup
03-24 21:17:32.397  3258  3314 I jxcore-log: 
,03-24 21:17:32.496  3258  3314 I jxcore-log: # 18. enqueueAtTop and run backwards
03-24 21:17:32.496  3258  3314 I jxcore-log: 
,03-24 21:17:33.009  3258  3314 I jxcore-log: ok 58 thirdPromise - first to run
03-24 21:17:33.009  3258  3314 I jxcore-log: ,
,03-24 21:17:33.011  3258  3314 I jxcore-log: ok 59 thirdPromise - in resolve
03-24 21:17:33.011  3258  3314 I jxcore-log: 
03-24 21:17:33.011  3258  3314 I jxcore-log: ok 60 secondPromise - second to run
03-24 21:17:33.011  3258  3314 I jxcore-log: 
,03-24 21:17:33.012  3258  3314 I jxcore-log: ok 61 secondPromise - in catch
03-24 21:17:33.012  3258  3314 I jxcore-log: 
03-24 21:17:33.013  3258  3314 I jxcore-log: ok 62 firstPromise - third to run
03-24 21:17:33.013  3258  3314 I jxcore-log: 
03-24 21:17:33.014  3258  3314 I jxcore-log: ok 63 firstPromise - in then
03-24 21:17:33.014  3258  3314 I jxcore-log: 
03-24 21:17:33.014  3258  3314 I jxcore-log: ok 64 testing promises
03-24 21:17:33.014  3258  3314 I jxcore-log: 
,03-24 21:17:33.016  3258  3314 I jxcore-log: # teardown
03-24 21:17:33.016  3258  3314 I jxcore-log: 
,03-24 21:17:33.152  3258  3314 I jxcore-log: # setup
03-24 21:17:33.152  3258  3314 I jxcore-log: 
,03-24 21:17:33.308  3258  3314 I jxcore-log: # 19. mix enqueue and enqueueAtTop
03-24 21:17:33.308  3258  3314 I jxcore-log: 
,03-24 21:17:33.431  3258  3314 I jxcore-log: ok 65 fourth
03-24 21:17:33.431  3258  3314 I jxcore-log: 
,03-24 21:17:33.434  3258  3314 I jxcore-log: ok 66 fourth
03-24 21:17:33.434  3258  3314 I jxcore-log: 
,03-24 21:17:33.438  3258  3314 I jxcore-log: ok 67 second
03-24 21:17:33.438  3258  3314 I jxcore-log: 
,03-24 21:17:33.441  3258  3314 I jxcore-log: ok 68 secondPromise - in then,
03-24 21:17:33.441  3258  3314 I jxcore-log: 
,03-24 21:17:33.545  3258  3314 I jxcore-log: ok 69 first,
03-24 21:17:33.545  3258  3314 I jxcore-log: 
,03-24 21:17:33.548  3258  3314 I jxcore-log: ok 70 firstPromise - in catch
03-24 21:17:33.548  3258  3314 I jxcore-log: 
,03-24 21:17:33.550  3258  3314 I jxcore-log: ok 71 third
03-24 21:17:33.550  3258  3314 I jxcore-log: 
,03-24 21:17:33.553  3258  3314 I jxcore-log: ok 72 thirdPromise - in then
03-24 21:17:33.553  3258  3314 I jxcore-log: 
,03-24 21:17:33.555  3258  3314 I jxcore-log: ok 73 testingPromises
03-24 21:17:33.555  3258  3314 I jxcore-log: 
,03-24 21:17:33.566  3258  3314 I jxcore-log: # teardown
03-24 21:17:33.566  3258  3314 I jxcore-log: 
,03-24 21:17:33.687  3258  3314 I jxcore-log: # setup
03-24 21:17:33.687  3258  3314 I jxcore-log: 
,03-24 21:17:33.806  3258  3314 I jxcore-log: # 20. queues handled independently
03-24 21:17:33.806  3258  3314 I jxcore-log: 
,03-24 21:17:33.930  3258  3314 I jxcore-log: ok 74 all short operations completed before the long resolves
03-24 21:17:33.930  3258  3314 I jxcore-log: 
,03-24 21:17:33.944  3258  3314 I jxcore-log: # teardown
03-24 21:17:33.944  3258  3314 I jxcore-log: 
,03-24 21:17:34.104  3258  3314 I jxcore-log: # setup
03-24 21:17:34.104  3258  3314 I jxcore-log: 
,03-24 21:17:34.286  3258  3314 I jxcore-log: # 21. basic,
03-24 21:17:34.286  3258  3314 I jxcore-log: 
,03-24 21:17:34.451  3258  3314 I jxcore-log: ok 75 sane
03-24 21:17:34.451  3258  3314 I jxcore-log: 
,03-24 21:17:34.457  3258  3314 I jxcore-log: # teardown
03-24 21:17:34.457  3258  3314 I jxcore-log: 
,03-24 21:17:34.577  3258  3314 I jxcore-log: # setup
03-24 21:17:34.577  3258  3314 I jxcore-log: 
,03-24 21:17:34.726  3258  3314 I jxcore-log: # 22. another
03-24 21:17:34.726  3258  3314 I jxcore-log: 
,03-24 21:17:34.910  3258  3314 I jxcore-log: ok 76 sane
03-24 21:17:34.910  3258  3314 I jxcore-log: 
,03-24 21:17:34.917  3258  3314 I jxcore-log: # teardown,
03-24 21:17:34.917  3258  3314 I jxcore-log: 
,03-24 21:17:35.079  3258  3314 I jxcore-log: # setup,
03-24 21:17:35.079  3258  3314 I jxcore-log: 
,03-24 21:17:35.450  3258  3314 I jxcore-log: # 23. can pass data in setup,
03-24 21:17:35.450  3258  3314 I jxcore-log: 
,03-24 21:17:35.976  3258  3314 I jxcore-log: ok 77 test participant has uuid
03-24 21:17:35.976  3258  3314 I jxcore-log: 
,03-24 21:17:35.977  3258  3314 I jxcore-log: ok 78 participant data matches
03-24 21:17:35.977  3258  3314 I jxcore-log: ,
03-24 21:17:35.979  3258  3314 I jxcore-log: ok 79 test participant has uuid
03-24 21:17:35.979  3258  3314 I jxcore-log: 
03-24 21:17:35.980  3258  3314 I jxcore-log: ok 80 participant data matches
03-24 21:17:35.980  3258  3314 I jxcore-log: 
03-24 21:17:35.981  3258  3314 I jxcore-log: ok 81 test participant has uuid,
03-24 21:17:35.981  3258  3314 I jxcore-log: 
03-24 21:17:35.984  3258  3314 I jxcore-log: ok 82 participant data matches
03-24 21:17:35.984  3258  3314 I jxcore-log: 
03-24 21:17:35.987  3258  3314 I jxcore-log: # teardown
03-24 21:17:35.987  3258  3314 I jxcore-log: 
,03-24 21:17:36.086  3258  3314 I jxcore-log: # setup
03-24 21:17:36.086  3258  3314 I jxcore-log: 
,03-24 21:17:36.999  3258  3314 I jxcore-log: # 24. #startListeningForAdvertisements should fail if start not called
03-24 21:17:36.999  3258  3314 I jxcore-log: 
,03-24 21:17:37.146  3258  3314 I jxcore-log: ok 83 specific error should be returned
03-24 21:17:37.146  3258  3314 I jxcore-log: 
,03-24 21:17:37.152  3258  3314 I jxcore-log: # teardown
03-24 21:17:37.152  3258  3314 I jxcore-log: 
,03-24 21:17:37.304  3258  3314 I jxcore-log: ok 84 error should be null
03-24 21:17:37.304  3258  3314 I jxcore-log: 
,03-24 21:17:37.305  3258  3314 I jxcore-log: ok 85 error should be null
03-24 21:17:37.305  3258  3314 I jxcore-log: 
03-24 21:17:37.309  3258  3314 I jxcore-log: # setup
03-24 21:17:37.309  3258  3314 I jxcore-log: 
,03-24 21:17:37.403  3258  3314 I jxcore-log: # 25. #startUpdateAdvertisingAndListening should fail if start not called
03-24 21:17:37.403  3258  3314 I jxcore-log: 
,03-24 21:17:37.541  3258  3314 I jxcore-log: ok 86 specific error should be returned
03-24 21:17:37.541  3258  3314 I jxcore-log: 
,03-24 21:17:37.548  3258  3314 I jxcore-log: # teardown
03-24 21:17:37.548  3258  3314 I jxcore-log: 
,03-24 21:17:37.639  3258  3314 I jxcore-log: ok 87 error should be null
03-24 21:17:37.639  3258  3314 I jxcore-log: 
,03-24 21:17:37.641  3258  3314 I jxcore-log: ok 88 error should be null
03-24 21:17:37.641  3258  3314 I jxcore-log: 
,03-24 21:17:37.650  3258  3314 I jxcore-log: # setup
03-24 21:17:37.650  3258  3314 I jxcore-log: 
,03-24 21:17:37.761  3258  3314 I jxcore-log: # 26. should be able to call #stopListeningForAdvertisements many times,
03-24 21:17:37.761  3258  3314 I jxcore-log: 
,03-24 21:17:38.045  3258  3314 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 21:17:38.045  3258  3314 I jxcore-log: 
,03-24 21:17:38.046  3258  3314 I jxcore-log: DEBUG createNativeListener: listening 42933
03-24 21:17:38.046  3258  3314 I jxcore-log: 
,03-24 21:17:38.049  3258  3314 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 21:17:38.050  3258  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 21:17:38.050  3258  3314 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 21:17:38.054  3258  3314 I jxcore-log: ok 89 error should be null
03-24 21:17:38.054  3258  3314 I jxcore-log: 
03-24 21:17:38.054  3258  3314 I jxcore-log: ok 90 error should be null
03-24 21:17:38.054  3258  3314 I jxcore-log: 
,03-24 21:17:38.056  3258  3314 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 21:17:38.056  3258  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 21:17:38.056  3258  3314 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 21:17:38.058  3258  3314 I jxcore-log: ok 91 error should be null
03-24 21:17:38.058  3258  3314 I jxcore-log: 
,03-24 21:17:38.058  3258  3314 I jxcore-log: ok 92 error should be null
03-24 21:17:38.058  3258  3314 I jxcore-log: 
03-24 21:17:38.061  3258  3314 I jxcore-log: # teardown
03-24 21:17:38.061  3258  3314 I jxcore-log: 
,03-24 21:17:38.236  3258  3314 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 21:17:38.236  3258  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 21:17:38.236  3258  3314 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 21:17:38.241  3258  3314 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 21:17:38.241  3258  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 21:17:38.241  3258  3314 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 21:17:38.248  3258  3314 I jxcore-log: ok 93 error should be null,
03-24 21:17:38.248  3258  3314 I jxcore-log: 
03-24 21:17:38.248  3258  3314 I jxcore-log: ok 94 error should be null
03-24 21:17:38.248  3258  3314 I jxcore-log: 
,03-24 21:17:38.255  3258  3314 I jxcore-log: # setup,
03-24 21:17:38.255  3258  3314 I jxcore-log: 
,03-24 21:17:38.421  3258  3314 I jxcore-log: # 27. should be able to call #startListeningForAdvertisements many times,
03-24 21:17:38.421  3258  3314 I jxcore-log: 
,03-24 21:17:38.572  3258  3314 I jxcore-log: DEBUG createNativeListener: creating native server,
03-24 21:17:38.572  3258  3314 I jxcore-log: 
,03-24 21:17:38.575  3258  3314 I jxcore-log: DEBUG createNativeListener: listening 57960,
03-24 21:17:38.575  3258  3314 I jxcore-log: 
,03-24 21:17:38.587  3258  3314 I io.jxcore.node.ConnectionHelper: start: Port number: 0, start advertisements: false,
03-24 21:17:38.587  3258  3314 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 21:17:38.587  3258  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 21:17:38.587  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
03-24 21:17:38.587  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-24 21:17:38.587  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-24 21:17:38.597  3258  3314 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-24 21:17:38.597   820  1333 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 21:17:38.607  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-24 21:17:38.624  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 21:17:38.624  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-24 21:17:38.624  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 21:17:38.624  3258  3314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 21:17:38.633  2145  2210 D BtGatt.GattService: registerClient() - UUID=8d8046d4-92ce-48a6-9fff-7d6520a0641b,
,03-24 21:17:38.636  2145  2208 D BtGatt.GattService: onClientRegistered() - UUID=8d8046d4-92ce-48a6-9fff-7d6520a0641b, clientIf=5
,03-24 21:17:38.637  3258  3275 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-24 21:17:38.638  2145  2164 D BtGatt.GattService: start scan with filters
,03-24 21:17:38.640  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-24 21:17:38.641  2145  2223 D BtGatt.ScanManager: handling starting scan
03-24 21:17:38.641  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 21:17:38.641  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-24 21:17:38.641  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-24 21:17:38.642  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 21:17:38.642  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 21:17:38.642   820  1362 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 21:17:38.643  3258  3258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-24 21:17:38.645  2145  2223 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f37799e
,03-24 21:17:38.648  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 21:17:38.648  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-24 21:17:38.650  3258  3258 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 21:17:38.650  3258  3258 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-24 21:17:38.651  3258  3258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 21:17:38.651  3258  3314 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 21:17:38.655  2145  2208 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1,
03-24 21:17:38.655  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:17:38.658  2145  2208 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 21:17:38.658  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 21:17:38.659  2145  2223 D BtGatt.ScanManager: Starting BLE batch scan
03-24 21:17:38.659  2145  2223 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-24 21:17:38.660  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false},
03-24 21:17:38.660  3258  3314 I jxcore-log: 
03-24 21:17:38.661  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 21:17:38.661  3258  3314 I jxcore-log: 
03-24 21:17:38.662  2145  2208 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 21:17:38.662  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 21:17:38.664  3258  3314 I jxcore-log: ok 95 error should be null
03-24 21:17:38.664  3258  3314 I jxcore-log: 
,03-24 21:17:38.664  3258  3314 I jxcore-log: ok 96 error should be null
03-24 21:17:38.664  3258  3314 I jxcore-log: 
03-24 21:17:38.665  2145  2208 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 21:17:38.665  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 21:17:38.670  3258  3314 I io.jxcore.node.ConnectionHelper: start: Port number: 0, start advertisements: false
,03-24 21:17:38.670  3258  3314 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 21:17:38.670  3258  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 21:17:38.670  3258  3314 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 21:17:38.670  3258  3314 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 21:17:38.673  3258  3314 I jxcore-log: ok 97 error should be null
03-24 21:17:38.673  3258  3314 I jxcore-log: 
,03-24 21:17:38.673  3258  3314 I jxcore-log: ok 98 error should be null
03-24 21:17:38.673  3258  3314 I jxcore-log: 
03-24 21:17:38.680  3258  3314 I jxcore-log: # teardown
03-24 21:17:38.680  3258  3314 I jxcore-log: 
,03-24 21:17:38.964  3258  3314 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 21:17:38.964  3258  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
03-24 21:17:38.964  3258  3314 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,03-24 21:17:38.964  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-24 21:17:38.964  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-24 21:17:38.964  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 21:17:38.964  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 21:17:38.965  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-24 21:17:38.965  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-24 21:17:38.967  2145  2164 D BtGatt.GattService: stopScan() - queue size =1
,03-24 21:17:38.972  2145  2166 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-24 21:17:38.974  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
,03-24 21:17:38.974  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 21:17:38.974  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false,
03-24 21:17:38.975  2145  2208 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16,
03-24 21:17:38.975  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
03-24 21:17:38.975  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-24 21:17:38.975  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-24 21:17:38.975  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 21:17:38.977  2145  2223 D BtGatt.ScanManager: stopping BLe Batch
03-24 21:17:38.977  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 21:17:38.977  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,03-24 21:17:38.977  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-24 21:17:38.978  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-24 21:17:38.978  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 21:17:38.979  3258  3258 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 21:17:38.979  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-24 21:17:38.979  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-24 21:17:38.980  2145  2208 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 21:17:38.980  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:17:38.981  2145  2223 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 21:17:38.983  2145  2208 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 21:17:38.983  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 21:17:38.989  3258  3314 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-24 21:17:38.989  3258  3314 I jxcore-log: 
,03-24 21:17:38.995  3258  3258 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
03-24 21:17:38.996   820  2348 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 21:17:39.002  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
,03-24 21:17:39.003  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 21:17:39.003  3258  3258 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 21:17:39.006  3258  3258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-24 21:17:39.007  3258  3258 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 21:17:39.007  3258  3258 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 21:17:39.007  3258  3258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-24 21:17:39.009  3258  3314 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 21:17:39.009  3258  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 21:17:39.009  3258  3314 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 21:17:39.012  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
,03-24 21:17:39.012  3258  3314 I jxcore-log: 
03-24 21:17:39.013  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 21:17:39.013  3258  3314 I jxcore-log: 
,03-24 21:17:39.018  3258  3314 I jxcore-log: ok 99 error should be null
03-24 21:17:39.018  3258  3314 I jxcore-log: ,
03-24 21:17:39.018  3258  3314 I jxcore-log: ok 100 error should be null
03-24 21:17:39.018  3258  3314 I jxcore-log: ,
,03-24 21:17:39.026  3258  3314 I jxcore-log: # setup
,03-24 21:17:39.026  3258  3314 I jxcore-log: 
,03-24 21:17:39.165  3258  3314 I jxcore-log: # 28. should be able to call #startUpdateAdvertisingAndListening many times
03-24 21:17:39.165  3258  3314 I jxcore-log: 
,03-24 21:17:39.581  3258  3314 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 21:17:39.581  3258  3314 I jxcore-log: ,
03-24 21:17:39.583  3258  3314 I jxcore-log: DEBUG createNativeListener: listening 40459
03-24 21:17:39.583  3258  3314 I jxcore-log: 
,03-24 21:17:39.599  3258  3314 I io.jxcore.node.ConnectionHelper: start: Port number: 40459, start advertisements: true
,03-24 21:17:39.599  3258  3314 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 21:17:39.599  3258  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-24 21:17:39.600  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true,
,03-24 21:17:39.605  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser,
03-24 21:17:39.605  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-24 21:17:39.605  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 21:17:39.606  3258  3314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null],
,03-24 21:17:39.611  2145  2210 D BtGatt.GattService: registerClient() - UUID=40e14cf1-f7ad-4d20-8663-be00f4458cfc
,03-24 21:17:39.612  2145  2208 D BtGatt.GattService: onClientRegistered() - UUID=40e14cf1-f7ad-4d20-8663-be00f4458cfc, clientIf=5
,03-24 21:17:39.612  3258  3275 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 21:17:39.613  2145  2164 D BtGatt.GattService: start scan with filters
,03-24 21:17:39.615  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-24 21:17:39.615  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-24 21:17:39.615  2145  2223 D BtGatt.ScanManager: handling starting scan,
,03-24 21:17:39.615  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-24 21:17:39.616  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,03-24 21:17:39.616  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
,03-24 21:17:39.616  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 21:17:39.616  3258  3258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-24 21:17:39.616  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 21:17:39.617  3258  3314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
,03-24 21:17:39.618  2145  2208 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 21:17:39.618  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 21:17:39.620  2145  2208 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15,
03-24 21:17:39.620  3258  3314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 21:17:39.620  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 21:17:39.620  2145  2223 D BtGatt.ScanManager: Starting BLE batch scan
03-24 21:17:39.620  2145  2223 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 21:17:39.620  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false],
03-24 21:17:39.621  3258  3314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-24 21:17:39.623  2145  2208 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,03-24 21:17:39.623  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:17:39.625  2145  2208 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 21:17:39.625  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 21:17:39.630  2145  2166 D BtGatt.GattService: registerClient() - UUID=d1ad262e-b250-48c3-87da-902a69687725
,03-24 21:17:39.630  2145  2208 D BtGatt.GattService: onClientRegistered() - UUID=d1ad262e-b250-48c3-87da-902a69687725, clientIf=6,
03-24 21:17:39.631  3258  3274 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-24 21:17:39.635  2145  2221 D BtGatt.AdvertiseManager: message : 0
,03-24 21:17:39.641  2145  2221 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 21:17:39.645  2145  2208 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 21:17:39.648  2145  2208 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0,
,03-24 21:17:39.650  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING,
,03-24 21:17:39.651  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-24 21:17:39.652   820  1332 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 21:17:39.658  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-24 21:17:39.658  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 21:17:39.658  3258  3314 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,03-24 21:17:39.659  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-24 21:17:39.661  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-24 21:17:39.662  3258  3314 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,03-24 21:17:39.663  3258  3314 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,03-24 21:17:39.663  3258  3314 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-24 21:17:39.664  3258  3258 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything,
,03-24 21:17:39.664  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,03-24 21:17:39.664  3258  3258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-24 21:17:39.664  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,03-24 21:17:39.665  3258  3258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-24 21:17:39.665  3258  3258 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-24 21:17:39.665  3258  3258 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-24 21:17:39.665  3258  3258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 21:17:39.665  3258  3258 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,03-24 21:17:39.665  3258  3258 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 21:17:39.665  3258  3258 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,03-24 21:17:39.666  3258  3314 I io.jxcore.node.ConnectionHelper: start: OK
03-24 21:17:39.666  3258  3258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 21:17:39.668   820  1362 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
03-24 21:17:39.672  3258  3707 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-24 21:17:39.677  3258  3707 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-24 21:17:39.681  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 21:17:39.681  3258  3314 I jxcore-log: 
,03-24 21:17:39.683  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 21:17:39.683  3258  3314 I jxcore-log: 
,03-24 21:17:39.694  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-24 21:17:39.694  3258  3314 I jxcore-log: 
,03-24 21:17:39.697  3258  3314 I jxcore-log: ok 101 error should be null
03-24 21:17:39.697  3258  3314 I jxcore-log: 
,03-24 21:17:39.697  3258  3314 I jxcore-log: ok 102 error should be null
03-24 21:17:39.697  3258  3314 I jxcore-log: 
,03-24 21:17:39.707  3258  3314 I io.jxcore.node.ConnectionHelper: start: Port number: 40459, start advertisements: true
03-24 21:17:39.707  3258  3314 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-24 21:17:39.707  3258  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-24 21:17:39.707  3258  3314 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 21:17:39.707  3258  3314 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 21:17:39.718  3258  3314 I jxcore-log: ok 103 error should be null
03-24 21:17:39.718  3258  3314 I jxcore-log: 
,03-24 21:17:39.719  3258  3314 I jxcore-log: ok 104 error should be null
03-24 21:17:39.719  3258  3314 I jxcore-log: 
,03-24 21:17:39.727  3258  3314 I jxcore-log: # teardown
03-24 21:17:39.727  3258  3314 I jxcore-log: 
,03-24 21:17:40.130  2145  2145 D BtGatt.ScanManager: awakened up at time 241767
,03-24 21:17:40.132  2145  2223 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 21:17:40.142  2145  2208 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,03-24 21:17:40.142  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:17:40.142  2145  2208 D BtGatt.GattService: current time is 241779809958
03-24 21:17:40.143  2145  2208 D BtGatt.GattService: Batch record : [-122, -120, -116, -13, -89, 83, 1, -128, -79, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -63, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
,03-24 21:17:40.146  2145  2208 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,03-24 21:17:40.151  2145  2208 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
,03-24 21:17:40.161  3258  3258 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 1
,03-24 21:17:40.163  3258  3258 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> E0:DB:10:14:E2:C0], added - the peer count is 2
03-24 21:17:40.164  3258  3258 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
,03-24 21:17:40.165  3258  3258 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> E0:DB:10:14:E2:C0], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 
,03-24 21:17:40.176  3258  3314 I jxcore-log: DEBUG createPeerListener: createPeerListener
03-24 21:17:40.176  3258  3314 I jxcore-log: 
,03-24 21:17:40.185  3258  3314 I jxcore-log: DEBUG createPeerListener: pleaseConnect= false
03-24 21:17:40.185  3258  3314 I jxcore-log: 
,03-24 21:17:40.188  3258  3314 I jxcore-log: DEBUG createPeerListener: createPeerListener
03-24 21:17:40.188  3258  3314 I jxcore-log: 
,03-24 21:17:40.191  3258  3314 I jxcore-log: DEBUG createPeerListener: pleaseConnect= false
03-24 21:17:40.191  3258  3314 I jxcore-log: 
,03-24 21:17:41.156  2145  2145 D BtGatt.ScanManager: awakened up at time 242793
,03-24 21:17:41.158  2145  2223 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 21:17:41.164  2145  2208 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,03-24 21:17:41.164  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:17:41.164  2145  2208 D BtGatt.GattService: current time is 242801933603
03-24 21:17:41.165  2145  2208 D BtGatt.GattService: Batch record : [-122, -120, -116, -13, -89, 83, 1, -128, -77, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -63, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
,03-24 21:17:41.166  2145  2208 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,03-24 21:17:41.168  2145  2208 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
,03-24 21:17:41.170  3258  3258 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> E0:DB:10:14:E2:C0] updated - the peer count is 2
,03-24 21:17:41.171  3258  3258 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
,03-24 21:17:41.302  3258  3314 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-24 21:17:41.302  3258  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
,03-24 21:17:41.302  3258  3314 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-24 21:17:41.302  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-24 21:17:41.303  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-24 21:17:41.304  3258  3314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-24 21:17:41.304  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
03-24 21:17:41.304  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,03-24 21:17:41.304  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 21:17:41.304  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,03-24 21:17:41.304  3258  3707 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-24 21:17:41.304  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser,
03-24 21:17:41.304  3258  3707 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,03-24 21:17:41.304  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-24 21:17:41.304  3258  3707 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,03-24 21:17:41.307  2145  2166 D BtGatt.GattService: stopScan() - queue size =1
03-24 21:17:41.309  2145  2164 D BtGatt.GattService: unregisterClient() - clientIf=5
03-24 21:17:41.309  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-24 21:17:41.309  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 21:17:41.309  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false,
03-24 21:17:41.309  2145  2208 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16,
03-24 21:17:41.309  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-24 21:17:41.310  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-24 21:17:41.310  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:17:41.310  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 21:17:41.310  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-24 21:17:41.310  2145  2223 D BtGatt.ScanManager: stopping BLe Batch
03-24 21:17:41.312  2145  2221 D BtGatt.AdvertiseManager: message : 1
03-24 21:17:41.313  2145  2208 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 21:17:41.313  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:17:41.313  2145  2223 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 21:17:41.314  2145  2221 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-24 21:17:41.317  2145  2208 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-24 21:17:41.317  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:17:41.317  2145  2208 D BtGatt.GattService: current time is 242954667041
03-24 21:17:41.318  2145  2208 D BtGatt.GattService: Batch record : [-122, -120, -116, -13, -89, 83, 1, -128, -77, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -63, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-24 21:17:41.319  2145  2208 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 21:17:41.320  2145  2208 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-24 21:17:41.320  2145  2208 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 21:17:41.321  2145  2208 D BtGatt.GattService: Client app is not null!
03-24 21:17:41.322  2145  2164 D BtGatt.GattService: unregisterClient() - clientIf=6
03-24 21:17:41.322  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 21:17:41.323  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-24 21:17:41.323  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-24 21:17:41.323  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-24 21:17:41.323  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-24 21:17:41.323  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 21:17:41.324  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 21:17:41.324  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-24 21:17:41.325  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,03-24 21:17:41.326  3258  3314 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-24 21:17:41.326  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 21:17:41.326  3258  3258 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 21:17:41.326  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 21:17:41.326  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-24 21:17:41.335  3258  3258 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
03-24 21:17:41.335   820  1362 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 21:17:41.340  3258  3314 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-24 21:17:41.340  3258  3314 I jxcore-log: ,
,03-24 21:17:41.346  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-24 21:17:41.347  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 21:17:41.347  3258  3258 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 21:17:41.352  3258  3258 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-24 21:17:41.352  3258  3258 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-24 21:17:41.352  3258  3258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 21:17:41.352  3258  3258 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
03-24 21:17:41.352  3258  3258 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-24 21:17:41.353  3258  3258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 21:17:41.353  3258  3258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 21:17:41.353  3258  3258 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-24 21:17:41.354  3258  3314 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 21:17:41.354  3258  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 21:17:41.354  3258  3314 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 21:17:41.356  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-24 21:17:41.356  3258  3314 I jxcore-log: 
,03-24 21:17:41.357  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 21:17:41.357  3258  3314 I jxcore-log: 
03-24 21:17:41.357  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 21:17:41.357  3258  3314 I jxcore-log: ,
03-24 21:17:41.364  3258  3314 I jxcore-log: ok 105 error should be null
03-24 21:17:41.364  3258  3314 I jxcore-log: 
03-24 21:17:41.364  3258  3314 I jxcore-log: ok 106 error should be null
03-24 21:17:41.364  3258  3314 I jxcore-log: 
,03-24 21:17:41.370  3258  3314 I jxcore-log: # setup
03-24 21:17:41.370  3258  3314 I jxcore-log: 
,03-24 21:17:42.040  3258  3314 I jxcore-log: # 29. should be able to call #stopAdvertisingAndListening many times
03-24 21:17:42.040  3258  3314 I jxcore-log: 
,03-24 21:17:42.269  3258  3314 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 21:17:42.269  3258  3314 I jxcore-log: 
,03-24 21:17:42.271  3258  3314 I jxcore-log: DEBUG createNativeListener: listening 52760
03-24 21:17:42.271  3258  3314 I jxcore-log: 
,03-24 21:17:42.276  3258  3314 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections,
03-24 21:17:42.276  3258  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 21:17:42.276  3258  3314 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 21:17:42.279  3258  3314 I jxcore-log: ok 107 error should be null
03-24 21:17:42.279  3258  3314 I jxcore-log: 
,03-24 21:17:42.280  3258  3314 I jxcore-log: ok 108 error should be null
03-24 21:17:42.280  3258  3314 I jxcore-log: 
03-24 21:17:42.282  3258  3314 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 21:17:42.282  3258  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 21:17:42.282  3258  3314 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 21:17:42.285  3258  3314 I jxcore-log: ok 109 error should be null
03-24 21:17:42.285  3258  3314 I jxcore-log: 
03-24 21:17:42.285  3258  3314 I jxcore-log: ok 110 error should be null
03-24 21:17:42.285  3258  3314 I jxcore-log: 
03-24 21:17:42.291  3258  3314 I jxcore-log: # teardown
03-24 21:17:42.291  3258  3314 I jxcore-log: 
,03-24 21:17:44.075  3258  3314 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-24 21:17:44.075  3258  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-24 21:17:44.075  3258  3314 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 21:17:44.077  3258  3314 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 21:17:44.077  3258  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 21:17:44.077  3258  3314 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 21:17:44.082  3258  3314 I jxcore-log: ok 111 error should be null
03-24 21:17:44.082  3258  3314 I jxcore-log: 
,03-24 21:17:44.083  3258  3314 I jxcore-log: ok 112 error should be null
03-24 21:17:44.083  3258  3314 I jxcore-log: 
,03-24 21:17:44.088  3258  3314 I jxcore-log: # setup
03-24 21:17:44.088  3258  3314 I jxcore-log: 
,03-24 21:17:44.192  3258  3314 I jxcore-log: # 30. #start should fail if called twice in a row
03-24 21:17:44.192  3258  3314 I jxcore-log: 
,03-24 21:17:45.002  3258  3314 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 21:17:45.002  3258  3314 I jxcore-log: 
,03-24 21:17:45.005  3258  3314 I jxcore-log: DEBUG createNativeListener: listening 58134
03-24 21:17:45.005  3258  3314 I jxcore-log: 
,03-24 21:17:45.006  3258  3314 I jxcore-log: ok 113 first call should succeed
03-24 21:17:45.006  3258  3314 I jxcore-log: 
,03-24 21:17:45.007  3258  3314 I jxcore-log: ok 114 first call should succeed
03-24 21:17:45.007  3258  3314 I jxcore-log: 
,03-24 21:17:45.010  3258  3314 I jxcore-log: ok 115 specific error should be returned
03-24 21:17:45.010  3258  3314 I jxcore-log: 
,03-24 21:17:45.012  3258  3314 I jxcore-log: # teardown
03-24 21:17:45.012  3258  3314 I jxcore-log: 
,03-24 21:17:45.130  3258  3314 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 21:17:45.130  3258  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-24 21:17:45.130  3258  3314 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 21:17:45.134  3258  3314 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 21:17:45.134  3258  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 21:17:45.134  3258  3314 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 21:17:45.139  3258  3314 I jxcore-log: ok 116 error should be null
03-24 21:17:45.139  3258  3314 I jxcore-log: 
,03-24 21:17:45.140  3258  3314 I jxcore-log: ok 117 error should be null
03-24 21:17:45.140  3258  3314 I jxcore-log: 
,03-24 21:17:45.145  3258  3314 I jxcore-log: # setup
03-24 21:17:45.145  3258  3314 I jxcore-log: 
,03-24 21:17:45.652  2145  2211 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 21:17:46.642  3258  3314 I jxcore-log: # 31. does not emit duplicate discoveryAdvertisingStateUpdate
03-24 21:17:46.642  3258  3314 I jxcore-log: 
,03-24 21:17:46.762  3258  3314 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 21:17:46.762  3258  3314 I jxcore-log: 
,03-24 21:17:46.764  3258  3314 I jxcore-log: DEBUG createNativeListener: listening 38877
03-24 21:17:46.764  3258  3314 I jxcore-log: 
,03-24 21:17:46.773  3258  3314 I io.jxcore.node.ConnectionHelper: start: Port number: 40459, start advertisements: false
,03-24 21:17:46.773  3258  3314 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 21:17:46.774  3258  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 21:17:46.774  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-24 21:17:46.778  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-24 21:17:46.778  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 21:17:46.778  3258  3314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 21:17:46.783  2145  2210 D BtGatt.GattService: registerClient() - UUID=9ac8d59b-bb40-4d22-86b5-660021683e43
,03-24 21:17:46.783  2145  2208 D BtGatt.GattService: onClientRegistered() - UUID=9ac8d59b-bb40-4d22-86b5-660021683e43, clientIf=5
03-24 21:17:46.784  3258  3274 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 21:17:46.785  2145  2166 D BtGatt.GattService: start scan with filters
,03-24 21:17:46.786  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 21:17:46.786  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-24 21:17:46.786  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-24 21:17:46.786  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,03-24 21:17:46.786  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 21:17:46.786  3258  3258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 21:17:46.787  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 21:17:46.787  2145  2223 D BtGatt.ScanManager: handling starting scan
03-24 21:17:46.787   820  1362 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 21:17:46.790  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 21:17:46.790  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 21:17:46.791  3258  3258 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,03-24 21:17:46.791  3258  3258 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 21:17:46.791  3258  3258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 21:17:46.791  3258  3314 I io.jxcore.node.ConnectionHelper: start: OK
03-24 21:17:46.796  2145  2208 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 21:17:46.796  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 21:17:46.798  2145  2208 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 21:17:46.798  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:17:46.798  2145  2223 D BtGatt.ScanManager: Starting BLE batch scan
03-24 21:17:46.798  2145  2223 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-24 21:17:46.801  2145  2208 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 21:17:46.801  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:17:46.803  2145  2208 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 21:17:46.803  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 21:17:46.807  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 21:17:46.807  3258  3314 I jxcore-log: 
,03-24 21:17:46.809  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 21:17:46.809  3258  3314 I jxcore-log: 
,03-24 21:17:46.824  3258  3314 I io.jxcore.node.ConnectionHelper: start: Port number: 38877, start advertisements: true
03-24 21:17:46.824  3258  3314 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-24 21:17:46.824  3258  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-24 21:17:46.824  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-24 21:17:46.827  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
03-24 21:17:46.827  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
03-24 21:17:46.827  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 21:17:46.827  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 21:17:46.827  3258  3314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 21:17:46.827  3258  3314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 21:17:46.827  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 21:17:46.827  3258  3314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-24 21:17:46.831  2145  2164 D BtGatt.GattService: registerClient() - UUID=9b1d95a4-4ff4-44af-83da-c554b53a602e
03-24 21:17:46.831  2145  2208 D BtGatt.GattService: onClientRegistered() - UUID=9b1d95a4-4ff4-44af-83da-c554b53a602e, clientIf=6
,03-24 21:17:46.832  3258  3275 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-24 21:17:46.834  2145  2221 D BtGatt.AdvertiseManager: message : 0
,03-24 21:17:46.838  2145  2221 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 21:17:46.842  2145  2208 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 21:17:46.845  2145  2208 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 21:17:46.846  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-24 21:17:46.846  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 21:17:46.846  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 21:17:46.846  3258  3258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-24 21:17:46.846  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-24 21:17:46.846  3258  3258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-24 21:17:46.846  3258  3258 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-24 21:17:46.846   820  2348 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 21:17:46.849  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 21:17:46.849  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-24 21:17:46.849  3258  3314 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-24 21:17:46.849  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 21:17:46.849  3258  3258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-24 21:17:46.851  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-24 21:17:46.851  3258  3314 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-24 21:17:46.851  3258  3314 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-24 21:17:46.851  3258  3314 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-24 21:17:46.851  3258  3314 I io.jxcore.node.ConnectionHelper: start: OK
03-24 21:17:46.851  3258  3258 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-24 21:17:46.851  3258  3258 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-24 21:17:46.851  3258  3258 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-24 21:17:46.854   820  1113 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 21:17:46.856  3258  3710 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-24 21:17:46.858  3258  3710 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-24 21:17:46.862  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-24 21:17:46.862  3258  3314 I jxcore-log: 
,03-24 21:17:46.871  3258  3314 I jxcore-log: ok 118 called only once
03-24 21:17:46.871  3258  3314 I jxcore-log: 
,03-24 21:17:46.871  3258  3314 I jxcore-log: ok 119 discovery state matches
03-24 21:17:46.871  3258  3314 I jxcore-log: 
03-24 21:17:46.872  3258  3314 I jxcore-log: ok 120 advertising state matches
03-24 21:17:46.872  3258  3314 I jxcore-log: 
,03-24 21:17:46.881  3258  3314 I jxcore-log: # teardown
03-24 21:17:46.881  3258  3314 I jxcore-log: 
,03-24 21:17:47.815  2145  2145 D BtGatt.ScanManager: awakened up at time 249452
,03-24 21:17:47.816  2145  2223 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 21:17:47.823  2145  2208 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-24 21:17:47.823  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:17:47.823  2145  2208 D BtGatt.GattService: current time is 249460585736
03-24 21:17:47.823  2145  2208 D BtGatt.GattService: Batch record : [-83, -95, -3, 38, -73, 99, 1, -128, -79, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -63, 3, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-24 21:17:47.824  2145  2208 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 21:17:47.825  2145  2208 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
,03-24 21:17:47.827  3258  3258 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> E0:DB:10:14:E2:C0], added - the peer count is 1
03-24 21:17:47.827  3258  3258 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 2
03-24 21:17:47.828  3258  3258 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> E0:DB:10:14:E2:C0], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 
,03-24 21:17:47.828  3258  3258 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
,03-24 21:17:47.842  3258  3314 I jxcore-log: DEBUG createPeerListener: createPeerListener
03-24 21:17:47.842  3258  3314 I jxcore-log: 
,03-24 21:17:47.850  3258  3314 I jxcore-log: DEBUG createPeerListener: pleaseConnect= false
03-24 21:17:47.850  3258  3314 I jxcore-log: 
,03-24 21:17:47.862  3258  3314 I jxcore-log: DEBUG createPeerListener: createPeerListener
03-24 21:17:47.862  3258  3314 I jxcore-log: 
,03-24 21:17:47.869  3258  3314 I jxcore-log: DEBUG createPeerListener: pleaseConnect= false
03-24 21:17:47.869  3258  3314 I jxcore-log: 
,03-24 21:17:48.116  3258  3314 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-24 21:17:48.116  3258  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-24 21:17:48.116  3258  3314 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-24 21:17:48.116  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...,
03-24 21:17:48.116  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-24 21:17:48.117  3258  3314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-24 21:17:48.117  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-24 21:17:48.117  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-24 21:17:48.117  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 21:17:48.117  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 21:17:48.117  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-24 21:17:48.117  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-24 21:17:48.118  3258  3710 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-24 21:17:48.118  3258  3710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,03-24 21:17:48.118  3258  3710 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-24 21:17:48.119  2145  2166 D BtGatt.GattService: stopScan() - queue size =1
03-24 21:17:48.120  2145  2164 D BtGatt.GattService: unregisterClient() - clientIf=5
03-24 21:17:48.121  2145  2208 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 21:17:48.121  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 21:17:48.121  2145  2223 D BtGatt.ScanManager: stopping BLe Batch
03-24 21:17:48.122  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 21:17:48.122  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 21:17:48.122  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-24 21:17:48.122  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
,03-24 21:17:48.122  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-24 21:17:48.122  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 21:17:48.122  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,03-24 21:17:48.124  2145  2221 D BtGatt.AdvertiseManager: message : 1
03-24 21:17:48.125  2145  2208 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 21:17:48.125  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:17:48.126  2145  2223 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 21:17:48.126  2145  2221 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-24 21:17:48.129  2145  2208 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-24 21:17:48.129  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:17:48.129  2145  2208 D BtGatt.GattService: current time is 249766359017
03-24 21:17:48.129  2145  2208 D BtGatt.GattService: Batch record : [-83, -95, -3, 38, -73, 99, 1, -128, -61, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -47, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
,03-24 21:17:48.129  2145  2208 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 21:17:48.129  2145  2208 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
,03-24 21:17:48.134  2145  2208 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,03-24 21:17:48.135  2145  2208 D BtGatt.GattService: Client app is not null!
03-24 21:17:48.136  2145  2164 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-24 21:17:48.137  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-24 21:17:48.137  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-24 21:17:48.137  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-24 21:17:48.137  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-24 21:17:48.137  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-24 21:17:48.137  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 21:17:48.137  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped,
,03-24 21:17:48.137  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-24 21:17:48.138  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-24 21:17:48.138  3258  3314 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-24 21:17:48.138  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 21:17:48.138  3258  3258 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 21:17:48.138  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-24 21:17:48.138  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-24 21:17:48.148  3258  3258 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-24 21:17:48.149   820  3100 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 21:17:48.151  3258  3314 I jxcore-log: INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
03-24 21:17:48.151  3258  3314 I jxcore-log: 
,03-24 21:17:48.152  3258  3314 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-24 21:17:48.152  3258  3314 I jxcore-log: 
,03-24 21:17:48.154  3258  3314 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-24 21:17:48.154  3258  3314 I jxcore-log: ,
03-24 21:17:48.158  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
,03-24 21:17:48.163  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 21:17:48.163  3258  3258 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
,03-24 21:17:48.168  3258  3258 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-24 21:17:48.169  3258  3258 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-24 21:17:48.169  3258  3258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-24 21:17:48.169  3258  3258 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 21:17:48.169  3258  3258 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 21:17:48.169  3258  3258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 21:17:48.169  3258  3258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 21:17:48.169  3258  3258 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-24 21:17:48.170  3258  3314 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 21:17:48.171  3258  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 21:17:48.171  3258  3314 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 21:17:48.172  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-24 21:17:48.172  3258  3314 I jxcore-log: 
,03-24 21:17:48.173  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 21:17:48.173  3258  3314 I jxcore-log: 
,03-24 21:17:48.174  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 21:17:48.174  3258  3314 I jxcore-log: 
03-24 21:17:48.179  3258  3314 I jxcore-log: ok 121 error should be null
03-24 21:17:48.179  3258  3314 I jxcore-log: 
03-24 21:17:48.179  3258  3314 I jxcore-log: ok 122 error should be null
03-24 21:17:48.179  3258  3314 I jxcore-log: 
,03-24 21:17:48.186  3258  3314 I jxcore-log: # setup
03-24 21:17:48.186  3258  3314 I jxcore-log: 
,03-24 21:17:48.334  3258  3314 I jxcore-log: # 32. does not send duplicate availability changes
03-24 21:17:48.334  3258  3314 I jxcore-log: 
,03-24 21:17:48.575  3258  3314 I jxcore-log: ok 123 should be called once
03-24 21:17:48.575  3258  3314 I jxcore-log: 
,03-24 21:17:48.576  3258  3314 I jxcore-log: ok 124 should not have been called more than once
03-24 21:17:48.576  3258  3314 I jxcore-log: 
,03-24 21:17:48.578  3258  3314 I jxcore-log: # teardown
03-24 21:17:48.578  3258  3314 I jxcore-log: 
,03-24 21:17:48.743  3258  3314 I jxcore-log: ok 125 error should be null
03-24 21:17:48.743  3258  3314 I jxcore-log: 
,03-24 21:17:48.745  3258  3314 I jxcore-log: ok 126 error should be null
03-24 21:17:48.745  3258  3314 I jxcore-log: 
03-24 21:17:48.751  3258  3314 I jxcore-log: # setup
03-24 21:17:48.751  3258  3314 I jxcore-log: 
,03-24 21:17:48.887  3258  3314 I jxcore-log: # 33. can get the network status
03-24 21:17:48.887  3258  3314 I jxcore-log: 
,03-24 21:17:49.051  3258  3314 I jxcore-log: ok 127 network status should have certain non-empty properties
03-24 21:17:49.051  3258  3314 I jxcore-log: 
,03-24 21:17:49.055  3258  3314 I jxcore-log: # teardown
03-24 21:17:49.055  3258  3314 I jxcore-log: 
,03-24 21:17:49.174  3258  3314 I jxcore-log: ok 128 error should be null
03-24 21:17:49.174  3258  3314 I jxcore-log: 
,03-24 21:17:49.174  3258  3314 I jxcore-log: ok 129 error should be null
03-24 21:17:49.174  3258  3314 I jxcore-log: 
,03-24 21:17:49.181  3258  3314 I jxcore-log: # setup
03-24 21:17:49.181  3258  3314 I jxcore-log: 
,03-24 21:17:49.308  3258  3314 I jxcore-log: # 34. wifi peer is marked unavailable if announcements stop
03-24 21:17:49.308  3258  3314 I jxcore-log: 
,03-24 21:17:49.468  3258  3314 I jxcore-log: ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined
03-24 21:17:49.468  3258  3314 I jxcore-log: 
,03-24 21:17:49.494  3258  3314 I jxcore-log: ok 130 host address should match
03-24 21:17:49.494  3258  3314 I jxcore-log: 
,03-24 21:17:49.494  3258  3314 I jxcore-log: ok 131 port should match
03-24 21:17:49.494  3258  3314 I jxcore-log: 
,03-24 21:17:51.473  3258  3314 I jxcore-log: ok 132 host address should be null
03-24 21:17:51.473  3258  3314 I jxcore-log: 
,03-24 21:17:51.474  3258  3314 I jxcore-log: ok 133 port should should be null
03-24 21:17:51.474  3258  3314 I jxcore-log: 
,03-24 21:17:51.496  3258  3314 I jxcore-log: # teardown
03-24 21:17:51.496  3258  3314 I jxcore-log: 
,03-24 21:17:51.675  3258  3314 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-24 21:17:51.675  3258  3314 I jxcore-log: 
,03-24 21:17:51.677  3258  3314 I jxcore-log: ok 134 error should be null
03-24 21:17:51.677  3258  3314 I jxcore-log: 
03-24 21:17:51.677  3258  3314 I jxcore-log: ok 135 error should be null
03-24 21:17:51.677  3258  3314 I jxcore-log: 
,03-24 21:17:51.679  3258  3314 I jxcore-log: # setup
03-24 21:17:51.679  3258  3314 I jxcore-log: 
,03-24 21:17:51.838  3258  3314 I jxcore-log: # 35. Can call start/stopListeningForAdvertisements
,03-24 21:17:51.838  3258  3314 I jxcore-log: 
,03-24 21:17:52.202  3258  3314 I io.jxcore.node.ConnectionHelper: start: Port number: 38877, start advertisements: false
,03-24 21:17:52.202  3258  3314 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 21:17:52.203  3258  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 21:17:52.203  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-24 21:17:52.211  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-24 21:17:52.212  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-24 21:17:52.212  3258  3314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 21:17:52.221  2145  2166 D BtGatt.GattService: registerClient() - UUID=4e0e639d-b463-4cee-9da4-e311a9d7c0ba,
03-24 21:17:52.222  2145  2208 D BtGatt.GattService: onClientRegistered() - UUID=4e0e639d-b463-4cee-9da4-e311a9d7c0ba, clientIf=5
03-24 21:17:52.223  3258  3274 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 21:17:52.224  2145  2210 D BtGatt.GattService: start scan with filters
,03-24 21:17:52.226  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
03-24 21:17:52.226  2145  2223 D BtGatt.ScanManager: handling starting scan
,03-24 21:17:52.226  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 21:17:52.227  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-24 21:17:52.228  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-24 21:17:52.228  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 21:17:52.228  3258  3258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-24 21:17:52.229  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 21:17:52.230   820  1333 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 21:17:52.240  2145  2208 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,03-24 21:17:52.241  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:17:52.241  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 21:17:52.241  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-24 21:17:52.241  3258  3258 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 21:17:52.242  3258  3258 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 21:17:52.243  3258  3258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-24 21:17:52.244  2145  2208 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15,
03-24 21:17:52.244  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:17:52.244  3258  3314 I io.jxcore.node.ConnectionHelper: start: OK
03-24 21:17:52.244  2145  2223 D BtGatt.ScanManager: Starting BLE batch scan
03-24 21:17:52.244  2145  2223 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 21:17:52.248  2145  2208 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0,
03-24 21:17:52.249  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 21:17:52.251  2145  2208 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 21:17:52.251  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 21:17:52.255  3258  3314 I jxcore-log: ok 136 Can call startListeningForAdvertisements without error
03-24 21:17:52.255  3258  3314 I jxcore-log: 
,03-24 21:17:52.256  3258  3314 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 21:17:52.256  3258  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 21:17:52.256  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,03-24 21:17:52.256  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-24 21:17:52.258  2145  2210 D BtGatt.GattService: stopScan() - queue size =1
,03-24 21:17:52.259  2145  2164 D BtGatt.GattService: unregisterClient() - clientIf=5
03-24 21:17:52.259  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-24 21:17:52.259  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 21:17:52.259  2145  2208 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 21:17:52.259  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-24 21:17:52.259  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:17:52.259  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,03-24 21:17:52.259  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,03-24 21:17:52.259  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 21:17:52.260  2145  2223 D BtGatt.ScanManager: stopping BLe Batch
03-24 21:17:52.260  3258  3258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-24 21:17:52.260  3258  3258 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 21:17:52.260  3258  3258 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 21:17:52.262  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 21:17:52.262  3258  3314 I jxcore-log: 
03-24 21:17:52.262  2145  2208 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 21:17:52.262  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:17:52.263  2145  2223 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 21:17:52.264  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 21:17:52.264  3258  3314 I jxcore-log: ,
03-24 21:17:52.264  2145  2208 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 21:17:52.264  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:17:52.266  3258  3314 I jxcore-log: ok 137 Can call stopListeningForAdvertisements without error
03-24 21:17:52.266  3258  3314 I jxcore-log: 
03-24 21:17:52.271  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 21:17:52.271  3258  3314 I jxcore-log: 
03-24 21:17:52.274  3258  3314 I jxcore-log: # teardown
03-24 21:17:52.274  3258  3314 I jxcore-log: 
,03-24 21:17:52.458  3258  3314 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 21:17:52.458  3258  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-24 21:17:52.458  3258  3314 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 21:17:52.465  3258  3314 I jxcore-log: ok 138 Should be able to call stopListeningForAdvertisments in teardown
03-24 21:17:52.465  3258  3314 I jxcore-log: 
,03-24 21:17:52.466  3258  3314 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-24 21:17:52.467  3258  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-24 21:17:52.467  3258  3314 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
03-24 21:17:52.467  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-24 21:17:52.467  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-24 21:17:52.467  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,03-24 21:17:52.467  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 21:17:52.468  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-24 21:17:52.471  3258  3314 D BluetoothLeScanner: could not find callback wrapper
,03-24 21:17:52.471  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-24 21:17:52.473  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-24 21:17:52.474  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 21:17:52.474  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-24 21:17:52.474  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-24 21:17:52.474  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,03-24 21:17:52.475  3258  3258 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 21:17:52.475  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 21:17:52.475  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-24 21:17:52.482  3258  3258 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
03-24 21:17:52.483   820  1332 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 21:17:52.490  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
03-24 21:17:52.491  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 21:17:52.491  3258  3258 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 21:17:52.496  3258  3258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false,
03-24 21:17:52.496  3258  3258 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 21:17:52.496  3258  3258 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-24 21:17:52.499  3258  3314 I jxcore-log: ok 139 Should be able to call stopAdvertisingAndListening in teardown
03-24 21:17:52.499  3258  3314 I jxcore-log: 
,03-24 21:17:52.513  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 21:17:52.513  3258  3314 I jxcore-log: 
,03-24 21:17:52.516  3258  3314 I jxcore-log: # setup
03-24 21:17:52.516  3258  3314 I jxcore-log: 
,03-24 21:17:52.885  3258  3314 I jxcore-log: # 36. Calling startListeningForAdvertisements twice is NOT an error
03-24 21:17:52.885  3258  3314 I jxcore-log: 
,03-24 21:17:53.108  3258  3314 I io.jxcore.node.ConnectionHelper: start: Port number: 38877, start advertisements: false
03-24 21:17:53.108  3258  3314 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-24 21:17:53.108  3258  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 21:17:53.108  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-24 21:17:53.117  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 21:17:53.117  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-24 21:17:53.117  3258  3314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 21:17:53.126  2145  2210 D BtGatt.GattService: registerClient() - UUID=405bebab-b65f-47ac-b642-d31c40021c20
,03-24 21:17:53.127  2145  2208 D BtGatt.GattService: onClientRegistered() - UUID=405bebab-b65f-47ac-b642-d31c40021c20, clientIf=5
03-24 21:17:53.128  3258  3274 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 21:17:53.129  2145  2164 D BtGatt.GattService: start scan with filters
,03-24 21:17:53.131  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-24 21:17:53.131  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 21:17:53.132  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-24 21:17:53.132  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,03-24 21:17:53.132  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 21:17:53.132  2145  2223 D BtGatt.ScanManager: handling starting scan
03-24 21:17:53.133  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 21:17:53.133  3258  3258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-24 21:17:53.134   820  1362 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
03-24 21:17:53.137  2145  2208 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 21:17:53.137  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:17:53.139  2145  2208 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 21:17:53.139  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 21:17:53.140  2145  2223 D BtGatt.ScanManager: Starting BLE batch scan
03-24 21:17:53.140  2145  2223 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 21:17:53.144  2145  2208 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 21:17:53.144  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:17:53.146  2145  2208 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 21:17:53.146  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 21:17:53.147  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-24 21:17:53.147  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 21:17:53.148  3258  3314 I io.jxcore.node.ConnectionHelper: start: OK
03-24 21:17:53.148  3258  3258 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 21:17:53.148  3258  3258 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-24 21:17:53.149  3258  3258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 21:17:53.154  3258  3314 I jxcore-log: ok 140 Can call startListeningForAdvertisements without error
03-24 21:17:53.154  3258  3314 I jxcore-log: 
,03-24 21:17:53.159  3258  3314 I io.jxcore.node.ConnectionHelper: start: Port number: 38877, start advertisements: false
,03-24 21:17:53.159  3258  3314 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 21:17:53.159  3258  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 21:17:53.159  3258  3314 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 21:17:53.159  3258  3314 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 21:17:53.160  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false},
03-24 21:17:53.160  3258  3314 I jxcore-log: 
03-24 21:17:53.161  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 21:17:53.161  3258  3314 I jxcore-log: 
,03-24 21:17:53.163  3258  3314 I jxcore-log: ok 141 Can call startListeningForAdvertisements twice without error,
03-24 21:17:53.163  3258  3314 I jxcore-log: 
03-24 21:17:53.169  3258  3314 I jxcore-log: # teardown
03-24 21:17:53.169  3258  3314 I jxcore-log: 
,03-24 21:17:53.348  3258  3314 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 21:17:53.349  3258  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 21:17:53.349  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-24 21:17:53.349  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-24 21:17:53.353  2145  2166 D BtGatt.GattService: stopScan() - queue size =1
03-24 21:17:53.354  2145  2210 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-24 21:17:53.355  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 21:17:53.355  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 21:17:53.355  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-24 21:17:53.355  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-24 21:17:53.355  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-24 21:17:53.356  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 21:17:53.356  3258  3258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 21:17:53.356  3258  3258 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 21:17:53.356  3258  3258 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-24 21:17:53.360  3258  3314 I jxcore-log: ok 142 Should be able to call stopListeningForAdvertisments in teardown
03-24 21:17:53.360  3258  3314 I jxcore-log: 
,03-24 21:17:53.360  3258  3314 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-24 21:17:53.360  3258  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 21:17:53.360  3258  3314 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
03-24 21:17:53.360  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-24 21:17:53.360  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-24 21:17:53.361  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 21:17:53.361  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 21:17:53.361  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-24 21:17:53.362  2145  2208 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,03-24 21:17:53.362  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:17:53.362  2145  2223 D BtGatt.ScanManager: stopping BLe Batch
,03-24 21:17:53.363  3258  3314 D BluetoothLeScanner: could not find callback wrapper
03-24 21:17:53.363  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-24 21:17:53.364  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 21:17:53.364  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 21:17:53.365  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-24 21:17:53.365  2145  2208 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 21:17:53.365  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 21:17:53.365  2145  2223 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 21:17:53.365  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-24 21:17:53.366  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 21:17:53.366  3258  3258 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 21:17:53.366  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-24 21:17:53.366  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-24 21:17:53.367  2145  2208 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 21:17:53.368  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:17:53.372  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 21:17:53.372  3258  3314 I jxcore-log: 
,03-24 21:17:53.373  3258  3258 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-24 21:17:53.374   820  1375 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 21:17:53.380  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-24 21:17:53.381  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-24 21:17:53.381  3258  3258 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
,03-24 21:17:53.384  3258  3258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false,
,03-24 21:17:53.384  3258  3258 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
,03-24 21:17:53.385  3258  3258 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-24 21:17:53.388  3258  3314 I jxcore-log: ok 143 Should be able to call stopAdvertisingAndListening in teardown
03-24 21:17:53.388  3258  3314 I jxcore-log: 
,03-24 21:17:53.402  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false},
03-24 21:17:53.402  3258  3314 I jxcore-log: 
,03-24 21:17:53.404  3258  3314 I jxcore-log: # setup,
03-24 21:17:53.404  3258  3314 I jxcore-log: 
,03-24 21:17:53.888  3258  3314 I jxcore-log: # 37. Can call start/stopUpdateAdvertisingAndListening,
03-24 21:17:53.888  3258  3314 I jxcore-log: 
,03-24 21:17:54.113  3258  3314 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: true
03-24 21:17:54.113  3258  3314 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 21:17:54.113  3258  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,03-24 21:17:54.114  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-24 21:17:54.122  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-24 21:17:54.122  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 21:17:54.123  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 21:17:54.123  3258  3314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 21:17:54.132  2145  2166 D BtGatt.GattService: registerClient() - UUID=3c9720be-043d-4074-902d-dbcb6a11b877
,03-24 21:17:54.132  2145  2208 D BtGatt.GattService: onClientRegistered() - UUID=3c9720be-043d-4074-902d-dbcb6a11b877, clientIf=5
03-24 21:17:54.133  3258  3274 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-24 21:17:54.134  2145  2210 D BtGatt.GattService: start scan with filters
03-24 21:17:54.138  2145  2223 D BtGatt.ScanManager: handling starting scan
,03-24 21:17:54.138  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 21:17:54.138  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 21:17:54.138  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,03-24 21:17:54.138  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-24 21:17:54.139  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 21:17:54.139  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 21:17:54.139  3258  3258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-24 21:17:54.139  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 21:17:54.140  3258  3314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 21:17:54.140  3258  3314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 21:17:54.140  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 21:17:54.142  3258  3314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-24 21:17:54.143  2145  2208 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 21:17:54.143  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:17:54.146  2145  2208 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,03-24 21:17:54.146  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:17:54.147  2145  2223 D BtGatt.ScanManager: Starting BLE batch scan
03-24 21:17:54.147  2145  2223 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-24 21:17:54.150  2145  2208 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 21:17:54.150  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 21:17:54.154  2145  2208 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,03-24 21:17:54.154  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 21:17:54.158  2145  2164 D BtGatt.GattService: registerClient() - UUID=bf1e3036-eaba-4e5c-87d2-0e7371ae3ac5
03-24 21:17:54.159  2145  2208 D BtGatt.GattService: onClientRegistered() - UUID=bf1e3036-eaba-4e5c-87d2-0e7371ae3ac5, clientIf=6
03-24 21:17:54.159  3258  3275 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-24 21:17:54.161  2145  2221 D BtGatt.AdvertiseManager: message : 0
,03-24 21:17:54.166  2145  2221 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 21:17:54.170  2145  2208 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0,
,03-24 21:17:54.172  2145  2208 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 21:17:54.173  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-24 21:17:54.173  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-24 21:17:54.174   820   836 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 21:17:54.177  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 21:17:54.177  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-24 21:17:54.177  3258  3314 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-24 21:17:54.177  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-24 21:17:54.177  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...,
03-24 21:17:54.178  3258  3314 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-24 21:17:54.178  3258  3314 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-24 21:17:54.178  3258  3314 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,03-24 21:17:54.178  3258  3258 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-24 21:17:54.178  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess,
03-24 21:17:54.178  3258  3258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,03-24 21:17:54.178  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-24 21:17:54.178  3258  3258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
,03-24 21:17:54.178  3258  3314 I io.jxcore.node.ConnectionHelper: start: OK,
,03-24 21:17:54.181  3258  3258 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-24 21:17:54.181  3258  3258 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-24 21:17:54.181  3258  3258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 21:17:54.181  3258  3258 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything,
03-24 21:17:54.181  3258  3258 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 21:17:54.181  3258  3258 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING,
03-24 21:17:54.181  3258  3258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 21:17:54.181   820   835 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
03-24 21:17:54.183  3258  3714 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-24 21:17:54.188  3258  3714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-24 21:17:54.190  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 21:17:54.190  3258  3314 I jxcore-log: 
,03-24 21:17:54.194  3258  3314 I jxcore-log: ok 144 Can call startUpdateAdvertisingAndListening without error
,03-24 21:17:54.194  3258  3314 I jxcore-log: 
03-24 21:17:54.195  3258  3314 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-24 21:17:54.195  3258  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
,03-24 21:17:54.195  3258  3314 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-24 21:17:54.195  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-24 21:17:54.195  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,03-24 21:17:54.196  3258  3314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-24 21:17:54.196  3258  3714 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
,03-24 21:17:54.196  3258  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-24 21:17:54.196  3258  3714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,03-24 21:17:54.196  3258  3258 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-24 21:17:54.197  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-24 21:17:54.197  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,03-24 21:17:54.197  3258  3258 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,03-24 21:17:54.197  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 21:17:54.197  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 21:17:54.197  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-24 21:17:54.197  3258  3258 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-24 21:17:54.197  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-24 21:17:54.198  2145  2166 D BtGatt.GattService: stopScan() - queue size =1
03-24 21:17:54.199  2145  2210 D BtGatt.GattService: unregisterClient() - clientIf=5
03-24 21:17:54.200  2145  2208 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 21:17:54.200  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:17:54.200  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 21:17:54.200  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 21:17:54.200  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,03-24 21:17:54.200  2145  2223 D BtGatt.ScanManager: stopping BLe Batch
03-24 21:17:54.200  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-24 21:17:54.200  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-24 21:17:54.200  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 21:17:54.200  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-24 21:17:54.203  2145  2208 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 21:17:54.203  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:17:54.203  2145  2221 D BtGatt.AdvertiseManager: message : 1
03-24 21:17:54.204  2145  2223 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 21:17:54.204  2145  2221 D BtGatt.AdvertiseManager: stop advertise for client 6
03-24 21:17:54.205  2145  2208 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 21:17:54.205  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 21:17:54.208  2145  2208 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,03-24 21:17:54.208  2145  2208 D BtGatt.GattService: Client app is not null!
,03-24 21:17:54.209  2145  2210 D BtGatt.GattService: unregisterClient() - clientIf=6
03-24 21:17:54.209  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 21:17:54.210  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-24 21:17:54.210  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-24 21:17:54.210  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-24 21:17:54.210  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,03-24 21:17:54.210  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 21:17:54.210  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 21:17:54.210  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-24 21:17:54.211  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-24 21:17:54.211  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 21:17:54.211  3258  3258 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 21:17:54.211  3258  3258 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 21:17:54.211  3258  3258 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 21:17:54.211  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 21:17:54.211  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-24 21:17:54.212  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 21:17:54.212  3258  3314 I jxcore-log: 
,03-24 21:17:54.216  3258  3258 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-24 21:17:54.216  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-24 21:17:54.216  3258  3314 I jxcore-log: 
03-24 21:17:54.216   820  1375 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 21:17:54.217  3258  3314 I jxcore-log: ok 145 Can call stopAdvertisingAndListening without error
03-24 21:17:54.217  3258  3314 I jxcore-log: 
03-24 21:17:54.221  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-24 21:17:54.223  3258  3314 I jxcore-log: # teardown
03-24 21:17:54.223  3258  3314 I jxcore-log: 
,03-24 21:17:54.224  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 21:17:54.224  3258  3258 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 21:17:54.226  3258  3258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-24 21:17:54.226  3258  3258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 21:17:54.226  3258  3258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-24 21:17:54.228  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-24 21:17:54.228  3258  3314 I jxcore-log: 
,03-24 21:17:54.229  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 21:17:54.229  3258  3314 I jxcore-log: 
,03-24 21:17:54.230  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 21:17:54.230  3258  3314 I jxcore-log: 
,03-24 21:17:55.236  3258  3314 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 21:17:55.237  3258  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 21:17:55.237  3258  3314 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 21:17:55.244  3258  3314 I jxcore-log: ok 146 Should be able to call stopListeningForAdvertisments in teardown
03-24 21:17:55.244  3258  3314 I jxcore-log: 
,03-24 21:17:55.245  3258  3314 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 21:17:55.245  3258  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-24 21:17:55.245  3258  3314 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 21:17:55.246  3258  3314 I jxcore-log: ok 147 Should be able to call stopAdvertisingAndListening in teardown
03-24 21:17:55.246  3258  3314 I jxcore-log: 
,03-24 21:17:55.253  3258  3314 I jxcore-log: # setup
03-24 21:17:55.253  3258  3314 I jxcore-log: 
,03-24 21:17:55.357  3258  3314 I jxcore-log: # 38. Calling startUpdateAdvertisingAndListening twice is NOT an error
03-24 21:17:55.357  3258  3314 I jxcore-log: 
,03-24 21:17:55.506  3258  3314 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: true
,03-24 21:17:55.506  3258  3314 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 21:17:55.506  3258  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-24 21:17:55.506  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-24 21:17:55.514  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
03-24 21:17:55.514  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 21:17:55.515  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 21:17:55.515  3258  3314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 21:17:55.525  2145  2166 D BtGatt.GattService: registerClient() - UUID=1b7ea2c5-0636-4ec5-a16e-c179aaf601aa
,03-24 21:17:55.526  2145  2208 D BtGatt.GattService: onClientRegistered() - UUID=1b7ea2c5-0636-4ec5-a16e-c179aaf601aa, clientIf=5
03-24 21:17:55.526  3258  3274 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 21:17:55.528  2145  2164 D BtGatt.GattService: start scan with filters
,03-24 21:17:55.530  2145  2223 D BtGatt.ScanManager: handling starting scan
,03-24 21:17:55.531  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 21:17:55.531  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-24 21:17:55.531  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-24 21:17:55.531  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-24 21:17:55.531  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
,03-24 21:17:55.533  3258  3258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 21:17:55.534  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,03-24 21:17:55.534  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,03-24 21:17:55.535  3258  3314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
,03-24 21:17:55.535  3258  3314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 21:17:55.535  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-24 21:17:55.535  3258  3314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...,
03-24 21:17:55.542  2145  2208 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 21:17:55.542  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
03-24 21:17:55.545  2145  2208 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 21:17:55.545  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
,03-24 21:17:55.545  2145  2223 D BtGatt.ScanManager: Starting BLE batch scan
03-24 21:17:55.545  2145  2223 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 21:17:55.549  2145  2208 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0,
03-24 21:17:55.549  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:17:55.551  2145  2210 D BtGatt.GattService: registerClient() - UUID=850af109-8d94-4053-9c28-1fc65d0bdfd3
,03-24 21:17:55.551  2145  2208 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 21:17:55.551  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:17:55.552  2145  2208 D BtGatt.GattService: onClientRegistered() - UUID=850af109-8d94-4053-9c28-1fc65d0bdfd3, clientIf=6
03-24 21:17:55.552  3258  3275 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-24 21:17:55.555  2145  2221 D BtGatt.AdvertiseManager: message : 0
,03-24 21:17:55.563  2145  2221 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 21:17:55.566  2145  2208 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 21:17:55.568  2145  2208 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 21:17:55.568  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-24 21:17:55.569  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 21:17:55.569   820  1362 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
,03-24 21:17:55.572  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 21:17:55.572  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-24 21:17:55.572  3258  3314 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-24 21:17:55.572  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 21:17:55.573  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-24 21:17:55.574  3258  3314 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,03-24 21:17:55.574  3258  3314 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,03-24 21:17:55.574  3258  3314 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-24 21:17:55.574  3258  3314 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 21:17:55.574  3258  3258 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-24 21:17:55.574  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,03-24 21:17:55.574  3258  3258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-24 21:17:55.574  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-24 21:17:55.574  3258  3258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-24 21:17:55.574  3258  3258 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-24 21:17:55.574  3258  3258 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 21:17:55.575  3258  3258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-24 21:17:55.575  3258  3258 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-24 21:17:55.575  3258  3258 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 21:17:55.575  3258  3258 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-24 21:17:55.575  3258  3258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 21:17:55.576   820  1460 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 21:17:55.577  3258  3715 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-24 21:17:55.578  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 21:17:55.578  3258  3314 I jxcore-log: 
03-24 21:17:55.579  3258  3715 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-24 21:17:55.581  3258  3314 I jxcore-log: ok 148 Can call startUpdateAdvertisingAndListening without error
03-24 21:17:55.581  3258  3314 I jxcore-log: 
,03-24 21:17:55.585  3258  3314 I io.jxcore.node.ConnectionHelper: start: Port number: 4243, start advertisements: true
03-24 21:17:55.585  3258  3314 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-24 21:17:55.585  3258  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-24 21:17:55.585  3258  3314 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 21:17:55.586  3258  3314 I io.jxcore.node.ConnectionHelper: start: OK
03-24 21:17:55.587  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 21:17:55.587  3258  3314 I jxcore-log: 
,03-24 21:17:55.588  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-24 21:17:55.588  3258  3314 I jxcore-log: 
03-24 21:17:55.589  3258  3314 I jxcore-log: ok 149 Can call startUpdateAdvertisingAndListening twice without error
03-24 21:17:55.589  3258  3314 I jxcore-log: 
03-24 21:17:55.594  3258  3314 I jxcore-log: # teardown,
03-24 21:17:55.594  3258  3314 I jxcore-log: 
,03-24 21:17:56.383  3258  3314 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 21:17:56.383  3258  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
,03-24 21:17:56.384  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
,03-24 21:17:56.384  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-24 21:17:56.388  2145  2166 D BtGatt.GattService: stopScan() - queue size =1
,03-24 21:17:56.391  2145  2164 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-24 21:17:56.392  2145  2208 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 21:17:56.392  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 21:17:56.392  2145  2223 D BtGatt.ScanManager: stopping BLe Batch
03-24 21:17:56.392  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 21:17:56.393  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 21:17:56.393  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-24 21:17:56.393  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING],
03-24 21:17:56.394  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-24 21:17:56.394  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-24 21:17:56.394  3258  3258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 21:17:56.395  3258  3258 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
03-24 21:17:56.395  3258  3258 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 21:17:56.396  2145  2208 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,03-24 21:17:56.396  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:17:56.397  2145  2223 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 21:17:56.399  3258  3314 I jxcore-log: ok 150 Should be able to call stopListeningForAdvertisments in teardown
03-24 21:17:56.399  3258  3314 I jxcore-log: 
,03-24 21:17:56.400  2145  2208 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-24 21:17:56.400  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 21:17:56.400  2145  2208 D BtGatt.GattService: current time is 258037322816
03-24 21:17:56.400  2145  2208 D BtGatt.GattService: Batch record : [66, 65, -74, 86, -73, 66, 1, -128, -78, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -64, 3, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-24 21:17:56.400  2145  2208 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 21:17:56.400  2145  2208 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-24 21:17:56.401  3258  3314 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-24 21:17:56.401  3258  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
03-24 21:17:56.401  3258  3314 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-24 21:17:56.401  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-24 21:17:56.401  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-24 21:17:56.403  3258  3314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-24 21:17:56.403  3258  3715 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
,03-24 21:17:56.403  3258  3715 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,03-24 21:17:56.403  3258  3715 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-24 21:17:56.404  3258  3258 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-24 21:17:56.405  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-24 21:17:56.405  3258  3258 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,03-24 21:17:56.405  3258  3258 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-24 21:17:56.405  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-24 21:17:56.405  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 21:17:56.405  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 21:17:56.405  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-24 21:17:56.407  3258  3314 D BluetoothLeScanner: could not find callback wrapper
03-24 21:17:56.407  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 21:17:56.407  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-24 21:17:56.409  2145  2221 D BtGatt.AdvertiseManager: message : 1
,03-24 21:17:56.411  2145  2221 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-24 21:17:56.414  2145  2208 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 21:17:56.414  2145  2208 D BtGatt.GattService: Client app is not null!
03-24 21:17:56.415  2145  2210 D BtGatt.GattService: unregisterClient() - clientIf=6
03-24 21:17:56.415  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-24 21:17:56.415  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-24 21:17:56.415  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-24 21:17:56.416  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED],
,03-24 21:17:56.416  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,03-24 21:17:56.416  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 21:17:56.416  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 21:17:56.416  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-24 21:17:56.416  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-24 21:17:56.416  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 21:17:56.416  3258  3258 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
03-24 21:17:56.417  3258  3258 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 21:17:56.417  3258  3258 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 21:17:56.417  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 21:17:56.417  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-24 21:17:56.418  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-24 21:17:56.418  3258  3314 I jxcore-log: 
03-24 21:17:56.420  3258  3314 I jxcore-log: ok 151 Should be able to call stopAdvertisingAndListening in teardown,
03-24 21:17:56.420  3258  3314 I jxcore-log: 
03-24 21:17:56.425  3258  3258 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-24 21:17:56.426   820  1332 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 21:17:56.429  3258  3314 I jxcore-log: # setup
03-24 21:17:56.429  3258  3314 I jxcore-log: 
,03-24 21:17:56.431  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-24 21:17:56.431  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 21:17:56.432  3258  3258 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
,03-24 21:17:56.435  3258  3258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 21:17:56.435  3258  3258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 21:17:56.437  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 21:17:56.437  3258  3314 I jxcore-log: 
,03-24 21:17:56.438  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 21:17:56.438  3258  3314 I jxcore-log: 
,03-24 21:17:56.564  3258  3314 I jxcore-log: # 39. peerAvailabilityChange is called
03-24 21:17:56.564  3258  3314 I jxcore-log: ,
,03-24 21:17:56.712  3258  3314 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: true
,03-24 21:17:56.712  3258  3314 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 21:17:56.712  3258  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-24 21:17:56.712  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-24 21:17:56.722  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-24 21:17:56.722  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 21:17:56.722  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-24 21:17:56.722  3258  3314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 21:17:56.733  2145  2210 D BtGatt.GattService: registerClient() - UUID=74ce3b9d-9328-49b7-adaf-3db724fbf0e1
03-24 21:17:56.734  2145  2208 D BtGatt.GattService: onClientRegistered() - UUID=74ce3b9d-9328-49b7-adaf-3db724fbf0e1, clientIf=5
,03-24 21:17:56.735  3258  3275 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 21:17:56.736  2145  2166 D BtGatt.GattService: start scan with filters
,03-24 21:17:56.738  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-24 21:17:56.738  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-24 21:17:56.738  2145  2223 D BtGatt.ScanManager: handling starting scan
03-24 21:17:56.740  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,03-24 21:17:56.740  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,03-24 21:17:56.740  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 21:17:56.740  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 21:17:56.741  3258  3258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 21:17:56.741  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,03-24 21:17:56.741  3258  3314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 21:17:56.741  3258  3314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 21:17:56.742  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 21:17:56.742  3258  3314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-24 21:17:56.750  2145  2208 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 21:17:56.750  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:17:56.754  2145  2208 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,03-24 21:17:56.754  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 21:17:56.754  2145  2223 D BtGatt.ScanManager: Starting BLE batch scan
,03-24 21:17:56.754  2145  2223 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-24 21:17:56.757  2145  2208 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 21:17:56.757  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 21:17:56.759  2145  2208 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 21:17:56.759  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 21:17:56.760  2145  2164 D BtGatt.GattService: registerClient() - UUID=321d7d6b-a6d7-40f2-b1f9-99ac138880ac
03-24 21:17:56.761  2145  2208 D BtGatt.GattService: onClientRegistered() - UUID=321d7d6b-a6d7-40f2-b1f9-99ac138880ac, clientIf=6
03-24 21:17:56.761  3258  3274 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-24 21:17:56.762  2145  2221 D BtGatt.AdvertiseManager: message : 0
,03-24 21:17:56.766  2145  2221 D BtGatt.AdvertiseManager: starting multi advertising,
,03-24 21:17:56.769  2145  2208 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 21:17:56.774  2145  2208 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 21:17:56.775  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-24 21:17:56.775  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-24 21:17:56.776   820  1362 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 21:17:56.782  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 21:17:56.782  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-24 21:17:56.782  3258  3314 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-24 21:17:56.782  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 21:17:56.784  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-24 21:17:56.784  3258  3314 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-24 21:17:56.785  3258  3314 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-24 21:17:56.785  3258  3314 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-24 21:17:56.785  3258  3314 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 21:17:56.785  3258  3258 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-24 21:17:56.785  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 21:17:56.785  3258  3258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-24 21:17:56.785  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-24 21:17:56.785  3258  3258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-24 21:17:56.785  3258  3258 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
,03-24 21:17:56.785  3258  3258 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-24 21:17:56.786  3258  3258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 21:17:56.786  3258  3258 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-24 21:17:56.786  3258  3258 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-24 21:17:56.786  3258  3258 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-24 21:17:56.786   820  1460 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 21:17:56.786  3258  3258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 21:17:56.787  3258  3716 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-24 21:17:56.788  3258  3716 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-24 21:17:56.805  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 21:17:56.805  3258  3314 I jxcore-log: 
,03-24 21:17:56.806  3258  3314 I jxcore-log: ok 152 Can call startUpdateAdvertisingAndListeningwithout error
03-24 21:17:56.806  3258  3314 I jxcore-log: 
,03-24 21:17:56.809  3258  3314 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: false
,03-24 21:17:56.809  3258  3314 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 21:17:56.810  3258  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should affect listening to advertisements only
03-24 21:17:56.810  3258  3314 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 21:17:56.810  3258  3314 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 21:17:56.811  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 21:17:56.811  3258  3314 I jxcore-log: 
,03-24 21:17:56.823  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-24 21:17:56.823  3258  3314 I jxcore-log: 
,03-24 21:17:56.829  3258  3314 I jxcore-log: ok 153 Can call startListeningForAdvertisements without error
03-24 21:17:56.829  3258  3314 I jxcore-log: 
,03-24 21:17:57.766  2145  2145 D BtGatt.ScanManager: awakened up at time 259403
03-24 21:17:57.767  2145  2223 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 21:17:57.776  2145  2208 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-24 21:17:57.776  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:17:57.776  2145  2208 D BtGatt.GattService: current time is 259413743858
03-24 21:17:57.776  2145  2208 D BtGatt.GattService: Batch record : [82, 39, 60, 102, -35, 89, 1, -128, -78, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -63, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-24 21:17:57.777  2145  2208 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 21:17:57.777  2145  2208 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-24 21:17:57.778  3258  3258 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 1
03-24 21:17:57.778  3258  3258 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> E0:DB:10:14:E2:C0], added - the peer count is 2
03-24 21:17:57.778  3258  3258 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
,03-24 21:17:57.778  3258  3258 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> E0:DB:10:14:E2:C0], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 
,03-24 21:17:57.780  3258  3314 I jxcore-log: ok 154 peers must be an array
03-24 21:17:57.780  3258  3314 I jxcore-log: 
03-24 21:17:57.781  3258  3314 I jxcore-log: ok 155 peers must not be zero-length
03-24 21:17:57.781  3258  3314 I jxcore-log: 
03-24 21:17:57.781  3258  3314 I jxcore-log: ok 156 peer must have peerIdentifier
03-24 21:17:57.781  3258  3314 I jxcore-log: 
,03-24 21:17:57.781  3258  3314 I jxcore-log: ok 157 peerIdentifier must be a string
03-24 21:17:57.781  3258  3314 I jxcore-log: 
03-24 21:17:57.782  3258  3314 I jxcore-log: ok 158 peer must have peerAvailable
03-24 21:17:57.782  3258  3314 I jxcore-log: 
03-24 21:17:57.782  3258  3314 I jxcore-log: ok 159 peer must have pleaseConnect
03-24 21:17:57.782  3258  3314 I jxcore-log: 
,03-24 21:17:57.789  3258  3314 I jxcore-log: # teardown
03-24 21:17:57.789  3258  3314 I jxcore-log: 
,03-24 21:17:58.609  3258  3314 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 21:17:58.610  3258  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
03-24 21:17:58.610  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-24 21:17:58.610  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-24 21:17:58.615  2145  2166 D BtGatt.GattService: stopScan() - queue size =1
,03-24 21:17:58.623  2145  2164 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-24 21:17:58.624  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-24 21:17:58.624  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 21:17:58.624  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false,
,03-24 21:17:58.625  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING],
,03-24 21:17:58.625  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-24 21:17:58.625  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 21:17:58.625  3258  3258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 21:17:58.625  3258  3258 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
03-24 21:17:58.626  3258  3258 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 21:17:58.626  2145  2208 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,03-24 21:17:58.626  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:17:58.627  2145  2223 D BtGatt.ScanManager: stopping BLe Batch
03-24 21:17:58.628  3258  3314 I jxcore-log: ok 160 Should be able to call stopListeningForAdvertisments in teardown
03-24 21:17:58.628  3258  3314 I jxcore-log: 
03-24 21:17:58.629  2145  2208 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 21:17:58.629  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:17:58.629  3258  3314 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-24 21:17:58.629  3258  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
03-24 21:17:58.629  3258  3314 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections,
03-24 21:17:58.629  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-24 21:17:58.629  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-24 21:17:58.629  2145  2223 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 21:17:58.630  3258  3314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-24 21:17:58.630  3258  3716 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-24 21:17:58.630  3258  3716 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-24 21:17:58.630  3258  3716 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,03-24 21:17:58.631  3258  3258 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-24 21:17:58.631  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-24 21:17:58.631  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,03-24 21:17:58.631  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 21:17:58.631  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 21:17:58.631  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-24 21:17:58.631  2145  2208 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-24 21:17:58.632  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:17:58.632  2145  2208 D BtGatt.GattService: current time is 260269289586
03-24 21:17:58.632  2145  2208 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -64, 4, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0, 82, 39, 60, 102, -35, 89, 1, -128, -79, 5, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-24 21:17:58.633  3258  3258 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-24 21:17:58.633  2145  2208 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64],
03-24 21:17:58.634  2145  2208 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 21:17:58.634  3258  3314 D BluetoothLeScanner: could not find callback wrapper
03-24 21:17:58.634  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 21:17:58.634  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-24 21:17:58.638  2145  2221 D BtGatt.AdvertiseManager: message : 1
,03-24 21:17:58.638  2145  2221 D BtGatt.AdvertiseManager: stop advertise for client 6
03-24 21:17:58.640  2145  2208 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 21:17:58.640  2145  2208 D BtGatt.GattService: Client app is not null!
,03-24 21:17:58.641  2145  2210 D BtGatt.GattService: unregisterClient() - clientIf=6
03-24 21:17:58.642  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 21:17:58.642  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,03-24 21:17:58.642  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-24 21:17:58.642  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-24 21:17:58.642  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,03-24 21:17:58.642  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 21:17:58.642  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 21:17:58.643  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-24 21:17:58.645  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,03-24 21:17:58.645  3258  3314 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-24 21:17:58.645  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 21:17:58.645  3258  3258 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 21:17:58.645  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-24 21:17:58.645  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-24 21:17:58.650  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-24 21:17:58.650  3258  3314 I jxcore-log: 
,03-24 21:17:58.650  3258  3258 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-24 21:17:58.650   820  1332 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 21:17:58.655  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-24 21:17:58.656  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 21:17:58.656  3258  3258 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 21:17:58.659  3258  3258 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-24 21:17:58.659  3258  3258 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 21:17:58.659  3258  3258 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 21:17:58.659  3258  3258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 21:17:58.659  3258  3258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-24 21:17:58.660  3258  3314 I jxcore-log: ok 161 Should be able to call stopAdvertisingAndListening in teardown
03-24 21:17:58.660  3258  3314 I jxcore-log: 
,03-24 21:17:58.666  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 21:17:58.666  3258  3314 I jxcore-log: 
,03-24 21:17:58.669  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 21:17:58.669  3258  3314 I jxcore-log: 
,03-24 21:17:58.671  3258  3314 I jxcore-log: # setup
03-24 21:17:58.671  3258  3314 I jxcore-log: 
,03-24 21:17:58.827  3258  3314 I jxcore-log: # 40. Can connect to a remote peer
03-24 21:17:58.827  3258  3314 I jxcore-log: 
,03-24 21:17:58.980  3258  3314 I io.jxcore.node.ConnectionHelper: start: Port number: 56557, start advertisements: true
,03-24 21:17:58.980  3258  3314 V io.jxcore.node.ConnectivityMonitor: start: Already started,
03-24 21:17:58.980  3258  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,03-24 21:17:58.980  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-24 21:17:58.986  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser,
,03-24 21:17:58.986  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 21:17:58.986  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 21:17:58.986  3258  3314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 21:17:58.994  2145  2166 D BtGatt.GattService: registerClient() - UUID=70071b71-8eac-4394-9c9c-e10a28c419f7,
,03-24 21:17:58.995  2145  2208 D BtGatt.GattService: onClientRegistered() - UUID=70071b71-8eac-4394-9c9c-e10a28c419f7, clientIf=5
,03-24 21:17:58.995  3258  3275 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5,
03-24 21:17:58.996  2145  2164 D BtGatt.GattService: start scan with filters
,03-24 21:17:58.997  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
03-24 21:17:58.997  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 21:17:58.997  2145  2223 D BtGatt.ScanManager: handling starting scan
03-24 21:17:58.998  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING],
03-24 21:17:58.998  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-24 21:17:58.998  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 21:17:58.998  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 21:17:58.998  3258  3258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false,
03-24 21:17:58.998  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,03-24 21:17:58.998  3258  3314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 21:17:58.999  3258  3314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 21:17:58.999  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-24 21:17:58.999  3258  3314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-24 21:17:59.007  2145  2208 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1,
03-24 21:17:59.007  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 21:17:59.009  2145  2208 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15,
03-24 21:17:59.009  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 21:17:59.009  2145  2223 D BtGatt.ScanManager: Starting BLE batch scan,
03-24 21:17:59.009  2145  2223 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 21:17:59.010  2145  2210 D BtGatt.GattService: registerClient() - UUID=5fa904f3-5803-419f-8a34-60f43ecbda83
03-24 21:17:59.010  2145  2208 D BtGatt.GattService: onClientRegistered() - UUID=5fa904f3-5803-419f-8a34-60f43ecbda83, clientIf=6
03-24 21:17:59.011  3258  3274 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-24 21:17:59.012  2145  2208 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,03-24 21:17:59.012  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 21:17:59.014  2145  2221 D BtGatt.AdvertiseManager: message : 0
03-24 21:17:59.015  2145  2208 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,03-24 21:17:59.015  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 21:17:59.019  2145  2221 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 21:17:59.022  2145  2208 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 21:17:59.025  2145  2208 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 21:17:59.026  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-24 21:17:59.026  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 21:17:59.026   820  3100 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 21:17:59.030  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-24 21:17:59.030  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-24 21:17:59.030  3258  3314 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-24 21:17:59.030  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 21:17:59.031  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-24 21:17:59.031  3258  3314 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-24 21:17:59.031  3258  3314 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,03-24 21:17:59.031  3258  3314 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-24 21:17:59.032  3258  3314 I io.jxcore.node.ConnectionHelper: start: OK
03-24 21:17:59.032  3258  3258 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-24 21:17:59.032  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 21:17:59.032  3258  3258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-24 21:17:59.032  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,03-24 21:17:59.033  3258  3258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
,03-24 21:17:59.033  3258  3258 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-24 21:17:59.033  3258  3258 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 21:17:59.033  3258  3258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 21:17:59.033  3258  3258 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-24 21:17:59.033  3258  3258 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 21:17:59.034  3258  3258 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-24 21:17:59.034  3258  3258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-24 21:17:59.035   820   836 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 21:17:59.036  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 21:17:59.036  3258  3314 I jxcore-log: 
03-24 21:17:59.037  3258  3717 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-24 21:17:59.040  3258  3314 I jxcore-log: ok 162 Can call startUpdateAdvertisingAndListening without error
,03-24 21:17:59.040  3258  3314 I jxcore-log: 
03-24 21:17:59.041  3258  3717 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-24 21:17:59.044  3258  3314 I io.jxcore.node.ConnectionHelper: start: Port number: 56557, start advertisements: false
,03-24 21:17:59.044  3258  3314 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 21:17:59.044  3258  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should affect listening to advertisements only
03-24 21:17:59.044  3258  3314 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 21:17:59.044  3258  3314 I io.jxcore.node.ConnectionHelper: start: OK
03-24 21:17:59.045  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 21:17:59.045  3258  3314 I jxcore-log: 
,03-24 21:17:59.046  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-24 21:17:59.046  3258  3314 I jxcore-log: 
,03-24 21:17:59.048  3258  3314 I jxcore-log: ok 163 Can call startListeningForAdvertisements without error
03-24 21:17:59.048  3258  3314 I jxcore-log: 
,03-24 21:17:59.644  3364  3718 V GoogleAuthProtoRequest: [337] a.<init>: mAccountName set to: thalitester@gmail.com
,03-24 21:17:59.738  1266  2545 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
03-24 21:17:59.738  1266  2545 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 21:17:59.738  1266  2545 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 21:17:59.739  1266  2545 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 21:17:59.745  1266  2545 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 21:17:59.772  3364  3718 W ExperimentUpdateService: [337] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,03-24 21:17:59.773  3364  3718 W ExperimentUpdateService: [337] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-24 21:17:59.773  3364  3718 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-24 21:17:59.773  3364  3718 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-24 21:17:59.773  3364  3718 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-24 21:17:59.773  3364  3718 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-24 21:17:59.773  3364  3718 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-24 21:17:59.773  3364  3718 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-24 21:17:59.773  3364  3718 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-24 21:17:59.773  3364  3718 W ExperimentUpdateService: 	,at com.a.a.a.g.a(SourceFile:79)
03-24 21:17:59.773  3364  3718 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-24 21:17:59.773  3364  3718 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-24 21:17:59.797  2145  2145 D BtGatt.ScanManager: awakened up at time 261433
,03-24 21:17:59.799  2145  2223 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 21:17:59.803  2145  2208 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-24 21:17:59.803  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:17:59.804  2145  2208 D BtGatt.GattService: current time is 261441116669
03-24 21:17:59.804  2145  2208 D BtGatt.GattService: Batch record : [92, -36, 53, 19, 0, 113, 1, -128, -78, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -59, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-24 21:17:59.805  2145  2208 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 21:17:59.805  2145  2208 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-24 21:17:59.807  3258  3258 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> E0:DB:10:14:E2:C0], added - the peer count is 1
,03-24 21:17:59.808  3258  3258 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 2
,03-24 21:17:59.808  3258  3258 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> E0:DB:10:14:E2:C0], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 
03-24 21:17:59.809  3258  3258 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
,03-24 21:17:59.813  3258  3314 I jxcore-log: INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"E0:DB:10:14:E2:C0","peerAvailable":true,"pleaseConnect":false}]
03-24 21:17:59.813  3258  3314 I jxcore-log: 
,03-24 21:17:59.824  3258  3314 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID E0:DB:10:14:E2:C0
,03-24 21:17:59.824  3258  3314 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> E0:DB:10:14:E2:C0]
,03-24 21:17:59.828  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address E0:DB:10:14:E2:C0
,03-24 21:17:59.829  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
03-24 21:17:59.829  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,03-24 21:17:59.831  3258  3314 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null E0:DB:10:14:E2:C0
,03-24 21:17:59.831  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address E0:DB:10:14:E2:C0
03-24 21:17:59.831  3258  3314 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: E0:DB:10:14:E2:C0)
,03-24 21:17:59.834  3258  3719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address E0:DB:10:14:E2:C0 (thread ID: 351)
03-24 21:17:59.835  3258  3314 I jxcore-log: INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"pleaseConnect":false}]
03-24 21:17:59.835  3258  3314 I jxcore-log: 
,03-24 21:17:59.835  3258  3719 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-24 21:17:59.841  2145  2164 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66,
,03-24 21:18:04.057  2145  2242 W bt-btif : info:x10,
,03-24 21:18:04.057  2145  2208 D         : remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
03-24 21:18:04.058  2145  2208 E BluetoothRemoteDevices: aclStateChangeCallback: Device is NULL
,03-24 21:18:04.151  2145  2242 W bt-sdp  : process_service_search_attr_rsp
,03-24 21:18:04.414  2145  2208 D btif_config: btif_get_device_type: Device [e0:db:10:14:e2:c0] type 1
,03-24 21:18:04.424  2145  2208 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 1,
03-24 21:18:04.424  2145  2208 E bt-btif : check_cod: remote_cod = 0x5a020c
,03-24 21:18:04.429  2145  2209 I BluetoothBondStateMachine: Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 10 NewState: 11,
03-24 21:18:04.430  2145  2209 I BluetoothBondStateMachine: Entering PendingCommandState State
,03-24 21:18:04.464  2145  2208 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 0,
03-24 21:18:04.465  2145  2209 D BluetoothAdapterProperties: Failed to remove device: E0:DB:10:14:E2:C0
,03-24 21:18:04.514  2145  2242 W bt-btif : new conn_srvc id:26, app_id:1
03-24 21:18:04.514  2145  2242 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:1
03-24 21:18:04.514  2145  2242 W bt-btif : bta_dm_pm_ssr:2, lat:1200
03-24 21:18:04.514  3258  3719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onSocketConnected: [<no peer name> E0:DB:10:14:E2:C0] (thread ID: 351)
03-24 21:18:04.514  3258  3719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 351)
,03-24 21:18:04.517  3258  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesWritten: 15 bytes successfully written (thread ID: 352)
03-24 21:18:04.517  3258  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Outgoing connection initialized (*handshake* thread ID: 352)
03-24 21:18:04.517  3258  3719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 351)
,03-24 21:18:04.520  3258  3721 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 352)
,03-24 21:18:04.534   820   854 I ActivityManager: Start proc 3722:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.BluetoothPairingRequest
03-24 21:18:04.535  2145  2209 I BluetoothBondStateMachine: Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 11 NewState: 10
,03-24 21:18:04.541  3258  3721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesRead: Read 15 bytes successfully (thread ID: 352)
03-24 21:18:04.542  3258  3721 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Handshake succeeded with [<no peer name> E0:DB:10:14:E2:C0]
03-24 21:18:04.542  3258  3721 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onHandshakeSucceeded: [<no peer name> E0:DB:10:14:E2:C0] (thread ID: 351)
03-24 21:18:04.542  3258  3721 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: handleSuccessfulClientThread: [<no peer name> E0:DB:10:14:E2:C0] (thread ID: 351)
03-24 21:18:04.542  3258  3721 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 352)
03-24 21:18:04.542  3258  3258 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> E0:DB:10:14:E2:C0]
,03-24 21:18:04.543  3258  3258 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing connection to peer [<no peer name> E0:DB:10:14:E2:C0],
03-24 21:18:04.544  3258  3258 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> E0:DB:10:14:E2:C0] updated - the peer count is 2
,03-24 21:18:04.546  3258  3258 I io.jxcore.node.ConnectionHelper: lowerBleDiscoveryPowerAndStartResetTimer: Lowering the power settings
,03-24 21:18:04.546  3258  3258 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 2 -> 0,
,03-24 21:18:04.547  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:,
03-24 21:18:04.547  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 21:18:04.547  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-24 21:18:04.547  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-24 21:18:04.547  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-24 21:18:04.547  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-24 21:18:04.552  2145  2221 D BtGatt.AdvertiseManager: message : 1
,03-24 21:18:04.554  2145  2221 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-24 21:18:04.558  2145  2208 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 21:18:04.558  2145  2208 D BtGatt.GattService: Client app is not null!
,03-24 21:18:04.559  2145  2210 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-24 21:18:04.560  3258  3258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-24 21:18:04.560  3258  3258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-24 21:18:04.560  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 3, timeout: 0, is connectable: false
03-24 21:18:04.560  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 21:18:04.560  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,03-24 21:18:04.561  3258  3258 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 21:18:04.561  3258  3258 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false],
,03-24 21:18:04.561  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 21:18:04.561  3258  3258 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-24 21:18:04.569  2145  2209 I BluetoothBondStateMachine: StableState(): Entering Off State
,03-24 21:18:04.571  2145  2166 D BtGatt.GattService: registerClient() - UUID=70170051-ba59-4953-bfd9-1b4831a79431
,03-24 21:18:04.571  2145  2208 D BtGatt.GattService: onClientRegistered() - UUID=70170051-ba59-4953-bfd9-1b4831a79431, clientIf=6
03-24 21:18:04.572  3258  3274 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-24 21:18:04.573  2145  2221 D BtGatt.AdvertiseManager: message : 0
,03-24 21:18:04.577  2145  2221 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 21:18:04.580  2145  2208 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 21:18:04.583  2145  2208 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 21:18:04.583  3258  3258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-24 21:18:04.585  2145  2166 D BtGatt.GattService: stopScan() - queue size =1
,03-24 21:18:04.585  2145  2164 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-24 21:18:04.586  3258  3258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-24 21:18:04.586  3258  3258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 21:18:04.586  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 21:18:04.586  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 21:18:04.586  3258  3258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 21:18:04.586  2145  2208 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,03-24 21:18:04.586  3258  3258 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-24 21:18:04.586  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:18:04.586  2145  2223 D BtGatt.ScanManager: stopping BLe Batch
,03-24 21:18:04.588  2145  2208 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 21:18:04.588  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:18:04.588  2145  2223 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 21:18:04.589  2145  2208 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-24 21:18:04.589  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:18:04.590  2145  2208 D BtGatt.GattService: current time is 266227032970
03-24 21:18:04.590  2145  2208 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -57, 28, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0, 92, -36, 53, 19, 0, 113, 1, -128, -73, 28, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-24 21:18:04.590  2145  2208 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-24 21:18:04.590  2145  2208 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 21:18:04.590  2145  2210 D BtGatt.GattService: registerClient() - UUID=92dc2b22-277c-4954-a005-6c0b891443ee
03-24 21:18:04.591  2145  2208 D BtGatt.GattService: onClientRegistered() - UUID=92dc2b22-277c-4954-a005-6c0b891443ee, clientIf=5
03-24 21:18:04.592  3258  3274 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-24 21:18:04.592  2145  2166 D BtGatt.GattService: start scan with filters
,03-24 21:18:04.593  3258  3258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 21:18:04.593  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true,
03-24 21:18:04.593  3258  3258 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 3 -> 1
03-24 21:18:04.593  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 21:18:04.593  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 21:18:04.593  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-24 21:18:04.593  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-24 21:18:04.593  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-24 21:18:04.593  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-24 21:18:04.594  2145  2223 D BtGatt.ScanManager: handling starting scan
,03-24 21:18:04.595  2145  2221 D BtGatt.AdvertiseManager: message : 1
,03-24 21:18:04.596  2145  2208 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 21:18:04.596  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:18:04.596  2145  2221 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-24 21:18:04.597  2145  2208 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 21:18:04.597  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:18:04.597  2145  2223 D BtGatt.ScanManager: Starting BLE batch scan
,03-24 21:18:04.597  2145  2223 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 21:18:04.598  2145  2208 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,03-24 21:18:04.598  2145  2208 D BtGatt.GattService: Client app is not null!
,03-24 21:18:04.599  2145  2166 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-24 21:18:04.599  3258  3258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 21:18:04.600  3258  3258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-24 21:18:04.600  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
,03-24 21:18:04.600  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 21:18:04.600  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 21:18:04.600  3258  3258 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 21:18:04.600  3258  3258 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-24 21:18:04.600  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 21:18:04.600  3258  3258 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-24 21:18:04.601  2145  2208 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 21:18:04.601  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:18:04.602  2145  2208 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,03-24 21:18:04.602  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 21:18:04.604  2145  2164 D BtGatt.GattService: registerClient() - UUID=670a643a-215a-47af-8759-b63f090b0160
,03-24 21:18:04.605  2145  2208 D BtGatt.GattService: onClientRegistered() - UUID=670a643a-215a-47af-8759-b63f090b0160, clientIf=6
03-24 21:18:04.605  3258  3274 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-24 21:18:04.606  2145  2221 D BtGatt.AdvertiseManager: message : 0
,03-24 21:18:04.608  2145  2221 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 21:18:04.610  2145  2208 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 21:18:04.613  2145  2208 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 21:18:04.613  3258  3258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-24 21:18:04.614  2145  2164 D BtGatt.GattService: stopScan() - queue size =1
,03-24 21:18:04.615  2145  2166 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-24 21:18:04.616  3258  3258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 21:18:04.616  3258  3258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 21:18:04.616  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 21:18:04.616  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 21:18:04.616  3258  3258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 21:18:04.616  3258  3258 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-24 21:18:04.616  2145  2208 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,03-24 21:18:04.616  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:18:04.616  2145  2223 D BtGatt.ScanManager: stopping BLe Batch
,03-24 21:18:04.618  2145  2208 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 21:18:04.618  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:18:04.618  2145  2223 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 21:18:04.620  2145  2208 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 21:18:04.620  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:18:04.620  2145  2210 D BtGatt.GattService: registerClient() - UUID=f9dde888-1fe4-49b7-a822-3925ae14b220
,03-24 21:18:04.621  2145  2208 D BtGatt.GattService: onClientRegistered() - UUID=f9dde888-1fe4-49b7-a822-3925ae14b220, clientIf=5
03-24 21:18:04.621  3258  3274 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-24 21:18:04.622  2145  2164 D BtGatt.GattService: start scan with filters
03-24 21:18:04.622  3258  3258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 21:18:04.622  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 21:18:04.623  3258  3258 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 2 -> 0
,03-24 21:18:04.623  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 21:18:04.623  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 21:18:04.623  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-24 21:18:04.623  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-24 21:18:04.623  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-24 21:18:04.623  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-24 21:18:04.626  2145  2223 D BtGatt.ScanManager: handling starting scan
03-24 21:18:04.626  2145  2221 D BtGatt.AdvertiseManager: message : 1
,03-24 21:18:04.627  2145  2221 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-24 21:18:04.629  2145  2208 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,03-24 21:18:04.629  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 21:18:04.630  2145  2208 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 21:18:04.630  2145  2208 D BtGatt.GattService: Client app is not null!
,03-24 21:18:04.631  2145  2164 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-24 21:18:04.631  3258  3258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 21:18:04.632  3258  3258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
,03-24 21:18:04.632  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-24 21:18:04.632  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 21:18:04.632  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 21:18:04.632  3258  3258 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 21:18:04.632  3258  3258 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 21:18:04.632  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 21:18:04.632  3258  3258 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-24 21:18:04.632  2145  2208 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 21:18:04.632  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:18:04.633  2145  2223 D BtGatt.ScanManager: Starting BLE batch scan
03-24 21:18:04.633  2145  2223 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-24 21:18:04.634  2145  2208 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0,
03-24 21:18:04.634  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 21:18:04.635  2145  2208 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 21:18:04.635  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 21:18:04.637  2145  2166 D BtGatt.GattService: registerClient() - UUID=d2686f30-4fae-4b19-8951-c97ef4f2db73
,03-24 21:18:04.637   820   858 D BluetoothManagerService: Message: 20
03-24 21:18:04.637   820   858 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3b310b4f:true
03-24 21:18:04.637  2145  2208 D BtGatt.GattService: onClientRegistered() - UUID=d2686f30-4fae-4b19-8951-c97ef4f2db73, clientIf=6
03-24 21:18:04.637  3258  3274 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-24 21:18:04.638  2145  2221 D BtGatt.AdvertiseManager: message : 0
,03-24 21:18:04.641   820  1460 I ActivityManager: Killing 1515:com.google.android.googlequicksearchbox:search/u0a28 (adj 15): empty #17
,03-24 21:18:04.643  2145  2221 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 21:18:04.645  2145  2208 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 21:18:04.647  2145  2208 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 21:18:04.648  3258  3258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-24 21:18:04.649  2145  2164 D BtGatt.GattService: stopScan() - queue size =1
03-24 21:18:04.650  2145  2210 D BtGatt.GattService: unregisterClient() - clientIf=5
03-24 21:18:04.650  3258  3258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 21:18:04.650  3258  3258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 21:18:04.650  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-24 21:18:04.650  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-24 21:18:04.650  3258  3258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 21:18:04.650  2145  2208 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 21:18:04.650  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:18:04.650  3258  3258 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-24 21:18:04.650  2145  2223 D BtGatt.ScanManager: stopping BLe Batch
,03-24 21:18:04.653  2145  2208 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,03-24 21:18:04.653  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:18:04.654  2145  2223 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 21:18:04.654  2145  2166 D BtGatt.GattService: registerClient() - UUID=68b19591-12df-4928-9694-9e66b30472a7
,03-24 21:18:04.654  2145  2208 D BtGatt.GattService: onClientRegistered() - UUID=68b19591-12df-4928-9694-9e66b30472a7, clientIf=5
03-24 21:18:04.654  3258  3274 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 21:18:04.654  2145  2208 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 21:18:04.654  2145  2164 D BtGatt.GattService: start scan with filters
03-24 21:18:04.654  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:18:04.655  3258  3258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 21:18:04.655  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-24 21:18:04.656  3258  3258 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing socket thread, for peer [<no peer name> E0:DB:10:14:E2:C0], created successfully
03-24 21:18:04.656  3258  3258 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 1
03-24 21:18:04.656  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 21:18:04.656  3258  3258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-24 21:18:04.656  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-24 21:18:04.656  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 21:18:04.656  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 21:18:04.656  3258  3741 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 353)
03-24 21:18:04.657  3258  3741 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 34761
03-24 21:18:04.657  3258  3741 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
03-24 21:18:04.657  3258  3741 I io.jxcore.node.ConnectionHelper: onListeningForIncomingConnections: Outgoing connection is using port 34761 (peer ID: E0:DB:10:14:E2:C0)
,03-24 21:18:04.658  3258  3741 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "E0:DB:10:14:E2:C0" removed
,03-24 21:18:04.660  3258  3314 I jxcore-log: INFO testThaliMobileNative: 
03-24 21:18:04.660  3258  3314 I jxcore-log: 
03-24 21:18:04.661  3258  3314 I jxcore-log: ok 164 Must have listeningPort
03-24 21:18:04.661  3258  3314 I jxcore-log: 
03-24 21:18:04.661  3258  3314 I jxcore-log: ok 165 listeningPort must be a number
03-24 21:18:04.661  3258  3314 I jxcore-log: 
,03-24 21:18:04.662  2145  2223 D BtGatt.ScanManager: handling starting scan
03-24 21:18:04.662  3258  3314 I jxcore-log: ok 166 Connection must have clientPort
03-24 21:18:04.662  3258  3314 I jxcore-log: 
03-24 21:18:04.662  3258  3314 I jxcore-log: ok 167 clientPort must be a number
03-24 21:18:04.662  3258  3314 I jxcore-log: 
03-24 21:18:04.663  3258  3314 I jxcore-log: ok 168 Connection must have serverPort
03-24 21:18:04.663  3258  3314 I jxcore-log: 
03-24 21:18:04.663  3258  3314 I jxcore-log: ok 169 serverPort must be a number
03-24 21:18:04.663  3258  3314 I jxcore-log: 
,03-24 21:18:04.664  2145  2208 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 21:18:04.664  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:18:04.664  3258  3314 I jxcore-log: ok 170 forward connection must have clientPort == 0
03-24 21:18:04.664  3258  3314 I jxcore-log: 
,03-24 21:18:04.665  2145  2208 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 21:18:04.665  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:18:04.665  2145  2223 D BtGatt.ScanManager: Starting BLE batch scan
03-24 21:18:04.665  2145  2223 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 21:18:04.666  3258  3314 I jxcore-log: ok 171 forward connection must have serverPort == 0
03-24 21:18:04.666  3258  3314 I jxcore-log: 
,03-24 21:18:04.666  2145  2208 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 21:18:04.666  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:18:04.667  2145  2208 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 21:18:04.667  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 21:18:04.671  3258  3314 I jxcore-log: # teardown
03-24 21:18:04.671  3258  3314 I jxcore-log: 
,03-24 21:18:04.720   820  1022 D WifiService: Client connection lost with reason: 4
,03-24 21:18:06.986  3258  3314 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 21:18:06.986  3258  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
03-24 21:18:06.986  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-24 21:18:06.986  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-24 21:18:06.991  2145  2166 D BtGatt.GattService: stopScan() - queue size =1
,03-24 21:18:06.994  2145  2164 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-24 21:18:06.995  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 21:18:06.995  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-24 21:18:06.995  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-24 21:18:06.996  2145  2208 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 21:18:06.996  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 21:18:06.996  2145  2223 D BtGatt.ScanManager: stopping BLe Batch
03-24 21:18:06.997  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-24 21:18:06.997  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
,03-24 21:18:06.997  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 21:18:06.999  3258  3258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 21:18:07.000  3258  3258 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
03-24 21:18:07.000  2145  2208 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 21:18:07.000  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:18:07.000  3258  3258 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 21:18:07.000  2145  2223 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 21:18:07.005  2145  2208 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-24 21:18:07.005  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:18:07.005  2145  2208 D BtGatt.GattService: current time is 268642430573
03-24 21:18:07.005  2145  2208 D BtGatt.GattService: Batch record : [92, -36, 53, 19, 0, 113, 1, -128, -78, 13, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -72, 18, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-24 21:18:07.006  2145  2208 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,03-24 21:18:07.006  2145  2208 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-24 21:18:07.007  3258  3314 I jxcore-log: ok 172 Should be able to call stopListeningForAdvertisments in teardown
03-24 21:18:07.007  3258  3314 I jxcore-log: ,
03-24 21:18:07.009  3258  3314 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-24 21:18:07.009  3258  3314 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> E0:DB:10:14:E2:C0]
03-24 21:18:07.009  3258  3314 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 353)
03-24 21:18:07.009  3258  3314 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 353)
03-24 21:18:07.010  3258  3314 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
03-24 21:18:07.010  3258  3314 D io.jxcore.node.OutgoingSocketThread: closeLocalSocketAndStreams: Nothing to close (thread ID: 353)
03-24 21:18:07.010  3258  3314 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 353)
03-24 21:18:07.011  3258  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
03-24 21:18:07.011  3258  3314 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-24 21:18:07.011  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,03-24 21:18:07.011  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-24 21:18:07.011  3258  3741 D io.jxcore.node.OutgoingSocketThread: Exiting thread (ID: 353)
03-24 21:18:07.013  3258  3314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-24 21:18:07.013  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-24 21:18:07.013  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-24 21:18:07.013  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 21:18:07.013  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 21:18:07.013  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-24 21:18:07.013  3258  3717 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-24 21:18:07.013  3258  3717 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-24 21:18:07.013  3258  3717 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-24 21:18:07.014  3258  3314 D BluetoothLeScanner: could not find callback wrapper
03-24 21:18:07.014  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 21:18:07.014  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,03-24 21:18:07.018  2145  2221 D BtGatt.AdvertiseManager: message : 1
,03-24 21:18:07.020  2145  2221 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-24 21:18:07.022  2145  2208 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 21:18:07.022  2145  2208 D BtGatt.GattService: Client app is not null!
03-24 21:18:07.022  2145  2166 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-24 21:18:07.023  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
03-24 21:18:07.023  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-24 21:18:07.023  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-24 21:18:07.023  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-24 21:18:07.023  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-24 21:18:07.023  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-24 21:18:07.023  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 21:18:07.023  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-24 21:18:07.024  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-24 21:18:07.024  3258  3314 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
,03-24 21:18:07.024  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 21:18:07.024  3258  3258 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 21:18:07.024  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 21:18:07.024  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-24 21:18:07.026  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-24 21:18:07.026  3258  3314 I jxcore-log: 
,03-24 21:18:07.029  3258  3258 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-24 21:18:07.030   820  1332 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 21:18:07.034  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
,03-24 21:18:07.035  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
,03-24 21:18:07.035  3258  3258 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 21:18:07.038  3258  3258 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-24 21:18:07.038  3258  3258 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-24 21:18:07.038  3258  3258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 21:18:07.038  3258  3258 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 21:18:07.038  3258  3258 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 21:18:07.038  3258  3258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 21:18:07.038  3258  3258 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-24 21:18:07.040  3258  3314 I jxcore-log: ok 173 Should be able to call stopAdvertisingAndListening in teardown
03-24 21:18:07.040  3258  3314 I jxcore-log: 
,03-24 21:18:07.045  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 21:18:07.045  3258  3314 I jxcore-log: 
,03-24 21:18:07.046  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 21:18:07.046  3258  3314 I jxcore-log: 
,03-24 21:18:07.047  3258  3314 I jxcore-log: # setup
03-24 21:18:07.047  3258  3314 I jxcore-log: 
,03-24 21:18:07.221  2145  2242 W bt-btif : bta_jv_rfc_port_to_cb(port_handle:0xd):jv handle:0x0 not FOUND
,03-24 21:18:08.030  3258  3314 I jxcore-log: # 41. Can shift large amounts of data
03-24 21:18:08.030  3258  3314 I jxcore-log: 
,03-24 21:18:08.263  3258  3314 I io.jxcore.node.ConnectionHelper: start: Port number: 41828, start advertisements: true
03-24 21:18:08.263  3258  3314 I io.jxcore.node.ConnectionHelper: restoreDefaultBleDiscoverySettings: Powering the BLE discovery back up
03-24 21:18:08.263  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 0 -> 2
,03-24 21:18:08.263  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 21:18:08.263  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 21:18:08.263  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-24 21:18:08.263  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-24 21:18:08.263  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-24 21:18:08.263  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-24 21:18:08.263  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 1, timeout: 0, is connectable: false
03-24 21:18:08.263  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-24 21:18:08.263  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 1 -> 3
03-24 21:18:08.263  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 21:18:08.263  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 21:18:08.263  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-24 21:18:08.263  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-24 21:18:08.263  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-24 21:18:08.263  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-24 21:18:08.263  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-24 21:18:08.263  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-24 21:18:08.263  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 0 -> 2
03-24 21:18:08.264  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 21:18:08.264  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 21:18:08.264  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-24 21:18:08.264  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-24 21:18:08.264  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-24 21:18:08.264  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-24 21:18:08.264  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-24 21:18:08.264  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 21:18:08.264  3258  3314 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 21:18:08.264  3258  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-24 21:18:08.264  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-24 21:18:08.274  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
03-24 21:18:08.275  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 21:18:08.275  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 21:18:08.275  3258  3314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-24 21:18:08.280  2145  2210 D BtGatt.GattService: registerClient() - UUID=2fea6dca-bc19-48fe-99f7-3ad238b02205
03-24 21:18:08.280  2145  2208 D BtGatt.GattService: onClientRegistered() - UUID=2fea6dca-bc19-48fe-99f7-3ad238b02205, clientIf=5
,03-24 21:18:08.281  3258  3275 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 21:18:08.282  2145  2164 D BtGatt.GattService: start scan with filters
,03-24 21:18:08.282  2145  2223 D BtGatt.ScanManager: handling starting scan
,03-24 21:18:08.283  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 21:18:08.283  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 21:18:08.283  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,03-24 21:18:08.283  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-24 21:18:08.283  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 21:18:08.283  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,03-24 21:18:08.283  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,03-24 21:18:08.283  3258  3314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 21:18:08.283  3258  3258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 21:18:08.284  3258  3314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 21:18:08.284  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 21:18:08.284  3258  3314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-24 21:18:08.286  2145  2208 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,03-24 21:18:08.286  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:18:08.288  2145  2208 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 21:18:08.288  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:18:08.288  2145  2223 D BtGatt.ScanManager: Starting BLE batch scan
03-24 21:18:08.288  2145  2223 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 21:18:08.290  2145  2208 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 21:18:08.290  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:18:08.292  2145  2208 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 21:18:08.292  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:18:08.294  2145  2210 D BtGatt.GattService: registerClient() - UUID=1671d305-d467-475f-aa0f-5c6542836f3d
03-24 21:18:08.294  2145  2208 D BtGatt.GattService: onClientRegistered() - UUID=1671d305-d467-475f-aa0f-5c6542836f3d, clientIf=6
,03-24 21:18:08.294  3258  3274 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-24 21:18:08.295  2145  2221 D BtGatt.AdvertiseManager: message : 0
,03-24 21:18:08.299  2145  2221 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 21:18:08.305  2145  2208 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 21:18:08.307  2145  2208 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 21:18:08.308  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-24 21:18:08.308  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-24 21:18:08.308   820  3100 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 21:18:08.310  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-24 21:18:08.310  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-24 21:18:08.310  3258  3314 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-24 21:18:08.310  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 21:18:08.311  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-24 21:18:08.311  3258  3314 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-24 21:18:08.311  3258  3314 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-24 21:18:08.311  3258  3314 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-24 21:18:08.311  3258  3314 I io.jxcore.node.ConnectionHelper: start: OK
03-24 21:18:08.311  3258  3258 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,03-24 21:18:08.312  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,03-24 21:18:08.312  3258  3258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-24 21:18:08.312  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-24 21:18:08.312  3258  3258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-24 21:18:08.312   820   836 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 21:18:08.312  3258  3258 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-24 21:18:08.312  3258  3258 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 21:18:08.312  3258  3258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 21:18:08.312  3258  3258 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-24 21:18:08.313  3258  3258 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-24 21:18:08.313  3258  3258 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-24 21:18:08.313  3258  3743 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-24 21:18:08.313  3258  3258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-24 21:18:08.315  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 21:18:08.315  3258  3314 I jxcore-log: 
03-24 21:18:08.316  3258  3743 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-24 21:18:08.317  3258  3314 I jxcore-log: ok 174 Can call startUpdateAdvertisingAndListening without error
03-24 21:18:08.317  3258  3314 I jxcore-log: 
,03-24 21:18:08.319  3258  3314 I io.jxcore.node.ConnectionHelper: start: Port number: 41828, start advertisements: false
,03-24 21:18:08.319  3258  3314 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 21:18:08.319  3258  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should affect listening to advertisements only
03-24 21:18:08.319  3258  3314 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 21:18:08.319  3258  3314 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 21:18:08.320  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 21:18:08.320  3258  3314 I jxcore-log: 
03-24 21:18:08.321  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-24 21:18:08.321  3258  3314 I jxcore-log: 
03-24 21:18:08.321  3258  3314 I jxcore-log: ok 175 Can call startListeningForAdvertisements without error
03-24 21:18:08.321  3258  3314 I jxcore-log: 
,03-24 21:18:10.059  2145  2206 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,03-24 21:18:10.270  2145  2242 W bt-btif : new conn_srvc id:26, app_id:255
,03-24 21:18:10.270  2145  2242 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:255
03-24 21:18:10.270  2145  2242 W bt-btif : bta_dm_pm_ssr:2, lat:1200
03-24 21:18:10.271  3258  3743 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection accepted
,03-24 21:18:10.274  3258  3743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection initialized (thread ID: 355)
,03-24 21:18:10.275  3258  3744 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 355)
,03-24 21:18:10.275  3258  3743 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-24 21:18:10.277   820  1362 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 21:18:10.280  3258  3743 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-24 21:18:10.286  3258  3743 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-24 21:18:10.317  3258  3744 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesRead: Read 15 bytes successfully (thread ID: 355)
,03-24 21:18:10.321  3258  3744 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Got valid identity from [<no peer name> E0:DB:10:14:E2:C0]
,03-24 21:18:10.321  3258  3744 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesWritten: 15 bytes successfully written (thread ID: 355)
,03-24 21:18:10.321  3258  3744 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: removeThreadFromList: Removing thread with ID 355
03-24 21:18:10.322  3258  3744 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Handshake thread disposed (thread ID: 355)
03-24 21:18:10.322  3258  3744 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onIncomingConnectionConnected: [<no peer name> E0:DB:10:14:E2:C0]
,03-24 21:18:10.324  3258  3258 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> E0:DB:10:14:E2:C0],
,03-24 21:18:10.324  3258  3258 I io.jxcore.node.ConnectionHelper: onConnected: Incoming connection to peer [<no peer name> E0:DB:10:14:E2:C0]
,03-24 21:18:10.325  3258  3258 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> E0:DB:10:14:E2:C0], added - the peer count is 1
03-24 21:18:10.326  3258  3258 I io.jxcore.node.ConnectionHelper: lowerBleDiscoveryPowerAndStartResetTimer: Lowering the power settings
03-24 21:18:10.326  3258  3258 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 2 -> 0
03-24 21:18:10.327  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:,
03-24 21:18:10.327  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 21:18:10.327  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-24 21:18:10.327  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-24 21:18:10.327  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-24 21:18:10.327  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-24 21:18:10.328  3258  3744 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 355)
03-24 21:18:10.333  2145  2221 D BtGatt.AdvertiseManager: message : 1
,03-24 21:18:10.334  2145  2221 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-24 21:18:10.340  2145  2208 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 21:18:10.340  2145  2208 D BtGatt.GattService: Client app is not null!
,03-24 21:18:10.342  2145  2166 D BtGatt.GattService: unregisterClient() - clientIf=6,
03-24 21:18:10.344  3258  3258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 21:18:10.344  3258  3258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED,
,03-24 21:18:10.345  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 3, timeout: 0, is connectable: false,
03-24 21:18:10.345  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 21:18:10.345  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,03-24 21:18:10.345  3258  3258 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
,03-24 21:18:10.346  3258  3258 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 21:18:10.346  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-24 21:18:10.346  3258  3258 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-24 21:18:10.352  2145  2164 D BtGatt.GattService: registerClient() - UUID=87063675-8c80-47e6-8df8-fb4240428e60
03-24 21:18:10.353  2145  2208 D BtGatt.GattService: onClientRegistered() - UUID=87063675-8c80-47e6-8df8-fb4240428e60, clientIf=6
03-24 21:18:10.353  3258  3275 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6,
,03-24 21:18:10.354  2145  2221 D BtGatt.AdvertiseManager: message : 0
03-24 21:18:10.357  2145  2221 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 21:18:10.360  2145  2208 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 21:18:10.363  2145  2208 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0,
03-24 21:18:10.364  3258  3258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-24 21:18:10.366  2145  2164 D BtGatt.GattService: stopScan() - queue size =1,
,03-24 21:18:10.367  2145  2208 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16,
03-24 21:18:10.368  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 21:18:10.368  2145  2223 D BtGatt.ScanManager: stopping BLe Batch
,03-24 21:18:10.368  2145  2166 D BtGatt.GattService: unregisterClient() - clientIf=5,
03-24 21:18:10.369  2145  2208 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0,
03-24 21:18:10.369  3258  3258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 21:18:10.369  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 21:18:10.369  3258  3258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-24 21:18:10.369  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0,
03-24 21:18:10.369  2145  2223 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 21:18:10.370  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-24 21:18:10.370  3258  3258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 21:18:10.370  3258  3258 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 21:18:10.372  2145  2208 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2,
03-24 21:18:10.372  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:18:10.372  2145  2208 D BtGatt.GattService: current time is 272009558697
03-24 21:18:10.372  2145  2208 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -59, 5, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0, -103, 65, -3, 62, -92, 111, 1, -128, -80, 4, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,03-24 21:18:10.373  2145  2208 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-24 21:18:10.374  2145  2208 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 21:18:10.378  2145  2164 D BtGatt.GattService: registerClient() - UUID=a9545340-7fd9-469d-a110-16bbadd89d4a,
03-24 21:18:10.378  2145  2208 D BtGatt.GattService: onClientRegistered() - UUID=a9545340-7fd9-469d-a110-16bbadd89d4a, clientIf=5
,03-24 21:18:10.379  3258  3275 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5,
,03-24 21:18:10.379  2145  2210 D BtGatt.GattService: start scan with filters
03-24 21:18:10.380  2145  2223 D BtGatt.ScanManager: handling starting scan,
03-24 21:18:10.380  3258  3258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 21:18:10.380  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 21:18:10.380  3258  3258 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 3 -> 1
03-24 21:18:10.380  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 21:18:10.380  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 21:18:10.380  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-24 21:18:10.380  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-24 21:18:10.380  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-24 21:18:10.380  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-24 21:18:10.383  2145  2221 D BtGatt.AdvertiseManager: message : 1
,03-24 21:18:10.383  2145  2208 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 21:18:10.383  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:18:10.384  2145  2221 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-24 21:18:10.385  2145  2208 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 21:18:10.385  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:18:10.385  2145  2223 D BtGatt.ScanManager: Starting BLE batch scan
03-24 21:18:10.385  2145  2223 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 21:18:10.387  2145  2208 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,03-24 21:18:10.387  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 21:18:10.388  2145  2208 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,03-24 21:18:10.389  2145  2208 D BtGatt.GattService: Client app is not null!
03-24 21:18:10.390  2145  2164 D BtGatt.GattService: unregisterClient() - clientIf=6
03-24 21:18:10.391  2145  2208 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 21:18:10.391  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:18:10.391  3258  3258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 21:18:10.391  3258  3258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-24 21:18:10.391  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-24 21:18:10.391  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,03-24 21:18:10.391  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 21:18:10.391  3258  3258 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 21:18:10.392  3258  3258 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 21:18:10.392  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-24 21:18:10.392  3258  3258 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-24 21:18:10.396  2145  2210 D BtGatt.GattService: registerClient() - UUID=6b64f7e8-9d89-4837-ade6-0683e243dbaf,
03-24 21:18:10.397  2145  2208 D BtGatt.GattService: onClientRegistered() - UUID=6b64f7e8-9d89-4837-ade6-0683e243dbaf, clientIf=6
,03-24 21:18:10.397  3258  3275 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-24 21:18:10.399  2145  2221 D BtGatt.AdvertiseManager: message : 0
,03-24 21:18:10.401  2145  2221 D BtGatt.AdvertiseManager: starting multi advertising,
,03-24 21:18:10.404  2145  2208 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 21:18:10.406  2145  2208 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 21:18:10.407  3258  3258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-24 21:18:10.409  2145  2210 D BtGatt.GattService: stopScan() - queue size =1
,03-24 21:18:10.410  2145  2166 D BtGatt.GattService: unregisterClient() - clientIf=5
03-24 21:18:10.410  3258  3258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 21:18:10.410  3258  3258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 21:18:10.410  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-24 21:18:10.410  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 21:18:10.410  3258  3258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 21:18:10.410  3258  3258 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-24 21:18:10.411  2145  2208 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 21:18:10.411  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:18:10.411  2145  2223 D BtGatt.ScanManager: stopping BLe Batch
,03-24 21:18:10.414  2145  2208 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0,
03-24 21:18:10.414  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:18:10.414  2145  2223 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 21:18:10.415  2145  2164 D BtGatt.GattService: registerClient() - UUID=84a0dc48-fa56-4670-ad0d-727178a6f299
03-24 21:18:10.416  2145  2208 D BtGatt.GattService: onClientRegistered() - UUID=84a0dc48-fa56-4670-ad0d-727178a6f299, clientIf=5,
03-24 21:18:10.416  2145  2208 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 21:18:10.416  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:18:10.416  3258  3275 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 21:18:10.416  2145  2210 D BtGatt.GattService: start scan with filters
,03-24 21:18:10.417  3258  3258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 21:18:10.417  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-24 21:18:10.417  3258  3258 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 2 -> 0,
03-24 21:18:10.418  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:,
03-24 21:18:10.418  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 21:18:10.418  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-24 21:18:10.418  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-24 21:18:10.418  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-24 21:18:10.418  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-24 21:18:10.420  2145  2221 D BtGatt.AdvertiseManager: message : 1
03-24 21:18:10.420  2145  2221 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-24 21:18:10.423  2145  2208 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 21:18:10.423  2145  2208 D BtGatt.GattService: Client app is not null!
03-24 21:18:10.425  2145  2210 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-24 21:18:10.426  3258  3258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-24 21:18:10.426  3258  3258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-24 21:18:10.426  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-24 21:18:10.426  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 21:18:10.426  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 21:18:10.426  3258  3258 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 21:18:10.426  3258  3258 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false],
03-24 21:18:10.427  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false],
03-24 21:18:10.427  3258  3258 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-24 21:18:10.430  2145  2223 D BtGatt.ScanManager: handling starting scan
,03-24 21:18:10.432  2145  2208 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,03-24 21:18:10.432  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 21:18:10.434  2145  2166 D BtGatt.GattService: registerClient() - UUID=c6f9a5ea-d676-4bce-aa45-aa519b8bac39
03-24 21:18:10.434  2145  2208 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,03-24 21:18:10.434  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 21:18:10.434  2145  2208 D BtGatt.GattService: onClientRegistered() - UUID=c6f9a5ea-d676-4bce-aa45-aa519b8bac39, clientIf=6
03-24 21:18:10.435  2145  2223 D BtGatt.ScanManager: Starting BLE batch scan
03-24 21:18:10.435  2145  2223 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-24 21:18:10.435  3258  3275 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-24 21:18:10.437  2145  2208 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 21:18:10.437  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 21:18:10.438  2145  2221 D BtGatt.AdvertiseManager: message : 0
,03-24 21:18:10.438  2145  2208 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 21:18:10.438  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 21:18:10.441  2145  2221 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 21:18:10.444  2145  2208 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 21:18:10.446  2145  2208 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 21:18:10.446  3258  3258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-24 21:18:10.448  2145  2166 D BtGatt.GattService: stopScan() - queue size =1
,03-24 21:18:10.449  2145  2164 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-24 21:18:10.449  3258  3258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 21:18:10.449  3258  3258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 21:18:10.449  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-24 21:18:10.449  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 21:18:10.449  3258  3258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 21:18:10.449  3258  3258 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-24 21:18:10.449  2145  2208 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 21:18:10.449  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 21:18:10.450  2145  2223 D BtGatt.ScanManager: stopping BLe Batch
03-24 21:18:10.452  2145  2210 D BtGatt.GattService: registerClient() - UUID=793c8c29-c716-44af-bf86-d6e319a99b12
03-24 21:18:10.452  2145  2208 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 21:18:10.452  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 21:18:10.453  2145  2208 D BtGatt.GattService: onClientRegistered() - UUID=793c8c29-c716-44af-bf86-d6e319a99b12, clientIf=5
03-24 21:18:10.453  3258  3275 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-24 21:18:10.453  2145  2223 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5,
03-24 21:18:10.453  2145  2166 D BtGatt.GattService: start scan with filters
,03-24 21:18:10.454  3258  3258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 21:18:10.454  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-24 21:18:10.454  2145  2208 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 21:18:10.454  3258  3258 I io.jxcore.node.ConnectionHelper: onConnected: Incoming socket thread, for peer [<no peer name> E0:DB:10:14:E2:C0], created successfully,
03-24 21:18:10.454  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:18:10.454  3258  3258 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 1,
03-24 21:18:10.454  3258  3258 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> E0:DB:10:14:E2:C0], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 
03-24 21:18:10.455  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess,
03-24 21:18:10.455  3258  3258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,03-24 21:18:10.455  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,03-24 21:18:10.455  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 21:18:10.455  3258  3745 D io.jxcore.node.IncomingSocketThread: Entering thread (ID: 356)
,03-24 21:18:10.455  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,03-24 21:18:10.458  3258  3745 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 41828
03-24 21:18:10.458  3258  3745 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,03-24 21:18:10.459  3258  3745 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-24 21:18:10.459  3258  3745 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
,03-24 21:18:10.459  3258  3745 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 356)
03-24 21:18:10.459  3258  3745 D io.jxcore.node.IncomingSocketThread: Exiting thread (ID: 356)
,03-24 21:18:10.460  2145  2223 D BtGatt.ScanManager: handling starting scan
03-24 21:18:10.461  3258  3314 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID E0:DB:10:14:E2:C0,
03-24 21:18:10.461  3258  3314 I io.jxcore.node.ConnectionHelper: connect: We already have an incoming connection to peer with ID E0:DB:10:14:E2:C0, but will connect anyway...
,03-24 21:18:10.461  3258  3314 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> E0:DB:10:14:E2:C0]
,03-24 21:18:10.462  2145  2208 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,03-24 21:18:10.462  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:18:10.463  2145  2208 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15,
03-24 21:18:10.463  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
,03-24 21:18:10.463  2145  2223 D BtGatt.ScanManager: Starting BLE batch scan
03-24 21:18:10.463  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to Note4-1 in address E0:DB:10:14:E2:C0
,03-24 21:18:10.463  2145  2223 D BtGatt.ScanManager: configuring batch scan storage, appIf 5,
,03-24 21:18:10.464  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
03-24 21:18:10.464  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,03-24 21:18:10.464  3258  3747 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 357, name: Sender)
03-24 21:18:10.464  3258  3314 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: Note4-1 E0:DB:10:14:E2:C0
03-24 21:18:10.464  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to Note4-1 in address E0:DB:10:14:E2:C0
,03-24 21:18:10.464  3258  3314 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: E0:DB:10:14:E2:C0)
03-24 21:18:10.465  2145  2208 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 21:18:10.465  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 21:18:10.466  2145  2208 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 21:18:10.466  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:18:10.468  3258  3749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address E0:DB:10:14:E2:C0 (thread ID: 359)
03-24 21:18:10.468  3258  3749 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-24 21:18:10.470  2145  2210 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66,
03-24 21:18:10.475  3258  3748 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 358, name: Receiver)
,03-24 21:18:10.524  2145  2242 W bt-sdp  : process_service_search_attr_rsp,
,03-24 21:18:10.568  2145  2242 W bt-btif : new conn_srvc id:26, app_id:1,
03-24 21:18:10.569  2145  2242 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:255
03-24 21:18:10.569  2145  2242 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:1
,03-24 21:18:10.569  2145  2242 W bt-btif : bta_dm_pm_ssr:2, lat:1200
03-24 21:18:10.569  3258  3749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onSocketConnected: [<no peer name> E0:DB:10:14:E2:C0] (thread ID: 359)
03-24 21:18:10.569  3258  3749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 359)
03-24 21:18:10.572  3258  3749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesWritten: 15 bytes successfully written (thread ID: 360)
03-24 21:18:10.572  3258  3749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Outgoing connection initialized (*handshake* thread ID: 360)
,03-24 21:18:10.572  3258  3749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 359)
,03-24 21:18:10.576  3258  3750 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 360)
,03-24 21:18:10.590  3258  3750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesRead: Read 15 bytes successfully (thread ID: 360)
,03-24 21:18:10.593  3258  3750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Handshake succeeded with [<no peer name> E0:DB:10:14:E2:C0]
03-24 21:18:10.594  3258  3750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onHandshakeSucceeded: [<no peer name> E0:DB:10:14:E2:C0] (thread ID: 359)
03-24 21:18:10.594  3258  3750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: handleSuccessfulClientThread: [<no peer name> E0:DB:10:14:E2:C0] (thread ID: 359)
,03-24 21:18:10.594  3258  3750 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 360),
03-24 21:18:10.594  3258  3258 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> E0:DB:10:14:E2:C0]
03-24 21:18:10.595  3258  3258 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing connection to peer [<no peer name> E0:DB:10:14:E2:C0]
03-24 21:18:10.595  3258  3258 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> E0:DB:10:14:E2:C0] updated - the peer count is 1
03-24 21:18:10.596  3258  3258 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing socket thread, for peer [<no peer name> E0:DB:10:14:E2:C0], created successfully
03-24 21:18:10.596  3258  3258 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 2
,03-24 21:18:10.598  3258  3751 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 361)
03-24 21:18:10.599  3258  3751 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 43479
03-24 21:18:10.599  3258  3751 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
03-24 21:18:10.599  3258  3751 I io.jxcore.node.ConnectionHelper: onListeningForIncomingConnections: Outgoing connection is using port 43479 (peer ID: E0:DB:10:14:E2:C0)
03-24 21:18:10.599  3258  3751 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "E0:DB:10:14:E2:C0" removed
,03-24 21:18:10.604  3258  3314 I jxcore-log: INFO testThaliMobileNative: 
03-24 21:18:10.604  3258  3314 I jxcore-log: 
,03-24 21:18:10.607  3258  3314 I jxcore-log: INFO testThaliMobileNative: Forward connection
03-24 21:18:10.607  3258  3314 I jxcore-log: 
,03-24 21:18:10.614  3258  3751 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 43479
,03-24 21:18:10.615  3258  3751 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
03-24 21:18:10.615  3258  3751 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-24 21:18:10.615  3258  3751 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-24 21:18:10.615  3258  3751 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 361)
03-24 21:18:10.615  3258  3751 D io.jxcore.node.OutgoingSocketThread: Exiting thread (ID: 361)
,03-24 21:18:10.618  3258  3752 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 362, name: Sender)
,03-24 21:18:10.620  3258  3753 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 363, name: Receiver)
,03-24 21:18:10.625  3258  3314 I jxcore-log: INFO testThaliMobileNative: forwardSend,
03-24 21:18:10.625  3258  3314 I jxcore-log: 
,03-24 21:18:10.937  3258  3314 I jxcore-log: INFO testThaliMobileNative: forwardData
03-24 21:18:10.937  3258  3314 I jxcore-log: 
,03-24 21:18:10.948  3258  3314 I jxcore-log: INFO testThaliMobileNative: forwardData,
03-24 21:18:10.948  3258  3314 I jxcore-log: 
,03-24 21:18:10.955  3258  3314 I jxcore-log: INFO testThaliMobileNative: forwardData
03-24 21:18:10.955  3258  3314 I jxcore-log: 
,03-24 21:18:10.959  3258  3314 I jxcore-log: ok 176 received should match sent forward
03-24 21:18:10.959  3258  3314 I jxcore-log: 
,03-24 21:18:10.974  3258  3314 I jxcore-log: # teardown
03-24 21:18:10.974  3258  3314 I jxcore-log: 
,03-24 21:18:14.808  2145  2242 W bt-btif : info:x10
03-24 21:18:14.808  2145  2208 D         : remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
03-24 21:18:14.809  2145  2208 E BluetoothRemoteDevices: aclStateChangeCallback: Device is NULL
,03-24 21:18:15.026  2145  2242 E bt-btm  : tBTM_SEC_DEV:0xaf17beb4 rs_disc_pending=1
03-24 21:18:15.026  2145  2242 W bt-btif : bta_dm_check_av:0
03-24 21:18:15.027  2145  2208 W bt-btif : btif_dm_cback : unhandled event (14)
,03-24 21:18:15.146  2145  2208 D btif_config: btif_get_device_type: Device [f8:95:c7:87:3c:51] type 1
,03-24 21:18:15.153  2145  2208 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
,03-24 21:18:15.153  2145  2208 E bt-btif : check_cod: remote_cod = 0x5a020c
,03-24 21:18:15.159  2145  2209 I BluetoothBondStateMachine: Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
,03-24 21:18:15.159  2145  2209 I BluetoothBondStateMachine: Entering PendingCommandState State
,03-24 21:18:15.257  2145  2208 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
03-24 21:18:15.257  2145  2209 D BluetoothAdapterProperties: Failed to remove device: F8:95:C7:87:3C:51
,03-24 21:18:15.260  2145  2209 I BluetoothBondStateMachine: Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,03-24 21:18:15.274  2145  2209 I BluetoothBondStateMachine: StableState(): Entering Off State
,03-24 21:18:15.303  2145  2242 W bt-btif : new conn_srvc id:26, app_id:255
,03-24 21:18:15.303  2145  2242 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:255
03-24 21:18:15.303  2145  2242 W bt-btif : bta_dm_pm_ssr:2, lat:1200
,03-24 21:18:15.304  3258  3743 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection accepted
03-24 21:18:15.304  3258  3743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection initialized (thread ID: 364)
,03-24 21:18:15.305  3258  3743 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-24 21:18:15.305   820   836 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 21:18:15.307  3258  3755 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 364)
03-24 21:18:15.308  3258  3743 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-24 21:18:15.310  3258  3743 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-24 21:18:15.320  3258  3755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesRead: Read 15 bytes successfully (thread ID: 364)
,03-24 21:18:15.323  3258  3755 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Got valid identity from [<no peer name> F8:95:C7:87:3C:51]
,03-24 21:18:15.324  3258  3755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesWritten: 15 bytes successfully written (thread ID: 364)
03-24 21:18:15.324  3258  3755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: removeThreadFromList: Removing thread with ID 364
03-24 21:18:15.324  3258  3755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Handshake thread disposed (thread ID: 364)
03-24 21:18:15.324  3258  3755 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onIncomingConnectionConnected: [<no peer name> F8:95:C7:87:3C:51]
03-24 21:18:15.324  3258  3755 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 364)
03-24 21:18:15.324  3258  3258 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> F8:95:C7:87:3C:51]
03-24 21:18:15.324  3258  3258 I io.jxcore.node.ConnectionHelper: onConnected: Incoming connection to peer [<no peer name> F8:95:C7:87:3C:51]
03-24 21:18:15.325  3258  3258 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 2
03-24 21:18:15.325  3258  3258 I io.jxcore.node.ConnectionHelper: onConnected: Incoming socket thread, for peer [<no peer name> F8:95:C7:87:3C:51], created successfully
03-24 21:18:15.325  3258  3258 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 3
,03-24 21:18:15.326  3258  3258 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
03-24 21:18:15.327  3258  3756 D io.jxcore.node.IncomingSocketThread: Entering thread (ID: 365)
,03-24 21:18:15.334  3258  3756 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 41828
,03-24 21:18:15.334  3258  3756 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
03-24 21:18:15.334  3258  3756 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-24 21:18:15.335  3258  3756 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-24 21:18:15.337  3258  3758 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 366, name: Sender)
,03-24 21:18:15.338  3258  3756 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 365)
,03-24 21:18:15.338  3258  3756 D io.jxcore.node.IncomingSocketThread: Exiting thread (ID: 365)
,03-24 21:18:15.341  3258  3759 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 367, name: Receiver)
,03-24 21:18:15.471  2145  2145 D BtGatt.ScanManager: awakened up at time 277108
,03-24 21:18:15.473  2145  2223 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 21:18:15.476  2145  2208 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,03-24 21:18:15.476  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 21:18:15.698  2145  2349 W bt-btif : invalid rfc slot id: 13
,03-24 21:18:15.699  3258  3759 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 367, thread name: Receiver): bt socket closed, read return: -1
03-24 21:18:15.699  3258  3759 E io.jxcore.node.IncomingSocketThread: The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
,03-24 21:18:15.699  3258  3759 W io.jxcore.node.ConnectionHelper: onDisconnected: Incoming connection, peer [<no peer name> F8:95:C7:87:3C:51] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
03-24 21:18:15.699  3258  3759 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 365
03-24 21:18:15.700  3258  3759 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 365)
,03-24 21:18:15.700  3258  3759 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
03-24 21:18:15.700  3258  3759 D io.jxcore.node.IncomingSocketThread: close: Stopping receiving thread...
,03-24 21:18:15.700  3258  3759 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 367
03-24 21:18:15.700  3258  3759 D io.jxcore.node.IncomingSocketThread: close: Stopping sending thread...
03-24 21:18:15.700  3258  3759 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 366
03-24 21:18:15.700  3258  3759 D io.jxcore.node.IncomingSocketThread: closeLocalSocketAndStreams: Closing... (thread ID: 365)
03-24 21:18:15.705  3258  3759 I io.jxcore.node.IncomingSocketThread: close: Complete (thread ID: 365)
,03-24 21:18:15.705  3258  3759 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
03-24 21:18:15.706  3258  3758 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 366, thread name: Sender): Socket closed
03-24 21:18:15.706  3258  3758 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 366, name: Sender)
,03-24 21:18:15.712  3258  3759 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 367, name: Receiver)
,03-24 21:18:15.720  3258  3314 I jxcore-log: INFO thaliMobileNativeWrapper: incomingConnectionToPortNumberFailed: %s
03-24 21:18:15.720  3258  3314 I jxcore-log: 
,03-24 21:18:15.722  3258  3314 I jxcore-log: INFO thaliMobileNativeWrapper: got incomingConnectionToPortNumberFailed while not in start
03-24 21:18:15.722  3258  3314 I jxcore-log: 
,03-24 21:18:15.735  2145  2242 W bt-rfcomm: rfc_find_lcid_mcb LCID reused LCID:0x46 current:0x0
,03-24 21:18:15.735  2145  2242 W bt-rfcomm: RFCOMM_DisconnectInd LCID:0x46
,03-24 21:18:16.299  2145  2349 W bt-btif : invalid rfc slot id: 14
,03-24 21:18:16.300  3258  3753 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 363, thread name: Receiver): bt socket closed, read return: -1
03-24 21:18:16.300  3258  3753 E io.jxcore.node.OutgoingSocketThread: The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected,
03-24 21:18:16.301  3258  3753 W io.jxcore.node.ConnectionHelper: onDisconnected: Outgoing connection, peer [<no peer name> E0:DB:10:14:E2:C0] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
03-24 21:18:16.302  2145  2349 W bt-btif : invalid rfc slot id: 11
03-24 21:18:16.303  3258  3748 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 358, thread name: Receiver): bt socket closed, read return: -1
03-24 21:18:16.303  3258  3748 E io.jxcore.node.IncomingSocketThread: The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
03-24 21:18:16.303  3258  3748 W io.jxcore.node.ConnectionHelper: onDisconnected: Incoming connection, peer [<no peer name> E0:DB:10:14:E2:C0] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,03-24 21:18:16.302  3258  3753 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: E0:DB:10:14:E2:C0
,03-24 21:18:16.306  3258  3753 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 361)
,03-24 21:18:16.307  3258  3753 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 361)
,03-24 21:18:16.312  3258  3753 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed,
,03-24 21:18:16.312  3258  3753 D io.jxcore.node.OutgoingSocketThread: close: Stopping receiving thread...
03-24 21:18:16.312  3258  3753 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 363
,03-24 21:18:16.312  3258  3753 D io.jxcore.node.OutgoingSocketThread: close: Stopping sending thread...
03-24 21:18:16.312  3258  3753 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 362
03-24 21:18:16.312  3258  3753 D io.jxcore.node.OutgoingSocketThread: closeLocalSocketAndStreams: Closing... (thread ID: 361)
03-24 21:18:16.313  3258  3753 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 361)
,03-24 21:18:16.313  3258  3753 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
03-24 21:18:16.314  3258  3748 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 356
03-24 21:18:16.314  3258  3752 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 362, thread name: Sender): Socket closed
03-24 21:18:16.314  3258  3748 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 356)
,03-24 21:18:16.314  3258  3752 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 362, name: Sender)
03-24 21:18:16.314  3258  3748 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
03-24 21:18:16.314  3258  3748 D io.jxcore.node.IncomingSocketThread: close: Stopping receiving thread...
03-24 21:18:16.314  3258  3748 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 358
,03-24 21:18:16.314  3258  3748 D io.jxcore.node.IncomingSocketThread: close: Stopping sending thread...
03-24 21:18:16.315  3258  3748 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 357
03-24 21:18:16.315  3258  3748 D io.jxcore.node.IncomingSocketThread: closeLocalSocketAndStreams: Closing... (thread ID: 356)
03-24 21:18:16.316  3258  3747 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 357, thread name: Sender): Socket closed
,03-24 21:18:16.316  3258  3747 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 357, name: Sender)
03-24 21:18:16.318  3258  3748 I io.jxcore.node.IncomingSocketThread: close: Complete (thread ID: 356)
03-24 21:18:16.318  3258  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
03-24 21:18:16.319  3258  3748 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 358, name: Receiver)
,03-24 21:18:16.321  3258  3753 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 363, name: Receiver)
03-24 21:18:16.325  3258  3314 I jxcore-log: INFO thaliMobileNativeWrapper: incomingConnectionToPortNumberFailed: %s
03-24 21:18:16.325  3258  3314 I jxcore-log: 
03-24 21:18:16.328  3258  3314 I jxcore-log: INFO thaliMobileNativeWrapper: got incomingConnectionToPortNumberFailed while not in start
03-24 21:18:16.328  3258  3314 I jxcore-log: 
,03-24 21:18:16.335  3258  3314 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 21:18:16.335  3258  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
,03-24 21:18:16.335  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-24 21:18:16.335  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-24 21:18:16.337  2145  2164 D BtGatt.GattService: stopScan() - queue size =1
,03-24 21:18:16.345  2145  2166 D BtGatt.GattService: unregisterClient() - clientIf=5,
03-24 21:18:16.345  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 21:18:16.345  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-24 21:18:16.345  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-24 21:18:16.345  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
,03-24 21:18:16.345  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-24 21:18:16.345  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 21:18:16.346  3258  3258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true,
03-24 21:18:16.346  3258  3258 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
03-24 21:18:16.346  3258  3258 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-24 21:18:16.346  2145  2208 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 21:18:16.346  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:18:16.347  2145  2223 D BtGatt.ScanManager: stopping BLe Batch
03-24 21:18:16.348  3258  3314 I jxcore-log: ok 177 Should be able to call stopListeningForAdvertisments in teardown
03-24 21:18:16.348  3258  3314 I jxcore-log: 
03-24 21:18:16.348  3258  3314 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-24 21:18:16.349  3258  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
03-24 21:18:16.349  3258  3314 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-24 21:18:16.349  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-24 21:18:16.349  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-24 21:18:16.349  3258  3314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-24 21:18:16.349  3258  3743 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-24 21:18:16.349  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-24 21:18:16.349  3258  3743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-24 21:18:16.349  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-24 21:18:16.349  3258  3743 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-24 21:18:16.349  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 21:18:16.349  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 21:18:16.349  3258  3258 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-24 21:18:16.349  3258  3258 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-24 21:18:16.349  3258  3258 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-24 21:18:16.349  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-24 21:18:16.350  2145  2208 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 21:18:16.350  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:18:16.350  2145  2223 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 21:18:16.351  2145  2208 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 21:18:16.351  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:18:16.351  3258  3314 D BluetoothLeScanner: could not find callback wrapper
03-24 21:18:16.351  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 21:18:16.351  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,03-24 21:18:16.358  2145  2221 D BtGatt.AdvertiseManager: message : 1,
03-24 21:18:16.358  2145  2221 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-24 21:18:16.360  2145  2208 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 21:18:16.361  2145  2208 D BtGatt.GattService: Client app is not null!
,03-24 21:18:16.361  2145  2210 D BtGatt.GattService: unregisterClient() - clientIf=6
03-24 21:18:16.362  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 21:18:16.362  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-24 21:18:16.362  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,03-24 21:18:16.362  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-24 21:18:16.362  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,03-24 21:18:16.362  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 21:18:16.362  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 21:18:16.362  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-24 21:18:16.362  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-24 21:18:16.362  3258  3314 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-24 21:18:16.362  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 21:18:16.363  3258  3258 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 21:18:16.363  3258  3258 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 21:18:16.363  3258  3258 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 21:18:16.363  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-24 21:18:16.363  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-24 21:18:16.367  3258  3258 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-24 21:18:16.368  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-24 21:18:16.368  3258  3314 I jxcore-log: 
03-24 21:18:16.368   820  1332 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 21:18:16.370  3258  3314 I jxcore-log: ok 178 Should be able to call stopAdvertisingAndListening in teardown
03-24 21:18:16.370  3258  3314 I jxcore-log: 
03-24 21:18:16.372  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
,03-24 21:18:16.373  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-24 21:18:16.373  3258  3258 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 21:18:16.376  3258  3258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-24 21:18:16.376  3258  3258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-24 21:18:16.383  3258  3314 I jxcore-log: # setup
03-24 21:18:16.383  3258  3314 I jxcore-log: 
,03-24 21:18:16.386  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 21:18:16.386  3258  3314 I jxcore-log: 
,03-24 21:18:16.389  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 21:18:16.389  3258  3314 I jxcore-log: 
,03-24 21:18:16.631  2145  2211 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 21:18:17.051  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 21:18:17.051  3258  3314 I jxcore-log: 
,03-24 21:18:17.056  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 21:18:17.056  3258  3314 I jxcore-log: 
,03-24 21:18:17.068  3258  3314 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 21:18:17.068  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 21:18:17.068  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 21:18:17.068  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 21:18:17.068  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 21:18:17.068  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 21:18:17.068  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 21:18:17.068  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 21:18:17.074  3258  3314 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 21:18:17.078  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 21:18:17.078  3258  3314 I jxcore-log: 
,03-24 21:18:17.082  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 21:18:17.082  3258  3314 I jxcore-log: 
,03-24 21:18:17.090  3258  3314 I jxcore-log: # 42. #startListeningForAdvertisements should fail if start not called
03-24 21:18:17.090  3258  3314 I jxcore-log: 
03-24 21:18:17.094  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 21:18:17.094  3258  3314 I jxcore-log: 
,03-24 21:18:17.803  2145  2242 W bt-rfcomm: rfc_find_lcid_mcb LCID reused LCID:0x43 current:0x0
,03-24 21:18:17.803  2145  2242 W bt-rfcomm: RFCOMM_DisconnectInd LCID:0x43
,03-24 21:18:18.886  3258  3314 I jxcore-log: ok 179 specific error should be returned
03-24 21:18:18.886  3258  3314 I jxcore-log: 
,03-24 21:18:18.892  3258  3314 I jxcore-log: # teardown
03-24 21:18:18.892  3258  3314 I jxcore-log: 
,03-24 21:18:18.987  3258  3314 I jxcore-log: # setup
03-24 21:18:18.987  3258  3314 I jxcore-log: 
,03-24 21:18:19.374  2145  2242 E bt-btm  : btm_sec_disconnected - Clearing Pending flag
,03-24 21:18:19.382  2145  2145 D BluetoothMapService: onReceive
,03-24 21:18:19.473   820  1362 I ActivityManager: Start proc 3761:com.google.android.googlequicksearchbox:search/u0a28 for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver
,03-24 21:18:19.618   820   858 D BluetoothManagerService: Message: 20
03-24 21:18:19.619   820   858 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b7d1547:true
,03-24 21:18:19.631  3761  3761 I BTConnectionReceiver: onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,03-24 21:18:19.804   820  1333 I ActivityManager: Start proc 3783:com.google.android.partnersetup/u0a16 for content provider com.google.android.partnersetup/.RlzAppProvider
,03-24 21:18:19.817  3761  3761 I BluetoothClassifier: Bluetooth Device Name: G4-1
,03-24 21:18:19.827   820   835 I ActivityManager: Killing 3413:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,03-24 21:18:19.911  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 21:18:19.911  3258  3314 I jxcore-log: 
,03-24 21:18:19.916  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 21:18:19.916  3258  3314 I jxcore-log: 
,03-24 21:18:19.927  3258  3314 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 21:18:19.927  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 21:18:19.927  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 21:18:19.927  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 21:18:19.927  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 21:18:19.927  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 21:18:19.927  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 21:18:19.927  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 21:18:19.929  3258  3314 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 21:18:19.930  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 21:18:19.930  3258  3314 I jxcore-log: 
,03-24 21:18:19.931  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 21:18:19.931  3258  3314 I jxcore-log: 
,03-24 21:18:19.933  3258  3314 I jxcore-log: # 43. #startUpdateAdvertisingAndListening should fail if start not called
03-24 21:18:19.933  3258  3314 I jxcore-log: 
,03-24 21:18:19.934  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 21:18:19.934  3258  3314 I jxcore-log: 
,03-24 21:18:19.941   820  1144 I ActivityManager: Killing 3468:com.google.android.apps.magazines/u0a67 (adj 15): empty #17
,03-24 21:18:20.029  3258  3314 I jxcore-log: ok 180 specific error should be returned
03-24 21:18:20.029  3258  3314 I jxcore-log: 
,03-24 21:18:20.036  3258  3314 I jxcore-log: # teardown,
03-24 21:18:20.036  3258  3314 I jxcore-log: ,
,03-24 21:18:20.265  3258  3314 I jxcore-log: # setup
03-24 21:18:20.265  3258  3314 I jxcore-log: 
,03-24 21:18:20.810  2145  2206 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,03-24 21:18:20.873  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 21:18:20.873  3258  3314 I jxcore-log: 
,03-24 21:18:20.877  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,03-24 21:18:20.877  3258  3314 I jxcore-log: 
,03-24 21:18:20.887  3258  3314 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 21:18:20.887  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 21:18:20.887  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 21:18:20.887  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 21:18:20.887  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 21:18:20.887  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 21:18:20.887  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 21:18:20.887  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 21:18:20.891  3258  3314 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 21:18:20.894  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 21:18:20.894  3258  3314 I jxcore-log: 
,03-24 21:18:20.898  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 21:18:20.898  3258  3314 I jxcore-log: 
,03-24 21:18:20.904  3258  3314 I jxcore-log: # 44. should be able to call #stopListeningForAdvertisements many times
03-24 21:18:20.904  3258  3314 I jxcore-log: 
,03-24 21:18:20.908  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 21:18:20.908  3258  3314 I jxcore-log: 
,03-24 21:18:21.811  2145  2242 E bt-btm  : btm_sec_disconnected - Clearing Pending flag
,03-24 21:18:21.818  2145  2145 D BluetoothMapService: onReceive
,03-24 21:18:21.850  3761  3761 I BTConnectionReceiver: onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,03-24 21:18:21.854  3761  3761 I BluetoothClassifier: Bluetooth Device Name: Note4-1
,03-24 21:18:22.467  3258  3314 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 21:18:22.467  3258  3314 I jxcore-log: 
,03-24 21:18:22.469  3258  3314 I jxcore-log: DEBUG createNativeListener: listening 50660
03-24 21:18:22.469  3258  3314 I jxcore-log: 
,03-24 21:18:22.471  3258  3314 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 21:18:22.471  3258  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 21:18:22.471  3258  3314 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 21:18:22.475  3258  3314 I jxcore-log: ok 181 no errors
03-24 21:18:22.475  3258  3314 I jxcore-log: 
,03-24 21:18:22.476  3258  3314 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 21:18:22.476  3258  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 21:18:22.476  3258  3314 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 21:18:22.477  3258  3314 I jxcore-log: ok 182 still no errors
03-24 21:18:22.477  3258  3314 I jxcore-log: 
,03-24 21:18:22.483  3258  3314 I jxcore-log: # teardown
03-24 21:18:22.483  3258  3314 I jxcore-log: 
,03-24 21:18:22.592  3258  3314 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 21:18:22.592  3258  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
03-24 21:18:22.592  3258  3314 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 21:18:22.596  3258  3314 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 21:18:22.596  3258  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 21:18:22.596  3258  3314 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 21:18:22.610  3258  3314 I jxcore-log: # setup
03-24 21:18:22.610  3258  3314 I jxcore-log: 
,03-24 21:18:22.721  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 21:18:22.721  3258  3314 I jxcore-log: 
,03-24 21:18:22.727  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 21:18:22.727  3258  3314 I jxcore-log: 
,03-24 21:18:22.739  3258  3314 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
03-24 21:18:22.739  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 21:18:22.739  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 21:18:22.739  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 21:18:22.739  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 21:18:22.739  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 21:18:22.739  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 21:18:22.739  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 21:18:22.742  3258  3314 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
03-24 21:18:22.744  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 21:18:22.744  3258  3314 I jxcore-log: 
,03-24 21:18:22.745  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 21:18:22.745  3258  3314 I jxcore-log: 
,03-24 21:18:22.748  3258  3314 I jxcore-log: # 45. should be able to call #startListeningForAdvertisements many times
03-24 21:18:22.748  3258  3314 I jxcore-log: 
,03-24 21:18:22.750  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 21:18:22.750  3258  3314 I jxcore-log: 
,03-24 21:18:22.950  3258  3314 I jxcore-log: DEBUG createNativeListener: creating native server,
03-24 21:18:22.950  3258  3314 I jxcore-log: 
,03-24 21:18:22.952  3258  3314 I jxcore-log: DEBUG createNativeListener: listening 40912
03-24 21:18:22.952  3258  3314 I jxcore-log: 
,03-24 21:18:22.959  3258  3314 I io.jxcore.node.ConnectionHelper: start: Port number: 41828, start advertisements: false,
03-24 21:18:22.959  3258  3314 I io.jxcore.node.ConnectionHelper: restoreDefaultBleDiscoverySettings: Powering the BLE discovery back up
03-24 21:18:22.959  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 0 -> 2
03-24 21:18:22.959  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 21:18:22.959  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 21:18:22.959  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2,
03-24 21:18:22.959  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-24 21:18:22.959  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-24 21:18:22.959  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-24 21:18:22.959  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 1, timeout: 0, is connectable: false
03-24 21:18:22.959  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
,03-24 21:18:22.959  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 1 -> 3
03-24 21:18:22.959  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 21:18:22.959  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 21:18:22.959  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-24 21:18:22.959  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-24 21:18:22.959  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-24 21:18:22.959  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-24 21:18:22.960  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-24 21:18:22.960  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-24 21:18:22.960  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 0 -> 2
03-24 21:18:22.960  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 21:18:22.960  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 21:18:22.960  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
,03-24 21:18:22.960  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-24 21:18:22.960  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-24 21:18:22.960  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-24 21:18:22.960  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-24 21:18:22.960  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-24 21:18:22.960  3258  3314 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 21:18:22.960  3258  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 21:18:22.960  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
03-24 21:18:22.967  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-24 21:18:22.967  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 21:18:22.967  3258  3314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 21:18:22.977  2145  2166 D BtGatt.GattService: registerClient() - UUID=7b8086a9-3ca6-477a-97eb-e888478edcb0,
03-24 21:18:22.977  2145  2208 D BtGatt.GattService: onClientRegistered() - UUID=7b8086a9-3ca6-477a-97eb-e888478edcb0, clientIf=5
03-24 21:18:22.978  3258  3275 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-24 21:18:22.980  2145  2210 D BtGatt.GattService: start scan with filters,
,03-24 21:18:22.983  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 21:18:22.983  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 21:18:22.983  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-24 21:18:22.983  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-24 21:18:22.984  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
,03-24 21:18:22.984  2145  2223 D BtGatt.ScanManager: handling starting scan,
03-24 21:18:22.984  3258  3258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 21:18:22.984  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 21:18:22.985   820  1375 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 21:18:22.991  2145  2208 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1,
03-24 21:18:22.991  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:18:22.992  2145  2208 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 21:18:22.992  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 21:18:22.993  2145  2223 D BtGatt.ScanManager: Starting BLE batch scan
,03-24 21:18:22.993  2145  2223 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 21:18:22.994  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 21:18:22.995  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-24 21:18:22.995  3258  3258 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,03-24 21:18:22.995  3258  3258 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-24 21:18:22.996  2145  2208 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 21:18:22.996  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:18:22.996  3258  3258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 21:18:22.996  3258  3314 I io.jxcore.node.ConnectionHelper: start: OK
03-24 21:18:22.997  2145  2208 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 21:18:22.997  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 21:18:23.002  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 21:18:23.002  3258  3314 I jxcore-log: 
,03-24 21:18:23.004  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 21:18:23.004  3258  3314 I jxcore-log: 
,03-24 21:18:23.005  3258  3314 I jxcore-log: ok 183 no errors
03-24 21:18:23.005  3258  3314 I jxcore-log: 
,03-24 21:18:23.009  3258  3314 I io.jxcore.node.ConnectionHelper: start: Port number: 41828, start advertisements: false
,03-24 21:18:23.009  3258  3314 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 21:18:23.009  3258  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 21:18:23.010  3258  3314 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 21:18:23.010  3258  3314 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 21:18:23.013  3258  3314 I jxcore-log: ok 184 still no errors
03-24 21:18:23.013  3258  3314 I jxcore-log: 
,03-24 21:18:23.031  3258  3314 I jxcore-log: # teardown
,03-24 21:18:23.031  3258  3314 I jxcore-log: 
,03-24 21:18:23.547  3258  3314 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-24 21:18:23.547  3258  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
03-24 21:18:23.547  3258  3314 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
03-24 21:18:23.547  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-24 21:18:23.547  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-24 21:18:23.547  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 21:18:23.547  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 21:18:23.548  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-24 21:18:23.548  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-24 21:18:23.552  2145  2166 D BtGatt.GattService: stopScan() - queue size =1
,03-24 21:18:23.555  2145  2164 D BtGatt.GattService: unregisterClient() - clientIf=5,
03-24 21:18:23.555  2145  2208 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 21:18:23.555  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
,03-24 21:18:23.556  2145  2223 D BtGatt.ScanManager: stopping BLe Batch
03-24 21:18:23.557  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 21:18:23.557  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 21:18:23.557  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-24 21:18:23.557  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-24 21:18:23.557  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,03-24 21:18:23.558  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 21:18:23.559  2145  2208 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 21:18:23.559  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:18:23.560  2145  2223 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 21:18:23.560  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 21:18:23.560  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,03-24 21:18:23.560  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-24 21:18:23.562  2145  2208 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 21:18:23.563  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:18:23.564  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-24 21:18:23.565  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,03-24 21:18:23.566  3258  3258 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 21:18:23.567  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 21:18:23.567  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-24 21:18:23.579  3258  3258 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
03-24 21:18:23.580   820  1362 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 21:18:23.589  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-24 21:18:23.591  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 21:18:23.591  3258  3258 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 21:18:23.595  3258  3258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-24 21:18:23.595  3258  3258 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-24 21:18:23.595  3258  3258 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-24 21:18:23.595  3258  3258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-24 21:18:23.597  3258  3314 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 21:18:23.597  3258  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 21:18:23.597  3258  3314 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 21:18:23.599  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 21:18:23.599  3258  3314 I jxcore-log: 
03-24 21:18:23.601  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 21:18:23.601  3258  3314 I jxcore-log: 
,03-24 21:18:23.618  3258  3314 I jxcore-log: # setup
03-24 21:18:23.618  3258  3314 I jxcore-log: 
,03-24 21:18:23.724  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 21:18:23.724  3258  3314 I jxcore-log: 
,03-24 21:18:23.725  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 21:18:23.725  3258  3314 I jxcore-log: 
,03-24 21:18:23.732  3258  3314 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 21:18:23.732  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 21:18:23.732  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
,03-24 21:18:23.732  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 21:18:23.732  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 21:18:23.732  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 21:18:23.732  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
,03-24 21:18:23.732  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 21:18:23.736  3258  3314 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
03-24 21:18:23.737  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 21:18:23.737  3258  3314 I jxcore-log: 
,03-24 21:18:23.739  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 21:18:23.739  3258  3314 I jxcore-log: 
,03-24 21:18:23.742  3258  3314 I jxcore-log: # 46. should be able to call #startUpdateAdvertisingAndListening many times
03-24 21:18:23.742  3258  3314 I jxcore-log: 
,03-24 21:18:23.744  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 21:18:23.744  3258  3314 I jxcore-log: 
,03-24 21:18:23.950  3258  3314 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 21:18:23.950  3258  3314 I jxcore-log: 
,03-24 21:18:23.953  3258  3314 I jxcore-log: DEBUG createNativeListener: listening 41977
03-24 21:18:23.953  3258  3314 I jxcore-log: 
,03-24 21:18:23.959  3258  3314 I io.jxcore.node.ConnectionHelper: start: Port number: 41977, start advertisements: true
,03-24 21:18:23.959  3258  3314 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 21:18:23.959  3258  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything,
03-24 21:18:23.959  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-24 21:18:23.962  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-24 21:18:23.962  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 21:18:23.962  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 21:18:23.963  3258  3314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 21:18:23.967  2145  2210 D BtGatt.GattService: registerClient() - UUID=1cc722ce-5c7a-438e-be22-6afa11b119cc
,03-24 21:18:23.967  2145  2208 D BtGatt.GattService: onClientRegistered() - UUID=1cc722ce-5c7a-438e-be22-6afa11b119cc, clientIf=5
,03-24 21:18:23.968  3258  3275 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 21:18:23.968  2145  2166 D BtGatt.GattService: start scan with filters,
03-24 21:18:23.969  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-24 21:18:23.969  2145  2223 D BtGatt.ScanManager: handling starting scan
03-24 21:18:23.969  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true,
03-24 21:18:23.971  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-24 21:18:23.971  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,03-24 21:18:23.971  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 21:18:23.971  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 21:18:23.971  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 21:18:23.971  3258  3258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-24 21:18:23.972  3258  3314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 21:18:23.972  2145  2208 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,03-24 21:18:23.972  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:18:23.973  3258  3314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-24 21:18:23.973  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 21:18:23.973  3258  3314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-24 21:18:23.974  2145  2208 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 21:18:23.974  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:18:23.975  2145  2223 D BtGatt.ScanManager: Starting BLE batch scan,
03-24 21:18:23.975  2145  2223 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 21:18:23.977  2145  2208 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0,
03-24 21:18:23.978  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:18:23.979  2145  2164 D BtGatt.GattService: registerClient() - UUID=2a39f23a-bcd6-4df6-bcad-cc96721a659c
,03-24 21:18:23.979  2145  2208 D BtGatt.GattService: onClientRegistered() - UUID=2a39f23a-bcd6-4df6-bcad-cc96721a659c, clientIf=6,
,03-24 21:18:23.980  3258  3274 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-24 21:18:23.980  2145  2208 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 21:18:23.980  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:18:23.981  2145  2221 D BtGatt.AdvertiseManager: message : 0
,03-24 21:18:23.987  2145  2221 D BtGatt.AdvertiseManager: starting multi advertising
03-24 21:18:23.991  2145  2208 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 21:18:23.994  2145  2208 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0,
,03-24 21:18:23.995  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-24 21:18:23.995  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 21:18:23.996   820  2348 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 21:18:23.998  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 21:18:23.998  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-24 21:18:23.998  3258  3314 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-24 21:18:23.999  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-24 21:18:24.000  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-24 21:18:24.000  3258  3314 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-24 21:18:24.000  3258  3314 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-24 21:18:24.000  3258  3314 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-24 21:18:24.000  3258  3314 I io.jxcore.node.ConnectionHelper: start: OK
03-24 21:18:24.000  3258  3258 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-24 21:18:24.001  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 21:18:24.001  3258  3258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-24 21:18:24.001  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-24 21:18:24.001  3258  3258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
,03-24 21:18:24.001  3258  3258 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-24 21:18:24.002  3258  3258 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 21:18:24.002  3258  3258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 21:18:24.002  3258  3258 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-24 21:18:24.002  3258  3258 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-24 21:18:24.002  3258  3258 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-24 21:18:24.003  3258  3258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 21:18:24.004  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 21:18:24.004  3258  3314 I jxcore-log: 
03-24 21:18:24.004   820   835 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 21:18:24.006  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 21:18:24.006  3258  3314 I jxcore-log: 
03-24 21:18:24.006  3258  3808 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-24 21:18:24.006  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-24 21:18:24.006  3258  3314 I jxcore-log: 
03-24 21:18:24.007  3258  3314 I jxcore-log: ok 185 no errors
03-24 21:18:24.007  3258  3314 I jxcore-log: 
,03-24 21:18:24.015  3258  3808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
03-24 21:18:24.016  3258  3314 I io.jxcore.node.ConnectionHelper: start: Port number: 41977, start advertisements: true
,03-24 21:18:24.016  3258  3314 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 21:18:24.016  3258  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-24 21:18:24.016  3258  3314 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 21:18:24.017  3258  3314 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 21:18:24.021  3258  3314 I jxcore-log: ok 186 still no errors
03-24 21:18:24.021  3258  3314 I jxcore-log: 
,03-24 21:18:24.028  3258  3314 I jxcore-log: # teardown,
03-24 21:18:24.028  3258  3314 I jxcore-log: 
,03-24 21:18:24.595  3258  3314 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections,
03-24 21:18:24.595  3258  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-24 21:18:24.595  3258  3314 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-24 21:18:24.596  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-24 21:18:24.596  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-24 21:18:24.596  3258  3314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-24 21:18:24.596  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-24 21:18:24.596  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-24 21:18:24.596  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,03-24 21:18:24.596  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 21:18:24.597  3258  3808 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-24 21:18:24.597  3258  3808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,03-24 21:18:24.597  3258  3808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,03-24 21:18:24.597  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-24 21:18:24.597  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-24 21:18:24.601  2145  2166 D BtGatt.GattService: stopScan() - queue size =1
,03-24 21:18:24.604  2145  2208 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 21:18:24.604  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:18:24.604  2145  2164 D BtGatt.GattService: unregisterClient() - clientIf=5
03-24 21:18:24.605  2145  2223 D BtGatt.ScanManager: stopping BLe Batch
03-24 21:18:24.605  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 21:18:24.606  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 21:18:24.606  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-24 21:18:24.606  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-24 21:18:24.606  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
,03-24 21:18:24.606  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 21:18:24.606  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-24 21:18:24.608  2145  2208 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 21:18:24.608  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:18:24.608  2145  2223 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 21:18:24.609  2145  2221 D BtGatt.AdvertiseManager: message : 1
03-24 21:18:24.609  2145  2221 D BtGatt.AdvertiseManager: stop advertise for client 6
03-24 21:18:24.612  2145  2208 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 21:18:24.612  2145  2208 D BtGatt.GattService: Client app is not null!
03-24 21:18:24.614  2145  2164 D BtGatt.GattService: unregisterClient() - clientIf=6
03-24 21:18:24.615  2145  2208 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-24 21:18:24.615  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 21:18:24.615  2145  2208 D BtGatt.GattService: current time is 286252165879
03-24 21:18:24.615  2145  2208 D BtGatt.GattService: Batch record : [96, 124, -71, -39, -84, 112, 1, -128, -78, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -63, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-24 21:18:24.615  2145  2208 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 21:18:24.615  2145  2208 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64],
03-24 21:18:24.615  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 21:18:24.616  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-24 21:18:24.616  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false,
03-24 21:18:24.616  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-24 21:18:24.616  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-24 21:18:24.617  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 21:18:24.617  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 21:18:24.617  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-24 21:18:24.619  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
03-24 21:18:24.619  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false,
03-24 21:18:24.619  3258  3258 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 21:18:24.619  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 21:18:24.619  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-24 21:18:24.629  3258  3258 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-24 21:18:24.630   820  2348 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 21:18:24.636  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-24 21:18:24.636  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 21:18:24.636  3258  3258 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 21:18:24.639  3258  3258 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-24 21:18:24.639  3258  3258 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-24 21:18:24.639  3258  3258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 21:18:24.639  3258  3258 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 21:18:24.639  3258  3258 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 21:18:24.639  3258  3258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 21:18:24.639  3258  3258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 21:18:24.639  3258  3258 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-24 21:18:24.640  3258  3314 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 21:18:24.640  3258  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 21:18:24.640  3258  3314 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 21:18:24.641  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-24 21:18:24.641  3258  3314 I jxcore-log: 
03-24 21:18:24.642  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 21:18:24.642  3258  3314 I jxcore-log: 
03-24 21:18:24.642  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 21:18:24.642  3258  3314 I jxcore-log: 
,03-24 21:18:24.652  3258  3314 I jxcore-log: # setup
03-24 21:18:24.652  3258  3314 I jxcore-log: 
,03-24 21:18:24.764  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 21:18:24.764  3258  3314 I jxcore-log: 
,03-24 21:18:24.765  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 21:18:24.765  3258  3314 I jxcore-log: 
,03-24 21:18:24.773  3258  3314 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 21:18:24.773  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 21:18:24.773  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 21:18:24.773  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 21:18:24.773  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 21:18:24.773  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 21:18:24.773  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 21:18:24.773  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 21:18:24.776  3258  3314 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 21:18:24.778  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 21:18:24.778  3258  3314 I jxcore-log: 
,03-24 21:18:24.780  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 21:18:24.780  3258  3314 I jxcore-log: 
,03-24 21:18:24.783  3258  3314 I jxcore-log: # 47. should be able to call #stopAdvertisingAndListening many times
03-24 21:18:24.783  3258  3314 I jxcore-log: 
,03-24 21:18:24.784  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 21:18:24.784  3258  3314 I jxcore-log: 
,03-24 21:18:24.992  3258  3314 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 21:18:24.992  3258  3314 I jxcore-log: 
,03-24 21:18:24.999  3258  3314 I jxcore-log: DEBUG createNativeListener: listening 37444
03-24 21:18:24.999  3258  3314 I jxcore-log: 
,03-24 21:18:25.001  3258  3314 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 21:18:25.001  3258  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-24 21:18:25.001  3258  3314 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 21:18:25.004  3258  3314 I jxcore-log: ok 187 no errors
03-24 21:18:25.004  3258  3314 I jxcore-log: 
,03-24 21:18:25.005  3258  3314 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 21:18:25.005  3258  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-24 21:18:25.005  3258  3314 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 21:18:25.008  3258  3314 I jxcore-log: ok 188 still no errors
03-24 21:18:25.008  3258  3314 I jxcore-log: 
,03-24 21:18:25.013  3258  3314 I jxcore-log: # teardown
03-24 21:18:25.013  3258  3314 I jxcore-log: 
,03-24 21:18:25.149  3258  3314 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-24 21:18:25.150  3258  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 21:18:25.150  3258  3314 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 21:18:25.156  3258  3314 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 21:18:25.156  3258  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-24 21:18:25.157  3258  3314 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 21:18:25.184  3258  3314 I jxcore-log: # setup
03-24 21:18:25.184  3258  3314 I jxcore-log: 
,03-24 21:18:25.290  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 21:18:25.290  3258  3314 I jxcore-log: 
,03-24 21:18:25.296  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 21:18:25.296  3258  3314 I jxcore-log: 
,03-24 21:18:25.307  3258  3314 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 21:18:25.307  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 21:18:25.307  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 21:18:25.307  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 21:18:25.307  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 21:18:25.307  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 21:18:25.307  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 21:18:25.307  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 21:18:25.311  3258  3314 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 21:18:25.314  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,03-24 21:18:25.314  3258  3314 I jxcore-log: 
,03-24 21:18:25.317  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,03-24 21:18:25.317  3258  3314 I jxcore-log: 
,03-24 21:18:25.321  3258  3314 I jxcore-log: # 48. can get the network status before starting,
03-24 21:18:25.321  3258  3314 I jxcore-log: 
,03-24 21:18:25.324  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
,03-24 21:18:25.324  3258  3314 I jxcore-log: 
,03-24 21:18:25.409  3258  3314 I jxcore-log: ok 189 network status should have certain non-empty properties
,03-24 21:18:25.409  3258  3314 I jxcore-log: 
,03-24 21:18:25.417  3258  3314 I jxcore-log: # teardown
,03-24 21:18:25.417  3258  3314 I jxcore-log: 
,03-24 21:18:25.561  3258  3314 I jxcore-log: # setup
03-24 21:18:25.561  3258  3314 I jxcore-log: 
,03-24 21:18:25.852  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 21:18:25.852  3258  3314 I jxcore-log: 
,03-24 21:18:25.855  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native,
03-24 21:18:25.855  3258  3314 I jxcore-log: 
,03-24 21:18:25.863  3258  3314 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
,03-24 21:18:25.863  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 21:18:25.863  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 21:18:25.863  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 21:18:25.863  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 21:18:25.863  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 21:18:25.863  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 21:18:25.863  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 21:18:25.866  3258  3314 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
03-24 21:18:25.867  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 21:18:25.867  3258  3314 I jxcore-log: 
,03-24 21:18:25.869  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 21:18:25.869  3258  3314 I jxcore-log: 
,03-24 21:18:25.871  3258  3314 I jxcore-log: # 49. error returned with bad router
03-24 21:18:25.871  3258  3314 I jxcore-log: 
,03-24 21:18:25.873  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 21:18:25.873  3258  3314 I jxcore-log: 
,03-24 21:18:26.100  3258  3314 I jxcore-log: ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a string
03-24 21:18:26.100  3258  3314 I jxcore-log: 
,03-24 21:18:26.103  3258  3314 I jxcore-log: ok 190 specific error expected
03-24 21:18:26.103  3258  3314 I jxcore-log: 
,03-24 21:18:26.105  3258  3314 I jxcore-log: # teardown
03-24 21:18:26.105  3258  3314 I jxcore-log: 
,03-24 21:18:26.248  3258  3314 I jxcore-log: # setup
03-24 21:18:26.248  3258  3314 I jxcore-log: 
,03-24 21:18:26.460  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 21:18:26.460  3258  3314 I jxcore-log: 
,03-24 21:18:26.464  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 21:18:26.464  3258  3314 I jxcore-log: 
,03-24 21:18:26.477  3258  3314 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 21:18:26.477  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 21:18:26.477  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 21:18:26.477  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 21:18:26.477  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 21:18:26.477  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 21:18:26.477  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 21:18:26.477  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 21:18:26.479  3258  3314 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 21:18:26.481  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 21:18:26.481  3258  3314 I jxcore-log: 
,03-24 21:18:26.482  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 21:18:26.482  3258  3314 I jxcore-log: 
,03-24 21:18:26.485  3258  3314 I jxcore-log: # 50. all services are stopped when we call stop
03-24 21:18:26.485  3258  3314 I jxcore-log: 
,03-24 21:18:26.487  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 21:18:26.487  3258  3314 I jxcore-log: 
,03-24 21:18:26.618  3258  3314 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 21:18:26.618  3258  3314 I jxcore-log: 
,03-24 21:18:26.621  3258  3314 I jxcore-log: DEBUG createNativeListener: listening 55734
03-24 21:18:26.621  3258  3314 I jxcore-log: 
,03-24 21:18:26.626  3258  3314 I io.jxcore.node.ConnectionHelper: start: Port number: 41977, start advertisements: false
,03-24 21:18:26.626  3258  3314 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 21:18:26.626  3258  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 21:18:26.626  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-24 21:18:26.629  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-24 21:18:26.629  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-24 21:18:26.629  3258  3314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-24 21:18:26.632  2145  2210 D BtGatt.GattService: registerClient() - UUID=d70be290-e052-4b40-a521-433baae94153
03-24 21:18:26.632  2145  2208 D BtGatt.GattService: onClientRegistered() - UUID=d70be290-e052-4b40-a521-433baae94153, clientIf=5
03-24 21:18:26.633  3258  3275 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-24 21:18:26.633  2145  2164 D BtGatt.GattService: start scan with filters
03-24 21:18:26.634  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-24 21:18:26.634  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 21:18:26.634  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-24 21:18:26.635  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-24 21:18:26.635  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
,03-24 21:18:26.635  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 21:18:26.635  3258  3258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 21:18:26.635   820  1144 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 21:18:26.636  2145  2223 D BtGatt.ScanManager: handling starting scan
,03-24 21:18:26.642  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-24 21:18:26.642  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 21:18:26.642  3258  3314 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 21:18:26.642  3258  3258 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only,
03-24 21:18:26.642  3258  3258 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 21:18:26.643  3258  3258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 21:18:26.644  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 21:18:26.644  3258  3314 I jxcore-log: 
03-24 21:18:26.645  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 21:18:26.645  3258  3314 I jxcore-log: 
03-24 21:18:26.649  3258  3314 I io.jxcore.node.ConnectionHelper: start: Port number: 55734, start advertisements: true
03-24 21:18:26.649  3258  3314 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 21:18:26.649  3258  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-24 21:18:26.649  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-24 21:18:26.655  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-24 21:18:26.655  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
03-24 21:18:26.655  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 21:18:26.655  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 21:18:26.655  3258  3314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 21:18:26.655  3258  3314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 21:18:26.655  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 21:18:26.655  3258  3314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-24 21:18:26.656  2145  2208 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 21:18:26.657  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 21:18:26.658  2145  2164 D BtGatt.GattService: registerClient() - UUID=0a7400b0-3dc4-467a-932a-8bb114057d0c,
,03-24 21:18:26.659  2145  2208 D BtGatt.GattService: onClientRegistered() - UUID=0a7400b0-3dc4-467a-932a-8bb114057d0c, clientIf=6
03-24 21:18:26.659  3258  3274 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-24 21:18:26.660  2145  2208 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 21:18:26.660  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:18:26.660  2145  2223 D BtGatt.ScanManager: Starting BLE batch scan
,03-24 21:18:26.660  2145  2223 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-24 21:18:26.660  2145  2221 D BtGatt.AdvertiseManager: message : 0
03-24 21:18:26.661  2145  2221 D BtGatt.AdvertiseManager: starting multi advertising
03-24 21:18:26.662  2145  2208 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,03-24 21:18:26.662  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 21:18:26.663  2145  2208 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1,
03-24 21:18:26.663  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:18:26.667  2145  2208 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
03-24 21:18:26.669  2145  2208 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
03-24 21:18:26.670  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 21:18:26.670  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-24 21:18:26.670  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 21:18:26.670  3258  3258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-24 21:18:26.670  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-24 21:18:26.670  3258  3258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-24 21:18:26.670  3258  3258 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-24 21:18:26.670   820  1362 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 21:18:26.672  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-24 21:18:26.672  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 21:18:26.672  3258  3314 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-24 21:18:26.672  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
03-24 21:18:26.672  3258  3258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 21:18:26.672  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-24 21:18:26.672  3258  3314 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,03-24 21:18:26.672  3258  3314 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-24 21:18:26.672  3258  3314 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-24 21:18:26.672  3258  3314 I io.jxcore.node.ConnectionHelper: start: OK,
03-24 21:18:26.673  3258  3258 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything,
,03-24 21:18:26.673  3258  3258 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 21:18:26.673  3258  3258 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,03-24 21:18:26.674   820  3100 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 21:18:26.675  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-24 21:18:26.675  3258  3314 I jxcore-log: 
,03-24 21:18:26.675  3258  3809 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-24 21:18:26.677  3258  3809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-24 21:18:26.679  3258  3314 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 21:18:26.679  3258  3314 I jxcore-log: 
03-24 21:18:26.681  3258  3314 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 21:18:26.681  3258  3314 I jxcore-log: ,
03-24 21:18:26.682  3258  3314 I jxcore-log: DEBUG createNativeListener: new mux
03-24 21:18:26.682  3258  3314 I jxcore-log: 
,03-24 21:18:26.685  3258  3314 I jxcore-log: ok 191 connection to servers manager should succeed after starting
,03-24 21:18:26.685  3258  3314 I jxcore-log: 
,03-24 21:18:26.692  3258  3314 I jxcore-log: ok 192 connection to router server should succeed after starting
,03-24 21:18:26.692  3258  3314 I jxcore-log: 
,03-24 21:18:26.694  3258  3314 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 21:18:26.694  3258  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything,
03-24 21:18:26.694  3258  3314 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,03-24 21:18:26.694  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-24 21:18:26.694  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown,
03-24 21:18:26.694  3258  3314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-24 21:18:26.695  3258  3809 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
,03-24 21:18:26.695  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-24 21:18:26.695  3258  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-24 21:18:26.695  3258  3809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,03-24 21:18:26.695  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,03-24 21:18:26.695  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 21:18:26.695  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 21:18:26.695  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser,
03-24 21:18:26.695  3258  3258 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-24 21:18:26.695  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...,
03-24 21:18:26.695  3258  3258 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-24 21:18:26.696  2145  2166 D BtGatt.GattService: stopScan() - queue size =1
,03-24 21:18:26.697  2145  2210 D BtGatt.GattService: unregisterClient() - clientIf=5
03-24 21:18:26.697  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 21:18:26.697  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED,
03-24 21:18:26.697  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-24 21:18:26.697  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-24 21:18:26.697  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
,03-24 21:18:26.697  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 21:18:26.697  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,03-24 21:18:26.698  2145  2208 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 21:18:26.698  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:18:26.698  2145  2223 D BtGatt.ScanManager: stopping BLe Batch
,03-24 21:18:26.699  2145  2221 D BtGatt.AdvertiseManager: message : 1
03-24 21:18:26.699  2145  2221 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-24 21:18:26.701  2145  2208 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 21:18:26.701  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:18:26.701  2145  2223 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 21:18:26.702  2145  2208 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 21:18:26.702  2145  2208 D BtGatt.GattService: Client app is not null!
03-24 21:18:26.703  2145  2210 D BtGatt.GattService: unregisterClient() - clientIf=6,
03-24 21:18:26.703  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 21:18:26.703  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-24 21:18:26.703  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,03-24 21:18:26.703  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-24 21:18:26.703  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-24 21:18:26.703  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 21:18:26.704  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped,
03-24 21:18:26.704  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-24 21:18:26.704  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,03-24 21:18:26.704  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 21:18:26.704  3258  3258 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 21:18:26.704  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 21:18:26.705  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-24 21:18:26.706  2145  2208 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
03-24 21:18:26.706  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 21:18:26.706  2145  2208 D BtGatt.GattService: current time is 288343544263
03-24 21:18:26.706  2145  2208 D BtGatt.GattService: Batch record : [36, 14, -80, -86, 124, 98, 1, -128, -61, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-24 21:18:26.706  2145  2208 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 21:18:26.710  3258  3314 I jxcore-log: DEBUG createNativeListener: incoming socket close,
03-24 21:18:26.710  3258  3314 I jxcore-log: 
03-24 21:18:26.710  3258  3258 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-24 21:18:26.710   820  1375 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 21:18:26.714  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
03-24 21:18:26.715  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 21:18:26.715  3258  3258 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 21:18:26.717  3258  3258 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-24 21:18:26.717  3258  3258 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 21:18:26.717  3258  3258 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 21:18:26.717  3258  3258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 21:18:26.717  3258  3258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 21:18:26.717  3258  3258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-24 21:18:26.719  3258  3314 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 21:18:26.719  3258  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only,
03-24 21:18:26.719  3258  3314 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 21:18:26.721  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-24 21:18:26.721  3258  3314 I jxcore-log: 
03-24 21:18:26.723  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 21:18:26.723  3258  3314 I jxcore-log: 
,03-24 21:18:26.725  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 21:18:26.725  3258  3314 I jxcore-log: 
,03-24 21:18:26.733  3258  3314 I jxcore-log: ok 193 is stopped after calling stop
03-24 21:18:26.733  3258  3314 I jxcore-log: 
,03-24 21:18:26.737  3258  3314 I jxcore-log: ok 194 connection to servers manager should fail after stopping,
03-24 21:18:26.737  3258  3314 I jxcore-log: 
,03-24 21:18:26.740  3258  3314 I jxcore-log: ok 195 connection to router server should fail after stopping,
03-24 21:18:26.740  3258  3314 I jxcore-log: 
,03-24 21:18:26.743  3258  3314 I jxcore-log: # teardown,
03-24 21:18:26.743  3258  3314 I jxcore-log: 
,03-24 21:18:27.282  3258  3314 I jxcore-log: # setup,
03-24 21:18:27.282  3258  3314 I jxcore-log: 
,03-24 21:18:27.392  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native,
03-24 21:18:27.392  3258  3314 I jxcore-log: 
,03-24 21:18:27.395  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 21:18:27.395  3258  3314 I jxcore-log: 
,03-24 21:18:27.400  3258  3314 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 21:18:27.400  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 21:18:27.400  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 21:18:27.400  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 21:18:27.400  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 21:18:27.400  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 21:18:27.400  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 21:18:27.400  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-24 21:18:27.403  3258  3314 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
03-24 21:18:27.406  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 21:18:27.406  3258  3314 I jxcore-log: 
03-24 21:18:27.410  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 21:18:27.410  3258  3314 I jxcore-log: 
,03-24 21:18:27.416  3258  3314 I jxcore-log: # 51. make sure terminateConnection is properly hooked up,
,03-24 21:18:27.416  3258  3314 I jxcore-log: ,
03-24 21:18:27.421  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 21:18:27.421  3258  3314 I jxcore-log: 
,03-24 21:18:28.233  3448  3810 V KeepSync: Connecting to GoogleApiClient
,03-24 21:18:28.316  3258  3314 I jxcore-log: ok 196 called with right arguments
03-24 21:18:28.316  3258  3314 I jxcore-log: 
03-24 21:18:28.318  3258  3314 I jxcore-log: # teardown
03-24 21:18:28.318  3258  3314 I jxcore-log: 
,03-24 21:18:28.331  1266  1296 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,03-24 21:18:28.332  1266  1296 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-24 21:18:28.332  1266  1296 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 21:18:28.332  1266  1296 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 21:18:28.339  1266  1296 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 21:18:28.364  1801  3811 E ClientConnectionOperation: Handling authorization failure
03-24 21:18:28.364  1801  3811 E ClientConnectionOperation: com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
03-24 21:18:28.364  1801  3811 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
03-24 21:18:28.364  1801  3811 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
03-24 21:18:28.364  1801  3811 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
03-24 21:18:28.364  1801  3811 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
03-24 21:18:28.364  1801  3811 E ClientConnectionOperation: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-24 21:18:28.364  1801  3811 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 21:18:28.364  1801  3811 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 21:18:28.364  1801  3811 E ClientConnectionOperation: 	at java.lang.Thread.run(Thread.java:818)
03-24 21:18:28.364  1801  3811 E ClientConnectionOperation: Caused by: com.google.android.gms.auth.ad: BadAuthentication
03-24 21:18:28.364  1801  3811 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.b(SourceFile:442)
03-24 21:18:28.364  1801  3811 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:365)
03-24 21:18:28.364  1801  3811 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:310)
03-24 21:18:28.364  1801  3811 E ClientConnectionOperation: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
03-24 21:18:28.364  1801  3811 E ClientConnectionOperation: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
03-24 21:18:28.364  1801  3811 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:30)
03-24 21:18:28.364  1801  3811 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:370)
03-24 21:18:28.364  1801  3811 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:340)
03-24 21:18:28.364  1801  3811 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:319)
03-24 21:18:28.364  1801  3811 E ClientConnectionOperation: 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
03-24 21:18:28.364  1801  3811 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
03-24 21:18:28.364  1801  3811 E ClientConnectionOperation: 	... 7 more
,03-24 21:18:28.368  3448  3810 V KeepSync: GoogleApiClient failed to connect with error code: 4
,03-24 21:18:28.373  3448  3810 E SQLiteLog: (284) automatic index on blob_node(is_deleted),
,03-24 21:18:28.391  3448  3810 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-24 21:18:28.392  3448  3810 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-24 21:18:28.398  3258  3314 I jxcore-log: # setup
03-24 21:18:28.398  3258  3314 I jxcore-log: 
,03-24 21:18:28.484  1266  1296 I art     : Explicit concurrent mark sweep GC freed 58346(3MB) AllocSpace objects, 10(1026KB) LOS objects, 36% free, 27MB/43MB, paused 1.588ms total 42.860ms
,03-24 21:18:28.519  1266  1290 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,03-24 21:18:28.520  1266  1290 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 21:18:28.520  1266  1290 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 21:18:28.521  1266  1290 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 21:18:28.530  1266  1290 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 21:18:28.579  3448  3810 E KeepSync: IOException
03-24 21:18:28.579  3448  3810 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
03-24 21:18:28.579  3448  3810 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
03-24 21:18:28.579  3448  3810 E KeepSync: ,	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
03-24 21:18:28.579  3448  3810 E KeepSync: 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
03-24 21:18:28.579  3448  3810 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
03-24 21:18:28.579  3448  3810 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
03-24 21:18:28.579  3448  3810 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343),
03-24 21:18:28.579  3448  3810 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
03-24 21:18:28.579  3448  3810 E KeepSync: 	at com.google.android.keep.util.m.a(SourceFile:207)
03-24 21:18:28.579  3448  3810 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
03-24 21:18:28.579  3448  3810 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
03-24 21:18:28.579  3448  3810 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
03-24 21:18:28.579  3448  3810 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
03-24 21:18:28.579  3448  3810 E KeepSync: 	,at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
03-24 21:18:28.579  3448  3810 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
03-24 21:18:28.579  3448  3810 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
03-24 21:18:28.579  3448  3810 E KeepSync: 	... 10 more
,03-24 21:18:28.579  3448  3810 W KeepSync: Sync result 2
,03-24 21:18:28.597   820   853 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 289744, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1],
,03-24 21:18:28.632  3494  3817 I BooksSync: Starting books sync for 61035162, extras: ade
,03-24 21:18:28.658  3494  3818 I BooksConfig: GmsCore Version = 7.8.99 (2134222-430)
,03-24 21:18:28.735  1266  1726 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books,
03-24 21:18:28.735  1266  1726 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 21:18:28.735  1266  1726 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 21:18:28.736  1266  1726 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 21:18:28.745  1266  1726 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 21:18:28.881  1266  2545 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-24 21:18:28.881  1266  2545 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 21:18:28.881  1266  2545 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 21:18:28.882  1266  2545 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 21:18:28.898  1266  2545 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 21:18:29.027   820  1144 I art     : Explicit concurrent mark sweep GC freed 28837(1425KB) AllocSpace objects, 10(819KB) LOS objects, 32% free, 33MB/49MB, paused 1.438ms total 118.423ms
,03-24 21:18:29.062  3494  3818 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,03-24 21:18:29.064  3494  3817 E BooksSync: Soft error
03-24 21:18:29.064  3494  3817 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-24 21:18:29.064  3494  3817 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,03-24 21:18:29.065  3494  3817 E BooksSync: Sync error
03-24 21:18:29.065  3494  3817 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-24 21:18:29.065  3494  3817 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-24 21:18:29.065  3494  3817 I BooksSync: Finished books sync
,03-24 21:18:29.071   820   853 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 289942, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-24 21:18:29.337  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 21:18:29.337  3258  3314 I jxcore-log: 
,03-24 21:18:29.338  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 21:18:29.338  3258  3314 I jxcore-log: 
,03-24 21:18:29.345  3258  3314 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 21:18:29.345  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 21:18:29.345  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 21:18:29.345  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 21:18:29.345  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 21:18:29.345  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 21:18:29.345  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 21:18:29.345  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 21:18:29.349  3258  3314 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 21:18:29.350  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 21:18:29.350  3258  3314 I jxcore-log: 
,03-24 21:18:29.352  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 21:18:29.352  3258  3314 I jxcore-log: 
,03-24 21:18:29.355  3258  3314 I jxcore-log: # 52. make sure terminateListener is properly hooked up
03-24 21:18:29.355  3258  3314 I jxcore-log: 
,03-24 21:18:29.356  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 21:18:29.356  3258  3314 I jxcore-log: 
,03-24 21:18:29.496  3258  3314 I jxcore-log: ok 197 called with right arguments
03-24 21:18:29.496  3258  3314 I jxcore-log: 
,03-24 21:18:29.498  3258  3314 I jxcore-log: # teardown
03-24 21:18:29.498  3258  3314 I jxcore-log: 
,03-24 21:18:29.647  3258  3314 I jxcore-log: # setup
03-24 21:18:29.647  3258  3314 I jxcore-log: 
,03-24 21:18:29.815  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 21:18:29.815  3258  3314 I jxcore-log: 
03-24 21:18:29.816  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 21:18:29.816  3258  3314 I jxcore-log: 
,03-24 21:18:29.823  3258  3314 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 21:18:29.823  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 21:18:29.823  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 21:18:29.823  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 21:18:29.823  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 21:18:29.823  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 21:18:29.823  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 21:18:29.823  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 21:18:29.826  3258  3314 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 21:18:29.827  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 21:18:29.827  3258  3314 I jxcore-log: 
,03-24 21:18:29.829  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 21:18:29.829  3258  3314 I jxcore-log: 
,03-24 21:18:29.832  3258  3314 I jxcore-log: # 53. make sure we actually call kill connections properly
03-24 21:18:29.832  3258  3314 I jxcore-log: 
,03-24 21:18:29.834  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 21:18:29.834  3258  3314 I jxcore-log: 
,03-24 21:18:29.964  3258  3314 I jxcore-log: ok 198 specific error expected
03-24 21:18:29.964  3258  3314 I jxcore-log: 
,03-24 21:18:29.969  3258  3314 I jxcore-log: # teardown
03-24 21:18:29.969  3258  3314 I jxcore-log: 
,03-24 21:18:30.072  3258  3314 I jxcore-log: # setup
03-24 21:18:30.072  3258  3314 I jxcore-log: 
,03-24 21:18:30.180  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 21:18:30.180  3258  3314 I jxcore-log: ,
,03-24 21:18:30.185  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 21:18:30.185  3258  3314 I jxcore-log: 
,03-24 21:18:30.196  3258  3314 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 21:18:30.196  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 21:18:30.196  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 21:18:30.196  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 21:18:30.196  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 21:18:30.196  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 21:18:30.196  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 21:18:30.196  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 21:18:30.201  3258  3314 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
,03-24 21:18:30.207  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 21:18:30.207  3258  3314 I jxcore-log: 
,03-24 21:18:30.212  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 21:18:30.212  3258  3314 I jxcore-log: 
,03-24 21:18:30.221  3258  3314 I jxcore-log: # 54. thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
03-24 21:18:30.221  3258  3314 I jxcore-log: 
,03-24 21:18:30.226  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 21:18:30.226  3258  3314 I jxcore-log: 
,03-24 21:18:30.375  3258  3314 I jxcore-log: DEBUG createNativeListener: creating native server
,03-24 21:18:30.375  3258  3314 I jxcore-log: 
,03-24 21:18:30.384  3258  3314 I jxcore-log: DEBUG createNativeListener: listening 45278
,03-24 21:18:30.384  3258  3314 I jxcore-log: 
,03-24 21:18:30.391  3258  3314 I jxcore-log: INFO thaliMobileNativeWrapper: routerPortConnectionFailed - {"routerPort":42955,"error":{}}
,03-24 21:18:30.391  3258  3314 I jxcore-log: 
03-24 21:18:30.392  3258  3314 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 21:18:30.392  3258  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 21:18:30.393  3258  3314 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 21:18:30.396  3258  3314 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 21:18:30.396  3258  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 21:18:30.396  3258  3314 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
,03-24 21:18:30.402  3258  3314 I jxcore-log: ok 199 failure reason is as expected
,03-24 21:18:30.402  3258  3314 I jxcore-log: 
03-24 21:18:30.403  3258  3314 I jxcore-log: ok 200 error description is as expected
03-24 21:18:30.403  3258  3314 I jxcore-log: 
,03-24 21:18:30.403  3258  3314 I jxcore-log: ok 201 must be stopped
03-24 21:18:30.403  3258  3314 I jxcore-log: 
,03-24 21:18:30.411  3258  3314 I jxcore-log: # teardown
03-24 21:18:30.411  3258  3314 I jxcore-log: 
,03-24 21:18:30.537  3258  3314 I jxcore-log: # setup
03-24 21:18:30.537  3258  3314 I jxcore-log: 
,03-24 21:18:30.635  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 21:18:30.635  3258  3314 I jxcore-log: 
,03-24 21:18:30.636  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 21:18:30.636  3258  3314 I jxcore-log: 
,03-24 21:18:30.646  3258  3314 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 21:18:30.646  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 21:18:30.646  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 21:18:30.646  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 21:18:30.646  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 21:18:30.646  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 21:18:30.646  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 21:18:30.646  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 21:18:30.651  3258  3314 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 21:18:30.655  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 21:18:30.655  3258  3314 I jxcore-log: 
,03-24 21:18:30.659  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 21:18:30.659  3258  3314 I jxcore-log: 
,03-24 21:18:30.665  3258  3314 I jxcore-log: # 55. We repeat failedConnection event when we get it from thaliTcpServersManager
03-24 21:18:30.665  3258  3314 I jxcore-log: 
,03-24 21:18:30.669  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 21:18:30.669  3258  3314 I jxcore-log: 
,03-24 21:18:30.798  3258  3314 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 21:18:30.798  3258  3314 I jxcore-log: 
,03-24 21:18:30.800  3258  3314 I jxcore-log: DEBUG createNativeListener: listening 54855
03-24 21:18:30.800  3258  3314 I jxcore-log: 
,03-24 21:18:30.804  3258  3314 I jxcore-log: ok 202 peerIdentifier matches
03-24 21:18:30.804  3258  3314 I jxcore-log: 
,03-24 21:18:30.805  3258  3314 I jxcore-log: ok 203 error description matches
03-24 21:18:30.805  3258  3314 I jxcore-log: 
,03-24 21:18:30.808  3258  3314 I jxcore-log: # teardown
03-24 21:18:30.808  3258  3314 I jxcore-log: 
,03-24 21:18:30.971  3258  3314 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-24 21:18:30.971  3258  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-24 21:18:30.971  3258  3314 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 21:18:30.974  3258  3314 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 21:18:30.975  3258  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-24 21:18:30.975  3258  3314 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 21:18:30.984  3258  3314 I jxcore-log: # setup
03-24 21:18:30.984  3258  3314 I jxcore-log: 
,03-24 21:18:31.070  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 21:18:31.070  3258  3314 I jxcore-log: 
,03-24 21:18:31.074  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 21:18:31.074  3258  3314 I jxcore-log: 
,03-24 21:18:31.082  3258  3314 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 21:18:31.082  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 21:18:31.082  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 21:18:31.082  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
,03-24 21:18:31.082  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 21:18:31.082  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 21:18:31.082  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 21:18:31.082  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 21:18:31.085  3258  3314 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
03-24 21:18:31.087  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 21:18:31.087  3258  3314 I jxcore-log: 
,03-24 21:18:31.089  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 21:18:31.089  3258  3314 I jxcore-log: 
,03-24 21:18:31.098  3258  3314 I jxcore-log: # 56. we successfully receive and replay discoveryAdvertisingStateUpdate
03-24 21:18:31.098  3258  3314 I jxcore-log: 
,03-24 21:18:31.100  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 21:18:31.100  3258  3314 I jxcore-log: 
,03-24 21:18:31.240  3258  3314 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 21:18:31.240  3258  3314 I jxcore-log: 
,03-24 21:18:31.242  3258  3314 I jxcore-log: DEBUG createNativeListener: listening 40221
03-24 21:18:31.242  3258  3314 I jxcore-log: 
,03-24 21:18:31.248  3258  3314 I io.jxcore.node.ConnectionHelper: start: Port number: 55734, start advertisements: false
,03-24 21:18:31.248  3258  3314 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 21:18:31.248  3258  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 21:18:31.248  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-24 21:18:31.252  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-24 21:18:31.253  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 21:18:31.253  3258  3314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 21:18:31.257  2145  2210 D BtGatt.GattService: registerClient() - UUID=e3a6bcc7-9f32-4dec-ae87-2043b48edef8
03-24 21:18:31.257  2145  2208 D BtGatt.GattService: onClientRegistered() - UUID=e3a6bcc7-9f32-4dec-ae87-2043b48edef8, clientIf=5
03-24 21:18:31.258  3258  3822 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-24 21:18:31.258  2145  2166 D BtGatt.GattService: start scan with filters
,03-24 21:18:31.259  2145  2223 D BtGatt.ScanManager: handling starting scan,
,03-24 21:18:31.260  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
,03-24 21:18:31.260  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true,
,03-24 21:18:31.260  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING],
03-24 21:18:31.260  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING],
03-24 21:18:31.260  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 21:18:31.260  3258  3258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 21:18:31.261  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 21:18:31.261   820  1333 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 21:18:31.267  2145  2208 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 21:18:31.267  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:18:31.267  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 21:18:31.267  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 21:18:31.267  3258  3258 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 21:18:31.268  3258  3258 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 21:18:31.268  3258  3258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 21:18:31.268  3258  3314 I io.jxcore.node.ConnectionHelper: start: OK
03-24 21:18:31.269  2145  2208 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 21:18:31.269  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:18:31.269  2145  2223 D BtGatt.ScanManager: Starting BLE batch scan
03-24 21:18:31.269  2145  2223 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 21:18:31.271  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 21:18:31.271  3258  3314 I jxcore-log: 
03-24 21:18:31.272  2145  2208 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 21:18:31.272  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:18:31.273  3258  3314 I jxcore-log: ok 204 discoveryActive matches
03-24 21:18:31.273  3258  3314 I jxcore-log: 
03-24 21:18:31.274  3258  3314 I jxcore-log: ok 205 advertisingActive matches
03-24 21:18:31.274  3258  3314 I jxcore-log: 
03-24 21:18:31.274  2145  2208 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 21:18:31.274  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 21:18:31.278  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 21:18:31.278  3258  3314 I jxcore-log: 
,03-24 21:18:31.285  3258  3314 I jxcore-log: not ok 206 discoveryActive matches
03-24 21:18:31.285  3258  3314 I jxcore-log: 
,03-24 21:18:31.285  3258  3314 I jxcore-log:   ---
03-24 21:18:31.285  3258  3314 I jxcore-log: 
,03-24 21:18:31.285  3258  3314 I jxcore-log:     operator: equal
03-24 21:18:31.285  3258  3314 I jxcore-log: 
03-24 21:18:31.285  3258  3314 I jxcore-log:     expected: false
03-24 21:18:31.285  3258  3314 I jxcore-log: 
,03-24 21:18:31.285  3258  3314 I jxcore-log:     actual:   true
03-24 21:18:31.285  3258  3314 I jxcore-log: 
03-24 21:18:31.286  3258  3314 I jxcore-log:   ...
03-24 21:18:31.286  3258  3314 I jxcore-log: 
,03-24 21:18:31.286  3258  3314 I jxcore-log: ok 207 advertisingActive matches,
03-24 21:18:31.286  3258  3314 I jxcore-log: 
03-24 21:18:31.288  3258  3314 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-24 21:18:31.288  3258  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
03-24 21:18:31.288  3258  3314 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
03-24 21:18:31.288  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-24 21:18:31.288  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-24 21:18:31.288  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 21:18:31.288  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode,
03-24 21:18:31.289  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-24 21:18:31.289  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-24 21:18:31.290  2145  2166 D BtGatt.GattService: stopScan() - queue size =1
,03-24 21:18:31.292  2145  2164 D BtGatt.GattService: unregisterClient() - clientIf=5
03-24 21:18:31.292  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 21:18:31.292  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-24 21:18:31.292  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-24 21:18:31.293  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,03-24 21:18:31.293  2145  2208 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,03-24 21:18:31.293  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:18:31.293  2145  2223 D BtGatt.ScanManager: stopping BLe Batch
,03-24 21:18:31.293  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-24 21:18:31.293  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 21:18:31.294  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 21:18:31.294  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 21:18:31.294  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-24 21:18:31.295  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-24 21:18:31.295  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 21:18:31.295  3258  3258 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 21:18:31.295  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 21:18:31.295  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-24 21:18:31.296  2145  2208 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 21:18:31.296  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:18:31.296  2145  2223 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 21:18:31.298  2145  2208 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 21:18:31.298  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 21:18:31.316  3258  3258 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-24 21:18:31.316   820  1113 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 21:18:31.320  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-24 21:18:31.320  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 21:18:31.320  3258  3258 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 21:18:31.322  3258  3258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 21:18:31.322  3258  3258 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 21:18:31.322  3258  3258 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 21:18:31.323  3258  3258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 21:18:31.324  3258  3314 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 21:18:31.324  3258  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 21:18:31.324  3258  3314 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 21:18:31.325  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 21:18:31.325  3258  3314 I jxcore-log: 
03-24 21:18:31.325  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 21:18:31.325  3258  3314 I jxcore-log: 
,03-24 21:18:31.335  3258  3314 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 21:18:31.335  3258  3314 I jxcore-log: 
,03-24 21:18:31.337  3258  3314 I jxcore-log: DEBUG createNativeListener: listening 59233
03-24 21:18:31.337  3258  3314 I jxcore-log: 
,03-24 21:18:31.340  3258  3314 I io.jxcore.node.ConnectionHelper: start: Port number: 59233, start advertisements: true
03-24 21:18:31.340  3258  3314 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 21:18:31.341  3258  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-24 21:18:31.341  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-24 21:18:31.342  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-24 21:18:31.342  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 21:18:31.342  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 21:18:31.342  3258  3314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 21:18:31.345  2145  2166 D BtGatt.GattService: registerClient() - UUID=e68362d2-76e3-4d0f-bff8-333ddb06abf4
,03-24 21:18:31.345  2145  2208 D BtGatt.GattService: onClientRegistered() - UUID=e68362d2-76e3-4d0f-bff8-333ddb06abf4, clientIf=5
03-24 21:18:31.345  3258  3274 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-24 21:18:31.346  2145  2210 D BtGatt.GattService: start scan with filters,
03-24 21:18:31.347  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 21:18:31.347  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 21:18:31.347  2145  2223 D BtGatt.ScanManager: handling starting scan,
03-24 21:18:31.348  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING],
03-24 21:18:31.348  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-24 21:18:31.348  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 21:18:31.348  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 21:18:31.348  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 21:18:31.348  3258  3258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-24 21:18:31.348  3258  3314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 21:18:31.348  3258  3314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 21:18:31.348  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 21:18:31.348  3258  3314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-24 21:18:31.348  2145  2208 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1,
03-24 21:18:31.348  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:18:31.349  2145  2208 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 21:18:31.349  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:18:31.349  2145  2223 D BtGatt.ScanManager: Starting BLE batch scan
03-24 21:18:31.350  2145  2223 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-24 21:18:31.351  2145  2164 D BtGatt.GattService: registerClient() - UUID=60707fa3-ab42-4d83-8295-4536445cda2a
03-24 21:18:31.351  2145  2208 D BtGatt.GattService: onClientRegistered() - UUID=60707fa3-ab42-4d83-8295-4536445cda2a, clientIf=6
03-24 21:18:31.351  3258  3822 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-24 21:18:31.351  2145  2208 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 21:18:31.351  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:18:31.352  2145  2221 D BtGatt.AdvertiseManager: message : 0
03-24 21:18:31.352  2145  2208 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 21:18:31.352  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 21:18:31.355  2145  2221 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 21:18:31.356  2145  2208 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 21:18:31.359  2145  2208 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 21:18:31.360  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-24 21:18:31.360  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 21:18:31.360   820   835 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 21:18:31.362  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-24 21:18:31.362  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 21:18:31.362  3258  3314 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-24 21:18:31.362  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-24 21:18:31.363  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-24 21:18:31.363  3258  3314 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-24 21:18:31.364  3258  3314 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-24 21:18:31.364  3258  3314 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,03-24 21:18:31.364  3258  3258 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,03-24 21:18:31.364  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 21:18:31.364  3258  3258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-24 21:18:31.364  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-24 21:18:31.365  3258  3258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
,03-24 21:18:31.365  3258  3258 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING],
03-24 21:18:31.365  3258  3258 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 21:18:31.365  3258  3258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 21:18:31.365   820  1375 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 21:18:31.365  3258  3258 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-24 21:18:31.365  3258  3258 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 21:18:31.365  3258  3258 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-24 21:18:31.365  3258  3258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-24 21:18:31.366  3258  3824 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-24 21:18:31.366  3258  3314 I io.jxcore.node.ConnectionHelper: start: OK
03-24 21:18:31.367  3258  3824 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
03-24 21:18:31.368  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 21:18:31.368  3258  3314 I jxcore-log: 
03-24 21:18:31.374  3258  3314 I jxcore-log: not ok 208 discoveryActive matches
03-24 21:18:31.374  3258  3314 I jxcore-log: 
03-24 21:18:31.374  3258  3314 I jxcore-log:   ---
03-24 21:18:31.374  3258  3314 I jxcore-log: 
03-24 21:18:31.374  3258  3314 I jxcore-log:     operator: equal
03-24 21:18:31.374  3258  3314 I jxcore-log: 
,03-24 21:18:31.374  3258  3314 I jxcore-log:     expected: false
03-24 21:18:31.374  3258  3314 I jxcore-log: 
03-24 21:18:31.374  3258  3314 I jxcore-log:     actual:   true
03-24 21:18:31.374  3258  3314 I jxcore-log: 
03-24 21:18:31.374  3258  3314 I jxcore-log:   ...
03-24 21:18:31.374  3258  3314 I jxcore-log: 
,03-24 21:18:31.378  3258  3314 I jxcore-log: not ok 209 advertisingActive matches
03-24 21:18:31.378  3258  3314 I jxcore-log: 
,03-24 21:18:31.379  3258  3314 I jxcore-log:   ---
03-24 21:18:31.379  3258  3314 I jxcore-log: 
,03-24 21:18:31.379  3258  3314 I jxcore-log:     operator: equal
03-24 21:18:31.379  3258  3314 I jxcore-log: 
,03-24 21:18:31.379  3258  3314 I jxcore-log:     expected: true
03-24 21:18:31.379  3258  3314 I jxcore-log: 
03-24 21:18:31.379  3258  3314 I jxcore-log:     actual:   false
03-24 21:18:31.379  3258  3314 I jxcore-log: 
,03-24 21:18:31.379  3258  3314 I jxcore-log:   ...
03-24 21:18:31.379  3258  3314 I jxcore-log: 
03-24 21:18:31.382  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false},
03-24 21:18:31.382  3258  3314 I jxcore-log: 
03-24 21:18:31.386  3258  3314 I jxcore-log: not ok 210 discoveryActive matches
03-24 21:18:31.386  3258  3314 I jxcore-log: 
03-24 21:18:31.386  3258  3314 I jxcore-log:   ---
03-24 21:18:31.386  3258  3314 I jxcore-log: 
03-24 21:18:31.387  3258  3314 I jxcore-log:     operator: equal,
03-24 21:18:31.387  3258  3314 I jxcore-log: 
03-24 21:18:31.387  3258  3314 I jxcore-log:     expected: false
03-24 21:18:31.387  3258  3314 I jxcore-log: 
03-24 21:18:31.387  3258  3314 I jxcore-log:     actual:   true
03-24 21:18:31.387  3258  3314 I jxcore-log: 
03-24 21:18:31.387  3258  3314 I jxcore-log:   ...
03-24 21:18:31.387  3258  3314 I jxcore-log: 
03-24 21:18:31.388  3258  3314 I jxcore-log: ok 211 advertisingActive matches
03-24 21:18:31.388  3258  3314 I jxcore-log: ,
03-24 21:18:31.390  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-24 21:18:31.390  3258  3314 I jxcore-log: 
03-24 21:18:31.391  3258  3314 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-24 21:18:31.391  3258  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
,03-24 21:18:31.391  3258  3314 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-24 21:18:31.391  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-24 21:18:31.391  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-24 21:18:31.392  3258  3314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-24 21:18:31.392  3258  3824 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-24 21:18:31.392  3258  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,03-24 21:18:31.392  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-24 21:18:31.392  3258  3824 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-24 21:18:31.392  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-24 21:18:31.392  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,03-24 21:18:31.392  3258  3258 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-24 21:18:31.392  3258  3258 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-24 21:18:31.392  3258  3258 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-24 21:18:31.392  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 21:18:31.392  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-24 21:18:31.392  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-24 21:18:31.395  2145  2166 D BtGatt.GattService: stopScan() - queue size =1
03-24 21:18:31.398  2145  2208 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 21:18:31.398  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:18:31.398  2145  2223 D BtGatt.ScanManager: stopping BLe Batch
03-24 21:18:31.398  2145  2210 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-24 21:18:31.399  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-24 21:18:31.399  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 21:18:31.400  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false,
,03-24 21:18:31.400  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-24 21:18:31.400  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-24 21:18:31.400  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 21:18:31.400  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,03-24 21:18:31.401  2145  2208 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 21:18:31.401  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:18:31.401  2145  2221 D BtGatt.AdvertiseManager: message : 1
03-24 21:18:31.402  2145  2223 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 21:18:31.402  2145  2221 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-24 21:18:31.403  2145  2208 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 21:18:31.403  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:18:31.404  2145  2208 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 21:18:31.404  2145  2208 D BtGatt.GattService: Client app is not null!
03-24 21:18:31.406  2145  2210 D BtGatt.GattService: unregisterClient() - clientIf=6
03-24 21:18:31.407  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 21:18:31.407  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-24 21:18:31.407  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-24 21:18:31.407  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,03-24 21:18:31.407  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-24 21:18:31.407  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 21:18:31.407  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 21:18:31.407  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-24 21:18:31.408  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-24 21:18:31.408  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 21:18:31.408  3258  3258 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 21:18:31.408  3258  3258 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 21:18:31.409  3258  3258 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 21:18:31.409  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-24 21:18:31.409  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-24 21:18:31.411  3258  3314 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 21:18:31.411  3258  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 21:18:31.411  3258  3314 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 21:18:31.414  3258  3258 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-24 21:18:31.414   820  3100 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 21:18:31.419  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-24 21:18:31.420  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-24 21:18:31.420  3258  3258 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 21:18:31.424  3258  3258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-24 21:18:31.424  3258  3258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 21:18:31.424  3258  3258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false,
03-24 21:18:31.425  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
,03-24 21:18:31.425  3258  3314 I jxcore-log: 
03-24 21:18:31.426  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false},
03-24 21:18:31.426  3258  3314 I jxcore-log: 
03-24 21:18:31.427  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false},
03-24 21:18:31.427  3258  3314 I jxcore-log: 
03-24 21:18:31.437  3258  3314 I jxcore-log: DEBUG createNativeListener: creating native server,
03-24 21:18:31.437  3258  3314 I jxcore-log: 
,03-24 21:18:31.439  3258  3314 I jxcore-log: DEBUG createNativeListener: listening 38304,
03-24 21:18:31.439  3258  3314 I jxcore-log: 
,03-24 21:18:31.446  3258  3314 I jxcore-log: # teardown
03-24 21:18:31.446  3258  3314 I jxcore-log: 
,03-24 21:18:31.969  3258  3314 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 21:18:31.970  3258  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 21:18:31.970  3258  3314 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 21:18:31.974  3258  3314 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 21:18:31.974  3258  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-24 21:18:31.974  3258  3314 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 21:18:31.983  3258  3314 I jxcore-log: # setup
03-24 21:18:31.983  3258  3314 I jxcore-log: 
,03-24 21:18:32.195  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 21:18:32.195  3258  3314 I jxcore-log: 
,03-24 21:18:32.198  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 21:18:32.198  3258  3314 I jxcore-log: 
,03-24 21:18:32.210  3258  3314 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 21:18:32.210  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 21:18:32.210  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 21:18:32.210  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 21:18:32.210  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 21:18:32.210  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 21:18:32.210  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 21:18:32.210  3258  3314 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 21:18:32.215  3258  3314 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 21:18:32.219  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 21:18:32.219  3258  3314 I jxcore-log: 
,03-24 21:18:32.223  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 21:18:32.223  3258  3314 I jxcore-log: 
,03-24 21:18:32.231  3258  3314 I jxcore-log: # 57. can do HTTP requests between peers
03-24 21:18:32.231  3258  3314 I jxcore-log: 
,03-24 21:18:32.235  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 21:18:32.235  3258  3314 I jxcore-log: 
,03-24 21:18:32.371  3258  3314 I jxcore-log: DEBUG createNativeListener: creating native server
,03-24 21:18:32.371  3258  3314 I jxcore-log: 
03-24 21:18:32.374  3258  3314 I jxcore-log: DEBUG createNativeListener: listening 36134
03-24 21:18:32.374  3258  3314 I jxcore-log: 
,03-24 21:18:32.381  3258  3314 I io.jxcore.node.ConnectionHelper: start: Port number: 59233, start advertisements: false,
03-24 21:18:32.381  3258  3314 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 21:18:32.381  3258  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 21:18:32.381  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-24 21:18:32.386  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...,
,03-24 21:18:32.386  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 21:18:32.386  3258  3314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 21:18:32.394  2145  2166 D BtGatt.GattService: registerClient() - UUID=fd7c7bf3-dd6c-4a22-b5e8-da22b71dd7a7
03-24 21:18:32.394  2145  2208 D BtGatt.GattService: onClientRegistered() - UUID=fd7c7bf3-dd6c-4a22-b5e8-da22b71dd7a7, clientIf=5,
03-24 21:18:32.395  3258  3822 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5,
03-24 21:18:32.395  2145  2164 D BtGatt.GattService: start scan with filters
03-24 21:18:32.396  2145  2223 D BtGatt.ScanManager: handling starting scan
,03-24 21:18:32.397  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
03-24 21:18:32.398  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 21:18:32.398  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-24 21:18:32.398  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,03-24 21:18:32.398  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
,03-24 21:18:32.400  3258  3258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-24 21:18:32.401  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-24 21:18:32.402   820  1333 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 21:18:32.406  2145  2208 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1,
,03-24 21:18:32.407  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
,03-24 21:18:32.408  2145  2208 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 21:18:32.408  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 21:18:32.409  2145  2223 D BtGatt.ScanManager: Starting BLE batch scan
03-24 21:18:32.409  2145  2223 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 21:18:32.411  2145  2208 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 21:18:32.412  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 21:18:32.413  2145  2208 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 21:18:32.414  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 21:18:32.416  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-24 21:18:32.416  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 21:18:32.416  3258  3314 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 21:18:32.417  3258  3258 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,03-24 21:18:32.417  3258  3258 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 21:18:32.417  3258  3258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 21:18:32.420  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 21:18:32.420  3258  3314 I jxcore-log: 
,03-24 21:18:32.440  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 21:18:32.440  3258  3314 I jxcore-log: 
,03-24 21:18:32.445  3258  3314 I io.jxcore.node.ConnectionHelper: start: Port number: 36134, start advertisements: true
,03-24 21:18:32.445  3258  3314 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 21:18:32.445  3258  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-24 21:18:32.445  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-24 21:18:32.450  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-24 21:18:32.450  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
03-24 21:18:32.450  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,03-24 21:18:32.450  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,03-24 21:18:32.450  3258  3314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 21:18:32.451  3258  3314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 21:18:32.451  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-24 21:18:32.451  3258  3314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-24 21:18:32.459  2145  2166 D BtGatt.GattService: registerClient() - UUID=79589541-4326-4b45-a2a5-f28dc59b722e
,03-24 21:18:32.459  2145  2208 D BtGatt.GattService: onClientRegistered() - UUID=79589541-4326-4b45-a2a5-f28dc59b722e, clientIf=6
,03-24 21:18:32.460  3258  3275 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-24 21:18:32.462  2145  2221 D BtGatt.AdvertiseManager: message : 0
,03-24 21:18:32.467  2145  2221 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 21:18:32.471  2145  2208 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 21:18:32.474  2145  2208 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 21:18:32.475  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,03-24 21:18:32.476  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-24 21:18:32.477  3258  3258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-24 21:18:32.477  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-24 21:18:32.479  3258  3258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-24 21:18:32.479  3258  3258 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING],
03-24 21:18:32.480  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 21:18:32.480   820  3100 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 21:18:32.489  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true,
03-24 21:18:32.489  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 21:18:32.490  3258  3258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-24 21:18:32.491  3258  3314 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-24 21:18:32.491  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 21:18:32.492  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...,
,03-24 21:18:32.493  3258  3314 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,03-24 21:18:32.493  3258  3314 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-24 21:18:32.493  3258  3314 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-24 21:18:32.493  3258  3314 I io.jxcore.node.ConnectionHelper: start: OK
03-24 21:18:32.493  3258  3258 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,03-24 21:18:32.493  3258  3258 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 21:18:32.494  3258  3258 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-24 21:18:32.497   820  1333 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 21:18:32.498  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-24 21:18:32.498  3258  3314 I jxcore-log: 
03-24 21:18:32.499  3258  3825 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-24 21:18:32.504  3258  3825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-24 21:18:33.426  2145  2145 D BtGatt.ScanManager: awakened up at time 295063
03-24 21:18:33.427  2145  2223 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 21:18:33.433  2145  2208 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,03-24 21:18:33.433  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 21:18:33.434  2145  2208 D BtGatt.GattService: current time is 295070996604
03-24 21:18:33.434  2145  2208 D BtGatt.GattService: Batch record : [-73, 9, 68, -6, 104, 125, 1, -128, -78, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -60, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
,03-24 21:18:33.434  2145  2208 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 21:18:33.435  2145  2208 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
,03-24 21:18:33.438  3258  3258 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 1
,03-24 21:18:33.439  3258  3258 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> E0:DB:10:14:E2:C0], added - the peer count is 2,
03-24 21:18:33.439  3258  3258 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
03-24 21:18:33.440  3258  3258 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> E0:DB:10:14:E2:C0], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 
03-24 21:18:33.442  3258  3314 I jxcore-log: DEBUG createPeerListener: createPeerListener
03-24 21:18:33.442  3258  3314 I jxcore-log: 
,03-24 21:18:33.445  3258  3314 I jxcore-log: DEBUG createPeerListener: pleaseConnect= false,
03-24 21:18:33.445  3258  3314 I jxcore-log: 
,03-24 21:18:33.447  3258  3314 I jxcore-log: ok 212 found a peer! {"peerIdentifier":"F8:95:C7:87:3C:51","portNumber":42803,"hostAddress":"127.0.0.1"}
,03-24 21:18:33.447  3258  3314 I jxcore-log: 
,03-24 21:18:33.458  3258  3314 I jxcore-log: DEBUG createPeerListener: first connection
03-24 21:18:33.458  3258  3314 I jxcore-log: 
,03-24 21:18:33.463  3258  3314 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID F8:95:C7:87:3C:51
,03-24 21:18:33.463  3258  3314 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> F8:95:C7:87:3C:51]
03-24 21:18:33.465  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to G4-1 in address F8:95:C7:87:3C:51
03-24 21:18:33.465  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
,03-24 21:18:33.465  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
03-24 21:18:33.465  3258  3314 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: G4-1 F8:95:C7:87:3C:51
,03-24 21:18:33.465  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to G4-1 in address F8:95:C7:87:3C:51
03-24 21:18:33.465  3258  3314 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: F8:95:C7:87:3C:51)
,03-24 21:18:33.467  3258  3826 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address F8:95:C7:87:3C:51 (thread ID: 374)
03-24 21:18:33.467  3258  3826 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-24 21:18:33.469  3258  3314 I jxcore-log: DEBUG createPeerListener: createPeerListener
,03-24 21:18:33.469  3258  3314 I jxcore-log: 
03-24 21:18:33.470  2145  2210 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,03-24 21:18:33.473  3258  3314 I jxcore-log: DEBUG createPeerListener: pleaseConnect= false
,03-24 21:18:33.473  3258  3314 I jxcore-log: 
,03-24 21:18:36.368  2145  2242 W bt-btif : info:x10
,03-24 21:18:36.368  2145  2208 D         : remote version info [f8:95:c7:87:3c:51]: 7, f, 2205
,03-24 21:18:36.405  3761  3761 I BTConnectionReceiver: onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,03-24 21:18:36.411  3761  3761 I BluetoothClassifier: Bluetooth Device Name: G4-1
,03-24 21:18:36.480  2145  2242 W bt-sdp  : process_service_search_attr_rsp
,03-24 21:18:37.137  2145  2208 D btif_config: btif_get_device_type: Device [f8:95:c7:87:3c:51] type 1,
,03-24 21:18:37.145  2145  2208 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
03-24 21:18:37.146  2145  2208 E bt-btif : check_cod: remote_cod = 0x5a020c
,03-24 21:18:37.153  2145  2209 I BluetoothBondStateMachine: Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
03-24 21:18:37.154  2145  2209 I BluetoothBondStateMachine: Entering PendingCommandState State
,03-24 21:18:37.305  2145  2208 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
03-24 21:18:37.306  2145  2209 D BluetoothAdapterProperties: Failed to remove device: F8:95:C7:87:3C:51
,03-24 21:18:37.313  2145  2209 I BluetoothBondStateMachine: Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,03-24 21:18:37.326  2145  2209 I BluetoothBondStateMachine: StableState(): Entering Off State
,03-24 21:18:37.374  2145  2242 W bt-btif : new conn_srvc id:26, app_id:1
03-24 21:18:37.374  2145  2242 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:1
03-24 21:18:37.374  2145  2242 W bt-btif : bta_dm_pm_ssr:2, lat:1200
03-24 21:18:37.374  3258  3826 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onSocketConnected: [<no peer name> F8:95:C7:87:3C:51] (thread ID: 374)
03-24 21:18:37.374  3258  3826 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 374)
03-24 21:18:37.376  3258  3826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesWritten: 15 bytes successfully written (thread ID: 375)
03-24 21:18:37.376  3258  3826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Outgoing connection initialized (*handshake* thread ID: 375)
,03-24 21:18:37.376  3258  3826 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 374)
,03-24 21:18:37.378  3258  3827 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 375)
,03-24 21:18:37.390  3258  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesRead: Read 15 bytes successfully (thread ID: 375)
,03-24 21:18:37.394  3258  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Handshake succeeded with [<no peer name> F8:95:C7:87:3C:51]
,03-24 21:18:37.394  3258  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onHandshakeSucceeded: [<no peer name> F8:95:C7:87:3C:51] (thread ID: 374)
03-24 21:18:37.394  3258  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: handleSuccessfulClientThread: [<no peer name> F8:95:C7:87:3C:51] (thread ID: 374)
03-24 21:18:37.394  3258  3827 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 375)
03-24 21:18:37.395  3258  3258 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> F8:95:C7:87:3C:51]
03-24 21:18:37.395  3258  3258 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing connection to peer [<no peer name> F8:95:C7:87:3C:51]
,03-24 21:18:37.395  3258  3258 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
03-24 21:18:37.395  3258  3258 I io.jxcore.node.ConnectionHelper: lowerBleDiscoveryPowerAndStartResetTimer: Lowering the power settings
03-24 21:18:37.396  3258  3258 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 2 -> 0,
03-24 21:18:37.396  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 21:18:37.396  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 21:18:37.396  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-24 21:18:37.396  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-24 21:18:37.396  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-24 21:18:37.396  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-24 21:18:37.403  2145  2221 D BtGatt.AdvertiseManager: message : 1
,03-24 21:18:37.405  2145  2221 D BtGatt.AdvertiseManager: stop advertise for client 6
03-24 21:18:37.410  2145  2208 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 21:18:37.410  2145  2208 D BtGatt.GattService: Client app is not null!
03-24 21:18:37.414  2145  2164 D BtGatt.GattService: unregisterClient() - clientIf=6
03-24 21:18:37.414  3258  3258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 21:18:37.414  3258  3258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-24 21:18:37.414  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 3, timeout: 0, is connectable: false
03-24 21:18:37.414  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,03-24 21:18:37.415  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 21:18:37.415  3258  3258 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 21:18:37.415  3258  3258 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 21:18:37.415  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 21:18:37.415  3258  3258 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-24 21:18:37.424  2145  2210 D BtGatt.GattService: registerClient() - UUID=cd8af547-abda-4347-8367-0539e4924287
03-24 21:18:37.424  2145  2208 D BtGatt.GattService: onClientRegistered() - UUID=cd8af547-abda-4347-8367-0539e4924287, clientIf=6
03-24 21:18:37.425  3258  3275 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-24 21:18:37.426  2145  2221 D BtGatt.AdvertiseManager: message : 0
,03-24 21:18:37.429  2145  2221 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 21:18:37.432  2145  2208 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0,
,03-24 21:18:37.435  2145  2208 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 21:18:37.436  3258  3258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-24 21:18:37.438  2145  2210 D BtGatt.GattService: stopScan() - queue size =1
,03-24 21:18:37.439  2145  2166 D BtGatt.GattService: unregisterClient() - clientIf=5
03-24 21:18:37.439  3258  3258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 21:18:37.439  3258  3258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-24 21:18:37.439  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-24 21:18:37.439  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 21:18:37.439  3258  3258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-24 21:18:37.439  3258  3258 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 21:18:37.440  2145  2208 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 21:18:37.440  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:18:37.440  2145  2223 D BtGatt.ScanManager: stopping BLe Batch
03-24 21:18:37.442  2145  2208 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 21:18:37.442  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:18:37.442  2145  2223 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 21:18:37.444  2145  2208 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,03-24 21:18:37.444  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:18:37.445  2145  2208 D BtGatt.GattService: current time is 299082066134
03-24 21:18:37.445  2145  2208 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -59, 47, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0, -73, 9, 68, -6, 104, 125, 1, -128, -78, 50, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-24 21:18:37.445  2145  2164 D BtGatt.GattService: registerClient() - UUID=e30fc2d5-00f7-47d0-9f3b-916ade0faca1
03-24 21:18:37.445  2145  2208 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-24 21:18:37.446  2145  2208 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 21:18:37.446  2145  2208 D BtGatt.GattService: onClientRegistered() - UUID=e30fc2d5-00f7-47d0-9f3b-916ade0faca1, clientIf=5
03-24 21:18:37.447  3258  3274 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 21:18:37.447  2145  2210 D BtGatt.GattService: start scan with filters
,03-24 21:18:37.449  3258  3258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
,03-24 21:18:37.449  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 21:18:37.449  3258  3258 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 3 -> 1
03-24 21:18:37.449  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 21:18:37.449  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 21:18:37.449  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-24 21:18:37.449  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-24 21:18:37.449  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-24 21:18:37.449  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-24 21:18:37.452  2145  2223 D BtGatt.ScanManager: handling starting scan
03-24 21:18:37.452  2145  2221 D BtGatt.AdvertiseManager: message : 1
03-24 21:18:37.453  2145  2221 D BtGatt.AdvertiseManager: stop advertise for client 6
03-24 21:18:37.456  2145  2208 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 21:18:37.456  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 21:18:37.457  2145  2208 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,03-24 21:18:37.457  2145  2208 D BtGatt.GattService: Client app is not null!,
03-24 21:18:37.458  2145  2164 D BtGatt.GattService: unregisterClient() - clientIf=6
03-24 21:18:37.458  3258  3258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 21:18:37.458  3258  3258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-24 21:18:37.458  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-24 21:18:37.458  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 21:18:37.459  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 21:18:37.459  3258  3258 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61,
,03-24 21:18:37.459  3258  3258 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 21:18:37.459  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 21:18:37.459  3258  3258 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-24 21:18:37.459  2145  2208 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,03-24 21:18:37.459  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:18:37.460  2145  2223 D BtGatt.ScanManager: Starting BLE batch scan
03-24 21:18:37.460  2145  2223 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-24 21:18:37.461  2145  2208 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 21:18:37.461  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:18:37.464  2145  2208 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,03-24 21:18:37.464  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:18:37.464  2145  2166 D BtGatt.GattService: registerClient() - UUID=b1dce222-bf80-4a50-b521-81de6a47fe94
,03-24 21:18:37.464  2145  2208 D BtGatt.GattService: onClientRegistered() - UUID=b1dce222-bf80-4a50-b521-81de6a47fe94, clientIf=6
03-24 21:18:37.465  3258  3275 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-24 21:18:37.466  2145  2221 D BtGatt.AdvertiseManager: message : 0
,03-24 21:18:37.468  2145  2221 D BtGatt.AdvertiseManager: starting multi advertising
03-24 21:18:37.471  2145  2208 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 21:18:37.473  2145  2208 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 21:18:37.474  3258  3258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-24 21:18:37.475  2145  2166 D BtGatt.GattService: stopScan() - queue size =1
,03-24 21:18:37.476  2145  2210 D BtGatt.GattService: unregisterClient() - clientIf=5,
03-24 21:18:37.476  3258  3258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 21:18:37.476  3258  3258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 21:18:37.476  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 21:18:37.476  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 21:18:37.477  3258  3258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 21:18:37.477  3258  3258 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-24 21:18:37.477  2145  2208 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 21:18:37.477  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:18:37.477  2145  2223 D BtGatt.ScanManager: stopping BLe Batch,
03-24 21:18:37.480  2145  2208 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 21:18:37.480  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:18:37.480  2145  2223 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 21:18:37.481  2145  2208 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 21:18:37.481  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 21:18:37.481  2145  2164 D BtGatt.GattService: registerClient() - UUID=17eff05c-9927-4753-8867-70c3e82ab0cd
,03-24 21:18:37.481  2145  2208 D BtGatt.GattService: onClientRegistered() - UUID=17eff05c-9927-4753-8867-70c3e82ab0cd, clientIf=5
03-24 21:18:37.482  3258  3274 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-24 21:18:37.482  2145  2166 D BtGatt.GattService: start scan with filters
03-24 21:18:37.484  3258  3258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 21:18:37.484  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 21:18:37.484  3258  3258 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 2 -> 0
03-24 21:18:37.484  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 21:18:37.484  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 21:18:37.484  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-24 21:18:37.484  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-24 21:18:37.484  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-24 21:18:37.484  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-24 21:18:37.486  2145  2223 D BtGatt.ScanManager: handling starting scan
03-24 21:18:37.486  2145  2221 D BtGatt.AdvertiseManager: message : 1
03-24 21:18:37.487  2145  2221 D BtGatt.AdvertiseManager: stop advertise for client 6
03-24 21:18:37.489  2145  2208 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 21:18:37.489  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:18:37.490  2145  2208 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 21:18:37.490  2145  2208 D BtGatt.GattService: Client app is not null!
,03-24 21:18:37.491  2145  2166 D BtGatt.GattService: unregisterClient() - clientIf=6,
03-24 21:18:37.491  3258  3258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 21:18:37.491  3258  3258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-24 21:18:37.491  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-24 21:18:37.491  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,03-24 21:18:37.491  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 21:18:37.491  3258  3258 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 21:18:37.492  3258  3258 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 21:18:37.492  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 21:18:37.492  3258  3258 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-24 21:18:37.493  2145  2208 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 21:18:37.493  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:18:37.493  2145  2223 D BtGatt.ScanManager: Starting BLE batch scan
03-24 21:18:37.493  2145  2223 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 21:18:37.495  2145  2208 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,03-24 21:18:37.495  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:18:37.496  2145  2208 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 21:18:37.496  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:18:37.500  2145  2210 D BtGatt.GattService: registerClient() - UUID=756039c7-e580-484e-a713-840f08e1d50a
03-24 21:18:37.500  2145  2208 D BtGatt.GattService: onClientRegistered() - UUID=756039c7-e580-484e-a713-840f08e1d50a, clientIf=6
03-24 21:18:37.501  3258  3275 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-24 21:18:37.503  2145  2221 D BtGatt.AdvertiseManager: message : 0
,03-24 21:18:37.507  2145  2221 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 21:18:37.510  2145  2208 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 21:18:37.513  2145  2208 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 21:18:37.514  3258  3258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING,
,03-24 21:18:37.516  2145  2210 D BtGatt.GattService: stopScan() - queue size =1
,03-24 21:18:37.518  2145  2208 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16,
03-24 21:18:37.518  2145  2166 D BtGatt.GattService: unregisterClient() - clientIf=5
03-24 21:18:37.518  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:18:37.519  2145  2223 D BtGatt.ScanManager: stopping BLe Batch
03-24 21:18:37.519  3258  3258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 21:18:37.519  3258  3258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 21:18:37.519  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
,03-24 21:18:37.519  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-24 21:18:37.519  3258  3258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 21:18:37.519  3258  3258 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 21:18:37.521  2145  2208 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0,
03-24 21:18:37.521  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 21:18:37.522  2145  2223 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 21:18:37.524  2145  2208 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
03-24 21:18:37.524  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 21:18:37.527  2145  2164 D BtGatt.GattService: registerClient() - UUID=0eb5a8c1-4dc6-497e-8d22-d8e54aa2ab7a,
03-24 21:18:37.528  2145  2208 D BtGatt.GattService: onClientRegistered() - UUID=0eb5a8c1-4dc6-497e-8d22-d8e54aa2ab7a, clientIf=5
,03-24 21:18:37.528  3258  3274 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 21:18:37.528  2145  2210 D BtGatt.GattService: start scan with filters
,03-24 21:18:37.529  2145  2223 D BtGatt.ScanManager: handling starting scan
,03-24 21:18:37.529  3258  3258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 21:18:37.529  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 21:18:37.530  3258  3258 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing socket thread, for peer [<no peer name> F8:95:C7:87:3C:51], created successfully
03-24 21:18:37.530  3258  3258 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 1
03-24 21:18:37.530  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 21:18:37.530  3258  3258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-24 21:18:37.530  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-24 21:18:37.531  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 21:18:37.531  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 21:18:37.531  2145  2208 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 21:18:37.531  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:18:37.532  2145  2208 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 21:18:37.532  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:18:37.532  2145  2223 D BtGatt.ScanManager: Starting BLE batch scan
03-24 21:18:37.532  2145  2223 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 21:18:37.532  3258  3828 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 376)
03-24 21:18:37.534  2145  2208 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 21:18:37.534  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:18:37.534  3258  3828 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 38262
03-24 21:18:37.534  3258  3828 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
03-24 21:18:37.534  3258  3828 I io.jxcore.node.ConnectionHelper: onListeningForIncomingConnections: Outgoing connection is using port 38262 (peer ID: F8:95:C7:87:3C:51)
03-24 21:18:37.535  2145  2208 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 21:18:37.535  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:18:37.535  3258  3828 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "F8:95:C7:87:3C:51" removed
,03-24 21:18:37.539  3258  3314 I jxcore-log: DEBUG createPeerListener: forward connection
03-24 21:18:37.539  3258  3314 I jxcore-log: 
,03-24 21:18:37.544  3258  3828 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 38262,
03-24 21:18:37.544  3258  3828 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
03-24 21:18:37.544  3258  3828 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-24 21:18:37.545  3258  3828 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-24 21:18:37.545  3258  3829 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 377, name: Sender)
,03-24 21:18:37.546  3258  3828 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 376)
03-24 21:18:37.546  3258  3828 D io.jxcore.node.OutgoingSocketThread: Exiting thread (ID: 376)
,03-24 21:18:37.549  3258  3830 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 378, name: Receiver)
,03-24 21:18:37.780  3258  3314 I jxcore-log: ok 213 server should return 200
03-24 21:18:37.780  3258  3314 I jxcore-log: 
,03-24 21:18:37.792  3258  3314 I jxcore-log: ok 214 response body should match testData
03-24 21:18:37.792  3258  3314 I jxcore-log: 
,03-24 21:18:37.798  3258  3314 I jxcore-log: # teardown
03-24 21:18:37.798  3258  3314 I jxcore-log: 
,03-24 21:18:37.810  3258  3829 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 377, thread name: Sender)
03-24 21:18:37.810  3258  3829 E io.jxcore.node.OutgoingSocketThread: The sending thread failed with error: Input stream got -1 on read
,03-24 21:18:37.811  3258  3829 W io.jxcore.node.ConnectionHelper: onDisconnected: Outgoing connection, peer [<no peer name> F8:95:C7:87:3C:51] disconnected: Input stream got -1 on read
03-24 21:18:37.811  3258  3829 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: F8:95:C7:87:3C:51
03-24 21:18:37.811  3258  3829 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 376)
03-24 21:18:37.811  3258  3829 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 376)
03-24 21:18:37.811  3258  3830 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 378, thread name: Receiver): bt socket closed, read return: -1
03-24 21:18:37.812  3258  3830 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 378, name: Receiver)
03-24 21:18:37.813  3258  3829 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
,03-24 21:18:37.813  3258  3829 D io.jxcore.node.OutgoingSocketThread: close: Stopping receiving thread...
03-24 21:18:37.813  3258  3829 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 378
,03-24 21:18:37.813  3258  3829 D io.jxcore.node.OutgoingSocketThread: close: Stopping sending thread...
03-24 21:18:37.813  3258  3829 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 377
03-24 21:18:37.813  3258  3829 D io.jxcore.node.OutgoingSocketThread: closeLocalSocketAndStreams: Closing... (thread ID: 376)
03-24 21:18:37.814  3258  3829 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 376)
03-24 21:18:37.815  3258  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
03-24 21:18:37.815  3258  3829 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 377, name: Sender)
,03-24 21:18:38.030  2145  2242 W bt-btif : bta_jv_rfc_port_to_cb(port_handle:0x18):jv handle:0x0 not FOUND
,03-24 21:18:41.475  2145  2242 E bt-btm  : btm_sec_disconnected - Clearing Pending flag
,03-24 21:18:41.482  2145  2145 D BluetoothMapService: onReceive
,03-24 21:18:41.510  3258  3314 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-24 21:18:41.511  3258  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-24 21:18:41.511  3258  3314 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-24 21:18:41.511  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-24 21:18:41.511  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-24 21:18:41.511  3761  3761 I BTConnectionReceiver: onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
03-24 21:18:41.511  3258  3314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-24 21:18:41.512  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-24 21:18:41.512  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-24 21:18:41.512  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 21:18:41.512  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 21:18:41.512  3258  3825 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-24 21:18:41.512  3258  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-24 21:18:41.512  3258  3825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-24 21:18:41.514  3761  3761 I BluetoothClassifier: Bluetooth Device Name: G4-1
03-24 21:18:41.515  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-24 21:18:41.515  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-24 21:18:41.518  2145  2210 D BtGatt.GattService: stopScan() - queue size =1
03-24 21:18:41.520  2145  2166 D BtGatt.GattService: unregisterClient() - clientIf=5
03-24 21:18:41.521  2145  2208 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 21:18:41.521  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:18:41.521  2145  2223 D BtGatt.ScanManager: stopping BLe Batch
03-24 21:18:41.522  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 21:18:41.522  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 21:18:41.522  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-24 21:18:41.522  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-24 21:18:41.522  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-24 21:18:41.522  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 21:18:41.523  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-24 21:18:41.523  2145  2208 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 21:18:41.523  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:18:41.524  2145  2223 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 21:18:41.524  2145  2221 D BtGatt.AdvertiseManager: message : 1
03-24 21:18:41.525  2145  2221 D BtGatt.AdvertiseManager: stop advertise for client 6
03-24 21:18:41.526  2145  2208 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-24 21:18:41.527  2145  2208 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 21:18:41.527  2145  2208 D BtGatt.GattService: current time is 303164186133
03-24 21:18:41.527  2145  2208 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -58, 44, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0, -45, 83, -128, 79, -44, 71, 1, -128, -90, 61, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-24 21:18:41.527  2145  2208 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-24 21:18:41.528  2145  2208 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 21:18:41.528  2145  2208 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 21:18:41.528  2145  2208 D BtGatt.GattService: Client app is not null!
03-24 21:18:41.530  2145  2166 D BtGatt.GattService: unregisterClient() - clientIf=6
03-24 21:18:41.531  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 21:18:41.531  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-24 21:18:41.531  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-24 21:18:41.531  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-24 21:18:41.531  3258  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-24 21:18:41.531  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 21:18:41.531  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 21:18:41.531  3258  3314 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-24 21:18:41.532  3258  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-24 21:18:41.532  3258  3314 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-24 21:18:41.532  3258  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 21:18:41.533  3258  3258 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 21:18:41.533  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 21:18:41.533  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-24 21:18:41.539  3258  3258 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-24 21:18:41.540   820   835 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 21:18:41.547  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-24 21:18:41.549  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-24 21:18:41.549  3258  3258 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-24 21:18:41.549  3258  3258 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-24 21:18:41.549  3258  3258 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 21:18:41.555  3258  3258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 21:18:41.555  3258  3258 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 21:18:41.555  3258  3258 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 21:18:41.556  3258  3258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 21:18:41.556  3258  3258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 21:18:41.557  3258  3258 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-24 21:18:41.557  3258  3314 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 21:18:41.557  3258  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 21:18:41.557  3258  3314 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 21:18:41.559  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-24 21:18:41.559  3258  3314 I jxcore-log: 
03-24 21:18:41.560  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 21:18:41.560  3258  3314 I jxcore-log: 
03-24 21:18:41.561  3258  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 21:18:41.561  3258  3314 I jxcore-log: 
,03-24 21:18:41.575  3258  3314 I jxcore-log: # setup,
03-24 21:18:41.575  3258  3314 I jxcore-log: 
,03-24 21:18:41.864  3258  3314 I jxcore-log: # 58. Test BEACONS_RETRIEVED_AND_PARSED locally
03-24 21:18:41.864  3258  3314 I jxcore-log: 
,03-24 21:18:42.370  2145  2206 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,03-24 21:18:42.509  3258  3314 I jxcore-log: ok 215 peerIdentifier should be hello,
03-24 21:18:42.509  3258  3314 I jxcore-log: 
,03-24 21:18:42.510  3258  3314 I jxcore-log: ok 216 Response should be BEACONS_RETRIEVED_AND_PARSED
03-24 21:18:42.510  3258  3314 I jxcore-log: 
03-24 21:18:42.511  3258  3314 I jxcore-log: ok 217 good beacon
03-24 21:18:42.511  3258  3314 I jxcore-log: 
,03-24 21:18:42.511  3258  3314 I jxcore-log: ok 218 good preAmble
03-24 21:18:42.511  3258  3314 I jxcore-log: ,
03-24 21:18:42.511  3258  3314 I jxcore-log: ok 219 public keys match!
03-24 21:18:42.511  3258  3314 I jxcore-log: 
03-24 21:18:42.512  3258  3314 I jxcore-log: ok 220 must return null after successful call
03-24 21:18:42.512  3258  3314 I jxcore-log: 
,03-24 21:18:42.520  3258  3314 I jxcore-log: # teardown
03-24 21:18:42.520  3258  3314 I jxcore-log: 
,03-24 21:18:43.474  3258  3314 I jxcore-log: # setup
03-24 21:18:43.474  3258  3314 I jxcore-log: 
,03-24 21:18:44.469  3258  3314 I jxcore-log: # 59. Test HTTP_BAD_RESPONSE locally
03-24 21:18:44.469  3258  3314 I jxcore-log: 
,03-24 21:18:45.328  3258  3314 I jxcore-log: ok 221 Response should be HTTP_BAD_RESPONSE
03-24 21:18:45.328  3258  3314 I jxcore-log: 
,03-24 21:18:45.330  3258  3314 I jxcore-log: ok 222 must return null after successful call
03-24 21:18:45.330  3258  3314 I jxcore-log: 
,03-24 21:18:45.340  3258  3314 I jxcore-log: # teardown
03-24 21:18:45.340  3258  3314 I jxcore-log: 
,03-24 21:18:45.485  3258  3314 I jxcore-log: # setup
03-24 21:18:45.485  3258  3314 I jxcore-log: 
,03-24 21:18:45.740  3258  3314 I jxcore-log: # 60. Test NETWORK_PROBLEM locally
03-24 21:18:45.740  3258  3314 I jxcore-log: 
,03-24 21:18:46.790  3258  3314 I jxcore-log: ok 223 Response should be NETWORK_PROBLEM
03-24 21:18:46.790  3258  3314 I jxcore-log: 
,03-24 21:18:46.797  3258  3314 I jxcore-log: ok 224 reject reason should be: Could not establish TCP connection
03-24 21:18:46.797  3258  3314 I jxcore-log: 
,03-24 21:18:46.813  3258  3314 I jxcore-log: # teardown
03-24 21:18:46.813  3258  3314 I jxcore-log: 
,03-24 21:18:46.863  3258  3314 I jxcore-log: # setup
03-24 21:18:46.863  3258  3314 I jxcore-log: 
,03-24 21:18:48.109  3258  3314 I jxcore-log: # 61. Test timeout locally
03-24 21:18:48.109  3258  3314 I jxcore-log: 
,03-24 21:18:49.336  3258  3314 I jxcore-log: ok 225 Should be NETWORK_PROBLEM caused by timeout
03-24 21:18:49.336  3258  3314 I jxcore-log: 
,03-24 21:18:49.344  3258  3314 I jxcore-log: ok 226 reject reason should be Could not establish TCP connection
03-24 21:18:49.344  3258  3314 I jxcore-log: 
,03-24 21:18:49.351  3258  3314 I jxcore-log: # teardown
03-24 21:18:49.351  3258  3314 I jxcore-log: 
,03-24 21:18:49.714  3258  3314 I jxcore-log: # setup
03-24 21:18:49.714  3258  3314 I jxcore-log: 
,03-24 21:18:49.941  3258  3314 I jxcore-log: # 62. Call the start two times
03-24 21:18:49.941  3258  3314 I jxcore-log: 
,03-24 21:18:50.117  3258  3314 I jxcore-log: ok 227 Call start once
03-24 21:18:50.117  3258  3314 I jxcore-log: 
,03-24 21:18:50.165  3258  3314 I jxcore-log: ok 228 Response should be BEACONS_RETRIEVED_AND_PARSED
03-24 21:18:50.165  3258  3314 I jxcore-log: 
,03-24 21:18:50.166  3258  3314 I jxcore-log: ok 229 must return null after successful call.
03-24 21:18:50.166  3258  3314 I jxcore-log: 
,03-24 21:18:50.176  3258  3314 I jxcore-log: # teardown
03-24 21:18:50.176  3258  3314 I jxcore-log: 
,03-24 21:18:50.334  3258  3314 I jxcore-log: # setup
03-24 21:18:50.334  3258  3314 I jxcore-log: 
,03-24 21:18:50.532  3258  3314 I jxcore-log: # 63. Call the kill before calling the start
03-24 21:18:50.532  3258  3314 I jxcore-log: 
,03-24 21:18:50.737  3258  3314 I jxcore-log: ok 230 Should be Killed
03-24 21:18:50.737  3258  3314 I jxcore-log: 
,03-24 21:18:50.749  3258  3314 I jxcore-log: ok 231 Start after killed
03-24 21:18:50.749  3258  3314 I jxcore-log: 
,03-24 21:18:50.760  3258  3314 I jxcore-log: # teardown
03-24 21:18:50.760  3258  3314 I jxcore-log: 
,03-24 21:18:50.905  3258  3314 I jxcore-log: # setup
03-24 21:18:50.905  3258  3314 I jxcore-log: 
,03-24 21:18:51.130  3258  3314 I jxcore-log: # 64. Call the kill immediately after the start
03-24 21:18:51.130  3258  3314 I jxcore-log: 
,03-24 21:18:51.304  3258  3314 I jxcore-log: ok 232 Should be KILLED
03-24 21:18:51.304  3258  3314 I jxcore-log: 
,03-24 21:18:51.306  3258  3314 I jxcore-log: ok 233 must return null after successful kill,
03-24 21:18:51.306  3258  3314 I jxcore-log: ,
,03-24 21:18:51.315  3258  3314 I jxcore-log: # teardown
03-24 21:18:51.315  3258  3314 I jxcore-log: 
,03-24 21:18:51.415  3258  3314 I jxcore-log: # setup
03-24 21:18:51.415  3258  3314 I jxcore-log: 
,03-24 21:18:51.619  3258  3314 I jxcore-log: # 65. Call the kill while waiting a response from the server,
,03-24 21:18:51.619  3258  3314 I jxcore-log: ,
,03-24 21:18:52.817  3258  3258 I io.jxcore.node.ConnectionHelper: restoreDefaultBleDiscoverySettings: Powering the BLE discovery back up
03-24 21:18:52.818  3258  3258 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 0 -> 2
03-24 21:18:52.818  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 21:18:52.818  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 21:18:52.818  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-24 21:18:52.818  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-24 21:18:52.818  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-24 21:18:52.818  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-24 21:18:52.819  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 1, timeout: 0, is connectable: false
03-24 21:18:52.819  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-24 21:18:52.819  3258  3258 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 1 -> 3
03-24 21:18:52.819  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 21:18:52.819  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 21:18:52.819  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-24 21:18:52.819  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-24 21:18:52.819  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-24 21:18:52.819  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-24 21:18:52.819  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-24 21:18:52.820  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-24 21:18:52.820  3258  3258 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 0 -> 2
03-24 21:18:52.820  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 21:18:52.820  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 21:18:52.820  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-24 21:18:52.820  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-24 21:18:52.820  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-24 21:18:52.820  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-24 21:18:52.820  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-24 21:18:52.820  3258  3258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanS,ettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-24 21:18:53.806  3258  3314 I jxcore-log: ok 234 Should be KILLED
03-24 21:18:53.806  3258  3314 I jxcore-log: 
03-24 21:18:53.809  3258  3314 I jxcore-log: ok 235 must return null after successful kill
03-24 21:18:53.809  3258  3314 I jxcore-log: 
,03-24 21:18:53.838  3258  3314 I jxcore-log: # teardown,
,03-24 21:18:53.838  3258  3314 I jxcore-log: 
,03-24 21:18:54.024  3258  3314 I jxcore-log: # setup,
03-24 21:18:54.024  3258  3314 I jxcore-log: 
,03-24 21:18:54.235  3258  3314 I jxcore-log: # 66. Test to exceed the max content size locally
03-24 21:18:54.235  3258  3314 I jxcore-log: 
,03-24 21:18:54.387  3258  3314 I jxcore-log: ok 236 HTTP_BAD_RESPONSE should be response when content size is exceeded
03-24 21:18:54.387  3258  3314 I jxcore-log: ,
,03-24 21:18:54.390  3258  3314 I jxcore-log: ok 237 must return null after successful call
03-24 21:18:54.390  3258  3314 I jxcore-log: 
,03-24 21:18:54.400  3258  3314 I jxcore-log: # teardown
03-24 21:18:54.400  3258  3314 I jxcore-log: 
,03-24 21:18:54.590  3258  3314 I jxcore-log: # setup
03-24 21:18:54.590  3258  3314 I jxcore-log: 
,03-24 21:18:54.752  3258  3314 I jxcore-log: # 67. Close the server socket while the client is waiting a response from the server. Local test.
03-24 21:18:54.752  3258  3314 I jxcore-log: 
,03-24 21:18:57.010  3258  3314 I jxcore-log: ok 238 Should be NETWORK_PROBLEM caused closing server socket
03-24 21:18:57.010  3258  3314 I jxcore-log: 
,03-24 21:18:57.019  3258  3314 I jxcore-log: ok 239 Should be Could not establish TCP connection
03-24 21:18:57.019  3258  3314 I jxcore-log: 
,03-24 21:18:57.030  3258  3314 I jxcore-log: # teardown
03-24 21:18:57.030  3258  3314 I jxcore-log: 
,03-24 21:18:57.118  3258  3314 I jxcore-log: # setup
03-24 21:18:57.118  3258  3314 I jxcore-log: 
,03-24 21:18:57.339  3258  3314 I jxcore-log: # 68. Close the client socket while the client is waiting a response from the server. Local test.
03-24 21:18:57.339  3258  3314 I jxcore-log: 
,03-24 21:18:58.329  1266  1715 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-24 21:18:58.329  1266  1715 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 21:18:58.329  1266  1715 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 21:18:58.330  1266  1715 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 21:18:58.334  1266  1715 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 21:18:58.352  3082  3838 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
03-24 21:18:58.352  3082  3838 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-24 21:18:58.352  3082  3838 E HttpOperation: 	at jdm.a(PG:82)
03-24 21:18:58.352  3082  3838 E HttpOperation: 	at jcs.o(PG:406)
03-24 21:18:58.352  3082  3838 E HttpOperation: 	at jcn.a(PG:1379)
03-24 21:18:58.352  3082  3838 E HttpOperation: 	at jcs.i(PG:143)
03-24 21:18:58.352  3082  3838 E HttpOperation: 	at blb.a(PG:3937)
03-24 21:18:58.352  3082  3838 E HttpOperation: 	at czp.a(PG:18188)
03-24 21:18:58.352  3082  3838 E HttpOperation: 	at czp.a(PG:9081)
03-24 21:18:58.352  3082  3838 E HttpOperation: 	at czq.run(PG:1686)
03-24 21:18:58.352  3082  3838 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-24 21:18:58.352  3082  3838 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 21:18:58.352  3082  3838 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 21:18:58.352  3082  3838 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 21:18:58.352  3082  3838 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-24 21:18:58.352  3082  3838 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-24 21:18:58.352  3082  3838 E HttpOperation: 	at jdj.a(PG:4091)
03-24 21:18:58.352  3082  3838 E HttpOperation: 	at jdj.a(PG:1125)
03-24 21:18:58.352  3082  3838 E HttpOperation: 	at jdm.a(PG:77)
03-24 21:18:58.352  3082  3838 E HttpOperation: 	... 12 more
03-24 21:18:58.352  3082  3838 E HttpOperation: Caused by: faj: BadAuthentication
03-24 21:18:58.352  3082  3838 E HttpOperation: 	at fal.a(PG:38)
03-24 21:18:58.352  3082  3838 E HttpOperation: 	at jdj.a(PG:4089)
03-24 21:18:58.352  3082  3838 E HttpOperation: 	... 14 more
,03-24 21:18:58.409  1266  1715 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-24 21:18:58.410  1266  1715 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 21:18:58.410  1266  1715 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-24 21:18:58.411  1266  1715 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 21:18:58.419  1266  1715 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 21:18:58.445  3082  3838 E HttpOperation: [getmobileexperiments] Unexpected exception
03-24 21:18:58.445  3082  3838 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-24 21:18:58.445  3082  3838 E HttpOperation: 	at jdm.a(PG:82)
03-24 21:18:58.445  3082  3838 E HttpOperation: 	at jcs.o(PG:406)
03-24 21:18:58.445  3082  3838 E HttpOperation: 	at jcn.a(PG:1379)
03-24 21:18:58.445  3082  3838 E HttpOperation: 	at jcs.i(PG:143)
03-24 21:18:58.445  3082  3838 E HttpOperation: 	at hec.a(PG:42)
03-24 21:18:58.445  3082  3838 E HttpOperation: 	at hee.a(PG:102)
03-24 21:18:58.445  3082  3838 E HttpOperation: 	at czr.a(PG:65)
03-24 21:18:58.445  3082  3838 E HttpOperation: 	at kka.a(PG:108)
03-24 21:18:58.445  3082  3838 E HttpOperation: 	at czp.a(PG:19176)
03-24 21:18:58.445  3082  3838 E HttpOperation: 	at czp.a(PG:9081)
03-24 21:18:58.445  3082  3838 E HttpOperation: 	at czq.run(PG:1686)
03-24 21:18:58.445  3082  3838 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-24 21:18:58.445  3082  3838 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 21:18:58.445  3082  3838 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 21:18:58.445  3082  3838 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 21:18:58.445  3082  3838 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-24 21:18:58.445  3082  3838 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-24 21:18:58.445  3082  3838 E HttpOperation: 	at jdj.a(PG:4091)
03-24 21:18:58.445  3082  3838 E HttpOperation: 	at jdj.a(PG:1125)
03-24 21:18:58.445  3082  3838 E HttpOperation: 	at jdm.a(PG:77)
03-24 21:18:58.445  3082  3838 E HttpOperation: 	... 15 more
03-24 21:18:58.445  3082  3838 E HttpOperation: Caused by: faj: BadAuthentication
03-24 21:18:58.445  3082  3838 E HttpOperation: 	at fal.a(PG:38)
03-24 21:18:58.445  3082  3838 E HttpOperation: 	at jdj.a(PG:4089)
03-24 21:18:58.445  3082  3838 E HttpOperation: 	... 17 more
,03-24 21:18:58.447  3082  3838 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
03-24 21:18:58.447  3082  3838 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
03-24 21:18:58.447  3082  3838 E ExperimentLoader: 	at jdm.a(PG:82),
03-24 21:18:58.447  3082  3838 E ExperimentLoader: 	at jcs.o(PG:406)
03-24 21:18:58.447  3082  3838 E ExperimentLoader: 	at jcn.a(PG:1379)
03-24 21:18:58.447  3082  3838 E ExperimentLoader: 	at jcs.i(PG:143)
03-24 21:18:58.447  3082  3838 E ExperimentLoader: 	at hec.a(PG:42)
03-24 21:18:58.447  3082  3838 E ExperimentLoader: 	at hee.a(PG:102)
03-24 21:18:58.447  3082  3838 E ExperimentLoader: 	,at czr.a(PG:65)
03-24 21:18:58.447  3082  3838 E ExperimentLoader: 	at kka.a(PG:108)
03-24 21:18:58.447  3082  3838 E ExperimentLoader: 	at czp.a(PG:19176)
03-24 21:18:58.447  3082  3838 E ExperimentLoader: 	at czp.a(PG:9081)
03-24 21:18:58.447  3082  3838 E ExperimentLoader: 	at czq.run(PG:1686)
03-24 21:18:58.447  3082  3838 E ExperimentLoader: 	,at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-24 21:18:58.447  3082  3838 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 21:18:58.447  3082  3838 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 21:18:58.447  3082  3838 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 21:18:58.447  3082  3838 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
03-24 21:18:58.447  3082  3838 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-24 21:18:58.447  3082  3838 E ExperimentLoader: 	at jdj.a(PG:4091),
03-24 21:18:58.447  3082  3838 E ExperimentLoader: 	at jdj.a(PG:1125)
03-24 21:18:58.447  3082  3838 E ExperimentLoader: 	at jdm.a(PG:77)
03-24 21:18:58.447  3082  3838 E ExperimentLoader: 	... 15 more
03-24 21:18:58.447  3082  3838 E ExperimentLoader: Caused by: faj: BadAuthentication
03-24 21:18:58.447  3082  3838 E ExperimentLoader: 	at fal.a(PG:38)
03-24 21:18:58.447  3082  3838 E ExperimentLoader: 	at jdj.a(PG:4089)
03-24 21:18:58.447  3082  3838 E ExperimentLoader: 	,... 17 more
,03-24 21:18:58.571   820   853 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 294113, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,03-24 21:18:59.554  3258  3314 I jxcore-log: ok 240 Should be NETWORK_PROBLEM caused closing client socket,
03-24 21:18:59.554  3258  3314 I jxcore-log: 
,03-24 21:18:59.561  3258  3314 I jxcore-log: ok 241 Should be Could not establish TCP connection
03-24 21:18:59.561  3258  3314 I jxcore-log: 
,03-24 21:18:59.587  3258  3314 I jxcore-log: # teardown
03-24 21:18:59.587  3258  3314 I jxcore-log: 
,03-24 21:18:59.758  3258  3314 I jxcore-log: # setup
03-24 21:18:59.758  3258  3314 I jxcore-log: 
,03-24 21:18:59.849  3258  3314 I jxcore-log: # 69. #generatePreambleAndBeacons bad args
03-24 21:18:59.849  3258  3314 I jxcore-log: 
,03-24 21:18:59.986  3258  3314 I jxcore-log: ok 242 publicKeysToNotify cannot be null
03-24 21:18:59.986  3258  3314 I jxcore-log: 
,03-24 21:18:59.988  3258  3314 I jxcore-log: ok 243 ecdh for local device cannot be null
03-24 21:18:59.988  3258  3314 I jxcore-log: 
03-24 21:18:59.989  3258  3314 I jxcore-log: ok 244 milliseconds cannot be less than 0
03-24 21:18:59.989  3258  3314 I jxcore-log: 
03-24 21:18:59.990  3258  3314 I jxcore-log: ok 245 milliseconds cannot be 0
03-24 21:18:59.990  3258  3314 I jxcore-log: 
03-24 21:18:59.992  3258  3314 I jxcore-log: ok 246 milliseconds cannot be greater than one_day
03-24 21:18:59.992  3258  3314 I jxcore-log: 
,03-24 21:18:59.996  3258  3314 I jxcore-log: # teardown
03-24 21:18:59.996  3258  3314 I jxcore-log: 
,03-24 21:19:00.125  3258  3314 I jxcore-log: # setup
03-24 21:19:00.125  3258  3314 I jxcore-log: 
,03-24 21:19:00.263  3258  3314 I jxcore-log: # 70. #generatePreambleAndBeacons empty keys to notify
03-24 21:19:00.263  3258  3314 I jxcore-log: 
,03-24 21:19:00.382  3258  3314 I jxcore-log: ok 247 should be equal
,03-24 21:19:00.382  3258  3314 I jxcore-log: 
,03-24 21:19:00.386  3258  3314 I jxcore-log: # teardown
,03-24 21:19:00.386  3258  3314 I jxcore-log: 
,03-24 21:19:00.504  3258  3314 I jxcore-log: # setup
03-24 21:19:00.504  3258  3314 I jxcore-log: 
,03-24 21:19:00.734  3258  3314 I jxcore-log: # 71. #generatePreambleAndBeacons multiple keys to notify
03-24 21:19:00.734  3258  3314 I jxcore-log: 
,03-24 21:19:00.970  3258  3314 I jxcore-log: ok 248 should be equal
03-24 21:19:00.970  3258  3314 I jxcore-log: 
,03-24 21:19:00.971  3258  3314 I jxcore-log: ok 249 should be equal
03-24 21:19:00.971  3258  3314 I jxcore-log: 
03-24 21:19:00.971  3258  3314 I jxcore-log: ok 250 (unnamed assert)
03-24 21:19:00.971  3258  3314 I jxcore-log: 
,03-24 21:19:00.971  3258  3314 I jxcore-log: ok 251 should be equal
03-24 21:19:00.971  3258  3314 I jxcore-log: 
03-24 21:19:00.973  3258  3314 I jxcore-log: # teardown
03-24 21:19:00.973  3258  3314 I jxcore-log: 
,03-24 21:19:01.146  3258  3314 I jxcore-log: # setup
03-24 21:19:01.146  3258  3314 I jxcore-log: 
,03-24 21:19:01.348  3258  3314 I jxcore-log: # 72. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
03-24 21:19:01.348  3258  3314 I jxcore-log: 
,03-24 21:19:01.545  3258  3314 I jxcore-log: ok 252 should throw
03-24 21:19:01.545  3258  3314 I jxcore-log: 
,03-24 21:19:01.548  3258  3314 I jxcore-log: # teardown
03-24 21:19:01.548  3258  3314 I jxcore-log: 
,03-24 21:19:01.756  3258  3314 I jxcore-log: # setup
03-24 21:19:01.756  3258  3314 I jxcore-log: 
,03-24 21:19:01.872  3258  3314 I jxcore-log: # 73. #parseBeacons invalid expiration in beaconStreamWithPreAmble
03-24 21:19:01.872  3258  3314 I jxcore-log: 
,03-24 21:19:02.038  3258  3314 I jxcore-log: ok 253 Preamble expiration must be a 64 bit integer
03-24 21:19:02.038  3258  3314 I jxcore-log: 
,03-24 21:19:02.041  3258  3314 I jxcore-log: # teardown
03-24 21:19:02.041  3258  3314 I jxcore-log: 
,03-24 21:19:02.202  3258  3314 I jxcore-log: # setup
03-24 21:19:02.202  3258  3314 I jxcore-log: 
,03-24 21:19:02.375  3258  3314 I jxcore-log: # 74. #parseBeacons expiration out of range lower
03-24 21:19:02.375  3258  3314 I jxcore-log: 
,03-24 21:19:02.555  3258  3314 I jxcore-log: ok 254 Expiration out of range
03-24 21:19:02.555  3258  3314 I jxcore-log: 
,03-24 21:19:02.558  3258  3314 I jxcore-log: # teardown
03-24 21:19:02.558  3258  3314 I jxcore-log: 
,03-24 21:19:02.684  3258  3314 I jxcore-log: # setup
03-24 21:19:02.684  3258  3314 I jxcore-log: 
,03-24 21:19:02.815  3258  3314 I jxcore-log: # 75. #parseBeacons expiration out of range lower
03-24 21:19:02.815  3258  3314 I jxcore-log: 
,03-24 21:19:03.053  3258  3314 I jxcore-log: ok 255 Expiration out of range
03-24 21:19:03.053  3258  3314 I jxcore-log: 
,03-24 21:19:03.065  3258  3314 I jxcore-log: # teardown
03-24 21:19:03.065  3258  3314 I jxcore-log: 
,03-24 21:19:04.249  3258  3314 I jxcore-log: # setup
03-24 21:19:04.249  3258  3314 I jxcore-log: 
,03-24 21:19:04.358  3258  3314 I jxcore-log: # 76. #parseBeacons no beacons returns null
03-24 21:19:04.358  3258  3314 I jxcore-log: 
,03-24 21:19:04.505  3258  3314 I jxcore-log: ok 256 should be equal
,03-24 21:19:04.505  3258  3314 I jxcore-log: 
,03-24 21:19:04.508  3258  3314 I jxcore-log: # teardown
03-24 21:19:04.508  3258  3314 I jxcore-log: 
,03-24 21:19:04.626  3258  3314 I jxcore-log: # setup
03-24 21:19:04.626  3258  3314 I jxcore-log: 
,03-24 21:19:04.754  3258  3314 I jxcore-log: # 77. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
03-24 21:19:04.754  3258  3314 I jxcore-log: 
,03-24 21:19:05.003  3258  3314 I jxcore-log: ok 257 Malformed encrypted beacon key ID
03-24 21:19:05.003  3258  3314 I jxcore-log: 
,03-24 21:19:05.006  3258  3314 I jxcore-log: # teardown
03-24 21:19:05.006  3258  3314 I jxcore-log: 
,03-24 21:19:05.111  3258  3314 I jxcore-log: # setup
03-24 21:19:05.111  3258  3314 I jxcore-log: 
,03-24 21:19:05.309  3258  3314 I jxcore-log: # 78. #parseBeacons addressBookCallback fails decrypt
03-24 21:19:05.309  3258  3314 I jxcore-log: 
,03-24 21:19:05.777  3258  3314 I jxcore-log: ok 258 should be equal
03-24 21:19:05.777  3258  3314 I jxcore-log: 
,03-24 21:19:05.779  3258  3314 I jxcore-log: # teardown
03-24 21:19:05.779  3258  3314 I jxcore-log: 
,03-24 21:19:06.294  3258  3314 I jxcore-log: # setup
03-24 21:19:06.294  3258  3314 I jxcore-log: 
,03-24 21:19:06.435  3258  3314 I jxcore-log: # 79. #parseBeacons addressBookCallback returns no matches
03-24 21:19:06.435  3258  3314 I jxcore-log: 
,03-24 21:19:08.031  3258  3314 I jxcore-log: ok 259 should be equal
03-24 21:19:08.031  3258  3314 I jxcore-log: 
,03-24 21:19:08.031  3258  3314 I jxcore-log: ok 260 should be equal
03-24 21:19:08.031  3258  3314 I jxcore-log: 
03-24 21:19:08.033  3258  3314 I jxcore-log: # teardown
03-24 21:19:08.033  3258  3314 I jxcore-log: 
,03-24 21:19:08.099  3258  3314 I jxcore-log: # setup
03-24 21:19:08.099  3258  3314 I jxcore-log: 
,03-24 21:19:09.139  3258  3314 I jxcore-log: # 80. #parseBeacons addressBookCallback returns spurious match
03-24 21:19:09.139  3258  3314 I jxcore-log: 
,03-24 21:19:09.885  3258  3314 I jxcore-log: ok 261 should be equal
03-24 21:19:09.885  3258  3314 I jxcore-log: 
03-24 21:19:09.886  3258  3314 I jxcore-log: ok 262 should be equal
03-24 21:19:09.886  3258  3314 I jxcore-log: 
,03-24 21:19:09.888  3258  3314 I jxcore-log: # teardown
03-24 21:19:09.888  3258  3314 I jxcore-log: 
,03-24 21:19:10.112  3258  3314 I jxcore-log: # setup
03-24 21:19:10.112  3258  3314 I jxcore-log: 
,03-24 21:19:10.695  3258  3314 I jxcore-log: # 81. #parseBeacons addressBookCallback returns public key
03-24 21:19:10.695  3258  3314 I jxcore-log: 
,03-24 21:19:10.966  3258  3314 I jxcore-log: ok 263 right number of calls to address book,
03-24 21:19:10.966  3258  3314 I jxcore-log: 
03-24 21:19:10.967  3258  3314 I jxcore-log: ok 264 good preAmble
03-24 21:19:10.967  3258  3314 I jxcore-log: 
03-24 21:19:10.967  3258  3314 I jxcore-log: ok 265 good unencryptedKeyId,
03-24 21:19:10.967  3258  3314 I jxcore-log: 
03-24 21:19:10.967  3258  3314 I jxcore-log: ok 266 good beacon
03-24 21:19:10.967  3258  3314 I jxcore-log: 
03-24 21:19:10.969  3258  3314 I jxcore-log: # teardown,
03-24 21:19:10.969  3258  3314 I jxcore-log: 
,03-24 21:19:11.178  3258  3314 I jxcore-log: # setup,
03-24 21:19:11.178  3258  3314 I jxcore-log: 
,03-24 21:19:12.805  3258  3314 I jxcore-log: # 82. validate generatePskIdentityField,
03-24 21:19:12.805  3258  3314 I jxcore-log: 
,03-24 21:19:14.076  3258  3314 I jxcore-log: ok 267 decoded buffers match
03-24 21:19:14.076  3258  3314 I jxcore-log: 
,03-24 21:19:14.085  3258  3314 I jxcore-log: # teardown,
03-24 21:19:14.085  3258  3314 I jxcore-log: 
,03-24 21:19:14.224  3258  3314 I jxcore-log: # setup,
03-24 21:19:14.224  3258  3314 I jxcore-log: 
,03-24 21:19:14.376  3258  3314 I jxcore-log: # 83. validate generatePskSecret
03-24 21:19:14.376  3258  3314 I jxcore-log: 
,03-24 21:19:14.585  3258  3314 I jxcore-log: ok 268 secrets match
03-24 21:19:14.585  3258  3314 I jxcore-log: 
,03-24 21:19:14.587  3258  3314 I jxcore-log: # teardown
03-24 21:19:14.587  3258  3314 I jxcore-log: 
,03-24 21:19:14.769  3258  3314 I jxcore-log: # setup
03-24 21:19:14.769  3258  3314 I jxcore-log: 
,03-24 21:19:14.942  3258  3314 I jxcore-log: # 84. Start and stop ThaliNotificationServer
03-24 21:19:14.942  3258  3314 I jxcore-log: 
,03-24 21:19:15.235  3258  3314 I jxcore-log: ok 269 ThaliMobile.StartUpdateAdvertisingAndListening should be called once
03-24 21:19:15.235  3258  3314 I jxcore-log: 
,03-24 21:19:15.235  3258  3314 I jxcore-log: ok 270 ThaliMobile.StopAdvertisingAndListeningshould be called once
03-24 21:19:15.235  3258  3314 I jxcore-log: 
03-24 21:19:15.237  3258  3314 I jxcore-log: # teardown
03-24 21:19:15.237  3258  3314 I jxcore-log: 
,03-24 21:19:15.358  3258  3314 I jxcore-log: # setup
03-24 21:19:15.358  3258  3314 I jxcore-log: 
,03-24 21:19:15.527  3258  3314 I jxcore-log: # 85. Pass an empty array to ThaliNotificationServer.start
03-24 21:19:15.527  3258  3314 I jxcore-log: 
,03-24 21:19:17.618  3258  3314 I jxcore-log: ok 271 StartUpdateAdvertisingAndListening should not be called
03-24 21:19:17.618  3258  3314 I jxcore-log: 
,03-24 21:19:17.633  3258  3314 I jxcore-log: ok 272 ThaliMobile.StopAdvertisingAndListening should be called once
03-24 21:19:17.633  3258  3314 I jxcore-log: 
,03-24 21:19:17.674  3258  3314 I jxcore-log: ok 273 no error
03-24 21:19:17.674  3258  3314 I jxcore-log: 
03-24 21:19:17.675  3258  3314 I jxcore-log: ok 274 should be 204
03-24 21:19:17.675  3258  3314 I jxcore-log: 
,03-24 21:19:17.680  3258  3314 I jxcore-log: # teardown
03-24 21:19:17.680  3258  3314 I jxcore-log: 
,03-24 21:19:18.480  3258  3314 I jxcore-log: # setup
03-24 21:19:18.480  3258  3314 I jxcore-log: 
,03-24 21:19:19.866  3258  3314 I jxcore-log: # 86. Pass a string to ThaliNotificationServer.start
03-24 21:19:19.866  3258  3314 I jxcore-log: 
,03-24 21:19:20.110  3258  3314 I jxcore-log: ok 275 StartUpdateAdvertisingAndListening should not be called
03-24 21:19:20.110  3258  3314 I jxcore-log: 
,03-24 21:19:20.118  3258  3314 I jxcore-log: # teardown
03-24 21:19:20.118  3258  3314 I jxcore-log: 
,03-24 21:19:20.736  3258  3314 I jxcore-log: # setup
03-24 21:19:20.736  3258  3314 I jxcore-log: 
,03-24 21:19:20.874  3258  3314 I jxcore-log: # 87. Pass an empty parameter to ThaliNotificationServer.start
,03-24 21:19:20.874  3258  3314 I jxcore-log: 
,03-24 21:19:21.458  3258  3314 I jxcore-log: ok 276 StartUpdateAdvertisingAndListening should not be called
03-24 21:19:21.458  3258  3314 I jxcore-log: 
,03-24 21:19:21.465  3258  3314 I jxcore-log: # teardown
,03-24 21:19:21.465  3258  3314 I jxcore-log: 
,03-24 21:19:21.536  3258  3314 I jxcore-log: # setup
03-24 21:19:21.536  3258  3314 I jxcore-log: 
,03-24 21:19:21.695  3258  3314 I jxcore-log: # 88. Make an HTTP request to /NotificationBeacons
03-24 21:19:21.695  3258  3314 I jxcore-log: 
,03-24 21:19:21.953  3258  3314 I jxcore-log: ok 277 no error
03-24 21:19:21.953  3258  3314 I jxcore-log: 
,03-24 21:19:21.953  3258  3314 I jxcore-log: ok 278 should be 200
03-24 21:19:21.953  3258  3314 I jxcore-log: 
,03-24 21:19:21.953  3258  3314 I jxcore-log: ok 279 should be equal
03-24 21:19:21.953  3258  3314 I jxcore-log: 
03-24 21:19:21.954  3258  3314 I jxcore-log: ok 280 should be equal
03-24 21:19:21.954  3258  3314 I jxcore-log: 
,03-24 21:19:21.970  3258  3314 I jxcore-log: ok 281 (unnamed assert),
03-24 21:19:21.970  3258  3314 I jxcore-log: 
,03-24 21:19:21.998  3258  3314 I jxcore-log: ok 282 no error,
03-24 21:19:21.998  3258  3314 I jxcore-log: 
03-24 21:19:21.998  3258  3314 I jxcore-log: ok 283 should be 204
03-24 21:19:21.998  3258  3314 I jxcore-log: 
,03-24 21:19:22.003  3258  3314 I jxcore-log: # teardown,
03-24 21:19:22.003  3258  3314 I jxcore-log: 
,03-24 21:19:22.190  3258  3314 I jxcore-log: # setup
03-24 21:19:22.190  3258  3314 I jxcore-log: 
,03-24 21:19:22.383  3258  3314 I jxcore-log: # 89. Make an HTTP request to /NotificationBeacons (no keys)
03-24 21:19:22.383  3258  3314 I jxcore-log: 
,03-24 21:19:22.580  3258  3314 I jxcore-log: ok 284 error should be null
03-24 21:19:22.580  3258  3314 I jxcore-log: 
,03-24 21:19:22.581  3258  3314 I jxcore-log: ok 285 should be 204
03-24 21:19:22.581  3258  3314 I jxcore-log: 
,03-24 21:19:22.587  3258  3314 I jxcore-log: # teardown
03-24 21:19:22.587  3258  3314 I jxcore-log: 
,03-24 21:19:22.716  3258  3314 I jxcore-log: # setup
03-24 21:19:22.716  3258  3314 I jxcore-log: 
,03-24 21:19:22.849  3258  3314 I jxcore-log: # 90. Make an HTTP request to /NotificationBeaconsbefore calling start
03-24 21:19:22.849  3258  3314 I jxcore-log: 
,03-24 21:19:23.022  3258  3314 I jxcore-log: ok 286 should be 404
03-24 21:19:23.022  3258  3314 I jxcore-log: 
,03-24 21:19:23.029  3258  3314 I jxcore-log: # teardown
03-24 21:19:23.029  3258  3314 I jxcore-log: 
,03-24 21:19:23.154  3258  3314 I jxcore-log: # setup
03-24 21:19:23.154  3258  3314 I jxcore-log: 
,03-24 21:19:23.250  3258  3314 I jxcore-log: # 91. #testThaliPeerAction - test getters
03-24 21:19:23.250  3258  3314 I jxcore-log: 
,03-24 21:19:23.405  3258  3314 I jxcore-log: ok 287 getPeerIdentifier
03-24 21:19:23.405  3258  3314 I jxcore-log: 
,03-24 21:19:23.407  3258  3314 I jxcore-log: ok 288 getConnectionType
03-24 21:19:23.407  3258  3314 I jxcore-log: 
,03-24 21:19:23.408  3258  3314 I jxcore-log: ok 289 getActionType
03-24 21:19:23.408  3258  3314 I jxcore-log: 
,03-24 21:19:23.410  3258  3314 I jxcore-log: ok 290 getActionState
03-24 21:19:23.410  3258  3314 I jxcore-log: 
,03-24 21:19:23.416  3258  3314 I jxcore-log: # teardown
03-24 21:19:23.416  3258  3314 I jxcore-log: 
,03-24 21:19:23.520  3258  3314 I jxcore-log: # setup
03-24 21:19:23.520  3258  3314 I jxcore-log: 
,03-24 21:19:23.638  3258  3314 I jxcore-log: # 92. #testThaliPeerAction - start and kill
03-24 21:19:23.638  3258  3314 I jxcore-log: 
,03-24 21:19:23.757  3258  3314 I jxcore-log: ok 291 initial state
03-24 21:19:23.757  3258  3314 I jxcore-log: 
,03-24 21:19:23.762  3258  3314 I jxcore-log: ok 292 after start
03-24 21:19:23.762  3258  3314 I jxcore-log: 
,03-24 21:19:23.763  3258  3314 I jxcore-log: ok 293 after kill
03-24 21:19:23.763  3258  3314 I jxcore-log: 
,03-24 21:19:23.769  3258  3314 I jxcore-log: # teardown
03-24 21:19:23.769  3258  3314 I jxcore-log: 
,03-24 21:19:23.885  3258  3314 I jxcore-log: # setup
03-24 21:19:23.885  3258  3314 I jxcore-log: 
,03-24 21:19:23.987  3258  3314 I jxcore-log: # 93. #testThaliPeerAction - double start
03-24 21:19:23.987  3258  3314 I jxcore-log: 
,03-24 21:19:24.097  3258  3314 I jxcore-log: ok 294 should be equal
03-24 21:19:24.097  3258  3314 I jxcore-log: 
,03-24 21:19:24.099  3258  3314 I jxcore-log: # teardown
03-24 21:19:24.099  3258  3314 I jxcore-log: 
,03-24 21:19:24.213  3258  3314 I jxcore-log: # setup
,03-24 21:19:24.213  3258  3314 I jxcore-log: 
,03-24 21:19:24.383  3258  3314 I jxcore-log: # 94. #testThaliPeerAction - start after kill
03-24 21:19:24.383  3258  3314 I jxcore-log: 
,03-24 21:19:24.595  3258  3314 I jxcore-log: ok 295 clean kill
03-24 21:19:24.595  3258  3314 I jxcore-log: 
,03-24 21:19:24.597  3258  3314 I jxcore-log: ok 296 should be equal
03-24 21:19:24.597  3258  3314 I jxcore-log: 
,03-24 21:19:24.605  3258  3314 I jxcore-log: # teardown
03-24 21:19:24.605  3258  3314 I jxcore-log: 
,03-24 21:19:24.756  3258  3314 I jxcore-log: # setup
,03-24 21:19:24.756  3258  3314 I jxcore-log: 
,03-24 21:19:24.910  3258  3314 I jxcore-log: # 95. #testThaliPeerAction - make sure ids are unique
03-24 21:19:24.910  3258  3314 I jxcore-log: ,
,03-24 21:19:25.041  3258  3314 I jxcore-log: ok 297 should not be equal
03-24 21:19:25.041  3258  3314 I jxcore-log: 
,03-24 21:19:25.048  3258  3314 I jxcore-log: # teardown
03-24 21:19:25.048  3258  3314 I jxcore-log: 
,03-24 21:19:25.149  3258  3314 I jxcore-log: # setup
03-24 21:19:25.149  3258  3314 I jxcore-log: 
,03-24 21:19:25.300  3258  3314 I jxcore-log: # 96. Test PeerConnectionInformation basics
03-24 21:19:25.300  3258  3314 I jxcore-log: 
,03-24 21:19:25.428  3258  3314 I jxcore-log: ok 298 getHostAddress works
03-24 21:19:25.428  3258  3314 I jxcore-log: 
,03-24 21:19:25.430  3258  3314 I jxcore-log: ok 299 getPortNumber works
03-24 21:19:25.430  3258  3314 I jxcore-log: 
,03-24 21:19:25.431  3258  3314 I jxcore-log: ok 300 getSuggestedTCPTimeout works
03-24 21:19:25.431  3258  3314 I jxcore-log: 
,03-24 21:19:25.439  3258  3314 I jxcore-log: # teardown
03-24 21:19:25.439  3258  3314 I jxcore-log: 
,03-24 21:19:25.564  3258  3314 I jxcore-log: # setup
03-24 21:19:25.564  3258  3314 I jxcore-log: 
,03-24 21:19:25.648  3258  3314 I jxcore-log: # 97. Test PeerDictionary basic functionality
03-24 21:19:25.648  3258  3314 I jxcore-log: 
,03-24 21:19:25.844  3258  3314 I jxcore-log: ok 301 Entry counter must be 1
03-24 21:19:25.844  3258  3314 I jxcore-log: 
,03-24 21:19:25.844  3258  3314 I jxcore-log: ok 302 Size must be 1
03-24 21:19:25.844  3258  3314 I jxcore-log: 
,03-24 21:19:25.845  3258  3314 I jxcore-log: ok 303 Entry counter must be 2
03-24 21:19:25.845  3258  3314 I jxcore-log: 
03-24 21:19:25.845  3258  3314 I jxcore-log: ok 304 Size must be 2
03-24 21:19:25.845  3258  3314 I jxcore-log: 
,03-24 21:19:25.850  3258  3314 I jxcore-log: ok 305 Entry2 should not be found
03-24 21:19:25.850  3258  3314 I jxcore-log: 
03-24 21:19:25.851  3258  3314 I jxcore-log: ok 306 Size must be 1
03-24 21:19:25.851  3258  3314 I jxcore-log: 
03-24 21:19:25.851  3258  3314 I jxcore-log: ok 307 Size must be 0
03-24 21:19:25.851  3258  3314 I jxcore-log: 
,03-24 21:19:25.855  3258  3314 I jxcore-log: ok 308 entry not found must be thrown
03-24 21:19:25.855  3258  3314 I jxcore-log: 
,03-24 21:19:25.857  3258  3314 I jxcore-log: # teardown
03-24 21:19:25.857  3258  3314 I jxcore-log: 
,03-24 21:19:25.960  3258  3314 I jxcore-log: # setup
03-24 21:19:25.960  3258  3314 I jxcore-log: 
,03-24 21:19:26.058  3258  3314 I jxcore-log: # 98. Test PeerDictionary with multiple entries.
03-24 21:19:26.058  3258  3314 I jxcore-log: 
,03-24 21:19:26.959  3258  3314 I jxcore-log: ok 309 Size must be100
03-24 21:19:26.959  3258  3314 I jxcore-log: 
,03-24 21:19:26.961  3258  3314 I jxcore-log: ok 310 Entries between 20 and MAXSIZE + 20 should exist
03-24 21:19:26.961  3258  3314 I jxcore-log: 
,03-24 21:19:27.674  3258  3314 I jxcore-log: ok 311 WAITING state entry should not be removed
03-24 21:19:27.674  3258  3314 I jxcore-log: 
,03-24 21:19:27.676  3258  3314 I jxcore-log: # teardown
03-24 21:19:27.676  3258  3314 I jxcore-log: 
,03-24 21:19:27.736  3258  3314 I jxcore-log: # setup
03-24 21:19:27.736  3258  3314 I jxcore-log: 
,03-24 21:19:27.823  1266  1266 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,03-24 21:19:27.854  3258  3314 I jxcore-log: # 99. RESOLVED entries are removed before WAITING state entry.
03-24 21:19:27.854  3258  3314 I jxcore-log: 
,03-24 21:19:27.887  1266  2545 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
03-24 21:19:27.888  1266  2545 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 21:19:27.888  1266  2545 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 21:19:27.888  1266  2545 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 21:19:27.905  1266  2545 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 21:19:27.970  1266  2545 W GLSActivity: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-24 21:19:27.970  1266  2545 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-24 21:19:27.970  1266  2545 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-24 21:19:27.970  1266  2545 W GLSActivity: 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
03-24 21:19:27.970  1266  2545 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
03-24 21:19:27.970  1266  2545 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
03-24 21:19:27.970  1266  2545 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:446)
,03-24 21:19:27.975  2748  2784 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
03-24 21:19:27.975  2748  2784 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
03-24 21:19:27.975  2748  2784 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
03-24 21:19:27.975  2748  2784 E PlayEventLogger: 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
03-24 21:19:27.975  2748  2784 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
03-24 21:19:27.975  2748  2784 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
03-24 21:19:27.975  2748  2784 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:446)
,03-24 21:19:28.026  2748  2784 W System  : Ignoring header User-Agent because its value was null.
,03-24 21:19:28.779  3258  3314 I jxcore-log: ok 312 Entries between 6 and MAXSIZE + 4 should exist
03-24 21:19:28.779  3258  3314 I jxcore-log: 
03-24 21:19:28.779  3258  3314 I jxcore-log: ok 313 Size should be MAXSIZE
03-24 21:19:28.779  3258  3314 I jxcore-log: 
03-24 21:19:28.779  3258  3314 I jxcore-log: ok 314 Size should be MAXSIZE+6
03-24 21:19:28.779  3258  3314 I jxcore-log: 
,03-24 21:19:28.782  3258  3314 I jxcore-log: # teardown
03-24 21:19:28.782  3258  3314 I jxcore-log: 
,03-24 21:19:28.892  3258  3314 I jxcore-log: # setup
03-24 21:19:28.892  3258  3314 I jxcore-log: 
,03-24 21:19:29.021  3258  3314 I jxcore-log: # 100. WAITING entries are removed before CONTROLLED_BY_POOL state entry.
03-24 21:19:29.021  3258  3314 I jxcore-log: 
,03-24 21:19:29.795  3258  3314 I jxcore-log: ok 315 WAITING state entry should not be removed
03-24 21:19:29.795  3258  3314 I jxcore-log: 
,03-24 21:19:29.796  3258  3314 I jxcore-log: ok 316 Waiting entries between 6 and MAXSIZE + 4 should exist
03-24 21:19:29.796  3258  3314 I jxcore-log: 
,03-24 21:19:29.796  3258  3314 I jxcore-log: ok 317 Size should be MAXSIZE
03-24 21:19:29.796  3258  3314 I jxcore-log: 
03-24 21:19:29.797  3258  3314 I jxcore-log: ok 318 entryCounter should be MAXSIZE+6
03-24 21:19:29.797  3258  3314 I jxcore-log: 
03-24 21:19:29.799  3258  3314 I jxcore-log: # teardown
03-24 21:19:29.799  3258  3314 I jxcore-log: 
,03-24 21:19:29.936  3258  3314 I jxcore-log: # setup
03-24 21:19:29.936  3258  3314 I jxcore-log: 
,03-24 21:19:30.250  3258  3314 I jxcore-log: # 101. When CONTROLLED_BY_POOL entry is removed and kill is called.
03-24 21:19:30.250  3258  3314 I jxcore-log: 
,03-24 21:19:31.058  3258  3314 I jxcore-log: ok 319 Kill should be called once
03-24 21:19:31.058  3258  3314 I jxcore-log: 
,03-24 21:19:31.059  3258  3314 I jxcore-log: ok 320 Size should be 100
03-24 21:19:31.059  3258  3314 I jxcore-log: 
03-24 21:19:31.061  3258  3314 I jxcore-log: # teardown
03-24 21:19:31.061  3258  3314 I jxcore-log: 
,03-24 21:19:31.180  3258  3314 I jxcore-log: # setup
03-24 21:19:31.180  3258  3314 I jxcore-log: 
,03-24 21:19:31.348  3258  3314 I jxcore-log: # 102. #ThaliPeerPoolInterface - bad enqueues
03-24 21:19:31.348  3258  3314 I jxcore-log: 
,03-24 21:19:31.503  3258  3314 I jxcore-log: ok 321 null arg
03-24 21:19:31.503  3258  3314 I jxcore-log: 
,03-24 21:19:31.510  3258  3314 I jxcore-log: ok 322 wrong arg type
03-24 21:19:31.510  3258  3314 I jxcore-log: 
,03-24 21:19:31.515  3258  3314 I jxcore-log: ok 323 wrong state
03-24 21:19:31.515  3258  3314 I jxcore-log: 
,03-24 21:19:31.517  3258  3314 I jxcore-log: # teardown
03-24 21:19:31.517  3258  3314 I jxcore-log: 
,03-24 21:19:31.646  3258  3314 I jxcore-log: # setup
03-24 21:19:31.646  3258  3314 I jxcore-log: 
,03-24 21:19:31.785  3258  3314 I jxcore-log: # 103. #ThaliPeerPoolInterface - do not allow same object type
03-24 21:19:31.785  3258  3314 I jxcore-log: 
,03-24 21:19:31.958  3258  3314 I jxcore-log: ok 324 good enqueue
,03-24 21:19:31.958  3258  3314 I jxcore-log: 
,03-24 21:19:31.964  3258  3314 I jxcore-log: ok 325 should be equal,
03-24 21:19:31.964  3258  3314 I jxcore-log: 
,03-24 21:19:31.971  3258  3314 I jxcore-log: # teardown
03-24 21:19:31.971  3258  3314 I jxcore-log: 
,03-24 21:19:32.107  3258  3314 I jxcore-log: # setup
03-24 21:19:32.107  3258  3314 I jxcore-log: 
,03-24 21:19:32.255  3258  3314 I jxcore-log: # 104. #ThaliPeerPoolInterface - make sure we catch kill and dequeue
03-24 21:19:32.255  3258  3314 I jxcore-log: 
,03-24 21:19:32.418  3258  3314 I jxcore-log: ok 326 good enqueue
03-24 21:19:32.418  3258  3314 I jxcore-log: 
,03-24 21:19:32.418  3258  3314 I jxcore-log: ok 327 2nd good enqueue
03-24 21:19:32.418  3258  3314 I jxcore-log: 
03-24 21:19:32.419  3258  3314 I jxcore-log: ok 328 we are in the pool
03-24 21:19:32.419  3258  3314 I jxcore-log: 
,03-24 21:19:32.422  3258  3314 I jxcore-log: ok 329 We are out of the pool
03-24 21:19:32.422  3258  3314 I jxcore-log: 
,03-24 21:19:32.422  3258  3314 I jxcore-log: ok 330 Action was killed
03-24 21:19:32.422  3258  3314 I jxcore-log: 
03-24 21:19:32.423  3258  3314 I jxcore-log: ok 331 The original kill was called too
03-24 21:19:32.423  3258  3314 I jxcore-log: 
03-24 21:19:32.423  3258  3314 I jxcore-log: ok 332 second item is still in queue
03-24 21:19:32.423  3258  3314 I jxcore-log: 
,03-24 21:19:32.426  3258  3314 I jxcore-log: # teardown
03-24 21:19:32.426  3258  3314 I jxcore-log: 
,03-24 21:19:32.576  3258  3314 I jxcore-log: # setup
03-24 21:19:32.576  3258  3314 I jxcore-log: 
,03-24 21:19:32.706  3258  3314 I jxcore-log: # 105. #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent
03-24 21:19:32.706  3258  3314 I jxcore-log: 
,03-24 21:19:32.888  3258  3314 I jxcore-log: ok 333 good enqueue
03-24 21:19:32.888  3258  3314 I jxcore-log: 
,03-24 21:19:32.890  3258  3314 I jxcore-log: ok 334 first kill
03-24 21:19:32.890  3258  3314 I jxcore-log: 
,03-24 21:19:32.892  3258  3314 I jxcore-log: ok 335 second NOOP kill
03-24 21:19:32.892  3258  3314 I jxcore-log: 
,03-24 21:19:32.897  3258  3314 I jxcore-log: # teardown
03-24 21:19:32.897  3258  3314 I jxcore-log: 
,03-24 21:19:33.022  3258  3314 I jxcore-log: # setup
03-24 21:19:33.022  3258  3314 I jxcore-log: 
,03-24 21:19:33.134  3258  3314 I jxcore-log: # 106. compareBufferArrays
03-24 21:19:33.134  3258  3314 I jxcore-log: 
,03-24 21:19:33.316  3258  3314 I jxcore-log: ok 336 should throw
03-24 21:19:33.316  3258  3314 I jxcore-log: 
,03-24 21:19:33.317  3258  3314 I jxcore-log: ok 337 should throw
03-24 21:19:33.317  3258  3314 I jxcore-log: 
03-24 21:19:33.318  3258  3314 I jxcore-log: ok 338 (unnamed assert)
03-24 21:19:33.318  3258  3314 I jxcore-log: 
,03-24 21:19:33.319  3258  3314 I jxcore-log: ok 339 (unnamed assert)
03-24 21:19:33.319  3258  3314 I jxcore-log: 
,03-24 21:19:33.319  3258  3314 I jxcore-log: ok 340 (unnamed assert)
03-24 21:19:33.319  3258  3314 I jxcore-log: 
03-24 21:19:33.319  3258  3314 I jxcore-log: ok 341 (unnamed assert)
03-24 21:19:33.319  3258  3314 I jxcore-log: 
03-24 21:19:33.320  3258  3314 I jxcore-log: ok 342 (unnamed assert)
03-24 21:19:33.320  3258  3314 I jxcore-log: 
,03-24 21:19:33.323  3258  3314 I jxcore-log: # teardown
03-24 21:19:33.323  3258  3314 I jxcore-log: 
,03-24 21:19:33.452  3258  3314 I jxcore-log: # setup
03-24 21:19:33.452  3258  3314 I jxcore-log: 
,03-24 21:19:33.637  3258  3314 I jxcore-log: # 107. Call start twice and get error
03-24 21:19:33.637  3258  3314 I jxcore-log: 
,03-24 21:19:33.814  3258  3314 I jxcore-log: ok 343 should throw
03-24 21:19:33.814  3258  3314 I jxcore-log: 
,03-24 21:19:33.817  3258  3314 I jxcore-log: # teardown
03-24 21:19:33.817  3258  3314 I jxcore-log: 
,03-24 21:19:33.935  3258  3314 I jxcore-log: # setup
03-24 21:19:33.935  3258  3314 I jxcore-log: 
,03-24 21:19:34.092  3258  3314 I jxcore-log: # 108. Start and make sure it runs
03-24 21:19:34.092  3258  3314 I jxcore-log: 
,03-24 21:19:34.296  3258  3314 I jxcore-log: # teardown
03-24 21:19:34.296  3258  3314 I jxcore-log: 
,03-24 21:19:34.451  3258  3314 I jxcore-log: # setup
03-24 21:19:34.451  3258  3314 I jxcore-log: 
,03-24 21:19:34.641  3258  3314 I jxcore-log: # 109. Make sure getTimeWhenRun is right after start
03-24 21:19:34.641  3258  3314 I jxcore-log: 
,03-24 21:19:34.770  3258  3314 I jxcore-log: ok 344 (unnamed assert)
03-24 21:19:34.770  3258  3314 I jxcore-log: 
,03-24 21:19:34.776  3258  3314 I jxcore-log: # teardown
03-24 21:19:34.776  3258  3314 I jxcore-log: 
,03-24 21:19:34.875  3258  3314 I jxcore-log: # setup
03-24 21:19:34.875  3258  3314 I jxcore-log: 
,03-24 21:19:35.014  3258  3314 I jxcore-log: # 110. Make sure getTimeWhenRun is -1 after function is called
03-24 21:19:35.014  3258  3314 I jxcore-log: 
,03-24 21:19:35.147  3258  3314 I jxcore-log: ok 345 should be equal
03-24 21:19:35.147  3258  3314 I jxcore-log: 
,03-24 21:19:35.158  3258  3314 I jxcore-log: # teardown
03-24 21:19:35.158  3258  3314 I jxcore-log: 
,03-24 21:19:35.251  3258  3314 I jxcore-log: # setup
03-24 21:19:35.251  3258  3314 I jxcore-log: 
,03-24 21:19:35.375  3258  3314 I jxcore-log: # 111. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running
03-24 21:19:35.375  3258  3314 I jxcore-log: 
,03-24 21:19:35.566  3258  3314 I jxcore-log: ok 346 should be equal
03-24 21:19:35.566  3258  3314 I jxcore-log: 
,03-24 21:19:35.568  3258  3314 I jxcore-log: ok 347 should be equal
03-24 21:19:35.568  3258  3314 I jxcore-log: 
,03-24 21:19:35.575  3258  3314 I jxcore-log: ok 348 should throw
03-24 21:19:35.575  3258  3314 I jxcore-log: 
,03-24 21:19:35.577  3258  3314 I jxcore-log: # teardown
03-24 21:19:35.577  3258  3314 I jxcore-log: 
,03-24 21:19:35.683  3258  3314 I jxcore-log: # setup
03-24 21:19:35.683  3258  3314 I jxcore-log: 
,03-24 21:19:35.939  3258  3314 I jxcore-log: # 112. Test TransientState
03-24 21:19:35.939  3258  3314 I jxcore-log: 
,03-24 21:19:36.106  3258  3314 I jxcore-log: ok 349 should throw
03-24 21:19:36.106  3258  3314 I jxcore-log: 
,03-24 21:19:36.112  3258  3314 I jxcore-log: ok 350 should throw
03-24 21:19:36.112  3258  3314 I jxcore-log: 
,03-24 21:19:36.115  3258  3314 I jxcore-log: ok 351 should be equal,
03-24 21:19:36.115  3258  3314 I jxcore-log: 
03-24 21:19:36.115  3258  3314 I jxcore-log: ok 352 should be equal
03-24 21:19:36.115  3258  3314 I jxcore-log: 
03-24 21:19:36.115  3258  3314 I jxcore-log: ok 353 should be equal
03-24 21:19:36.115  3258  3314 I jxcore-log: 
,03-24 21:19:36.116  3258  3314 I jxcore-log: ok 354 should be equal
03-24 21:19:36.116  3258  3314 I jxcore-log: 
03-24 21:19:36.116  3258  3314 I jxcore-log: ok 355 (unnamed assert)
03-24 21:19:36.116  3258  3314 I jxcore-log: 
,03-24 21:19:36.117  3258  3314 I jxcore-log: ok 356 (unnamed assert)
03-24 21:19:36.117  3258  3314 I jxcore-log: 
03-24 21:19:36.120  3258  3314 I jxcore-log: # teardown
03-24 21:19:36.120  3258  3314 I jxcore-log: 
,03-24 21:19:36.317  3258  3314 I jxcore-log: # setup
03-24 21:19:36.317  3258  3314 I jxcore-log: 
,03-24 21:19:36.460  3258  3314 I jxcore-log: # 113. No peers and empty database
03-24 21:19:36.460  3258  3314 I jxcore-log: 
,03-24 21:19:36.709  3258  3314 I jxcore-log: ok 357 verify failed
03-24 21:19:36.709  3258  3314 I jxcore-log: 
03-24 21:19:36.709  3258  3314 I jxcore-log: ok 358 constructor called once
03-24 21:19:36.709  3258  3314 I jxcore-log: 
03-24 21:19:36.711  3258  3314 I jxcore-log: ok 359 constructor called with right args
03-24 21:19:36.711  3258  3314 I jxcore-log: 
03-24 21:19:36.711  3258  3314 I jxcore-log: ok 360 match start arg
03-24 21:19:36.711  3258  3314 I jxcore-log: 
,03-24 21:19:36.711  3258  3314 I jxcore-log: ok 361 start called once
03-24 21:19:36.711  3258  3314 I jxcore-log: 
03-24 21:19:36.711  3258  3314 I jxcore-log: ok 362 stop called once
03-24 21:19:36.711  3258  3314 I jxcore-log: 
,03-24 21:19:36.712  3258  3314 I jxcore-log: ok 363 stop after start
03-24 21:19:36.712  3258  3314 I jxcore-log: 
03-24 21:19:36.716  3258  3314 I jxcore-log: # teardown
03-24 21:19:36.716  3258  3314 I jxcore-log: 
,03-24 21:19:40.186  3258  3314 I jxcore-log: # setup
03-24 21:19:40.186  3258  3314 I jxcore-log: 
,03-24 21:19:40.336  3258  3314 I jxcore-log: # 114. One peer and empty DB
03-24 21:19:40.336  3258  3314 I jxcore-log: 
,03-24 21:19:42.011  3258  3314 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-24 21:19:42.011  3258  3314 I jxcore-log: 
,03-24 21:19:42.013  3258  3314 I jxcore-log: ok 364 verify failed
03-24 21:19:42.013  3258  3314 I jxcore-log: 
03-24 21:19:42.013  3258  3314 I jxcore-log: ok 365 constructor called once
03-24 21:19:42.013  3258  3314 I jxcore-log: 
,03-24 21:19:42.015  3258  3314 I jxcore-log: ok 366 constructor called with right args
03-24 21:19:42.015  3258  3314 I jxcore-log: 
,03-24 21:19:42.016  3258  3314 I jxcore-log: ok 367 match start arg
03-24 21:19:42.016  3258  3314 I jxcore-log: 
03-24 21:19:42.016  3258  3314 I jxcore-log: ok 368 start called once
03-24 21:19:42.016  3258  3314 I jxcore-log: 
,03-24 21:19:42.017  3258  3314 I jxcore-log: ok 369 stop called once
03-24 21:19:42.017  3258  3314 I jxcore-log: 
03-24 21:19:42.017  3258  3314 I jxcore-log: ok 370 stop after start
03-24 21:19:42.017  3258  3314 I jxcore-log: 
,03-24 21:19:42.023  3258  3314 I jxcore-log: # teardown
03-24 21:19:42.023  3258  3314 I jxcore-log: 
,03-24 21:19:42.145  3258  3314 I jxcore-log: # setup
03-24 21:19:42.145  3258  3314 I jxcore-log: 
,03-24 21:19:42.745  3258  3314 I jxcore-log: # 115. One peer with _Local set behind current seq
03-24 21:19:42.745  3258  3314 I jxcore-log: 
,03-24 21:19:43.011  3258  3314 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-24 21:19:43.011  3258  3314 I jxcore-log: 
03-24 21:19:43.012  3258  3314 I jxcore-log: ok 371 verify failed
03-24 21:19:43.012  3258  3314 I jxcore-log: 
,03-24 21:19:43.013  3258  3314 I jxcore-log: ok 372 constructor called once
03-24 21:19:43.013  3258  3314 I jxcore-log: 
03-24 21:19:43.014  3258  3314 I jxcore-log: ok 373 constructor called with right args
03-24 21:19:43.014  3258  3314 I jxcore-log: 
03-24 21:19:43.015  3258  3314 I jxcore-log: ok 374 match start arg
03-24 21:19:43.015  3258  3314 I jxcore-log: 
03-24 21:19:43.015  3258  3314 I jxcore-log: ok 375 start called once
03-24 21:19:43.015  3258  3314 I jxcore-log: 
03-24 21:19:43.015  3258  3314 I jxcore-log: ok 376 stop called once
03-24 21:19:43.015  3258  3314 I jxcore-log: 
03-24 21:19:43.015  3258  3314 I jxcore-log: ok 377 stop after start
03-24 21:19:43.015  3258  3314 I jxcore-log: 
,03-24 21:19:43.021  3258  3314 I jxcore-log: # teardown
03-24 21:19:43.021  3258  3314 I jxcore-log: 
,03-24 21:19:43.167  3258  3314 I jxcore-log: # setup
03-24 21:19:43.167  3258  3314 I jxcore-log: 
,03-24 21:19:43.275  3258  3314 I jxcore-log: # 116. One peer with _Local set equal to current seq
03-24 21:19:43.275  3258  3314 I jxcore-log: 
,03-24 21:19:43.626  3258  3314 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-24 21:19:43.626  3258  3314 I jxcore-log: 
,03-24 21:19:43.627  3258  3314 I jxcore-log: ok 378 verify failed
03-24 21:19:43.627  3258  3314 I jxcore-log: 
,03-24 21:19:43.628  3258  3314 I jxcore-log: ok 379 constructor called once
03-24 21:19:43.628  3258  3314 I jxcore-log: 
03-24 21:19:43.629  3258  3314 I jxcore-log: ok 380 constructor called with right args
03-24 21:19:43.629  3258  3314 I jxcore-log: 
03-24 21:19:43.630  3258  3314 I jxcore-log: ok 381 match start arg,
03-24 21:19:43.630  3258  3314 I jxcore-log: 
03-24 21:19:43.630  3258  3314 I jxcore-log: ok 382 start called once
03-24 21:19:43.630  3258  3314 I jxcore-log: 
03-24 21:19:43.631  3258  3314 I jxcore-log: ok 383 stop called once,
03-24 21:19:43.631  3258  3314 I jxcore-log: 
03-24 21:19:43.631  3258  3314 I jxcore-log: ok 384 stop after start
03-24 21:19:43.631  3258  3314 I jxcore-log: 
,03-24 21:19:43.638  3258  3314 I jxcore-log: # teardown
03-24 21:19:43.638  3258  3314 I jxcore-log: ,
,03-24 21:19:43.861  3258  3314 I jxcore-log: # setup
03-24 21:19:43.861  3258  3314 I jxcore-log: 
,03-24 21:19:47.288  3258  3314 I jxcore-log: # 117. One peer with _Local set ahead of current seq (and no this should not happen)
03-24 21:19:47.288  3258  3314 I jxcore-log: 
,03-24 21:19:47.734  3258  3314 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-24 21:19:47.734  3258  3314 I jxcore-log: 
,03-24 21:19:47.736  3258  3314 I jxcore-log: ok 385 verify failed
03-24 21:19:47.736  3258  3314 I jxcore-log: 
03-24 21:19:47.736  3258  3314 I jxcore-log: ok 386 constructor called once
03-24 21:19:47.736  3258  3314 I jxcore-log: 
,03-24 21:19:47.737  3258  3314 I jxcore-log: ok 387 constructor called with right args
03-24 21:19:47.737  3258  3314 I jxcore-log: 
03-24 21:19:47.738  3258  3314 I jxcore-log: ok 388 match start arg
03-24 21:19:47.738  3258  3314 I jxcore-log: 
,03-24 21:19:47.738  3258  3314 I jxcore-log: ok 389 start called once
03-24 21:19:47.738  3258  3314 I jxcore-log: 
03-24 21:19:47.738  3258  3314 I jxcore-log: ok 390 stop called once
03-24 21:19:47.738  3258  3314 I jxcore-log: 
03-24 21:19:47.739  3258  3314 I jxcore-log: ok 391 stop after start
03-24 21:19:47.739  3258  3314 I jxcore-log: 
03-24 21:19:47.745  3258  3314 I jxcore-log: # teardown
03-24 21:19:47.745  3258  3314 I jxcore-log: 
,03-24 21:19:49.435  3258  3314 I jxcore-log: # setup
03-24 21:19:49.435  3258  3314 I jxcore-log: 
,03-24 21:19:49.643  3258  3314 I jxcore-log: # 118. Three peers, one not in DB, one behind and one ahead
03-24 21:19:49.643  3258  3314 I jxcore-log: 
,03-24 21:19:50.327  3258  3314 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-24 21:19:50.327  3258  3314 I jxcore-log: 
,03-24 21:19:50.329  3258  3314 I jxcore-log: ok 392 verify failed
03-24 21:19:50.329  3258  3314 I jxcore-log: 
,03-24 21:19:50.330  3258  3314 I jxcore-log: ok 393 constructor called once
03-24 21:19:50.330  3258  3314 I jxcore-log: 
,03-24 21:19:50.330  3258  3314 I jxcore-log: ok 394 constructor called with right args
03-24 21:19:50.330  3258  3314 I jxcore-log: 
03-24 21:19:50.331  3258  3314 I jxcore-log: ok 395 match start arg
03-24 21:19:50.331  3258  3314 I jxcore-log: 
03-24 21:19:50.331  3258  3314 I jxcore-log: ok 396 start called once
03-24 21:19:50.331  3258  3314 I jxcore-log: 
03-24 21:19:50.331  3258  3314 I jxcore-log: ok 397 stop called once
03-24 21:19:50.331  3258  3314 I jxcore-log: 
,03-24 21:19:50.331  3258  3314 I jxcore-log: ok 398 stop after start
03-24 21:19:50.331  3258  3314 I jxcore-log: 
,03-24 21:19:50.337  3258  3314 I jxcore-log: # teardown
03-24 21:19:50.337  3258  3314 I jxcore-log: 
,03-24 21:19:51.806  3258  3314 I jxcore-log: # setup
,03-24 21:19:51.806  3258  3314 I jxcore-log: 
,03-24 21:19:51.986  3258  3314 I jxcore-log: # 119. More than maximum peers, make sure we only send maximum allowed
,03-24 21:19:51.986  3258  3314 I jxcore-log: 
,03-24 21:19:52.822  3258  3314 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-24 21:19:52.822  3258  3314 I jxcore-log: 
,03-24 21:19:52.824  3258  3314 I jxcore-log: ok 399 verify failed
03-24 21:19:52.824  3258  3314 I jxcore-log: 
,03-24 21:19:52.825  3258  3314 I jxcore-log: ok 400 constructor called once
03-24 21:19:52.825  3258  3314 I jxcore-log: 
,03-24 21:19:52.825  3258  3314 I jxcore-log: ok 401 constructor called with right args
03-24 21:19:52.825  3258  3314 I jxcore-log: 
03-24 21:19:52.826  3258  3314 I jxcore-log: ok 402 match start arg
03-24 21:19:52.826  3258  3314 I jxcore-log: 
03-24 21:19:52.826  3258  3314 I jxcore-log: ok 403 start called once
03-24 21:19:52.826  3258  3314 I jxcore-log: 
,03-24 21:19:52.826  3258  3314 I jxcore-log: ok 404 stop called once
03-24 21:19:52.826  3258  3314 I jxcore-log: 
03-24 21:19:52.826  3258  3314 I jxcore-log: ok 405 stop after start
03-24 21:19:52.826  3258  3314 I jxcore-log: 
03-24 21:19:52.831  3258  3314 I jxcore-log: # teardown
03-24 21:19:52.831  3258  3314 I jxcore-log: 
,03-24 21:19:52.997  3258  3314 I jxcore-log: # setup,
03-24 21:19:52.997  3258  3314 I jxcore-log: 
,03-24 21:19:53.114  3258  3314 I jxcore-log: # 120. two peers with empty DB, update the doc,
03-24 21:19:53.114  3258  3314 I jxcore-log: 
,03-24 21:19:53.441  3258  3314 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"},
03-24 21:19:53.441  3258  3314 I jxcore-log: 
,03-24 21:19:53.479  3258  3314 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"},
03-24 21:19:53.479  3258  3314 I jxcore-log: 
03-24 21:19:53.480  3258  3314 I jxcore-log: ok 406 verify failed
03-24 21:19:53.480  3258  3314 I jxcore-log: 
,03-24 21:19:53.481  3258  3314 I jxcore-log: ok 407 constructor called once
03-24 21:19:53.481  3258  3314 I jxcore-log: 
03-24 21:19:53.481  3258  3314 I jxcore-log: ok 408 constructor called with right args
03-24 21:19:53.481  3258  3314 I jxcore-log: 
,03-24 21:19:53.482  3258  3314 I jxcore-log: ok 409 last start before stop
03-24 21:19:53.482  3258  3314 I jxcore-log: 
03-24 21:19:53.482  3258  3314 I jxcore-log: ok 410 empty first start
03-24 21:19:53.482  3258  3314 I jxcore-log: 
03-24 21:19:53.483  3258  3314 I jxcore-log: ok 411 full second start
03-24 21:19:53.483  3258  3314 I jxcore-log: 
03-24 21:19:53.484  3258  3314 I jxcore-log: ok 412 only 2 timers
03-24 21:19:53.484  3258  3314 I jxcore-log: 
,03-24 21:19:53.488  3258  3314 I jxcore-log: # teardown
03-24 21:19:53.488  3258  3314 I jxcore-log: 
,03-24 21:19:54.625  3258  3314 I jxcore-log: # setup
03-24 21:19:54.625  3258  3314 I jxcore-log: 
,03-24 21:19:54.796  3258  3314 I jxcore-log: # 121. add doc and make sure tokens refresh when they expire
03-24 21:19:54.796  3258  3314 I jxcore-log: 
,03-24 21:19:55.318  3258  3314 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-24 21:19:55.318  3258  3314 I jxcore-log: 
,03-24 21:19:55.430  3258  3314 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-24 21:19:55.430  3258  3314 I jxcore-log: 
,03-24 21:19:55.528  3258  3314 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-24 21:19:55.528  3258  3314 I jxcore-log: 
,03-24 21:19:55.530  3258  3314 I jxcore-log: ok 413 verify failed
03-24 21:19:55.530  3258  3314 I jxcore-log: 
,03-24 21:19:55.530  3258  3314 I jxcore-log: ok 414 constructor called once
03-24 21:19:55.530  3258  3314 I jxcore-log: 
03-24 21:19:55.530  3258  3314 I jxcore-log: ok 415 constructor called with right args
03-24 21:19:55.530  3258  3314 I jxcore-log: 
03-24 21:19:55.531  3258  3314 I jxcore-log: ok 416 start before stop
03-24 21:19:55.531  3258  3314 I jxcore-log: 
,03-24 21:19:55.531  3258  3314 I jxcore-log: ok 417 We got at least 3 calls to start
03-24 21:19:55.531  3258  3314 I jxcore-log: 
03-24 21:19:55.531  3258  3314 I jxcore-log: ok 418 at least 3
03-24 21:19:55.531  3258  3314 I jxcore-log: 
03-24 21:19:55.531  3258  3314 I jxcore-log: ok 419 default 1
03-24 21:19:55.531  3258  3314 I jxcore-log: 
,03-24 21:19:55.532  3258  3314 I jxcore-log: ok 420 1 run
03-24 21:19:55.532  3258  3314 I jxcore-log: 
03-24 21:19:55.532  3258  3314 I jxcore-log: ok 421 default 2
03-24 21:19:55.532  3258  3314 I jxcore-log: 
03-24 21:19:55.532  3258  3314 I jxcore-log: ok 422 2 run
03-24 21:19:55.532  3258  3314 I jxcore-log: 
03-24 21:19:55.533  3258  3314 I jxcore-log: ok 423 default 3
03-24 21:19:55.533  3258  3314 I jxcore-log: 
,03-24 21:19:55.537  3258  3314 I jxcore-log: # teardown
03-24 21:19:55.537  3258  3314 I jxcore-log: 
,03-24 21:19:55.767  3258  3314 I jxcore-log: # setup
03-24 21:19:55.767  3258  3314 I jxcore-log: 
,03-24 21:19:55.897  3258  3314 I jxcore-log: # 122. start and stop and start and stop
03-24 21:19:55.897  3258  3314 I jxcore-log: 
,03-24 21:19:56.171  3258  3314 I jxcore-log: ok 424 start out null
03-24 21:19:56.171  3258  3314 I jxcore-log: 
,03-24 21:19:56.191  3258  3314 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-24 21:19:56.191  3258  3314 I jxcore-log: 
,03-24 21:19:56.192  3258  3314 I jxcore-log: ok 425 back to null
03-24 21:19:56.192  3258  3314 I jxcore-log: 
,03-24 21:19:56.214  3258  3314 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-24 21:19:56.214  3258  3314 I jxcore-log: 
,03-24 21:19:56.215  3258  3314 I jxcore-log: ok 426 still null
03-24 21:19:56.215  3258  3314 I jxcore-log: 
03-24 21:19:56.216  3258  3314 I jxcore-log: ok 427 verify failed
03-24 21:19:56.216  3258  3314 I jxcore-log: 
,03-24 21:19:56.216  3258  3314 I jxcore-log: ok 428 constructor called once
03-24 21:19:56.216  3258  3314 I jxcore-log: 
,03-24 21:19:56.217  3258  3314 I jxcore-log: ok 429 constructor called with right args
03-24 21:19:56.217  3258  3314 I jxcore-log: 
03-24 21:19:56.217  3258  3314 I jxcore-log: ok 430 first start before first stop
03-24 21:19:56.217  3258  3314 I jxcore-log: 
03-24 21:19:56.217  3258  3314 I jxcore-log: ok 431 first stop before second start
03-24 21:19:56.217  3258  3314 I jxcore-log: 
,03-24 21:19:56.218  3258  3314 I jxcore-log: ok 432 second start before second stop
03-24 21:19:56.218  3258  3314 I jxcore-log: 
,03-24 21:19:56.227  3258  3314 I jxcore-log: # teardown
03-24 21:19:56.227  3258  3314 I jxcore-log: 
,03-24 21:19:56.632  3258  3314 I jxcore-log: # setup
03-24 21:19:56.632  3258  3314 I jxcore-log: 
,03-24 21:19:56.754  3258  3314 I jxcore-log: # 123. two identical starts in a row
03-24 21:19:56.754  3258  3314 I jxcore-log: 
,03-24 21:19:57.558  3258  3314 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-24 21:19:57.558  3258  3314 I jxcore-log: 
,03-24 21:19:57.560  3258  3314 I jxcore-log: ok 433 verify failed
03-24 21:19:57.560  3258  3314 I jxcore-log: 
,03-24 21:19:57.561  3258  3314 I jxcore-log: ok 434 constructor called once
03-24 21:19:57.561  3258  3314 I jxcore-log: 
,03-24 21:19:57.562  3258  3314 I jxcore-log: ok 435 constructor called with right args
03-24 21:19:57.562  3258  3314 I jxcore-log: 
,03-24 21:19:57.562  3258  3314 I jxcore-log: ok 436 (unnamed assert)
03-24 21:19:57.562  3258  3314 I jxcore-log: 
,03-24 21:19:57.568  3258  3314 I jxcore-log: # teardown
03-24 21:19:57.568  3258  3314 I jxcore-log: 
,03-24 21:19:57.691  3258  3314 I jxcore-log: # setup
03-24 21:19:57.691  3258  3314 I jxcore-log: 
,03-24 21:19:58.515  3258  3314 I jxcore-log: # 124. two different starts in a row
03-24 21:19:58.515  3258  3314 I jxcore-log: 
,03-24 21:19:58.797  3258  3314 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-24 21:19:58.797  3258  3314 I jxcore-log: 
,03-24 21:19:58.802  3258  3314 I jxcore-log: ok 437 verify failed
03-24 21:19:58.802  3258  3314 I jxcore-log: 
03-24 21:19:58.802  3258  3314 I jxcore-log: ok 438 constructor called once
03-24 21:19:58.802  3258  3314 I jxcore-log: 
03-24 21:19:58.803  3258  3314 I jxcore-log: ok 439 constructor called with right args
03-24 21:19:58.803  3258  3314 I jxcore-log: 
03-24 21:19:58.804  3258  3314 I jxcore-log: ok 440 (unnamed assert)
03-24 21:19:58.804  3258  3314 I jxcore-log: 
,03-24 21:19:58.804  3258  3314 I jxcore-log: ok 441 (unnamed assert)
03-24 21:19:58.804  3258  3314 I jxcore-log: 
,03-24 21:19:58.808  3258  3314 I jxcore-log: # teardown
03-24 21:19:58.808  3258  3314 I jxcore-log: 
,03-24 21:19:59.345  3258  3314 I jxcore-log: # setup
03-24 21:19:59.345  3258  3314 I jxcore-log: 
,03-24 21:19:59.492  3258  3314 I jxcore-log: # 125. two stops and a start and two stops
03-24 21:19:59.492  3258  3314 I jxcore-log: 
,03-24 21:19:59.795  3258  3314 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-24 21:19:59.795  3258  3314 I jxcore-log: 
03-24 21:19:59.797  3258  3314 I jxcore-log: ok 442 verify failed
03-24 21:19:59.797  3258  3314 I jxcore-log: 
03-24 21:19:59.798  3258  3314 I jxcore-log: ok 443 constructor called once
03-24 21:19:59.798  3258  3314 I jxcore-log: 
03-24 21:19:59.798  3258  3314 I jxcore-log: ok 444 constructor called with right args
03-24 21:19:59.798  3258  3314 I jxcore-log: 
03-24 21:19:59.799  3258  3314 I jxcore-log: ok 445 start before stop
03-24 21:19:59.799  3258  3314 I jxcore-log: 
03-24 21:19:59.803  3258  3314 I jxcore-log: # teardown
03-24 21:19:59.803  3258  3314 I jxcore-log: 
,03-24 21:19:59.835   820  1144 D WifiService: acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@56a6530}
,03-24 21:19:59.838   820  1021 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=1.25 rxSuccessRate=0.50 targetRoamBSSID=any RSSI=-127
,03-24 21:19:59.849  3364  3850 V GoogleAuthProtoRequest: [338] a.<init>: mAccountName set to: thalitester@gmail.com
,03-24 21:19:59.909  1266  3820 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,03-24 21:19:59.910  1266  3820 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 21:19:59.910  1266  3820 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 21:19:59.910  1266  3820 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 21:19:59.913  1266  3820 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 21:19:59.925  3364  3850 W ExperimentUpdateService: [338] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,03-24 21:19:59.925  3364  3850 W ExperimentUpdateService: [338] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-24 21:19:59.925  3364  3850 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-24 21:19:59.925  3364  3850 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-24 21:19:59.925  3364  3850 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-24 21:19:59.925  3364  3850 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-24 21:19:59.925  3364  3850 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-24 21:19:59.925  3364  3850 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-24 21:19:59.925  3364  3850 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-24 21:19:59.925  3364  3850 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-24 21:19:59.925  3364  3850 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-24 21:19:59.925  3364  3850 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-24 21:19:59.979  1266  1266 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 21:20:00.010  1266  3820 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/ads_measurement
,03-24 21:20:00.010  1266  3820 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/ads_measurement without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 21:20:00.010  1266  3820 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 21:20:00.010  1266  3820 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 21:20:00.016  1266  3820 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 21:20:00.032  1801  3852 E Ads     : [JAMS] Failed to get OAuth token: com.google.android.gms.auth.ad: BadAuthentication
,03-24 21:20:00.132  3258  3314 I jxcore-log: # setup
03-24 21:20:00.132  3258  3314 I jxcore-log: 
,03-24 21:20:00.274  3258  3314 I jxcore-log: # 126. we properly enqueue requests so no then needed
03-24 21:20:00.274  3258  3314 I jxcore-log: 
,03-24 21:20:00.627  3258  3314 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-24 21:20:00.627  3258  3314 I jxcore-log: 
,03-24 21:20:00.629  3258  3314 I jxcore-log: ok 446 verify failed
03-24 21:20:00.629  3258  3314 I jxcore-log: 
03-24 21:20:00.630  3258  3314 I jxcore-log: ok 447 constructor called once
03-24 21:20:00.630  3258  3314 I jxcore-log: 
,03-24 21:20:00.631  3258  3314 I jxcore-log: ok 448 constructor called with right args
03-24 21:20:00.631  3258  3314 I jxcore-log: 
,03-24 21:20:00.631  3258  3314 I jxcore-log: ok 449 start before stop
03-24 21:20:00.631  3258  3314 I jxcore-log: 
,03-24 21:20:00.637  3258  3314 I jxcore-log: # teardown
,03-24 21:20:00.637  3258  3314 I jxcore-log: 
,03-24 21:20:01.086  3258  3314 I jxcore-log: # setup
03-24 21:20:01.086  3258  3314 I jxcore-log: 
,03-24 21:20:01.541   820   835 D WifiService: releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@56a6530}
,03-24 21:20:01.556   820  1333 D WifiService: acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@30318451}
,03-24 21:20:01.588   820  1256 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::injectLocation(GpsExtLocation):857]: error! inject position failed
,03-24 21:20:01.652  3258  3314 I jxcore-log: # 127. test calculateSeqPointKeyId
03-24 21:20:01.652  3258  3314 I jxcore-log: 
,03-24 21:20:01.667   870   870 I kickstart: STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
03-24 21:20:01.668   870   870 I kickstart: STATUS: Wrote to /sys/power/wake_lock
,03-24 21:20:01.708   870   870 E kickstart: ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2
03-24 21:20:01.708   870   870 I kickstart: STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2' for writing
,03-24 21:20:02.080  3258  3314 I jxcore-log: ok 450 should be equal
03-24 21:20:02.080  3258  3314 I jxcore-log: 
03-24 21:20:02.081  3258  3314 I jxcore-log: ok 451 should be equal
03-24 21:20:02.081  3258  3314 I jxcore-log: 
,03-24 21:20:02.084  3258  3314 I jxcore-log: # teardown
03-24 21:20:02.084  3258  3314 I jxcore-log: 
,03-24 21:20:02.296  3258  3314 I jxcore-log: # setup
03-24 21:20:02.296  3258  3314 I jxcore-log: 
,03-24 21:20:02.422  3258  3314 I jxcore-log: # 128. can create servers manager
03-24 21:20:02.422  3258  3314 I jxcore-log: 
,03-24 21:20:02.546  3258  3314 I jxcore-log: ok 452 serversManager must not be null
03-24 21:20:02.546  3258  3314 I jxcore-log: 
,03-24 21:20:02.548  3258  3314 I jxcore-log: ok 453 serversManager must be an object
03-24 21:20:02.548  3258  3314 I jxcore-log: 
,03-24 21:20:02.555  3258  3314 I jxcore-log: # teardown
03-24 21:20:02.555  3258  3314 I jxcore-log: 
,03-24 21:20:02.690  3258  3314 I jxcore-log: # setup
03-24 21:20:02.690  3258  3314 I jxcore-log: 
,03-24 21:20:02.698   870   870 I kickstart: STATUS: Received file 'm9kefs2'
03-24 21:20:02.699   870   870 I kickstart: STATUS: 950272 bytes transferred in 0.989781 seconds
03-24 21:20:02.699   870   870 I kickstart: STATUS: Successfully downloaded files from target 
03-24 21:20:02.699   870   870 I kickstart: STATUS: Wrote to /sys/power/wake_unlock
,03-24 21:20:02.702   870   870 I kickstart: STATUS: Sahara protocol completed
,03-24 21:20:02.804  3258  3314 I jxcore-log: # 129. calling stop without start causes error
03-24 21:20:02.804  3258  3314 I jxcore-log: 
,03-24 21:20:02.945  3258  3314 I jxcore-log: ok 454 We need to call start first
,03-24 21:20:02.945  3258  3314 I jxcore-log: 
,03-24 21:20:02.948  3258  3314 I jxcore-log: # teardown
03-24 21:20:02.948  3258  3314 I jxcore-log: 
,03-24 21:20:03.077  3258  3314 I jxcore-log: # setup
03-24 21:20:03.077  3258  3314 I jxcore-log: 
,03-24 21:20:03.238  3258  3314 I jxcore-log: # 130. can start/stop servers manager
03-24 21:20:03.238  3258  3314 I jxcore-log: 
,03-24 21:20:03.420  3258  3314 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 21:20:03.420  3258  3314 I jxcore-log: 
,03-24 21:20:03.430  3258  3314 I jxcore-log: DEBUG createNativeListener: listening 58328
03-24 21:20:03.430  3258  3314 I jxcore-log: 
,03-24 21:20:03.434  3258  3314 I jxcore-log: ok 455 port must be in range
03-24 21:20:03.434  3258  3314 I jxcore-log: 
,03-24 21:20:03.436  3258  3314 I jxcore-log: # teardown
03-24 21:20:03.436  3258  3314 I jxcore-log: 
,03-24 21:20:03.618  3258  3314 I jxcore-log: # setup
03-24 21:20:03.618  3258  3314 I jxcore-log: 
,03-24 21:20:03.743  3258  3314 I jxcore-log: # 131. starting twice resolves with listening port
03-24 21:20:03.743  3258  3314 I jxcore-log: 
,03-24 21:20:03.997  3258  3314 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 21:20:03.997  3258  3314 I jxcore-log: 
,03-24 21:20:04.009  3258  3314 I jxcore-log: DEBUG createNativeListener: listening 54336
03-24 21:20:04.009  3258  3314 I jxcore-log: 
,03-24 21:20:04.015  3258  3314 I jxcore-log: ok 456 second start should return same port
03-24 21:20:04.015  3258  3314 I jxcore-log: 
,03-24 21:20:04.018  3258  3314 I jxcore-log: # teardown
03-24 21:20:04.018  3258  3314 I jxcore-log: 
,03-24 21:20:04.166  3258  3314 I jxcore-log: # setup
03-24 21:20:04.166  3258  3314 I jxcore-log: 
,03-24 21:20:04.297  3258  3314 I jxcore-log: # 132. terminateIncomingConnection will terminate a connection
03-24 21:20:04.297  3258  3314 I jxcore-log: 
,03-24 21:20:04.566  3258  3314 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 21:20:04.566  3258  3314 I jxcore-log: 
03-24 21:20:04.568  3258  3314 I jxcore-log: DEBUG createNativeListener: listening 36857
03-24 21:20:04.568  3258  3314 I jxcore-log: 
,03-24 21:20:04.575  3258  3314 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 21:20:04.575  3258  3314 I jxcore-log: 
,03-24 21:20:04.577  3258  3314 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 21:20:04.577  3258  3314 I jxcore-log: 
03-24 21:20:04.578  3258  3314 I jxcore-log: DEBUG createNativeListener: new mux
03-24 21:20:04.578  3258  3314 I jxcore-log: 
,03-24 21:20:04.581  3258  3314 I jxcore-log: ok 457 we should be connected
03-24 21:20:04.581  3258  3314 I jxcore-log: 
,03-24 21:20:04.585  3258  3314 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 21:20:04.585  3258  3314 I jxcore-log: 
,03-24 21:20:04.586  3258  3314 I jxcore-log: ok 458 now we are disconnected
03-24 21:20:04.586  3258  3314 I jxcore-log: 
,03-24 21:20:04.598  3258  3314 I jxcore-log: # teardown
03-24 21:20:04.598  3258  3314 I jxcore-log: 
,03-24 21:20:04.760  3258  3314 I jxcore-log: # setup
03-24 21:20:04.760  3258  3314 I jxcore-log: 
,03-24 21:20:04.974  3258  3314 I jxcore-log: # 133. terminate an Outgoing connection will terminate the server
03-24 21:20:04.974  3258  3314 I jxcore-log: 
,03-24 21:20:07.935  3258  3314 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 21:20:07.935  3258  3314 I jxcore-log: 
03-24 21:20:07.944  3258  3314 I jxcore-log: DEBUG createNativeListener: listening 56001
03-24 21:20:07.944  3258  3314 I jxcore-log: 
,03-24 21:20:07.947  3258  3314 I jxcore-log: # teardown
03-24 21:20:07.947  3258  3314 I jxcore-log: 
,03-24 21:20:08.089  3258  3314 I jxcore-log: # setup
03-24 21:20:08.089  3258  3314 I jxcore-log: 
,03-24 21:20:08.309  3258  3314 I jxcore-log: # 134. terminate an Outgoing connection with wrong arguments is not harmful
03-24 21:20:08.309  3258  3314 I jxcore-log: 
,03-24 21:20:09.575  3258  3314 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 21:20:09.575  3258  3314 I jxcore-log: 
03-24 21:20:09.578  3258  3314 I jxcore-log: DEBUG createNativeListener: listening 42646
03-24 21:20:09.578  3258  3314 I jxcore-log: 
03-24 21:20:09.580  3258  3314 I jxcore-log: # teardown
03-24 21:20:09.580  3258  3314 I jxcore-log: 
,03-24 21:20:09.717  3258  3314 I jxcore-log: # setup
03-24 21:20:09.717  3258  3314 I jxcore-log: 
,03-24 21:20:09.855  3258  3314 I jxcore-log: ok 459 should be in started state
03-24 21:20:09.855  3258  3314 I jxcore-log: 
03-24 21:20:09.857  3258  3314 I jxcore-log: # 135. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted
03-24 21:20:09.857  3258  3314 I jxcore-log: 
,03-24 21:20:10.723  3258  3314 I jxcore-log: ok 460 peer identifier should match
03-24 21:20:10.723  3258  3314 I jxcore-log: 
03-24 21:20:10.724  3258  3314 I jxcore-log: ok 461 host address should match
03-24 21:20:10.724  3258  3314 I jxcore-log: 
,03-24 21:20:10.724  3258  3314 I jxcore-log: ok 462 port should match
03-24 21:20:10.724  3258  3314 I jxcore-log: 
,03-24 21:20:10.730  3258  3314 I jxcore-log: ok 463 host address should be null
03-24 21:20:10.730  3258  3314 I jxcore-log: 
,03-24 21:20:10.730  3258  3314 I jxcore-log: ok 464 port should should be null
03-24 21:20:10.730  3258  3314 I jxcore-log: 
,03-24 21:20:10.736  3258  3314 I jxcore-log: # teardown
03-24 21:20:10.736  3258  3314 I jxcore-log: 
,03-24 21:20:11.201  3258  3314 I jxcore-log: ok 465 should not be in started state
03-24 21:20:11.201  3258  3314 I jxcore-log: 
,03-24 21:20:11.206  3258  3314 I jxcore-log: # setup
03-24 21:20:11.206  3258  3314 I jxcore-log: 
,03-24 21:20:11.356  3258  3314 I jxcore-log: ok 466 should be in started state
03-24 21:20:11.356  3258  3314 I jxcore-log: 
,03-24 21:20:11.358  3258  3314 I jxcore-log: # 136. #startUpdateAdvertisingAndListening should use different USN after every invocation
03-24 21:20:11.358  3258  3314 I jxcore-log: 
,03-24 21:20:11.520  3258  3314 I jxcore-log: ok 467 USN should have changed from the first one
03-24 21:20:11.520  3258  3314 I jxcore-log: 
,03-24 21:20:11.528  3258  3314 I jxcore-log: ok 468 when receiving the second byebye, the first USN should be already set
03-24 21:20:11.528  3258  3314 I jxcore-log: 
,03-24 21:20:11.535  3258  3314 I jxcore-log: # teardown
03-24 21:20:11.535  3258  3314 I jxcore-log: 
,03-24 21:20:11.657  3258  3314 I jxcore-log: ok 469 should not be in started state
03-24 21:20:11.657  3258  3314 I jxcore-log: 
,03-24 21:20:11.659  3258  3314 I jxcore-log: # setup
03-24 21:20:11.659  3258  3314 I jxcore-log: 
,03-24 21:20:11.762  3258  3314 I jxcore-log: ok 470 should be in started state
03-24 21:20:11.762  3258  3314 I jxcore-log: 
,03-24 21:20:11.769  3258  3314 I jxcore-log: # 137. messages with invalid location or USN should be ignored
03-24 21:20:11.769  3258  3314 I jxcore-log: 
,03-24 21:20:11.904  3258  3314 I jxcore-log: WARN thaliWifiInfrastructure: Failed to parse a valid port number from location: http://foo.bar:90000
03-24 21:20:11.904  3258  3314 I jxcore-log: 
,03-24 21:20:11.906  3258  3314 I jxcore-log: ok 471 should not have emitted with invalid port
03-24 21:20:11.906  3258  3314 I jxcore-log: 
,03-24 21:20:11.914  3258  3314 I jxcore-log: WARN thaliWifiInfrastructure: Received an invalid USN value: 
03-24 21:20:11.914  3258  3314 I jxcore-log: 
,03-24 21:20:11.915  3258  3314 I jxcore-log: ok 472 should not have emitted with invalid USN
03-24 21:20:11.915  3258  3314 I jxcore-log: 
,03-24 21:20:11.917  3258  3314 I jxcore-log: # teardown
03-24 21:20:11.917  3258  3314 I jxcore-log: 
,03-24 21:20:12.035  3258  3314 I jxcore-log: ok 473 should not be in started state
03-24 21:20:12.035  3258  3314 I jxcore-log: 
,03-24 21:20:12.037  3258  3314 I jxcore-log: # setup
03-24 21:20:12.037  3258  3314 I jxcore-log: 
,03-24 21:20:12.240  3258  3314 I jxcore-log: ok 474 should be in started state
03-24 21:20:12.240  3258  3314 I jxcore-log: 
,03-24 21:20:12.243  3258  3314 I jxcore-log: # 138. verify that Thali-specific messages are filtered correctly
03-24 21:20:12.243  3258  3314 I jxcore-log: 
,03-24 21:20:12.347  3258  3314 I jxcore-log: ok 475 irrelevant messages should be ignored
03-24 21:20:12.347  3258  3314 I jxcore-log: 
,03-24 21:20:12.354  3258  3314 I jxcore-log: ok 476 relevant messages should not be ignored
03-24 21:20:12.354  3258  3314 I jxcore-log: 
,03-24 21:20:12.355  3258  3314 I jxcore-log: ok 477 messages from this device should be ignored
03-24 21:20:12.355  3258  3314 I jxcore-log: 
,03-24 21:20:12.359  3258  3314 I jxcore-log: # teardown
03-24 21:20:12.359  3258  3314 I jxcore-log: 
,03-24 21:20:12.470  3258  3314 I jxcore-log: ok 478 should not be in started state
03-24 21:20:12.470  3258  3314 I jxcore-log: 
,03-24 21:20:12.476  3258  3314 I jxcore-log: # setup
03-24 21:20:12.476  3258  3314 I jxcore-log: 
,03-24 21:20:12.685  3258  3314 I jxcore-log: ok 479 should be in started state
03-24 21:20:12.685  3258  3314 I jxcore-log: 
,03-24 21:20:12.690  3258  3314 I jxcore-log: # 139. #startListeningForAdvertisements should fail if start not called
03-24 21:20:12.690  3258  3314 I jxcore-log: 
,03-24 21:20:12.814  3258  3314 I jxcore-log: ok 480 specific error should be returned
03-24 21:20:12.814  3258  3314 I jxcore-log: 
,03-24 21:20:12.819  3258  3314 I jxcore-log: # teardown
03-24 21:20:12.819  3258  3314 I jxcore-log: 
,03-24 21:20:12.955  3258  3314 I jxcore-log: ok 481 should not be in started state
03-24 21:20:12.955  3258  3314 I jxcore-log: 
03-24 21:20:12.957  3258  3314 I jxcore-log: # setup
03-24 21:20:12.957  3258  3314 I jxcore-log: 
,03-24 21:20:13.139  3258  3314 I jxcore-log: ok 482 should be in started state
03-24 21:20:13.139  3258  3314 I jxcore-log: 
,03-24 21:20:13.144  3258  3314 I jxcore-log: # 140. #startUpdateAdvertisingAndListening should fail if start not called
03-24 21:20:13.144  3258  3314 I jxcore-log: 
,03-24 21:20:13.332  3258  3314 I jxcore-log: ok 483 specific error should be returned
03-24 21:20:13.332  3258  3314 I jxcore-log: 
,03-24 21:20:13.336  3258  3314 I jxcore-log: # teardown
03-24 21:20:13.336  3258  3314 I jxcore-log: 
,03-24 21:20:13.615  3258  3314 I jxcore-log: ok 484 should not be in started state
03-24 21:20:13.615  3258  3314 I jxcore-log: 
,03-24 21:20:13.618  3258  3314 I jxcore-log: # setup
03-24 21:20:13.618  3258  3314 I jxcore-log: 
,03-24 21:20:13.755  3258  3314 I jxcore-log: ok 485 should be in started state
03-24 21:20:13.755  3258  3314 I jxcore-log: 
,03-24 21:20:13.757  3258  3314 I jxcore-log: # 141. #start should fail if called twice in a row
03-24 21:20:13.757  3258  3314 I jxcore-log: 
,03-24 21:20:13.874  3258  3314 I jxcore-log: ok 486 specific error should be received
03-24 21:20:13.874  3258  3314 I jxcore-log: 
,03-24 21:20:13.877  3258  3314 I jxcore-log: # teardown
03-24 21:20:13.877  3258  3314 I jxcore-log: 
,03-24 21:20:13.986  3258  3314 I jxcore-log: ok 487 should not be in started state
03-24 21:20:13.986  3258  3314 I jxcore-log: 
,03-24 21:20:13.994  3258  3314 I jxcore-log: # setup
03-24 21:20:13.994  3258  3314 I jxcore-log: 
,03-24 21:20:14.121  3258  3314 I jxcore-log: ok 488 should be in started state
03-24 21:20:14.121  3258  3314 I jxcore-log: 
,03-24 21:20:14.127  3258  3314 I jxcore-log: # 142. should not be started after stop is called
03-24 21:20:14.127  3258  3314 I jxcore-log: 
,03-24 21:20:14.295  3258  3314 I jxcore-log: ok 489 should not be started
03-24 21:20:14.295  3258  3314 I jxcore-log: 
,03-24 21:20:14.296  3258  3314 I jxcore-log: ok 490 should not be listening
03-24 21:20:14.296  3258  3314 I jxcore-log: 
03-24 21:20:14.296  3258  3314 I jxcore-log: ok 491 should not target listening
03-24 21:20:14.296  3258  3314 I jxcore-log: 
,03-24 21:20:14.296  3258  3314 I jxcore-log: ok 492 should not be advertising
03-24 21:20:14.296  3258  3314 I jxcore-log: 
03-24 21:20:14.297  3258  3314 I jxcore-log: ok 493 should not target advertising
03-24 21:20:14.297  3258  3314 I jxcore-log: 
03-24 21:20:14.299  3258  3314 I jxcore-log: # teardown
03-24 21:20:14.299  3258  3314 I jxcore-log: 
,03-24 21:20:14.420  3258  3314 I jxcore-log: ok 494 should not be in started state
03-24 21:20:14.420  3258  3314 I jxcore-log: 
,03-24 21:20:14.427  3258  3314 I jxcore-log: # setup
03-24 21:20:14.427  3258  3314 I jxcore-log: 
,03-24 21:20:14.524  3258  3314 I jxcore-log: ok 495 should be in started state
03-24 21:20:14.524  3258  3314 I jxcore-log: 
,03-24 21:20:14.531  3258  3314 I jxcore-log: # 143. #startUpdateAdvertisingAndListening should fail invalid router has been passed
03-24 21:20:14.531  3258  3314 I jxcore-log: 
,03-24 21:20:14.665  3258  3314 I jxcore-log: ERROR thaliWifiInfrastructure: Unable to use the given router: TypeError: Router.use() requires middleware function but got a string
03-24 21:20:14.665  3258  3314 I jxcore-log: 
,03-24 21:20:14.667  3258  3314 I jxcore-log: ok 496 specific error should be received
03-24 21:20:14.667  3258  3314 I jxcore-log: 
,03-24 21:20:14.670  3258  3314 I jxcore-log: # teardown
03-24 21:20:14.670  3258  3314 I jxcore-log: 
,03-24 21:20:14.806  3258  3314 I jxcore-log: ok 497 should not be in started state
03-24 21:20:14.806  3258  3314 I jxcore-log: 
,03-24 21:20:14.814  3258  3314 I jxcore-log: # setup
03-24 21:20:14.814  3258  3314 I jxcore-log: 
,03-24 21:20:14.986  3258  3314 I jxcore-log: ok 498 should be in started state
03-24 21:20:14.986  3258  3314 I jxcore-log: 
03-24 21:20:14.988  3258  3314 I jxcore-log: # 144. #startUpdateAdvertisingAndListening should fail if router server starting fails
03-24 21:20:14.988  3258  3314 I jxcore-log: 
,03-24 21:20:15.113  3258  3314 I jxcore-log: ERROR thaliWifiInfrastructure: Router server emitted an error: Error: listen EADDRINUSE
03-24 21:20:15.113  3258  3314 I jxcore-log: 
,03-24 21:20:15.115  3258  3314 I jxcore-log: ok 499 specific error expected
03-24 21:20:15.115  3258  3314 I jxcore-log: 
,03-24 21:20:15.118  3258  3314 I jxcore-log: # teardown
03-24 21:20:15.118  3258  3314 I jxcore-log: 
,03-24 21:20:15.226  3258  3314 I jxcore-log: ok 500 should not be in started state
03-24 21:20:15.226  3258  3314 I jxcore-log: 
,03-24 21:20:15.228  3258  3314 I jxcore-log: # setup
03-24 21:20:15.228  3258  3314 I jxcore-log: 
,03-24 21:20:15.354  3258  3314 I jxcore-log: ok 501 should be in started state
03-24 21:20:15.354  3258  3314 I jxcore-log: 
,03-24 21:20:15.362  3258  3314 I jxcore-log: # 145. #startUpdateAdvertisingAndListening should start hosting given router object
03-24 21:20:15.362  3258  3314 I jxcore-log: 
,03-24 21:20:15.551  3258  3314 I jxcore-log: ok 502 server should respond with code 200
03-24 21:20:15.551  3258  3314 I jxcore-log: 
,03-24 21:20:15.557  3258  3314 I jxcore-log: # teardown
03-24 21:20:15.557  3258  3314 I jxcore-log: 
,03-24 21:20:15.661  3258  3314 I jxcore-log: ok 503 should not be in started state
03-24 21:20:15.661  3258  3314 I jxcore-log: 
,03-24 21:20:15.668  3258  3314 I jxcore-log: # setup
03-24 21:20:15.668  3258  3314 I jxcore-log: 
,03-24 21:20:15.747  3258  3314 I jxcore-log: ok 504 should be in started state
03-24 21:20:15.747  3258  3314 I jxcore-log: 
,03-24 21:20:15.753  3258  3314 I jxcore-log: # 146. #stop can be called multiple times in a row
03-24 21:20:15.753  3258  3314 I jxcore-log: 
,03-24 21:20:15.916  3258  3314 I jxcore-log: ok 505 should be in stopped state
03-24 21:20:15.916  3258  3314 I jxcore-log: 
,03-24 21:20:15.917  3258  3314 I jxcore-log: ok 506 should still be in stopped state
03-24 21:20:15.917  3258  3314 I jxcore-log: 
,03-24 21:20:15.920  3258  3314 I jxcore-log: # teardown
03-24 21:20:15.920  3258  3314 I jxcore-log: 
,03-24 21:20:16.035  3258  3314 I jxcore-log: ok 507 should not be in started state
03-24 21:20:16.035  3258  3314 I jxcore-log: 
,03-24 21:20:16.037  3258  3314 I jxcore-log: # setup
03-24 21:20:16.037  3258  3314 I jxcore-log: 
,03-24 21:20:16.148  3258  3314 I jxcore-log: ok 508 should be in started state
03-24 21:20:16.148  3258  3314 I jxcore-log: 
,03-24 21:20:16.155  3258  3314 I jxcore-log: # 147. #startListeningForAdvertisements can be called multiple times in a row
03-24 21:20:16.155  3258  3314 I jxcore-log: 
,03-24 21:20:16.396  3258  3314 I jxcore-log: ok 509 should be in listening state
03-24 21:20:16.396  3258  3314 I jxcore-log: 
,03-24 21:20:16.400  3258  3314 I jxcore-log: ok 510 should still be in listening state
03-24 21:20:16.400  3258  3314 I jxcore-log: 
,03-24 21:20:16.407  3258  3314 I jxcore-log: # teardown
03-24 21:20:16.407  3258  3314 I jxcore-log: 
,03-24 21:20:18.859  3258  3314 I jxcore-log: ok 511 should not be in started state
03-24 21:20:18.859  3258  3314 I jxcore-log: 
,03-24 21:20:18.865  3258  3314 I jxcore-log: # setup
03-24 21:20:18.865  3258  3314 I jxcore-log: 
,03-24 21:20:18.999  3258  3314 I jxcore-log: ok 512 should be in started state
03-24 21:20:18.999  3258  3314 I jxcore-log: 
,03-24 21:20:19.005  3258  3314 I jxcore-log: # 148. #stopListeningForAdvertisements can be called multiple times in a row
03-24 21:20:19.005  3258  3314 I jxcore-log: 
,03-24 21:20:20.026  3258  3314 I jxcore-log: ok 513 should not be in listening state
03-24 21:20:20.026  3258  3314 I jxcore-log: 
03-24 21:20:20.027  3258  3314 I jxcore-log: ok 514 should still not be in listening state
03-24 21:20:20.027  3258  3314 I jxcore-log: 
03-24 21:20:20.029  3258  3314 I jxcore-log: # teardown
03-24 21:20:20.029  3258  3314 I jxcore-log: 
,03-24 21:20:20.144  3258  3314 I jxcore-log: ok 515 should not be in started state
,03-24 21:20:20.144  3258  3314 I jxcore-log: 
03-24 21:20:20.146  3258  3314 I jxcore-log: # setup
03-24 21:20:20.146  3258  3314 I jxcore-log: 
,03-24 21:20:21.598   820  1332 D WifiService: releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@30318451}
,03-24 21:20:21.662  3258  3314 I jxcore-log: ok 516 should be in started state
03-24 21:20:21.662  3258  3314 I jxcore-log: 
,03-24 21:20:21.668  3258  3314 I jxcore-log: # 149. #stopAdvertisingAndListening can be called multiple times in a row
03-24 21:20:21.668  3258  3314 I jxcore-log: 
,03-24 21:20:22.583  3258  3314 I jxcore-log: ok 517 should not be in advertising state
03-24 21:20:22.583  3258  3314 I jxcore-log: 
,03-24 21:20:22.589  3258  3314 I jxcore-log: ok 518 should still not be in advertising state
03-24 21:20:22.589  3258  3314 I jxcore-log: 
,03-24 21:20:22.595  3258  3314 I jxcore-log: # teardown
03-24 21:20:22.595  3258  3314 I jxcore-log: 
,03-24 21:20:23.817  3258  3314 I jxcore-log: ok 519 should not be in started state
03-24 21:20:23.817  3258  3314 I jxcore-log: 
,03-24 21:20:23.824  3258  3314 I jxcore-log: # setup
03-24 21:20:23.824  3258  3314 I jxcore-log: 
,03-24 21:20:23.954  3258  3314 I jxcore-log: ok 520 should be in started state
03-24 21:20:23.954  3258  3314 I jxcore-log: 
,03-24 21:20:23.961  3258  3314 I jxcore-log: # 150. functions are run from a queue in the right order
03-24 21:20:23.961  3258  3314 I jxcore-log: 
,03-24 21:20:25.508  3258  3314 I jxcore-log: ok 521 call order must match
03-24 21:20:25.508  3258  3314 I jxcore-log: 
,03-24 21:20:25.513  3258  3314 I jxcore-log: # teardown
03-24 21:20:25.513  3258  3314 I jxcore-log: 
,03-24 21:20:25.644  3258  3314 I jxcore-log: ok 522 should not be in started state
03-24 21:20:25.644  3258  3314 I jxcore-log: ,
03-24 21:20:25.646  3258  3314 I jxcore-log: # setup
03-24 21:20:25.646  3258  3314 I jxcore-log: 
,03-24 21:20:25.906  3258  3314 I jxcore-log: # 151. #ThaliPeerPoolDefault - single action,
03-24 21:20:25.906  3258  3314 I jxcore-log: 
,03-24 21:20:26.019  3258  3314 I jxcore-log: ok 523 is an agent
03-24 21:20:26.019  3258  3314 I jxcore-log: 
03-24 21:20:26.022  3258  3314 I jxcore-log: ok 524 enqueue is fine
,03-24 21:20:26.022  3258  3314 I jxcore-log: 
03-24 21:20:26.025  3258  3314 I jxcore-log: ok 525 Everything should be off the queue
03-24 21:20:26.025  3258  3314 I jxcore-log: 
,03-24 21:20:26.029  3258  3314 I jxcore-log: # teardown,
03-24 21:20:26.029  3258  3314 I jxcore-log: 
,03-24 21:20:26.268  3258  3314 I jxcore-log: # setup
,03-24 21:20:26.268  3258  3314 I jxcore-log: 
,03-24 21:20:26.369  3258  3314 I jxcore-log: # 152. #ThaliPeerPoolDefault - multiple actions
03-24 21:20:26.369  3258  3314 I jxcore-log: 
,03-24 21:20:26.483  3258  3314 I jxcore-log: ok 526 is an agent
03-24 21:20:26.483  3258  3314 I jxcore-log: 
,03-24 21:20:26.489  3258  3314 I jxcore-log: ok 527 first enqueue is fine
03-24 21:20:26.489  3258  3314 I jxcore-log: 
,03-24 21:20:26.495  3258  3314 I jxcore-log: ok 528 is an agent
03-24 21:20:26.495  3258  3314 I jxcore-log: 
03-24 21:20:26.495  3258  3314 I jxcore-log: ok 529 second enqueue is fine
03-24 21:20:26.495  3258  3314 I jxcore-log: 
03-24 21:20:26.498  3258  3314 I jxcore-log: ok 530 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.
03-24 21:20:26.498  3258  3314 I jxcore-log: 
03-24 21:20:26.498  3258  3314 I jxcore-log: ok 531 Queue is empty
03-24 21:20:26.498  3258  3314 I jxcore-log: 
,03-24 21:20:26.501  3258  3314 I jxcore-log: # teardown
03-24 21:20:26.501  3258  3314 I jxcore-log: 
,03-24 21:20:26.751  3258  3314 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
03-24 21:20:26.751  3258  3314 I jxcore-log: 
,03-24 21:20:27.046  3860  3860 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,03-24 21:20:27.049  3860  3860 D AndroidRuntime: CheckJNI is OFF
,03-24 21:20:27.163  3860  3860 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,03-24 21:20:27.177   820   854 I ActivityManager: Force stopping com.test.thalitest appid=10095 user=-1: uninstall pkg
03-24 21:20:27.178   820   854 I ActivityManager: Killing 3258:com.test.thalitest/u0a95 (adj 0): stop com.test.thalitest
,03-24 21:20:27.242   820   864 W PackageSettings: Skipping PackageSetting{169d37a5 com.example.hello/10273} due to missing metadata
,03-24 21:20:27.355   820  1375 I WindowState: WIN DEATH: Window{85480e3 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,03-24 21:20:27.356   820  1022 D WifiService: Client connection lost with reason: 4
,03-24 21:20:27.395   820   854 W ActivityManager: Force removing ActivityRecord{2e0b0d05 u0 com.test.thalitest/.MainActivity t17}: app died, no saved state,
,03-24 21:20:27.411   820   820 V ActivityManager: Display changed displayId=0
,03-24 21:20:27.442   820   864 I ActivityManager: Force stopping com.test.thalitest appid=10095 user=0: pkg removed
,03-24 21:20:27.448   820   836 W ActivityManager: Spurious death for ProcessRecord{32bf3124 3258:com.test.thalitest/u0a95}, curProc for 3258: null
,03-24 21:20:27.450   820  1044 D TaskPersister: removeObsoleteFile: deleting file=17_task.xml
,03-24 21:20:27.453  1234  1234 I Keyboard.Facilitator: resetDictionaries() : en_US
,03-24 21:20:27.458   820  1012 I InputReader: Reconfiguring input devices.  changes=0x00000010
,03-24 21:20:27.458  1234  3874 I Keyboard.Facilitator.DecoderInitializer: run()
03-24 21:20:27.460  1234  3874 I Decoder : createOrResetDecoder
,03-24 21:20:27.463  2974  2974 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,03-24 21:20:27.490  1064  1064 I art     : Explicit concurrent mark sweep GC freed 20338(896KB) AllocSpace objects, 0(0B) LOS objects, 20% free, 61MB/77MB, paused 976us total 42.618ms
,03-24 21:20:27.498   820  1460 I ActivityManager: Start proc 3876:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,03-24 21:20:27.510   369   369 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 204us total 9.719ms
,03-24 21:20:27.518   820   820 I art     : Explicit concurrent mark sweep GC freed 33172(1861KB) AllocSpace objects, 6(284KB) LOS objects, 32% free, 33MB/49MB, paused 3.891ms total 71.492ms
,03-24 21:20:27.521   369   369 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 212us total 10.954ms
,03-24 21:20:27.525  1266  1266 I ConfigService: onCreate
,03-24 21:20:27.535   369   369 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 249us total 11.469ms
,03-24 21:20:27.543   820   836 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3258 uid 10095
,03-24 21:20:27.549  1234  1234 I Keyboard.Facilitator: onFinishInput()
,03-24 21:20:27.598  1376  1376 I art     : Explicit concurrent mark sweep GC freed 4989(364KB) AllocSpace objects, 12(1408KB) LOS objects, 31% free, 35MB/51MB, paused 737us total 21.950ms
,03-24 21:20:27.604  1234  3874 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,03-24 21:20:27.610   820   820 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
03-24 21:20:27.610   820   820 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,03-24 21:20:27.641  1234  3874 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,03-24 21:20:27.643  1234  3874 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
03-24 21:20:27.643  1234  3874 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,03-24 21:20:27.644  1234  3874 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
03-24 21:20:27.644  1234  3874 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
03-24 21:20:27.645  1234  3874 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
03-24 21:20:27.645  1234  3874 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
03-24 21:20:27.646  1234  3874 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
03-24 21:20:27.646  1234  3874 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
03-24 21:20:27.646  1234  3874 I Keyboard.Facilitator.Delight2FileSweeper: run()
03-24 21:20:27.646  1234  3874 I Keyboard.Facilitator.RecurringTaskScheduler: run()
,03-24 21:20:27.646  1234  3874 I StatsUtilsManager: startPeriodStatsRecorder() : Success
,03-24 21:20:27.646  1234  3874 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,03-24 21:20:27.657   820   864 I art     : Explicit concurrent mark sweep GC freed 9662(960KB) AllocSpace objects, 2(126KB) LOS objects, 32% free, 33MB/49MB, paused 2.531ms total 133.128ms
,03-24 21:20:27.676  3876  3907 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,03-24 21:20:27.688   820   835 I ActivityManager: Start proc 3909:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,03-24 21:20:27.734  3876  3905 I ContactLocale: AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,03-24 21:20:27.737  3860  3860 I art     : System.exit called, status: 0
03-24 21:20:27.737  3860  3860 I AndroidRuntime: VM exiting with result code 0.
,03-24 21:20:27.743   820   835 I ActivityManager: Start proc 3930:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,03-24 21:20:27.747   820  1375 I ActivityManager: Killing 3560:com.android.chrome/u0a40 (adj 15): empty #17
,03-24 21:20:27.754  3761  3761 W LocationOracleImpl: Best location was null
,03-24 21:20:27.759  1376  1376 D Launcher.Workspace: 11683562 - stripEmptyScreens()
,03-24 21:20:27.760  1376  1376 D Launcher.Workspace: 11683562 - stripEmptyScreens()
,03-24 21:20:27.765  3761  3761 I VS.Container: create_recognizer
,03-24 21:20:27.824  3761  3957 I HotwordRecognitionRnr: Starting hotword detection.
,03-24 21:20:27.825  3761  3958 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.u@3e8e625d
,03-24 21:20:27.827   357  3960 I AudioFlinger: AudioFlinger's thread 0xb4c52000 ready to run
,03-24 21:20:27.829   357  1009 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,03-24 21:20:27.830  3761  3958 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.u@3e8e625d
,03-24 21:20:27.840   357  3960 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
03-24 21:20:27.840   357  3960 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
03-24 21:20:27.840   357  3960 E ACDB-LOADER: Error: ACDB AudProc vol returned = -19
,03-24 21:20:27.840   357  3960 D audio_hw_primary: enable_snd_device: snd_device(55: voice-rec-mic)
,03-24 21:20:27.850   357  3960 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record,
,03-24 21:20:27.903   820   864 I ActivityManager: Start proc 3962:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,03-24 21:20:27.929  3876  3905 E SQLiteLog: (3850) statement aborts at 22: [DELETE FROM deleted_contacts WHERE contact_deleted_timestamp < ?] disk I/O error
,--------- beginning of crash
03-24 21:20:27.931  3876  3905 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
03-24 21:20:27.931  3876  3905 E AndroidRuntime: Process: android.process.acore, PID: 3876
03-24 21:20:27.931  3876  3905 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-24 21:20:27.931  3876  3905 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
03-24 21:20:27.931  3876  3905 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
03-24 21:20:27.931  3876  3905 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
03-24 21:20:27.931  3876  3905 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
03-24 21:20:27.931  3876  3905 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
03-24 21:20:27.931  3876  3905 E AndroidRuntime: 	at com.android.providers.contacts.database.DeletedContactsTableUtil.deleteOldLogs(DeletedContactsTableUtil.java:78)
03-24 21:20:27.931  3876  3905 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1730)
03-24 21:20:27.931  3876  3905 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1492)
03-24 21:20:27.931  3876  3905 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-24 21:20:27.931  3876  3905 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
03-24 21:20:27.931  3876  3905 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-24 21:20:27.935   820  1332 I ActivityManager: Killing 3608:com.qualcomm.timeservice/1000 (adj 15): empty #17
,03-24 21:20:27.938   820  3981 E DropBoxManagerService: Can't write: system_app_crash
03-24 21:20:27.938   820  3981 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop95.tmp: open failed: EROFS (Read-only file system)
03-24 21:20:27.938   820  3981 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-24 21:20:27.938   820  3981 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-24 21:20:27.938   820  3981 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-24 21:20:27.938   820  3981 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-24 21:20:27.938   820  3981 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-24 21:20:27.938   820  3981 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
03-24 21:20:27.938   820  3981 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-24 21:20:27.938   820  3981 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-24 21:20:27.938   820  3981 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-24 21:20:27.938   820  3981 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-24 21:20:27.938   820  3981 E DropBoxManagerService: 	... 5 more
03-24 21:20:27.940  3930  3930 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
,03-24 21:20:28.075   820  3983 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,03-24 21:20:28.076   820   854 D Atlas   : Validating map...
,03-24 21:20:28.095  1266  1266 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
03-24 21:20:28.095  1266  1266 D AndroidRuntime: Shutting down VM
,03-24 21:20:28.096  1266  1266 E AndroidRuntime: FATAL EXCEPTION: main
03-24 21:20:28.096  1266  1266 E AndroidRuntime: Process: com.google.process.gapps, PID: 1266
03-24 21:20:28.096  1266  1266 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-24 21:20:28.096  1266  1266 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2616)
03-24 21:20:28.096  1266  1266 E AndroidRuntime: 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
03-24 21:20:28.096  1266  1266 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
03-24 21:20:28.096  1266  1266 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-24 21:20:28.096  1266  1266 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
03-24 21:20:28.096  1266  1266 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5254)
03-24 21:20:28.096  1266  1266 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
03-24 21:20:28.096  1266  1266 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-24 21:20:28.096  1266  1266 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
03-24 21:20:28.096  1266  1266 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
03-24 21:20:28.096  1266  1266 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-24 21:20:28.096  1266  1266 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
03-24 21:20:28.096  1266  1266 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
03-24 21:20:28.096  1266  1266 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
03-24 21:20:28.096  1266  1266 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
03-24 21:20:28.096  1266  1266 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
03-24 21:20:28.096  1266  1266 E AndroidRuntime: 	at com.google.android.gms.gcm.bh.a(SourceFile:310)
03-24 21:20:28.096  1266  1266 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:127)
03-24 21:20:28.096  1266  1266 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:321)
03-24 21:20:28.096  1266  1266 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2609)
03-24 21:20:28.096  1266  1266 E AndroidRuntime: 	... 9 more
03-24 21:20:28.105  3930  3984 E SQLiteDatabase: Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
03-24 21:20:28.105  3930  3984 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-24 21:20:28.105  3930  3984 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-24 21:20:28.105  3930  3984 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-24 21:20:28.105  3930  3984 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-24 21:20:28.105  3930  3984 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-24 21:20:28.105  3930  3984 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-24 21:20:28.105  3930  3984 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-24 21:20:28.105  3930  3984 E SQLiteDatabase: 	at android.database.sqlite.SQL,iteDatabase.openInner(SQLiteDatabase.java:806)
03-24 21:20:28.105  3930  3984 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-24 21:20:28.105  3930  3984 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-24 21:20:28.105  3930  3984 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-24 21:20:28.105  3930  3984 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-24 21:20:28.105  3930  3984 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-24 21:20:28.105  3930  3984 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-24 21:20:28.105  3930  3984 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
03-24 21:20:28.105  3930  3984 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
03-24 21:20:28.105  3930  3984 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-24 21:20:28.105  3930  3984 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-24 21:20:28.105  3930  3984 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
03-24 21:20:28.105  3930  3984 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-24 21:20:28.106  3930  3984 E AndroidRuntime: FATAL EXCEPTION: IntentService[KeyChainService]
03-24 21:20:28.106  3930  3984 E AndroidRuntime: Process: com.android.keychain, PID: 3930
03-24 21:20:28.106  3930  3984 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-24 21:20:28.106  3930  3984 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-24 21:20:28.106  3930  3984 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-24 21:20:28.106  3930  3984 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-24 21:20:28.106  3930  3984 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-24 21:20:28.106  3930  3984 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-24 21:20:28.106  3930  3984 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-24 21:20:28.106  3930  3984 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-24 21:20:28.106  3930  3984 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-24 21:20:28.106  3930  3984 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-24 21:20:28.106  3930  3984 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-24 21:20:28.106  3930  3984 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-24 21:20:28.106  3930  3984 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-24 21:20:28.106  3930  3984 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-24 21:20:28.106  3930  3984 E AndroidRuntime: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
03-24 21:20:28.106  3930  3984 E AndroidRuntime: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
03-24 21:20:28.106  3930  3984 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-24 21:20:28.106  3930  3984 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-24 21:20:28.106  3930  3984 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
03-24 21:20:28.106  3930  3984 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-24 21:20:28.108   820  3986 E DropBoxManagerService: Can't write: system_app_crash
03-24 21:20:28.108   820  3986 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop97.tmp: open failed: EROFS (Read-only file system)
03-24 21:20:28.108   820  3986 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-24 21:20:28.108   820  3986 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-24 21:20:28.108   820  3986 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-24 21:20:28.108   820  3986 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-24 21:20:28.108   820  3986 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-24 21:20:28.108   820  3986 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
03-24 21:20:28.108   820  3986 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-24 21:20:28.108   820  3986 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-24 21:20:28.108   820  3986 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-24 21:20:28.108   820  3986 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-24 21:20:28.108   820  3986 E DropBoxManagerService: 	... 5 more
03-24 21:20:28.112   820  3987 E DropBoxManagerService: Can't write: system_app_crash
03-24 21:20:28.112   820  3987 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop98.tmp: open failed: EROFS (Read-only file system)
03-24 21:20:28.112   820  3987 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-24 21:20:28.112   820  3987 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-24 21:20:28.112   820  3987 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-24 21:20:28.112   820  3987 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-24 21:20:28.112   820  3987 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-24 21:20:28.112   820  3987 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
03-24 21:20:28.112   820  3987 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-24 21:20:28.112   820  3987 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-24 21:20:28.112   820  3987 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-24 21:20:28.112   820  3987 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-24 21:20:28.112   820  3987 E DropBoxManagerService: 	... 5 more
03-24 21:20:28.116   820  3983 I OpenGLRenderer: Initialized EGL, version 1.4
03-24 21:20:28.131   820  3983 D OpenGLRenderer: Enabling debug mode 0
,03-24 21:20:28.201  3761  3761 I HotwordWorker: onReady
,03-24 21:20:28.223  3761  3995 E Search.SharedPreferencesProto: Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,03-24 21:20:28.231  1801  1911 W Icing   : Received bad json for section weights override -- ignoring.
03-24 21:20:28.232  1801  1911 W Icing   : Received bad json for corpus context scoring override -- ignoring.
,03-24 21:20:28.232  1801  1911 W Icing   : Received bad json for section weights override -- ignoring.
03-24 21:20:28.232  1801  1911 W Icing   : Received bad json for corpus context scoring override -- ignoring.
,03-24 21:20:28.238  3761  3949 W FileUtils: Failed to chmod(/data/data/com.google.android.googlequicksearchbox/files): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
03-24 21:20:28.238  3761  3949 E FileBytesWriter: Failed to write new file: loracle.new
,03-24 21:20:28.240  3761  3996 E Search.SharedPreferencesProto: Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,03-24 21:20:28.242  3761  3997 E Search.SharedPreferencesProto: Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,03-24 21:20:28.261  3761  3949 W FileUtils: Failed to chmod(/data/data/com.google.android.googlequicksearchbox/files): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,03-24 21:20:28.261  3761  3949 E FileBytesWriter: Failed to write new file: loracle.new
,03-24 21:20:28.441  3761  3761 I HotwordDetector: Closing mic
,03-24 21:20:28.442  3761  3955 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.u@3e8e625d,
,03-24 21:20:28.483  3761  4000 E Search.SharedPreferencesProto: Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,03-24 21:20:28.495   357  3960 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
03-24 21:20:28.496   357  3960 D audio_hw_primary: disable_snd_device: snd_device(55: voice-rec-mic)
,03-24 21:20:28.500   357  1009 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,03-24 21:20:28.504  3761  3956 I HotwordRecognitionRnr: Stopping hotword detection.
,03-24 21:20:28.505  3761  3761 W TRUiThreadExecutor: Task does not implement UiTask: com.google.common.g.a.p@2f634c60
,03-24 21:20:28.508  3761  3957 I HotwordRecognitionRnr: Hotword detection finished
,03-24 21:20:28.654  1234  3874 E native  : dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,03-24 21:20:28.655  1234  3874 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,03-24 21:20:28.693  1234  3874 E native  : dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
03-24 21:20:28.693  1234  3874 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,03-24 21:20:28.724  1234  3874 E native  : dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
,03-24 21:20:28.724  1234  3874 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
03-24 21:20:28.724  1234  3874 E native  : dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
03-24 21:20:28.724  1234  3874 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
,03-24 21:20:30.269  1801  1847 W Icing   : Usage reports not received in time.
,03-24 21:20:32.312  1801  1847 W Icing   : Usage reports not received in time.
,03-24 21:20:32.330   820  1460 I ActivityManager: Killing 3627:com.google.android.deskclock/u0a44 (adj 15): empty #17
,03-24 21:20:32.804  3761  4008 E Search.SharedPreferencesProto: Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,03-24 21:20:38.367   820  1256 E QMI_FW  : xport_send: Sendto failed for port 4608
03-24 21:20:38.368   820  1256 E LocSvc_api_v02: E/locClientSendReq:2446]: send_msg_sync error: -1
,03-24 21:20:38.368   820  1256 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 11, ind.status = -1657656595
03-24 21:20:38.368   820  1256 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
03-24 21:20:38.368   820  1256 E QMI_FW  : xport_send: Sendto failed for port 4608
03-24 21:20:38.368   820  1256 E LocSvc_api_v02: E/locClientSendReq:2446]: send_msg_sync error: -1
,03-24 21:20:38.368   820  1256 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 11, ind.status = -1657656595
03-24 21:20:38.369   820  1256 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
03-24 21:20:38.372   259   319 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,03-24 21:20:38.380   870   870 E kickstart: ERROR: function: rx_data:288 Read/Write File descriptor returned error: No such device, error code -1
03-24 21:20:38.380   870   870 E kickstart: ERROR: function: sahara_main:1143 Sahara protocol error
,03-24 21:20:38.381   870   870 E kickstart: ERROR: function: main:268 Uploading  Image using Sahara protocol failed
03-24 21:20:38.381   870   870 I kickstart: STATUS: Wrote to /sys/power/wake_unlock

```
