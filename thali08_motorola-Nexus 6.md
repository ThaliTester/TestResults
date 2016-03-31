#### Test 64746945aaa3c62_thali08_motorola-Nexus 6 Logs


```
--------- beginning of system
,03-31 10:12:39.385   822   864 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
--------- beginning of main
03-31 10:12:39.396   822   864 I Adreno  : EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
03-31 10:12:39.438   258   820 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (215 us)
03-31 10:12:39.673  3237  3237 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
03-31 10:12:39.677  3237  3237 D AndroidRuntime: CheckJNI is OFF
03-31 10:12:39.826  3237  3237 D AndroidRuntime: Calling main entry com.android.commands.am.Am
03-31 10:12:39.831   822  1449 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
03-31 10:12:39.838   822  1449 V WindowManager: addAppToken: AppWindowToken{1dd5a8bd token=Token{a3db814 ActivityRecord{d3fa267 u0 com.test.thalitest/.MainActivity t17}}} to stack=1 task=17 at 0
03-31 10:12:39.847   822   862 V WindowManager: Adding window Window{37aff5ac u0 Starting com.test.thalitest} at 2 of 7 (after Window{dd84277 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
03-31 10:12:39.851  3237  3237 D AndroidRuntime: Shutting down VM
03-31 10:12:39.857  1514  1514 I HotwordDetector: Closing mic
03-31 10:12:39.858  1514  1796 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.u@2ec02d7
03-31 10:12:39.887   822  1201 I ActivityManager: Start proc 3253:com.test.thalitest/u0a95 for activity com.test.thalitest/.MainActivity
03-31 10:12:39.907   357  1802 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
03-31 10:12:39.909   357  1802 D audio_hw_primary: disable_snd_device: snd_device(55: voice-rec-mic)
03-31 10:12:39.917   357  1032 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
03-31 10:12:39.921  1514  1798 I HotwordRecognitionRnr: Stopping hotword detection.
03-31 10:12:39.921  1514  1799 I HotwordRecognitionRnr: Hotword detection finished
03-31 10:12:39.953   822  1410 I ActivityManager: Killing 2860:com.google.android.apps.messaging/u0a75 (adj 15): empty #17
03-31 10:12:40.034   822   862 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
03-31 10:12:40.034   822   822 V ActivityManager: Display changed displayId=0
03-31 10:12:40.036   258   258 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6482000
03-31 10:12:40.036   258   258 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
03-31 10:12:40.059   822  1410 I ActivityManager: Killing 2689:com.google.android.apps.fitness/u0a51 (adj 15): empty #18
,03-31 10:12:40.200   873   873 I kickstart: STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
03-31 10:12:40.200   873   873 I kickstart: STATUS: Wrote to /sys/power/wake_lock
,03-31 10:12:40.242   873   873 E kickstart: ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1
03-31 10:12:40.242   873   873 I kickstart: STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1' for writing
03-31 10:12:40.243   822  1256 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1660388627
,03-31 10:12:40.243   822  1256 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,03-31 10:12:40.269  3253  3253 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,03-31 10:12:40.282  3253  3253 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 5550-5553),
03-31 10:12:40.283  3253  3253 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-31 10:12:40.296  3253  3253 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {28fa134e}
03-31 10:12:40.296  3253  3253 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-31 10:12:40.296  3253  3253 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,03-31 10:12:40.306  3253  3253 I BrowserStartupController: Initializing chromium process, singleProcess=true
03-31 10:12:40.306  3253  3253 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-31 10:12:40.307  3253  3253 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-31 10:12:40.314   258   319 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0,
,03-31 10:12:40.315   258   258 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
03-31 10:12:40.315   822  1048 D SurfaceControl: Excessive delay in setPowerMode(): 280ms
,03-31 10:12:40.317  3253  3278 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,03-31 10:12:40.322   822   864 I DreamManagerService: Entering dreamland.
03-31 10:12:40.322   357  1035 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
03-31 10:12:40.322   357  1035 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,03-31 10:12:40.323   822   864 I PowerManagerService: Dozing...
03-31 10:12:40.324   822   859 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,03-31 10:12:40.326  3253  3253 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,03-31 10:12:40.331  3253  3253 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-31 10:12:40.331  3253  3253 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-31 10:12:40.331  3253  3253 I Adreno  : EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,03-31 10:12:40.336   822  1012 E WifiStateMachine: cancelDelayedScan -> 16
,03-31 10:12:40.339   822  1012 E native  : do suspend false
,03-31 10:12:40.380   822   861 D BluetoothManagerService: Message: 20
,03-31 10:12:40.380   822   861 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@efa499d:true
,03-31 10:12:40.383   822  1012 E WifiStateMachine: cancelDelayedScan -> 18
,03-31 10:12:40.408  3253  3253 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-31 10:12:40.415  3253  3253 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-31 10:12:40.426  3253  3253 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,03-31 10:12:40.427   822  1012 E native  : do suspend true
,03-31 10:12:40.432  3253  3253 W art     : Attempt to remove local handle scope entry from IRT, ignoring,
03-31 10:12:40.432  3253  3253 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-31 10:12:40.499   357  1035 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
03-31 10:12:40.499   357  1035 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,03-31 10:12:40.500  3253  3302 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,03-31 10:12:40.504  3253  3253 D Atlas   : Validating map...
,03-31 10:12:40.511   822  1429 V WindowManager: Adding window Window{2a25d40d u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{37aff5ac u0 Starting com.test.thalitest})
,03-31 10:12:40.514  3253  3289 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,03-31 10:12:40.541   822  1012 E WifiStateMachine: WifiStateMachine Disconnected CMD_START_SCAN source -2 17, 18 -> obsolete
,03-31 10:12:40.550  3253  3302 I OpenGLRenderer: Initialized EGL, version 1.4
,03-31 10:12:40.555  3253  3302 D OpenGLRenderer: Enabling debug mode 0
,03-31 10:12:40.602   822  1012 E WifiStateMachine: WifiStateMachine Disconnected CMD_START_SCAN source -2 15, 18 -> obsolete
,03-31 10:12:40.610   822   862 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +759ms
,03-31 10:12:40.619  1237  1237 I Keyboard.Facilitator: onFinishInput()
,03-31 10:12:40.629  3253  3253 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,03-31 10:12:40.649  3253  3253 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3253
,03-31 10:12:40.752  3253  3253 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-31 10:12:40.980  3253  3305 D jxcore_app_log: JniHelper::setJavaVM(0xb489d200), pthread_self() = -1573432576
,03-31 10:12:40.994  3253  3305 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-31 10:12:40.994  3253  3305 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-31 10:12:40.994  3253  3305 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-31 10:12:40.994  3253  3305 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
,03-31 10:12:40.994  3253  3305 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-31 10:12:40.995  3253  3305 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ffdc06b added. We now have 1 listener(s)
,03-31 10:12:40.998   822  1329 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 10:12:41.008  3253  3305 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,03-31 10:12:41.012  3253  3305 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,03-31 10:12:41.014  3253  3305 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
03-31 10:12:41.015  3253  3305 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,03-31 10:12:41.023  3253  3305 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-31 10:12:41.023  3253  3305 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
,03-31 10:12:41.023  3253  3305 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-31 10:12:41.023  3253  3305 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
03-31 10:12:41.023  3253  3305 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-31 10:12:41.023  3253  3305 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-31 10:12:41.023  3253  3305 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE,
03-31 10:12:41.023  3253  3305 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-31 10:12:41.023  3253  3305 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-31 10:12:41.023  3253  3305 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-31 10:12:41.023  3253  3305 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,03-31 10:12:41.023  3253  3305 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32fac786 added. We now have 1 listener(s)
03-31 10:12:41.023  3253  3305 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-31 10:12:41.028   822  1014 D WifiService: New client listening to asynchronous messages
,03-31 10:12:41.030  3253  3305 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage,
,03-31 10:12:41.032  3253  3305 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,03-31 10:12:41.032  3253  3305 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2,
03-31 10:12:41.032  3253  3305 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
03-31 10:12:41.032  3253  3305 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,03-31 10:12:41.035  3253  3305 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 10:12:41.035   822   841 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 10:12:41.037  3253  3305 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,03-31 10:12:41.041  3253  3305 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
03-31 10:12:41.041  3253  3305 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 10:12:41.041  3253  3305 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 10:12:41.041  3253  3305 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 10:12:41.041  3253  3305 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 10:12:41.041  3253  3305 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
03-31 10:12:41.041  3253  3305 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
03-31 10:12:41.041  3253  3305 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
03-31 10:12:41.042  3253  3305 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-31 10:12:41.042  3253  3305 D io.jxcore.node.ConnectivityMonitor: start: OK
,03-31 10:12:41.043  3253  3253 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-31 10:12:41.045  3253  3305 I io.jxcore.node.LifeCycleMonitor: start: OK
,03-31 10:12:41.073  3253  3253 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-31 10:12:41.234   873   873 I kickstart: STATUS: Received file 'm9kefs1'
,03-31 10:12:41.234   873   873 I kickstart: STATUS: 950272 bytes transferred in 0.991514 seconds
03-31 10:12:41.234   873   873 I kickstart: STATUS: Successfully downloaded files from target 
03-31 10:12:41.234   873   873 I kickstart: STATUS: Wrote to /sys/power/wake_unlock
,03-31 10:12:41.237   873   873 I kickstart: STATUS: Sahara protocol completed
,03-31 10:12:41.689  3253  3312 W jxcore-log: Initializing JXcore engine
,03-31 10:12:41.689  3253  3312 W jxcore-log: JXcore engine is ready
,03-31 10:12:41.720  3312  3312 W Thread-344: type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[9648]" dev="sockfs" ino=9648 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
03-31 10:12:41.720  3312  3312 W Thread-344: type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
03-31 10:12:41.720  3312  3312 W Thread-344: type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[10647]" dev="sockfs" ino=10647 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
03-31 10:12:41.720  3312  3312 W Thread-344: type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[20024]" dev="sockfs" ino=20024 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,03-31 10:12:41.741  3253  3312 W jxcore-log: Starting JXcore engine
,03-31 10:12:41.824  3253  3312 W jxcore-log: Platform android
03-31 10:12:41.824  3253  3312 W jxcore-log: 
,03-31 10:12:41.824  3253  3312 W jxcore-log: Process ARCH arm
03-31 10:12:41.824  3253  3312 W jxcore-log: 
,03-31 10:12:42.023  3253  3312 I jxcore-log: JXcore Cordova bridge is ready!
03-31 10:12:42.023  3253  3312 I jxcore-log: 
03-31 10:12:42.023  3253  3312 W jxcore-log: JXcore engine is started
,03-31 10:12:42.029  3253  3305 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-31 10:12:42.031  3253  3253 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,03-31 10:12:42.889  1155  1155 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,03-31 10:12:43.307  1155  1155 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,03-31 10:12:43.339  1155  1155 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,03-31 10:12:43.340  1155  1155 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,03-31 10:12:43.364   822  1012 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
03-31 10:12:43.364   822  1012 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
03-31 10:12:43.364   822  1015 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,03-31 10:12:43.369   822  1012 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,03-31 10:12:43.376   353   799 D CommandListener: Setting iface cfg
,03-31 10:12:43.380   822  1012 E WifiStateMachine: Start Dhcp Watchdog 1
,03-31 10:12:43.383   822  1012 E WifiStateMachine:  WifiLinkLayerStats: 
03-31 10:12:43.383   822  1012 E WifiStateMachine:  my bss beacon rx: 1
03-31 10:12:43.383   822  1012 E WifiStateMachine:  RSSI mgmt: -39
03-31 10:12:43.383   822  1012 E WifiStateMachine:  BE :  rx=0 tx=3 lost=0 retries=1
03-31 10:12:43.383   822  1012 E WifiStateMachine:  BK :  rx=0 tx=0 lost=0 retries=0
03-31 10:12:43.383   822  1012 E WifiStateMachine:  VI :  rx=0 tx=0 lost=0 retries=0
03-31 10:12:43.383   822  1012 E WifiStateMachine:  VO :  rx=2 tx=0 lost=0 retries=0
03-31 10:12:43.383   822  1012 E WifiStateMachine:  on_time : 477 tx_time=63 rx_time=110 scan_time=0
,03-31 10:12:43.482   822  1012 E native  : do suspend false
,03-31 10:12:43.495   822  1012 E WifiStateMachine: scanCount==0 - aborting
,03-31 10:12:43.740  3315  3315 I dhcpcd  : version 5.5.6 starting
,03-31 10:12:43.856  3315  3315 I dhcpcd  : wlan0: rebinding lease of 192.168.1.125
,03-31 10:12:44.010  3315  3315 I dhcpcd  : wlan0: acknowledged 192.168.1.125 from 192.168.1.1
,03-31 10:12:44.089  3315  3315 I dhcpcd  : wlan0: leased 192.168.1.125 for 172800 seconds
,03-31 10:12:44.514   822  1012 E native  : do suspend true
,03-31 10:12:44.560   822  1015 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED,
,03-31 10:12:44.562   822  1015 D ConnectivityService: Adding iface wlan0 to network 100
,03-31 10:12:44.566   822  1012 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,03-31 10:12:44.580   822  1015 E ConnectivityService: Unexpected mtu value: 0, wlan0
03-31 10:12:44.580   822  1015 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 100
,03-31 10:12:44.581   822  1015 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,03-31 10:12:44.582   822  1015 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,03-31 10:12:44.583   822  1015 D ConnectivityService: Setting Dns servers for network 100 to [/192.168.1.1]
,03-31 10:12:44.589   822  1015 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,03-31 10:12:44.592   822  1015 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
03-31 10:12:44.592   822  3313 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
03-31 10:12:44.593   822  3313 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Connected
03-31 10:12:44.593   822  3313 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
03-31 10:12:44.593   822  3313 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
03-31 10:12:44.593   822  1015 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
03-31 10:12:44.593   822  1015 D ConnectivityService:    accepting network in place of null
,03-31 10:12:44.594   822  1015 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.125/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
,03-31 10:12:44.595   822  1015 D ConnectivityService: Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
,03-31 10:12:44.601   822  1015 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,03-31 10:12:44.602  1070  1542 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,03-31 10:12:44.602   822  1015 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
03-31 10:12:44.603   822  1015 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,03-31 10:12:44.606   822  1015 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
03-31 10:12:44.607   822   861 D Tethering: MasterInitialState.processMessage what=3
,03-31 10:12:44.613   822  1410 V BackupManagerService: Scheduling immediate backup pass
03-31 10:12:44.613  1345  1374 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
03-31 10:12:44.613  1345  1374 E PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,03-31 10:12:44.615   822   856 D TelephonyManager: getDataEnabled: retVal=false
,03-31 10:12:44.615   822   822 V BackupManagerService: Running a backup pass
03-31 10:12:44.616  2916  2916 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,03-31 10:12:44.617   822  1047 V BackupManagerService: clearing pending backups
03-31 10:12:44.617  3253  3253 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
03-31 10:12:44.617  3253  3253 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 10:12:44.617  3253  3253 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 10:12:44.617  3253  3253 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 10:12:44.617  3253  3253 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 10:12:44.617  3253  3253 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 10:12:44.617  3253  3253 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 10:12:44.617  3253  3253 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 10:12:44.617  3253  3253 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,03-31 10:12:44.622  2916  2916 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,03-31 10:12:44.631   822   856 E GpsLocationProvider: No APN found to select.
03-31 10:12:44.631   822  1047 V PerformBackupTask: Beginning backup of 14 targets
,03-31 10:12:44.639   822  1047 D PerformBackupTask: invokeAgentForBackup on @pm@
,03-31 10:12:44.641   822  1047 V BackupServiceBinder: doBackup() invoked
,03-31 10:12:44.643   822  1047 I PMBA    : Previous metadata 1570415 mismatch vs 1860966 - rewriting
,03-31 10:12:44.662   822  1201 I ActivityManager: Start proc 3355:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.steen.receiver.ConnectivityChangeReceiver
,03-31 10:12:44.666   822  1047 I BackupRestoreController: Getting widget state for user: 0
,03-31 10:12:44.740   822  3374 D GpsLocationProvider: NTP server returned: 1459411965094 (Thu Mar 31 10:12:45 GMT+02:00 2016) reference: 170011 certainty: 15 system time offset: 354
03-31 10:12:44.742   822  1274 D AlarmManagerService: Setting time of day to sec=1459411965
03-31 10:12:45.096   822  1274 W AlarmManagerService: Unable to set rtc to 1459411965: Invalid argument
,03-31 10:12:45.154   822  1047 I art     : Explicit concurrent mark sweep GC freed 65573(3MB) AllocSpace objects, 3(48KB) LOS objects, 32% free, 33MB/49MB, paused 1.608ms total 110.195ms
,03-31 10:12:45.158   822  3313 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 31 Mar 2016 08:12:45 GMT], X-Android-Received-Millis=[1459411965158], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1459411965108]}
,03-31 10:12:45.181  1804  3380 E Auth.Api.Credentials: [CredentialSyncAdapter] Unknown sync event.
,03-31 10:12:45.183   822  1449 I ActivityManager: Start proc 3389:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,03-31 10:12:45.185   822  3313 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Validated
03-31 10:12:45.186   822  1015 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
03-31 10:12:45.186   822  1015 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 100]
03-31 10:12:45.186   822  1015 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
03-31 10:12:45.186   822  1015 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
03-31 10:12:45.186   822  1015 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
03-31 10:12:45.186  1070  1542 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
03-31 10:12:45.186   822  1015 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,03-31 10:12:45.194   369   369 I art     : Explicit concurrent mark sweep GC freed 704(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 21MB/36MB, paused 209us total 10.949ms
,03-31 10:12:45.206   369   369 I art     : Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 203us total 12.057ms
,03-31 10:12:45.215   369   369 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 207us total 8.464ms
,03-31 10:12:45.226  3389  3389 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,03-31 10:12:45.238  3389  3389 D SprintDMHelper: simOperator:  IMSI: null
03-31 10:12:45.238  3389  3389 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,03-31 10:12:45.248  1832  1849 W GmsBackupTransport: Unknown package in backup request: @pm@
,03-31 10:12:45.250  1832  1849 V GmsBackupTransport: starting performBackup for @pm@
,03-31 10:12:45.257  1804  3409 W DriveInitializer: Background init thread started
,03-31 10:12:45.258  1804  1804 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,03-31 10:12:45.263  1804  1804 D SystemUpdateService: onCreate
03-31 10:12:45.263  1832  1849 V GmsBackupTransport: performBackup done for @pm@
,03-31 10:12:45.267  1804  1804 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,03-31 10:12:45.271  1265  1265 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 10:12:45.272  1804  3412 I SystemUpdateService: active receiver: enabled
,03-31 10:12:45.280  1804  3410 W DriveInitializer: Awaiting to be initialized
,03-31 10:12:45.281  1804  3412 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,03-31 10:12:45.295  1804  3412 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]; metered: false; mobile allowed: true
03-31 10:12:45.295  1804  3412 I SystemUpdateService: now status is 0 (complete)
03-31 10:12:45.295  1804  3412 I SystemUpdateService: processDownloadedFile /data/data/com.google.android.gms/app_download/update.zip
03-31 10:12:45.295  1804  3412 I SystemUpdateService: file has been verified
,03-31 10:12:45.296  1265  1282 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: android
03-31 10:12:45.296  1804  3412 I SystemUpdateService: OTA package size = 25802302
03-31 10:12:45.297  1265  1282 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> android without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-31 10:12:45.297  1265  1282 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 10:12:45.297  1265  1282 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 10:12:45.301  1265  1282 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 10:12:45.335  1265  1282 W GLSActivity: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-31 10:12:45.335  1265  1282 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-31 10:12:45.335  1265  1282 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-31 10:12:45.335  1265  1282 W GLSActivity: 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
03-31 10:12:45.335  1265  1282 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
03-31 10:12:45.335  1265  1282 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
03-31 10:12:45.335  1265  1282 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:446)
,03-31 10:12:45.337  1832  1847 W GmsBackupTransport: Error sending final backup to server: 
03-31 10:12:45.337  1832  1847 W GmsBackupTransport: com.google.android.gms.backup.d.d: Can not get client auth token
03-31 10:12:45.337  1832  1847 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:1080)
03-31 10:12:45.337  1832  1847 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:65)
03-31 10:12:45.337  1832  1847 W GmsBackupTransport: 	at com.google.android.gms.backup.aa.finishBackup(SourceFile:409)
03-31 10:12:45.337  1832  1847 W GmsBackupTransport: 	at android.app.backup.BackupTransport$TransportImpl.finishBackup(BackupTransport.java:547)
03-31 10:12:45.337  1832  1847 W GmsBackupTransport: 	at com.android.internal.backup.IBackupTransport$Stub.onTransact(IBackupTransport.java:162)
03-31 10:12:45.337  1832  1847 W GmsBackupTransport: 	at android.os.Binder.execTransact(Binder.java:446)
03-31 10:12:45.337  1832  1847 W GmsBackupTransport: Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
03-31 10:12:45.337  1832  1847 W GmsBackupTransport: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
03-31 10:12:45.337  1832  1847 W GmsBackupTransport: 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
03-31 10:12:45.337  1832  1847 W GmsBackupTransport: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
03-31 10:12:45.337  1832  1847 W GmsBackupTransport: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
03-31 10:12:45.337  1832  1847 W GmsBackupTransport: 	... 1 more
,03-31 10:12:45.368   822  1047 D BackupManagerService: Now staging backup of com.google.android.talk
,03-31 10:12:45.392   822  1047 D BackupManagerService: Now staging backup of com.google.android.dialer
,03-31 10:12:45.395   822  1047 D BackupManagerService: Now staging backup of com.android.providers.settings
,03-31 10:12:45.397   822  1047 D BackupManagerService: Now staging backup of com.android.sharedstoragebackup
,03-31 10:12:45.399   822  1047 D BackupManagerService: Now staging backup of com.google.android.gm
,03-31 10:12:45.401   822  1047 D BackupManagerService: Now staging backup of com.android.providers.userdictionary
,03-31 10:12:45.403   822  1047 D BackupManagerService: Now staging backup of com.android.nfc
,03-31 10:12:45.405   822  1047 D BackupManagerService: Now staging backup of com.google.android.apps.genie.geniewidget
,03-31 10:12:45.407   822  1047 D BackupManagerService: Now staging backup of com.google.android.marvin.talkback
,03-31 10:12:45.410   822  1047 D BackupManagerService: Now staging backup of com.google.android.inputmethod.latin
,03-31 10:12:45.416   822  1047 D BackupManagerService: Now staging backup of com.google.android.calendar
,03-31 10:12:45.427   822  1047 D BackupManagerService: Now staging backup of com.android.vending
,03-31 10:12:45.429  1804  3412 I SystemUpdateService: showing system update notification
,03-31 10:12:45.433   822  1047 D BackupManagerService: Now staging backup of android
,03-31 10:12:45.439   822  1047 D BackupManagerService: Now staging backup of com.google.android.googlequicksearchbox
,03-31 10:12:45.451  1804  3425 I iu.SyncManager: SYNC; picasa accounts
,03-31 10:12:45.456  1804  1804 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,03-31 10:12:45.458  1804  1804 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,03-31 10:12:45.464  1832  1847 I GmsBackupTransport: Next backup will happen in 43199872 millis.
,03-31 10:12:45.465  1804  3425 I iu.UploadsManager: num queued entries: 0
03-31 10:12:45.465  1804  3425 I iu.UploadsManager: num updated entries: 0
03-31 10:12:45.466  1804  3425 I iu.SyncManager: NEXT; no task
03-31 10:12:45.466   822  1047 I BackupManagerService: Backup pass finished.
,03-31 10:12:45.481   822   822 I ValidateNoPeople: skipping global notification
,03-31 10:12:45.489  1265  1720 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-31 10:12:45.489  1265  1720 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 10:12:45.489  1265  1720 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 10:12:45.489  1265  1720 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 10:12:45.492  1265  1720 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 10:12:45.503  3074  3407 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
03-31 10:12:45.503  3074  3407 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-31 10:12:45.503  3074  3407 E HttpOperation: 	at jdm.a(PG:82)
03-31 10:12:45.503  3074  3407 E HttpOperation: 	at jcs.o(PG:406)
03-31 10:12:45.503  3074  3407 E HttpOperation: 	at jcn.a(PG:1379)
03-31 10:12:45.503  3074  3407 E HttpOperation: 	at jcs.i(PG:143)
03-31 10:12:45.503  3074  3407 E HttpOperation: 	at blb.a(PG:3937)
03-31 10:12:45.503  3074  3407 E HttpOperation: 	at czp.a(PG:18188)
03-31 10:12:45.503  3074  3407 E HttpOperation: 	at czp.a(PG:9081)
03-31 10:12:45.503  3074  3407 E HttpOperation: 	at czq.run(PG:1686)
03-31 10:12:45.503  3074  3407 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-31 10:12:45.503  3074  3407 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-31 10:12:45.503  3074  3407 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 10:12:45.503  3074  3407 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 10:12:45.503  3074  3407 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-31 10:12:45.503  3074  3407 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-31 10:12:45.503  3074  3407 E HttpOperation: 	at jdj.a(PG:4091)
03-31 10:12:45.503  3074  3407 E HttpOperation: 	at jdj.a(PG:1125)
03-31 10:12:45.503  3074  3407 E HttpOperation: 	at jdm.a(PG:77)
03-31 10:12:45.503  3074  3407 E HttpOperation: 	... 12 more
03-31 10:12:45.503  3074  3407 E HttpOperation: Caused by: faj: BadAuthentication
03-31 10:12:45.503  3074  3407 E HttpOperation: 	at fal.a(PG:38)
03-31 10:12:45.503  3074  3407 E HttpOperation: 	at jdj.a(PG:4089)
03-31 10:12:45.503  3074  3407 E HttpOperation: 	... 14 more
,03-31 10:12:45.508  1804  3409 W DriveInitializer: Background init thread ended
,03-31 10:12:45.552  1265  3209 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,03-31 10:12:45.552  1265  3209 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 10:12:45.552  1265  3209 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 10:12:45.552  1265  3209 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 10:12:45.554  1265  3209 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 10:12:45.583   822   856 I ActivityManager: Start proc 3433:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,03-31 10:12:45.612  1804  1804 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
03-31 10:12:45.613  1804  1804 I Kids    : [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
,03-31 10:12:45.617  1265  1265 I art     : Explicit concurrent mark sweep GC freed 20079(1142KB) AllocSpace objects, 2(32KB) LOS objects, 38% free, 26MB/42MB, paused 828us total 29.973ms
,03-31 10:12:45.620  1804  1804 D SystemUpdateService: onDestroy
,03-31 10:12:45.639   822  1410 I ActivityManager: Start proc 3454:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,03-31 10:12:45.650  3074  3407 E HttpOperation: [getmobileexperiments] Unexpected exception
03-31 10:12:45.650  3074  3407 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-31 10:12:45.650  3074  3407 E HttpOperation: 	at jdm.a(PG:82)
03-31 10:12:45.650  3074  3407 E HttpOperation: 	at jcs.o(PG:406)
03-31 10:12:45.650  3074  3407 E HttpOperation: 	at jcn.a(PG:1379)
03-31 10:12:45.650  3074  3407 E HttpOperation: 	at jcs.i(PG:143)
03-31 10:12:45.650  3074  3407 E HttpOperation: 	at hec.a(PG:42)
03-31 10:12:45.650  3074  3407 E HttpOperation: 	at hee.a(PG:102)
03-31 10:12:45.650  3074  3407 E HttpOperation: 	at czr.a(PG:65)
03-31 10:12:45.650  3074  3407 E HttpOperation: 	at kka.a(PG:108)
03-31 10:12:45.650  3074  3407 E HttpOperation: 	at czp.a(PG:19176)
03-31 10:12:45.650  3074  3407 E HttpOperation: 	at czp.a(PG:9081)
03-31 10:12:45.650  3074  3407 E HttpOperation: 	at czq.run(PG:1686)
03-31 10:12:45.650  3074  3407 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-31 10:12:45.650  3074  3407 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-31 10:12:45.650  3074  3407 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 10:12:45.650  3074  3407 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 10:12:45.650  3074  3407 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-31 10:12:45.650  3074  3407 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-31 10:12:45.650  3074  3407 E HttpOperation: 	at jdj.a(PG:4091)
03-31 10:12:45.650  3074  3407 E HttpOperation: 	at jdj.a(PG:1125)
03-31 10:12:45.650  3074  3407 E HttpOperation: 	at jdm.a(PG:77)
03-31 10:12:45.650  3074  3407 E HttpOperation: 	... 15 more
03-31 10:12:45.650  3074  3407 E HttpOperation: Caused by: faj: BadAuthentication
03-31 10:12:45.650  3074  3407 E HttpOperation: 	at fal.a(PG:38)
03-31 10:12:45.650  3074  3407 E HttpOperation: 	at jdj.a(PG:4089)
03-31 10:12:45.650  3074  3407 E HttpOperation: 	... 17 more
03-31 10:12:45.651  3074  3407 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
03-31 10:12:45.651  3074  3407 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
03-31 10:12:45.651  3074  3407 E ExperimentLoader: 	at jdm.a(PG:82)
03-31 10:12:45.651  3074  3407 E ExperimentLoader: 	at jcs.o(PG:406)
03-31 10:12:45.651  3074  3407 E ExperimentLoader: 	at jcn.a(PG:1379)
03-31 10:12:45.651  3074  3407 E ExperimentLoader: 	at jcs.i(PG:143)
03-31 10:12:45.651  3074  3407 E ExperimentLoader: 	at hec.a(PG:42)
03-31 10:12:45.651  3074  3407 E ExperimentLoader: 	at hee.a(PG:102)
03-31 10:12:45.651  3074  3407 E ExperimentLoader: 	at czr.a(PG:65)
03-31 10:12:45.651  3074  3407 E ExperimentLoader: 	at kka.a(PG:108)
03-31 10:12:45.651  3074  3407 E ExperimentLoader: 	at czp.a(PG:19176)
03-31 10:12:45.651  3074  3407 E ExperimentLoader: 	at czp.a(PG:9081)
03-31 10:12:45.651  3074  3407 E ExperimentLoader: 	at czq.run(PG:1686)
03-31 10:12:45.651  3074  3407 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-31 10:12:45.651  3074  3407 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-31 10:12:45.651  3074  3407 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 10:12:45.651  3074  3407 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 10:12:45.651  3074  3407 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
03-31 10:12:45.651  3074  3407 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-31 10:12:45.651  3074  3407 E ExperimentLoader: 	at jdj.a(PG:4091)
03-31 10:12:45.651  3074  3407 E ExperimentLoader: 	at jdj.a(PG:1,125)
03-31 10:12:45.651  3074  3407 E ExperimentLoader: 	at jdm.a(PG:77)
03-31 10:12:45.651  3074  3407 E ExperimentLoader: 	... 15 more
03-31 10:12:45.651  3074  3407 E ExperimentLoader: Caused by: faj: BadAuthentication
03-31 10:12:45.651  3074  3407 E ExperimentLoader: 	at fal.a(PG:38)
03-31 10:12:45.651  3074  3407 E ExperimentLoader: 	at jdj.a(PG:4089)
03-31 10:12:45.651  3074  3407 E ExperimentLoader: 	... 17 more
,03-31 10:12:45.756  3454  3454 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
03-31 10:12:45.756  3454  3454 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-31 10:12:45.756  3454  3454 I GAv4    :   adb logcat -s GAv4
,03-31 10:12:45.768  3454  3454 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,03-31 10:12:45.784  1265  3448 D GCM     : Connected
,03-31 10:12:45.790  3454  3454 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,03-31 10:12:45.801  3454  3480 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,03-31 10:12:45.807  1265  3448 D GCM     : Message class com.google.f.a.a.p
,03-31 10:12:45.807   822   856 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 39532, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,03-31 10:12:45.814   822  1412 I ActivityManager: Killing 2897:com.android.settings/1000 (adj 15): empty #17
,03-31 10:12:45.836  3141  3453 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,03-31 10:12:45.873   822   841 I ActivityManager: Killing 2450:com.google.android.apps.maps/u0a65 (adj 15): empty #17
,03-31 10:12:46.021   822   856 I ActivityManager: Start proc 3484:com.google.android.keep/u0a79 for service com.google.android.keep/.syncadapter.KeepSyncAdapterService
,03-31 10:12:46.085  3433  3433 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,03-31 10:12:46.092  3433  3433 I BooksApp: Created application version: 3.6.8 (30608)
,03-31 10:12:46.150  3433  3518 I BooksSync: Starting books sync for 61035162, extras: ade
,03-31 10:12:46.203  3454  3454 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,03-31 10:12:46.218  3454  3454 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 1134-1135)
03-31 10:12:46.218  3454  3454 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-31 10:12:46.228  3454  3454 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1e792c0d}
,03-31 10:12:46.228  3454  3454 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-31 10:12:46.228  3454  3454 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,03-31 10:12:46.239  3454  3454 I BrowserStartupController: Initializing chromium process, singleProcess=true
03-31 10:12:46.240  3454  3454 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-31 10:12:46.240  3454  3454 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-31 10:12:46.249  3484  3528 V KeepSync: Connecting to GoogleApiClient
03-31 10:12:46.250  3454  3454 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,03-31 10:12:46.256  3454  3454 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-31 10:12:46.256  3454  3454 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-31 10:12:46.256  3454  3454 I Adreno  : EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,03-31 10:12:46.300  1804  3533 W BaseAppContext: Using Auth Proxy for data requests.
,03-31 10:12:46.305  1804  3533 W BaseAppContext: Using Auth Proxy for data requests.
,03-31 10:12:46.309  3433  3542 I BooksConfig: GmsCore Version = 7.8.99 (2134222-430)
,03-31 10:12:46.324  1265  1282 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
03-31 10:12:46.324  1265  1282 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 10:12:46.324  1265  1282 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 10:12:46.325  1265  1282 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 10:12:46.327  3454  3454 I NSApplication: Starting up...
,03-31 10:12:46.328  1265  1282 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 10:12:46.334  3454  3545 W AudioManagerAndroid: Requires BLUETOOTH permission
,03-31 10:12:46.341  1804  3533 E ClientConnectionOperation: Handling authorization failure
03-31 10:12:46.341  1804  3533 E ClientConnectionOperation: com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
03-31 10:12:46.341  1804  3533 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
03-31 10:12:46.341  1804  3533 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
03-31 10:12:46.341  1804  3533 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
03-31 10:12:46.341  1804  3533 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
03-31 10:12:46.341  1804  3533 E ClientConnectionOperation: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-31 10:12:46.341  1804  3533 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 10:12:46.341  1804  3533 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 10:12:46.341  1804  3533 E ClientConnectionOperation: 	at java.lang.Thread.run(Thread.java:818)
03-31 10:12:46.341  1804  3533 E ClientConnectionOperation: Caused by: com.google.android.gms.auth.ad: BadAuthentication
03-31 10:12:46.341  1804  3533 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.b(SourceFile:442)
03-31 10:12:46.341  1804  3533 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:365)
03-31 10:12:46.341  1804  3533 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:310)
03-31 10:12:46.341  1804  3533 E ClientConnectionOperation: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
03-31 10:12:46.341  1804  3533 E ClientConnectionOperation: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
03-31 10:12:46.341  1804  3533 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:30)
03-31 10:12:46.341  1804  3533 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:370)
03-31 10:12:46.341  1804  3533 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:340)
03-31 10:12:46.341  1804  3533 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:319)
03-31 10:12:46.341  1804  3533 E ClientConnectionOperation: 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
03-31 10:12:46.341  1804  3533 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
03-31 10:12:46.341  1804  3533 E ClientConnectionOperation: 	... 7 more
,03-31 10:12:46.366   822  1454 I ActivityManager: Start proc 3550:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,03-31 10:12:46.370  3484  3528 V KeepSync: GoogleApiClient failed to connect with error code: 4
03-31 10:12:46.371  3484  3528 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-31 10:12:46.382  3484  3528 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-31 10:12:46.384  3484  3528 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-31 10:12:46.397   822  1378 I art     : Explicit concurrent mark sweep GC freed 29830(1374KB) AllocSpace objects, 5(118KB) LOS objects, 32% free, 33MB/49MB, paused 1.321ms total 48.851ms
,03-31 10:12:46.422  1265  1902 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-31 10:12:46.422  1265  1902 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 10:12:46.422  1265  1902 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 10:12:46.422  1265  1902 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 10:12:46.425  1265  1902 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 10:12:46.476  1265  3209 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-31 10:12:46.476  1265  3209 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 10:12:46.476  1265  3209 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 10:12:46.476  1265  3209 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 10:12:46.479  1265  3209 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 10:12:46.507  1265  3209 I art     : Explicit concurrent mark sweep GC freed 11773(624KB) AllocSpace objects, 3(330KB) LOS objects, 38% free, 26MB/42MB, paused 1.023ms total 20.550ms
,03-31 10:12:46.511  3433  3542 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,03-31 10:12:46.514  3433  3518 E BooksSync: Soft error
03-31 10:12:46.514  3433  3518 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-31 10:12:46.514  3433  3518 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,03-31 10:12:46.514  3433  3518 E BooksSync: Sync error
03-31 10:12:46.514  3433  3518 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-31 10:12:46.514  3433  3518 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-31 10:12:46.514  3433  3518 I BooksSync: Finished books sync
,03-31 10:12:46.521   822  1201 I ActivityManager: Killing 2981:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,03-31 10:12:46.525  1265  1719 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
03-31 10:12:46.525  1265  1719 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 10:12:46.525  1265  1719 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 10:12:46.525  1265  1719 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 10:12:46.527   822   856 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 39539, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-31 10:12:46.576  1265  1719 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 10:12:46.614  3484  3528 E KeepSync: IOException
03-31 10:12:46.614  3484  3528 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
03-31 10:12:46.614  3484  3528 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
03-31 10:12:46.614  3484  3528 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
03-31 10:12:46.614  3484  3528 E KeepSync: 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
03-31 10:12:46.614  3484  3528 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
03-31 10:12:46.614  3484  3528 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
03-31 10:12:46.614  3484  3528 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
03-31 10:12:46.614  3484  3528 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
03-31 10:12:46.614  3484  3528 E KeepSync: 	at com.google.android.keep.util.m.a(SourceFile:207)
03-31 10:12:46.614  3484  3528 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
03-31 10:12:46.614  3484  3528 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
03-31 10:12:46.614  3484  3528 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
03-31 10:12:46.614  3484  3528 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
03-31 10:12:46.614  3484  3528 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
03-31 10:12:46.614  3484  3528 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
03-31 10:12:46.614  3484  3528 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
03-31 10:12:46.614  3484  3528 E KeepSync: 	... 10 more
03-31 10:12:46.614  3484  3528 W KeepSync: Sync result 2
,03-31 10:12:46.622   822   840 I ActivityManager: Killing 3001:com.android.musicfx/u0a18 (adj 15): empty #17
,03-31 10:12:46.623   822   856 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 39539, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-31 10:12:46.738  1804  3570 I PeopleSync: onPerformSync() [5005f081]
,03-31 10:12:46.800  1804  3574 I PeopleDatabaseHelper: cleanUpNonGplusAccounts done.
,03-31 10:12:46.826   822  1410 I ActivityManager: Start proc 3577:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
03-31 10:12:46.827   822  1410 I ActivityManager: Killing 3030:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,03-31 10:12:46.905  1265  1265 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 10:12:46.984  1804  3570 I PeopleSync: Setting subscription: result=true [5005f081]
,03-31 10:12:46.990  1804  3570 I PeopleSync: Starting sync, feed=null [5005f081]
,03-31 10:12:47.023  1804  3570 W BaseAppContext: Using Auth Proxy for data requests.
,03-31 10:12:47.029  1804  3570 W BaseAppContext: Using Auth Proxy for data requests.
,03-31 10:12:47.042  1804  3570 W BaseAppContext: Using Auth Proxy for data requests.
,03-31 10:12:47.052  1804  3570 I PeopleSync: Sync start: cannotHavePeople=true isPageExistenceCheckOnly=false
,03-31 10:12:47.091  1265  3209 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.media.upload https://www.googleapis.com/auth/plus.pages.manage https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.profiles.read https://www.googleapis.com/auth/plus.profiles.write https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/plus.applications.manage https://www.googleapis.com/auth/plus.settings
,03-31 10:12:47.091  1265  3209 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.media.upload https://www.googleapis.com/auth/plus.pages.manage https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.profiles.read https://www.googleapis.com/auth/plus.profiles.write https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/plus.applications.manage https://www.googleapis.com/auth/plus.settings without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 10:12:47.091  1265  3209 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 10:12:47.092  1265  3209 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 10:12:47.095  1265  3209 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 10:12:47.110  1804  3570 I PeopleSync: Sync finished, successful=false, took 53ms
,03-31 10:12:47.123  1804  3570 I PeopleSync: Cannot authenticate [5005f081]
03-31 10:12:47.123  1804  3570 I PeopleSync: com.google.android.gms.auth.ad: BadAuthentication
03-31 10:12:47.123  1804  3570 I PeopleSync: 	at com.google.android.gms.auth.p.b(SourceFile:442)
03-31 10:12:47.123  1804  3570 I PeopleSync: 	at com.google.android.gms.auth.p.a(SourceFile:365)
03-31 10:12:47.123  1804  3570 I PeopleSync: 	at com.google.android.gms.auth.p.a(SourceFile:310)
03-31 10:12:47.123  1804  3570 I PeopleSync: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
03-31 10:12:47.123  1804  3570 I PeopleSync: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
03-31 10:12:47.123  1804  3570 I PeopleSync: 	at com.google.android.gms.common.server.o.b(SourceFile:30)
03-31 10:12:47.123  1804  3570 I PeopleSync: 	at com.google.android.gms.people.service.g.b(SourceFile:171)
03-31 10:12:47.123  1804  3570 I PeopleSync: 	at com.google.android.gms.common.server.o.b(SourceFile:370)
03-31 10:12:47.123  1804  3570 I PeopleSync: 	at com.google.android.gms.common.server.o.a(SourceFile:340)
03-31 10:12:47.123  1804  3570 I PeopleSync: 	at com.google.android.gms.common.server.o.a(SourceFile:319)
03-31 10:12:47.123  1804  3570 I PeopleSync: 	at com.google.android.gms.plus.service.v2whitelisted.b.a(SourceFile:1184)
03-31 10:12:47.123  1804  3570 I PeopleSync: 	at com.google.android.gms.people.sync.aa.g(SourceFile:1086)
03-31 10:12:47.123  1804  3570 I PeopleSync: 	at com.google.android.gms.people.sync.aa.a(SourceFile:241)
03-31 10:12:47.123  1804  3570 I PeopleSync: 	at com.google.android.gms.people.sync.s.a(SourceFile:283)
03-31 10:12:47.123  1804  3570 I PeopleSync: 	at com.google.android.gms.people.sync.s.a(SourceFile:191)
03-31 10:12:47.123  1804  3570 I PeopleSync: 	at com.google.android.gms.people.sync.s.a(SourceFile:93)
03-31 10:12:47.123  1804  3570 I PeopleSync: 	at com.google.android.gms.common.j.a.onPerformSync(SourceFile:81)
03-31 10:12:47.123  1804  3570 I PeopleSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,03-31 10:12:47.188  1804  3570 I PeopleSync: ***Sync finished***, duration: 446 [5005f081]
,03-31 10:12:47.204   822   856 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.gms.people, PERIODIC, currentRunTime 43693, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,03-31 10:12:47.205   822  1201 I ActivityManager: Killing 1462:android.process.acore/u0a5 (adj 15): empty #17
03-31 10:12:47.206   822   856 D SyncManager: not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.gms.people, PERIODIC, currentRunTime 203396, reason: Periodic
,03-31 10:12:47.590   822  1412 I ActivityManager: Killing 2792:com.google.android.gm/u0a78 (adj 15): empty #17
,03-31 10:12:47.763   822  1429 I ActivityManager: Start proc 3596:com.qualcomm.timeservice/1000 for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver
,03-31 10:12:47.810  3596  3596 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1459411967810
03-31 10:12:47.811  3596  3596 D         : TimeServiceNative: User Time to be set is 1459411967811
03-31 10:12:47.811  3596  3596 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
03-31 10:12:47.811  3596  3596 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
03-31 10:12:47.811  3596  3596 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1459411967811
03-31 10:12:47.811  3596  3596 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
03-31 10:12:47.811   372   881 D QC-time-services: Daemon: Connection accepted:time_genoff
03-31 10:12:47.811   372  3614 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1459411967811
03-31 10:12:47.811   372  3614 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1459411967811, operation = 0
,03-31 10:12:47.811   372  3614 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS7/17/70 4:24:26
03-31 10:12:47.811   372  3614 D QC-time-services: Daemon:Value read from RTC seconds = 19715066000
03-31 10:12:47.811   372  3614 D QC-time-services: Daemon:new time 1459411967811 
03-31 10:12:47.811   372  3614 D QC-time-services: Daemon: delta 1439696901811 genoff 1439696901811 
03-31 10:12:47.811   372  3614 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1439696901811 to memory
03-31 10:12:47.811   372  3614 D QC-time-services: Daemon:Opening File: /data/time/ats_2
03-31 10:12:47.811   372  3614 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,03-31 10:12:47.816   372  3614 D QC-time-services: Updating the TOD offset
03-31 10:12:47.816   372  3614 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1439696901811 to memory
03-31 10:12:47.816   372  3614 D QC-time-services: Daemon:Opening File: /data/time/ats_1
03-31 10:12:47.816   372  3614 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,03-31 10:12:47.818   372  3614 E QC-time-services: Daemon:Update to modem bit set
03-31 10:12:47.818  3596  3596 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
03-31 10:12:47.818   372  3614 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
03-31 10:12:47.818   372  3614 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1143447167811
,03-31 10:12:47.889   372   881 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,03-31 10:12:47.895   372   879 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,03-31 10:12:47.936   822  1410 I ActivityManager: Start proc 3616:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver
,03-31 10:12:47.950   822   840 I ActivityManager: Killing 1876:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,03-31 10:12:48.205  3616  3616 I GAv4    : Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
03-31 10:12:48.205  3616  3616 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-31 10:12:48.205  3616  3616 I GAv4    :   adb logcat -s GAv4
,03-31 10:12:48.219  3616  3616 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,03-31 10:12:48.230  3616  3616 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,03-31 10:12:48.243  3616  3635 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,03-31 10:12:48.329   822  1201 I ActivityManager: Killing 3112:com.android.providers.calendar/u0a3 (adj 15): empty #17
,03-31 10:12:48.685  3141  3141 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-31 10:12:48.686  3141  3141 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-31 10:12:48.693   822  1014 D WifiService: New client listening to asynchronous messages
,03-31 10:12:48.745   822  1378 I ActivityManager: Start proc 3645:com.android.providers.calendar/u0a3 for content provider com.android.providers.calendar/.CalendarProvider2
,03-31 10:12:48.746  1804  1804 I art     : Explicit concurrent mark sweep GC freed 17056(1131KB) AllocSpace objects, 11(176KB) LOS objects, 35% free, 29MB/45MB, paused 1.321ms total 65.246ms
,03-31 10:12:48.751  1804  1804 V Herrevad: NQAS connected
,03-31 10:12:48.769  3645  3645 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,03-31 10:12:48.813  3645  3645 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@2e37de49(com.android.providers.calendar.CalendarProvider2@28fa134e)
,03-31 10:12:48.892   822  1449 I art     : Explicit concurrent mark sweep GC freed 21099(979KB) AllocSpace objects, 4(64KB) LOS objects, 32% free, 33MB/49MB, paused 864us total 44.577ms
,03-31 10:12:48.902  1265  1282 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
,03-31 10:12:48.902  1265  1282 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 10:12:48.902  1265  1282 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 10:12:48.902  1265  1282 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 10:12:48.905  1265  1282 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-31 10:12:48.912  3141  3641 E Babel   : UserRecoverableAuthException.
,03-31 10:12:48.912  3141  3641 E Babel   : eei: BadAuthentication
03-31 10:12:48.912  3141  3641 E Babel   : 	at eeg.a(Unknown Source)
03-31 10:12:48.912  3141  3641 E Babel   : 	at eeg.a(Unknown Source)
03-31 10:12:48.912  3141  3641 E Babel   : 	at eeg.a(Unknown Source)
03-31 10:12:48.912  3141  3641 E Babel   : 	at g.a(Unknown Source)
03-31 10:12:48.912  3141  3641 E Babel   : 	at cae.a(SourceFile:3089)
03-31 10:12:48.912  3141  3641 E Babel   : 	at cae.a(SourceFile:1131)
03-31 10:12:48.912  3141  3641 E Babel   : 	at cws.a(SourceFile:4333)
03-31 10:12:48.912  3141  3641 E Babel   : 	at cws.a(SourceFile:1419)
03-31 10:12:48.912  3141  3641 E Babel   : 	at crl.a(SourceFile:492)
03-31 10:12:48.912  3141  3641 E Babel   : 	at crl.a(SourceFile:1468)
03-31 10:12:48.912  3141  3641 E Babel   : 	at cqu.a(SourceFile:4416)
03-31 10:12:48.912  3141  3641 E Babel   : 	at cas.b(SourceFile:106)
03-31 10:12:48.912  3141  3641 E Babel   : 	at cap.d(SourceFile:335)
03-31 10:12:48.912  3141  3641 E Babel   : 	at caq.run(SourceFile:81)
03-31 10:12:48.912  3141  3641 E Babel   : Error getting auth token
03-31 10:12:48.913  3141  3641 E Babel   : dvm
03-31 10:12:48.913  3141  3641 E Babel   : 	at g.a(Unknown Source)
03-31 10:12:48.913  3141  3641 E Babel   : 	at cae.a(SourceFile:3089)
03-31 10:12:48.913  3141  3641 E Babel   : 	at cae.a(SourceFile:1131)
03-31 10:12:48.913  3141  3641 E Babel   : 	at cws.a(SourceFile:4333)
03-31 10:12:48.913  3141  3641 E Babel   : 	at cws.a(SourceFile:1419)
03-31 10:12:48.913  3141  3641 E Babel   : 	at crl.a(SourceFile:492)
03-31 10:12:48.913  3141  3641 E Babel   : 	at crl.a(SourceFile:1468)
03-31 10:12:48.913  3141  3641 E Babel   : 	at cqu.a(SourceFile:4416)
03-31 10:12:48.913  3141  3641 E Babel   : 	at cas.b(SourceFile:106)
03-31 10:12:48.913  3141  3641 E Babel   : 	at cap.d(SourceFile:335)
03-31 10:12:48.913  3141  3641 E Babel   : 	at caq.run(SourceFile:81)
,03-31 10:12:48.915  3141  3641 E Babel   : Account registration failed 1-Redacted-21
,03-31 10:12:48.916  3141  3641 E Babel   : cyp: null -- null
03-31 10:12:48.916  3141  3641 E Babel   : 	at cae.a(SourceFile:3121)
03-31 10:12:48.916  3141  3641 E Babel   : 	at cae.a(SourceFile:1131)
03-31 10:12:48.916  3141  3641 E Babel   : 	at cws.a(SourceFile:4333)
03-31 10:12:48.916  3141  3641 E Babel   : 	at cws.a(SourceFile:1419)
03-31 10:12:48.916  3141  3641 E Babel   : 	at crl.a(SourceFile:492)
03-31 10:12:48.916  3141  3641 E Babel   : 	at crl.a(SourceFile:1468)
03-31 10:12:48.916  3141  3641 E Babel   : 	at cqu.a(SourceFile:4416)
03-31 10:12:48.916  3141  3641 E Babel   : 	at cas.b(SourceFile:106)
03-31 10:12:48.916  3141  3641 E Babel   : 	at cap.d(SourceFile:335)
03-31 10:12:48.916  3141  3641 E Babel   : 	at caq.run(SourceFile:81)
,03-31 10:12:48.922  3141  3641 I art     : Note: end time exceeds epoch: 
,03-31 10:12:48.936  1265  1719 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
,03-31 10:12:48.936  1265  1719 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 10:12:48.936  1265  1719 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 10:12:48.937  1265  1719 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 10:12:48.939  1265  1719 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 10:12:48.948  1265  1719 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-31 10:12:48.965  3141  3671 E Babel   : Unexpected exception while authenticating.
03-31 10:12:48.965  3141  3671 E Babel   : eej: User intervention required. Notification has been pushed.
03-31 10:12:48.965  3141  3671 E Babel   : 	at eeg.b(Unknown Source)
03-31 10:12:48.965  3141  3671 E Babel   : 	at eeg.b(Unknown Source)
03-31 10:12:48.965  3141  3671 E Babel   : 	at g.a(Unknown Source)
03-31 10:12:48.965  3141  3671 E Babel   : 	at cae.b(SourceFile:1146)
03-31 10:12:48.965  3141  3671 E Babel   : 	at dcg.run(SourceFile:5617)
03-31 10:12:48.965  3141  3671 E Babel   : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 10:12:48.965  3141  3671 E Babel   : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 10:12:48.965  3141  3671 E Babel   : 	at java.lang.Thread.run(Thread.java:818)
,03-31 10:12:49.864  3645  3645 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,03-31 10:12:49.864  3645  3645 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,03-31 10:12:50.127  3645  3674 E SQLiteLog: (284) automatic index on view_events(_id)
,03-31 10:12:51.103  3433  3512 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,03-31 10:12:52.200  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 10:12:52.200  3253  3312 I jxcore-log: 
,03-31 10:12:52.202  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 10:12:52.202  3253  3312 I jxcore-log: 
,03-31 10:12:52.210  3253  3312 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 10:12:52.210  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 10:12:52.210  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 10:12:52.210  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 10:12:52.210  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true,
03-31 10:12:52.210  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 10:12:52.210  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 10:12:52.210  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 10:12:52.215  3253  3312 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 10:12:52.217  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 10:12:52.217  3253  3312 I jxcore-log: 
,03-31 10:12:52.219  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 10:12:52.219  3253  3312 I jxcore-log: 
,03-31 10:12:52.736  3253  3312 I jxcore-log: Unit Test app is loaded
03-31 10:12:52.736  3253  3312 I jxcore-log: 
,03-31 10:12:52.742  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 10:12:52.742  3253  3312 I jxcore-log: 
,03-31 10:12:52.756  3253  3312 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,03-31 10:12:52.757  3253  3253 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
03-31 10:12:52.758  3253  3312 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
03-31 10:12:52.758  3253  3312 I jxcore-log: 
,03-31 10:12:52.761  3253  3312 I jxcore-log: My device name is: motorola-Nexus 6
,03-31 10:12:52.761  3253  3312 I jxcore-log: 
,03-31 10:12:55.089   822  1410 I ActivityManager: Killing 2730:com.android.vending/u0a19 (adj 15): empty #17
,03-31 10:12:55.300   822  1410 E libprocessgroup: failed to kill 1 processes for processgroup 2730
,03-31 10:12:56.230   822  1378 I ActivityManager: Start proc 3678:com.android.vending/u0a19 for service com.android.vending/com.google.android.finsky.services.ContentFiltersService
,03-31 10:12:56.381  3678  3678 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,03-31 10:12:56.495  3678  3678 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,03-31 10:12:56.540  3253  3312 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
03-31 10:12:56.540  3253  3312 I jxcore-log: 
,03-31 10:12:56.589   822  1384 I ActivityManager: Start proc 3714:com.google.android.gms:car/u0a11 for service com.google.android.gms/.car.CarService
,03-31 10:12:56.611  3678  3678 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-31 10:12:56.618  3678  3678 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-31 10:12:56.634  3714  3714 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,03-31 10:12:56.634  3714  3714 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-31 10:12:56.662   822  1454 I ActivityManager: Killing 1514:com.google.android.googlequicksearchbox:search/u0a28 (adj 15): empty #17
,03-31 10:12:56.666  3714  3714 I MultiDex: VM with version 2.1.0 has multidex support
03-31 10:12:56.666  3714  3714 I MultiDex: install
03-31 10:12:56.666  3714  3714 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,03-31 10:12:56.670  3678  3693 D Finsky  : [374] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,03-31 10:12:56.795   822  1014 D WifiService: Client connection lost with reason: 4
,03-31 10:12:56.877  3678  3678 D Finsky  : [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
03-31 10:12:56.877  3678  3678 D Finsky  : [1] 2.run: Finished loading 1 libraries.
,03-31 10:12:56.878  1265  1265 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 10:12:56.911  3714  3714 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,03-31 10:12:56.913  1265  1719 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
03-31 10:12:56.913  1265  1719 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 10:12:56.913  1265  1719 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 10:12:56.914  1265  1719 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 10:12:56.916  1265  1719 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 10:12:56.920  3253  3312 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
03-31 10:12:56.920  3253  3312 I jxcore-log: 
,03-31 10:12:56.933  3253  3312 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
03-31 10:12:56.933  3253  3312 I jxcore-log: 
,03-31 10:12:56.937  3253  3312 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
03-31 10:12:56.937  3253  3312 I jxcore-log: 
,03-31 10:12:56.945  3678  3678 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,03-31 10:12:56.946  1265  1719 I art     : Explicit concurrent mark sweep GC freed 14255(894KB) AllocSpace objects, 3(330KB) LOS objects, 37% free, 26MB/42MB, paused 730us total 26.091ms
,03-31 10:12:56.964  3678  3693 D Finsky  : [374] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,03-31 10:12:56.965  3678  3678 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,03-31 10:12:56.971  3714  3714 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-31 10:12:56.976  1265  2110 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,03-31 10:12:56.981  1265  1265 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-31 10:12:56.985  3253  3312 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
03-31 10:12:56.985  3253  3312 I jxcore-log: 
,03-31 10:12:56.985  1804  1804 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,03-31 10:12:57.003  3253  3312 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
03-31 10:12:57.003  3253  3312 I jxcore-log: 
03-31 10:12:57.007  3253  3312 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
03-31 10:12:57.007  3253  3312 I jxcore-log: 
,03-31 10:12:57.011   822  1454 I ActivityManager: Start proc 3742:com.google.android.gms.wearable/u0a11 for service com.google.android.gms/.wearable.service.WearableService
,03-31 10:12:57.028   369   369 I art     : Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 21MB/36MB, paused 337us total 15.628ms
,03-31 10:12:57.035  3742  3742 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-31 10:12:57.035  3742  3742 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-31 10:12:57.039   369   369 I art     : Explicit concurrent mark sweep GC freed 7(224B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 232us total 11.048ms
,03-31 10:12:57.050   369   369 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 243us total 9.521ms
,03-31 10:12:57.053  3742  3742 I MultiDex: VM with version 2.1.0 has multidex support
03-31 10:12:57.053  3742  3742 I MultiDex: install
03-31 10:12:57.053  3742  3742 I MultiDex: VM has multidex support, MultiDex support library is disabled.
03-31 10:12:57.054  1804  3757 D LocationInitializer: Restart initialization of location
,03-31 10:12:57.072  3742  3742 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,03-31 10:12:57.116  3742  3742 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-31 10:12:57.123  1265  2113 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,03-31 10:12:57.125  1265  1265 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-31 10:12:57.128  3742  3764 W NativeLibraryUtils: Install did not work
03-31 10:12:57.128  3742  3764 W NativeLibraryUtils: java.io.IOException: fcntl failed: EAGAIN (Try again)
03-31 10:12:57.128  3742  3764 W NativeLibraryUtils: 	at java.nio.FileChannelImpl.basicLock(FileChannelImpl.java:123)
03-31 10:12:57.128  3742  3764 W NativeLibraryUtils: 	at java.nio.FileChannelImpl.tryLock(FileChannelImpl.java:181)
03-31 10:12:57.128  3742  3764 W NativeLibraryUtils: 	at java.nio.channels.FileChannel.tryLock(FileChannel.java:584)
03-31 10:12:57.128  3742  3764 W NativeLibraryUtils: 	at com.google.android.gms.common.util.ax.a(SourceFile:314)
03-31 10:12:57.128  3742  3764 W NativeLibraryUtils: 	at com.google.android.gms.common.app.a.run(SourceFile:136)
03-31 10:12:57.128  3742  3764 W NativeLibraryUtils: Caused by: android.system.ErrnoException: fcntl failed: EAGAIN (Try again)
03-31 10:12:57.128  3742  3764 W NativeLibraryUtils: 	at libcore.io.Posix.fcntlFlock(Native Method)
03-31 10:12:57.128  3742  3764 W NativeLibraryUtils: 	at libcore.io.ForwardingOs.fcntlFlock(ForwardingOs.java:70)
03-31 10:12:57.128  3742  3764 W NativeLibraryUtils: 	at java.nio.FileChannelImpl.basicLock(FileChannelImpl.java:121)
03-31 10:12:57.128  3742  3764 W NativeLibraryUtils: 	... 4 more
,03-31 10:12:57.131  1804  1804 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,03-31 10:12:57.133  3742  3742 D WearableService: callingUid 10011, callindPid: 3742
,03-31 10:12:57.148  1804  3765 D LocationInitializer: Restart initialization of location
,03-31 10:12:57.151  1832  2071 E MDM     : [144] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,03-31 10:12:57.154  1832  2071 E MDM     : [144] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,03-31 10:12:57.255  3678  3678 V Finsky  : [1] GearheadStateMonitor.onReady: sIsProjecting:false
,03-31 10:12:57.511  3678  3678 D Finsky  : [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,03-31 10:12:57.582   822  1002 I ActivityManager: Start proc 3771:com.google.android.googlequicksearchbox:search/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.voicesearch.logger.EventLoggerService
,03-31 10:12:57.591  1265  1265 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 10:12:57.626  1265  2559 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
03-31 10:12:57.626  1265  2559 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 10:12:57.626  1265  2559 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 10:12:57.626  1265  2559 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 10:12:57.630  1265  2559 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 10:12:57.648  3678  3678 W Finsky  : [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,03-31 10:12:57.656  1265  1265 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 10:12:57.678  1265  1720 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,03-31 10:12:57.678  1265  1720 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 10:12:57.679  1265  1720 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 10:12:57.679  1265  1720 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 10:12:57.682  1265  1720 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 10:12:57.705  1265  1265 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 10:12:57.731  1265  1719 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,03-31 10:12:57.731  1265  1719 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 10:12:57.731  1265  1719 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 10:12:57.731  1265  1719 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 10:12:57.734  1265  1719 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 10:12:57.748  3678  3678 W Finsky  : [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,03-31 10:12:57.875   822  1429 I ActivityManager: Start proc 3795:com.google.android.partnersetup/u0a16 for content provider com.google.android.partnersetup/.RlzAppProvider
,03-31 10:12:57.969  1265  1265 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 10:12:57.987  1265  2559 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,03-31 10:12:57.987  1265  2559 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 10:12:57.987  1265  2559 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 10:12:57.987  1265  2559 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 10:12:57.990  1265  2559 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 10:12:58.069   822  1412 I art     : Explicit concurrent mark sweep GC freed 17902(853KB) AllocSpace objects, 3(236KB) LOS objects, 32% free, 33MB/49MB, paused 2.342ms total 72.994ms
,03-31 10:12:58.084  3678  3678 W Finsky  : [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,03-31 10:12:58.087  3678  3678 D Finsky  : [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,03-31 10:12:58.097  3678  3678 D Finsky  : [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,03-31 10:12:58.100  3678  3678 D Finsky  : [1] DailyHygiene.reschedule: Scheduling new run in 762 minutes (failures=5)
,03-31 10:12:58.112  1832  1847 D DeviceConnectionService: client connected with version: 7571000
,03-31 10:12:58.116   822  1454 I ActivityManager: Killing 3389:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,03-31 10:12:58.325   822  1454 I ActivityManager: Killing 2916:com.google.android.music:main/u0a66 (adj 15): empty #18
,03-31 10:12:58.953  2153  2218 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-31 10:12:59.132  3253  3312 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
03-31 10:12:59.132  3253  3312 I jxcore-log: 
,03-31 10:12:59.148  3253  3312 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
03-31 10:12:59.148  3253  3312 I jxcore-log: 
,03-31 10:12:59.157  3253  3312 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
03-31 10:12:59.157  3253  3312 I jxcore-log: 
,03-31 10:12:59.406  3253  3312 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
03-31 10:12:59.406  3253  3312 I jxcore-log: 
,03-31 10:12:59.476  3253  3312 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
03-31 10:12:59.476  3253  3312 I jxcore-log: 
,03-31 10:12:59.531  3253  3312 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
03-31 10:12:59.531  3253  3312 I jxcore-log: 
,03-31 10:12:59.538  3253  3312 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
03-31 10:12:59.538  3253  3312 I jxcore-log: 
,03-31 10:12:59.548  3253  3312 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
03-31 10:12:59.548  3253  3312 I jxcore-log: 
,03-31 10:12:59.553  3253  3312 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
03-31 10:12:59.553  3253  3312 I jxcore-log: 
,03-31 10:12:59.559  3253  3312 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
03-31 10:12:59.559  3253  3312 I jxcore-log: 
,03-31 10:12:59.575  3253  3312 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
03-31 10:12:59.575  3253  3312 I jxcore-log: 
,03-31 10:12:59.594  3253  3312 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
03-31 10:12:59.594  3253  3312 I jxcore-log: 
,03-31 10:12:59.677  3253  3312 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
03-31 10:12:59.677  3253  3312 I jxcore-log: 
,03-31 10:12:59.683  3253  3312 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
03-31 10:12:59.683  3253  3312 I jxcore-log: 
,03-31 10:12:59.709  3253  3312 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
03-31 10:12:59.709  3253  3312 I jxcore-log: 
,03-31 10:13:00.874  3253  3312 I jxcore-log: TAP version 13
03-31 10:13:00.874  3253  3312 I jxcore-log: 
,03-31 10:13:00.878  3253  3312 I jxcore-log: # setup
03-31 10:13:00.878  3253  3312 I jxcore-log: 
,03-31 10:13:01.035  3253  3312 I jxcore-log: # 1. calling createNativeListener directly rejects
03-31 10:13:01.035  3253  3312 I jxcore-log: 
,03-31 10:13:01.551  3253  3312 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 10:13:01.551  3253  3312 I jxcore-log: 
,03-31 10:13:01.556  3253  3312 I jxcore-log: DEBUG createNativeListener: listening 49747
03-31 10:13:01.556  3253  3312 I jxcore-log: 
,03-31 10:13:01.562  3253  3312 I jxcore-log: ok 1 Should throw
03-31 10:13:01.562  3253  3312 I jxcore-log: 
,03-31 10:13:01.565  3253  3312 I jxcore-log: # teardown
03-31 10:13:01.565  3253  3312 I jxcore-log: 
,03-31 10:13:01.712  3253  3312 I jxcore-log: # setup
03-31 10:13:01.712  3253  3312 I jxcore-log: 
,03-31 10:13:01.828  3253  3312 I jxcore-log: # 2. emits incomingConnectionState
03-31 10:13:01.828  3253  3312 I jxcore-log: 
,03-31 10:13:01.932  3253  3312 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 10:13:01.932  3253  3312 I jxcore-log: 
03-31 10:13:01.936  3253  3312 I jxcore-log: DEBUG createNativeListener: listening 42620
03-31 10:13:01.936  3253  3312 I jxcore-log: 
,03-31 10:13:01.946  3253  3312 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 10:13:01.946  3253  3312 I jxcore-log: 
,03-31 10:13:01.950  3253  3312 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 10:13:01.950  3253  3312 I jxcore-log: 
,03-31 10:13:01.959  3253  3312 I jxcore-log: DEBUG createNativeListener: new mux
03-31 10:13:01.959  3253  3312 I jxcore-log: 
,03-31 10:13:01.965  3253  3312 I jxcore-log: ok 2 initial connection state should be CONNECTED
03-31 10:13:01.965  3253  3312 I jxcore-log: 
,03-31 10:13:01.979  3253  3312 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 10:13:01.979  3253  3312 I jxcore-log: 
,03-31 10:13:01.980  3253  3312 I jxcore-log: ok 3 final connection state should be DISCONNECTED
03-31 10:13:01.980  3253  3312 I jxcore-log: 
,03-31 10:13:01.989  3253  3312 I jxcore-log: # teardown
03-31 10:13:01.989  3253  3312 I jxcore-log: 
,03-31 10:13:02.064  3253  3312 I jxcore-log: # setup
03-31 10:13:02.064  3253  3312 I jxcore-log: 
,03-31 10:13:02.176   822   841 I ActivityManager: Killing 3454:com.google.android.apps.magazines/u0a67 (adj 15): empty #17
,03-31 10:13:02.257  3253  3312 I jxcore-log: # 3. emits routerPortConnectionFailed,
03-31 10:13:02.257  3253  3312 I jxcore-log: 
,03-31 10:13:02.408   822  1104 I ActivityManager: Killing 3550:com.android.chrome/u0a40 (adj 15): empty #17
,03-31 10:13:02.440  3253  3312 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 10:13:02.440  3253  3312 I jxcore-log: 
,03-31 10:13:02.442  3253  3312 I jxcore-log: DEBUG createNativeListener: listening 41938
03-31 10:13:02.442  3253  3312 I jxcore-log: 
,03-31 10:13:02.448  3253  3312 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 10:13:02.448  3253  3312 I jxcore-log: 
,03-31 10:13:02.449  3253  3312 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 10:13:02.449  3253  3312 I jxcore-log: 
,03-31 10:13:02.451  3253  3312 I jxcore-log: DEBUG createNativeListener: new mux
03-31 10:13:02.451  3253  3312 I jxcore-log: 
,03-31 10:13:02.476  3253  3312 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 10:13:02.476  3253  3312 I jxcore-log: 
,03-31 10:13:02.478  3253  3312 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 10:13:02.478  3253  3312 I jxcore-log: 
,03-31 10:13:02.482  3253  3312 I jxcore-log: DEBUG createNativeListener: 
03-31 10:13:02.482  3253  3312 I jxcore-log: 
,03-31 10:13:02.483  3253  3312 I jxcore-log: ok 4 tried to connect to right port
03-31 10:13:02.483  3253  3312 I jxcore-log: 
,03-31 10:13:02.484  3253  3312 I jxcore-log: ok 5 failed due to refused connection
03-31 10:13:02.484  3253  3312 I jxcore-log: 
,03-31 10:13:02.485  3253  3312 I jxcore-log: ok 6 routerPortConnectionFailed is emitted
03-31 10:13:02.485  3253  3312 I jxcore-log: 
03-31 10:13:02.488  3253  3312 I jxcore-log: # teardown
03-31 10:13:02.488  3253  3312 I jxcore-log: 
03-31 10:13:02.490  3253  3312 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 10:13:02.490  3253  3312 I jxcore-log: 
,03-31 10:13:02.649  3253  3312 I jxcore-log: DEBUG createNativeListener: mux close
03-31 10:13:02.649  3253  3312 I jxcore-log: 
,03-31 10:13:02.654  3253  3312 I jxcore-log: # setup
03-31 10:13:02.654  3253  3312 I jxcore-log: 
,03-31 10:13:02.656  3253  3312 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 10:13:02.656  3253  3312 I jxcore-log: 
,03-31 10:13:02.764  2153  2218 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-31 10:13:02.787  3253  3312 I jxcore-log: # 4. native server connections all up
03-31 10:13:02.787  3253  3312 I jxcore-log: 
,03-31 10:13:02.891  3253  3312 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 10:13:02.891  3253  3312 I jxcore-log: 
,03-31 10:13:02.903  3253  3312 I jxcore-log: DEBUG createNativeListener: listening 56619
03-31 10:13:02.903  3253  3312 I jxcore-log: 
,03-31 10:13:02.911  3253  3312 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 10:13:02.911  3253  3312 I jxcore-log: 
,03-31 10:13:02.912  3253  3312 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 10:13:02.912  3253  3312 I jxcore-log: 
,03-31 10:13:02.914  3253  3312 I jxcore-log: DEBUG createNativeListener: new mux
03-31 10:13:02.914  3253  3312 I jxcore-log: 
,03-31 10:13:02.942  3253  3312 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 10:13:02.942  3253  3312 I jxcore-log: 
,03-31 10:13:02.945  3253  3312 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 10:13:02.945  3253  3312 I jxcore-log: 
,03-31 10:13:02.947  3253  3312 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 10:13:02.947  3253  3312 I jxcore-log: 
,03-31 10:13:02.949  3253  3312 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 10:13:02.949  3253  3312 I jxcore-log: 
,03-31 10:13:02.978  3253  3312 I jxcore-log: ok 7 Send/recvd #1 should be equal length
03-31 10:13:02.978  3253  3312 I jxcore-log: 
,03-31 10:13:02.978  3253  3312 I jxcore-log: ok 8 Send/recvd #1 should be same
03-31 10:13:02.978  3253  3312 I jxcore-log: 
03-31 10:13:02.980  3253  3312 I jxcore-log: ok 9 Send/recvd #2 should be equal length
03-31 10:13:02.980  3253  3312 I jxcore-log: 
03-31 10:13:02.981  3253  3312 I jxcore-log: ok 10 Send/recvd #2 should be same
03-31 10:13:02.981  3253  3312 I jxcore-log: 
,03-31 10:13:02.984  3253  3312 I jxcore-log: ok 11 Should be exactly 2 client sockets
03-31 10:13:02.984  3253  3312 I jxcore-log: 
,03-31 10:13:02.991  3253  3312 I jxcore-log: # teardown
03-31 10:13:02.991  3253  3312 I jxcore-log: 
,03-31 10:13:03.151  3253  3312 I jxcore-log: DEBUG createNativeListener: stream close:
,03-31 10:13:03.151  3253  3312 I jxcore-log: 
,03-31 10:13:03.154  3253  3312 I jxcore-log: DEBUG createNativeListener: stream close:
,03-31 10:13:03.154  3253  3312 I jxcore-log: 
,03-31 10:13:03.157  3253  3312 I jxcore-log: DEBUG createNativeListener: mux close
03-31 10:13:03.157  3253  3312 I jxcore-log: 
,03-31 10:13:03.162  3253  3312 I jxcore-log: # setup
03-31 10:13:03.162  3253  3312 I jxcore-log: 
,03-31 10:13:03.163  3253  3312 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 10:13:03.163  3253  3312 I jxcore-log: 
,03-31 10:13:03.290  3253  3312 I jxcore-log: # 5. native server - closing incoming stream cleans outgoing socket
03-31 10:13:03.290  3253  3312 I jxcore-log: 
,03-31 10:13:03.493  3253  3312 I jxcore-log: DEBUG createNativeListener: creating native server,
03-31 10:13:03.493  3253  3312 I jxcore-log: 
,03-31 10:13:03.502  3253  3312 I jxcore-log: DEBUG createNativeListener: listening 37108,
03-31 10:13:03.502  3253  3312 I jxcore-log: 
,03-31 10:13:03.509  3253  3312 I jxcore-log: DEBUG createNativeListener: new incoming socket,
03-31 10:13:03.509  3253  3312 I jxcore-log: 
03-31 10:13:03.510  3253  3312 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 10:13:03.510  3253  3312 I jxcore-log: 
,03-31 10:13:03.512  3253  3312 I jxcore-log: DEBUG createNativeListener: new mux
03-31 10:13:03.512  3253  3312 I jxcore-log: 
,03-31 10:13:03.524  3253  3312 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 10:13:03.524  3253  3312 I jxcore-log: 
,03-31 10:13:03.529  3253  3312 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 10:13:03.529  3253  3312 I jxcore-log: 
,03-31 10:13:03.556  3253  3312 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 10:13:03.556  3253  3312 I jxcore-log: 
,03-31 10:13:03.570  3253  3312 I jxcore-log: ok 12 socket shouldn't close until after stream
03-31 10:13:03.570  3253  3312 I jxcore-log: 
,03-31 10:13:03.570  3253  3312 I jxcore-log: ok 13 incoming remains open
03-31 10:13:03.570  3253  3312 I jxcore-log: 
,03-31 10:13:03.577  3253  3312 I jxcore-log: # teardown
03-31 10:13:03.577  3253  3312 I jxcore-log: 
,03-31 10:13:03.686  3253  3312 I jxcore-log: DEBUG createNativeListener: mux close
03-31 10:13:03.686  3253  3312 I jxcore-log: 
,03-31 10:13:03.697  3253  3312 I jxcore-log: # setup
03-31 10:13:03.697  3253  3312 I jxcore-log: 
,03-31 10:13:03.698  3253  3312 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 10:13:03.698  3253  3312 I jxcore-log: 
,03-31 10:13:03.816  3253  3312 I jxcore-log: # 6. native server - closing incoming connection cleans outgoing socket
,03-31 10:13:03.816  3253  3312 I jxcore-log: 
,03-31 10:13:03.914  3253  3312 I jxcore-log: DEBUG createNativeListener: creating native server
,03-31 10:13:03.914  3253  3312 I jxcore-log: 
,03-31 10:13:03.919  3253  3312 I jxcore-log: DEBUG createNativeListener: listening 47429
,03-31 10:13:03.919  3253  3312 I jxcore-log: 
,03-31 10:13:03.926  3253  3312 I jxcore-log: DEBUG createNativeListener: new incoming socket
,03-31 10:13:03.926  3253  3312 I jxcore-log: 
,03-31 10:13:03.927  3253  3312 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 10:13:03.927  3253  3312 I jxcore-log: 
,03-31 10:13:03.930  3253  3312 I jxcore-log: DEBUG createNativeListener: new mux
03-31 10:13:03.930  3253  3312 I jxcore-log: 
,03-31 10:13:03.942  3253  3312 I jxcore-log: ok 14 we should not have gotten an error
,03-31 10:13:03.942  3253  3312 I jxcore-log: 
,03-31 10:13:03.948  3253  3312 I jxcore-log: DEBUG createNativeListener: new stream: 
,03-31 10:13:03.948  3253  3312 I jxcore-log: 
,03-31 10:13:03.956  3253  3312 I jxcore-log: DEBUG createNativeListener: new outgoing socket
,03-31 10:13:03.956  3253  3312 I jxcore-log: 
,03-31 10:13:03.976  3253  3312 I jxcore-log: DEBUG createNativeListener: stream close:
,03-31 10:13:03.976  3253  3312 I jxcore-log: 
,03-31 10:13:03.978  3253  3312 I jxcore-log: DEBUG createNativeListener: incoming socket close
,03-31 10:13:03.978  3253  3312 I jxcore-log: 
,03-31 10:13:03.986  3253  3312 I jxcore-log: ok 15 socket shouldn't close until after incoming
,03-31 10:13:03.986  3253  3312 I jxcore-log: 
,03-31 10:13:03.987  3253  3312 I jxcore-log: ok 16 incoming is cleaned up
03-31 10:13:03.987  3253  3312 I jxcore-log: 
,03-31 10:13:03.993  3253  3312 I jxcore-log: # teardown
03-31 10:13:03.993  3253  3312 I jxcore-log: 
,03-31 10:13:04.119  3253  3312 I jxcore-log: # setup
03-31 10:13:04.119  3253  3312 I jxcore-log: 
,03-31 10:13:04.254  3253  3312 I jxcore-log: # 7. native server - closing outgoing socket cleans associated mux stream
03-31 10:13:04.254  3253  3312 I jxcore-log: 
,03-31 10:13:04.374  3253  3312 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 10:13:04.374  3253  3312 I jxcore-log: 
,03-31 10:13:04.377  3253  3312 I jxcore-log: DEBUG createNativeListener: listening 40358
03-31 10:13:04.377  3253  3312 I jxcore-log: 
,03-31 10:13:04.383  3253  3312 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 10:13:04.383  3253  3312 I jxcore-log: 
,03-31 10:13:04.384  3253  3312 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 10:13:04.384  3253  3312 I jxcore-log: 
03-31 10:13:04.387  3253  3312 I jxcore-log: DEBUG createNativeListener: new mux
03-31 10:13:04.387  3253  3312 I jxcore-log: 
,03-31 10:13:04.396  3253  3312 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 10:13:04.396  3253  3312 I jxcore-log: 
,03-31 10:13:04.399  3253  3312 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 10:13:04.399  3253  3312 I jxcore-log: 
,03-31 10:13:04.412  3253  3312 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 10:13:04.412  3253  3312 I jxcore-log: 
,03-31 10:13:04.420  3253  3312 I jxcore-log: ok 17 stream was closed
03-31 10:13:04.420  3253  3312 I jxcore-log: 
,03-31 10:13:04.421  3253  3312 I jxcore-log: ok 18 incoming should survive
03-31 10:13:04.421  3253  3312 I jxcore-log: 
03-31 10:13:04.421  3253  3312 I jxcore-log: ok 19 mux should have no streams
03-31 10:13:04.421  3253  3312 I jxcore-log: 
,03-31 10:13:04.428  3253  3312 I jxcore-log: # teardown
03-31 10:13:04.428  3253  3312 I jxcore-log: 
,03-31 10:13:04.557  3253  3312 I jxcore-log: DEBUG createNativeListener: mux close
03-31 10:13:04.557  3253  3312 I jxcore-log: 
,03-31 10:13:04.562  3253  3312 I jxcore-log: # setup
03-31 10:13:04.562  3253  3312 I jxcore-log: 
03-31 10:13:04.564  3253  3312 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 10:13:04.564  3253  3312 I jxcore-log: 
,03-31 10:13:04.711  3253  3312 I jxcore-log: # 8. native server - closing the whole server cleans everything up
03-31 10:13:04.711  3253  3312 I jxcore-log: 
,03-31 10:13:04.814  3253  3312 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 10:13:04.814  3253  3312 I jxcore-log: 
,03-31 10:13:04.818  3253  3312 I jxcore-log: DEBUG createNativeListener: listening 34332
03-31 10:13:04.818  3253  3312 I jxcore-log: 
,03-31 10:13:04.824  3253  3312 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 10:13:04.824  3253  3312 I jxcore-log: 
,03-31 10:13:04.825  3253  3312 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 10:13:04.825  3253  3312 I jxcore-log: 
,03-31 10:13:04.826  3253  3312 I jxcore-log: DEBUG createNativeListener: new mux
03-31 10:13:04.826  3253  3312 I jxcore-log: 
,03-31 10:13:04.836  3253  3312 I jxcore-log: ok 20 we should not have gotten an error
03-31 10:13:04.836  3253  3312 I jxcore-log: 
,03-31 10:13:04.843  3253  3312 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 10:13:04.843  3253  3312 I jxcore-log: 
,03-31 10:13:04.845  3253  3312 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 10:13:04.845  3253  3312 I jxcore-log: 
,03-31 10:13:04.856  3253  3312 I jxcore-log: ok 21 Buffers are identical
03-31 10:13:04.856  3253  3312 I jxcore-log: 
,03-31 10:13:04.858  3253  3312 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 10:13:04.858  3253  3312 I jxcore-log: 
,03-31 10:13:04.861  3253  3312 I jxcore-log: DEBUG createNativeListener: mux close
03-31 10:13:04.861  3253  3312 I jxcore-log: 
,03-31 10:13:04.865  3253  3312 I jxcore-log: ok 22 native server is nulled out
03-31 10:13:04.865  3253  3312 I jxcore-log: 
03-31 10:13:04.865  3253  3312 I jxcore-log: ok 23 native server should be closed
03-31 10:13:04.865  3253  3312 I jxcore-log: 
,03-31 10:13:04.866  3253  3312 I jxcore-log: ok 24 incoming has been removed
03-31 10:13:04.866  3253  3312 I jxcore-log: 
03-31 10:13:04.866  3253  3312 I jxcore-log: ok 25 Incoming should be done
03-31 10:13:04.866  3253  3312 I jxcore-log: 
03-31 10:13:04.866  3253  3312 I jxcore-log: ok 26 The mux object should be closed
03-31 10:13:04.866  3253  3312 I jxcore-log: 
,03-31 10:13:04.866  3253  3312 I jxcore-log: ok 27 The mux stream should be closed
03-31 10:13:04.866  3253  3312 I jxcore-log: 
03-31 10:13:04.867  3253  3312 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 10:13:04.867  3253  3312 I jxcore-log: 
,03-31 10:13:04.883  3253  3312 I jxcore-log: # teardown,
03-31 10:13:04.883  3253  3312 I jxcore-log: 
,03-31 10:13:04.991  3253  3312 I jxcore-log: # setup
03-31 10:13:04.991  3253  3312 I jxcore-log: 
,03-31 10:13:05.157  3253  3312 I jxcore-log: # 9. native server - we can get a ton of connections and data through and still clean up the server completely
03-31 10:13:05.157  3253  3312 I jxcore-log: 
,03-31 10:13:05.279  3253  3312 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 10:13:05.279  3253  3312 I jxcore-log: 
,03-31 10:13:05.282  3253  3312 I jxcore-log: DEBUG createNativeListener: listening 50057
03-31 10:13:05.282  3253  3312 I jxcore-log: 
,03-31 10:13:05.302  3253  3312 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 10:13:05.302  3253  3312 I jxcore-log: 
,03-31 10:13:05.303  3253  3312 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 10:13:05.303  3253  3312 I jxcore-log: 
,03-31 10:13:05.304  3253  3312 I jxcore-log: DEBUG createNativeListener: new mux
03-31 10:13:05.304  3253  3312 I jxcore-log: 
,03-31 10:13:05.308  3253  3312 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 10:13:05.308  3253  3312 I jxcore-log: 
,03-31 10:13:05.309  3253  3312 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 10:13:05.309  3253  3312 I jxcore-log: 
,03-31 10:13:05.310  3253  3312 I jxcore-log: DEBUG createNativeListener: new mux
03-31 10:13:05.310  3253  3312 I jxcore-log: 
,03-31 10:13:05.313  3253  3312 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 10:13:05.313  3253  3312 I jxcore-log: 
,03-31 10:13:05.314  3253  3312 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 10:13:05.314  3253  3312 I jxcore-log: 
03-31 10:13:05.315  3253  3312 I jxcore-log: DEBUG createNativeListener: new mux
03-31 10:13:05.315  3253  3312 I jxcore-log: 
,03-31 10:13:05.318  3253  3312 I jxcore-log: DEBUG createNativeListener: new incoming socket,
03-31 10:13:05.318  3253  3312 I jxcore-log: 
03-31 10:13:05.319  3253  3312 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 10:13:05.319  3253  3312 I jxcore-log: 
,03-31 10:13:05.320  3253  3312 I jxcore-log: DEBUG createNativeListener: new mux
03-31 10:13:05.320  3253  3312 I jxcore-log: 
,03-31 10:13:05.323  3253  3312 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 10:13:05.323  3253  3312 I jxcore-log: 
,03-31 10:13:05.327  3253  3312 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 10:13:05.327  3253  3312 I jxcore-log: 
,03-31 10:13:05.329  3253  3312 I jxcore-log: DEBUG createNativeListener: new mux
03-31 10:13:05.329  3253  3312 I jxcore-log: 
,03-31 10:13:05.331  3253  3312 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 10:13:05.331  3253  3312 I jxcore-log: 
,03-31 10:13:05.332  3253  3312 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 10:13:05.332  3253  3312 I jxcore-log: 
,03-31 10:13:05.333  3253  3312 I jxcore-log: DEBUG createNativeListener: new mux
03-31 10:13:05.333  3253  3312 I jxcore-log: 
,03-31 10:13:05.335  3253  3312 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 10:13:05.335  3253  3312 I jxcore-log: 
,03-31 10:13:05.336  3253  3312 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 10:13:05.336  3253  3312 I jxcore-log: 
03-31 10:13:05.337  3253  3312 I jxcore-log: DEBUG createNativeListener: new mux
03-31 10:13:05.337  3253  3312 I jxcore-log: 
03-31 10:13:05.338  3253  3312 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 10:13:05.338  3253  3312 I jxcore-log: 
,03-31 10:13:05.339  3253  3312 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 10:13:05.339  3253  3312 I jxcore-log: 
03-31 10:13:05.339  3253  3312 I jxcore-log: DEBUG createNativeListener: new mux
03-31 10:13:05.339  3253  3312 I jxcore-log: 
03-31 10:13:05.341  3253  3312 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 10:13:05.341  3253  3312 I jxcore-log: 
,03-31 10:13:05.341  3253  3312 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 10:13:05.341  3253  3312 I jxcore-log: 
03-31 10:13:05.342  3253  3312 I jxcore-log: DEBUG createNativeListener: new mux
03-31 10:13:05.342  3253  3312 I jxcore-log: 
03-31 10:13:05.344  3253  3312 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 10:13:05.344  3253  3312 I jxcore-log: 
03-31 10:13:05.344  3253  3312 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 10:13:05.344  3253  3312 I jxcore-log: 
,03-31 10:13:05.345  3253  3312 I jxcore-log: DEBUG createNativeListener: new mux
03-31 10:13:05.345  3253  3312 I jxcore-log: 
,03-31 10:13:05.431  3253  3312 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 10:13:05.431  3253  3312 I jxcore-log: 
,03-31 10:13:05.434  3253  3312 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 10:13:05.434  3253  3312 I jxcore-log: 
,03-31 10:13:05.436  3253  3312 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 10:13:05.436  3253  3312 I jxcore-log: 
,03-31 10:13:05.438  3253  3312 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 10:13:05.438  3253  3312 I jxcore-log: 
,03-31 10:13:05.439  3253  3312 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 10:13:05.439  3253  3312 I jxcore-log: 
,03-31 10:13:05.441  3253  3312 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 10:13:05.441  3253  3312 I jxcore-log: 
,03-31 10:13:05.443  3253  3312 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 10:13:05.443  3253  3312 I jxcore-log: 
,03-31 10:13:05.445  3253  3312 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 10:13:05.445  3253  3312 I jxcore-log: 
,03-31 10:13:05.447  3253  3312 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 10:13:05.447  3253  3312 I jxcore-log: 
,03-31 10:13:05.449  3253  3312 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 10:13:05.449  3253  3312 I jxcore-log: 
,03-31 10:13:05.450  3253  3312 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 10:13:05.450  3253  3312 I jxcore-log: 
,03-31 10:13:05.452  3253  3312 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 10:13:05.452  3253  3312 I jxcore-log: 
,03-31 10:13:05.453  3253  3312 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 10:13:05.453  3253  3312 I jxcore-log: 
,03-31 10:13:05.454  3253  3312 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 10:13:05.454  3253  3312 I jxcore-log: 
03-31 10:13:05.455  3253  3312 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 10:13:05.455  3253  3312 I jxcore-log: 
,03-31 10:13:05.456  3253  3312 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 10:13:05.456  3253  3312 I jxcore-log: 
,03-31 10:13:05.458  3253  3312 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 10:13:05.458  3253  3312 I jxcore-log: 
,03-31 10:13:05.459  3253  3312 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 10:13:05.459  3253  3312 I jxcore-log: 
,03-31 10:13:05.460  3253  3312 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 10:13:05.460  3253  3312 I jxcore-log: 
,03-31 10:13:05.462  3253  3312 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 10:13:05.462  3253  3312 I jxcore-log: 
,03-31 10:13:05.465  3253  3312 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 10:13:05.465  3253  3312 I jxcore-log: 
,03-31 10:13:05.467  3253  3312 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 10:13:05.467  3253  3312 I jxcore-log: 
,03-31 10:13:05.468  3253  3312 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 10:13:05.468  3253  3312 I jxcore-log: 
,03-31 10:13:05.469  3253  3312 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 10:13:05.469  3253  3312 I jxcore-log: 
,03-31 10:13:05.471  3253  3312 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 10:13:05.471  3253  3312 I jxcore-log: 
,03-31 10:13:05.472  3253  3312 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 10:13:05.472  3253  3312 I jxcore-log: 
,03-31 10:13:05.473  3253  3312 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 10:13:05.473  3253  3312 I jxcore-log: 
,03-31 10:13:05.474  3253  3312 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 10:13:05.474  3253  3312 I jxcore-log: 
,03-31 10:13:05.475  3253  3312 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 10:13:05.475  3253  3312 I jxcore-log: 
,03-31 10:13:05.477  3253  3312 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 10:13:05.477  3253  3312 I jxcore-log: 
,03-31 10:13:05.477  3253  3312 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 10:13:05.477  3253  3312 I jxcore-log: 
,03-31 10:13:05.479  3253  3312 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 10:13:05.479  3253  3312 I jxcore-log: 
,03-31 10:13:05.480  3253  3312 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 10:13:05.480  3253  3312 I jxcore-log: 
,03-31 10:13:05.482  3253  3312 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 10:13:05.482  3253  3312 I jxcore-log: 
,03-31 10:13:05.483  3253  3312 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 10:13:05.483  3253  3312 I jxcore-log: 
03-31 10:13:05.484  3253  3312 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 10:13:05.484  3253  3312 I jxcore-log: 
,03-31 10:13:05.485  3253  3312 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 10:13:05.485  3253  3312 I jxcore-log: 
,03-31 10:13:05.486  3253  3312 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 10:13:05.486  3253  3312 I jxcore-log: 
,03-31 10:13:05.487  3253  3312 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 10:13:05.487  3253  3312 I jxcore-log: 
,03-31 10:13:05.488  3253  3312 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 10:13:05.488  3253  3312 I jxcore-log: 
,03-31 10:13:05.490  3253  3312 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 10:13:05.490  3253  3312 I jxcore-log: 
,03-31 10:13:05.491  3253  3312 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 10:13:05.491  3253  3312 I jxcore-log: 
,03-31 10:13:05.492  3253  3312 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 10:13:05.492  3253  3312 I jxcore-log: 
,03-31 10:13:05.494  3253  3312 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 10:13:05.494  3253  3312 I jxcore-log: 
,03-31 10:13:05.495  3253  3312 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 10:13:05.495  3253  3312 I jxcore-log: 
,03-31 10:13:05.496  3253  3312 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 10:13:05.496  3253  3312 I jxcore-log: 
,03-31 10:13:05.497  3253  3312 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 10:13:05.497  3253  3312 I jxcore-log: 
,03-31 10:13:05.498  3253  3312 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 10:13:05.498  3253  3312 I jxcore-log: 
,03-31 10:13:05.506  3253  3312 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 10:13:05.506  3253  3312 I jxcore-log: 
,03-31 10:13:05.507  3253  3312 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 10:13:05.507  3253  3312 I jxcore-log: 
03-31 10:13:05.508  3253  3312 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 10:13:05.508  3253  3312 I jxcore-log: 
,03-31 10:13:05.510  3253  3312 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 10:13:05.510  3253  3312 I jxcore-log: 
03-31 10:13:05.511  3253  3312 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 10:13:05.511  3253  3312 I jxcore-log: 
,03-31 10:13:05.512  3253  3312 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 10:13:05.512  3253  3312 I jxcore-log: 
03-31 10:13:05.513  3253  3312 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 10:13:05.513  3253  3312 I jxcore-log: 
03-31 10:13:05.514  3253  3312 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 10:13:05.514  3253  3312 I jxcore-log: 
,03-31 10:13:05.516  3253  3312 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 10:13:05.516  3253  3312 I jxcore-log: 
,03-31 10:13:05.518  3253  3312 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 10:13:05.518  3253  3312 I jxcore-log: 
,03-31 10:13:05.519  3253  3312 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 10:13:05.519  3253  3312 I jxcore-log: 
,03-31 10:13:05.521  3253  3312 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 10:13:05.521  3253  3312 I jxcore-log: 
,03-31 10:13:05.522  3253  3312 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 10:13:05.522  3253  3312 I jxcore-log: 
,03-31 10:13:05.523  3253  3312 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 10:13:05.523  3253  3312 I jxcore-log: 
,03-31 10:13:05.524  3253  3312 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 10:13:05.524  3253  3312 I jxcore-log: 
03-31 10:13:05.525  3253  3312 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 10:13:05.525  3253  3312 I jxcore-log: 
03-31 10:13:05.527  3253  3312 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 10:13:05.527  3253  3312 I jxcore-log: 
03-31 10:13:05.528  3253  3312 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 10:13:05.528  3253  3312 I jxcore-log: 
03-31 10:13:05.529  3253  3312 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 10:13:05.529  3253  3312 I jxcore-log: 
03-31 10:13:05.531  3253  3312 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 10:13:05.531  3253  3312 I jxcore-log: 
03-31 10:13:05.532  3253  3312 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 10:13:05.532  3253  3312 I jxcore-log: 
,03-31 10:13:05.533  3253  3312 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 10:13:05.533  3253  3312 I jxcore-log: 
,03-31 10:13:05.534  3253  3312 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 10:13:05.534  3253  3312 I jxcore-log: 
03-31 10:13:05.536  3253  3312 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 10:13:05.536  3253  3312 I jxcore-log: 
,03-31 10:13:05.537  3253  3312 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 10:13:05.537  3253  3312 I jxcore-log: 
,03-31 10:13:05.538  3253  3312 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 10:13:05.538  3253  3312 I jxcore-log: 
,03-31 10:13:05.539  3253  3312 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 10:13:05.539  3253  3312 I jxcore-log: 
,03-31 10:13:05.541  3253  3312 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 10:13:05.541  3253  3312 I jxcore-log: 
,03-31 10:13:05.542  3253  3312 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 10:13:05.542  3253  3312 I jxcore-log: 
,03-31 10:13:05.543  3253  3312 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 10:13:05.543  3253  3312 I jxcore-log: 
03-31 10:13:05.544  3253  3312 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 10:13:05.544  3253  3312 I jxcore-log: 
,03-31 10:13:05.545  3253  3312 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 10:13:05.545  3253  3312 I jxcore-log: 
,03-31 10:13:05.619  3253  3312 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 10:13:05.619  3253  3312 I jxcore-log: 
,03-31 10:13:05.621  3253  3312 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 10:13:05.621  3253  3312 I jxcore-log: 
,03-31 10:13:05.622  3253  3312 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 10:13:05.622  3253  3312 I jxcore-log: 
,03-31 10:13:05.624  3253  3312 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 10:13:05.624  3253  3312 I jxcore-log: 
,03-31 10:13:05.625  3253  3312 I jxcore-log: DEBUG createNativeListener: mux close
03-31 10:13:05.625  3253  3312 I jxcore-log: 
,03-31 10:13:05.627  3253  3312 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 10:13:05.627  3253  3312 I jxcore-log: 
,03-31 10:13:05.628  3253  3312 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 10:13:05.628  3253  3312 I jxcore-log: 
03-31 10:13:05.629  3253  3312 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 10:13:05.629  3253  3312 I jxcore-log: 
,03-31 10:13:05.629  3253  3312 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 10:13:05.629  3253  3312 I jxcore-log: 
,03-31 10:13:05.630  3253  3312 I jxcore-log: DEBUG createNativeListener: mux close
03-31 10:13:05.630  3253  3312 I jxcore-log: 
,03-31 10:13:05.633  3253  3312 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 10:13:05.633  3253  3312 I jxcore-log: 
,03-31 10:13:05.634  3253  3312 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 10:13:05.634  3253  3312 I jxcore-log: 
,03-31 10:13:05.635  3253  3312 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 10:13:05.635  3253  3312 I jxcore-log: 
03-31 10:13:05.636  3253  3312 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 10:13:05.636  3253  3312 I jxcore-log: 
,03-31 10:13:05.638  3253  3312 I jxcore-log: DEBUG createNativeListener: mux close
03-31 10:13:05.638  3253  3312 I jxcore-log: 
,03-31 10:13:05.639  3253  3312 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 10:13:05.639  3253  3312 I jxcore-log: 
,03-31 10:13:05.640  3253  3312 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 10:13:05.640  3253  3312 I jxcore-log: 
,03-31 10:13:05.641  3253  3312 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 10:13:05.641  3253  3312 I jxcore-log: 
,03-31 10:13:05.642  3253  3312 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 10:13:05.642  3253  3312 I jxcore-log: 
03-31 10:13:05.643  3253  3312 I jxcore-log: DEBUG createNativeListener: mux close
03-31 10:13:05.643  3253  3312 I jxcore-log: 
,03-31 10:13:05.644  3253  3312 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 10:13:05.644  3253  3312 I jxcore-log: 
,03-31 10:13:05.645  3253  3312 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 10:13:05.645  3253  3312 I jxcore-log: 
,03-31 10:13:05.646  3253  3312 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 10:13:05.646  3253  3312 I jxcore-log: 
03-31 10:13:05.646  3253  3312 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 10:13:05.646  3253  3312 I jxcore-log: 
03-31 10:13:05.647  3253  3312 I jxcore-log: DEBUG createNativeListener: mux close
03-31 10:13:05.647  3253  3312 I jxcore-log: 
03-31 10:13:05.649  3253  3312 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 10:13:05.649  3253  3312 I jxcore-log: 
,03-31 10:13:05.649  3253  3312 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 10:13:05.649  3253  3312 I jxcore-log: 
,03-31 10:13:05.650  3253  3312 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 10:13:05.650  3253  3312 I jxcore-log: 
,03-31 10:13:05.651  3253  3312 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 10:13:05.651  3253  3312 I jxcore-log: 
,03-31 10:13:05.652  3253  3312 I jxcore-log: DEBUG createNativeListener: mux close
03-31 10:13:05.652  3253  3312 I jxcore-log: 
03-31 10:13:05.653  3253  3312 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 10:13:05.653  3253  3312 I jxcore-log: 
,03-31 10:13:05.654  3253  3312 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 10:13:05.654  3253  3312 I jxcore-log: 
,03-31 10:13:05.655  3253  3312 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 10:13:05.655  3253  3312 I jxcore-log: 
03-31 10:13:05.655  3253  3312 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 10:13:05.655  3253  3312 I jxcore-log: 
03-31 10:13:05.656  3253  3312 I jxcore-log: DEBUG createNativeListener: mux close
03-31 10:13:05.656  3253  3312 I jxcore-log: 
03-31 10:13:05.657  3253  3312 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 10:13:05.657  3253  3312 I jxcore-log: 
,03-31 10:13:05.658  3253  3312 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 10:13:05.658  3253  3312 I jxcore-log: 
03-31 10:13:05.659  3253  3312 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 10:13:05.659  3253  3312 I jxcore-log: 
03-31 10:13:05.659  3253  3312 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 10:13:05.659  3253  3312 I jxcore-log: 
03-31 10:13:05.660  3253  3312 I jxcore-log: DEBUG createNativeListener: mux close
03-31 10:13:05.660  3253  3312 I jxcore-log: 
,03-31 10:13:05.661  3253  3312 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 10:13:05.661  3253  3312 I jxcore-log: 
03-31 10:13:05.662  3253  3312 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 10:13:05.662  3253  3312 I jxcore-log: 
03-31 10:13:05.663  3253  3312 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 10:13:05.663  3253  3312 I jxcore-log: 
03-31 10:13:05.663  3253  3312 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 10:13:05.663  3253  3312 I jxcore-log: 
03-31 10:13:05.664  3253  3312 I jxcore-log: DEBUG createNativeListener: mux close
03-31 10:13:05.664  3253  3312 I jxcore-log: 
03-31 10:13:05.665  3253  3312 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 10:13:05.665  3253  3312 I jxcore-log: 
03-31 10:13:05.666  3253  3312 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 10:13:05.666  3253  3312 I jxcore-log: 
03-31 10:13:05.667  3253  3312 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 10:13:05.667  3253  3312 I jxcore-log: 
03-31 10:13:05.668  3253  3312 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 10:13:05.668  3253  3312 I jxcore-log: 
03-31 10:13:05.668  3253  3312 I jxcore-log: DEBUG createNativeListener: mux close
03-31 10:13:05.668  3253  3312 I jxcore-log: 
03-31 10:13:05.671  3253  3312 I jxcore-log: ok 28 native server is nulled out
03-31 10:13:05.671  3253  3312 I jxcore-log: 
03-31 10:13:05.672  3253  3312 I jxcore-log: ok 29 native server should be closed
03-31 10:13:05.672  3253  3312 I jxcore-log: 
03-31 10:13:05.672  3253  3312 I jxcore-log: ok 30 incoming has been removed
03-31 10:13:05.672  3253  3312 I jxcore-log: 
03-31 10:13:05.673  3253  3312 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 10:13:05.673  3253  3312 I jxcore-log: 
03-31 10:13:05.674  3253  3312 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 10:13:05.674  3253  3312 I jxcore-log: 
03-31 10:13:05.674  3253  3312 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 10:13:05.674  3253  3312 I jxcore-log: 
03-31 10:13:05.675  3253  3312 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 10:13:05.675  3253  3312 I jxcore-log: 
03-31 10:13:05.675  3253  3312 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 10:13:05.675  3253  3312 I jxcore-log: 
03-31 10:13:05.676  3253  3312 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 10:13:05.676  3253  3312 I jxcore-log: 
03-31 10:13:05.676  3253  3312 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 10:13:05.676  3253  3312 I jxcore-log: 
03-31 10:13:05.676  3253  3312 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 10:13:05.676  3253  3312 I jxcore-log: 
03-31 10:13:05.677  3253  3312 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 10:13:05.677  3253  3312 I jxcore-log: 
03-31 10:13:05.677  3253  3312 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 10:13:05.677  3253  3312 I jxcore-log: 
,03-31 10:13:05.814  3253  3312 I jxcore-log: # teardown
03-31 10:13:05.814  3253  3312 I jxcore-log: 
,03-31 10:13:05.944  3253  3312 I jxcore-log: # setup
03-31 10:13:05.944  3253  3312 I jxcore-log: 
,03-31 10:13:06.058  3253  3312 I jxcore-log: # 10. native server - simulate mux failure, make sure everything is cleaned up
03-31 10:13:06.058  3253  3312 I jxcore-log: 
,03-31 10:13:06.153  3253  3312 I jxcore-log: DEBUG createNativeListener: creating native server,
03-31 10:13:06.153  3253  3312 I jxcore-log: 
,03-31 10:13:06.162  3253  3312 I jxcore-log: DEBUG createNativeListener: listening 40148
03-31 10:13:06.162  3253  3312 I jxcore-log: 
,03-31 10:13:06.169  3253  3312 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 10:13:06.169  3253  3312 I jxcore-log: 
,03-31 10:13:06.170  3253  3312 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 10:13:06.170  3253  3312 I jxcore-log: 
,03-31 10:13:06.172  3253  3312 I jxcore-log: DEBUG createNativeListener: new mux
03-31 10:13:06.172  3253  3312 I jxcore-log: 
,03-31 10:13:06.179  3253  3312 I jxcore-log: ok 31 we should not have gotten an error
03-31 10:13:06.179  3253  3312 I jxcore-log: 
,03-31 10:13:06.183  3253  3312 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 10:13:06.183  3253  3312 I jxcore-log: 
,03-31 10:13:06.186  3253  3312 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 10:13:06.186  3253  3312 I jxcore-log: 
,03-31 10:13:06.193  3253  3312 I jxcore-log: ok 32 Buffers are identical
03-31 10:13:06.193  3253  3312 I jxcore-log: ,
03-31 10:13:06.194  3253  3312 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 10:13:06.194  3253  3312 I jxcore-log: 
,03-31 10:13:06.196  3253  3312 I jxcore-log: DEBUG createNativeListener: mux close
03-31 10:13:06.196  3253  3312 I jxcore-log: 
,03-31 10:13:06.206  3253  3312 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 10:13:06.206  3253  3312 I jxcore-log: 
,03-31 10:13:06.207  3253  3312 I jxcore-log: ok 33 server should be fine
03-31 10:13:06.207  3253  3312 I jxcore-log: 
,03-31 10:13:06.207  3253  3312 I jxcore-log: ok 34 server should be open
03-31 10:13:06.207  3253  3312 I jxcore-log: 
,03-31 10:13:06.208  3253  3312 I jxcore-log: ok 35 incoming has been removed
03-31 10:13:06.208  3253  3312 I jxcore-log: 
,03-31 10:13:06.208  3253  3312 I jxcore-log: ok 36 The mux object should be closed
03-31 10:13:06.208  3253  3312 I jxcore-log: 
03-31 10:13:06.209  3253  3312 I jxcore-log: ok 37 The mux stream should be closed
03-31 10:13:06.209  3253  3312 I jxcore-log: 
,03-31 10:13:06.216  3253  3312 I jxcore-log: # teardown
03-31 10:13:06.216  3253  3312 I jxcore-log: 
,03-31 10:13:06.337  3253  3312 I jxcore-log: # setup
03-31 10:13:06.337  3253  3312 I jxcore-log: 
,03-31 10:13:06.461  3253  3312 I jxcore-log: # 11. native server - timing out the incoming connection cleans everything up
03-31 10:13:06.461  3253  3312 I jxcore-log: 
,03-31 10:13:06.557  3253  3312 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 10:13:06.557  3253  3312 I jxcore-log: 
,03-31 10:13:06.565  3253  3312 I jxcore-log: DEBUG createNativeListener: listening 49704
03-31 10:13:06.565  3253  3312 I jxcore-log: 
,03-31 10:13:06.571  3253  3312 I jxcore-log: DEBUG createNativeListener: new incoming socket
,03-31 10:13:06.571  3253  3312 I jxcore-log: 
03-31 10:13:06.572  3253  3312 I jxcore-log: DEBUG createNativeListener: creating incoming mux,
03-31 10:13:06.572  3253  3312 I jxcore-log: 
03-31 10:13:06.574  3253  3312 I jxcore-log: DEBUG createNativeListener: new mux,
03-31 10:13:06.574  3253  3312 I jxcore-log: 
,03-31 10:13:06.581  3253  3312 I jxcore-log: ok 38 we should not have gotten an error
03-31 10:13:06.581  3253  3312 I jxcore-log: 
,03-31 10:13:06.584  3253  3312 I jxcore-log: DEBUG createNativeListener: new stream: 
,03-31 10:13:06.584  3253  3312 I jxcore-log: 
,03-31 10:13:06.587  3253  3312 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 10:13:06.587  3253  3312 I jxcore-log: 
,03-31 10:13:06.594  3253  3312 I jxcore-log: ok 39 Buffers are identical
03-31 10:13:06.594  3253  3312 I jxcore-log: 
,03-31 10:13:06.598  3253  3312 I jxcore-log: DEBUG createNativeListener: incoming socket timeout
03-31 10:13:06.598  3253  3312 I jxcore-log: 
,03-31 10:13:06.600  3253  3312 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 10:13:06.600  3253  3312 I jxcore-log: 
,03-31 10:13:06.602  3253  3312 I jxcore-log: DEBUG createNativeListener: mux close
03-31 10:13:06.602  3253  3312 I jxcore-log: 
,03-31 10:13:06.607  3253  3312 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 10:13:06.607  3253  3312 I jxcore-log: 
,03-31 10:13:06.608  3253  3312 I jxcore-log: ok 40 server should be fine
03-31 10:13:06.608  3253  3312 I jxcore-log: 
,03-31 10:13:06.608  3253  3312 I jxcore-log: ok 41 server should be open
03-31 10:13:06.608  3253  3312 I jxcore-log: 
,03-31 10:13:06.609  3253  3312 I jxcore-log: ok 42 incoming has been removed
03-31 10:13:06.609  3253  3312 I jxcore-log: 
03-31 10:13:06.609  3253  3312 I jxcore-log: ok 43 The mux object should be closed
03-31 10:13:06.609  3253  3312 I jxcore-log: 
,03-31 10:13:06.609  3253  3312 I jxcore-log: ok 44 The mux stream should be closed
03-31 10:13:06.609  3253  3312 I jxcore-log: 
,03-31 10:13:06.619  3253  3312 I jxcore-log: # teardown
03-31 10:13:06.619  3253  3312 I jxcore-log: 
,03-31 10:13:06.747  3253  3312 I jxcore-log: # setup
,03-31 10:13:06.747  3253  3312 I jxcore-log: 
,03-31 10:13:06.882  3253  3312 I jxcore-log: # 12. closeAll can close even when connections open
03-31 10:13:06.882  3253  3312 I jxcore-log: 
,03-31 10:13:07.007  3253  3312 I jxcore-log: ok 45 not possible to connect to the server anymore
,03-31 10:13:07.007  3253  3312 I jxcore-log: 
,03-31 10:13:07.013  3253  3312 I jxcore-log: # teardown
03-31 10:13:07.013  3253  3312 I jxcore-log: 
,03-31 10:13:07.134  3253  3312 I jxcore-log: # setup
03-31 10:13:07.134  3253  3312 I jxcore-log: 
,03-31 10:13:07.262  3253  3312 I jxcore-log: # 13. closeAll with promise
03-31 10:13:07.262  3253  3312 I jxcore-log: 
,03-31 10:13:07.706  3253  3312 I jxcore-log: ok 46 not possible to connect to the server anymore
03-31 10:13:07.706  3253  3312 I jxcore-log: 
,03-31 10:13:07.712  3253  3312 I jxcore-log: # teardown
,03-31 10:13:07.712  3253  3312 I jxcore-log: 
,03-31 10:13:08.268  3253  3312 I jxcore-log: # setup
03-31 10:13:08.268  3253  3312 I jxcore-log: 
,03-31 10:13:08.480  3253  3312 I jxcore-log: # 14. closeAll properly throws when closing a non open server with eatNotRunning set to false
03-31 10:13:08.480  3253  3312 I jxcore-log: 
,03-31 10:13:08.542  3253  3312 I jxcore-log: ok 47 Got the right error
03-31 10:13:08.542  3253  3312 I jxcore-log: 
,03-31 10:13:08.544  3253  3312 I jxcore-log: # teardown
03-31 10:13:08.544  3253  3312 I jxcore-log: 
,03-31 10:13:08.716  3253  3312 I jxcore-log: # setup
03-31 10:13:08.716  3253  3312 I jxcore-log: 
,03-31 10:13:08.846  3253  3312 I jxcore-log: # 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true
03-31 10:13:08.846  3253  3312 I jxcore-log: 
,03-31 10:13:08.945  3253  3312 I jxcore-log: # teardown
03-31 10:13:08.945  3253  3312 I jxcore-log: 
,03-31 10:13:09.102  3253  3312 I jxcore-log: # setup
03-31 10:13:09.102  3253  3312 I jxcore-log: 
,03-31 10:13:09.352  3253  3312 I jxcore-log: # 16. multiplex can send data
03-31 10:13:09.352  3253  3312 I jxcore-log: 
,03-31 10:13:09.574  3253  3312 I jxcore-log: ok 48 String should be length:200
03-31 10:13:09.574  3253  3312 I jxcore-log: 
,03-31 10:13:09.581  3253  3312 I jxcore-log: # teardown
03-31 10:13:09.581  3253  3312 I jxcore-log: 
,03-31 10:13:09.739  3253  3312 I jxcore-log: # setup,
03-31 10:13:09.739  3253  3312 I jxcore-log: 
,03-31 10:13:09.858  3253  3312 I jxcore-log: # 17. enqueue and run in order
03-31 10:13:09.858  3253  3312 I jxcore-log: 
,03-31 10:13:10.109  3253  3312 I jxcore-log: ok 49 firstPromise setTimeout
03-31 10:13:10.109  3253  3312 I jxcore-log: 
03-31 10:13:10.111  3253  3312 I jxcore-log: ok 50 firstPromise result
03-31 10:13:10.111  3253  3312 I jxcore-log: 
03-31 10:13:10.113  3253  3312 I jxcore-log: ok 51 firstPromise testValue
03-31 10:13:10.113  3253  3312 I jxcore-log: 
,03-31 10:13:10.216  3253  3312 I jxcore-log: ok 52 secondPromise setTimeout
03-31 10:13:10.216  3253  3312 I jxcore-log: 
,03-31 10:13:10.220  3253  3312 I jxcore-log: ok 53 secondPromise result
03-31 10:13:10.220  3253  3312 I jxcore-log: 
,03-31 10:13:10.222  3253  3312 I jxcore-log: ok 54 secondPromise testValue
03-31 10:13:10.222  3253  3312 I jxcore-log: 
,03-31 10:13:10.224  3253  3312 I jxcore-log: ok 55 thirdPromise in promise
03-31 10:13:10.224  3253  3312 I jxcore-log: 
,03-31 10:13:10.227  3253  3312 I jxcore-log: ok 56 thirdPromise result
03-31 10:13:10.227  3253  3312 I jxcore-log: 
03-31 10:13:10.229  3253  3312 I jxcore-log: ok 57 thirdPromise testValue
03-31 10:13:10.229  3253  3312 I jxcore-log: 
,03-31 10:13:10.237  3253  3312 I jxcore-log: # teardown
03-31 10:13:10.237  3253  3312 I jxcore-log: 
,03-31 10:13:10.558  3253  3312 I jxcore-log: # setup
03-31 10:13:10.558  3253  3312 I jxcore-log: 
,03-31 10:13:10.663  3253  3312 I jxcore-log: # 18. enqueueAtTop and run backwards
03-31 10:13:10.663  3253  3312 I jxcore-log: 
,03-31 10:13:10.797  3253  3312 I jxcore-log: ok 58 thirdPromise - first to run
03-31 10:13:10.797  3253  3312 I jxcore-log: 
,03-31 10:13:10.799  3253  3312 I jxcore-log: ok 59 thirdPromise - in resolve
03-31 10:13:10.799  3253  3312 I jxcore-log: 
,03-31 10:13:10.799  3253  3312 I jxcore-log: ok 60 secondPromise - second to run
03-31 10:13:10.799  3253  3312 I jxcore-log: ,
03-31 10:13:10.800  3253  3312 I jxcore-log: ok 61 secondPromise - in catch
03-31 10:13:10.800  3253  3312 I jxcore-log: 
03-31 10:13:10.800  3253  3312 I jxcore-log: ok 62 firstPromise - third to run
03-31 10:13:10.800  3253  3312 I jxcore-log: 
03-31 10:13:10.801  3253  3312 I jxcore-log: ok 63 firstPromise - in then
03-31 10:13:10.801  3253  3312 I jxcore-log: 
,03-31 10:13:10.801  3253  3312 I jxcore-log: ok 64 testing promises
03-31 10:13:10.801  3253  3312 I jxcore-log: 
03-31 10:13:10.805  3253  3312 I jxcore-log: # teardown
03-31 10:13:10.805  3253  3312 I jxcore-log: 
,03-31 10:13:11.039  3253  3312 I jxcore-log: # setup
03-31 10:13:11.039  3253  3312 I jxcore-log: 
,03-31 10:13:11.231  3253  3312 I jxcore-log: # 19. mix enqueue and enqueueAtTop
03-31 10:13:11.231  3253  3312 I jxcore-log: 
,03-31 10:13:11.580  3253  3312 I jxcore-log: ok 65 fourth
03-31 10:13:11.580  3253  3312 I jxcore-log: 
,03-31 10:13:11.584  3253  3312 I jxcore-log: ok 66 fourth
03-31 10:13:11.584  3253  3312 I jxcore-log: 
,03-31 10:13:11.585  3253  3312 I jxcore-log: ok 67 second
03-31 10:13:11.585  3253  3312 I jxcore-log: 
,03-31 10:13:11.586  3253  3312 I jxcore-log: ok 68 secondPromise - in then
03-31 10:13:11.586  3253  3312 I jxcore-log: 
,03-31 10:13:11.690  3253  3312 I jxcore-log: ok 69 first
03-31 10:13:11.690  3253  3312 I jxcore-log: 
,03-31 10:13:11.693  3253  3312 I jxcore-log: ok 70 firstPromise - in catch
03-31 10:13:11.693  3253  3312 I jxcore-log: 
03-31 10:13:11.695  3253  3312 I jxcore-log: ok 71 third
03-31 10:13:11.695  3253  3312 I jxcore-log: 
,03-31 10:13:11.697  3253  3312 I jxcore-log: ok 72 thirdPromise - in then
03-31 10:13:11.697  3253  3312 I jxcore-log: 
,03-31 10:13:11.700  3253  3312 I jxcore-log: ok 73 testingPromises
03-31 10:13:11.700  3253  3312 I jxcore-log: 
,03-31 10:13:11.713  3253  3312 I jxcore-log: # teardown
03-31 10:13:11.713  3253  3312 I jxcore-log: ,
,03-31 10:13:12.195  3253  3312 I jxcore-log: # setup
03-31 10:13:12.195  3253  3312 I jxcore-log: 
,03-31 10:13:12.915  3253  3312 I jxcore-log: # 20. queues handled independently
03-31 10:13:12.915  3253  3312 I jxcore-log: 
,03-31 10:13:13.499  3253  3312 I jxcore-log: ok 74 all short operations completed before the long resolves
03-31 10:13:13.499  3253  3312 I jxcore-log: 
,03-31 10:13:13.510  3253  3312 I jxcore-log: # teardown
03-31 10:13:13.510  3253  3312 I jxcore-log: 
,03-31 10:13:13.894  3253  3312 I jxcore-log: # setup
03-31 10:13:13.894  3253  3312 I jxcore-log: 
,03-31 10:13:14.457  3253  3312 I jxcore-log: # 21. basic
03-31 10:13:14.457  3253  3312 I jxcore-log: 
,03-31 10:13:14.613  3253  3312 I jxcore-log: ok 75 sane
03-31 10:13:14.613  3253  3312 I jxcore-log: 
,03-31 10:13:14.619  3253  3312 I jxcore-log: # teardown
03-31 10:13:14.619  3253  3312 I jxcore-log: 
,03-31 10:13:14.741  3253  3312 I jxcore-log: # setup
03-31 10:13:14.741  3253  3312 I jxcore-log: ,
,03-31 10:13:14.882  3253  3312 I jxcore-log: # 22. another
03-31 10:13:14.882  3253  3312 I jxcore-log: 
,03-31 10:13:15.334  3253  3312 I jxcore-log: ok 76 sane
03-31 10:13:15.334  3253  3312 I jxcore-log: 
,03-31 10:13:15.341  3253  3312 I jxcore-log: # teardown
03-31 10:13:15.341  3253  3312 I jxcore-log: 
,03-31 10:13:15.960  3253  3312 I jxcore-log: # setup
03-31 10:13:15.960  3253  3312 I jxcore-log: 
,03-31 10:13:16.345  3253  3312 I jxcore-log: # 23. can pass data in setup
03-31 10:13:16.345  3253  3312 I jxcore-log: 
,03-31 10:13:16.922  3253  3312 I jxcore-log: ok 77 test participant has uuid
03-31 10:13:16.922  3253  3312 I jxcore-log: 
,03-31 10:13:16.925  3253  3312 I jxcore-log: ok 78 participant data matches
03-31 10:13:16.925  3253  3312 I jxcore-log: 
03-31 10:13:16.926  3253  3312 I jxcore-log: ok 79 test participant has uuid
03-31 10:13:16.926  3253  3312 I jxcore-log: 
,03-31 10:13:16.928  3253  3312 I jxcore-log: ok 80 participant data matches
03-31 10:13:16.928  3253  3312 I jxcore-log: 
03-31 10:13:16.929  3253  3312 I jxcore-log: ok 81 test participant has uuid
03-31 10:13:16.929  3253  3312 I jxcore-log: 
,03-31 10:13:16.931  3253  3312 I jxcore-log: ok 82 participant data matches
03-31 10:13:16.931  3253  3312 I jxcore-log: 
,03-31 10:13:16.933  3253  3312 I jxcore-log: ok 83 own UUID is found from the participants list
03-31 10:13:16.933  3253  3312 I jxcore-log: 
,03-31 10:13:16.936  3253  3312 I jxcore-log: # teardown
03-31 10:13:16.936  3253  3312 I jxcore-log: 
,03-31 10:13:17.118  3253  3312 I jxcore-log: # setup
03-31 10:13:17.118  3253  3312 I jxcore-log: 
,03-31 10:13:17.511  3253  3312 I jxcore-log: # 24. #startListeningForAdvertisements should fail if start not called
03-31 10:13:17.511  3253  3312 I jxcore-log: 
,03-31 10:13:18.230  3253  3312 I jxcore-log: ok 84 specific error should be returned
03-31 10:13:18.230  3253  3312 I jxcore-log: 
,03-31 10:13:18.235  3253  3312 I jxcore-log: # teardown
03-31 10:13:18.235  3253  3312 I jxcore-log: 
,03-31 10:13:18.797  1265  1265 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 10:13:18.930  1265  3839 I VacuumService: Vacuum at: now=1459411998930 tag=VacuumService
,03-31 10:13:18.937  3355  3838 V GoogleAuthProtoRequest: [335] a.<init>: mAccountName set to: thalitester@gmail.com
,03-31 10:13:18.972  1265  1720 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
03-31 10:13:18.972  1265  1720 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 10:13:18.973  1265  1720 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-31 10:13:18.973  1265  1720 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 10:13:18.975  1265  1720 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 10:13:18.999  3355  3838 W ExperimentUpdateService: [335] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,03-31 10:13:19.000  3355  3838 W ExperimentUpdateService: [335] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-31 10:13:19.000  3355  3838 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-31 10:13:19.000  3355  3838 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-31 10:13:19.000  3355  3838 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-31 10:13:19.000  3355  3838 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-31 10:13:19.000  3355  3838 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-31 10:13:19.000  3355  3838 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-31 10:13:19.000  3355  3838 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-31 10:13:19.000  3355  3838 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-31 10:13:19.000  3355  3838 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-31 10:13:19.000  3355  3838 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-31 10:13:19.075  1265  1265 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 10:13:19.084  1265  3840 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,03-31 10:13:19.133  1265  3840 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
03-31 10:13:19.133  1265  3840 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 10:13:19.133  1265  3840 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 10:13:19.133  1265  3840 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 10:13:19.138  1265  3840 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 10:13:19.145  1265  1719 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,03-31 10:13:19.145  1265  1719 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 10:13:19.145  1265  1719 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 10:13:19.145  1265  1719 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 10:13:19.165  1265  1719 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 10:13:19.179  3678  3678 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
03-31 10:13:19.180  3678  3678 D Finsky  : [1] 5.onFinished: Installation state replication failed.
03-31 10:13:19.180  3678  3678 D Finsky  : [1] 5.onFinished: Scheduling replication attempt 1.
,03-31 10:13:19.192  1265  3840 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-31 10:13:19.192  1265  3840 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-31 10:13:19.192  1265  3840 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-31 10:13:19.192  1265  3840 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-31 10:13:19.192  1265  3840 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-31 10:13:19.192  1265  3840 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-31 10:13:19.192  1265  3840 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-31 10:13:19.192  1265  3840 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-31 10:13:19.192  1265  3840 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-31 10:13:19.192  1265  3840 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-31 10:13:19.192  1265  3840 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-31 10:13:19.192  1265  3840 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-31 10:13:19.192  1265  3840 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-31 10:13:21.715  3253  3312 I jxcore-log: ok 85 error should be null
03-31 10:13:21.715  3253  3312 I jxcore-log: 
03-31 10:13:21.715  3253  3312 I jxcore-log: ok 86 error should be null
03-31 10:13:21.715  3253  3312 I jxcore-log: 
,03-31 10:13:21.718  3253  3312 I jxcore-log: # setup
,03-31 10:13:21.718  3253  3312 I jxcore-log: 
,03-31 10:13:22.470  3253  3312 I jxcore-log: # 25. #startUpdateAdvertisingAndListening should fail if start not called
03-31 10:13:22.470  3253  3312 I jxcore-log: 
,03-31 10:13:23.664  3253  3312 I jxcore-log: ok 87 specific error should be returned
03-31 10:13:23.664  3253  3312 I jxcore-log: 
,03-31 10:13:23.666  3253  3312 I jxcore-log: # teardown,
03-31 10:13:23.666  3253  3312 I jxcore-log: 
,03-31 10:13:25.005  1265  3840 W Uploader: No account for auth token provided
,03-31 10:13:25.083  3253  3312 I jxcore-log: ok 88 error should be null
03-31 10:13:25.083  3253  3312 I jxcore-log: 
,03-31 10:13:25.084  3253  3312 I jxcore-log: ok 89 error should be null
03-31 10:13:25.084  3253  3312 I jxcore-log: 
,03-31 10:13:25.087  3253  3312 I jxcore-log: # setup
,03-31 10:13:25.087  3253  3312 I jxcore-log: 
,03-31 10:13:25.272  1265  3840 W Uploader: No account for auth token provided
,03-31 10:13:26.475  3253  3312 I jxcore-log: # 26. should be able to call #stopListeningForAdvertisements many times
03-31 10:13:26.475  3253  3312 I jxcore-log: 
,03-31 10:13:26.545  1265  3840 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
03-31 10:13:26.546  1265  3840 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-31 10:13:26.546  1265  3840 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-31 10:13:26.546  1265  3840 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 10:13:26.553  1265  3840 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 10:13:26.608  1265  3840 I art     : Explicit concurrent mark sweep GC freed 39984(2MB) AllocSpace objects, 8(719KB) LOS objects, 37% free, 26MB/42MB, paused 1.506ms total 50.826ms
,03-31 10:13:26.660  1265  3840 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-31 10:13:26.660  1265  3840 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-31 10:13:26.660  1265  3840 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-31 10:13:26.660  1265  3840 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-31 10:13:26.660  1265  3840 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-31 10:13:26.660  1265  3840 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-31 10:13:26.660  1265  3840 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-31 10:13:26.660  1265  3840 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-31 10:13:26.660  1265  3840 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-31 10:13:26.660  1265  3840 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-31 10:13:26.660  1265  3840 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-31 10:13:26.660  1265  3840 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-31 10:13:26.660  1265  3840 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-31 10:13:27.132  1265  3840 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,03-31 10:13:27.133  1265  3840 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 10:13:27.133  1265  3840 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 10:13:27.134  1265  3840 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 10:13:27.149  1265  3840 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 10:13:27.221  1265  3840 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-31 10:13:27.221  1265  3840 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
,03-31 10:13:27.221  1265  3840 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-31 10:13:27.221  1265  3840 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-31 10:13:27.221  1265  3840 E Uploader: ,	at com.google.android.gms.auth.p.c(SourceFile:550)
03-31 10:13:27.221  1265  3840 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-31 10:13:27.221  1265  3840 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508),
03-31 10:13:27.221  1265  3840 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-31 10:13:27.221  1265  3840 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
,03-31 10:13:27.221  1265  3840 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-31 10:13:27.221  1265  3840 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-31 10:13:27.221  1265  3840 E Uploader: 	,at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-31 10:13:27.221  1265  3840 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-31 10:13:27.395  3253  3312 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 10:13:27.395  3253  3312 I jxcore-log: 
,03-31 10:13:27.397  3253  3312 I jxcore-log: DEBUG createNativeListener: listening 38058
03-31 10:13:27.397  3253  3312 I jxcore-log: 
,03-31 10:13:27.400  3253  3312 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-31 10:13:27.400  3253  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 10:13:27.400  3253  3312 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 10:13:27.406  3253  3312 I jxcore-log: ok 90 error should be null
03-31 10:13:27.406  3253  3312 I jxcore-log: 
03-31 10:13:27.406  3253  3312 I jxcore-log: ok 91 error should be null
03-31 10:13:27.406  3253  3312 I jxcore-log: 
03-31 10:13:27.408  3253  3312 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-31 10:13:27.408  3253  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-31 10:13:27.408  3253  3312 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 10:13:27.411  3253  3312 I jxcore-log: ok 92 error should be null,
,03-31 10:13:27.411  3253  3312 I jxcore-log: 
03-31 10:13:27.411  3253  3312 I jxcore-log: ok 93 error should be null
03-31 10:13:27.411  3253  3312 I jxcore-log: 
03-31 10:13:27.415  3253  3312 I jxcore-log: # teardown
03-31 10:13:27.415  3253  3312 I jxcore-log: 
,03-31 10:13:27.597  1265  3840 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,03-31 10:13:27.597  1265  3840 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-31 10:13:27.598  1265  3840 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 10:13:27.598  1265  3840 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 10:13:27.610  1265  3840 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 10:13:27.695  1265  3840 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-31 10:13:27.695  1265  3840 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-31 10:13:27.695  1265  3840 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-31 10:13:27.695  1265  3840 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-31 10:13:27.695  1265  3840 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-31 10:13:27.695  1265  3840 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-31 10:13:27.695  1265  3840 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-31 10:13:27.695  1265  3840 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-31 10:13:27.695  1265  3840 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-31 10:13:27.695  1265  3840 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-31 10:13:27.695  1265  3840 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-31 10:13:27.695  1265  3840 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-31 10:13:27.695  1265  3840 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-31 10:13:27.910  1265  3840 W Uploader: No account for auth token provided
,03-31 10:13:28.105  1265  3840 W Uploader: No account for auth token provided
,03-31 10:13:28.332  1265  3840 W Uploader: No account for auth token provided
,03-31 10:13:28.575  3253  3312 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-31 10:13:28.575  3253  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 10:13:28.575  3253  3312 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 10:13:28.579  3253  3312 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-31 10:13:28.579  3253  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 10:13:28.579  3253  3312 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 10:13:28.584  3253  3312 I jxcore-log: ok 94 error should be null,
03-31 10:13:28.584  3253  3312 I jxcore-log: 
,03-31 10:13:28.585  3253  3312 I jxcore-log: ok 95 error should be null,
03-31 10:13:28.585  3253  3312 I jxcore-log: 
03-31 10:13:28.590  3253  3312 I jxcore-log: # setup,
03-31 10:13:28.590  3253  3312 I jxcore-log: 
,03-31 10:13:28.606  1265  3840 W Uploader: No account for auth token provided
,03-31 10:13:28.829  1265  3840 W Uploader: No account for auth token provided
,03-31 10:13:28.894  3253  3312 I jxcore-log: # 27. should be able to call #startListeningForAdvertisements many times
03-31 10:13:28.894  3253  3312 I jxcore-log: 
,03-31 10:13:29.033  1265  3840 W Uploader:  no longer exists, so no auth token.
,03-31 10:13:29.334  1265  3840 W Uploader: No account for auth token provided
,03-31 10:13:29.423  3253  3312 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 10:13:29.423  3253  3312 I jxcore-log: 
03-31 10:13:29.425  3253  3312 I jxcore-log: DEBUG createNativeListener: listening 35661
03-31 10:13:29.425  3253  3312 I jxcore-log: 
,03-31 10:13:29.435  3253  3312 I io.jxcore.node.ConnectionHelper: start: Port number: 0, start advertisements: false
03-31 10:13:29.435  3253  3312 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 10:13:29.435  3253  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-31 10:13:29.436  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
03-31 10:13:29.436  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 10:13:29.436  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-31 10:13:29.444  3253  3312 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-31 10:13:29.445   822   840 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 10:13:29.455  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-31 10:13:29.463  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-31 10:13:29.463  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-31 10:13:29.463  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 10:13:29.463  3253  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 10:13:29.474  2153  2170 D BtGatt.GattService: registerClient() - UUID=8be1d1bd-648e-40bc-acfb-a9b4cecfc2f3
,03-31 10:13:29.475  2153  2216 D BtGatt.GattService: onClientRegistered() - UUID=8be1d1bd-648e-40bc-acfb-a9b4cecfc2f3, clientIf=5
,03-31 10:13:29.476  3253  3268 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-31 10:13:29.478  2153  2337 D BtGatt.GattService: start scan with filters
03-31 10:13:29.481  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-31 10:13:29.481  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 10:13:29.481  2153  2227 D BtGatt.ScanManager: handling starting scan
03-31 10:13:29.481  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-31 10:13:29.482  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-31 10:13:29.482  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
,03-31 10:13:29.483  3253  3253 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 10:13:29.484  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-31 10:13:29.485   822  1104 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-31 10:13:29.486  2153  2227 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20b02c6f
,03-31 10:13:29.493  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-31 10:13:29.493  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-31 10:13:29.494  3253  3312 I io.jxcore.node.ConnectionHelper: start: OK
,03-31 10:13:29.494  3253  3253 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-31 10:13:29.494  3253  3253 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 10:13:29.495  3253  3253 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-31 10:13:29.499  2153  2216 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,03-31 10:13:29.499  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 10:13:29.502  2153  2216 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15,
03-31 10:13:29.502  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 10:13:29.503  2153  2227 D BtGatt.ScanManager: Starting BLE batch scan
,03-31 10:13:29.503  2153  2227 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-31 10:13:29.506  2153  2216 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0,
03-31 10:13:29.506  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 10:13:29.508  2153  2216 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-31 10:13:29.508  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 10:13:29.516  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false},
03-31 10:13:29.516  3253  3312 I jxcore-log: 
03-31 10:13:29.518  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 10:13:29.518  3253  3312 I jxcore-log: 
,03-31 10:13:29.521  3253  3312 I jxcore-log: ok 96 error should be null
03-31 10:13:29.521  3253  3312 I jxcore-log: 
,03-31 10:13:29.523  3253  3312 I jxcore-log: ok 97 error should be null
03-31 10:13:29.523  3253  3312 I jxcore-log: 
,03-31 10:13:29.534  3253  3312 I io.jxcore.node.ConnectionHelper: start: Port number: 0, start advertisements: false,
,03-31 10:13:29.534  3253  3312 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 10:13:29.534  3253  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-31 10:13:29.534  3253  3312 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-31 10:13:29.534  3253  3312 I io.jxcore.node.ConnectionHelper: start: OK
,03-31 10:13:29.539  3253  3312 I jxcore-log: ok 98 error should be null,
03-31 10:13:29.539  3253  3312 I jxcore-log: 
03-31 10:13:29.540  3253  3312 I jxcore-log: ok 99 error should be null
03-31 10:13:29.540  3253  3312 I jxcore-log: 
,03-31 10:13:29.560  3253  3312 I jxcore-log: # teardown
03-31 10:13:29.560  3253  3312 I jxcore-log: 
,03-31 10:13:29.585  1265  3840 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,03-31 10:13:29.585  1265  3840 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-31 10:13:29.585  1265  3840 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 10:13:29.586  1265  3840 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 10:13:29.594  1265  3840 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 10:13:29.650  1265  3840 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-31 10:13:29.650  1265  3840 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-31 10:13:29.650  1265  3840 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-31 10:13:29.650  1265  3840 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-31 10:13:29.650  1265  3840 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-31 10:13:29.650  1265  3840 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-31 10:13:29.650  1265  3840 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-31 10:13:29.650  1265  3840 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-31 10:13:29.650  1265  3840 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-31 10:13:29.650  1265  3840 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-31 10:13:29.650  1265  3840 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-31 10:13:29.650  1265  3840 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-31 10:13:29.650  1265  3840 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-31 10:13:29.923  1265  3840 W Uploader: No account for auth token provided
,03-31 10:13:30.166  3253  3312 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-31 10:13:30.167  3253  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,03-31 10:13:30.167  3253  3312 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
03-31 10:13:30.167  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-31 10:13:30.167  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-31 10:13:30.167  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-31 10:13:30.168  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-31 10:13:30.169  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-31 10:13:30.169  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-31 10:13:30.175  2153  2171 D BtGatt.GattService: stopScan() - queue size =1
03-31 10:13:30.177  2153  2170 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-31 10:13:30.177  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 10:13:30.178  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 10:13:30.178  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-31 10:13:30.178  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,03-31 10:13:30.178  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,03-31 10:13:30.178  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false,
03-31 10:13:30.179  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-31 10:13:30.180  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-31 10:13:30.180  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-31 10:13:30.182  2153  2216 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-31 10:13:30.182  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 10:13:30.182  2153  2227 D BtGatt.ScanManager: stopping BLe Batch
03-31 10:13:30.183  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-31 10:13:30.183  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 10:13:30.183  3253  3253 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 10:13:30.183  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 10:13:30.184  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-31 10:13:30.185  2153  2216 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-31 10:13:30.185  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 10:13:30.185  2153  2227 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-31 10:13:30.187  2153  2216 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-31 10:13:30.187  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 10:13:30.190  3253  3312 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-31 10:13:30.190  3253  3312 I jxcore-log: 
,03-31 10:13:30.195  3253  3253 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
03-31 10:13:30.196   822  1429 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 10:13:30.206  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
03-31 10:13:30.207  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-31 10:13:30.207  3253  3253 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-31 10:13:30.213  3253  3253 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false,
03-31 10:13:30.214  3253  3253 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-31 10:13:30.214  3253  3253 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 10:13:30.214  3253  3253 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 10:13:30.215  3253  3312 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-31 10:13:30.215  3253  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 10:13:30.215  3253  3312 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 10:13:30.217  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 10:13:30.217  3253  3312 I jxcore-log: 
,03-31 10:13:30.220  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false},
03-31 10:13:30.220  3253  3312 I jxcore-log: 
,03-31 10:13:30.227  3253  3312 I jxcore-log: ok 100 error should be null
03-31 10:13:30.227  3253  3312 I jxcore-log: ,
03-31 10:13:30.227  3253  3312 I jxcore-log: ok 101 error should be null
03-31 10:13:30.227  3253  3312 I jxcore-log: 
,03-31 10:13:30.236  3253  3312 I jxcore-log: # setup
03-31 10:13:30.236  3253  3312 I jxcore-log: 
,03-31 10:13:30.255  1265  3840 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
03-31 10:13:30.255  1265  3840 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 10:13:30.255  1265  3840 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 10:13:30.255  1265  3840 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 10:13:30.261  1265  3840 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 10:13:30.302  1265  3840 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-31 10:13:30.302  1265  3840 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-31 10:13:30.302  1265  3840 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-31 10:13:30.302  1265  3840 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-31 10:13:30.302  1265  3840 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-31 10:13:30.302  1265  3840 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-31 10:13:30.302  1265  3840 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-31 10:13:30.302  1265  3840 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-31 10:13:30.302  1265  3840 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-31 10:13:30.302  1265  3840 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-31 10:13:30.302  1265  3840 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-31 10:13:30.302  1265  3840 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-31 10:13:30.302  1265  3840 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-31 10:13:30.541  1265  3840 W Uploader: No account for auth token provided
,03-31 10:13:30.764  3253  3312 I jxcore-log: # 28. should be able to call #startUpdateAdvertisingAndListening many times
03-31 10:13:30.764  3253  3312 I jxcore-log: 
,03-31 10:13:31.278  3253  3312 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 10:13:31.278  3253  3312 I jxcore-log: 
,03-31 10:13:31.292  3253  3312 I jxcore-log: DEBUG createNativeListener: listening 51950
03-31 10:13:31.292  3253  3312 I jxcore-log: 
,03-31 10:13:31.309  3253  3312 I io.jxcore.node.ConnectionHelper: start: Port number: 51950, start advertisements: true
03-31 10:13:31.310  3253  3312 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-31 10:13:31.310  3253  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-31 10:13:31.310  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-31 10:13:31.317  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-31 10:13:31.317  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-31 10:13:31.317  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 10:13:31.318  3253  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 10:13:31.325  2153  2337 D BtGatt.GattService: registerClient() - UUID=c866efc9-946b-4086-aaa0-f56103880782
,03-31 10:13:31.326  2153  2216 D BtGatt.GattService: onClientRegistered() - UUID=c866efc9-946b-4086-aaa0-f56103880782, clientIf=5
03-31 10:13:31.327  3253  3268 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-31 10:13:31.328  2153  2171 D BtGatt.GattService: start scan with filters
,03-31 10:13:31.330  2153  2227 D BtGatt.ScanManager: handling starting scan
,03-31 10:13:31.330  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-31 10:13:31.330  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 10:13:31.330  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-31 10:13:31.331  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-31 10:13:31.331  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 10:13:31.332  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-31 10:13:31.332  3253  3253 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 10:13:31.332  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,03-31 10:13:31.334  3253  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
,03-31 10:13:31.338  2153  2216 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,03-31 10:13:31.338  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 10:13:31.340  2153  2216 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-31 10:13:31.340  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 10:13:31.341  2153  2227 D BtGatt.ScanManager: Starting BLE batch scan
03-31 10:13:31.341  2153  2227 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-31 10:13:31.342  3253  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-31 10:13:31.343  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 10:13:31.343  3253  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-31 10:13:31.344  2153  2216 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-31 10:13:31.344  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 10:13:31.346  2153  2216 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-31 10:13:31.346  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 10:13:31.355  2153  2170 D BtGatt.GattService: registerClient() - UUID=3ba2fd84-76a5-4836-8b0a-fef90103cb49
,03-31 10:13:31.356  2153  2216 D BtGatt.GattService: onClientRegistered() - UUID=3ba2fd84-76a5-4836-8b0a-fef90103cb49, clientIf=6
,03-31 10:13:31.357  3253  3269 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-31 10:13:31.361  2153  2226 D BtGatt.AdvertiseManager: message : 0,
,03-31 10:13:31.365  2153  2226 D BtGatt.AdvertiseManager: starting multi advertising
,03-31 10:13:31.368  2153  2216 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-31 10:13:31.371  2153  2216 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-31 10:13:31.372  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-31 10:13:31.372  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-31 10:13:31.373   822  1410 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 10:13:31.377  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-31 10:13:31.377  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-31 10:13:31.377  3253  3312 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-31 10:13:31.377  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-31 10:13:31.379  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-31 10:13:31.380  3253  3312 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,03-31 10:13:31.380  3253  3312 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-31 10:13:31.380  3253  3312 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-31 10:13:31.380  3253  3312 I io.jxcore.node.ConnectionHelper: start: OK
,03-31 10:13:31.381  3253  3253 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-31 10:13:31.381  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,03-31 10:13:31.381  3253  3253 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-31 10:13:31.381  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-31 10:13:31.381  3253  3253 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
,03-31 10:13:31.382  3253  3253 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-31 10:13:31.382  3253  3253 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-31 10:13:31.382  3253  3253 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-31 10:13:31.382  3253  3253 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-31 10:13:31.382  3253  3253 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 10:13:31.383  3253  3253 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-31 10:13:31.383  3253  3253 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-31 10:13:31.384   822  3823 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 10:13:31.387  3253  3845 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-31 10:13:31.390  3253  3845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
03-31 10:13:31.395  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 10:13:31.395  3253  3312 I jxcore-log: 
,03-31 10:13:31.397  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 10:13:31.397  3253  3312 I jxcore-log: 
03-31 10:13:31.398  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-31 10:13:31.398  3253  3312 I jxcore-log: 
,03-31 10:13:31.400  3253  3312 I jxcore-log: ok 102 error should be null
,03-31 10:13:31.400  3253  3312 I jxcore-log: 
03-31 10:13:31.400  3253  3312 I jxcore-log: ok 103 error should be null
03-31 10:13:31.400  3253  3312 I jxcore-log: 
,03-31 10:13:31.409  3253  3312 I io.jxcore.node.ConnectionHelper: start: Port number: 51950, start advertisements: true
,03-31 10:13:31.410  3253  3312 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-31 10:13:31.410  3253  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-31 10:13:31.410  3253  3312 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-31 10:13:31.410  3253  3312 I io.jxcore.node.ConnectionHelper: start: OK
,03-31 10:13:31.418  3253  3312 I jxcore-log: ok 104 error should be null
,03-31 10:13:31.418  3253  3312 I jxcore-log: 
03-31 10:13:31.419  3253  3312 I jxcore-log: ok 105 error should be null
03-31 10:13:31.419  3253  3312 I jxcore-log: 
,03-31 10:13:31.425  3253  3312 I jxcore-log: # teardown
,03-31 10:13:31.425  3253  3312 I jxcore-log: 
,03-31 10:13:32.355  2153  2153 D BtGatt.ScanManager: awakened up at time 217272
,03-31 10:13:32.359  2153  2227 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5,
,03-31 10:13:32.366  2153  2216 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2,
,03-31 10:13:32.366  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
03-31 10:13:32.367  2153  2216 D BtGatt.GattService: current time is 217284548457
,03-31 10:13:32.367  2153  2216 D BtGatt.GattService: Batch record : [-42, -10, -22, 53, 40, 78, 1, -128, -81, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -63, 0, 0, 0, 0],
,03-31 10:13:32.369  2153  2216 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81],
,03-31 10:13:32.371  2153  2216 D BtGatt.GattService: ScanRecord : []
03-31 10:13:32.379  3253  3253 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 1
,03-31 10:13:32.380  3253  3253 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
,03-31 10:13:32.387  3253  3312 I jxcore-log: DEBUG createPeerListener: createPeerListener
03-31 10:13:32.387  3253  3312 I jxcore-log: 
,03-31 10:13:32.395  3253  3312 I jxcore-log: DEBUG createPeerListener: pleaseConnect= false
03-31 10:13:32.395  3253  3312 I jxcore-log: 
,03-31 10:13:33.382  2153  2153 D BtGatt.ScanManager: awakened up at time 218299
,03-31 10:13:33.385  2153  2227 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-31 10:13:33.396  2153  2216 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-31 10:13:33.396  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 10:13:33.396  2153  2216 D BtGatt.GattService: current time is 218313786373
03-31 10:13:33.396  2153  2216 D BtGatt.GattService: Batch record : [-42, -10, -22, 53, 40, 78, 1, -128, -80, 9, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -63, 10, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
,03-31 10:13:33.397  2153  2216 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-31 10:13:33.398  2153  2216 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-31 10:13:33.400  3253  3253 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> E0:DB:10:14:E2:C0], added - the peer count is 2
,03-31 10:13:33.401  3253  3253 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
03-31 10:13:33.401  3253  3253 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> E0:DB:10:14:E2:C0], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 
,03-31 10:13:33.406  3253  3312 I jxcore-log: DEBUG createPeerListener: createPeerListener
03-31 10:13:33.406  3253  3312 I jxcore-log: 
,03-31 10:13:33.414  3253  3312 I jxcore-log: DEBUG createPeerListener: pleaseConnect= false
03-31 10:13:33.414  3253  3312 I jxcore-log: 
,03-31 10:13:33.515  3253  3312 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 10:13:33.516  3253  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-31 10:13:33.516  3253  3312 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-31 10:13:33.516  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-31 10:13:33.516  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-31 10:13:33.517  3253  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-31 10:13:33.517  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-31 10:13:33.517  3253  3845 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
,03-31 10:13:33.517  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-31 10:13:33.517  3253  3845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-31 10:13:33.517  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-31 10:13:33.518  3253  3845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-31 10:13:33.518  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,03-31 10:13:33.519  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-31 10:13:33.519  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-31 10:13:33.523  2153  2171 D BtGatt.GattService: stopScan() - queue size =1
03-31 10:13:33.525  2153  2337 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-31 10:13:33.525  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 10:13:33.525  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 10:13:33.525  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-31 10:13:33.525  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-31 10:13:33.525  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING],
03-31 10:13:33.526  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-31 10:13:33.526  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-31 10:13:33.527  2153  2216 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-31 10:13:33.527  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 10:13:33.527  2153  2227 D BtGatt.ScanManager: stopping BLe Batch
03-31 10:13:33.529  2153  2226 D BtGatt.AdvertiseManager: message : 1
03-31 10:13:33.530  2153  2216 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-31 10:13:33.530  2153  2226 D BtGatt.AdvertiseManager: stop advertise for client 6
03-31 10:13:33.530  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 10:13:33.531  2153  2227 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-31 10:13:33.532  2153  2216 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-31 10:13:33.532  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
03-31 10:13:33.533  2153  2216 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-31 10:13:33.534  2153  2216 D BtGatt.GattService: Client app is not null!
03-31 10:13:33.535  2153  2337 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-31 10:13:33.536  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-31 10:13:33.536  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-31 10:13:33.536  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-31 10:13:33.536  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-31 10:13:33.536  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-31 10:13:33.536  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 10:13:33.536  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-31 10:13:33.536  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-31 10:13:33.537  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-31 10:13:33.537  3253  3312 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-31 10:13:33.537  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 10:13:33.537  3253  3253 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 10:13:33.537  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-31 10:13:33.537  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-31 10:13:33.554  3253  3253 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
,03-31 10:13:33.554   822  1454 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 10:13:33.557  3253  3312 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-31 10:13:33.557  3253  3312 I jxcore-log: 
,03-31 10:13:33.559  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-31 10:13:33.560  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-31 10:13:33.560  3253  3253 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-31 10:13:33.560  3253  3253 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-31 10:13:33.560  3253  3253 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-31 10:13:33.563  3253  3253 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-31 10:13:33.563  3253  3253 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 10:13:33.563  3253  3253 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 10:13:33.564  3253  3253 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 10:13:33.564  3253  3253 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 10:13:33.564  3253  3253 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-31 10:13:33.564  3253  3312 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-31 10:13:33.565  3253  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 10:13:33.565  3253  3312 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 10:13:33.566  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-31 10:13:33.566  3253  3312 I jxcore-log: 
,03-31 10:13:33.567  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 10:13:33.567  3253  3312 I jxcore-log: 
,03-31 10:13:33.569  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 10:13:33.569  3253  3312 I jxcore-log: 
,03-31 10:13:33.576  3253  3312 I jxcore-log: ok 106 error should be null
,03-31 10:13:33.576  3253  3312 I jxcore-log: 
03-31 10:13:33.576  3253  3312 I jxcore-log: ok 107 error should be null
03-31 10:13:33.576  3253  3312 I jxcore-log: 
03-31 10:13:33.582  3253  3312 I jxcore-log: # setup
03-31 10:13:33.582  3253  3312 I jxcore-log: 
,03-31 10:13:33.888  3253  3312 I jxcore-log: # 29. should be able to call #stopAdvertisingAndListening many times
03-31 10:13:33.888  3253  3312 I jxcore-log: 
,03-31 10:13:34.140  3253  3312 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 10:13:34.140  3253  3312 I jxcore-log: 
,03-31 10:13:34.143  3253  3312 I jxcore-log: DEBUG createNativeListener: listening 34628
03-31 10:13:34.143  3253  3312 I jxcore-log: 
,03-31 10:13:34.148  3253  3312 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 10:13:34.148  3253  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 10:13:34.148  3253  3312 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 10:13:34.151  3253  3312 I jxcore-log: ok 108 error should be null
03-31 10:13:34.151  3253  3312 I jxcore-log: 
,03-31 10:13:34.152  3253  3312 I jxcore-log: ok 109 error should be null
03-31 10:13:34.152  3253  3312 I jxcore-log: 
,03-31 10:13:34.156  3253  3312 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 10:13:34.156  3253  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-31 10:13:34.156  3253  3312 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 10:13:34.159  3253  3312 I jxcore-log: ok 110 error should be null
,03-31 10:13:34.159  3253  3312 I jxcore-log: 
03-31 10:13:34.160  3253  3312 I jxcore-log: ok 111 error should be null
03-31 10:13:34.160  3253  3312 I jxcore-log: 
,03-31 10:13:34.167  3253  3312 I jxcore-log: # teardown
,03-31 10:13:34.167  3253  3312 I jxcore-log: 
,03-31 10:13:34.275  3253  3312 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 10:13:34.275  3253  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 10:13:34.275  3253  3312 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-31 10:13:34.277  3253  3312 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-31 10:13:34.277  3253  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 10:13:34.277  3253  3312 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 10:13:34.285  3253  3312 I jxcore-log: ok 112 error should be null
,03-31 10:13:34.285  3253  3312 I jxcore-log: 
03-31 10:13:34.286  3253  3312 I jxcore-log: ok 113 error should be null
03-31 10:13:34.286  3253  3312 I jxcore-log: 
03-31 10:13:34.291  3253  3312 I jxcore-log: # setup,
03-31 10:13:34.291  3253  3312 I jxcore-log: 
,03-31 10:13:34.365  3253  3312 I jxcore-log: # 30. #start should fail if called twice in a row
03-31 10:13:34.365  3253  3312 I jxcore-log: 
,03-31 10:13:34.585  3253  3312 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 10:13:34.585  3253  3312 I jxcore-log: 
03-31 10:13:34.587  3253  3312 I jxcore-log: DEBUG createNativeListener: listening 36987
03-31 10:13:34.587  3253  3312 I jxcore-log: 
,03-31 10:13:34.589  3253  3312 I jxcore-log: ok 114 first call should succeed
03-31 10:13:34.589  3253  3312 I jxcore-log: 
03-31 10:13:34.590  3253  3312 I jxcore-log: ok 115 first call should succeed
03-31 10:13:34.590  3253  3312 I jxcore-log: 
,03-31 10:13:34.592  3253  3312 I jxcore-log: ok 116 specific error should be returned
03-31 10:13:34.592  3253  3312 I jxcore-log: 
03-31 10:13:34.595  3253  3312 I jxcore-log: # teardown
03-31 10:13:34.595  3253  3312 I jxcore-log: 
,03-31 10:13:34.774  3253  3312 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 10:13:34.774  3253  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 10:13:34.774  3253  3312 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-31 10:13:34.776  3253  3312 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-31 10:13:34.776  3253  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-31 10:13:34.776  3253  3312 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 10:13:34.782  3253  3312 I jxcore-log: ok 117 error should be null
03-31 10:13:34.782  3253  3312 I jxcore-log: 
,03-31 10:13:34.783  3253  3312 I jxcore-log: ok 118 error should be null
03-31 10:13:34.783  3253  3312 I jxcore-log: 
,03-31 10:13:34.788  3253  3312 I jxcore-log: # setup
03-31 10:13:34.788  3253  3312 I jxcore-log: 
,03-31 10:13:34.965  3253  3312 I jxcore-log: # 31. does not emit duplicate discoveryAdvertisingStateUpdate
03-31 10:13:34.965  3253  3312 I jxcore-log: 
,03-31 10:13:35.154  3253  3312 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 10:13:35.154  3253  3312 I jxcore-log: 
,03-31 10:13:35.156  3253  3312 I jxcore-log: DEBUG createNativeListener: listening 50129
03-31 10:13:35.156  3253  3312 I jxcore-log: 
,03-31 10:13:35.165  3253  3312 I io.jxcore.node.ConnectionHelper: start: Port number: 51950, start advertisements: false
,03-31 10:13:35.165  3253  3312 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 10:13:35.165  3253  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-31 10:13:35.165  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-31 10:13:35.170  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-31 10:13:35.170  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 10:13:35.170  3253  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 10:13:35.175  2153  2171 D BtGatt.GattService: registerClient() - UUID=8d2afba6-0999-42ba-b575-fd6170da4b87,
03-31 10:13:35.176  2153  2216 D BtGatt.GattService: onClientRegistered() - UUID=8d2afba6-0999-42ba-b575-fd6170da4b87, clientIf=5
,03-31 10:13:35.177  3253  3269 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-31 10:13:35.177  2153  2170 D BtGatt.GattService: start scan with filters
03-31 10:13:35.178  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-31 10:13:35.178  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 10:13:35.179  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-31 10:13:35.179  2153  2227 D BtGatt.ScanManager: handling starting scan
03-31 10:13:35.179  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-31 10:13:35.179  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false,
03-31 10:13:35.179  3253  3253 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 10:13:35.180  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-31 10:13:35.182   822  1412 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 10:13:35.185  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 10:13:35.186  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-31 10:13:35.186  3253  3253 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only,
03-31 10:13:35.186  3253  3253 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 10:13:35.186  3253  3253 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-31 10:13:35.186  3253  3312 I io.jxcore.node.ConnectionHelper: start: OK
03-31 10:13:35.189  2153  2216 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-31 10:13:35.190  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 10:13:35.191  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 10:13:35.191  3253  3312 I jxcore-log: 
03-31 10:13:35.192  2153  2216 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,03-31 10:13:35.192  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 10:13:35.192  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 10:13:35.192  3253  3312 I jxcore-log: 
03-31 10:13:35.192  2153  2227 D BtGatt.ScanManager: Starting BLE batch scan
03-31 10:13:35.192  2153  2227 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-31 10:13:35.196  2153  2216 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-31 10:13:35.196  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 10:13:35.198  2153  2216 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,03-31 10:13:35.199  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 10:13:35.206  3253  3312 I io.jxcore.node.ConnectionHelper: start: Port number: 50129, start advertisements: true,
03-31 10:13:35.206  3253  3312 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-31 10:13:35.206  3253  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-31 10:13:35.206  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-31 10:13:35.209  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
03-31 10:13:35.209  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
03-31 10:13:35.209  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,03-31 10:13:35.210  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61",
03-31 10:13:35.210  3253  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-31 10:13:35.210  3253  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-31 10:13:35.210  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 10:13:35.210  3253  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-31 10:13:35.214  2153  2170 D BtGatt.GattService: registerClient() - UUID=1dfcf9cb-ac2d-4461-ba6b-80b9016f5cdb
03-31 10:13:35.214  2153  2216 D BtGatt.GattService: onClientRegistered() - UUID=1dfcf9cb-ac2d-4461-ba6b-80b9016f5cdb, clientIf=6
03-31 10:13:35.215  3253  3268 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6,
03-31 10:13:35.216  2153  2226 D BtGatt.AdvertiseManager: message : 0
03-31 10:13:35.219  2153  2226 D BtGatt.AdvertiseManager: starting multi advertising
03-31 10:13:35.222  2153  2216 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-31 10:13:35.225  2153  2216 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0,
03-31 10:13:35.226  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-31 10:13:35.226  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-31 10:13:35.226  3253  3253 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-31 10:13:35.226  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-31 10:13:35.228  3253  3253 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
,03-31 10:13:35.228  3253  3253 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-31 10:13:35.228  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-31 10:13:35.228   822   840 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 10:13:35.231  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-31 10:13:35.231  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-31 10:13:35.232  3253  3253 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-31 10:13:35.232  3253  3312 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-31 10:13:35.232  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 10:13:35.232  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-31 10:13:35.233  3253  3312 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,03-31 10:13:35.233  3253  3312 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,03-31 10:13:35.233  3253  3312 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-31 10:13:35.233  3253  3253 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-31 10:13:35.233  3253  3253 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 10:13:35.233  3253  3253 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,03-31 10:13:35.233  3253  3312 I io.jxcore.node.ConnectionHelper: start: OK
03-31 10:13:35.239   822  1384 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-31 10:13:35.242  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-31 10:13:35.242  3253  3312 I jxcore-log: 
03-31 10:13:35.242  3253  3847 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-31 10:13:35.249  3253  3312 I jxcore-log: ok 119 called only once
03-31 10:13:35.249  3253  3312 I jxcore-log: 
,03-31 10:13:35.250  3253  3312 I jxcore-log: ok 120 discovery state matches
03-31 10:13:35.250  3253  3312 I jxcore-log: 
03-31 10:13:35.250  3253  3312 I jxcore-log: ok 121 advertising state matches
03-31 10:13:35.250  3253  3312 I jxcore-log: 
03-31 10:13:35.252  3253  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-31 10:13:35.260  3253  3312 I jxcore-log: # teardown
03-31 10:13:35.260  3253  3312 I jxcore-log: 
,03-31 10:13:35.604  3253  3312 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-31 10:13:35.604  3253  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-31 10:13:35.604  3253  3312 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-31 10:13:35.604  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-31 10:13:35.604  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,03-31 10:13:35.605  3253  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-31 10:13:35.605  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-31 10:13:35.605  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-31 10:13:35.605  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-31 10:13:35.605  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-31 10:13:35.605  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-31 10:13:35.605  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-31 10:13:35.605  3253  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-31 10:13:35.605  3253  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,03-31 10:13:35.606  3253  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,03-31 10:13:35.614  2153  2337 D BtGatt.GattService: stopScan() - queue size =1
,03-31 10:13:35.624  2153  2337 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-31 10:13:35.624  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 10:13:35.625  2153  2216 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-31 10:13:35.625  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 10:13:35.625  2153  2227 D BtGatt.ScanManager: stopping BLe Batch
03-31 10:13:35.624  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 10:13:35.627  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,03-31 10:13:35.627  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-31 10:13:35.627  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
,03-31 10:13:35.627  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-31 10:13:35.627  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-31 10:13:35.628  2153  2216 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-31 10:13:35.628  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 10:13:35.629  2153  2227 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-31 10:13:35.629  2153  2226 D BtGatt.AdvertiseManager: message : 1
03-31 10:13:35.630  2153  2226 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-31 10:13:35.633  2153  2216 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-31 10:13:35.633  2153  2216 D BtGatt.GattService: Client app is not null!
,03-31 10:13:35.635  2153  2337 D BtGatt.GattService: unregisterClient() - clientIf=6
03-31 10:13:35.635  2153  2216 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-31 10:13:35.635  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
,03-31 10:13:35.635  2153  2216 D BtGatt.GattService: current time is 220553035331
03-31 10:13:35.636  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
03-31 10:13:35.636  2153  2216 D BtGatt.GattService: Batch record : [-14, -36, 53, 107, 119, 113, 1, -128, -80, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -63, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
,03-31 10:13:35.636  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-31 10:13:35.636  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-31 10:13:35.636  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-31 10:13:35.636  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-31 10:13:35.636  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 10:13:35.636  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-31 10:13:35.636  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-31 10:13:35.636  2153  2216 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-31 10:13:35.637  2153  2216 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-31 10:13:35.638  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-31 10:13:35.638  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 10:13:35.638  3253  3253 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 10:13:35.638  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
03-31 10:13:35.639  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-31 10:13:35.645  3253  3253 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-31 10:13:35.645   822  1384 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-31 10:13:35.647  3253  3312 I jxcore-log: INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
03-31 10:13:35.647  3253  3312 I jxcore-log: 
,03-31 10:13:35.648  3253  3312 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-31 10:13:35.648  3253  3312 I jxcore-log: 
,03-31 10:13:35.650  3253  3312 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-31 10:13:35.650  3253  3312 I jxcore-log: 
,03-31 10:13:35.657  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-31 10:13:35.658  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-31 10:13:35.658  3253  3253 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-31 10:13:35.662  3253  3253 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-31 10:13:35.662  3253  3253 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,03-31 10:13:35.662  3253  3253 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-31 10:13:35.662  3253  3253 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 10:13:35.662  3253  3253 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 10:13:35.662  3253  3253 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 10:13:35.662  3253  3253 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 10:13:35.663  3253  3253 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-31 10:13:35.663  3253  3312 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-31 10:13:35.663  3253  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 10:13:35.663  3253  3312 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-31 10:13:35.665  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-31 10:13:35.665  3253  3312 I jxcore-log: 
,03-31 10:13:35.666  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 10:13:35.666  3253  3312 I jxcore-log: 
,03-31 10:13:35.667  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 10:13:35.667  3253  3312 I jxcore-log: 
,03-31 10:13:35.671  3253  3312 I jxcore-log: ok 122 error should be null
03-31 10:13:35.671  3253  3312 I jxcore-log: 
,03-31 10:13:35.672  3253  3312 I jxcore-log: ok 123 error should be null
03-31 10:13:35.672  3253  3312 I jxcore-log: 
,03-31 10:13:35.678  3253  3312 I jxcore-log: # setup
03-31 10:13:35.678  3253  3312 I jxcore-log: 
,03-31 10:13:36.496  3253  3312 I jxcore-log: # 32. does not send duplicate availability changes
03-31 10:13:36.496  3253  3312 I jxcore-log: 
,03-31 10:13:36.708  3253  3312 I jxcore-log: ok 124 should be called once
03-31 10:13:36.708  3253  3312 I jxcore-log: 
,03-31 10:13:36.711  3253  3312 I jxcore-log: ok 125 should not have been called more than once
03-31 10:13:36.711  3253  3312 I jxcore-log: 
,03-31 10:13:36.713  3253  3312 I jxcore-log: # teardown
03-31 10:13:36.713  3253  3312 I jxcore-log: 
,03-31 10:13:37.303  3253  3312 I jxcore-log: ok 126 error should be null
03-31 10:13:37.303  3253  3312 I jxcore-log: 
03-31 10:13:37.304  3253  3312 I jxcore-log: ok 127 error should be null
03-31 10:13:37.304  3253  3312 I jxcore-log: 
,03-31 10:13:37.306  3253  3312 I jxcore-log: # setup
03-31 10:13:37.306  3253  3312 I jxcore-log: 
,03-31 10:13:37.475  3253  3312 I jxcore-log: # 33. can get the network status
03-31 10:13:37.475  3253  3312 I jxcore-log: 
,03-31 10:13:37.583  3253  3312 I jxcore-log: ok 128 network status should have certain non-empty properties
03-31 10:13:37.583  3253  3312 I jxcore-log: 
,03-31 10:13:37.585  3253  3312 I jxcore-log: # teardown
03-31 10:13:37.585  3253  3312 I jxcore-log: 
,03-31 10:13:37.892  3253  3312 I jxcore-log: ok 129 error should be null
03-31 10:13:37.892  3253  3312 I jxcore-log: 
,03-31 10:13:37.894  3253  3312 I jxcore-log: ok 130 error should be null
03-31 10:13:37.894  3253  3312 I jxcore-log: 
,03-31 10:13:37.907  3253  3312 I jxcore-log: # setup
03-31 10:13:37.907  3253  3312 I jxcore-log: 
,03-31 10:13:38.080  3253  3312 I jxcore-log: # 34. wifi peer is marked unavailable if announcements stop
03-31 10:13:38.080  3253  3312 I jxcore-log: 
,03-31 10:13:38.311  3253  3312 I jxcore-log: ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined
03-31 10:13:38.311  3253  3312 I jxcore-log: 
,03-31 10:13:38.336  3253  3312 I jxcore-log: ok 131 host address should match
03-31 10:13:38.336  3253  3312 I jxcore-log: 
,03-31 10:13:38.337  3253  3312 I jxcore-log: ok 132 port should match
03-31 10:13:38.337  3253  3312 I jxcore-log: 
,03-31 10:13:39.504  1265  1265 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 10:13:39.597  1265  3209 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
03-31 10:13:39.598  1265  3209 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 10:13:39.598  1265  3209 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 10:13:39.598  1265  3209 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 10:13:39.609  1265  3209 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 10:13:39.648  3678  3678 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
03-31 10:13:39.649  3678  3678 D Finsky  : [1] 5.onFinished: Installation state replication failed.
,03-31 10:13:39.650  3678  3678 D Finsky  : [1] 5.onFinished: Scheduling replication attempt 2.
,03-31 10:13:40.314  3253  3312 I jxcore-log: ok 133 host address should be null
03-31 10:13:40.314  3253  3312 I jxcore-log: 
,03-31 10:13:40.316  3253  3312 I jxcore-log: ok 134 port should should be null
03-31 10:13:40.316  3253  3312 I jxcore-log: 
,03-31 10:13:40.329  3253  3312 I jxcore-log: # teardown
03-31 10:13:40.329  3253  3312 I jxcore-log: 
,03-31 10:13:40.447  3253  3312 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-31 10:13:40.447  3253  3312 I jxcore-log: 
,03-31 10:13:40.449  3253  3312 I jxcore-log: ok 135 error should be null
03-31 10:13:40.449  3253  3312 I jxcore-log: 
,03-31 10:13:40.450  3253  3312 I jxcore-log: ok 136 error should be null
03-31 10:13:40.450  3253  3312 I jxcore-log: 
03-31 10:13:40.452  3253  3312 I jxcore-log: # setup
03-31 10:13:40.452  3253  3312 I jxcore-log: 
,03-31 10:13:40.919  3253  3312 I jxcore-log: # 35. Can call start/stopListeningForAdvertisements
03-31 10:13:40.919  3253  3312 I jxcore-log: 
,03-31 10:13:41.014  1237  1407 I Keyboard.Facilitator.LanguageModelFlusher: run()
,03-31 10:13:41.014  1237  1407 I Keyboard.Facilitator: flushDynamicLanguageModels()
,03-31 10:13:41.053  1265  1265 I ConfigService: onCreate
,03-31 10:13:41.161  3253  3312 I io.jxcore.node.ConnectionHelper: start: Port number: 50129, start advertisements: false
,03-31 10:13:41.161  3253  3312 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 10:13:41.161  3253  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-31 10:13:41.161  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-31 10:13:41.171  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...,
03-31 10:13:41.171  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 10:13:41.171  3253  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 10:13:41.180  2153  2170 D BtGatt.GattService: registerClient() - UUID=2dc1e90d-7309-47ac-954d-c26ec68f271e
,03-31 10:13:41.181  2153  2216 D BtGatt.GattService: onClientRegistered() - UUID=2dc1e90d-7309-47ac-954d-c26ec68f271e, clientIf=5
03-31 10:13:41.182  3253  3268 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-31 10:13:41.183  2153  2171 D BtGatt.GattService: start scan with filters
,03-31 10:13:41.185  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-31 10:13:41.185  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-31 10:13:41.186  2153  2227 D BtGatt.ScanManager: handling starting scan
03-31 10:13:41.186  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-31 10:13:41.187  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-31 10:13:41.188  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 10:13:41.189  3253  3253 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-31 10:13:41.189  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-31 10:13:41.190   822  1329 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 10:13:41.198  2153  2216 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,03-31 10:13:41.198  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 10:13:41.200  2153  2216 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-31 10:13:41.200  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 10:13:41.201  2153  2227 D BtGatt.ScanManager: Starting BLE batch scan
03-31 10:13:41.201  2153  2227 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-31 10:13:41.203  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 10:13:41.203  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK,
03-31 10:13:41.204  3253  3253 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,03-31 10:13:41.204  3253  3253 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 10:13:41.204  3253  3253 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 10:13:41.205  3253  3312 I io.jxcore.node.ConnectionHelper: start: OK
03-31 10:13:41.205  2153  2216 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,03-31 10:13:41.206  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 10:13:41.208  2153  2216 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-31 10:13:41.208  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 10:13:41.211  3253  3312 I jxcore-log: ok 137 Can call startListeningForAdvertisements without error
03-31 10:13:41.211  3253  3312 I jxcore-log: 
03-31 10:13:41.214  3253  3312 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-31 10:13:41.214  3253  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 10:13:41.214  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-31 10:13:41.214  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-31 10:13:41.216  2153  2171 D BtGatt.GattService: stopScan() - queue size =1
,03-31 10:13:41.220  2153  2216 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16,
03-31 10:13:41.221  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 10:13:41.221  2153  2171 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-31 10:13:41.221  2153  2227 D BtGatt.ScanManager: stopping BLe Batch
03-31 10:13:41.221  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-31 10:13:41.222  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 10:13:41.222  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-31 10:13:41.222  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,03-31 10:13:41.222  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,03-31 10:13:41.222  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 10:13:41.222  3253  3253 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 10:13:41.222  3253  3253 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 10:13:41.222  3253  3253 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 10:13:41.223  2153  2216 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-31 10:13:41.224  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 10:13:41.224  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 10:13:41.224  3253  3312 I jxcore-log: 
03-31 10:13:41.224  2153  2227 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-31 10:13:41.225  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 10:13:41.225  3253  3312 I jxcore-log: 
03-31 10:13:41.225  2153  2216 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-31 10:13:41.226  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 10:13:41.227  3253  3312 I jxcore-log: ok 138 Can call stopListeningForAdvertisements without error
03-31 10:13:41.227  3253  3312 I jxcore-log: 
03-31 10:13:41.232  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 10:13:41.232  3253  3312 I jxcore-log: 
,03-31 10:13:41.234  3253  3312 I jxcore-log: # teardown
03-31 10:13:41.234  3253  3312 I jxcore-log: 
,03-31 10:13:41.630  3253  3312 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-31 10:13:41.631  3253  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 10:13:41.631  3253  3312 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 10:13:41.637  3253  3312 I jxcore-log: ok 139 Should be able to call stopListeningForAdvertisments in teardown
03-31 10:13:41.637  3253  3312 I jxcore-log: 
,03-31 10:13:41.640  3253  3312 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 10:13:41.640  3253  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 10:13:41.640  3253  3312 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
03-31 10:13:41.640  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-31 10:13:41.641  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,03-31 10:13:41.641  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-31 10:13:41.641  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-31 10:13:41.642  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-31 10:13:41.645  3253  3312 D BluetoothLeScanner: could not find callback wrapper
03-31 10:13:41.645  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
,03-31 10:13:41.649  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-31 10:13:41.649  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-31 10:13:41.649  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-31 10:13:41.650  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,03-31 10:13:41.650  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 10:13:41.650  3253  3253 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-31 10:13:41.650  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 10:13:41.650  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-31 10:13:41.660  3253  3253 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-31 10:13:41.660   822  1429 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
,03-31 10:13:41.669  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-31 10:13:41.671  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-31 10:13:41.671  3253  3253 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-31 10:13:41.676  3253  3253 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 10:13:41.676  3253  3253 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-31 10:13:41.676  3253  3253 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-31 10:13:41.679  3253  3312 I jxcore-log: ok 140 Should be able to call stopAdvertisingAndListening in teardown
03-31 10:13:41.679  3253  3312 I jxcore-log: 
,03-31 10:13:41.693  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 10:13:41.693  3253  3312 I jxcore-log: 
,03-31 10:13:41.697  3253  3312 I jxcore-log: # setup
03-31 10:13:41.697  3253  3312 I jxcore-log: 
,03-31 10:13:41.855  3253  3312 I jxcore-log: # 36. Calling startListeningForAdvertisements twice is NOT an error
03-31 10:13:41.855  3253  3312 I jxcore-log: 
,03-31 10:13:42.413  3253  3312 I io.jxcore.node.ConnectionHelper: start: Port number: 50129, start advertisements: false
03-31 10:13:42.413  3253  3312 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 10:13:42.413  3253  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-31 10:13:42.414  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-31 10:13:42.421  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-31 10:13:42.422  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 10:13:42.422  3253  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 10:13:42.431  2153  2337 D BtGatt.GattService: registerClient() - UUID=91b4c1d3-d773-434b-a8f1-284ca10b1c37
,03-31 10:13:42.432  2153  2216 D BtGatt.GattService: onClientRegistered() - UUID=91b4c1d3-d773-434b-a8f1-284ca10b1c37, clientIf=5
,03-31 10:13:42.433  3253  3268 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-31 10:13:42.434  2153  2170 D BtGatt.GattService: start scan with filters
,03-31 10:13:42.437  2153  2227 D BtGatt.ScanManager: handling starting scan
,03-31 10:13:42.439  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-31 10:13:42.439  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-31 10:13:42.441  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-31 10:13:42.441  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,03-31 10:13:42.441  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 10:13:42.442  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK,
03-31 10:13:42.442  3253  3253 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-31 10:13:42.443   822  1201 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 10:13:42.447  2153  2216 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,03-31 10:13:42.447  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 10:13:42.449  2153  2216 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-31 10:13:42.449  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 10:13:42.449  2153  2227 D BtGatt.ScanManager: Starting BLE batch scan
03-31 10:13:42.449  2153  2227 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-31 10:13:42.452  2153  2216 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-31 10:13:42.452  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 10:13:42.454  2153  2216 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,03-31 10:13:42.454  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 10:13:42.454  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-31 10:13:42.454  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-31 10:13:42.454  3253  3312 I io.jxcore.node.ConnectionHelper: start: OK
03-31 10:13:42.455  3253  3253 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,03-31 10:13:42.455  3253  3253 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 10:13:42.455  3253  3253 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 10:13:42.458  3253  3312 I jxcore-log: ok 141 Can call startListeningForAdvertisements without error
03-31 10:13:42.458  3253  3312 I jxcore-log: ,
,03-31 10:13:42.464  3253  3312 I io.jxcore.node.ConnectionHelper: start: Port number: 50129, start advertisements: false
,03-31 10:13:42.464  3253  3312 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-31 10:13:42.464  3253  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-31 10:13:42.464  3253  3312 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 10:13:42.465  3253  3312 I io.jxcore.node.ConnectionHelper: start: OK
03-31 10:13:42.466  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 10:13:42.466  3253  3312 I jxcore-log: 
,03-31 10:13:42.467  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 10:13:42.467  3253  3312 I jxcore-log: 
,03-31 10:13:42.470  3253  3312 I jxcore-log: ok 142 Can call startListeningForAdvertisements twice without error
03-31 10:13:42.470  3253  3312 I jxcore-log: 
,03-31 10:13:42.477  3253  3312 I jxcore-log: # teardown
03-31 10:13:42.477  3253  3312 I jxcore-log: 
,03-31 10:13:42.661  3253  3312 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-31 10:13:42.661  3253  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 10:13:42.661  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-31 10:13:42.661  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-31 10:13:42.664  2153  2337 D BtGatt.GattService: stopScan() - queue size =1
,03-31 10:13:42.666  2153  2171 D BtGatt.GattService: unregisterClient() - clientIf=5
03-31 10:13:42.666  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 10:13:42.666  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 10:13:42.666  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-31 10:13:42.667  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-31 10:13:42.667  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-31 10:13:42.667  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 10:13:42.668  3253  3253 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 10:13:42.668  2153  2216 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-31 10:13:42.668  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 10:13:42.668  3253  3253 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 10:13:42.668  3253  3253 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 10:13:42.669  2153  2227 D BtGatt.ScanManager: stopping BLe Batch
03-31 10:13:42.670  3253  3312 I jxcore-log: ok 143 Should be able to call stopListeningForAdvertisments in teardown
03-31 10:13:42.670  3253  3312 I jxcore-log: 
03-31 10:13:42.671  2153  2216 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-31 10:13:42.671  3253  3312 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 10:13:42.671  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 10:13:42.671  3253  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 10:13:42.671  3253  3312 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,03-31 10:13:42.671  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
03-31 10:13:42.671  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-31 10:13:42.671  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,03-31 10:13:42.671  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-31 10:13:42.671  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-31 10:13:42.671  2153  2227 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-31 10:13:42.673  2153  2216 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-31 10:13:42.673  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 10:13:42.673  3253  3312 D BluetoothLeScanner: could not find callback wrapper
03-31 10:13:42.673  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-31 10:13:42.676  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-31 10:13:42.676  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-31 10:13:42.676  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-31 10:13:42.677  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-31 10:13:42.677  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 10:13:42.677  3253  3253 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 10:13:42.677  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 10:13:42.677  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-31 10:13:42.678  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 10:13:42.678  3253  3312 I jxcore-log: 
,03-31 10:13:42.685  3253  3253 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-31 10:13:42.686   822   841 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 10:13:42.694  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-31 10:13:42.696  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-31 10:13:42.696  3253  3253 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-31 10:13:42.701  3253  3253 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-31 10:13:42.701  3253  3253 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 10:13:42.701  3253  3253 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 10:13:42.702  3253  3312 I jxcore-log: ok 144 Should be able to call stopAdvertisingAndListening in teardown
03-31 10:13:42.702  3253  3312 I jxcore-log: 
,03-31 10:13:42.709  3253  3312 I jxcore-log: # setup
03-31 10:13:42.709  3253  3312 I jxcore-log: 
,03-31 10:13:42.712  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 10:13:42.712  3253  3312 I jxcore-log: 
,03-31 10:13:43.224  3253  3312 I jxcore-log: # 37. Can call start/stopUpdateAdvertisingAndListening
,03-31 10:13:43.224  3253  3312 I jxcore-log: 
,03-31 10:13:43.667  3253  3312 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: true
03-31 10:13:43.667  3253  3312 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 10:13:43.667  3253  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-31 10:13:43.668  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-31 10:13:43.676  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-31 10:13:43.677  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-31 10:13:43.677  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 10:13:43.677  3253  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 10:13:43.687  2153  2337 D BtGatt.GattService: registerClient() - UUID=25c766d3-a2b5-4727-8e0b-590a210db54a
,03-31 10:13:43.687  2153  2216 D BtGatt.GattService: onClientRegistered() - UUID=25c766d3-a2b5-4727-8e0b-590a210db54a, clientIf=5
03-31 10:13:43.688  3253  3268 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-31 10:13:43.689  2153  2171 D BtGatt.GattService: start scan with filters,
,03-31 10:13:43.691  2153  2227 D BtGatt.ScanManager: handling starting scan,
03-31 10:13:43.691  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-31 10:13:43.692  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 10:13:43.692  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-31 10:13:43.692  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-31 10:13:43.692  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 10:13:43.693  3253  3253 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 10:13:43.693  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-31 10:13:43.694  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-31 10:13:43.694  3253  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
,03-31 10:13:43.694  3253  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 10:13:43.695  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 10:13:43.695  3253  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-31 10:13:43.703  2153  2216 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,03-31 10:13:43.703  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 10:13:43.706  2153  2216 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-31 10:13:43.706  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
,03-31 10:13:43.706  2153  2227 D BtGatt.ScanManager: Starting BLE batch scan
03-31 10:13:43.706  2153  2227 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-31 10:13:43.709  2153  2170 D BtGatt.GattService: registerClient() - UUID=053b7b14-6cd1-49ee-9f3e-89c4b38c779a
03-31 10:13:43.710  2153  2216 D BtGatt.GattService: onClientRegistered() - UUID=053b7b14-6cd1-49ee-9f3e-89c4b38c779a, clientIf=6
03-31 10:13:43.711  3253  3269 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-31 10:13:43.712  2153  2216 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-31 10:13:43.712  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 10:13:43.714  2153  2216 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-31 10:13:43.715  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 10:13:43.716  2153  2226 D BtGatt.AdvertiseManager: message : 0
,03-31 10:13:43.725  2153  2226 D BtGatt.AdvertiseManager: starting multi advertising
,03-31 10:13:43.729  2153  2216 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-31 10:13:43.732  2153  2216 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-31 10:13:43.733  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-31 10:13:43.733  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-31 10:13:43.734   822  3823 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 10:13:43.741  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
03-31 10:13:43.741  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-31 10:13:43.741  3253  3312 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-31 10:13:43.741  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-31 10:13:43.743  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-31 10:13:43.743  3253  3312 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-31 10:13:43.743  3253  3312 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-31 10:13:43.744  3253  3312 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,03-31 10:13:43.744  3253  3253 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,03-31 10:13:43.744  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,03-31 10:13:43.745  3253  3253 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-31 10:13:43.745  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-31 10:13:43.745  3253  3253 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
,03-31 10:13:43.745  3253  3253 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-31 10:13:43.745  3253  3253 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true,
03-31 10:13:43.745  3253  3253 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 10:13:43.746  3253  3253 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,03-31 10:13:43.746  3253  3253 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 10:13:43.746  3253  3253 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-31 10:13:43.746   822  1429 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-31 10:13:43.746  3253  3253 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-31 10:13:43.747  3253  3312 I io.jxcore.node.ConnectionHelper: start: OK
03-31 10:13:43.748  3253  3850 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback,
03-31 10:13:43.753  3253  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
03-31 10:13:43.754  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
,03-31 10:13:43.754  3253  3312 I jxcore-log: 
03-31 10:13:43.757  3253  3312 I jxcore-log: ok 145 Can call startUpdateAdvertisingAndListening without error
03-31 10:13:43.757  3253  3312 I jxcore-log: 
,03-31 10:13:43.759  3253  3312 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 10:13:43.759  3253  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
,03-31 10:13:43.759  3253  3312 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-31 10:13:43.759  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-31 10:13:43.759  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-31 10:13:43.760  3253  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-31 10:13:43.760  3253  3850 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-31 10:13:43.760  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-31 10:13:43.760  3253  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-31 10:13:43.760  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-31 10:13:43.760  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-31 10:13:43.760  3253  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,03-31 10:13:43.760  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-31 10:13:43.760  3253  3253 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-31 10:13:43.762  3253  3253 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-31 10:13:43.762  3253  3253 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-31 10:13:43.762  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-31 10:13:43.763  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-31 10:13:43.766  2153  2337 D BtGatt.GattService: stopScan() - queue size =1
,03-31 10:13:43.767  2153  2171 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-31 10:13:43.768  2153  2216 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-31 10:13:43.768  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 10:13:43.768  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 10:13:43.768  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-31 10:13:43.768  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false,
,03-31 10:13:43.768  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-31 10:13:43.768  2153  2227 D BtGatt.ScanManager: stopping BLe Batch,
03-31 10:13:43.768  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-31 10:13:43.768  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-31 10:13:43.768  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-31 10:13:43.770  2153  2226 D BtGatt.AdvertiseManager: message : 1
03-31 10:13:43.770  2153  2226 D BtGatt.AdvertiseManager: stop advertise for client 6
03-31 10:13:43.771  2153  2216 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-31 10:13:43.771  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 10:13:43.771  2153  2227 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-31 10:13:43.773  2153  2216 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,03-31 10:13:43.773  2153  2216 D BtGatt.GattService: Client app is not null!,
03-31 10:13:43.774  2153  2171 D BtGatt.GattService: unregisterClient() - clientIf=6
03-31 10:13:43.774  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-31 10:13:43.774  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,03-31 10:13:43.774  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-31 10:13:43.774  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,03-31 10:13:43.775  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-31 10:13:43.775  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 10:13:43.775  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-31 10:13:43.775  2153  2216 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,03-31 10:13:43.775  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-31 10:13:43.775  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 10:13:43.775  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-31 10:13:43.775  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 10:13:43.776  3253  3253 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-31 10:13:43.776  3253  3253 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 10:13:43.776  3253  3253 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 10:13:43.776  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 10:13:43.776  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-31 10:13:43.780  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 10:13:43.780  3253  3312 I jxcore-log: 
,03-31 10:13:43.781  3253  3253 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-31 10:13:43.781   822  1329 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-31 10:13:43.782  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-31 10:13:43.782  3253  3312 I jxcore-log: 
,03-31 10:13:43.784  3253  3312 I jxcore-log: ok 146 Can call stopAdvertisingAndListening without error
03-31 10:13:43.784  3253  3312 I jxcore-log: 
03-31 10:13:43.787  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-31 10:13:43.788  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-31 10:13:43.788  3253  3253 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 10:13:43.790  3253  3312 I jxcore-log: # teardown
03-31 10:13:43.790  3253  3312 I jxcore-log: 
03-31 10:13:43.791  3253  3253 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-31 10:13:43.791  3253  3253 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 10:13:43.791  3253  3253 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-31 10:13:43.793  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-31 10:13:43.793  3253  3312 I jxcore-log: 
,03-31 10:13:43.794  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 10:13:43.794  3253  3312 I jxcore-log: 
03-31 10:13:43.795  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 10:13:43.795  3253  3312 I jxcore-log: 
,03-31 10:13:44.960  3253  3312 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-31 10:13:44.960  3253  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 10:13:44.960  3253  3312 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 10:13:44.965  3253  3312 I jxcore-log: ok 147 Should be able to call stopListeningForAdvertisments in teardown
03-31 10:13:44.965  3253  3312 I jxcore-log: 
03-31 10:13:44.966  3253  3312 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-31 10:13:44.966  3253  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 10:13:44.966  3253  3312 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 10:13:44.967  3253  3312 I jxcore-log: ok 148 Should be able to call stopAdvertisingAndListening in teardown
03-31 10:13:44.967  3253  3312 I jxcore-log: 
,03-31 10:13:44.972  3253  3312 I jxcore-log: # setup
03-31 10:13:44.972  3253  3312 I jxcore-log: 
,03-31 10:13:45.137  3253  3312 I jxcore-log: # 38. Calling startUpdateAdvertisingAndListening twice is NOT an error
03-31 10:13:45.137  3253  3312 I jxcore-log: 
,03-31 10:13:45.293  3484  3853 V KeepSync: Connecting to GoogleApiClient
,03-31 10:13:45.396   822  1412 I art     : Explicit concurrent mark sweep GC freed 31618(1598KB) AllocSpace objects, 14(318KB) LOS objects, 31% free, 34MB/50MB, paused 2.187ms total 88.636ms
,03-31 10:13:45.446  3253  3312 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: true
03-31 10:13:45.446  3253  3312 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 10:13:45.446  3253  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-31 10:13:45.446  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-31 10:13:45.448  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
03-31 10:13:45.448  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-31 10:13:45.449  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 10:13:45.449  3253  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 10:13:45.451  2153  2171 D BtGatt.GattService: registerClient() - UUID=2b78e47a-0faf-4742-bb89-13dd07e49b95
,03-31 10:13:45.452  2153  2216 D BtGatt.GattService: onClientRegistered() - UUID=2b78e47a-0faf-4742-bb89-13dd07e49b95, clientIf=5
03-31 10:13:45.452  3253  3269 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-31 10:13:45.452  2153  2170 D BtGatt.GattService: start scan with filters
,03-31 10:13:45.454  2153  2227 D BtGatt.ScanManager: handling starting scan
03-31 10:13:45.454  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-31 10:13:45.454  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-31 10:13:45.454  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-31 10:13:45.454  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-31 10:13:45.454  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 10:13:45.454  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-31 10:13:45.454  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-31 10:13:45.454  3253  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-31 10:13:45.454  3253  3253 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 10:13:45.455  3253  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 10:13:45.455  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 10:13:45.455  3253  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-31 10:13:45.460  2153  2337 D BtGatt.GattService: registerClient() - UUID=c94b1657-c910-425d-b4fe-e9d1f7513209
03-31 10:13:45.461  2153  2216 D BtGatt.GattService: onClientRegistered() - UUID=c94b1657-c910-425d-b4fe-e9d1f7513209, clientIf=6
03-31 10:13:45.461  3253  3268 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-31 10:13:45.461  2153  2216 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-31 10:13:45.461  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 10:13:45.462  2153  2216 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-31 10:13:45.462  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 10:13:45.462  2153  2227 D BtGatt.ScanManager: Starting BLE batch scan
03-31 10:13:45.463  2153  2227 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-31 10:13:45.464  2153  2216 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-31 10:13:45.464  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 10:13:45.466  2153  2216 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-31 10:13:45.466  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 10:13:45.468  2153  2226 D BtGatt.AdvertiseManager: message : 0
,03-31 10:13:45.470  2153  2226 D BtGatt.AdvertiseManager: starting multi advertising
,03-31 10:13:45.472  2153  2216 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-31 10:13:45.474  2153  2216 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
03-31 10:13:45.475  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-31 10:13:45.475  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-31 10:13:45.475   822  1449 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 10:13:45.477  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 10:13:45.477  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-31 10:13:45.477  3253  3312 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-31 10:13:45.477  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-31 10:13:45.478  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-31 10:13:45.478  3253  3312 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-31 10:13:45.478  3253  3312 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-31 10:13:45.478  3253  3312 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-31 10:13:45.478  3253  3253 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-31 10:13:45.478  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-31 10:13:45.478  3253  3253 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-31 10:13:45.478  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-31 10:13:45.478  3253  3253 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-31 10:13:45.478  3253  3253 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
,03-31 10:13:45.478  3253  3253 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-31 10:13:45.478  3253  3253 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 10:13:45.478  3253  3253 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-31 10:13:45.478  3253  3253 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 10:13:45.478  3253  3253 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-31 10:13:45.479  3253  3253 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-31 10:13:45.479  3253  3312 I io.jxcore.node.ConnectionHelper: start: OK
03-31 10:13:45.480  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 10:13:45.480  3253  3312 I jxcore-log: 
03-31 10:13:45.481   822  1384 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-31 10:13:45.481  3253  3312 I jxcore-log: ok 149 Can call startUpdateAdvertisingAndListening without error
03-31 10:13:45.481  3253  3312 I jxcore-log: 
03-31 10:13:45.481  3253  3857 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-31 10:13:45.485  3253  3312 I io.jxcore.node.ConnectionHelper: start: Port number: 4243, start advertisements: true
03-31 10:13:45.485  3253  3312 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 10:13:45.485  3253  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-31 10:13:45.485  3253  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
03-31 10:13:45.485  3253  3312 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 10:13:45.486  3253  3312 I io.jxcore.node.ConnectionHelper: start: OK
03-31 10:13:45.486  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 10:13:45.486  3253  3312 I jxcore-log: 
03-31 10:13:45.487  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-31 10:13:45.487  3253  3312 I jxcore-log: 
03-31 10:13:45.488  3253  3312 I jxcore-log: ok 150 Can call startUpdateAdvertisingAndListening twice without error
03-31 10:13:45.488  3253  3312 I jxcore-log: 
,03-31 10:13:45.489  1265  1282 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-31 10:13:45.489  1265  1282 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 10:13:45.489  1265  1282 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 10:13:45.490  1265  1282 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
03-31 10:13:45.492  1265  1282 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 10:13:45.493  3253  3312 I jxcore-log: # teardown
03-31 10:13:45.493  3253  3312 I jxcore-log: 
03-31 10:13:45.496  1265  1720 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
03-31 10:13:45.497  1265  1720 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 10:13:45.497  1265  1720 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 10:13:45.497  1265  1720 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
03-31 10:13:45.501  1265  1720 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 10:13:45.504  3074  3852 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
03-31 10:13:45.504  3074  3852 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-31 10:13:45.504  3074  3852 E HttpOperation: 	at jdm.a(PG:82)
03-31 10:13:45.504  3074  3852 E HttpOperation: 	at jcs.o(PG:406)
03-31 10:13:45.504  3074  3852 E HttpOperation: 	at jcn.a(PG:1379)
03-31 10:13:45.504  3074  3852 E HttpOperation: 	at jcs.i(PG:143)
03-31 10:13:45.504  3074  3852 E HttpOperation: 	at blb.a(PG:3937)
03-31 10:13:45.504  3074  3852 E HttpOperation: 	at czp.a(PG:18188)
03-31 10:13:45.504  3074  3852 E HttpOperation: 	at czp.a(PG:9081)
03-31 10:13:45.504  3074  3852 E HttpOperation: 	at czq.run(PG:1686)
03-31 10:13:45.504  3074  3852 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-31 10:13:45.504  3074  3852 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-31 10:13:45.504  3074  3852 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 10:13:45.504  3074  3852 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 10:13:45.504  3074  3852 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-31 10:13:45.504  3074  3852 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-31 10:13:45.504  3074  3852 E HttpOperation: 	at jdj.a(PG:4091)
03-31 10:13:45.504  3074  3852 E HttpOperation: 	at jdj.a(PG:1125)
03-31 10:13:45.504  3074  3852 E HttpOperation: 	at jdm.a(PG:77)
03-31 10:13:45.504  3074  3852 E HttpOperation: 	... 12 more
03-31 10:13:45.504  3074  3852 E HttpOperation: Caused by: faj: BadAuthentication
03-31 10:13:45.504  3074  3852 E HttpOperation: 	at fal.a(PG:38)
03-31 10:13:45.504  3074  3852 E HttpOperation: 	at jdj.a(PG:4089)
03-31 10:13:45.504  3074  3852 E HttpOperation: 	... 14 more
,03-31 10:13:45.514  1804  3855 E ClientConnectionOperation: Handling authorization failure
03-31 10:13:45.514  1804  3855 E ClientConnectionOperation: com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
03-31 10:13:45.514  1804  3855 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
03-31 10:13:45.514  1804  3855 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
03-31 10:13:45.514  1804  3855 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
03-31 10:13:45.514  1804  3855 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
03-31 10:13:45.514  1804  3855 E ClientConnectionOperation: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-31 10:13:45.514  1804  3855 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 10:13:45.514  1804  3855 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 10:13:45.514  1804  3855 E ClientConnectionOperation: 	at java.lang.Thread.run(Thread.java:818)
03-31 10:13:45.514  1804  3855 E ClientConnectionOperation: Caused by: com.google.android.gms.auth.ad: BadAuthentication
03-31 10:13:45.514  1804  3855 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.b(SourceFile:442)
03-31 10:13:45.514  1804  3855 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:365)
03-31 10:13:45.514  1804  3855 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:310)
03-31 10:13:45.514  1804  3855 E ClientConnectionOperation: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
03-31 10:13:45.514  1804  3855 E ClientConnectionOperation: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
03-31 10:13:45.514  1804  3855 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:30)
03-31 10:13:45.514  1804  3855 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:370)
03-31 10:13:45.514  1804  3855 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:340)
03-31 10:13:45.514  1804  3855 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:319)
03-31 10:13:45.514  1804  3855 E ClientConnectionOperation: 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
03-31 10:13:45.514  1804  3855 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
03-31 10:13:45.514  1804  3855 E ClientConnectionOperation: 	... 7 more
,03-31 10:13:45.517  3484  3853 V KeepSync: GoogleApiClient failed to connect with error code: 4
,03-31 10:13:45.520  3484  3853 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-31 10:13:45.526  3484  3853 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
03-31 10:13:45.526  3484  3853 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-31 10:13:45.539  1265  2559 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-31 10:13:45.539  1265  2559 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 10:13:45.539  1265  2559 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 10:13:45.539  1265  2559 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 10:13:45.542  1265  2559 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 10:13:45.551  3074  3852 E HttpOperation: [getmobileexperiments] Unexpected exception
03-31 10:13:45.551  3074  3852 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-31 10:13:45.551  3074  3852 E HttpOperation: 	at jdm.a(PG:82)
03-31 10:13:45.551  3074  3852 E HttpOperation: 	at jcs.o(PG:406)
03-31 10:13:45.551  3074  3852 E HttpOperation: 	at jcn.a(PG:1379)
03-31 10:13:45.551  3074  3852 E HttpOperation: 	at jcs.i(PG:143)
03-31 10:13:45.551  3074  3852 E HttpOperation: 	at hec.a(PG:42)
03-31 10:13:45.551  3074  3852 E HttpOperation: 	at hee.a(PG:102)
03-31 10:13:45.551  3074  3852 E HttpOperation: 	at czr.a(PG:65)
03-31 10:13:45.551  3074  3852 E HttpOperation: 	at kka.a(PG:108)
03-31 10:13:45.551  3074  3852 E HttpOperation: 	at czp.a(PG:19176)
03-31 10:13:45.551  3074  3852 E HttpOperation: 	at czp.a(PG:9081)
03-31 10:13:45.551  3074  3852 E HttpOperation: 	at czq.run(PG:1686)
03-31 10:13:45.551  3074  3852 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-31 10:13:45.551  3074  3852 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-31 10:13:45.551  3074  3852 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 10:13:45.551  3074  3852 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 10:13:45.551  3074  3852 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-31 10:13:45.551  3074  3852 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-31 10:13:45.551  3074  3852 E HttpOperation: 	at jdj.a(PG:4091)
03-31 10:13:45.551  3074  3852 E HttpOperation: 	at jdj.a(PG:1125)
03-31 10:13:45.551  3074  3852 E HttpOperation: 	at jdm.a(PG:77)
03-31 10:13:45.551  3074  3852 E HttpOperation: 	... 15 more
03-31 10:13:45.551  3074  3852 E HttpOperation: Caused by: faj: BadAuthentication
03-31 10:13:45.551  3074  3852 E HttpOperation: 	at fal.a(PG:38)
03-31 10:13:45.551  3074  3852 E HttpOperation: 	at jdj.a(PG:4089)
03-31 10:13:45.551  3074  3852 E HttpOperation: 	... 17 more
03-31 10:13:45.551  3074  3852 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
03-31 10:13:45.551  3074  3852 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
03-31 10:13:45.551  3074  3852 E ExperimentLoader: 	at jdm.a(PG:82)
03-31 10:13:45.551  3074  3852 E ExperimentLoader: 	at jcs.o(PG:406)
03-31 10:13:45.551  3074  3852 E ExperimentLoader: 	at jcn.a(PG:1379)
03-31 10:13:45.551  3074  3852 E ExperimentLoader: 	at jcs.i(PG:143)
03-31 10:13:45.551  3074  3852 E ExperimentLoader: 	at hec.a(PG:42)
03-31 10:13:45.551  3074  3852 E ExperimentLoader: 	at hee.a(PG:102)
03-31 10:13:45.551  3074  3852 E ExperimentLoader: 	at czr.a(PG:65)
03-31 10:13:45.551  3074  3852 E ExperimentLoader: 	at kka.a(PG:108)
03-31 10:13:45.551  3074  3852 E ExperimentLoader: 	at czp.a(PG:19176)
03-31 10:13:45.551  3074  3852 E ExperimentLoader: 	at czp.a(PG:9081)
03-31 10:13:45.551  3074  3852 E ExperimentLoader: 	at czq.run(PG:1686)
03-31 10:13:45.551  3074  3852 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-31 10:13:45.551  3074  3852 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-31 10:13:45.551  3074  3852 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 10:13:45.551  3074  3852 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 10:13:45.551  3074  3852 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
03-31 10:13:45.551  3074  3852 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-31 10:13:45.551  3074  3852 E ExperimentLoader: 	at jdj.a(PG:4091)
03-31 10:13:45.551  3074  3852 E ExperimentLoader: 	at jdj.a(PG:1,125)
03-31 10:13:45.551  3074  3852 E ExperimentLoader: 	at jdm.a(PG:77)
03-31 10:13:45.551  3074  3852 E ExperimentLoader: 	... 15 more
03-31 10:13:45.551  3074  3852 E ExperimentLoader: Caused by: faj: BadAuthentication
03-31 10:13:45.551  3074  3852 E ExperimentLoader: 	at fal.a(PG:38)
03-31 10:13:45.551  3074  3852 E ExperimentLoader: 	at jdj.a(PG:4089)
03-31 10:13:45.551  3074  3852 E ExperimentLoader: 	... 17 more
,03-31 10:13:45.599  1265  1902 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,03-31 10:13:45.599  1265  1902 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 10:13:45.599  1265  1902 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 10:13:45.599  1265  1902 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 10:13:45.604  1265  1902 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 10:13:45.628   822   856 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 202555, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,03-31 10:13:45.642  3484  3853 E KeepSync: IOException
03-31 10:13:45.642  3484  3853 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
03-31 10:13:45.642  3484  3853 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
03-31 10:13:45.642  3484  3853 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
03-31 10:13:45.642  3484  3853 E KeepSync: 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
03-31 10:13:45.642  3484  3853 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
03-31 10:13:45.642  3484  3853 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
03-31 10:13:45.642  3484  3853 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
03-31 10:13:45.642  3484  3853 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
03-31 10:13:45.642  3484  3853 E KeepSync: 	at com.google.android.keep.util.m.a(SourceFile:207)
03-31 10:13:45.642  3484  3853 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
03-31 10:13:45.642  3484  3853 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
03-31 10:13:45.642  3484  3853 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
03-31 10:13:45.642  3484  3853 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
03-31 10:13:45.642  3484  3853 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
03-31 10:13:45.642  3484  3853 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
03-31 10:13:45.642  3484  3853 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
03-31 10:13:45.642  3484  3853 E KeepSync: 	... 10 more
03-31 10:13:45.642  3484  3853 W KeepSync: Sync result 2
,03-31 10:13:45.646  3433  3860 I BooksSync: Starting books sync for 61035162, extras: ade
,03-31 10:13:45.648   822   856 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 203591, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-31 10:13:45.661  3433  3861 I BooksConfig: GmsCore Version = 7.8.99 (2134222-430)
,03-31 10:13:45.664  1804  3862 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,03-31 10:13:45.673  1265  1265 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 10:13:45.682  1265  1282 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-31 10:13:45.682  1265  1282 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 10:13:45.682  1265  1282 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-31 10:13:45.683  1265  1282 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 10:13:45.685  1265  1282 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 10:13:45.691  1265  2557 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: mail
03-31 10:13:45.691  1265  2557 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> mail without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 10:13:45.691  1265  2557 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 10:13:45.691  1265  2557 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 10:13:45.695  1265  2557 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 10:13:45.714  1265  2557 W GLSActivity: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-31 10:13:45.714  1265  2557 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-31 10:13:45.714  1265  2557 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-31 10:13:45.714  1265  2557 W GLSActivity: 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
03-31 10:13:45.714  1265  2557 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
03-31 10:13:45.714  1265  2557 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
03-31 10:13:45.714  1265  2557 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:446)
,03-31 10:13:45.716  1804  3862 W SubscribedFeeds: Hard error
,03-31 10:13:45.721   822   856 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), subscribedfeeds, PERIODIC, currentRunTime 230045, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,03-31 10:13:45.721   822   856 D SyncManager: not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), subscribedfeeds, PERIODIC, currentRunTime 262975, reason: Periodic
,03-31 10:13:45.743  1265  1720 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-31 10:13:45.743  1265  1720 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 10:13:45.743  1265  1720 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 10:13:45.743  1265  1720 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 10:13:45.747  1265  1720 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 10:13:45.758  3433  3861 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,03-31 10:13:45.758  3433  3860 E BooksSync: Soft error
03-31 10:13:45.758  3433  3860 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-31 10:13:45.758  3433  3860 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,03-31 10:13:45.758  3433  3860 E BooksSync: Sync error
03-31 10:13:45.758  3433  3860 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-31 10:13:45.758  3433  3860 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-31 10:13:45.758  3433  3860 I BooksSync: Finished books sync
,03-31 10:13:45.764  2381  2381 I AnalyticsLogBase: PlayLogger.onLoggerConnected
,03-31 10:13:45.765   822   856 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 203745, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-31 10:13:45.825  1832  3864 I GCoreUlr: Uploading GCM registration ID for account#2#
,03-31 10:13:45.841  1832  3864 W BaseAppContext: Using Auth Proxy for data requests.
,03-31 10:13:45.855  1832  3864 I GLSUser : [ChannelManager] Attempting to channel bind connection HttpClient.
,03-31 10:13:45.867  1832  3864 I GLSUser : [ChannelManager] Checking whether channelId is enabled. isEnabledGmsCore? false, isEnabledSdk? true, isAtLeastKitKat? true
,03-31 10:13:45.869  2381  3863 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-31 10:13:45.869  2381  3863 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-31 10:13:45.898  2381  3863 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,03-31 10:13:45.907  1265  1720 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/userlocation.reporting
,03-31 10:13:45.907  1265  1720 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/userlocation.reporting without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 10:13:45.907  1265  1720 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 10:13:45.907  1265  1720 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 10:13:45.913  1265  1720 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 10:13:45.926  1832  3864 E GCoreUlr: 
03-31 10:13:45.926  1832  3864 E GCoreUlr: com.google.android.gms.auth.ad: BadAuthentication
03-31 10:13:45.926  1832  3864 E GCoreUlr: 	at com.google.android.gms.auth.p.b(SourceFile:442)
03-31 10:13:45.926  1832  3864 E GCoreUlr: 	at com.google.android.gms.auth.p.a(SourceFile:365)
03-31 10:13:45.926  1832  3864 E GCoreUlr: 	at com.google.android.gms.auth.p.a(SourceFile:310)
03-31 10:13:45.926  1832  3864 E GCoreUlr: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
03-31 10:13:45.926  1832  3864 E GCoreUlr: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
03-31 10:13:45.926  1832  3864 E GCoreUlr: 	at com.google.android.gms.common.server.o.b(SourceFile:30)
03-31 10:13:45.926  1832  3864 E GCoreUlr: 	at com.google.android.gms.common.server.o.b(SourceFile:370)
03-31 10:13:45.926  1832  3864 E GCoreUlr: 	at com.google.android.gms.common.server.o.a(SourceFile:340)
03-31 10:13:45.926  1832  3864 E GCoreUlr: 	at com.google.android.gms.common.server.o.a(SourceFile:319)
03-31 10:13:45.926  1832  3864 E GCoreUlr: 	at com.google.android.location.reporting.c.c.a(SourceFile:166)
03-31 10:13:45.926  1832  3864 E GCoreUlr: 	at com.google.android.location.reporting.c.g.a(SourceFile:111)
03-31 10:13:45.926  1832  3864 E GCoreUlr: 	at com.google.android.location.reporting.service.t.b(SourceFile:220)
03-31 10:13:45.926  1832  3864 E GCoreUlr: 	at com.google.android.location.reporting.service.t.a(SourceFile:173)
03-31 10:13:45.926  1832  3864 E GCoreUlr: 	at com.google.android.location.reporting.service.s.onPerformSync(SourceFile:149)
03-31 10:13:45.926  1832  3864 E GCoreUlr: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,03-31 10:13:45.939   822   856 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.location.reporting, PERIODIC, currentRunTime 230066, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,03-31 10:13:45.941   822   856 D SyncManager: not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.location.reporting, PERIODIC, currentRunTime 263783, reason: Periodic
,03-31 10:13:45.954  2381  3863 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-31 10:13:45.959  2381  3863 W AbstractGoogleClient: Application name is not set. Call Builder#setApplicationName.
,03-31 10:13:46.011   822   856 I ActivityManager: Start proc 3872:com.google.android.gm/u0a78 for service com.google.android.gm/.provider.MailSyncAdapterService
,03-31 10:13:46.081  1265  1902 I art     : Explicit concurrent mark sweep GC freed 46923(2MB) AllocSpace objects, 3(330KB) LOS objects, 36% free, 27MB/43MB, paused 1.443ms total 51.934ms
,03-31 10:13:46.117  3872  3892 I Gmail   : getAccountsCursor
,03-31 10:13:46.121  3872  3893 D ActivityThread: Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,03-31 10:13:46.126  1265  1265 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 10:13:46.131  1265  1265 I ConfigService: onDestroy
,03-31 10:13:46.286   822  1429 I ActivityManager: Start proc 3895:com.google.android.gm.exchange/u0a77 for service com.google.android.gm.exchange/com.android.exchange.service.EasService
,03-31 10:13:46.358  3253  3312 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-31 10:13:46.358  3253  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
03-31 10:13:46.358  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-31 10:13:46.358  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-31 10:13:46.363  3872  3872 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,03-31 10:13:46.363  2153  2337 D BtGatt.GattService: stopScan() - queue size =1
,03-31 10:13:46.374  2153  2171 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-31 10:13:46.375  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 10:13:46.375  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-31 10:13:46.375  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,03-31 10:13:46.376  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
,03-31 10:13:46.376  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
,03-31 10:13:46.376  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-31 10:13:46.376  3253  3253 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-31 10:13:46.376  3253  3253 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
03-31 10:13:46.376  3253  3253 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-31 10:13:46.377  2153  2216 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-31 10:13:46.377  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 10:13:46.377  2153  2227 D BtGatt.ScanManager: stopping BLe Batch
03-31 10:13:46.377  3253  3312 I jxcore-log: ok 151 Should be able to call stopListeningForAdvertisments in teardown
03-31 10:13:46.377  3253  3312 I jxcore-log: 
,03-31 10:13:46.378  3253  3312 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-31 10:13:46.378  3253  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
03-31 10:13:46.378  3253  3312 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-31 10:13:46.378  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-31 10:13:46.378  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,03-31 10:13:46.379  3253  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-31 10:13:46.379  2153  2216 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-31 10:13:46.379  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 10:13:46.380  3253  3857 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-31 10:13:46.380  2153  2227 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-31 10:13:46.380  3253  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,03-31 10:13:46.380  3253  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-31 10:13:46.380  3253  3253 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-31 10:13:46.380  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-31 10:13:46.381  3253  3253 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-31 10:13:46.381  3253  3253 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-31 10:13:46.381  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,03-31 10:13:46.381  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-31 10:13:46.381  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-31 10:13:46.381  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-31 10:13:46.381  1265  1902 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.calendar, service: oauth2:https://www.googleapis.com/auth/calendar
03-31 10:13:46.381  1265  1902 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/calendar without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 10:13:46.381  1265  1902 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-31 10:13:46.381  1265  1902 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
03-31 10:13:46.382  2153  2216 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-31 10:13:46.382  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 10:13:46.382  2153  2216 D BtGatt.GattService: current time is 231299986525
03-31 10:13:46.382  2153  2216 D BtGatt.GattService: Batch record : [-29, -15, -79, 31, 67, 119, 1, -128, -80, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -63, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
,03-31 10:13:46.382  2153  2216 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-31 10:13:46.383  2153  2216 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
,03-31 10:13:46.389  3253  3312 D BluetoothLeScanner: could not find callback wrapper
03-31 10:13:46.389  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 10:13:46.389  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,03-31 10:13:46.390  2153  2226 D BtGatt.AdvertiseManager: message : 1
03-31 10:13:46.391  2153  2226 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-31 10:13:46.393  2153  2216 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-31 10:13:46.393  2153  2216 D BtGatt.GattService: Client app is not null!
,03-31 10:13:46.393  2153  2337 D BtGatt.GattService: unregisterClient() - clientIf=6
03-31 10:13:46.394  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-31 10:13:46.394  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-31 10:13:46.394  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-31 10:13:46.394  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-31 10:13:46.394  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-31 10:13:46.394  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 10:13:46.394  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-31 10:13:46.394  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-31 10:13:46.444   822  1104 I art     : Explicit concurrent mark sweep GC freed 27375(1160KB) AllocSpace objects, 10(725KB) LOS objects, 32% free, 33MB/49MB, paused 1.789ms total 79.632ms
,03-31 10:13:46.469   822  1454 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,03-31 10:13:46.471  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,03-31 10:13:46.471  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,03-31 10:13:46.472  3253  3253 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
03-31 10:13:46.472  3253  3253 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-31 10:13:46.472  3253  3253 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 10:13:46.472  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-31 10:13:46.472  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-31 10:13:46.474  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-31 10:13:46.474  3253  3312 I jxcore-log: 
,03-31 10:13:46.475  3253  3312 I jxcore-log: ok 152 Should be able to call stopAdvertisingAndListening in teardown
03-31 10:13:46.475  3253  3312 I jxcore-log: 
,03-31 10:13:46.477  1265  1902 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 10:13:46.480  3253  3312 I jxcore-log: # setup
03-31 10:13:46.480  3253  3312 I jxcore-log: 
,03-31 10:13:46.484  3253  3253 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-31 10:13:46.484   822  1412 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 10:13:46.491  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-31 10:13:46.493  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-31 10:13:46.493  3253  3253 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-31 10:13:46.495  3895  3895 I Exchange: EasService.onCreate
,03-31 10:13:46.496  3253  3253 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 10:13:46.496  3253  3253 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 10:13:46.497  3872  3921 W Gmail   : Sync started for account: account:61035162
03-31 10:13:46.498  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 10:13:46.498  3253  3312 I jxcore-log: 
03-31 10:13:46.498  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 10:13:46.498  3253  3312 I jxcore-log: 
,03-31 10:13:46.504  3872  3920 I Gmail   : Observing account changes for notifications
,03-31 10:13:46.505  3895  3924 I Exchange: RestartPingTask
,03-31 10:13:46.513  3872  3927 I Gmail   : getAccountsCursor
,03-31 10:13:46.522  1265  1265 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 10:13:46.531  3895  3895 I Exchange: RestartPingsTask did not start any pings.
,03-31 10:13:46.531  3895  3895 I Exchange: PSS stopIfIdle
,03-31 10:13:46.531  3895  3895 I Exchange: PSS has no active accounts; stopping service.
,03-31 10:13:46.534  3895  3895 I Exchange: onDestroy
,03-31 10:13:46.546  3872  3921 E SQLiteLog: (283) recovered 32 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,03-31 10:13:46.549  2381  3863 E CalendarSyncAdapter: Exception in onPerformLoggedSync 
03-31 10:13:46.549  2381  3863 E CalendarSyncAdapter: com.google.android.apiary.AuthenticationException: Could not get an auth token
03-31 10:13:46.549  2381  3863 E CalendarSyncAdapter: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(GoogleRequestInitializer.java:152)
03-31 10:13:46.549  2381  3863 E CalendarSyncAdapter: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(GoogleRequestInitializer.java:89)
03-31 10:13:46.549  2381  3863 E CalendarSyncAdapter: 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:858)
03-31 10:13:46.549  2381  3863 E CalendarSyncAdapter: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(AbstractGoogleClientRequest.java:410)
03-31 10:13:46.549  2381  3863 E CalendarSyncAdapter: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(AbstractGoogleClientRequest.java:343)
03-31 10:13:46.549  2381  3863 E CalendarSyncAdapter: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(AbstractGoogleClientRequest.java:460)
03-31 10:13:46.549  2381  3863 E CalendarSyncAdapter: 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.processAccountCalendars(CalendarSyncAdapterApiary.java:2382)
03-31 10:13:46.549  2381  3863 E CalendarSyncAdapter: 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.updateCalendarsFromServerFeed(CalendarSyncAdapterApiary.java:1850)
03-31 10:13:46.549  2381  3863 E CalendarSyncAdapter: 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.getServerDiffs(CalendarSyncAdapterApiary.java:1733)
03-31 10:13:46.549  2381  3863 E CalendarSyncAdapter: 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.performSync(CalendarSyncAdapterApiary.java:503)
03-31 10:13:46.549  2381  3863 E CalendarSyncAdapter: 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.onPerformLoggedSync(CalendarSyncAdapterApiary.java:392)
03-31 10:13:46.549  2381  3863 E CalendarSyncAdapter: 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
03-31 10:13:46.549  2381  3863 E CalendarSyncAdapter: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
03-31 10:13:46.549  2381  3863 E CalendarSyncAdapter: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
03-31 10:13:46.549  2381  3863 E CalendarSyncAdapter: 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
03-31 10:13:46.549  2381  3863 E CalendarSyncAdapter: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
03-31 10:13:46.549  2381  3863 E CalendarSyncAdapter: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(GoogleRequestInitializer.java:140)
03-31 10:13:46.549  2381  3863 E CalendarSyncAdapter: 	... 12 more
,03-31 10:13:46.555   822   856 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.android.calendar, PERIODIC, currentRunTime 230056, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,03-31 10:13:46.556   822   856 D SyncManager: not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.calendar, PERIODIC, currentRunTime 262890, reason: Periodic
,03-31 10:13:46.600   822  1454 I ActivityManager: Start proc 3937:android.process.acore/u0a5 for content provider com.android.providers.contacts/.ContactsProvider2
,03-31 10:13:46.600  3253  3312 I jxcore-log: # 39. peerAvailabilityChange is called
03-31 10:13:46.600  3253  3312 I jxcore-log: 
,03-31 10:13:46.611  3872  3932 I Gmail   : notifyAccountChanged
,03-31 10:13:46.612  3872  3892 I Gmail   : getAccountsCursor
,03-31 10:13:46.616  1265  1265 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 10:13:46.618  3872  3932 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,03-31 10:13:46.623  3872  3932 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,03-31 10:13:46.630  3872  3932 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,03-31 10:13:46.631  3872  3932 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,03-31 10:13:46.670  1265  3936 I [@@    ] SyncAdapterProxy: Delagator disabled, using the (deprecated) GData sync adapter
,03-31 10:13:46.673  3872  3921 I Gmail   : notifyAccountChanged
,03-31 10:13:46.711  3937  3956 I ContactLocale: AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,03-31 10:13:46.737  3872  3927 I Gmail   : getAccountsCursor
,03-31 10:13:46.745  1265  1265 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 10:13:46.769  3253  3312 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: true
03-31 10:13:46.769  3253  3312 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 10:13:46.769  3253  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-31 10:13:46.769  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-31 10:13:46.772  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
03-31 10:13:46.772  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-31 10:13:46.772  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-31 10:13:46.772  3253  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 10:13:46.775  2153  2337 D BtGatt.GattService: registerClient() - UUID=ef6042fd-0267-4753-b318-37b385316ecc
03-31 10:13:46.775  2153  2216 D BtGatt.GattService: onClientRegistered() - UUID=ef6042fd-0267-4753-b318-37b385316ecc, clientIf=5
03-31 10:13:46.775  3253  3854 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-31 10:13:46.776  2153  2170 D BtGatt.GattService: start scan with filters
,03-31 10:13:46.776  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-31 10:13:46.776  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-31 10:13:46.776  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-31 10:13:46.776  2153  2227 D BtGatt.ScanManager: handling starting scan
03-31 10:13:46.776  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-31 10:13:46.776  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 10:13:46.776  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-31 10:13:46.777  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-31 10:13:46.777  3253  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-31 10:13:46.777  3253  3253 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 10:13:46.777  3253  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 10:13:46.777  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 10:13:46.777  3253  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-31 10:13:46.779  2153  2216 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-31 10:13:46.779  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 10:13:46.780  2153  2171 D BtGatt.GattService: registerClient() - UUID=85233dc2-dbcd-401c-a668-9641b8e1153c
03-31 10:13:46.780  2153  2216 D BtGatt.GattService: onClientRegistered() - UUID=85233dc2-dbcd-401c-a668-9641b8e1153c, clientIf=6
03-31 10:13:46.781  3253  3269 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-31 10:13:46.781  2153  2216 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-31 10:13:46.781  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 10:13:46.781  2153  2227 D BtGatt.ScanManager: Starting BLE batch scan
03-31 10:13:46.781  2153  2227 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-31 10:13:46.781  2153  2226 D BtGatt.AdvertiseManager: message : 0
03-31 10:13:46.782  2153  2216 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,03-31 10:13:46.783  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 10:13:46.784  2153  2216 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-31 10:13:46.784  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 10:13:46.784  2153  2226 D BtGatt.AdvertiseManager: starting multi advertising
03-31 10:13:46.787  2153  2216 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-31 10:13:46.789  2153  2216 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-31 10:13:46.790  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-31 10:13:46.790  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-31 10:13:46.790   822  1429 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 10:13:46.792  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 10:13:46.792  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-31 10:13:46.792  3253  3312 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-31 10:13:46.792  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-31 10:13:46.794  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-31 10:13:46.794  3253  3312 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-31 10:13:46.794  3253  3312 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-31 10:13:46.794  3253  3312 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-31 10:13:46.794  3253  3312 I io.jxcore.node.ConnectionHelper: start: OK
03-31 10:13:46.795   822  1378 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-31 10:13:46.795  3253  3253 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-31 10:13:46.795  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-31 10:13:46.795  3253  3253 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,03-31 10:13:46.795  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-31 10:13:46.795  3253  3253 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-31 10:13:46.795  3253  3253 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-31 10:13:46.795  3253  3253 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-31 10:13:46.795  3253  3253 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 10:13:46.795  3253  3253 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-31 10:13:46.795  3253  3958 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-31 10:13:46.795  3253  3253 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 10:13:46.796  3253  3253 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-31 10:13:46.796  3253  3253 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-31 10:13:46.797  3253  3958 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-31 10:13:46.797  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 10:13:46.797  3253  3312 I jxcore-log: 
03-31 10:13:46.798  3253  3312 I jxcore-log: ok 153 Can call startUpdateAdvertisingAndListeningwithout error
03-31 10:13:46.798  3253  3312 I jxcore-log: 
,03-31 10:13:46.801  3253  3312 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: false
03-31 10:13:46.801  3253  3312 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 10:13:46.801  3253  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should affect listening to advertisements only
03-31 10:13:46.801  3253  3312 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-31 10:13:46.801  3253  3312 I io.jxcore.node.ConnectionHelper: start: OK
,03-31 10:13:46.802  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 10:13:46.802  3253  3312 I jxcore-log: 
,03-31 10:13:46.803  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-31 10:13:46.803  3253  3312 I jxcore-log: 
03-31 10:13:46.804  3253  3312 I jxcore-log: ok 154 Can call startListeningForAdvertisements without error
03-31 10:13:46.804  3253  3312 I jxcore-log: 
,03-31 10:13:46.819  3872  3921 I Gmail   : MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 4353, normalSync: true
,03-31 10:13:46.841  1265  1265 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 10:13:46.857  1265  3209 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
03-31 10:13:46.857  1265  3209 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-31 10:13:46.857  1265  3209 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 10:13:46.857  1265  3209 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 10:13:46.859  1265  3209 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 10:13:46.880  1265  3209 W GLSActivity: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-31 10:13:46.880  1265  3209 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-31 10:13:46.880  1265  3209 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-31 10:13:46.880  1265  3209 W GLSActivity: 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
03-31 10:13:46.880  1265  3209 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
03-31 10:13:46.880  1265  3209 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
03-31 10:13:46.880  1265  3209 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:446)
,03-31 10:13:46.883  1265  3936 D ContactsSyncAdapter: innerSync failed
03-31 10:13:46.883  1265  3936 D ContactsSyncAdapter: com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
03-31 10:13:46.883  1265  3936 D ContactsSyncAdapter: 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
03-31 10:13:46.883  1265  3936 D ContactsSyncAdapter: 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
03-31 10:13:46.883  1265  3936 D ContactsSyncAdapter: 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
03-31 10:13:46.883  1265  3936 D ContactsSyncAdapter: 	at com.google.android.syncadapters.contacts.delegation.SyncAdapterProxy.onPerformLoggedSync(SyncAdapterProxy.java:123)
03-31 10:13:46.883  1265  3936 D ContactsSyncAdapter: 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
03-31 10:13:46.883  1265  3936 D ContactsSyncAdapter: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
03-31 10:13:46.883  1265  3936 D ContactsSyncAdapter: Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
03-31 10:13:46.883  1265  3936 D ContactsSyncAdapter: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
03-31 10:13:46.883  1265  3936 D ContactsSyncAdapter: 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
03-31 10:13:46.883  1265  3936 D ContactsSyncAdapter: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
03-31 10:13:46.883  1265  3936 D ContactsSyncAdapter: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
03-31 10:13:46.883  1265  3936 D ContactsSyncAdapter: 	at android.os.Binder.execTransact(Binder.java:446)
,03-31 10:13:46.890   822  1410 I ActivityManager: Killing 3596:com.qualcomm.timeservice/1000 (adj 15): empty #17
,03-31 10:13:47.014   822   856 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, PERIODIC, currentRunTime 230079, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,03-31 10:13:47.019   822   856 D SyncManager: not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts, PERIODIC, currentRunTime 263552, reason: Periodic
,03-31 10:13:47.117  3872  3921 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-31 10:13:47.118  3872  3921 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-31 10:13:47.192  3872  3921 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,03-31 10:13:47.243  3872  3921 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-31 10:13:47.251  1265  1265 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 10:13:47.325  1265  1282 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gm, service: mail
03-31 10:13:47.326  1265  1282 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> mail without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 10:13:47.326  1265  3209 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/reminders
03-31 10:13:47.326  1265  3209 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/reminders without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 10:13:47.326  1265  3209 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 10:13:47.326  1265  3209 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 10:13:47.327  1265  1282 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-31 10:13:47.327  1265  1282 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 10:13:47.330  1265  1282 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 10:13:47.330  1265  3209 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 10:13:47.343  1804  3960 E ReminderSync: AuthError [T SyncAdapterThread-1:id=233:priority=5:group=main]
,03-31 10:13:47.349   822   856 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.gms.reminders, PERIODIC, currentRunTime 230083, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,03-31 10:13:47.349   822   856 D SyncManager: not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.gms.reminders, PERIODIC, currentRunTime 264605, reason: Periodic
,03-31 10:13:47.361  1265  1282 W GLSActivity: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-31 10:13:47.361  1265  1282 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-31 10:13:47.361  1265  1282 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-31 10:13:47.361  1265  1282 W GLSActivity: 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
03-31 10:13:47.361  1265  1282 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
03-31 10:13:47.361  1265  1282 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
03-31 10:13:47.361  1265  1282 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:446)
,03-31 10:13:47.393   822   856 I ActivityManager: Start proc 3962:com.google.android.apps.magazines/u0a67 for service com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.service.SyncAdapterService
,03-31 10:13:47.405  1265  1265 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 10:13:47.425  1265  1902 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gm, service: mail
03-31 10:13:47.425  1265  1902 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> mail without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 10:13:47.425  1265  1902 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 10:13:47.426  1265  1902 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 10:13:47.429  1265  1902 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 10:13:47.454  1265  1902 W GLSActivity: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-31 10:13:47.454  1265  1902 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-31 10:13:47.454  1265  1902 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-31 10:13:47.454  1265  1902 W GLSActivity: 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
03-31 10:13:47.454  1265  1902 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
03-31 10:13:47.454  1265  1902 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
03-31 10:13:47.454  1265  1902 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:446)
,03-31 10:13:47.483  3872  3921 I Gmail   : notifyAccountChanged
,03-31 10:13:47.486  3872  3893 I Gmail   : getAccountsCursor
,03-31 10:13:47.493  1265  1265 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 10:13:47.519  3872  3921 I Gmail   : notifyAccountChanged
,03-31 10:13:47.521  3872  3921 W Gmail   : Sync complete for account: account:61035162
,03-31 10:13:47.522  3872  3919 I Gmail   : getAccountsCursor
,03-31 10:13:47.526  1265  1265 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 10:13:47.530   822   856 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), gmail-ls, PERIODIC, currentRunTime 230073, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
03-31 10:13:47.531   822   856 D SyncManager: not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), gmail-ls, PERIODIC, currentRunTime 264421, reason: Periodic
03-31 10:13:47.532   822  1378 I ActivityManager: Killing 3616:com.google.android.deskclock/u0a44 (adj 15): empty #17
,03-31 10:13:47.545  3962  3962 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
03-31 10:13:47.545  3962  3962 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-31 10:13:47.545  3962  3962 I GAv4    :   adb logcat -s GAv4
,03-31 10:13:47.561  1265  1265 I art     : Explicit concurrent mark sweep GC freed 17462(1011KB) AllocSpace objects, 19(2MB) LOS objects, 37% free, 27MB/43MB, paused 1.093ms total 34.768ms
,03-31 10:13:47.641  3962  3962 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,03-31 10:13:47.675  3962  3962 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,03-31 10:13:47.685  3962  3985 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,03-31 10:13:47.708   822   856 I ActivityManager: Start proc 3986:com.android.chrome/u0a40 for service com.android.chrome/org.chromium.chrome.browser.sync.ChromeBrowserSyncAdapterService
,03-31 10:13:47.793   822  1384 I art     : Explicit concurrent mark sweep GC freed 20154(845KB) AllocSpace objects, 4(346KB) LOS objects, 31% free, 34MB/50MB, paused 2.269ms total 61.087ms
,03-31 10:13:47.795  2153  2153 D BtGatt.ScanManager: awakened up at time 232712
03-31 10:13:47.796  2153  2227 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-31 10:13:47.803  2153  2216 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-31 10:13:47.803  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 10:13:47.803  2153  2216 D BtGatt.GattService: current time is 232720878399
,03-31 10:13:47.803  2153  2216 D BtGatt.GattService: Batch record : [-56, 40, -2, 24, 117, 119, 1, -128, -81, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -58, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
,03-31 10:13:47.804  2153  2216 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-31 10:13:47.804  2153  2216 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-31 10:13:47.807  3253  3253 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> E0:DB:10:14:E2:C0], added - the peer count is 1
03-31 10:13:47.807  3253  3253 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 2,
03-31 10:13:47.807  3253  3253 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> E0:DB:10:14:E2:C0], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 
03-31 10:13:47.807  3253  3253 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
,03-31 10:13:47.813  3253  3312 I jxcore-log: ok 155 peers must be an array
03-31 10:13:47.813  3253  3312 I jxcore-log: 
,03-31 10:13:47.813  3253  3312 I jxcore-log: ok 156 peers must not be zero-length
03-31 10:13:47.813  3253  3312 I jxcore-log: 
,03-31 10:13:47.814  3253  3312 I jxcore-log: ok 157 peer must have peerIdentifier
03-31 10:13:47.814  3253  3312 I jxcore-log: 
03-31 10:13:47.823  3253  3312 I jxcore-log: ok 158 peerIdentifier must be a string
03-31 10:13:47.823  3253  3312 I jxcore-log: 
03-31 10:13:47.824  3253  3312 I jxcore-log: ok 159 peer must have peerAvailable
03-31 10:13:47.824  3253  3312 I jxcore-log: 
03-31 10:13:47.824  3253  3312 I jxcore-log: ok 160 peer must have pleaseConnect
03-31 10:13:47.824  3253  3312 I jxcore-log: 
03-31 10:13:47.829  3253  3312 I jxcore-log: # teardown
03-31 10:13:47.829  3253  3312 I jxcore-log: 
,03-31 10:13:47.864  3986  4018 D DelayedSyncController: Delaying sync.
,03-31 10:13:47.870   822   840 I ActivityManager: Killing 3577:com.google.android.apps.photos/u0a71 (adj 15): empty #17
,03-31 10:13:48.024  3962  3962 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,03-31 10:13:48.040  3962  3962 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 2956-2957)
,03-31 10:13:48.040  3962  3962 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-31 10:13:48.045  3962  3962 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1e792c0d}
,03-31 10:13:48.045  3962  3962 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-31 10:13:48.046  3962  3962 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,03-31 10:13:48.059  3962  3962 I BrowserStartupController: Initializing chromium process, singleProcess=true
03-31 10:13:48.060  3962  3962 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-31 10:13:48.061  3962  3962 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-31 10:13:48.082  1804  1804 W BaseAppContext: Using Auth Proxy for data requests.
,03-31 10:13:48.097  3962  3962 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,03-31 10:13:48.099  1804  1804 W BaseAppContext: Using Auth Proxy for data requests.
,03-31 10:13:48.105  3962  3962 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-31 10:13:48.105  3962  3962 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-31 10:13:48.105  3962  3962 I Adreno  : EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,03-31 10:13:48.112  1804  1804 W BaseAppContext: Using Auth Proxy for data requests.
,03-31 10:13:48.115  1804  1804 W BaseAppContext: Using Auth Proxy for data requests.,
,03-31 10:13:48.126  1804  1804 W BaseAppContext: Using Auth Proxy for data requests.
,03-31 10:13:48.135  1804  1804 W BaseAppContext: Using Auth Proxy for data requests.,
,03-31 10:13:48.157  1804  1804 W BaseAppContext: Using Auth Proxy for data requests.
,03-31 10:13:48.176  3962  4034 W AudioManagerAndroid: Requires BLUETOOTH permission
,03-31 10:13:48.178  3962  3962 I NSApplication: Starting up...
,03-31 10:13:48.194  3962  4040 I SyncAdapterService: Ignoring sync request for non-current account
,03-31 10:13:48.200  3253  3312 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-31 10:13:48.200  3253  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
03-31 10:13:48.200  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-31 10:13:48.200  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-31 10:13:48.201  2153  2171 D BtGatt.GattService: stopScan() - queue size =1
,03-31 10:13:48.202  2153  2337 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-31 10:13:48.202  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 10:13:48.202  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 10:13:48.202  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-31 10:13:48.203  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-31 10:13:48.203  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-31 10:13:48.203  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-31 10:13:48.203  3253  3253 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-31 10:13:48.203  3253  3253 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
03-31 10:13:48.203  3253  3253 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 10:13:48.203  2153  2216 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-31 10:13:48.203  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 10:13:48.203  2153  2227 D BtGatt.ScanManager: stopping BLe Batch
,03-31 10:13:48.204  3253  3312 I jxcore-log: ok 161 Should be able to call stopListeningForAdvertisments in teardown
03-31 10:13:48.204  3253  3312 I jxcore-log: 
,03-31 10:13:48.205  3253  3312 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 10:13:48.205  3253  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
03-31 10:13:48.205  3253  3312 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-31 10:13:48.205  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,03-31 10:13:48.205  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-31 10:13:48.206  2153  2216 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-31 10:13:48.206  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 10:13:48.206  3253  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-31 10:13:48.206  3253  3958 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-31 10:13:48.206  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-31 10:13:48.206  3253  3958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-31 10:13:48.206  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-31 10:13:48.206  3253  3958 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-31 10:13:48.206  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-31 10:13:48.206  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-31 10:13:48.206  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-31 10:13:48.206  2153  2227 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-31 10:13:48.206  3253  3253 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-31 10:13:48.206  3253  3253 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-31 10:13:48.207  3253  3312 D BluetoothLeScanner: could not find callback wrapper
03-31 10:13:48.207  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 10:13:48.207  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,03-31 10:13:48.208  2153  2216 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-31 10:13:48.208  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 10:13:48.208  2153  2216 D BtGatt.GattService: current time is 233126289128
03-31 10:13:48.209  2153  2216 D BtGatt.GattService: Batch record : [-56, 40, -2, 24, 117, 119, 1, -128, -81, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -63, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-31 10:13:48.209  2153  2216 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-31 10:13:48.209  2153  2216 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
,03-31 10:13:48.209  2153  2226 D BtGatt.AdvertiseManager: message : 1
03-31 10:13:48.209  2153  2226 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-31 10:13:48.211  2153  2216 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0,
03-31 10:13:48.211  2153  2216 D BtGatt.GattService: Client app is not null!
03-31 10:13:48.212  2153  2171 D BtGatt.GattService: unregisterClient() - clientIf=6
03-31 10:13:48.213  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-31 10:13:48.213  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-31 10:13:48.213  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-31 10:13:48.213  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,03-31 10:13:48.213  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-31 10:13:48.213  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 10:13:48.213  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-31 10:13:48.213  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-31 10:13:48.253   822   856 I ActivityManager: Start proc 4042:com.google.android.music:main/u0a66 for service com.google.android.music/.sync.SyncAdapterService
,03-31 10:13:48.254  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-31 10:13:48.254  3253  3312 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-31 10:13:48.254  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 10:13:48.254  3253  3253 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-31 10:13:48.254  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 10:13:48.254  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-31 10:13:48.255  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-31 10:13:48.255  3253  3312 I jxcore-log: 
,03-31 10:13:48.263  3253  3253 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-31 10:13:48.264   822   840 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 10:13:48.267  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-31 10:13:48.270  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-31 10:13:48.270  3253  3253 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-31 10:13:48.273   822  1384 I ActivityManager: Killing 3141:com.google.android.talk/u0a61 (adj 15): empty #17
,03-31 10:13:48.273  3253  3253 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-31 10:13:48.273  3253  3253 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 10:13:48.273  3253  3253 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 10:13:48.274  3253  3253 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 10:13:48.274  3253  3253 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 10:13:48.275  3253  3312 I jxcore-log: ok 162 Should be able to call stopAdvertisingAndListening in teardown
03-31 10:13:48.275  3253  3312 I jxcore-log: 
03-31 10:13:48.281  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 10:13:48.281  3253  3312 I jxcore-log: 
,03-31 10:13:48.284  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 10:13:48.284  3253  3312 I jxcore-log: 
,03-31 10:13:48.285  3253  3312 I jxcore-log: # setup
03-31 10:13:48.285  3253  3312 I jxcore-log: 
,03-31 10:13:48.316  4042  4042 I MusicStore: Database version: 120
,03-31 10:13:48.401  3253  3312 I jxcore-log: # 40. Can connect to a remote peer
,03-31 10:13:48.401  3253  3312 I jxcore-log: 
,03-31 10:13:48.580   822   856 I ActivityManager: Start proc 4066:com.google.android.apps.cloudprint:sync/u0a41 for service com.google.android.apps.cloudprint/.printdialog.services.CloudPrintSyncService
,03-31 10:13:48.595  3253  3312 I io.jxcore.node.ConnectionHelper: start: Port number: 37640, start advertisements: true
,03-31 10:13:48.595  3253  3312 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-31 10:13:48.595  3253  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-31 10:13:48.595  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-31 10:13:48.601  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-31 10:13:48.601  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-31 10:13:48.601  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 10:13:48.601  3253  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 10:13:48.604  2153  2171 D BtGatt.GattService: registerClient() - UUID=7763c0f5-fe4f-42d3-a0f4-7f64a6d552d4
03-31 10:13:48.604  2153  2216 D BtGatt.GattService: onClientRegistered() - UUID=7763c0f5-fe4f-42d3-a0f4-7f64a6d552d4, clientIf=5
03-31 10:13:48.605  3253  3268 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-31 10:13:48.606  2153  2170 D BtGatt.GattService: start scan with filters
03-31 10:13:48.607  2153  2227 D BtGatt.ScanManager: handling starting scan
,03-31 10:13:48.609  2153  2216 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-31 10:13:48.609  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 10:13:48.610  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-31 10:13:48.610  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 10:13:48.610  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-31 10:13:48.611  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-31 10:13:48.611  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 10:13:48.611  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-31 10:13:48.611  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-31 10:13:48.611  3253  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-31 10:13:48.611  3253  3253 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 10:13:48.611  3253  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 10:13:48.611  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 10:13:48.611  3253  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-31 10:13:48.612  2153  2216 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-31 10:13:48.612  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 10:13:48.613  2153  2227 D BtGatt.ScanManager: Starting BLE batch scan
03-31 10:13:48.613  2153  2227 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-31 10:13:48.615  2153  2337 D BtGatt.GattService: registerClient() - UUID=c5d46fa3-b02c-4c00-8332-c73eee1dcdac
03-31 10:13:48.615  2153  2216 D BtGatt.GattService: onClientRegistered() - UUID=c5d46fa3-b02c-4c00-8332-c73eee1dcdac, clientIf=6
03-31 10:13:48.615  3253  3854 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-31 10:13:48.616  2153  2216 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-31 10:13:48.616  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 10:13:48.616  2153  2226 D BtGatt.AdvertiseManager: message : 0
,03-31 10:13:48.618  2153  2216 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-31 10:13:48.618  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 10:13:48.619  2153  2226 D BtGatt.AdvertiseManager: starting multi advertising
,03-31 10:13:48.623  2153  2216 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-31 10:13:48.627  2153  2216 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-31 10:13:48.628  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-31 10:13:48.628  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-31 10:13:48.628   822   841 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 10:13:48.631  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 10:13:48.631  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-31 10:13:48.631  3253  3312 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-31 10:13:48.631  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-31 10:13:48.632  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-31 10:13:48.633  3253  3312 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-31 10:13:48.633  3253  3312 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-31 10:13:48.633  3253  3312 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,03-31 10:13:48.633  3253  3253 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-31 10:13:48.634  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,03-31 10:13:48.634  3253  3253 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-31 10:13:48.634  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-31 10:13:48.634  3253  3253 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-31 10:13:48.634  3253  3253 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-31 10:13:48.634  3253  3253 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-31 10:13:48.634  3253  3253 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 10:13:48.634  3253  3253 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-31 10:13:48.634  3253  3253 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 10:13:48.634   822  1201 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-31 10:13:48.634  3253  3253 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-31 10:13:48.634  3253  3253 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-31 10:13:48.635  3253  4085 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-31 10:13:48.635  3253  3312 I io.jxcore.node.ConnectionHelper: start: OK
,03-31 10:13:48.637  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false},
03-31 10:13:48.637  3253  3312 I jxcore-log: 
03-31 10:13:48.638  3253  3312 I jxcore-log: ok 163 Can call startUpdateAdvertisingAndListening without error
03-31 10:13:48.638  3253  3312 I jxcore-log: 
,03-31 10:13:48.639  3253  4085 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-31 10:13:48.640  3253  3312 I io.jxcore.node.ConnectionHelper: start: Port number: 37640, start advertisements: false
,03-31 10:13:48.641  3253  3312 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 10:13:48.641  3253  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should affect listening to advertisements only
03-31 10:13:48.641  3253  3312 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 10:13:48.641  3253  3312 I io.jxcore.node.ConnectionHelper: start: OK
03-31 10:13:48.642  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 10:13:48.642  3253  3312 I jxcore-log: 
03-31 10:13:48.642  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-31 10:13:48.642  3253  3312 I jxcore-log: 
,03-31 10:13:48.644  3253  3312 I jxcore-log: ok 164 Can call startListeningForAdvertisements without error
03-31 10:13:48.644  3253  3312 I jxcore-log: 
,03-31 10:13:48.674  4042  4042 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-31 10:13:48.674  4042  4042 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-31 10:13:48.703  4042  4042 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,03-31 10:13:48.746  4042  4042 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
03-31 10:13:48.746  4042  4042 D AndroidMusic: GMSCore installation verified
,03-31 10:13:48.752  4042  4042 I ConfigStore: Config Database version: 1
,03-31 10:13:48.850  4042  4042 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,03-31 10:13:48.912  4042  4042 I GHttpClientFactory: Using our fixed implementation of GMSCore's GoogleHttpClient
,03-31 10:13:48.926  4042  4042 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,03-31 10:13:48.936  4042  4042 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,03-31 10:13:48.937  4042  4089 I MusicLifecycle: Sync started
,03-31 10:13:48.982   822  1429 I ActivityManager: Start proc 4092:com.google.android.apps.cloudprint/u0a41 for service com.google.android.apps.cloudprint/.printdialog.services.NotificationIntentService
,03-31 10:13:48.997  4042  4042 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,03-31 10:13:49.007  4042  4042 I GHttpClientFactory: Using our fixed implementation of GMSCore's GoogleHttpClient
,03-31 10:13:49.009  4042  4042 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,03-31 10:13:49.019  4066  4109 I com.google.android.apps.cloudprint.printdialog.database.CloudPrintSyncAdapter: Sync request not initiated by GCP app. Dropping
,03-31 10:13:49.063   822   841 I ActivityManager: Killing 3714:com.google.android.gms:car/u0a11 (adj 15): empty #17
,03-31 10:13:49.288  2153  2153 D BtGatt.ScanManager: awakened up at time 234205
,03-31 10:13:49.290  2153  2227 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-31 10:13:49.291   822   840 I ActivityManager: Killing 3771:com.google.android.googlequicksearchbox:search/u0a28 (adj 15): empty #17
,03-31 10:13:49.300  2153  2216 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-31 10:13:49.300  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 10:13:49.300  2153  2216 D BtGatt.GattService: current time is 234218050534
03-31 10:13:49.301  2153  2216 D BtGatt.GattService: Batch record : [-58, 91, 20, -32, -98, 113, 1, -128, -80, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -64, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
,03-31 10:13:49.301  2153  2216 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-31 10:13:49.302  2153  2216 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-31 10:13:49.305  3253  3253 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> E0:DB:10:14:E2:C0], added - the peer count is 1
,03-31 10:13:49.306  3253  3253 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 2
03-31 10:13:49.306  3253  3253 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> E0:DB:10:14:E2:C0], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: ,
03-31 10:13:49.307  3253  3253 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
,03-31 10:13:49.312  3253  3312 I jxcore-log: INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"E0:DB:10:14:E2:C0","peerAvailable":true,"pleaseConnect":false}],
03-31 10:13:49.312  3253  3312 I jxcore-log: 
,03-31 10:13:49.325  3253  3312 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID E0:DB:10:14:E2:C0
,03-31 10:13:49.325  3253  3312 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> E0:DB:10:14:E2:C0]
,03-31 10:13:49.404  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address E0:DB:10:14:E2:C0
03-31 10:13:49.406  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
03-31 10:13:49.406  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
03-31 10:13:49.407  3253  3312 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null E0:DB:10:14:E2:C0
03-31 10:13:49.408  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address E0:DB:10:14:E2:C0
,03-31 10:13:49.408  3253  3312 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: E0:DB:10:14:E2:C0)
03-31 10:13:49.410  3253  4115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address E0:DB:10:14:E2:C0 (thread ID: 352)
,03-31 10:13:49.411  3253  4115 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-31 10:13:49.413  3253  3312 I jxcore-log: INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"pleaseConnect":false}],
03-31 10:13:49.413  3253  3312 I jxcore-log: 
,03-31 10:13:49.416  2153  2170 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,03-31 10:13:49.459  1265  1265 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 10:13:49.474  1804  4116 E Auth.Api.Credentials: [CredentialSyncAdapter] Unknown sync event.
,03-31 10:13:49.511  1265  2559 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.music, service: sj
,03-31 10:13:49.511  1265  2559 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> sj without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 10:13:49.511  1265  2559 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 10:13:49.511  1265  2559 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 10:13:49.518  1265  2559 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 10:13:49.584  1265  2559 W GLSActivity: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-31 10:13:49.584  1265  2559 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-31 10:13:49.584  1265  2559 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-31 10:13:49.584  1265  2559 W GLSActivity: 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
03-31 10:13:49.584  1265  2559 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
03-31 10:13:49.584  1265  2559 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
03-31 10:13:49.584  1265  2559 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:446)
,03-31 10:13:49.601  4042  4089 I MusicLifecycle: Sync ended
03-31 10:13:49.601  4042  4089 W MusicSyncAdapter: Sync failed due to an authentication issue.
,03-31 10:13:49.613   822   856 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.music.MusicContent, PERIODIC, currentRunTime 230105, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,03-31 10:13:49.614   822   856 D SyncManager: not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.music.MusicContent, PERIODIC, currentRunTime 266143, reason: Periodic
,03-31 10:13:49.656  4042  4118 I MusicLeanback: Conditions not met for autocaching. okToAttempt=false
03-31 10:13:49.656  4042  4118 I MusicLeanback: Stop autocaching.
,03-31 10:13:49.710  3742  3742 D WearableService: callingUid 10011, callindPid: 3742
,03-31 10:13:49.747  4042  4042 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
03-31 10:13:49.748  4042  4126 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,03-31 10:13:49.753   822  1329 I ActivityManager: Killing 3795:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,03-31 10:13:50.816   822  1412 I ActivityManager: Killing 3355:com.google.android.apps.gcs/u0a89 (adj 15): empty #17
,03-31 10:13:51.411  3872  3915 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,03-31 10:13:52.328  2153  2228 W bt-btif : info:x10
03-31 10:13:52.329  2153  2216 D         : remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,03-31 10:13:52.330  2153  2216 E BluetoothRemoteDevices: aclStateChangeCallback: Device is NULL
,03-31 10:13:52.614  2153  2228 W bt-sdp  : process_service_search_attr_rsp
,03-31 10:13:53.599  2153  2216 D btif_config: btif_get_device_type: Device [e0:db:10:14:e2:c0] type 1
,03-31 10:13:53.609  2153  2216 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 1
,03-31 10:13:53.609  2153  2216 E bt-btif : check_cod: remote_cod = 0x5a020c
,03-31 10:13:53.615  2153  2217 I BluetoothBondStateMachine: Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 10 NewState: 11
03-31 10:13:53.615  2153  2217 I BluetoothBondStateMachine: Entering PendingCommandState State
,03-31 10:13:53.683   822   857 I ActivityManager: Start proc 4131:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.BluetoothPairingRequest
,03-31 10:13:53.701   369   369 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 357us total 17.441ms
,03-31 10:13:53.716   369   369 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 346us total 15.040ms
,03-31 10:13:53.735   369   369 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 468us total 17.237ms
,03-31 10:13:53.763   822   861 D BluetoothManagerService: Message: 20
03-31 10:13:53.763   822   861 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@181c37d7:true
,03-31 10:13:53.766   822  1449 I ActivityManager: Killing 3678:com.android.vending/u0a19 (adj 15): empty #17
,03-31 10:13:53.946  2153  2216 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 0
,03-31 10:13:53.948  2153  2217 D BluetoothAdapterProperties: Failed to remove device: E0:DB:10:14:E2:C0
,03-31 10:13:53.981  2153  2217 I BluetoothBondStateMachine: Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 11 NewState: 10
,03-31 10:13:54.096   822  1329 I art     : Explicit concurrent mark sweep GC freed 19006(782KB) AllocSpace objects, 6(473KB) LOS objects, 32% free, 33MB/49MB, paused 2.245ms total 89.234ms
,03-31 10:13:54.123  2153  2217 I BluetoothBondStateMachine: StableState(): Entering Off State
,03-31 10:13:54.136  4042  4150 I MusicLeanback: Conditions not met for autocaching. okToAttempt=false
03-31 10:13:54.136  4042  4150 I MusicLeanback: Stop autocaching.
,03-31 10:13:54.150  4042  4042 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,03-31 10:13:54.155  4042  4155 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,03-31 10:13:54.305  2153  2153 D BtGatt.ScanManager: awakened up at time 239223
,03-31 10:13:54.309  2153  2227 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-31 10:13:54.315  2153  2216 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-31 10:13:54.315  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 10:13:54.315  2153  2216 D BtGatt.GattService: current time is 239232951574
,03-31 10:13:54.316  2153  2216 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -55, 61, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0, -58, 91, 20, -32, -98, 113, 1, -128, -76, 62, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-31 10:13:54.316  2153  2216 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-31 10:13:54.317  2153  2216 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,03-31 10:13:54.321  3253  3253 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> E0:DB:10:14:E2:C0] updated - the peer count is 2
03-31 10:13:54.321  3253  3253 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
,03-31 10:13:54.581  2153  2228 W bt-btif : new conn_srvc id:26, app_id:1
03-31 10:13:54.581  2153  2228 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:1
,03-31 10:13:54.581  2153  2228 W bt-btif : bta_dm_pm_ssr:2, lat:1200
03-31 10:13:54.582  3253  4115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onSocketConnected: [<no peer name> E0:DB:10:14:E2:C0] (thread ID: 352)
03-31 10:13:54.583  3253  4115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 352)
,03-31 10:13:54.585  3253  4115 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesWritten: 15 bytes successfully written (thread ID: 353)
,03-31 10:13:54.586  3253  4115 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Outgoing connection initialized (*handshake* thread ID: 353)
,03-31 10:13:54.586  3253  4115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 352)
03-31 10:13:54.590  3253  4158 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 353)
,03-31 10:13:54.925  3253  4158 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesRead: Read 15 bytes successfully (thread ID: 353),
03-31 10:13:54.928  3253  4158 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Handshake succeeded with [<no peer name> E0:DB:10:14:E2:C0]
03-31 10:13:54.929  3253  4158 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onHandshakeSucceeded: [<no peer name> E0:DB:10:14:E2:C0] (thread ID: 352)
03-31 10:13:54.929  3253  4158 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: handleSuccessfulClientThread: [<no peer name> E0:DB:10:14:E2:C0] (thread ID: 352)
03-31 10:13:54.930  3253  4158 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 353)
03-31 10:13:54.930  3253  3253 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> E0:DB:10:14:E2:C0]
03-31 10:13:54.931  3253  3253 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing connection to peer [<no peer name> E0:DB:10:14:E2:C0],
03-31 10:13:54.931  3253  3253 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> E0:DB:10:14:E2:C0] updated - the peer count is 2
03-31 10:13:54.934  3253  3253 I io.jxcore.node.ConnectionHelper: lowerBleDiscoveryPowerAndStartResetTimer: Lowering the power settings
03-31 10:13:54.936  3253  3253 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 2 -> 0
03-31 10:13:54.937  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-31 10:13:54.937  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-31 10:13:54.937  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-31 10:13:54.937  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-31 10:13:54.937  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-31 10:13:54.937  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-31 10:13:54.942  2153  2226 D BtGatt.AdvertiseManager: message : 1
03-31 10:13:54.943  2153  2226 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-31 10:13:54.950  2153  2216 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0,
03-31 10:13:54.950  2153  2216 D BtGatt.GattService: Client app is not null!
03-31 10:13:54.953  2153  2337 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-31 10:13:54.954  3253  3253 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-31 10:13:54.954  3253  3253 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,03-31 10:13:54.954  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 3, timeout: 0, is connectable: false
03-31 10:13:54.954  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-31 10:13:54.954  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-31 10:13:54.954  3253  3253 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-31 10:13:54.955  3253  3253 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 10:13:54.956  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-31 10:13:54.957  3253  3253 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-31 10:13:54.965  2153  2171 D BtGatt.GattService: registerClient() - UUID=d883bd0e-f983-4cbe-bf42-ca72adcf41b4
,03-31 10:13:54.965  2153  2216 D BtGatt.GattService: onClientRegistered() - UUID=d883bd0e-f983-4cbe-bf42-ca72adcf41b4, clientIf=6
03-31 10:13:54.965  3253  3854 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-31 10:13:54.967  2153  2226 D BtGatt.AdvertiseManager: message : 0
,03-31 10:13:54.971  2153  2226 D BtGatt.AdvertiseManager: starting multi advertising,
,03-31 10:13:54.974  2153  2216 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0,
,03-31 10:13:54.977  2153  2216 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0,
03-31 10:13:54.977  3253  3253 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-31 10:13:54.979  2153  2170 D BtGatt.GattService: stopScan() - queue size =1
,03-31 10:13:54.981  2153  2337 D BtGatt.GattService: unregisterClient() - clientIf=5,
03-31 10:13:54.981  3253  3253 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 10:13:54.982  3253  3253 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 10:13:54.982  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-31 10:13:54.982  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-31 10:13:54.982  3253  3253 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 10:13:54.982  3253  3253 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 10:13:54.983  2153  2216 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-31 10:13:54.983  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 10:13:54.984  2153  2227 D BtGatt.ScanManager: stopping BLe Batch
03-31 10:13:54.985  2153  2216 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-31 10:13:54.985  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 10:13:54.986  2153  2227 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-31 10:13:54.988  2153  2216 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-31 10:13:54.988  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 10:13:54.988  2153  2216 D BtGatt.GattService: current time is 239905772511
03-31 10:13:54.988  2153  2216 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -58, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0, -58, 91, 20, -32, -98, 113, 1, -128, -83, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-31 10:13:54.988  2153  2216 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-31 10:13:54.988  2153  2216 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-31 10:13:54.990  2153  2171 D BtGatt.GattService: registerClient() - UUID=74a60b80-6086-462c-9644-a1f4f97a6815
03-31 10:13:54.990  2153  2216 D BtGatt.GattService: onClientRegistered() - UUID=74a60b80-6086-462c-9644-a1f4f97a6815, clientIf=5
03-31 10:13:54.990  3253  3268 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5,
03-31 10:13:54.991  2153  2170 D BtGatt.GattService: start scan with filters
03-31 10:13:54.991  3253  3253 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-31 10:13:54.991  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 10:13:54.991  3253  3253 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 3 -> 1
,03-31 10:13:54.991  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-31 10:13:54.991  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-31 10:13:54.991  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-31 10:13:54.991  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-31 10:13:54.991  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-31 10:13:54.991  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-31 10:13:54.993  2153  2226 D BtGatt.AdvertiseManager: message : 1
,03-31 10:13:54.994  2153  2226 D BtGatt.AdvertiseManager: stop advertise for client 6
03-31 10:13:54.997  2153  2216 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-31 10:13:54.997  2153  2216 D BtGatt.GattService: Client app is not null!
03-31 10:13:54.998  2153  2337 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-31 10:13:54.999  3253  3253 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-31 10:13:55.000  3253  3253 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-31 10:13:55.000  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-31 10:13:55.000  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,03-31 10:13:55.000  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-31 10:13:55.000  3253  3253 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-31 10:13:55.000  3253  3253 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-31 10:13:55.000  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 10:13:55.000  3253  3253 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-31 10:13:55.003  2153  2227 D BtGatt.ScanManager: handling starting scan
03-31 10:13:55.005  2153  2216 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1,
03-31 10:13:55.005  2153  2337 D BtGatt.GattService: registerClient() - UUID=6881d7e8-0225-4ff3-8eaa-c893c04a9f8b
03-31 10:13:55.005  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
03-31 10:13:55.006  2153  2216 D BtGatt.GattService: onClientRegistered() - UUID=6881d7e8-0225-4ff3-8eaa-c893c04a9f8b, clientIf=6
03-31 10:13:55.006  3253  3269 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-31 10:13:55.007  2153  2216 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-31 10:13:55.007  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 10:13:55.007  2153  2227 D BtGatt.ScanManager: Starting BLE batch scan,
03-31 10:13:55.007  2153  2227 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-31 10:13:55.008  2153  2226 D BtGatt.AdvertiseManager: message : 0
03-31 10:13:55.008  2153  2216 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-31 10:13:55.009  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 10:13:55.010  2153  2216 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-31 10:13:55.010  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 10:13:55.011  2153  2226 D BtGatt.AdvertiseManager: starting multi advertising
,03-31 10:13:55.014  2153  2216 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-31 10:13:55.016  2153  2216 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-31 10:13:55.016  3253  3253 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-31 10:13:55.018  2153  2337 D BtGatt.GattService: stopScan() - queue size =1
,03-31 10:13:55.019  2153  2170 D BtGatt.GattService: unregisterClient() - clientIf=5
03-31 10:13:55.019  3253  3253 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 10:13:55.019  3253  3253 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 10:13:55.019  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-31 10:13:55.019  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-31 10:13:55.019  3253  3253 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 10:13:55.019  3253  3253 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-31 10:13:55.020  2153  2216 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-31 10:13:55.020  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 10:13:55.020  2153  2227 D BtGatt.ScanManager: stopping BLe Batch
,03-31 10:13:55.021  2153  2216 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-31 10:13:55.022  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 10:13:55.022  2153  2227 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-31 10:13:55.023  2153  2216 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-31 10:13:55.023  2153  2171 D BtGatt.GattService: registerClient() - UUID=ff9ba30b-df91-406e-873e-b435f5e337e9
03-31 10:13:55.023  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 10:13:55.023  2153  2216 D BtGatt.GattService: onClientRegistered() - UUID=ff9ba30b-df91-406e-873e-b435f5e337e9, clientIf=5
03-31 10:13:55.023  3253  3854 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-31 10:13:55.025  2153  2337 D BtGatt.GattService: start scan with filters
,03-31 10:13:55.026  3253  3253 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-31 10:13:55.026  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 10:13:55.026  3253  3253 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 2 -> 0
,03-31 10:13:55.026  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-31 10:13:55.026  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-31 10:13:55.026  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-31 10:13:55.026  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-31 10:13:55.026  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-31 10:13:55.026  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-31 10:13:55.027  2153  2227 D BtGatt.ScanManager: handling starting scan
03-31 10:13:55.028  2153  2226 D BtGatt.AdvertiseManager: message : 1
03-31 10:13:55.028  2153  2226 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-31 10:13:55.029  2153  2216 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-31 10:13:55.029  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 10:13:55.030  2153  2216 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,03-31 10:13:55.030  2153  2216 D BtGatt.GattService: Client app is not null!
03-31 10:13:55.031  2153  2337 D BtGatt.GattService: unregisterClient() - clientIf=6
03-31 10:13:55.032  3253  3253 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-31 10:13:55.032  3253  3253 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
,03-31 10:13:55.032  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-31 10:13:55.032  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-31 10:13:55.032  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-31 10:13:55.032  3253  3253 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-31 10:13:55.032  3253  3253 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 10:13:55.032  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 10:13:55.032  3253  3253 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-31 10:13:55.033  2153  2216 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-31 10:13:55.033  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 10:13:55.033  2153  2227 D BtGatt.ScanManager: Starting BLE batch scan
03-31 10:13:55.033  2153  2227 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-31 10:13:55.035  2153  2216 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,03-31 10:13:55.035  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 10:13:55.036  2153  2216 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-31 10:13:55.036  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 10:13:55.037  2153  2171 D BtGatt.GattService: registerClient() - UUID=cb2323a2-a0b5-4d42-852d-44edf362453c
,03-31 10:13:55.037  2153  2216 D BtGatt.GattService: onClientRegistered() - UUID=cb2323a2-a0b5-4d42-852d-44edf362453c, clientIf=6
03-31 10:13:55.037  3253  3268 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-31 10:13:55.038  2153  2226 D BtGatt.AdvertiseManager: message : 0
,03-31 10:13:55.041  2153  2226 D BtGatt.AdvertiseManager: starting multi advertising
,03-31 10:13:55.043  2153  2216 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-31 10:13:55.045  2153  2216 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-31 10:13:55.046  3253  3253 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-31 10:13:55.047  2153  2170 D BtGatt.GattService: stopScan() - queue size =1
,03-31 10:13:55.048  2153  2337 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-31 10:13:55.048  3253  3253 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 10:13:55.048  3253  3253 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 10:13:55.048  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-31 10:13:55.048  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-31 10:13:55.048  3253  3253 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 10:13:55.048  3253  3253 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null],
03-31 10:13:55.048  2153  2216 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-31 10:13:55.048  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 10:13:55.049  2153  2227 D BtGatt.ScanManager: stopping BLe Batch
,03-31 10:13:55.051  2153  2216 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,03-31 10:13:55.051  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 10:13:55.051  2153  2171 D BtGatt.GattService: registerClient() - UUID=a12b5623-19ea-4a7e-82ba-299b271a4381
03-31 10:13:55.051  2153  2216 D BtGatt.GattService: onClientRegistered() - UUID=a12b5623-19ea-4a7e-82ba-299b271a4381, clientIf=5
03-31 10:13:55.052  2153  2227 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-31 10:13:55.052  3253  3269 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-31 10:13:55.052  2153  2337 D BtGatt.GattService: start scan with filters
03-31 10:13:55.053  3253  3253 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-31 10:13:55.053  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 10:13:55.053  2153  2216 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,03-31 10:13:55.053  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 10:13:55.053  3253  3253 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing socket thread, for peer [<no peer name> E0:DB:10:14:E2:C0], created successfully
03-31 10:13:55.053  3253  3253 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 1
03-31 10:13:55.053  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-31 10:13:55.053  3253  3253 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-31 10:13:55.053  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-31 10:13:55.053  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,03-31 10:13:55.053  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-31 10:13:55.054  3253  4159 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 354)
03-31 10:13:55.055  3253  4159 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 44610
03-31 10:13:55.055  3253  4159 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
03-31 10:13:55.055  3253  4159 I io.jxcore.node.ConnectionHelper: onListeningForIncomingConnections: Outgoing connection is using port 44610 (peer ID: E0:DB:10:14:E2:C0)
03-31 10:13:55.055  3253  4159 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "E0:DB:10:14:E2:C0" removed
03-31 10:13:55.059  3253  3312 I jxcore-log: INFO testThaliMobileNative: 
03-31 10:13:55.059  3253  3312 I jxcore-log: 
,03-31 10:13:55.059  3253  3312 I jxcore-log: ok 165 Must have listeningPort
03-31 10:13:55.059  3253  3312 I jxcore-log: 
03-31 10:13:55.060  3253  3312 I jxcore-log: ok 166 listeningPort must be a number
03-31 10:13:55.060  3253  3312 I jxcore-log: 
03-31 10:13:55.060  3253  3312 I jxcore-log: ok 167 Connection must have clientPort
03-31 10:13:55.060  3253  3312 I jxcore-log: 
03-31 10:13:55.060  3253  3312 I jxcore-log: ok 168 clientPort must be a number
03-31 10:13:55.060  3253  3312 I jxcore-log: 
,03-31 10:13:55.061  3253  3312 I jxcore-log: ok 169 Connection must have serverPort
03-31 10:13:55.061  3253  3312 I jxcore-log: 
03-31 10:13:55.061  3253  3312 I jxcore-log: ok 170 serverPort must be a number
03-31 10:13:55.061  3253  3312 I jxcore-log: 
03-31 10:13:55.061  3253  3312 I jxcore-log: ok 171 forward connection must have clientPort == 0
03-31 10:13:55.061  3253  3312 I jxcore-log: 
03-31 10:13:55.062  3253  3312 I jxcore-log: ok 172 forward connection must have serverPort == 0
03-31 10:13:55.062  3253  3312 I jxcore-log: 
03-31 10:13:55.063  2153  2227 D BtGatt.ScanManager: handling starting scan
,03-31 10:13:55.065  2153  2216 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-31 10:13:55.065  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 10:13:55.066  2153  2216 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-31 10:13:55.066  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 10:13:55.066  2153  2227 D BtGatt.ScanManager: Starting BLE batch scan
03-31 10:13:55.066  2153  2227 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-31 10:13:55.068  2153  2216 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-31 10:13:55.068  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 10:13:55.069  2153  2216 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-31 10:13:55.069  3253  3312 I jxcore-log: # teardown
03-31 10:13:55.069  3253  3312 I jxcore-log: 
03-31 10:13:55.069  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 10:13:58.331  2153  2214 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,03-31 10:13:59.110  2153  2218 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-31 10:13:59.726   822  1002 I ActivityManager: Start proc 4161:com.android.vending/u0a19 for service com.android.vending/com.google.android.finsky.services.ContentSyncService
,03-31 10:13:59.907  4161  4161 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,03-31 10:13:59.931  2153  2228 W bt-btif : dm_pm_timer expires
03-31 10:13:59.931  2153  2228 W bt-btif : dm_pm_timer expires 0
,03-31 10:13:59.931  2153  2228 W bt-btif : proc dm_pm_timer expires
,03-31 10:14:00.003  4161  4161 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,03-31 10:14:00.009  2153  2153 D BtGatt.ScanManager: awakened up at time 244927
03-31 10:14:00.010  2153  2227 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-31 10:14:00.014  2153  2216 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-31 10:14:00.014  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 10:14:00.014  2153  2216 D BtGatt.GattService: current time is 244931993967
03-31 10:14:00.014  2153  2216 D BtGatt.GattService: Batch record : [-58, 91, 20, -32, -98, 113, 1, -128, -80, 65, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -70, 72, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-31 10:14:00.015  2153  2216 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-31 10:14:00.015  2153  2216 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-31 10:14:00.016  3253  3253 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
03-31 10:14:00.016  3253  3253 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> E0:DB:10:14:E2:C0] updated - the peer count is 2
,03-31 10:14:00.123   822  1449 I ActivityManager: Start proc 4199:com.google.android.gms:car/u0a11 for service com.google.android.gms/.car.CarService
,03-31 10:14:00.137  4161  4161 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-31 10:14:00.139  4161  4161 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-31 10:14:00.184  4199  4199 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-31 10:14:00.184  4199  4199 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-31 10:14:00.192  4161  4161 D Finsky  : [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
03-31 10:14:00.193  4161  4161 D Finsky  : [1] 2.run: Finished loading 1 libraries.
,03-31 10:14:00.210  4161  4161 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,03-31 10:14:00.215  4199  4199 I MultiDex: VM with version 2.1.0 has multidex support
03-31 10:14:00.215  4199  4199 I MultiDex: install
03-31 10:14:00.215  4199  4199 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,03-31 10:14:00.226  4161  4161 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,03-31 10:14:00.230  4199  4199 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,03-31 10:14:00.260  4199  4199 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-31 10:14:00.269  1265  2533 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,03-31 10:14:00.274  1265  1265 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-31 10:14:00.283  1804  1804 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,03-31 10:14:00.310  3742  3742 D WearableService: callingUid 10011, callindPid: 3742
,03-31 10:14:00.316  1832  2111 E MDM     : [148] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,03-31 10:14:00.321  1804  4225 D LocationInitializer: Restart initialization of location
,03-31 10:14:00.347  1265  1720 I art     : Explicit concurrent mark sweep GC freed 9967(471KB) AllocSpace objects, 11(1212KB) LOS objects, 37% free, 26MB/42MB, paused 1.159ms total 40.685ms
,03-31 10:14:00.384  3253  3312 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-31 10:14:00.384  3253  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
03-31 10:14:00.384  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-31 10:14:00.385  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-31 10:14:00.389  2153  2170 D BtGatt.GattService: stopScan() - queue size =1
,03-31 10:14:00.391  2153  2171 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-31 10:14:00.392  2153  2216 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-31 10:14:00.392  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 10:14:00.392  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 10:14:00.392  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 10:14:00.392  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-31 10:14:00.392  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-31 10:14:00.392  2153  2227 D BtGatt.ScanManager: stopping BLe Batch
03-31 10:14:00.392  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-31 10:14:00.392  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-31 10:14:00.392  3253  3253 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-31 10:14:00.392  3253  3253 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
03-31 10:14:00.393  3253  3253 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 10:14:00.393  3253  3312 I jxcore-log: ok 173 Should be able to call stopListeningForAdvertisments in teardown
03-31 10:14:00.393  3253  3312 I jxcore-log: 
03-31 10:14:00.394  3253  3312 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-31 10:14:00.394  3253  3312 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> E0:DB:10:14:E2:C0]
03-31 10:14:00.394  3253  3312 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 354)
03-31 10:14:00.394  3253  3312 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 354)
03-31 10:14:00.394  3253  3312 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
03-31 10:14:00.394  3253  3312 D io.jxcore.node.OutgoingSocketThread: closeLocalSocketAndStreams: Nothing to close (thread ID: 354)
03-31 10:14:00.394  3253  3312 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 354)
03-31 10:14:00.394  3253  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
03-31 10:14:00.394  3253  3312 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-31 10:14:00.394  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-31 10:14:00.394  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-31 10:14:00.394  2153  2216 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-31 10:14:00.394  3253  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-31 10:14:00.394  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 10:14:00.394  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-31 10:14:00.394  3253  4085 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-31 10:14:00.394  3253  4085 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-31 10:14:00.394  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-31 10:14:00.394  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-31 10:14:00.394  3253  4085 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-31 10:14:00.394  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-31 10:14:00.394  3253  3253 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-31 10:14:00.394  3253  3253 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-31 10:14:00.395  3253  4159 D io.jxcore.node.OutgoingSocketThread: Exiting thread (ID: 354)
03-31 10:14:00.395  3253  3253 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-31 10:14:00.395  2153  2227 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-3,1 10:14:00.395  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-31 10:14:00.396  2153  2216 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-31 10:14:00.396  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 10:14:00.397  3253  3312 D BluetoothLeScanner: could not find callback wrapper
03-31 10:14:00.397  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 10:14:00.397  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-31 10:14:00.399  2153  2226 D BtGatt.AdvertiseManager: message : 1
03-31 10:14:00.400  2153  2226 D BtGatt.AdvertiseManager: stop advertise for client 6
03-31 10:14:00.403  2153  2216 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-31 10:14:00.403  2153  2216 D BtGatt.GattService: Client app is not null!
03-31 10:14:00.405  2153  2171 D BtGatt.GattService: unregisterClient() - clientIf=6
03-31 10:14:00.405  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-31 10:14:00.405  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-31 10:14:00.405  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-31 10:14:00.405  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-31 10:14:00.405  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-31 10:14:00.405  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 10:14:00.405  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-31 10:14:00.405  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-31 10:14:00.406  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-31 10:14:00.406  3253  3312 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-31 10:14:00.406  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 10:14:00.407  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-31 10:14:00.407  3253  3312 I jxcore-log: 
03-31 10:14:00.407  3253  3253 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 10:14:00.407  3253  3253 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 10:14:00.407  3253  3253 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 10:14:00.407  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 10:14:00.407  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-31 10:14:00.409  3253  3312 I jxcore-log: ok 174 Should be able to call stopAdvertisingAndListening in teardown
03-31 10:14:00.409  3253  3312 I jxcore-log: 
03-31 10:14:00.412  3253  3312 I jxcore-log: # setup
03-31 10:14:00.412  3253  3312 I jxcore-log: 
03-31 10:14:00.414  3253  3253 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-31 10:14:00.415   822   840 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-31 10:14:00.418  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-31 10:14:00.419  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-31 10:14:00.419  3253  3253 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 10:14:00.421  3253  3253 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 10:14:00.421  3253  3253 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 10:14:00.422  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 10:14:00.422  3253  3312 I jxcore-log: 
03-31 10:14:00.422  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 10:14:00.422  3253  3312 I jxcore-log: 
,03-31 10:14:00.460  2153  2228 W bt-btif : bta_jv_rfc_port_to_cb(port_handle:0xd):jv handle:0x0 not FOUND
,03-31 10:14:00.525  4161  4161 V Finsky  : [1] GearheadStateMonitor.onReady: sIsProjecting:false
,03-31 10:14:00.530  1265  1265 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 10:14:00.553  1265  1902 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,03-31 10:14:00.554  1265  1902 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 10:14:00.554  1265  1902 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 10:14:00.554  1265  1902 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 10:14:00.558  1265  1902 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 10:14:00.572  4161  4161 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,03-31 10:14:00.572  4161  4161 D Finsky  : [1] 5.onFinished: Installation state replication failed.
03-31 10:14:00.572  4161  4161 D Finsky  : [1] 5.onFinished: Scheduling replication attempt 3.
,03-31 10:14:00.937   822  1429 I ActivityManager: Start proc 4231:com.google.android.apps.gcs/u0a89 for service com.google.android.apps.gcs/com.google.android.flib.nova.experiment.ExperimentUpdateService
,03-31 10:14:01.026  4161  4161 D Finsky  : [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,03-31 10:14:01.052  1265  1265 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 10:14:01.092  1265  3209 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,03-31 10:14:01.092  1265  3209 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 10:14:01.092  1265  3209 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 10:14:01.092  1265  3209 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 10:14:01.097  1265  3209 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 10:14:01.115  4161  4161 W Finsky  : [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,03-31 10:14:01.124  1265  1265 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 10:14:01.155  1265  3209 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,03-31 10:14:01.156  1265  3209 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 10:14:01.156  1265  3209 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 10:14:01.156  1265  3209 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 10:14:01.169  1265  3209 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 10:14:01.219  3253  3312 I jxcore-log: # 41. Can shift large amounts of data
03-31 10:14:01.219  3253  3312 I jxcore-log: 
,03-31 10:14:01.282  4231  4258 V GoogleAuthProtoRequest: [465] a.<init>: mAccountName set to: thalitester@gmail.com
03-31 10:14:01.283  1265  1265 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 10:14:01.323  1265  1283 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
03-31 10:14:01.324  1265  1283 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 10:14:01.324  1265  1283 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 10:14:01.324  1265  1283 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 10:14:01.329  1265  1283 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 10:14:01.345  1265  1719 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,03-31 10:14:01.346  1265  1719 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-31 10:14:01.346  1265  1719 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 10:14:01.346  1265  1719 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 10:14:01.352  1265  1719 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,03-31 10:14:01.356  4161  4161 W Finsky  : [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,03-31 10:14:01.382  4231  4258 W ExperimentUpdateService: [465] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,03-31 10:14:01.384  4231  4258 W ExperimentUpdateService: [465] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-31 10:14:01.384  4231  4258 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-31 10:14:01.384  4231  4258 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-31 10:14:01.384  4231  4258 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-31 10:14:01.384  4231  4258 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-31 10:14:01.384  4231  4258 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-31 10:14:01.384  4231  4258 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-31 10:14:01.384  4231  4258 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-31 10:14:01.384  4231  4258 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-31 10:14:01.384  4231  4258 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-31 10:14:01.384  4231  4258 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-31 10:14:01.428  4231  4260 V GoogleAuthProtoRequest: [466] a.<init>: mAccountName set to: thalitester@gmail.com
,03-31 10:14:01.468  1265  2559 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
03-31 10:14:01.468  1265  2559 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 10:14:01.468  1265  2559 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 10:14:01.468  1265  2559 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 10:14:01.475  1265  2559 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 10:14:01.495  4231  4260 W ExperimentUpdateService: [466] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
03-31 10:14:01.496  4231  4260 W ExperimentUpdateService: [466] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-31 10:14:01.496  4231  4260 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-31 10:14:01.496  4231  4260 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-31 10:14:01.496  4231  4260 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-31 10:14:01.496  4231  4260 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-31 10:14:01.496  4231  4260 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-31 10:14:01.496  4231  4260 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-31 10:14:01.496  4231  4260 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-31 10:14:01.496  4231  4260 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-31 10:14:01.496  4231  4260 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-31 10:14:01.496  4231  4260 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-31 10:14:01.726  1265  1265 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 10:14:01.791  1265  1720 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
03-31 10:14:01.792  1265  1720 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 10:14:01.792  1265  1720 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-31 10:14:01.792  1265  1720 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 10:14:01.805  1265  1720 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 10:14:01.850  4161  4161 W Finsky  : [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,03-31 10:14:01.857  4161  4161 D Finsky  : [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,03-31 10:14:01.872  4161  4161 D Finsky  : [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,03-31 10:14:01.876  4161  4161 D Finsky  : [1] DailyHygiene.reschedule: Giving up. (failures=6)
,03-31 10:14:01.901  1832  1894 D DeviceConnectionService: client connected with version: 7571000
,03-31 10:14:01.905   822   840 I ActivityManager: Killing 3074:com.google.android.apps.plus/u0a74 (adj 15): empty #17
,03-31 10:14:01.930  3253  3312 I io.jxcore.node.ConnectionHelper: start: Port number: 35132, start advertisements: true
,03-31 10:14:01.930  3253  3312 I io.jxcore.node.ConnectionHelper: restoreDefaultBleDiscoverySettings: Powering the BLE discovery back up
,03-31 10:14:01.930  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 0 -> 2
03-31 10:14:01.930  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-31 10:14:01.930  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-31 10:14:01.930  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-31 10:14:01.930  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-31 10:14:01.930  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-31 10:14:01.930  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-31 10:14:01.930  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 1, timeout: 0, is connectable: false
03-31 10:14:01.931  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
,03-31 10:14:01.931  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 1 -> 3
03-31 10:14:01.931  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-31 10:14:01.931  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-31 10:14:01.931  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-31 10:14:01.931  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-31 10:14:01.931  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-31 10:14:01.931  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-31 10:14:01.931  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-31 10:14:01.931  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-31 10:14:01.931  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 0 -> 2
03-31 10:14:01.931  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-31 10:14:01.931  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-31 10:14:01.931  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-31 10:14:01.931  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-31 10:14:01.931  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-31 10:14:01.931  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-31 10:14:01.931  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-31 10:14:01.931  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-31 10:14:01.931  3253  3312 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 10:14:01.931  3253  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-31 10:14:01.931  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-31 10:14:01.933  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
03-31 10:14:01.933  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-31 10:14:01.933  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 10:14:01.933  3253  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 10:14:01.936  2153  2171 D BtGatt.GattService: registerClient() - UUID=8db34f78-c016-40d7-8ebb-f175e36dab62
03-31 10:14:01.936  2153  2216 D BtGatt.GattService: onClientRegistered() - UUID=8db34f78-c016-40d7-8ebb-f175e36dab62, clientIf=5
03-31 10:14:01.937  3253  3268 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-31 10:14:01.937  2153  2170 D BtGatt.GattService: start scan with filters
,03-31 10:14:01.938  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-31 10:14:01.938  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-31 10:14:01.938  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-31 10:14:01.938  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-31 10:14:01.938  2153  2227 D BtGatt.ScanManager: handling starting scan
03-31 10:14:01.938  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
,03-31 10:14:01.938  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-31 10:14:01.938  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-31 10:14:01.938  3253  3253 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 10:14:01.938  3253  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-31 10:14:01.938  3253  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 10:14:01.938  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 10:14:01.938  3253  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-31 10:14:01.940  2153  2216 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-31 10:14:01.940  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 10:14:01.940  2153  2337 D BtGatt.GattService: registerClient() - UUID=c64f6729-b131-43c3-b58d-ee19c7626a4b
03-31 10:14:01.941  2153  2216 D BtGatt.GattService: onClientRegistered() - UUID=c64f6729-b131-43c3-b58d-ee19c7626a4b, clientIf=6
03-31 10:14:01.941  3253  3854 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-31 10:14:01.941  2153  2216 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-31 10:14:01.941  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 10:14:01.941  2153  2226 D BtGatt.AdvertiseManager: message : 0
03-31 10:14:01.942  2153  2227 D BtGatt.ScanManager: Starting BLE batch scan
03-31 10:14:01.942  2153  2227 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-31 10:14:01.943  2153  2226 D BtGatt.AdvertiseManager: starting multi advertising
03-31 10:14:01.944  2153  2216 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-31 10:14:01.944  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 10:14:01.945  2153  2216 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-31 10:14:01.945  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 10:14:01.949  2153  2216 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-31 10:14:01.951  2153  2216 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-31 10:14:01.952  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-31 10:14:01.952  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-31 10:14:02.023   822  1378 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 10:14:02.027  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 10:14:02.027  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-31 10:14:02.027  3253  3312 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-31 10:14:02.027  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-31 10:14:02.029  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-31 10:14:02.029  3253  3312 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-31 10:14:02.029  3253  3312 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,03-31 10:14:02.029  3253  3312 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,03-31 10:14:02.029  3253  3312 I io.jxcore.node.ConnectionHelper: start: OK
03-31 10:14:02.029  3253  3253 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-31 10:14:02.030  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-31 10:14:02.030  3253  3253 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-31 10:14:02.030  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-31 10:14:02.030  3253  3253 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-31 10:14:02.031  3253  3253 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-31 10:14:02.031  3253  3253 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-31 10:14:02.031  3253  3253 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-31 10:14:02.031  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 10:14:02.031  3253  3312 I jxcore-log: 
,03-31 10:14:02.031   822  1104 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 10:14:02.031  3253  3253 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-31 10:14:02.031  3253  3253 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 10:14:02.032  3253  3253 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,03-31 10:14:02.032  3253  3253 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-31 10:14:02.033  3253  3312 I jxcore-log: ok 175 Can call startUpdateAdvertisingAndListening without error
03-31 10:14:02.033  3253  3312 I jxcore-log: 
,03-31 10:14:02.036  3253  4263 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-31 10:14:02.063  3253  4263 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-31 10:14:02.065  3253  3312 I io.jxcore.node.ConnectionHelper: start: Port number: 35132, start advertisements: false
,03-31 10:14:02.065  3253  3312 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-31 10:14:02.065  3253  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should affect listening to advertisements only
,03-31 10:14:02.065  3253  3312 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-31 10:14:02.065  3253  3312 I io.jxcore.node.ConnectionHelper: start: OK
,03-31 10:14:02.066  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 10:14:02.066  3253  3312 I jxcore-log: 
03-31 10:14:02.067  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-31 10:14:02.067  3253  3312 I jxcore-log: 
03-31 10:14:02.068  3253  3312 I jxcore-log: ok 176 Can call startListeningForAdvertisements without error
03-31 10:14:02.068  3253  3312 I jxcore-log: 
,03-31 10:14:02.764  2153  2218 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-31 10:14:03.991  2153  2228 W bt-btif : new conn_srvc id:26, app_id:255
03-31 10:14:03.993  3253  4263 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection accepted
,03-31 10:14:03.994  3253  4263 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection initialized (thread ID: 356)
,03-31 10:14:03.995  3253  4263 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-31 10:14:03.997  3253  4265 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 356)
03-31 10:14:03.998   822  1454 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 10:14:04.001  3253  4263 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-31 10:14:04.006  3253  4263 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-31 10:14:04.588  3253  4265 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesRead: Read 15 bytes successfully (thread ID: 356)
,03-31 10:14:04.591  3253  4265 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Got valid identity from [<no peer name> E0:DB:10:14:E2:C0]
03-31 10:14:04.592  3253  4265 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesWritten: 15 bytes successfully written (thread ID: 356)
03-31 10:14:04.592  3253  4265 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: removeThreadFromList: Removing thread with ID 356
03-31 10:14:04.592  3253  4265 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Handshake thread disposed (thread ID: 356)
03-31 10:14:04.593  3253  4265 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onIncomingConnectionConnected: [<no peer name> E0:DB:10:14:E2:C0]
03-31 10:14:04.594  3253  4265 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 356)
03-31 10:14:04.595  3253  3253 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> E0:DB:10:14:E2:C0]
03-31 10:14:04.595  3253  3253 I io.jxcore.node.ConnectionHelper: onConnected: Incoming connection to peer [<no peer name> E0:DB:10:14:E2:C0]
03-31 10:14:04.595  3253  3253 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> E0:DB:10:14:E2:C0], added - the peer count is 1
,03-31 10:14:04.597  3253  3253 I io.jxcore.node.ConnectionHelper: lowerBleDiscoveryPowerAndStartResetTimer: Lowering the power settings
,03-31 10:14:04.597  3253  3253 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 2 -> 0
03-31 10:14:04.598  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-31 10:14:04.598  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-31 10:14:04.598  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-31 10:14:04.598  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-31 10:14:04.598  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-31 10:14:04.598  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-31 10:14:04.604  2153  2226 D BtGatt.AdvertiseManager: message : 1
,03-31 10:14:04.605  2153  2226 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-31 10:14:04.611  2153  2216 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,03-31 10:14:04.611  2153  2216 D BtGatt.GattService: Client app is not null!
03-31 10:14:04.613  2153  2170 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-31 10:14:04.616  3253  3253 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-31 10:14:04.616  3253  3253 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-31 10:14:04.616  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 3, timeout: 0, is connectable: false
03-31 10:14:04.616  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-31 10:14:04.616  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,03-31 10:14:04.617  3253  3253 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-31 10:14:04.617  3253  3253 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 10:14:04.617  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 10:14:04.618  3253  3253 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-31 10:14:04.628  2153  2171 D BtGatt.GattService: registerClient() - UUID=f0ac894a-ccee-4728-b4b7-e002e5896251,
03-31 10:14:04.628  2153  2216 D BtGatt.GattService: onClientRegistered() - UUID=f0ac894a-ccee-4728-b4b7-e002e5896251, clientIf=6
03-31 10:14:04.629  3253  3854 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-31 10:14:04.631  2153  2226 D BtGatt.AdvertiseManager: message : 0
,03-31 10:14:04.637  2153  2226 D BtGatt.AdvertiseManager: starting multi advertising
,03-31 10:14:04.641  2153  2216 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-31 10:14:04.645  2153  2216 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-31 10:14:04.646  3253  3253 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-31 10:14:04.649  2153  2171 D BtGatt.GattService: stopScan() - queue size =1
,03-31 10:14:04.652  2153  2171 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-31 10:14:04.653  2153  2216 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-31 10:14:04.653  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 10:14:04.653  2153  2227 D BtGatt.ScanManager: stopping BLe Batch
,03-31 10:14:04.653  3253  3253 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 10:14:04.654  3253  3253 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 10:14:04.654  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-31 10:14:04.654  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-31 10:14:04.654  3253  3253 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 10:14:04.654  3253  3253 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-31 10:14:04.657  2153  2216 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-31 10:14:04.657  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 10:14:04.658  2153  2227 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-31 10:14:04.662  2153  2216 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-31 10:14:04.662  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 10:14:04.662  2153  2216 D BtGatt.GattService: current time is 249579810007
03-31 10:14:04.662  2153  2216 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -64, 6, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0, -45, 45, -19, -88, -8, 71, 1, -128, -79, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-31 10:14:04.663  2153  2216 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-31 10:14:04.663  2153  2216 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-31 10:14:04.665  2153  2170 D BtGatt.GattService: registerClient() - UUID=ab455319-ca9d-45ce-985d-a4618d5106d7
03-31 10:14:04.666  2153  2216 D BtGatt.GattService: onClientRegistered() - UUID=ab455319-ca9d-45ce-985d-a4618d5106d7, clientIf=5
03-31 10:14:04.666  3253  3268 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-31 10:14:04.667  2153  2337 D BtGatt.GattService: start scan with filters
,03-31 10:14:04.668  3253  3253 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-31 10:14:04.668  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 10:14:04.668  3253  3253 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 3 -> 1
03-31 10:14:04.668  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-31 10:14:04.668  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-31 10:14:04.668  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-31 10:14:04.668  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-31 10:14:04.668  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-31 10:14:04.668  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-31 10:14:04.671  2153  2226 D BtGatt.AdvertiseManager: message : 1
03-31 10:14:04.672  2153  2227 D BtGatt.ScanManager: handling starting scan
03-31 10:14:04.673  2153  2226 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-31 10:14:04.674  2153  2216 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,03-31 10:14:04.674  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 10:14:04.676  2153  2216 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-31 10:14:04.676  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 10:14:04.676  2153  2227 D BtGatt.ScanManager: Starting BLE batch scan
03-31 10:14:04.676  2153  2227 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-31 10:14:04.678  2153  2216 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-31 10:14:04.678  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 10:14:04.679  2153  2216 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-31 10:14:04.679  2153  2216 D BtGatt.GattService: Client app is not null!
,03-31 10:14:04.680  2153  2337 D BtGatt.GattService: unregisterClient() - clientIf=6
03-31 10:14:04.681  3253  3253 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-31 10:14:04.681  2153  2216 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-31 10:14:04.681  3253  3253 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-31 10:14:04.681  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-31 10:14:04.681  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-31 10:14:04.681  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 10:14:04.681  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-31 10:14:04.681  3253  3253 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-31 10:14:04.682  3253  3253 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 10:14:04.682  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 10:14:04.682  3253  3253 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-31 10:14:04.687  2153  2171 D BtGatt.GattService: registerClient() - UUID=f664776e-0941-49cd-a23d-38b332ebf5d6
,03-31 10:14:04.687  2153  2216 D BtGatt.GattService: onClientRegistered() - UUID=f664776e-0941-49cd-a23d-38b332ebf5d6, clientIf=6
03-31 10:14:04.687  3253  3269 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-31 10:14:04.688  2153  2226 D BtGatt.AdvertiseManager: message : 0
,03-31 10:14:04.691  2153  2226 D BtGatt.AdvertiseManager: starting multi advertising
,03-31 10:14:04.693  2153  2216 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-31 10:14:04.695  2153  2216 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-31 10:14:04.696  3253  3253 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-31 10:14:04.697  2153  2171 D BtGatt.GattService: stopScan() - queue size =1
03-31 10:14:04.698  2153  2170 D BtGatt.GattService: unregisterClient() - clientIf=5
03-31 10:14:04.699  3253  3253 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 10:14:04.699  3253  3253 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 10:14:04.699  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-31 10:14:04.699  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-31 10:14:04.699  3253  3253 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 10:14:04.699  3253  3253 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 10:14:04.699  2153  2216 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-31 10:14:04.699  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 10:14:04.700  2153  2227 D BtGatt.ScanManager: stopping BLe Batch
,03-31 10:14:04.702  2153  2216 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-31 10:14:04.702  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 10:14:04.703  2153  2227 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-31 10:14:04.703  2153  2337 D BtGatt.GattService: registerClient() - UUID=9058881c-2fd1-40dc-8e31-894c6e8afac6
03-31 10:14:04.703  2153  2216 D BtGatt.GattService: onClientRegistered() - UUID=9058881c-2fd1-40dc-8e31-894c6e8afac6, clientIf=5
03-31 10:14:04.704  3253  3854 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-31 10:14:04.704  2153  2171 D BtGatt.GattService: start scan with filters
,03-31 10:14:04.704  2153  2216 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-31 10:14:04.704  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 10:14:04.704  3253  3253 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-31 10:14:04.704  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 10:14:04.705  3253  3253 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 2 -> 0
03-31 10:14:04.705  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-31 10:14:04.705  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-31 10:14:04.705  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-31 10:14:04.705  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-31 10:14:04.705  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-31 10:14:04.705  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-31 10:14:04.708  2153  2227 D BtGatt.ScanManager: handling starting scan
03-31 10:14:04.708  2153  2226 D BtGatt.AdvertiseManager: message : 1
03-31 10:14:04.709  2153  2226 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-31 10:14:04.712  2153  2216 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-31 10:14:04.712  2153  2216 D BtGatt.GattService: Client app is not null!
03-31 10:14:04.713  2153  2337 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-31 10:14:04.713  3253  3253 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-31 10:14:04.713  3253  3253 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-31 10:14:04.713  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-31 10:14:04.713  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-31 10:14:04.713  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-31 10:14:04.714  3253  3253 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61,
03-31 10:14:04.714  2153  2216 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-31 10:14:04.714  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 10:14:04.714  3253  3253 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 10:14:04.714  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 10:14:04.714  3253  3253 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-31 10:14:04.716  2153  2216 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-31 10:14:04.716  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 10:14:04.716  2153  2227 D BtGatt.ScanManager: Starting BLE batch scan
03-31 10:14:04.716  2153  2227 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-31 10:14:04.718  2153  2216 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-31 10:14:04.718  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 10:14:04.719  2153  2170 D BtGatt.GattService: registerClient() - UUID=a594ced6-beef-4b5a-87aa-114973efccf5
03-31 10:14:04.719  2153  2216 D BtGatt.GattService: onClientRegistered() - UUID=a594ced6-beef-4b5a-87aa-114973efccf5, clientIf=6
,03-31 10:14:04.720  2153  2216 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-31 10:14:04.719  3253  3268 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-31 10:14:04.720  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 10:14:04.721  2153  2226 D BtGatt.AdvertiseManager: message : 0
03-31 10:14:04.723  2153  2226 D BtGatt.AdvertiseManager: starting multi advertising
03-31 10:14:04.725  2153  2216 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-31 10:14:04.728  2153  2216 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
03-31 10:14:04.728  3253  3253 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-31 10:14:04.730  2153  2170 D BtGatt.GattService: stopScan() - queue size =1,
03-31 10:14:04.730  2153  2171 D BtGatt.GattService: unregisterClient() - clientIf=5
03-31 10:14:04.731  3253  3253 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 10:14:04.731  3253  3253 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 10:14:04.731  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-31 10:14:04.731  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-31 10:14:04.731  3253  3253 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 10:14:04.731  3253  3253 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-31 10:14:04.731  2153  2216 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-31 10:14:04.731  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 10:14:04.731  2153  2227 D BtGatt.ScanManager: stopping BLe Batch
03-31 10:14:04.734  2153  2216 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-31 10:14:04.734  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 10:14:04.734  2153  2227 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-31 10:14:04.735  2153  2337 D BtGatt.GattService: registerClient() - UUID=74c7995e-3ccb-42a7-8afe-fa1d2c866513
03-31 10:14:04.735  2153  2216 D BtGatt.GattService: onClientRegistered() - UUID=74c7995e-3ccb-42a7-8afe-fa1d2c866513, clientIf=5
03-31 10:14:04.735  3253  3269 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-31 10:14:04.735  2153  2216 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-31 10:14:04.735  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
03-31 10:14:04.736  2153  2170 D BtGatt.GattService: start scan with filters
03-31 10:14:04.736  3253  3253 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-31 10:14:04.736  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 10:14:04.737  3253  3253 I io.jxcore.node.ConnectionHelper: onConnected: Incoming socket thread, for peer [<no peer name> E0:DB:10:14:E2:C0], created successfully
03-31 10:14:04.737  3253  3253 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 1
03-31 10:14:04.737  3253  3253 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> E0:DB:10:14:E2:C0], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 
03-31 10:14:04.737  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-31 10:14:04.737  3253  3253 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-31 10:14:04.737  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-31 10:14:04.737  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-31 10:14:04.737  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-31 10:14:04.737  3253  4266 D io.jxcore.node.IncomingSocketThread: Entering thread (ID: 357)
,03-31 10:14:04.741  3253  4266 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 35132
,03-31 10:14:04.742  2153  2227 D BtGatt.ScanManager: handling starting scan
03-31 10:14:04.742  3253  4266 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
03-31 10:14:04.742  3253  4266 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-31 10:14:04.743  3253  4266 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-31 10:14:04.743  3253  4266 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 357)
03-31 10:14:04.743  3253  4266 D io.jxcore.node.IncomingSocketThread: Exiting thread (ID: 357)
03-31 10:14:04.743  2153  2216 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-31 10:14:04.743  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 10:14:04.744  2153  2216 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-31 10:14:04.745  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 10:14:04.745  2153  2227 D BtGatt.ScanManager: Starting BLE batch scan
03-31 10:14:04.745  2153  2227 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-31 10:14:04.745  3253  4268 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 358, name: Sender)
,03-31 10:14:04.747  2153  2216 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,03-31 10:14:04.747  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 10:14:04.748  2153  2216 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-31 10:14:04.748  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 10:14:04.749  3253  4269 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 359, name: Receiver)
,03-31 10:14:04.751  3253  3312 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID E0:DB:10:14:E2:C0
,03-31 10:14:04.751  3253  3312 I io.jxcore.node.ConnectionHelper: connect: We already have an incoming connection to peer with ID E0:DB:10:14:E2:C0, but will connect anyway...
03-31 10:14:04.751  3253  3312 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> E0:DB:10:14:E2:C0]
,03-31 10:14:04.753  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to Note4-1 in address E0:DB:10:14:E2:C0
,03-31 10:14:04.754  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
,03-31 10:14:04.754  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,03-31 10:14:04.754  3253  3312 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: Note4-1 E0:DB:10:14:E2:C0
03-31 10:14:04.754  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to Note4-1 in address E0:DB:10:14:E2:C0
03-31 10:14:04.754  3253  3312 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: E0:DB:10:14:E2:C0)
03-31 10:14:04.755  3253  4270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address E0:DB:10:14:E2:C0 (thread ID: 360)
03-31 10:14:04.755  3253  4270 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-31 10:14:04.757  2153  2337 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,03-31 10:14:05.002  2153  2228 W bt-sdp  : process_service_search_attr_rsp
,03-31 10:14:05.328   822  1410 I ActivityManager: Killing 3484:com.google.android.keep/u0a79 (adj 15): empty #17
,03-31 10:14:05.430  2153  2228 W bt-btif : new conn_srvc id:26, app_id:1
,03-31 10:14:05.430  3253  4270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onSocketConnected: [<no peer name> E0:DB:10:14:E2:C0] (thread ID: 360)
03-31 10:14:05.431  3253  4270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 360)
,03-31 10:14:05.432  3253  4270 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesWritten: 15 bytes successfully written (thread ID: 361)
03-31 10:14:05.433  3253  4270 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Outgoing connection initialized (*handshake* thread ID: 361)
03-31 10:14:05.433  3253  4270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 360)
03-31 10:14:05.436  3253  4271 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 361)
,03-31 10:14:05.577   822  1201 I ActivityManager: Killing 3433:com.google.android.apps.books/u0a34 (adj 15): empty #17
,03-31 10:14:06.042  3253  4271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesRead: Read 15 bytes successfully (thread ID: 361)
,03-31 10:14:06.045  3253  4271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Handshake succeeded with [<no peer name> E0:DB:10:14:E2:C0]
03-31 10:14:06.045  3253  4271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onHandshakeSucceeded: [<no peer name> E0:DB:10:14:E2:C0] (thread ID: 360)
03-31 10:14:06.046  3253  4271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: handleSuccessfulClientThread: [<no peer name> E0:DB:10:14:E2:C0] (thread ID: 360)
,03-31 10:14:06.046  3253  4271 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 361)
,03-31 10:14:06.046  3253  3253 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> E0:DB:10:14:E2:C0]
03-31 10:14:06.046  3253  3253 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing connection to peer [<no peer name> E0:DB:10:14:E2:C0]
03-31 10:14:06.046  3253  3253 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> E0:DB:10:14:E2:C0] updated - the peer count is 1
03-31 10:14:06.048  3253  3253 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing socket thread, for peer [<no peer name> E0:DB:10:14:E2:C0], created successfully
03-31 10:14:06.048  3253  3253 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 2
03-31 10:14:06.049  3253  4272 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 362)
03-31 10:14:06.049  3253  4272 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 59998
03-31 10:14:06.049  3253  4272 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,03-31 10:14:06.049  3253  4272 I io.jxcore.node.ConnectionHelper: onListeningForIncomingConnections: Outgoing connection is using port 59998 (peer ID: E0:DB:10:14:E2:C0)
03-31 10:14:06.049  3253  4272 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "E0:DB:10:14:E2:C0" removed
,03-31 10:14:06.052  3253  3312 I jxcore-log: INFO testThaliMobileNative: 
03-31 10:14:06.052  3253  3312 I jxcore-log: 
03-31 10:14:06.053  3253  3312 I jxcore-log: INFO testThaliMobileNative: Forward connection
03-31 10:14:06.053  3253  3312 I jxcore-log: 
,03-31 10:14:06.058  3253  3312 I jxcore-log: INFO testThaliMobileNative: forwardSend
03-31 10:14:06.058  3253  3312 I jxcore-log: 
,03-31 10:14:06.060  3253  4272 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 59998
,03-31 10:14:06.060  3253  4272 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
03-31 10:14:06.060  3253  4272 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
,03-31 10:14:06.061  3253  4272 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-31 10:14:06.061  3253  4273 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 363, name: Sender)
,03-31 10:14:06.062  3253  4272 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 362)
03-31 10:14:06.063  3253  4272 D io.jxcore.node.OutgoingSocketThread: Exiting thread (ID: 362)
,03-31 10:14:06.064  3253  4274 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 364, name: Receiver)
,03-31 10:14:06.218  3253  3312 I jxcore-log: INFO testThaliMobileNative: forwardData
03-31 10:14:06.218  3253  3312 I jxcore-log: 
,03-31 10:14:06.259  3253  3312 I jxcore-log: INFO testThaliMobileNative: forwardData
03-31 10:14:06.259  3253  3312 I jxcore-log: 
,03-31 10:14:06.332  3253  3312 I jxcore-log: INFO testThaliMobileNative: forwardData
03-31 10:14:06.332  3253  3312 I jxcore-log: 
,03-31 10:14:06.405  3253  3312 I jxcore-log: INFO testThaliMobileNative: forwardData
03-31 10:14:06.405  3253  3312 I jxcore-log: 
,03-31 10:14:06.476  3253  3312 I jxcore-log: INFO testThaliMobileNative: forwardData
03-31 10:14:06.476  3253  3312 I jxcore-log: 
,03-31 10:14:06.479  3253  3312 I jxcore-log: ok 177 received should match sent forward
03-31 10:14:06.479  3253  3312 I jxcore-log: 
,03-31 10:14:06.494  3253  3312 I jxcore-log: # teardown
03-31 10:14:06.494  3253  3312 I jxcore-log: 
,03-31 10:14:07.437  2153  2228 W bt-btif : info:x10
03-31 10:14:07.437  2153  2216 D         : remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
03-31 10:14:07.438  2153  2216 E BluetoothRemoteDevices: aclStateChangeCallback: Device is NULL
,03-31 10:14:07.683  2153  2228 E bt-btm  : tBTM_SEC_DEV:0xa2ffaeb4 rs_disc_pending=1
03-31 10:14:07.683  2153  2228 W bt-btif : bta_dm_check_av:0
,03-31 10:14:07.683  2153  2216 W bt-btif : btif_dm_cback : unhandled event (14)
,03-31 10:14:07.759  2153  2216 D btif_config: btif_get_device_type: Device [f8:95:c7:87:3c:51] type 1
,03-31 10:14:07.765  2153  2216 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1,
,03-31 10:14:07.765  2153  2216 E bt-btif : check_cod: remote_cod = 0x5a020c
03-31 10:14:07.769  2153  2217 I BluetoothBondStateMachine: Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
,03-31 10:14:07.773  2153  2217 I BluetoothBondStateMachine: Entering PendingCommandState State
,03-31 10:14:07.890  2153  2216 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,03-31 10:14:07.891  2153  2217 D BluetoothAdapterProperties: Failed to remove device: F8:95:C7:87:3C:51
,03-31 10:14:07.895  2153  2217 I BluetoothBondStateMachine: Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,03-31 10:14:07.911  2153  2217 I BluetoothBondStateMachine: StableState(): Entering Off State
,03-31 10:14:07.938  2153  2228 W bt-btif : new conn_srvc id:26, app_id:255
,03-31 10:14:07.938  2153  2228 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:255
03-31 10:14:07.938  2153  2228 W bt-btif : bta_dm_pm_ssr:2, lat:1200
03-31 10:14:07.939  3253  4263 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection accepted
03-31 10:14:07.939  3253  4263 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection initialized (thread ID: 365)
,03-31 10:14:07.940  3253  4263 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-31 10:14:07.940  3253  4275 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 365)
03-31 10:14:07.941   822  1449 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-31 10:14:07.943  3253  4263 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-31 10:14:07.947  3253  4263 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-31 10:14:07.951  3253  4275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesRead: Read 15 bytes successfully (thread ID: 365)
03-31 10:14:07.952  3253  4275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Got valid identity from [<no peer name> F8:95:C7:87:3C:51]
03-31 10:14:07.952  3253  4275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesWritten: 15 bytes successfully written (thread ID: 365)
03-31 10:14:07.952  3253  4275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: removeThreadFromList: Removing thread with ID 365
03-31 10:14:07.952  3253  4275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Handshake thread disposed (thread ID: 365)
03-31 10:14:07.952  3253  4275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onIncomingConnectionConnected: [<no peer name> F8:95:C7:87:3C:51]
03-31 10:14:07.953  3253  3253 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> F8:95:C7:87:3C:51]
03-31 10:14:07.953  3253  3253 I io.jxcore.node.ConnectionHelper: onConnected: Incoming connection to peer [<no peer name> F8:95:C7:87:3C:51]
03-31 10:14:07.953  3253  3253 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 2
03-31 10:14:07.953  3253  3253 I io.jxcore.node.ConnectionHelper: onConnected: Incoming socket thread, for peer [<no peer name> F8:95:C7:87:3C:51], created successfully
03-31 10:14:07.953  3253  3253 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 3
03-31 10:14:07.953  3253  3253 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
03-31 10:14:07.954  3253  4275 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 365)
,03-31 10:14:07.957  3253  4276 D io.jxcore.node.IncomingSocketThread: Entering thread (ID: 366)
,03-31 10:14:07.967  3253  4276 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 35132
03-31 10:14:07.968  3253  4276 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
03-31 10:14:07.968  3253  4276 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
,03-31 10:14:07.968  3253  4276 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-31 10:14:07.969  3253  4276 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 366)
03-31 10:14:07.969  3253  4276 D io.jxcore.node.IncomingSocketThread: Exiting thread (ID: 366)
,03-31 10:14:07.971  3253  4278 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 367, name: Sender)
,03-31 10:14:07.973  3253  4279 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 368, name: Receiver)
,03-31 10:14:08.622  3253  4268 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 358, thread name: Sender)
03-31 10:14:08.623  3253  4268 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Input stream got -1 on read
03-31 10:14:08.623  3253  4268 W io.jxcore.node.ConnectionHelper: onDisconnected: Incoming connection, peer [<no peer name> E0:DB:10:14:E2:C0] disconnected: Input stream got -1 on read
,03-31 10:14:08.623  3253  4268 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 357
03-31 10:14:08.623  3253  4278 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 367, thread name: Sender)
03-31 10:14:08.623  3253  4278 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Input stream got -1 on read
,03-31 10:14:08.623  3253  4268 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 357)
03-31 10:14:08.623  3253  4278 W io.jxcore.node.ConnectionHelper: onDisconnected: Incoming connection, peer [<no peer name> F8:95:C7:87:3C:51] disconnected: Input stream got -1 on read
03-31 10:14:08.624  3253  4268 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
03-31 10:14:08.624  3253  4268 D io.jxcore.node.IncomingSocketThread: close: Stopping receiving thread...
03-31 10:14:08.624  3253  4268 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 359
03-31 10:14:08.624  3253  4269 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 359, thread name: Receiver): bt socket closed, read return: -1
03-31 10:14:08.624  3253  4268 D io.jxcore.node.IncomingSocketThread: close: Stopping sending thread...
03-31 10:14:08.624  3253  4268 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 358
03-31 10:14:08.624  3253  4269 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 359, name: Receiver)
03-31 10:14:08.624  3253  4268 D io.jxcore.node.IncomingSocketThread: closeLocalSocketAndStreams: Closing... (thread ID: 357)
03-31 10:14:08.626  3253  4268 I io.jxcore.node.IncomingSocketThread: close: Complete (thread ID: 357)
03-31 10:14:08.626  3253  4268 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
03-31 10:14:08.626  3253  4278 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 366
03-31 10:14:08.626  3253  4278 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 366)
03-31 10:14:08.627  3253  4278 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
03-31 10:14:08.627  3253  4278 D io.jxcore.node.IncomingSocketThread: close: Stopping receiving thread...
03-31 10:14:08.627  3253  4278 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 368
,03-31 10:14:08.627  3253  4278 D io.jxcore.node.IncomingSocketThread: close: Stopping sending thread...
03-31 10:14:08.627  3253  4279 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 368, thread name: Receiver): bt socket closed, read return: -1
03-31 10:14:08.627  3253  4279 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 368, name: Receiver)
03-31 10:14:08.627  3253  4278 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 367
03-31 10:14:08.628  3253  4278 D io.jxcore.node.IncomingSocketThread: closeLocalSocketAndStreams: Closing... (thread ID: 366)
03-31 10:14:08.629  3253  4278 I io.jxcore.node.IncomingSocketThread: close: Complete (thread ID: 366)
03-31 10:14:08.629  3253  4278 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
03-31 10:14:08.629  3253  4278 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 367, name: Sender)
,03-31 10:14:08.631  3253  4268 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 358, name: Sender)
03-31 10:14:08.632  3253  3312 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-31 10:14:08.632  3253  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
03-31 10:14:08.632  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,03-31 10:14:08.632  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...,
03-31 10:14:08.636  2153  2337 D BtGatt.GattService: stopScan() - queue size =1
03-31 10:14:08.639  2153  2171 D BtGatt.GattService: unregisterClient() - clientIf=5
03-31 10:14:08.639  2153  2216 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-31 10:14:08.639  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 10:14:08.639  2153  2227 D BtGatt.ScanManager: stopping BLe Batch
03-31 10:14:08.640  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 10:14:08.640  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 10:14:08.640  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-31 10:14:08.640  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-31 10:14:08.641  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-31 10:14:08.641  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-31 10:14:08.641  3253  3253 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-31 10:14:08.641  3253  3253 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
03-31 10:14:08.641  3253  3253 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 10:14:08.643  2153  2216 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,03-31 10:14:08.644  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 10:14:08.644  2153  2227 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-31 10:14:08.645  3253  3312 I jxcore-log: INFO thaliMobileNativeWrapper: incomingConnectionToPortNumberFailed: %s
03-31 10:14:08.645  3253  3312 I jxcore-log: 
03-31 10:14:08.646  3253  3312 I jxcore-log: INFO thaliMobileNativeWrapper: got incomingConnectionToPortNumberFailed while not in start
03-31 10:14:08.646  3253  3312 I jxcore-log: 
,03-31 10:14:08.647  2153  2216 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-31 10:14:08.647  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 10:14:08.647  2153  2216 D BtGatt.GattService: current time is 253565088287
03-31 10:14:08.647  2153  2216 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -78, 58, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0, -45, 45, -19, -88, -8, 71, 1, -128, -81, 41, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-31 10:14:08.648  2153  2216 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-31 10:14:08.648  3253  3312 I jxcore-log: ok 178 Should be able to call stopListeningForAdvertisments in teardown
03-31 10:14:08.648  3253  3312 I jxcore-log: 
03-31 10:14:08.648  2153  2216 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-31 10:14:08.649  3253  3312 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-31 10:14:08.649  3253  3312 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> E0:DB:10:14:E2:C0]
03-31 10:14:08.649  3253  3312 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 362)
03-31 10:14:08.649  3253  3312 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 362)
03-31 10:14:08.649  3253  3312 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
03-31 10:14:08.649  3253  3312 D io.jxcore.node.OutgoingSocketThread: close: Stopping receiving thread...
03-31 10:14:08.649  3253  3312 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 364
03-31 10:14:08.649  3253  3312 D io.jxcore.node.OutgoingSocketThread: close: Stopping sending thread...
03-31 10:14:08.649  3253  3312 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 363
03-31 10:14:08.649  3253  3312 D io.jxcore.node.OutgoingSocketThread: closeLocalSocketAndStreams: Closing... (thread ID: 362)
,03-31 10:14:08.649  3253  4274 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 364, thread name: Receiver): bt socket closed, read return: -1
03-31 10:14:08.649  3253  4274 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 364, name: Receiver)
03-31 10:14:08.649  3253  4273 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 363, thread name: Sender): Socket closed
03-31 10:14:08.649  3253  4273 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 363, name: Sender)
,03-31 10:14:08.652  3253  3312 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 362)
03-31 10:14:08.652  3253  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
03-31 10:14:08.652  3253  3312 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-31 10:14:08.652  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-31 10:14:08.652  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-31 10:14:08.652  3253  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-31 10:14:08.652  3253  4263 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-31 10:14:08.652  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-31 10:14:08.652  3253  4263 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-31 10:14:08.653  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-31 10:14:08.653  3253  4263 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-31 10:14:08.653  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-31 10:14:08.653  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-31 10:14:08.653  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-31 10:14:08.653  3253  3253 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-31 10:14:08.653  3253  3253 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-31 10:14:08.654  3253  3312 D BluetoothLeScanner: could not find callback wrapper
03-31 10:14:08.654  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 10:14:08.654  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,03-31 10:14:08.656  2153  2226 D BtGatt.AdvertiseManager: message : 1
,03-31 10:14:08.657  2153  2226 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-31 10:14:08.659  2153  2216 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-31 10:14:08.659  2153  2216 D BtGatt.GattService: Client app is not null!
03-31 10:14:08.660  2153  2171 D BtGatt.GattService: unregisterClient() - clientIf=6
03-31 10:14:08.661  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-31 10:14:08.661  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-31 10:14:08.661  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,03-31 10:14:08.661  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-31 10:14:08.661  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,03-31 10:14:08.661  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 10:14:08.661  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,03-31 10:14:08.661  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-31 10:14:08.662  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,03-31 10:14:08.662  3253  3312 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear,
03-31 10:14:08.662  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,03-31 10:14:08.662  3253  3253 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 10:14:08.662  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 10:14:08.662  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener,
03-31 10:14:08.664  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-31 10:14:08.664  3253  3312 I jxcore-log: ,
03-31 10:14:08.669  3253  3253 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-31 10:14:08.670   822  1412 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 10:14:08.675  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-31 10:14:08.676  2153  2228 W bt-btif : bta_jv_rfc_port_to_cb(port_handle:0xe):jv handle:0x0 not FOUND
,03-31 10:14:08.676  2153  2228 E bt-btif : bta_jv_port_mgmt_sr_cback, p_cb:0x0, p_cb->p_cback0x0
03-31 10:14:08.676  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
,03-31 10:14:08.676  3253  3253 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-31 10:14:08.681  3253  3253 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-31 10:14:08.681  3253  3253 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 10:14:08.681  3253  3253 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-31 10:14:08.681  3253  3253 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 10:14:08.681  3253  3253 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 10:14:08.682  3253  3312 I jxcore-log: ok 179 Should be able to call stopAdvertisingAndListening in teardown
03-31 10:14:08.682  3253  3312 I jxcore-log: 
,03-31 10:14:08.687  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false},
03-31 10:14:08.687  3253  3312 I jxcore-log: 
03-31 10:14:08.687  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 10:14:08.687  3253  3312 I jxcore-log: 
,03-31 10:14:08.689  3253  3312 I jxcore-log: # setup
03-31 10:14:08.689  3253  3312 I jxcore-log: 
,03-31 10:14:08.741  2153  2228 W bt-btif : bta_jv_rfc_port_to_cb(port_handle:0x11):jv handle:0x0 not FOUND
,03-31 10:14:09.025  2153  2228 W bt-btif : bta_jv_rfc_port_to_cb(port_handle:0x10):jv handle:0x0 not FOUND
,03-31 10:14:09.025  2153  2228 E bt-btif : bta_jv_port_mgmt_sr_cback, p_cb:0x0, p_cb->p_cback0x0
,03-31 10:14:10.256  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 10:14:10.256  3253  3312 I jxcore-log: ,
03-31 10:14:10.258  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 10:14:10.258  3253  3312 I jxcore-log: 
,03-31 10:14:10.267  3253  3312 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
,03-31 10:14:10.267  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 10:14:10.267  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 10:14:10.267  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 10:14:10.267  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 10:14:10.267  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 10:14:10.267  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 10:14:10.267  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 10:14:10.272  3253  3312 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 10:14:10.274  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,03-31 10:14:10.274  3253  3312 I jxcore-log: 
,03-31 10:14:10.277  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,03-31 10:14:10.277  3253  3312 I jxcore-log: 
,03-31 10:14:10.282  3253  3312 I jxcore-log: # 42. #startListeningForAdvertisements should fail if start not called
,03-31 10:14:10.282  3253  3312 I jxcore-log: 
,03-31 10:14:10.286  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"},
03-31 10:14:10.286  3253  3312 I jxcore-log: 
,03-31 10:14:10.454  3253  3312 I jxcore-log: ok 180 specific error should be returned
03-31 10:14:10.454  3253  3312 I jxcore-log: 
,03-31 10:14:10.460  3253  3312 I jxcore-log: # teardown
03-31 10:14:10.460  3253  3312 I jxcore-log: 
,03-31 10:14:10.709  3253  3312 I jxcore-log: ok 181 must be stopped
03-31 10:14:10.709  3253  3312 I jxcore-log: 
,03-31 10:14:10.715  3253  3312 I jxcore-log: # setup
03-31 10:14:10.715  3253  3312 I jxcore-log: 
,03-31 10:14:10.965  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,03-31 10:14:10.965  3253  3312 I jxcore-log: 
,03-31 10:14:10.966  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 10:14:10.966  3253  3312 I jxcore-log: 
,03-31 10:14:10.975  3253  3312 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
,03-31 10:14:10.975  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 10:14:10.975  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 10:14:10.975  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 10:14:10.975  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 10:14:10.975  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 10:14:10.975  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 10:14:10.975  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 10:14:10.979  3253  3312 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 10:14:10.981  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 10:14:10.981  3253  3312 I jxcore-log: 
,03-31 10:14:10.983  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 10:14:10.983  3253  3312 I jxcore-log: 
,03-31 10:14:10.987  3253  3312 I jxcore-log: # 43. #startUpdateAdvertisingAndListening should fail if start not called
03-31 10:14:10.987  3253  3312 I jxcore-log: 
,03-31 10:14:10.988  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 10:14:10.988  3253  3312 I jxcore-log: 
,03-31 10:14:11.239  3253  3312 I jxcore-log: ok 182 specific error should be returned
03-31 10:14:11.239  3253  3312 I jxcore-log: 
,03-31 10:14:11.245  3253  3312 I jxcore-log: # teardown
03-31 10:14:11.245  3253  3312 I jxcore-log: 
,03-31 10:14:11.984  3253  3312 I jxcore-log: ok 183 must be stopped
03-31 10:14:11.984  3253  3312 I jxcore-log: 
,03-31 10:14:11.986  3253  3312 I jxcore-log: # setup
03-31 10:14:11.986  3253  3312 I jxcore-log: 
,03-31 10:14:12.719  2153  2228 E bt-btm  : btm_sec_disconnected - Clearing Pending flag
,03-31 10:14:12.728  2153  2153 D BluetoothMapService: onReceive
,03-31 10:14:12.830   822   841 I ActivityManager: Start proc 4281:com.google.android.googlequicksearchbox:search/u0a28 for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver
,03-31 10:14:12.941   822   861 D BluetoothManagerService: Message: 20
03-31 10:14:12.942   822   861 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c6d81ac:true
,03-31 10:14:12.958  4281  4281 I BTConnectionReceiver: onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,03-31 10:14:13.150   822  1429 I ActivityManager: Start proc 4307:com.google.android.partnersetup/u0a16 for content provider com.google.android.partnersetup/.RlzAppProvider
,03-31 10:14:13.153  4281  4281 I BluetoothClassifier: Bluetooth Device Name: Note4-1
,03-31 10:14:13.157   822   840 I art     : Explicit concurrent mark sweep GC freed 22130(1056KB) AllocSpace objects, 1(110KB) LOS objects, 32% free, 33MB/49MB, paused 1.479ms total 69.898ms
,03-31 10:14:13.164   822  1412 I ActivityManager: Killing 3645:com.android.providers.calendar/u0a3 (adj 15): empty #17
,03-31 10:14:13.235  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 10:14:13.235  3253  3312 I jxcore-log: 
,03-31 10:14:13.236  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 10:14:13.236  3253  3312 I jxcore-log: 
,03-31 10:14:13.240  3253  3312 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 10:14:13.240  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 10:14:13.240  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 10:14:13.240  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 10:14:13.240  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 10:14:13.240  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 10:14:13.240  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 10:14:13.240  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 10:14:13.241  3253  3312 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
03-31 10:14:13.242  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 10:14:13.242  3253  3312 I jxcore-log: 
,03-31 10:14:13.243  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 10:14:13.243  3253  3312 I jxcore-log: 
,03-31 10:14:13.244  3253  3312 I jxcore-log: # 44. should be able to call #stopListeningForAdvertisements many times
03-31 10:14:13.244  3253  3312 I jxcore-log: 
03-31 10:14:13.245  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 10:14:13.245  3253  3312 I jxcore-log: 
,03-31 10:14:13.279   822   840 I ActivityManager: Killing 3895:com.google.android.gm.exchange/u0a77 (adj 15): empty #17
,03-31 10:14:13.422  3253  3312 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 10:14:13.422  3253  3312 I jxcore-log: 
,03-31 10:14:13.424  3253  3312 I jxcore-log: DEBUG createNativeListener: listening 50510,
03-31 10:14:13.424  3253  3312 I jxcore-log: 
,03-31 10:14:13.427  3253  3312 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements,
03-31 10:14:13.427  3253  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 10:14:13.428  3253  3312 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 10:14:13.431  3253  3312 I jxcore-log: ok 184 no errors
,03-31 10:14:13.431  3253  3312 I jxcore-log: 
,03-31 10:14:13.433  3253  3312 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-31 10:14:13.433  3253  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 10:14:13.433  3253  3312 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 10:14:13.437  3253  3312 I jxcore-log: ok 185 still no errors
03-31 10:14:13.437  3253  3312 I jxcore-log: ,
03-31 10:14:13.438  2153  2214 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
03-31 10:14:13.443  3253  3312 I jxcore-log: # teardown
03-31 10:14:13.443  3253  3312 I jxcore-log: 
,03-31 10:14:13.607  3253  3312 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-31 10:14:13.607  3253  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 10:14:13.607  3253  3312 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 10:14:13.611  3253  3312 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-31 10:14:13.611  3253  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 10:14:13.611  3253  3312 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 10:14:13.623  3253  3312 I jxcore-log: ok 186 must be stopped
,03-31 10:14:13.623  3253  3312 I jxcore-log: 
,03-31 10:14:13.630  3253  3312 I jxcore-log: # setup
,03-31 10:14:13.630  3253  3312 I jxcore-log: 
,03-31 10:14:13.748  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 10:14:13.748  3253  3312 I jxcore-log: 
,03-31 10:14:13.753  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 10:14:13.753  3253  3312 I jxcore-log: 
,03-31 10:14:13.760  3253  3312 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 10:14:13.760  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 10:14:13.760  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 10:14:13.760  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 10:14:13.760  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 10:14:13.760  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 10:14:13.760  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 10:14:13.760  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 10:14:13.763  3253  3312 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 10:14:13.765  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 10:14:13.765  3253  3312 I jxcore-log: 
,03-31 10:14:13.766  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 10:14:13.766  3253  3312 I jxcore-log: 
,03-31 10:14:13.769  3253  3312 I jxcore-log: # 45. should be able to call #startListeningForAdvertisements many times
03-31 10:14:13.769  3253  3312 I jxcore-log: 
,03-31 10:14:13.771  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 10:14:13.771  3253  3312 I jxcore-log: 
,03-31 10:14:14.027  3253  3312 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 10:14:14.027  3253  3312 I jxcore-log: 
,03-31 10:14:14.029  3253  3312 I jxcore-log: DEBUG createNativeListener: listening 46532
03-31 10:14:14.029  3253  3312 I jxcore-log: 
,03-31 10:14:14.035  3253  3312 I io.jxcore.node.ConnectionHelper: start: Port number: 35132, start advertisements: false
,03-31 10:14:14.035  3253  3312 I io.jxcore.node.ConnectionHelper: restoreDefaultBleDiscoverySettings: Powering the BLE discovery back up
03-31 10:14:14.035  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 0 -> 2
03-31 10:14:14.035  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-31 10:14:14.035  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-31 10:14:14.035  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-31 10:14:14.035  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-31 10:14:14.035  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-31 10:14:14.035  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-31 10:14:14.035  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 1, timeout: 0, is connectable: false
03-31 10:14:14.035  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-31 10:14:14.035  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 1 -> 3
,03-31 10:14:14.035  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-31 10:14:14.035  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-31 10:14:14.035  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-31 10:14:14.035  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-31 10:14:14.035  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-31 10:14:14.035  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-31 10:14:14.036  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-31 10:14:14.036  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-31 10:14:14.036  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 0 -> 2
03-31 10:14:14.036  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-31 10:14:14.036  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-31 10:14:14.036  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-31 10:14:14.036  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-31 10:14:14.036  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-31 10:14:14.036  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-31 10:14:14.036  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-31 10:14:14.036  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-31 10:14:14.036  3253  3312 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 10:14:14.036  3253  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-31 10:14:14.036  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
03-31 10:14:14.042  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-31 10:14:14.042  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 10:14:14.042  3253  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 10:14:14.047  2153  2337 D BtGatt.GattService: registerClient() - UUID=1a8f9f14-9b93-4374-82ce-b83128015235,
03-31 10:14:14.047  2153  2216 D BtGatt.GattService: onClientRegistered() - UUID=1a8f9f14-9b93-4374-82ce-b83128015235, clientIf=5
03-31 10:14:14.048  3253  3854 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-31 10:14:14.049  2153  2170 D BtGatt.GattService: start scan with filters,
03-31 10:14:14.051  2153  2227 D BtGatt.ScanManager: handling starting scan
03-31 10:14:14.053  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-31 10:14:14.053  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true,
03-31 10:14:14.053  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-31 10:14:14.053  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-31 10:14:14.054  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
,03-31 10:14:14.054  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-31 10:14:14.054  3253  3253 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 10:14:14.054   822  1378 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-31 10:14:14.055  2153  2216 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-31 10:14:14.055  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 10:14:14.056  2153  2216 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-31 10:14:14.056  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
03-31 10:14:14.057  2153  2227 D BtGatt.ScanManager: Starting BLE batch scan
03-31 10:14:14.057  2153  2227 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-31 10:14:14.057  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 10:14:14.057  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-31 10:14:14.057  3253  3312 I io.jxcore.node.ConnectionHelper: start: OK
03-31 10:14:14.058  3253  3253 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-31 10:14:14.058  3253  3253 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 10:14:14.058  3253  3253 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 10:14:14.059  2153  2216 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-31 10:14:14.059  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 10:14:14.060  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 10:14:14.060  3253  3312 I jxcore-log: 
03-31 10:14:14.061  2153  2216 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-31 10:14:14.061  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 10:14:14.062  3253  3312 I jxcore-log: ok 187 no errors
03-31 10:14:14.062  3253  3312 I jxcore-log: 
03-31 10:14:14.067  3253  3312 I io.jxcore.node.ConnectionHelper: start: Port number: 35132, start advertisements: false,
03-31 10:14:14.067  3253  3312 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 10:14:14.067  3253  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-31 10:14:14.067  3253  3312 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-31 10:14:14.067  3253  3312 I io.jxcore.node.ConnectionHelper: start: OK
,03-31 10:14:14.070  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 10:14:14.070  3253  3312 I jxcore-log: 
,03-31 10:14:14.071  3253  3312 I jxcore-log: ok 188 still no errors
,03-31 10:14:14.071  3253  3312 I jxcore-log: 
,03-31 10:14:14.079  3253  3312 I jxcore-log: # teardown,
03-31 10:14:14.079  3253  3312 I jxcore-log: 
,03-31 10:14:14.094  2153  2228 E bt-btm  : btm_sec_disconnected - Clearing Pending flag,
,03-31 10:14:14.097  2153  2153 D BluetoothMapService: onReceive,
,03-31 10:14:14.111  4281  4281 I BTConnectionReceiver: onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,03-31 10:14:14.114  4281  4281 I BluetoothClassifier: Bluetooth Device Name: G4-1
,03-31 10:14:14.326  3253  3312 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-31 10:14:14.326  3253  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
03-31 10:14:14.326  3253  3312 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,03-31 10:14:14.326  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-31 10:14:14.326  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-31 10:14:14.326  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-31 10:14:14.326  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-31 10:14:14.327  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-31 10:14:14.327  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-31 10:14:14.332  2153  2171 D BtGatt.GattService: stopScan() - queue size =1
,03-31 10:14:14.335  2153  2216 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,03-31 10:14:14.335  2153  2170 D BtGatt.GattService: unregisterClient() - clientIf=5
03-31 10:14:14.335  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 10:14:14.336  2153  2227 D BtGatt.ScanManager: stopping BLe Batch
,03-31 10:14:14.336  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-31 10:14:14.336  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED,
03-31 10:14:14.336  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false,
03-31 10:14:14.337  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-31 10:14:14.338  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-31 10:14:14.338  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-31 10:14:14.339  2153  2216 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-31 10:14:14.339  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 10:14:14.339  2153  2227 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-31 10:14:14.340  2153  2216 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,03-31 10:14:14.340  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 10:14:14.340  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-31 10:14:14.340  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,03-31 10:14:14.341  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-31 10:14:14.342  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-31 10:14:14.342  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,03-31 10:14:14.342  3253  3253 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 10:14:14.342  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 10:14:14.343  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-31 10:14:14.353  3253  3253 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-31 10:14:14.354   822  1412 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 10:14:14.366  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-31 10:14:14.367  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0,
03-31 10:14:14.367  3253  3253 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-31 10:14:14.374  3253  3253 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-31 10:14:14.374  3253  3253 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 10:14:14.374  3253  3253 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 10:14:14.375  3253  3253 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-31 10:14:14.377  3253  3312 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-31 10:14:14.378  3253  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 10:14:14.378  3253  3312 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 10:14:14.381  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 10:14:14.381  3253  3312 I jxcore-log: 
,03-31 10:14:14.384  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 10:14:14.384  3253  3312 I jxcore-log: 
,03-31 10:14:14.394  3253  3312 I jxcore-log: ok 189 must be stopped
,03-31 10:14:14.394  3253  3312 I jxcore-log: 
,03-31 10:14:14.406  3253  3312 I jxcore-log: # setup
,03-31 10:14:14.406  3253  3312 I jxcore-log: 
,03-31 10:14:14.569  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 10:14:14.569  3253  3312 I jxcore-log: 
,03-31 10:14:14.570  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 10:14:14.570  3253  3312 I jxcore-log: 
,03-31 10:14:14.579  3253  3312 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
03-31 10:14:14.579  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 10:14:14.579  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 10:14:14.579  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 10:14:14.579  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true,
03-31 10:14:14.579  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 10:14:14.579  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 10:14:14.579  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 10:14:14.583  3253  3312 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
,03-31 10:14:14.586  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native,
03-31 10:14:14.586  3253  3312 I jxcore-log: 
,03-31 10:14:14.590  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native,
03-31 10:14:14.590  3253  3312 I jxcore-log: 
,03-31 10:14:14.596  3253  3312 I jxcore-log: # 46. should be able to call #startUpdateAdvertisingAndListening many times,
03-31 10:14:14.596  3253  3312 I jxcore-log: 
,03-31 10:14:14.600  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"},
03-31 10:14:14.600  3253  3312 I jxcore-log: 
,03-31 10:14:14.776  3253  3312 I jxcore-log: DEBUG createNativeListener: creating native server,
,03-31 10:14:14.776  3253  3312 I jxcore-log: ,
,03-31 10:14:14.778  3253  3312 I jxcore-log: DEBUG createNativeListener: listening 55085
,03-31 10:14:14.778  3253  3312 I jxcore-log: ,
,03-31 10:14:14.784  3253  3312 I io.jxcore.node.ConnectionHelper: start: Port number: 55085, start advertisements: true
,03-31 10:14:14.784  3253  3312 V io.jxcore.node.ConnectivityMonitor: start: Already started,
,03-31 10:14:14.784  3253  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything,
,03-31 10:14:14.784  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true,
03-31 10:14:14.789  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-31 10:14:14.789  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-31 10:14:14.789  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 10:14:14.789  3253  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-31 10:14:14.796  2153  2171 D BtGatt.GattService: registerClient() - UUID=76ef11e4-b49e-463b-b161-1c118b300c9b,
,03-31 10:14:14.797  2153  2216 D BtGatt.GattService: onClientRegistered() - UUID=76ef11e4-b49e-463b-b161-1c118b300c9b, clientIf=5
03-31 10:14:14.798  3253  3854 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-31 10:14:14.799  2153  2337 D BtGatt.GattService: start scan with filters
03-31 10:14:14.800  2153  2227 D BtGatt.ScanManager: handling starting scan
03-31 10:14:14.802  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-31 10:14:14.802  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 10:14:14.802  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-31 10:14:14.802  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,03-31 10:14:14.802  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 10:14:14.802  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-31 10:14:14.802  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-31 10:14:14.802  3253  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-31 10:14:14.802  3253  3253 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false,
03-31 10:14:14.802  3253  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 10:14:14.802  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 10:14:14.802  3253  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-31 10:14:14.803  2153  2216 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-31 10:14:14.803  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 10:14:14.805  2153  2216 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-31 10:14:14.805  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 10:14:14.805  2153  2227 D BtGatt.ScanManager: Starting BLE batch scan
03-31 10:14:14.805  2153  2227 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-31 10:14:14.807  2153  2171 D BtGatt.GattService: registerClient() - UUID=01f1253f-a69f-4deb-955c-0c7b3ea6f913
03-31 10:14:14.808  2153  2216 D BtGatt.GattService: onClientRegistered() - UUID=01f1253f-a69f-4deb-955c-0c7b3ea6f913, clientIf=6
,03-31 10:14:14.808  3253  3268 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-31 10:14:14.809  2153  2216 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-31 10:14:14.809  2153  2226 D BtGatt.AdvertiseManager: message : 0
03-31 10:14:14.809  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 10:14:14.812  2153  2216 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-31 10:14:14.812  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 10:14:14.816  2153  2226 D BtGatt.AdvertiseManager: starting multi advertising
,03-31 10:14:14.819  2153  2216 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-31 10:14:14.823  2153  2216 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-31 10:14:14.823  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-31 10:14:14.823  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-31 10:14:14.824   822  1384 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 10:14:14.828  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-31 10:14:14.828  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-31 10:14:14.828  3253  3312 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-31 10:14:14.828  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
,03-31 10:14:14.829  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-31 10:14:14.830  3253  3312 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,03-31 10:14:14.830  3253  3312 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-31 10:14:14.830  3253  3312 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-31 10:14:14.830  3253  3312 I io.jxcore.node.ConnectionHelper: start: OK
,03-31 10:14:14.830  3253  3253 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-31 10:14:14.831  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-31 10:14:14.831  3253  3253 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING,
03-31 10:14:14.831  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-31 10:14:14.831  3253  3253 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
,03-31 10:14:14.831  3253  3253 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-31 10:14:14.831  3253  3253 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-31 10:14:14.831  3253  3253 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false,
03-31 10:14:14.832  3253  3253 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-31 10:14:14.832  3253  3253 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-31 10:14:14.832  3253  3253 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-31 10:14:14.832  3253  3253 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-31 10:14:14.832  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
,03-31 10:14:14.832  3253  3312 I jxcore-log: 
03-31 10:14:14.833   822  1412 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-31 10:14:14.834  3253  4327 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-31 10:14:14.837  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false},
03-31 10:14:14.837  3253  3312 I jxcore-log: 
03-31 10:14:14.838  3253  4327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
03-31 10:14:14.839  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true},
03-31 10:14:14.839  3253  3312 I jxcore-log: 
03-31 10:14:14.840  3253  3312 I jxcore-log: ok 190 no errors
03-31 10:14:14.840  3253  3312 I jxcore-log: 
,03-31 10:14:14.846  3253  3312 I io.jxcore.node.ConnectionHelper: start: Port number: 55085, start advertisements: true,
,03-31 10:14:14.846  3253  3312 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-31 10:14:14.846  3253  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-31 10:14:14.846  3253  3312 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 10:14:14.846  3253  3312 I io.jxcore.node.ConnectionHelper: start: OK
,03-31 10:14:14.850  3253  3312 I jxcore-log: ok 191 still no errors,
03-31 10:14:14.850  3253  3312 I jxcore-log: 
,03-31 10:14:14.865  3253  3312 I jxcore-log: # teardown,
03-31 10:14:14.865  3253  3312 I jxcore-log: 
,03-31 10:14:15.146  3253  3312 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections,
03-31 10:14:15.147  3253  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
,03-31 10:14:15.147  3253  3312 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,03-31 10:14:15.147  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,03-31 10:14:15.147  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-31 10:14:15.149  3253  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-31 10:14:15.149  3253  4327 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-31 10:14:15.149  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-31 10:14:15.149  3253  4327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-31 10:14:15.149  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-31 10:14:15.149  3253  4327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,03-31 10:14:15.149  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,03-31 10:14:15.149  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode,
03-31 10:14:15.149  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-31 10:14:15.150  3253  3253 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-31 10:14:15.150  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-31 10:14:15.150  3253  3253 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-31 10:14:15.154  2153  2170 D BtGatt.GattService: stopScan() - queue size =1,
03-31 10:14:15.165  2153  2216 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-31 10:14:15.165  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 10:14:15.165  2153  2337 D BtGatt.GattService: unregisterClient() - clientIf=5
03-31 10:14:15.165  2153  2227 D BtGatt.ScanManager: stopping BLe Batch,
,03-31 10:14:15.165  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 10:14:15.165  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 10:14:15.165  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-31 10:14:15.165  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING],
03-31 10:14:15.165  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-31 10:14:15.165  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-31 10:14:15.165  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-31 10:14:15.175  2153  2216 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-31 10:14:15.175  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 10:14:15.175  2153  2227 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-31 10:14:15.178  2153  2216 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-31 10:14:15.178  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 10:14:15.178  2153  2216 D BtGatt.GattService: current time is 260095509795,
03-31 10:14:15.178  2153  2216 D BtGatt.GattService: Batch record : [-126, -74, -2, 9, 66, 121, 1, -128, -81, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -63, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-31 10:14:15.178  2153  2216 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-31 10:14:15.178  2153  2226 D BtGatt.AdvertiseManager: message : 1
,03-31 10:14:15.178  2153  2216 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-31 10:14:15.182  2153  2226 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-31 10:14:15.184  2153  2216 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,03-31 10:14:15.184  2153  2216 D BtGatt.GattService: Client app is not null!
03-31 10:14:15.185  2153  2337 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-31 10:14:15.185  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-31 10:14:15.185  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-31 10:14:15.185  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-31 10:14:15.186  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-31 10:14:15.186  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,03-31 10:14:15.186  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 10:14:15.186  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-31 10:14:15.186  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-31 10:14:15.186  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-31 10:14:15.186  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 10:14:15.186  3253  3253 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 10:14:15.186  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 10:14:15.187  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-31 10:14:15.191  3253  3253 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-31 10:14:15.191   822  1454 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 10:14:15.196  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-31 10:14:15.196  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-31 10:14:15.197  3253  3253 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-31 10:14:15.200  3253  3253 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-31 10:14:15.200  3253  3253 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 10:14:15.200  3253  3253 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 10:14:15.200  3253  3253 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-31 10:14:15.200  3253  3253 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 10:14:15.201  3253  3253 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-31 10:14:15.201  3253  3312 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-31 10:14:15.201  3253  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 10:14:15.201  3253  3312 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-31 10:14:15.203  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-31 10:14:15.203  3253  3312 I jxcore-log: 
,03-31 10:14:15.204  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 10:14:15.204  3253  3312 I jxcore-log: 
,03-31 10:14:15.204  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 10:14:15.204  3253  3312 I jxcore-log: 
,03-31 10:14:15.208  3253  3312 I jxcore-log: ok 192 must be stopped
03-31 10:14:15.208  3253  3312 I jxcore-log: 
,03-31 10:14:15.214  3253  3312 I jxcore-log: # setup
03-31 10:14:15.214  3253  3312 I jxcore-log: 
,03-31 10:14:15.479  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 10:14:15.479  3253  3312 I jxcore-log: 
,03-31 10:14:15.484  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 10:14:15.484  3253  3312 I jxcore-log: 
,03-31 10:14:15.492  3253  3312 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 10:14:15.492  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 10:14:15.492  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 10:14:15.492  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 10:14:15.492  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 10:14:15.492  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 10:14:15.492  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 10:14:15.492  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 10:14:15.496  3253  3312 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 10:14:15.497  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 10:14:15.497  3253  3312 I jxcore-log: 
,03-31 10:14:15.499  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 10:14:15.499  3253  3312 I jxcore-log: 
,03-31 10:14:15.502  3253  3312 I jxcore-log: # 47. should be able to call #stopAdvertisingAndListening many times
03-31 10:14:15.502  3253  3312 I jxcore-log: 
,03-31 10:14:15.504  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 10:14:15.504  3253  3312 I jxcore-log: 
,03-31 10:14:15.621  2153  2228 W bt-btif : dm_pm_timer expires
,03-31 10:14:15.621  2153  2228 W bt-btif : dm_pm_timer expires 0
03-31 10:14:15.621  2153  2228 W bt-btif : proc dm_pm_timer expires
,03-31 10:14:15.671  3253  3312 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 10:14:15.671  3253  3312 I jxcore-log: 
,03-31 10:14:15.673  3253  3312 I jxcore-log: DEBUG createNativeListener: listening 48018
03-31 10:14:15.673  3253  3312 I jxcore-log: 
,03-31 10:14:15.675  3253  3312 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 10:14:15.675  3253  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 10:14:15.676  3253  3312 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 10:14:15.677  3253  3312 I jxcore-log: ok 193 no errors
03-31 10:14:15.677  3253  3312 I jxcore-log: 
03-31 10:14:15.678  3253  3312 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-31 10:14:15.679  3253  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-31 10:14:15.679  3253  3312 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 10:14:15.681  3253  3312 I jxcore-log: ok 194 still no errors
03-31 10:14:15.681  3253  3312 I jxcore-log: 
,03-31 10:14:15.687  3253  3312 I jxcore-log: # teardown
03-31 10:14:15.687  3253  3312 I jxcore-log: 
,03-31 10:14:15.810  3253  3312 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 10:14:15.810  3253  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 10:14:15.810  3253  3312 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 10:14:15.814  3253  3312 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-31 10:14:15.814  3253  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 10:14:15.814  3253  3312 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 10:14:15.825  3253  3312 I jxcore-log: ok 195 must be stopped
03-31 10:14:15.825  3253  3312 I jxcore-log: 
,03-31 10:14:15.830  3253  3312 I jxcore-log: # setup
03-31 10:14:15.830  3253  3312 I jxcore-log: 
,03-31 10:14:15.923  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 10:14:15.923  3253  3312 I jxcore-log: 
,03-31 10:14:15.925  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 10:14:15.925  3253  3312 I jxcore-log: 
,03-31 10:14:15.932  3253  3312 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 10:14:15.932  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 10:14:15.932  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 10:14:15.932  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 10:14:15.932  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 10:14:15.932  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 10:14:15.932  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 10:14:15.932  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 10:14:15.936  3253  3312 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 10:14:15.937  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 10:14:15.937  3253  3312 I jxcore-log: 
,03-31 10:14:15.939  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 10:14:15.939  3253  3312 I jxcore-log: 
,03-31 10:14:15.942  3253  3312 I jxcore-log: # 48. can get the network status before starting
03-31 10:14:15.942  3253  3312 I jxcore-log: 
,03-31 10:14:15.944  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 10:14:15.944  3253  3312 I jxcore-log: 
,03-31 10:14:16.100  3253  3312 I jxcore-log: ok 196 network status should have certain non-empty properties
03-31 10:14:16.100  3253  3312 I jxcore-log: 
,03-31 10:14:16.105  3253  3312 I jxcore-log: # teardown
03-31 10:14:16.105  3253  3312 I jxcore-log: 
,03-31 10:14:16.224  3253  3312 I jxcore-log: ok 197 must be stopped
03-31 10:14:16.224  3253  3312 I jxcore-log: 
,03-31 10:14:16.226  3253  3312 I jxcore-log: # setup
03-31 10:14:16.226  3253  3312 I jxcore-log: 
,03-31 10:14:16.370  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 10:14:16.370  3253  3312 I jxcore-log: 
,03-31 10:14:16.375  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 10:14:16.375  3253  3312 I jxcore-log: 
,03-31 10:14:16.386  3253  3312 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 10:14:16.386  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 10:14:16.386  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 10:14:16.386  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 10:14:16.386  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 10:14:16.386  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 10:14:16.386  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 10:14:16.386  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 10:14:16.390  3253  3312 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 10:14:16.392  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 10:14:16.392  3253  3312 I jxcore-log: 
,03-31 10:14:16.393  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 10:14:16.393  3253  3312 I jxcore-log: 
,03-31 10:14:16.396  3253  3312 I jxcore-log: # 49. error returned with bad router
03-31 10:14:16.396  3253  3312 I jxcore-log: 
,03-31 10:14:16.398  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 10:14:16.398  3253  3312 I jxcore-log: 
,03-31 10:14:16.530  3253  3312 I jxcore-log: ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a string
03-31 10:14:16.530  3253  3312 I jxcore-log: 
,03-31 10:14:16.533  3253  3312 I jxcore-log: ok 198 specific error expected
03-31 10:14:16.533  3253  3312 I jxcore-log: 
,03-31 10:14:16.535  3253  3312 I jxcore-log: # teardown
03-31 10:14:16.535  3253  3312 I jxcore-log: 
,03-31 10:14:16.656  3253  3312 I jxcore-log: ok 199 must be stopped
03-31 10:14:16.656  3253  3312 I jxcore-log: 
,03-31 10:14:16.662  3253  3312 I jxcore-log: # setup
03-31 10:14:16.662  3253  3312 I jxcore-log: 
,03-31 10:14:16.797  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 10:14:16.797  3253  3312 I jxcore-log: 
,03-31 10:14:16.801  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 10:14:16.801  3253  3312 I jxcore-log: 
,03-31 10:14:16.810  3253  3312 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 10:14:16.810  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 10:14:16.810  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 10:14:16.810  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 10:14:16.810  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 10:14:16.810  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 10:14:16.810  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 10:14:16.810  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 10:14:16.814  3253  3312 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 10:14:16.815  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 10:14:16.815  3253  3312 I jxcore-log: 
,03-31 10:14:16.817  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 10:14:16.817  3253  3312 I jxcore-log: 
,03-31 10:14:16.820  3253  3312 I jxcore-log: # 50. all services are stopped when we call stop
03-31 10:14:16.820  3253  3312 I jxcore-log: 
,03-31 10:14:16.822  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 10:14:16.822  3253  3312 I jxcore-log: 
,03-31 10:14:16.953  3253  3312 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 10:14:16.953  3253  3312 I jxcore-log: 
,03-31 10:14:16.955  3253  3312 I jxcore-log: DEBUG createNativeListener: listening 42956
03-31 10:14:16.955  3253  3312 I jxcore-log: 
,03-31 10:14:16.962  3253  3312 I io.jxcore.node.ConnectionHelper: start: Port number: 55085, start advertisements: false
,03-31 10:14:16.962  3253  3312 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 10:14:16.962  3253  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-31 10:14:16.962  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-31 10:14:16.967  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-31 10:14:16.967  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-31 10:14:16.967  3253  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 10:14:16.972  2153  2337 D BtGatt.GattService: registerClient() - UUID=942028e6-8f9c-4239-93e1-6aeb7cc03c1d
03-31 10:14:16.973  2153  2216 D BtGatt.GattService: onClientRegistered() - UUID=942028e6-8f9c-4239-93e1-6aeb7cc03c1d, clientIf=5
,03-31 10:14:16.973  3253  3269 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-31 10:14:16.974  2153  2170 D BtGatt.GattService: start scan with filters
,03-31 10:14:16.976  2153  2227 D BtGatt.ScanManager: handling starting scan
,03-31 10:14:16.977  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-31 10:14:16.977  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-31 10:14:16.977  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,03-31 10:14:16.977  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,03-31 10:14:16.977  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 10:14:16.977  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-31 10:14:16.978  3253  3253 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 10:14:16.980   822  3823 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 10:14:16.982  2153  2216 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-31 10:14:16.983  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 10:14:16.986  2153  2216 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,03-31 10:14:16.986  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 10:14:16.986  2153  2227 D BtGatt.ScanManager: Starting BLE batch scan
03-31 10:14:16.986  2153  2227 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-31 10:14:16.988  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-31 10:14:16.989  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-31 10:14:16.989  3253  3312 I io.jxcore.node.ConnectionHelper: start: OK
03-31 10:14:16.989  3253  3253 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only,
03-31 10:14:16.989  3253  3253 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 10:14:16.989  2153  2216 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,03-31 10:14:16.989  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 10:14:16.990  3253  3253 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 10:14:16.991  2153  2216 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-31 10:14:16.991  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 10:14:16.995  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 10:14:16.995  3253  3312 I jxcore-log: 
,03-31 10:14:16.997  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 10:14:16.997  3253  3312 I jxcore-log: 
,03-31 10:14:17.005  3253  3312 I io.jxcore.node.ConnectionHelper: start: Port number: 42956, start advertisements: true
,03-31 10:14:17.005  3253  3312 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 10:14:17.005  3253  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-31 10:14:17.005  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-31 10:14:17.010  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
03-31 10:14:17.010  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
,03-31 10:14:17.010  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-31 10:14:17.010  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-31 10:14:17.010  3253  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
,03-31 10:14:17.010  3253  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 10:14:17.010  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 10:14:17.010  3253  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-31 10:14:17.016  2153  2171 D BtGatt.GattService: registerClient() - UUID=3af4f975-6d2a-4420-977c-9cc016ab27b1
,03-31 10:14:17.017  2153  2216 D BtGatt.GattService: onClientRegistered() - UUID=3af4f975-6d2a-4420-977c-9cc016ab27b1, clientIf=6
03-31 10:14:17.017  3253  3854 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-31 10:14:17.018  2153  2226 D BtGatt.AdvertiseManager: message : 0
,03-31 10:14:17.020  2153  2226 D BtGatt.AdvertiseManager: starting multi advertising,
,03-31 10:14:17.024  2153  2216 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0,
,03-31 10:14:17.026  2153  2216 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-31 10:14:17.027  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,03-31 10:14:17.027  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-31 10:14:17.027  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-31 10:14:17.027  3253  3253 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-31 10:14:17.027  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-31 10:14:17.027  3253  3253 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-31 10:14:17.027  3253  3253 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-31 10:14:17.027   822  1201 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 10:14:17.031  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-31 10:14:17.031  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-31 10:14:17.031  3253  3312 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-31 10:14:17.031  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 10:14:17.031  3253  3253 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-31 10:14:17.032  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-31 10:14:17.032  3253  3312 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-31 10:14:17.032  3253  3312 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-31 10:14:17.032  3253  3312 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-31 10:14:17.032  3253  3312 I io.jxcore.node.ConnectionHelper: start: OK
03-31 10:14:17.033  3253  3253 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,03-31 10:14:17.033  3253  3253 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 10:14:17.033  3253  3253 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-31 10:14:17.034   822  1454 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-31 10:14:17.035  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-31 10:14:17.035  3253  3312 I jxcore-log: 
03-31 10:14:17.036  3253  4328 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-31 10:14:17.041  3253  3312 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 10:14:17.041  3253  3312 I jxcore-log: 
,03-31 10:14:17.044  3253  4328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-31 10:14:17.044  3253  3312 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 10:14:17.044  3253  3312 I jxcore-log: 
,03-31 10:14:17.046  3253  3312 I jxcore-log: DEBUG createNativeListener: new mux
03-31 10:14:17.046  3253  3312 I jxcore-log: 
,03-31 10:14:17.051  3253  3312 I jxcore-log: ok 200 connection to servers manager should succeed after starting
03-31 10:14:17.051  3253  3312 I jxcore-log: 
,03-31 10:14:17.075  3253  3312 I jxcore-log: ok 201 connection to router server should succeed after starting
03-31 10:14:17.075  3253  3312 I jxcore-log: 
,03-31 10:14:17.076  3253  3312 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-31 10:14:17.076  3253  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-31 10:14:17.076  3253  3312 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-31 10:14:17.076  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-31 10:14:17.076  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-31 10:14:17.077  3253  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-31 10:14:17.077  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-31 10:14:17.077  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,03-31 10:14:17.077  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-31 10:14:17.077  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-31 10:14:17.077  3253  4328 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-31 10:14:17.077  3253  4328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-31 10:14:17.077  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-31 10:14:17.077  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-31 10:14:17.077  3253  4328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-31 10:14:17.079  2153  2337 D BtGatt.GattService: stopScan() - queue size =1,
03-31 10:14:17.079  2153  2170 D BtGatt.GattService: unregisterClient() - clientIf=5
03-31 10:14:17.080  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 10:14:17.080  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-31 10:14:17.080  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-31 10:14:17.080  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-31 10:14:17.080  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
,03-31 10:14:17.080  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-31 10:14:17.080  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-31 10:14:17.080  2153  2216 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-31 10:14:17.080  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 10:14:17.080  2153  2227 D BtGatt.ScanManager: stopping BLe Batch
,03-31 10:14:17.082  2153  2226 D BtGatt.AdvertiseManager: message : 1
03-31 10:14:17.083  2153  2226 D BtGatt.AdvertiseManager: stop advertise for client 6
03-31 10:14:17.084  2153  2216 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-31 10:14:17.084  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 10:14:17.084  2153  2227 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-31 10:14:17.086  2153  2216 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-31 10:14:17.086  2153  2216 D BtGatt.GattService: Client app is not null!
03-31 10:14:17.086  2153  2170 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-31 10:14:17.087  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-31 10:14:17.087  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-31 10:14:17.087  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-31 10:14:17.087  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-31 10:14:17.087  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-31 10:14:17.087  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 10:14:17.087  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-31 10:14:17.087  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-31 10:14:17.088  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-31 10:14:17.088  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 10:14:17.089  3253  3253 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 10:14:17.089  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 10:14:17.089  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-31 10:14:17.090  2153  2216 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
03-31 10:14:17.090  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 10:14:17.091  2153  2216 D BtGatt.GattService: current time is 262008318700
,03-31 10:14:17.091  2153  2216 D BtGatt.GattService: Batch record : [-65, 71, 11, 114, 108, 108, 1, -128, -80, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-31 10:14:17.091  2153  2216 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-31 10:14:17.091  3253  3312 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 10:14:17.091  3253  3312 I jxcore-log: 
,03-31 10:14:17.099  3253  3253 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-31 10:14:17.099   822  1378 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 10:14:17.109  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-31 10:14:17.110  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-31 10:14:17.110  3253  3253 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-31 10:14:17.115  3253  3253 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-31 10:14:17.116  3253  3253 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,03-31 10:14:17.116  3253  3253 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-31 10:14:17.116  3253  3253 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 10:14:17.116  3253  3253 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 10:14:17.117  3253  3253 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 10:14:17.117  3253  3253 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 10:14:17.117  3253  3253 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-31 10:14:17.118  3253  3312 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-31 10:14:17.118  3253  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 10:14:17.118  3253  3312 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 10:14:17.119  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-31 10:14:17.119  3253  3312 I jxcore-log: 
03-31 10:14:17.120  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 10:14:17.120  3253  3312 I jxcore-log: 
03-31 10:14:17.121  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 10:14:17.121  3253  3312 I jxcore-log: 
03-31 10:14:17.126  3253  3312 I jxcore-log: ok 202 is stopped after calling stop
03-31 10:14:17.126  3253  3312 I jxcore-log: 
,03-31 10:14:17.132  3253  3312 I jxcore-log: ok 203 connection to servers manager should fail after stopping
03-31 10:14:17.132  3253  3312 I jxcore-log: 
,03-31 10:14:17.137  3253  3312 I jxcore-log: ok 204 connection to router server should fail after stopping
03-31 10:14:17.137  3253  3312 I jxcore-log: 
,03-31 10:14:17.142  3253  3312 I jxcore-log: # teardown
03-31 10:14:17.142  3253  3312 I jxcore-log: 
,03-31 10:14:17.634  3253  3312 I jxcore-log: ok 205 must be stopped
03-31 10:14:17.634  3253  3312 I jxcore-log: 
03-31 10:14:17.636  3253  3312 I jxcore-log: # setup
03-31 10:14:17.636  3253  3312 I jxcore-log: 
,03-31 10:14:17.825  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 10:14:17.825  3253  3312 I jxcore-log: 
,03-31 10:14:17.831  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,03-31 10:14:17.831  3253  3312 I jxcore-log: 
,03-31 10:14:17.844  3253  3312 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 10:14:17.844  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 10:14:17.844  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 10:14:17.844  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 10:14:17.844  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 10:14:17.844  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 10:14:17.844  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 10:14:17.844  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 10:14:17.849  3253  3312 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 10:14:17.852  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 10:14:17.852  3253  3312 I jxcore-log: ,
,03-31 10:14:17.856  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,03-31 10:14:17.856  3253  3312 I jxcore-log: 
,03-31 10:14:17.863  3253  3312 I jxcore-log: # 51. make sure terminateConnection is properly hooked up
,03-31 10:14:17.863  3253  3312 I jxcore-log: 
,03-31 10:14:17.865  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
,03-31 10:14:17.865  3253  3312 I jxcore-log: 
,03-31 10:14:18.087  3253  3312 I jxcore-log: ok 206 called with right arguments
03-31 10:14:18.087  3253  3312 I jxcore-log: ,
03-31 10:14:18.089  3253  3312 I jxcore-log: # teardown
03-31 10:14:18.089  3253  3312 I jxcore-log: 
,03-31 10:14:18.284  3253  3312 I jxcore-log: ok 207 must be stopped
03-31 10:14:18.284  3253  3312 I jxcore-log: 
,03-31 10:14:18.287  3253  3312 I jxcore-log: # setup
,03-31 10:14:18.287  3253  3312 I jxcore-log: 
,03-31 10:14:18.623  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 10:14:18.623  3253  3312 I jxcore-log: 
,03-31 10:14:18.625  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native,
03-31 10:14:18.625  3253  3312 I jxcore-log: 
,03-31 10:14:18.635  3253  3312 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
,03-31 10:14:18.635  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 10:14:18.635  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 10:14:18.635  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 10:14:18.635  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 10:14:18.635  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
,03-31 10:14:18.635  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 10:14:18.635  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 10:14:18.639  3253  3312 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 10:14:18.643  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,03-31 10:14:18.643  3253  3312 I jxcore-log: 
,03-31 10:14:18.646  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,03-31 10:14:18.646  3253  3312 I jxcore-log: 
,03-31 10:14:18.653  3253  3312 I jxcore-log: # 52. make sure terminateListener is properly hooked up
03-31 10:14:18.653  3253  3312 I jxcore-log: ,
,03-31 10:14:18.657  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
,03-31 10:14:18.657  3253  3312 I jxcore-log: 
,03-31 10:14:18.869  3253  3312 I jxcore-log: ok 208 called with right arguments
03-31 10:14:18.869  3253  3312 I jxcore-log: 
,03-31 10:14:18.872  3253  3312 I jxcore-log: # teardown
03-31 10:14:18.872  3253  3312 I jxcore-log: 
,03-31 10:14:19.694  3253  3312 I jxcore-log: ok 209 must be stopped
,03-31 10:14:19.694  3253  3312 I jxcore-log: 
,03-31 10:14:19.697  3253  3312 I jxcore-log: # setup
03-31 10:14:19.697  3253  3312 I jxcore-log: 
,03-31 10:14:20.371  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 10:14:20.371  3253  3312 I jxcore-log: 
,03-31 10:14:20.374  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 10:14:20.374  3253  3312 I jxcore-log: 
,03-31 10:14:20.381  3253  3312 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 10:14:20.381  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 10:14:20.381  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 10:14:20.381  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 10:14:20.381  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 10:14:20.381  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 10:14:20.381  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 10:14:20.381  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 10:14:20.386  3253  3312 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 10:14:20.387  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 10:14:20.387  3253  3312 I jxcore-log: 
,03-31 10:14:20.389  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 10:14:20.389  3253  3312 I jxcore-log: 
,03-31 10:14:20.392  3253  3312 I jxcore-log: # 53. make sure we actually call kill connections properly
03-31 10:14:20.392  3253  3312 I jxcore-log: 
,03-31 10:14:20.393  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 10:14:20.393  3253  3312 I jxcore-log: 
,03-31 10:14:20.552  3253  3312 I jxcore-log: ok 210 specific error expected
03-31 10:14:20.552  3253  3312 I jxcore-log: 
,03-31 10:14:20.555  3253  3312 I jxcore-log: # teardown
03-31 10:14:20.555  3253  3312 I jxcore-log: 
,03-31 10:14:21.134  3253  3312 I jxcore-log: ok 211 must be stopped
03-31 10:14:21.134  3253  3312 I jxcore-log: 
,03-31 10:14:21.137  3253  3312 I jxcore-log: # setup
03-31 10:14:21.137  3253  3312 I jxcore-log: 
,03-31 10:14:21.263  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 10:14:21.263  3253  3312 I jxcore-log: 
,03-31 10:14:21.266  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 10:14:21.266  3253  3312 I jxcore-log: 
,03-31 10:14:21.279  3253  3312 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 10:14:21.279  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 10:14:21.279  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 10:14:21.279  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 10:14:21.279  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 10:14:21.279  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 10:14:21.279  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 10:14:21.279  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 10:14:21.285  3253  3312 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 10:14:21.290  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 10:14:21.290  3253  3312 I jxcore-log: 
,03-31 10:14:21.296  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 10:14:21.296  3253  3312 I jxcore-log: 
,03-31 10:14:21.304  3253  3312 I jxcore-log: # 54. thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
03-31 10:14:21.304  3253  3312 I jxcore-log: 
,03-31 10:14:21.310  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 10:14:21.310  3253  3312 I jxcore-log: 
,03-31 10:14:21.772  1265  1265 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 10:14:21.842  1265  3209 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
03-31 10:14:21.843  1265  3209 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-31 10:14:21.843  1265  3209 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 10:14:21.843  1265  3209 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 10:14:21.856  1265  3209 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 10:14:21.899  4161  4161 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,03-31 10:14:21.901  4161  4161 D Finsky  : [1] 5.onFinished: Installation state replication failed.
,03-31 10:14:21.902  4161  4161 D Finsky  : [1] 5.onFinished: Scheduling replication attempt 4.
,03-31 10:14:22.231  3253  3312 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 10:14:22.231  3253  3312 I jxcore-log: 
,03-31 10:14:22.234  3253  3312 I jxcore-log: DEBUG createNativeListener: listening 41880
03-31 10:14:22.234  3253  3312 I jxcore-log: 
,03-31 10:14:22.241  3253  3312 I jxcore-log: INFO thaliMobileNativeWrapper: routerPortConnectionFailed - {"routerPort":56927,"error":{}}
03-31 10:14:22.241  3253  3312 I jxcore-log: 
03-31 10:14:22.242  3253  3312 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-31 10:14:22.242  3253  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 10:14:22.242  3253  3312 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 10:14:22.244  3253  3312 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-31 10:14:22.244  3253  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 10:14:22.244  3253  3312 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 10:14:22.255  3253  3312 I jxcore-log: ok 212 failure reason is as expected,
03-31 10:14:22.255  3253  3312 I jxcore-log: 
03-31 10:14:22.255  3253  3312 I jxcore-log: ok 213 error description is as expected
03-31 10:14:22.255  3253  3312 I jxcore-log: 
03-31 10:14:22.256  3253  3312 I jxcore-log: ok 214 must be stopped
03-31 10:14:22.256  3253  3312 I jxcore-log: 
,03-31 10:14:22.262  3253  3312 I jxcore-log: # teardown
03-31 10:14:22.262  3253  3312 I jxcore-log: 
,03-31 10:14:22.418  3253  3312 I jxcore-log: ok 215 must be stopped
03-31 10:14:22.418  3253  3312 I jxcore-log: 
,03-31 10:14:22.424  3253  3312 I jxcore-log: # setup
03-31 10:14:22.424  3253  3312 I jxcore-log: 
,03-31 10:14:23.165  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 10:14:23.165  3253  3312 I jxcore-log: 
,03-31 10:14:23.169  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 10:14:23.169  3253  3312 I jxcore-log: 
,03-31 10:14:23.180  3253  3312 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 10:14:23.180  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 10:14:23.180  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 10:14:23.180  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 10:14:23.180  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 10:14:23.180  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 10:14:23.180  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 10:14:23.180  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 10:14:23.184  3253  3312 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 10:14:23.186  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 10:14:23.186  3253  3312 I jxcore-log: 
,03-31 10:14:23.188  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 10:14:23.188  3253  3312 I jxcore-log: 
,03-31 10:14:23.192  3253  3312 I jxcore-log: # 55. We repeat failedConnection event when we get it from thaliTcpServersManager
03-31 10:14:23.192  3253  3312 I jxcore-log: 
,03-31 10:14:23.195  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 10:14:23.195  3253  3312 I jxcore-log: 
,03-31 10:14:23.419  3253  3312 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 10:14:23.419  3253  3312 I jxcore-log: 
,03-31 10:14:23.422  3253  3312 I jxcore-log: DEBUG createNativeListener: listening 38506
03-31 10:14:23.422  3253  3312 I jxcore-log: 
,03-31 10:14:23.426  3253  3312 I jxcore-log: ok 216 peerIdentifier matches
03-31 10:14:23.426  3253  3312 I jxcore-log: 
,03-31 10:14:23.427  3253  3312 I jxcore-log: ok 217 error description matches
03-31 10:14:23.427  3253  3312 I jxcore-log: 
,03-31 10:14:23.431  3253  3312 I jxcore-log: # teardown
03-31 10:14:23.431  3253  3312 I jxcore-log: 
,03-31 10:14:24.189  3253  3312 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-31 10:14:24.190  3253  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 10:14:24.190  3253  3312 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 10:14:24.194  3253  3312 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-31 10:14:24.194  3253  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 10:14:24.194  3253  3312 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 10:14:24.199  3253  3312 I jxcore-log: ok 218 must be stopped
03-31 10:14:24.199  3253  3312 I jxcore-log: 
,03-31 10:14:24.206  3253  3312 I jxcore-log: # setup
03-31 10:14:24.206  3253  3312 I jxcore-log: 
,03-31 10:14:24.314  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 10:14:24.314  3253  3312 I jxcore-log: 
,03-31 10:14:24.316  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 10:14:24.316  3253  3312 I jxcore-log: 
,03-31 10:14:24.324  3253  3312 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 10:14:24.324  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 10:14:24.324  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 10:14:24.324  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 10:14:24.324  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 10:14:24.324  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 10:14:24.324  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 10:14:24.324  3253  3312 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 10:14:24.328  3253  3312 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 10:14:24.332  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 10:14:24.332  3253  3312 I jxcore-log: 
,03-31 10:14:24.335  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 10:14:24.335  3253  3312 I jxcore-log: 
,03-31 10:14:24.357  3253  3312 I jxcore-log: # 56. we successfully receive and replay discoveryAdvertisingStateUpdate
03-31 10:14:24.357  3253  3312 I jxcore-log: 
,03-31 10:14:24.358  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 10:14:24.358  3253  3312 I jxcore-log: 
,03-31 10:14:24.578  3253  3312 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 10:14:24.578  3253  3312 I jxcore-log: 
,03-31 10:14:24.580  3253  3312 I jxcore-log: DEBUG createNativeListener: listening 59462
03-31 10:14:24.580  3253  3312 I jxcore-log: 
,03-31 10:14:24.585  3253  3312 I io.jxcore.node.ConnectionHelper: start: Port number: 42956, start advertisements: false
,03-31 10:14:24.585  3253  3312 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 10:14:24.585  3253  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-31 10:14:24.585  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-31 10:14:24.590  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-31 10:14:24.591  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 10:14:24.591  3253  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 10:14:24.596  2153  2170 D BtGatt.GattService: registerClient() - UUID=d8a45a75-5128-4d83-9d94-54e99f66c43a
,03-31 10:14:24.597  2153  2216 D BtGatt.GattService: onClientRegistered() - UUID=d8a45a75-5128-4d83-9d94-54e99f66c43a, clientIf=5
,03-31 10:14:24.597  3253  3268 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-31 10:14:24.598  2153  2171 D BtGatt.GattService: start scan with filters
,03-31 10:14:24.600  2153  2227 D BtGatt.ScanManager: handling starting scan
03-31 10:14:24.601  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-31 10:14:24.601  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-31 10:14:24.601  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,03-31 10:14:24.601  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING],
03-31 10:14:24.601  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 10:14:24.602  3253  3253 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-31 10:14:24.602  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-31 10:14:24.603   822  1412 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 10:14:24.608  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 10:14:24.608  2153  2216 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-31 10:14:24.608  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 10:14:24.609  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-31 10:14:24.610  3253  3253 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-31 10:14:24.610  3253  3253 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-31 10:14:24.610  3253  3253 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 10:14:24.610  2153  2216 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-31 10:14:24.610  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 10:14:24.611  2153  2227 D BtGatt.ScanManager: Starting BLE batch scan
,03-31 10:14:24.611  2153  2227 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-31 10:14:24.611  3253  3312 I io.jxcore.node.ConnectionHelper: start: OK
03-31 10:14:24.614  2153  2216 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-31 10:14:24.614  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 10:14:24.616  2153  2216 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-31 10:14:24.616  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 10:14:24.618  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 10:14:24.618  3253  3312 I jxcore-log: 
,03-31 10:14:24.621  3253  3312 I jxcore-log: ok 219 discoveryActive matches
03-31 10:14:24.621  3253  3312 I jxcore-log: 
,03-31 10:14:24.623  3253  3312 I jxcore-log: ok 220 advertisingActive matches
03-31 10:14:24.623  3253  3312 I jxcore-log: 
,03-31 10:14:24.626  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 10:14:24.626  3253  3312 I jxcore-log: 
,03-31 10:14:24.628  3253  3312 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 10:14:24.628  3253  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,03-31 10:14:24.628  3253  3312 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
03-31 10:14:24.628  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-31 10:14:24.629  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,03-31 10:14:24.629  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-31 10:14:24.629  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-31 10:14:24.629  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-31 10:14:24.629  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-31 10:14:24.632  2153  2171 D BtGatt.GattService: stopScan() - queue size =1
,03-31 10:14:24.635  2153  2216 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-31 10:14:24.635  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 10:14:24.636  2153  2227 D BtGatt.ScanManager: stopping BLe Batch
03-31 10:14:24.636  2153  2337 D BtGatt.GattService: unregisterClient() - clientIf=5
03-31 10:14:24.637  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 10:14:24.637  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 10:14:24.637  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,03-31 10:14:24.637  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-31 10:14:24.638  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-31 10:14:24.638  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 10:14:24.639  2153  2216 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,03-31 10:14:24.639  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 10:14:24.639  2153  2227 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-31 10:14:24.639  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-31 10:14:24.640  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-31 10:14:24.640  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-31 10:14:24.642  2153  2216 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,03-31 10:14:24.642  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
03-31 10:14:24.643  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-31 10:14:24.643  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 10:14:24.644  3253  3253 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 10:14:24.644  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 10:14:24.644  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-31 10:14:24.653  3253  3253 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
03-31 10:14:24.653   822   840 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 10:14:24.663  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
03-31 10:14:24.664  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-31 10:14:24.664  3253  3253 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-31 10:14:24.669  3253  3253 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false,
03-31 10:14:24.669  3253  3253 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 10:14:24.670  3253  3253 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 10:14:24.670  3253  3253 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 10:14:24.671  3253  3312 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-31 10:14:24.672  3253  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 10:14:24.672  3253  3312 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 10:14:24.674  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 10:14:24.674  3253  3312 I jxcore-log: 
,03-31 10:14:24.675  3253  3312 I jxcore-log: ok 221 discoveryActive matches
03-31 10:14:24.675  3253  3312 I jxcore-log: 
03-31 10:14:24.676  3253  3312 I jxcore-log: ok 222 advertisingActive matches
03-31 10:14:24.676  3253  3312 I jxcore-log: 
,03-31 10:14:24.679  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false},
03-31 10:14:24.679  3253  3312 I jxcore-log: 
,03-31 10:14:24.697  3253  3312 I jxcore-log: DEBUG createNativeListener: creating native server,
03-31 10:14:24.697  3253  3312 I jxcore-log: 
03-31 10:14:24.700  3253  3312 I jxcore-log: DEBUG createNativeListener: listening 46282
03-31 10:14:24.700  3253  3312 I jxcore-log: 
,03-31 10:14:24.706  3253  3312 I io.jxcore.node.ConnectionHelper: start: Port number: 46282, start advertisements: true
,03-31 10:14:24.706  3253  3312 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 10:14:24.706  3253  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-31 10:14:24.706  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-31 10:14:24.713  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
03-31 10:14:24.713  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-31 10:14:24.713  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 10:14:24.713  3253  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 10:14:24.720  2153  2171 D BtGatt.GattService: registerClient() - UUID=3ce40c6f-e320-4a9c-a7a0-fc8083fe9f37,
03-31 10:14:24.720  2153  2216 D BtGatt.GattService: onClientRegistered() - UUID=3ce40c6f-e320-4a9c-a7a0-fc8083fe9f37, clientIf=5
03-31 10:14:24.720  3253  3854 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-31 10:14:24.721  2153  2170 D BtGatt.GattService: start scan with filters
,03-31 10:14:24.724  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-31 10:14:24.724  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 10:14:24.724  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-31 10:14:24.724  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,03-31 10:14:24.724  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 10:14:24.724  2153  2227 D BtGatt.ScanManager: handling starting scan
03-31 10:14:24.725  3253  3253 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 10:14:24.725  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-31 10:14:24.725  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-31 10:14:24.725  3253  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-31 10:14:24.725  3253  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-31 10:14:24.725  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 10:14:24.725  3253  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-31 10:14:24.728  2153  2216 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-31 10:14:24.729  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 10:14:24.729  2153  2171 D BtGatt.GattService: registerClient() - UUID=033ba3b4-54ba-413a-9ccf-939dd7ad0c25
,03-31 10:14:24.730  2153  2216 D BtGatt.GattService: onClientRegistered() - UUID=033ba3b4-54ba-413a-9ccf-939dd7ad0c25, clientIf=6
03-31 10:14:24.730  3253  3268 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-31 10:14:24.731  2153  2216 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,03-31 10:14:24.731  2153  2226 D BtGatt.AdvertiseManager: message : 0
03-31 10:14:24.732  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 10:14:24.732  2153  2227 D BtGatt.ScanManager: Starting BLE batch scan
03-31 10:14:24.732  2153  2227 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-31 10:14:24.735  2153  2216 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,03-31 10:14:24.735  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 10:14:24.735  2153  2226 D BtGatt.AdvertiseManager: starting multi advertising,
03-31 10:14:24.738  2153  2216 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
03-31 10:14:24.740  2153  2216 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-31 10:14:24.740  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 10:14:24.743  2153  2216 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
03-31 10:14:24.745  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-31 10:14:24.745  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-31 10:14:24.745   822  1104 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-31 10:14:24.748  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-31 10:14:24.748  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-31 10:14:24.748  3253  3312 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-31 10:14:24.748  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 10:14:24.749  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-31 10:14:24.749  3253  3312 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-31 10:14:24.749  3253  3312 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-31 10:14:24.749  3253  3312 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-31 10:14:24.749  3253  3253 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,03-31 10:14:24.749  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-31 10:14:24.750  3253  3253 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,03-31 10:14:24.750  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-31 10:14:24.750  3253  3253 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-31 10:14:24.750  3253  3253 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
,03-31 10:14:24.750  3253  3253 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-31 10:14:24.750  3253  3253 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 10:14:24.750  3253  3253 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-31 10:14:24.750  3253  3253 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 10:14:24.750  3253  3253 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,03-31 10:14:24.750  3253  3253 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-31 10:14:24.750  3253  3312 I io.jxcore.node.ConnectionHelper: start: OK
03-31 10:14:24.751   822  3823 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-31 10:14:24.752  3253  4331 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-31 10:14:24.754  3253  4331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-31 10:14:24.755  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 10:14:24.755  3253  3312 I jxcore-log: 
,03-31 10:14:24.761  3253  3312 I jxcore-log: not ok 223 discoveryActive matches
03-31 10:14:24.761  3253  3312 I jxcore-log: 
,03-31 10:14:24.762  3253  3312 I jxcore-log:   ---
03-31 10:14:24.762  3253  3312 I jxcore-log: 
,03-31 10:14:24.762  3253  3312 I jxcore-log:     operator: equal
03-31 10:14:24.762  3253  3312 I jxcore-log: 
03-31 10:14:24.762  3253  3312 I jxcore-log:     expected: false
03-31 10:14:24.762  3253  3312 I jxcore-log: 
03-31 10:14:24.762  3253  3312 I jxcore-log:     actual:   true
03-31 10:14:24.762  3253  3312 I jxcore-log: 
03-31 10:14:24.762  3253  3312 I jxcore-log:   ...
03-31 10:14:24.762  3253  3312 I jxcore-log: 
,03-31 10:14:24.765  3253  3312 I jxcore-log: not ok 224 advertisingActive matches
03-31 10:14:24.765  3253  3312 I jxcore-log: 
03-31 10:14:24.765  3253  3312 I jxcore-log:   ---
03-31 10:14:24.765  3253  3312 I jxcore-log: 
03-31 10:14:24.765  3253  3312 I jxcore-log:     operator: equal
03-31 10:14:24.765  3253  3312 I jxcore-log: 
,03-31 10:14:24.765  3253  3312 I jxcore-log:     expected: true
03-31 10:14:24.765  3253  3312 I jxcore-log: 
03-31 10:14:24.765  3253  3312 I jxcore-log:     actual:   false
03-31 10:14:24.765  3253  3312 I jxcore-log: 
03-31 10:14:24.766  3253  3312 I jxcore-log:   ...
03-31 10:14:24.766  3253  3312 I jxcore-log: 
,03-31 10:14:24.767  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 10:14:24.767  3253  3312 I jxcore-log: 
,03-31 10:14:24.768  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-31 10:14:24.768  3253  3312 I jxcore-log: 
,03-31 10:14:24.771  3253  3312 I jxcore-log: not ok 225 discoveryActive matches
03-31 10:14:24.771  3253  3312 I jxcore-log: 
03-31 10:14:24.771  3253  3312 I jxcore-log:   ---
03-31 10:14:24.771  3253  3312 I jxcore-log: 
,03-31 10:14:24.771  3253  3312 I jxcore-log:     operator: equal
03-31 10:14:24.771  3253  3312 I jxcore-log: 
03-31 10:14:24.772  3253  3312 I jxcore-log:     expected: false
03-31 10:14:24.772  3253  3312 I jxcore-log: 
03-31 10:14:24.772  3253  3312 I jxcore-log:     actual:   true
03-31 10:14:24.772  3253  3312 I jxcore-log: 
,03-31 10:14:24.772  3253  3312 I jxcore-log:   ...
03-31 10:14:24.772  3253  3312 I jxcore-log: 
,03-31 10:14:24.774  3253  3312 I jxcore-log: not ok 226 advertisingActive matches
03-31 10:14:24.774  3253  3312 I jxcore-log: 
,03-31 10:14:24.775  3253  3312 I jxcore-log:   ---
03-31 10:14:24.775  3253  3312 I jxcore-log: 
03-31 10:14:24.775  3253  3312 I jxcore-log:     operator: equal
,03-31 10:14:24.775  3253  3312 I jxcore-log: 
03-31 10:14:24.775  3253  3312 I jxcore-log:     expected: false
03-31 10:14:24.775  3253  3312 I jxcore-log: 
03-31 10:14:24.775  3253  3312 I jxcore-log:     actual:   true
03-31 10:14:24.775  3253  3312 I jxcore-log: 
,03-31 10:14:24.775  3253  3312 I jxcore-log:   ...
03-31 10:14:24.775  3253  3312 I jxcore-log: 
03-31 10:14:24.777  3253  3312 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-31 10:14:24.777  3253  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
,03-31 10:14:24.777  3253  3312 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-31 10:14:24.777  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-31 10:14:24.777  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,03-31 10:14:24.778  3253  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-31 10:14:24.778  3253  4331 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-31 10:14:24.778  3253  4331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-31 10:14:24.778  3253  4331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,03-31 10:14:24.779  3253  3253 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-31 10:14:24.779  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-31 10:14:24.779  3253  3253 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-31 10:14:24.779  3253  3253 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-31 10:14:24.779  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-31 10:14:24.779  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-31 10:14:24.779  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,03-31 10:14:24.779  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-31 10:14:24.779  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-31 10:14:24.781  2153  2170 D BtGatt.GattService: stopScan() - queue size =1
03-31 10:14:24.782  2153  2337 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-31 10:14:24.782  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 10:14:24.782  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 10:14:24.782  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,03-31 10:14:24.782  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-31 10:14:24.782  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-31 10:14:24.782  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-31 10:14:24.782  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-31 10:14:24.783  2153  2216 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-31 10:14:24.783  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 10:14:24.783  2153  2227 D BtGatt.ScanManager: stopping BLe Batch
03-31 10:14:24.784  2153  2226 D BtGatt.AdvertiseManager: message : 1
03-31 10:14:24.785  2153  2226 D BtGatt.AdvertiseManager: stop advertise for client 6
03-31 10:14:24.786  2153  2216 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-31 10:14:24.786  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 10:14:24.786  2153  2227 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-31 10:14:24.788  2153  2216 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-31 10:14:24.788  2153  2216 D BtGatt.GattService: Client app is not null!
03-31 10:14:24.788  2153  2337 D BtGatt.GattService: unregisterClient() - clientIf=6
03-31 10:14:24.789  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-31 10:14:24.789  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-31 10:14:24.789  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-31 10:14:24.789  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-31 10:14:24.789  3253  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-31 10:14:24.789  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 10:14:24.789  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-31 10:14:24.789  3253  3312 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-31 10:14:24.790  3253  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-31 10:14:24.790  3253  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 10:14:24.790  2153  2216 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-31 10:14:24.790  2153  2216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 10:14:24.790  3253  3253 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 10:14:24.790  3253  3253 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 10:14:24.790  3253  3253 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 10:14:24.790  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 10:14:24.790  3253,  3253 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-31 10:14:24.796  3253  3253 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-31 10:14:24.797   822   840 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 10:14:24.798  3253  3312 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-31 10:14:24.798  3253  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 10:14:24.798  3253  3312 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 10:14:24.801  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-31 10:14:24.802  3253  3253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-31 10:14:24.802  3253  3253 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-31 10:14:24.804  3253  3253 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-31 10:14:24.804  3253  3253 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 10:14:24.805  3253  3253 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-31 10:14:24.807  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-31 10:14:24.807  3253  3312 I jxcore-log: 
,03-31 10:14:24.810  3253  3312 I jxcore-log: ok 227 discoveryActive matches
03-31 10:14:24.810  3253  3312 I jxcore-log: ,
,03-31 10:14:24.818  3253  3312 I jxcore-log: not ok 228 advertisingActive matches
03-31 10:14:24.818  3253  3312 I jxcore-log: 
,03-31 10:14:24.818  3253  3312 I jxcore-log:   ---
03-31 10:14:24.818  3253  3312 I jxcore-log: 
,03-31 10:14:24.819  3253  3312 I jxcore-log:     operator: equal
03-31 10:14:24.819  3253  3312 I jxcore-log: 
,03-31 10:14:24.819  3253  3312 I jxcore-log:     expected: false
03-31 10:14:24.819  3253  3312 I jxcore-log: 
03-31 10:14:24.820  3253  3312 I jxcore-log:     actual:   true
03-31 10:14:24.820  3253  3312 I jxcore-log: ,
03-31 10:14:24.820  3253  3312 I jxcore-log:   ...
03-31 10:14:24.820  3253  3312 I jxcore-log: 
03-31 10:14:24.825  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 10:14:24.825  3253  3312 I jxcore-log: 
,03-31 10:14:24.827  3253  3312 I jxcore-log: ok 229 discoveryActive matches
,03-31 10:14:24.827  3253  3312 I jxcore-log: 
03-31 10:14:24.829  3253  3312 I jxcore-log: ok 230 advertisingActive matches
03-31 10:14:24.829  3253  3312 I jxcore-log: 
03-31 10:14:24.833  3253  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 10:14:24.833  3253  3312 I jxcore-log: 
,03-31 10:14:24.845  3253  3312 I jxcore-log: DEBUG createNativeListener: creating native server
,03-31 10:14:24.845  3253  3312 I jxcore-log: 
,03-31 10:14:24.848  3253  3312 I jxcore-log: DEBUG createNativeListener: listening 53733
03-31 10:14:24.848  3253  3312 I jxcore-log: 
,03-31 10:14:24.856  3253  3312 I jxcore-log: Uncaught Promise Rejection: {},
03-31 10:14:24.856  3253  3312 I jxcore-log: 
,03-31 10:14:24.860  3253  3312 E jxcore-log: Trace: [Error: Call Stop!]
03-31 10:14:24.860  3253  3312 E jxcore-log:     at $3.prototype.trace@console.js:139:8
03-31 10:14:24.860  3253  3312 E jxcore-log:     at @/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:38:3
03-31 10:14:24.860  3253  3312 E jxcore-log:     at emit@events.js:98:1
,03-31 10:14:24.860  3253  3312 E jxcore-log:     at handlers.reject/<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/thali/node_modules/lie/lib/index.js:128:11
03-31 10:14:24.860  3253  3312 E jxcore-log:     at nextTick@/data/data/com.test.thalitest/files/www/jxcore/node_modules/immediate/lib/index.js:61:7
03-31 10:14:24.860  3253  3312 E jxcore-log:     at $0a@node.js:917:1
03-31 10:14:24.860  3253  3312 E jxcore-log: 
03-31 10:14:24.860  3253  3312 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
03-31 10:14:24.860  3253  3312 I jxcore-log: 
,03-31 10:14:24.863  3253  3312 I jxcore-log: # teardown
03-31 10:14:24.863  3253  3312 I jxcore-log: 
,03-31 10:14:25.175  4332  4332 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,03-31 10:14:25.178  4332  4332 D AndroidRuntime: CheckJNI is OFF,
,03-31 10:14:25.286  4332  4332 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,03-31 10:14:25.299   822   857 I ActivityManager: Force stopping com.test.thalitest appid=10095 user=-1: uninstall pkg
03-31 10:14:25.299   822   857 I ActivityManager: Killing 3253:com.test.thalitest/u0a95 (adj 0): stop com.test.thalitest
,03-31 10:14:25.377   822   867 W PackageSettings: Skipping PackageSetting{33f802a com.example.hello/10273} due to missing metadata,
,03-31 10:14:25.419   822  1003 W InputDispatcher: channel '2a25d40d com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
03-31 10:14:25.419   822  1003 E InputDispatcher: channel '2a25d40d com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
03-31 10:14:25.419   822  1410 I WindowState: WIN DEATH: Window{2a25d40d u0 com.test.thalitest/com.test.thalitest.MainActivity}
03-31 10:14:25.419   822  1410 W InputDispatcher: Attempted to unregister already unregistered input channel '2a25d40d com.test.thalitest/com.test.thalitest.MainActivity (server)'
,03-31 10:14:25.423   822  1014 D WifiService: Client connection lost with reason: 4
,03-31 10:14:25.507   822   857 W ActivityManager: Force removing ActivityRecord{d3fa267 u0 com.test.thalitest/.MainActivity t17}: app died, no saved state
,03-31 10:14:25.522   822   822 V ActivityManager: Display changed displayId=0
,03-31 10:14:25.547   822  1384 W ActivityManager: Spurious death for ProcessRecord{1448042f 3253:com.test.thalitest/u0a95}, curProc for 3253: null
03-31 10:14:25.548   822   867 I ActivityManager: Force stopping com.test.thalitest appid=10095 user=0: pkg removed
,03-31 10:14:25.567  1237  1237 I Keyboard.Facilitator: resetDictionaries() : en_US
,03-31 10:14:25.572  1237  4347 I Keyboard.Facilitator.DecoderInitializer: run()
,03-31 10:14:25.575  1237  4347 I Decoder : createOrResetDecoder
,03-31 10:14:25.576   822  1004 I InputReader: Reconfiguring input devices.  changes=0x00000010
,03-31 10:14:25.578   822  1049 D TaskPersister: removeObsoleteFile: deleting file=17_task.xml
,03-31 10:14:25.586  2964  2964 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,03-31 10:14:25.617  1265  1265 I ConfigService: onCreate
,03-31 10:14:25.622  1070  1070 I art     : Explicit concurrent mark sweep GC freed 52550(2MB) AllocSpace objects, 1(30MB) LOS objects, 20% free, 62MB/78MB, paused 1.058ms total 63.325ms
,03-31 10:14:25.639  3937  4350 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,03-31 10:14:25.645  1237  4347 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,03-31 10:14:25.649   822   822 I art     : Explicit concurrent mark sweep GC freed 17261(1288KB) AllocSpace objects, 2(32KB) LOS objects, 32% free, 33MB/49MB, paused 2.454ms total 92.538ms
03-31 10:14:25.649   822   867 I art     : WaitForGcToComplete blocked for 26.107ms for cause Explicit
,03-31 10:14:25.663   822  3823 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3253 uid 10095
,03-31 10:14:25.666   822  1104 I ActivityManager: Start proc 4351:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,03-31 10:14:25.669  1237  1237 I Keyboard.Facilitator: onFinishInput()
,03-31 10:14:25.700  1237  4347 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
03-31 10:14:25.702  1237  4347 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
03-31 10:14:25.702  1237  4347 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,03-31 10:14:25.704  1237  4347 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
03-31 10:14:25.704  1237  4347 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,03-31 10:14:25.705  1237  4347 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
03-31 10:14:25.705  1237  4347 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
03-31 10:14:25.706  1237  4347 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
03-31 10:14:25.706  1237  4347 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
03-31 10:14:25.706  1237  4347 I Keyboard.Facilitator.Delight2FileSweeper: run()
03-31 10:14:25.706  1237  4347 I Keyboard.Facilitator.RecurringTaskScheduler: run()
03-31 10:14:25.706  1237  4347 I StatsUtilsManager: startPeriodStatsRecorder() : Success
03-31 10:14:25.706  1237  4347 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,03-31 10:14:25.716  1383  1383 I art     : Explicit concurrent mark sweep GC freed 4974(363KB) AllocSpace objects, 12(1408KB) LOS objects, 31% free, 35MB/51MB, paused 690us total 19.247ms
,03-31 10:14:25.721   822  1410 I ActivityManager: Start proc 4371:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,03-31 10:14:25.747   822   822 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
03-31 10:14:25.747   822   822 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,03-31 10:14:25.765  4371  4371 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
,03-31 10:14:25.778  1265  1265 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
03-31 10:14:25.778  1265  1265 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,03-31 10:14:25.789  1383  1383 D Launcher.Workspace: 11683562 - stripEmptyScreens()
03-31 10:14:25.790  1383  1383 D Launcher.Workspace: 11683562 - stripEmptyScreens()
,03-31 10:14:25.800   822  1410 I ActivityManager: Killing 2381:com.google.android.calendar/u0a37 (adj 15): empty #17
,03-31 10:14:25.816   822   867 I art     : Explicit concurrent mark sweep GC freed 8651(782KB) AllocSpace objects, 1(16KB) LOS objects, 32% free, 33MB/49MB, paused 1.517ms total 165.551ms
,03-31 10:14:25.869  4332  4332 I art     : System.exit called, status: 0
03-31 10:14:25.869  4332  4332 I AndroidRuntime: VM exiting with result code 0.
,03-31 10:14:26.072   822   867 I ActivityManager: Start proc 4405:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,03-31 10:14:26.088  1804  4415 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,03-31 10:14:26.089  1804  1804 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
03-31 10:14:26.089  1804  1804 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,03-31 10:14:26.091  1804  4415 D AccountUtils: Clearing selected account for com.test.thalitest
,03-31 10:14:26.112  1804  1804 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
03-31 10:14:26.112  1804  1804 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,03-31 10:14:26.125  1804  4415 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,03-31 10:14:26.150  4281  4281 W LocationOracleImpl: Best location was null
03-31 10:14:26.151  1804  4425 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,03-31 10:14:26.153  1804  4426 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
03-31 10:14:26.154  1804  4426 E DriveAsyncService: disk I/O error (code 3850)
03-31 10:14:26.154  1804  4426 E DriveAsyncService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-31 10:14:26.154  1804  4426 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-31 10:14:26.154  1804  4426 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-31 10:14:26.154  1804  4426 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-31 10:14:26.154  1804  4426 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-31 10:14:26.154  1804  4426 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-31 10:14:26.154  1804  4426 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-31 10:14:26.154  1804  4426 E DriveAsyncService: 	at com.google.android.gms.drive.database.k.l(SourceFile:596)
03-31 10:14:26.154  1804  4426 E DriveAsyncService: 	at com.google.android.gms.drive.database.k.b(SourceFile:570)
03-31 10:14:26.154  1804  4426 E DriveAsyncService: 	at com.google.android.gms.drive.database.f.h(SourceFile:1473)
03-31 10:14:26.154  1804  4426 E DriveAsyncService: 	at com.google.android.gms.drive.api.a.bc.a(SourceFile:16)
03-31 10:14:26.154  1804  4426 E DriveAsyncService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-31 10:14:26.154  1804  4426 E DriveAsyncService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 10:14:26.154  1804  4426 E DriveAsyncService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 10:14:26.154  1804  4426 E DriveAsyncService: 	at java.lang.Thread.run(Thread.java:818)
,03-31 10:14:26.155  4281  4434 E Search.SharedPreferencesProto: Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
03-31 10:14:26.155  1804  4415 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
03-31 10:14:26.155  1804  4415 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-31 10:14:26.155  1804  4415 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-31 10:14:26.155  1804  4415 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-31 10:14:26.155  1804  4415 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-31 10:14:26.155  1804  4415 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-31 10:14:26.155  1804  4415 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-31 10:14:26.155  1804  4415 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-31 10:14:26.155  1804  4415 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-31 10:14:26.155  1804  4415 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-31 10:14:26.155  1804  4415 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-31 10:14:26.155  1804  4415 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-31 10:14:26.155  1804  4415 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-31 10:14:26.155  1804  4415 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-31 10:14:26.155  1804  4415 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-31 10:14:26.155  1804  4415 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
03-31 10:14:26.155  1804  4415 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
03-31 10:14:26.155  1804  4415 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-31 10:14:26.155  1804  4415 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-31 10:14:26.155  1804  4415 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
03-31 10:14:26.155  1804  4415 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-31 10:14:26.156  1804  4415 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
03-31 10:14:26.156  1804  4415 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-31 10:14:26.156  1804  4415 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-31 10:14:26.156  1804  4415 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-31 10:14:26.156  1804  4415 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-31 10:14:26.156  1804  4415 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-31 10:14:26.156  1804  4415 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-31 10:14:26.156  1804  4415 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-31 10:14:26.156  1804  4415 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInn,er(SQLiteDatabase.java:806)
03-31 10:14:26.156  1804  4415 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-31 10:14:26.156  1804  4415 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-31 10:14:26.156  1804  4415 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-31 10:14:26.156  1804  4415 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-31 10:14:26.156  1804  4415 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-31 10:14:26.156  1804  4415 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-31 10:14:26.156  1804  4415 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
03-31 10:14:26.156  1804  4415 E SQLiteOpenHelper: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
03-31 10:14:26.156  1804  4415 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-31 10:14:26.156  1804  4415 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-31 10:14:26.156  1804  4415 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:135)
03-31 10:14:26.156  1804  4415 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-31 10:14:26.162  4281  4281 I VS.Container: create_recognizer
03-31 10:14:26.162  1804  4415 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
03-31 10:14:26.163  1804  4427 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
03-31 10:14:26.163  1804  4427 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-31 10:14:26.163  1804  4427 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-31 10:14:26.163  1804  4427 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-31 10:14:26.163  1804  4427 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-31 10:14:26.163  1804  4427 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-31 10:14:26.163  1804  4427 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-31 10:14:26.163  1804  4427 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-31 10:14:26.163  1804  4427 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-31 10:14:26.163  1804  4427 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-31 10:14:26.163  1804  4427 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-31 10:14:26.163  1804  4427 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-31 10:14:26.163  1804  4427 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-31 10:14:26.163  1804  4427 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-31 10:14:26.163  1804  4427 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
03-31 10:14:26.163  1804  4427 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
03-31 10:14:26.163  1804  4427 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
03-31 10:14:26.163  1804  4427 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
03-31 10:14:26.163  1804  4427 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
03-31 10:14:26.163  1804  4427 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-31 10:14:26.163  1804  4427 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-31 10:14:26.163  1804  4427 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
03-31 10:14:26.163  1804  4427 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-31 10:14:26.163  1804  4427 E SQLiteOpenHelper: Couldn't open metrics.db for writing (will try read-only):
03-31 10:14:26.163  1804  4427 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-31 10:14:26.163  1804  4427 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-31 10:14:26.163  1804  4427 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-31 10:14:26.163  1804  4427 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-31 10:14:26.163  1804  4427 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-31 10:14:26.163  1804  4427 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-31 10:14:26.163  1804  4427 E SQLiteOpenHelper: ,	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-31 10:14:26.163  1804  4427 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-31 10:14:26.163  1804  4427 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-31 10:14:26.163  1804  4427 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-31 10:14:26.163  1804  4427 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-31 10:14:26.163  1804  4427 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-31 10:14:26.163  1804  4427 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-31 10:14:26.163  1804  4427 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
03-31 10:14:26.163  1804  4427 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
03-31 10:14:26.163  1804  4427 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
03-31 10:14:26.163  1804  4427 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
03-31 10:14:26.163  1804  4427 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
03-31 10:14:26.163  1804  4427 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-31 10:14:26.163  1804  4427 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-31 10:14:26.163  1804  4427 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:135)
03-31 10:14:26.163  1804  4427 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,--------- beginning of crash
03-31 10:14:26.180  1804  4425 E AndroidRuntime: FATAL EXCEPTION: PlayGamesAsyncThread1
03-31 10:14:26.180  1804  4425 E AndroidRuntime: Process: com.google.android.gms, PID: 1804
03-31 10:14:26.180  1804  4425 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-31 10:14:26.180  1804  4425 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-31 10:14:26.180  1804  4425 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-31 10:14:26.180  1804  4425 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-31 10:14:26.180  1804  4425 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-31 10:14:26.180  1804  4425 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-31 10:14:26.180  1804  4425 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
03-31 10:14:26.180  1804  4425 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
03-31 10:14:26.180  1804  4425 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
03-31 10:14:26.180  1804  4425 E AndroidRuntime: 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
03-31 10:14:26.180  1804  4425 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
03-31 10:14:26.180  1804  4425 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
03-31 10:14:26.180  1804  4425 E AndroidRuntime: 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3044)
03-31 10:14:26.180  1804  4425 E AndroidRuntime: 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
03-31 10:14:26.180  1804  4425 E AndroidRuntime: 	at com.google.android.gms.games.service.PlayGamesAsyncService$OperationAdapter.execute(PlayGamesAsyncService.java:920)
03-31 10:14:26.180  1804  4425 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
03-31 10:14:26.180  1804  4425 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 10:14:26.180  1804  4425 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 10:14:26.180  1804  4425 E AndroidRuntime: 	at java.lang.Thread.run(Thread.java:818)
,03-31 10:14:26.186   822   857 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-31 10:14:26.186   822   857 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
03-31 10:14:26.187   822  4438 E DropBoxManagerService: Can't write: system_app_crash
03-31 10:14:26.187   822  4438 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop97.tmp: open failed: EROFS (Read-only file system)
03-31 10:14:26.187   822  4438 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-31 10:14:26.187   822  4438 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-31 10:14:26.187   822  4438 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-31 10:14:26.187   822  4438 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-31 10:14:26.187   822  4438 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-31 10:14:26.187   822  4438 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
03-31 10:14:26.187   822  4438 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-31 10:14:26.187   822  4438 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-31 10:14:26.187   822  4438 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-31 10:14:26.187   822  4438 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-31 10:14:26.187   822  4438 E DropBoxManagerService: 	... 5 more
,03-31 10:14:26.192  4281  4393 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.googlequicksearchbox/databases/jar_store.db'.
03-31 10:14:26.192  4281  4393 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-31 10:14:26.192  4281  4393 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-31 10:14:26.192  4281  4393 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-31 10:14:26.192  4281  4393 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-31 10:14:26.192  4281  4393 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-31 10:14:26.192  4281  4393 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-31 10:14:26.192  4281  4393 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-31 10:14:26.192  4281  4393 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-31 10:14:26.192  4281  4393 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-31 10:14:26.192  4281  4393 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-31 10:14:26.192  4281  4393 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-31 10:14:26.192  4281  4393 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-31 10:14:26.192  4281  4393 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-31 10:14:26.192  4281  4393 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
03-31 10:14:26.192  4281  4393 E SQLiteDatabase: 	at com.google.android.apps.gsa.velour.k.pj(JarStore.java:893)
03-31 10:14:26.192  4281  4393 E SQLiteDatabase: 	at com.google.android.apps.gsa.velour.g.pe(JarStore.java:1036)
03-31 10:14:26.192  4281  4393 E SQLiteDatabase: 	at com.google.android.apps.gsa.velour.f.pb(JarStore.java:173)
03-31 10:14:26.192  4281  4393 E SQLiteDatabase: 	at com.google.android.apps.gsa.velour.r.gF(VelourReleaseState.java:325)
03-31 10:14:26.192  4281  4393 E SQLiteDatabase: 	at com.google.android.apps.gsa.velour.r.zd(VelourReleaseState.java:128)
03-31 10:14:26.192  4281  4393 E SQLiteDatabase: 	at com.google.android.apps.gsa.velour.r.aJp(VelourReleaseState.java:202)
03-31 10:14:26.192  4281  4393 E SQLiteDatabase: 	at com.google.android.apps.gsa.velour.r.a(VelourReleaseState.java:44)
03-31 10:14:26.192  4281  4393 E SQLiteDatabase: 	at com.google.android.apps.gsa.velour.s.iq(VelourReleaseState.java:371)
03-31 10:14:26.192  4281  4393 E SQLiteDatabase: 	at com.google.android.apps.gsa.shared.velour.j.auD(JarObjectLoader.java:185)
03-31 10:14:26.192  4281  4393 E SQLiteDatabase: 	at com.google.android.apps.gsa.shared.velour.j.call(JarObjectLoader.java:137)
03-31 10:14:26.192  4281  4393 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-31 10:14:26.192  4281  4393 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 10:14:26.192  4281  4393 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 10:14:26.192  4281  4393 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-31 10:14:26.192  4281  4393 E SQLiteDatabase: 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
03-31 10:14:26.192  4281  4393 E SQLiteOpenHelper: Couldn't open jar_store.db for writing (will try read-only):
03-31 10:14:26.192  4281  4393 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database ,in read/write mode.
03-31 10:14:26.192  4281  4393 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-31 10:14:26.192  4281  4393 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-31 10:14:26.192  4281  4393 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-31 10:14:26.192  4281  4393 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-31 10:14:26.192  4281  4393 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-31 10:14:26.192  4281  4393 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-31 10:14:26.192  4281  4393 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-31 10:14:26.192  4281  4393 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-31 10:14:26.192  4281  4393 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-31 10:14:26.192  4281  4393 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-31 10:14:26.192  4281  4393 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-31 10:14:26.192  4281  4393 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-31 10:14:26.192  4281  4393 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
03-31 10:14:26.192  4281  4393 E SQLiteOpenHelper: 	at com.google.android.apps.gsa.velour.k.pj(JarStore.java:893)
03-31 10:14:26.192  4281  4393 E SQLiteOpenHelper: 	at com.google.android.apps.gsa.velour.g.pe(JarStore.java:1036)
03-31 10:14:26.192  4281  4393 E SQLiteOpenHelper: 	at com.google.android.apps.gsa.velour.f.pb(JarStore.java:173)
03-31 10:14:26.192  4281  4393 E SQLiteOpenHelper: 	at com.google.android.apps.gsa.velour.r.gF(VelourReleaseState.java:325)
03-31 10:14:26.192  4281  4393 E SQLiteOpenHelper: 	at com.google.android.apps.gsa.velour.r.zd(VelourReleaseState.java:128)
03-31 10:14:26.192  4281  4393 E SQLiteOpenHelper: 	at com.google.android.apps.gsa.velour.r.aJp(VelourReleaseState.java:202)
03-31 10:14:26.192  4281  4393 E SQLiteOpenHelper: 	at com.google.android.apps.gsa.velour.r.a(VelourReleaseState.java:44)
03-31 10:14:26.192  4281  4393 E SQLiteOpenHelper: 	at com.google.android.apps.gsa.velour.s.iq(VelourReleaseState.java:371)
03-31 10:14:26.192  4281  4393 E SQLiteOpenHelper: 	at com.google.android.apps.gsa.shared.velour.j.auD(JarObjectLoader.java:185)
03-31 10:14:26.192  4281  4393 E SQLiteOpenHelper: 	at com.google.android.apps.gsa.shared.velour.j.call(JarObjectLoader.java:137)
03-31 10:14:26.192  4281  4393 E SQLiteOpenHelper: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-31 10:14:26.192  4281  4393 E SQLiteOpenHelper: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 10:14:26.192  4281  4393 E SQLiteOpenHelper: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 10:14:26.192  4281  4393 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
03-31 10:14:26.192  4281  4393 E SQLiteOpenHelper: 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
03-31 10:14:26.194  4281  4393 W SQLiteOpenHelper: Opened jar_store.db in read-only mode
,03-31 10:14:26.202  1265  2559 I art     : Explicit concurrent mark sweep GC freed 27212(1466KB) AllocSpace objects, 5(362KB) LOS objects, 38% free, 25MB/41MB, paused 1.409ms total 32.129ms
,03-31 10:14:26.207   822  4439 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
03-31 10:14:26.207  1804  4427 W SQLiteOpenHelper: Opened metrics.db in read-only mode
03-31 10:14:26.207  1804  4427 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,03-31 10:14:26.207  1804  4427 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
03-31 10:14:26.207   822   857 D Atlas   : Validating map...
03-31 10:14:26.208  1804  4427 E SQLiteLog: (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
03-31 10:14:26.208  1804  4427 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
03-31 10:14:26.208  1804  4427 I Process : Sending signal. PID: 1804 SIG: 9
,03-31 10:14:26.213   255   255 E lowmemorykiller: Error writing /proc/1804/oom_score_adj; errno=22
,03-31 10:14:26.214   822  1410 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
03-31 10:14:26.214   822  1410 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigFetchService in 1000ms
,03-31 10:14:26.234   822  4439 I OpenGLRenderer: Initialized EGL, version 1.4
,03-31 10:14:26.241   822  4439 D OpenGLRenderer: Enabling debug mode 0
,03-31 10:14:26.270  1383  1383 W Launcher: setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@18f80d81 new=com.google.android.velvet.VelvetApplication@18f80d81
,03-31 10:14:26.279  4281  4449 I HotwordRecognitionRnr: Starting hotword detection.
,03-31 10:14:26.285   822  1014 D WifiService: Client connection lost with reason: 4
03-31 10:14:26.285  4281  4450 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.u@2627df2c
,03-31 10:14:26.291   357  1032 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,03-31 10:14:26.291   357  4454 I AudioFlinger: AudioFlinger's thread 0xb4d2c000 ready to run
,03-31 10:14:26.293  4281  4450 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.u@2627df2c
,03-31 10:14:26.295  1383  1564 E SQLiteLog: (3850) statement aborts at 24: [DELETE FROM shortcut_and_widget_previews WHERE name LIKE ? OR name LIKE ?] disk I/O error
,03-31 10:14:26.301   822  1454 I ActivityManager: Start proc 4456:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,03-31 10:14:26.302   357  4454 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
03-31 10:14:26.302   357  4454 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
03-31 10:14:26.302   357  4454 E ACDB-LOADER: Error: ACDB AudProc vol returned = -19
03-31 10:14:26.302   357  4454 D audio_hw_primary: enable_snd_device: snd_device(55: voice-rec-mic)
,03-31 10:14:26.311  4281  4445 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/data/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
03-31 10:14:26.311  4281  4445 E AndroidRuntime: FATAL EXCEPTION: IntentService[UpdateCorporaService]
03-31 10:14:26.311  4281  4445 E AndroidRuntime: Process: com.google.android.googlequicksearchbox:search, PID: 4281
03-31 10:14:26.311  4281  4445 E AndroidRuntime: java.lang.RuntimeException: java.util.concurrent.ExecutionException: com.google.android.libraries.velour.dynloader.h: Failed to load JAR icingsync
03-31 10:14:26.311  4281  4445 E AndroidRuntime: 	at com.google.android.apps.gsa.shared.e.j.e(ExtraDexRegistry.java:108)
03-31 10:14:26.311  4281  4445 E AndroidRuntime: 	at com.google.android.apps.gsa.shared.e.j.c(ExtraDexRegistry.java:214)
03-31 10:14:26.311  4281  4445 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.bb(UpdateIcingCorporaService.java:232)
03-31 10:14:26.311  4281  4445 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:205)
03-31 10:14:26.311  4281  4445 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-31 10:14:26.311  4281  4445 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-31 10:14:26.311  4281  4445 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
03-31 10:14:26.311  4281  4445 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-31 10:14:26.311  4281  4445 E AndroidRuntime: Caused by: java.util.concurrent.ExecutionException: com.google.android.libraries.velour.dynloader.h: Failed to load JAR icingsync
03-31 10:14:26.311  4281  4445 E AndroidRuntime: 	at java.util.concurrent.FutureTask.report(FutureTask.java:93)
03-31 10:14:26.311  4281  4445 E AndroidRuntime: 	at java.util.concurrent.FutureTask.get(FutureTask.java:163)
03-31 10:14:26.311  4281  4445 E AndroidRuntime: 	at com.google.android.apps.gsa.shared.util.c.d.get(LazyListenableFuture.java:124)
03-31 10:14:26.311  4281  4445 E AndroidRuntime: 	at com.google.android.apps.gsa.shared.e.j.e(ExtraDexRegistry.java:94)
03-31 10:14:26.311  4281  4445 E AndroidRuntime: 	... 7 more
03-31 10:14:26.311  4281  4445 E AndroidRuntime: Caused by: com.google.android.libraries.velour.dynloader.h: Failed to load JAR icingsync
03-31 10:14:26.311  4281  4445 E AndroidRuntime: 	at com.google.android.libraries.velour.dynloader.i.bjO(JarLoader.java:216)
03-31 10:14:26.311  4281  4445 E AndroidRuntime: 	at com.google.android.apps.gsa.shared.e.k.auz(ExtraDexRegistry.java:344)
03-31 10:14:26.311  4281  4445 E AndroidRuntime: 	at com.google.android.apps.gsa.shared.e.k.a(ExtraDexRegistry.java:303)
03-31 10:14:26.311  4281  4445 E AndroidRuntime: 	at com.google.android.apps.gsa.shared.e.k$1.auD(ExtraDexRegistry.java:323)
03-31 10:14:26.311  4281  4445 E AndroidRuntime: 	at com.google.android.apps.gsa.shared.e.k$1.call(ExtraDexRegistry.java:318)
03-31 10:14:26.311  4281  4445 E AndroidRuntime: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-31 10:14:26.311  4281  4445 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 10:14:26.311  4281  4445 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 10:14:26.311  4281  4445 E AndroidRuntime: 	at java.lang.Thread.run(Thread.java:818)
03-31 10:14:26.311  4281  4445 E AndroidRuntime: 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
03-31 10:14:26.311  4281  4445 E AndroidRuntime: Caused by: java.io.IOException: open failed: EROFS (Read-only file system)
03-31 10:14:26.311  4281  4445 E AndroidRuntime: 	at java.io.File.createNewFile(File.java:941)
03-31 10:14:26.311  4281  4445 E AndroidRuntime: 	at com.google.android.libraries.velour.dynloader.i.bjP(JarLoader.java:278)
03-31 10:14:26.311 , 4281  4445 E AndroidRuntime: 	at com.google.android.libraries.velour.dynloader.i.bjO(JarLoader.java:207)
03-31 10:14:26.311  4281  4445 E AndroidRuntime: 	... 9 more
03-31 10:14:26.311  4281  4445 E AndroidRuntime: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-31 10:14:26.311  4281  4445 E AndroidRuntime: 	at libcore.io.Posix.open(Native Method)
03-31 10:14:26.311  4281  4445 E AndroidRuntime: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-31 10:14:26.311  4281  4445 E AndroidRuntime: 	at java.io.File.createNewFile(File.java:934)
03-31 10:14:26.311  4281  4445 E AndroidRuntime: 	... 11 more
,03-31 10:14:26.315   357  4454 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,03-31 10:14:26.341   822  1104 I ActivityManager: Start proc 4474:com.google.android.apps.docs/u0a46 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
,03-31 10:14:26.342   822  1410 I ActivityManager: Process com.google.android.gms (pid 1804) has died
03-31 10:14:26.342   822  1410 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 10872ms
03-31 10:14:26.342   822  1410 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 10872ms
,03-31 10:14:26.342   822  1410 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 10872ms
03-31 10:14:26.342   822  1410 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 10871ms
03-31 10:14:26.342   822  1410 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 10871ms
03-31 10:14:26.342   822  1410 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 20871ms
,03-31 10:14:26.349   822  4484 E DropBoxManagerService: Can't write: system_app_crash
03-31 10:14:26.349   822  4484 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop101.tmp: open failed: EROFS (Read-only file system)
03-31 10:14:26.349   822  4484 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-31 10:14:26.349   822  4484 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-31 10:14:26.349   822  4484 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-31 10:14:26.349   822  4484 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-31 10:14:26.349   822  4484 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-31 10:14:26.349   822  4484 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
03-31 10:14:26.349   822  4484 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-31 10:14:26.349   822  4484 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-31 10:14:26.349   822  4484 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-31 10:14:26.349   822  4484 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-31 10:14:26.349   822  4484 E DropBoxManagerService: 	... 5 more
,03-31 10:14:26.365  4281  4433 W FileUtils: Failed to chmod(/data/data/com.google.android.googlequicksearchbox/files): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
03-31 10:14:26.365  4281  4433 E FileBytesWriter: Failed to write new file: loracle.new
,03-31 10:14:26.368  4281  4492 E Search.SharedPreferencesProto: Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,03-31 10:14:26.389  4281  4281 I HotwordWorker: onReady

```
