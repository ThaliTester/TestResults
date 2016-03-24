#### Test 639107048b8fbc2_thali08_motorola-Nexus 6 Logs


```
--------- beginning of system
03-24 17:38:43.901   823   864 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,--------- beginning of main
03-24 17:38:43.925   823   864 I Adreno  : EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
03-24 17:38:43.962   259   275 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (309 us)
03-24 17:38:44.105  2157  2223 D HeadsetStateMachine: Disconnected process message: 10, size: 0
03-24 17:38:44.164  3256  3256 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
03-24 17:38:44.167  3256  3256 D AndroidRuntime: CheckJNI is OFF
03-24 17:38:44.292  3256  3256 D AndroidRuntime: Calling main entry com.android.commands.am.Am
03-24 17:38:44.307   823   839 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
03-24 17:38:44.323   823   839 V WindowManager: addAppToken: AppWindowToken{1f8ed101 token=Token{16506e8 ActivityRecord{3452580b u0 com.test.thalitest/.MainActivity t17}}} to stack=1 task=17 at 0
03-24 17:38:44.326  3256  3256 D AndroidRuntime: Shutting down VM
03-24 17:38:44.346  1538  1804 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.u@ff2ead1
03-24 17:38:44.347  1538  1538 I HotwordDetector: Closing mic
03-24 17:38:44.349   823   862 V WindowManager: Adding window Window{a6fcb00 u0 Starting com.test.thalitest} at 2 of 7 (after Window{33a232f5 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
03-24 17:38:44.383   823  1404 I ActivityManager: Start proc 3273:com.test.thalitest/u0a95 for activity com.test.thalitest/.MainActivity
03-24 17:38:44.404   359  1810 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
03-24 17:38:44.407   359  1810 D audio_hw_primary: disable_snd_device: snd_device(55: voice-rec-mic)
03-24 17:38:44.413   359  1036 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
03-24 17:38:44.415  1538  1807 I HotwordRecognitionRnr: Hotword detection finished
03-24 17:38:44.416  1538  1805 I HotwordRecognitionRnr: Stopping hotword detection.
03-24 17:38:44.454   823  1413 I ActivityManager: Killing 2884:com.google.android.apps.messaging/u0a75 (adj 15): empty #17
03-24 17:38:44.508   823  1413 I ActivityManager: Killing 2715:com.google.android.apps.fitness/u0a51 (adj 15): empty #18
03-24 17:38:44.531   823  1283 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1659516179
03-24 17:38:44.531   823  1283 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
03-24 17:38:44.534   823   862 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
03-24 17:38:44.535   823   823 V ActivityManager: Display changed displayId=0
03-24 17:38:44.538   259   259 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6082000
03-24 17:38:44.538   259   259 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,03-24 17:38:44.615   874   874 I kickstart: STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
,03-24 17:38:44.616   874   874 I kickstart: STATUS: Wrote to /sys/power/wake_lock
,03-24 17:38:44.643   874   874 E kickstart: ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2
,03-24 17:38:44.644   874   874 I kickstart: STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2' for writing
,03-24 17:38:44.698  3273  3273 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,03-24 17:38:44.714  3273  3273 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 3666-3670)
,03-24 17:38:44.715  3273  3273 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-24 17:38:44.746  3273  3273 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {148057c4}
,03-24 17:38:44.747  3273  3273 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-24 17:38:44.747  3273  3273 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,03-24 17:38:44.757  3273  3273 I BrowserStartupController: Initializing chromium process, singleProcess=true
03-24 17:38:44.757  3273  3273 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-24 17:38:44.758  3273  3273 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-24 17:38:44.766  3273  3297 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,03-24 17:38:44.772  3273  3273 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,03-24 17:38:44.777  3273  3273 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-24 17:38:44.777  3273  3273 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-24 17:38:44.777  3273  3273 I Adreno  : EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,03-24 17:38:44.802   259   321 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0,
03-24 17:38:44.804   259   259 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,03-24 17:38:44.804   823  1052 D SurfaceControl: Excessive delay in setPowerMode(): 269ms
,03-24 17:38:44.806   823   864 I DreamManagerService: Entering dreamland.,
03-24 17:38:44.807   823   864 I PowerManagerService: Dozing...
,03-24 17:38:44.808   823   859 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,03-24 17:38:44.829   359  1221 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
03-24 17:38:44.830   359  1221 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,03-24 17:38:44.836   823  1019 E WifiStateMachine: cancelDelayedScan -> 16
,03-24 17:38:44.841   823  1019 E native  : do suspend false
,03-24 17:38:44.857   823   861 D BluetoothManagerService: Message: 20
03-24 17:38:44.857   823   861 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ca4e3e1:true
,03-24 17:38:44.878   823  1019 E WifiStateMachine: cancelDelayedScan -> 18
,03-24 17:38:44.887  3273  3273 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-24 17:38:44.896  3273  3273 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-24 17:38:44.909  3273  3273 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,03-24 17:38:44.915  3273  3273 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-24 17:38:44.916  3273  3273 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-24 17:38:44.934   823  1019 E native  : do suspend true
,03-24 17:38:44.959  3273  3321 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,03-24 17:38:44.966  3273  3273 D Atlas   : Validating map...
,03-24 17:38:44.973   823  1154 V WindowManager: Adding window Window{179d8751 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{a6fcb00 u0 Starting com.test.thalitest})
,03-24 17:38:44.975  3273  3306 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,03-24 17:38:44.983   359  1221 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
03-24 17:38:44.983   359  1221 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,03-24 17:38:45.023  3273  3321 I OpenGLRenderer: Initialized EGL, version 1.4
,03-24 17:38:45.030  3273  3321 D OpenGLRenderer: Enabling debug mode 0
,03-24 17:38:45.040   823  1019 E WifiStateMachine: WifiStateMachine Disconnected CMD_START_SCAN source -2 17, 18 -> obsolete
,03-24 17:38:45.079   823   862 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +733ms
,03-24 17:38:45.083  1248  1248 I Keyboard.Facilitator: onFinishInput()
,03-24 17:38:45.088  3273  3273 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3273
,03-24 17:38:45.099  3273  3273 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,03-24 17:38:45.176  3273  3273 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-24 17:38:45.285  3273  3324 D jxcore_app_log: JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576403328
,03-24 17:38:45.288  3273  3324 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-24 17:38:45.288  3273  3324 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-24 17:38:45.288  3273  3324 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-24 17:38:45.288  3273  3324 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-24 17:38:45.288  3273  3324 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-24 17:38:45.288  3273  3324 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a99a789 added. We now have 1 listener(s)
,03-24 17:38:45.288   823  1104 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
,03-24 17:38:45.290  3273  3324 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61,
03-24 17:38:45.291  3273  3324 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,03-24 17:38:45.291  3273  3324 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66,
03-24 17:38:45.291  3273  3324 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: ,
03-24 17:38:45.293  3273  3324 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-24 17:38:45.293  3273  3324 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-24 17:38:45.293  3273  3324 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
,03-24 17:38:45.293  3273  3324 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
03-24 17:38:45.293  3273  3324 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-24 17:38:45.293  3273  3324 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-24 17:38:45.293  3273  3324 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
03-24 17:38:45.293  3273  3324 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
,03-24 17:38:45.293  3273  3324 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2,
03-24 17:38:45.293  3273  3324 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
,03-24 17:38:45.293  3273  3324 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-24 17:38:45.293  3273  3324 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a9537bc added. We now have 1 listener(s)
,03-24 17:38:45.293  3273  3324 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-24 17:38:45.296   823  1020 D WifiService: New client listening to asynchronous messages,
,03-24 17:38:45.297  3273  3324 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
03-24 17:38:45.298  3273  3324 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
03-24 17:38:45.298  3273  3324 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
03-24 17:38:45.299  3273  3324 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
03-24 17:38:45.299  3273  3324 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
03-24 17:38:45.300  3273  3324 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 17:38:45.301   823  1104 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 17:38:45.301  3273  3324 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
03-24 17:38:45.304  3273  3324 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 17:38:45.304  3273  3324 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 17:38:45.304  3273  3324 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 17:38:45.304  3273  3324 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 17:38:45.304  3273  3324 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 17:38:45.304  3273  3324 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
03-24 17:38:45.304  3273  3324 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
03-24 17:38:45.304  3273  3324 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
03-24 17:38:45.304  3273  3324 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-24 17:38:45.304  3273  3324 D io.jxcore.node.ConnectivityMonitor: start: OK
03-24 17:38:45.305  3273  3273 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
03-24 17:38:45.305  3273  3324 I io.jxcore.node.LifeCycleMonitor: start: OK
,03-24 17:38:45.326  3273  3273 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41),
,03-24 17:38:45.640   874   874 I kickstart: STATUS: Received file 'm9kefs2'
03-24 17:38:45.640   874   874 I kickstart: STATUS: 950272 bytes transferred in 0.995580 seconds
03-24 17:38:45.640   874   874 I kickstart: STATUS: Successfully downloaded files from target 
03-24 17:38:45.640   874   874 I kickstart: STATUS: Wrote to /sys/power/wake_unlock
,03-24 17:38:45.644   874   874 I kickstart: STATUS: Sahara protocol completed,
,03-24 17:38:45.897   823  1019 E WifiStateMachine: WifiStateMachine Disconnected CMD_START_SCAN source -2 15, 18 -> obsolete
,03-24 17:38:45.978  3273  3332 W jxcore-log: Initializing JXcore engine
03-24 17:38:45.978  3273  3332 W jxcore-log: JXcore engine is ready
,03-24 17:38:46.005  3332  3332 W Thread-350: type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[11465]" dev="sockfs" ino=11465 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0,
,03-24 17:38:46.005  3332  3332 W Thread-350: type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,03-24 17:38:46.026  3273  3332 W jxcore-log: Starting JXcore engine
,03-24 17:38:46.005  3332  3332 W Thread-350: type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[10773]" dev="sockfs" ino=10773 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,03-24 17:38:46.005  3332  3332 W Thread-350: type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[21051]" dev="sockfs" ino=21051 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0,
,03-24 17:38:46.102  3273  3332 W jxcore-log: Platform android
03-24 17:38:46.102  3273  3332 W jxcore-log: 
,03-24 17:38:46.102  3273  3332 W jxcore-log: Process ARCH arm
03-24 17:38:46.102  3273  3332 W jxcore-log: 
,03-24 17:38:46.295  3273  3332 I jxcore-log: JXcore Cordova bridge is ready!,
03-24 17:38:46.295  3273  3332 I jxcore-log: 
03-24 17:38:46.295  3273  3332 W jxcore-log: JXcore engine is started
,03-24 17:38:46.310  3273  3324 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION,
,03-24 17:38:46.316  3273  3273 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41),
,03-24 17:38:47.386  1150  1150 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,03-24 17:38:47.804  1150  1150 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,03-24 17:38:47.845  1150  1150 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
03-24 17:38:47.846  1150  1150 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,03-24 17:38:47.873   823  1019 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
,03-24 17:38:47.873   823  1019 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,03-24 17:38:47.875   823  1021 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,03-24 17:38:47.877   823  1019 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,03-24 17:38:47.880   355   801 D CommandListener: Setting iface cfg
,03-24 17:38:47.883   823  1019 E WifiStateMachine: Start Dhcp Watchdog 1,
,03-24 17:38:47.887   823  1019 E WifiStateMachine:  WifiLinkLayerStats: 
03-24 17:38:47.887   823  1019 E WifiStateMachine:  my bss beacon rx: 1
03-24 17:38:47.887   823  1019 E WifiStateMachine:  RSSI mgmt: -39
03-24 17:38:47.887   823  1019 E WifiStateMachine:  BE :  rx=0 tx=3 lost=0 retries=1
03-24 17:38:47.887   823  1019 E WifiStateMachine:  BK :  rx=0 tx=0 lost=0 retries=0
03-24 17:38:47.887   823  1019 E WifiStateMachine:  VI :  rx=0 tx=0 lost=0 retries=0
03-24 17:38:47.887   823  1019 E WifiStateMachine:  VO :  rx=2 tx=0 lost=0 retries=0
03-24 17:38:47.887   823  1019 E WifiStateMachine:  on_time : 485 tx_time=63 rx_time=59 scan_time=0
,03-24 17:38:47.978   823  1019 E native  : do suspend false,
,03-24 17:38:47.990   823  1019 E WifiStateMachine: scanCount==0 - aborting,
,03-24 17:38:48.238  3335  3335 I dhcpcd  : version 5.5.6 starting
,03-24 17:38:48.354  3335  3335 I dhcpcd  : wlan0: rebinding lease of 192.168.1.125
,03-24 17:38:48.481  3335  3335 I dhcpcd  : wlan0: acknowledged 192.168.1.125 from 192.168.1.1
,03-24 17:38:48.595  3335  3335 I dhcpcd  : wlan0: leased 192.168.1.125 for 172800 seconds,
,03-24 17:38:49.012   823  1019 E native  : do suspend true
,03-24 17:38:49.053   823  1021 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED,
03-24 17:38:49.054   823  1021 D ConnectivityService: Adding iface wlan0 to network 100
,03-24 17:38:49.058   823  1019 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,03-24 17:38:49.081   823  1021 E ConnectivityService: Unexpected mtu value: 0, wlan0
03-24 17:38:49.081   823  1021 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 100
03-24 17:38:49.082   823  1021 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,03-24 17:38:49.084   823  1021 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,03-24 17:38:49.086   823  1021 D ConnectivityService: Setting Dns servers for network 100 to [/192.168.1.1]
,03-24 17:38:49.105   823  1021 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,03-24 17:38:49.108   823  1021 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
03-24 17:38:49.108   823  3333 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
03-24 17:38:49.109   823  3333 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Connected
03-24 17:38:49.109   823  3333 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
03-24 17:38:49.109   823  1021 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
03-24 17:38:49.109   823  1021 D ConnectivityService:    accepting network in place of null
03-24 17:38:49.109   823  3333 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
03-24 17:38:49.110   823  1021 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.125/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
03-24 17:38:49.111   823  1021 D ConnectivityService: Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
03-24 17:38:49.113   823  1021 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,03-24 17:38:49.114   823  1021 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
03-24 17:38:49.114   823  1021 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
03-24 17:38:49.114   823  1021 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
03-24 17:38:49.114  1074  1567 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,03-24 17:38:49.117   823   861 D Tethering: MasterInitialState.processMessage what=3
,03-24 17:38:49.121   823  1151 V BackupManagerService: Scheduling immediate backup pass
,03-24 17:38:49.123   823   823 V BackupManagerService: Running a backup pass
,03-24 17:38:49.124   823  1051 V BackupManagerService: clearing pending backups,
,03-24 17:38:49.128  2941  2941 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
03-24 17:38:49.130  3273  3273 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
03-24 17:38:49.130  3273  3273 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 17:38:49.130  3273  3273 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 17:38:49.130  3273  3273 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 17:38:49.130  3273  3273 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 17:38:49.130  3273  3273 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 17:38:49.130  3273  3273 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 17:38:49.130  3273  3273 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-24 17:38:49.130  3273  3273 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,03-24 17:38:49.133   823  1051 V PerformBackupTask: Beginning backup of 14 targets
,03-24 17:38:49.137  2941  2941 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,03-24 17:38:49.142   823  1051 D PerformBackupTask: invokeAgentForBackup on @pm@
,03-24 17:38:49.144   823  1051 V BackupServiceBinder: doBackup() invoked
,03-24 17:38:49.146   823  1051 I PMBA    : Previous metadata 1570415 mismatch vs 1860966 - rewriting
,03-24 17:38:49.161   823  1051 I BackupRestoreController: Getting widget state for user: 0
,03-24 17:38:49.186   823  1404 I ActivityManager: Start proc 3374:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.steen.receiver.ConnectivityChangeReceiver
,03-24 17:38:49.202   371   371 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 328us total 16.062ms
,03-24 17:38:49.217   371   371 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 340us total 14.270ms
,03-24 17:38:49.222   823  1290 D AlarmManagerService: Setting time of day to sec=1458837528
03-24 17:38:48.750   823  1290 W AlarmManagerService: Unable to set rtc to 1458837528: Invalid argument
,03-24 17:38:48.763   371   371 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 256us total 18.068ms
,03-24 17:38:48.770  1337  1361 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
03-24 17:38:48.770  1337  1361 E PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
03-24 17:38:48.770   823   856 D TelephonyManager: getDataEnabled: retVal=false
,03-24 17:38:48.774  1265  2584 I art     : Explicit concurrent mark sweep GC freed 29995(1526KB) AllocSpace objects, 0(0B) LOS objects, 38% free, 25MB/41MB, paused 1.251ms total 55.761ms
,03-24 17:38:48.787   823   856 E GpsLocationProvider: No APN found to select.
,03-24 17:38:48.799   823  3398 D GpsLocationProvider: NTP server returned: 1458837528750 (Thu Mar 24 17:38:48 GMT+01:00 2016) reference: 168177 certainty: 20 system time offset: -49
,03-24 17:38:48.821   823  3333 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 24 Mar 2016 16:38:48 GMT], X-Android-Received-Millis=[1458837528820], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1458837528786]}
03-24 17:38:48.821   823  3333 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Validated
03-24 17:38:48.821   823  1021 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
03-24 17:38:48.821   823  1021 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 100]
03-24 17:38:48.821   823  1021 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
,03-24 17:38:48.821   823  1021 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
03-24 17:38:48.821   823  1021 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
03-24 17:38:48.822  1074  1567 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
03-24 17:38:48.822   823  1021 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,03-24 17:38:48.826  1842  1858 W GmsBackupTransport: Unknown package in backup request: @pm@
03-24 17:38:48.827  1842  1858 V GmsBackupTransport: starting performBackup for @pm@
,03-24 17:38:48.841  1842  1858 V GmsBackupTransport: performBackup done for @pm@
,03-24 17:38:48.875   823   838 I ActivityManager: Start proc 3409:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,03-24 17:38:48.881  1265  1265 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 17:38:48.897  1814  3397 E Auth.Api.Credentials: [CredentialSyncAdapter] Unknown sync event.
,03-24 17:38:48.908  1265  1281 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: android
03-24 17:38:48.908  1265  1281 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> android without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 17:38:48.908  1265  1281 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 17:38:48.908  1265  1281 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 17:38:48.910  1265  1281 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 17:38:48.938  1265  1281 W GLSActivity: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-24 17:38:48.938  1265  1281 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-24 17:38:48.938  1265  1281 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-24 17:38:48.938  1265  1281 W GLSActivity: 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
03-24 17:38:48.938  1265  1281 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
03-24 17:38:48.938  1265  1281 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
03-24 17:38:48.938  1265  1281 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:446)
,03-24 17:38:48.944  1842  1899 W GmsBackupTransport: Error sending final backup to server: 
03-24 17:38:48.944  1842  1899 W GmsBackupTransport: com.google.android.gms.backup.d.d: Can not get client auth token
03-24 17:38:48.944  1842  1899 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:1080)
03-24 17:38:48.944  1842  1899 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:65)
03-24 17:38:48.944  1842  1899 W GmsBackupTransport: 	at com.google.android.gms.backup.aa.finishBackup(SourceFile:409)
03-24 17:38:48.944  1842  1899 W GmsBackupTransport: 	at android.app.backup.BackupTransport$TransportImpl.finishBackup(BackupTransport.java:547)
03-24 17:38:48.944  1842  1899 W GmsBackupTransport: 	at com.android.internal.backup.IBackupTransport$Stub.onTransact(IBackupTransport.java:162)
03-24 17:38:48.944  1842  1899 W GmsBackupTransport: 	at android.os.Binder.execTransact(Binder.java:446)
03-24 17:38:48.944  1842  1899 W GmsBackupTransport: Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
03-24 17:38:48.944  1842  1899 W GmsBackupTransport: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
03-24 17:38:48.944  1842  1899 W GmsBackupTransport: 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
03-24 17:38:48.944  1842  1899 W GmsBackupTransport: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
03-24 17:38:48.944  1842  1899 W GmsBackupTransport: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
03-24 17:38:48.944  1842  1899 W GmsBackupTransport: 	... 1 more
,03-24 17:38:48.945   823  1051 D BackupManagerService: Now staging backup of com.google.android.talk
,03-24 17:38:48.946  3409  3409 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,03-24 17:38:48.949   823  1051 D BackupManagerService: Now staging backup of com.google.android.dialer
,03-24 17:38:48.951   823  1051 D BackupManagerService: Now staging backup of com.android.providers.settings
,03-24 17:38:48.954   823  1051 D BackupManagerService: Now staging backup of com.android.sharedstoragebackup
,03-24 17:38:48.956   823  1051 D BackupManagerService: Now staging backup of com.google.android.gm
,03-24 17:38:48.957  3409  3409 D SprintDMHelper: simOperator:  IMSI: null
03-24 17:38:48.957  3409  3409 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,03-24 17:38:48.958   823  1051 D BackupManagerService: Now staging backup of com.android.providers.userdictionary
,03-24 17:38:48.960   823  1051 D BackupManagerService: Now staging backup of com.android.nfc
,03-24 17:38:48.962   823  1051 D BackupManagerService: Now staging backup of com.google.android.apps.genie.geniewidget
,03-24 17:38:48.988  1814  3430 W DriveInitializer: Background init thread started
,03-24 17:38:48.991   823  1051 D BackupManagerService: Now staging backup of com.google.android.marvin.talkback
,03-24 17:38:49.004   823  1051 D BackupManagerService: Now staging backup of com.google.android.inputmethod.latin
,03-24 17:38:49.013   823  1051 D BackupManagerService: Now staging backup of com.google.android.calendar
,03-24 17:38:49.022   823  1051 D BackupManagerService: Now staging backup of com.android.vending
,03-24 17:38:49.033   823  1051 D BackupManagerService: Now staging backup of android
,03-24 17:38:49.039   823  1051 D BackupManagerService: Now staging backup of com.google.android.googlequicksearchbox
,03-24 17:38:49.061  1842  1858 I GmsBackupTransport: Next backup will happen in 43199879 millis.
03-24 17:38:49.063   823  1051 I BackupManagerService: Backup pass finished.
,03-24 17:38:49.095  1814  1814 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,03-24 17:38:49.117  1265  2585 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-24 17:38:49.117  1265  2585 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 17:38:49.117  1265  2585 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 17:38:49.117  1265  2585 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
03-24 17:38:49.118  1814  3431 W DriveInitializer: Awaiting to be initialized
,03-24 17:38:49.120  1265  2585 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 17:38:49.133  3093  3428 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
03-24 17:38:49.133  3093  3428 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-24 17:38:49.133  3093  3428 E HttpOperation: 	at jdm.a(PG:82)
03-24 17:38:49.133  3093  3428 E HttpOperation: 	at jcs.o(PG:406)
03-24 17:38:49.133  3093  3428 E HttpOperation: 	at jcn.a(PG:1379)
03-24 17:38:49.133  3093  3428 E HttpOperation: 	at jcs.i(PG:143)
03-24 17:38:49.133  3093  3428 E HttpOperation: 	at blb.a(PG:3937)
03-24 17:38:49.133  3093  3428 E HttpOperation: 	at czp.a(PG:18188)
03-24 17:38:49.133  3093  3428 E HttpOperation: 	at czp.a(PG:9081)
03-24 17:38:49.133  3093  3428 E HttpOperation: 	at czq.run(PG:1686)
03-24 17:38:49.133  3093  3428 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-24 17:38:49.133  3093  3428 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 17:38:49.133  3093  3428 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 17:38:49.133  3093  3428 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 17:38:49.133  3093  3428 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-24 17:38:49.133  3093  3428 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-24 17:38:49.133  3093  3428 E HttpOperation: 	at jdj.a(PG:4091)
03-24 17:38:49.133  3093  3428 E HttpOperation: 	at jdj.a(PG:1125)
03-24 17:38:49.133  3093  3428 E HttpOperation: 	at jdm.a(PG:77)
03-24 17:38:49.133  3093  3428 E HttpOperation: 	... 12 more
03-24 17:38:49.133  3093  3428 E HttpOperation: Caused by: faj: BadAuthentication
03-24 17:38:49.133  3093  3428 E HttpOperation: 	at fal.a(PG:38)
03-24 17:38:49.133  3093  3428 E HttpOperation: 	at jdj.a(PG:4089)
03-24 17:38:49.133  3093  3428 E HttpOperation: 	... 14 more
,03-24 17:38:49.169   823  1446 I art     : Explicit concurrent mark sweep GC freed 71311(3MB) AllocSpace objects, 5(80KB) LOS objects, 32% free, 33MB/49MB, paused 1.718ms total 69.215ms
,03-24 17:38:49.179  1814  1814 D SystemUpdateService: onCreate
,03-24 17:38:49.181  1265  2585 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-24 17:38:49.181  1265  2585 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 17:38:49.181  1265  2585 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 17:38:49.181  1265  2585 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 17:38:49.183  1814  1814 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,03-24 17:38:49.187  1265  2585 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 17:38:49.198  3093  3428 E HttpOperation: [getmobileexperiments] Unexpected exception
03-24 17:38:49.198  3093  3428 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-24 17:38:49.198  3093  3428 E HttpOperation: 	at jdm.a(PG:82)
03-24 17:38:49.198  3093  3428 E HttpOperation: 	at jcs.o(PG:406)
03-24 17:38:49.198  3093  3428 E HttpOperation: 	at jcn.a(PG:1379)
03-24 17:38:49.198  3093  3428 E HttpOperation: 	at jcs.i(PG:143)
03-24 17:38:49.198  3093  3428 E HttpOperation: 	at hec.a(PG:42)
03-24 17:38:49.198  3093  3428 E HttpOperation: 	at hee.a(PG:102)
03-24 17:38:49.198  3093  3428 E HttpOperation: 	at czr.a(PG:65)
03-24 17:38:49.198  3093  3428 E HttpOperation: 	at kka.a(PG:108)
03-24 17:38:49.198  3093  3428 E HttpOperation: 	at czp.a(PG:19176)
03-24 17:38:49.198  3093  3428 E HttpOperation: 	at czp.a(PG:9081)
03-24 17:38:49.198  3093  3428 E HttpOperation: 	at czq.run(PG:1686)
03-24 17:38:49.198  3093  3428 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-24 17:38:49.198  3093  3428 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 17:38:49.198  3093  3428 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 17:38:49.198  3093  3428 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 17:38:49.198  3093  3428 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-24 17:38:49.198  3093  3428 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-24 17:38:49.198  3093  3428 E HttpOperation: 	at jdj.a(PG:4091)
03-24 17:38:49.198  3093  3428 E HttpOperation: 	at jdj.a(PG:1125)
03-24 17:38:49.198  3093  3428 E HttpOperation: 	at jdm.a(PG:77)
03-24 17:38:49.198  3093  3428 E HttpOperation: 	... 15 more
03-24 17:38:49.198  3093  3428 E HttpOperation: Caused by: faj: BadAuthentication
03-24 17:38:49.198  3093  3428 E HttpOperation: 	at fal.a(PG:38)
03-24 17:38:49.198  3093  3428 E HttpOperation: 	at jdj.a(PG:4089)
03-24 17:38:49.198  3093  3428 E HttpOperation: 	... 17 more
03-24 17:38:49.199  3093  3428 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
03-24 17:38:49.199  3093  3428 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
03-24 17:38:49.199  3093  3428 E ExperimentLoader: 	at jdm.a(PG:82)
03-24 17:38:49.199  3093  3428 E ExperimentLoader: 	at jcs.o(PG:406)
03-24 17:38:49.199  3093  3428 E ExperimentLoader: 	at jcn.a(PG:1379)
03-24 17:38:49.199  3093  3428 E ExperimentLoader: 	at jcs.i(PG:143)
03-24 17:38:49.199  3093  3428 E ExperimentLoader: 	at hec.a(PG:42)
03-24 17:38:49.199  3093  3428 E ExperimentLoader: 	at hee.a(PG:102)
03-24 17:38:49.199  3093  3428 E ExperimentLoader: 	at czr.a(PG:65)
03-24 17:38:49.199  3093  3428 E ExperimentLoader: 	at kka.a(PG:108)
03-24 17:38:49.199  3093  3428 E ExperimentLoader: 	at czp.a(PG:19176)
03-24 17:38:49.199  3093  3428 E ExperimentLoader: 	at czp.a(PG:9081)
03-24 17:38:49.199  3093  3428 E ExperimentLoader: 	at czq.run(PG:1686)
03-24 17:38:49.199  3093  3428 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-24 17:38:49.199  3093  3428 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 17:38:49.199  3093  3428 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 17:38:49.199  3093  3428 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 17:38:49.199  3093  3428 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
03-24 17:38:49.199  3093  3428 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-24 17:38:49.199  3093  3428 E ExperimentLoader: 	at jdj.a(PG:4091)
03-24 17:38:49.199  3093  3428 E ExperimentLoader: 	at jdj.a(PG:1,125)
03-24 17:38:49.199  3093  3428 E ExperimentLoader: 	at jdm.a(PG:77)
03-24 17:38:49.199  3093  3428 E ExperimentLoader: 	... 15 more
03-24 17:38:49.199  3093  3428 E ExperimentLoader: Caused by: faj: BadAuthentication
03-24 17:38:49.199  3093  3428 E ExperimentLoader: 	at fal.a(PG:38)
03-24 17:38:49.199  3093  3428 E ExperimentLoader: 	at jdj.a(PG:4089)
03-24 17:38:49.199  3093  3428 E ExperimentLoader: 	... 17 more
03-24 17:38:49.205  1814  3437 I SystemUpdateService: active receiver: enabled
03-24 17:38:49.211  1814  3437 I SystemUpdateService: Already downloaded, skipping offpeak checks.
03-24 17:38:49.213  1814  1814 W art     : No such thread id for suspend: 44
03-24 17:38:49.214  1814  3437 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]; metered: false; mobile allowed: true
03-24 17:38:49.214  1814  3437 I SystemUpdateService: now status is 0 (complete)
03-24 17:38:49.214  1814  3437 I SystemUpdateService: processDownloadedFile /data/data/com.google.android.gms/app_download/update.zip
03-24 17:38:49.214  1814  3437 I SystemUpdateService: file has been verified
03-24 17:38:49.214  1814  3437 I SystemUpdateService: OTA package size = 25802302
03-24 17:38:49.225  1814  3437 I SystemUpdateService: showing system update notification
,03-24 17:38:49.239   823   823 I ValidateNoPeople: skipping global notification
,03-24 17:38:49.260  1814  3430 W DriveInitializer: Background init thread ended
,03-24 17:38:49.337   823   856 I ActivityManager: Start proc 3452:com.google.android.keep/u0a79 for service com.google.android.keep/.syncadapter.KeepSyncAdapterService
,03-24 17:38:49.352   823  1413 I ActivityManager: Killing 2918:com.android.settings/1000 (adj 15): empty #17
03-24 17:38:49.353   823   856 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 38971, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-24 17:38:49.469  1814  1814 D SystemUpdateService: onDestroy
,03-24 17:38:49.491   823   856 I ActivityManager: Start proc 3473:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,03-24 17:38:49.508  1814  3483 I iu.SyncManager: SYNC; picasa accounts
,03-24 17:38:49.512  1814  1814 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,03-24 17:38:49.514  1814  1814 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,03-24 17:38:49.520  1814  3483 I iu.UploadsManager: num queued entries: 0
03-24 17:38:49.520  1814  3483 I iu.UploadsManager: num updated entries: 0
03-24 17:38:49.521  1814  3483 I iu.SyncManager: NEXT; no task
,03-24 17:38:49.528  1814  1814 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,03-24 17:38:49.531  1814  1814 I Kids    : [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
,03-24 17:38:49.538  1265  1281 I art     : Explicit concurrent mark sweep GC freed 16706(936KB) AllocSpace objects, 2(32KB) LOS objects, 38% free, 26MB/42MB, paused 1.105ms total 28.802ms
,03-24 17:38:49.568   823   839 I ActivityManager: Start proc 3496:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,03-24 17:38:49.655  3496  3496 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
03-24 17:38:49.655  3496  3496 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-24 17:38:49.655  3496  3496 I GAv4    :   adb logcat -s GAv4
,03-24 17:38:49.665  3496  3496 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,03-24 17:38:49.675  3496  3496 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,03-24 17:38:49.678  3496  3524 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,03-24 17:38:49.680  3129  3493 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,03-24 17:38:49.682   823  1154 I ActivityManager: Killing 2452:com.google.android.apps.maps/u0a65 (adj 15): empty #17
,03-24 17:38:49.717  3452  3523 V KeepSync: Connecting to GoogleApiClient
,03-24 17:38:49.818  1265  3471 D GCM     : Connected
,03-24 17:38:49.836  1814  3527 W BaseAppContext: Using Auth Proxy for data requests.
,03-24 17:38:49.847  1814  3527 W BaseAppContext: Using Auth Proxy for data requests.
,03-24 17:38:49.868  1265  1281 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
03-24 17:38:49.868  1265  1281 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-24 17:38:49.868  1265  1281 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 17:38:49.868  1265  1281 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 17:38:49.871  1265  1281 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 17:38:49.892  1814  3527 E ClientConnectionOperation: Handling authorization failure
03-24 17:38:49.892  1814  3527 E ClientConnectionOperation: com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
03-24 17:38:49.892  1814  3527 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
03-24 17:38:49.892  1814  3527 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
03-24 17:38:49.892  1814  3527 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
03-24 17:38:49.892  1814  3527 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
03-24 17:38:49.892  1814  3527 E ClientConnectionOperation: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-24 17:38:49.892  1814  3527 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 17:38:49.892  1814  3527 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 17:38:49.892  1814  3527 E ClientConnectionOperation: 	at java.lang.Thread.run(Thread.java:818)
03-24 17:38:49.892  1814  3527 E ClientConnectionOperation: Caused by: com.google.android.gms.auth.ad: BadAuthentication
03-24 17:38:49.892  1814  3527 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.b(SourceFile:442)
03-24 17:38:49.892  1814  3527 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:365)
03-24 17:38:49.892  1814  3527 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:310)
03-24 17:38:49.892  1814  3527 E ClientConnectionOperation: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
03-24 17:38:49.892  1814  3527 E ClientConnectionOperation: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
03-24 17:38:49.892  1814  3527 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:30)
03-24 17:38:49.892  1814  3527 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:370)
03-24 17:38:49.892  1814  3527 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:340)
03-24 17:38:49.892  1814  3527 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:319)
03-24 17:38:49.892  1814  3527 E ClientConnectionOperation: 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
03-24 17:38:49.892  1814  3527 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
03-24 17:38:49.892  1814  3527 E ClientConnectionOperation: 	... 7 more
,03-24 17:38:49.894  3452  3523 V KeepSync: GoogleApiClient failed to connect with error code: 4
,03-24 17:38:49.903  3452  3523 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-24 17:38:49.909  3452  3523 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
03-24 17:38:49.910  3452  3523 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-24 17:38:49.929  1265  3471 D GCM     : Message class com.google.f.a.a.p
,03-24 17:38:49.971  3496  3496 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,03-24 17:38:49.979  3496  3496 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 9406-9407)
03-24 17:38:49.979  3496  3496 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-24 17:38:49.984  3496  3496 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1d1b11bb}
,03-24 17:38:49.984  3496  3496 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-24 17:38:49.984  3496  3496 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
03-24 17:38:49.984  3473  3473 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,03-24 17:38:49.991  3496  3496 I BrowserStartupController: Initializing chromium process, singleProcess=true
,03-24 17:38:49.992  3496  3496 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-24 17:38:49.992  3496  3496 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-24 17:38:49.995  3473  3473 I BooksApp: Created application version: 3.6.8 (30608)
,03-24 17:38:50.004  3496  3496 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,03-24 17:38:50.011  3496  3496 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-24 17:38:50.011  3496  3496 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-24 17:38:50.011  3496  3496 I Adreno  : EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,03-24 17:38:50.052  1265  2584 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
03-24 17:38:50.052  1265  2584 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 17:38:50.052  1265  2584 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 17:38:50.052  1265  2584 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 17:38:50.058  1265  2584 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 17:38:50.060  3496  3562 W AudioManagerAndroid: Requires BLUETOOTH permission
,03-24 17:38:50.074  3496  3496 I NSApplication: Starting up...
,03-24 17:38:50.084  3473  3553 I BooksSync: Starting books sync for 61035162, extras: ade
,03-24 17:38:50.111   823   839 I ActivityManager: Start proc 3568:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,03-24 17:38:50.135  3452  3523 E KeepSync: IOException
03-24 17:38:50.135  3452  3523 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
03-24 17:38:50.135  3452  3523 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
03-24 17:38:50.135  3452  3523 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
03-24 17:38:50.135  3452  3523 E KeepSync: 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
03-24 17:38:50.135  3452  3523 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
03-24 17:38:50.135  3452  3523 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
03-24 17:38:50.135  3452  3523 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
03-24 17:38:50.135  3452  3523 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
03-24 17:38:50.135  3452  3523 E KeepSync: 	at com.google.android.keep.util.m.a(SourceFile:207)
03-24 17:38:50.135  3452  3523 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
03-24 17:38:50.135  3452  3523 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
03-24 17:38:50.135  3452  3523 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
03-24 17:38:50.135  3452  3523 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
03-24 17:38:50.135  3452  3523 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
03-24 17:38:50.135  3452  3523 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
03-24 17:38:50.135  3452  3523 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
03-24 17:38:50.135  3452  3523 E KeepSync: 	... 10 more
03-24 17:38:50.135  3452  3523 W KeepSync: Sync result 2
,03-24 17:38:50.141   823   856 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 38977, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-24 17:38:50.141   823   838 I ActivityManager: Killing 3001:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,03-24 17:38:50.329  3473  3590 I BooksConfig: GmsCore Version = 7.8.99 (2134222-430)
,03-24 17:38:50.387  1265  2585 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-24 17:38:50.387  1265  2585 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 17:38:50.387  1265  2585 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 17:38:50.387  1265  2585 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 17:38:50.390  1265  2585 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 17:38:50.440  1265  1281 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-24 17:38:50.440  1265  1281 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 17:38:50.440  1265  1281 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 17:38:50.440  1265  1281 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 17:38:50.443  1265  1281 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 17:38:50.451  3473  3590 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,03-24 17:38:50.453  3473  3553 E BooksSync: Soft error
03-24 17:38:50.453  3473  3553 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-24 17:38:50.453  3473  3553 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,03-24 17:38:50.453  3473  3553 E BooksSync: Sync error
03-24 17:38:50.453  3473  3553 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-24 17:38:50.453  3473  3553 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-24 17:38:50.453  3473  3553 I BooksSync: Finished books sync
,03-24 17:38:50.457   823   856 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 38977, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-24 17:38:50.458   823  1413 I ActivityManager: Killing 3051:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,03-24 17:38:50.563   823  1413 I ActivityManager: Killing 3022:com.android.musicfx/u0a18 (adj 15): empty #18
,03-24 17:38:50.927   823  1413 I ActivityManager: Start proc 3595:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,03-24 17:38:50.928   823  1413 I ActivityManager: Killing 2469:android.process.acore/u0a5 (adj 15): empty #17
,03-24 17:38:51.961   823   839 I ActivityManager: Killing 2818:com.google.android.gm/u0a78 (adj 15): empty #17
,03-24 17:38:52.270   823  1153 I ActivityManager: Start proc 3613:com.qualcomm.timeservice/1000 for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver
,03-24 17:38:52.300   823  1413 I art     : Explicit concurrent mark sweep GC freed 30537(1432KB) AllocSpace objects, 5(121KB) LOS objects, 32% free, 33MB/49MB, paused 1.468ms total 77.353ms
,03-24 17:38:52.329  3613  3613 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1458837532329
,03-24 17:38:52.329  3613  3613 D         : TimeServiceNative: User Time to be set is 1458837532329
03-24 17:38:52.329  3613  3613 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
03-24 17:38:52.329  3613  3613 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
03-24 17:38:52.329  3613  3613 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1458837532329
,03-24 17:38:52.330  3613  3613 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
03-24 17:38:52.330   374   877 D QC-time-services: Daemon: Connection accepted:time_genoff
03-24 17:38:52.330   374  3632 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1458837532329
03-24 17:38:52.330   374  3632 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1458837532329, operation = 0
03-24 17:38:52.330   374  3632 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS7/10/70 12:50:34
03-24 17:38:52.330   374  3632 D QC-time-services: Daemon:Value read from RTC seconds = 19140634000
,03-24 17:38:52.330   374  3632 D QC-time-services: Daemon:new time 1458837532329 
03-24 17:38:52.331   374  3632 D QC-time-services: Daemon: delta 1439696898329 genoff 1439696898329 
03-24 17:38:52.331   374  3632 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1439696898329 to memory
03-24 17:38:52.331   374  3632 D QC-time-services: Daemon:Opening File: /data/time/ats_2
03-24 17:38:52.331   374  3632 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
03-24 17:38:52.333   374  3632 D QC-time-services: Updating the TOD offset
03-24 17:38:52.333   374  3632 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1439696898329 to memory
03-24 17:38:52.333   374  3632 D QC-time-services: Daemon:Opening File: /data/time/ats_1
03-24 17:38:52.333   374  3632 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,03-24 17:38:52.336   374  3632 E QC-time-services: Daemon:Update to modem bit set
03-24 17:38:52.336   374  3632 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
03-24 17:38:52.336   374  3632 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1142872732329
03-24 17:38:52.337  3613  3613 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,03-24 17:38:52.406   374   877 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,03-24 17:38:52.411   374   875 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,03-24 17:38:52.449   823  1417 I ActivityManager: Start proc 3634:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver
,03-24 17:38:52.460   823  1153 I ActivityManager: Killing 1881:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,03-24 17:38:52.566  3634  3634 I GAv4    : Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
03-24 17:38:52.566  3634  3634 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-24 17:38:52.566  3634  3634 I GAv4    :   adb logcat -s GAv4
,03-24 17:38:52.594  3634  3634 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,03-24 17:38:52.606  3634  3634 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.,
,03-24 17:38:52.621  3634  3653 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,03-24 17:38:52.738  1814  1814 V Herrevad: NQAS connected
,03-24 17:38:52.749   823  1020 D WifiService: New client listening to asynchronous messages
,03-24 17:38:52.758  3129  3129 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,03-24 17:38:52.759  3129  3129 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-24 17:38:52.832  1265  1728 I art     : Explicit concurrent mark sweep GC freed 13145(709KB) AllocSpace objects, 3(330KB) LOS objects, 37% free, 26MB/42MB, paused 1.267ms total 29.815ms
,03-24 17:38:52.872  1265  2584 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
,03-24 17:38:52.873  1265  2584 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 17:38:52.873  1265  2584 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 17:38:52.873  1265  2584 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 17:38:52.876  1265  2584 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 17:38:52.888  3129  3662 E Babel   : UserRecoverableAuthException.
,03-24 17:38:52.890  3129  3662 E Babel   : eei: BadAuthentication
03-24 17:38:52.890  3129  3662 E Babel   : 	at eeg.a(Unknown Source)
03-24 17:38:52.890  3129  3662 E Babel   : 	at eeg.a(Unknown Source)
03-24 17:38:52.890  3129  3662 E Babel   : 	at eeg.a(Unknown Source)
03-24 17:38:52.890  3129  3662 E Babel   : 	at g.a(Unknown Source)
03-24 17:38:52.890  3129  3662 E Babel   : 	at cae.a(SourceFile:3089)
03-24 17:38:52.890  3129  3662 E Babel   : 	at cae.a(SourceFile:1131)
03-24 17:38:52.890  3129  3662 E Babel   : 	at cws.a(SourceFile:4333)
03-24 17:38:52.890  3129  3662 E Babel   : 	at cws.a(SourceFile:1419)
03-24 17:38:52.890  3129  3662 E Babel   : 	at crl.a(SourceFile:492)
03-24 17:38:52.890  3129  3662 E Babel   : 	at crl.a(SourceFile:1468)
03-24 17:38:52.890  3129  3662 E Babel   : 	at cqu.a(SourceFile:4416)
03-24 17:38:52.890  3129  3662 E Babel   : 	at cas.b(SourceFile:106)
03-24 17:38:52.890  3129  3662 E Babel   : 	at cap.d(SourceFile:335)
03-24 17:38:52.890  3129  3662 E Babel   : 	at caq.run(SourceFile:81)
03-24 17:38:52.890  3129  3662 E Babel   : Error getting auth token
03-24 17:38:52.890  3129  3662 E Babel   : dvm
03-24 17:38:52.890  3129  3662 E Babel   : 	at g.a(Unknown Source)
03-24 17:38:52.890  3129  3662 E Babel   : 	at cae.a(SourceFile:3089)
03-24 17:38:52.890  3129  3662 E Babel   : 	at cae.a(SourceFile:1131)
03-24 17:38:52.890  3129  3662 E Babel   : 	at cws.a(SourceFile:4333)
03-24 17:38:52.890  3129  3662 E Babel   : 	at cws.a(SourceFile:1419)
03-24 17:38:52.890  3129  3662 E Babel   : 	at crl.a(SourceFile:492)
03-24 17:38:52.890  3129  3662 E Babel   : 	at crl.a(SourceFile:1468)
03-24 17:38:52.890  3129  3662 E Babel   : 	at cqu.a(SourceFile:4416)
03-24 17:38:52.890  3129  3662 E Babel   : 	at cas.b(SourceFile:106)
03-24 17:38:52.890  3129  3662 E Babel   : 	at cap.d(SourceFile:335)
03-24 17:38:52.890  3129  3662 E Babel   : 	at caq.run(SourceFile:81)
,03-24 17:38:52.893  3129  3662 E Babel   : Account registration failed 1-Redacted-21
,03-24 17:38:52.894  3129  3662 E Babel   : cyp: null -- null
03-24 17:38:52.894  3129  3662 E Babel   : 	at cae.a(SourceFile:3121)
03-24 17:38:52.894  3129  3662 E Babel   : 	at cae.a(SourceFile:1131)
03-24 17:38:52.894  3129  3662 E Babel   : 	at cws.a(SourceFile:4333)
03-24 17:38:52.894  3129  3662 E Babel   : 	at cws.a(SourceFile:1419)
03-24 17:38:52.894  3129  3662 E Babel   : 	at crl.a(SourceFile:492)
03-24 17:38:52.894  3129  3662 E Babel   : 	at crl.a(SourceFile:1468)
03-24 17:38:52.894  3129  3662 E Babel   : 	at cqu.a(SourceFile:4416)
03-24 17:38:52.894  3129  3662 E Babel   : 	at cas.b(SourceFile:106)
03-24 17:38:52.894  3129  3662 E Babel   : 	at cap.d(SourceFile:335)
03-24 17:38:52.894  3129  3662 E Babel   : 	at caq.run(SourceFile:81)
,03-24 17:38:52.903  3129  3662 I art     : Note: end time exceeds epoch: 
,03-24 17:38:52.917  1265  2584 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
03-24 17:38:52.917  1265  2584 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-24 17:38:52.917  1265  2584 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 17:38:52.917  1265  2584 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 17:38:52.919  1265  2584 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 17:38:52.933  1265  2584 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-24 17:38:52.945  3129  3669 E Babel   : Unexpected exception while authenticating.
,03-24 17:38:52.945  3129  3669 E Babel   : eej: User intervention required. Notification has been pushed.
03-24 17:38:52.945  3129  3669 E Babel   : 	at eeg.b(Unknown Source)
03-24 17:38:52.945  3129  3669 E Babel   : 	at eeg.b(Unknown Source)
03-24 17:38:52.945  3129  3669 E Babel   : 	at g.a(Unknown Source)
03-24 17:38:52.945  3129  3669 E Babel   : 	at cae.b(SourceFile:1146)
03-24 17:38:52.945  3129  3669 E Babel   : 	at dcg.run(SourceFile:5617)
03-24 17:38:52.945  3129  3669 E Babel   : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 17:38:52.945  3129  3669 E Babel   : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 17:38:52.945  3129  3669 E Babel   : 	at java.lang.Thread.run(Thread.java:818)
,03-24 17:38:54.993  3473  3545 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,03-24 17:38:55.837  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 17:38:55.837  3273  3332 I jxcore-log: 
,03-24 17:38:55.840  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 17:38:55.840  3273  3332 I jxcore-log: 
,03-24 17:38:55.854  3273  3332 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 17:38:55.854  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 17:38:55.854  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 17:38:55.854  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 17:38:55.854  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 17:38:55.854  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 17:38:55.854  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 17:38:55.854  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 17:38:55.859  3273  3332 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 17:38:55.861  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native,
03-24 17:38:55.861  3273  3332 I jxcore-log: 
,03-24 17:38:55.864  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native,
03-24 17:38:55.864  3273  3332 I jxcore-log: 
,03-24 17:38:56.402  3273  3332 I jxcore-log: Unit Test app is loaded
03-24 17:38:56.402  3273  3332 I jxcore-log: 
,03-24 17:38:56.414  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 17:38:56.414  3273  3332 I jxcore-log: 
,03-24 17:38:56.417  3273  3273 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,03-24 17:38:56.441  3273  3332 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,03-24 17:38:56.449  3273  3332 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
03-24 17:38:56.449  3273  3332 I jxcore-log: 
,03-24 17:38:56.454  3273  3332 I jxcore-log: My device name is: motorola-Nexus 6
03-24 17:38:56.454  3273  3332 I jxcore-log: 
,03-24 17:38:56.696  1265  1265 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 17:38:56.794  1265  3679 I VacuumService: Vacuum at: now=1458837536794 tag=VacuumService
,03-24 17:38:56.927  3374  3678 V GoogleAuthProtoRequest: [340] a.<init>: mAccountName set to: thalitester@gmail.com
,03-24 17:38:57.001  1265  2585 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
03-24 17:38:57.001  1265  2585 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 17:38:57.001  1265  2585 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 17:38:57.001  1265  2585 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 17:38:57.007  1265  2585 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 17:38:57.022  3374  3678 W ExperimentUpdateService: [340] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,03-24 17:38:57.025  3374  3678 W ExperimentUpdateService: [340] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-24 17:38:57.025  3374  3678 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-24 17:38:57.025  3374  3678 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-24 17:38:57.025  3374  3678 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-24 17:38:57.025  3374  3678 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-24 17:38:57.025  3374  3678 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-24 17:38:57.025  3374  3678 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-24 17:38:57.025  3374  3678 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-24 17:38:57.025  3374  3678 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-24 17:38:57.025  3374  3678 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-24 17:38:57.025  3374  3678 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-24 17:38:57.155  1265  3680 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,03-24 17:38:57.178  1265  3680 W Uploader: No account for auth token provided
,03-24 17:38:57.621  1265  3680 W Uploader: No account for auth token provided
,03-24 17:38:57.844  1265  3680 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,03-24 17:38:57.844  1265  3680 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-24 17:38:57.845  1265  3680 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 17:38:57.845  1265  3680 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 17:38:57.855  1265  3680 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 17:38:57.917  1265  3680 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-24 17:38:57.917  1265  3680 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-24 17:38:57.917  1265  3680 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-24 17:38:57.917  1265  3680 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-24 17:38:57.917  1265  3680 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-24 17:38:57.917  1265  3680 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-24 17:38:57.917  1265  3680 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-24 17:38:57.917  1265  3680 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-24 17:38:57.917  1265  3680 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-24 17:38:57.917  1265  3680 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-24 17:38:57.917  1265  3680 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-24 17:38:57.917  1265  3680 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-24 17:38:57.917  1265  3680 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-24 17:38:57.955   823  1153 I ActivityManager: Killing 2756:com.android.vending/u0a19 (adj 15): empty #17
,03-24 17:38:58.284  1265  3680 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,03-24 17:38:58.284  1265  3680 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 17:38:58.285  1265  3680 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 17:38:58.285  1265  3680 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,03-24 17:38:58.293  1265  3680 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,03-24 17:38:58.342  1265  3680 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-24 17:38:58.342  1265  3680 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-24 17:38:58.342  1265  3680 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-24 17:38:58.342  1265  3680 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-24 17:38:58.342  1265  3680 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-24 17:38:58.342  1265  3680 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-24 17:38:58.342  1265  3680 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-24 17:38:58.342  1265  3680 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-24 17:38:58.342  1265  3680 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-24 17:38:58.342  1265  3680 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-24 17:38:58.342  1265  3680 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-24 17:38:58.342  1265  3680 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-24 17:38:58.342  1265  3680 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-24 17:38:58.523  1265  3680 W Uploader: No account for auth token provided
,03-24 17:38:58.694  1265  3680 W Uploader: No account for auth token provided
,03-24 17:38:58.815  1265  3680 W Uploader: No account for auth token provided
,03-24 17:38:59.002  1265  3680 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
03-24 17:38:59.002  1265  3680 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 17:38:59.002  1265  3680 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 17:38:59.002  1265  3680 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 17:38:59.006  1265  3680 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,03-24 17:38:59.044  1265  3680 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-24 17:38:59.044  1265  3680 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-24 17:38:59.044  1265  3680 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-24 17:38:59.044  1265  3680 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-24 17:38:59.044  1265  3680 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-24 17:38:59.044  1265  3680 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-24 17:38:59.044  1265  3680 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-24 17:38:59.044  1265  3680 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-24 17:38:59.044  1265  3680 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-24 17:38:59.044  1265  3680 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-24 17:38:59.044  1265  3680 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-24 17:38:59.044  1265  3680 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-24 17:38:59.044  1265  3680 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-24 17:38:59.231  1265  3680 W Uploader: No account for auth token provided
,03-24 17:38:59.333  1265  3680 W Uploader: No account for auth token provided
,03-24 17:38:59.441  1265  3680 W Uploader:  no longer exists, so no auth token.
,03-24 17:38:59.554  1265  3680 W Uploader: No account for auth token provided,
,03-24 17:38:59.712  1265  3680 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,03-24 17:38:59.712  1265  3680 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
03-24 17:38:59.712  1265  3680 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 17:38:59.713  1265  3680 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 17:38:59.734  1265  3680 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 17:38:59.783  1265  3680 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-24 17:38:59.783  1265  3680 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-24 17:38:59.783  1265  3680 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-24 17:38:59.783  1265  3680 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-24 17:38:59.783  1265  3680 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-24 17:38:59.783  1265  3680 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-24 17:38:59.783  1265  3680 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-24 17:38:59.783  1265  3680 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-24 17:38:59.783  1265  3680 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-24 17:38:59.783  1265  3680 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-24 17:38:59.783  1265  3680 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-24 17:38:59.783  1265  3680 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-24 17:38:59.783  1265  3680 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-24 17:39:00.110  1265  3680 W Uploader: No account for auth token provided
,03-24 17:39:00.145   823  1151 I art     : Explicit concurrent mark sweep GC freed 19002(890KB) AllocSpace objects, 3(236KB) LOS objects, 31% free, 34MB/50MB, paused 1.363ms total 92.570ms
,03-24 17:39:00.194   823  1154 I ActivityManager: Start proc 3683:com.android.vending/u0a19 for service com.android.vending/com.google.android.finsky.services.ContentFiltersService
,03-24 17:39:00.201  1265  3680 W Uploader: No account for auth token provided
,03-24 17:39:00.298  3683  3683 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,03-24 17:39:00.344  1265  3680 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,03-24 17:39:00.344  1265  3680 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 17:39:00.344  1265  3680 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 17:39:00.344  1265  3680 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 17:39:00.348  1265  3680 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 17:39:00.373  1265  3680 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-24 17:39:00.373  1265  3680 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-24 17:39:00.373  1265  3680 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-24 17:39:00.373  1265  3680 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-24 17:39:00.373  1265  3680 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-24 17:39:00.373  1265  3680 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-24 17:39:00.373  1265  3680 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-24 17:39:00.373  1265  3680 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-24 17:39:00.373  1265  3680 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-24 17:39:00.373  1265  3680 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-24 17:39:00.373  1265  3680 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-24 17:39:00.373  1265  3680 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-24 17:39:00.373  1265  3680 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-24 17:39:00.383  3683  3683 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,03-24 17:39:00.465   823  1154 I ActivityManager: Start proc 3719:com.google.android.gms:car/u0a11 for service com.google.android.gms/.car.CarService
,03-24 17:39:00.478  3683  3683 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
03-24 17:39:00.478  3683  3683 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-24 17:39:00.504  3719  3719 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-24 17:39:00.504  3719  3719 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-24 17:39:00.523   823  1151 I ActivityManager: Killing 2941:com.google.android.music:main/u0a66 (adj 15): empty #17
,03-24 17:39:00.528  3683  3698 D Finsky  : [374] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,03-24 17:39:00.534  3719  3719 I MultiDex: VM with version 2.1.0 has multidex support
03-24 17:39:00.534  3719  3719 I MultiDex: install
03-24 17:39:00.534  3719  3719 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,03-24 17:39:00.749  3273  3332 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
03-24 17:39:00.749  3273  3332 I jxcore-log: 
,03-24 17:39:00.757  1265  1265 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 17:39:00.773  3683  3683 D Finsky  : [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
03-24 17:39:00.773  3683  3683 D Finsky  : [1] 2.run: Finished loading 1 libraries.
,03-24 17:39:00.778  3719  3719 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
03-24 17:39:00.781  3683  3683 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,03-24 17:39:00.796  3683  3683 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,03-24 17:39:00.818  1265  1282 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,03-24 17:39:00.818  1265  1282 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 17:39:00.818  1265  1282 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 17:39:00.818  1265  1282 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 17:39:00.821  1265  1282 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 17:39:00.833  3719  3719 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-24 17:39:00.837  1265  2115 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,03-24 17:39:00.840  3683  3698 D Finsky  : [374] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,03-24 17:39:00.841  1265  1265 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-24 17:39:00.846  1814  1814 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,03-24 17:39:00.901   823  1417 I ActivityManager: Start proc 3747:com.google.android.gms.wearable/u0a11 for service com.google.android.gms/.wearable.service.WearableService
,03-24 17:39:00.926   371   371 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 332us total 26.110ms
,03-24 17:39:00.927  1814  3762 D LocationInitializer: Restart initialization of location
,03-24 17:39:00.932  3747  3747 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-24 17:39:00.933  3747  3747 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-24 17:39:00.941   371   371 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 325us total 13.730ms
,03-24 17:39:00.954  3747  3747 I MultiDex: VM with version 2.1.0 has multidex support
03-24 17:39:00.954  3747  3747 I MultiDex: install
03-24 17:39:00.954  3747  3747 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,03-24 17:39:00.966   371   371 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 234us total 22.565ms
,03-24 17:39:00.973  3747  3747 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,03-24 17:39:00.987  1265  2086 I art     : Explicit concurrent mark sweep GC freed 47257(2MB) AllocSpace objects, 7(684KB) LOS objects, 36% free, 27MB/43MB, paused 1.055ms total 34.053ms
,03-24 17:39:01.014  3747  3747 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-24 17:39:01.018  1265  2118 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,03-24 17:39:01.022  1265  1265 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-24 17:39:01.024  1814  1829 I art     : Explicit concurrent mark sweep GC freed 18224(1225KB) AllocSpace objects, 16(256KB) LOS objects, 35% free, 28MB/44MB, paused 1.996ms total 34.931ms
03-24 17:39:01.025  1814  1814 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,03-24 17:39:01.030  3747  3747 D WearableService: callingUid 10011, callindPid: 3747
,03-24 17:39:01.063  1814  3771 D LocationInitializer: Restart initialization of location
,03-24 17:39:01.081  1842  2076 E MDM     : [144] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,03-24 17:39:01.084  1842  2076 E MDM     : [144] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,03-24 17:39:01.207  3683  3683 V Finsky  : [1] GearheadStateMonitor.onReady: sIsProjecting:false
,03-24 17:39:01.208  3273  3332 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
03-24 17:39:01.208  3273  3332 I jxcore-log: 
,03-24 17:39:01.218  3273  3332 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
03-24 17:39:01.218  3273  3332 I jxcore-log: 
,03-24 17:39:01.222  3273  3332 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
03-24 17:39:01.222  3273  3332 I jxcore-log: 
,03-24 17:39:01.259  3273  3332 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
03-24 17:39:01.259  3273  3332 I jxcore-log: 
,03-24 17:39:01.273  3273  3332 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
03-24 17:39:01.273  3273  3332 I jxcore-log: 
,03-24 17:39:01.276  3273  3332 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js,
03-24 17:39:01.276  3273  3332 I jxcore-log: 
,03-24 17:39:01.397  3683  3683 D Finsky  : [1] DailyHygiene.onStartCommand: Beginning daily hygiene,
,03-24 17:39:01.429  1265  1265 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 17:39:01.497  1265  1727 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
03-24 17:39:01.498  1265  1727 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 17:39:01.498  1265  1727 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 17:39:01.498  1265  1727 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 17:39:01.502  1265  1727 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 17:39:01.513  3683  3683 W Finsky  : [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,03-24 17:39:01.520  1265  1265 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 17:39:01.546  1265  2584 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket,
03-24 17:39:01.546  1265  2584 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 17:39:01.546  1265  2584 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-24 17:39:01.546  1265  2584 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 17:39:01.551  1265  2584 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,03-24 17:39:01.576  1265  1265 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 17:39:01.625  1265  1727 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
03-24 17:39:01.625  1265  1727 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 17:39:01.625  1265  1727 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 17:39:01.626  1265  1727 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 17:39:01.631  1265  1727 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 17:39:01.648  3683  3683 W Finsky  : [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,03-24 17:39:01.908  1265  1265 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 17:39:01.964  1265  1282 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,03-24 17:39:01.965  1265  1282 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 17:39:01.965  1265  1282 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 17:39:01.965  1265  1282 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 17:39:01.976  1265  1282 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 17:39:02.016  3683  3683 W Finsky  : [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,03-24 17:39:02.023  3683  3683 D Finsky  : [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,03-24 17:39:02.043  3683  3683 D Finsky  : [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,03-24 17:39:02.050  3683  3683 D Finsky  : [1] DailyHygiene.reschedule: Scheduling new run in 741 minutes (failures=5)
,03-24 17:39:02.076  1842  1899 D DeviceConnectionService: client connected with version: 7571000
,03-24 17:39:03.271  3273  3332 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
03-24 17:39:03.271  3273  3332 I jxcore-log: 
,03-24 17:39:03.288  3273  3332 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js,
03-24 17:39:03.288  3273  3332 I jxcore-log: 
,03-24 17:39:03.297  3273  3332 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
03-24 17:39:03.297  3273  3332 I jxcore-log: 
,03-24 17:39:03.422  3273  3332 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
03-24 17:39:03.422  3273  3332 I jxcore-log: 
,03-24 17:39:03.476  3273  3332 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
03-24 17:39:03.476  3273  3332 I jxcore-log: 
,03-24 17:39:03.523  3273  3332 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
03-24 17:39:03.523  3273  3332 I jxcore-log: 
,03-24 17:39:03.659  3273  3332 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
03-24 17:39:03.659  3273  3332 I jxcore-log: 
,03-24 17:39:03.664  3273  3332 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
03-24 17:39:03.664  3273  3332 I jxcore-log: 
,03-24 17:39:03.670  3273  3332 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
03-24 17:39:03.670  3273  3332 I jxcore-log: 
,03-24 17:39:03.686  3273  3332 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
03-24 17:39:03.686  3273  3332 I jxcore-log: 
,03-24 17:39:03.704  3273  3332 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
03-24 17:39:03.704  3273  3332 I jxcore-log: 
,03-24 17:39:03.803  3273  3332 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
03-24 17:39:03.803  3273  3332 I jxcore-log: 
,03-24 17:39:03.809  3273  3332 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
03-24 17:39:03.809  3273  3332 I jxcore-log: 
,03-24 17:39:03.834  3273  3332 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
03-24 17:39:03.834  3273  3332 I jxcore-log: 
,03-24 17:39:04.930  3273  3332 I jxcore-log: TAP version 13
03-24 17:39:04.930  3273  3332 I jxcore-log: 
,03-24 17:39:04.934  3273  3332 I jxcore-log: # setup
03-24 17:39:04.934  3273  3332 I jxcore-log: 
,03-24 17:39:05.253  3273  3332 I jxcore-log: # 1. calling createNativeListener directly rejects
03-24 17:39:05.253  3273  3332 I jxcore-log: 
,03-24 17:39:05.871  3273  3332 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 17:39:05.871  3273  3332 I jxcore-log: 
,03-24 17:39:05.876  3273  3332 I jxcore-log: DEBUG createNativeListener: listening 53123,
03-24 17:39:05.876  3273  3332 I jxcore-log: 
,03-24 17:39:05.882  3273  3332 I jxcore-log: ok 1 Should throw
03-24 17:39:05.882  3273  3332 I jxcore-log: 
03-24 17:39:05.885  3273  3332 I jxcore-log: # teardown
03-24 17:39:05.885  3273  3332 I jxcore-log: 
,03-24 17:39:06.094  3273  3332 I jxcore-log: # setup
03-24 17:39:06.094  3273  3332 I jxcore-log: 
,03-24 17:39:06.098   823  1413 I ActivityManager: Killing 3409:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,03-24 17:39:06.335  3273  3332 I jxcore-log: # 2. emits incomingConnectionState
03-24 17:39:06.335  3273  3332 I jxcore-log: 
,03-24 17:39:06.341   823  1153 I ActivityManager: Killing 3496:com.google.android.apps.magazines/u0a67 (adj 15): empty #17
,03-24 17:39:06.491  3273  3332 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 17:39:06.491  3273  3332 I jxcore-log: 
,03-24 17:39:06.495  3273  3332 I jxcore-log: DEBUG createNativeListener: listening 58585,
,03-24 17:39:06.495  3273  3332 I jxcore-log: 
,03-24 17:39:06.503  3273  3332 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 17:39:06.503  3273  3332 I jxcore-log: 
,03-24 17:39:06.506  3273  3332 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 17:39:06.506  3273  3332 I jxcore-log: 
,03-24 17:39:06.515  3273  3332 I jxcore-log: DEBUG createNativeListener: new mux
03-24 17:39:06.515  3273  3332 I jxcore-log: 
,03-24 17:39:06.520  3273  3332 I jxcore-log: ok 2 initial connection state should be CONNECTED
03-24 17:39:06.520  3273  3332 I jxcore-log: 
,03-24 17:39:06.535  3273  3332 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 17:39:06.535  3273  3332 I jxcore-log: 
,03-24 17:39:06.536  3273  3332 I jxcore-log: ok 3 final connection state should be DISCONNECTED
03-24 17:39:06.536  3273  3332 I jxcore-log: 
,03-24 17:39:06.542  3273  3332 I jxcore-log: # teardown
03-24 17:39:06.542  3273  3332 I jxcore-log: 
,03-24 17:39:06.687  3273  3332 I jxcore-log: # setup,
03-24 17:39:06.687  3273  3332 I jxcore-log: 
,03-24 17:39:06.818  3273  3332 I jxcore-log: # 3. emits routerPortConnectionFailed
03-24 17:39:06.818  3273  3332 I jxcore-log: 
,03-24 17:39:06.956  3273  3332 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 17:39:06.956  3273  3332 I jxcore-log: 
,03-24 17:39:06.959  3273  3332 I jxcore-log: DEBUG createNativeListener: listening 46591
03-24 17:39:06.959  3273  3332 I jxcore-log: 
,03-24 17:39:06.965  3273  3332 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 17:39:06.965  3273  3332 I jxcore-log: 
,03-24 17:39:06.966  3273  3332 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 17:39:06.966  3273  3332 I jxcore-log: 
,03-24 17:39:06.967  3273  3332 I jxcore-log: DEBUG createNativeListener: new mux
03-24 17:39:06.967  3273  3332 I jxcore-log: 
,03-24 17:39:06.993  3273  3332 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 17:39:06.993  3273  3332 I jxcore-log: 
,03-24 17:39:06.996  3273  3332 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 17:39:06.996  3273  3332 I jxcore-log: 
,03-24 17:39:07.000  3273  3332 I jxcore-log: DEBUG createNativeListener: 
03-24 17:39:07.000  3273  3332 I jxcore-log: 
,03-24 17:39:07.001  3273  3332 I jxcore-log: ok 4 tried to connect to right port
03-24 17:39:07.001  3273  3332 I jxcore-log: 
,03-24 17:39:07.001  3273  3332 I jxcore-log: ok 5 failed due to refused connection
03-24 17:39:07.001  3273  3332 I jxcore-log: 
,03-24 17:39:07.002  3273  3332 I jxcore-log: ok 6 routerPortConnectionFailed is emitted
03-24 17:39:07.002  3273  3332 I jxcore-log: 
,03-24 17:39:07.006  3273  3332 I jxcore-log: # teardown
03-24 17:39:07.006  3273  3332 I jxcore-log: 
03-24 17:39:07.007  3273  3332 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 17:39:07.007  3273  3332 I jxcore-log: 
,03-24 17:39:07.231  3273  3332 I jxcore-log: DEBUG createNativeListener: mux close
03-24 17:39:07.231  3273  3332 I jxcore-log: 
,03-24 17:39:07.236  3273  3332 I jxcore-log: # setup
03-24 17:39:07.236  3273  3332 I jxcore-log: 
,03-24 17:39:07.237  3273  3332 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 17:39:07.237  3273  3332 I jxcore-log: 
,03-24 17:39:07.447  3273  3332 I jxcore-log: # 4. native server connections all up
03-24 17:39:07.447  3273  3332 I jxcore-log: 
,03-24 17:39:07.605  3273  3332 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 17:39:07.605  3273  3332 I jxcore-log: 
,03-24 17:39:07.614  3273  3332 I jxcore-log: DEBUG createNativeListener: listening 53146
03-24 17:39:07.614  3273  3332 I jxcore-log: 
,03-24 17:39:07.626  3273  3332 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 17:39:07.626  3273  3332 I jxcore-log: 
,03-24 17:39:07.627  3273  3332 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 17:39:07.627  3273  3332 I jxcore-log: 
,03-24 17:39:07.629  3273  3332 I jxcore-log: DEBUG createNativeListener: new mux
03-24 17:39:07.629  3273  3332 I jxcore-log: 
,03-24 17:39:07.656  3273  3332 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 17:39:07.656  3273  3332 I jxcore-log: 
,03-24 17:39:07.660  3273  3332 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 17:39:07.660  3273  3332 I jxcore-log: 
,03-24 17:39:07.664  3273  3332 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 17:39:07.664  3273  3332 I jxcore-log: 
,03-24 17:39:07.667  3273  3332 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 17:39:07.667  3273  3332 I jxcore-log: 
,03-24 17:39:07.687  3273  3332 I jxcore-log: ok 7 Send/recvd #1 should be equal length
03-24 17:39:07.687  3273  3332 I jxcore-log: 
,03-24 17:39:07.688  3273  3332 I jxcore-log: ok 8 Send/recvd #1 should be same
03-24 17:39:07.688  3273  3332 I jxcore-log: 
,03-24 17:39:07.690  3273  3332 I jxcore-log: ok 9 Send/recvd #2 should be equal length
03-24 17:39:07.690  3273  3332 I jxcore-log: 
03-24 17:39:07.691  3273  3332 I jxcore-log: ok 10 Send/recvd #2 should be same
03-24 17:39:07.691  3273  3332 I jxcore-log: 
,03-24 17:39:07.694  3273  3332 I jxcore-log: ok 11 Should be exactly 2 client sockets
03-24 17:39:07.694  3273  3332 I jxcore-log: 
,03-24 17:39:07.710  3273  3332 I jxcore-log: # teardown
03-24 17:39:07.710  3273  3332 I jxcore-log: 
,03-24 17:39:07.853  2157  2223 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 17:39:07.870  3273  3332 I jxcore-log: DEBUG createNativeListener: stream close:
,03-24 17:39:07.870  3273  3332 I jxcore-log: 
,03-24 17:39:07.875  3273  3332 I jxcore-log: DEBUG createNativeListener: stream close:
,03-24 17:39:07.875  3273  3332 I jxcore-log: 
,03-24 17:39:07.879  3273  3332 I jxcore-log: DEBUG createNativeListener: mux close
,03-24 17:39:07.879  3273  3332 I jxcore-log: 
,03-24 17:39:07.884  3273  3332 I jxcore-log: # setup
03-24 17:39:07.884  3273  3332 I jxcore-log: 
,03-24 17:39:07.886  3273  3332 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 17:39:07.886  3273  3332 I jxcore-log: 
,03-24 17:39:08.024  3273  3332 I jxcore-log: # 5. native server - closing incoming stream cleans outgoing socket
03-24 17:39:08.024  3273  3332 I jxcore-log: 
,03-24 17:39:08.184  3273  3332 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 17:39:08.184  3273  3332 I jxcore-log: 
03-24 17:39:08.187  3273  3332 I jxcore-log: DEBUG createNativeListener: listening 34856
03-24 17:39:08.187  3273  3332 I jxcore-log: 
,03-24 17:39:08.192  3273  3332 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 17:39:08.192  3273  3332 I jxcore-log: 
03-24 17:39:08.194  3273  3332 I jxcore-log: DEBUG createNativeListener: creating incoming mux,
03-24 17:39:08.194  3273  3332 I jxcore-log: 
03-24 17:39:08.195  3273  3332 I jxcore-log: DEBUG createNativeListener: new mux
03-24 17:39:08.195  3273  3332 I jxcore-log: 
,03-24 17:39:08.207  3273  3332 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 17:39:08.207  3273  3332 I jxcore-log: 
,03-24 17:39:08.210  3273  3332 I jxcore-log: DEBUG createNativeListener: new outgoing socket
,03-24 17:39:08.210  3273  3332 I jxcore-log: 
,03-24 17:39:08.224  3273  3332 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 17:39:08.224  3273  3332 I jxcore-log: 
,03-24 17:39:08.236  3273  3332 I jxcore-log: ok 12 socket shouldn't close until after stream
03-24 17:39:08.236  3273  3332 I jxcore-log: 
,03-24 17:39:08.237  3273  3332 I jxcore-log: ok 13 incoming remains open
03-24 17:39:08.237  3273  3332 I jxcore-log: 
,03-24 17:39:08.243  3273  3332 I jxcore-log: # teardown
03-24 17:39:08.243  3273  3332 I jxcore-log: 
,03-24 17:39:08.380  3273  3332 I jxcore-log: DEBUG createNativeListener: mux close
03-24 17:39:08.380  3273  3332 I jxcore-log: 
,03-24 17:39:08.388  3273  3332 I jxcore-log: # setup
03-24 17:39:08.388  3273  3332 I jxcore-log: 
,03-24 17:39:08.389  3273  3332 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 17:39:08.389  3273  3332 I jxcore-log: 
,03-24 17:39:08.527  3273  3332 I jxcore-log: # 6. native server - closing incoming connection cleans outgoing socket
,03-24 17:39:08.527  3273  3332 I jxcore-log: 
,03-24 17:39:08.644  3273  3332 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 17:39:08.644  3273  3332 I jxcore-log: ,
,03-24 17:39:08.649  3273  3332 I jxcore-log: DEBUG createNativeListener: listening 52190
,03-24 17:39:08.649  3273  3332 I jxcore-log: 
,03-24 17:39:08.655  3273  3332 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 17:39:08.655  3273  3332 I jxcore-log: 
,03-24 17:39:08.656  3273  3332 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 17:39:08.656  3273  3332 I jxcore-log: 
,03-24 17:39:08.658  3273  3332 I jxcore-log: DEBUG createNativeListener: new mux
03-24 17:39:08.658  3273  3332 I jxcore-log: 
,03-24 17:39:08.669  3273  3332 I jxcore-log: ok 14 we should not have gotten an error
03-24 17:39:08.669  3273  3332 I jxcore-log: 
,03-24 17:39:08.674  3273  3332 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 17:39:08.674  3273  3332 I jxcore-log: 
,03-24 17:39:08.679  3273  3332 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 17:39:08.679  3273  3332 I jxcore-log: 
,03-24 17:39:08.690  3273  3332 I jxcore-log: DEBUG createNativeListener: stream close:,
03-24 17:39:08.690  3273  3332 I jxcore-log: 
,03-24 17:39:08.693  3273  3332 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 17:39:08.693  3273  3332 I jxcore-log: 
,03-24 17:39:08.701  3273  3332 I jxcore-log: ok 15 socket shouldn't close until after incoming
03-24 17:39:08.701  3273  3332 I jxcore-log: 
,03-24 17:39:08.701  3273  3332 I jxcore-log: ok 16 incoming is cleaned up
03-24 17:39:08.701  3273  3332 I jxcore-log: 
,03-24 17:39:08.708  3273  3332 I jxcore-log: # teardown
03-24 17:39:08.708  3273  3332 I jxcore-log: 
,03-24 17:39:08.869  3273  3332 I jxcore-log: # setup
03-24 17:39:08.869  3273  3332 I jxcore-log: 
,03-24 17:39:09.081  3273  3332 I jxcore-log: # 7. native server - closing outgoing socket cleans associated mux stream
03-24 17:39:09.081  3273  3332 I jxcore-log: 
,03-24 17:39:09.219  3273  3332 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 17:39:09.219  3273  3332 I jxcore-log: 
,03-24 17:39:09.226  3273  3332 I jxcore-log: DEBUG createNativeListener: listening 60626
03-24 17:39:09.226  3273  3332 I jxcore-log: 
,03-24 17:39:09.232  3273  3332 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 17:39:09.232  3273  3332 I jxcore-log: 
,03-24 17:39:09.234  3273  3332 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 17:39:09.234  3273  3332 I jxcore-log: 
,03-24 17:39:09.237  3273  3332 I jxcore-log: DEBUG createNativeListener: new mux
03-24 17:39:09.237  3273  3332 I jxcore-log: 
,03-24 17:39:09.248  3273  3332 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 17:39:09.248  3273  3332 I jxcore-log: 
,03-24 17:39:09.251  3273  3332 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 17:39:09.251  3273  3332 I jxcore-log: 
,03-24 17:39:09.266  3273  3332 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 17:39:09.266  3273  3332 I jxcore-log: 
,03-24 17:39:09.276  3273  3332 I jxcore-log: ok 17 stream was closed
03-24 17:39:09.276  3273  3332 I jxcore-log: 
,03-24 17:39:09.277  3273  3332 I jxcore-log: ok 18 incoming should survive
03-24 17:39:09.277  3273  3332 I jxcore-log: 
03-24 17:39:09.277  3273  3332 I jxcore-log: ok 19 mux should have no streams
03-24 17:39:09.277  3273  3332 I jxcore-log: 
,03-24 17:39:09.285  3273  3332 I jxcore-log: # teardown
03-24 17:39:09.285  3273  3332 I jxcore-log: 
,03-24 17:39:09.405  3273  3332 I jxcore-log: DEBUG createNativeListener: mux close
03-24 17:39:09.405  3273  3332 I jxcore-log: 
,03-24 17:39:09.411  3273  3332 I jxcore-log: # setup
,03-24 17:39:09.411  3273  3332 I jxcore-log: 
03-24 17:39:09.412  3273  3332 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 17:39:09.412  3273  3332 I jxcore-log: 
,03-24 17:39:09.546  3273  3332 I jxcore-log: # 8. native server - closing the whole server cleans everything up
03-24 17:39:09.546  3273  3332 I jxcore-log: 
,03-24 17:39:09.640  3273  3332 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 17:39:09.640  3273  3332 I jxcore-log: ,
,03-24 17:39:09.648  3273  3332 I jxcore-log: DEBUG createNativeListener: listening 55118
03-24 17:39:09.648  3273  3332 I jxcore-log: 
,03-24 17:39:09.654  3273  3332 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 17:39:09.654  3273  3332 I jxcore-log: 
,03-24 17:39:09.655  3273  3332 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 17:39:09.655  3273  3332 I jxcore-log: 
,03-24 17:39:09.657  3273  3332 I jxcore-log: DEBUG createNativeListener: new mux
03-24 17:39:09.657  3273  3332 I jxcore-log: 
,03-24 17:39:09.667  3273  3332 I jxcore-log: ok 20 we should not have gotten an error
03-24 17:39:09.667  3273  3332 I jxcore-log: 
,03-24 17:39:09.674  3273  3332 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 17:39:09.674  3273  3332 I jxcore-log: 
,03-24 17:39:09.678  3273  3332 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 17:39:09.678  3273  3332 I jxcore-log: 
,03-24 17:39:09.688  3273  3332 I jxcore-log: ok 21 Buffers are identical
03-24 17:39:09.688  3273  3332 I jxcore-log: 
,03-24 17:39:09.690  3273  3332 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 17:39:09.690  3273  3332 I jxcore-log: 
,03-24 17:39:09.694  3273  3332 I jxcore-log: DEBUG createNativeListener: mux close
03-24 17:39:09.694  3273  3332 I jxcore-log: 
,03-24 17:39:09.698  3273  3332 I jxcore-log: ok 22 native server is nulled out
03-24 17:39:09.698  3273  3332 I jxcore-log: 
,03-24 17:39:09.698  3273  3332 I jxcore-log: ok 23 native server should be closed
03-24 17:39:09.698  3273  3332 I jxcore-log: 
,03-24 17:39:09.698  3273  3332 I jxcore-log: ok 24 incoming has been removed
03-24 17:39:09.698  3273  3332 I jxcore-log: 
03-24 17:39:09.699  3273  3332 I jxcore-log: ok 25 Incoming should be done
03-24 17:39:09.699  3273  3332 I jxcore-log: 
03-24 17:39:09.699  3273  3332 I jxcore-log: ok 26 The mux object should be closed
03-24 17:39:09.699  3273  3332 I jxcore-log: ,
03-24 17:39:09.699  3273  3332 I jxcore-log: ok 27 The mux stream should be closed
03-24 17:39:09.699  3273  3332 I jxcore-log: 
03-24 17:39:09.701  3273  3332 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 17:39:09.701  3273  3332 I jxcore-log: 
,03-24 17:39:09.717  3273  3332 I jxcore-log: # teardown
03-24 17:39:09.717  3273  3332 I jxcore-log: 
,03-24 17:39:09.864  3273  3332 I jxcore-log: # setup
03-24 17:39:09.864  3273  3332 I jxcore-log: 
,03-24 17:39:10.004  3273  3332 I jxcore-log: # 9. native server - we can get a ton of connections and data through and still clean up the server completely
03-24 17:39:10.004  3273  3332 I jxcore-log: 
,03-24 17:39:10.162  3273  3332 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 17:39:10.162  3273  3332 I jxcore-log: 
,03-24 17:39:10.171  3273  3332 I jxcore-log: DEBUG createNativeListener: listening 45788
03-24 17:39:10.171  3273  3332 I jxcore-log: 
,03-24 17:39:10.197  3273  3332 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 17:39:10.197  3273  3332 I jxcore-log: 
,03-24 17:39:10.198  3273  3332 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 17:39:10.198  3273  3332 I jxcore-log: 
,03-24 17:39:10.200  3273  3332 I jxcore-log: DEBUG createNativeListener: new mux
03-24 17:39:10.200  3273  3332 I jxcore-log: 
,03-24 17:39:10.203  3273  3332 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 17:39:10.203  3273  3332 I jxcore-log: 
,03-24 17:39:10.204  3273  3332 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 17:39:10.204  3273  3332 I jxcore-log: 
,03-24 17:39:10.206  3273  3332 I jxcore-log: DEBUG createNativeListener: new mux
03-24 17:39:10.206  3273  3332 I jxcore-log: 
03-24 17:39:10.208  3273  3332 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 17:39:10.208  3273  3332 I jxcore-log: 
03-24 17:39:10.209  3273  3332 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 17:39:10.209  3273  3332 I jxcore-log: 
,03-24 17:39:10.210  3273  3332 I jxcore-log: DEBUG createNativeListener: new mux
03-24 17:39:10.210  3273  3332 I jxcore-log: 
03-24 17:39:10.214  3273  3332 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 17:39:10.214  3273  3332 I jxcore-log: 
03-24 17:39:10.215  3273  3332 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 17:39:10.215  3273  3332 I jxcore-log: 
,03-24 17:39:10.216  3273  3332 I jxcore-log: DEBUG createNativeListener: new mux
03-24 17:39:10.216  3273  3332 I jxcore-log: 
,03-24 17:39:10.220  3273  3332 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 17:39:10.220  3273  3332 I jxcore-log: 
03-24 17:39:10.221  3273  3332 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 17:39:10.221  3273  3332 I jxcore-log: 
,03-24 17:39:10.223  3273  3332 I jxcore-log: DEBUG createNativeListener: new mux
03-24 17:39:10.223  3273  3332 I jxcore-log: 
,03-24 17:39:10.225  3273  3332 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 17:39:10.225  3273  3332 I jxcore-log: 
,03-24 17:39:10.229  3273  3332 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 17:39:10.229  3273  3332 I jxcore-log: 
,03-24 17:39:10.230  3273  3332 I jxcore-log: DEBUG createNativeListener: new mux
03-24 17:39:10.230  3273  3332 I jxcore-log: 
,03-24 17:39:10.233  3273  3332 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 17:39:10.233  3273  3332 I jxcore-log: 
,03-24 17:39:10.233  3273  3332 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 17:39:10.233  3273  3332 I jxcore-log: 
,03-24 17:39:10.234  3273  3332 I jxcore-log: DEBUG createNativeListener: new mux
03-24 17:39:10.234  3273  3332 I jxcore-log: 
03-24 17:39:10.236  3273  3332 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 17:39:10.236  3273  3332 I jxcore-log: 
03-24 17:39:10.236  3273  3332 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 17:39:10.236  3273  3332 I jxcore-log: 
,03-24 17:39:10.237  3273  3332 I jxcore-log: DEBUG createNativeListener: new mux
03-24 17:39:10.237  3273  3332 I jxcore-log: 
03-24 17:39:10.239  3273  3332 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 17:39:10.239  3273  3332 I jxcore-log: 
03-24 17:39:10.239  3273  3332 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 17:39:10.239  3273  3332 I jxcore-log: 
,03-24 17:39:10.240  3273  3332 I jxcore-log: DEBUG createNativeListener: new mux
03-24 17:39:10.240  3273  3332 I jxcore-log: 
03-24 17:39:10.241  3273  3332 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 17:39:10.241  3273  3332 I jxcore-log: 
03-24 17:39:10.242  3273  3332 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 17:39:10.242  3273  3332 I jxcore-log: 
,03-24 17:39:10.243  3273  3332 I jxcore-log: DEBUG createNativeListener: new mux
03-24 17:39:10.243  3273  3332 I jxcore-log: 
,03-24 17:39:10.331  3273  3332 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 17:39:10.331  3273  3332 I jxcore-log: 
,03-24 17:39:10.334  3273  3332 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 17:39:10.334  3273  3332 I jxcore-log: 
,03-24 17:39:10.336  3273  3332 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 17:39:10.336  3273  3332 I jxcore-log: 
,03-24 17:39:10.337  3273  3332 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 17:39:10.337  3273  3332 I jxcore-log: 
,03-24 17:39:10.339  3273  3332 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 17:39:10.339  3273  3332 I jxcore-log: 
03-24 17:39:10.340  3273  3332 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 17:39:10.340  3273  3332 I jxcore-log: 
,03-24 17:39:10.342  3273  3332 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 17:39:10.342  3273  3332 I jxcore-log: 
,03-24 17:39:10.344  3273  3332 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 17:39:10.344  3273  3332 I jxcore-log: 
,03-24 17:39:10.347  3273  3332 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 17:39:10.347  3273  3332 I jxcore-log: 
,03-24 17:39:10.348  3273  3332 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 17:39:10.348  3273  3332 I jxcore-log: 
,03-24 17:39:10.350  3273  3332 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 17:39:10.350  3273  3332 I jxcore-log: 
,03-24 17:39:10.351  3273  3332 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 17:39:10.351  3273  3332 I jxcore-log: 
,03-24 17:39:10.352  3273  3332 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 17:39:10.352  3273  3332 I jxcore-log: 
,03-24 17:39:10.354  3273  3332 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 17:39:10.354  3273  3332 I jxcore-log: 
,03-24 17:39:10.355  3273  3332 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 17:39:10.355  3273  3332 I jxcore-log: 
,03-24 17:39:10.357  3273  3332 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 17:39:10.357  3273  3332 I jxcore-log: 
,03-24 17:39:10.359  3273  3332 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 17:39:10.359  3273  3332 I jxcore-log: 
,03-24 17:39:10.360  3273  3332 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 17:39:10.360  3273  3332 I jxcore-log: 
,03-24 17:39:10.362  3273  3332 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 17:39:10.362  3273  3332 I jxcore-log: 
,03-24 17:39:10.364  3273  3332 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 17:39:10.364  3273  3332 I jxcore-log: 
,03-24 17:39:10.367  3273  3332 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 17:39:10.367  3273  3332 I jxcore-log: 
,03-24 17:39:10.369  3273  3332 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 17:39:10.369  3273  3332 I jxcore-log: 
,03-24 17:39:10.371  3273  3332 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 17:39:10.371  3273  3332 I jxcore-log: 
,03-24 17:39:10.372  3273  3332 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 17:39:10.372  3273  3332 I jxcore-log: 
,03-24 17:39:10.374  3273  3332 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 17:39:10.374  3273  3332 I jxcore-log: 
,03-24 17:39:10.375  3273  3332 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 17:39:10.375  3273  3332 I jxcore-log: 
,03-24 17:39:10.377  3273  3332 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 17:39:10.377  3273  3332 I jxcore-log: 
,03-24 17:39:10.378  3273  3332 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 17:39:10.378  3273  3332 I jxcore-log: 
,03-24 17:39:10.379  3273  3332 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 17:39:10.379  3273  3332 I jxcore-log: 
,03-24 17:39:10.380  3273  3332 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 17:39:10.380  3273  3332 I jxcore-log: 
,03-24 17:39:10.381  3273  3332 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 17:39:10.381  3273  3332 I jxcore-log: 
,03-24 17:39:10.383  3273  3332 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 17:39:10.383  3273  3332 I jxcore-log: 
,03-24 17:39:10.385  3273  3332 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 17:39:10.385  3273  3332 I jxcore-log: 
,03-24 17:39:10.386  3273  3332 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 17:39:10.386  3273  3332 I jxcore-log: 
,03-24 17:39:10.387  3273  3332 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 17:39:10.387  3273  3332 I jxcore-log: 
,03-24 17:39:10.389  3273  3332 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 17:39:10.389  3273  3332 I jxcore-log: 
,03-24 17:39:10.390  3273  3332 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 17:39:10.390  3273  3332 I jxcore-log: 
,03-24 17:39:10.391  3273  3332 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 17:39:10.391  3273  3332 I jxcore-log: 
,03-24 17:39:10.392  3273  3332 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 17:39:10.392  3273  3332 I jxcore-log: 
,03-24 17:39:10.394  3273  3332 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 17:39:10.394  3273  3332 I jxcore-log: 
,03-24 17:39:10.396  3273  3332 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 17:39:10.396  3273  3332 I jxcore-log: 
03-24 17:39:10.397  3273  3332 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 17:39:10.397  3273  3332 I jxcore-log: 
,03-24 17:39:10.398  3273  3332 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 17:39:10.398  3273  3332 I jxcore-log: 
,03-24 17:39:10.400  3273  3332 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 17:39:10.400  3273  3332 I jxcore-log: 
,03-24 17:39:10.401  3273  3332 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 17:39:10.401  3273  3332 I jxcore-log: 
,03-24 17:39:10.402  3273  3332 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 17:39:10.402  3273  3332 I jxcore-log: 
03-24 17:39:10.403  3273  3332 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 17:39:10.403  3273  3332 I jxcore-log: 
,03-24 17:39:10.405  3273  3332 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 17:39:10.405  3273  3332 I jxcore-log: 
,03-24 17:39:10.413  3273  3332 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 17:39:10.413  3273  3332 I jxcore-log: 
,03-24 17:39:10.415  3273  3332 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 17:39:10.415  3273  3332 I jxcore-log: 
,03-24 17:39:10.416  3273  3332 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 17:39:10.416  3273  3332 I jxcore-log: 
,03-24 17:39:10.417  3273  3332 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 17:39:10.417  3273  3332 I jxcore-log: 
,03-24 17:39:10.418  3273  3332 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 17:39:10.418  3273  3332 I jxcore-log: 
03-24 17:39:10.419  3273  3332 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 17:39:10.419  3273  3332 I jxcore-log: 
,03-24 17:39:10.420  3273  3332 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 17:39:10.420  3273  3332 I jxcore-log: 
,03-24 17:39:10.421  3273  3332 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 17:39:10.421  3273  3332 I jxcore-log: 
,03-24 17:39:10.423  3273  3332 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 17:39:10.423  3273  3332 I jxcore-log: 
,03-24 17:39:10.425  3273  3332 I jxcore-log: DEBUG createNativeListener: new outgoing socket,
03-24 17:39:10.425  3273  3332 I jxcore-log: 
03-24 17:39:10.426  3273  3332 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 17:39:10.426  3273  3332 I jxcore-log: 
,03-24 17:39:10.428  3273  3332 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 17:39:10.428  3273  3332 I jxcore-log: 
,03-24 17:39:10.429  3273  3332 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 17:39:10.429  3273  3332 I jxcore-log: 
,03-24 17:39:10.430  3273  3332 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 17:39:10.430  3273  3332 I jxcore-log: 
,03-24 17:39:10.431  3273  3332 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 17:39:10.431  3273  3332 I jxcore-log: 
,03-24 17:39:10.432  3273  3332 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 17:39:10.432  3273  3332 I jxcore-log: 
03-24 17:39:10.434  3273  3332 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 17:39:10.434  3273  3332 I jxcore-log: 
,03-24 17:39:10.435  3273  3332 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 17:39:10.435  3273  3332 I jxcore-log: 
,03-24 17:39:10.436  3273  3332 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 17:39:10.436  3273  3332 I jxcore-log: 
,03-24 17:39:10.437  3273  3332 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 17:39:10.437  3273  3332 I jxcore-log: 
,03-24 17:39:10.438  3273  3332 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 17:39:10.438  3273  3332 I jxcore-log: 
03-24 17:39:10.440  3273  3332 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 17:39:10.440  3273  3332 I jxcore-log: 
,03-24 17:39:10.441  3273  3332 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 17:39:10.441  3273  3332 I jxcore-log: 
,03-24 17:39:10.442  3273  3332 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 17:39:10.442  3273  3332 I jxcore-log: 
,03-24 17:39:10.444  3273  3332 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 17:39:10.444  3273  3332 I jxcore-log: 
,03-24 17:39:10.445  3273  3332 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 17:39:10.445  3273  3332 I jxcore-log: 
,03-24 17:39:10.446  3273  3332 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 17:39:10.446  3273  3332 I jxcore-log: 
,03-24 17:39:10.448  3273  3332 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 17:39:10.448  3273  3332 I jxcore-log: 
,03-24 17:39:10.449  3273  3332 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 17:39:10.449  3273  3332 I jxcore-log: 
,03-24 17:39:10.450  3273  3332 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 17:39:10.450  3273  3332 I jxcore-log: 
03-24 17:39:10.451  3273  3332 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 17:39:10.451  3273  3332 I jxcore-log: 
,03-24 17:39:10.452  3273  3332 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 17:39:10.452  3273  3332 I jxcore-log: 
,03-24 17:39:10.526  3273  3332 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 17:39:10.526  3273  3332 I jxcore-log: 
,03-24 17:39:10.528  3273  3332 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 17:39:10.528  3273  3332 I jxcore-log: 
,03-24 17:39:10.529  3273  3332 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 17:39:10.529  3273  3332 I jxcore-log: 
03-24 17:39:10.530  3273  3332 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 17:39:10.530  3273  3332 I jxcore-log: 
,03-24 17:39:10.531  3273  3332 I jxcore-log: DEBUG createNativeListener: mux close
03-24 17:39:10.531  3273  3332 I jxcore-log: 
,03-24 17:39:10.533  3273  3332 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 17:39:10.533  3273  3332 I jxcore-log: 
,03-24 17:39:10.534  3273  3332 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 17:39:10.534  3273  3332 I jxcore-log: 
,03-24 17:39:10.535  3273  3332 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 17:39:10.535  3273  3332 I jxcore-log: 
03-24 17:39:10.536  3273  3332 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 17:39:10.536  3273  3332 I jxcore-log: 
,03-24 17:39:10.537  3273  3332 I jxcore-log: DEBUG createNativeListener: mux close
03-24 17:39:10.537  3273  3332 I jxcore-log: 
03-24 17:39:10.539  3273  3332 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 17:39:10.539  3273  3332 I jxcore-log: 
03-24 17:39:10.540  3273  3332 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 17:39:10.540  3273  3332 I jxcore-log: 
,03-24 17:39:10.541  3273  3332 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 17:39:10.541  3273  3332 I jxcore-log: 
03-24 17:39:10.542  3273  3332 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 17:39:10.542  3273  3332 I jxcore-log: 
03-24 17:39:10.543  3273  3332 I jxcore-log: DEBUG createNativeListener: mux close
03-24 17:39:10.543  3273  3332 I jxcore-log: 
,03-24 17:39:10.545  3273  3332 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 17:39:10.545  3273  3332 I jxcore-log: 
,03-24 17:39:10.546  3273  3332 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 17:39:10.546  3273  3332 I jxcore-log: 
03-24 17:39:10.546  3273  3332 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 17:39:10.546  3273  3332 I jxcore-log: 
,03-24 17:39:10.547  3273  3332 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 17:39:10.547  3273  3332 I jxcore-log: 
03-24 17:39:10.548  3273  3332 I jxcore-log: DEBUG createNativeListener: mux close
03-24 17:39:10.548  3273  3332 I jxcore-log: 
03-24 17:39:10.549  3273  3332 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 17:39:10.549  3273  3332 I jxcore-log: 
,03-24 17:39:10.550  3273  3332 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 17:39:10.550  3273  3332 I jxcore-log: 
03-24 17:39:10.551  3273  3332 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 17:39:10.551  3273  3332 I jxcore-log: 
,03-24 17:39:10.551  3273  3332 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 17:39:10.551  3273  3332 I jxcore-log: 
03-24 17:39:10.553  3273  3332 I jxcore-log: DEBUG createNativeListener: mux close
03-24 17:39:10.553  3273  3332 I jxcore-log: 
,03-24 17:39:10.554  3273  3332 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 17:39:10.554  3273  3332 I jxcore-log: 
,03-24 17:39:10.555  3273  3332 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 17:39:10.555  3273  3332 I jxcore-log: 
,03-24 17:39:10.556  3273  3332 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 17:39:10.556  3273  3332 I jxcore-log: 
,03-24 17:39:10.556  3273  3332 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 17:39:10.556  3273  3332 I jxcore-log: ,
03-24 17:39:10.558  3273  3332 I jxcore-log: DEBUG createNativeListener: mux close,
03-24 17:39:10.558  3273  3332 I jxcore-log: 
,03-24 17:39:10.558  3273  3332 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 17:39:10.558  3273  3332 I jxcore-log: ,
03-24 17:39:10.559  3273  3332 I jxcore-log: DEBUG createNativeListener: stream close:,
03-24 17:39:10.559  3273  3332 I jxcore-log: 
,03-24 17:39:10.560  3273  3332 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 17:39:10.560  3273  3332 I jxcore-log: 
,03-24 17:39:10.561  3273  3332 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 17:39:10.561  3273  3332 I jxcore-log: 
,03-24 17:39:10.562  3273  3332 I jxcore-log: DEBUG createNativeListener: mux close
03-24 17:39:10.562  3273  3332 I jxcore-log: 
,03-24 17:39:10.563  3273  3332 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 17:39:10.563  3273  3332 I jxcore-log: 
,03-24 17:39:10.563  3273  3332 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 17:39:10.563  3273  3332 I jxcore-log: 
,03-24 17:39:10.564  3273  3332 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 17:39:10.564  3273  3332 I jxcore-log: 
03-24 17:39:10.565  3273  3332 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 17:39:10.565  3273  3332 I jxcore-log: 
03-24 17:39:10.566  3273  3332 I jxcore-log: DEBUG createNativeListener: mux close
03-24 17:39:10.566  3273  3332 I jxcore-log: 
03-24 17:39:10.567  3273  3332 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 17:39:10.567  3273  3332 I jxcore-log: 
03-24 17:39:10.567  3273  3332 I jxcore-log: DEBUG createNativeListener: stream close:
,03-24 17:39:10.567  3273  3332 I jxcore-log: 
03-24 17:39:10.568  3273  3332 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 17:39:10.568  3273  3332 I jxcore-log: 
,03-24 17:39:10.569  3273  3332 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 17:39:10.569  3273  3332 I jxcore-log: 
,03-24 17:39:10.570  3273  3332 I jxcore-log: DEBUG createNativeListener: mux close
03-24 17:39:10.570  3273  3332 I jxcore-log: 
03-24 17:39:10.570  3273  3332 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 17:39:10.570  3273  3332 I jxcore-log: 
,03-24 17:39:10.571  3273  3332 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 17:39:10.571  3273  3332 I jxcore-log: 
,03-24 17:39:10.572  3273  3332 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 17:39:10.572  3273  3332 I jxcore-log: 
,03-24 17:39:10.573  3273  3332 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 17:39:10.573  3273  3332 I jxcore-log: 
03-24 17:39:10.574  3273  3332 I jxcore-log: DEBUG createNativeListener: mux close
03-24 17:39:10.574  3273  3332 I jxcore-log: 
,03-24 17:39:10.577  3273  3332 I jxcore-log: ok 28 native server is nulled out
03-24 17:39:10.577  3273  3332 I jxcore-log: 
,03-24 17:39:10.577  3273  3332 I jxcore-log: ok 29 native server should be closed
03-24 17:39:10.577  3273  3332 I jxcore-log: 
,03-24 17:39:10.578  3273  3332 I jxcore-log: ok 30 incoming has been removed
03-24 17:39:10.578  3273  3332 I jxcore-log: 
,03-24 17:39:10.579  3273  3332 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 17:39:10.579  3273  3332 I jxcore-log: 
,03-24 17:39:10.580  3273  3332 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 17:39:10.580  3273  3332 I jxcore-log: 
,03-24 17:39:10.580  3273  3332 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 17:39:10.580  3273  3332 I jxcore-log: 
,03-24 17:39:10.580  3273  3332 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 17:39:10.580  3273  3332 I jxcore-log: 
,03-24 17:39:10.581  3273  3332 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 17:39:10.581  3273  3332 I jxcore-log: 
,03-24 17:39:10.581  3273  3332 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 17:39:10.581  3273  3332 I jxcore-log: 
,03-24 17:39:10.581  3273  3332 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 17:39:10.581  3273  3332 I jxcore-log: 
03-24 17:39:10.582  3273  3332 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 17:39:10.582  3273  3332 I jxcore-log: 
03-24 17:39:10.582  3273  3332 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 17:39:10.582  3273  3332 I jxcore-log: 
03-24 17:39:10.583  3273  3332 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 17:39:10.583  3273  3332 I jxcore-log: 
,03-24 17:39:10.687  3273  3332 I jxcore-log: # teardown
03-24 17:39:10.687  3273  3332 I jxcore-log: 
,03-24 17:39:10.704  3273  3332 I jxcore-log: # setup
03-24 17:39:10.704  3273  3332 I jxcore-log: 
,03-24 17:39:10.838  3273  3332 I jxcore-log: # 10. native server - simulate mux failure, make sure everything is cleaned up
03-24 17:39:10.838  3273  3332 I jxcore-log: 
,03-24 17:39:10.997  3273  3332 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 17:39:10.997  3273  3332 I jxcore-log: 
,03-24 17:39:11.004  3273  3332 I jxcore-log: DEBUG createNativeListener: listening 45430
03-24 17:39:11.004  3273  3332 I jxcore-log: 
,03-24 17:39:11.014  3273  3332 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 17:39:11.014  3273  3332 I jxcore-log: 
,03-24 17:39:11.016  3273  3332 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 17:39:11.016  3273  3332 I jxcore-log: 
,03-24 17:39:11.017  3273  3332 I jxcore-log: DEBUG createNativeListener: new mux
03-24 17:39:11.017  3273  3332 I jxcore-log: 
,03-24 17:39:11.025  3273  3332 I jxcore-log: ok 31 we should not have gotten an error
03-24 17:39:11.025  3273  3332 I jxcore-log: 
,03-24 17:39:11.028  3273  3332 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 17:39:11.028  3273  3332 I jxcore-log: 
,03-24 17:39:11.031  3273  3332 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 17:39:11.031  3273  3332 I jxcore-log: 
,03-24 17:39:11.039  3273  3332 I jxcore-log: ok 32 Buffers are identical
03-24 17:39:11.039  3273  3332 I jxcore-log: 
,03-24 17:39:11.040  3273  3332 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 17:39:11.040  3273  3332 I jxcore-log: 
,03-24 17:39:11.041  3273  3332 I jxcore-log: DEBUG createNativeListener: mux close
03-24 17:39:11.041  3273  3332 I jxcore-log: 
,03-24 17:39:11.053  3273  3332 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 17:39:11.053  3273  3332 I jxcore-log: 
,03-24 17:39:11.054  3273  3332 I jxcore-log: ok 33 server should be fine
03-24 17:39:11.054  3273  3332 I jxcore-log: 
,03-24 17:39:11.054  3273  3332 I jxcore-log: ok 34 server should be open
03-24 17:39:11.054  3273  3332 I jxcore-log: 
03-24 17:39:11.055  3273  3332 I jxcore-log: ok 35 incoming has been removed
03-24 17:39:11.055  3273  3332 I jxcore-log: 
03-24 17:39:11.055  3273  3332 I jxcore-log: ok 36 The mux object should be closed
03-24 17:39:11.055  3273  3332 I jxcore-log: 
,03-24 17:39:11.055  3273  3332 I jxcore-log: ok 37 The mux stream should be closed
03-24 17:39:11.055  3273  3332 I jxcore-log: 
,03-24 17:39:11.062  3273  3332 I jxcore-log: # teardown
,03-24 17:39:11.062  3273  3332 I jxcore-log: 
,03-24 17:39:11.182  3273  3332 I jxcore-log: # setup
03-24 17:39:11.182  3273  3332 I jxcore-log: 
,03-24 17:39:11.303  3273  3332 I jxcore-log: # 11. native server - timing out the incoming connection cleans everything up
03-24 17:39:11.303  3273  3332 I jxcore-log: 
,03-24 17:39:11.542  3273  3332 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 17:39:11.542  3273  3332 I jxcore-log: 
,03-24 17:39:11.545  3273  3332 I jxcore-log: DEBUG createNativeListener: listening 49153,
,03-24 17:39:11.545  3273  3332 I jxcore-log: 
,03-24 17:39:11.549  3273  3332 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 17:39:11.549  3273  3332 I jxcore-log: 
,03-24 17:39:11.550  3273  3332 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 17:39:11.550  3273  3332 I jxcore-log: 
,03-24 17:39:11.551  3273  3332 I jxcore-log: DEBUG createNativeListener: new mux
03-24 17:39:11.551  3273  3332 I jxcore-log: 
,03-24 17:39:11.555  3273  3332 I jxcore-log: ok 38 we should not have gotten an error
03-24 17:39:11.555  3273  3332 I jxcore-log: 
,03-24 17:39:11.557  3273  3332 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 17:39:11.557  3273  3332 I jxcore-log: 
,03-24 17:39:11.559  3273  3332 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 17:39:11.559  3273  3332 I jxcore-log: 
,03-24 17:39:11.563  3273  3332 I jxcore-log: ok 39 Buffers are identical
03-24 17:39:11.563  3273  3332 I jxcore-log: 
,03-24 17:39:11.566  3273  3332 I jxcore-log: DEBUG createNativeListener: incoming socket timeout
03-24 17:39:11.566  3273  3332 I jxcore-log: 
,03-24 17:39:11.567  3273  3332 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 17:39:11.567  3273  3332 I jxcore-log: 
,03-24 17:39:11.568  3273  3332 I jxcore-log: DEBUG createNativeListener: mux close
03-24 17:39:11.568  3273  3332 I jxcore-log: 
,03-24 17:39:11.571  3273  3332 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 17:39:11.571  3273  3332 I jxcore-log: 
,03-24 17:39:11.571  3273  3332 I jxcore-log: ok 40 server should be fine
03-24 17:39:11.571  3273  3332 I jxcore-log: 
03-24 17:39:11.571  3273  3332 I jxcore-log: ok 41 server should be open
03-24 17:39:11.571  3273  3332 I jxcore-log: 
03-24 17:39:11.572  3273  3332 I jxcore-log: ok 42 incoming has been removed
03-24 17:39:11.572  3273  3332 I jxcore-log: 
,03-24 17:39:11.572  3273  3332 I jxcore-log: ok 43 The mux object should be closed
03-24 17:39:11.572  3273  3332 I jxcore-log: 
03-24 17:39:11.572  3273  3332 I jxcore-log: ok 44 The mux stream should be closed
03-24 17:39:11.572  3273  3332 I jxcore-log: 
03-24 17:39:11.578  3273  3332 I jxcore-log: # teardown
03-24 17:39:11.578  3273  3332 I jxcore-log: 
,03-24 17:39:11.790  3273  3332 I jxcore-log: # setup
03-24 17:39:11.790  3273  3332 I jxcore-log: 
,03-24 17:39:11.947  3273  3332 I jxcore-log: # 12. closeAll can close even when connections open
03-24 17:39:11.947  3273  3332 I jxcore-log: 
,03-24 17:39:12.106  3273  3332 I jxcore-log: ok 45 not possible to connect to the server anymore
03-24 17:39:12.106  3273  3332 I jxcore-log: 
,03-24 17:39:12.110  3273  3332 I jxcore-log: # teardown
03-24 17:39:12.110  3273  3332 I jxcore-log: 
,03-24 17:39:12.221  3273  3332 I jxcore-log: # setup
03-24 17:39:12.221  3273  3332 I jxcore-log: 
,03-24 17:39:12.409  3273  3332 I jxcore-log: # 13. closeAll with promise
03-24 17:39:12.409  3273  3332 I jxcore-log: 
,03-24 17:39:12.590  3273  3332 I jxcore-log: ok 46 not possible to connect to the server anymore
03-24 17:39:12.590  3273  3332 I jxcore-log: 
,03-24 17:39:12.594  3273  3332 I jxcore-log: # teardown
03-24 17:39:12.594  3273  3332 I jxcore-log: 
,03-24 17:39:12.701  3273  3332 I jxcore-log: # setup
03-24 17:39:12.701  3273  3332 I jxcore-log: 
,03-24 17:39:12.831  3273  3332 I jxcore-log: # 14. multiplex can send data
03-24 17:39:12.831  3273  3332 I jxcore-log: 
,03-24 17:39:13.026  3273  3332 I jxcore-log: ok 47 String should be length:200
03-24 17:39:13.026  3273  3332 I jxcore-log: 
,03-24 17:39:13.035  3273  3332 I jxcore-log: # teardown
03-24 17:39:13.035  3273  3332 I jxcore-log: 
,03-24 17:39:13.144  3273  3332 I jxcore-log: # setup
,03-24 17:39:13.144  3273  3332 I jxcore-log: 
,03-24 17:39:13.245  3273  3332 I jxcore-log: # 15. enqueue and run in order
03-24 17:39:13.245  3273  3332 I jxcore-log: 
,03-24 17:39:13.537  3273  3332 I jxcore-log: ok 48 firstPromise setTimeout
03-24 17:39:13.537  3273  3332 I jxcore-log: 
,03-24 17:39:13.540  3273  3332 I jxcore-log: ok 49 firstPromise result
03-24 17:39:13.540  3273  3332 I jxcore-log: 
03-24 17:39:13.541  3273  3332 I jxcore-log: ok 50 firstPromise testValue
03-24 17:39:13.541  3273  3332 I jxcore-log: 
,03-24 17:39:13.647  3273  3332 I jxcore-log: ok 51 secondPromise setTimeout
03-24 17:39:13.647  3273  3332 I jxcore-log: 
,03-24 17:39:13.651  3273  3332 I jxcore-log: ok 52 secondPromise result
03-24 17:39:13.651  3273  3332 I jxcore-log: 
03-24 17:39:13.653  3273  3332 I jxcore-log: ok 53 secondPromise testValue
03-24 17:39:13.653  3273  3332 I jxcore-log: 
,03-24 17:39:13.658  3273  3332 I jxcore-log: ok 54 thirdPromise in promise
03-24 17:39:13.658  3273  3332 I jxcore-log: 
,03-24 17:39:13.662  3273  3332 I jxcore-log: ok 55 thirdPromise result
03-24 17:39:13.662  3273  3332 I jxcore-log: 
,03-24 17:39:13.664  3273  3332 I jxcore-log: ok 56 thirdPromise testValue
03-24 17:39:13.664  3273  3332 I jxcore-log: 
,03-24 17:39:13.678  3273  3332 I jxcore-log: # teardown
03-24 17:39:13.678  3273  3332 I jxcore-log: 
,03-24 17:39:13.820  3273  3332 I jxcore-log: # setup
03-24 17:39:13.820  3273  3332 I jxcore-log: 
,03-24 17:39:13.967  3273  3332 I jxcore-log: # 16. enqueueAtTop and run backwards
03-24 17:39:13.967  3273  3332 I jxcore-log: 
,03-24 17:39:14.192  3273  3332 I jxcore-log: ok 57 thirdPromise - first to run
03-24 17:39:14.192  3273  3332 I jxcore-log: 
,03-24 17:39:14.193  3273  3332 I jxcore-log: ok 58 thirdPromise - in resolve
03-24 17:39:14.193  3273  3332 I jxcore-log: 
,03-24 17:39:14.195  3273  3332 I jxcore-log: ok 59 secondPromise - second to run
03-24 17:39:14.195  3273  3332 I jxcore-log: 
,03-24 17:39:14.196  3273  3332 I jxcore-log: ok 60 secondPromise - in catch
03-24 17:39:14.196  3273  3332 I jxcore-log: 
,03-24 17:39:14.197  3273  3332 I jxcore-log: ok 61 firstPromise - third to run
03-24 17:39:14.197  3273  3332 I jxcore-log: 
,03-24 17:39:14.199  3273  3332 I jxcore-log: ok 62 firstPromise - in then
03-24 17:39:14.199  3273  3332 I jxcore-log: 
,03-24 17:39:14.199  3273  3332 I jxcore-log: ok 63 testing promises
03-24 17:39:14.199  3273  3332 I jxcore-log: 
,03-24 17:39:14.203  3273  3332 I jxcore-log: # teardown
03-24 17:39:14.203  3273  3332 I jxcore-log: 
,03-24 17:39:14.328  3273  3332 I jxcore-log: # setup
03-24 17:39:14.328  3273  3332 I jxcore-log: 
,03-24 17:39:14.508  3273  3332 I jxcore-log: # 17. mix enqueue and enqueueAtTop
03-24 17:39:14.508  3273  3332 I jxcore-log: 
,03-24 17:39:14.637  3273  3332 I jxcore-log: ok 64 fourth
03-24 17:39:14.637  3273  3332 I jxcore-log: ,
,03-24 17:39:14.640  3273  3332 I jxcore-log: ok 65 fourth
03-24 17:39:14.640  3273  3332 I jxcore-log: 
,03-24 17:39:14.644  3273  3332 I jxcore-log: ok 66 second
03-24 17:39:14.644  3273  3332 I jxcore-log: 
,03-24 17:39:14.645  3273  3332 I jxcore-log: ok 67 secondPromise - in then
03-24 17:39:14.645  3273  3332 I jxcore-log: 
,03-24 17:39:14.748  3273  3332 I jxcore-log: ok 68 first
03-24 17:39:14.748  3273  3332 I jxcore-log: 
,03-24 17:39:14.750  3273  3332 I jxcore-log: ok 69 firstPromise - in catch
03-24 17:39:14.750  3273  3332 I jxcore-log: 
,03-24 17:39:14.754  3273  3332 I jxcore-log: ok 70 third
03-24 17:39:14.754  3273  3332 I jxcore-log: 
,03-24 17:39:14.756  3273  3332 I jxcore-log: ok 71 thirdPromise - in then
03-24 17:39:14.756  3273  3332 I jxcore-log: 
,03-24 17:39:14.758  3273  3332 I jxcore-log: ok 72 testingPromises
,03-24 17:39:14.758  3273  3332 I jxcore-log: 
,03-24 17:39:14.771  3273  3332 I jxcore-log: # teardown
03-24 17:39:14.771  3273  3332 I jxcore-log: 
,03-24 17:39:15.233  3273  3332 I jxcore-log: # setup
03-24 17:39:15.233  3273  3332 I jxcore-log: 
,03-24 17:39:15.493  3273  3332 I jxcore-log: # 18. queues handled independently
03-24 17:39:15.493  3273  3332 I jxcore-log: 
,03-24 17:39:15.659  3273  3332 I jxcore-log: ok 73 all short operations completed before the long resolves
03-24 17:39:15.659  3273  3332 I jxcore-log: 
,03-24 17:39:15.663  3273  3332 I jxcore-log: # teardown,
03-24 17:39:15.663  3273  3332 I jxcore-log: 
,03-24 17:39:15.764  3273  3332 I jxcore-log: # setup
03-24 17:39:15.764  3273  3332 I jxcore-log: 
,03-24 17:39:15.884  3273  3332 I jxcore-log: # 19. basic
03-24 17:39:15.884  3273  3332 I jxcore-log: 
,03-24 17:39:15.983  3273  3332 I jxcore-log: ok 74 sane
03-24 17:39:15.983  3273  3332 I jxcore-log: 
,03-24 17:39:15.990  3273  3332 I jxcore-log: # teardown
03-24 17:39:15.990  3273  3332 I jxcore-log: 
,03-24 17:39:16.119  3273  3332 I jxcore-log: # setup
03-24 17:39:16.119  3273  3332 I jxcore-log: 
,03-24 17:39:16.208  3273  3332 I jxcore-log: # 20. another
03-24 17:39:16.208  3273  3332 I jxcore-log: 
,03-24 17:39:16.335  3273  3332 I jxcore-log: ok 75 sane
03-24 17:39:16.335  3273  3332 I jxcore-log: 
,03-24 17:39:16.341  3273  3332 I jxcore-log: # teardown
03-24 17:39:16.341  3273  3332 I jxcore-log: 
,03-24 17:39:16.459  3273  3332 I jxcore-log: # setup
03-24 17:39:16.459  3273  3332 I jxcore-log: 
,03-24 17:39:16.538  3273  3332 I jxcore-log: # 21. can pass data in setup
03-24 17:39:16.538  3273  3332 I jxcore-log: 
,03-24 17:39:16.641  3273  3332 I jxcore-log: ok 76 test participant has uuid
03-24 17:39:16.641  3273  3332 I jxcore-log: 
,03-24 17:39:16.643  3273  3332 I jxcore-log: ok 77 participant data matches
03-24 17:39:16.643  3273  3332 I jxcore-log: 
,03-24 17:39:16.645  3273  3332 I jxcore-log: ok 78 test participant has uuid
03-24 17:39:16.645  3273  3332 I jxcore-log: 
,03-24 17:39:16.646  3273  3332 I jxcore-log: ok 79 participant data matches
03-24 17:39:16.646  3273  3332 I jxcore-log: 
,03-24 17:39:16.647  3273  3332 I jxcore-log: ok 80 test participant has uuid
03-24 17:39:16.647  3273  3332 I jxcore-log: 
,03-24 17:39:16.649  3273  3332 I jxcore-log: ok 81 participant data matches
03-24 17:39:16.649  3273  3332 I jxcore-log: 
,03-24 17:39:16.657  3273  3332 I jxcore-log: # teardown
03-24 17:39:16.657  3273  3332 I jxcore-log: 
,03-24 17:39:16.824  3273  3332 I jxcore-log: # setup
03-24 17:39:16.824  3273  3332 I jxcore-log: 
,03-24 17:39:16.913  1265  1265 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 17:39:16.978  3273  3332 I jxcore-log: # 22. #startListeningForAdvertisements should fail if start not called
03-24 17:39:16.978  3273  3332 I jxcore-log: 
,03-24 17:39:17.000  1265  2585 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
03-24 17:39:17.001  1265  2585 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 17:39:17.001  1265  2585 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 17:39:17.001  1265  2585 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 17:39:17.009  1265  2585 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 17:39:17.041  3683  3683 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,03-24 17:39:17.043  3683  3683 D Finsky  : [1] 5.onFinished: Installation state replication failed.
,03-24 17:39:17.044  3683  3683 D Finsky  : [1] 5.onFinished: Scheduling replication attempt 1.
,03-24 17:39:17.113  3273  3332 I jxcore-log: ok 82 specific error should be returned
03-24 17:39:17.113  3273  3332 I jxcore-log: 
,03-24 17:39:17.115  3273  3332 I jxcore-log: # teardown
03-24 17:39:17.115  3273  3332 I jxcore-log: 
,03-24 17:39:17.295  3273  3332 I jxcore-log: ok 83 error should be null
03-24 17:39:17.295  3273  3332 I jxcore-log: 
,03-24 17:39:17.296  3273  3332 I jxcore-log: ok 84 error should be null
03-24 17:39:17.296  3273  3332 I jxcore-log: 
03-24 17:39:17.298  3273  3332 I jxcore-log: # setup
03-24 17:39:17.298  3273  3332 I jxcore-log: 
,03-24 17:39:17.409  3273  3332 I jxcore-log: # 23. #startUpdateAdvertisingAndListening should fail if start not called
03-24 17:39:17.409  3273  3332 I jxcore-log: 
,03-24 17:39:17.613  3273  3332 I jxcore-log: ok 85 specific error should be returned
03-24 17:39:17.613  3273  3332 I jxcore-log: 
,03-24 17:39:17.616  3273  3332 I jxcore-log: # teardown
03-24 17:39:17.616  3273  3332 I jxcore-log: 
,03-24 17:39:17.724  3273  3332 I jxcore-log: ok 86 error should be null
03-24 17:39:17.724  3273  3332 I jxcore-log: 
,03-24 17:39:17.726  3273  3332 I jxcore-log: ok 87 error should be null
03-24 17:39:17.726  3273  3332 I jxcore-log: 
03-24 17:39:17.731  3273  3332 I jxcore-log: # setup
03-24 17:39:17.731  3273  3332 I jxcore-log: 
,03-24 17:39:17.854  3273  3332 I jxcore-log: # 24. should be able to call #stopListeningForAdvertisements many times
03-24 17:39:17.854  3273  3332 I jxcore-log: 
,03-24 17:39:18.019  3273  3332 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 17:39:18.019  3273  3332 I jxcore-log: 
,03-24 17:39:18.020  3273  3332 I jxcore-log: DEBUG createNativeListener: listening 56694
03-24 17:39:18.020  3273  3332 I jxcore-log: 
03-24 17:39:18.023  3273  3332 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 17:39:18.023  3273  3332 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-24 17:39:18.023  3273  3332 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 17:39:18.028  3273  3332 I jxcore-log: ok 88 error should be null
03-24 17:39:18.028  3273  3332 I jxcore-log: 
,03-24 17:39:18.029  3273  3332 I jxcore-log: ok 89 error should be null
03-24 17:39:18.029  3273  3332 I jxcore-log: 
03-24 17:39:18.030  3273  3332 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 17:39:18.030  3273  3332 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-24 17:39:18.030  3273  3332 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 17:39:18.033  3273  3332 I jxcore-log: ok 90 error should be null
03-24 17:39:18.033  3273  3332 I jxcore-log: 
,03-24 17:39:18.033  3273  3332 I jxcore-log: ok 91 error should be null
03-24 17:39:18.033  3273  3332 I jxcore-log: 
,03-24 17:39:18.037  3273  3332 I jxcore-log: # teardown
03-24 17:39:18.037  3273  3332 I jxcore-log: 
,03-24 17:39:18.175  3273  3332 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 17:39:18.175  3273  3332 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 17:39:18.175  3273  3332 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 17:39:18.178  3273  3332 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 17:39:18.178  3273  3332 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-24 17:39:18.178  3273  3332 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 17:39:18.181  3273  3332 I jxcore-log: ok 92 error should be null
03-24 17:39:18.181  3273  3332 I jxcore-log: 
03-24 17:39:18.182  3273  3332 I jxcore-log: ok 93 error should be null
03-24 17:39:18.182  3273  3332 I jxcore-log: 
,03-24 17:39:18.189  3273  3332 I jxcore-log: # setup
03-24 17:39:18.189  3273  3332 I jxcore-log: 
,03-24 17:39:18.321  3273  3332 I jxcore-log: # 25. should be able to call #startListeningForAdvertisements many times
03-24 17:39:18.321  3273  3332 I jxcore-log: 
,03-24 17:39:18.442  3273  3332 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 17:39:18.442  3273  3332 I jxcore-log: 
,03-24 17:39:18.444  3273  3332 I jxcore-log: DEBUG createNativeListener: listening 39584
03-24 17:39:18.444  3273  3332 I jxcore-log: 
,03-24 17:39:18.455  3273  3332 I io.jxcore.node.ConnectionHelper: start: Port number: 0, start advertisements: false
03-24 17:39:18.455  3273  3332 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 17:39:18.455  3273  3332 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 17:39:18.455  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
03-24 17:39:18.455  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 17:39:18.455  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-24 17:39:18.464  3273  3332 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-24 17:39:18.465   823  1104 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 17:39:18.476  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-24 17:39:18.491  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-24 17:39:18.491  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 17:39:18.491  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 17:39:18.493  3273  3332 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 17:39:18.506  2157  2172 D BtGatt.GattService: registerClient() - UUID=0aed225f-b11f-4ed0-bc6c-6da64abc553e
,03-24 17:39:18.507  2157  2220 D BtGatt.GattService: onClientRegistered() - UUID=0aed225f-b11f-4ed0-bc6c-6da64abc553e, clientIf=5
03-24 17:39:18.508  3273  3292 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-24 17:39:18.511  2157  2222 D BtGatt.GattService: start scan with filters
,03-24 17:39:18.514  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-24 17:39:18.515  2157  2231 D BtGatt.ScanManager: handling starting scan
03-24 17:39:18.515  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-24 17:39:18.520  2157  2231 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3afb46ad
03-24 17:39:18.520  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-24 17:39:18.520  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-24 17:39:18.520  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 17:39:18.521  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-24 17:39:18.521  3273  3273 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 17:39:18.522   823  1446 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 17:39:18.534  2157  2220 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 17:39:18.534  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 17:39:18.535  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-24 17:39:18.535  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-24 17:39:18.537  2157  2220 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 17:39:18.537  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 17:39:18.538  3273  3273 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,03-24 17:39:18.538  3273  3273 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 17:39:18.539  2157  2231 D BtGatt.ScanManager: Starting BLE batch scan
03-24 17:39:18.539  3273  3273 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 17:39:18.539  2157  2231 D BtGatt.ScanManager: configuring batch scan storage, appIf 5,
03-24 17:39:18.540  3273  3332 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 17:39:18.542  2157  2220 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 17:39:18.542  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 17:39:18.546  2157  2220 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,03-24 17:39:18.546  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 17:39:18.559  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 17:39:18.559  3273  3332 I jxcore-log: 
,03-24 17:39:18.561  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 17:39:18.561  3273  3332 I jxcore-log: 
,03-24 17:39:18.565  3273  3332 I jxcore-log: ok 94 error should be null
03-24 17:39:18.565  3273  3332 I jxcore-log: 
,03-24 17:39:18.566  3273  3332 I jxcore-log: ok 95 error should be null
03-24 17:39:18.566  3273  3332 I jxcore-log: 
,03-24 17:39:18.575  3273  3332 I io.jxcore.node.ConnectionHelper: start: Port number: 0, start advertisements: false
,03-24 17:39:18.575  3273  3332 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 17:39:18.575  3273  3332 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,03-24 17:39:18.575  3273  3332 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 17:39:18.575  3273  3332 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 17:39:18.579  3273  3332 I jxcore-log: ok 96 error should be null
03-24 17:39:18.579  3273  3332 I jxcore-log: 
03-24 17:39:18.580  3273  3332 I jxcore-log: ok 97 error should be null
03-24 17:39:18.580  3273  3332 I jxcore-log: 
,03-24 17:39:18.594  3273  3332 I jxcore-log: # teardown
03-24 17:39:18.594  3273  3332 I jxcore-log: 
,03-24 17:39:18.741  3273  3332 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 17:39:18.741  3273  3332 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
03-24 17:39:18.741  3273  3332 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
03-24 17:39:18.741  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-24 17:39:18.742  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-24 17:39:18.742  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 17:39:18.742  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,03-24 17:39:18.744  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-24 17:39:18.744  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-24 17:39:18.747  2157  2222 D BtGatt.GattService: stopScan() - queue size =1
,03-24 17:39:18.751  2157  2220 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,03-24 17:39:18.752  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:39:18.752  2157  2173 D BtGatt.GattService: unregisterClient() - clientIf=5
03-24 17:39:18.752  2157  2231 D BtGatt.ScanManager: stopping BLe Batch
03-24 17:39:18.753  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 17:39:18.753  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 17:39:18.754  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false,
03-24 17:39:18.755  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,03-24 17:39:18.755  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-24 17:39:18.755  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-24 17:39:18.756  2157  2220 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,03-24 17:39:18.756  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 17:39:18.757  2157  2231 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 17:39:18.759  2157  2220 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
03-24 17:39:18.759  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 17:39:18.759  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
,03-24 17:39:18.760  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,03-24 17:39:18.760  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-24 17:39:18.762  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
,03-24 17:39:18.763  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false,
03-24 17:39:18.763  3273  3273 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
03-24 17:39:18.763  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 17:39:18.763  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-24 17:39:18.767  3273  3332 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-24 17:39:18.767  3273  3332 I jxcore-log: 
03-24 17:39:18.774  3273  3273 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-24 17:39:18.775   823  1153 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 17:39:18.782  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-24 17:39:18.783  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 17:39:18.783  3273  3273 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 17:39:18.786  3273  3273 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-24 17:39:18.786  3273  3273 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 17:39:18.786  3273  3273 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 17:39:18.787  3273  3273 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 17:39:18.787  3273  3332 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 17:39:18.787  3273  3332 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 17:39:18.788  3273  3332 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 17:39:18.789  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 17:39:18.789  3273  3332 I jxcore-log: 
03-24 17:39:18.789  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 17:39:18.789  3273  3332 I jxcore-log: 
,03-24 17:39:18.793  3273  3332 I jxcore-log: ok 98 error should be null
03-24 17:39:18.793  3273  3332 I jxcore-log: 
,03-24 17:39:18.793  3273  3332 I jxcore-log: ok 99 error should be null
03-24 17:39:18.793  3273  3332 I jxcore-log: 
,03-24 17:39:18.798  3273  3332 I jxcore-log: # setup
03-24 17:39:18.798  3273  3332 I jxcore-log: 
,03-24 17:39:18.949  3273  3332 I jxcore-log: # 26. should be able to call #startUpdateAdvertisingAndListening many times
03-24 17:39:18.949  3273  3332 I jxcore-log: 
,03-24 17:39:19.171  3273  3332 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 17:39:19.171  3273  3332 I jxcore-log: 
,03-24 17:39:19.173  3273  3332 I jxcore-log: DEBUG createNativeListener: listening 58482
03-24 17:39:19.173  3273  3332 I jxcore-log: 
,03-24 17:39:19.188  3273  3332 I io.jxcore.node.ConnectionHelper: start: Port number: 58482, start advertisements: true
,03-24 17:39:19.188  3273  3332 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 17:39:19.188  3273  3332 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-24 17:39:19.188  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-24 17:39:19.192  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser,
,03-24 17:39:19.192  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 17:39:19.192  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 17:39:19.193  3273  3332 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 17:39:19.197  2157  2222 D BtGatt.GattService: registerClient() - UUID=5b65d88b-3833-457c-946f-1bd50d2aa254
,03-24 17:39:19.197  2157  2220 D BtGatt.GattService: onClientRegistered() - UUID=5b65d88b-3833-457c-946f-1bd50d2aa254, clientIf=5
03-24 17:39:19.198  3273  3327 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 17:39:19.198  2157  2173 D BtGatt.GattService: start scan with filters
,03-24 17:39:19.200  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 17:39:19.200  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 17:39:19.200  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,03-24 17:39:19.200  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-24 17:39:19.200  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 17:39:19.200  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,03-24 17:39:19.200  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 17:39:19.200  3273  3273 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 17:39:19.200  2157  2231 D BtGatt.ScanManager: handling starting scan,
,03-24 17:39:19.201  3273  3332 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 17:39:19.202  3273  3332 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 17:39:19.202  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-24 17:39:19.202  3273  3332 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-24 17:39:19.204  2157  2220 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 17:39:19.205  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:39:19.207  2157  2220 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 17:39:19.207  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:39:19.208  2157  2231 D BtGatt.ScanManager: Starting BLE batch scan
03-24 17:39:19.208  2157  2231 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 17:39:19.208  2157  2172 D BtGatt.GattService: registerClient() - UUID=13f45a21-fce1-4c5e-8e63-59b9cbf548f0
03-24 17:39:19.209  2157  2220 D BtGatt.GattService: onClientRegistered() - UUID=13f45a21-fce1-4c5e-8e63-59b9cbf548f0, clientIf=6
,03-24 17:39:19.210  3273  3292 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-24 17:39:19.211  2157  2220 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 17:39:19.212  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:39:19.214  2157  2220 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 17:39:19.214  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 17:39:19.217  2157  2230 D BtGatt.AdvertiseManager: message : 0
,03-24 17:39:19.223  2157  2230 D BtGatt.AdvertiseManager: starting multi advertising,
,03-24 17:39:19.228  2157  2220 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0,
,03-24 17:39:19.232  2157  2220 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 17:39:19.234  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-24 17:39:19.234  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-24 17:39:19.236   823  1154 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 17:39:19.243  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-24 17:39:19.243  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 17:39:19.243  3273  3332 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-24 17:39:19.244  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-24 17:39:19.246  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-24 17:39:19.248  3273  3332 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,03-24 17:39:19.249  3273  3332 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,03-24 17:39:19.249  3273  3332 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,03-24 17:39:19.251  3273  3273 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,03-24 17:39:19.251   823  1413 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 17:39:19.252  3273  3332 I io.jxcore.node.ConnectionHelper: start: OK
03-24 17:39:19.253  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,03-24 17:39:19.253  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-24 17:39:19.253  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,03-24 17:39:19.253  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-24 17:39:19.253  3273  3273 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-24 17:39:19.253  3273  3273 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 17:39:19.253  3273  3790 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-24 17:39:19.253  3273  3273 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-24 17:39:19.253  3273  3273 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-24 17:39:19.253  3273  3273 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 17:39:19.253  3273  3273 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-24 17:39:19.254  3273  3273 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 17:39:19.257  3273  3790 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-24 17:39:19.263  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 17:39:19.263  3273  3332 I jxcore-log: 
,03-24 17:39:19.264  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 17:39:19.264  3273  3332 I jxcore-log: 
,03-24 17:39:19.265  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-24 17:39:19.265  3273  3332 I jxcore-log: 
,03-24 17:39:19.267  3273  3332 I jxcore-log: ok 100 error should be null
03-24 17:39:19.267  3273  3332 I jxcore-log: 
,03-24 17:39:19.267  3273  3332 I jxcore-log: ok 101 error should be null
,03-24 17:39:19.267  3273  3332 I jxcore-log: 
,03-24 17:39:19.282  3273  3332 I io.jxcore.node.ConnectionHelper: start: Port number: 58482, start advertisements: true
,03-24 17:39:19.282  3273  3332 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 17:39:19.283  3273  3332 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,03-24 17:39:19.283  3273  3332 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 17:39:19.283  3273  3332 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 17:39:19.292  3273  3332 I jxcore-log: ok 102 error should be null
03-24 17:39:19.292  3273  3332 I jxcore-log: 
,03-24 17:39:19.293  3273  3332 I jxcore-log: ok 103 error should be null
03-24 17:39:19.293  3273  3332 I jxcore-log: 
,03-24 17:39:19.301  3273  3332 I jxcore-log: # teardown
03-24 17:39:19.301  3273  3332 I jxcore-log: 
,03-24 17:39:19.718  2157  2157 D BtGatt.ScanManager: awakened up at time 199146
,03-24 17:39:19.720  2157  2231 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 17:39:19.734  2157  2220 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
03-24 17:39:19.734  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:39:19.734  2157  2220 D BtGatt.GattService: current time is 199162414192
03-24 17:39:19.735  2157  2220 D BtGatt.GattService: Batch record : [-123, 69, 122, 111, -12, 122, 1, -128, -78, 3, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -63, 7, 0, 0, 0, -127, -59, 40, 32, -73, -32, 1, -128, -60, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-24 17:39:19.737  2157  2220 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 17:39:19.739  2157  2220 D BtGatt.GattService: ScanRecord : []
03-24 17:39:19.740  2157  2220 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
,03-24 17:39:19.751  3273  3273 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> E0:DB:10:14:E2:C0], added - the peer count is 1
,03-24 17:39:19.753  3273  3273 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 2
,03-24 17:39:19.753  3273  3273 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> E0:DB:10:14:E2:C0], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 
,03-24 17:39:19.754  3273  3273 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
,03-24 17:39:19.763  3273  3332 I jxcore-log: DEBUG createPeerListener: createPeerListener
,03-24 17:39:19.763  3273  3332 I jxcore-log: 
,03-24 17:39:19.774  3273  3332 I jxcore-log: DEBUG createPeerListener: pleaseConnect= false
03-24 17:39:19.774  3273  3332 I jxcore-log: 
,03-24 17:39:19.777  3273  3332 I jxcore-log: DEBUG createPeerListener: createPeerListener
,03-24 17:39:19.777  3273  3332 I jxcore-log: 
,03-24 17:39:19.779  3273  3332 I jxcore-log: DEBUG createPeerListener: pleaseConnect= false,
03-24 17:39:19.779  3273  3332 I jxcore-log: 
,03-24 17:39:19.855  3273  3332 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 17:39:19.855  3273  3332 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-24 17:39:19.855  3273  3332 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,03-24 17:39:19.855  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-24 17:39:19.856  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-24 17:39:19.856  3273  3332 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-24 17:39:19.857  3273  3790 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-24 17:39:19.857  3273  3790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-24 17:39:19.857  3273  3790 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-24 17:39:19.857  3273  3273 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false,
,03-24 17:39:19.858  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-24 17:39:19.858  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-24 17:39:19.858  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart,
03-24 17:39:19.858  3273  3273 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-24 17:39:19.858  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode,
03-24 17:39:19.858  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-24 17:39:19.858  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-24 17:39:19.860  2157  2173 D BtGatt.GattService: stopScan() - queue size =1
,03-24 17:39:19.862  2157  2172 D BtGatt.GattService: unregisterClient() - clientIf=5
03-24 17:39:19.862  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 17:39:19.862  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 17:39:19.862  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-24 17:39:19.862  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-24 17:39:19.862  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-24 17:39:19.862  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 17:39:19.862  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-24 17:39:19.865  2157  2230 D BtGatt.AdvertiseManager: message : 1
,03-24 17:39:19.866  2157  2230 D BtGatt.AdvertiseManager: stop advertise for client 6
03-24 17:39:19.867  2157  2220 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 17:39:19.867  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:39:19.867  2157  2231 D BtGatt.ScanManager: stopping BLe Batch
,03-24 17:39:19.871  2157  2220 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 17:39:19.871  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:39:19.871  2157  2231 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 17:39:19.874  2157  2220 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0,
03-24 17:39:19.874  2157  2220 D BtGatt.GattService: Client app is not null!
03-24 17:39:19.875  2157  2172 D BtGatt.GattService: unregisterClient() - clientIf=6,
,03-24 17:39:19.875  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 17:39:19.876  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,03-24 17:39:19.876  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-24 17:39:19.876  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-24 17:39:19.876  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-24 17:39:19.876  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 17:39:19.876  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 17:39:19.876  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-24 17:39:19.877  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-24 17:39:19.877  3273  3332 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-24 17:39:19.877  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 17:39:19.878  3273  3273 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 17:39:19.878  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 17:39:19.878  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-24 17:39:19.881  2157  2220 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
03-24 17:39:19.881  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:39:19.881  2157  2220 D BtGatt.GattService: current time is 199309025911
,03-24 17:39:19.881  2157  2220 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -47, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-24 17:39:19.881  2157  2220 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
,03-24 17:39:19.890  3273  3273 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-24 17:39:19.891   823  1404 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 17:39:19.896  3273  3332 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-24 17:39:19.896  3273  3332 I jxcore-log: 
,03-24 17:39:19.897  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-24 17:39:19.898  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-24 17:39:19.898  3273  3273 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 17:39:19.901  3273  3273 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED,
03-24 17:39:19.901  3273  3273 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 17:39:19.901  3273  3273 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 17:39:19.901  3273  3273 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true,
03-24 17:39:19.902  3273  3273 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 17:39:19.902  3273  3273 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-24 17:39:19.905  3273  3332 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements,
03-24 17:39:19.905  3273  3332 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 17:39:19.905  3273  3332 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 17:39:19.907  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-24 17:39:19.907  3273  3332 I jxcore-log: 
,03-24 17:39:19.909  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 17:39:19.909  3273  3332 I jxcore-log: 
,03-24 17:39:19.911  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 17:39:19.911  3273  3332 I jxcore-log: 
,03-24 17:39:19.917  3273  3332 I jxcore-log: ok 104 error should be null,
03-24 17:39:19.917  3273  3332 I jxcore-log: 
03-24 17:39:19.917  3273  3332 I jxcore-log: ok 105 error should be null
03-24 17:39:19.917  3273  3332 I jxcore-log: 
,03-24 17:39:19.924  3273  3332 I jxcore-log: # setup,
03-24 17:39:19.924  3273  3332 I jxcore-log: 
,03-24 17:39:20.214  3273  3332 I jxcore-log: # 27. should be able to call #stopAdvertisingAndListening many times,
03-24 17:39:20.214  3273  3332 I jxcore-log: 
,03-24 17:39:20.362  3273  3332 I jxcore-log: DEBUG createNativeListener: creating native server,
03-24 17:39:20.362  3273  3332 I jxcore-log: 
,03-24 17:39:20.365  3273  3332 I jxcore-log: DEBUG createNativeListener: listening 56043
03-24 17:39:20.365  3273  3332 I jxcore-log: 
,03-24 17:39:20.370  3273  3332 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 17:39:20.370  3273  3332 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 17:39:20.370  3273  3332 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 17:39:20.373  3273  3332 I jxcore-log: ok 106 error should be null
03-24 17:39:20.373  3273  3332 I jxcore-log: 
,03-24 17:39:20.374  3273  3332 I jxcore-log: ok 107 error should be null
03-24 17:39:20.374  3273  3332 I jxcore-log: 
,03-24 17:39:20.377  3273  3332 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 17:39:20.377  3273  3332 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 17:39:20.377  3273  3332 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 17:39:20.379  3273  3332 I jxcore-log: ok 108 error should be null
03-24 17:39:20.379  3273  3332 I jxcore-log: 
03-24 17:39:20.379  3273  3332 I jxcore-log: ok 109 error should be null
03-24 17:39:20.379  3273  3332 I jxcore-log: 
,03-24 17:39:20.387  3273  3332 I jxcore-log: # teardown
03-24 17:39:20.387  3273  3332 I jxcore-log: 
,03-24 17:39:20.496  3273  3332 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 17:39:20.496  3273  3332 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 17:39:20.496  3273  3332 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 17:39:20.498  3273  3332 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 17:39:20.498  3273  3332 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-24 17:39:20.498  3273  3332 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 17:39:20.501  3273  3332 I jxcore-log: ok 110 error should be null
03-24 17:39:20.501  3273  3332 I jxcore-log: 
03-24 17:39:20.503  3273  3332 I jxcore-log: ok 111 error should be null
03-24 17:39:20.503  3273  3332 I jxcore-log: 
,03-24 17:39:20.510  3273  3332 I jxcore-log: # setup
03-24 17:39:20.510  3273  3332 I jxcore-log: 
,03-24 17:39:20.632  3273  3332 I jxcore-log: # 28. #start should fail if called twice in a row
03-24 17:39:20.632  3273  3332 I jxcore-log: 
,03-24 17:39:20.745  3273  3332 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 17:39:20.745  3273  3332 I jxcore-log: 
,03-24 17:39:20.748  3273  3332 I jxcore-log: DEBUG createNativeListener: listening 49953
03-24 17:39:20.748  3273  3332 I jxcore-log: 
,03-24 17:39:20.750  3273  3332 I jxcore-log: ok 112 first call should succeed
03-24 17:39:20.750  3273  3332 I jxcore-log: 
,03-24 17:39:20.750  3273  3332 I jxcore-log: ok 113 first call should succeed
03-24 17:39:20.750  3273  3332 I jxcore-log: 
,03-24 17:39:20.754  3273  3332 I jxcore-log: ok 114 specific error should be returned
03-24 17:39:20.754  3273  3332 I jxcore-log: 
,03-24 17:39:20.757  3273  3332 I jxcore-log: # teardown
03-24 17:39:20.757  3273  3332 I jxcore-log: 
,03-24 17:39:20.869  3273  3332 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections,
03-24 17:39:20.870  3273  3332 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 17:39:20.870  3273  3332 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 17:39:20.874  3273  3332 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements,
,03-24 17:39:20.874  3273  3332 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 17:39:20.875  3273  3332 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 17:39:20.881  3273  3332 I jxcore-log: ok 115 error should be null
03-24 17:39:20.881  3273  3332 I jxcore-log: 
,03-24 17:39:20.881  3273  3332 I jxcore-log: ok 116 error should be null
03-24 17:39:20.881  3273  3332 I jxcore-log: 
,03-24 17:39:20.887  3273  3332 I jxcore-log: # setup
03-24 17:39:20.887  3273  3332 I jxcore-log: 
,03-24 17:39:21.030  3273  3332 I jxcore-log: # 29. does not emit duplicate discoveryAdvertisingStateUpdate
03-24 17:39:21.030  3273  3332 I jxcore-log: 
,03-24 17:39:21.146  3273  3332 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 17:39:21.146  3273  3332 I jxcore-log: 
,03-24 17:39:21.148  3273  3332 I jxcore-log: DEBUG createNativeListener: listening 48414
03-24 17:39:21.148  3273  3332 I jxcore-log: 
,03-24 17:39:21.157  3273  3332 I io.jxcore.node.ConnectionHelper: start: Port number: 58482, start advertisements: false
,03-24 17:39:21.158  3273  3332 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 17:39:21.158  3273  3332 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 17:39:21.158  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-24 17:39:21.164  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 17:39:21.164  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 17:39:21.164  3273  3332 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null],
,03-24 17:39:21.170  2157  2222 D BtGatt.GattService: registerClient() - UUID=e4d678cf-8161-4225-8df9-98bad5074999,
03-24 17:39:21.171  2157  2220 D BtGatt.GattService: onClientRegistered() - UUID=e4d678cf-8161-4225-8df9-98bad5074999, clientIf=5
03-24 17:39:21.171  3273  3292 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 17:39:21.172  2157  2172 D BtGatt.GattService: start scan with filters
,03-24 17:39:21.173  2157  2231 D BtGatt.ScanManager: handling starting scan
,03-24 17:39:21.174  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 17:39:21.174  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-24 17:39:21.174  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-24 17:39:21.174  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,03-24 17:39:21.174  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 17:39:21.175  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 17:39:21.175  3273  3273 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 17:39:21.177   823   838 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 17:39:21.181  2157  2220 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 17:39:21.181  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:39:21.182  2157  2220 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 17:39:21.183  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:39:21.183  2157  2231 D BtGatt.ScanManager: Starting BLE batch scan
03-24 17:39:21.183  2157  2231 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 17:39:21.185  2157  2220 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 17:39:21.185  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:39:21.186  2157  2220 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 17:39:21.186  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:39:21.188  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-24 17:39:21.188  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 17:39:21.188  3273  3332 I io.jxcore.node.ConnectionHelper: start: OK
03-24 17:39:21.189  3273  3273 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 17:39:21.189  3273  3273 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 17:39:21.189  3273  3273 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-24 17:39:21.197  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
,03-24 17:39:21.197  3273  3332 I jxcore-log: 
03-24 17:39:21.198  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 17:39:21.198  3273  3332 I jxcore-log: 
,03-24 17:39:21.215  3273  3332 I io.jxcore.node.ConnectionHelper: start: Port number: 48414, start advertisements: true,
03-24 17:39:21.215  3273  3332 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 17:39:21.215  3273  3332 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,03-24 17:39:21.215  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-24 17:39:21.220  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-24 17:39:21.220  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
03-24 17:39:21.220  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,03-24 17:39:21.220  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 17:39:21.220  3273  3332 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 17:39:21.220  3273  3332 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-24 17:39:21.220  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 17:39:21.220  3273  3332 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-24 17:39:21.226  2157  2222 D BtGatt.GattService: registerClient() - UUID=b50fa233-400a-4290-9987-86971b49e12e
,03-24 17:39:21.226  2157  2220 D BtGatt.GattService: onClientRegistered() - UUID=b50fa233-400a-4290-9987-86971b49e12e, clientIf=6
03-24 17:39:21.227  3273  3291 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-24 17:39:21.228  2157  2230 D BtGatt.AdvertiseManager: message : 0
,03-24 17:39:21.233  2157  2230 D BtGatt.AdvertiseManager: starting multi advertising,
,03-24 17:39:21.237  2157  2220 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 17:39:21.239  2157  2220 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0,
03-24 17:39:21.240  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-24 17:39:21.240  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 17:39:21.240  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,03-24 17:39:21.240  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-24 17:39:21.240  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-24 17:39:21.241  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING],
03-24 17:39:21.241  3273  3273 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-24 17:39:21.241   823  1104 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 17:39:21.244  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 17:39:21.244  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-24 17:39:21.244  3273  3332 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-24 17:39:21.244  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-24 17:39:21.244  3273  3273 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-24 17:39:21.245  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-24 17:39:21.245  3273  3332 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-24 17:39:21.245  3273  3332 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,03-24 17:39:21.245  3273  3332 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-24 17:39:21.246  3273  3332 I io.jxcore.node.ConnectionHelper: start: OK
03-24 17:39:21.246  3273  3273 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,03-24 17:39:21.246  3273  3273 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 17:39:21.246  3273  3273 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-24 17:39:21.249   823  1417 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 17:39:21.250  3273  3791 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-24 17:39:21.253  3273  3791 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
03-24 17:39:21.257  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-24 17:39:21.257  3273  3332 I jxcore-log: 
,03-24 17:39:21.263  3273  3332 I jxcore-log: ok 117 called only once,
03-24 17:39:21.263  3273  3332 I jxcore-log: 
03-24 17:39:21.263  3273  3332 I jxcore-log: ok 118 discovery state matches
03-24 17:39:21.263  3273  3332 I jxcore-log: 
,03-24 17:39:21.264  3273  3332 I jxcore-log: ok 119 advertising state matches
03-24 17:39:21.264  3273  3332 I jxcore-log: 
,03-24 17:39:21.273  3273  3332 I jxcore-log: # teardown
03-24 17:39:21.273  3273  3332 I jxcore-log: 
,03-24 17:39:21.768  3273  3332 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 17:39:21.768  3273  3332 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-24 17:39:21.769  3273  3332 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-24 17:39:21.769  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-24 17:39:21.769  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-24 17:39:21.772  3273  3332 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-24 17:39:21.773  3273  3791 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close,
,03-24 17:39:21.773  3273  3791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread,
03-24 17:39:21.774  3273  3791 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-24 17:39:21.774  3273  3273 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-24 17:39:21.775  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-24 17:39:21.775  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-24 17:39:21.775  3273  3273 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,03-24 17:39:21.775  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 17:39:21.775  3273  3273 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-24 17:39:21.775  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,03-24 17:39:21.775  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-24 17:39:21.775  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-24 17:39:21.778  2157  2173 D BtGatt.GattService: stopScan() - queue size =1
,03-24 17:39:21.780  2157  2173 D BtGatt.GattService: unregisterClient() - clientIf=5
03-24 17:39:21.781  2157  2220 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 17:39:21.781  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:39:21.781  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 17:39:21.782  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 17:39:21.782  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false,
03-24 17:39:21.782  2157  2231 D BtGatt.ScanManager: stopping BLe Batch
03-24 17:39:21.782  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-24 17:39:21.783  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
,03-24 17:39:21.783  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 17:39:21.783  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...,
03-24 17:39:21.784  2157  2220 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 17:39:21.785  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 17:39:21.785  2157  2231 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 17:39:21.787  2157  2230 D BtGatt.AdvertiseManager: message : 1
,03-24 17:39:21.788  2157  2220 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,03-24 17:39:21.788  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:39:21.788  2157  2220 D BtGatt.GattService: current time is 201216099556
03-24 17:39:21.788  2157  2220 D BtGatt.GattService: Batch record : [-117, -56, 84, -34, 10, 113, 1, -128, -62, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -65, 3, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-24 17:39:21.789  2157  2220 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,03-24 17:39:21.790  2157  2220 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-24 17:39:21.790  2157  2230 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-24 17:39:21.793  2157  2220 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 17:39:21.793  2157  2220 D BtGatt.GattService: Client app is not null!,
03-24 17:39:21.795  2157  2173 D BtGatt.GattService: unregisterClient() - clientIf=6
03-24 17:39:21.795  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-24 17:39:21.796  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED,
,03-24 17:39:21.796  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-24 17:39:21.796  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,03-24 17:39:21.796  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-24 17:39:21.796  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-24 17:39:21.796  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,03-24 17:39:21.796  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...,
,03-24 17:39:21.798  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-24 17:39:21.798  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 17:39:21.799  3273  3273 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 17:39:21.799  3273  3273 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 17:39:21.799  3273  3273 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 17:39:21.799  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 17:39:21.799  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-24 17:39:21.802  3273  3332 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 17:39:21.803  3273  3332 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 17:39:21.803  3273  3332 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 17:39:21.806  3273  3332 I jxcore-log: INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
03-24 17:39:21.806  3273  3332 I jxcore-log: 
03-24 17:39:21.807  3273  3332 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-24 17:39:21.807  3273  3332 I jxcore-log: 
,03-24 17:39:21.809  3273  3332 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-24 17:39:21.809  3273  3332 I jxcore-log: 
,03-24 17:39:21.810  3273  3273 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-24 17:39:21.811   823  1151 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 17:39:21.818  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-24 17:39:21.820  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-24 17:39:21.820  3273  3273 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 17:39:21.825  3273  3273 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 17:39:21.825  3273  3273 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-24 17:39:21.825  3273  3273 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-24 17:39:21.828  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-24 17:39:21.828  3273  3332 I jxcore-log: 
,03-24 17:39:21.831  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 17:39:21.831  3273  3332 I jxcore-log: 
,03-24 17:39:21.833  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 17:39:21.833  3273  3332 I jxcore-log: 
,03-24 17:39:21.841  3273  3332 I jxcore-log: ok 120 error should be null
03-24 17:39:21.841  3273  3332 I jxcore-log: 
,03-24 17:39:21.843  3273  3332 I jxcore-log: ok 121 error should be null
03-24 17:39:21.843  3273  3332 I jxcore-log: 
,03-24 17:39:21.854  3273  3332 I jxcore-log: # setup
03-24 17:39:21.854  3273  3332 I jxcore-log: 
,03-24 17:39:21.977  3273  3332 I jxcore-log: # 30. does not send duplicate availability changes
03-24 17:39:21.977  3273  3332 I jxcore-log: 
,03-24 17:39:22.260  3273  3332 I jxcore-log: ok 122 should be called once
03-24 17:39:22.260  3273  3332 I jxcore-log: 
,03-24 17:39:22.262  3273  3332 I jxcore-log: ok 123 should not have been called more than once
03-24 17:39:22.262  3273  3332 I jxcore-log: 
,03-24 17:39:22.265  3273  3332 I jxcore-log: # teardown
03-24 17:39:22.265  3273  3332 I jxcore-log: 
,03-24 17:39:22.486  3273  3332 I jxcore-log: ok 124 error should be null
03-24 17:39:22.486  3273  3332 I jxcore-log: 
,03-24 17:39:22.488  3273  3332 I jxcore-log: ok 125 error should be null
03-24 17:39:22.488  3273  3332 I jxcore-log: 
03-24 17:39:22.493  3273  3332 I jxcore-log: # setup
03-24 17:39:22.493  3273  3332 I jxcore-log: 
,03-24 17:39:22.662  3273  3332 I jxcore-log: # 31. can get the network status
03-24 17:39:22.662  3273  3332 I jxcore-log: 
,03-24 17:39:22.855  3273  3332 I jxcore-log: ok 126 network status should have certain non-empty properties
03-24 17:39:22.855  3273  3332 I jxcore-log: 
03-24 17:39:22.861  3273  3332 I jxcore-log: # teardown
03-24 17:39:22.861  3273  3332 I jxcore-log: 
,03-24 17:39:23.043  3273  3332 I jxcore-log: ok 127 error should be null
03-24 17:39:23.043  3273  3332 I jxcore-log: 
03-24 17:39:23.044  3273  3332 I jxcore-log: ok 128 error should be null
03-24 17:39:23.044  3273  3332 I jxcore-log: 
03-24 17:39:23.045  3273  3332 I jxcore-log: # setup
03-24 17:39:23.045  3273  3332 I jxcore-log: 
,03-24 17:39:23.164  3273  3332 I jxcore-log: # 32. wifi peer is marked unavailable if announcements stop
03-24 17:39:23.164  3273  3332 I jxcore-log: 
,03-24 17:39:23.516  3273  3332 I jxcore-log: ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined
03-24 17:39:23.516  3273  3332 I jxcore-log: 
,03-24 17:39:23.541  3273  3332 I jxcore-log: ok 129 host address should match
03-24 17:39:23.541  3273  3332 I jxcore-log: 
03-24 17:39:23.541  3273  3332 I jxcore-log: ok 130 port should match
03-24 17:39:23.541  3273  3332 I jxcore-log: 
,03-24 17:39:25.522  3273  3332 I jxcore-log: ok 131 host address should be null
03-24 17:39:25.522  3273  3332 I jxcore-log: 
,03-24 17:39:25.524  3273  3332 I jxcore-log: ok 132 port should should be null
03-24 17:39:25.524  3273  3332 I jxcore-log: 
,03-24 17:39:25.545  3273  3332 I jxcore-log: # teardown
03-24 17:39:25.545  3273  3332 I jxcore-log: 
,03-24 17:39:25.684  3273  3332 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-24 17:39:25.684  3273  3332 I jxcore-log: 
,03-24 17:39:25.687  3273  3332 I jxcore-log: ok 133 error should be null
03-24 17:39:25.687  3273  3332 I jxcore-log: 
,03-24 17:39:25.687  3273  3332 I jxcore-log: ok 134 error should be null
03-24 17:39:25.687  3273  3332 I jxcore-log: 
,03-24 17:39:25.689  3273  3332 I jxcore-log: # setup
03-24 17:39:25.689  3273  3332 I jxcore-log: 
,03-24 17:39:25.773  3273  3332 I jxcore-log: # 33. Can call start/stopListeningForAdvertisements
03-24 17:39:25.773  3273  3332 I jxcore-log: 
,03-24 17:39:25.893  3273  3332 I io.jxcore.node.ConnectionHelper: start: Port number: 48414, start advertisements: false
03-24 17:39:25.893  3273  3332 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-24 17:39:25.893  3273  3332 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 17:39:25.893  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-24 17:39:25.901  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 17:39:25.901  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-24 17:39:25.902  3273  3332 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null],
,03-24 17:39:25.911  2157  2172 D BtGatt.GattService: registerClient() - UUID=eb261787-9699-4c65-8afd-5a5f072d9535,
03-24 17:39:25.912  2157  2220 D BtGatt.GattService: onClientRegistered() - UUID=eb261787-9699-4c65-8afd-5a5f072d9535, clientIf=5
03-24 17:39:25.913  3273  3292 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-24 17:39:25.914  2157  2222 D BtGatt.GattService: start scan with filters
,03-24 17:39:25.918  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
03-24 17:39:25.918  2157  2231 D BtGatt.ScanManager: handling starting scan
03-24 17:39:25.918  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 17:39:25.919  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-24 17:39:25.920  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-24 17:39:25.920  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 17:39:25.920  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 17:39:25.920  3273  3273 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-24 17:39:25.921   823  1153 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 17:39:25.930  2157  2220 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 17:39:25.930  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 17:39:25.933  2157  2220 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 17:39:25.933  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 17:39:25.933  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 17:39:25.933  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:39:25.934  3273  3332 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 17:39:25.934  3273  3273 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 17:39:25.934  2157  2231 D BtGatt.ScanManager: Starting BLE batch scan
03-24 17:39:25.934  3273  3273 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-24 17:39:25.934  2157  2231 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 17:39:25.934  3273  3273 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 17:39:25.938  2157  2220 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 17:39:25.938  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:39:25.940  3273  3332 I jxcore-log: ok 135 Can call startListeningForAdvertisements without error
03-24 17:39:25.940  3273  3332 I jxcore-log: 
03-24 17:39:25.941  2157  2220 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 17:39:25.941  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:39:25.943  3273  3332 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 17:39:25.943  3273  3332 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-24 17:39:25.943  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-24 17:39:25.943  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-24 17:39:25.945  2157  2222 D BtGatt.GattService: stopScan() - queue size =1
03-24 17:39:25.946  2157  2173 D BtGatt.GattService: unregisterClient() - clientIf=5,
,03-24 17:39:25.947  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 17:39:25.947  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 17:39:25.947  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-24 17:39:25.947  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,03-24 17:39:25.947  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-24 17:39:25.947  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 17:39:25.947  2157  2220 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 17:39:25.947  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:39:25.948  3273  3273 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 17:39:25.948  3273  3273 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 17:39:25.948  3273  3273 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 17:39:25.948  2157  2231 D BtGatt.ScanManager: stopping BLe Batch
,03-24 17:39:25.949  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 17:39:25.949  3273  3332 I jxcore-log: 
03-24 17:39:25.950  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 17:39:25.950  3273  3332 I jxcore-log: 
03-24 17:39:25.951  2157  2220 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,03-24 17:39:25.951  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:39:25.951  2157  2231 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 17:39:25.952  2157  2220 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
03-24 17:39:25.952  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:39:25.953  3273  3332 I jxcore-log: ok 136 Can call stopListeningForAdvertisements without error
03-24 17:39:25.953  3273  3332 I jxcore-log: ,
,03-24 17:39:25.958  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 17:39:25.958  3273  3332 I jxcore-log: 
,03-24 17:39:25.960  3273  3332 I jxcore-log: # teardown
03-24 17:39:25.960  3273  3332 I jxcore-log: 
,03-24 17:39:26.199  3273  3332 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 17:39:26.199  3273  3332 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 17:39:26.199  3273  3332 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 17:39:26.204  3273  3332 I jxcore-log: ok 137 Should be able to call stopListeningForAdvertisments in teardown
03-24 17:39:26.204  3273  3332 I jxcore-log: 
,03-24 17:39:26.204  3273  3332 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-24 17:39:26.205  3273  3332 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 17:39:26.205  3273  3332 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
03-24 17:39:26.205  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-24 17:39:26.205  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-24 17:39:26.205  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,03-24 17:39:26.205  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 17:39:26.205  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-24 17:39:26.206  3273  3332 D BluetoothLeScanner: could not find callback wrapper
03-24 17:39:26.206  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-24 17:39:26.208  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 17:39:26.208  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 17:39:26.208  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-24 17:39:26.209  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-24 17:39:26.209  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 17:39:26.210  3273  3273 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 17:39:26.210  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 17:39:26.210  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-24 17:39:26.218  3273  3273 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-24 17:39:26.219   823  1404 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 17:39:26.226  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-24 17:39:26.227  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-24 17:39:26.227  3273  3273 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 17:39:26.233  3273  3273 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-24 17:39:26.233  3273  3273 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-24 17:39:26.233  3273  3273 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-24 17:39:26.235  3273  3332 I jxcore-log: ok 138 Should be able to call stopAdvertisingAndListening in teardown
03-24 17:39:26.235  3273  3332 I jxcore-log: 
,03-24 17:39:26.246  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 17:39:26.246  3273  3332 I jxcore-log: ,
03-24 17:39:26.248  3273  3332 I jxcore-log: # setup
03-24 17:39:26.248  3273  3332 I jxcore-log: 
,03-24 17:39:26.330  3273  3332 I jxcore-log: # 34. Calling startListeningForAdvertisements twice is NOT an error
03-24 17:39:26.330  3273  3332 I jxcore-log: 
,03-24 17:39:26.503  3273  3332 I io.jxcore.node.ConnectionHelper: start: Port number: 48414, start advertisements: false
,03-24 17:39:26.503  3273  3332 V io.jxcore.node.ConnectivityMonitor: start: Already started,
,03-24 17:39:26.503  3273  3332 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 17:39:26.503  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-24 17:39:26.510  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 17:39:26.510  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-24 17:39:26.510  3273  3332 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 17:39:26.520  2157  2173 D BtGatt.GattService: registerClient() - UUID=a914b924-a594-4603-a724-833a0a99e4ca
,03-24 17:39:26.521  2157  2220 D BtGatt.GattService: onClientRegistered() - UUID=a914b924-a594-4603-a724-833a0a99e4ca, clientIf=5
,03-24 17:39:26.522  3273  3327 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 17:39:26.523  2157  2222 D BtGatt.GattService: start scan with filters
,03-24 17:39:26.524  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
,03-24 17:39:26.525  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-24 17:39:26.525  2157  2231 D BtGatt.ScanManager: handling starting scan
03-24 17:39:26.525  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING],
,03-24 17:39:26.525  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-24 17:39:26.525  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 17:39:26.525  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-24 17:39:26.526  3273  3273 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 17:39:26.527   823  1404 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 17:39:26.529  2157  2220 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 17:39:26.530  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:39:26.532  2157  2220 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 17:39:26.532  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 17:39:26.532  2157  2231 D BtGatt.ScanManager: Starting BLE batch scan
03-24 17:39:26.533  2157  2231 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 17:39:26.536  2157  2220 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 17:39:26.536  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:39:26.538  2157  2220 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1,
03-24 17:39:26.538  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:39:26.539  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-24 17:39:26.540  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-24 17:39:26.540  3273  3332 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 17:39:26.540  3273  3273 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 17:39:26.540  3273  3273 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 17:39:26.541  3273  3273 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-24 17:39:26.546  3273  3332 I jxcore-log: ok 139 Can call startListeningForAdvertisements without error
03-24 17:39:26.546  3273  3332 I jxcore-log: 
,03-24 17:39:26.555  3273  3332 I io.jxcore.node.ConnectionHelper: start: Port number: 48414, start advertisements: false
,03-24 17:39:26.555  3273  3332 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 17:39:26.555  3273  3332 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 17:39:26.555  3273  3332 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 17:39:26.556  3273  3332 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 17:39:26.559  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false},
03-24 17:39:26.559  3273  3332 I jxcore-log: 
,03-24 17:39:26.561  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 17:39:26.561  3273  3332 I jxcore-log: 
,03-24 17:39:26.563  3273  3332 I jxcore-log: ok 140 Can call startListeningForAdvertisements twice without error
03-24 17:39:26.563  3273  3332 I jxcore-log: 
,03-24 17:39:26.574  3273  3332 I jxcore-log: # teardown
03-24 17:39:26.574  3273  3332 I jxcore-log: 
,03-24 17:39:27.042  2157  2157 D BtGatt.ScanManager: awakened up at time 206469
,03-24 17:39:27.043  2157  2231 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 17:39:27.053  2157  2220 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 17:39:27.053  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 17:39:27.781  3273  3332 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 17:39:27.782  3273  3332 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 17:39:27.782  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-24 17:39:27.782  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-24 17:39:27.787  2157  2172 D BtGatt.GattService: stopScan() - queue size =1
,03-24 17:39:27.789  2157  2173 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-24 17:39:27.792  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-24 17:39:27.792  2157  2220 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 17:39:27.792  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:39:27.792  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 17:39:27.792  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,03-24 17:39:27.793  2157  2231 D BtGatt.ScanManager: stopping BLe Batch
03-24 17:39:27.793  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED],
03-24 17:39:27.793  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,03-24 17:39:27.793  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 17:39:27.797  2157  2220 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 17:39:27.797  3273  3273 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-24 17:39:27.797  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:39:27.797  3273  3273 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-24 17:39:27.797  3273  3273 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 17:39:27.798  2157  2231 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 17:39:27.799  2157  2220 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
03-24 17:39:27.799  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 17:39:27.805  3273  3332 I jxcore-log: ok 141 Should be able to call stopListeningForAdvertisments in teardown
,03-24 17:39:27.805  3273  3332 I jxcore-log: 
03-24 17:39:27.805  3273  3332 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 17:39:27.805  3273  3332 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
03-24 17:39:27.805  3273  3332 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
03-24 17:39:27.805  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
,03-24 17:39:27.806  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...,
03-24 17:39:27.806  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 17:39:27.806  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,03-24 17:39:27.806  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-24 17:39:27.808  3273  3332 D BluetoothLeScanner: could not find callback wrapper
,03-24 17:39:27.809  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 17:39:27.811  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 17:39:27.811  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 17:39:27.811  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-24 17:39:27.812  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
,03-24 17:39:27.813  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 17:39:27.813  3273  3273 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 17:39:27.813  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 17:39:27.813  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-24 17:39:27.816  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 17:39:27.816  3273  3332 I jxcore-log: 
,03-24 17:39:27.822  3273  3273 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-24 17:39:27.822   823  1413 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 17:39:27.828  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-24 17:39:27.830  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 17:39:27.830  3273  3273 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 17:39:27.836  3273  3273 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-24 17:39:27.836  3273  3273 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 17:39:27.836  3273  3273 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-24 17:39:27.841  3273  3332 I jxcore-log: ok 142 Should be able to call stopAdvertisingAndListening in teardown
03-24 17:39:27.841  3273  3332 I jxcore-log: 
,03-24 17:39:27.847  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 17:39:27.847  3273  3332 I jxcore-log: 
,03-24 17:39:27.850  3273  3332 I jxcore-log: # setup
03-24 17:39:27.850  3273  3332 I jxcore-log: 
,03-24 17:39:27.935  3273  3332 I jxcore-log: # 35. Can call start/stopUpdateAdvertisingAndListening
,03-24 17:39:27.935  3273  3332 I jxcore-log: 
,03-24 17:39:28.195  3273  3332 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: true,
03-24 17:39:28.195  3273  3332 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 17:39:28.195  3273  3332 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-24 17:39:28.195  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-24 17:39:28.201  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser,
,03-24 17:39:28.201  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 17:39:28.201  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-24 17:39:28.201  3273  3332 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 17:39:28.208  2157  2172 D BtGatt.GattService: registerClient() - UUID=f89403f6-e043-4905-91f4-525124a2cdb1,
,03-24 17:39:28.208  2157  2220 D BtGatt.GattService: onClientRegistered() - UUID=f89403f6-e043-4905-91f4-525124a2cdb1, clientIf=5
,03-24 17:39:28.209  3273  3327 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 17:39:28.209  2157  2173 D BtGatt.GattService: start scan with filters
,03-24 17:39:28.212  2157  2231 D BtGatt.ScanManager: handling starting scan
,03-24 17:39:28.213  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 17:39:28.213  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true,
03-24 17:39:28.213  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,03-24 17:39:28.213  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-24 17:39:28.213  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
,03-24 17:39:28.213  3273  3273 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 17:39:28.213  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,03-24 17:39:28.214  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,03-24 17:39:28.214  3273  3332 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
,03-24 17:39:28.220  3273  3332 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false],
03-24 17:39:28.220  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-24 17:39:28.220  3273  3332 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-24 17:39:28.220  2157  2220 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 17:39:28.220  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 17:39:28.222  2157  2220 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,03-24 17:39:28.222  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:39:28.223  2157  2231 D BtGatt.ScanManager: Starting BLE batch scan
,03-24 17:39:28.223  2157  2231 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 17:39:28.225  2157  2220 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 17:39:28.225  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:39:28.227  2157  2220 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 17:39:28.227  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 17:39:28.235  2157  2222 D BtGatt.GattService: registerClient() - UUID=d03fed56-7401-4c39-aadb-143d5b3b35c0
,03-24 17:39:28.235  2157  2220 D BtGatt.GattService: onClientRegistered() - UUID=d03fed56-7401-4c39-aadb-143d5b3b35c0, clientIf=6
03-24 17:39:28.235  3273  3292 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-24 17:39:28.237  2157  2230 D BtGatt.AdvertiseManager: message : 0
,03-24 17:39:28.240  2157  2230 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 17:39:28.243  2157  2220 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 17:39:28.245  2157  2220 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 17:39:28.246  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-24 17:39:28.246  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 17:39:28.246   823   838 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 17:39:28.252  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-24 17:39:28.253  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-24 17:39:28.253  3273  3332 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-24 17:39:28.253  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 17:39:28.255  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-24 17:39:28.255  3273  3332 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,03-24 17:39:28.255  3273  3332 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-24 17:39:28.255  3273  3332 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-24 17:39:28.256  3273  3273 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,03-24 17:39:28.256  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 17:39:28.256  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-24 17:39:28.256  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-24 17:39:28.257  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
,03-24 17:39:28.257  3273  3273 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-24 17:39:28.257  3273  3273 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-24 17:39:28.257  3273  3273 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 17:39:28.257  3273  3273 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,03-24 17:39:28.257  3273  3273 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 17:39:28.257  3273  3273 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-24 17:39:28.257  3273  3273 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 17:39:28.258  3273  3332 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 17:39:28.258   823  1413 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 17:39:28.261  3273  3793 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-24 17:39:28.263  3273  3793 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-24 17:39:28.267  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false},
03-24 17:39:28.267  3273  3332 I jxcore-log: 
,03-24 17:39:28.271  3273  3332 I jxcore-log: ok 143 Can call startUpdateAdvertisingAndListening without error,
03-24 17:39:28.271  3273  3332 I jxcore-log: 
,03-24 17:39:28.273  3273  3332 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections,
03-24 17:39:28.273  3273  3332 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-24 17:39:28.273  3273  3332 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,03-24 17:39:28.273  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-24 17:39:28.273  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-24 17:39:28.274  3273  3332 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-24 17:39:28.274  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-24 17:39:28.274  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,03-24 17:39:28.274  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 17:39:28.274  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 17:39:28.274  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-24 17:39:28.274  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-24 17:39:28.275  3273  3793 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-24 17:39:28.276  2157  2172 D BtGatt.GattService: stopScan() - queue size =1
,03-24 17:39:28.275  3273  3793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,03-24 17:39:28.277  3273  3793 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-24 17:39:28.278  2157  2172 D BtGatt.GattService: unregisterClient() - clientIf=5
03-24 17:39:28.278  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-24 17:39:28.278  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 17:39:28.278  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-24 17:39:28.279  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
,03-24 17:39:28.279  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-24 17:39:28.279  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 17:39:28.279  2157  2220 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 17:39:28.279  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 17:39:28.279  2157  2231 D BtGatt.ScanManager: stopping BLe Batch
03-24 17:39:28.279  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-24 17:39:28.282  2157  2230 D BtGatt.AdvertiseManager: message : 1
,03-24 17:39:28.282  2157  2220 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 17:39:28.282  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:39:28.282  2157  2231 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 17:39:28.283  2157  2230 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-24 17:39:28.283  2157  2220 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 17:39:28.284  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 17:39:28.288  2157  2220 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 17:39:28.288  2157  2220 D BtGatt.GattService: Client app is not null!,
03-24 17:39:28.290  2157  2172 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-24 17:39:28.291  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
03-24 17:39:28.291  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-24 17:39:28.291  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,03-24 17:39:28.292  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-24 17:39:28.292  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,03-24 17:39:28.292  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 17:39:28.292  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 17:39:28.292  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-24 17:39:28.294  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,03-24 17:39:28.294  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,03-24 17:39:28.294  3273  3273 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 17:39:28.294  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 17:39:28.294  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-24 17:39:28.298  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 17:39:28.298  3273  3332 I jxcore-log: 
,03-24 17:39:28.301  3273  3273 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-24 17:39:28.301   823  1417 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 17:39:28.302  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-24 17:39:28.302  3273  3332 I jxcore-log: 
,03-24 17:39:28.308  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-24 17:39:28.309  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 17:39:28.309  3273  3273 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 17:39:28.313  3273  3273 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-24 17:39:28.313  3273  3273 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-24 17:39:28.313  3273  3273 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-24 17:39:28.314  3273  3273 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 17:39:28.314  3273  3273 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 17:39:28.314  3273  3273 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 17:39:28.314  3273  3273 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 17:39:28.314  3273  3273 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-24 17:39:28.316  3273  3332 I jxcore-log: ok 144 Can call stopAdvertisingAndListening without error
03-24 17:39:28.316  3273  3332 I jxcore-log: 
,03-24 17:39:28.330  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-24 17:39:28.330  3273  3332 I jxcore-log: 
,03-24 17:39:28.333  3273  3332 I jxcore-log: # teardown
03-24 17:39:28.333  3273  3332 I jxcore-log: 
,03-24 17:39:28.335  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 17:39:28.335  3273  3332 I jxcore-log: 
,03-24 17:39:28.336  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 17:39:28.336  3273  3332 I jxcore-log: 
,03-24 17:39:28.599  3273  3332 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 17:39:28.599  3273  3332 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 17:39:28.599  3273  3332 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 17:39:28.608  3273  3332 I jxcore-log: ok 145 Should be able to call stopListeningForAdvertisments in teardown
03-24 17:39:28.608  3273  3332 I jxcore-log: 
03-24 17:39:28.610  3273  3332 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-24 17:39:28.610  3273  3332 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 17:39:28.610  3273  3332 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 17:39:28.614  3273  3332 I jxcore-log: ok 146 Should be able to call stopAdvertisingAndListening in teardown
03-24 17:39:28.614  3273  3332 I jxcore-log: 
,03-24 17:39:28.620  3273  3332 I jxcore-log: # setup
03-24 17:39:28.620  3273  3332 I jxcore-log: 
,03-24 17:39:28.946  3273  3332 I jxcore-log: # 36. Calling startUpdateAdvertisingAndListening twice is NOT an error
03-24 17:39:28.946  3273  3332 I jxcore-log: 
,03-24 17:39:29.105  3273  3332 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: true
,03-24 17:39:29.105  3273  3332 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 17:39:29.106  3273  3332 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-24 17:39:29.106  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-24 17:39:29.115  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-24 17:39:29.116  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 17:39:29.116  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-24 17:39:29.116  3273  3332 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 17:39:29.125  2157  2172 D BtGatt.GattService: registerClient() - UUID=9d406b79-f2ff-4603-87c6-b5af46a892f8
03-24 17:39:29.126  2157  2220 D BtGatt.GattService: onClientRegistered() - UUID=9d406b79-f2ff-4603-87c6-b5af46a892f8, clientIf=5
03-24 17:39:29.127  3273  3327 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-24 17:39:29.134  2157  2173 D BtGatt.GattService: start scan with filters,
,03-24 17:39:29.137  2157  2231 D BtGatt.ScanManager: handling starting scan
,03-24 17:39:29.141  2157  2220 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 17:39:29.141  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 17:39:29.143  2157  2220 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,03-24 17:39:29.143  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:39:29.144  2157  2231 D BtGatt.ScanManager: Starting BLE batch scan
03-24 17:39:29.144  2157  2231 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 17:39:29.145  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-24 17:39:29.145  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 17:39:29.146  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-24 17:39:29.146  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,03-24 17:39:29.146  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 17:39:29.147  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,03-24 17:39:29.147  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 17:39:29.147  3273  3273 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 17:39:29.147  2157  2220 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 17:39:29.147  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 17:39:29.148  3273  3332 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 17:39:29.149  2157  2220 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 17:39:29.149  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:39:29.150  3273  3332 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-24 17:39:29.151  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 17:39:29.151  3273  3332 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-24 17:39:29.159  2157  2173 D BtGatt.GattService: registerClient() - UUID=4fe72a6a-0262-4585-bba0-f7ac8ef11763
03-24 17:39:29.159  2157  2220 D BtGatt.GattService: onClientRegistered() - UUID=4fe72a6a-0262-4585-bba0-f7ac8ef11763, clientIf=6
03-24 17:39:29.159  3273  3291 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-24 17:39:29.162  2157  2230 D BtGatt.AdvertiseManager: message : 0
,03-24 17:39:29.168  2157  2230 D BtGatt.AdvertiseManager: starting multi advertising,
,03-24 17:39:29.171  2157  2220 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 17:39:29.175  2157  2220 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0,
,03-24 17:39:29.176  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-24 17:39:29.176  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 17:39:29.177   823   838 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 17:39:29.182  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-24 17:39:29.183  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 17:39:29.183  3273  3332 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-24 17:39:29.183  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 17:39:29.185  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...,
03-24 17:39:29.186  3273  3332 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true,
03-24 17:39:29.186  3273  3332 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-24 17:39:29.186  3273  3332 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-24 17:39:29.189  3273  3273 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-24 17:39:29.189  3273  3332 I io.jxcore.node.ConnectionHelper: start: OK
03-24 17:39:29.189  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess,
03-24 17:39:29.190  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-24 17:39:29.190  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-24 17:39:29.190  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-24 17:39:29.190  3273  3273 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-24 17:39:29.190  3273  3273 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 17:39:29.190  3273  3273 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 17:39:29.190  3273  3273 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-24 17:39:29.190  3273  3273 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 17:39:29.191  3273  3273 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-24 17:39:29.191  3273  3273 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 17:39:29.192  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 17:39:29.192  3273  3332 I jxcore-log: 
03-24 17:39:29.193   823   839 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 17:39:29.195  3273  3794 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-24 17:39:29.195  3273  3332 I jxcore-log: ok 147 Can call startUpdateAdvertisingAndListening without error
03-24 17:39:29.195  3273  3332 I jxcore-log: 
,03-24 17:39:29.200  3273  3794 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-24 17:39:29.203  3273  3332 I io.jxcore.node.ConnectionHelper: start: Port number: 4243, start advertisements: true
03-24 17:39:29.203  3273  3332 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 17:39:29.203  3273  3332 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,03-24 17:39:29.203  3273  3332 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 17:39:29.203  3273  3332 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 17:39:29.207  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 17:39:29.207  3273  3332 I jxcore-log: 
,03-24 17:39:29.221  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true},
03-24 17:39:29.221  3273  3332 I jxcore-log: 
,03-24 17:39:29.223  3273  3332 I jxcore-log: ok 148 Can call startUpdateAdvertisingAndListening twice without error,
03-24 17:39:29.223  3273  3332 I jxcore-log: 
,03-24 17:39:29.228  3273  3332 I jxcore-log: # teardown,
03-24 17:39:29.228  3273  3332 I jxcore-log: 
,03-24 17:39:29.484  3273  3332 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 17:39:29.485  3273  3332 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
03-24 17:39:29.485  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-24 17:39:29.485  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-24 17:39:29.487  2157  2172 D BtGatt.GattService: stopScan() - queue size =1,
,03-24 17:39:29.492  2157  2173 D BtGatt.GattService: unregisterClient() - clientIf=5,
,03-24 17:39:29.493  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 17:39:29.493  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-24 17:39:29.493  2157  2220 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 17:39:29.493  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-24 17:39:29.493  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-24 17:39:29.493  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:39:29.494  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-24 17:39:29.494  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-24 17:39:29.494  3273  3273 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 17:39:29.494  3273  3273 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
,03-24 17:39:29.494  3273  3273 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 17:39:29.494  2157  2231 D BtGatt.ScanManager: stopping BLe Batch
03-24 17:39:29.496  2157  2220 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 17:39:29.496  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:39:29.496  3273  3332 I jxcore-log: ok 149 Should be able to call stopListeningForAdvertisments in teardown
03-24 17:39:29.496  3273  3332 I jxcore-log: 
03-24 17:39:29.496  2157  2231 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 17:39:29.497  3273  3332 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-24 17:39:29.497  3273  3332 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
03-24 17:39:29.497  3273  3332 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-24 17:39:29.497  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-24 17:39:29.497  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-24 17:39:29.497  3273  3332 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-24 17:39:29.497  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-24 17:39:29.497  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-24 17:39:29.497  3273  3794 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-24 17:39:29.497  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 17:39:29.497  3273  3794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-24 17:39:29.497  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,03-24 17:39:29.497  3273  3794 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-24 17:39:29.497  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-24 17:39:29.498  2157  2220 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-24 17:39:29.498  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:39:29.498  2157  2220 D BtGatt.GattService: current time is 208926342261
03-24 17:39:29.498  2157  2220 D BtGatt.GattService: Batch record : [13, -122, 107, -88, -23, 84, 1, -128, -64, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -47, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-24 17:39:29.499  3273  3332 D BluetoothLeScanner: could not find callback wrapper
03-24 17:39:29.499  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 17:39:29.499  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-24 17:39:29.499  2157  2220 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 17:39:29.499  2157  2230 D BtGatt.AdvertiseManager: message : 1
03-24 17:39:29.500  2157  2230 D BtGatt.AdvertiseManager: stop advertise for client 6
03-24 17:39:29.500  2157  2220 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
,03-24 17:39:29.501  2157  2220 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 17:39:29.501  2157  2220 D BtGatt.GattService: Client app is not null!
,03-24 17:39:29.502  2157  2222 D BtGatt.GattService: unregisterClient() - clientIf=6
03-24 17:39:29.502  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 17:39:29.503  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-24 17:39:29.503  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-24 17:39:29.503  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-24 17:39:29.503  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,03-24 17:39:29.503  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-24 17:39:29.503  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,03-24 17:39:29.503  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-24 17:39:29.504  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,03-24 17:39:29.504  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 17:39:29.504  3273  3273 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 17:39:29.504  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-24 17:39:29.505  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-24 17:39:29.507  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-24 17:39:29.507  3273  3332 I jxcore-log: ,
03-24 17:39:29.507  3273  3273 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-24 17:39:29.507   823   838 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 17:39:29.510  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-24 17:39:29.510  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-24 17:39:29.511  3273  3273 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-24 17:39:29.511  3273  3273 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,03-24 17:39:29.511  3273  3273 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 17:39:29.512  3273  3273 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 17:39:29.512  3273  3273 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
03-24 17:39:29.512  3273  3273 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 17:39:29.512  3273  3273 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-24 17:39:29.513  3273  3273 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-24 17:39:29.513  3273  3332 I jxcore-log: ok 150 Should be able to call stopAdvertisingAndListening in teardown
03-24 17:39:29.513  3273  3332 I jxcore-log: 
,03-24 17:39:29.516  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 17:39:29.516  3273  3332 I jxcore-log: 
03-24 17:39:29.517  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false},
03-24 17:39:29.517  3273  3332 I jxcore-log: 
03-24 17:39:29.518  3273  3332 I jxcore-log: # setup
03-24 17:39:29.518  3273  3332 I jxcore-log: 
,03-24 17:39:29.663  3273  3332 I jxcore-log: # 37. peerAvailabilityChange is called
03-24 17:39:29.663  3273  3332 I jxcore-log: 
,03-24 17:39:30.007  3273  3332 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: true
03-24 17:39:30.008  3273  3332 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 17:39:30.008  3273  3332 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-24 17:39:30.008  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-24 17:39:30.016  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-24 17:39:30.016  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 17:39:30.016  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 17:39:30.016  3273  3332 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 17:39:30.024  2157  2222 D BtGatt.GattService: registerClient() - UUID=d773b2b4-dcd8-4365-b8ba-18b05e197938
,03-24 17:39:30.025  2157  2220 D BtGatt.GattService: onClientRegistered() - UUID=d773b2b4-dcd8-4365-b8ba-18b05e197938, clientIf=5
,03-24 17:39:30.026  3273  3292 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 17:39:30.026  2157  2172 D BtGatt.GattService: start scan with filters
,03-24 17:39:30.029  2157  2231 D BtGatt.ScanManager: handling starting scan
03-24 17:39:30.029  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 17:39:30.029  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-24 17:39:30.029  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-24 17:39:30.029  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,03-24 17:39:30.030  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
,03-24 17:39:30.030  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 17:39:30.030  3273  3273 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 17:39:30.030  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 17:39:30.030  3273  3332 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
,03-24 17:39:30.031  3273  3332 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 17:39:30.031  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 17:39:30.031  3273  3332 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-24 17:39:30.034  2157  2220 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 17:39:30.034  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:39:30.036  2157  2220 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,03-24 17:39:30.036  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:39:30.036  2157  2231 D BtGatt.ScanManager: Starting BLE batch scan
,03-24 17:39:30.037  2157  2231 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 17:39:30.039  2157  2220 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 17:39:30.040  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 17:39:30.042  2157  2220 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 17:39:30.042  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 17:39:30.042  2157  2173 D BtGatt.GattService: registerClient() - UUID=ac2b279d-da24-4859-84eb-93f53e2bcc6b
03-24 17:39:30.043  2157  2220 D BtGatt.GattService: onClientRegistered() - UUID=ac2b279d-da24-4859-84eb-93f53e2bcc6b, clientIf=6
03-24 17:39:30.044  3273  3327 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-24 17:39:30.049  2157  2230 D BtGatt.AdvertiseManager: message : 0
,03-24 17:39:30.055  2157  2230 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 17:39:30.058  2157  2220 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 17:39:30.060  2157  2220 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 17:39:30.061  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-24 17:39:30.062  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-24 17:39:30.063   823   838 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 17:39:30.070  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-24 17:39:30.070  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 17:39:30.070  3273  3332 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-24 17:39:30.070  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-24 17:39:30.071  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-24 17:39:30.072  3273  3332 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,03-24 17:39:30.072  3273  3332 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-24 17:39:30.072  3273  3332 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-24 17:39:30.073  3273  3332 I io.jxcore.node.ConnectionHelper: start: OK
03-24 17:39:30.073  3273  3273 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-24 17:39:30.073  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 17:39:30.073  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-24 17:39:30.073  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,03-24 17:39:30.073  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-24 17:39:30.073  3273  3273 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-24 17:39:30.073  3273  3273 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 17:39:30.073  3273  3273 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 17:39:30.073  3273  3273 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-24 17:39:30.073  3273  3273 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 17:39:30.073  3273  3273 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-24 17:39:30.073  3273  3273 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-24 17:39:30.075   823  1413 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 17:39:30.076  3273  3795 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-24 17:39:30.077  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 17:39:30.077  3273  3332 I jxcore-log: 
,03-24 17:39:30.079  3273  3332 I jxcore-log: ok 151 Can call startUpdateAdvertisingAndListeningwithout error
,03-24 17:39:30.079  3273  3332 I jxcore-log: 
,03-24 17:39:30.081  3273  3795 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...,
,03-24 17:39:30.083  3273  3332 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: false
,03-24 17:39:30.083  3273  3332 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-24 17:39:30.083  3273  3332 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should affect listening to advertisements only
03-24 17:39:30.083  3273  3332 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 17:39:30.083  3273  3332 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 17:39:30.085  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false},
03-24 17:39:30.085  3273  3332 I jxcore-log: 
03-24 17:39:30.086  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-24 17:39:30.086  3273  3332 I jxcore-log: ,
03-24 17:39:30.087  3273  3332 I jxcore-log: ok 152 Can call startListeningForAdvertisements without error
03-24 17:39:30.087  3273  3332 I jxcore-log: 
,03-24 17:39:30.547  2157  2157 D BtGatt.ScanManager: awakened up at time 209975
,03-24 17:39:30.548  2157  2231 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 17:39:30.560  2157  2220 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-24 17:39:30.560  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:39:30.560  2157  2220 D BtGatt.GattService: current time is 209988189865
,03-24 17:39:30.560  2157  2220 D BtGatt.GattService: Batch record : [115, 121, 123, -124, -123, 75, 1, -128, -79, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -59, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-24 17:39:30.561  2157  2220 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81],
03-24 17:39:30.562  2157  2220 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64],
,03-24 17:39:30.565  3273  3273 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> E0:DB:10:14:E2:C0], added - the peer count is 1
,03-24 17:39:30.566  3273  3273 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 2
,03-24 17:39:30.566  3273  3273 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> E0:DB:10:14:E2:C0], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 
03-24 17:39:30.567  3273  3273 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
,03-24 17:39:30.572  3273  3332 I jxcore-log: ok 153 peers must be an array
03-24 17:39:30.572  3273  3332 I jxcore-log: 
03-24 17:39:30.574  3273  3332 I jxcore-log: ok 154 peers must not be zero-length
03-24 17:39:30.574  3273  3332 I jxcore-log: 
,03-24 17:39:30.576  3273  3332 I jxcore-log: ok 155 peer must have peerIdentifier
03-24 17:39:30.576  3273  3332 I jxcore-log: 
,03-24 17:39:30.598  3273  3332 I jxcore-log: ok 156 peerIdentifier must be a string,
03-24 17:39:30.598  3273  3332 I jxcore-log: 
03-24 17:39:30.599  3273  3332 I jxcore-log: ok 157 peer must have peerAvailable
03-24 17:39:30.599  3273  3332 I jxcore-log: ,
03-24 17:39:30.599  3273  3332 I jxcore-log: ok 158 peer must have pleaseConnect
03-24 17:39:30.599  3273  3332 I jxcore-log: 
,03-24 17:39:30.606  3273  3332 I jxcore-log: # teardown
,03-24 17:39:30.606  3273  3332 I jxcore-log: 
,03-24 17:39:30.863  3374  3796 V GoogleAuthProtoRequest: [342] a.<init>: mAccountName set to: thalitester@gmail.com
,03-24 17:39:30.959   823  1104 I art     : Explicit concurrent mark sweep GC freed 24555(1164KB) AllocSpace objects, 5(551KB) LOS objects, 32% free, 33MB/49MB, paused 1.367ms total 78.994ms
,03-24 17:39:31.009  1265  1281 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
03-24 17:39:31.009  1265  1281 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 17:39:31.009  1265  1281 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 17:39:31.009  1265  1281 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 17:39:31.011  1265  1281 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 17:39:31.021  3374  3796 W ExperimentUpdateService: [342] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,03-24 17:39:31.022  3374  3796 W ExperimentUpdateService: [342] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-24 17:39:31.022  3374  3796 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-24 17:39:31.022  3374  3796 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-24 17:39:31.022  3374  3796 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-24 17:39:31.022  3374  3796 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-24 17:39:31.022  3374  3796 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-24 17:39:31.022  3374  3796 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-24 17:39:31.022  3374  3796 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-24 17:39:31.022  3374  3796 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-24 17:39:31.022  3374  3796 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-24 17:39:31.022  3374  3796 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-24 17:39:31.064  2157  2157 D BtGatt.ScanManager: awakened up at time 210492
,03-24 17:39:31.067  2157  2231 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 17:39:31.070  2157  2220 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,03-24 17:39:31.070  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:39:31.070  2157  2220 D BtGatt.GattService: current time is 210498241688
03-24 17:39:31.070  2157  2220 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -60, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0, 115, 121, 123, -124, -123, 75, 1, -128, -79, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-24 17:39:31.071  2157  2220 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-24 17:39:31.071  2157  2220 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,03-24 17:39:31.074  3273  3273 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
,03-24 17:39:31.074  3273  3273 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> E0:DB:10:14:E2:C0] updated - the peer count is 2
,03-24 17:39:31.489  3273  3332 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements,
03-24 17:39:31.489  3273  3332 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
03-24 17:39:31.489  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-24 17:39:31.489  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-24 17:39:31.494  2157  2173 D BtGatt.GattService: stopScan() - queue size =1
,03-24 17:39:31.497  2157  2220 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 17:39:31.497  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 17:39:31.497  2157  2231 D BtGatt.ScanManager: stopping BLe Batch
03-24 17:39:31.498  2157  2172 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-24 17:39:31.499  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 17:39:31.499  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-24 17:39:31.499  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-24 17:39:31.499  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-24 17:39:31.499  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-24 17:39:31.499  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 17:39:31.499  3273  3273 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 17:39:31.500  3273  3273 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
03-24 17:39:31.500  2157  2220 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 17:39:31.500  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:39:31.500  2157  2231 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 17:39:31.500  3273  3273 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-24 17:39:31.505  2157  2220 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-24 17:39:31.505  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 17:39:31.505  2157  2220 D BtGatt.GattService: current time is 210933143875
03-24 17:39:31.505  2157  2220 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -62, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0, 115, 121, 123, -124, -123, 75, 1, -128, -77, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-24 17:39:31.505  2157  2220 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-24 17:39:31.506  2157  2220 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 17:39:31.507  3273  3332 I jxcore-log: ok 159 Should be able to call stopListeningForAdvertisments in teardown
03-24 17:39:31.507  3273  3332 I jxcore-log: 
,03-24 17:39:31.508  3273  3332 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-24 17:39:31.508  3273  3332 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
03-24 17:39:31.509  3273  3332 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-24 17:39:31.509  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-24 17:39:31.509  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-24 17:39:31.509  3273  3332 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-24 17:39:31.509  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-24 17:39:31.509  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-24 17:39:31.509  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 17:39:31.509  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 17:39:31.510  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-24 17:39:31.510  3273  3795 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-24 17:39:31.510  3273  3795 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-24 17:39:31.510  3273  3795 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-24 17:39:31.512  3273  3332 D BluetoothLeScanner: could not find callback wrapper
03-24 17:39:31.512  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 17:39:31.512  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,03-24 17:39:31.516  2157  2230 D BtGatt.AdvertiseManager: message : 1
,03-24 17:39:31.516  2157  2230 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-24 17:39:31.520  2157  2220 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 17:39:31.520  2157  2220 D BtGatt.GattService: Client app is not null!
,03-24 17:39:31.522  2157  2222 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-24 17:39:31.523  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 17:39:31.523  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,03-24 17:39:31.523  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,03-24 17:39:31.523  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-24 17:39:31.524  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-24 17:39:31.524  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 17:39:31.524  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 17:39:31.524  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-24 17:39:31.526  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,03-24 17:39:31.526  3273  3332 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-24 17:39:31.526  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 17:39:31.526  3273  3273 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 17:39:31.527  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 17:39:31.527  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-24 17:39:31.530  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-24 17:39:31.530  3273  3332 I jxcore-log: 
,03-24 17:39:31.538  3273  3273 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-24 17:39:31.539   823  1404 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 17:39:31.551  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-24 17:39:31.553  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 17:39:31.553  3273  3273 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 17:39:31.562  3273  3273 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-24 17:39:31.562  3273  3273 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-24 17:39:31.562  3273  3273 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 17:39:31.562  3273  3273 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 17:39:31.562  3273  3273 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-24 17:39:31.563  3273  3273 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 17:39:31.563  3273  3273 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-24 17:39:31.566  3273  3332 I jxcore-log: ok 160 Should be able to call stopAdvertisingAndListening in teardown
03-24 17:39:31.566  3273  3332 I jxcore-log: 
,03-24 17:39:31.594  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 17:39:31.594  3273  3332 I jxcore-log: 
,03-24 17:39:31.595  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 17:39:31.595  3273  3332 I jxcore-log: 
03-24 17:39:31.597  3273  3332 I jxcore-log: # setup
03-24 17:39:31.597  3273  3332 I jxcore-log: 
,03-24 17:39:31.810  3273  3332 I jxcore-log: # 38. Can connect to a remote peer
03-24 17:39:31.810  3273  3332 I jxcore-log: 
,03-24 17:39:31.987  3273  3332 I io.jxcore.node.ConnectionHelper: start: Port number: 33198, start advertisements: true
,03-24 17:39:31.988  3273  3332 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 17:39:31.988  3273  3332 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-24 17:39:31.988  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-24 17:39:31.996  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-24 17:39:31.996  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 17:39:31.997  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 17:39:31.997  3273  3332 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 17:39:32.006  2157  2222 D BtGatt.GattService: registerClient() - UUID=ceb17550-a31d-4990-ab58-49e4956c110d
,03-24 17:39:32.007  2157  2220 D BtGatt.GattService: onClientRegistered() - UUID=ceb17550-a31d-4990-ab58-49e4956c110d, clientIf=5
03-24 17:39:32.008  3273  3291 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-24 17:39:32.010  2157  2173 D BtGatt.GattService: start scan with filters
,03-24 17:39:32.015  2157  2231 D BtGatt.ScanManager: handling starting scan
03-24 17:39:32.016  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-24 17:39:32.016  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-24 17:39:32.016  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-24 17:39:32.016  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-24 17:39:32.016  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 17:39:32.017  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 17:39:32.017  3273  3273 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 17:39:32.017  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 17:39:32.017  3273  3332 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
,03-24 17:39:32.018  3273  3332 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 17:39:32.018  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-24 17:39:32.018  3273  3332 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-24 17:39:32.027  2157  2220 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,03-24 17:39:32.027  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 17:39:32.030  2157  2220 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15,
,03-24 17:39:32.030  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:39:32.031  2157  2231 D BtGatt.ScanManager: Starting BLE batch scan
03-24 17:39:32.031  2157  2231 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 17:39:32.034  2157  2220 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 17:39:32.034  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 17:39:32.035  2157  2222 D BtGatt.GattService: registerClient() - UUID=5523b23f-7153-498a-91ed-af649e0d74de
03-24 17:39:32.036  2157  2220 D BtGatt.GattService: onClientRegistered() - UUID=5523b23f-7153-498a-91ed-af649e0d74de, clientIf=6
03-24 17:39:32.037  2157  2220 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 17:39:32.037  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:39:32.037  3273  3292 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-24 17:39:32.041  2157  2230 D BtGatt.AdvertiseManager: message : 0
,03-24 17:39:32.047  2157  2230 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 17:39:32.051  2157  2220 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 17:39:32.055  2157  2220 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 17:39:32.056  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-24 17:39:32.056  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 17:39:32.057   823   839 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 17:39:32.060  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-24 17:39:32.061  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 17:39:32.061  3273  3332 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,03-24 17:39:32.061  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-24 17:39:32.062  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-24 17:39:32.063  3273  3332 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-24 17:39:32.063  3273  3332 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING,
03-24 17:39:32.063  3273  3332 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-24 17:39:32.064  3273  3273 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,03-24 17:39:32.064  3273  3332 I io.jxcore.node.ConnectionHelper: start: OK
03-24 17:39:32.064  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 17:39:32.065  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING,
03-24 17:39:32.065  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-24 17:39:32.065  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
,03-24 17:39:32.065  3273  3273 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-24 17:39:32.065  3273  3273 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 17:39:32.065  3273  3273 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-24 17:39:32.066  3273  3273 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-24 17:39:32.066  3273  3273 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 17:39:32.066   823  1404 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
03-24 17:39:32.066  3273  3273 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-24 17:39:32.066  3273  3273 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-24 17:39:32.067  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 17:39:32.067  3273  3332 I jxcore-log: 
03-24 17:39:32.068  3273  3797 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-24 17:39:32.070  3273  3332 I jxcore-log: ok 161 Can call startUpdateAdvertisingAndListening without error,
03-24 17:39:32.070  3273  3332 I jxcore-log: 
03-24 17:39:32.074  3273  3797 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-24 17:39:32.078  3273  3332 I io.jxcore.node.ConnectionHelper: start: Port number: 33198, start advertisements: false
,03-24 17:39:32.078  3273  3332 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 17:39:32.078  3273  3332 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should affect listening to advertisements only
03-24 17:39:32.078  3273  3332 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 17:39:32.078  3273  3332 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 17:39:32.081  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
,03-24 17:39:32.081  3273  3332 I jxcore-log: 
,03-24 17:39:32.083  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-24 17:39:32.083  3273  3332 I jxcore-log: 
,03-24 17:39:32.086  3273  3332 I jxcore-log: ok 162 Can call startListeningForAdvertisements without error
,03-24 17:39:32.086  3273  3332 I jxcore-log: 
,03-24 17:39:33.042  2157  2157 D BtGatt.ScanManager: awakened up at time 212469
,03-24 17:39:33.044  2157  2231 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 17:39:33.052  2157  2220 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,03-24 17:39:33.052  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:39:33.052  2157  2220 D BtGatt.GattService: current time is 212480521479
03-24 17:39:33.053  2157  2220 D BtGatt.GattService: Batch record : [81, -24, -24, -59, -40, 123, 1, -128, -79, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -60, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
,03-24 17:39:33.053  2157  2220 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 17:39:33.054  2157  2220 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-24 17:39:33.056  3273  3273 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> E0:DB:10:14:E2:C0], added - the peer count is 1
03-24 17:39:33.056  3273  3273 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 2
,03-24 17:39:33.057  3273  3273 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> E0:DB:10:14:E2:C0], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 
03-24 17:39:33.057  3273  3273 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
03-24 17:39:33.061  3273  3332 I jxcore-log: INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"E0:DB:10:14:E2:C0","peerAvailable":true,"pleaseConnect":false}]
03-24 17:39:33.061  3273  3332 I jxcore-log: 
,03-24 17:39:33.071  3273  3332 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID E0:DB:10:14:E2:C0
03-24 17:39:33.072  3273  3332 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> E0:DB:10:14:E2:C0]
,03-24 17:39:33.076  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address E0:DB:10:14:E2:C0
,03-24 17:39:33.077  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
03-24 17:39:33.077  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,03-24 17:39:33.078  3273  3332 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null E0:DB:10:14:E2:C0
03-24 17:39:33.078  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address E0:DB:10:14:E2:C0
03-24 17:39:33.078  3273  3332 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: E0:DB:10:14:E2:C0)
,03-24 17:39:33.079  3273  3798 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address E0:DB:10:14:E2:C0 (thread ID: 357)
03-24 17:39:33.079  3273  3798 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-24 17:39:33.081  2157  2173 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,03-24 17:39:33.083  3273  3332 I jxcore-log: INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"pleaseConnect":false}]
03-24 17:39:33.083  3273  3332 I jxcore-log: 
,03-24 17:39:35.680  2157  2233 W bt-btif : info:x10
,03-24 17:39:35.681  2157  2220 D         : remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
03-24 17:39:35.681  2157  2220 E BluetoothRemoteDevices: aclStateChangeCallback: Device is NULL
,03-24 17:39:35.873  2157  2233 E bt-btm  : tBTM_SEC_DEV:0xa2f3107c rs_disc_pending=0
,03-24 17:39:35.873  2157  2233 W bt-btif : bta_dm_check_av:0
03-24 17:39:35.874  2157  2220 W bt-btif : btif_dm_cback : unhandled event (14)
,03-24 17:39:37.260  1265  1265 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 17:39:37.333  1265  2584 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
03-24 17:39:37.334  1265  2584 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 17:39:37.334  1265  2584 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-24 17:39:37.334  1265  2584 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 17:39:37.346  1265  2584 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 17:39:37.388  3683  3683 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,03-24 17:39:37.390  3683  3683 D Finsky  : [1] 5.onFinished: Installation state replication failed.
,03-24 17:39:37.391  3683  3683 D Finsky  : [1] 5.onFinished: Scheduling replication attempt 2.
,03-24 17:39:38.057  2157  2157 D BtGatt.ScanManager: awakened up at time 217484
,03-24 17:39:38.059  2157  2231 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 17:39:38.064  2157  2220 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,03-24 17:39:38.064  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 17:39:38.065  2157  2220 D BtGatt.GattService: current time is 217492763144
,03-24 17:39:38.065  2157  2220 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -57, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0, 81, -24, -24, -59, -40, 123, 1, -128, -73, 5, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, 74, -104, -24, 8, -21, 105, 1, -128, -73, 3, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, 31, 118, -27, -117, -104, 125, 1, -128, -86, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, 15, 53, -107, -52, -71, 71, 1, -128, -85, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-24 17:39:38.066  2157  2220 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-24 17:39:38.067  2157  2220 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 17:39:38.067  2157  2220 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 17:39:38.068  2157  2220 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,03-24 17:39:38.069  2157  2220 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 17:39:38.072  3273  3273 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
,03-24 17:39:38.073  3273  3273 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> E0:DB:10:14:E2:C0] updated - the peer count is 2
03-24 17:39:38.074  3273  3273 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
03-24 17:39:38.075  3273  3273 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
03-24 17:39:38.075  3273  3273 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
,03-24 17:39:38.203  2157  2233 W bt-sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,03-24 17:39:38.203  2157  2233 E bt-btif : DISCOVERY_COMP_EVT slot id:10, failed to find channle,                                       status:1, scn:0
,03-24 17:39:38.204  2157  2343 W bt-btif : invalid rfc slot id: 10
,03-24 17:39:38.205  3273  3798 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 357)
03-24 17:39:38.205  3273  3798 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Maximum number of allowed retries (0) reached, giving up... (thread ID: 357)
03-24 17:39:38.205  3273  3798 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 357)
03-24 17:39:38.207  3273  3798 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: removeAndShutdownBluetoothClientThread: Thread ID: 357
03-24 17:39:38.207  3273  3273 W org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnectionFailed: Failed to connect to peer [<no peer name> E0:DB:10:14:E2:C0]: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
,03-24 17:39:38.207  3273  3798 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdownBluetoothClientThread: Thread ID: 357
03-24 17:39:38.207  3273  3273 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> E0:DB:10:14:E2:C0], error message: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
03-24 17:39:38.208  3273  3798 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 357)
03-24 17:39:38.208  3273  3273 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "E0:DB:10:14:E2:C0" removed
03-24 17:39:38.209  3273  3273 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
03-24 17:39:38.209  3273  3273 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,03-24 17:39:38.213  3273  3800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 357
03-24 17:39:38.214  3273  3800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 357)
03-24 17:39:38.214  3273  3800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 357)
03-24 17:39:38.214  3273  3332 I jxcore-log: INFO testThaliMobileNative: Connect returned an error: Connection to peer [<no peer name> E0:DB:10:14:E2:C0] failed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
03-24 17:39:38.214  3273  3332 I jxcore-log: 
03-24 17:39:38.217  3273  3332 I jxcore-log: INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
03-24 17:39:38.217  3273  3332 I jxcore-log: 
,03-24 17:39:38.683  2157  2218 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,03-24 17:39:40.198  2157  2233 E bt-btm  : btm_sec_disconnected - Clearing Pending flag
,03-24 17:39:40.198  2157  2220 E BluetoothRemoteDevices: aclStateChangeCallback: Device is NULL
,03-24 17:39:41.070  2157  2157 D BtGatt.ScanManager: awakened up at time 220497
,03-24 17:39:41.071  2157  2231 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5,
,03-24 17:39:41.082  2157  2220 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2,
03-24 17:39:41.083  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:39:41.083  2157  2220 D BtGatt.GattService: current time is 220511099705
,03-24 17:39:41.083  2157  2220 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -69, 32, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0, 15, 53, -107, -52, -71, 71, 1, -128, -86, 22, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-24 17:39:41.084  2157  2220 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
,03-24 17:39:41.085  2157  2220 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 17:39:41.088  3273  3273 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
03-24 17:39:41.088  3273  3273 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> E0:DB:10:14:E2:C0] updated - the peer count is 2
,03-24 17:39:41.230  3273  3332 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID E0:DB:10:14:E2:C0
,03-24 17:39:41.230  3273  3332 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> E0:DB:10:14:E2:C0]
,03-24 17:39:41.234  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address E0:DB:10:14:E2:C0
03-24 17:39:41.235  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port 1
03-24 17:39:41.235  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
03-24 17:39:41.235  3273  3332 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null E0:DB:10:14:E2:C0
03-24 17:39:41.236  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address E0:DB:10:14:E2:C0
03-24 17:39:41.236  3273  3332 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: E0:DB:10:14:E2:C0)
,03-24 17:39:41.239  3273  3802 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address E0:DB:10:14:E2:C0 (thread ID: 359)
03-24 17:39:41.240  3273  3802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: createBluetoothSocketToServiceRecord: Socket created with channel/port 1
,03-24 17:39:41.240  3273  3802 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-24 17:39:41.245  2157  2222 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,03-24 17:39:42.216  2157  2233 W bt-btif : info:x10
,03-24 17:39:42.216  2157  2220 D         : remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
03-24 17:39:42.216  2157  2220 E BluetoothRemoteDevices: aclStateChangeCallback: Device is NULL
,03-24 17:39:42.332  2157  2233 W bt-sdp  : process_service_search_attr_rsp
,03-24 17:39:42.584  2157  2220 D btif_config: btif_get_device_type: Device [e0:db:10:14:e2:c0] type 1
,03-24 17:39:42.593  2157  2220 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 1
,03-24 17:39:42.593  2157  2220 E bt-btif : check_cod: remote_cod = 0x5a020c
,03-24 17:39:42.600  2157  2221 I BluetoothBondStateMachine: Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 10 NewState: 11
,03-24 17:39:42.600  2157  2221 I BluetoothBondStateMachine: Entering PendingCommandState State
,03-24 17:39:42.651  2157  2220 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 0
,03-24 17:39:42.652  2157  2221 D BluetoothAdapterProperties: Failed to remove device: E0:DB:10:14:E2:C0
,03-24 17:39:42.675   823   857 I ActivityManager: Start proc 3803:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.BluetoothPairingRequest
,03-24 17:39:42.676  2157  2221 I BluetoothBondStateMachine: Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 11 NewState: 10
,03-24 17:39:42.699  2157  2221 I BluetoothBondStateMachine: StableState(): Entering Off State
,03-24 17:39:42.770   823   861 D BluetoothManagerService: Message: 20
03-24 17:39:42.771   823   861 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1708ace8:true
,03-24 17:39:42.773   823   838 I ActivityManager: Killing 3568:com.android.chrome/u0a40 (adj 15): empty #17
,03-24 17:39:42.799  2157  2233 W bt-btif : new conn_srvc id:26, app_id:1
,03-24 17:39:42.799  2157  2233 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:1
03-24 17:39:42.799  2157  2233 W bt-btif : bta_dm_pm_ssr:2, lat:1200
,03-24 17:39:42.800  3273  3802 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onSocketConnected: [<no peer name> E0:DB:10:14:E2:C0] (thread ID: 359)
03-24 17:39:42.800  3273  3802 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Socket connection succeeded (using port 1), total number of attempts: 1 (thread ID: 359)
03-24 17:39:42.802  3273  3802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesWritten: 15 bytes successfully written (thread ID: 360)
03-24 17:39:42.802  3273  3802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Outgoing connection initialized (*handshake* thread ID: 360)
03-24 17:39:42.802  3273  3802 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 359)
,03-24 17:39:42.805  3273  3822 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 360)
,03-24 17:39:42.819  3273  3822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesRead: Read 15 bytes successfully (thread ID: 360)
,03-24 17:39:42.820  3273  3822 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Handshake succeeded with [<no peer name> E0:DB:10:14:E2:C0]
03-24 17:39:42.820  3273  3822 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onHandshakeSucceeded: [<no peer name> E0:DB:10:14:E2:C0] (thread ID: 359)
03-24 17:39:42.820  3273  3822 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: handleSuccessfulClientThread: [<no peer name> E0:DB:10:14:E2:C0] (thread ID: 359)
,03-24 17:39:42.820  3273  3822 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 360)
03-24 17:39:42.821  3273  3273 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> E0:DB:10:14:E2:C0]
03-24 17:39:42.821  3273  3273 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing connection to peer [<no peer name> E0:DB:10:14:E2:C0]
03-24 17:39:42.821  3273  3273 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> E0:DB:10:14:E2:C0] updated - the peer count is 2
,03-24 17:39:42.824  3273  3273 I io.jxcore.node.ConnectionHelper: lowerBleDiscoveryPowerAndStartResetTimer: Lowering the power settings
,03-24 17:39:42.824  3273  3273 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 2 -> 0
03-24 17:39:42.825  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 17:39:42.825  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 17:39:42.825  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-24 17:39:42.825  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-24 17:39:42.825  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
,03-24 17:39:42.825  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-24 17:39:42.828  2157  2230 D BtGatt.AdvertiseManager: message : 1,
,03-24 17:39:42.829  2157  2230 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-24 17:39:42.832  2157  2220 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,03-24 17:39:42.832  2157  2220 D BtGatt.GattService: Client app is not null!
03-24 17:39:42.834  2157  2172 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-24 17:39:42.836  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-24 17:39:42.836  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-24 17:39:42.836  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 3, timeout: 0, is connectable: false
03-24 17:39:42.836  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 17:39:42.836  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 17:39:42.837  3273  3273 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 17:39:42.837  3273  3273 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 17:39:42.837  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 17:39:42.837  3273  3273 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-24 17:39:42.847  2157  2173 D BtGatt.GattService: registerClient() - UUID=f5721e99-3baa-47b1-9df0-60733de0a0bb
,03-24 17:39:42.847  2157  2220 D BtGatt.GattService: onClientRegistered() - UUID=f5721e99-3baa-47b1-9df0-60733de0a0bb, clientIf=6
03-24 17:39:42.848  3273  3292 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-24 17:39:42.850  2157  2230 D BtGatt.AdvertiseManager: message : 0,
,03-24 17:39:42.854  2157  2230 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 17:39:42.857  2157  2220 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 17:39:42.861  2157  2220 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 17:39:42.861  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-24 17:39:42.864  2157  2173 D BtGatt.GattService: stopScan() - queue size =1
,03-24 17:39:42.865  2157  2222 D BtGatt.GattService: unregisterClient() - clientIf=5
03-24 17:39:42.866  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 17:39:42.866  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-24 17:39:42.866  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 17:39:42.866  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 17:39:42.866  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 17:39:42.866  3273  3273 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 17:39:42.869  2157  2220 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 17:39:42.869  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:39:42.869  2157  2231 D BtGatt.ScanManager: stopping BLe Batch
,03-24 17:39:42.871  2157  2220 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,03-24 17:39:42.872  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:39:42.872  2157  2231 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 17:39:42.873  2157  2220 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 17:39:42.873  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 17:39:42.876  2157  2173 D BtGatt.GattService: registerClient() - UUID=b3c840f5-081b-4521-8260-541d05d10cf2
,03-24 17:39:42.877  2157  2220 D BtGatt.GattService: onClientRegistered() - UUID=b3c840f5-081b-4521-8260-541d05d10cf2, clientIf=5
,03-24 17:39:42.877  3273  3291 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-24 17:39:42.882  2157  2172 D BtGatt.GattService: start scan with filters,
,03-24 17:39:42.883  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 17:39:42.883  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 17:39:42.884  3273  3273 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 3 -> 1
03-24 17:39:42.884  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 17:39:42.884  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 17:39:42.884  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-24 17:39:42.884  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-24 17:39:42.884  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-24 17:39:42.884  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-24 17:39:42.887  2157  2231 D BtGatt.ScanManager: handling starting scan
,03-24 17:39:42.891  2157  2230 D BtGatt.AdvertiseManager: message : 1
,03-24 17:39:42.891  2157  2230 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-24 17:39:42.893  2157  2220 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,03-24 17:39:42.893  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:39:42.895  2157  2220 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 17:39:42.895  2157  2220 D BtGatt.GattService: Client app is not null!
,03-24 17:39:42.896  2157  2222 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-24 17:39:42.897  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-24 17:39:42.897  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-24 17:39:42.897  2157  2220 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 17:39:42.897  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-24 17:39:42.897  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 17:39:42.897  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:39:42.897  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 17:39:42.897  3273  3273 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 17:39:42.898  3273  3273 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-24 17:39:42.898  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-24 17:39:42.898  3273  3273 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-24 17:39:42.898  2157  2231 D BtGatt.ScanManager: Starting BLE batch scan
03-24 17:39:42.898  2157  2231 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 17:39:42.900  2157  2220 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 17:39:42.900  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 17:39:42.902  2157  2220 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,03-24 17:39:42.902  2157  2173 D BtGatt.GattService: registerClient() - UUID=c0b4dfc9-4f53-4f7a-89d6-73ae05683d51
03-24 17:39:42.903  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:39:42.903  2157  2220 D BtGatt.GattService: onClientRegistered() - UUID=c0b4dfc9-4f53-4f7a-89d6-73ae05683d51, clientIf=6
03-24 17:39:42.904  3273  3327 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-24 17:39:42.905  2157  2230 D BtGatt.AdvertiseManager: message : 0
,03-24 17:39:42.908  2157  2230 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 17:39:42.911  2157  2220 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 17:39:42.914  2157  2220 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 17:39:42.915  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-24 17:39:42.916  2157  2173 D BtGatt.GattService: stopScan() - queue size =1
,03-24 17:39:42.917  2157  2172 D BtGatt.GattService: unregisterClient() - clientIf=5
03-24 17:39:42.917  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-24 17:39:42.918  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-24 17:39:42.918  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 17:39:42.918  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 17:39:42.918  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 17:39:42.918  3273  3273 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 17:39:42.919  2157  2220 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,03-24 17:39:42.919  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:39:42.919  2157  2231 D BtGatt.ScanManager: stopping BLe Batch
,03-24 17:39:42.921  2157  2220 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 17:39:42.922  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 17:39:42.922  2157  2231 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 17:39:42.922  2157  2222 D BtGatt.GattService: registerClient() - UUID=1015d893-4f50-438c-9370-7a97b37431e5
03-24 17:39:42.922  2157  2220 D BtGatt.GattService: onClientRegistered() - UUID=1015d893-4f50-438c-9370-7a97b37431e5, clientIf=5
,03-24 17:39:42.923  3273  3327 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 17:39:42.923  2157  2220 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 17:39:42.923  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:39:42.923  2157  2173 D BtGatt.GattService: start scan with filters
03-24 17:39:42.924  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 17:39:42.924  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 17:39:42.924  3273  3273 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 2 -> 0
03-24 17:39:42.924  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 17:39:42.924  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 17:39:42.924  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
,03-24 17:39:42.924  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-24 17:39:42.924  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-24 17:39:42.924  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-24 17:39:42.926  2157  2230 D BtGatt.AdvertiseManager: message : 1
03-24 17:39:42.927  2157  2230 D BtGatt.AdvertiseManager: stop advertise for client 6
03-24 17:39:42.928  2157  2231 D BtGatt.ScanManager: handling starting scan
,03-24 17:39:42.931  2157  2220 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 17:39:42.931  2157  2220 D BtGatt.GattService: Client app is not null!
,03-24 17:39:42.932  2157  2173 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-24 17:39:42.933  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-24 17:39:42.933  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-24 17:39:42.933  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
,03-24 17:39:42.933  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 17:39:42.933  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,03-24 17:39:42.933  3273  3273 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61,
03-24 17:39:42.933  3273  3273 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 17:39:42.934  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false],
,03-24 17:39:42.934  3273  3273 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-24 17:39:42.934  2157  2220 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1,
03-24 17:39:42.934  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:39:42.936  2157  2220 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,03-24 17:39:42.936  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:39:42.936  2157  2231 D BtGatt.ScanManager: Starting BLE batch scan
03-24 17:39:42.937  2157  2231 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-24 17:39:42.938  2157  2220 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 17:39:42.938  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:39:42.939  2157  2172 D BtGatt.GattService: registerClient() - UUID=552c5da2-2947-4eef-9aee-d09451d3f999
03-24 17:39:42.939  2157  2220 D BtGatt.GattService: onClientRegistered() - UUID=552c5da2-2947-4eef-9aee-d09451d3f999, clientIf=6
,03-24 17:39:42.939  3273  3292 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-24 17:39:42.940  2157  2220 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 17:39:42.940  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 17:39:42.941  2157  2230 D BtGatt.AdvertiseManager: message : 0
03-24 17:39:42.945  2157  2230 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 17:39:42.948  2157  2220 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 17:39:42.950  2157  2220 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0,
03-24 17:39:42.951  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-24 17:39:42.952  2157  2172 D BtGatt.GattService: stopScan() - queue size =1
,03-24 17:39:42.953  2157  2173 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-24 17:39:42.954  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 17:39:42.954  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-24 17:39:42.954  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-24 17:39:42.954  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 17:39:42.954  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-24 17:39:42.954  3273  3273 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-24 17:39:42.955  2157  2220 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 17:39:42.955  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:39:42.957  2157  2231 D BtGatt.ScanManager: stopping BLe Batch
,03-24 17:39:42.958  2157  2172 D BtGatt.GattService: registerClient() - UUID=abf18d3a-390e-4850-bf2e-8fd1a2b5fa1b
03-24 17:39:42.959  2157  2220 D BtGatt.GattService: onClientRegistered() - UUID=abf18d3a-390e-4850-bf2e-8fd1a2b5fa1b, clientIf=5
03-24 17:39:42.959  2157  2220 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 17:39:42.959  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:39:42.959  3273  3291 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 17:39:42.959  2157  2222 D BtGatt.GattService: start scan with filters
03-24 17:39:42.959  2157  2231 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 17:39:42.960  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 17:39:42.960  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 17:39:42.960  3273  3273 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing socket thread, for peer [<no peer name> E0:DB:10:14:E2:C0], created successfully
03-24 17:39:42.961  2157  2220 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 17:39:42.961  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:39:42.961  3273  3273 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
03-24 17:39:42.961  3273  3273 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
03-24 17:39:42.961  3273  3273 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 1
03-24 17:39:42.961  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 17:39:42.961  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,03-24 17:39:42.961  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-24 17:39:42.961  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 17:39:42.961  3273  3824 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 361)
03-24 17:39:42.961  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,03-24 17:39:42.963  3273  3824 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 38267
03-24 17:39:42.963  3273  3824 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
03-24 17:39:42.963  3273  3824 I io.jxcore.node.ConnectionHelper: onListeningForIncomingConnections: Outgoing connection is using port 38267 (peer ID: E0:DB:10:14:E2:C0)
03-24 17:39:42.963  3273  3824 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "E0:DB:10:14:E2:C0" removed,
03-24 17:39:42.967  3273  3332 I jxcore-log: INFO testThaliMobileNative: 
03-24 17:39:42.967  3273  3332 I jxcore-log: 
03-24 17:39:42.968  2157  2231 D BtGatt.ScanManager: handling starting scan
03-24 17:39:42.968  3273  3332 I jxcore-log: ok 163 Must have listeningPort
03-24 17:39:42.968  3273  3332 I jxcore-log: 
03-24 17:39:42.969  3273  3332 I jxcore-log: ok 164 listeningPort must be a number,
03-24 17:39:42.969  3273  3332 I jxcore-log: 
,03-24 17:39:42.969  2157  2220 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 17:39:42.969  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 17:39:42.970  3273  3332 I jxcore-log: ok 165 Connection must have clientPort
03-24 17:39:42.970  3273  3332 I jxcore-log: 
03-24 17:39:42.971  2157  2220 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 17:39:42.971  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:39:42.971  2157  2231 D BtGatt.ScanManager: Starting BLE batch scan,
03-24 17:39:42.971  2157  2231 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 17:39:42.971  3273  3332 I jxcore-log: ok 166 clientPort must be a number
03-24 17:39:42.971  3273  3332 I jxcore-log: 
03-24 17:39:42.973  2157  2220 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,03-24 17:39:42.973  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 17:39:42.973  3273  3332 I jxcore-log: ok 167 Connection must have serverPort,
03-24 17:39:42.973  3273  3332 I jxcore-log: 
03-24 17:39:42.974  2157  2220 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 17:39:42.974  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:39:42.974  3273  3332 I jxcore-log: ok 168 serverPort must be a number,
03-24 17:39:42.974  3273  3332 I jxcore-log: 
03-24 17:39:42.976  3273  3332 I jxcore-log: ok 169 forward connection must have clientPort == 0
03-24 17:39:42.976  3273  3332 I jxcore-log: 
03-24 17:39:42.976  3273  3332 I jxcore-log: ok 170 forward connection must have serverPort == 0
,03-24 17:39:42.976  3273  3332 I jxcore-log: 
,03-24 17:39:42.986  3273  3332 I jxcore-log: # teardown,
03-24 17:39:42.986  3273  3332 I jxcore-log: 
,03-24 17:39:43.866  2157  2233 W bt-btif : info:x10,
,03-24 17:39:43.866  2157  2220 D         : remote version info [f8:95:c7:87:3c:51]: 0, 0, 0
,03-24 17:39:43.867  2157  2220 E BluetoothRemoteDevices: aclStateChangeCallback: Device is NULL
,03-24 17:39:44.327  2157  2233 E bt-btm  : tBTM_SEC_DEV:0xa2f30eb4 rs_disc_pending=1
,03-24 17:39:44.327  2157  2233 W bt-btif : bta_dm_check_av:0
03-24 17:39:44.327  2157  2220 W bt-btif : btif_dm_cback : unhandled event (14)
,03-24 17:39:44.651  1248  1470 I Keyboard.Facilitator.LanguageModelFlusher: run()
03-24 17:39:44.651  1248  1470 I Keyboard.Facilitator: flushDynamicLanguageModels()
,03-24 17:39:44.680  1265  1265 I ConfigService: onCreate
,03-24 17:39:44.866  2157  2233 E bt-btm  : tBTM_SEC_DEV:0xa2f3107c rs_disc_pending=0
03-24 17:39:44.866  2157  2233 W bt-btif : bta_dm_check_av:0
03-24 17:39:44.866  2157  2220 W bt-btif : btif_dm_cback : unhandled event (14)
,03-24 17:39:45.733  2157  2220 D btif_config: btif_get_device_type: Device [f8:95:c7:87:3c:51] type 1,
,03-24 17:39:45.741  2157  2220 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
,03-24 17:39:45.742  2157  2220 E bt-btif : check_cod: remote_cod = 0x5a020c,
03-24 17:39:45.745  2157  2221 I BluetoothBondStateMachine: Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11,
03-24 17:39:45.745  2157  2221 I BluetoothBondStateMachine: Entering PendingCommandState State
,03-24 17:39:45.831  2157  2220 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
03-24 17:39:45.832  2157  2221 D BluetoothAdapterProperties: Failed to remove device: F8:95:C7:87:3C:51
,03-24 17:39:45.835  2157  2221 I BluetoothBondStateMachine: Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,03-24 17:39:45.848  2157  2221 I BluetoothBondStateMachine: StableState(): Entering Off State
,03-24 17:39:45.908  2157  2233 W bt-btif : new conn_srvc id:26, app_id:255
,03-24 17:39:45.908  2157  2233 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:255
03-24 17:39:45.908  2157  2233 W bt-btif : bta_dm_pm_ssr:2, lat:1200
03-24 17:39:45.910  3273  3797 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection accepted
,03-24 17:39:45.911  3273  3797 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection initialized (thread ID: 362)
03-24 17:39:45.912  3273  3797 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-24 17:39:45.913   823   839 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 17:39:45.914  3273  3827 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 362)
03-24 17:39:45.916  3273  3797 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-24 17:39:45.922  3273  3797 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-24 17:39:46.087  2157  2233 E bt-btm  : tBTM_SEC_DEV:0xa2f3107c rs_disc_pending=1
03-24 17:39:46.087  2157  2233 W bt-btif : bta_dm_check_av:0
,03-24 17:39:46.087  2157  2220 W bt-btif : btif_dm_cback : unhandled event (14)
,03-24 17:39:46.116  3273  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesRead: Read 15 bytes successfully (thread ID: 362)
,03-24 17:39:46.120  3273  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Got valid identity from [<no peer name> F8:95:C7:87:3C:51]
,03-24 17:39:46.121  3273  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesWritten: 15 bytes successfully written (thread ID: 362)
,03-24 17:39:46.121  3273  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: removeThreadFromList: Removing thread with ID 362
03-24 17:39:46.121  3273  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Handshake thread disposed (thread ID: 362)
03-24 17:39:46.121  3273  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onIncomingConnectionConnected: [<no peer name> F8:95:C7:87:3C:51]
03-24 17:39:46.122  3273  3827 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 362)
,03-24 17:39:46.123  3273  3273 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> F8:95:C7:87:3C:51]
03-24 17:39:46.125  3273  3273 I io.jxcore.node.ConnectionHelper: onConnected: Incoming connection to peer [<no peer name> F8:95:C7:87:3C:51]
03-24 17:39:46.125  3273  3273 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
,03-24 17:39:46.129  3273  3273 I io.jxcore.node.ConnectionHelper: onConnected: Incoming socket thread, for peer [<no peer name> F8:95:C7:87:3C:51], created successfully
03-24 17:39:46.129  3273  3273 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 2
,03-24 17:39:46.133  3273  3828 D io.jxcore.node.IncomingSocketThread: Entering thread (ID: 363)
,03-24 17:39:46.139  3273  3828 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 33198
,03-24 17:39:46.140  3273  3828 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,03-24 17:39:46.141  3273  3828 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
,03-24 17:39:46.142  3273  3828 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-24 17:39:46.144  3273  3830 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 364, name: Sender)
03-24 17:39:46.144  3273  3828 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 363)
03-24 17:39:46.144  3273  3828 D io.jxcore.node.IncomingSocketThread: Exiting thread (ID: 363)
,03-24 17:39:46.148  3273  3831 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 365, name: Receiver)
,03-24 17:39:47.405  2157  2233 E bt-btm  : tBTM_SEC_DEV:0xa2f3107c rs_disc_pending=0
03-24 17:39:47.405  2157  2233 W bt-btif : bta_dm_check_av:0
,03-24 17:39:47.405  2157  2220 W bt-btif : btif_dm_cback : unhandled event (14)
,03-24 17:39:47.487  2157  2343 W bt-btif : invalid rfc slot id: 9
,03-24 17:39:47.487  3273  3831 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 365, thread name: Receiver): bt socket closed, read return: -1
,03-24 17:39:47.488  3273  3831 E io.jxcore.node.IncomingSocketThread: The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
03-24 17:39:47.488  3273  3831 W io.jxcore.node.ConnectionHelper: onDisconnected: Incoming connection, peer [<no peer name> F8:95:C7:87:3C:51] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
03-24 17:39:47.488  3273  3831 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 363
03-24 17:39:47.488  3273  3831 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 363)
03-24 17:39:47.488  3273  3831 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
,03-24 17:39:47.489  3273  3831 D io.jxcore.node.IncomingSocketThread: close: Stopping receiving thread...
,03-24 17:39:47.489  3273  3831 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 365
,03-24 17:39:47.489  3273  3831 D io.jxcore.node.IncomingSocketThread: close: Stopping sending thread...
03-24 17:39:47.489  3273  3831 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 364
03-24 17:39:47.489  3273  3831 D io.jxcore.node.IncomingSocketThread: closeLocalSocketAndStreams: Closing... (thread ID: 363),
03-24 17:39:47.490  3273  3831 I io.jxcore.node.IncomingSocketThread: close: Complete (thread ID: 363)
03-24 17:39:47.490  3273  3830 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 364, thread name: Sender): Socket closed
03-24 17:39:47.490  3273  3831 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
03-24 17:39:47.490  3273  3830 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 364, name: Sender)
03-24 17:39:47.491  3273  3831 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 365, name: Receiver)
,03-24 17:39:47.518  3273  3332 I jxcore-log: INFO thaliMobileNativeWrapper: incomingConnectionToPortNumberFailed: %s,
03-24 17:39:47.518  3273  3332 I jxcore-log: 
,03-24 17:39:47.520  3273  3332 I jxcore-log: INFO thaliMobileNativeWrapper: got incomingConnectionToPortNumberFailed while not in start
03-24 17:39:47.520  3273  3332 I jxcore-log: 
,03-24 17:39:47.705  2157  2233 W bt-rfcomm: rfc_find_lcid_mcb LCID reused LCID:0x44 current:0x0
,03-24 17:39:47.705  2157  2233 W bt-rfcomm: RFCOMM_DisconnectInd LCID:0x44
,03-24 17:39:47.813  2157  2233 W bt-btif : dm_pm_timer expires
03-24 17:39:47.814  2157  2233 W bt-btif : dm_pm_timer expires 0
03-24 17:39:47.814  2157  2233 W bt-btif : proc dm_pm_timer expires
,03-24 17:39:47.927  2157  2233 E bt-btm  : tBTM_SEC_DEV:0xa2f30eb4 rs_disc_pending=0
,03-24 17:39:47.927  2157  2233 W bt-btif : bta_dm_check_av:0
03-24 17:39:47.927  2157  2220 W bt-btif : btif_dm_cback : unhandled event (14)
,03-24 17:39:47.977  2157  2157 D BtGatt.ScanManager: awakened up at time 227405
,03-24 17:39:47.980  2157  2231 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 17:39:47.984  2157  2220 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,03-24 17:39:47.984  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:39:47.985  2157  2220 D BtGatt.GattService: current time is 227412658036
03-24 17:39:47.985  2157  2220 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -72, 53, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0, 15, 53, -107, -52, -71, 71, 1, -128, -92, 53, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-24 17:39:47.986  2157  2220 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-24 17:39:47.986  2157  2220 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 17:39:47.989  3273  3273 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
,03-24 17:39:47.990  3273  3273 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> E0:DB:10:14:E2:C0] updated - the peer count is 2
,03-24 17:39:48.396  2157  2233 E bt-btm  : tBTM_SEC_DEV:0xa2f3107c rs_disc_pending=1
,03-24 17:39:48.396  2157  2233 W bt-btif : bta_dm_check_av:0
03-24 17:39:48.396  2157  2220 W bt-btif : btif_dm_cback : unhandled event (14)
,03-24 17:39:48.891  3452  3833 V KeepSync: Connecting to GoogleApiClient
,03-24 17:39:48.994  1265  1282 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-24 17:39:48.994  1265  1282 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 17:39:48.994  1265  1282 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-24 17:39:48.994  1265  1282 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 17:39:49.012  1265  1282 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 17:39:49.045  3093  3834 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
03-24 17:39:49.045  3093  3834 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-24 17:39:49.045  3093  3834 E HttpOperation: 	at jdm.a(PG:82)
03-24 17:39:49.045  3093  3834 E HttpOperation: 	at jcs.o(PG:406)
03-24 17:39:49.045  3093  3834 E HttpOperation: 	at jcn.a(PG:1379)
03-24 17:39:49.045  3093  3834 E HttpOperation: 	at jcs.i(PG:143)
03-24 17:39:49.045  3093  3834 E HttpOperation: 	at blb.a(PG:3937)
03-24 17:39:49.045  3093  3834 E HttpOperation: 	at czp.a(PG:18188)
03-24 17:39:49.045  3093  3834 E HttpOperation: 	at czp.a(PG:9081)
03-24 17:39:49.045  3093  3834 E HttpOperation: 	at czq.run(PG:1686)
03-24 17:39:49.045  3093  3834 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-24 17:39:49.045  3093  3834 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 17:39:49.045  3093  3834 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 17:39:49.045  3093  3834 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 17:39:49.045  3093  3834 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-24 17:39:49.045  3093  3834 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-24 17:39:49.045  3093  3834 E HttpOperation: 	at jdj.a(PG:4091)
03-24 17:39:49.045  3093  3834 E HttpOperation: 	at jdj.a(PG:1125)
03-24 17:39:49.045  3093  3834 E HttpOperation: 	at jdm.a(PG:77)
03-24 17:39:49.045  3093  3834 E HttpOperation: 	... 12 more
03-24 17:39:49.045  3093  3834 E HttpOperation: Caused by: faj: BadAuthentication
03-24 17:39:49.045  3093  3834 E HttpOperation: 	at fal.a(PG:38)
03-24 17:39:49.045  3093  3834 E HttpOperation: 	at jdj.a(PG:4089)
03-24 17:39:49.045  3093  3834 E HttpOperation: 	... 14 more
,03-24 17:39:49.050  1265  2585 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
03-24 17:39:49.050  1265  2585 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 17:39:49.050  1265  2585 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 17:39:49.051  1265  2585 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 17:39:49.059  1265  2585 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 17:39:49.093  1814  3836 E ClientConnectionOperation: Handling authorization failure
03-24 17:39:49.093  1814  3836 E ClientConnectionOperation: com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
03-24 17:39:49.093  1814  3836 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
03-24 17:39:49.093  1814  3836 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
03-24 17:39:49.093  1814  3836 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
03-24 17:39:49.093  1814  3836 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
03-24 17:39:49.093  1814  3836 E ClientConnectionOperation: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-24 17:39:49.093  1814  3836 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 17:39:49.093  1814  3836 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 17:39:49.093  1814  3836 E ClientConnectionOperation: 	at java.lang.Thread.run(Thread.java:818)
03-24 17:39:49.093  1814  3836 E ClientConnectionOperation: Caused by: com.google.android.gms.auth.ad: BadAuthentication
03-24 17:39:49.093  1814  3836 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.b(SourceFile:442)
03-24 17:39:49.093  1814  3836 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:365)
03-24 17:39:49.093  1814  3836 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:310)
03-24 17:39:49.093  1814  3836 E ClientConnectionOperation: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
03-24 17:39:49.093  1814  3836 E ClientConnectionOperation: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
03-24 17:39:49.093  1814  3836 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:30)
03-24 17:39:49.093  1814  3836 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:370)
03-24 17:39:49.093  1814  3836 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:340)
03-24 17:39:49.093  1814  3836 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:319)
03-24 17:39:49.093  1814  3836 E ClientConnectionOperation: 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
03-24 17:39:49.093  1814  3836 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
03-24 17:39:49.093  1814  3836 E ClientConnectionOperation: 	... 7 more
,03-24 17:39:49.097  3452  3833 V KeepSync: GoogleApiClient failed to connect with error code: 4
,03-24 17:39:49.105  3452  3833 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-24 17:39:49.108  1265  2584 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-24 17:39:49.109  1265  2584 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-24 17:39:49.109  1265  2584 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 17:39:49.109  1265  2584 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 17:39:49.115  1265  2584 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 17:39:49.117  3452  3833 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-24 17:39:49.120  3452  3833 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-24 17:39:49.131  3093  3834 E HttpOperation: [getmobileexperiments] Unexpected exception
03-24 17:39:49.131  3093  3834 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-24 17:39:49.131  3093  3834 E HttpOperation: 	at jdm.a(PG:82)
03-24 17:39:49.131  3093  3834 E HttpOperation: 	at jcs.o(PG:406)
03-24 17:39:49.131  3093  3834 E HttpOperation: 	at jcn.a(PG:1379)
03-24 17:39:49.131  3093  3834 E HttpOperation: 	at jcs.i(PG:143)
03-24 17:39:49.131  3093  3834 E HttpOperation: 	at hec.a(PG:42)
03-24 17:39:49.131  3093  3834 E HttpOperation: 	at hee.a(PG:102)
03-24 17:39:49.131  3093  3834 E HttpOperation: 	at czr.a(PG:65)
03-24 17:39:49.131  3093  3834 E HttpOperation: 	at kka.a(PG:108)
03-24 17:39:49.131  3093  3834 E HttpOperation: 	at czp.a(PG:19176)
03-24 17:39:49.131  3093  3834 E HttpOperation: 	at czp.a(PG:9081)
03-24 17:39:49.131  3093  3834 E HttpOperation: 	at czq.run(PG:1686)
03-24 17:39:49.131  3093  3834 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-24 17:39:49.131  3093  3834 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 17:39:49.131  3093  3834 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 17:39:49.131  3093  3834 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 17:39:49.131  3093  3834 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-24 17:39:49.131  3093  3834 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-24 17:39:49.131  3093  3834 E HttpOperation: 	at jdj.a(PG:4091)
03-24 17:39:49.131  3093  3834 E HttpOperation: 	at jdj.a(PG:1125)
03-24 17:39:49.131  3093  3834 E HttpOperation: 	at jdm.a(PG:77)
03-24 17:39:49.131  3093  3834 E HttpOperation: 	... 15 more
03-24 17:39:49.131  3093  3834 E HttpOperation: Caused by: faj: BadAuthentication
03-24 17:39:49.131  3093  3834 E HttpOperation: 	at fal.a(PG:38)
03-24 17:39:49.131  3093  3834 E HttpOperation: 	at jdj.a(PG:4089)
03-24 17:39:49.131  3093  3834 E HttpOperation: 	... 17 more
03-24 17:39:49.132  3093  3834 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
03-24 17:39:49.132  3093  3834 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
03-24 17:39:49.132  3093  3834 E ExperimentLoader: 	at jdm.a(PG:82)
03-24 17:39:49.132  3093  3834 E ExperimentLoader: 	at jcs.o(PG:406)
03-24 17:39:49.132  3093  3834 E ExperimentLoader: 	at jcn.a(PG:1379)
03-24 17:39:49.132  3093  3834 E ExperimentLoader: 	at jcs.i(PG:143)
03-24 17:39:49.132  3093  3834 E ExperimentLoader: 	at hec.a(PG:42)
03-24 17:39:49.132  3093  3834 E ExperimentLoader: 	at hee.a(PG:102)
03-24 17:39:49.132  3093  3834 E ExperimentLoader: 	at czr.a(PG:65)
03-24 17:39:49.132  3093  3834 E ExperimentLoader: 	at kka.a(PG:108)
03-24 17:39:49.132  3093  3834 E ExperimentLoader: 	at czp.a(PG:19176)
03-24 17:39:49.132  3093  3834 E ExperimentLoader: 	at czp.a(PG:9081)
03-24 17:39:49.132  3093  3834 E ExperimentLoader: 	at czq.run(PG:1686)
03-24 17:39:49.132  3093  3834 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-24 17:39:49.132  3093  3834 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 17:39:49.132  3093  3834 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 17:39:49.132  3093  3834 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 17:39:49.132  3093  3834 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
03-24 17:39:49.132  3093  3834 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-24 17:39:49.132  3093  3834 E ExperimentLoader: 	at jdj.a(PG:4091)
03-24 17:39:49.132  3093  3834 E ExperimentLoader: 	at jdj.a(PG:1,125)
03-24 17:39:49.132  3093  3834 E ExperimentLoader: 	at jdm.a(PG:77)
03-24 17:39:49.132  3093  3834 E ExperimentLoader: 	... 15 more
03-24 17:39:49.132  3093  3834 E ExperimentLoader: Caused by: faj: BadAuthentication
03-24 17:39:49.132  3093  3834 E ExperimentLoader: 	at fal.a(PG:38)
03-24 17:39:49.132  3093  3834 E ExperimentLoader: 	at jdj.a(PG:4089)
03-24 17:39:49.132  3093  3834 E ExperimentLoader: 	... 17 more
,03-24 17:39:49.197  1265  1728 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
03-24 17:39:49.197  1265  1728 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 17:39:49.197  1265  1728 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 17:39:49.197  1265  1728 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 17:39:49.203  1265  1728 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,03-24 17:39:49.257  3452  3833 E KeepSync: IOException
03-24 17:39:49.257  3452  3833 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
03-24 17:39:49.257  3452  3833 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
03-24 17:39:49.257  3452  3833 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
03-24 17:39:49.257  3452  3833 E KeepSync: 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
03-24 17:39:49.257  3452  3833 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
03-24 17:39:49.257  3452  3833 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
03-24 17:39:49.257  3452  3833 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
03-24 17:39:49.257  3452  3833 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
03-24 17:39:49.257  3452  3833 E KeepSync: 	at com.google.android.keep.util.m.a(SourceFile:207)
03-24 17:39:49.257  3452  3833 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
03-24 17:39:49.257  3452  3833 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
03-24 17:39:49.257  3452  3833 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
03-24 17:39:49.257  3452  3833 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
03-24 17:39:49.257  3452  3833 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
03-24 17:39:49.257  3452  3833 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
03-24 17:39:49.257  3452  3833 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
03-24 17:39:49.257  3452  3833 E KeepSync: 	... 10 more
03-24 17:39:49.257  3452  3833 W KeepSync: Sync result 2
,03-24 17:39:49.263   823   856 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 201302, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-24 17:39:49.303   823   856 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 201678, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-24 17:39:49.313  3473  3839 I BooksSync: Starting books sync for 61035162, extras: ade
,03-24 17:39:49.330  3473  3840 I BooksConfig: GmsCore Version = 7.8.99 (2134222-430)
,03-24 17:39:49.372  1265  1282 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,03-24 17:39:49.373  1265  1282 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-24 17:39:49.373  1265  1282 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-24 17:39:49.373  1265  1282 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 17:39:49.383  1265  1282 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 17:39:49.501  1265  2585 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,03-24 17:39:49.502  1265  2585 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 17:39:49.502  1265  2585 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 17:39:49.503  1265  2585 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 17:39:49.511  1265  2585 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 17:39:49.614  1265  2585 I art     : Explicit concurrent mark sweep GC freed 39644(2MB) AllocSpace objects, 14(1543KB) LOS objects, 37% free, 26MB/42MB, paused 1.573ms total 69.441ms
,03-24 17:39:49.618  3473  3840 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,03-24 17:39:49.620  3473  3839 E BooksSync: Soft error
03-24 17:39:49.620  3473  3839 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-24 17:39:49.620  3473  3839 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,03-24 17:39:49.621  3473  3839 E BooksSync: Sync error
03-24 17:39:49.621  3473  3839 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-24 17:39:49.621  3473  3839 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,03-24 17:39:49.621  3473  3839 I BooksSync: Finished books sync
,03-24 17:39:49.630   823   856 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 202855, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1],
,03-24 17:39:49.775  1265  1265 I ConfigService: onDestroy
,03-24 17:39:51.218  2157  2218 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,03-24 17:39:51.699  2157  2233 E bt-btm  : btm_sec_disconnected - Clearing Pending flag
,03-24 17:39:51.706  2157  2157 D BluetoothMapService: onReceive
,03-24 17:39:51.735   823   861 D BluetoothManagerService: Message: 20,
03-24 17:39:51.736   823   861 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@220c8a3e:true
,03-24 17:39:51.765  1538  1538 I BTConnectionReceiver: onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,03-24 17:39:51.774  1538  1538 I BluetoothClassifier: Bluetooth Device Name: G4-1
,03-24 17:39:52.632  2157  2157 D BtGatt.ScanManager: awakened up at time 232060
,03-24 17:39:52.637  2157  2231 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 17:39:52.645  2157  2220 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
03-24 17:39:52.645  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:39:52.646  2157  2220 D BtGatt.GattService: current time is 232073740950
,03-24 17:39:52.646  2157  2220 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -69, 10, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-24 17:39:52.646  2157  2220 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-24 17:39:52.649  3273  3273 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> E0:DB:10:14:E2:C0] updated - the peer count is 2
,03-24 17:39:53.664  2157  2157 D BtGatt.ScanManager: awakened up at time 233091
03-24 17:39:53.665  2157  2231 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 17:39:53.673  2157  2220 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,03-24 17:39:53.674  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
03-24 17:39:53.674  2157  2220 D BtGatt.GattService: current time is 233101941158
03-24 17:39:53.674  2157  2220 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -78, 11, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-24 17:39:53.675  2157  2220 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
,03-24 17:39:53.676  3273  3273 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> E0:DB:10:14:E2:C0] updated - the peer count is 2
,03-24 17:39:54.502  3273  3332 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 17:39:54.503  3273  3332 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
,03-24 17:39:54.503  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
03-24 17:39:54.503  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-24 17:39:54.505  2157  2222 D BtGatt.GattService: stopScan() - queue size =1
03-24 17:39:54.507  2157  2222 D BtGatt.GattService: unregisterClient() - clientIf=5
03-24 17:39:54.508  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 17:39:54.508  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 17:39:54.508  2157  2220 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,03-24 17:39:54.509  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:39:54.509  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-24 17:39:54.509  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-24 17:39:54.509  2157  2231 D BtGatt.ScanManager: stopping BLe Batch
03-24 17:39:54.509  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-24 17:39:54.509  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 17:39:54.510  3273  3273 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 17:39:54.510  3273  3273 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
,03-24 17:39:54.511  3273  3273 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 17:39:54.511  2157  2220 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 17:39:54.511  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 17:39:54.512  2157  2231 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 17:39:54.513  2157  2220 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 17:39:54.514  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:39:54.514  3273  3332 I jxcore-log: ok 171 Should be able to call stopListeningForAdvertisments in teardown
03-24 17:39:54.514  3273  3332 I jxcore-log: 
03-24 17:39:54.515  3273  3332 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-24 17:39:54.515  3273  3332 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> E0:DB:10:14:E2:C0]
03-24 17:39:54.515  3273  3332 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 361)
03-24 17:39:54.515  3273  3332 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 361)
03-24 17:39:54.515  3273  3332 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
03-24 17:39:54.515  3273  3332 D io.jxcore.node.OutgoingSocketThread: closeLocalSocketAndStreams: Nothing to close (thread ID: 361)
03-24 17:39:54.515  3273  3332 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 361)
03-24 17:39:54.516  3273  3824 D io.jxcore.node.OutgoingSocketThread: Exiting thread (ID: 361)
,03-24 17:39:54.517  3273  3332 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
03-24 17:39:54.517  3273  3332 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-24 17:39:54.517  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-24 17:39:54.517  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-24 17:39:54.518  3273  3332 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-24 17:39:54.518  3273  3797 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-24 17:39:54.518  3273  3797 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-24 17:39:54.518  3273  3797 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-24 17:39:54.518  3273  3273 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-24 17:39:54.519  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-24 17:39:54.519  3273  3273 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-24 17:39:54.520  3273  3273 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-24 17:39:54.520  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-24 17:39:54.520  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 17:39:54.520  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,03-24 17:39:54.520  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-24 17:39:54.523  3273  3332 D BluetoothLeScanner: could not find callback wrapper
03-24 17:39:54.524  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 17:39:54.524  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,03-24 17:39:54.526  2157  2230 D BtGatt.AdvertiseManager: message : 1
03-24 17:39:54.527  2157  2230 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-24 17:39:54.530  2157  2220 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,03-24 17:39:54.530  2157  2220 D BtGatt.GattService: Client app is not null!
03-24 17:39:54.531  2157  2173 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-24 17:39:54.533  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
03-24 17:39:54.533  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-24 17:39:54.534  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-24 17:39:54.534  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,03-24 17:39:54.534  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,03-24 17:39:54.534  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 17:39:54.534  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 17:39:54.534  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-24 17:39:54.535  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,03-24 17:39:54.535  3273  3332 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-24 17:39:54.535  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 17:39:54.535  3273  3273 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 17:39:54.535  3273  3273 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 17:39:54.536  3273  3273 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 17:39:54.536  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 17:39:54.536  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-24 17:39:54.539  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true},
03-24 17:39:54.539  3273  3332 I jxcore-log: 
,03-24 17:39:54.542  3273  3332 I jxcore-log: ok 172 Should be able to call stopAdvertisingAndListening in teardown
03-24 17:39:54.542  3273  3332 I jxcore-log: 
03-24 17:39:54.543  3273  3273 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-24 17:39:54.544   823  1151 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 17:39:54.550  3273  3332 I jxcore-log: # setup
,03-24 17:39:54.550  3273  3332 I jxcore-log: 
,03-24 17:39:54.555  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
,03-24 17:39:54.556  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-24 17:39:54.556  3273  3273 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
,03-24 17:39:54.563  3273  3273 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-24 17:39:54.563  3273  3273 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-24 17:39:54.564  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 17:39:54.564  3273  3332 I jxcore-log: 
,03-24 17:39:54.566  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 17:39:54.566  3273  3332 I jxcore-log: 
,03-24 17:39:55.214  2157  2233 W bt-btif : bta_jv_rfc_port_to_cb(port_handle:0xd):jv handle:0x0 not FOUND
,03-24 17:39:57.683  1265  1265 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 17:39:57.756  1265  1603 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
03-24 17:39:57.756  1265  1603 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 17:39:57.756  1265  1603 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-24 17:39:57.756  1265  1603 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 17:39:57.764  1265  1603 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 17:39:57.789  3683  3683 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,03-24 17:39:57.790  3683  3683 D Finsky  : [1] 5.onFinished: Installation state replication failed.
03-24 17:39:57.791  3683  3683 D Finsky  : [1] 5.onFinished: Scheduling replication attempt 3.
,03-24 17:39:58.504  3273  3332 I jxcore-log: # 39. Can shift large amounts of data
03-24 17:39:58.504  3273  3332 I jxcore-log: 
,03-24 17:39:59.074  2157  2233 E bt-btm  : btm_sec_disconnected - Clearing Pending flag
,03-24 17:39:59.081  2157  2157 D BluetoothMapService: onReceive
,03-24 17:39:59.112  1538  1538 I BTConnectionReceiver: onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,03-24 17:39:59.117  1538  1538 I BluetoothClassifier: Bluetooth Device Name: Note4-1
,03-24 17:40:01.132  3273  3273 I io.jxcore.node.ConnectionHelper: restoreDefaultBleDiscoverySettings: Powering the BLE discovery back up
03-24 17:40:01.133  3273  3273 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 0 -> 2
03-24 17:40:01.133  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 17:40:01.133  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 17:40:01.133  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-24 17:40:01.133  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-24 17:40:01.133  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-24 17:40:01.133  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-24 17:40:01.133  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 1, timeout: 0, is connectable: false
03-24 17:40:01.133  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-24 17:40:01.134  3273  3273 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 1 -> 3
03-24 17:40:01.134  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 17:40:01.134  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 17:40:01.134  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-24 17:40:01.134  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-24 17:40:01.134  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-24 17:40:01.134  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-24 17:40:01.134  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-24 17:40:01.134  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-24 17:40:01.134  3273  3273 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 0 -> 2
03-24 17:40:01.135  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 17:40:01.135  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 17:40:01.135  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-24 17:40:01.135  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-24 17:40:01.135  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-24 17:40:01.135  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-24 17:40:01.135  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-24 17:40:01.135  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanS,ettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-24 17:40:19.992  3273  3332 I io.jxcore.node.ConnectionHelper: start: Port number: 57571, start advertisements: true
03-24 17:40:19.992  3273  3332 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 17:40:19.993  3273  3332 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-24 17:40:19.993  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-24 17:40:19.997  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
03-24 17:40:19.997  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-24 17:40:19.997  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 17:40:19.997  3273  3332 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 17:40:20.003  2157  2172 D BtGatt.GattService: registerClient() - UUID=210f067d-a86e-47e5-8485-cee515cc7ed8
,03-24 17:40:20.004  2157  2220 D BtGatt.GattService: onClientRegistered() - UUID=210f067d-a86e-47e5-8485-cee515cc7ed8, clientIf=5
,03-24 17:40:20.005  3273  3291 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-24 17:40:20.005  2157  2173 D BtGatt.GattService: start scan with filters
,03-24 17:40:20.007  2157  2231 D BtGatt.ScanManager: handling starting scan,
,03-24 17:40:20.008  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-24 17:40:20.008  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-24 17:40:20.009  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING],
03-24 17:40:20.009  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-24 17:40:20.009  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
,03-24 17:40:20.009  3273  3273 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 17:40:20.010  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,03-24 17:40:20.010  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 17:40:20.010  3273  3332 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 17:40:20.010  3273  3332 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 17:40:20.011  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-24 17:40:20.011  3273  3332 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-24 17:40:20.021  2157  2220 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1,
03-24 17:40:20.021  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:40:20.022  2157  2173 D BtGatt.GattService: registerClient() - UUID=19617b76-9876-4522-8f4d-f0d9d327865c
03-24 17:40:20.022  2157  2220 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 17:40:20.023  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:40:20.023  2157  2220 D BtGatt.GattService: onClientRegistered() - UUID=19617b76-9876-4522-8f4d-f0d9d327865c, clientIf=6
03-24 17:40:20.023  2157  2231 D BtGatt.ScanManager: Starting BLE batch scan
,03-24 17:40:20.023  2157  2231 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 17:40:20.024  3273  3292 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-24 17:40:20.025  2157  2230 D BtGatt.AdvertiseManager: message : 0
03-24 17:40:20.026  2157  2220 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 17:40:20.026  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 17:40:20.028  2157  2220 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1,
03-24 17:40:20.028  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 17:40:20.031  2157  2230 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 17:40:20.034  2157  2220 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0,
,03-24 17:40:20.037  2157  2220 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0,
03-24 17:40:20.038  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-24 17:40:20.038  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-24 17:40:20.039   823  1413 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 17:40:20.045  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
03-24 17:40:20.046  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 17:40:20.046  3273  3332 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-24 17:40:20.046  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-24 17:40:20.047  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...,
03-24 17:40:20.048  3273  3332 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,03-24 17:40:20.049  3273  3332 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING,
03-24 17:40:20.049  3273  3332 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-24 17:40:20.049  3273  3332 I io.jxcore.node.ConnectionHelper: start: OK
03-24 17:40:20.049  3273  3273 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,03-24 17:40:20.049  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 17:40:20.049  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-24 17:40:20.049  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-24 17:40:20.050  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-24 17:40:20.050  3273  3273 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
,03-24 17:40:20.050  3273  3273 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 17:40:20.050  3273  3273 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 17:40:20.050  3273  3273 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-24 17:40:20.050  3273  3273 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-24 17:40:20.050   823   838 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 17:40:20.051  3273  3273 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-24 17:40:20.051  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 17:40:20.051  3273  3332 I jxcore-log: 
,03-24 17:40:20.051  3273  3273 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 17:40:20.052  3273  3847 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-24 17:40:20.058  3273  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...,
03-24 17:40:20.058  3273  3332 I jxcore-log: ok 173 Can call startUpdateAdvertisingAndListening without error
03-24 17:40:20.058  3273  3332 I jxcore-log: 
,03-24 17:40:20.064  3273  3332 I io.jxcore.node.ConnectionHelper: start: Port number: 57571, start advertisements: false,
03-24 17:40:20.064  3273  3332 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 17:40:20.064  3273  3332 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should affect listening to advertisements only
,03-24 17:40:20.065  3273  3332 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 17:40:20.065  3273  3332 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 17:40:20.067  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false},
03-24 17:40:20.067  3273  3332 I jxcore-log: 
,03-24 17:40:20.069  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true},
03-24 17:40:20.069  3273  3332 I jxcore-log: 
,03-24 17:40:20.071  3273  3332 I jxcore-log: ok 174 Can call startListeningForAdvertisements without error,
03-24 17:40:20.071  3273  3332 I jxcore-log: 
,03-24 17:40:21.043  2157  2157 D BtGatt.ScanManager: awakened up at time 260470
,03-24 17:40:21.045  2157  2231 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 17:40:21.055  2157  2220 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-24 17:40:21.055  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:40:21.056  2157  2220 D BtGatt.GattService: current time is 260483816981
03-24 17:40:21.056  2157  2220 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -59, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0, -38, 29, 123, -22, -101, 93, 1, -128, -77, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-24 17:40:21.057  2157  2220 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-24 17:40:21.057  2157  2220 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 17:40:21.061  3273  3273 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 1
03-24 17:40:21.061  3273  3273 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> E0:DB:10:14:E2:C0], added - the peer count is 2
,03-24 17:40:21.062  3273  3273 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
03-24 17:40:21.063  3273  3273 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> E0:DB:10:14:E2:C0], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 
,03-24 17:40:21.077  3273  3332 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID F8:95:C7:87:3C:51
03-24 17:40:21.077  3273  3332 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> F8:95:C7:87:3C:51]
,03-24 17:40:21.081  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to G4-1 in address F8:95:C7:87:3C:51
03-24 17:40:21.081  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
03-24 17:40:21.081  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,03-24 17:40:21.082  3273  3332 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: G4-1 F8:95:C7:87:3C:51
,03-24 17:40:21.082  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to G4-1 in address F8:95:C7:87:3C:51
03-24 17:40:21.082  3273  3332 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: F8:95:C7:87:3C:51)
,03-24 17:40:21.082  3273  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address F8:95:C7:87:3C:51 (thread ID: 367)
03-24 17:40:21.082  3273  3848 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-24 17:40:21.086  2157  2222 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,03-24 17:40:21.286  1265  1265 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 17:40:21.400   823  1446 I art     : Explicit concurrent mark sweep GC freed 29028(1299KB) AllocSpace objects, 5(174KB) LOS objects, 32% free, 33MB/49MB, paused 1.689ms total 84.304ms
,03-24 17:40:21.443  1265  1282 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
03-24 17:40:21.443  1265  1282 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 17:40:21.443  1265  1282 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 17:40:21.443  1265  1282 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 17:40:21.447  1265  1282 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 17:40:21.461  3683  3683 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,03-24 17:40:21.461  3683  3683 D Finsky  : [1] 5.onFinished: Installation state replication failed.
,03-24 17:40:21.461  3683  3683 D Finsky  : [1] 5.onFinished: Scheduling replication attempt 4.
,03-24 17:40:22.702  2157  2233 W bt-btif : No ag scb for peer addr
,03-24 17:40:22.844  2157  2233 W bt-btif : info:x10
,03-24 17:40:22.844  2157  2220 D         : remote version info [f8:95:c7:87:3c:51]: 7, f, 2205
,03-24 17:40:22.873  1538  1538 I BTConnectionReceiver: onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,03-24 17:40:22.878  1538  1538 I BluetoothClassifier: Bluetooth Device Name: G4-1
,03-24 17:40:23.662  2157  2233 W bt-sdp  : process_service_search_attr_rsp
,03-24 17:40:24.858  2157  2220 D btif_config: btif_get_device_type: Device [f8:95:c7:87:3c:51] type 1
,03-24 17:40:24.865  2157  2220 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
,03-24 17:40:24.865  2157  2220 E bt-btif : check_cod: remote_cod = 0x5a020c
,03-24 17:40:24.870  2157  2221 I BluetoothBondStateMachine: Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
,03-24 17:40:24.870  2157  2221 I BluetoothBondStateMachine: Entering PendingCommandState State
,03-24 17:40:25.287  2157  2220 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
03-24 17:40:25.288  2157  2221 D BluetoothAdapterProperties: Failed to remove device: F8:95:C7:87:3C:51
,03-24 17:40:25.293  2157  2221 I BluetoothBondStateMachine: Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,03-24 17:40:25.311  2157  2221 I BluetoothBondStateMachine: StableState(): Entering Off State
,03-24 17:40:26.061  2157  2157 D BtGatt.ScanManager: awakened up at time 265488
,03-24 17:40:26.063  2157  2231 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 17:40:26.068  2157  2220 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2,
,03-24 17:40:26.069  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:40:26.069  2157  2220 D BtGatt.GattService: current time is 265497129167
03-24 17:40:26.069  2157  2220 D BtGatt.GattService: Batch record : [-38, 29, 123, -22, -101, 93, 1, -128, -72, 18, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -63, 18, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-24 17:40:26.070  2157  2220 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,03-24 17:40:26.071  2157  2220 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-24 17:40:26.074  3273  3273 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
03-24 17:40:26.075  3273  3273 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> E0:DB:10:14:E2:C0] updated - the peer count is 2
,03-24 17:40:27.572  2157  2233 W bt-btif : new conn_srvc id:26, app_id:255
,03-24 17:40:27.572  2157  2233 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:255
03-24 17:40:27.572  2157  2233 W bt-btif : bta_dm_pm_ssr:2, lat:1200
03-24 17:40:27.573  3273  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection accepted,
03-24 17:40:27.573  2157  2233 W bt-btif : new conn_srvc id:26, app_id:1
03-24 17:40:27.574  3273  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection initialized (thread ID: 368)
03-24 17:40:27.574  2157  2233 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:255
,03-24 17:40:27.574  2157  2233 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:1
03-24 17:40:27.574  2157  2233 W bt-btif : bta_dm_pm_ssr:2, lat:1200
03-24 17:40:27.574  3273  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-24 17:40:27.575   823  1404 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 17:40:27.575  3273  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onSocketConnected: [<no peer name> F8:95:C7:87:3C:51] (thread ID: 367)
03-24 17:40:27.576  3273  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 367)
,03-24 17:40:27.577  3273  3851 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 368)
03-24 17:40:27.577  3273  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesWritten: 15 bytes successfully written (thread ID: 369)
03-24 17:40:27.578  3273  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Outgoing connection initialized (*handshake* thread ID: 369)
03-24 17:40:27.578  3273  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 367)
03-24 17:40:27.579  3273  3847 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-24 17:40:27.582  3273  3852 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 369)
,03-24 17:40:27.586  3273  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-24 17:40:27.594  3273  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesRead: Read 15 bytes successfully (thread ID: 368)
,03-24 17:40:27.597  3273  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Got valid identity from [<no peer name> F8:95:C7:87:3C:51]
,03-24 17:40:27.597  3273  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesWritten: 15 bytes successfully written (thread ID: 368)
03-24 17:40:27.598  3273  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: removeThreadFromList: Removing thread with ID 368,
03-24 17:40:27.598  3273  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Handshake thread disposed (thread ID: 368)
03-24 17:40:27.598  3273  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onIncomingConnectionConnected: [<no peer name> F8:95:C7:87:3C:51]
,03-24 17:40:27.598  3273  3851 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 368)
03-24 17:40:27.598  3273  3273 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> F8:95:C7:87:3C:51]
03-24 17:40:27.598  3273  3273 I io.jxcore.node.ConnectionHelper: onConnected: Incoming connection to peer [<no peer name> F8:95:C7:87:3C:51]
03-24 17:40:27.599  3273  3273 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
03-24 17:40:27.599  3273  3273 I io.jxcore.node.ConnectionHelper: lowerBleDiscoveryPowerAndStartResetTimer: Lowering the power settings
03-24 17:40:27.599  3273  3273 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 2 -> 0
,03-24 17:40:27.599  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
,03-24 17:40:27.599  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 17:40:27.599  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-24 17:40:27.599  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-24 17:40:27.599  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-24 17:40:27.599  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-24 17:40:27.602  3273  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesRead: Read 15 bytes successfully (thread ID: 369)
03-24 17:40:27.603  2157  2230 D BtGatt.AdvertiseManager: message : 1
03-24 17:40:27.604  2157  2230 D BtGatt.AdvertiseManager: stop advertise for client 6
03-24 17:40:27.605  3273  3852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Handshake succeeded with [<no peer name> F8:95:C7:87:3C:51]
,03-24 17:40:27.605  3273  3852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onHandshakeSucceeded: [<no peer name> F8:95:C7:87:3C:51] (thread ID: 367)
,03-24 17:40:27.606  3273  3852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: handleSuccessfulClientThread: [<no peer name> F8:95:C7:87:3C:51] (thread ID: 367)
,03-24 17:40:27.606  3273  3852 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 369)
03-24 17:40:27.608  2157  2220 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,03-24 17:40:27.608  2157  2220 D BtGatt.GattService: Client app is not null!
03-24 17:40:27.610  2157  2222 D BtGatt.GattService: unregisterClient() - clientIf=6
03-24 17:40:27.611  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 17:40:27.611  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-24 17:40:27.611  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 3, timeout: 0, is connectable: false
,03-24 17:40:27.611  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 17:40:27.611  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 17:40:27.612  3273  3273 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
,03-24 17:40:27.612  3273  3273 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 17:40:27.613  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 17:40:27.613  3273  3273 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-24 17:40:27.620  2157  2172 D BtGatt.GattService: registerClient() - UUID=8b019079-5c5b-4ac9-bedd-efdca41b9968
,03-24 17:40:27.620  2157  2220 D BtGatt.GattService: onClientRegistered() - UUID=8b019079-5c5b-4ac9-bedd-efdca41b9968, clientIf=6
03-24 17:40:27.620  3273  3327 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-24 17:40:27.622  2157  2230 D BtGatt.AdvertiseManager: message : 0
,03-24 17:40:27.625  2157  2230 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 17:40:27.627  2157  2220 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 17:40:27.630  2157  2220 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 17:40:27.630  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-24 17:40:27.632  2157  2172 D BtGatt.GattService: stopScan() - queue size =1
,03-24 17:40:27.633  2157  2220 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 17:40:27.633  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 17:40:27.634  2157  2231 D BtGatt.ScanManager: stopping BLe Batch
03-24 17:40:27.634  2157  2172 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-24 17:40:27.635  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 17:40:27.635  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 17:40:27.635  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0,
03-24 17:40:27.635  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 17:40:27.635  2157  2220 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 17:40:27.635  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:40:27.635  2157  2231 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 17:40:27.635  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 17:40:27.636  3273  3273 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 17:40:27.636  2157  2220 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 17:40:27.636  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 17:40:27.641  2157  2222 D BtGatt.GattService: registerClient() - UUID=9ef15ea8-453e-4aea-8a67-5985d341bfbf
03-24 17:40:27.642  2157  2220 D BtGatt.GattService: onClientRegistered() - UUID=9ef15ea8-453e-4aea-8a67-5985d341bfbf, clientIf=5
,03-24 17:40:27.642  3273  3292 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 17:40:27.642  2157  2173 D BtGatt.GattService: start scan with filters
,03-24 17:40:27.643  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 17:40:27.643  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 17:40:27.643  3273  3273 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 3 -> 1
03-24 17:40:27.643  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 17:40:27.643  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 17:40:27.643  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-24 17:40:27.643  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1,
03-24 17:40:27.643  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-24 17:40:27.643  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-24 17:40:27.645  2157  2230 D BtGatt.AdvertiseManager: message : 1
03-24 17:40:27.646  2157  2230 D BtGatt.AdvertiseManager: stop advertise for client 6
03-24 17:40:27.646  2157  2231 D BtGatt.ScanManager: handling starting scan
,03-24 17:40:27.649  2157  2220 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 17:40:27.649  2157  2220 D BtGatt.GattService: Client app is not null!
,03-24 17:40:27.650  2157  2173 D BtGatt.GattService: unregisterClient() - clientIf=6
03-24 17:40:27.650  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 17:40:27.650  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
,03-24 17:40:27.651  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-24 17:40:27.651  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 17:40:27.651  2157  2220 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1,
03-24 17:40:27.651  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:40:27.651  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 17:40:27.651  3273  3273 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 17:40:27.651  3273  3273 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 17:40:27.651  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-24 17:40:27.651  3273  3273 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-24 17:40:27.652  2157  2220 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 17:40:27.652  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 17:40:27.652  2157  2231 D BtGatt.ScanManager: Starting BLE batch scan
03-24 17:40:27.652  2157  2231 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 17:40:27.654  2157  2220 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 17:40:27.654  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:40:27.655  2157  2220 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 17:40:27.655  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 17:40:27.656  2157  2172 D BtGatt.GattService: registerClient() - UUID=4dc21aa7-d9d7-45b9-bd06-86bf5971da66
03-24 17:40:27.656  2157  2220 D BtGatt.GattService: onClientRegistered() - UUID=4dc21aa7-d9d7-45b9-bd06-86bf5971da66, clientIf=6
03-24 17:40:27.656  3273  3291 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-24 17:40:27.657  2157  2230 D BtGatt.AdvertiseManager: message : 0
,03-24 17:40:27.659  2157  2230 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 17:40:27.661  2157  2220 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0,
,03-24 17:40:27.664  2157  2220 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 17:40:27.664  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-24 17:40:27.665  2157  2172 D BtGatt.GattService: stopScan() - queue size =1
,03-24 17:40:27.666  2157  2222 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-24 17:40:27.666  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-24 17:40:27.666  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED,
03-24 17:40:27.667  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 17:40:27.667  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 17:40:27.667  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 17:40:27.667  2157  2220 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 17:40:27.667  3273  3273 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-24 17:40:27.667  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:40:27.667  2157  2231 D BtGatt.ScanManager: stopping BLe Batch
03-24 17:40:27.669  2157  2220 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 17:40:27.669  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:40:27.669  2157  2231 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 17:40:27.670  2157  2173 D BtGatt.GattService: registerClient() - UUID=886f5712-bf78-4047-a743-c020e16edc8d
,03-24 17:40:27.670  2157  2220 D BtGatt.GattService: onClientRegistered() - UUID=886f5712-bf78-4047-a743-c020e16edc8d, clientIf=5,
03-24 17:40:27.670  3273  3327 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 17:40:27.670  2157  2172 D BtGatt.GattService: start scan with filters,
03-24 17:40:27.671  2157  2220 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
03-24 17:40:27.671  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:40:27.671  2157  2220 D BtGatt.GattService: current time is 267099042656
03-24 17:40:27.671  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 17:40:27.671  2157  2220 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -61, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-24 17:40:27.671  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-24 17:40:27.671  3273  3273 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 2 -> 0
03-24 17:40:27.671  2157  2220 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-24 17:40:27.671  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 17:40:27.671  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 17:40:27.671  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-24 17:40:27.671  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-24 17:40:27.671  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-24 17:40:27.671  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-24 17:40:27.675  2157  2231 D BtGatt.ScanManager: handling starting scan
03-24 17:40:27.675  2157  2230 D BtGatt.AdvertiseManager: message : 1
03-24 17:40:27.676  2157  2230 D BtGatt.AdvertiseManager: stop advertise for client 6
03-24 17:40:27.677  2157  2220 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 17:40:27.677  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 17:40:27.678  2157  2220 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 17:40:27.678  2157  2220 D BtGatt.GattService: Client app is not null!
03-24 17:40:27.679  2157  2222 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-24 17:40:27.679  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-24 17:40:27.679  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
,03-24 17:40:27.679  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-24 17:40:27.680  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 17:40:27.680  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 17:40:27.680  3273  3273 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 17:40:27.680  3273  3273 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false],
03-24 17:40:27.680  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 17:40:27.680  3273  3273 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-24 17:40:27.681  2157  2220 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 17:40:27.681  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:40:27.681  2157  2231 D BtGatt.ScanManager: Starting BLE batch scan
03-24 17:40:27.681  2157  2231 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 17:40:27.683  2157  2220 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,03-24 17:40:27.683  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:40:27.684  2157  2173 D BtGatt.GattService: registerClient() - UUID=d61db7ad-3c9a-4a72-9f1f-a7b38717271c
,03-24 17:40:27.684  2157  2220 D BtGatt.GattService: onClientRegistered() - UUID=d61db7ad-3c9a-4a72-9f1f-a7b38717271c, clientIf=6
03-24 17:40:27.684  2157  2220 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,03-24 17:40:27.684  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:40:27.685  3273  3292 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-24 17:40:27.685  2157  2230 D BtGatt.AdvertiseManager: message : 0
03-24 17:40:27.688  2157  2230 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 17:40:27.690  2157  2220 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 17:40:27.692  2157  2220 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 17:40:27.692  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-24 17:40:27.693  2157  2173 D BtGatt.GattService: stopScan() - queue size =1,
,03-24 17:40:27.694  2157  2172 D BtGatt.GattService: unregisterClient() - clientIf=5
03-24 17:40:27.694  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 17:40:27.694  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 17:40:27.694  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
,03-24 17:40:27.694  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 17:40:27.695  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 17:40:27.695  3273  3273 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-24 17:40:27.695  2157  2220 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,03-24 17:40:27.695  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:40:27.696  2157  2231 D BtGatt.ScanManager: stopping BLe Batch
03-24 17:40:27.697  2157  2220 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 17:40:27.698  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 17:40:27.698  2157  2222 D BtGatt.GattService: registerClient() - UUID=2641b82c-ea9f-4a12-bbdd-32a0277ac32b
03-24 17:40:27.698  2157  2231 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 17:40:27.698  2157  2220 D BtGatt.GattService: onClientRegistered() - UUID=2641b82c-ea9f-4a12-bbdd-32a0277ac32b, clientIf=5
03-24 17:40:27.698  3273  3291 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 17:40:27.698  2157  2173 D BtGatt.GattService: start scan with filters
,03-24 17:40:27.699  2157  2220 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 17:40:27.699  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:40:27.699  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 17:40:27.699  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 17:40:27.699  3273  3273 I io.jxcore.node.ConnectionHelper: onConnected: Incoming socket thread, for peer [<no peer name> F8:95:C7:87:3C:51], created successfully
03-24 17:40:27.699  3273  3273 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 1
03-24 17:40:27.699  3273  3273 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> F8:95:C7:87:3C:51]
03-24 17:40:27.699  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,03-24 17:40:27.700  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-24 17:40:27.700  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-24 17:40:27.700  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 17:40:27.700  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 17:40:27.700  3273  3273 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing connection to peer [<no peer name> F8:95:C7:87:3C:51]
03-24 17:40:27.700  3273  3273 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
03-24 17:40:27.701  3273  3853 D io.jxcore.node.IncomingSocketThread: Entering thread (ID: 370)
03-24 17:40:27.701  3273  3273 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing socket thread, for peer [<no peer name> F8:95:C7:87:3C:51], created successfully
03-24 17:40:27.701  3273  3273 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 2
,03-24 17:40:27.703  2157  2231 D BtGatt.ScanManager: handling starting scan
03-24 17:40:27.703  3273  3854 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 371)
,03-24 17:40:27.703  3273  3854 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 44675,
,03-24 17:40:27.703  3273  3854 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
03-24 17:40:27.704  2157  2220 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 17:40:27.704  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:40:27.705  3273  3854 I io.jxcore.node.ConnectionHelper: onListeningForIncomingConnections: Outgoing connection is using port 44675 (peer ID: F8:95:C7:87:3C:51)
,03-24 17:40:27.705  3273  3854 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "F8:95:C7:87:3C:51" removed
03-24 17:40:27.705  2157  2220 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 17:40:27.705  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:40:27.706  2157  2231 D BtGatt.ScanManager: Starting BLE batch scan
03-24 17:40:27.706  2157  2231 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-24 17:40:27.707  3273  3332 I jxcore-log: INFO testThaliMobileNative: 
03-24 17:40:27.707  3273  3332 I jxcore-log: 
03-24 17:40:27.707  2157  2220 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 17:40:27.707  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:40:27.707  3273  3853 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57571
03-24 17:40:27.707  3273  3853 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,03-24 17:40:27.707  3273  3853 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-24 17:40:27.708  3273  3332 I jxcore-log: INFO testThaliMobileNative: Forward connection
03-24 17:40:27.708  3273  3332 I jxcore-log: 
03-24 17:40:27.708  3273  3853 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-24 17:40:27.709  2157  2220 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 17:40:27.709  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:40:27.709  3273  3856 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 372, name: Sender)
03-24 17:40:27.709  3273  3853 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 370)
,03-24 17:40:27.709  3273  3853 D io.jxcore.node.IncomingSocketThread: Exiting thread (ID: 370)
03-24 17:40:27.710  3273  3854 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 44675
03-24 17:40:27.710  3273  3854 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
03-24 17:40:27.710  3273  3854 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-24 17:40:27.710  3273  3854 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-24 17:40:27.711  3273  3858 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 374, name: Sender)
03-24 17:40:27.712  3273  3854 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 371)
03-24 17:40:27.712  3273  3854 D io.jxcore.node.OutgoingSocketThread: Exiting thread (ID: 371)
03-24 17:40:27.712  3273  3857 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 373, name: Receiver)
,03-24 17:40:27.715  3273  3332 I jxcore-log: INFO testThaliMobileNative: forwardSend
03-24 17:40:27.715  3273  3332 I jxcore-log: 
,03-24 17:40:27.717  3273  3859 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 375, name: Receiver)
,03-24 17:40:27.812  3273  3332 I jxcore-log: INFO testThaliMobileNative: forwardData
03-24 17:40:27.812  3273  3332 I jxcore-log: 
,03-24 17:40:27.819  3273  3332 I jxcore-log: INFO testThaliMobileNative: forwardData
03-24 17:40:27.819  3273  3332 I jxcore-log: 
,03-24 17:40:27.827  3273  3332 I jxcore-log: INFO testThaliMobileNative: forwardData
03-24 17:40:27.827  3273  3332 I jxcore-log: 
,03-24 17:40:27.834  3273  3332 I jxcore-log: INFO testThaliMobileNative: forwardData
03-24 17:40:27.834  3273  3332 I jxcore-log: 
,03-24 17:40:27.839  3273  3332 I jxcore-log: INFO testThaliMobileNative: forwardData
03-24 17:40:27.839  3273  3332 I jxcore-log: 
,03-24 17:40:27.840  3273  3332 I jxcore-log: ok 175 received should match sent forward
03-24 17:40:27.840  3273  3332 I jxcore-log: 
,03-24 17:40:27.854  3273  3332 I jxcore-log: # teardown
03-24 17:40:27.854  3273  3332 I jxcore-log: 
,03-24 17:40:28.846  2157  2218 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,03-24 17:40:31.094  3374  3860 V GoogleAuthProtoRequest: [343] a.<init>: mAccountName set to: thalitester@gmail.com
,03-24 17:40:31.172  1265  1603 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,03-24 17:40:31.174  1265  1603 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 17:40:31.174  1265  1603 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 17:40:31.174  1265  1603 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 17:40:31.185  1265  1603 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 17:40:31.217  3374  3860 W ExperimentUpdateService: [343] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,03-24 17:40:31.219  3374  3860 W ExperimentUpdateService: [343] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-24 17:40:31.219  3374  3860 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-24 17:40:31.219  3374  3860 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-24 17:40:31.219  3374  3860 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-24 17:40:31.219  3374  3860 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-24 17:40:31.219  3374  3860 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-24 17:40:31.219  3374  3860 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-24 17:40:31.219  3374  3860 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-24 17:40:31.219  3374  3860 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-24 17:40:31.219  3374  3860 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93),
03-24 17:40:31.219  3374  3860 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-24 17:40:31.243  2157  2157 D BtGatt.ScanManager: awakened up at time 270671
03-24 17:40:31.245  2157  2231 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 17:40:31.246  2157  2220 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 17:40:31.246  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 17:40:31.751  2157  2157 D BtGatt.ScanManager: awakened up at time 271178
,03-24 17:40:31.754  2157  2231 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 17:40:31.757  2157  2220 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 17:40:31.757  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 17:40:32.921  2157  2157 D BtGatt.ScanManager: awakened up at time 272349
03-24 17:40:32.924  2157  2231 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 17:40:32.931  2157  2220 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,03-24 17:40:32.931  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 17:40:33.742  3273  3856 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 372, thread name: Sender)
,03-24 17:40:33.743  3273  3856 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Input stream got -1 on read
,03-24 17:40:33.743  3273  3856 W io.jxcore.node.ConnectionHelper: onDisconnected: Incoming connection, peer [<no peer name> F8:95:C7:87:3C:51] disconnected: Input stream got -1 on read,
,03-24 17:40:33.743  3273  3856 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 370
03-24 17:40:33.743  3273  3856 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 370),
,03-24 17:40:33.744  3273  3856 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
03-24 17:40:33.744  3273  3856 D io.jxcore.node.IncomingSocketThread: close: Stopping receiving thread...
03-24 17:40:33.744  3273  3856 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 373
,03-24 17:40:33.744  3273  3856 D io.jxcore.node.IncomingSocketThread: close: Stopping sending thread...
03-24 17:40:33.744  3273  3856 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 372
,03-24 17:40:33.744  3273  3856 D io.jxcore.node.IncomingSocketThread: closeLocalSocketAndStreams: Closing... (thread ID: 370)
,03-24 17:40:33.745  3273  3857 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 373, thread name: Receiver): bt socket closed, read return: -1
,03-24 17:40:33.745  3273  3857 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 373, name: Receiver)
03-24 17:40:33.745  3273  3856 I io.jxcore.node.IncomingSocketThread: close: Complete (thread ID: 370)
03-24 17:40:33.746  3273  3856 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
03-24 17:40:33.746  3273  3856 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 372, name: Sender)
03-24 17:40:33.750  3273  3332 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 17:40:33.751  3273  3332 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
03-24 17:40:33.751  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-24 17:40:33.751  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-24 17:40:33.755  2157  2222 D BtGatt.GattService: stopScan() - queue size =1
03-24 17:40:33.758  2157  2173 D BtGatt.GattService: unregisterClient() - clientIf=5
03-24 17:40:33.759  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-24 17:40:33.759  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 17:40:33.759  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false,
,03-24 17:40:33.760  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
,03-24 17:40:33.760  2157  2220 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 17:40:33.760  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
,03-24 17:40:33.760  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:40:33.760  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 17:40:33.761  3273  3273 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 17:40:33.762  2157  2231 D BtGatt.ScanManager: stopping BLe Batch
03-24 17:40:33.763  3273  3273 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
,03-24 17:40:33.763  3273  3273 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 17:40:33.764  2157  2220 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0,
03-24 17:40:33.765  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
,03-24 17:40:33.765  2157  2231 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 17:40:33.766  3273  3332 I jxcore-log: INFO thaliMobileNativeWrapper: incomingConnectionToPortNumberFailed: %s,
,03-24 17:40:33.766  3273  3332 I jxcore-log: 
03-24 17:40:33.768  3273  3332 I jxcore-log: INFO thaliMobileNativeWrapper: got incomingConnectionToPortNumberFailed while not in start
03-24 17:40:33.768  3273  3332 I jxcore-log: 
03-24 17:40:33.768  2157  2220 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 17:40:33.768  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:40:33.770  3273  3332 I jxcore-log: ok 176 Should be able to call stopListeningForAdvertisments in teardown
03-24 17:40:33.770  3273  3332 I jxcore-log: 
03-24 17:40:33.771  3273  3332 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-24 17:40:33.772  3273  3332 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> F8:95:C7:87:3C:51]
03-24 17:40:33.772  3273  3332 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 371)
03-24 17:40:33.772  3273  3332 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 371)
03-24 17:40:33.773  3273  3859 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 375, thread name: Receiver): bt socket closed, read return: -1,
03-24 17:40:33.773  3273  3859 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 375, name: Receiver)
03-24 17:40:33.774  3273  3332 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
03-24 17:40:33.775  3273  3332 D io.jxcore.node.OutgoingSocketThread: close: Stopping receiving thread...
03-24 17:40:33.775  3273  3332 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 375
03-24 17:40:33.775  3273  3332 D io.jxcore.node.OutgoingSocketThread: close: Stopping sending thread...
03-24 17:40:33.775  3273  3332 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 374
03-24 17:40:33.775  3273  3332 D io.jxcore.node.OutgoingSocketThread: closeLocalSocketAndStreams: Closing... (thread ID: 371)
03-24 17:40:33.775  3273  3858 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 374, thread name: Sender): Socket closed
03-24 17:40:33.776  3273  3858 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 374, name: Sender)
03-24 17:40:33.777  3273  3332 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 371)
03-24 17:40:33.778  3273  3332 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,03-24 17:40:33.778  3273  3332 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-24 17:40:33.778  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-24 17:40:33.778  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-24 17:40:33.778  3273  3332 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-24 17:40:33.778  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-24 17:40:33.778  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-24 17:40:33.778  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 17:40:33.779  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 17:40:33.779  3273  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-24 17:40:33.779  3273  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-24 17:40:33.779  3273  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-24 17:40:33.780  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-24 17:40:33.783  3273  3332 D BluetoothLeScanner: could not find callback wrapper
,03-24 17:40:33.783  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 17:40:33.783  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-24 17:40:33.785  2157  2230 D BtGatt.AdvertiseManager: message : 1
03-24 17:40:33.785  2157  2230 D BtGatt.AdvertiseManager: stop advertise for client 6
03-24 17:40:33.788  2157  2220 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 17:40:33.788  2157  2220 D BtGatt.GattService: Client app is not null!
03-24 17:40:33.789  2157  2222 D BtGatt.GattService: unregisterClient() - clientIf=6
03-24 17:40:33.790  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 17:40:33.790  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-24 17:40:33.790  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-24 17:40:33.790  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-24 17:40:33.790  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-24 17:40:33.791  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-24 17:40:33.791  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 17:40:33.791  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-24 17:40:33.791  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-24 17:40:33.791  3273  3332 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-24 17:40:33.791  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 17:40:33.792  3273  3273 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 17:40:33.792  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 17:40:33.792  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-24 17:40:33.796  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-24 17:40:33.796  3273  3332 I jxcore-log: 
03-24 17:40:33.798  3273  3273 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-24 17:40:33.798   823  1151 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 17:40:33.804  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
,03-24 17:40:33.805  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
,03-24 17:40:33.806  3273  3273 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 17:40:33.810  3273  3273 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-24 17:40:33.810  3273  3273 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-24 17:40:33.810  3273  3273 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 17:40:33.810  3273  3273 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 17:40:33.810  3273  3273 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 17:40:33.810  3273  3273 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 17:40:33.810  3273  3273 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-24 17:40:33.813  3273  3332 I jxcore-log: ok 177 Should be able to call stopAdvertisingAndListening in teardown
03-24 17:40:33.813  3273  3332 I jxcore-log: 
,03-24 17:40:33.819  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 17:40:33.819  3273  3332 I jxcore-log: 
,03-24 17:40:33.820  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 17:40:33.820  3273  3332 I jxcore-log: 
,03-24 17:40:33.823  3273  3332 I jxcore-log: # setup
,03-24 17:40:33.823  3273  3332 I jxcore-log: 
,03-24 17:40:34.726  2157  2233 W bt-btif : bta_jv_rfc_port_to_cb(port_handle:0x10):jv handle:0x0 not FOUND
,03-24 17:40:34.726  2157  2233 E bt-btif : bta_jv_port_mgmt_sr_cback, p_cb:0x0, p_cb->p_cback0x0
03-24 17:40:34.727  2157  2233 W bt-btif : bta_jv_rfc_port_to_cb(port_handle:0x11):jv handle:0x0 not FOUND
,03-24 17:40:34.770  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 17:40:34.770  3273  3332 I jxcore-log: 
03-24 17:40:34.772  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 17:40:34.772  3273  3332 I jxcore-log: 
,03-24 17:40:34.780  3273  3332 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 17:40:34.780  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 17:40:34.780  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 17:40:34.780  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 17:40:34.780  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 17:40:34.780  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 17:40:34.780  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 17:40:34.780  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 17:40:34.784  3273  3332 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 17:40:34.786  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 17:40:34.786  3273  3332 I jxcore-log: 
,03-24 17:40:34.788  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 17:40:34.788  3273  3332 I jxcore-log: 
,03-24 17:40:34.790  3273  3332 I jxcore-log: # 40. #startListeningForAdvertisements should fail if start not called
,03-24 17:40:34.790  3273  3332 I jxcore-log: 
,03-24 17:40:34.792  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"},
03-24 17:40:34.792  3273  3332 I jxcore-log: 
,03-24 17:40:35.366  3273  3332 I jxcore-log: ok 178 specific error should be returned
03-24 17:40:35.366  3273  3332 I jxcore-log: 
,03-24 17:40:35.374  3273  3332 I jxcore-log: # teardown
,03-24 17:40:35.374  3273  3332 I jxcore-log: 
,03-24 17:40:35.647  3273  3332 I jxcore-log: # setup
03-24 17:40:35.647  3273  3332 I jxcore-log: 
,03-24 17:40:36.929  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 17:40:36.929  3273  3332 I jxcore-log: 
,03-24 17:40:36.934  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native,
03-24 17:40:36.934  3273  3332 I jxcore-log: 
,03-24 17:40:36.949  3273  3332 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 17:40:36.949  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 17:40:36.949  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 17:40:36.949  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 17:40:36.949  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 17:40:36.949  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 17:40:36.949  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 17:40:36.949  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 17:40:36.956  3273  3332 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 17:40:36.961  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native,
03-24 17:40:36.961  3273  3332 I jxcore-log: 
,03-24 17:40:36.966  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native,
03-24 17:40:36.966  3273  3332 I jxcore-log: 
,03-24 17:40:36.974  3273  3332 I jxcore-log: # 41. #startUpdateAdvertisingAndListening should fail if start not called,
03-24 17:40:36.974  3273  3332 I jxcore-log: 
03-24 17:40:36.979  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 17:40:36.979  3273  3332 I jxcore-log: 
,03-24 17:40:37.123  3273  3332 I jxcore-log: ok 179 specific error should be returned
03-24 17:40:37.123  3273  3332 I jxcore-log: 
,03-24 17:40:37.125  3273  3332 I jxcore-log: # teardown
03-24 17:40:37.125  3273  3332 I jxcore-log: 
,03-24 17:40:37.301  3273  3332 I jxcore-log: # setup
03-24 17:40:37.301  3273  3332 I jxcore-log: 
,03-24 17:40:37.483  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 17:40:37.483  3273  3332 I jxcore-log: 
,03-24 17:40:37.485  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 17:40:37.485  3273  3332 I jxcore-log: 
,03-24 17:40:37.491  3273  3332 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 17:40:37.491  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 17:40:37.491  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED,
03-24 17:40:37.491  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 17:40:37.491  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 17:40:37.491  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 17:40:37.491  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 17:40:37.491  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 17:40:37.495  3273  3332 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 17:40:37.496  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 17:40:37.496  3273  3332 I jxcore-log: 
,03-24 17:40:37.497  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 17:40:37.497  3273  3332 I jxcore-log: 
,03-24 17:40:37.499  3273  3332 I jxcore-log: # 42. should be able to call #stopListeningForAdvertisements many times
03-24 17:40:37.499  3273  3332 I jxcore-log: 
03-24 17:40:37.501  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 17:40:37.501  3273  3332 I jxcore-log: 
,03-24 17:40:37.727  3273  3332 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 17:40:37.727  3273  3332 I jxcore-log: 
,03-24 17:40:37.729  3273  3332 I jxcore-log: DEBUG createNativeListener: listening 43483
03-24 17:40:37.729  3273  3332 I jxcore-log: 
,03-24 17:40:37.731  3273  3332 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 17:40:37.731  3273  3332 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 17:40:37.731  3273  3332 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 17:40:37.734  3273  3332 I jxcore-log: ok 180 no errors
03-24 17:40:37.734  3273  3332 I jxcore-log: 
03-24 17:40:37.735  3273  3332 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 17:40:37.735  3273  3332 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 17:40:37.735  3273  3332 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 17:40:37.736  3273  3332 I jxcore-log: ok 181 still no errors
03-24 17:40:37.736  3273  3332 I jxcore-log: 
,03-24 17:40:37.742  3273  3332 I jxcore-log: # teardown,
03-24 17:40:37.742  3273  3332 I jxcore-log: 
,03-24 17:40:37.883  3273  3332 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 17:40:37.884  3273  3332 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 17:40:37.884  3273  3332 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 17:40:37.885  3273  3332 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 17:40:37.885  3273  3332 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-24 17:40:37.885  3273  3332 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 17:40:37.893  3273  3332 I jxcore-log: # setup
03-24 17:40:37.893  3273  3332 I jxcore-log: 
,03-24 17:40:38.044  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 17:40:38.044  3273  3332 I jxcore-log: 
,03-24 17:40:38.045  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 17:40:38.045  3273  3332 I jxcore-log: 
,03-24 17:40:38.051  3273  3332 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
,03-24 17:40:38.051  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 17:40:38.051  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 17:40:38.051  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 17:40:38.051  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 17:40:38.051  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 17:40:38.051  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 17:40:38.051  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 17:40:38.054  3273  3332 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 17:40:38.055  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 17:40:38.055  3273  3332 I jxcore-log: 
,03-24 17:40:38.056  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 17:40:38.056  3273  3332 I jxcore-log: 
,03-24 17:40:38.059  3273  3332 I jxcore-log: # 43. should be able to call #startListeningForAdvertisements many times
03-24 17:40:38.059  3273  3332 I jxcore-log: 
03-24 17:40:38.060  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 17:40:38.060  3273  3332 I jxcore-log: 
,03-24 17:40:38.212  3273  3332 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 17:40:38.212  3273  3332 I jxcore-log: 
,03-24 17:40:38.215  3273  3332 I jxcore-log: DEBUG createNativeListener: listening 58436
03-24 17:40:38.215  3273  3332 I jxcore-log: 
,03-24 17:40:38.220  3273  3332 I io.jxcore.node.ConnectionHelper: start: Port number: 57571, start advertisements: false
,03-24 17:40:38.220  3273  3332 I io.jxcore.node.ConnectionHelper: restoreDefaultBleDiscoverySettings: Powering the BLE discovery back up
03-24 17:40:38.221  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 0 -> 2
03-24 17:40:38.221  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 17:40:38.221  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 17:40:38.221  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-24 17:40:38.221  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-24 17:40:38.221  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-24 17:40:38.221  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-24 17:40:38.221  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 1, timeout: 0, is connectable: false
03-24 17:40:38.221  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-24 17:40:38.221  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 1 -> 3
03-24 17:40:38.221  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 17:40:38.221  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 17:40:38.221  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-24 17:40:38.221  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-24 17:40:38.221  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-24 17:40:38.221  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-24 17:40:38.221  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-24 17:40:38.221  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-24 17:40:38.221  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 0 -> 2
03-24 17:40:38.221  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 17:40:38.221  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 17:40:38.221  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-24 17:40:38.221  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-24 17:40:38.221  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-24 17:40:38.221  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-24 17:40:38.221  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-24 17:40:38.221  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 17:40:38.221  3273  3332 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 17:40:38.221  3273  3332 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 17:40:38.221  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
03-24 17:40:38.228  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 17:40:38.229  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 17:40:38.229  3273  3332 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=,null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-24 17:40:38.238  2157  2222 D BtGatt.GattService: registerClient() - UUID=a366d70c-04d0-474e-8fd5-6f334c0d6e2c
03-24 17:40:38.238  2157  2220 D BtGatt.GattService: onClientRegistered() - UUID=a366d70c-04d0-474e-8fd5-6f334c0d6e2c, clientIf=5
03-24 17:40:38.239  3273  3291 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 17:40:38.239  2157  2173 D BtGatt.GattService: start scan with filters
03-24 17:40:38.242  2157  2231 D BtGatt.ScanManager: handling starting scan
03-24 17:40:38.244  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 17:40:38.244  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 17:40:38.244  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-24 17:40:38.245  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-24 17:40:38.245  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 17:40:38.245  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 17:40:38.245   823  1151 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 17:40:38.246  3273  3273 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 17:40:38.246  2157  2220 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 17:40:38.246  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:40:38.248  2157  2220 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 17:40:38.248  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:40:38.248  2157  2231 D BtGatt.ScanManager: Starting BLE batch scan
03-24 17:40:38.248  2157  2231 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 17:40:38.248  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 17:40:38.248  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 17:40:38.249  3273  3273 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 17:40:38.249  3273  3273 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 17:40:38.249  3273  3273 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 17:40:38.250  2157  2220 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 17:40:38.250  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:40:38.250  3273  3332 I io.jxcore.node.ConnectionHelper: start: OK
03-24 17:40:38.251  2157  2220 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 17:40:38.251  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:40:38.254  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 17:40:38.254  3273  3332 I jxcore-log: 
03-24 17:40:38.255  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 17:40:38.255  3273  3332 I jxcore-log: 
03-24 17:40:38.256  3273  3332 I jxcore-log: ok 182 no errors
03-24 17:40:38.256  3273  3332 I jxcore-log: 
03-24 17:40:38.260  3273  3332 I io.jxcore.node.ConnectionHelper: start: Port number: 57571, start advertisements: false
03-24 17:40:38.260  3273  3332 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 17:40:38.260  3273  3332 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 17:40:38.260  3273  3332 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 17:40:38.261  3273  3332 I io.jxcore.node.ConnectionHelper: start: OK
03-24 17:40:38.263  3273  3332 I jxcore-log: ok 183 still no errors
03-24 17:40:38.263  3273  3332 I jxcore-log: 
03-24 17:40:38.269  3273  3332 I jxcore-log: # teardown
03-24 17:40:38.269  3273  3332 I jxcore-log: 
,03-24 17:40:38.448  3273  3332 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 17:40:38.448  3273  3332 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
03-24 17:40:38.448  3273  3332 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
03-24 17:40:38.448  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-24 17:40:38.448  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,03-24 17:40:38.448  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 17:40:38.448  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 17:40:38.449  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-24 17:40:38.449  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-24 17:40:38.451  2157  2173 D BtGatt.GattService: stopScan() - queue size =1
,03-24 17:40:38.453  2157  2172 D BtGatt.GattService: unregisterClient() - clientIf=5
03-24 17:40:38.454  2157  2220 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 17:40:38.454  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 17:40:38.454  2157  2231 D BtGatt.ScanManager: stopping BLe Batch
03-24 17:40:38.454  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 17:40:38.455  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-24 17:40:38.455  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,03-24 17:40:38.455  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-24 17:40:38.455  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-24 17:40:38.455  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-24 17:40:38.457  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 17:40:38.457  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 17:40:38.457  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-24 17:40:38.458  2157  2220 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 17:40:38.458  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:40:38.458  2157  2231 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 17:40:38.458  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-24 17:40:38.459  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 17:40:38.459  3273  3273 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 17:40:38.459  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 17:40:38.459  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-24 17:40:38.460  2157  2220 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 17:40:38.460  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 17:40:38.469  3273  3273 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-24 17:40:38.471   823  1404 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 17:40:38.478  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
03-24 17:40:38.479  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 17:40:38.479  3273  3273 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 17:40:38.484  3273  3273 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-24 17:40:38.484  3273  3273 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 17:40:38.484  3273  3273 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 17:40:38.484  3273  3273 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-24 17:40:38.487  3273  3332 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 17:40:38.487  3273  3332 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-24 17:40:38.488  3273  3332 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 17:40:38.493  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
,03-24 17:40:38.493  3273  3332 I jxcore-log: 
,03-24 17:40:38.497  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
,03-24 17:40:38.497  3273  3332 I jxcore-log: 
,03-24 17:40:38.510  3273  3332 I jxcore-log: # setup
03-24 17:40:38.510  3273  3332 I jxcore-log: 
,03-24 17:40:38.695  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 17:40:38.695  3273  3332 I jxcore-log: 
,03-24 17:40:38.700  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 17:40:38.700  3273  3332 I jxcore-log: 
,03-24 17:40:38.713  3273  3332 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 17:40:38.713  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 17:40:38.713  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 17:40:38.713  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 17:40:38.713  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 17:40:38.713  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 17:40:38.713  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 17:40:38.713  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 17:40:38.717  3273  3332 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 17:40:38.722  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 17:40:38.722  3273  3332 I jxcore-log: 
,03-24 17:40:38.726  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 17:40:38.726  3273  3332 I jxcore-log: 
03-24 17:40:38.731  3273  3332 I jxcore-log: # 44. should be able to call #startUpdateAdvertisingAndListening many times
03-24 17:40:38.731  3273  3332 I jxcore-log: 
,03-24 17:40:38.734  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 17:40:38.734  3273  3332 I jxcore-log: 
,03-24 17:40:38.935  2157  2233 E bt-btm  : btm_sec_disconnected - Clearing Pending flag
,03-24 17:40:38.943  2157  2157 D BluetoothMapService: onReceive
,03-24 17:40:38.964  3273  3332 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 17:40:38.964  3273  3332 I jxcore-log: 
,03-24 17:40:38.967  3273  3332 I jxcore-log: DEBUG createNativeListener: listening 34571
03-24 17:40:38.967  3273  3332 I jxcore-log: 
,03-24 17:40:38.968  1538  1538 I BTConnectionReceiver: onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,03-24 17:40:38.975  1538  1538 I BluetoothClassifier: Bluetooth Device Name: G4-1
,03-24 17:40:38.979  3273  3332 I io.jxcore.node.ConnectionHelper: start: Port number: 34571, start advertisements: true
03-24 17:40:38.979  3273  3332 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-24 17:40:38.979  3273  3332 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-24 17:40:38.979  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-24 17:40:38.986  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser,
03-24 17:40:38.986  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 17:40:38.986  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true,
03-24 17:40:38.987  3273  3332 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 17:40:38.993  2157  2222 D BtGatt.GattService: registerClient() - UUID=893aae03-3db9-4ec3-9f23-54019d888cb8
,03-24 17:40:38.993  2157  2220 D BtGatt.GattService: onClientRegistered() - UUID=893aae03-3db9-4ec3-9f23-54019d888cb8, clientIf=5
03-24 17:40:38.994  3273  3291 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-24 17:40:38.995  2157  2172 D BtGatt.GattService: start scan with filters
,03-24 17:40:38.997  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 17:40:38.997  2157  2231 D BtGatt.ScanManager: handling starting scan
,03-24 17:40:38.997  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true,
03-24 17:40:38.997  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-24 17:40:38.997  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-24 17:40:38.997  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 17:40:38.997  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 17:40:38.997  3273  3273 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 17:40:38.998  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61",
03-24 17:40:38.998  3273  3332 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 17:40:38.998  3273  3332 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 17:40:38.998  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 17:40:38.998  3273  3332 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-24 17:40:38.999  2157  2220 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 17:40:38.999  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 17:40:39.000  2157  2220 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 17:40:39.000  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:40:39.000  2157  2231 D BtGatt.ScanManager: Starting BLE batch scan
03-24 17:40:39.000  2157  2231 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-24 17:40:39.002  2157  2220 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 17:40:39.003  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 17:40:39.004  2157  2220 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,03-24 17:40:39.004  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 17:40:39.015  2157  2222 D BtGatt.GattService: registerClient() - UUID=9f6d4490-11f4-49af-8515-7211d7a9f690
,03-24 17:40:39.016  2157  2220 D BtGatt.GattService: onClientRegistered() - UUID=9f6d4490-11f4-49af-8515-7211d7a9f690, clientIf=6
,03-24 17:40:39.016  3273  3327 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-24 17:40:39.018  2157  2230 D BtGatt.AdvertiseManager: message : 0
,03-24 17:40:39.021  2157  2230 D BtGatt.AdvertiseManager: starting multi advertising,
,03-24 17:40:39.023  2157  2220 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0,
,03-24 17:40:39.026  2157  2220 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 17:40:39.027  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-24 17:40:39.027  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-24 17:40:39.027   823  1153 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 17:40:39.032  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
03-24 17:40:39.032  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-24 17:40:39.032  3273  3332 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-24 17:40:39.032  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 17:40:39.033  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-24 17:40:39.033  3273  3332 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-24 17:40:39.033  3273  3332 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-24 17:40:39.033  3273  3332 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK,
03-24 17:40:39.034  3273  3273 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-24 17:40:39.034  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,03-24 17:40:39.034  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-24 17:40:39.034  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,03-24 17:40:39.034  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-24 17:40:39.034  3273  3273 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-24 17:40:39.034  3273  3273 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-24 17:40:39.034   823  1446 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 17:40:39.034  3273  3273 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-24 17:40:39.034  3273  3273 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-24 17:40:39.034  3273  3273 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 17:40:39.035  3273  3273 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,03-24 17:40:39.035  3273  3273 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-24 17:40:39.035  3273  3863 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-24 17:40:39.035  3273  3332 I io.jxcore.node.ConnectionHelper: start: OK
03-24 17:40:39.037  3273  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
03-24 17:40:39.038  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false},
03-24 17:40:39.038  3273  3332 I jxcore-log: 
03-24 17:40:39.039  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
,03-24 17:40:39.039  3273  3332 I jxcore-log: 
03-24 17:40:39.040  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-24 17:40:39.040  3273  3332 I jxcore-log: 
,03-24 17:40:39.042  3273  3332 I jxcore-log: ok 184 no errors
03-24 17:40:39.042  3273  3332 I jxcore-log: 
03-24 17:40:39.047  3273  3332 I io.jxcore.node.ConnectionHelper: start: Port number: 34571, start advertisements: true
,03-24 17:40:39.047  3273  3332 V io.jxcore.node.ConnectivityMonitor: start: Already started,
03-24 17:40:39.047  3273  3332 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-24 17:40:39.047  3273  3332 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 17:40:39.047  3273  3332 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 17:40:39.051  3273  3332 I jxcore-log: ok 185 still no errors
03-24 17:40:39.051  3273  3332 I jxcore-log: 
,03-24 17:40:39.056  3273  3332 I jxcore-log: # teardown
03-24 17:40:39.056  3273  3332 I jxcore-log: 
,03-24 17:40:39.313  3273  3332 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 17:40:39.314  3273  3332 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-24 17:40:39.314  3273  3332 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-24 17:40:39.314  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-24 17:40:39.314  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,03-24 17:40:39.315  3273  3332 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-24 17:40:39.315  3273  3863 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-24 17:40:39.315  3273  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-24 17:40:39.315  3273  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,03-24 17:40:39.315  3273  3273 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-24 17:40:39.316  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-24 17:40:39.317  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,03-24 17:40:39.317  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 17:40:39.317  3273  3273 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-24 17:40:39.317  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,03-24 17:40:39.317  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-24 17:40:39.317  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-24 17:40:39.319  2157  2172 D BtGatt.GattService: stopScan() - queue size =1
03-24 17:40:39.321  2157  2220 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,03-24 17:40:39.321  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:40:39.322  2157  2231 D BtGatt.ScanManager: stopping BLe Batch
03-24 17:40:39.322  2157  2173 D BtGatt.GattService: unregisterClient() - clientIf=5,
03-24 17:40:39.323  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 17:40:39.323  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED,
03-24 17:40:39.323  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,03-24 17:40:39.323  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING],
03-24 17:40:39.323  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
,03-24 17:40:39.323  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 17:40:39.324  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...,
,03-24 17:40:39.324  2157  2220 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,03-24 17:40:39.324  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
,03-24 17:40:39.324  2157  2231 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5,
03-24 17:40:39.327  2157  2220 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2,
03-24 17:40:39.328  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
03-24 17:40:39.328  2157  2220 D BtGatt.GattService: current time is 278756044578,
03-24 17:40:39.328  2157  2220 D BtGatt.GattService: Batch record : [96, 95, 50, -72, 83, 104, 1, -128, -78, 6, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -47, 5, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0],
03-24 17:40:39.329  2157  2220 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81],
,03-24 17:40:39.329  2157  2220 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
,03-24 17:40:39.331  2157  2230 D BtGatt.AdvertiseManager: message : 1,
03-24 17:40:39.332  2157  2230 D BtGatt.AdvertiseManager: stop advertise for client 6,
03-24 17:40:39.334  2157  2220 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,03-24 17:40:39.334  2157  2220 D BtGatt.GattService: Client app is not null!
,03-24 17:40:39.336  2157  2173 D BtGatt.GattService: unregisterClient() - clientIf=6,
03-24 17:40:39.337  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
03-24 17:40:39.338  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-24 17:40:39.338  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false,
03-24 17:40:39.338  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED],
,03-24 17:40:39.338  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-24 17:40:39.338  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 17:40:39.338  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,03-24 17:40:39.338  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-24 17:40:39.339  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,03-24 17:40:39.339  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 17:40:39.340  3273  3273 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 17:40:39.340  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 17:40:39.340  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-24 17:40:39.350  3273  3273 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-24 17:40:39.351   823   838 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 17:40:39.363  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
,03-24 17:40:39.365  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-24 17:40:39.365  3273  3273 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 17:40:39.372  3273  3273 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED,
03-24 17:40:39.372  3273  3273 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 17:40:39.372  3273  3273 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-24 17:40:39.373  3273  3273 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 17:40:39.373  3273  3273 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 17:40:39.374  3273  3273 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-24 17:40:39.376  3273  3332 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 17:40:39.377  3273  3332 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-24 17:40:39.377  3273  3332 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 17:40:39.381  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-24 17:40:39.381  3273  3332 I jxcore-log: 
,03-24 17:40:39.383  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 17:40:39.383  3273  3332 I jxcore-log: 
,03-24 17:40:39.385  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 17:40:39.385  3273  3332 I jxcore-log: 
,03-24 17:40:39.405  3273  3332 I jxcore-log: # setup
,03-24 17:40:39.405  3273  3332 I jxcore-log: 
,03-24 17:40:39.584  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 17:40:39.584  3273  3332 I jxcore-log: 
,03-24 17:40:39.585  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 17:40:39.585  3273  3332 I jxcore-log: 
,03-24 17:40:39.593  3273  3332 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 17:40:39.593  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 17:40:39.593  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 17:40:39.593  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 17:40:39.593  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 17:40:39.593  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 17:40:39.593  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 17:40:39.593  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 17:40:39.597  3273  3332 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 17:40:39.599  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 17:40:39.599  3273  3332 I jxcore-log: 
,03-24 17:40:39.600  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 17:40:39.600  3273  3332 I jxcore-log: 
,03-24 17:40:39.604  3273  3332 I jxcore-log: # 45. should be able to call #stopAdvertisingAndListening many times
03-24 17:40:39.604  3273  3332 I jxcore-log: 
,03-24 17:40:39.606  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 17:40:39.606  3273  3332 I jxcore-log: 
,03-24 17:40:39.732  3273  3332 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 17:40:39.732  3273  3332 I jxcore-log: 
,03-24 17:40:39.735  3273  3332 I jxcore-log: DEBUG createNativeListener: listening 45706
03-24 17:40:39.735  3273  3332 I jxcore-log: 
,03-24 17:40:39.737  3273  3332 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-24 17:40:39.737  3273  3332 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 17:40:39.737  3273  3332 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 17:40:39.740  3273  3332 I jxcore-log: ok 186 no errors
,03-24 17:40:39.740  3273  3332 I jxcore-log: 
03-24 17:40:39.741  3273  3332 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-24 17:40:39.741  3273  3332 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 17:40:39.741  3273  3332 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 17:40:39.744  3273  3332 I jxcore-log: ok 187 still no errors
03-24 17:40:39.744  3273  3332 I jxcore-log: 
,03-24 17:40:39.750  3273  3332 I jxcore-log: # teardown
03-24 17:40:39.750  3273  3332 I jxcore-log: 
,03-24 17:40:39.852  3273  3332 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 17:40:39.852  3273  3332 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 17:40:39.853  3273  3332 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 17:40:39.856  3273  3332 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 17:40:39.856  3273  3332 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 17:40:39.856  3273  3332 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 17:40:39.883  3273  3332 I jxcore-log: # setup
03-24 17:40:39.883  3273  3332 I jxcore-log: 
,03-24 17:40:39.954  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 17:40:39.954  3273  3332 I jxcore-log: 
,03-24 17:40:39.958  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 17:40:39.958  3273  3332 I jxcore-log: 
,03-24 17:40:39.970  3273  3332 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 17:40:39.970  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 17:40:39.970  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED,
03-24 17:40:39.970  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 17:40:39.970  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 17:40:39.970  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 17:40:39.970  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 17:40:39.970  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 17:40:39.977  3273  3332 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 17:40:39.981  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native,
03-24 17:40:39.981  3273  3332 I jxcore-log: 
,03-24 17:40:39.986  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native,
03-24 17:40:39.986  3273  3332 I jxcore-log: 
,03-24 17:40:39.994  3273  3332 I jxcore-log: # 46. can get the network status before starting,
03-24 17:40:39.994  3273  3332 I jxcore-log: 
03-24 17:40:39.995  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
,03-24 17:40:39.995  3273  3332 I jxcore-log: 
,03-24 17:40:40.094  3273  3332 I jxcore-log: ok 188 network status should have certain non-empty properties
,03-24 17:40:40.094  3273  3332 I jxcore-log: 
,03-24 17:40:40.097  3273  3332 I jxcore-log: # teardown
03-24 17:40:40.097  3273  3332 I jxcore-log: 
,03-24 17:40:40.204  3273  3332 I jxcore-log: # setup
03-24 17:40:40.204  3273  3332 I jxcore-log: 
,03-24 17:40:40.316  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 17:40:40.316  3273  3332 I jxcore-log: 
,03-24 17:40:40.321  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 17:40:40.321  3273  3332 I jxcore-log: 
,03-24 17:40:40.334  3273  3332 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 17:40:40.334  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
,03-24 17:40:40.334  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 17:40:40.334  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 17:40:40.334  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 17:40:40.334  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 17:40:40.334  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 17:40:40.334  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 17:40:40.339  3273  3332 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 17:40:40.345  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 17:40:40.345  3273  3332 I jxcore-log: 
,03-24 17:40:40.349  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 17:40:40.349  3273  3332 I jxcore-log: 
,03-24 17:40:40.358  3273  3332 I jxcore-log: # 47. error returned with bad router
03-24 17:40:40.358  3273  3332 I jxcore-log: 
,03-24 17:40:40.364  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 17:40:40.364  3273  3332 I jxcore-log: 
,03-24 17:40:40.537  3273  3332 I jxcore-log: ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a string
03-24 17:40:40.537  3273  3332 I jxcore-log: 
,03-24 17:40:40.539  3273  3332 I jxcore-log: ok 189 specific error expected
03-24 17:40:40.539  3273  3332 I jxcore-log: 
,03-24 17:40:40.541  3273  3332 I jxcore-log: # teardown
03-24 17:40:40.541  3273  3332 I jxcore-log: 
,03-24 17:40:40.673  3273  3332 I jxcore-log: # setup
03-24 17:40:40.673  3273  3332 I jxcore-log: 
,03-24 17:40:40.780  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 17:40:40.780  3273  3332 I jxcore-log: 
,03-24 17:40:40.784  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 17:40:40.784  3273  3332 I jxcore-log: 
,03-24 17:40:40.798  3273  3332 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 17:40:40.798  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 17:40:40.798  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 17:40:40.798  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 17:40:40.798  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 17:40:40.798  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 17:40:40.798  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 17:40:40.798  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 17:40:40.804  3273  3332 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 17:40:40.807  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 17:40:40.807  3273  3332 I jxcore-log: 
,03-24 17:40:40.810  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 17:40:40.810  3273  3332 I jxcore-log: 
,03-24 17:40:40.817  3273  3332 I jxcore-log: # 48. all services are stopped when we call stop
03-24 17:40:40.817  3273  3332 I jxcore-log: 
,03-24 17:40:40.821  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 17:40:40.821  3273  3332 I jxcore-log: 
,03-24 17:40:40.942  3273  3332 I jxcore-log: DEBUG createNativeListener: creating native server
,03-24 17:40:40.942  3273  3332 I jxcore-log: 
,03-24 17:40:40.944  3273  3332 I jxcore-log: DEBUG createNativeListener: listening 57264
03-24 17:40:40.944  3273  3332 I jxcore-log: 
,03-24 17:40:40.951  3273  3332 I io.jxcore.node.ConnectionHelper: start: Port number: 34571, start advertisements: false
,03-24 17:40:40.951  3273  3332 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 17:40:40.951  3273  3332 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 17:40:40.952  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-24 17:40:40.956  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-24 17:40:40.956  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 17:40:40.956  3273  3332 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 17:40:40.962  2157  2172 D BtGatt.GattService: registerClient() - UUID=2610c372-4bef-4830-82a4-f1197c83417c
,03-24 17:40:40.962  2157  2220 D BtGatt.GattService: onClientRegistered() - UUID=2610c372-4bef-4830-82a4-f1197c83417c, clientIf=5
,03-24 17:40:40.963  3273  3291 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 17:40:40.963  2157  2173 D BtGatt.GattService: start scan with filters
,03-24 17:40:40.964  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 17:40:40.964  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 17:40:40.964  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-24 17:40:40.964  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-24 17:40:40.964  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
,03-24 17:40:40.964  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 17:40:40.964  3273  3273 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 17:40:40.965  2157  2231 D BtGatt.ScanManager: handling starting scan
03-24 17:40:40.965   823  1153 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 17:40:40.969  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 17:40:40.969  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 17:40:40.970  3273  3273 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 17:40:40.970  3273  3273 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 17:40:40.970  3273  3273 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 17:40:40.970  3273  3332 I io.jxcore.node.ConnectionHelper: start: OK
03-24 17:40:40.974  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false},
03-24 17:40:40.974  3273  3332 I jxcore-log: 
03-24 17:40:40.975  2157  2220 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 17:40:40.975  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 17:40:40.976  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 17:40:40.976  3273  3332 I jxcore-log: 
03-24 17:40:40.977  2157  2220 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 17:40:40.977  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:40:40.978  2157  2231 D BtGatt.ScanManager: Starting BLE batch scan
03-24 17:40:40.978  2157  2231 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-24 17:40:40.981  2157  2220 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,03-24 17:40:40.981  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 17:40:40.984  2157  2220 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 17:40:40.984  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 17:40:40.988  3273  3332 I io.jxcore.node.ConnectionHelper: start: Port number: 57264, start advertisements: true
03-24 17:40:40.988  3273  3332 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-24 17:40:40.988  3273  3332 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-24 17:40:40.988  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-24 17:40:40.994  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
03-24 17:40:40.994  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
,03-24 17:40:40.994  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 17:40:40.994  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 17:40:40.994  3273  3332 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 17:40:40.994  3273  3332 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 17:40:40.994  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-24 17:40:40.994  3273  3332 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-24 17:40:41.000  2157  2222 D BtGatt.GattService: registerClient() - UUID=8d15bc4d-2a7a-4658-a4d9-09f9bcad65a8
,03-24 17:40:41.001  2157  2220 D BtGatt.GattService: onClientRegistered() - UUID=8d15bc4d-2a7a-4658-a4d9-09f9bcad65a8, clientIf=6
03-24 17:40:41.001  3273  3292 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-24 17:40:41.003  2157  2230 D BtGatt.AdvertiseManager: message : 0
,03-24 17:40:41.008  2157  2230 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 17:40:41.013  2157  2220 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 17:40:41.015  2157  2220 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 17:40:41.016  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 17:40:41.017  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-24 17:40:41.017  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-24 17:40:41.017  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,03-24 17:40:41.018  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-24 17:40:41.018  3273  3273 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-24 17:40:41.019  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 17:40:41.019   823   839 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 17:40:41.023  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 17:40:41.023  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-24 17:40:41.023  3273  3273 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 17:40:41.024  3273  3332 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-24 17:40:41.024  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 17:40:41.024  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-24 17:40:41.025  3273  3332 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,03-24 17:40:41.025  3273  3332 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-24 17:40:41.025  3273  3332 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-24 17:40:41.025  3273  3273 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-24 17:40:41.026  3273  3273 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-24 17:40:41.026  3273  3273 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-24 17:40:41.026  3273  3332 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 17:40:41.028   823   838 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 17:40:41.029  3273  3864 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-24 17:40:41.030  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-24 17:40:41.030  3273  3332 I jxcore-log: 
,03-24 17:40:41.034  3273  3864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-24 17:40:41.036  3273  3332 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 17:40:41.036  3273  3332 I jxcore-log: 
,03-24 17:40:41.038  3273  3332 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 17:40:41.038  3273  3332 I jxcore-log: 
,03-24 17:40:41.040  3273  3332 I jxcore-log: DEBUG createNativeListener: new mux
03-24 17:40:41.040  3273  3332 I jxcore-log: 
,03-24 17:40:41.045  3273  3332 I jxcore-log: ok 190 connection to servers manager should succeed after starting
03-24 17:40:41.045  3273  3332 I jxcore-log: 
,03-24 17:40:41.055  3273  3332 I jxcore-log: ok 191 connection to router server should succeed after starting
03-24 17:40:41.055  3273  3332 I jxcore-log: 
,03-24 17:40:41.057  3273  3332 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-24 17:40:41.057  3273  3332 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-24 17:40:41.057  3273  3332 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-24 17:40:41.057  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-24 17:40:41.057  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-24 17:40:41.057  3273  3332 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-24 17:40:41.057  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-24 17:40:41.057  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-24 17:40:41.057  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 17:40:41.057  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 17:40:41.058  3273  3864 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
,03-24 17:40:41.058  3273  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-24 17:40:41.058  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-24 17:40:41.058  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-24 17:40:41.058  3273  3864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-24 17:40:41.060  2157  2172 D BtGatt.GattService: stopScan() - queue size =1
03-24 17:40:41.061  2157  2173 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-24 17:40:41.062  2157  2220 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 17:40:41.063  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:40:41.063  2157  2231 D BtGatt.ScanManager: stopping BLe Batch
03-24 17:40:41.064  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-24 17:40:41.064  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 17:40:41.064  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-24 17:40:41.064  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-24 17:40:41.064  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-24 17:40:41.064  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 17:40:41.064  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,03-24 17:40:41.066  2157  2230 D BtGatt.AdvertiseManager: message : 1
,03-24 17:40:41.067  2157  2230 D BtGatt.AdvertiseManager: stop advertise for client 6,
03-24 17:40:41.067  2157  2220 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 17:40:41.067  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 17:40:41.068  2157  2231 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 17:40:41.071  2157  2220 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
03-24 17:40:41.071  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:40:41.071  2157  2220 D BtGatt.GattService: current time is 280499637338
,03-24 17:40:41.072  2157  2220 D BtGatt.GattService: Batch record : [72, -73, 79, -41, -122, 87, 1, -128, -78, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-24 17:40:41.072  2157  2220 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 17:40:41.073  2157  2220 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 17:40:41.074  2157  2220 D BtGatt.GattService: Client app is not null!
,03-24 17:40:41.075  2157  2173 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-24 17:40:41.076  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 17:40:41.076  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-24 17:40:41.076  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-24 17:40:41.076  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,03-24 17:40:41.076  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-24 17:40:41.076  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 17:40:41.076  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 17:40:41.076  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-24 17:40:41.077  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,03-24 17:40:41.077  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 17:40:41.077  3273  3273 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 17:40:41.077  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 17:40:41.077  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-24 17:40:41.086  3273  3332 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 17:40:41.086  3273  3332 I jxcore-log: ,
03-24 17:40:41.086  3273  3273 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-24 17:40:41.087   823   839 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 17:40:41.095  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
03-24 17:40:41.096  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 17:40:41.096  3273  3273 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 17:40:41.099  3273  3273 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-24 17:40:41.099  3273  3273 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-24 17:40:41.099  3273  3273 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 17:40:41.099  3273  3273 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 17:40:41.099  3273  3273 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 17:40:41.100  3273  3273 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 17:40:41.100  3273  3273 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 17:40:41.100  3273  3273 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-24 17:40:41.101  3273  3332 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 17:40:41.102  3273  3332 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 17:40:41.102  3273  3332 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 17:40:41.104  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-24 17:40:41.104  3273  3332 I jxcore-log: 
,03-24 17:40:41.106  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 17:40:41.106  3273  3332 I jxcore-log: 
,03-24 17:40:41.108  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 17:40:41.108  3273  3332 I jxcore-log: 
03-24 17:40:41.112  3273  3332 I jxcore-log: ok 192 is stopped after calling stop
03-24 17:40:41.112  3273  3332 I jxcore-log: 
,03-24 17:40:41.118  3273  3332 I jxcore-log: ok 193 connection to servers manager should fail after stopping
03-24 17:40:41.118  3273  3332 I jxcore-log: 
,03-24 17:40:41.123  3273  3332 I jxcore-log: ok 194 connection to router server should fail after stopping
03-24 17:40:41.123  3273  3332 I jxcore-log: 
,03-24 17:40:41.128  3273  3332 I jxcore-log: # teardown
03-24 17:40:41.128  3273  3332 I jxcore-log: 
,03-24 17:40:41.473  3273  3332 I jxcore-log: # setup
03-24 17:40:41.473  3273  3332 I jxcore-log: 
,03-24 17:40:41.770  1265  1265 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 17:40:41.821  1265  1282 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure,
03-24 17:40:41.821  1265  1282 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 17:40:41.821  1265  1282 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 17:40:41.821  1265  1282 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 17:40:41.831  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native,
03-24 17:40:41.831  3273  3332 I jxcore-log: 
,03-24 17:40:41.832  1265  1282 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
03-24 17:40:41.835  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 17:40:41.835  3273  3332 I jxcore-log: 
,03-24 17:40:41.847  3273  3332 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 17:40:41.847  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 17:40:41.847  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 17:40:41.847  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 17:40:41.847  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 17:40:41.847  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 17:40:41.847  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 17:40:41.847  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 17:40:41.851  3273  3332 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 17:40:41.854  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 17:40:41.854  3273  3332 I jxcore-log: 
,03-24 17:40:41.855  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 17:40:41.855  3273  3332 I jxcore-log: 
,03-24 17:40:41.858  3273  3332 I jxcore-log: # 49. make sure terminateConnection is properly hooked up
03-24 17:40:41.858  3273  3332 I jxcore-log: 
,03-24 17:40:41.860  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 17:40:41.860  3273  3332 I jxcore-log: 
,03-24 17:40:41.864  3683  3683 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
03-24 17:40:41.865  3683  3683 D Finsky  : [1] 5.onFinished: Installation state replication failed.
03-24 17:40:41.866  3683  3683 D Finsky  : [1] 5.onFinished: Scheduling replication attempt 5.
,03-24 17:40:42.024  3273  3332 I jxcore-log: ok 195 called with right arguments
03-24 17:40:42.024  3273  3332 I jxcore-log: 
,03-24 17:40:42.027  3273  3332 I jxcore-log: # teardown
03-24 17:40:42.027  3273  3332 I jxcore-log: 
,03-24 17:40:42.224  3273  3332 I jxcore-log: # setup
03-24 17:40:42.224  3273  3332 I jxcore-log: 
,03-24 17:40:42.370  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 17:40:42.370  3273  3332 I jxcore-log: 
,03-24 17:40:42.375  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 17:40:42.375  3273  3332 I jxcore-log: 
,03-24 17:40:42.388  3273  3332 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 17:40:42.388  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 17:40:42.388  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 17:40:42.388  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 17:40:42.388  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 17:40:42.388  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 17:40:42.388  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 17:40:42.388  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 17:40:42.390  3273  3332 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 17:40:42.392  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 17:40:42.392  3273  3332 I jxcore-log: 
,03-24 17:40:42.393  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 17:40:42.393  3273  3332 I jxcore-log: 
,03-24 17:40:42.396  3273  3332 I jxcore-log: # 50. make sure terminateListener is properly hooked up
03-24 17:40:42.396  3273  3332 I jxcore-log: 
,03-24 17:40:42.398  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 17:40:42.398  3273  3332 I jxcore-log: 
,03-24 17:40:42.728  3273  3332 I jxcore-log: ok 196 called with right arguments
,03-24 17:40:42.728  3273  3332 I jxcore-log: 
,03-24 17:40:42.730  3273  3332 I jxcore-log: # teardown
03-24 17:40:42.730  3273  3332 I jxcore-log: 
,03-24 17:40:42.893  3273  3332 I jxcore-log: # setup
03-24 17:40:42.893  3273  3332 I jxcore-log: 
,03-24 17:40:43.104  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 17:40:43.104  3273  3332 I jxcore-log: 
03-24 17:40:43.105  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 17:40:43.105  3273  3332 I jxcore-log: 
,03-24 17:40:43.112  3273  3332 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 17:40:43.112  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 17:40:43.112  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 17:40:43.112  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 17:40:43.112  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 17:40:43.112  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 17:40:43.112  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 17:40:43.112  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 17:40:43.114  3273  3332 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 17:40:43.116  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 17:40:43.116  3273  3332 I jxcore-log: 
,03-24 17:40:43.117  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 17:40:43.117  3273  3332 I jxcore-log: 
03-24 17:40:43.120  3273  3332 I jxcore-log: # 51. make sure we actually call kill connections properly
03-24 17:40:43.120  3273  3332 I jxcore-log: 
03-24 17:40:43.121  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 17:40:43.121  3273  3332 I jxcore-log: 
,03-24 17:40:43.280  3273  3332 I jxcore-log: ok 197 specific error expected
03-24 17:40:43.280  3273  3332 I jxcore-log: 
,03-24 17:40:43.284  3273  3332 I jxcore-log: # teardown
03-24 17:40:43.284  3273  3332 I jxcore-log: 
,03-24 17:40:43.404  3273  3332 I jxcore-log: # setup
03-24 17:40:43.404  3273  3332 I jxcore-log: 
,03-24 17:40:43.605  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 17:40:43.605  3273  3332 I jxcore-log: 
,03-24 17:40:43.606  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 17:40:43.606  3273  3332 I jxcore-log: 
,03-24 17:40:43.612  3273  3332 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 17:40:43.612  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 17:40:43.612  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 17:40:43.612  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 17:40:43.612  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 17:40:43.612  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 17:40:43.612  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
,03-24 17:40:43.612  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-24 17:40:43.615  3273  3332 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 17:40:43.617  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 17:40:43.617  3273  3332 I jxcore-log: 
,03-24 17:40:43.618  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 17:40:43.618  3273  3332 I jxcore-log: 
,03-24 17:40:43.621  3273  3332 I jxcore-log: # 52. thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
03-24 17:40:43.621  3273  3332 I jxcore-log: 
,03-24 17:40:43.623  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 17:40:43.623  3273  3332 I jxcore-log: 
,03-24 17:40:43.855  3273  3332 I jxcore-log: DEBUG createNativeListener: creating native server
,03-24 17:40:43.855  3273  3332 I jxcore-log: 
,03-24 17:40:43.858  3273  3332 I jxcore-log: DEBUG createNativeListener: listening 50347,
03-24 17:40:43.858  3273  3332 I jxcore-log: 
,03-24 17:40:43.865  3273  3332 I jxcore-log: INFO thaliMobileNativeWrapper: routerPortConnectionFailed - {"routerPort":38500,"error":{}}
03-24 17:40:43.865  3273  3332 I jxcore-log: ,
03-24 17:40:43.866  3273  3332 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-24 17:40:43.866  3273  3332 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 17:40:43.866  3273  3332 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 17:40:43.869  3273  3332 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 17:40:43.869  3273  3332 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-24 17:40:43.869  3273  3332 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 17:40:43.880  3273  3332 I jxcore-log: ok 198 failure reason is as expected
03-24 17:40:43.880  3273  3332 I jxcore-log: ,
03-24 17:40:43.881  3273  3332 I jxcore-log: ok 199 error description is as expected
03-24 17:40:43.881  3273  3332 I jxcore-log: 
,03-24 17:40:43.881  3273  3332 I jxcore-log: ok 200 must be stopped
03-24 17:40:43.881  3273  3332 I jxcore-log: 
,03-24 17:40:43.889  3273  3332 I jxcore-log: # teardown
,03-24 17:40:43.889  3273  3332 I jxcore-log: 
,03-24 17:40:43.997  2157  2223 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 17:40:44.075  3273  3332 I jxcore-log: # setup
03-24 17:40:44.075  3273  3332 I jxcore-log: 
,03-24 17:40:44.291  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 17:40:44.291  3273  3332 I jxcore-log: 
,03-24 17:40:44.294  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 17:40:44.294  3273  3332 I jxcore-log: 
,03-24 17:40:44.302  3273  3332 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 17:40:44.302  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 17:40:44.302  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 17:40:44.302  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 17:40:44.302  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 17:40:44.302  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 17:40:44.302  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 17:40:44.302  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 17:40:44.305  3273  3332 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 17:40:44.306  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 17:40:44.306  3273  3332 I jxcore-log: 
03-24 17:40:44.307  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 17:40:44.307  3273  3332 I jxcore-log: 
,03-24 17:40:44.309  3273  3332 I jxcore-log: # 53. We repeat failedConnection event when we get it from thaliTcpServersManager
03-24 17:40:44.309  3273  3332 I jxcore-log: 
,03-24 17:40:44.311  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 17:40:44.311  3273  3332 I jxcore-log: 
,03-24 17:40:44.538  3273  3332 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 17:40:44.538  3273  3332 I jxcore-log: 
,03-24 17:40:44.540  3273  3332 I jxcore-log: DEBUG createNativeListener: listening 53643
03-24 17:40:44.540  3273  3332 I jxcore-log: 
,03-24 17:40:44.544  3273  3332 I jxcore-log: ok 201 peerIdentifier matches
03-24 17:40:44.544  3273  3332 I jxcore-log: 
,03-24 17:40:44.544  3273  3332 I jxcore-log: ok 202 error description matches
03-24 17:40:44.544  3273  3332 I jxcore-log: 
03-24 17:40:44.547  3273  3332 I jxcore-log: # teardown
03-24 17:40:44.547  3273  3332 I jxcore-log: 
,03-24 17:40:44.773  3273  3332 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections,
03-24 17:40:44.773  3273  3332 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-24 17:40:44.773  3273  3332 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
03-24 17:40:44.775  3273  3332 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 17:40:44.775  3273  3332 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 17:40:44.775  3273  3332 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 17:40:44.784  3273  3332 I jxcore-log: # setup
03-24 17:40:44.784  3273  3332 I jxcore-log: 
,03-24 17:40:44.893  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 17:40:44.893  3273  3332 I jxcore-log: 
03-24 17:40:44.895  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 17:40:44.895  3273  3332 I jxcore-log: 
,03-24 17:40:44.903  3273  3332 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 17:40:44.903  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 17:40:44.903  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 17:40:44.903  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 17:40:44.903  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 17:40:44.903  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 17:40:44.903  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 17:40:44.903  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 17:40:44.906  3273  3332 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 17:40:44.908  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 17:40:44.908  3273  3332 I jxcore-log: 
,03-24 17:40:44.911  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 17:40:44.911  3273  3332 I jxcore-log: 
,03-24 17:40:44.914  3273  3332 I jxcore-log: # 54. we successfully receive and replay discoveryAdvertisingStateUpdate
03-24 17:40:44.914  3273  3332 I jxcore-log: 
,03-24 17:40:44.916  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 17:40:44.916  3273  3332 I jxcore-log: 
,03-24 17:40:45.101  3273  3332 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 17:40:45.101  3273  3332 I jxcore-log: 
,03-24 17:40:45.104  3273  3332 I jxcore-log: DEBUG createNativeListener: listening 39901
03-24 17:40:45.104  3273  3332 I jxcore-log: 
,03-24 17:40:45.110  3273  3332 I io.jxcore.node.ConnectionHelper: start: Port number: 57264, start advertisements: false
,03-24 17:40:45.110  3273  3332 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 17:40:45.110  3273  3332 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 17:40:45.111  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-24 17:40:45.114  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-24 17:40:45.114  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 17:40:45.114  3273  3332 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 17:40:45.120  2157  2222 D BtGatt.GattService: registerClient() - UUID=5ef3e946-52ee-4bcd-a276-652b2f6b6e12
,03-24 17:40:45.121  2157  2220 D BtGatt.GattService: onClientRegistered() - UUID=5ef3e946-52ee-4bcd-a276-652b2f6b6e12, clientIf=5
03-24 17:40:45.121  3273  3327 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 17:40:45.121  2157  2172 D BtGatt.GattService: start scan with filters
,03-24 17:40:45.123  2157  2231 D BtGatt.ScanManager: handling starting scan
,03-24 17:40:45.125  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 17:40:45.125  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 17:40:45.125  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,03-24 17:40:45.125  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-24 17:40:45.125  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
,03-24 17:40:45.125  3273  3273 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-24 17:40:45.126  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 17:40:45.126   823  1151 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 17:40:45.130  2157  2220 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 17:40:45.130  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:40:45.132  2157  2220 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,03-24 17:40:45.132  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:40:45.132  2157  2231 D BtGatt.ScanManager: Starting BLE batch scan
03-24 17:40:45.132  2157  2231 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-24 17:40:45.134  2157  2220 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 17:40:45.134  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 17:40:45.136  2157  2220 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 17:40:45.136  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 17:40:45.137  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 17:40:45.138  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 17:40:45.138  3273  3332 I io.jxcore.node.ConnectionHelper: start: OK
03-24 17:40:45.138  3273  3273 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,03-24 17:40:45.138  3273  3273 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 17:40:45.139  3273  3273 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-24 17:40:45.143  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 17:40:45.143  3273  3332 I jxcore-log: 
,03-24 17:40:45.146  3273  3332 I jxcore-log: ok 203 discoveryActive matches
03-24 17:40:45.146  3273  3332 I jxcore-log: 
,03-24 17:40:45.147  3273  3332 I jxcore-log: ok 204 advertisingActive matches
03-24 17:40:45.147  3273  3332 I jxcore-log: 
,03-24 17:40:45.150  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 17:40:45.150  3273  3332 I jxcore-log: 
,03-24 17:40:45.158  3273  3332 I jxcore-log: not ok 205 discoveryActive matches
03-24 17:40:45.158  3273  3332 I jxcore-log: 
03-24 17:40:45.158  3273  3332 I jxcore-log:   ---
,03-24 17:40:45.158  3273  3332 I jxcore-log: 
03-24 17:40:45.158  3273  3332 I jxcore-log:     operator: equal
03-24 17:40:45.158  3273  3332 I jxcore-log: 
03-24 17:40:45.158  3273  3332 I jxcore-log:     expected: false
03-24 17:40:45.158  3273  3332 I jxcore-log: 
,03-24 17:40:45.158  3273  3332 I jxcore-log:     actual:   true
03-24 17:40:45.158  3273  3332 I jxcore-log: 
03-24 17:40:45.159  3273  3332 I jxcore-log:   ...
03-24 17:40:45.159  3273  3332 I jxcore-log: 
03-24 17:40:45.159  3273  3332 I jxcore-log: ok 206 advertisingActive matches
03-24 17:40:45.159  3273  3332 I jxcore-log: 
,03-24 17:40:45.161  3273  3332 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-24 17:40:45.161  3273  3332 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
03-24 17:40:45.161  3273  3332 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,03-24 17:40:45.161  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-24 17:40:45.161  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-24 17:40:45.162  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 17:40:45.162  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 17:40:45.162  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser,
03-24 17:40:45.162  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-24 17:40:45.163  2157  2172 D BtGatt.GattService: stopScan() - queue size =1
03-24 17:40:45.165  2157  2172 D BtGatt.GattService: unregisterClient() - clientIf=5
03-24 17:40:45.166  2157  2220 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16,
03-24 17:40:45.166  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:40:45.166  2157  2231 D BtGatt.ScanManager: stopping BLe Batch
03-24 17:40:45.166  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 17:40:45.166  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 17:40:45.166  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-24 17:40:45.166  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-24 17:40:45.166  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED],
03-24 17:40:45.167  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 17:40:45.168  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 17:40:45.168  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,03-24 17:40:45.168  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-24 17:40:45.169  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,03-24 17:40:45.169  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 17:40:45.169  3273  3273 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
03-24 17:40:45.169  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 17:40:45.169  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-24 17:40:45.169  2157  2220 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 17:40:45.169  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:40:45.171  2157  2231 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 17:40:45.173  2157  2220 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 17:40:45.173  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:40:45.174  3273  3273 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-24 17:40:45.175   823  1446 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 17:40:45.180  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-24 17:40:45.181  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 17:40:45.181  3273  3273 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 17:40:45.184  3273  3273 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 17:40:45.184  3273  3273 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-24 17:40:45.184  3273  3273 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 17:40:45.185  3273  3273 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 17:40:45.186  3273  3332 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 17:40:45.186  3273  3332 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 17:40:45.186  3273  3332 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 17:40:45.188  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 17:40:45.188  3273  3332 I jxcore-log: 
03-24 17:40:45.189  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 17:40:45.189  3273  3332 I jxcore-log: 
,03-24 17:40:45.202  3273  3332 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 17:40:45.202  3273  3332 I jxcore-log: 
,03-24 17:40:45.205  3273  3332 I jxcore-log: DEBUG createNativeListener: listening 48458
03-24 17:40:45.205  3273  3332 I jxcore-log: 
,03-24 17:40:45.210  3273  3332 I io.jxcore.node.ConnectionHelper: start: Port number: 48458, start advertisements: true
,03-24 17:40:45.210  3273  3332 V io.jxcore.node.ConnectivityMonitor: start: Already started,
03-24 17:40:45.210  3273  3332 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-24 17:40:45.210  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-24 17:40:45.214  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser,
03-24 17:40:45.214  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 17:40:45.214  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-24 17:40:45.214  3273  3332 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 17:40:45.218  2157  2222 D BtGatt.GattService: registerClient() - UUID=09ebf8d1-31fd-4d38-8a8b-45c06e0c1ff9,
,03-24 17:40:45.218  2157  2220 D BtGatt.GattService: onClientRegistered() - UUID=09ebf8d1-31fd-4d38-8a8b-45c06e0c1ff9, clientIf=5
,03-24 17:40:45.218  3273  3327 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 17:40:45.218  2157  2172 D BtGatt.GattService: start scan with filters
03-24 17:40:45.219  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 17:40:45.219  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true,
03-24 17:40:45.219  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-24 17:40:45.220  2157  2231 D BtGatt.ScanManager: handling starting scan
03-24 17:40:45.220  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,03-24 17:40:45.220  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 17:40:45.220  3273  3273 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 17:40:45.221  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,03-24 17:40:45.221  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 17:40:45.221  3273  3332 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 17:40:45.222  2157  2220 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 17:40:45.222  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
03-24 17:40:45.223  3273  3332 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 17:40:45.223  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 17:40:45.223  3273  3332 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...,
03-24 17:40:45.223  2157  2220 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 17:40:45.224  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:40:45.224  2157  2231 D BtGatt.ScanManager: Starting BLE batch scan
,03-24 17:40:45.224  2157  2231 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 17:40:45.226  2157  2220 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,03-24 17:40:45.226  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:40:45.228  2157  2220 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,03-24 17:40:45.228  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:40:45.230  2157  2173 D BtGatt.GattService: registerClient() - UUID=16e3fbae-97d5-400a-a5cb-5d45ff2bc294
03-24 17:40:45.230  2157  2220 D BtGatt.GattService: onClientRegistered() - UUID=16e3fbae-97d5-400a-a5cb-5d45ff2bc294, clientIf=6
03-24 17:40:45.231  3273  3291 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-24 17:40:45.232  2157  2230 D BtGatt.AdvertiseManager: message : 0
,03-24 17:40:45.235  2157  2230 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 17:40:45.238  2157  2220 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0,
03-24 17:40:45.240  2157  2220 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 17:40:45.240  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-24 17:40:45.240  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-24 17:40:45.241   823  1404 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 17:40:45.244  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-24 17:40:45.244  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 17:40:45.244  3273  3332 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-24 17:40:45.244  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-24 17:40:45.245  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-24 17:40:45.245  3273  3332 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-24 17:40:45.245  3273  3332 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-24 17:40:45.245  3273  3332 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,03-24 17:40:45.246  3273  3273 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-24 17:40:45.246  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 17:40:45.246  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-24 17:40:45.246  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-24 17:40:45.246  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-24 17:40:45.246  3273  3273 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
,03-24 17:40:45.246  3273  3273 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-24 17:40:45.246  3273  3273 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 17:40:45.246  3273  3273 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-24 17:40:45.246  3273  3273 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 17:40:45.247  3273  3273 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-24 17:40:45.247  3273  3273 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-24 17:40:45.247  3273  3332 I io.jxcore.node.ConnectionHelper: start: OK
03-24 17:40:45.248   823   838 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 17:40:45.250  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 17:40:45.250  3273  3332 I jxcore-log: 
03-24 17:40:45.250  3273  3866 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback,
03-24 17:40:45.253  3273  3866 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-24 17:40:45.258  3273  3332 I jxcore-log: not ok 207 discoveryActive matches
03-24 17:40:45.258  3273  3332 I jxcore-log: 
03-24 17:40:45.258  3273  3332 I jxcore-log:   ---
03-24 17:40:45.258  3273  3332 I jxcore-log: 
03-24 17:40:45.259  3273  3332 I jxcore-log:     operator: equal
03-24 17:40:45.259  3273  3332 I jxcore-log: 
03-24 17:40:45.259  3273  3332 I jxcore-log:     expected: false
03-24 17:40:45.259  3273  3332 I jxcore-log: 
03-24 17:40:45.259  3273  3332 I jxcore-log:     actual:   true
03-24 17:40:45.259  3273  3332 I jxcore-log: 
03-24 17:40:45.259  3273  3332 I jxcore-log:   ...
03-24 17:40:45.259  3273  3332 I jxcore-log: 
,03-24 17:40:45.263  3273  3332 I jxcore-log: not ok 208 advertisingActive matches
03-24 17:40:45.263  3273  3332 I jxcore-log: 
03-24 17:40:45.263  3273  3332 I jxcore-log:   ---
03-24 17:40:45.263  3273  3332 I jxcore-log: 
,03-24 17:40:45.263  3273  3332 I jxcore-log:     operator: equal
03-24 17:40:45.263  3273  3332 I jxcore-log: 
03-24 17:40:45.263  3273  3332 I jxcore-log:     expected: true
03-24 17:40:45.263  3273  3332 I jxcore-log: 
03-24 17:40:45.263  3273  3332 I jxcore-log:     actual:   false
03-24 17:40:45.263  3273  3332 I jxcore-log: 
03-24 17:40:45.263  3273  3332 I jxcore-log:   ...
03-24 17:40:45.263  3273  3332 I jxcore-log: 
,03-24 17:40:45.265  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 17:40:45.265  3273  3332 I jxcore-log: 
,03-24 17:40:45.269  3273  3332 I jxcore-log: not ok 209 discoveryActive matches
03-24 17:40:45.269  3273  3332 I jxcore-log: 
,03-24 17:40:45.269  3273  3332 I jxcore-log:   ---
03-24 17:40:45.269  3273  3332 I jxcore-log: 
03-24 17:40:45.269  3273  3332 I jxcore-log:     operator: equal
03-24 17:40:45.269  3273  3332 I jxcore-log: 
03-24 17:40:45.269  3273  3332 I jxcore-log:     expected: false
03-24 17:40:45.269  3273  3332 I jxcore-log: 
03-24 17:40:45.269  3273  3332 I jxcore-log:     actual:   true
03-24 17:40:45.269  3273  3332 I jxcore-log: 
03-24 17:40:45.269  3273  3332 I jxcore-log:   ...
03-24 17:40:45.269  3273  3332 I jxcore-log: 
,03-24 17:40:45.269  3273  3332 I jxcore-log: ok 210 advertisingActive matches
03-24 17:40:45.269  3273  3332 I jxcore-log: 
03-24 17:40:45.271  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-24 17:40:45.271  3273  3332 I jxcore-log: 
,03-24 17:40:45.273  3273  3332 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 17:40:45.273  3273  3332 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
,03-24 17:40:45.273  3273  3332 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-24 17:40:45.273  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-24 17:40:45.273  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown,
,03-24 17:40:45.273  3273  3332 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-24 17:40:45.273  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-24 17:40:45.273  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...,
03-24 17:40:45.273  3273  3866 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-24 17:40:45.273  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart,
03-24 17:40:45.273  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode,
03-24 17:40:45.273  3273  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-24 17:40:45.273  3273  3866 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-24 17:40:45.274  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-24 17:40:45.274  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-24 17:40:45.275  2157  2222 D BtGatt.GattService: stopScan() - queue size =1
,03-24 17:40:45.277  2157  2172 D BtGatt.GattService: unregisterClient() - clientIf=5
03-24 17:40:45.278  2157  2220 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,03-24 17:40:45.278  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
03-24 17:40:45.278  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 17:40:45.278  2157  2231 D BtGatt.ScanManager: stopping BLe Batch
03-24 17:40:45.278  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 17:40:45.279  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,03-24 17:40:45.279  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-24 17:40:45.279  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-24 17:40:45.279  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 17:40:45.279  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-24 17:40:45.280  2157  2230 D BtGatt.AdvertiseManager: message : 1
03-24 17:40:45.281  2157  2220 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 17:40:45.281  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:40:45.281  2157  2230 D BtGatt.AdvertiseManager: stop advertise for client 6
03-24 17:40:45.281  2157  2231 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 17:40:45.282  2157  2220 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 17:40:45.283  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:40:45.284  2157  2220 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 17:40:45.285  2157  2220 D BtGatt.GattService: Client app is not null!
03-24 17:40:45.286  2157  2172 D BtGatt.GattService: unregisterClient() - clientIf=6
03-24 17:40:45.287  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 17:40:45.287  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-24 17:40:45.287  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-24 17:40:45.287  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,03-24 17:40:45.287  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-24 17:40:45.287  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 17:40:45.287  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 17:40:45.287  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-24 17:40:45.288  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-24 17:40:45.288  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 17:40:45.288  3273  3273 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 17:40:45.288  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 17:40:45.288  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-24 17:40:45.294  3273  3273 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-24 17:40:45.295   823  1413 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 17:40:45.301  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-24 17:40:45.302  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 17:40:45.302  3273  3273 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-24 17:40:45.302  3273  3273 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-24 17:40:45.302  3273  3273 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 17:40:45.306  3273  3273 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-24 17:40:45.306  3273  3273 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 17:40:45.306  3273  3273 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 17:40:45.306  3273  3273 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 17:40:45.306  3273  3273 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 17:40:45.306  3273  3273 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-24 17:40:45.307  3273  3332 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 17:40:45.307  3273  3332 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 17:40:45.307  3273  3332 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 17:40:45.309  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-24 17:40:45.309  3273  3332 I jxcore-log: 
03-24 17:40:45.310  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 17:40:45.310  3273  3332 I jxcore-log: 
03-24 17:40:45.311  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 17:40:45.311  3273  3332 I jxcore-log: 
,03-24 17:40:45.320  3273  3332 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 17:40:45.320  3273  3332 I jxcore-log: 
,03-24 17:40:45.323  3273  3332 I jxcore-log: DEBUG createNativeListener: listening 34660
03-24 17:40:45.323  3273  3332 I jxcore-log: 
,03-24 17:40:45.329  3273  3332 I jxcore-log: # teardown
03-24 17:40:45.329  3273  3332 I jxcore-log: 
,03-24 17:40:45.766  3273  3332 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 17:40:45.766  3273  3332 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 17:40:45.766  3273  3332 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 17:40:45.771  3273  3332 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements,
03-24 17:40:45.771  3273  3332 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 17:40:45.771  3273  3332 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
,03-24 17:40:45.793  3273  3332 I jxcore-log: # setup
03-24 17:40:45.793  3273  3332 I jxcore-log: ,
,03-24 17:40:45.946  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,03-24 17:40:45.946  3273  3332 I jxcore-log: 
,03-24 17:40:45.951  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 17:40:45.951  3273  3332 I jxcore-log: 
,03-24 17:40:45.960  3273  3332 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 17:40:45.960  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 17:40:45.960  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 17:40:45.960  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 17:40:45.960  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 17:40:45.960  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 17:40:45.960  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 17:40:45.960  3273  3332 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 17:40:45.964  3273  3332 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 17:40:45.965  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 17:40:45.965  3273  3332 I jxcore-log: 
,03-24 17:40:45.967  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 17:40:45.967  3273  3332 I jxcore-log: 
03-24 17:40:45.969  3273  3332 I jxcore-log: # 55. can do HTTP requests between peers
03-24 17:40:45.969  3273  3332 I jxcore-log: 
,03-24 17:40:45.971  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 17:40:45.971  3273  3332 I jxcore-log: 
,03-24 17:40:46.100  3273  3332 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 17:40:46.100  3273  3332 I jxcore-log: 
,03-24 17:40:46.102  3273  3332 I jxcore-log: DEBUG createNativeListener: listening 42166
03-24 17:40:46.102  3273  3332 I jxcore-log: 
,03-24 17:40:46.108  3273  3332 I io.jxcore.node.ConnectionHelper: start: Port number: 48458, start advertisements: false
,03-24 17:40:46.108  3273  3332 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 17:40:46.108  3273  3332 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 17:40:46.108  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-24 17:40:46.115  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-24 17:40:46.115  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-24 17:40:46.115  3273  3332 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 17:40:46.121  2157  2173 D BtGatt.GattService: registerClient() - UUID=4350246c-0f91-4091-bc3f-9b5e69083bf1
,03-24 17:40:46.122  2157  2220 D BtGatt.GattService: onClientRegistered() - UUID=4350246c-0f91-4091-bc3f-9b5e69083bf1, clientIf=5
,03-24 17:40:46.123  3273  3292 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-24 17:40:46.124  2157  2222 D BtGatt.GattService: start scan with filters
,03-24 17:40:46.125  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 17:40:46.125  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 17:40:46.125  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-24 17:40:46.125  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-24 17:40:46.125  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 17:40:46.125  2157  2231 D BtGatt.ScanManager: handling starting scan
,03-24 17:40:46.126  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 17:40:46.126  3273  3273 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 17:40:46.128   823  1417 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 17:40:46.141  2157  2220 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,03-24 17:40:46.142  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:40:46.142  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 17:40:46.142  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-24 17:40:46.143  3273  3332 I io.jxcore.node.ConnectionHelper: start: OK
03-24 17:40:46.143  3273  3273 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 17:40:46.143  3273  3273 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 17:40:46.144  3273  3273 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 17:40:46.144  2157  2220 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,03-24 17:40:46.144  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:40:46.145  2157  2231 D BtGatt.ScanManager: Starting BLE batch scan
03-24 17:40:46.145  2157  2231 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-24 17:40:46.147  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 17:40:46.147  3273  3332 I jxcore-log: 
03-24 17:40:46.147  2157  2220 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 17:40:46.147  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 17:40:46.149  2157  2220 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 17:40:46.149  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 17:40:46.156  3273  3332 I io.jxcore.node.ConnectionHelper: start: Port number: 42166, start advertisements: true
,03-24 17:40:46.156  3273  3332 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 17:40:46.156  3273  3332 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-24 17:40:46.156  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-24 17:40:46.162  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser,
03-24 17:40:46.162  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
03-24 17:40:46.162  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 17:40:46.163  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,03-24 17:40:46.163  3273  3332 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 17:40:46.163  3273  3332 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 17:40:46.163  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 17:40:46.163  3273  3332 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-24 17:40:46.171  2157  2172 D BtGatt.GattService: registerClient() - UUID=899b3ea4-242e-4c90-857f-54622e1f237a,
03-24 17:40:46.172  2157  2220 D BtGatt.GattService: onClientRegistered() - UUID=899b3ea4-242e-4c90-857f-54622e1f237a, clientIf=6
,03-24 17:40:46.172  3273  3327 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-24 17:40:46.174  2157  2230 D BtGatt.AdvertiseManager: message : 0
,03-24 17:40:46.180  2157  2230 D BtGatt.AdvertiseManager: starting multi advertising,
,03-24 17:40:46.184  2157  2220 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 17:40:46.187  2157  2220 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 17:40:46.188  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 17:40:46.188  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-24 17:40:46.189  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-24 17:40:46.189  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-24 17:40:46.189  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-24 17:40:46.189  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-24 17:40:46.189   823   839 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 17:40:46.189  3273  3273 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-24 17:40:46.194  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 17:40:46.194  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-24 17:40:46.194  3273  3332 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-24 17:40:46.194  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 17:40:46.194  3273  3273 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 17:40:46.195  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-24 17:40:46.196  3273  3332 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,03-24 17:40:46.196  3273  3332 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-24 17:40:46.196  3273  3332 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK,
03-24 17:40:46.196  3273  3332 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 17:40:46.196  3273  3273 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-24 17:40:46.196  3273  3273 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 17:40:46.197  3273  3273 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,03-24 17:40:46.199   823  1446 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 17:40:46.201  3273  3867 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-24 17:40:46.205  3273  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-24 17:40:46.219  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 17:40:46.219  3273  3332 I jxcore-log: 
,03-24 17:40:46.221  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-24 17:40:46.221  3273  3332 I jxcore-log: 
,03-24 17:40:47.158  2157  2157 D BtGatt.ScanManager: awakened up at time 286586
,03-24 17:40:47.159  2157  2231 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5,
,03-24 17:40:47.168  2157  2220 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,03-24 17:40:47.168  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:40:47.168  2157  2220 D BtGatt.GattService: current time is 286596190721
,03-24 17:40:47.168  2157  2220 D BtGatt.GattService: Batch record : [-42, 49, -79, 50, -25, 96, 1, -128, -78, 3, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -58, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
,03-24 17:40:47.169  2157  2220 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 17:40:47.170  2157  2220 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
,03-24 17:40:47.171  3273  3273 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> E0:DB:10:14:E2:C0], added - the peer count is 1
03-24 17:40:47.172  3273  3273 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 2,
03-24 17:40:47.172  3273  3273 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> E0:DB:10:14:E2:C0], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 
,03-24 17:40:47.173  3273  3273 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
03-24 17:40:47.175  3273  3332 I jxcore-log: DEBUG createPeerListener: createPeerListener
03-24 17:40:47.175  3273  3332 I jxcore-log: 
,03-24 17:40:47.178  3273  3332 I jxcore-log: DEBUG createPeerListener: pleaseConnect= false
,03-24 17:40:47.178  3273  3332 I jxcore-log: 
,03-24 17:40:47.180  3273  3332 I jxcore-log: ok 211 found a peer! {"peerIdentifier":"E0:DB:10:14:E2:C0","portNumber":51916,"hostAddress":"127.0.0.1"}
,03-24 17:40:47.180  3273  3332 I jxcore-log: 
,03-24 17:40:47.191  3273  3332 I jxcore-log: DEBUG createPeerListener: first connection
03-24 17:40:47.191  3273  3332 I jxcore-log: 
,03-24 17:40:47.196  3273  3332 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID E0:DB:10:14:E2:C0
,03-24 17:40:47.196  3273  3332 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> E0:DB:10:14:E2:C0]
03-24 17:40:47.197  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to Note4-1 in address E0:DB:10:14:E2:C0
,03-24 17:40:47.197  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
03-24 17:40:47.197  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,03-24 17:40:47.197  3273  3332 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: Note4-1 E0:DB:10:14:E2:C0
03-24 17:40:47.198  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to Note4-1 in address E0:DB:10:14:E2:C0,
03-24 17:40:47.198  3273  3332 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: E0:DB:10:14:E2:C0)
,03-24 17:40:47.200  3273  3868 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address E0:DB:10:14:E2:C0 (thread ID: 380),
03-24 17:40:47.200  3273  3868 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback,
,03-24 17:40:47.204  2157  2222 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,03-24 17:40:47.204  3273  3332 I jxcore-log: DEBUG createPeerListener: createPeerListener
03-24 17:40:47.204  3273  3332 I jxcore-log: 
,03-24 17:40:47.209  3273  3332 I jxcore-log: DEBUG createPeerListener: pleaseConnect= false
03-24 17:40:47.209  3273  3332 I jxcore-log: 
,03-24 17:40:49.909  2157  2233 W bt-btif : info:x10
,03-24 17:40:49.910  2157  2220 D         : remote version info [e0:db:10:14:e2:c0]: 7, f, 6109
,03-24 17:40:49.946  1538  1538 I BTConnectionReceiver: onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,03-24 17:40:49.951  1538  1538 I BluetoothClassifier: Bluetooth Device Name: Note4-1
,03-24 17:40:49.965  2157  2233 W bt-sdp  : process_service_search_attr_rsp
,03-24 17:40:50.048  2157  2233 W bt-btif : new conn_srvc id:26, app_id:1
,03-24 17:40:50.048  2157  2233 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:1
03-24 17:40:50.048  2157  2233 W bt-btif : bta_dm_pm_ssr:2, lat:1200
,03-24 17:40:50.048  3273  3868 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onSocketConnected: [<no peer name> E0:DB:10:14:E2:C0] (thread ID: 380)
03-24 17:40:50.049  3273  3868 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 380)
03-24 17:40:50.050  3273  3868 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesWritten: 15 bytes successfully written (thread ID: 381)
03-24 17:40:50.050  3273  3868 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Outgoing connection initialized (*handshake* thread ID: 381)
,03-24 17:40:50.050  3273  3868 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 380)
03-24 17:40:50.053  3273  3869 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 381)
,03-24 17:40:50.074  3273  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesRead: Read 15 bytes successfully (thread ID: 381)
,03-24 17:40:50.078  3273  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Handshake succeeded with [<no peer name> E0:DB:10:14:E2:C0]
,03-24 17:40:50.078  3273  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onHandshakeSucceeded: [<no peer name> E0:DB:10:14:E2:C0] (thread ID: 380)
03-24 17:40:50.078  3273  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: handleSuccessfulClientThread: [<no peer name> E0:DB:10:14:E2:C0] (thread ID: 380)
,03-24 17:40:50.079  3273  3273 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> E0:DB:10:14:E2:C0]
,03-24 17:40:50.079  3273  3273 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing connection to peer [<no peer name> E0:DB:10:14:E2:C0]
03-24 17:40:50.079  3273  3273 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> E0:DB:10:14:E2:C0] updated - the peer count is 2
03-24 17:40:50.080  3273  3273 I io.jxcore.node.ConnectionHelper: lowerBleDiscoveryPowerAndStartResetTimer: Lowering the power settings
,03-24 17:40:50.080  3273  3273 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 2 -> 0
03-24 17:40:50.080  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 17:40:50.080  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 17:40:50.080  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-24 17:40:50.080  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-24 17:40:50.080  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-24 17:40:50.080  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-24 17:40:50.081  3273  3869 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 381)
03-24 17:40:50.087  2157  2230 D BtGatt.AdvertiseManager: message : 1
03-24 17:40:50.089  2157  2230 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-24 17:40:50.094  2157  2220 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 17:40:50.094  2157  2220 D BtGatt.GattService: Client app is not null!
,03-24 17:40:50.097  2157  2173 D BtGatt.GattService: unregisterClient() - clientIf=6
03-24 17:40:50.098  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-24 17:40:50.098  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,03-24 17:40:50.098  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 3, timeout: 0, is connectable: false
03-24 17:40:50.098  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 17:40:50.098  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 17:40:50.099  3273  3273 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 17:40:50.100  3273  3273 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 17:40:50.101  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 17:40:50.101  3273  3273 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-24 17:40:50.110  2157  2222 D BtGatt.GattService: registerClient() - UUID=1d289d38-181e-47b1-b861-675d79a3e6ad
,03-24 17:40:50.110  2157  2220 D BtGatt.GattService: onClientRegistered() - UUID=1d289d38-181e-47b1-b861-675d79a3e6ad, clientIf=6
03-24 17:40:50.110  3273  3291 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-24 17:40:50.112  2157  2230 D BtGatt.AdvertiseManager: message : 0
,03-24 17:40:50.115  2157  2230 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 17:40:50.118  2157  2220 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0,
03-24 17:40:50.120  2157  2220 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 17:40:50.121  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-24 17:40:50.123  2157  2222 D BtGatt.GattService: stopScan() - queue size =1
,03-24 17:40:50.125  2157  2173 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-24 17:40:50.125  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-24 17:40:50.126  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 17:40:50.126  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 17:40:50.126  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 17:40:50.126  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 17:40:50.126  2157  2220 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 17:40:50.126  3273  3273 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-24 17:40:50.126  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:40:50.126  2157  2231 D BtGatt.ScanManager: stopping BLe Batch
03-24 17:40:50.128  2157  2220 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 17:40:50.128  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:40:50.128  2157  2231 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 17:40:50.130  2157  2220 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-24 17:40:50.130  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:40:50.131  2157  2220 D BtGatt.GattService: current time is 289558749106
03-24 17:40:50.131  2157  2220 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -59, 26, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0, -42, 49, -79, 50, -25, 96, 1, -128, -80, 27, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-24 17:40:50.131  2157  2220 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-24 17:40:50.131  2157  2220 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 17:40:50.132  2157  2172 D BtGatt.GattService: registerClient() - UUID=b97639c7-d4f8-4d1c-822e-203a9862dcfb
03-24 17:40:50.132  2157  2220 D BtGatt.GattService: onClientRegistered() - UUID=b97639c7-d4f8-4d1c-822e-203a9862dcfb, clientIf=5
03-24 17:40:50.133  3273  3327 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 17:40:50.133  2157  2172 D BtGatt.GattService: start scan with filters
,03-24 17:40:50.139  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
03-24 17:40:50.139  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-24 17:40:50.139  3273  3273 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 3 -> 1,
,03-24 17:40:50.139  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 17:40:50.139  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 17:40:50.139  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-24 17:40:50.139  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-24 17:40:50.139  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-24 17:40:50.139  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-24 17:40:50.140  2157  2231 D BtGatt.ScanManager: handling starting scan
,03-24 17:40:50.143  2157  2230 D BtGatt.AdvertiseManager: message : 1
03-24 17:40:50.143  2157  2230 D BtGatt.AdvertiseManager: stop advertise for client 6
03-24 17:40:50.145  2157  2220 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 17:40:50.145  2157  2220 D BtGatt.GattService: Client app is not null!
03-24 17:40:50.147  2157  2222 D BtGatt.GattService: unregisterClient() - clientIf=6
03-24 17:40:50.147  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 17:40:50.147  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-24 17:40:50.147  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-24 17:40:50.147  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,03-24 17:40:50.147  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 17:40:50.148  3273  3273 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 17:40:50.148  3273  3273 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 17:40:50.148  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 17:40:50.148  3273  3273 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-24 17:40:50.148  2157  2220 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,03-24 17:40:50.148  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:40:50.150  2157  2220 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 17:40:50.150  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 17:40:50.152  2157  2231 D BtGatt.ScanManager: Starting BLE batch scan
03-24 17:40:50.152  2157  2231 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 17:40:50.154  2157  2220 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 17:40:50.154  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 17:40:50.155  2157  2172 D BtGatt.GattService: registerClient() - UUID=47ae6e5f-c3df-4352-964e-deb56f434a19
03-24 17:40:50.155  2157  2220 D BtGatt.GattService: onClientRegistered() - UUID=47ae6e5f-c3df-4352-964e-deb56f434a19, clientIf=6
03-24 17:40:50.156  2157  2220 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 17:40:50.156  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:40:50.156  3273  3292 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-24 17:40:50.156  2157  2230 D BtGatt.AdvertiseManager: message : 0,
03-24 17:40:50.159  2157  2230 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 17:40:50.161  2157  2220 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0,
,03-24 17:40:50.163  2157  2220 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 17:40:50.164  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-24 17:40:50.165  2157  2172 D BtGatt.GattService: stopScan() - queue size =1,
,03-24 17:40:50.166  2157  2173 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-24 17:40:50.167  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 17:40:50.167  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 17:40:50.167  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 17:40:50.167  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...,
03-24 17:40:50.167  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 17:40:50.167  3273  3273 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-24 17:40:50.167  2157  2220 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16,
03-24 17:40:50.167  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:40:50.168  2157  2231 D BtGatt.ScanManager: stopping BLe Batch
,03-24 17:40:50.170  2157  2220 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 17:40:50.170  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:40:50.170  2157  2231 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 17:40:50.171  2157  2172 D BtGatt.GattService: registerClient() - UUID=528f79d0-8433-44bb-b6e6-cc5c79f8842d
03-24 17:40:50.171  2157  2220 D BtGatt.GattService: onClientRegistered() - UUID=528f79d0-8433-44bb-b6e6-cc5c79f8842d, clientIf=5
03-24 17:40:50.171  3273  3291 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 17:40:50.172  2157  2222 D BtGatt.GattService: start scan with filters
03-24 17:40:50.172  2157  2220 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-24 17:40:50.173  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:40:50.173  2157  2220 D BtGatt.GattService: current time is 289600838637
,03-24 17:40:50.173  2157  2220 D BtGatt.GattService: Batch record : [-42, 49, -79, 50, -25, 96, 1, -128, -79, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -60, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-24 17:40:50.173  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 17:40:50.173  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 17:40:50.173  3273  3273 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 2 -> 0
03-24 17:40:50.173  2157  2220 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81],
03-24 17:40:50.173  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 17:40:50.173  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 17:40:50.173  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-24 17:40:50.173  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-24 17:40:50.173  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-24 17:40:50.173  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-24 17:40:50.173  2157  2220 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-24 17:40:50.176  2157  2230 D BtGatt.AdvertiseManager: message : 1
,03-24 17:40:50.177  2157  2231 D BtGatt.ScanManager: handling starting scan
03-24 17:40:50.177  2157  2230 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-24 17:40:50.180  2157  2220 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 17:40:50.180  2157  2220 D BtGatt.GattService: Client app is not null!
,03-24 17:40:50.180  2157  2222 D BtGatt.GattService: unregisterClient() - clientIf=6
03-24 17:40:50.181  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 17:40:50.181  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-24 17:40:50.181  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-24 17:40:50.181  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,03-24 17:40:50.181  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 17:40:50.181  3273  3273 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 17:40:50.181  3273  3273 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 17:40:50.181  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-24 17:40:50.181  3273  3273 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-24 17:40:50.181  2157  2220 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 17:40:50.182  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:40:50.183  2157  2220 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 17:40:50.183  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:40:50.183  2157  2231 D BtGatt.ScanManager: Starting BLE batch scan
,03-24 17:40:50.183  2157  2231 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-24 17:40:50.185  2157  2173 D BtGatt.GattService: registerClient() - UUID=c8509b2e-9770-49cb-8f69-fae21600cc5d
03-24 17:40:50.185  2157  2220 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 17:40:50.185  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:40:50.185  2157  2220 D BtGatt.GattService: onClientRegistered() - UUID=c8509b2e-9770-49cb-8f69-fae21600cc5d, clientIf=6
03-24 17:40:50.186  3273  3327 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-24 17:40:50.186  2157  2220 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 17:40:50.186  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 17:40:50.187  2157  2230 D BtGatt.AdvertiseManager: message : 0
,03-24 17:40:50.189  2157  2230 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 17:40:50.191  2157  2220 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 17:40:50.194  2157  2220 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 17:40:50.194  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-24 17:40:50.195  2157  2222 D BtGatt.GattService: stopScan() - queue size =1
,03-24 17:40:50.196  2157  2173 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-24 17:40:50.196  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-24 17:40:50.197  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-24 17:40:50.197  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-24 17:40:50.197  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-24 17:40:50.197  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 17:40:50.197  3273  3273 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-24 17:40:50.197  2157  2220 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 17:40:50.197  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:40:50.197  2157  2231 D BtGatt.ScanManager: stopping BLe Batch
03-24 17:40:50.199  2157  2172 D BtGatt.GattService: registerClient() - UUID=dccd3cb5-b567-460c-9891-05e20bb000bf
,03-24 17:40:50.200  2157  2220 D BtGatt.GattService: onClientRegistered() - UUID=dccd3cb5-b567-460c-9891-05e20bb000bf, clientIf=5
03-24 17:40:50.200  3273  3292 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 17:40:50.200  2157  2222 D BtGatt.GattService: start scan with filters
03-24 17:40:50.200  2157  2220 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,03-24 17:40:50.200  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 17:40:50.200  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 17:40:50.200  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:40:50.201  2157  2231 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 17:40:50.201  3273  3273 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing socket thread, for peer [<no peer name> E0:DB:10:14:E2:C0], created successfully
,03-24 17:40:50.201  3273  3273 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 1
03-24 17:40:50.201  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 17:40:50.201  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-24 17:40:50.201  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-24 17:40:50.201  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 17:40:50.201  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 17:40:50.202  2157  2220 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,03-24 17:40:50.202  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:40:50.202  3273  3870 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 382)
,03-24 17:40:50.205  3273  3870 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 35824
,03-24 17:40:50.205  3273  3870 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
03-24 17:40:50.205  2157  2231 D BtGatt.ScanManager: handling starting scan
03-24 17:40:50.205  3273  3870 I io.jxcore.node.ConnectionHelper: onListeningForIncomingConnections: Outgoing connection is using port 35824 (peer ID: E0:DB:10:14:E2:C0)
03-24 17:40:50.205  3273  3870 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "E0:DB:10:14:E2:C0" removed
03-24 17:40:50.207  2157  2220 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 17:40:50.207  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 17:40:50.207  3273  3332 I jxcore-log: DEBUG createPeerListener: forward connection
03-24 17:40:50.207  3273  3332 I jxcore-log: 
,03-24 17:40:50.208  2157  2220 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 17:40:50.208  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:40:50.208  2157  2231 D BtGatt.ScanManager: Starting BLE batch scan
03-24 17:40:50.208  2157  2231 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 17:40:50.209  2157  2220 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 17:40:50.209  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:40:50.210  3273  3870 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 35824
03-24 17:40:50.210  3273  3870 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
03-24 17:40:50.210  3273  3870 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
,03-24 17:40:50.210  3273  3870 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-24 17:40:50.210  3273  3870 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 382)
03-24 17:40:50.210  2157  2220 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 17:40:50.210  3273  3870 D io.jxcore.node.OutgoingSocketThread: Exiting thread (ID: 382)
03-24 17:40:50.210  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:40:50.211  3273  3872 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 384, name: Receiver)
03-24 17:40:50.212  3273  3871 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 383, name: Sender)
,03-24 17:40:50.680  3273  3871 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 383, thread name: Sender)
03-24 17:40:50.680  3273  3871 E io.jxcore.node.OutgoingSocketThread: The sending thread failed with error: Input stream got -1 on read
03-24 17:40:50.680  3273  3871 W io.jxcore.node.ConnectionHelper: onDisconnected: Outgoing connection, peer [<no peer name> E0:DB:10:14:E2:C0] disconnected: Input stream got -1 on read
,03-24 17:40:50.681  3273  3871 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: E0:DB:10:14:E2:C0
03-24 17:40:50.681  3273  3871 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 382)
03-24 17:40:50.681  3273  3871 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 382)
03-24 17:40:50.681  3273  3871 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
03-24 17:40:50.681  3273  3871 D io.jxcore.node.OutgoingSocketThread: close: Stopping receiving thread...
03-24 17:40:50.681  3273  3872 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 384, thread name: Receiver): bt socket closed, read return: -1
,03-24 17:40:50.682  3273  3871 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 384
03-24 17:40:50.682  3273  3872 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 384, name: Receiver)
03-24 17:40:50.682  3273  3871 D io.jxcore.node.OutgoingSocketThread: close: Stopping sending thread...
03-24 17:40:50.682  3273  3871 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 383
03-24 17:40:50.682  3273  3871 D io.jxcore.node.OutgoingSocketThread: closeLocalSocketAndStreams: Closing... (thread ID: 382)
03-24 17:40:50.683  3273  3871 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 382)
03-24 17:40:50.684  3273  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
03-24 17:40:50.684  3273  3871 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 383, name: Sender)
,03-24 17:40:50.695  3273  3332 I jxcore-log: ok 212 server should return 200
03-24 17:40:50.695  3273  3332 I jxcore-log: 
,03-24 17:40:50.700  2157  2233 W bt-btif : bta_jv_rfc_port_to_cb(port_handle:0x18):jv handle:0x0 not FOUND
,03-24 17:40:50.713  3273  3332 I jxcore-log: ok 213 response body should match testData
,03-24 17:40:50.713  3273  3332 I jxcore-log: 
,03-24 17:40:50.721  3273  3332 I jxcore-log: # teardown
,03-24 17:40:50.721  3273  3332 I jxcore-log: 
,03-24 17:40:52.912  2157  2218 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,03-24 17:40:53.614  3452  3874 V KeepSync: Connecting to GoogleApiClient
,03-24 17:40:53.789  1265  1728 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,03-24 17:40:53.790  1265  1728 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-24 17:40:53.790  1265  1728 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 17:40:53.790  1265  1728 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 17:40:53.805  1265  1728 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 17:40:53.843  1814  3876 E ClientConnectionOperation: Handling authorization failure
03-24 17:40:53.843  1814  3876 E ClientConnectionOperation: com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
03-24 17:40:53.843  1814  3876 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
03-24 17:40:53.843  1814  3876 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
03-24 17:40:53.843  1814  3876 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
03-24 17:40:53.843  1814  3876 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
03-24 17:40:53.843  1814  3876 E ClientConnectionOperation: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-24 17:40:53.843  1814  3876 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 17:40:53.843  1814  3876 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 17:40:53.843  1814  3876 E ClientConnectionOperation: 	at java.lang.Thread.run(Thread.java:818)
03-24 17:40:53.843  1814  3876 E ClientConnectionOperation: Caused by: com.google.android.gms.auth.ad: BadAuthentication
03-24 17:40:53.843  1814  3876 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.b(SourceFile:442)
03-24 17:40:53.843  1814  3876 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:365)
03-24 17:40:53.843  1814  3876 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:310)
03-24 17:40:53.843  1814  3876 E ClientConnectionOperation: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
,03-24 17:40:53.843  1814  3876 E ClientConnectionOperation: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
03-24 17:40:53.843  1814  3876 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:30)
03-24 17:40:53.843  1814  3876 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:370)
03-24 17:40:53.843  1814  3876 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:340)
03-24 17:40:53.843  1814  3876 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:319)
03-24 17:40:53.843  1814  3876 E ClientConnectionOperation: 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
03-24 17:40:53.843  1814  3876 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
03-24 17:40:53.843  1814  3876 E ClientConnectionOperation: 	... 7 more
,03-24 17:40:53.850  3452  3874 V KeepSync: GoogleApiClient failed to connect with error code: 4
,03-24 17:40:53.858  3452  3874 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-24 17:40:53.868  3452  3874 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-24 17:40:53.869  3452  3874 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-24 17:40:53.938  1265  2585 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,03-24 17:40:53.938  1265  2585 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 17:40:53.938  1265  2585 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 17:40:53.938  1265  2585 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 17:40:53.944  1265  2585 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 17:40:53.988  3452  3874 E KeepSync: IOException
03-24 17:40:53.988  3452  3874 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
,03-24 17:40:53.988  3452  3874 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
03-24 17:40:53.988  3452  3874 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
03-24 17:40:53.988  3452  3874 E KeepSync: 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
03-24 17:40:53.988  3452  3874 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
03-24 17:40:53.988  3452  3874 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
,03-24 17:40:53.988  3452  3874 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
03-24 17:40:53.988  3452  3874 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
03-24 17:40:53.988  3452  3874 E KeepSync: 	at com.google.android.keep.util.m.a(SourceFile:207)
03-24 17:40:53.988  3452  3874 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
03-24 17:40:53.988  3452  3874 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198),
03-24 17:40:53.988  3452  3874 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
03-24 17:40:53.988  3452  3874 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
03-24 17:40:53.988  3452  3874 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
03-24 17:40:53.988  3452  3874 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
03-24 17:40:53.988  3452  3874 E KeepSync: 	at com.google.android.a,piary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
03-24 17:40:53.988  3452  3874 E KeepSync: 	... 10 more
03-24 17:40:53.988  3452  3874 W KeepSync: Sync result 2
,03-24 17:40:54.001   823   856 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 292951, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-24 17:40:54.049  2157  2233 E bt-btm  : btm_sec_disconnected - Clearing Pending flag,
,03-24 17:40:54.051  2157  2157 D BluetoothMapService: onReceive
,03-24 17:40:54.070  1538  1538 I BTConnectionReceiver: onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,03-24 17:40:54.074  1538  1538 I BluetoothClassifier: Bluetooth Device Name: Note4-1
,03-24 17:40:54.983  2157  2157 D BtGatt.ScanManager: awakened up at time 294411
,03-24 17:40:54.987  2157  2231 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 17:40:54.996  2157  2220 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 17:40:54.996  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 17:40:56.012  2157  2157 D BtGatt.ScanManager: awakened up at time 295439
,03-24 17:40:56.014  2157  2231 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 17:40:56.023  2157  2220 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,03-24 17:40:56.023  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 17:40:57.038  2157  2157 D BtGatt.ScanManager: awakened up at time 296466
,03-24 17:40:57.041  2157  2231 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5,
,03-24 17:40:57.050  2157  2220 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 17:40:57.050  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 17:40:58.067  2157  2157 D BtGatt.ScanManager: awakened up at time 297495
,03-24 17:40:58.069  2157  2231 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 17:40:58.079  2157  2220 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 17:40:58.079  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 17:40:59.095  2157  2157 D BtGatt.ScanManager: awakened up at time 298522
,03-24 17:40:59.098  2157  2231 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 17:40:59.107  2157  2220 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,03-24 17:40:59.107  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 17:41:00.127  2157  2157 D BtGatt.ScanManager: awakened up at time 299554
,03-24 17:41:00.128  2157  2231 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 17:41:00.135  2157  2220 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
03-24 17:41:00.135  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 17:41:01.151  2157  2157 D BtGatt.ScanManager: awakened up at time 300579
,03-24 17:41:01.154  2157  2231 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 17:41:01.164  2157  2220 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,03-24 17:41:01.164  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 17:41:01.961  3374  3880 V GoogleAuthProtoRequest: [344] a.<init>: mAccountName set to: thalitester@gmail.com
,03-24 17:41:02.046  1265  2584 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,03-24 17:41:02.047  1265  2584 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 17:41:02.047  1265  2584 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 17:41:02.047  1265  2584 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 17:41:02.055  1265  2584 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 17:41:02.071  3374  3880 W ExperimentUpdateService: [344] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,03-24 17:41:02.071  3374  3880 W ExperimentUpdateService: [344] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-24 17:41:02.071  3374  3880 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-24 17:41:02.071  3374  3880 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-24 17:41:02.071  3374  3880 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-24 17:41:02.071  3374  3880 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-24 17:41:02.071  3374  3880 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-24 17:41:02.071  3374  3880 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-24 17:41:02.071  3374  3880 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-24 17:41:02.071  3374  3880 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-24 17:41:02.071  3374  3880 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-24 17:41:02.071  3374  3880 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-24 17:41:02.091  2157  2157 D BtGatt.ScanManager: awakened up at time 301518
,03-24 17:41:02.091  2157  2231 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 17:41:02.093  2157  2220 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 17:41:02.093  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 17:41:02.174  1265  1265 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 17:41:02.213  1265  1281 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
03-24 17:41:02.213  1265  1281 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-24 17:41:02.213  1265  1281 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 17:41:02.213  1265  1281 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 17:41:02.219  1265  1281 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 17:41:02.240  3683  3683 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,03-24 17:41:02.241  3683  3683 D Finsky  : [1] 5.onFinished: Installation state replication failed.,
03-24 17:41:02.242  3683  3683 D Finsky  : [1] 5.onFinished: Giving up after 6 failures.
,03-24 17:41:02.597  2157  2157 D BtGatt.ScanManager: awakened up at time 302024
,03-24 17:41:02.599  2157  2231 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 17:41:02.607  2157  2220 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 17:41:02.607  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 17:41:03.622  2157  2157 D BtGatt.ScanManager: awakened up at time 303050
,03-24 17:41:03.625  2157  2231 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 17:41:03.630  2157  2220 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,03-24 17:41:03.630  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 17:41:04.647  2157  2157 D BtGatt.ScanManager: awakened up at time 304075
,03-24 17:41:04.649  2157  2231 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 17:41:04.658  2157  2220 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 17:41:04.658  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 17:41:05.675  2157  2157 D BtGatt.ScanManager: awakened up at time 305103
03-24 17:41:05.675  3273  3273 I io.jxcore.node.ConnectionHelper: restoreDefaultBleDiscoverySettings: Powering the BLE discovery back up
03-24 17:41:05.676  3273  3273 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 0 -> 2
03-24 17:41:05.676  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 17:41:05.676  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 17:41:05.676  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-24 17:41:05.676  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-24 17:41:05.676  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-24 17:41:05.676  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-24 17:41:05.681  2157  2230 D BtGatt.AdvertiseManager: message : 1
,03-24 17:41:05.682  2157  2230 D BtGatt.AdvertiseManager: stop advertise for client 6
03-24 17:41:05.682  2157  2231 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 17:41:05.692  2157  2220 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
03-24 17:41:05.692  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
03-24 17:41:05.696  2157  2220 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 17:41:05.696  2157  2220 D BtGatt.GattService: Client app is not null!
,03-24 17:41:05.699  2157  2173 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-24 17:41:05.701  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 17:41:05.701  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-24 17:41:05.701  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 1, timeout: 0, is connectable: false
03-24 17:41:05.701  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 17:41:05.702  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 17:41:05.703  3273  3273 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 17:41:05.703  3273  3273 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 17:41:05.703  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 17:41:05.703  3273  3273 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-24 17:41:05.711  2157  2172 D BtGatt.GattService: registerClient() - UUID=61155e89-a7ea-44b3-877e-21955d8172ba
,03-24 17:41:05.712  2157  2220 D BtGatt.GattService: onClientRegistered() - UUID=61155e89-a7ea-44b3-877e-21955d8172ba, clientIf=6
03-24 17:41:05.713  3273  3291 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-24 17:41:05.715  2157  2230 D BtGatt.AdvertiseManager: message : 0
,03-24 17:41:05.720  2157  2230 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 17:41:05.723  2157  2220 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 17:41:05.726  2157  2220 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 17:41:05.727  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-24 17:41:05.730  2157  2172 D BtGatt.GattService: stopScan() - queue size =1
,03-24 17:41:05.732  2157  2222 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-24 17:41:05.732  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 17:41:05.733  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 17:41:05.733  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-24 17:41:05.733  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-24 17:41:05.733  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 17:41:05.733  3273  3273 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-24 17:41:05.734  2157  2220 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,03-24 17:41:05.735  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:41:05.735  2157  2231 D BtGatt.ScanManager: stopping BLe Batch
,03-24 17:41:05.737  2157  2220 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0,
03-24 17:41:05.737  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:41:05.737  2157  2231 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 17:41:05.739  2157  2220 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 17:41:05.739  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 17:41:05.740  2157  2173 D BtGatt.GattService: registerClient() - UUID=05458a76-fc68-4b82-a85c-ec0691475f69
03-24 17:41:05.741  2157  2220 D BtGatt.GattService: onClientRegistered() - UUID=05458a76-fc68-4b82-a85c-ec0691475f69, clientIf=5
03-24 17:41:05.741  3273  3327 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 17:41:05.742  2157  2172 D BtGatt.GattService: start scan with filters
03-24 17:41:05.743  2157  2231 D BtGatt.ScanManager: handling starting scan
03-24 17:41:05.743  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 17:41:05.743  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 17:41:05.743  3273  3273 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 1 -> 3
03-24 17:41:05.744  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 17:41:05.744  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 17:41:05.744  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-24 17:41:05.744  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-24 17:41:05.744  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
,03-24 17:41:05.744  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-24 17:41:05.748  2157  2220 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,03-24 17:41:05.748  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 17:41:05.749  2157  2230 D BtGatt.AdvertiseManager: message : 1
03-24 17:41:05.750  2157  2220 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,03-24 17:41:05.750  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:41:05.750  2157  2231 D BtGatt.ScanManager: Starting BLE batch scan
03-24 17:41:05.750  2157  2231 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 17:41:05.750  2157  2230 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-24 17:41:05.753  2157  2220 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0,
03-24 17:41:05.753  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:41:05.754  2157  2220 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,03-24 17:41:05.754  2157  2220 D BtGatt.GattService: Client app is not null!
03-24 17:41:05.755  2157  2172 D BtGatt.GattService: unregisterClient() - clientIf=6
03-24 17:41:05.756  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 17:41:05.756  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-24 17:41:05.756  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-24 17:41:05.756  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 17:41:05.756  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 17:41:05.756  3273  3273 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
,03-24 17:41:05.757  3273  3273 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 17:41:05.757  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-24 17:41:05.757  3273  3273 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-24 17:41:05.758  2157  2220 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 17:41:05.758  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 17:41:05.762  2157  2222 D BtGatt.GattService: registerClient() - UUID=392fb759-0121-4ccc-b996-3df49eaeba9b
03-24 17:41:05.763  2157  2220 D BtGatt.GattService: onClientRegistered() - UUID=392fb759-0121-4ccc-b996-3df49eaeba9b, clientIf=6
03-24 17:41:05.763  3273  3292 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-24 17:41:05.764  2157  2230 D BtGatt.AdvertiseManager: message : 0
,03-24 17:41:05.766  2157  2230 D BtGatt.AdvertiseManager: starting multi advertising,
,03-24 17:41:05.769  2157  2220 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 17:41:05.771  2157  2220 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 17:41:05.772  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-24 17:41:05.774  2157  2222 D BtGatt.GattService: stopScan() - queue size =1
,03-24 17:41:05.775  2157  2173 D BtGatt.GattService: unregisterClient() - clientIf=5
03-24 17:41:05.775  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 17:41:05.775  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 17:41:05.775  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-24 17:41:05.775  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 17:41:05.775  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 17:41:05.775  3273  3273 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-24 17:41:05.776  2157  2220 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 17:41:05.776  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:41:05.776  2157  2231 D BtGatt.ScanManager: stopping BLe Batch
03-24 17:41:05.777  2157  2220 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,03-24 17:41:05.777  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:41:05.778  2157  2231 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 17:41:05.778  2157  2222 D BtGatt.GattService: registerClient() - UUID=643c676b-8d4a-440d-9d81-cecb405adb72
03-24 17:41:05.779  2157  2220 D BtGatt.GattService: onClientRegistered() - UUID=643c676b-8d4a-440d-9d81-cecb405adb72, clientIf=5
,03-24 17:41:05.779  3273  3291 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 17:41:05.779  2157  2220 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 17:41:05.779  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:41:05.779  2157  2172 D BtGatt.GattService: start scan with filters
03-24 17:41:05.780  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 17:41:05.780  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 17:41:05.780  3273  3273 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 0 -> 2
03-24 17:41:05.780  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 17:41:05.780  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 17:41:05.780  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-24 17:41:05.780  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-24 17:41:05.780  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-24 17:41:05.780  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-24 17:41:05.783  2157  2230 D BtGatt.AdvertiseManager: message : 1
03-24 17:41:05.783  2157  2231 D BtGatt.ScanManager: handling starting scan,
03-24 17:41:05.784  2157  2230 D BtGatt.AdvertiseManager: stop advertise for client 6
03-24 17:41:05.785  2157  2220 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 17:41:05.786  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:41:05.787  2157  2220 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 17:41:05.787  2157  2220 D BtGatt.GattService: Client app is not null!
03-24 17:41:05.787  2157  2172 D BtGatt.GattService: unregisterClient() - clientIf=6
03-24 17:41:05.788  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 17:41:05.788  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
,03-24 17:41:05.788  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-24 17:41:05.788  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 17:41:05.788  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 17:41:05.788  3273  3273 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 17:41:05.788  3273  3273 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 17:41:05.789  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 17:41:05.789  3273  3273 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-24 17:41:05.789  2157  2220 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,03-24 17:41:05.789  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:41:05.790  2157  2231 D BtGatt.ScanManager: Starting BLE batch scan
03-24 17:41:05.790  2157  2231 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 17:41:05.791  2157  2220 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 17:41:05.791  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:41:05.793  2157  2220 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 17:41:05.793  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 17:41:05.839  2157  2173 I art     : Explicit concurrent mark sweep GC freed 30815(1714KB) AllocSpace objects, 6(96KB) LOS objects, 39% free, 22MB/37MB, paused 1.031ms total 45.578ms
03-24 17:41:05.840  2157  2173 D BtGatt.GattService: registerClient() - UUID=8831f8e1-1b59-46c4-ab90-42338717d82c
03-24 17:41:05.840  2157  2220 D BtGatt.GattService: onClientRegistered() - UUID=8831f8e1-1b59-46c4-ab90-42338717d82c, clientIf=6
,03-24 17:41:05.841  3273  3327 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-24 17:41:05.842  2157  2230 D BtGatt.AdvertiseManager: message : 0
,03-24 17:41:05.846  2157  2230 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 17:41:05.849  2157  2220 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 17:41:05.851  2157  2220 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0,
,03-24 17:41:05.855  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING,
,03-24 17:41:05.856  2157  2173 D BtGatt.GattService: stopScan() - queue size =1
,03-24 17:41:05.857  2157  2222 D BtGatt.GattService: unregisterClient() - clientIf=5
03-24 17:41:05.858  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-24 17:41:05.858  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-24 17:41:05.858  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 17:41:05.858  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 17:41:05.858  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 17:41:05.858  3273  3273 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 17:41:05.859  2157  2220 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 17:41:05.859  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:41:05.860  2157  2231 D BtGatt.ScanManager: stopping BLe Batch
03-24 17:41:05.861  2157  2220 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,03-24 17:41:05.861  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:41:05.862  2157  2231 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 17:41:05.863  2157  2172 D BtGatt.GattService: registerClient() - UUID=d169f001-225d-4bc9-8f34-e3e82f4ecd4b
03-24 17:41:05.863  2157  2220 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 17:41:05.863  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 17:41:05.864  2157  2220 D BtGatt.GattService: onClientRegistered() - UUID=d169f001-225d-4bc9-8f34-e3e82f4ecd4b, clientIf=5
03-24 17:41:05.866  3273  3883 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-24 17:41:05.867  2157  2173 D BtGatt.GattService: start scan with filters
,03-24 17:41:05.868  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 17:41:05.868  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 17:41:05.868  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 17:41:05.868  3273  3273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-24 17:41:05.868  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-24 17:41:05.868  2157  2231 D BtGatt.ScanManager: handling starting scan
03-24 17:41:05.868  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 17:41:05.868  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,03-24 17:41:05.870  2157  2220 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 17:41:05.870  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 17:41:05.873  2157  2220 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15,
,03-24 17:41:05.873  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:41:05.873  2157  2231 D BtGatt.ScanManager: Starting BLE batch scan
,03-24 17:41:05.873  2157  2231 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 17:41:05.875  2157  2220 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,03-24 17:41:05.875  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 17:41:05.877  2157  2220 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 17:41:05.877  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 17:41:06.707  2157  2157 D BtGatt.ScanManager: awakened up at time 306135
,03-24 17:41:06.712  2157  2231 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 17:41:06.722  2157  2220 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,03-24 17:41:06.722  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:41:06.723  2157  2220 D BtGatt.GattService: current time is 306150948474
03-24 17:41:06.723  2157  2220 D BtGatt.GattService: Batch record : [-42, 49, -79, 50, -25, 96, 1, -128, -79, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -59, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-24 17:41:06.724  2157  2220 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,03-24 17:41:06.725  2157  2220 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-24 17:41:06.727  3273  3273 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> E0:DB:10:14:E2:C0] updated - the peer count is 2
,03-24 17:41:06.728  3273  3273 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
,03-24 17:41:07.736  2157  2157 D BtGatt.ScanManager: awakened up at time 307163
,03-24 17:41:07.738  2157  2231 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 17:41:07.748  2157  2220 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,03-24 17:41:07.748  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:41:07.748  2157  2220 D BtGatt.GattService: current time is 307176449099
,03-24 17:41:07.749  2157  2220 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -64, 6, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0, -42, 49, -79, 50, -25, 96, 1, -128, -79, 5, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-24 17:41:07.749  2157  2220 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
,03-24 17:41:07.750  2157  2220 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,03-24 17:41:07.754  3273  3273 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> E0:DB:10:14:E2:C0] updated - the peer count is 2
03-24 17:41:07.754  3273  3273 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
,03-24 17:41:07.854  2157  2223 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 17:41:08.028  3273  3332 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 17:41:08.028  3273  3332 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-24 17:41:08.029  3273  3332 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-24 17:41:08.029  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-24 17:41:08.029  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,03-24 17:41:08.031  3273  3332 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-24 17:41:08.032  3273  3867 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-24 17:41:08.032  3273  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-24 17:41:08.033  3273  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,03-24 17:41:08.033  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-24 17:41:08.034  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-24 17:41:08.034  3273  3273 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-24 17:41:08.034  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 17:41:08.034  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 17:41:08.034  3273  3273 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,03-24 17:41:08.035  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-24 17:41:08.035  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-24 17:41:08.039  2157  2172 D BtGatt.GattService: stopScan() - queue size =1
03-24 17:41:08.041  2157  2173 D BtGatt.GattService: unregisterClient() - clientIf=5
03-24 17:41:08.043  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 17:41:08.043  2157  2220 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 17:41:08.043  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:41:08.043  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 17:41:08.043  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,03-24 17:41:08.043  2157  2231 D BtGatt.ScanManager: stopping BLe Batch
03-24 17:41:08.043  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-24 17:41:08.044  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-24 17:41:08.044  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 17:41:08.044  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-24 17:41:08.046  2157  2220 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 17:41:08.046  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:41:08.047  2157  2231 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 17:41:08.048  2157  2230 D BtGatt.AdvertiseManager: message : 1
,03-24 17:41:08.048  2157  2220 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,03-24 17:41:08.048  2157  2220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 17:41:08.049  2157  2230 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-24 17:41:08.053  2157  2220 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 17:41:08.053  2157  2220 D BtGatt.GattService: Client app is not null!
,03-24 17:41:08.055  2157  2173 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-24 17:41:08.056  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 17:41:08.056  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-24 17:41:08.056  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-24 17:41:08.057  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-24 17:41:08.057  3273  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-24 17:41:08.057  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-24 17:41:08.057  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 17:41:08.057  3273  3332 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-24 17:41:08.058  3273  3332 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-24 17:41:08.059  3273  3332 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-24 17:41:08.059  3273  3332 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,03-24 17:41:08.059  3273  3273 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 17:41:08.059  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 17:41:08.059  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-24 17:41:08.069  3273  3273 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-24 17:41:08.070   823  1154 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 17:41:08.081  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-24 17:41:08.082  3273  3273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 17:41:08.082  3273  3273 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 17:41:08.090  3273  3273 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-24 17:41:08.090  3273  3273 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-24 17:41:08.090  3273  3273 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-24 17:41:08.090  3273  3273 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-24 17:41:08.091  3273  3273 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-24 17:41:08.091  3273  3273 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 17:41:08.093  3273  3332 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 17:41:08.093  3273  3332 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-24 17:41:08.093  3273  3332 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 17:41:08.096  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-24 17:41:08.096  3273  3332 I jxcore-log: 
,03-24 17:41:08.098  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 17:41:08.098  3273  3332 I jxcore-log: 
03-24 17:41:08.101  3273  3332 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 17:41:08.101  3273  3332 I jxcore-log: 
,03-24 17:41:08.123  3273  3332 I jxcore-log: # setup
03-24 17:41:08.123  3273  3332 I jxcore-log: 
,03-24 17:41:10.188  3273  3332 I jxcore-log: # 56. Test BEACONS_RETRIEVED_AND_PARSED locally
03-24 17:41:10.188  3273  3332 I jxcore-log: 
,03-24 17:41:10.405  3273  3332 I jxcore-log: ok 214 peerIdentifier should be identifier
03-24 17:41:10.405  3273  3332 I jxcore-log: 
03-24 17:41:10.405  3273  3332 I jxcore-log: ok 215 Response should be BEACONS_RETRIEVED_AND_PARSED
03-24 17:41:10.405  3273  3332 I jxcore-log: 
03-24 17:41:10.406  3273  3332 I jxcore-log: ok 216 good beacon
03-24 17:41:10.406  3273  3332 I jxcore-log: 
,03-24 17:41:10.406  3273  3332 I jxcore-log: ok 217 good preAmble
03-24 17:41:10.406  3273  3332 I jxcore-log: 
03-24 17:41:10.406  3273  3332 I jxcore-log: ok 218 public keys match!
03-24 17:41:10.406  3273  3332 I jxcore-log: 
,03-24 17:41:10.408  3273  3332 I jxcore-log: ok 219 must return null after successful call
03-24 17:41:10.408  3273  3332 I jxcore-log: 
,03-24 17:41:10.415  3273  3332 I jxcore-log: # teardown
03-24 17:41:10.415  3273  3332 I jxcore-log: 
,03-24 17:41:13.907  3273  3332 I jxcore-log: # setup
03-24 17:41:13.907  3273  3332 I jxcore-log: 
,03-24 17:41:16.643  3273  3332 I jxcore-log: # 57. Test HTTP_BAD_RESPONSE locally
03-24 17:41:16.643  3273  3332 I jxcore-log: 
,03-24 17:41:23.590  3473  3890 I BooksSync: Starting books sync for 61035162, extras: ade
,03-24 17:41:23.635  3473  3891 I BooksConfig: GmsCore Version = 7.8.99 (2134222-430)
,03-24 17:41:23.754   823  1151 I art     : Explicit concurrent mark sweep GC freed 28902(1359KB) AllocSpace objects, 3(236KB) LOS objects, 32% free, 33MB/49MB, paused 2.183ms total 83.357ms
,03-24 17:41:23.797  1265  1282 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-24 17:41:23.797  1265  2585 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-24 17:41:23.797  1265  2585 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 17:41:23.797  1265  2585 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 17:41:23.797  1265  2585 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 17:41:23.798  1265  1282 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 17:41:23.798  1265  1282 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 17:41:23.798  1265  1282 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 17:41:23.802  1265  2585 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 17:41:23.804  1265  1282 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 17:41:23.823  3093  3889 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
03-24 17:41:23.823  3093  3889 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-24 17:41:23.823  3093  3889 E HttpOperation: 	at jdm.a(PG:82)
03-24 17:41:23.823  3093  3889 E HttpOperation: 	at jcs.o(PG:406)
03-24 17:41:23.823  3093  3889 E HttpOperation: 	at jcn.a(PG:1379)
03-24 17:41:23.823  3093  3889 E HttpOperation: 	at jcs.i(PG:143)
03-24 17:41:23.823  3093  3889 E HttpOperation: 	at blb.a(PG:3937)
03-24 17:41:23.823  3093  3889 E HttpOperation: 	at czp.a(PG:18188)
03-24 17:41:23.823  3093  3889 E HttpOperation: 	at czp.a(PG:9081)
03-24 17:41:23.823  3093  3889 E HttpOperation: 	at czq.run(PG:1686)
03-24 17:41:23.823  3093  3889 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-24 17:41:23.823  3093  3889 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 17:41:23.823  3093  3889 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 17:41:23.823  3093  3889 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 17:41:23.823  3093  3889 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-24 17:41:23.823  3093  3889 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-24 17:41:23.823  3093  3889 E HttpOperation: 	at jdj.a(PG:4091)
03-24 17:41:23.823  3093  3889 E HttpOperation: 	at jdj.a(PG:1125)
03-24 17:41:23.823  3093  3889 E HttpOperation: 	at jdm.a(PG:77)
03-24 17:41:23.823  3093  3889 E HttpOperation: 	... 12 more
03-24 17:41:23.823  3093  3889 E HttpOperation: Caused by: faj: BadAuthentication
03-24 17:41:23.823  3093  3889 E HttpOperation: 	at fal.a(PG:38)
03-24 17:41:23.823  3093  3889 E HttpOperation: 	at jdj.a(PG:4089)
03-24 17:41:23.823  3093  3889 E HttpOperation: 	... 14 more
,03-24 17:41:23.873  1265  1281 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-24 17:41:23.873  1265  1281 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 17:41:23.874  1265  1281 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 17:41:23.874  1265  1281 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 17:41:23.875  1265  2584 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-24 17:41:23.875  1265  2584 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 17:41:23.875  1265  2584 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 17:41:23.875  1265  2584 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 17:41:23.877  1265  1281 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 17:41:23.879  1265  2584 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 17:41:23.891  3093  3889 E HttpOperation: [getmobileexperiments] Unexpected exception
03-24 17:41:23.891  3093  3889 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-24 17:41:23.891  3093  3889 E HttpOperation: 	at jdm.a(PG:82)
03-24 17:41:23.891  3093  3889 E HttpOperation: 	at jcs.o(PG:406)
03-24 17:41:23.891  3093  3889 E HttpOperation: 	at jcn.a(PG:1379)
03-24 17:41:23.891  3093  3889 E HttpOperation: 	at jcs.i(PG:143)
03-24 17:41:23.891  3093  3889 E HttpOperation: 	at hec.a(PG:42)
03-24 17:41:23.891  3093  3889 E HttpOperation: 	at hee.a(PG:102)
03-24 17:41:23.891  3093  3889 E HttpOperation: 	at czr.a(PG:65)
03-24 17:41:23.891  3093  3889 E HttpOperation: 	at kka.a(PG:108)
03-24 17:41:23.891  3093  3889 E HttpOperation: 	at czp.a(PG:19176)
03-24 17:41:23.891  3093  3889 E HttpOperation: 	at czp.a(PG:9081)
03-24 17:41:23.891  3093  3889 E HttpOperation: 	at czq.run(PG:1686)
03-24 17:41:23.891  3093  3889 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-24 17:41:23.891  3093  3889 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 17:41:23.891  3093  3889 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 17:41:23.891  3093  3889 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 17:41:23.891  3093  3889 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-24 17:41:23.891  3093  3889 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-24 17:41:23.891  3093  3889 E HttpOperation: 	at jdj.a(PG:4091)
03-24 17:41:23.891  3093  3889 E HttpOperation: 	at jdj.a(PG:1125)
03-24 17:41:23.891  3093  3889 E HttpOperation: 	at jdm.a(PG:77)
03-24 17:41:23.891  3093  3889 E HttpOperation: 	... 15 more
03-24 17:41:23.891  3093  3889 E HttpOperation: Caused by: faj: BadAuthentication
03-24 17:41:23.891  3093  3889 E HttpOperation: 	at fal.a(PG:38)
03-24 17:41:23.891  3093  3889 E HttpOperation: 	at jdj.a(PG:4089)
03-24 17:41:23.891  3093  3889 E HttpOperation: 	... 17 more
,03-24 17:41:23.892  3093  3889 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token,
03-24 17:41:23.892  3093  3889 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
03-24 17:41:23.892  3093  3889 E ExperimentLoader: 	at jdm.a(PG:82),
03-24 17:41:23.892  3093  3889 E ExperimentLoader: 	at jcs.o(PG:406)
03-24 17:41:23.892  3093  3889 E ExperimentLoader: 	at jcn.a(PG:1379)
03-24 17:41:23.892  3093  3889 E ExperimentLoader: 	,at jcs.i(PG:143)
03-24 17:41:23.892  3093  3889 E ExperimentLoader: 	at hec.a(PG:42)
03-24 17:41:23.892  3093  3889 E ExperimentLoader: 	at hee.a(PG:102)
,03-24 17:41:23.892  3093  3889 E ExperimentLoader: 	at czr.a(PG:65)
03-24 17:41:23.892  3093  3889 E ExperimentLoader: 	at kka.a(PG:108)
03-24 17:41:23.892  3093  3889 E ExperimentLoader: 	at czp.a(PG:19176)
03-24 17:41:23.892  3093  3889 E ExperimentLoader: 	,at czp.a(PG:9081)
03-24 17:41:23.892  3093  3889 E ExperimentLoader: 	at czq.run(PG:1686)
03-24 17:41:23.892  3093  3889 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-24 17:41:23.892  3093  3889 E ExperimentLoader: ,	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 17:41:23.892  3093  3889 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 17:41:23.892  3093  3889 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587),
03-24 17:41:23.892  3093  3889 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
03-24 17:41:23.892  3093  3889 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-24 17:41:23.892  3093  3889 E ExperimentLoader: 	at jdj.a(PG:4091)
03-24 17:41:23.892  3093  3889 E ExperimentLoader: 	at jdj.a(PG:1125)
03-24 17:41:23.892  3093  3889 E ExperimentLoader: 	at jdm.a(PG:77)
,03-24 17:41:23.892  3093  3889 E ExperimentLoader: 	... 15 more
03-24 17:41:23.892  3093  3889 E ExperimentLoader: Caused by: faj: BadAuthentication
03-24 17:41:23.892  3093  3889 E ExperimentLoader: 	at fal.a(PG:38)
,03-24 17:41:23.892  3093  3889 E ExperimentLoader: 	at jdj.a(PG:4089)
03-24 17:41:23.892  3093  3889 E ExperimentLoader: 	... 17 more
,03-24 17:41:23.892  3473  3891 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-24 17:41:23.893  3473  3890 E BooksSync: Soft error
03-24 17:41:23.893  3473  3890 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,03-24 17:41:23.893  3473  3890 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-24 17:41:23.894  3473  3890 E BooksSync: Sync error
03-24 17:41:23.894  3473  3890 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-24 17:41:23.894  3473  3890 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,03-24 17:41:23.894  3473  3890 I BooksSync: Finished books sync
,03-24 17:41:23.906   823   856 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 294997, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1],
,03-24 17:41:23.996   823   856 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 293732, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-24 17:41:32.114   823  1154 D WifiService: acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@26ac0cda}
,03-24 17:41:32.126   823  1019 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=1.25 rxSuccessRate=0.50 targetRoamBSSID=any RSSI=-127
,03-24 17:41:32.182  3374  3893 V GoogleAuthProtoRequest: [345] a.<init>: mAccountName set to: thalitester@gmail.com
,03-24 17:41:32.231  1265  2584 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,03-24 17:41:32.232  1265  2584 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 17:41:32.232  1265  2584 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 17:41:32.232  1265  2584 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 17:41:32.242  1265  2584 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 17:41:32.264  3374  3893 W ExperimentUpdateService: [345] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,03-24 17:41:32.264  3374  3893 W ExperimentUpdateService: [345] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-24 17:41:32.264  3374  3893 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-24 17:41:32.264  3374  3893 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-24 17:41:32.264  3374  3893 W ExperimentUpdateService: ,	at com.a.a.a.k.get(SourceFile:97)
03-24 17:41:32.264  3374  3893 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-24 17:41:32.264  3374  3893 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-24 17:41:32.264  3374  3893 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-24 17:41:32.264  3374  3893 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-24 17:41:32.264  3374  3893 W ExperimentUpdateService: ,	at com.a.a.a.g.a(SourceFile:79)
03-24 17:41:32.264  3374  3893 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-24 17:41:32.264  3374  3893 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-24 17:41:32.804  3273  3332 I jxcore-log: ok 220 Response should be HTTP_BAD_RESPONSE
03-24 17:41:32.804  3273  3332 I jxcore-log: 
,03-24 17:41:32.805  3273  3332 I jxcore-log: ok 221 must return null after successful call
03-24 17:41:32.805  3273  3332 I jxcore-log: 
,03-24 17:41:32.814  3273  3332 I jxcore-log: # teardown
03-24 17:41:32.814  3273  3332 I jxcore-log: 
,03-24 17:41:33.829   823  1151 D WifiService: releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@26ac0cda}
,03-24 17:41:33.895   823  1283 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::injectLocation(GpsExtLocation):857]: error! inject position failed
,03-24 17:41:33.968   874   874 I kickstart: STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
,03-24 17:41:33.969   874   874 I kickstart: STATUS: Wrote to /sys/power/wake_lock
,03-24 17:41:34.010   874   874 E kickstart: ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1
,03-24 17:41:34.010   874   874 I kickstart: STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1' for writing
,03-24 17:41:34.994   874   874 I kickstart: STATUS: Received file 'm9kefs1'
03-24 17:41:34.994   874   874 I kickstart: STATUS: 950272 bytes transferred in 0.983159 seconds
,03-24 17:41:34.994   874   874 I kickstart: STATUS: Successfully downloaded files from target 
03-24 17:41:34.994   874   874 I kickstart: STATUS: Wrote to /sys/power/wake_unlock
,03-24 17:41:34.998   874   874 I kickstart: STATUS: Sahara protocol completed
,03-24 17:41:44.121  2157  2223 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 17:41:57.655  3273  3332 I jxcore-log: # setup
03-24 17:41:57.655  3273  3332 I jxcore-log: 
,03-24 17:41:57.908  3273  3332 I jxcore-log: # 58. Test NETWORK_PROBLEM locally
,03-24 17:41:57.908  3273  3332 I jxcore-log: 
,03-24 17:42:00.565  3273  3332 I jxcore-log: ok 222 Response should be NETWORK_PROBLEM
03-24 17:42:00.565  3273  3332 I jxcore-log: 
03-24 17:42:00.571  3273  3332 I jxcore-log: ok 223 reject reason should be: Could not establish TCP connection
03-24 17:42:00.571  3273  3332 I jxcore-log: 
,03-24 17:42:00.588  3273  3332 I jxcore-log: # teardown
03-24 17:42:00.588  3273  3332 I jxcore-log: 
,03-24 17:42:01.016  3273  3332 I jxcore-log: # setup,
03-24 17:42:01.016  3273  3332 I jxcore-log: 
,03-24 17:42:44.281  2157  2223 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 17:43:01.276  3273  3332 I jxcore-log: # 59. Test timeout locally
03-24 17:43:01.276  3273  3332 I jxcore-log: 
,03-24 17:43:02.130  3374  3909 V GoogleAuthProtoRequest: [346] a.<init>: mAccountName set to: thalitester@gmail.com
,03-24 17:43:02.296  3374  3910 V GoogleAuthProtoRequest: [347] a.<init>: mAccountName set to: thalitester@gmail.com
,03-24 17:43:02.347  1265  2084 I art     : Explicit concurrent mark sweep GC freed 49043(2MB) AllocSpace objects, 6(661KB) LOS objects, 37% free, 26MB/42MB, paused 825us total 25.323ms
,03-24 17:43:02.403  1265  1728 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,03-24 17:43:02.404  1265  1728 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-24 17:43:02.405  1265  1728 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 17:43:02.406  1265  1728 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 17:43:02.412  1265  1281 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
03-24 17:43:02.412  1265  1728 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 17:43:02.412  1265  1281 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 17:43:02.413  1265  1281 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 17:43:02.413  1265  1281 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 17:43:02.422  1265  1281 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 17:43:02.427  3374  3909 W ExperimentUpdateService: [346] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,03-24 17:43:02.427  3374  3909 W ExperimentUpdateService: [346] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-24 17:43:02.427  3374  3909 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-24 17:43:02.427  3374  3909 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-24 17:43:02.427  3374  3909 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-24 17:43:02.427  3374  3909 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-24 17:43:02.427  3374  3909 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-24 17:43:02.427  3374  3909 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-24 17:43:02.427  3374  3909 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-24 17:43:02.427  3374  3909 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-24 17:43:02.427  3374  3909 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-24 17:43:02.427  3374  3909 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-24 17:43:02.438  3374  3910 W ExperimentUpdateService: [347] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,03-24 17:43:02.440  3374  3910 W ExperimentUpdateService: [347] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-24 17:43:02.440  3374  3910 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-24 17:43:02.440  3374  3910 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-24 17:43:02.440  3374  3910 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-24 17:43:02.440  3374  3910 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-24 17:43:02.440  3374  3910 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-24 17:43:02.440  3374  3910 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-24 17:43:02.440  3374  3910 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-24 17:43:02.440  3374  3910 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-24 17:43:02.440  3374  3910 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-24 17:43:02.440  3374  3910 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-24 17:43:02.477  3452  3913 V KeepSync: Connecting to GoogleApiClient
,03-24 17:43:02.516  1265  2584 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
03-24 17:43:02.516  1265  2584 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 17:43:02.516  1265  2584 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-24 17:43:02.516  1265  2584 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 17:43:02.519  1265  2584 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 17:43:02.532  1814  3915 E ClientConnectionOperation: Handling authorization failure
03-24 17:43:02.532  1814  3915 E ClientConnectionOperation: com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
03-24 17:43:02.532  1814  3915 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
03-24 17:43:02.532  1814  3915 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
03-24 17:43:02.532  1814  3915 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
03-24 17:43:02.532  1814  3915 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
03-24 17:43:02.532  1814  3915 E ClientConnectionOperation: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-24 17:43:02.532  1814  3915 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 17:43:02.532  1814  3915 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 17:43:02.532  1814  3915 E ClientConnectionOperation: 	at java.lang.Thread.run(Thread.java:818)
03-24 17:43:02.532  1814  3915 E ClientConnectionOperation: Caused by: com.google.android.gms.auth.ad: BadAuthentication
03-24 17:43:02.532  1814  3915 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.b(SourceFile:442)
03-24 17:43:02.532  1814  3915 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:365)
03-24 17:43:02.532  1814  3915 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:310)
03-24 17:43:02.532  1814  3915 E ClientConnectionOperation: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
03-24 17:43:02.532  1814  3915 E ClientConnectionOperation: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
03-24 17:43:02.532  1814  3915 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:30)
03-24 17:43:02.532  1814  3915 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:370)
03-24 17:43:02.532  1814  3915 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:340)
03-24 17:43:02.532  1814  3915 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:319)
03-24 17:43:02.532  1814  3915 E ClientConnectionOperation: 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
03-24 17:43:02.532  1814  3915 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
03-24 17:43:02.532  1814  3915 E ClientConnectionOperation: 	... 7 more
,03-24 17:43:02.535  3452  3913 V KeepSync: GoogleApiClient failed to connect with error code: 4
,03-24 17:43:02.536  3452  3913 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-24 17:43:02.542  3452  3913 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-24 17:43:02.543  3452  3913 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-24 17:43:02.602  1265  1728 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
03-24 17:43:02.602  1265  1728 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-24 17:43:02.602  1265  1728 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 17:43:02.602  1265  1728 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 17:43:02.606  1265  1728 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 17:43:02.643  3452  3913 E KeepSync: IOException
03-24 17:43:02.643  3452  3913 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
03-24 17:43:02.643  3452  3913 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
03-24 17:43:02.643  3452  3913 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
03-24 17:43:02.643  3452  3913 E KeepSync: 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
03-24 17:43:02.643  3452  3913 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
03-24 17:43:02.643  3452  3913 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
03-24 17:43:02.643  3452  3913 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
03-24 17:43:02.643  3452  3913 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
03-24 17:43:02.643  3452  3913 E KeepSync: 	at com.google.android.keep.util.m.a(SourceFile:207)
03-24 17:43:02.643  3452  3913 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
03-24 17:43:02.643  3452  3913 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
03-24 17:43:02.643  3452  3913 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
03-24 17:43:02.643  3452  3913 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
03-24 17:43:02.643  3452  3913 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
03-24 17:43:02.643  3452  3913 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
03-24 17:43:02.643  3452  3913 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
03-24 17:43:02.643  3452  3913 E KeepSync: 	... 10 more
03-24 17:43:02.643  3452  3913 W KeepSync: Sync result 2
,03-24 17:43:02.650   823   856 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 421869, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-24 17:43:07.854  2157  2223 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 17:43:21.892  3273  3332 I jxcore-log: ok 224 Should be NETWORK_PROBLEM caused by timeout
03-24 17:43:21.892  3273  3332 I jxcore-log: 
,03-24 17:43:21.899  3273  3332 I jxcore-log: ok 225 reject reason should be Could not establish TCP connection
03-24 17:43:21.899  3273  3332 I jxcore-log: 
,03-24 17:43:21.910  3273  3332 I jxcore-log: # teardown
03-24 17:43:21.910  3273  3332 I jxcore-log: 
,03-24 17:43:22.038  3273  3332 I jxcore-log: # setup
03-24 17:43:22.038  3273  3332 I jxcore-log: 
,03-24 17:43:22.399  3273  3332 I jxcore-log: # 60. Call the start two times
03-24 17:43:22.399  3273  3332 I jxcore-log: 
,03-24 17:43:22.522  3273  3332 I jxcore-log: ok 226 Call start once
03-24 17:43:22.522  3273  3332 I jxcore-log: 
,03-24 17:43:22.571  3273  3332 I jxcore-log: ok 227 Response should be BEACONS_RETRIEVED_AND_PARSED
03-24 17:43:22.571  3273  3332 I jxcore-log: 
,03-24 17:43:22.572  3273  3332 I jxcore-log: ok 228 must return null after successful call.
03-24 17:43:22.572  3273  3332 I jxcore-log: 
,03-24 17:43:22.580  3273  3332 I jxcore-log: # teardown
03-24 17:43:22.580  3273  3332 I jxcore-log: 
,03-24 17:43:22.765  3273  3332 I jxcore-log: # setup
03-24 17:43:22.765  3273  3332 I jxcore-log: 
,03-24 17:43:22.967  3273  3332 I jxcore-log: # 61. Call the kill before calling the start
03-24 17:43:22.967  3273  3332 I jxcore-log: 
,03-24 17:43:23.094  3273  3332 I jxcore-log: ok 229 Should be Killed
03-24 17:43:23.094  3273  3332 I jxcore-log: 
03-24 17:43:23.102  3273  3332 I jxcore-log: ok 230 Start after killed
03-24 17:43:23.102  3273  3332 I jxcore-log: 
,03-24 17:43:23.110  3273  3332 I jxcore-log: # teardown,
03-24 17:43:23.110  3273  3332 I jxcore-log: 
,03-24 17:43:23.272  3273  3332 I jxcore-log: # setup,
03-24 17:43:23.272  3273  3332 I jxcore-log: 
,03-24 17:43:23.499  3273  3332 I jxcore-log: # 62. Call the kill immediately after the start
03-24 17:43:23.499  3273  3332 I jxcore-log: 
,03-24 17:43:23.673  3273  3332 I jxcore-log: ok 231 Should be KILLED
03-24 17:43:23.673  3273  3332 I jxcore-log: 
,03-24 17:43:23.675  3273  3332 I jxcore-log: ok 232 must return null after successful kill
03-24 17:43:23.675  3273  3332 I jxcore-log: 
,03-24 17:43:23.682  3273  3332 I jxcore-log: # teardown
03-24 17:43:23.682  3273  3332 I jxcore-log: 
,03-24 17:43:23.790  3273  3332 I jxcore-log: # setup
03-24 17:43:23.790  3273  3332 I jxcore-log: 
,03-24 17:43:24.006  3273  3332 I jxcore-log: # 63. Call the kill while waiting a response from the server
03-24 17:43:24.006  3273  3332 I jxcore-log: 
,03-24 17:43:26.141  3273  3332 I jxcore-log: ok 233 Should be KILLED
03-24 17:43:26.141  3273  3332 I jxcore-log: 
,03-24 17:43:26.144  3273  3332 I jxcore-log: ok 234 must return null after successful kill
03-24 17:43:26.144  3273  3332 I jxcore-log: 
,03-24 17:43:26.169  3273  3332 I jxcore-log: # teardown
03-24 17:43:26.169  3273  3332 I jxcore-log: 
,03-24 17:43:27.046  3273  3332 I jxcore-log: # setup
03-24 17:43:27.046  3273  3332 I jxcore-log: 
,03-24 17:43:27.237  3273  3332 I jxcore-log: # 64. Test to exceed the max content size locally
03-24 17:43:27.237  3273  3332 I jxcore-log: 
,03-24 17:43:27.384  3273  3332 I jxcore-log: ok 235 HTTP_BAD_RESPONSE should be response when content size is exceeded
03-24 17:43:27.384  3273  3332 I jxcore-log: 
,03-24 17:43:27.388  3273  3332 I jxcore-log: ok 236 must return null after successful call
03-24 17:43:27.388  3273  3332 I jxcore-log: 
,03-24 17:43:27.401  3273  3332 I jxcore-log: # teardown
03-24 17:43:27.401  3273  3332 I jxcore-log: 
,03-24 17:43:27.504  3273  3332 I jxcore-log: # setup
03-24 17:43:27.504  3273  3332 I jxcore-log: 
,03-24 17:43:27.709  3273  3332 I jxcore-log: # 65. Close the server socket while the client is waiting a response from the server. Local test.
03-24 17:43:27.709  3273  3332 I jxcore-log: 
,03-24 17:43:29.920  3273  3332 I jxcore-log: ok 237 Should be NETWORK_PROBLEM caused closing server socket
03-24 17:43:29.920  3273  3332 I jxcore-log: 
,03-24 17:43:29.926  3273  3332 I jxcore-log: ok 238 Should be Could not establish TCP connection
03-24 17:43:29.926  3273  3332 I jxcore-log: 
,03-24 17:43:29.935  3273  3332 I jxcore-log: # teardown
03-24 17:43:29.935  3273  3332 I jxcore-log: 
,03-24 17:43:30.085  3273  3332 I jxcore-log: # setup
03-24 17:43:30.085  3273  3332 I jxcore-log: 
,03-24 17:43:30.361  3273  3332 I jxcore-log: # 66. Close the client socket while the client is waiting a response from the server. Local test.
03-24 17:43:30.361  3273  3332 I jxcore-log: 
,03-24 17:43:32.557  3273  3332 I jxcore-log: ok 239 Should be NETWORK_PROBLEM caused closing client socket
03-24 17:43:32.557  3273  3332 I jxcore-log: 
,03-24 17:43:32.561  3273  3332 I jxcore-log: ok 240 Should be Could not establish TCP connection
03-24 17:43:32.561  3273  3332 I jxcore-log: 
,03-24 17:43:32.573  3273  3332 I jxcore-log: # teardown
03-24 17:43:32.573  3273  3332 I jxcore-log: 
,03-24 17:43:32.704  3273  3332 I jxcore-log: # setup
03-24 17:43:32.704  3273  3332 I jxcore-log: 
,03-24 17:43:32.826  3273  3332 I jxcore-log: # 67. #generatePreambleAndBeacons bad args
03-24 17:43:32.826  3273  3332 I jxcore-log: 
,03-24 17:43:33.016  3273  3332 I jxcore-log: ok 241 publicKeysToNotify cannot be null
03-24 17:43:33.016  3273  3332 I jxcore-log: 
03-24 17:43:33.018  3273  3332 I jxcore-log: ok 242 ecdh for local device cannot be null
03-24 17:43:33.018  3273  3332 I jxcore-log: 
03-24 17:43:33.019  3273  3332 I jxcore-log: ok 243 milliseconds cannot be less than 0
03-24 17:43:33.019  3273  3332 I jxcore-log: 
,03-24 17:43:33.024  3273  3332 I jxcore-log: ok 244 milliseconds cannot be 0
03-24 17:43:33.024  3273  3332 I jxcore-log: 
,03-24 17:43:33.026  3273  3332 I jxcore-log: ok 245 milliseconds cannot be greater than one_day
03-24 17:43:33.026  3273  3332 I jxcore-log: 
,03-24 17:43:33.029  3273  3332 I jxcore-log: # teardown
03-24 17:43:33.029  3273  3332 I jxcore-log: 
,03-24 17:43:33.213  3273  3332 I jxcore-log: # setup
03-24 17:43:33.213  3273  3332 I jxcore-log: 
,03-24 17:43:33.380  3273  3332 I jxcore-log: # 68. #generatePreambleAndBeacons empty keys to notify
03-24 17:43:33.380  3273  3332 I jxcore-log: 
,03-24 17:43:33.531  3273  3332 I jxcore-log: ok 246 should be equal
03-24 17:43:33.531  3273  3332 I jxcore-log: 
,03-24 17:43:33.534  3273  3332 I jxcore-log: # teardown
03-24 17:43:33.534  3273  3332 I jxcore-log: 
,03-24 17:43:33.641  3273  3332 I jxcore-log: # setup
03-24 17:43:33.641  3273  3332 I jxcore-log: 
,03-24 17:43:33.799  3273  3332 I jxcore-log: # 69. #generatePreambleAndBeacons multiple keys to notify
03-24 17:43:33.799  3273  3332 I jxcore-log: 
,03-24 17:43:34.069  3273  3332 I jxcore-log: ok 247 should be equal
03-24 17:43:34.069  3273  3332 I jxcore-log: 
,03-24 17:43:34.069  3273  3332 I jxcore-log: ok 248 should be equal
03-24 17:43:34.069  3273  3332 I jxcore-log: 
,03-24 17:43:34.070  3273  3332 I jxcore-log: ok 249 (unnamed assert)
03-24 17:43:34.070  3273  3332 I jxcore-log: 
03-24 17:43:34.070  3273  3332 I jxcore-log: ok 250 should be equal
03-24 17:43:34.070  3273  3332 I jxcore-log: 
03-24 17:43:34.072  3273  3332 I jxcore-log: # teardown
03-24 17:43:34.072  3273  3332 I jxcore-log: 
,03-24 17:43:34.238  3273  3332 I jxcore-log: # setup
03-24 17:43:34.238  3273  3332 I jxcore-log: 
,03-24 17:43:34.365  3273  3332 I jxcore-log: # 70. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
03-24 17:43:34.365  3273  3332 I jxcore-log: 
,03-24 17:43:34.484  3273  3332 I jxcore-log: ok 251 should throw
03-24 17:43:34.484  3273  3332 I jxcore-log: 
,03-24 17:43:34.487  3273  3332 I jxcore-log: # teardown
03-24 17:43:34.487  3273  3332 I jxcore-log: 
,03-24 17:43:34.610  3273  3332 I jxcore-log: # setup
03-24 17:43:34.610  3273  3332 I jxcore-log: 
,03-24 17:43:34.700  3273  3332 I jxcore-log: # 71. #parseBeacons invalid expiration in beaconStreamWithPreAmble
03-24 17:43:34.700  3273  3332 I jxcore-log: 
,03-24 17:43:34.853  3273  3332 I jxcore-log: ok 252 Preamble expiration must be a 64 bit integer
03-24 17:43:34.853  3273  3332 I jxcore-log: 
,03-24 17:43:34.855  3273  3332 I jxcore-log: # teardown
03-24 17:43:34.855  3273  3332 I jxcore-log: 
,03-24 17:43:34.972  3273  3332 I jxcore-log: # setup
03-24 17:43:34.972  3273  3332 I jxcore-log: 
,03-24 17:43:35.074  3273  3332 I jxcore-log: # 72. #parseBeacons expiration out of range lower
03-24 17:43:35.074  3273  3332 I jxcore-log: 
,03-24 17:43:35.265  3273  3332 I jxcore-log: ok 253 Expiration out of range
03-24 17:43:35.265  3273  3332 I jxcore-log: 
,03-24 17:43:35.268  3273  3332 I jxcore-log: # teardown
03-24 17:43:35.268  3273  3332 I jxcore-log: 
,03-24 17:43:35.370  3273  3332 I jxcore-log: # setup
03-24 17:43:35.370  3273  3332 I jxcore-log: 
,03-24 17:43:35.530  3273  3332 I jxcore-log: # 73. #parseBeacons expiration out of range lower
03-24 17:43:35.530  3273  3332 I jxcore-log: 
,03-24 17:43:35.706  3273  3332 I jxcore-log: ok 254 Expiration out of range
03-24 17:43:35.706  3273  3332 I jxcore-log: 
,03-24 17:43:35.709  3273  3332 I jxcore-log: # teardown
03-24 17:43:35.709  3273  3332 I jxcore-log: 
,03-24 17:43:35.848  3273  3332 I jxcore-log: # setup
03-24 17:43:35.848  3273  3332 I jxcore-log: 
,03-24 17:43:35.964  3273  3332 I jxcore-log: # 74. #parseBeacons no beacons returns null
03-24 17:43:35.964  3273  3332 I jxcore-log: 
,03-24 17:43:36.092  3273  3332 I jxcore-log: ok 255 should be equal
03-24 17:43:36.092  3273  3332 I jxcore-log: 
,03-24 17:43:36.094  3273  3332 I jxcore-log: # teardown
03-24 17:43:36.094  3273  3332 I jxcore-log: 
,03-24 17:43:36.264  3273  3332 I jxcore-log: # setup
03-24 17:43:36.264  3273  3332 I jxcore-log: 
,03-24 17:43:36.392  3273  3332 I jxcore-log: # 75. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
03-24 17:43:36.392  3273  3332 I jxcore-log: 
,03-24 17:43:36.513  3273  3332 I jxcore-log: ok 256 Malformed encrypted beacon key ID
03-24 17:43:36.513  3273  3332 I jxcore-log: 
,03-24 17:43:36.515  3273  3332 I jxcore-log: # teardown
03-24 17:43:36.515  3273  3332 I jxcore-log: 
,03-24 17:43:36.636  3273  3332 I jxcore-log: # setup
03-24 17:43:36.636  3273  3332 I jxcore-log: 
,03-24 17:43:36.778  3273  3332 I jxcore-log: # 76. #parseBeacons addressBookCallback fails decrypt
03-24 17:43:36.778  3273  3332 I jxcore-log: 
,03-24 17:43:36.967  3273  3332 I jxcore-log: ok 257 should be equal
03-24 17:43:36.967  3273  3332 I jxcore-log: 
,03-24 17:43:36.969  3273  3332 I jxcore-log: # teardown
03-24 17:43:36.969  3273  3332 I jxcore-log: 
,03-24 17:43:37.110  3273  3332 I jxcore-log: # setup
03-24 17:43:37.110  3273  3332 I jxcore-log: 
,03-24 17:43:41.155  3273  3332 I jxcore-log: # 77. #parseBeacons addressBookCallback returns no matches
03-24 17:43:41.155  3273  3332 I jxcore-log: 
,03-24 17:43:41.460  3273  3332 I jxcore-log: ok 258 should be equal
,03-24 17:43:41.460  3273  3332 I jxcore-log: 
03-24 17:43:41.460  3273  3332 I jxcore-log: ok 259 should be equal
03-24 17:43:41.460  3273  3332 I jxcore-log: 
03-24 17:43:41.462  3273  3332 I jxcore-log: # teardown
03-24 17:43:41.462  3273  3332 I jxcore-log: 
,03-24 17:43:42.654  3273  3332 I jxcore-log: # setup
03-24 17:43:42.654  3273  3332 I jxcore-log: 
,03-24 17:43:42.764  3273  3332 I jxcore-log: # 78. #parseBeacons addressBookCallback returns spurious match
03-24 17:43:42.764  3273  3332 I jxcore-log: 
,03-24 17:43:44.416  3273  3332 I jxcore-log: ok 260 should be equal
03-24 17:43:44.416  3273  3332 I jxcore-log: 
,03-24 17:43:44.417  3273  3332 I jxcore-log: ok 261 should be equal
03-24 17:43:44.417  3273  3332 I jxcore-log: 
,03-24 17:43:44.426  3273  3332 I jxcore-log: # teardown
03-24 17:43:44.426  3273  3332 I jxcore-log: 
,03-24 17:43:44.440  2157  2223 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 17:43:44.565  3273  3332 I jxcore-log: # setup
03-24 17:43:44.565  3273  3332 I jxcore-log: 
,03-24 17:43:44.701  3273  3332 I jxcore-log: # 79. #parseBeacons addressBookCallback returns public key
03-24 17:43:44.701  3273  3332 I jxcore-log: 
,03-24 17:43:44.945  3273  3332 I jxcore-log: ok 262 right number of calls to address book
03-24 17:43:44.945  3273  3332 I jxcore-log: 
,03-24 17:43:44.947  3273  3332 I jxcore-log: ok 263 good preAmble
03-24 17:43:44.947  3273  3332 I jxcore-log: 
03-24 17:43:44.947  3273  3332 I jxcore-log: ok 264 good unencryptedKeyId
03-24 17:43:44.947  3273  3332 I jxcore-log: 
,03-24 17:43:44.947  3273  3332 I jxcore-log: ok 265 good beacon
03-24 17:43:44.947  3273  3332 I jxcore-log: 
03-24 17:43:44.949  3273  3332 I jxcore-log: # teardown
03-24 17:43:44.949  3273  3332 I jxcore-log: 
,03-24 17:43:45.100  3273  3332 I jxcore-log: # setup
03-24 17:43:45.100  3273  3332 I jxcore-log: 
,03-24 17:43:45.217  3273  3332 I jxcore-log: # 80. validate generatePskIdentityField
03-24 17:43:45.217  3273  3332 I jxcore-log: 
,03-24 17:43:45.377  3273  3332 I jxcore-log: ok 266 decoded buffers match
03-24 17:43:45.377  3273  3332 I jxcore-log: 
,03-24 17:43:45.384  3273  3332 I jxcore-log: # teardown
03-24 17:43:45.384  3273  3332 I jxcore-log: 
,03-24 17:43:45.553  3273  3332 I jxcore-log: # setup
03-24 17:43:45.553  3273  3332 I jxcore-log: 
,03-24 17:43:45.714  3273  3332 I jxcore-log: # 81. validate generatePskSecret
03-24 17:43:45.714  3273  3332 I jxcore-log: 
,03-24 17:43:45.884  3273  3332 I jxcore-log: ok 267 secrets match
03-24 17:43:45.884  3273  3332 I jxcore-log: 
,03-24 17:43:45.886  3273  3332 I jxcore-log: # teardown
03-24 17:43:45.886  3273  3332 I jxcore-log: 
,03-24 17:43:46.038  3273  3332 I jxcore-log: # setup
03-24 17:43:46.038  3273  3332 I jxcore-log: 
,03-24 17:43:46.262  3273  3332 I jxcore-log: # 82. Add two Peers.
03-24 17:43:46.262  3273  3332 I jxcore-log: 
,03-24 17:43:46.459  3273  3332 I jxcore-log: _peerAvailabilityChanged
03-24 17:43:46.459  3273  3332 I jxcore-log: 
,03-24 17:43:46.460  3273  3332 I jxcore-log: peerIdentifier:id123
03-24 17:43:46.460  3273  3332 I jxcore-log: 
,03-24 17:43:46.460  3273  3332 I jxcore-log: connectionType:AndroidBluetooth
03-24 17:43:46.460  3273  3332 I jxcore-log: 
,03-24 17:43:46.460  3273  3332 I jxcore-log: hostAddress:anything
03-24 17:43:46.460  3273  3332 I jxcore-log: 
,03-24 17:43:46.461  3273  3332 I jxcore-log: portNumber:8080
03-24 17:43:46.461  3273  3332 I jxcore-log: 
03-24 17:43:46.461  3273  3332 I jxcore-log: _peerAvailabilityChanged - end
03-24 17:43:46.461  3273  3332 I jxcore-log: 
03-24 17:43:46.468  3273  3332 I jxcore-log: ok 268 should be equal
03-24 17:43:46.468  3273  3332 I jxcore-log: 
,03-24 17:43:46.468  3273  3332 I jxcore-log: _peerAvailabilityChanged
03-24 17:43:46.468  3273  3332 I jxcore-log: 
,03-24 17:43:46.468  3273  3332 I jxcore-log: peerIdentifier:id3212
03-24 17:43:46.468  3273  3332 I jxcore-log: 
03-24 17:43:46.468  3273  3332 I jxcore-log: connectionType:tcp
03-24 17:43:46.468  3273  3332 I jxcore-log: 
,03-24 17:43:46.468  3273  3332 I jxcore-log: hostAddress:anything
03-24 17:43:46.468  3273  3332 I jxcore-log: 
03-24 17:43:46.468  3273  3332 I jxcore-log: portNumber:8080
03-24 17:43:46.468  3273  3332 I jxcore-log: 
03-24 17:43:46.468  3273  3332 I jxcore-log: _peerAvailabilityChanged - end
03-24 17:43:46.468  3273  3332 I jxcore-log: 
,03-24 17:43:46.471  3273  3332 I jxcore-log: ok 269 should be equal
03-24 17:43:46.471  3273  3332 I jxcore-log: 
03-24 17:43:46.471  3273  3332 I jxcore-log: ok 270 should be equal
03-24 17:43:46.471  3273  3332 I jxcore-log: 
,03-24 17:43:46.471  3273  3332 I jxcore-log: ok 271 should be equal
03-24 17:43:46.471  3273  3332 I jxcore-log: 
03-24 17:43:46.473  3273  3332 I jxcore-log: ok 272 should be equal
03-24 17:43:46.473  3273  3332 I jxcore-log: 
,03-24 17:43:46.475  3273  3332 I jxcore-log: # teardown
03-24 17:43:46.475  3273  3332 I jxcore-log: 
,03-24 17:43:46.580  3273  3332 I jxcore-log: killed
03-24 17:43:46.580  3273  3332 I jxcore-log: 
,03-24 17:43:46.591  3273  3332 I jxcore-log: # setup
03-24 17:43:46.591  3273  3332 I jxcore-log: 
,03-24 17:43:46.802  3273  3332 I jxcore-log: # 83. TCP_NATIVE peer loses DNS
03-24 17:43:46.802  3273  3332 I jxcore-log: 
,03-24 17:43:46.950  3273  3332 I jxcore-log: _peerAvailabilityChanged,
03-24 17:43:46.950  3273  3332 I jxcore-log: 
03-24 17:43:46.950  3273  3332 I jxcore-log: peerIdentifier:id124
03-24 17:43:46.950  3273  3332 I jxcore-log: 
03-24 17:43:46.950  3273  3332 I jxcore-log: connectionType:tcp
03-24 17:43:46.950  3273  3332 I jxcore-log: 
,03-24 17:43:46.951  3273  3332 I jxcore-log: hostAddress:127.0.0.1
03-24 17:43:46.951  3273  3332 I jxcore-log: 
03-24 17:43:46.951  3273  3332 I jxcore-log: portNumber:53202
03-24 17:43:46.951  3273  3332 I jxcore-log: 
03-24 17:43:46.951  3273  3332 I jxcore-log: _peerAvailabilityChanged - end
03-24 17:43:46.951  3273  3332 I jxcore-log: 
,03-24 17:43:46.962  3273  3332 I jxcore-log: ok 273 should be equal
03-24 17:43:46.962  3273  3332 I jxcore-log: 
,03-24 17:43:46.963  3273  3332 I jxcore-log: _peerAvailabilityChanged
03-24 17:43:46.963  3273  3332 I jxcore-log: 
03-24 17:43:46.964  3273  3332 I jxcore-log: peerIdentifier:id124
03-24 17:43:46.964  3273  3332 I jxcore-log: 
03-24 17:43:46.964  3273  3332 I jxcore-log: connectionType:tcp,
03-24 17:43:46.964  3273  3332 I jxcore-log: 
,03-24 17:43:46.964  3273  3332 I jxcore-log: hostAddress:undefined
03-24 17:43:46.964  3273  3332 I jxcore-log: 
03-24 17:43:46.964  3273  3332 I jxcore-log: portNumber:53202
03-24 17:43:46.964  3273  3332 I jxcore-log: 
03-24 17:43:46.964  3273  3332 I jxcore-log: _peerAvailabilityChanged - end
03-24 17:43:46.964  3273  3332 I jxcore-log: 
03-24 17:43:46.964  3273  3332 I jxcore-log: ok 274 should be equal
03-24 17:43:46.964  3273  3332 I jxcore-log: 
03-24 17:43:46.967  3273  3332 I jxcore-log: # teardown
03-24 17:43:46.967  3273  3332 I jxcore-log: 
,03-24 17:43:47.089  3273  3332 I jxcore-log: killed
03-24 17:43:47.089  3273  3332 I jxcore-log: 
,03-24 17:43:47.100  3273  3332 I jxcore-log: # setup
03-24 17:43:47.100  3273  3332 I jxcore-log: 
,03-24 17:43:47.337  3273  3332 I jxcore-log: # 84. Resolves an action locally
03-24 17:43:47.337  3273  3332 I jxcore-log: 
,03-24 17:43:47.433  3273  3332 I jxcore-log: _peerAvailabilityChanged
03-24 17:43:47.433  3273  3332 I jxcore-log: 
,03-24 17:43:47.433  3273  3332 I jxcore-log: peerIdentifier:id124
03-24 17:43:47.433  3273  3332 I jxcore-log: 
03-24 17:43:47.433  3273  3332 I jxcore-log: connectionType:tcp
03-24 17:43:47.433  3273  3332 I jxcore-log: 
03-24 17:43:47.433  3273  3332 I jxcore-log: hostAddress:127.0.0.1
03-24 17:43:47.433  3273  3332 I jxcore-log: 
03-24 17:43:47.433  3273  3332 I jxcore-log: portNumber:41335
03-24 17:43:47.433  3273  3332 I jxcore-log: 
03-24 17:43:47.433  3273  3332 I jxcore-log: _peerAvailabilityChanged - end
03-24 17:43:47.433  3273  3332 I jxcore-log: 
,03-24 17:43:47.486  3273  3332 I jxcore-log: ok 275 Host address must match
03-24 17:43:47.486  3273  3332 I jxcore-log: 
,03-24 17:43:47.486  3273  3332 I jxcore-log: ok 276 suggestedTCPTimeout must match
03-24 17:43:47.486  3273  3332 I jxcore-log: 
03-24 17:43:47.487  3273  3332 I jxcore-log: ok 277 connectionType must match
03-24 17:43:47.487  3273  3332 I jxcore-log: 
03-24 17:43:47.487  3273  3332 I jxcore-log: ok 278 portNumber must match
03-24 17:43:47.487  3273  3332 I jxcore-log: 
,03-24 17:43:47.491  3273  3332 I jxcore-log: # teardown
03-24 17:43:47.491  3273  3332 I jxcore-log: 
,03-24 17:43:47.888  3273  3332 I jxcore-log: killed
03-24 17:43:47.888  3273  3332 I jxcore-log: 
,03-24 17:43:47.895  3273  3332 I jxcore-log: # setup
03-24 17:43:47.895  3273  3332 I jxcore-log: 
,03-24 17:43:48.088  3273  3332 I jxcore-log: # 85. Resolves an action locally using ThaliPeerPoolDefault
03-24 17:43:48.088  3273  3332 I jxcore-log: 
,03-24 17:43:48.239  3273  3332 I jxcore-log: _peerAvailabilityChanged
03-24 17:43:48.239  3273  3332 I jxcore-log: 
,03-24 17:43:48.239  3273  3332 I jxcore-log: peerIdentifier:id124
03-24 17:43:48.239  3273  3332 I jxcore-log: 
,03-24 17:43:48.239  3273  3332 I jxcore-log: connectionType:tcp
03-24 17:43:48.239  3273  3332 I jxcore-log: 
03-24 17:43:48.240  3273  3332 I jxcore-log: hostAddress:127.0.0.1
03-24 17:43:48.240  3273  3332 I jxcore-log: 
03-24 17:43:48.240  3273  3332 I jxcore-log: portNumber:44558
03-24 17:43:48.240  3273  3332 I jxcore-log: 
03-24 17:43:48.240  3273  3332 I jxcore-log: _peerAvailabilityChanged - end
03-24 17:43:48.240  3273  3332 I jxcore-log: 
,03-24 17:43:48.307  3273  3332 I jxcore-log: ok 279 Host address must match
03-24 17:43:48.307  3273  3332 I jxcore-log: 
,03-24 17:43:48.308  3273  3332 I jxcore-log: ok 280 suggestedTCPTimeout must match
03-24 17:43:48.308  3273  3332 I jxcore-log: 
03-24 17:43:48.308  3273  3332 I jxcore-log: ok 281 connectionType must match
03-24 17:43:48.308  3273  3332 I jxcore-log: 
03-24 17:43:48.308  3273  3332 I jxcore-log: ok 282 portNumber must match
03-24 17:43:48.308  3273  3332 I jxcore-log: 
,03-24 17:43:48.315  3273  3332 I jxcore-log: # teardown
03-24 17:43:48.315  3273  3332 I jxcore-log: 
,03-24 17:43:48.437  3273  3332 I jxcore-log: killed
03-24 17:43:48.437  3273  3332 I jxcore-log: 
,03-24 17:43:48.445  3273  3332 I jxcore-log: # setup
03-24 17:43:48.445  3273  3332 I jxcore-log: 
,03-24 17:43:48.638  3273  3332 I jxcore-log: # 86. Action fails because of a bad hostname.
03-24 17:43:48.638  3273  3332 I jxcore-log: 
,03-24 17:43:48.776  3273  3332 I jxcore-log: _peerAvailabilityChanged
03-24 17:43:48.776  3273  3332 I jxcore-log: 
,03-24 17:43:48.776  3273  3332 I jxcore-log: peerIdentifier:id123
03-24 17:43:48.776  3273  3332 I jxcore-log: 
03-24 17:43:48.776  3273  3332 I jxcore-log: connectionType:tcp
03-24 17:43:48.776  3273  3332 I jxcore-log: 
03-24 17:43:48.776  3273  3332 I jxcore-log: hostAddress:address-that-does-not-exists
03-24 17:43:48.776  3273  3332 I jxcore-log: 
03-24 17:43:48.776  3273  3332 I jxcore-log: portNumber:123
03-24 17:43:48.776  3273  3332 I jxcore-log: 
,03-24 17:43:48.776  3273  3332 I jxcore-log: _peerAvailabilityChanged - end
03-24 17:43:48.776  3273  3332 I jxcore-log: 
,03-24 17:43:53.783  3273  3332 I jxcore-log: ok 283 should be equal
03-24 17:43:53.783  3273  3332 I jxcore-log: 
,03-24 17:43:53.785  3273  3332 I jxcore-log: ok 284 should be equal
03-24 17:43:53.785  3273  3332 I jxcore-log: 
03-24 17:43:53.787  3273  3332 I jxcore-log: ok 285 should be equal
03-24 17:43:53.787  3273  3332 I jxcore-log: 
,03-24 17:43:53.805  3273  3332 I jxcore-log: # teardown
03-24 17:43:53.805  3273  3332 I jxcore-log: 
,03-24 17:43:54.239  3273  3332 I jxcore-log: killed
03-24 17:43:54.239  3273  3332 I jxcore-log: 
,03-24 17:43:54.250  3273  3332 I jxcore-log: # setup
03-24 17:43:54.250  3273  3332 I jxcore-log: ,
,03-24 17:43:58.108  3273  3332 I jxcore-log: # 87. hostaddress is removed when the action is running. 
03-24 17:43:58.108  3273  3332 I jxcore-log: 
,03-24 17:43:59.775  3273  3332 I jxcore-log: _peerAvailabilityChanged
03-24 17:43:59.775  3273  3332 I jxcore-log: 
03-24 17:43:59.775  3273  3332 I jxcore-log: peerIdentifier:id124
03-24 17:43:59.775  3273  3332 I jxcore-log: 
03-24 17:43:59.775  3273  3332 I jxcore-log: connectionType:tcp
03-24 17:43:59.775  3273  3332 I jxcore-log: 
03-24 17:43:59.775  3273  3332 I jxcore-log: hostAddress:127.0.0.1
03-24 17:43:59.775  3273  3332 I jxcore-log: 
03-24 17:43:59.775  3273  3332 I jxcore-log: portNumber:54769
03-24 17:43:59.775  3273  3332 I jxcore-log: 
03-24 17:43:59.775  3273  3332 I jxcore-log: _peerAvailabilityChanged - end
03-24 17:43:59.775  3273  3332 I jxcore-log: 
,03-24 17:44:00.584  1265  1265 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 17:44:00.637  1265  2585 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,03-24 17:44:00.638  1265  2585 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 17:44:00.638  1265  2585 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 17:44:00.638  1265  2585 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 17:44:00.645  1265  2585 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 17:44:00.700  1265  2585 W GLSActivity: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-24 17:44:00.700  1265  2585 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-24 17:44:00.700  1265  2585 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-24 17:44:00.700  1265  2585 W GLSActivity: 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
03-24 17:44:00.700  1265  2585 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
03-24 17:44:00.700  1265  2585 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
03-24 17:44:00.700  1265  2585 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:446)
,03-24 17:44:00.703  3683  3717 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
03-24 17:44:00.703  3683  3717 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
03-24 17:44:00.703  3683  3717 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
03-24 17:44:00.703  3683  3717 E PlayEventLogger: 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
03-24 17:44:00.703  3683  3717 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
03-24 17:44:00.703  3683  3717 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
03-24 17:44:00.703  3683  3717 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:446)
,03-24 17:44:00.744  3683  3717 W System  : Ignoring header User-Agent because its value was null.
,03-24 17:44:01.781  3273  3332 I jxcore-log: _peerAvailabilityChanged
03-24 17:44:01.781  3273  3332 I jxcore-log: 
03-24 17:44:01.781  3273  3332 I jxcore-log: peerIdentifier:id124
03-24 17:44:01.781  3273  3332 I jxcore-log: 
03-24 17:44:01.781  3273  3332 I jxcore-log: connectionType:tcp
03-24 17:44:01.781  3273  3332 I jxcore-log: 
,03-24 17:44:01.781  3273  3332 I jxcore-log: hostAddress:undefined
03-24 17:44:01.781  3273  3332 I jxcore-log: 
03-24 17:44:01.782  3273  3332 I jxcore-log: portNumber:54769
03-24 17:44:01.782  3273  3332 I jxcore-log: 
03-24 17:44:01.782  3273  3332 I jxcore-log: _peerAvailabilityChanged - end
03-24 17:44:01.782  3273  3332 I jxcore-log: 
,03-24 17:44:01.788  3273  3332 I jxcore-log: ok 286 should be equal
03-24 17:44:01.788  3273  3332 I jxcore-log: 
,03-24 17:44:01.815  3273  3332 I jxcore-log: # teardown
03-24 17:44:01.815  3273  3332 I jxcore-log: 
,03-24 17:44:02.431  3273  3332 I jxcore-log: killed
03-24 17:44:02.431  3273  3332 I jxcore-log: 
,03-24 17:44:02.443  3273  3332 I jxcore-log: # setup
,03-24 17:44:02.443  3273  3332 I jxcore-log: 
,03-24 17:44:02.574  3473  3935 I BooksSync: Starting books sync for 61035162, extras: ade
,03-24 17:44:02.609  3473  3936 I BooksConfig: GmsCore Version = 7.8.99 (2134222-430)
,03-24 17:44:02.638  1265  2585 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-24 17:44:02.638  1265  2585 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 17:44:02.638  1265  2585 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 17:44:02.638  1265  2585 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 17:44:02.642  1265  2585 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 17:44:02.644  1265  1282 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-24 17:44:02.644  1265  1282 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 17:44:02.644  1265  1282 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 17:44:02.644  1265  1282 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 17:44:02.650  1265  1282 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 17:44:02.660  3093  3934 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
03-24 17:44:02.660  3093  3934 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-24 17:44:02.660  3093  3934 E HttpOperation: 	at jdm.a(PG:82)
03-24 17:44:02.660  3093  3934 E HttpOperation: 	at jcs.o(PG:406)
03-24 17:44:02.660  3093  3934 E HttpOperation: 	at jcn.a(PG:1379)
03-24 17:44:02.660  3093  3934 E HttpOperation: 	at jcs.i(PG:143)
03-24 17:44:02.660  3093  3934 E HttpOperation: 	at blb.a(PG:3937)
03-24 17:44:02.660  3093  3934 E HttpOperation: 	at czp.a(PG:18188)
03-24 17:44:02.660  3093  3934 E HttpOperation: 	at czp.a(PG:9081)
03-24 17:44:02.660  3093  3934 E HttpOperation: 	at czq.run(PG:1686)
03-24 17:44:02.660  3093  3934 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-24 17:44:02.660  3093  3934 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 17:44:02.660  3093  3934 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 17:44:02.660  3093  3934 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 17:44:02.660  3093  3934 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-24 17:44:02.660  3093  3934 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-24 17:44:02.660  3093  3934 E HttpOperation: 	at jdj.a(PG:4091)
03-24 17:44:02.660  3093  3934 E HttpOperation: 	at jdj.a(PG:1125)
03-24 17:44:02.660  3093  3934 E HttpOperation: 	at jdm.a(PG:77)
03-24 17:44:02.660  3093  3934 E HttpOperation: 	... 12 more
03-24 17:44:02.660  3093  3934 E HttpOperation: Caused by: faj: BadAuthentication
03-24 17:44:02.660  3093  3934 E HttpOperation: 	at fal.a(PG:38)
03-24 17:44:02.660  3093  3934 E HttpOperation: 	at jdj.a(PG:4089)
03-24 17:44:02.660  3093  3934 E HttpOperation: 	... 14 more
,03-24 17:44:02.708  1265  1603 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-24 17:44:02.708  1265  1603 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 17:44:02.708  1265  1603 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 17:44:02.708  1265  1603 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 17:44:02.715  1265  1603 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 17:44:02.729  3093  3934 E HttpOperation: [getmobileexperiments] Unexpected exception
03-24 17:44:02.729  3093  3934 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-24 17:44:02.729  3093  3934 E HttpOperation: 	at jdm.a(PG:82)
03-24 17:44:02.729  3093  3934 E HttpOperation: 	at jcs.o(PG:406)
03-24 17:44:02.729  3093  3934 E HttpOperation: 	at jcn.a(PG:1379)
03-24 17:44:02.729  3093  3934 E HttpOperation: 	at jcs.i(PG:143)
03-24 17:44:02.729  3093  3934 E HttpOperation: 	at hec.a(PG:42)
03-24 17:44:02.729  3093  3934 E HttpOperation: 	at hee.a(PG:102)
03-24 17:44:02.729  3093  3934 E HttpOperation: 	at czr.a(PG:65)
03-24 17:44:02.729  3093  3934 E HttpOperation: 	at kka.a(PG:108)
03-24 17:44:02.729  3093  3934 E HttpOperation: 	at czp.a(PG:19176)
03-24 17:44:02.729  3093  3934 E HttpOperation: 	at czp.a(PG:9081)
03-24 17:44:02.729  3093  3934 E HttpOperation: 	at czq.run(PG:1686)
03-24 17:44:02.729  3093  3934 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-24 17:44:02.729  3093  3934 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 17:44:02.729  3093  3934 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 17:44:02.729  3093  3934 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 17:44:02.729  3093  3934 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-24 17:44:02.729  3093  3934 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-24 17:44:02.729  3093  3934 E HttpOperation: 	at jdj.a(PG:4091)
03-24 17:44:02.729  3093  3934 E HttpOperation: 	at jdj.a(PG:1125)
03-24 17:44:02.729  3093  3934 E HttpOperation: 	at jdm.a(PG:77)
03-24 17:44:02.729  3093  3934 E HttpOperation: 	... 15 more
03-24 17:44:02.729  3093  3934 E HttpOperation: Caused by: faj: BadAuthentication
03-24 17:44:02.729  3093  3934 E HttpOperation: 	at fal.a(PG:38)
03-24 17:44:02.729  3093  3934 E HttpOperation: 	at jdj.a(PG:4089)
03-24 17:44:02.729  3093  3934 E HttpOperation: 	... 17 more
,03-24 17:44:02.729  3093  3934 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
03-24 17:44:02.729  3093  3934 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
03-24 17:44:02.729  3093  3934 E ExperimentLoader: 	at jdm.a(PG:82)
03-24 17:44:02.729  3093  3934 E ExperimentLoader: 	at jcs.o(PG:406)
03-24 17:44:02.729  3093  3934 E ExperimentLoader: 	at jcn.a(PG:1379)
03-24 17:44:02.729  3093  3934 E ExperimentLoader: 	at jcs.i(PG:143)
03-24 17:44:02.729  3093  3934 E ExperimentLoader: 	at hec.a(PG:42)
03-24 17:44:02.729  3093  3934 E ExperimentLoader: 	at hee.a(PG:102)
03-24 17:44:02.729  3093  3934 E ExperimentLoader: 	at czr.a(PG:65)
03-24 17:44:02.729  3093  3934 E ExperimentLoader: 	at kka.a(PG:108)
03-24 17:44:02.729  3093  3934 E ExperimentLoader: 	at czp.a(PG:19176)
03-24 17:44:02.729  3093  3934 E ExperimentLoader: 	at czp.a(PG:9081)
03-24 17:44:02.729  3093  3934 E ExperimentLoader: 	at czq.run(PG:1686)
03-24 17:44:02.729  3093  3934 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-24 17:44:02.729  3093  3934 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 17:44:02.729  3093  3934 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 17:44:02.729  3093  3934 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 17:44:02.729  3093  3934 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
03-24 17:44:02.729  3093  3934 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-24 17:44:02.729  3093  3934 E ExperimentLoader: 	at jdj.a(PG:4091)
03-24 17:44:02.729  3093  3934 E ExperimentLoader: 	at jdj.a(PG:1125)
03-24 17:44:02.729  3093  3934 E ExperimentLoader: 	at jdm.a(PG:77)
03-24 17:44:02.729  3093  3934 E ExperimentLoader: 	... 15 more
03-24 17:44:02.729  3093  3934 E ExperimentLoader: Caused by: faj: BadAuthentication
03-24 17:44:02.729  3093  3934 E ExperimentLoader: 	at fal.a(PG:38)
03-24 17:44:02.729  3093  3934 E ExperimentLoader: 	at jdj.a(PG:4089)
03-24 17:44:02.729  3093  3934 E ExperimentLoader: 	... 17 more
,03-24 17:44:02.743   823  1417 I art     : Explicit concurrent mark sweep GC freed 36469(1695KB) AllocSpace objects, 7(206KB) LOS objects, 31% free, 34MB/50MB, paused 1.465ms total 67.399ms
,03-24 17:44:02.788  1265  2584 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-24 17:44:02.788  1265  2584 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 17:44:02.788  1265  2584 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 17:44:02.788  1265  2584 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 17:44:02.791  1265  2584 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 17:44:02.802  3473  3936 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,03-24 17:44:02.803  3473  3935 E BooksSync: Soft error
03-24 17:44:02.803  3473  3935 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-24 17:44:02.803  3473  3935 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-24 17:44:02.803  3473  3935 E BooksSync: Sync error
03-24 17:44:02.803  3473  3935 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-24 17:44:02.803  3473  3935 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-24 17:44:02.803  3473  3935 I BooksSync: Finished books sync
,03-24 17:44:02.807   823   856 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 455214, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-24 17:44:02.823   823   856 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 453508, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-24 17:44:03.809  3273  3332 I jxcore-log: # 88. Start and stop ThaliNotificationServer
03-24 17:44:03.809  3273  3332 I jxcore-log: 
,03-24 17:44:07.858  2157  2223 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 17:44:09.353  3273  3332 I jxcore-log: ok 287 ThaliMobile.StartUpdateAdvertisingAndListening should be called once
03-24 17:44:09.353  3273  3332 I jxcore-log: 
,03-24 17:44:09.353  3273  3332 I jxcore-log: ok 288 ThaliMobile.StopAdvertisingAndListeningshould be called once
03-24 17:44:09.353  3273  3332 I jxcore-log: 
,03-24 17:44:09.355  3273  3332 I jxcore-log: # teardown
03-24 17:44:09.355  3273  3332 I jxcore-log: 
,03-24 17:44:10.201  3273  3332 I jxcore-log: # setup
03-24 17:44:10.201  3273  3332 I jxcore-log: 
,03-24 17:44:10.384  3273  3332 I jxcore-log: # 89. Pass an empty array to ThaliNotificationServer.start
03-24 17:44:10.384  3273  3332 I jxcore-log: 
,03-24 17:44:10.920  3273  3332 I jxcore-log: ok 289 StartUpdateAdvertisingAndListening should not be called
03-24 17:44:10.920  3273  3332 I jxcore-log: 
,03-24 17:44:10.935  3273  3332 I jxcore-log: ok 290 ThaliMobile.StopAdvertisingAndListening should be called once
03-24 17:44:10.935  3273  3332 I jxcore-log: 
,03-24 17:44:10.976  3273  3332 I jxcore-log: ok 291 no error
03-24 17:44:10.976  3273  3332 I jxcore-log: 
,03-24 17:44:10.977  3273  3332 I jxcore-log: ok 292 should be 204
03-24 17:44:10.977  3273  3332 I jxcore-log: 
,03-24 17:44:10.983  3273  3332 I jxcore-log: # teardown
03-24 17:44:10.983  3273  3332 I jxcore-log: 
,03-24 17:44:11.186  3273  3332 I jxcore-log: # setup
03-24 17:44:11.186  3273  3332 I jxcore-log: 
,03-24 17:44:11.329  3273  3332 I jxcore-log: # 90. Pass a string to ThaliNotificationServer.start
03-24 17:44:11.329  3273  3332 I jxcore-log: 
,03-24 17:44:11.537  3273  3332 I jxcore-log: ok 293 StartUpdateAdvertisingAndListening should not be called
,03-24 17:44:11.537  3273  3332 I jxcore-log: 
03-24 17:44:11.540  3273  3332 I jxcore-log: # teardown
03-24 17:44:11.540  3273  3332 I jxcore-log: 
,03-24 17:44:11.737  3273  3332 I jxcore-log: # setup
03-24 17:44:11.737  3273  3332 I jxcore-log: 
,03-24 17:44:11.884  3273  3332 I jxcore-log: # 91. Pass an empty parameter to ThaliNotificationServer.start
03-24 17:44:11.884  3273  3332 I jxcore-log: 
,03-24 17:44:12.127  3273  3332 I jxcore-log: ok 294 StartUpdateAdvertisingAndListening should not be called
03-24 17:44:12.127  3273  3332 I jxcore-log: 
,03-24 17:44:12.134  3273  3332 I jxcore-log: # teardown
03-24 17:44:12.134  3273  3332 I jxcore-log: 
,03-24 17:44:12.326  3273  3332 I jxcore-log: # setup
03-24 17:44:12.326  3273  3332 I jxcore-log: 
,03-24 17:44:12.517  3273  3332 I jxcore-log: # 92. Make an HTTP request to /NotificationBeacons
03-24 17:44:12.517  3273  3332 I jxcore-log: 
,03-24 17:44:12.736  3273  3332 I jxcore-log: ok 295 no error
03-24 17:44:12.736  3273  3332 I jxcore-log: 
03-24 17:44:12.736  3273  3332 I jxcore-log: ok 296 should be 200
03-24 17:44:12.736  3273  3332 I jxcore-log: 
03-24 17:44:12.737  3273  3332 I jxcore-log: ok 297 should be equal
03-24 17:44:12.737  3273  3332 I jxcore-log: 
03-24 17:44:12.737  3273  3332 I jxcore-log: ok 298 should be equal
03-24 17:44:12.737  3273  3332 I jxcore-log: 
,03-24 17:44:12.753  3273  3332 I jxcore-log: ok 299 (unnamed assert)
03-24 17:44:12.753  3273  3332 I jxcore-log: 
,03-24 17:44:12.775  3273  3332 I jxcore-log: ok 300 no error
03-24 17:44:12.775  3273  3332 I jxcore-log: 
,03-24 17:44:12.776  3273  3332 I jxcore-log: ok 301 should be 204
03-24 17:44:12.776  3273  3332 I jxcore-log: 
,03-24 17:44:12.780  3273  3332 I jxcore-log: # teardown
03-24 17:44:12.780  3273  3332 I jxcore-log: 
,03-24 17:44:12.918  3273  3332 I jxcore-log: # setup
03-24 17:44:12.918  3273  3332 I jxcore-log: 
,03-24 17:44:13.124  3273  3332 I jxcore-log: # 93. Make an HTTP request to /NotificationBeacons (no keys)
03-24 17:44:13.124  3273  3332 I jxcore-log: 
,03-24 17:44:13.290  3273  3332 I jxcore-log: ok 302 error should be null
03-24 17:44:13.290  3273  3332 I jxcore-log: 
,03-24 17:44:13.290  3273  3332 I jxcore-log: ok 303 should be 204
03-24 17:44:13.290  3273  3332 I jxcore-log: 
,03-24 17:44:13.296  3273  3332 I jxcore-log: # teardown
03-24 17:44:13.296  3273  3332 I jxcore-log: 
,03-24 17:44:13.407  3273  3332 I jxcore-log: # setup
03-24 17:44:13.407  3273  3332 I jxcore-log: 
,03-24 17:44:13.632  3273  3332 I jxcore-log: # 94. Make an HTTP request to /NotificationBeaconsbefore calling start
03-24 17:44:13.632  3273  3332 I jxcore-log: 
,03-24 17:44:13.795  3273  3332 I jxcore-log: ok 304 should be 404
03-24 17:44:13.795  3273  3332 I jxcore-log: 
,03-24 17:44:13.802  3273  3332 I jxcore-log: # teardown
03-24 17:44:13.802  3273  3332 I jxcore-log: 
,03-24 17:44:13.941  3273  3332 I jxcore-log: # setup
03-24 17:44:13.941  3273  3332 I jxcore-log: 
,03-24 17:44:14.081  3273  3332 I jxcore-log: # 95. #testThaliPeerAction - test getters,
03-24 17:44:14.081  3273  3332 I jxcore-log: 
,03-24 17:44:14.253  3273  3332 I jxcore-log: ok 305 getPeerIdentifier,
03-24 17:44:14.253  3273  3332 I jxcore-log: 
03-24 17:44:14.255  3273  3332 I jxcore-log: ok 306 getConnectionType
03-24 17:44:14.255  3273  3332 I jxcore-log: 
03-24 17:44:14.257  3273  3332 I jxcore-log: ok 307 getActionType
03-24 17:44:14.257  3273  3332 I jxcore-log: 
,03-24 17:44:14.258  3273  3332 I jxcore-log: ok 308 getActionState
03-24 17:44:14.258  3273  3332 I jxcore-log: 
03-24 17:44:14.266  3273  3332 I jxcore-log: # teardown
03-24 17:44:14.266  3273  3332 I jxcore-log: 
,03-24 17:44:14.384  3273  3332 I jxcore-log: # setup
,03-24 17:44:14.384  3273  3332 I jxcore-log: 
,03-24 17:44:14.490  3273  3332 I jxcore-log: # 96. #testThaliPeerAction - start and kill
03-24 17:44:14.490  3273  3332 I jxcore-log: 
,03-24 17:44:14.624  3273  3332 I jxcore-log: ok 309 initial state
,03-24 17:44:14.624  3273  3332 I jxcore-log: 
03-24 17:44:14.625  3273  3332 I jxcore-log: ok 310 after start
03-24 17:44:14.625  3273  3332 I jxcore-log: 
,03-24 17:44:14.626  3273  3332 I jxcore-log: ok 311 after kill
03-24 17:44:14.626  3273  3332 I jxcore-log: 
,03-24 17:44:14.630  3273  3332 I jxcore-log: # teardown
,03-24 17:44:14.630  3273  3332 I jxcore-log: 
,03-24 17:44:15.844  3273  3332 I jxcore-log: # setup,
03-24 17:44:15.844  3273  3332 I jxcore-log: 
,03-24 17:44:15.997  3273  3332 I jxcore-log: # 97. #testThaliPeerAction - double start
03-24 17:44:15.997  3273  3332 I jxcore-log: 
,03-24 17:44:16.335  3273  3332 I jxcore-log: ok 312 should be equal
,03-24 17:44:16.335  3273  3332 I jxcore-log: 
,03-24 17:44:16.338  3273  3332 I jxcore-log: # teardown
03-24 17:44:16.338  3273  3332 I jxcore-log: 
,03-24 17:44:16.524  3273  3332 I jxcore-log: # setup
,03-24 17:44:16.524  3273  3332 I jxcore-log: 
,03-24 17:44:16.725  3273  3332 I jxcore-log: # 98. #testThaliPeerAction - start after kill
03-24 17:44:16.725  3273  3332 I jxcore-log: ,
,03-24 17:44:16.963  3273  3332 I jxcore-log: ok 313 clean kill
,03-24 17:44:16.963  3273  3332 I jxcore-log: 
03-24 17:44:16.966  3273  3332 I jxcore-log: ok 314 should be equal
03-24 17:44:16.966  3273  3332 I jxcore-log: 
03-24 17:44:16.968  3273  3332 I jxcore-log: # teardown
03-24 17:44:16.968  3273  3332 I jxcore-log: 
,03-24 17:44:17.179  3273  3332 I jxcore-log: # setup
03-24 17:44:17.179  3273  3332 I jxcore-log: 
,03-24 17:44:17.395  3273  3332 I jxcore-log: # 99. #testThaliPeerAction - make sure ids are unique
,03-24 17:44:17.395  3273  3332 I jxcore-log: 
,03-24 17:44:17.831  3273  3332 I jxcore-log: ok 315 should not be equal,
03-24 17:44:17.831  3273  3332 I jxcore-log: 
,03-24 17:44:17.844  3273  3332 I jxcore-log: # teardown
03-24 17:44:17.844  3273  3332 I jxcore-log: 
,03-24 17:44:18.757  3273  3332 I jxcore-log: # setup
03-24 17:44:18.757  3273  3332 I jxcore-log: ,
,03-24 17:44:18.944  3273  3332 I jxcore-log: # 100. Test PeerConnectionInformation basics,
03-24 17:44:18.944  3273  3332 I jxcore-log: 
,03-24 17:44:19.499  3273  3332 I jxcore-log: ok 316 connection type works
03-24 17:44:19.499  3273  3332 I jxcore-log: 
,03-24 17:44:19.500  3273  3332 I jxcore-log: ok 317 getHostAddress works
03-24 17:44:19.500  3273  3332 I jxcore-log: 
03-24 17:44:19.502  3273  3332 I jxcore-log: ok 318 getPortNumber works
03-24 17:44:19.502  3273  3332 I jxcore-log: 
,03-24 17:44:19.504  3273  3332 I jxcore-log: ok 319 getSuggestedTCPTimeout works
03-24 17:44:19.504  3273  3332 I jxcore-log: 
03-24 17:44:19.507  3273  3332 I jxcore-log: # teardown,
03-24 17:44:19.507  3273  3332 I jxcore-log: 
,03-24 17:44:19.720  3273  3332 I jxcore-log: # setup
,03-24 17:44:19.720  3273  3332 I jxcore-log: 
,03-24 17:44:20.251  3273  3332 I jxcore-log: # 101. Test PeerDictionary basic functionality
03-24 17:44:20.251  3273  3332 I jxcore-log: 
,03-24 17:44:22.830  3273  3332 I jxcore-log: ok 320 Entry counter must be 1
03-24 17:44:22.830  3273  3332 I jxcore-log: 
,03-24 17:44:22.830  3273  3332 I jxcore-log: ok 321 Size must be 1
03-24 17:44:22.830  3273  3332 I jxcore-log: 
03-24 17:44:22.831  3273  3332 I jxcore-log: ok 322 Entry counter must be 2
03-24 17:44:22.831  3273  3332 I jxcore-log: 
03-24 17:44:22.831  3273  3332 I jxcore-log: ok 323 Size must be 2
03-24 17:44:22.831  3273  3332 I jxcore-log: 
,03-24 17:44:22.837  3273  3332 I jxcore-log: ok 324 Entry2 should not be found
03-24 17:44:22.837  3273  3332 I jxcore-log: 
,03-24 17:44:22.837  3273  3332 I jxcore-log: ok 325 Size must be 1
03-24 17:44:22.837  3273  3332 I jxcore-log: 
03-24 17:44:22.838  3273  3332 I jxcore-log: ok 326 Size must be 0
03-24 17:44:22.838  3273  3332 I jxcore-log: 
,03-24 17:44:22.844  3273  3332 I jxcore-log: # teardown
03-24 17:44:22.844  3273  3332 I jxcore-log: 
,03-24 17:44:24.764  3273  3332 I jxcore-log: # setup
03-24 17:44:24.764  3273  3332 I jxcore-log: 
,03-24 17:44:25.781  3273  3332 I jxcore-log: # 102. Test PeerDictionary with multiple entries.
03-24 17:44:25.781  3273  3332 I jxcore-log: 
,03-24 17:44:33.064  3273  3332 I jxcore-log: ok 327 Size must be100
03-24 17:44:33.064  3273  3332 I jxcore-log: 
,03-24 17:44:33.067  3273  3332 I jxcore-log: ok 328 Entries between 20 and MAXSIZE + 20 should exist
03-24 17:44:33.067  3273  3332 I jxcore-log: 
,03-24 17:44:33.775  3273  3332 I jxcore-log: ok 329 WAITING state entry should not be removed
03-24 17:44:33.775  3273  3332 I jxcore-log: 
,03-24 17:44:33.781  3273  3332 I jxcore-log: # teardown
03-24 17:44:33.781  3273  3332 I jxcore-log: 
,03-24 17:44:34.054  3273  3332 I jxcore-log: # setup
03-24 17:44:34.054  3273  3332 I jxcore-log: 
,03-24 17:44:35.599  3273  3332 I jxcore-log: # 103. RESOLVED entries are removed before WAITING state entry.
03-24 17:44:35.599  3273  3332 I jxcore-log: 
,03-24 17:44:38.509  3273  3332 I jxcore-log: ok 330 Entries between 6 and MAXSIZE + 4 should exist
03-24 17:44:38.509  3273  3332 I jxcore-log: 
03-24 17:44:38.510  3273  3332 I jxcore-log: ok 331 Size should be MAXSIZE
03-24 17:44:38.510  3273  3332 I jxcore-log: 
03-24 17:44:38.510  3273  3332 I jxcore-log: ok 332 Size should be MAXSIZE+6
03-24 17:44:38.510  3273  3332 I jxcore-log: 
,03-24 17:44:38.514  3273  3332 I jxcore-log: # teardown
03-24 17:44:38.514  3273  3332 I jxcore-log: 
,03-24 17:44:39.915  3273  3332 I jxcore-log: # setup
03-24 17:44:39.915  3273  3332 I jxcore-log: 
,03-24 17:44:40.394  3273  3332 I jxcore-log: # 104. WAITING entries are removed before CONTROLLED_BY_POOL state entry.
03-24 17:44:40.394  3273  3332 I jxcore-log: 
,03-24 17:44:42.489  3273  3332 I jxcore-log: ok 333 WAITING state entry should not be removed
03-24 17:44:42.489  3273  3332 I jxcore-log: 
,03-24 17:44:42.490  3273  3332 I jxcore-log: ok 334 Waiting entries between 6 and MAXSIZE + 4 should exist
03-24 17:44:42.490  3273  3332 I jxcore-log: 
03-24 17:44:42.491  3273  3332 I jxcore-log: ok 335 Size should be MAXSIZE
03-24 17:44:42.491  3273  3332 I jxcore-log: 
03-24 17:44:42.491  3273  3332 I jxcore-log: ok 336 entryCounter should be MAXSIZE+6
03-24 17:44:42.491  3273  3332 I jxcore-log: 
,03-24 17:44:42.494  3273  3332 I jxcore-log: # teardown
03-24 17:44:42.494  3273  3332 I jxcore-log: 
,03-24 17:44:43.695  3273  3332 I jxcore-log: # setup
03-24 17:44:43.695  3273  3332 I jxcore-log: 
,03-24 17:44:44.604  2157  2223 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 17:44:46.040  3273  3332 I jxcore-log: # 105. When CONTROLLED_BY_POOL entry is removed and kill is called.
03-24 17:44:46.040  3273  3332 I jxcore-log: 
,03-24 17:44:47.706  3273  3332 I jxcore-log: ok 337 Kill should be called once
03-24 17:44:47.706  3273  3332 I jxcore-log: ,
03-24 17:44:47.706  3273  3332 I jxcore-log: ok 338 Size should be 100
03-24 17:44:47.706  3273  3332 I jxcore-log: 
,03-24 17:44:47.709  3273  3332 I jxcore-log: # teardown
03-24 17:44:47.709  3273  3332 I jxcore-log: 
,03-24 17:44:49.493  3273  3332 I jxcore-log: # setup
03-24 17:44:49.493  3273  3332 I jxcore-log: 
,03-24 17:44:58.586  3273  3332 I jxcore-log: # 106. #ThaliPeerPoolInterface - bad enqueues
03-24 17:44:58.586  3273  3332 I jxcore-log: 
,03-24 17:45:02.685  3374  3947 V GoogleAuthProtoRequest: [348] a.<init>: mAccountName set to: thalitester@gmail.com
,03-24 17:45:02.767  1265  1281 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
03-24 17:45:02.767  1265  1281 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 17:45:02.767  1265  1281 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-24 17:45:02.769  1265  1281 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 17:45:02.774  1265  1281 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 17:45:02.786  3374  3947 W ExperimentUpdateService: [348] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,03-24 17:45:02.787  3374  3947 W ExperimentUpdateService: [348] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-24 17:45:02.787  3374  3947 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-24 17:45:02.787  3374  3947 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-24 17:45:02.787  3374  3947 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-24 17:45:02.787  3374  3947 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-24 17:45:02.787  3374  3947 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-24 17:45:02.787  3374  3947 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-24 17:45:02.787  3374  3947 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-24 17:45:02.787  3374  3947 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-24 17:45:02.787  3374  3947 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-24 17:45:02.787  3374  3947 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-24 17:45:07.860  2157  2223 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 17:45:19.156  3273  3332 I jxcore-log: ok 339 null arg
03-24 17:45:19.156  3273  3332 I jxcore-log: 
,03-24 17:45:19.162  3273  3332 I jxcore-log: ok 340 wrong arg type,
03-24 17:45:19.162  3273  3332 I jxcore-log: 
,03-24 17:45:19.165  3273  3332 I jxcore-log: ok 341 wrong state
,03-24 17:45:19.165  3273  3332 I jxcore-log: 
,03-24 17:45:19.170  3273  3332 I jxcore-log: # teardown
,03-24 17:45:19.170  3273  3332 I jxcore-log: 
,03-24 17:46:00.893  3273  3332 I jxcore-log: # setup
03-24 17:46:00.893  3273  3332 I jxcore-log: 
,03-24 17:46:07.854  2157  2223 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 17:46:10.007  3273  3332 I jxcore-log: # 107. #ThaliPeerPoolInterface - do not allow same object type
03-24 17:46:10.007  3273  3332 I jxcore-log: 
,03-24 17:46:10.117  3273  3332 I jxcore-log: ok 342 good enqueue
03-24 17:46:10.117  3273  3332 I jxcore-log: 
,03-24 17:46:10.122  3273  3332 I jxcore-log: ok 343 should be equal
03-24 17:46:10.122  3273  3332 I jxcore-log: 
,03-24 17:46:10.130  3273  3332 I jxcore-log: # teardown
03-24 17:46:10.130  3273  3332 I jxcore-log: ,
,03-24 17:46:10.623  3273  3332 I jxcore-log: # setup
03-24 17:46:10.623  3273  3332 I jxcore-log: 
,03-24 17:46:10.865  3273  3332 I jxcore-log: # 108. #ThaliPeerPoolInterface - make sure we catch kill and dequeue
03-24 17:46:10.865  3273  3332 I jxcore-log: 
,03-24 17:46:11.444  3273  3332 I jxcore-log: ok 344 good enqueue
03-24 17:46:11.444  3273  3332 I jxcore-log: 
03-24 17:46:11.445  3273  3332 I jxcore-log: ok 345 2nd good enqueue
03-24 17:46:11.445  3273  3332 I jxcore-log: 
03-24 17:46:11.445  3273  3332 I jxcore-log: ok 346 we are in the pool
03-24 17:46:11.445  3273  3332 I jxcore-log: 
03-24 17:46:11.448  3273  3332 I jxcore-log: ok 347 We are out of the pool
03-24 17:46:11.448  3273  3332 I jxcore-log: 
03-24 17:46:11.448  3273  3332 I jxcore-log: ok 348 Action was killed
03-24 17:46:11.448  3273  3332 I jxcore-log: 
03-24 17:46:11.448  3273  3332 I jxcore-log: ok 349 The original kill was called too
03-24 17:46:11.448  3273  3332 I jxcore-log: 
03-24 17:46:11.449  3273  3332 I jxcore-log: ok 350 second item is still in queue
03-24 17:46:11.449  3273  3332 I jxcore-log: 
03-24 17:46:11.451  3273  3332 I jxcore-log: # teardown
03-24 17:46:11.451  3273  3332 I jxcore-log: 
,03-24 17:46:11.681  3273  3332 I jxcore-log: # setup
03-24 17:46:11.681  3273  3332 I jxcore-log: 
,03-24 17:46:11.976  3273  3332 I jxcore-log: # 109. #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent
03-24 17:46:11.976  3273  3332 I jxcore-log: 
,03-24 17:46:12.155  3273  3332 I jxcore-log: ok 351 good enqueue
03-24 17:46:12.155  3273  3332 I jxcore-log: 
,03-24 17:46:12.157  3273  3332 I jxcore-log: ok 352 first kill
03-24 17:46:12.157  3273  3332 I jxcore-log: 
,03-24 17:46:12.159  3273  3332 I jxcore-log: ok 353 second NOOP kill
03-24 17:46:12.159  3273  3332 I jxcore-log: 
,03-24 17:46:12.165  3273  3332 I jxcore-log: # teardown
03-24 17:46:12.165  3273  3332 I jxcore-log: 
,03-24 17:46:12.368  3273  3332 I jxcore-log: # setup
03-24 17:46:12.368  3273  3332 I jxcore-log: 
,03-24 17:46:12.518  3273  3332 I jxcore-log: # 110. compareBufferArrays
03-24 17:46:12.518  3273  3332 I jxcore-log: 
,03-24 17:46:12.646  3273  3332 I jxcore-log: ok 354 should throw
,03-24 17:46:12.646  3273  3332 I jxcore-log: 
03-24 17:46:12.647  3273  3332 I jxcore-log: ok 355 should throw
03-24 17:46:12.647  3273  3332 I jxcore-log: 
03-24 17:46:12.648  3273  3332 I jxcore-log: ok 356 (unnamed assert)
03-24 17:46:12.648  3273  3332 I jxcore-log: 
,03-24 17:46:12.648  3273  3332 I jxcore-log: ok 357 (unnamed assert)
03-24 17:46:12.648  3273  3332 I jxcore-log: 
03-24 17:46:12.649  3273  3332 I jxcore-log: ok 358 (unnamed assert)
03-24 17:46:12.649  3273  3332 I jxcore-log: 
,03-24 17:46:12.649  3273  3332 I jxcore-log: ok 359 (unnamed assert)
03-24 17:46:12.649  3273  3332 I jxcore-log: 
03-24 17:46:12.650  3273  3332 I jxcore-log: ok 360 (unnamed assert)
03-24 17:46:12.650  3273  3332 I jxcore-log: 
,03-24 17:46:12.654  3273  3332 I jxcore-log: # teardown
03-24 17:46:12.654  3273  3332 I jxcore-log: 
,03-24 17:46:14.024  3273  3332 I jxcore-log: # setup
03-24 17:46:14.024  3273  3332 I jxcore-log: 
,03-24 17:46:14.513  3273  3332 I jxcore-log: # 111. Call start twice and get error
03-24 17:46:14.513  3273  3332 I jxcore-log: 
,03-24 17:46:14.637  3273  3332 I jxcore-log: ok 361 should throw
03-24 17:46:14.637  3273  3332 I jxcore-log: 
,03-24 17:46:14.645  3273  3332 I jxcore-log: # teardown
03-24 17:46:14.645  3273  3332 I jxcore-log: 
,03-24 17:46:14.805  3273  3332 I jxcore-log: # setup
03-24 17:46:14.805  3273  3332 I jxcore-log: 
,03-24 17:46:15.666  3273  3332 I jxcore-log: # 112. Start and make sure it runs
03-24 17:46:15.666  3273  3332 I jxcore-log: 
,03-24 17:46:15.808  3273  3332 I jxcore-log: # teardown
03-24 17:46:15.808  3273  3332 I jxcore-log: 
,03-24 17:46:15.915  3273  3332 I jxcore-log: # setup
03-24 17:46:15.915  3273  3332 I jxcore-log: 
,03-24 17:46:16.065  3273  3332 I jxcore-log: # 113. Make sure getTimeWhenRun is right after start
03-24 17:46:16.065  3273  3332 I jxcore-log: 
,03-24 17:46:16.227  3273  3332 I jxcore-log: ok 362 (unnamed assert)
03-24 17:46:16.227  3273  3332 I jxcore-log: 
,03-24 17:46:16.234  3273  3332 I jxcore-log: # teardown
03-24 17:46:16.234  3273  3332 I jxcore-log: 
,03-24 17:46:16.416  3273  3332 I jxcore-log: # setup
03-24 17:46:16.416  3273  3332 I jxcore-log: 
,03-24 17:46:16.558  3273  3332 I jxcore-log: # 114. Make sure getTimeWhenRun is -1 after function is called
03-24 17:46:16.558  3273  3332 I jxcore-log: 
,03-24 17:46:16.654  3273  3332 I jxcore-log: ok 363 should be equal
03-24 17:46:16.654  3273  3332 I jxcore-log: 
03-24 17:46:16.658  3273  3332 I jxcore-log: # teardown
03-24 17:46:16.658  3273  3332 I jxcore-log: 
,03-24 17:46:16.779  3273  3332 I jxcore-log: # setup
03-24 17:46:16.779  3273  3332 I jxcore-log: 
,03-24 17:46:16.947  3273  3332 I jxcore-log: # 115. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running
03-24 17:46:16.947  3273  3332 I jxcore-log: 
,03-24 17:46:17.097  3273  3332 I jxcore-log: ok 364 should be equal
03-24 17:46:17.097  3273  3332 I jxcore-log: 
,03-24 17:46:17.098  3273  3332 I jxcore-log: ok 365 should be equal
03-24 17:46:17.098  3273  3332 I jxcore-log: 
,03-24 17:46:17.101  3273  3332 I jxcore-log: ok 366 should throw
03-24 17:46:17.101  3273  3332 I jxcore-log: 
,03-24 17:46:17.108  3273  3332 I jxcore-log: # teardown
03-24 17:46:17.108  3273  3332 I jxcore-log: 
,03-24 17:46:17.316  3273  3332 I jxcore-log: # setup,
03-24 17:46:17.316  3273  3332 I jxcore-log: 
,03-24 17:46:17.509  3273  3332 I jxcore-log: # 116. Test TransientState,
03-24 17:46:17.509  3273  3332 I jxcore-log: 
,03-24 17:46:17.647  3273  3332 I jxcore-log: ok 367 should throw
03-24 17:46:17.647  3273  3332 I jxcore-log: 
,03-24 17:46:17.653  3273  3332 I jxcore-log: ok 368 should throw
03-24 17:46:17.653  3273  3332 I jxcore-log: 
,03-24 17:46:17.654  3273  3332 I jxcore-log: ok 369 should be equal
03-24 17:46:17.654  3273  3332 I jxcore-log: 
,03-24 17:46:17.654  3273  3332 I jxcore-log: ok 370 should be equal
03-24 17:46:17.654  3273  3332 I jxcore-log: 
03-24 17:46:17.655  3273  3332 I jxcore-log: ok 371 should be equal
03-24 17:46:17.655  3273  3332 I jxcore-log: 
03-24 17:46:17.655  3273  3332 I jxcore-log: ok 372 should be equal
03-24 17:46:17.655  3273  3332 I jxcore-log: 
,03-24 17:46:17.656  3273  3332 I jxcore-log: ok 373 (unnamed assert)
03-24 17:46:17.656  3273  3332 I jxcore-log: 
03-24 17:46:17.656  3273  3332 I jxcore-log: ok 374 (unnamed assert),
03-24 17:46:17.656  3273  3332 I jxcore-log: 
03-24 17:46:17.659  3273  3332 I jxcore-log: # teardown
03-24 17:46:17.659  3273  3332 I jxcore-log: 
,03-24 17:46:17.769  3273  3332 I jxcore-log: # setup
03-24 17:46:17.769  3273  3332 I jxcore-log: 
,03-24 17:46:17.920  3273  3332 I jxcore-log: # 117. No peers and empty database
03-24 17:46:17.920  3273  3332 I jxcore-log: 
,03-24 17:46:18.266  3273  3332 I jxcore-log: ok 375 verify failed
03-24 17:46:18.266  3273  3332 I jxcore-log: 
,03-24 17:46:18.266  3273  3332 I jxcore-log: ok 376 constructor called once
03-24 17:46:18.266  3273  3332 I jxcore-log: ,
03-24 17:46:18.268  3273  3332 I jxcore-log: ok 377 constructor called with right args
03-24 17:46:18.268  3273  3332 I jxcore-log: 
03-24 17:46:18.269  3273  3332 I jxcore-log: ok 378 match start arg
03-24 17:46:18.269  3273  3332 I jxcore-log: 
,03-24 17:46:18.270  3273  3332 I jxcore-log: ok 379 start called once
03-24 17:46:18.270  3273  3332 I jxcore-log: 
,03-24 17:46:18.270  3273  3332 I jxcore-log: ok 380 stop called once
03-24 17:46:18.270  3273  3332 I jxcore-log: 
03-24 17:46:18.270  3273  3332 I jxcore-log: ok 381 stop after start
03-24 17:46:18.270  3273  3332 I jxcore-log: 
,03-24 17:46:18.276  3273  3332 I jxcore-log: # teardown
03-24 17:46:18.276  3273  3332 I jxcore-log: 
,03-24 17:46:19.325  3273  3332 I jxcore-log: # setup
03-24 17:46:19.325  3273  3332 I jxcore-log: 
,03-24 17:46:19.803  3273  3332 I jxcore-log: # 118. One peer and empty DB
03-24 17:46:19.803  3273  3332 I jxcore-log: 
,03-24 17:46:20.135  3273  3332 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-24 17:46:20.135  3273  3332 I jxcore-log: ,
03-24 17:46:20.137  3273  3332 I jxcore-log: ok 382 verify failed
03-24 17:46:20.137  3273  3332 I jxcore-log: 
03-24 17:46:20.137  3273  3332 I jxcore-log: ok 383 constructor called once
03-24 17:46:20.137  3273  3332 I jxcore-log: 
03-24 17:46:20.138  3273  3332 I jxcore-log: ok 384 constructor called with right args
03-24 17:46:20.138  3273  3332 I jxcore-log: 
,03-24 17:46:20.138  3273  3332 I jxcore-log: ok 385 match start arg
03-24 17:46:20.138  3273  3332 I jxcore-log: 
03-24 17:46:20.139  3273  3332 I jxcore-log: ok 386 start called once
03-24 17:46:20.139  3273  3332 I jxcore-log: 
03-24 17:46:20.139  3273  3332 I jxcore-log: ok 387 stop called once
03-24 17:46:20.139  3273  3332 I jxcore-log: 
03-24 17:46:20.139  3273  3332 I jxcore-log: ok 388 stop after start
03-24 17:46:20.139  3273  3332 I jxcore-log: 
,03-24 17:46:20.146  3273  3332 I jxcore-log: # teardown
03-24 17:46:20.146  3273  3332 I jxcore-log: 
,03-24 17:46:20.451  3273  3332 I jxcore-log: # setup
03-24 17:46:20.451  3273  3332 I jxcore-log: 
,03-24 17:46:22.464  3273  3332 I jxcore-log: # 119. One peer with _Local set behind current seq
03-24 17:46:22.464  3273  3332 I jxcore-log: 
,03-24 17:46:24.422  3273  3332 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-24 17:46:24.422  3273  3332 I jxcore-log: 
,03-24 17:46:24.424  3273  3332 I jxcore-log: ok 389 verify failed
03-24 17:46:24.424  3273  3332 I jxcore-log: 
,03-24 17:46:24.424  3273  3332 I jxcore-log: ok 390 constructor called once
03-24 17:46:24.424  3273  3332 I jxcore-log: 
,03-24 17:46:24.425  3273  3332 I jxcore-log: ok 391 constructor called with right args
03-24 17:46:24.425  3273  3332 I jxcore-log: 
03-24 17:46:24.426  3273  3332 I jxcore-log: ok 392 match start arg
03-24 17:46:24.426  3273  3332 I jxcore-log: 
,03-24 17:46:24.426  3273  3332 I jxcore-log: ok 393 start called once
03-24 17:46:24.426  3273  3332 I jxcore-log: 
03-24 17:46:24.426  3273  3332 I jxcore-log: ok 394 stop called once
03-24 17:46:24.426  3273  3332 I jxcore-log: 
03-24 17:46:24.426  3273  3332 I jxcore-log: ok 395 stop after start
03-24 17:46:24.426  3273  3332 I jxcore-log: 
03-24 17:46:24.432  3273  3332 I jxcore-log: # teardown
03-24 17:46:24.432  3273  3332 I jxcore-log: 
,03-24 17:46:24.973  3273  3332 I jxcore-log: # setup
03-24 17:46:24.973  3273  3332 I jxcore-log: 
,03-24 17:46:25.884  3273  3332 I jxcore-log: # 120. One peer with _Local set equal to current seq
03-24 17:46:25.884  3273  3332 I jxcore-log: 
,03-24 17:46:26.338  3273  3332 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-24 17:46:26.338  3273  3332 I jxcore-log: 
,03-24 17:46:26.339  3273  3332 I jxcore-log: ok 396 verify failed
03-24 17:46:26.339  3273  3332 I jxcore-log: 
03-24 17:46:26.340  3273  3332 I jxcore-log: ok 397 constructor called once
03-24 17:46:26.340  3273  3332 I jxcore-log: 
,03-24 17:46:26.340  3273  3332 I jxcore-log: ok 398 constructor called with right args
03-24 17:46:26.340  3273  3332 I jxcore-log: 
03-24 17:46:26.340  3273  3332 I jxcore-log: ok 399 match start arg
03-24 17:46:26.340  3273  3332 I jxcore-log: 
,03-24 17:46:26.341  3273  3332 I jxcore-log: ok 400 start called once
03-24 17:46:26.341  3273  3332 I jxcore-log: 
03-24 17:46:26.341  3273  3332 I jxcore-log: ok 401 stop called once
03-24 17:46:26.341  3273  3332 I jxcore-log: 
03-24 17:46:26.341  3273  3332 I jxcore-log: ok 402 stop after start
03-24 17:46:26.341  3273  3332 I jxcore-log: 
,03-24 17:46:26.346  3273  3332 I jxcore-log: # teardown
03-24 17:46:26.346  3273  3332 I jxcore-log: 
,03-24 17:46:26.703  3273  3332 I jxcore-log: # setup
03-24 17:46:26.703  3273  3332 I jxcore-log: 
,03-24 17:46:26.991  3273  3332 I jxcore-log: # 121. One peer with _Local set ahead of current seq (and no this should not happen)
03-24 17:46:26.991  3273  3332 I jxcore-log: 
,03-24 17:46:29.744  3273  3332 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-24 17:46:29.744  3273  3332 I jxcore-log: 
,03-24 17:46:29.746  3273  3332 I jxcore-log: ok 403 verify failed
03-24 17:46:29.746  3273  3332 I jxcore-log: 
,03-24 17:46:29.746  3273  3332 I jxcore-log: ok 404 constructor called once
03-24 17:46:29.746  3273  3332 I jxcore-log: 
,03-24 17:46:29.747  3273  3332 I jxcore-log: ok 405 constructor called with right args
03-24 17:46:29.747  3273  3332 I jxcore-log: 
03-24 17:46:29.747  3273  3332 I jxcore-log: ok 406 match start arg
03-24 17:46:29.747  3273  3332 I jxcore-log: 
03-24 17:46:29.748  3273  3332 I jxcore-log: ok 407 start called once
03-24 17:46:29.748  3273  3332 I jxcore-log: 
,03-24 17:46:29.748  3273  3332 I jxcore-log: ok 408 stop called once
03-24 17:46:29.748  3273  3332 I jxcore-log: 
03-24 17:46:29.748  3273  3332 I jxcore-log: ok 409 stop after start
03-24 17:46:29.748  3273  3332 I jxcore-log: 
03-24 17:46:29.753  3273  3332 I jxcore-log: # teardown
03-24 17:46:29.753  3273  3332 I jxcore-log: 
,03-24 17:46:29.878  3273  3332 I jxcore-log: # setup
03-24 17:46:29.878  3273  3332 I jxcore-log: 
,03-24 17:46:30.155  3273  3332 I jxcore-log: # 122. Three peers, one not in DB, one behind and one ahead
03-24 17:46:30.155  3273  3332 I jxcore-log: 
,03-24 17:46:31.089  3273  3332 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-24 17:46:31.089  3273  3332 I jxcore-log: 
03-24 17:46:31.091  3273  3332 I jxcore-log: ok 410 verify failed
03-24 17:46:31.091  3273  3332 I jxcore-log: 
,03-24 17:46:31.092  3273  3332 I jxcore-log: ok 411 constructor called once
03-24 17:46:31.092  3273  3332 I jxcore-log: 
03-24 17:46:31.093  3273  3332 I jxcore-log: ok 412 constructor called with right args
03-24 17:46:31.093  3273  3332 I jxcore-log: 
03-24 17:46:31.093  3273  3332 I jxcore-log: ok 413 match start arg
03-24 17:46:31.093  3273  3332 I jxcore-log: 
,03-24 17:46:31.094  3273  3332 I jxcore-log: ok 414 start called once
03-24 17:46:31.094  3273  3332 I jxcore-log: 
,03-24 17:46:31.094  3273  3332 I jxcore-log: ok 415 stop called once
03-24 17:46:31.094  3273  3332 I jxcore-log: 
03-24 17:46:31.094  3273  3332 I jxcore-log: ok 416 stop after start
03-24 17:46:31.094  3273  3332 I jxcore-log: 
,03-24 17:46:31.100  3273  3332 I jxcore-log: # teardown
03-24 17:46:31.100  3273  3332 I jxcore-log: 
,03-24 17:46:32.125  3273  3332 I jxcore-log: # setup
03-24 17:46:32.125  3273  3332 I jxcore-log: 
,03-24 17:46:32.256  3273  3332 I jxcore-log: # 123. More than maximum peers, make sure we only send maximum allowed
03-24 17:46:32.256  3273  3332 I jxcore-log: 
,03-24 17:46:33.073  3273  3332 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
,03-24 17:46:33.073  3273  3332 I jxcore-log: 
03-24 17:46:33.075  3273  3332 I jxcore-log: ok 417 verify failed
03-24 17:46:33.075  3273  3332 I jxcore-log: 
03-24 17:46:33.075  3273  3332 I jxcore-log: ok 418 constructor called once
03-24 17:46:33.075  3273  3332 I jxcore-log: ,
03-24 17:46:33.076  3273  3332 I jxcore-log: ok 419 constructor called with right args
03-24 17:46:33.076  3273  3332 I jxcore-log: 
,03-24 17:46:33.077  3273  3332 I jxcore-log: ok 420 match start arg
03-24 17:46:33.077  3273  3332 I jxcore-log: 
03-24 17:46:33.077  3273  3332 I jxcore-log: ok 421 start called once
,03-24 17:46:33.077  3273  3332 I jxcore-log: 
03-24 17:46:33.078  3273  3332 I jxcore-log: ok 422 stop called once
,03-24 17:46:33.078  3273  3332 I jxcore-log: 
03-24 17:46:33.078  3273  3332 I jxcore-log: ok 423 stop after start
03-24 17:46:33.078  3273  3332 I jxcore-log: 
,03-24 17:46:33.085  3273  3332 I jxcore-log: # teardown
,03-24 17:46:33.085  3273  3332 I jxcore-log: 
,03-24 17:46:33.244  3273  3332 I jxcore-log: # setup
03-24 17:46:33.244  3273  3332 I jxcore-log: 
,03-24 17:46:33.390  3273  3332 I jxcore-log: # 124. two peers with empty DB, update the doc
03-24 17:46:33.390  3273  3332 I jxcore-log: 
,03-24 17:46:33.697  3273  3332 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"},
03-24 17:46:33.697  3273  3332 I jxcore-log: 
,03-24 17:46:33.737  3273  3332 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"},
03-24 17:46:33.737  3273  3332 I jxcore-log: 
03-24 17:46:33.739  3273  3332 I jxcore-log: ok 424 verify failed
03-24 17:46:33.739  3273  3332 I jxcore-log: 
,03-24 17:46:33.739  3273  3332 I jxcore-log: ok 425 constructor called once,
03-24 17:46:33.739  3273  3332 I jxcore-log: 
03-24 17:46:33.740  3273  3332 I jxcore-log: ok 426 constructor called with right args
03-24 17:46:33.740  3273  3332 I jxcore-log: 
03-24 17:46:33.740  3273  3332 I jxcore-log: ok 427 last start before stop
03-24 17:46:33.740  3273  3332 I jxcore-log: 
03-24 17:46:33.741  3273  3332 I jxcore-log: ok 428 empty first start
03-24 17:46:33.741  3273  3332 I jxcore-log: 
,03-24 17:46:33.742  3273  3332 I jxcore-log: ok 429 full second start
03-24 17:46:33.742  3273  3332 I jxcore-log: 
,03-24 17:46:33.742  3273  3332 I jxcore-log: ok 430 only 2 timers
03-24 17:46:33.742  3273  3332 I jxcore-log: 
03-24 17:46:33.746  3273  3332 I jxcore-log: # teardown,
03-24 17:46:33.746  3273  3332 I jxcore-log: 
,03-24 17:46:33.886  3273  3332 I jxcore-log: # setup
,03-24 17:46:33.886  3273  3332 I jxcore-log: 
,03-24 17:46:34.032  3273  3332 I jxcore-log: # 125. add doc and make sure tokens refresh when they expire
03-24 17:46:34.032  3273  3332 I jxcore-log: 
,03-24 17:46:34.419  3273  3332 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-24 17:46:34.419  3273  3332 I jxcore-log: 
,03-24 17:46:34.544  3273  3332 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-24 17:46:34.544  3273  3332 I jxcore-log: 
,03-24 17:46:34.634  3273  3332 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-24 17:46:34.634  3273  3332 I jxcore-log: 
,03-24 17:46:34.638  3273  3332 I jxcore-log: ok 431 verify failed
03-24 17:46:34.638  3273  3332 I jxcore-log: 
03-24 17:46:34.639  3273  3332 I jxcore-log: ok 432 constructor called once
03-24 17:46:34.639  3273  3332 I jxcore-log: 
03-24 17:46:34.640  3273  3332 I jxcore-log: ok 433 constructor called with right args
03-24 17:46:34.640  3273  3332 I jxcore-log: 
03-24 17:46:34.641  3273  3332 I jxcore-log: ok 434 start before stop
03-24 17:46:34.641  3273  3332 I jxcore-log: 
,03-24 17:46:34.644  3273  3332 I jxcore-log: ok 435 We got at least 3 calls to start
03-24 17:46:34.644  3273  3332 I jxcore-log: 
03-24 17:46:34.645  3273  3332 I jxcore-log: ok 436 at least 3
03-24 17:46:34.645  3273  3332 I jxcore-log: 
03-24 17:46:34.645  3273  3332 I jxcore-log: ok 437 default 1
03-24 17:46:34.645  3273  3332 I jxcore-log: 
,03-24 17:46:34.646  3273  3332 I jxcore-log: ok 438 1 run
03-24 17:46:34.646  3273  3332 I jxcore-log: 
03-24 17:46:34.646  3273  3332 I jxcore-log: ok 439 default 2
03-24 17:46:34.646  3273  3332 I jxcore-log: 
03-24 17:46:34.647  3273  3332 I jxcore-log: ok 440 2 run
03-24 17:46:34.647  3273  3332 I jxcore-log: 
03-24 17:46:34.647  3273  3332 I jxcore-log: ok 441 default 3
03-24 17:46:34.647  3273  3332 I jxcore-log: 
03-24 17:46:34.653  3273  3332 I jxcore-log: # teardown
03-24 17:46:34.653  3273  3332 I jxcore-log: 
,03-24 17:46:34.785  3273  3332 I jxcore-log: # setup
03-24 17:46:34.785  3273  3332 I jxcore-log: 
,03-24 17:46:34.910  3273  3332 I jxcore-log: # 126. start and stop and start and stop
03-24 17:46:34.910  3273  3332 I jxcore-log: 
,03-24 17:46:35.219  3273  3332 I jxcore-log: ok 442 start out null
,03-24 17:46:35.219  3273  3332 I jxcore-log: 
,03-24 17:46:35.251  3273  3332 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
,03-24 17:46:35.251  3273  3332 I jxcore-log: 
03-24 17:46:35.252  3273  3332 I jxcore-log: ok 443 back to null
03-24 17:46:35.252  3273  3332 I jxcore-log: 
,03-24 17:46:35.277  3273  3332 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
,03-24 17:46:35.277  3273  3332 I jxcore-log: 
03-24 17:46:35.278  3273  3332 I jxcore-log: ok 444 still null
03-24 17:46:35.278  3273  3332 I jxcore-log: 
,03-24 17:46:35.281  3273  3332 I jxcore-log: ok 445 verify failed
03-24 17:46:35.281  3273  3332 I jxcore-log: ,
03-24 17:46:35.281  3273  3332 I jxcore-log: ok 446 constructor called once
03-24 17:46:35.281  3273  3332 I jxcore-log: 
,03-24 17:46:35.283  3273  3332 I jxcore-log: ok 447 constructor called with right args
03-24 17:46:35.283  3273  3332 I jxcore-log: 
,03-24 17:46:35.283  3273  3332 I jxcore-log: ok 448 first start before first stop
03-24 17:46:35.283  3273  3332 I jxcore-log: 
,03-24 17:46:35.284  3273  3332 I jxcore-log: ok 449 first stop before second start
03-24 17:46:35.284  3273  3332 I jxcore-log: 
03-24 17:46:35.285  3273  3332 I jxcore-log: ok 450 second start before second stop
03-24 17:46:35.285  3273  3332 I jxcore-log: 
,03-24 17:46:35.293  3273  3332 I jxcore-log: # teardown
,03-24 17:46:35.293  3273  3332 I jxcore-log: 
,03-24 17:46:35.385  3273  3332 I jxcore-log: # setup
03-24 17:46:35.385  3273  3332 I jxcore-log: 
,03-24 17:46:35.537  3273  3332 I jxcore-log: # 127. two identical starts in a row
03-24 17:46:35.537  3273  3332 I jxcore-log: 
,03-24 17:46:35.876  3273  3332 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-24 17:46:35.876  3273  3332 I jxcore-log: 
03-24 17:46:35.879  3273  3332 I jxcore-log: ok 451 verify failed
03-24 17:46:35.879  3273  3332 I jxcore-log: 
03-24 17:46:35.879  3273  3332 I jxcore-log: ok 452 constructor called once
03-24 17:46:35.879  3273  3332 I jxcore-log: 
03-24 17:46:35.879  3273  3332 I jxcore-log: ok 453 constructor called with right args
03-24 17:46:35.879  3273  3332 I jxcore-log: 
03-24 17:46:35.880  3273  3332 I jxcore-log: ok 454 (unnamed assert)
03-24 17:46:35.880  3273  3332 I jxcore-log: 
,03-24 17:46:35.885  3273  3332 I jxcore-log: # teardown
03-24 17:46:35.885  3273  3332 I jxcore-log: 
,03-24 17:46:36.294  3273  3332 I jxcore-log: # setup
03-24 17:46:36.294  3273  3332 I jxcore-log: 
,03-24 17:46:36.538  3273  3332 I jxcore-log: # 128. two different starts in a row
03-24 17:46:36.538  3273  3332 I jxcore-log: 
,03-24 17:46:36.904  3273  3332 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-24 17:46:36.904  3273  3332 I jxcore-log: 
,03-24 17:46:36.909  3273  3332 I jxcore-log: ok 455 verify failed
03-24 17:46:36.909  3273  3332 I jxcore-log: 
03-24 17:46:36.909  3273  3332 I jxcore-log: ok 456 constructor called once
03-24 17:46:36.909  3273  3332 I jxcore-log: 
03-24 17:46:36.910  3273  3332 I jxcore-log: ok 457 constructor called with right args
03-24 17:46:36.910  3273  3332 I jxcore-log: 
03-24 17:46:36.910  3273  3332 I jxcore-log: ok 458 (unnamed assert)
03-24 17:46:36.910  3273  3332 I jxcore-log: 
,03-24 17:46:36.910  3273  3332 I jxcore-log: ok 459 (unnamed assert)
03-24 17:46:36.910  3273  3332 I jxcore-log: 
03-24 17:46:36.915  3273  3332 I jxcore-log: # teardown
03-24 17:46:36.915  3273  3332 I jxcore-log: 
,03-24 17:46:37.109  3273  3332 I jxcore-log: # setup
03-24 17:46:37.109  3273  3332 I jxcore-log: 
,03-24 17:46:37.257  3273  3332 I jxcore-log: # 129. two stops and a start and two stops
03-24 17:46:37.257  3273  3332 I jxcore-log: 
,03-24 17:46:37.540  3273  3332 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-24 17:46:37.540  3273  3332 I jxcore-log: 
,03-24 17:46:37.542  3273  3332 I jxcore-log: ok 460 verify failed
03-24 17:46:37.542  3273  3332 I jxcore-log: 
,03-24 17:46:37.543  3273  3332 I jxcore-log: ok 461 constructor called once
03-24 17:46:37.543  3273  3332 I jxcore-log: 
,03-24 17:46:37.543  3273  3332 I jxcore-log: ok 462 constructor called with right args
03-24 17:46:37.543  3273  3332 I jxcore-log: 
,03-24 17:46:37.544  3273  3332 I jxcore-log: ok 463 start before stop
03-24 17:46:37.544  3273  3332 I jxcore-log: 
03-24 17:46:37.548  3273  3332 I jxcore-log: # teardown
03-24 17:46:37.548  3273  3332 I jxcore-log: 
,03-24 17:46:37.676  3273  3332 I jxcore-log: # setup
03-24 17:46:37.676  3273  3332 I jxcore-log: 
,03-24 17:46:37.809  3273  3332 I jxcore-log: # 130. we properly enqueue requests so no then needed
03-24 17:46:37.809  3273  3332 I jxcore-log: 
,03-24 17:46:38.154  3273  3332 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-24 17:46:38.154  3273  3332 I jxcore-log: 
,03-24 17:46:38.156  3273  3332 I jxcore-log: ok 464 verify failed
03-24 17:46:38.156  3273  3332 I jxcore-log: 
03-24 17:46:38.156  3273  3332 I jxcore-log: ok 465 constructor called once
03-24 17:46:38.156  3273  3332 I jxcore-log: 
03-24 17:46:38.156  3273  3332 I jxcore-log: ok 466 constructor called with right args
03-24 17:46:38.156  3273  3332 I jxcore-log: 
,03-24 17:46:38.157  3273  3332 I jxcore-log: ok 467 start before stop
03-24 17:46:38.157  3273  3332 I jxcore-log: 
03-24 17:46:38.160  3273  3332 I jxcore-log: # teardown
03-24 17:46:38.160  3273  3332 I jxcore-log: 
,03-24 17:46:38.322  3273  3332 I jxcore-log: # setup
03-24 17:46:38.322  3273  3332 I jxcore-log: 
,03-24 17:46:38.463  3273  3332 I jxcore-log: # 131. test calculateSeqPointKeyId
03-24 17:46:38.463  3273  3332 I jxcore-log: ,
,03-24 17:46:38.665  3273  3332 I jxcore-log: ok 468 should be equal
03-24 17:46:38.665  3273  3332 I jxcore-log: 
,03-24 17:46:38.665  3273  3332 I jxcore-log: ok 469 should be equal
03-24 17:46:38.665  3273  3332 I jxcore-log: 
03-24 17:46:38.667  3273  3332 I jxcore-log: # teardown
03-24 17:46:38.667  3273  3332 I jxcore-log: 
,03-24 17:46:38.838  3273  3332 I jxcore-log: # setup,
03-24 17:46:38.838  3273  3332 I jxcore-log: 
,03-24 17:46:38.949  3273  3332 I jxcore-log: # 132. can create servers manager
03-24 17:46:38.949  3273  3332 I jxcore-log: 
,03-24 17:46:39.059  3273  3332 I jxcore-log: ok 470 serversManager must not be null
03-24 17:46:39.059  3273  3332 I jxcore-log: 
,03-24 17:46:39.061  3273  3332 I jxcore-log: ok 471 serversManager must be an object
03-24 17:46:39.061  3273  3332 I jxcore-log: 
,03-24 17:46:39.067  3273  3332 I jxcore-log: # teardown,
03-24 17:46:39.067  3273  3332 I jxcore-log: ,
,03-24 17:46:39.227  3273  3332 I jxcore-log: # setup
03-24 17:46:39.227  3273  3332 I jxcore-log: 
,03-24 17:46:39.474  3273  3332 I jxcore-log: # 133. calling stop without start causes error
03-24 17:46:39.474  3273  3332 I jxcore-log: 
,03-24 17:46:39.585  3273  3332 I jxcore-log: ok 472 We need to call start first
03-24 17:46:39.585  3273  3332 I jxcore-log: 
,03-24 17:46:39.592  3273  3332 I jxcore-log: # teardown
03-24 17:46:39.592  3273  3332 I jxcore-log: 
,03-24 17:46:39.696  3273  3332 I jxcore-log: # setup
03-24 17:46:39.696  3273  3332 I jxcore-log: 
,03-24 17:46:39.853  3273  3332 I jxcore-log: # 134. can start/stop servers manager
03-24 17:46:39.853  3273  3332 I jxcore-log: 
,03-24 17:46:39.999  3273  3332 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 17:46:39.999  3273  3332 I jxcore-log: 
,03-24 17:46:40.009  3273  3332 I jxcore-log: DEBUG createNativeListener: listening 37008
03-24 17:46:40.009  3273  3332 I jxcore-log: 
,03-24 17:46:40.013  3273  3332 I jxcore-log: ok 473 port must be in range
03-24 17:46:40.013  3273  3332 I jxcore-log: 
,03-24 17:46:40.016  3273  3332 I jxcore-log: # teardown
03-24 17:46:40.016  3273  3332 I jxcore-log: 
,03-24 17:46:40.233  3273  3332 I jxcore-log: # setup
03-24 17:46:40.233  3273  3332 I jxcore-log: 
,03-24 17:46:40.326  3273  3332 I jxcore-log: # 135. starting twice resolves with listening port
03-24 17:46:40.326  3273  3332 I jxcore-log: 
,03-24 17:46:40.513  3273  3332 I jxcore-log: DEBUG createNativeListener: creating native server,
03-24 17:46:40.513  3273  3332 I jxcore-log: 
03-24 17:46:40.516  3273  3332 I jxcore-log: DEBUG createNativeListener: listening 36891
03-24 17:46:40.516  3273  3332 I jxcore-log: 
03-24 17:46:40.518  3273  3332 I jxcore-log: ok 474 second start should return same port
03-24 17:46:40.518  3273  3332 I jxcore-log: 
,03-24 17:46:40.520  3273  3332 I jxcore-log: # teardown
03-24 17:46:40.520  3273  3332 I jxcore-log: 
,03-24 17:46:40.705  3273  3332 I jxcore-log: # setup
03-24 17:46:40.705  3273  3332 I jxcore-log: ,
,03-24 17:46:40.813  3273  3332 I jxcore-log: # 136. terminateIncomingConnection will terminate a connection
,03-24 17:46:40.813  3273  3332 I jxcore-log: 
,03-24 17:46:40.954  3273  3332 I jxcore-log: DEBUG createNativeListener: creating native server
,03-24 17:46:40.954  3273  3332 I jxcore-log: 
,03-24 17:46:40.957  3273  3332 I jxcore-log: DEBUG createNativeListener: listening 38430
03-24 17:46:40.957  3273  3332 I jxcore-log: 
,03-24 17:46:40.969  3273  3332 I jxcore-log: DEBUG createNativeListener: new incoming socket
,03-24 17:46:40.969  3273  3332 I jxcore-log: 
,03-24 17:46:40.973  3273  3332 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 17:46:40.973  3273  3332 I jxcore-log: 
,03-24 17:46:40.979  3273  3332 I jxcore-log: DEBUG createNativeListener: new mux
,03-24 17:46:40.979  3273  3332 I jxcore-log: 
,03-24 17:46:40.987  3273  3332 I jxcore-log: ok 475 we should be connected
,03-24 17:46:40.987  3273  3332 I jxcore-log: 
,03-24 17:46:40.994  3273  3332 I jxcore-log: DEBUG createNativeListener: incoming socket close,
03-24 17:46:40.994  3273  3332 I jxcore-log: 
03-24 17:46:40.995  3273  3332 I jxcore-log: ok 476 now we are disconnected
03-24 17:46:40.995  3273  3332 I jxcore-log: 
,03-24 17:46:41.008  3273  3332 I jxcore-log: # teardown,
03-24 17:46:41.008  3273  3332 I jxcore-log: 
,03-24 17:46:41.211  3273  3332 I jxcore-log: # setup,
03-24 17:46:41.211  3273  3332 I jxcore-log: 
,03-24 17:46:41.403  3273  3332 I jxcore-log: # 137. terminate an Outgoing connection will terminate the server,
03-24 17:46:41.403  3273  3332 I jxcore-log: 
,03-24 17:46:41.516  3273  3332 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 17:46:41.516  3273  3332 I jxcore-log: 
,03-24 17:46:41.525  3273  3332 I jxcore-log: DEBUG createNativeListener: listening 54004
03-24 17:46:41.525  3273  3332 I jxcore-log: 
,03-24 17:46:41.534  3273  3332 I jxcore-log: # teardown
03-24 17:46:41.534  3273  3332 I jxcore-log: 
,03-24 17:46:41.719  3273  3332 I jxcore-log: # setup
03-24 17:46:41.719  3273  3332 I jxcore-log: 
,03-24 17:46:41.874  3273  3332 I jxcore-log: # 138. terminate an Outgoing connection with wrong arguments is not harmful
03-24 17:46:41.874  3273  3332 I jxcore-log: 
,03-24 17:46:42.062  3273  3332 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 17:46:42.062  3273  3332 I jxcore-log: 
,03-24 17:46:42.072  3273  3332 I jxcore-log: DEBUG createNativeListener: listening 49350
03-24 17:46:42.072  3273  3332 I jxcore-log: 
,03-24 17:46:42.076  3273  3332 I jxcore-log: # teardown
03-24 17:46:42.076  3273  3332 I jxcore-log: 
,03-24 17:46:42.217  3273  3332 I jxcore-log: # setup
03-24 17:46:42.217  3273  3332 I jxcore-log: 
,03-24 17:46:42.355  3273  3332 I jxcore-log: ok 477 should be in started state,
03-24 17:46:42.355  3273  3332 I jxcore-log: 
,03-24 17:46:42.357  3273  3332 I jxcore-log: # 139. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted
03-24 17:46:42.357  3273  3332 I jxcore-log: 
,03-24 17:46:42.563  3273  3332 I jxcore-log: ok 478 peer identifier should match
03-24 17:46:42.563  3273  3332 I jxcore-log: 
03-24 17:46:42.564  3273  3332 I jxcore-log: ok 479 host address should match
03-24 17:46:42.564  3273  3332 I jxcore-log: 
03-24 17:46:42.564  3273  3332 I jxcore-log: ok 480 port should match
03-24 17:46:42.564  3273  3332 I jxcore-log: 
,03-24 17:46:42.572  3273  3332 I jxcore-log: ok 481 host address should be null
03-24 17:46:42.572  3273  3332 I jxcore-log: 
03-24 17:46:42.572  3273  3332 I jxcore-log: ok 482 port should should be null
03-24 17:46:42.572  3273  3332 I jxcore-log: 
,03-24 17:46:42.578  3273  3332 I jxcore-log: # teardown
03-24 17:46:42.578  3273  3332 I jxcore-log: 
,03-24 17:46:42.749  3273  3332 I jxcore-log: ok 483 should not be in started state
03-24 17:46:42.749  3273  3332 I jxcore-log: 
,03-24 17:46:42.755  3273  3332 I jxcore-log: # setup
03-24 17:46:42.755  3273  3332 I jxcore-log: 
,03-24 17:46:42.938  3273  3332 I jxcore-log: ok 484 should be in started state
03-24 17:46:42.938  3273  3332 I jxcore-log: 
,03-24 17:46:42.940  3273  3332 I jxcore-log: # 140. #startUpdateAdvertisingAndListening should use different USN after every invocation
03-24 17:46:42.940  3273  3332 I jxcore-log: 
,03-24 17:46:43.119  3273  3332 I jxcore-log: ok 485 USN should have changed from the first one
03-24 17:46:43.119  3273  3332 I jxcore-log: 
,03-24 17:46:43.130  3273  3332 I jxcore-log: ok 486 when receiving the second byebye, the first USN should be already set
03-24 17:46:43.130  3273  3332 I jxcore-log: 
,03-24 17:46:43.137  3273  3332 I jxcore-log: # teardown
03-24 17:46:43.137  3273  3332 I jxcore-log: 
,03-24 17:46:43.277  3273  3332 I jxcore-log: ok 487 should not be in started state
03-24 17:46:43.277  3273  3332 I jxcore-log: 
,03-24 17:46:43.279  3273  3332 I jxcore-log: # setup
03-24 17:46:43.279  3273  3332 I jxcore-log: 
,03-24 17:46:43.396  3273  3332 I jxcore-log: ok 488 should be in started state,
03-24 17:46:43.396  3273  3332 I jxcore-log: 
03-24 17:46:43.398  3273  3332 I jxcore-log: # 141. messages with invalid location or USN should be ignored
03-24 17:46:43.398  3273  3332 I jxcore-log: 
,03-24 17:46:43.564  3273  3332 I jxcore-log: WARN thaliWifiInfrastructure: Failed to parse a valid port number from location: http://foo.bar:90000,
03-24 17:46:43.564  3273  3332 I jxcore-log: 
,03-24 17:46:43.564  3273  3332 I jxcore-log: ok 489 should not have emitted with invalid port
03-24 17:46:43.564  3273  3332 I jxcore-log: 
03-24 17:46:43.566  3273  3332 I jxcore-log: WARN thaliWifiInfrastructure: Received an invalid USN value: ,
03-24 17:46:43.566  3273  3332 I jxcore-log: 
03-24 17:46:43.567  3273  3332 I jxcore-log: ok 490 should not have emitted with invalid USN
03-24 17:46:43.567  3273  3332 I jxcore-log: 
03-24 17:46:43.569  3273  3332 I jxcore-log: # teardown
03-24 17:46:43.569  3273  3332 I jxcore-log: 
,03-24 17:46:43.731  3273  3332 I jxcore-log: ok 491 should not be in started state,
03-24 17:46:43.731  3273  3332 I jxcore-log: 
03-24 17:46:43.738  3273  3332 I jxcore-log: # setup
03-24 17:46:43.738  3273  3332 I jxcore-log: 
,03-24 17:46:43.940  3273  3332 I jxcore-log: ok 492 should be in started state,
03-24 17:46:43.940  3273  3332 I jxcore-log: 
,03-24 17:46:43.945  3273  3332 I jxcore-log: # 142. verify that Thali-specific messages are filtered correctly,
03-24 17:46:43.945  3273  3332 I jxcore-log: 
,03-24 17:46:44.079  3273  3332 I jxcore-log: ok 493 irrelevant messages should be ignored
,03-24 17:46:44.079  3273  3332 I jxcore-log: 
,03-24 17:46:44.082  3273  3332 I jxcore-log: ok 494 relevant messages should not be ignored
03-24 17:46:44.082  3273  3332 I jxcore-log: 
,03-24 17:46:44.084  3273  3332 I jxcore-log: ok 495 messages from this device should be ignored
03-24 17:46:44.084  3273  3332 I jxcore-log: 
,03-24 17:46:44.086  3273  3332 I jxcore-log: # teardown
03-24 17:46:44.086  3273  3332 I jxcore-log: 
,03-24 17:46:44.199  3273  3332 I jxcore-log: ok 496 should not be in started state
03-24 17:46:44.199  3273  3332 I jxcore-log: 
,03-24 17:46:44.204  3273  3332 I jxcore-log: # setup
03-24 17:46:44.204  3273  3332 I jxcore-log: 
,03-24 17:46:44.301  3273  3332 I jxcore-log: ok 497 should be in started state
03-24 17:46:44.301  3273  3332 I jxcore-log: 
,03-24 17:46:44.305  3273  3332 I jxcore-log: # 143. #startListeningForAdvertisements should fail if start not called
03-24 17:46:44.305  3273  3332 I jxcore-log: 
,03-24 17:46:44.500  3273  3332 I jxcore-log: ok 498 specific error should be returned
03-24 17:46:44.500  3273  3332 I jxcore-log: 
,03-24 17:46:44.505  3273  3332 I jxcore-log: # teardown
03-24 17:46:44.505  3273  3332 I jxcore-log: 
,03-24 17:46:44.631  3273  3332 I jxcore-log: ok 499 should not be in started state
03-24 17:46:44.631  3273  3332 I jxcore-log: 
,03-24 17:46:44.638  3273  3332 I jxcore-log: # setup
03-24 17:46:44.638  3273  3332 I jxcore-log: 
,03-24 17:46:44.781  3273  3332 I jxcore-log: ok 500 should be in started state
03-24 17:46:44.781  3273  3332 I jxcore-log: 
,03-24 17:46:44.785  3273  3332 I jxcore-log: # 144. #startUpdateAdvertisingAndListening should fail if start not called
03-24 17:46:44.785  3273  3332 I jxcore-log: 
,03-24 17:46:44.923  2157  2223 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 17:46:44.965  3273  3332 I jxcore-log: ok 501 specific error should be returned
03-24 17:46:44.965  3273  3332 I jxcore-log: 
,03-24 17:46:44.966  3273  3332 I jxcore-log: # teardown
03-24 17:46:44.966  3273  3332 I jxcore-log: 
,03-24 17:46:45.121  3273  3332 I jxcore-log: ok 502 should not be in started state
03-24 17:46:45.121  3273  3332 I jxcore-log: 
,03-24 17:46:45.126  3273  3332 I jxcore-log: # setup
,03-24 17:46:45.126  3273  3332 I jxcore-log: 
,03-24 17:46:45.256  3273  3332 I jxcore-log: ok 503 should be in started state
03-24 17:46:45.256  3273  3332 I jxcore-log: ,
,03-24 17:46:45.264  3273  3332 I jxcore-log: # 145. #start should fail if called twice in a row,
03-24 17:46:45.264  3273  3332 I jxcore-log: 
,03-24 17:46:45.376  3273  3332 I jxcore-log: ok 504 specific error should be received,
03-24 17:46:45.376  3273  3332 I jxcore-log: 
,03-24 17:46:45.384  3273  3332 I jxcore-log: # teardown,
03-24 17:46:45.384  3273  3332 I jxcore-log: 
,03-24 17:46:45.524  3273  3332 I jxcore-log: ok 505 should not be in started state,
03-24 17:46:45.524  3273  3332 I jxcore-log: 
03-24 17:46:45.526  3273  3332 I jxcore-log: # setup
03-24 17:46:45.526  3273  3332 I jxcore-log: 
,03-24 17:46:45.673  3273  3332 I jxcore-log: ok 506 should be in started state
03-24 17:46:45.673  3273  3332 I jxcore-log: 
,03-24 17:46:45.680  3273  3332 I jxcore-log: # 146. should not be started after stop is called
,03-24 17:46:45.680  3273  3332 I jxcore-log: 
,03-24 17:46:45.844  3273  3332 I jxcore-log: ok 507 should not be started
03-24 17:46:45.844  3273  3332 I jxcore-log: 
,03-24 17:46:45.844  3273  3332 I jxcore-log: ok 508 should not be listening
03-24 17:46:45.844  3273  3332 I jxcore-log: 
03-24 17:46:45.845  3273  3332 I jxcore-log: ok 509 should not target listening
03-24 17:46:45.845  3273  3332 I jxcore-log: 
,03-24 17:46:45.846  3273  3332 I jxcore-log: ok 510 should not be advertising
03-24 17:46:45.846  3273  3332 I jxcore-log: 
,03-24 17:46:45.846  3273  3332 I jxcore-log: ok 511 should not target advertising
03-24 17:46:45.846  3273  3332 I jxcore-log: 
,03-24 17:46:45.848  3273  3332 I jxcore-log: # teardown
03-24 17:46:45.848  3273  3332 I jxcore-log: 
,03-24 17:46:45.989  3273  3332 I jxcore-log: ok 512 should not be in started state
03-24 17:46:45.989  3273  3332 I jxcore-log: 
,03-24 17:46:45.997  3273  3332 I jxcore-log: # setup
03-24 17:46:45.997  3273  3332 I jxcore-log: 
,03-24 17:46:46.145  3273  3332 I jxcore-log: ok 513 should be in started state
03-24 17:46:46.145  3273  3332 I jxcore-log: 
,03-24 17:46:46.147  3273  3332 I jxcore-log: # 147. #startUpdateAdvertisingAndListening should fail invalid router has been passed
03-24 17:46:46.147  3273  3332 I jxcore-log: 
,03-24 17:46:46.390  3273  3332 I jxcore-log: ERROR thaliWifiInfrastructure: Unable to use the given router: TypeError: Router.use() requires middleware function but got a string
03-24 17:46:46.390  3273  3332 I jxcore-log: 
,03-24 17:46:46.392  3273  3332 I jxcore-log: ok 514 specific error should be received
03-24 17:46:46.392  3273  3332 I jxcore-log: 
03-24 17:46:46.394  3273  3332 I jxcore-log: # teardown
03-24 17:46:46.394  3273  3332 I jxcore-log: 
,03-24 17:46:46.526  3273  3332 I jxcore-log: ok 515 should not be in started state
03-24 17:46:46.526  3273  3332 I jxcore-log: 
,03-24 17:46:46.528  3273  3332 I jxcore-log: # setup
03-24 17:46:46.528  3273  3332 I jxcore-log: 
,03-24 17:46:46.679  3273  3332 I jxcore-log: ok 516 should be in started state
03-24 17:46:46.679  3273  3332 I jxcore-log: 
,03-24 17:46:46.685  3273  3332 I jxcore-log: # 148. #startUpdateAdvertisingAndListening should fail if router server starting fails
03-24 17:46:46.685  3273  3332 I jxcore-log: 
,03-24 17:46:46.811  3273  3332 I jxcore-log: ERROR thaliWifiInfrastructure: Router server emitted an error: Error: listen EADDRINUSE
03-24 17:46:46.811  3273  3332 I jxcore-log: 
,03-24 17:46:46.813  3273  3332 I jxcore-log: ok 517 specific error expected
03-24 17:46:46.813  3273  3332 I jxcore-log: 
,03-24 17:46:46.816  3273  3332 I jxcore-log: # teardown
03-24 17:46:46.816  3273  3332 I jxcore-log: 
,03-24 17:46:46.947  3273  3332 I jxcore-log: ok 518 should not be in started state
03-24 17:46:46.947  3273  3332 I jxcore-log: 
,03-24 17:46:46.954  3273  3332 I jxcore-log: # setup
03-24 17:46:46.954  3273  3332 I jxcore-log: 
,03-24 17:46:47.094  3273  3332 I jxcore-log: ok 519 should be in started state
03-24 17:46:47.094  3273  3332 I jxcore-log: 
,03-24 17:46:47.096  3273  3332 I jxcore-log: # 149. #startUpdateAdvertisingAndListening should start hosting given router object
03-24 17:46:47.096  3273  3332 I jxcore-log: 
,03-24 17:46:47.311  3273  3332 I jxcore-log: ok 520 server should respond with code 200
03-24 17:46:47.311  3273  3332 I jxcore-log: 
,03-24 17:46:47.317  3273  3332 I jxcore-log: # teardown
03-24 17:46:47.317  3273  3332 I jxcore-log: 
,03-24 17:46:47.426  3273  3332 I jxcore-log: ok 521 should not be in started state
03-24 17:46:47.426  3273  3332 I jxcore-log: 
03-24 17:46:47.432  3273  3332 I jxcore-log: # setup
03-24 17:46:47.432  3273  3332 I jxcore-log: 
,03-24 17:46:47.577  3273  3332 I jxcore-log: ok 522 should be in started state
03-24 17:46:47.577  3273  3332 I jxcore-log: 
,03-24 17:46:47.584  3273  3332 I jxcore-log: # 150. #stop can be called multiple times in a row
03-24 17:46:47.584  3273  3332 I jxcore-log: 
,03-24 17:46:47.705  3273  3332 I jxcore-log: ok 523 should be in stopped state
03-24 17:46:47.705  3273  3332 I jxcore-log: 
,03-24 17:46:47.706  3273  3332 I jxcore-log: ok 524 should still be in stopped state
03-24 17:46:47.706  3273  3332 I jxcore-log: 
03-24 17:46:47.709  3273  3332 I jxcore-log: # teardown
03-24 17:46:47.709  3273  3332 I jxcore-log: 
,03-24 17:46:47.857  3273  3332 I jxcore-log: ok 525 should not be in started state
03-24 17:46:47.857  3273  3332 I jxcore-log: 
,03-24 17:46:47.864  3273  3332 I jxcore-log: # setup
03-24 17:46:47.864  3273  3332 I jxcore-log: 
,03-24 17:46:47.993  3273  3332 I jxcore-log: ok 526 should be in started state
,03-24 17:46:47.993  3273  3332 I jxcore-log: 
,03-24 17:46:48.005  3273  3332 I jxcore-log: # 151. #startListeningForAdvertisements can be called multiple times in a row
03-24 17:46:48.005  3273  3332 I jxcore-log: 
,03-24 17:46:48.125  3273  3332 I jxcore-log: ok 527 should be in listening state
03-24 17:46:48.125  3273  3332 I jxcore-log: 
,03-24 17:46:48.127  3273  3332 I jxcore-log: ok 528 should still be in listening state
03-24 17:46:48.127  3273  3332 I jxcore-log: 
,03-24 17:46:48.130  3273  3332 I jxcore-log: # teardown,
03-24 17:46:48.130  3273  3332 I jxcore-log: 
,03-24 17:46:48.294  3273  3332 I jxcore-log: ok 529 should not be in started state
03-24 17:46:48.294  3273  3332 I jxcore-log: 
,03-24 17:46:48.299  3273  3332 I jxcore-log: # setup
03-24 17:46:48.299  3273  3332 I jxcore-log: 
,03-24 17:46:48.415  3273  3332 I jxcore-log: ok 530 should be in started state
,03-24 17:46:48.415  3273  3332 I jxcore-log: 
03-24 17:46:48.417  3273  3332 I jxcore-log: # 152. #stopListeningForAdvertisements can be called multiple times in a row
03-24 17:46:48.417  3273  3332 I jxcore-log: 
,03-24 17:46:48.570  3273  3332 I jxcore-log: ok 531 should not be in listening state
03-24 17:46:48.570  3273  3332 I jxcore-log: 
,03-24 17:46:48.574  3273  3332 I jxcore-log: ok 532 should still not be in listening state
03-24 17:46:48.574  3273  3332 I jxcore-log: 
,03-24 17:46:48.576  3273  3332 I jxcore-log: # teardown
03-24 17:46:48.576  3273  3332 I jxcore-log: 
,03-24 17:46:48.710  3273  3332 I jxcore-log: ok 533 should not be in started state
03-24 17:46:48.710  3273  3332 I jxcore-log: 
,03-24 17:46:48.715  3273  3332 I jxcore-log: # setup
03-24 17:46:48.715  3273  3332 I jxcore-log: 
,03-24 17:46:48.860  3273  3332 I jxcore-log: ok 534 should be in started state
03-24 17:46:48.860  3273  3332 I jxcore-log: 
,03-24 17:46:48.868  3273  3332 I jxcore-log: # 153. #stopAdvertisingAndListening can be called multiple times in a row
03-24 17:46:48.868  3273  3332 I jxcore-log: 
,03-24 17:46:49.007  3273  3332 I jxcore-log: ok 535 should not be in advertising state
,03-24 17:46:49.007  3273  3332 I jxcore-log: 
03-24 17:46:49.012  3273  3332 I jxcore-log: ok 536 should still not be in advertising state
03-24 17:46:49.012  3273  3332 I jxcore-log: 
,03-24 17:46:49.016  3273  3332 I jxcore-log: # teardown
03-24 17:46:49.016  3273  3332 I jxcore-log: 
,03-24 17:46:49.135  3273  3332 I jxcore-log: ok 537 should not be in started state
03-24 17:46:49.135  3273  3332 I jxcore-log: 
,03-24 17:46:49.138  3273  3332 I jxcore-log: # setup
03-24 17:46:49.138  3273  3332 I jxcore-log: 
,03-24 17:46:49.286  3273  3332 I jxcore-log: ok 538 should be in started state
03-24 17:46:49.286  3273  3332 I jxcore-log: 
,03-24 17:46:49.296  3273  3332 I jxcore-log: # 154. functions are run from a queue in the right order
03-24 17:46:49.296  3273  3332 I jxcore-log: 
,03-24 17:46:49.458  3273  3332 I jxcore-log: ok 539 call order must match
03-24 17:46:49.458  3273  3332 I jxcore-log: 
,03-24 17:46:49.465  3273  3332 I jxcore-log: # teardown
03-24 17:46:49.465  3273  3332 I jxcore-log: 
,03-24 17:46:49.621  3273  3332 I jxcore-log: ok 540 should not be in started state
03-24 17:46:49.621  3273  3332 I jxcore-log: 
,03-24 17:46:49.629  3273  3332 I jxcore-log: # setup
03-24 17:46:49.629  3273  3332 I jxcore-log: 
,03-24 17:46:49.960  3273  3332 I jxcore-log: # 155. #ThaliPeerPoolDefault - single action
03-24 17:46:49.960  3273  3332 I jxcore-log: 
,03-24 17:46:50.155  3273  3332 I jxcore-log: ok 541 is an agent
03-24 17:46:50.155  3273  3332 I jxcore-log: 
,03-24 17:46:50.156  3273  3332 I jxcore-log: ok 542 enqueue is fine
03-24 17:46:50.156  3273  3332 I jxcore-log: 
,03-24 17:46:50.158  3273  3332 I jxcore-log: ok 543 Everything should be off the queue
03-24 17:46:50.158  3273  3332 I jxcore-log: 
,03-24 17:46:50.161  3273  3332 I jxcore-log: # teardown
03-24 17:46:50.161  3273  3332 I jxcore-log: 
,03-24 17:46:50.321  3273  3332 I jxcore-log: # setup
03-24 17:46:50.321  3273  3332 I jxcore-log: 
,03-24 17:46:50.537  3273  3332 I jxcore-log: # 156. #ThaliPeerPoolDefault - multiple actions
03-24 17:46:50.537  3273  3332 I jxcore-log: ,
,03-24 17:46:50.891  3273  3332 I jxcore-log: ok 544 is an agent
03-24 17:46:50.891  3273  3332 I jxcore-log: 
,03-24 17:46:50.894  3273  3332 I jxcore-log: ok 545 first enqueue is fine
03-24 17:46:50.894  3273  3332 I jxcore-log: 
,03-24 17:46:50.898  3273  3332 I jxcore-log: ok 546 is an agent
03-24 17:46:50.898  3273  3332 I jxcore-log: 
,03-24 17:46:50.901  3273  3332 I jxcore-log: ok 547 second enqueue is fine
,03-24 17:46:50.901  3273  3332 I jxcore-log: 
,03-24 17:46:50.905  3273  3332 I jxcore-log: ok 548 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.
03-24 17:46:50.905  3273  3332 I jxcore-log: 
,03-24 17:46:50.906  3273  3332 I jxcore-log: ok 549 Queue is empty
03-24 17:46:50.906  3273  3332 I jxcore-log: 
,03-24 17:46:50.908  3273  3332 I jxcore-log: # teardown
03-24 17:46:50.908  3273  3332 I jxcore-log: 
,03-24 17:46:54.728  3273  3332 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
03-24 17:46:54.728  3273  3332 I jxcore-log: 
,03-24 17:46:55.016  3972  3972 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,03-24 17:46:55.019  3972  3972 D AndroidRuntime: CheckJNI is OFF
,03-24 17:46:55.131  3972  3972 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,03-24 17:46:55.143   823   857 I ActivityManager: Force stopping com.test.thalitest appid=10095 user=-1: uninstall pkg
03-24 17:46:55.143   823   857 I ActivityManager: Killing 3273:com.test.thalitest/u0a95 (adj 0): stop com.test.thalitest
,03-24 17:46:55.268   823   867 W PackageSettings: Skipping PackageSetting{8758080 com.example.hello/10273} due to missing metadata
,03-24 17:46:55.336   823  1104 I WindowState: WIN DEATH: Window{179d8751 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,03-24 17:46:55.338   823  1020 D WifiService: Client connection lost with reason: 4
,03-24 17:46:55.352   823   857 E libprocessgroup: failed to kill 1 processes for processgroup 3273
,03-24 17:46:55.353   823   857 W ActivityManager: Force removing ActivityRecord{3452580b u0 com.test.thalitest/.MainActivity t17}: app died, no saved state
,03-24 17:46:55.366   823   823 V ActivityManager: Display changed displayId=0
03-24 17:46:55.371   823   867 I ActivityManager: Force stopping com.test.thalitest appid=10095 user=0: pkg removed
,03-24 17:46:55.388   823  1417 W ActivityManager: Spurious death for ProcessRecord{14b2ae0a 3273:com.test.thalitest/u0a95}, curProc for 3273: null
,03-24 17:46:55.405   823  1053 D TaskPersister: removeObsoleteFile: deleting file=17_task.xml
,03-24 17:46:55.413  1248  1248 I Keyboard.Facilitator: resetDictionaries() : en_US
,03-24 17:46:55.414  2984  2984 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,03-24 17:46:55.419  1248  3986 I Keyboard.Facilitator.DecoderInitializer: run()
03-24 17:46:55.419   823  1010 I InputReader: Reconfiguring input devices.  changes=0x00000010
,03-24 17:46:55.421  1248  3986 I Decoder : createOrResetDecoder
,03-24 17:46:55.458   823   823 I art     : Explicit concurrent mark sweep GC freed 21107(1248KB) AllocSpace objects, 7(394KB) LOS objects, 32% free, 33MB/49MB, paused 1.664ms total 75.631ms
,03-24 17:46:55.458  1074  1074 I art     : Explicit concurrent mark sweep GC freed 57110(2MB) AllocSpace objects, 1(30MB) LOS objects, 20% free, 61MB/77MB, paused 1.511ms total 67.802ms
,03-24 17:46:55.460  1538  1538 I art     : Explicit concurrent mark sweep GC freed 11597(566KB) AllocSpace objects, 2(32KB) LOS objects, 22% free, 26MB/34MB, paused 515us total 82.770ms
,03-24 17:46:55.463   823  1413 I ActivityManager: Start proc 3988:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,03-24 17:46:55.470   823  1404 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3273 uid 10095
,03-24 17:46:55.471  1248  1248 I Keyboard.Facilitator: onFinishInput()
,03-24 17:46:55.482  1265  1265 I ConfigService: onCreate
,03-24 17:46:55.519  1248  3986 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,03-24 17:46:55.525  1538  1538 W LocationOracleImpl: Best location was null
,03-24 17:46:55.539  1369  1369 I art     : Explicit concurrent mark sweep GC freed 4974(363KB) AllocSpace objects, 12(1408KB) LOS objects, 31% free, 35MB/51MB, paused 780us total 24.480ms
,03-24 17:46:55.547   823   823 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
03-24 17:46:55.547   823   823 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,03-24 17:46:55.549  1538  4010 I HotwordRecognitionRnr: Starting hotword detection.
,03-24 17:46:55.550  1538  4011 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.u@256c7131
,03-24 17:46:55.551   359  4013 I AudioFlinger: AudioFlinger's thread 0xb40a3000 ready to run
,03-24 17:46:55.554   359  1036 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,03-24 17:46:55.555  1538  4011 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.u@256c7131
,03-24 17:46:55.565   359  4013 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
03-24 17:46:55.565   359  4013 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
03-24 17:46:55.565   359  4013 E ACDB-LOADER: Error: ACDB AudProc vol returned = -19
03-24 17:46:55.565   359  4013 D audio_hw_primary: enable_snd_device: snd_device(55: voice-rec-mic)
,03-24 17:46:55.573   359  4013 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,03-24 17:46:55.578  1248  3986 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
03-24 17:46:55.579  1248  3986 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
03-24 17:46:55.579  1248  3986 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,03-24 17:46:55.584  1248  3986 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
03-24 17:46:55.584  1248  3986 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
03-24 17:46:55.584  1248  3986 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
03-24 17:46:55.584  1248  3986 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,03-24 17:46:55.586  1248  3986 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,03-24 17:46:55.586  1248  3986 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
,03-24 17:46:55.586  1248  3986 I Keyboard.Facilitator.Delight2FileSweeper: run()
03-24 17:46:55.586  1248  3986 I Keyboard.Facilitator.RecurringTaskScheduler: run()
,03-24 17:46:55.586  1248  3986 I StatsUtilsManager: startPeriodStatsRecorder() : Success
03-24 17:46:55.586  1248  3986 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,03-24 17:46:55.633   823  1151 D WifiService: acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@1ba7540b}
,03-24 17:46:55.637   823  1019 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=140.06 rxSuccessRate=171.88 targetRoamBSSID=any RSSI=-127
,03-24 17:46:55.641  3988  4027 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,03-24 17:46:55.642  1538  1538 I HotwordWorker: onReady
,03-24 17:46:55.651   823   867 I art     : Explicit concurrent mark sweep GC freed 11092(996KB) AllocSpace objects, 1(110KB) LOS objects, 32% free, 33MB/49MB, paused 3.400ms total 173.946ms
,03-24 17:46:55.654  1538  4016 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,03-24 17:46:55.666   823  1154 I ActivityManager: Start proc 4028:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,03-24 17:46:55.675   823  1019 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=455.03 rxSuccessRate=590.94 targetRoamBSSID=any RSSI=-127
,03-24 17:46:55.681  3988  4025 I ContactLocale: AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,03-24 17:46:55.684  1538  4016 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 5109-5112)
03-24 17:46:55.684  1538  4016 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-24 17:46:55.688  1538  4016 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-24 17:46:55.692   823  1283 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1659516179
03-24 17:46:55.692   823  1283 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,03-24 17:46:55.722  3972  3972 I art     : System.exit called, status: 0
03-24 17:46:55.722  3972  3972 I AndroidRuntime: VM exiting with result code 0.
,03-24 17:46:55.731   823  1154 I ActivityManager: Start proc 4054:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,03-24 17:46:55.766   874   874 I kickstart: STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
03-24 17:46:55.767   874   874 I kickstart: STATUS: Wrote to /sys/power/wake_lock
,03-24 17:46:55.783   823   867 I ActivityManager: Start proc 4071:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,03-24 17:46:55.791  1369  1369 D Launcher.Workspace: 11683562 - stripEmptyScreens()
03-24 17:46:55.792  1369  1369 D Launcher.Workspace: 11683562 - stripEmptyScreens()
,03-24 17:46:55.808   874   874 E kickstart: ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2
03-24 17:46:55.808   874   874 I kickstart: STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2' for writing
,03-24 17:46:55.811   823   839 I ActivityManager: Killing 3613:com.qualcomm.timeservice/1000 (adj 15): empty #17
,03-24 17:46:55.816  1538  4016 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-24 17:46:55.810  4054  4054 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
,03-24 17:46:55.941  1265  1265 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
03-24 17:46:55.942  1265  1265 D AndroidRuntime: Shutting down VM
,--------- beginning of crash
03-24 17:46:55.943  1265  1265 E AndroidRuntime: FATAL EXCEPTION: main
03-24 17:46:55.943  1265  1265 E AndroidRuntime: Process: com.google.process.gapps, PID: 1265
03-24 17:46:55.943  1265  1265 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-24 17:46:55.943  1265  1265 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2616)
03-24 17:46:55.943  1265  1265 E AndroidRuntime: 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
03-24 17:46:55.943  1265  1265 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
03-24 17:46:55.943  1265  1265 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-24 17:46:55.943  1265  1265 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
03-24 17:46:55.943  1265  1265 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5254)
03-24 17:46:55.943  1265  1265 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
03-24 17:46:55.943  1265  1265 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-24 17:46:55.943  1265  1265 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
03-24 17:46:55.943  1265  1265 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
03-24 17:46:55.943  1265  1265 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-24 17:46:55.943  1265  1265 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
03-24 17:46:55.943  1265  1265 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
03-24 17:46:55.943  1265  1265 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
03-24 17:46:55.943  1265  1265 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
03-24 17:46:55.943  1265  1265 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
03-24 17:46:55.943  1265  1265 E AndroidRuntime: 	at com.google.android.gms.gcm.bh.a(SourceFile:310)
03-24 17:46:55.943  1265  1265 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:127)
03-24 17:46:55.943  1265  1265 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:321)
03-24 17:46:55.943  1265  1265 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2609)
03-24 17:46:55.943  1265  1265 E AndroidRuntime: 	... 9 more
,03-24 17:46:55.958  4054  4094 E SQLiteDatabase: Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
03-24 17:46:55.958  4054  4094 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-24 17:46:55.958  4054  4094 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-24 17:46:55.958  4054  4094 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-24 17:46:55.958  4054  4094 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-24 17:46:55.958  4054  4094 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-24 17:46:55.958  4054  4094 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-24 17:46:55.958  4054  4094 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-24 17:46:55.958  4054  4094 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-24 17:46:55.958  4054  4094 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-24 17:46:55.958  4054  4094 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-24 17:46:55.958  4054  4094 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-24 17:46:55.958  4054  4094 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-24 17:46:55.958  4054  4094 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-24 17:46:55.958  4054  4094 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-24 17:46:55.958  4054  4094 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
03-24 17:46:55.958  4054  4094 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
03-24 17:46:55.958  4054  4094 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-24 17:46:55.958  4054  4094 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-24 17:46:55.958  4054  4094 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
03-24 17:46:55.958  4054  4094 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-24 17:46:55.959  4054  4094 E AndroidRuntime: FATAL EXCEPTION: IntentService[KeyChainService]
03-24 17:46:55.959  4054  4094 E AndroidRuntime: Process: com.android.keychain, PID: 4054
03-24 17:46:55.959  4054  4094 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-24 17:46:55.959  4054  4094 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-24 17:46:55.959  4054  4094 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-24 17:46:55.959  4054  4094 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-24 17:46:55.959  4054  4094 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-24 17:46:55.959  4054  4094 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-24 17:46:55.959  4054  4094 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-24 17:46:55.959  4054  4094 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-24 17:46:55.959  4054  4094 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.ja,va:791)
03-24 17:46:55.959  4054  4094 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-24 17:46:55.959  4054  4094 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-24 17:46:55.959  4054  4094 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-24 17:46:55.959  4054  4094 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-24 17:46:55.959  4054  4094 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-24 17:46:55.959  4054  4094 E AndroidRuntime: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
03-24 17:46:55.959  4054  4094 E AndroidRuntime: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
03-24 17:46:55.959  4054  4094 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-24 17:46:55.959  4054  4094 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-24 17:46:55.959  4054  4094 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
03-24 17:46:55.959  4054  4094 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-24 17:46:55.967   823  4101 E DropBoxManagerService: Can't write: system_app_crash
03-24 17:46:55.967   823  4101 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop95.tmp: open failed: EROFS (Read-only file system)
03-24 17:46:55.967   823  4101 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-24 17:46:55.967   823  4101 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-24 17:46:55.967   823  4101 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-24 17:46:55.967   823  4101 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-24 17:46:55.967   823  4101 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-24 17:46:55.967   823  4101 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
03-24 17:46:55.967   823  4101 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-24 17:46:55.967   823  4101 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-24 17:46:55.967   823  4101 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-24 17:46:55.967   823  4101 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-24 17:46:55.967   823  4101 E DropBoxManagerService: 	... 5 more
,03-24 17:46:55.967   823  4099 E DropBoxManagerService: Can't write: system_app_crash
03-24 17:46:55.967   823  4099 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop94.tmp: open failed: EROFS (Read-only file system)
03-24 17:46:55.967   823  4099 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456),
03-24 17:46:55.967   823  4099 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-24 17:46:55.967   823  4099 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-24 17:46:55.967   823  4099 E DropBoxManagerService: 	,at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-24 17:46:55.967   823  4099 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-24 17:46:55.967   823  4099 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
,03-24 17:46:55.967   823  4099 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-24 17:46:55.967   823  4099 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-24 17:46:55.967   823  4099 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-24 17:46:55.967   823  4099 E DropBoxManagerService: 	,at libcore.io.IoBridge.open(IoBridge.java:442)
03-24 17:46:55.967   823  4099 E DropBoxManagerService: 	... 5 more
,03-24 17:46:55.991   823  4106 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,03-24 17:46:55.991   823   857 D Atlas   : Validating map...
,03-24 17:46:56.030   823  4106 I OpenGLRenderer: Initialized EGL, version 1.4
,03-24 17:46:56.037   823  4106 D OpenGLRenderer: Enabling debug mode 0
,03-24 17:46:56.266  1538  1538 I HotwordDetector: Closing mic
03-24 17:46:56.267  1538  1804 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.u@256c7131
,03-24 17:46:56.299  1538  4112 E Search.SharedPreferencesProto: Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,03-24 17:46:56.347   359  4013 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
,03-24 17:46:56.353   359  4013 D audio_hw_primary: disable_snd_device: snd_device(55: voice-rec-mic)
,03-24 17:46:56.382   359  1036 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,03-24 17:46:56.385  1538  1805 I HotwordRecognitionRnr: Stopping hotword detection.
03-24 17:46:56.385  1538  4010 I HotwordRecognitionRnr: Hotword detection finished
,03-24 17:46:56.634  1248  3986 E native  : dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
03-24 17:46:56.634  1248  3986 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp,
,03-24 17:46:56.669  1248  3986 E native  : dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
03-24 17:46:56.669  1248  3986 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,03-24 17:46:56.692  1248  3986 E native  : dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
03-24 17:46:56.692  1248  3986 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
03-24 17:46:56.693  1248  3986 E native  : dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
03-24 17:46:56.693  1248  3986 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
,03-24 17:46:56.895   874   874 E kickstart: ERROR: function: rx_data:267 Timeout Occured, No response or command came from the target!
,03-24 17:46:56.895   874   874 I kickstart: WARNING: function: sahara_start:892 Retrying memory read request
,03-24 17:46:57.320   823  1151 D WifiService: releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@1ba7540b}
,03-24 17:46:57.897   874   874 E kickstart: ERROR: function: rx_data:267 Timeout Occured, No response or command came from the target!
,03-24 17:46:57.897   874   874 I kickstart: WARNING: function: sahara_start:892 Retrying memory read request
,03-24 17:46:58.231  1538  4115 E Search.SharedPreferencesProto: Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,03-24 17:46:58.239   823  1151 I ActivityManager: Killing 2382:com.google.android.calendar/u0a37 (adj 15): empty #17
,03-24 17:46:58.347   823  1151 I ActivityManager: Killing 3595:com.google.android.apps.photos/u0a71 (adj 15): empty #18
,03-24 17:46:58.899   874   874 E kickstart: ERROR: function: rx_data:267 Timeout Occured, No response or command came from the target!
,03-24 17:46:58.899   874   874 I kickstart: WARNING: function: sahara_start:892 Retrying memory read request
,03-24 17:46:59.900   874   874 E kickstart: ERROR: function: rx_data:267 Timeout Occured, No response or command came from the target!
,03-24 17:46:59.900   874   874 I kickstart: WARNING: function: sahara_start:892 Retrying memory read request
,03-24 17:47:00.902   874   874 E kickstart: ERROR: function: rx_data:267 Timeout Occured, No response or command came from the target!
03-24 17:47:00.902   874   874 E kickstart: ERROR: function: sahara_main:1143 Sahara protocol error
,03-24 17:47:00.903   874   874 E kickstart: ERROR: function: main:268 Uploading  Image using Sahara protocol failed
03-24 17:47:00.904   874   874 I kickstart: STATUS: Wrote to /sys/power/wake_unlock
,03-24 17:47:01.148   823  1283 E QMI_FW  : xport_send: Sendto failed for port 3840
03-24 17:47:01.149   823  1283 E LocSvc_api_v02: E/locClientSendReq:2446]: send_msg_sync error: -1
03-24 17:47:01.149   823  1283 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 11, ind.status = -1659516179
03-24 17:47:01.149   823  1283 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
03-24 17:47:01.149   823  1283 E QMI_FW  : xport_send: Sendto failed for port 3840
03-24 17:47:01.149   823  1283 E LocSvc_api_v02: E/locClientSendReq:2446]: send_msg_sync error: -1
03-24 17:47:01.149   823  1283 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::injectLocation(GpsExtLocation):857]: error! inject position failed
,03-24 17:47:01.157   259   321 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
