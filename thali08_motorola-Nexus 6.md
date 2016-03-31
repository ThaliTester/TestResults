#### Test 646138038b5bc7c_thali08_motorola-Nexus 6 Logs


```
--------- beginning of main
,03-31 17:40:56.353  2163  2210 D HeadsetStateMachine: Disconnected process message: 10, size: 0
03-31 17:40:56.618  3256  3256 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
03-31 17:40:56.621  3256  3256 D AndroidRuntime: CheckJNI is OFF
03-31 17:40:56.744  3256  3256 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
03-31 17:40:56.752   823  1150 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
03-31 17:40:56.782   823  1150 V WindowManager: addAppToken: AppWindowToken{3c876286 token=Token{2c288761 ActivityRecord{1fd41ac8 u0 com.test.thalitest/.MainActivity t17}}} to stack=1 task=17 at 0
03-31 17:40:56.790   823   862 V WindowManager: Adding window Window{1a01c199 u0 Starting com.test.thalitest} at 2 of 7 (after Window{7abe75 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
03-31 17:40:56.792  3256  3256 D AndroidRuntime: Shutting down VM
03-31 17:40:56.797  1546  1758 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.u@52c16cb
03-31 17:40:56.797  1546  1546 I HotwordDetector: Closing mic
03-31 17:40:56.846   823   841 I ActivityManager: Start proc 3270:com.test.thalitest/u0a95 for activity com.test.thalitest/.MainActivity
03-31 17:40:56.865   359  1765 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
03-31 17:40:56.866   359  1765 D audio_hw_primary: disable_snd_device: snd_device(55: voice-rec-mic)
03-31 17:40:56.873   359  1020 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
03-31 17:40:56.875  1546  1760 I HotwordRecognitionRnr: Stopping hotword detection.
03-31 17:40:56.875  1546  1762 I HotwordRecognitionRnr: Hotword detection finished
03-31 17:40:56.922   823  1370 I ActivityManager: Killing 2899:com.android.settings/1000 (adj 15): empty #17
03-31 17:40:56.985   823  1271 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1658479891
03-31 17:40:56.985   823  1271 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,03-31 17:40:57.027   823  1370 I ActivityManager: Killing 2865:com.google.android.apps.messaging/u0a75 (adj 15): empty #18
03-31 17:40:57.070   873   873 I kickstart: STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
03-31 17:40:57.071   873   873 I kickstart: STATUS: Wrote to /sys/power/wake_lock
03-31 17:40:57.112   873   873 E kickstart: ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1
03-31 17:40:57.112   873   873 I kickstart: STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1' for writing
03-31 17:40:57.203  3270  3270 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
03-31 17:40:57.216  3270  3270 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 6961-6965)
03-31 17:40:57.216  3270  3270 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-31 17:40:57.249  3270  3270 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {212fc22d}
03-31 17:40:57.250  3270  3270 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-31 17:40:57.251  3270  3270 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
03-31 17:40:57.264  3270  3270 I BrowserStartupController: Initializing chromium process, singleProcess=true
03-31 17:40:57.265  3270  3270 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-31 17:40:57.266  3270  3270 E SysUtils: ApplicationContext is null in ApplicationStatus
03-31 17:40:57.273  3270  3294 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
03-31 17:40:57.281  3270  3270 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
03-31 17:40:57.288  3270  3270 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-31 17:40:57.288  3270  3270 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-31 17:40:57.288  3270  3270 I Adreno  : EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
03-31 17:40:57.387   823   861 D BluetoothManagerService: Message: 20
03-31 17:40:57.387   823   861 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@19f4790e:true
03-31 17:40:57.427  3270  3270 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-31 17:40:57.435  3270  3270 W AwContents: onDetachedFromWindow called when already detached. Ignoring
03-31 17:40:57.447  3270  3270 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
03-31 17:40:57.452  3270  3270 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-31 17:40:57.452  3270  3270 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-31 17:40:57.492  3270  3316 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
03-31 17:40:57.495  3270  3270 D Atlas   : Validating map...
03-31 17:40:57.500   823   841 V WindowManager: Adding window Window{2df741be u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{1a01c199 u0 Starting com.test.thalitest})
03-31 17:40:57.502  3270  3303 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
03-31 17:40:57.552  3270  3316 I OpenGLRenderer: Initialized EGL, version 1.4
03-31 17:40:57.569  3270  3316 D OpenGLRenderer: Enabling debug mode 0
03-31 17:40:57.662   823   862 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +865ms
03-31 17:40:57.670  1251  1251 I Keyboard.Facilitator: onFinishInput()
03-31 17:40:57.700  3270  3270 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3270
03-31 17:40:57.815  3270  3270 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
03-31 17:40:57.940  3270  3320 D jxcore_app_log: JniHelper::setJavaVM(0xb489d200), pthread_self() = -1573425920
03-31 17:40:57.944  3270  3320 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-31 17:40:57.944  3270  3320 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-31 17:40:57.944  3270  3320 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-31 17:40:57.944  3270  3320 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-31 17:40:57.944  3270  3320 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-31 17:40:57.944  3270  3320 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@270710e added. We now have 1 listener(s)
03-31 17:40:57.945   823  1370 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-31 17:40:57.947  3270  3320 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
03-31 17:40:57.948  3270  3320 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-31 17:40:57.949  3270  3320 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
03-31 17:40:57.949  3270  3320 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
03-31 17:40:57.953  3270  3320 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-31 17:40:57.953  3270  3320 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-31 17:40:57.953  3270  3320 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-31 17:40:57.953  3270  3320 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
03-31 17:40:57.953  3270  3320 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-31 17:40:57.953  3270  3320 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-31 17:40:57.953  3270  3320 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
03-31 17:40:57.953  3270  3320 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-31 17:40:57.953  3270  3320 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-31 17:40:57.953  3270  3320 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-31 17:40:57.953  3270  3320 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-31 17:40:57.953  3270  3320 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27605ec5 added. We now have 1 listener(s)
03-31 17:40:57.953  3270  3320 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
03-31 17:40:57.958   823  1022 D WifiService: New client listening to asynchronous messages
03-31 17:40:57.961  3270  3320 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
03-31 17:40:57.965  3270  3320 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
03-31 17:40:57.965  3270  3320 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
03-31 17:40:57.967  3270  3320 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
03-31 17:40:57.967  3270  3320 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
03-31 17:40:57.972  3270  3320 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 17:40:57.974   823  1149 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-31 17:40:57.975  3270  3320 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,03-31 17:40:57.981  3270  3320 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 17:40:57.981  3270  3320 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 17:40:57.981  3270  3320 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 17:40:57.981  3270  3320 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 17:40:57.981  3270  3320 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true,
03-31 17:40:57.981  3270  3320 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
03-31 17:40:57.981  3270  3320 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
03-31 17:40:57.981  3270  3320 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
03-31 17:40:57.982  3270  3320 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-31 17:40:57.982  3270  3320 D io.jxcore.node.ConnectivityMonitor: start: OK
,03-31 17:40:57.984  3270  3320 I io.jxcore.node.LifeCycleMonitor: start: OK
03-31 17:40:57.984  3270  3270 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-31 17:40:58.102   873   873 I kickstart: STATUS: Received file 'm9kefs1'
03-31 17:40:58.102   873   873 I kickstart: STATUS: 950272 bytes transferred in 0.989856 seconds
03-31 17:40:58.102   873   873 I kickstart: STATUS: Successfully downloaded files from target 
03-31 17:40:58.102   873   873 I kickstart: STATUS: Wrote to /sys/power/wake_unlock
,03-31 17:40:58.105   873   873 I kickstart: STATUS: Sahara protocol completed
,03-31 17:40:58.133  3270  3270 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-31 17:40:58.634  3270  3328 W jxcore-log: Initializing JXcore engine
03-31 17:40:58.634  3270  3328 W jxcore-log: JXcore engine is ready
,03-31 17:40:58.661  3328  3328 W Thread-349: type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[13023]" dev="sockfs" ino=13023 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,03-31 17:40:58.661  3328  3328 W Thread-349: type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
03-31 17:40:58.661  3328  3328 W Thread-349: type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[10517]" dev="sockfs" ino=10517 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
03-31 17:40:58.661  3328  3328 W Thread-349: type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[21145]" dev="sockfs" ino=21145 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,03-31 17:40:58.686  3270  3328 W jxcore-log: Starting JXcore engine
,03-31 17:40:58.778  3270  3328 W jxcore-log: Platform android
03-31 17:40:58.778  3270  3328 W jxcore-log: 
03-31 17:40:58.778  3270  3328 W jxcore-log: Process ARCH arm
03-31 17:40:58.778  3270  3328 W jxcore-log: 
,03-31 17:40:59.004  3270  3328 I jxcore-log: JXcore Cordova bridge is ready!
03-31 17:40:59.004  3270  3328 I jxcore-log: 
03-31 17:40:59.004  3270  3328 W jxcore-log: JXcore engine is started
,03-31 17:40:59.015  3270  3320 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-31 17:40:59.018  3270  3270 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,03-31 17:41:08.291  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 17:41:08.291  3270  3328 I jxcore-log: 
,03-31 17:41:08.294  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native,
03-31 17:41:08.294  3270  3328 I jxcore-log: 
,03-31 17:41:08.300  3270  3328 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
,03-31 17:41:08.300  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
,03-31 17:41:08.300  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
,03-31 17:41:08.300  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 17:41:08.300  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true,
03-31 17:41:08.300  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
03-31 17:41:08.300  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false,
03-31 17:41:08.300  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false,
,03-31 17:41:08.307  3270  3328 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,03-31 17:41:08.309  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 17:41:08.309  3270  3328 I jxcore-log: 
,03-31 17:41:08.311  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 17:41:08.311  3270  3328 I jxcore-log: 
,03-31 17:41:08.833  3270  3328 I jxcore-log: Unit Test app is loaded
03-31 17:41:08.833  3270  3328 I jxcore-log: 
,03-31 17:41:08.845  3270  3270 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,03-31 17:41:08.848  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
03-31 17:41:08.848  3270  3328 I jxcore-log: 
,03-31 17:41:08.865  3270  3328 I jxcore-log: My device name is: motorola-Nexus 6
03-31 17:41:08.865  3270  3328 I jxcore-log: 
,03-31 17:41:12.678  3270  3328 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
03-31 17:41:12.678  3270  3328 I jxcore-log: 
,03-31 17:41:13.046  3270  3328 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
03-31 17:41:13.046  3270  3328 I jxcore-log: 
,03-31 17:41:13.059  3270  3328 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js,
03-31 17:41:13.059  3270  3328 I jxcore-log: 
,03-31 17:41:13.063  3270  3328 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
,03-31 17:41:13.063  3270  3328 I jxcore-log: 
,03-31 17:41:13.101  3270  3328 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
03-31 17:41:13.101  3270  3328 I jxcore-log: 
,03-31 17:41:13.117  3270  3328 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
03-31 17:41:13.117  3270  3328 I jxcore-log: 
,03-31 17:41:13.122  3270  3328 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
03-31 17:41:13.122  3270  3328 I jxcore-log: 
,03-31 17:41:13.123   823   864 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,03-31 17:41:13.134   823   864 I Adreno  : EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,03-31 17:41:13.153   258  3318 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (259 us)
,03-31 17:41:13.707   823   862 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
03-31 17:41:13.707   823   823 V ActivityManager: Display changed displayId=0
03-31 17:41:13.707   258   258 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6082000
03-31 17:41:13.708   258   258 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,03-31 17:41:13.982   258   315 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,03-31 17:41:13.985   258   258 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,03-31 17:41:13.985   823  1040 D SurfaceControl: Excessive delay in setPowerMode(): 278ms
,03-31 17:41:13.991   823   864 I DreamManagerService: Entering dreamland.
,03-31 17:41:13.992   359  1208 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,03-31 17:41:13.992   359  1208 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
03-31 17:41:13.994   823   859 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,03-31 17:41:14.000   823   864 I PowerManagerService: Dozing...
,03-31 17:41:14.008   823  1008 E WifiStateMachine: cancelDelayedScan -> 16
,03-31 17:41:14.010   823  1008 E native  : do suspend false
,03-31 17:41:14.102   823  1409 I art     : Explicit concurrent mark sweep GC freed 41452(2MB) AllocSpace objects, 3(48KB) LOS objects, 32% free, 33MB/49MB, paused 2.093ms total 53.658ms
,03-31 17:41:14.128  1251  1251 I Keyboard.Facilitator: onFinishInput()
,03-31 17:41:14.145   823  1008 E WifiStateMachine: cancelDelayedScan -> 18
,03-31 17:41:14.188   823  1008 E native  : do suspend true
,03-31 17:41:14.200   359   359 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
03-31 17:41:14.200   359   359 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,03-31 17:41:14.214   823  1008 E WifiStateMachine: WifiStateMachine Disconnected CMD_START_SCAN source -2 17, 18 -> obsolete
,03-31 17:41:14.236  1233  1233 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 17:41:14.254  1233  3087 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
03-31 17:41:14.254  1233  3087 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 17:41:14.254  1233  3087 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 17:41:14.254  1233  3087 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 17:41:14.257  1233  3087 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 17:41:14.266  2737  2737 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.,
03-31 17:41:14.266  2737  2737 D Finsky  : [1] 5.onFinished: Installation state replication failed.
03-31 17:41:14.266  2737  2737 D Finsky  : [1] 5.onFinished: Scheduling replication attempt 5.
,03-31 17:41:15.325  3270  3328 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
03-31 17:41:15.325  3270  3328 I jxcore-log: 
,03-31 17:41:15.342  3270  3328 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js,
03-31 17:41:15.342  3270  3328 I jxcore-log: 
,03-31 17:41:15.351  3270  3328 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js,
03-31 17:41:15.351  3270  3328 I jxcore-log: 
,03-31 17:41:15.356   823  1008 E WifiStateMachine: WifiStateMachine Disconnected CMD_START_SCAN source -2 15, 18 -> obsolete
,03-31 17:41:15.598  3270  3328 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
,03-31 17:41:15.598  3270  3328 I jxcore-log: 
,03-31 17:41:15.668  3270  3328 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
03-31 17:41:15.668  3270  3328 I jxcore-log: 
,03-31 17:41:15.723  3270  3328 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
03-31 17:41:15.723  3270  3328 I jxcore-log: 
,03-31 17:41:15.730  3270  3328 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
03-31 17:41:15.730  3270  3328 I jxcore-log: 
,03-31 17:41:15.740  3270  3328 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
03-31 17:41:15.740  3270  3328 I jxcore-log: 
,03-31 17:41:15.745  3270  3328 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
03-31 17:41:15.745  3270  3328 I jxcore-log: 
,03-31 17:41:15.750  3270  3328 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,03-31 17:41:15.750  3270  3328 I jxcore-log: 
,03-31 17:41:15.766  3270  3328 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
03-31 17:41:15.766  3270  3328 I jxcore-log: 
,03-31 17:41:15.785  3270  3328 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js,
03-31 17:41:15.785  3270  3328 I jxcore-log: 
,03-31 17:41:15.868  3270  3328 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
03-31 17:41:15.868  3270  3328 I jxcore-log: 
,03-31 17:41:15.873  3270  3328 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
03-31 17:41:15.873  3270  3328 I jxcore-log: 
,03-31 17:41:15.899  3270  3328 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js,
03-31 17:41:15.899  3270  3328 I jxcore-log: 
,03-31 17:41:15.910  3270  3328 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,03-31 17:41:15.912  3270  3328 I jxcore-log: INFO testUtils: BLE multiple advertisement supported,
03-31 17:41:15.912  3270  3328 I jxcore-log: 
,03-31 17:41:16.568  1124  1124 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700',
,03-31 17:41:16.989  1124  1124 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,03-31 17:41:17.025  1124  1124 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
03-31 17:41:17.026  1124  1124 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,03-31 17:41:17.053   823  1008 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
03-31 17:41:17.053   823  1008 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,03-31 17:41:17.055   823  1023 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING,
03-31 17:41:17.056   823  1008 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,03-31 17:41:17.062   355   815 D CommandListener: Setting iface cfg
,03-31 17:41:17.066   823  1008 E WifiStateMachine: Start Dhcp Watchdog 1
,03-31 17:41:17.071   823  1008 E WifiStateMachine:  WifiLinkLayerStats: 
03-31 17:41:17.071   823  1008 E WifiStateMachine:  my bss beacon rx: 1
03-31 17:41:17.071   823  1008 E WifiStateMachine:  RSSI mgmt: -40
03-31 17:41:17.071   823  1008 E WifiStateMachine:  BE :  rx=0 tx=3 lost=0 retries=0
03-31 17:41:17.071   823  1008 E WifiStateMachine:  BK :  rx=0 tx=0 lost=0 retries=0
03-31 17:41:17.071   823  1008 E WifiStateMachine:  VI :  rx=0 tx=0 lost=0 retries=0
03-31 17:41:17.071   823  1008 E WifiStateMachine:  VO :  rx=2 tx=0 lost=0 retries=0
03-31 17:41:17.071   823  1008 E WifiStateMachine:  on_time : 477 tx_time=62 rx_time=99 scan_time=0
,03-31 17:41:17.171   823  1008 E native  : do suspend false
,03-31 17:41:17.189   823  1008 E WifiStateMachine: scanCount==0 - aborting
,03-31 17:41:17.435  3343  3343 I dhcpcd  : version 5.5.6 starting
,03-31 17:41:17.525  3343  3343 I dhcpcd  : wlan0: rebinding lease of 192.168.1.125
,03-31 17:41:17.643  3343  3343 I dhcpcd  : wlan0: acknowledged 192.168.1.125 from 192.168.1.1
,03-31 17:41:17.701  3343  3343 I dhcpcd  : wlan0: leased 192.168.1.125 for 172800 seconds
,03-31 17:41:18.213   823  1008 E native  : do suspend true
,03-31 17:41:18.268   823  1023 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,03-31 17:41:18.273   823  1023 D ConnectivityService: Adding iface wlan0 to network 100
,03-31 17:41:18.277   823  1008 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,03-31 17:41:18.300   823  1023 E ConnectivityService: Unexpected mtu value: 0, wlan0
,03-31 17:41:18.300   823  1023 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 100
,03-31 17:41:18.302   823  1023 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,03-31 17:41:18.303   823  1023 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,03-31 17:41:18.304   823  1023 D ConnectivityService: Setting Dns servers for network 100 to [/192.168.1.1]
,03-31 17:41:18.312   823  1023 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,03-31 17:41:18.315   823  1023 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
,03-31 17:41:18.315   823  3341 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
,03-31 17:41:18.315   823  3341 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Connected
03-31 17:41:18.316   823  3341 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
03-31 17:41:18.316   823  1023 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
,03-31 17:41:18.316   823  3341 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
03-31 17:41:18.316   823  1023 D ConnectivityService:    accepting network in place of null
03-31 17:41:18.318   823  1023 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.125/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
03-31 17:41:18.319   823  1023 D ConnectivityService: Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
,03-31 17:41:18.322   823  1023 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,03-31 17:41:18.323   823  1023 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
03-31 17:41:18.323   823  1023 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
03-31 17:41:18.323  1061  1492 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
03-31 17:41:18.323   823  1023 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,03-31 17:41:18.327   823   861 D Tethering: MasterInitialState.processMessage what=3
,03-31 17:41:18.331   823  1409 V BackupManagerService: Scheduling immediate backup pass
,03-31 17:41:18.334   823   823 V BackupManagerService: Running a backup pass
,03-31 17:41:18.334   823  1038 V BackupManagerService: clearing pending backups
,03-31 17:41:18.338  3270  3270 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
03-31 17:41:18.338  3270  3270 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 17:41:18.338  3270  3270 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 17:41:18.338  3270  3270 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 17:41:18.338  3270  3270 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 17:41:18.338  3270  3270 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 17:41:18.338  3270  3270 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 17:41:18.338  3270  3270 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 17:41:18.341  1546  1546 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,03-31 17:41:18.342  3270  3270 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 17:41:18.344  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 17:41:18.344  3270  3328 I jxcore-log: 
03-31 17:41:18.344  2922  2922 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
03-31 17:41:18.344  1342  1637 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
03-31 17:41:18.345  1342  1637 E PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,03-31 17:41:18.347   823   856 D TelephonyManager: getDataEnabled: retVal=false
,03-31 17:41:18.350   823  1038 V PerformBackupTask: Beginning backup of 14 targets
,03-31 17:41:18.351  2922  2922 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,03-31 17:41:18.354   823  1038 D PerformBackupTask: invokeAgentForBackup on @pm@
,03-31 17:41:18.357   823  1038 V BackupServiceBinder: doBackup() invoked
,03-31 17:41:18.359   823   856 E GpsLocationProvider: No APN found to select.
,03-31 17:41:18.359   823  1038 I PMBA    : Previous metadata 1570415 mismatch vs 1860966 - rewriting
,03-31 17:41:18.375   823  1038 I BackupRestoreController: Getting widget state for user: 0
,03-31 17:41:18.387   823   842 I ActivityManager: Start proc 3383:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.steen.receiver.ConnectivityChangeReceiver
,03-31 17:41:18.402   371   371 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 318us total 13.608ms
,03-31 17:41:18.412   371   371 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 195us total 8.973ms
,03-31 17:41:18.425   371   371 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 206us total 12.119ms
03-31 17:41:18.425  1836  1866 W GmsBackupTransport: Unknown package in backup request: @pm@
,03-31 17:41:18.427  1836  1866 V GmsBackupTransport: starting performBackup for @pm@
,03-31 17:41:18.433  1836  1866 V GmsBackupTransport: performBackup done for @pm@
,03-31 17:41:18.442  1233  1233 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 17:41:18.465  1233  1640 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: android
03-31 17:41:18.466  1233  1640 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> android without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 17:41:18.466  1233  1640 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 17:41:18.466  1233  1640 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 17:41:18.471  1233  1640 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 17:41:18.474   823  1277 D AlarmManagerService: Setting time of day to sec=1459438878
03-31 17:41:18.804   823  1277 W AlarmManagerService: Unable to set rtc to 1459438878: Invalid argument
,03-31 17:41:18.831  1233  1640 W GLSActivity: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-31 17:41:18.831  1233  1640 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-31 17:41:18.831  1233  1640 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-31 17:41:18.831  1233  1640 W GLSActivity: 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
03-31 17:41:18.831  1233  1640 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
03-31 17:41:18.831  1233  1640 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
03-31 17:41:18.831  1233  1640 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:446)
,03-31 17:41:18.835  1836  1894 W GmsBackupTransport: Error sending final backup to server: 
03-31 17:41:18.835  1836  1894 W GmsBackupTransport: com.google.android.gms.backup.d.d: Can not get client auth token
03-31 17:41:18.835  1836  1894 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:1080)
03-31 17:41:18.835  1836  1894 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:65)
03-31 17:41:18.835  1836  1894 W GmsBackupTransport: 	at com.google.android.gms.backup.aa.finishBackup(SourceFile:409)
03-31 17:41:18.835  1836  1894 W GmsBackupTransport: 	at android.app.backup.BackupTransport$TransportImpl.finishBackup(BackupTransport.java:547)
03-31 17:41:18.835  1836  1894 W GmsBackupTransport: 	at com.android.internal.backup.IBackupTransport$Stub.onTransact(IBackupTransport.java:162)
03-31 17:41:18.835  1836  1894 W GmsBackupTransport: 	at android.os.Binder.execTransact(Binder.java:446)
03-31 17:41:18.835  1836  1894 W GmsBackupTransport: Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
03-31 17:41:18.835  1836  1894 W GmsBackupTransport: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
03-31 17:41:18.835  1836  1894 W GmsBackupTransport: 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
03-31 17:41:18.835  1836  1894 W GmsBackupTransport: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
03-31 17:41:18.835  1836  1894 W GmsBackupTransport: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
03-31 17:41:18.835  1836  1894 W GmsBackupTransport: 	... 1 more
,03-31 17:41:18.838   823  3402 D GpsLocationProvider: NTP server returned: 1459438878849 (Thu Mar 31 17:41:18 GMT+02:00 2016) reference: 168257 certainty: 41 system time offset: 12
,03-31 17:41:18.840   823  1038 D BackupManagerService: Now staging backup of com.google.android.talk
,03-31 17:41:18.893   823  1093 I ActivityManager: Start proc 3417:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,03-31 17:41:18.896   823  1038 D BackupManagerService: Now staging backup of com.google.android.dialer
,03-31 17:41:18.902   823  1038 D BackupManagerService: Now staging backup of com.android.providers.settings
,03-31 17:41:18.910   823  1038 D BackupManagerService: Now staging backup of com.android.sharedstoragebackup
,03-31 17:41:18.916   823  1038 D BackupManagerService: Now staging backup of com.google.android.gm
,03-31 17:41:18.918   823  1038 D BackupManagerService: Now staging backup of com.android.providers.userdictionary
,03-31 17:41:18.921   823  1038 D BackupManagerService: Now staging backup of com.android.nfc
,03-31 17:41:18.924   823  1038 D BackupManagerService: Now staging backup of com.google.android.apps.genie.geniewidget
,03-31 17:41:18.929   823  1038 D BackupManagerService: Now staging backup of com.google.android.marvin.talkback
,03-31 17:41:18.929  3417  3417 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,03-31 17:41:18.931   823  1038 D BackupManagerService: Now staging backup of com.google.android.inputmethod.latin
,03-31 17:41:18.936   823  1038 D BackupManagerService: Now staging backup of com.google.android.calendar
,03-31 17:41:18.938  3417  3417 D SprintDMHelper: simOperator:  IMSI: null
03-31 17:41:18.938  3417  3417 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,03-31 17:41:18.939   823  1038 D BackupManagerService: Now staging backup of com.android.vending
,03-31 17:41:18.941   823  1038 D BackupManagerService: Now staging backup of android
,03-31 17:41:18.943   823  1038 D BackupManagerService: Now staging backup of com.google.android.googlequicksearchbox
,03-31 17:41:18.945  1766  3437 W DriveInitializer: Background init thread started
,03-31 17:41:18.946  1836  1866 I GmsBackupTransport: Next backup will happen in 43199887 millis.
,03-31 17:41:18.950   823  1038 I BackupManagerService: Backup pass finished.
,03-31 17:41:18.954   823  3341 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 31 Mar 2016 15:41:18 GMT], X-Android-Received-Millis=[1459438878954], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1459438878818]}
,03-31 17:41:18.954   823  3341 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Validated
03-31 17:41:18.954   823  1023 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
03-31 17:41:18.955   823  1023 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 100]
03-31 17:41:18.955   823  1023 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
03-31 17:41:18.955   823  1023 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
03-31 17:41:18.955   823  1023 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
03-31 17:41:18.955  1061  1492 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
03-31 17:41:18.955   823  1023 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,03-31 17:41:18.960  1766  3438 W DriveInitializer: Awaiting to be initialized
,03-31 17:41:18.982  1766  1766 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,03-31 17:41:18.986  1766  1766 D SystemUpdateService: onCreate
,03-31 17:41:18.989  1766  1766 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,03-31 17:41:18.999  1766  3442 I SystemUpdateService: active receiver: enabled
,03-31 17:41:19.002  1766  3442 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,03-31 17:41:19.003  1233  1640 I art     : Explicit concurrent mark sweep GC freed 20042(1095KB) AllocSpace objects, 0(0B) LOS objects, 38% free, 26MB/42MB, paused 1.009ms total 23.235ms
,03-31 17:41:19.009  1766  3442 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]; metered: false; mobile allowed: true
,03-31 17:41:19.009  1766  3442 I SystemUpdateService: now status is 0 (complete)
,03-31 17:41:19.009  1766  3442 I SystemUpdateService: processDownloadedFile /data/data/com.google.android.gms/app_download/update.zip
,03-31 17:41:19.009  1766  3442 I SystemUpdateService: file has been verified
03-31 17:41:19.010  1766  3442 I SystemUpdateService: OTA package size = 25802302
,03-31 17:41:19.017  1766  3442 I SystemUpdateService: showing system update notification
,03-31 17:41:19.036   823   823 I ValidateNoPeople: skipping global notification
,03-31 17:41:19.062   823   856 I ActivityManager: Start proc 3448:com.google.android.keep/u0a79 for service com.google.android.keep/.syncadapter.KeepSyncAdapterService
,03-31 17:41:19.081  1766  3467 I iu.SyncManager: SYNC; picasa accounts
,03-31 17:41:19.085  1766  1766 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,03-31 17:41:19.091  1766  1766 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,03-31 17:41:19.093  1766  3437 W DriveInitializer: Background init thread ended
,03-31 17:41:19.102  1766  1766 D SystemUpdateService: onDestroy
,03-31 17:41:19.113  1766  3467 I iu.UploadsManager: num queued entries: 0
,03-31 17:41:19.114  1766  3467 I iu.UploadsManager: num updated entries: 0
,03-31 17:41:19.119  1766  3467 I iu.SyncManager: NEXT; no task
,03-31 17:41:19.126  1766  1766 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,03-31 17:41:19.130  1233  2542 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-31 17:41:19.130  1233  2542 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 17:41:19.130  1233  2542 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 17:41:19.130  1233  2542 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 17:41:19.133  1233  2542 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-31 17:41:19.132  1766  1766 I Kids    : [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
,03-31 17:41:19.167   823  1150 I ActivityManager: Start proc 3480:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,03-31 17:41:19.176  3104  3433 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
03-31 17:41:19.176  3104  3433 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-31 17:41:19.176  3104  3433 E HttpOperation: 	at jdm.a(PG:82)
03-31 17:41:19.176  3104  3433 E HttpOperation: 	at jcs.o(PG:406)
03-31 17:41:19.176  3104  3433 E HttpOperation: 	at jcn.a(PG:1379)
03-31 17:41:19.176  3104  3433 E HttpOperation: 	at jcs.i(PG:143)
03-31 17:41:19.176  3104  3433 E HttpOperation: 	at blb.a(PG:3937)
03-31 17:41:19.176  3104  3433 E HttpOperation: 	at czp.a(PG:18188)
03-31 17:41:19.176  3104  3433 E HttpOperation: 	at czp.a(PG:9081)
03-31 17:41:19.176  3104  3433 E HttpOperation: 	at czq.run(PG:1686)
03-31 17:41:19.176  3104  3433 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-31 17:41:19.176  3104  3433 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-31 17:41:19.176  3104  3433 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 17:41:19.176  3104  3433 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 17:41:19.176  3104  3433 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-31 17:41:19.176  3104  3433 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-31 17:41:19.176  3104  3433 E HttpOperation: 	at jdj.a(PG:4091)
03-31 17:41:19.176  3104  3433 E HttpOperation: 	at jdj.a(PG:1125)
03-31 17:41:19.176  3104  3433 E HttpOperation: 	at jdm.a(PG:77)
03-31 17:41:19.176  3104  3433 E HttpOperation: 	... 12 more
03-31 17:41:19.176  3104  3433 E HttpOperation: Caused by: faj: BadAuthentication
03-31 17:41:19.176  3104  3433 E HttpOperation: 	at fal.a(PG:38)
03-31 17:41:19.176  3104  3433 E HttpOperation: 	at jdj.a(PG:4089)
03-31 17:41:19.176  3104  3433 E HttpOperation: 	... 14 more
,03-31 17:41:19.211  1233  2542 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-31 17:41:19.211  1233  2542 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 17:41:19.211  1233  2542 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 17:41:19.211  1233  2542 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 17:41:19.214  1233  2542 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 17:41:19.227  3104  3433 E HttpOperation: [getmobileexperiments] Unexpected exception
03-31 17:41:19.227  3104  3433 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-31 17:41:19.227  3104  3433 E HttpOperation: 	at jdm.a(PG:82)
03-31 17:41:19.227  3104  3433 E HttpOperation: 	at jcs.o(PG:406)
03-31 17:41:19.227  3104  3433 E HttpOperation: 	at jcn.a(PG:1379)
03-31 17:41:19.227  3104  3433 E HttpOperation: 	at jcs.i(PG:143)
03-31 17:41:19.227  3104  3433 E HttpOperation: 	at hec.a(PG:42)
03-31 17:41:19.227  3104  3433 E HttpOperation: 	at hee.a(PG:102)
03-31 17:41:19.227  3104  3433 E HttpOperation: 	at czr.a(PG:65)
03-31 17:41:19.227  3104  3433 E HttpOperation: 	at kka.a(PG:108)
03-31 17:41:19.227  3104  3433 E HttpOperation: 	at czp.a(PG:19176)
03-31 17:41:19.227  3104  3433 E HttpOperation: 	at czp.a(PG:9081)
03-31 17:41:19.227  3104  3433 E HttpOperation: 	at czq.run(PG:1686)
03-31 17:41:19.227  3104  3433 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-31 17:41:19.227  3104  3433 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-31 17:41:19.227  3104  3433 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 17:41:19.227  3104  3433 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 17:41:19.227  3104  3433 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-31 17:41:19.227  3104  3433 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-31 17:41:19.227  3104  3433 E HttpOperation: 	at jdj.a(PG:4091)
03-31 17:41:19.227  3104  3433 E HttpOperation: 	at jdj.a(PG:1125)
03-31 17:41:19.227  3104  3433 E HttpOperation: 	at jdm.a(PG:77)
03-31 17:41:19.227  3104  3433 E HttpOperation: 	... 15 more
03-31 17:41:19.227  3104  3433 E HttpOperation: Caused by: faj: BadAuthentication
03-31 17:41:19.227  3104  3433 E HttpOperation: 	at fal.a(PG:38)
03-31 17:41:19.227  3104  3433 E HttpOperation: 	at jdj.a(PG:4089)
03-31 17:41:19.227  3104  3433 E HttpOperation: 	... 17 more
03-31 17:41:19.227  3104  3433 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
03-31 17:41:19.227  3104  3433 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
03-31 17:41:19.227  3104  3433 E ExperimentLoader: 	at jdm.a(PG:82)
03-31 17:41:19.227  3104  3433 E ExperimentLoader: 	at jcs.o(PG:406)
03-31 17:41:19.227  3104  3433 E ExperimentLoader: 	at jcn.a(PG:1379)
03-31 17:41:19.227  3104  3433 E ExperimentLoader: 	at jcs.i(PG:143)
03-31 17:41:19.227  3104  3433 E ExperimentLoader: 	at hec.a(PG:42)
03-31 17:41:19.227  3104  3433 E ExperimentLoader: 	at hee.a(PG:102)
03-31 17:41:19.227  3104  3433 E ExperimentLoader: 	at czr.a(PG:65)
03-31 17:41:19.227  3104  3433 E ExperimentLoader: 	at kka.a(PG:108)
03-31 17:41:19.227  3104  3433 E ExperimentLoader: 	at czp.a(PG:19176)
03-31 17:41:19.227  3104  3433 E ExperimentLoader: 	at czp.a(PG:9081)
03-31 17:41:19.227  3104  3433 E ExperimentLoader: 	at czq.run(PG:1686)
03-31 17:41:19.227  3104  3433 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-31 17:41:19.227  3104  3433 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-31 17:41:19.227  3104  3433 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 17:41:19.227  3104  3433 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 17:41:19.227  3104  3433 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
03-31 17:41:19.227  3104  3433 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-31 17:41:19.227  3104  3433 E ExperimentLoader: 	at jdj.a(PG:4091)
03-31 17:41:19.227  3104  3433 E ExperimentLoader: 	at jdj.a(PG:1,125)
03-31 17:41:19.227  3104  3433 E ExperimentLoader: 	at jdm.a(PG:77)
03-31 17:41:19.227  3104  3433 E ExperimentLoader: 	... 15 more
03-31 17:41:19.227  3104  3433 E ExperimentLoader: Caused by: faj: BadAuthentication
03-31 17:41:19.227  3104  3433 E ExperimentLoader: 	at fal.a(PG:38)
03-31 17:41:19.227  3104  3433 E ExperimentLoader: 	at jdj.a(PG:4089)
03-31 17:41:19.227  3104  3433 E ExperimentLoader: 	... 17 more
,03-31 17:41:19.294  3448  3504 V KeepSync: Connecting to GoogleApiClient
,03-31 17:41:19.299  3480  3480 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
03-31 17:41:19.299  3480  3480 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-31 17:41:19.299  3480  3480 I GAv4    :   adb logcat -s GAv4
,03-31 17:41:19.322  3480  3480 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,03-31 17:41:19.326   823   856 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 39135, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,03-31 17:41:19.332  3480  3480 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,03-31 17:41:19.337  3480  3513 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,03-31 17:41:19.346  1766  3512 W BaseAppContext: Using Auth Proxy for data requests.
,03-31 17:41:19.376   823   856 I ActivityManager: Start proc 3515:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,03-31 17:41:19.380  1766  3512 W BaseAppContext: Using Auth Proxy for data requests.
,03-31 17:41:19.386  3163  3476 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,03-31 17:41:19.393   823  1411 I ActivityManager: Killing 2432:com.google.android.apps.maps/u0a65 (adj 15): empty #17
,03-31 17:41:19.511  1233  2542 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
03-31 17:41:19.511  1233  2542 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 17:41:19.511  1233  2542 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 17:41:19.511  1233  2542 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 17:41:19.515  1233  2542 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 17:41:19.533  1766  3512 E ClientConnectionOperation: Handling authorization failure
03-31 17:41:19.533  1766  3512 E ClientConnectionOperation: com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
03-31 17:41:19.533  1766  3512 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
03-31 17:41:19.533  1766  3512 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
03-31 17:41:19.533  1766  3512 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
03-31 17:41:19.533  1766  3512 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
03-31 17:41:19.533  1766  3512 E ClientConnectionOperation: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-31 17:41:19.533  1766  3512 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 17:41:19.533  1766  3512 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 17:41:19.533  1766  3512 E ClientConnectionOperation: 	at java.lang.Thread.run(Thread.java:818)
03-31 17:41:19.533  1766  3512 E ClientConnectionOperation: Caused by: com.google.android.gms.auth.ad: BadAuthentication
03-31 17:41:19.533  1766  3512 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.b(SourceFile:442)
03-31 17:41:19.533  1766  3512 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:365)
03-31 17:41:19.533  1766  3512 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:310)
03-31 17:41:19.533  1766  3512 E ClientConnectionOperation: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
03-31 17:41:19.533  1766  3512 E ClientConnectionOperation: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
03-31 17:41:19.533  1766  3512 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:30)
03-31 17:41:19.533  1766  3512 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:370)
03-31 17:41:19.533  1766  3512 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:340)
03-31 17:41:19.533  1766  3512 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:319)
03-31 17:41:19.533  1766  3512 E ClientConnectionOperation: 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
03-31 17:41:19.533  1766  3512 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
03-31 17:41:19.533  1766  3512 E ClientConnectionOperation: 	... 7 more
,03-31 17:41:19.537  3448  3504 V KeepSync: GoogleApiClient failed to connect with error code: 4
,03-31 17:41:19.545  3448  3504 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-31 17:41:19.546  1233  3511 D GCM     : Connected
,03-31 17:41:19.554  3448  3504 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
03-31 17:41:19.554  3448  3504 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-31 17:41:19.627  3480  3480 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,03-31 17:41:19.638  3480  3480 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 9055-9057)
,03-31 17:41:19.638  3480  3480 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-31 17:41:19.642  3480  3480 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2597d858}
03-31 17:41:19.642  3480  3480 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-31 17:41:19.642  3480  3480 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
03-31 17:41:19.650  3480  3480 I BrowserStartupController: Initializing chromium process, singleProcess=true
,03-31 17:41:19.651  3480  3480 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-31 17:41:19.652  3480  3480 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-31 17:41:19.662  3480  3480 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,03-31 17:41:19.667  3480  3480 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-31 17:41:19.667  3480  3480 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-31 17:41:19.668  3480  3480 I Adreno  : EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,03-31 17:41:19.696   823   841 I art     : Explicit concurrent mark sweep GC freed 51222(2MB) AllocSpace objects, 5(120KB) LOS objects, 32% free, 33MB/49MB, paused 1.447ms total 81.183ms
03-31 17:41:19.699  1233  3511 D GCM     : Message class com.google.f.a.a.p
,03-31 17:41:19.726  1233  1250 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,03-31 17:41:19.726  1233  1250 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 17:41:19.726  1233  1250 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 17:41:19.726  1233  1250 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 17:41:19.730  1233  1250 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 17:41:19.733  3480  3560 W AudioManagerAndroid: Requires BLUETOOTH permission
,03-31 17:41:19.745  3480  3480 I NSApplication: Starting up...
,03-31 17:41:19.792   823  1393 I ActivityManager: Start proc 3566:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,03-31 17:41:19.793   823  1393 I ActivityManager: Killing 3011:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,03-31 17:41:19.879  1233  2542 I art     : Explicit concurrent mark sweep GC freed 15911(908KB) AllocSpace objects, 5(362KB) LOS objects, 38% free, 26MB/42MB, paused 1.034ms total 25.693ms
,03-31 17:41:19.901  3448  3504 E KeepSync: IOException
03-31 17:41:19.901  3448  3504 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
03-31 17:41:19.901  3448  3504 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
03-31 17:41:19.901  3448  3504 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
03-31 17:41:19.901  3448  3504 E KeepSync: 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
03-31 17:41:19.901  3448  3504 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
03-31 17:41:19.901  3448  3504 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
03-31 17:41:19.901  3448  3504 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
03-31 17:41:19.901  3448  3504 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
03-31 17:41:19.901  3448  3504 E KeepSync: 	at com.google.android.keep.util.m.a(SourceFile:207)
03-31 17:41:19.901  3448  3504 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
03-31 17:41:19.901  3448  3504 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
03-31 17:41:19.901  3448  3504 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
03-31 17:41:19.901  3448  3504 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
03-31 17:41:19.901  3448  3504 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
03-31 17:41:19.901  3448  3504 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
03-31 17:41:19.901  3448  3504 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
03-31 17:41:19.901  3448  3504 E KeepSync: 	... 10 more
03-31 17:41:19.901  3448  3504 W KeepSync: Sync result 2
,03-31 17:41:19.909   823  1370 I ActivityManager: Killing 3031:com.android.musicfx/u0a18 (adj 15): empty #17
,03-31 17:41:19.910   823   856 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 39152, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-31 17:41:20.048  3515  3515 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,03-31 17:41:20.056  3515  3515 I BooksApp: Created application version: 3.6.8 (30608)
,03-31 17:41:20.171  3515  3588 I BooksSync: Starting books sync for 61035162, extras: ade
,03-31 17:41:20.265  3515  3600 I BooksConfig: GmsCore Version = 7.8.99 (2134222-430)
03-31 17:41:20.266   823  1410 I ActivityManager: Start proc 3598:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,03-31 17:41:20.266   823  1410 I ActivityManager: Killing 3059:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,03-31 17:41:20.543  1233  2543 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-31 17:41:20.543  1233  2543 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 17:41:20.543  1233  2543 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 17:41:20.543  1233  2543 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 17:41:20.549  1233  2543 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 17:41:20.622  1233  1713 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,03-31 17:41:20.622  1233  1713 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-31 17:41:20.622  1233  1713 I GLSUser : [GLSUser] Extracting token using key: Auth,
03-31 17:41:20.622  1233  1713 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
03-31 17:41:20.625  1233  1713 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,03-31 17:41:20.639  3515  3600 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,03-31 17:41:20.640  3515  3588 E BooksSync: Soft error
03-31 17:41:20.640  3515  3588 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-31 17:41:20.640  3515  3588 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-31 17:41:20.640  3515  3588 E BooksSync: Sync error
03-31 17:41:20.640  3515  3588 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-31 17:41:20.640  3515  3588 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,03-31 17:41:20.641  3515  3588 I BooksSync: Finished books sync
,03-31 17:41:20.649   823  1410 I ActivityManager: Killing 2991:android.process.acore/u0a5 (adj 15): empty #17
,03-31 17:41:20.652   823   856 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 39153, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-31 17:41:20.754   823  1410 I ActivityManager: Killing 2773:com.google.android.gms:car/u0a11 (adj 15): empty #18
,03-31 17:41:21.324   823  1393 I ActivityManager: Killing 2798:com.google.android.gm/u0a78 (adj 15): empty #17
,03-31 17:41:21.484  3270  3328 I jxcore-log: TAP version 13
03-31 17:41:21.484  3270  3328 I jxcore-log: 
,03-31 17:41:21.487  3270  3328 I jxcore-log: # setup
03-31 17:41:21.487  3270  3328 I jxcore-log: 
,03-31 17:41:21.615   823  1093 I ActivityManager: Start proc 3625:com.qualcomm.timeservice/1000 for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver
,03-31 17:41:21.681  3625  3625 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1459438881681
,03-31 17:41:21.681  3625  3625 D         : TimeServiceNative: User Time to be set is 1459438881681
,03-31 17:41:21.681  3625  3625 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
03-31 17:41:21.681  3625  3625 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
,03-31 17:41:21.681  3625  3625 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1459438881681
03-31 17:41:21.681   374   881 D QC-time-services: Daemon: Connection accepted:time_genoff
03-31 17:41:21.681  3625  3625 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!,
03-31 17:41:21.681   374  3642 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1459438881681
03-31 17:41:21.681   374  3642 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1459438881681, operation = 0
,03-31 17:41:21.682   374  3642 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS7/17/70 11:53:0
03-31 17:41:21.682   374  3642 D QC-time-services: Daemon:Value read from RTC seconds = 19741980000
,03-31 17:41:21.682   374  3642 D QC-time-services: Daemon:new time 1459438881681 
03-31 17:41:21.682   374  3642 D QC-time-services: Daemon: delta 1439696901681 genoff 1439696901681 
,03-31 17:41:21.682   374  3642 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1439696901681 to memory
03-31 17:41:21.682   374  3642 D QC-time-services: Daemon:Opening File: /data/time/ats_2
,03-31 17:41:21.682   374  3642 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
03-31 17:41:21.684   374  3642 D QC-time-services: Updating the TOD offset,
03-31 17:41:21.684   374  3642 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1439696901681 to memory
03-31 17:41:21.684   374  3642 D QC-time-services: Daemon:Opening File: /data/time/ats_1
,03-31 17:41:21.684   374  3642 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
03-31 17:41:21.687   374  3642 E QC-time-services: Daemon:Update to modem bit set
03-31 17:41:21.688   374  3642 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
03-31 17:41:21.688   374  3642 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1143474081681
,03-31 17:41:21.689  3625  3625 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,03-31 17:41:21.711  3270  3328 I jxcore-log: # 1. calling createNativeListener directly rejects
03-31 17:41:21.711  3270  3328 I jxcore-log: 
,03-31 17:41:21.762   374   881 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,03-31 17:41:21.767   374   879 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40,
,03-31 17:41:21.808   823  1370 I ActivityManager: Start proc 3644:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver
,03-31 17:41:21.825   823   841 I ActivityManager: Killing 1877:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,03-31 17:41:21.854  3270  3328 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 17:41:21.854  3270  3328 I jxcore-log: 
03-31 17:41:21.859  3270  3328 I jxcore-log: DEBUG createNativeListener: listening 57017
03-31 17:41:21.859  3270  3328 I jxcore-log: 
,03-31 17:41:21.866  3270  3328 I jxcore-log: ok 1 Should throw
03-31 17:41:21.866  3270  3328 I jxcore-log: 
03-31 17:41:21.868  3270  3328 I jxcore-log: # teardown
03-31 17:41:21.868  3270  3328 I jxcore-log: 
,03-31 17:41:22.008  3644  3644 I GAv4    : Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
03-31 17:41:22.008  3644  3644 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-31 17:41:22.008  3644  3644 I GAv4    :   adb logcat -s GAv4
,03-31 17:41:22.026  3644  3644 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,03-31 17:41:22.063  3644  3644 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,03-31 17:41:22.089  3644  3663 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,03-31 17:41:22.090  3270  3328 I jxcore-log: # setup
03-31 17:41:22.090  3270  3328 I jxcore-log: 
,03-31 17:41:22.118   823  1411 I ActivityManager: Killing 3135:com.android.providers.calendar/u0a3 (adj 15): empty #17
,03-31 17:41:22.202  3270  3328 I jxcore-log: # 2. emits incomingConnectionState
03-31 17:41:22.202  3270  3328 I jxcore-log: 
,03-31 17:41:22.351  3270  3328 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 17:41:22.351  3270  3328 I jxcore-log: 
,03-31 17:41:22.367  3270  3328 I jxcore-log: DEBUG createNativeListener: listening 32926
03-31 17:41:22.367  3270  3328 I jxcore-log: 
,03-31 17:41:22.395  3270  3328 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 17:41:22.395  3270  3328 I jxcore-log: 
,03-31 17:41:22.402  3270  3328 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 17:41:22.402  3270  3328 I jxcore-log: 
,03-31 17:41:22.413  3270  3328 I jxcore-log: DEBUG createNativeListener: new mux
03-31 17:41:22.413  3270  3328 I jxcore-log: 
,03-31 17:41:22.419  3270  3328 I jxcore-log: ok 2 initial connection state should be CONNECTED
03-31 17:41:22.419  3270  3328 I jxcore-log: 
,03-31 17:41:22.432  1766  1766 V Herrevad: NQAS connected
,03-31 17:41:22.438  3163  3163 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-31 17:41:22.438  3163  3163 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-31 17:41:22.441   823  1022 D WifiService: New client listening to asynchronous messages
,03-31 17:41:22.447  3270  3328 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 17:41:22.447  3270  3328 I jxcore-log: 
03-31 17:41:22.448  3270  3328 I jxcore-log: ok 3 final connection state should be DISCONNECTED
03-31 17:41:22.448  3270  3328 I jxcore-log: 
,03-31 17:41:22.456  3270  3328 I jxcore-log: # teardown
03-31 17:41:22.456  3270  3328 I jxcore-log: 
,03-31 17:41:22.484  1766  3666 I art     : Explicit concurrent mark sweep GC freed 14690(1088KB) AllocSpace objects, 13(208KB) LOS objects, 35% free, 28MB/44MB, paused 853us total 37.971ms
,03-31 17:41:22.493   823  1150 I ActivityManager: Start proc 3674:com.android.providers.calendar/u0a3 for content provider com.android.providers.calendar/.CalendarProvider2
,03-31 17:41:22.512  3674  3674 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,03-31 17:41:22.556  3674  3674 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@14139144(com.android.providers.calendar.CalendarProvider2@212fc22d)
,03-31 17:41:22.586  3270  3328 I jxcore-log: # setup
03-31 17:41:22.586  3270  3328 I jxcore-log: 
,03-31 17:41:22.612  1233  1640 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
,03-31 17:41:22.613  1233  1640 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 17:41:22.613  1233  1640 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 17:41:22.613  1233  1640 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 17:41:22.616  1233  1640 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 17:41:22.626  3163  3670 E Babel   : UserRecoverableAuthException.
,03-31 17:41:22.626  3163  3670 E Babel   : eei: BadAuthentication
03-31 17:41:22.626  3163  3670 E Babel   : 	at eeg.a(Unknown Source)
03-31 17:41:22.626  3163  3670 E Babel   : 	at eeg.a(Unknown Source)
03-31 17:41:22.626  3163  3670 E Babel   : 	at eeg.a(Unknown Source)
03-31 17:41:22.626  3163  3670 E Babel   : 	at g.a(Unknown Source),
03-31 17:41:22.626  3163  3670 E Babel   : 	at cae.a(SourceFile:3089)
03-31 17:41:22.626  3163  3670 E Babel   : 	at cae.a(SourceFile:1131)
03-31 17:41:22.626  3163  3670 E Babel   : 	at cws.a(SourceFile:4333)
03-31 17:41:22.626  3163  3670 E Babel   : 	at cws.a(SourceFile:1419)
03-31 17:41:22.626  3163  3670 E Babel   : 	at crl.a(SourceFile:492)
03-31 17:41:22.626  3163  3670 E Babel   : 	at crl.a(SourceFile:1468),
03-31 17:41:22.626  3163  3670 E Babel   : 	at cqu.a(SourceFile:4416)
03-31 17:41:22.626  3163  3670 E Babel   : 	at cas.b(SourceFile:106)
03-31 17:41:22.626  3163  3670 E Babel   : 	at cap.d(SourceFile:335)
03-31 17:41:22.626  3163  3670 E Babel   : 	at caq.run(SourceFile:81)
03-31 17:41:22.627  3163  3670 E Babel   : Error getting auth token
03-31 17:41:22.627  3163  3670 E Babel   : dvm
03-31 17:41:22.627  3163  3670 E Babel   : 	at g.a(Unknown Source)
03-31 17:41:22.627  3163  3670 E Babel   : 	at cae.a(SourceFile:3089)
03-31 17:41:22.627  3163  3670 E Babel   : 	at cae.a(SourceFile:1131)
03-31 17:41:22.627  3163  3670 E Babel   : 	at cws.a(SourceFile:4333)
03-31 17:41:22.627  3163  3670 E Babel   : 	at cws.a(SourceFile:1419)
03-31 17:41:22.627  3163  3670 E Babel   : 	at crl.a(SourceFile:492)
03-31 17:41:22.627  3163  3670 E Babel   : 	at crl.a(SourceFile:1468)
03-31 17:41:22.627  3163  3670 E Babel   : 	at cqu.a(SourceFile:4416)
03-31 17:41:22.627  3163  3670 E Babel   : 	at cas.b(SourceFile:106)
03-31 17:41:22.627  3163  3670 E Babel   : ,	at cap.d(SourceFile:335)
03-31 17:41:22.627  3163  3670 E Babel   : 	at caq.run(SourceFile:81)
,03-31 17:41:22.630  3163  3670 E Babel   : Account registration failed 1-Redacted-21
,03-31 17:41:22.632  3163  3670 E Babel   : cyp: null -- null
03-31 17:41:22.632  3163  3670 E Babel   : 	at cae.a(SourceFile:3121)
03-31 17:41:22.632  3163  3670 E Babel   : 	at cae.a(SourceFile:1131)
03-31 17:41:22.632  3163  3670 E Babel   : 	at cws.a(SourceFile:4333)
03-31 17:41:22.632  3163  3670 E Babel   : 	at cws.a(SourceFile:1419)
03-31 17:41:22.632  3163  3670 E Babel   : 	at crl.a(SourceFile:492)
03-31 17:41:22.632  3163  3670 E Babel   : 	at crl.a(SourceFile:1468)
03-31 17:41:22.632  3163  3670 E Babel   : 	at cqu.a(SourceFile:4416)
03-31 17:41:22.632  3163  3670 E Babel   : 	at cas.b(SourceFile:106)
03-31 17:41:22.632  3163  3670 E Babel   : 	at cap.d(SourceFile:335)
03-31 17:41:22.632  3163  3670 E Babel   : 	at caq.run(SourceFile:81)
,03-31 17:41:22.647  3163  3670 I art     : Note: end time exceeds epoch: 
,03-31 17:41:22.660   823  1093 I art     : Explicit concurrent mark sweep GC freed 18281(811KB) AllocSpace objects, 2(32KB) LOS objects, 32% free, 33MB/49MB, paused 1.511ms total 53.581ms
,03-31 17:41:22.663  1233  1713 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
,03-31 17:41:22.663  1233  1713 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 17:41:22.664  1233  1713 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 17:41:22.664  1233  1713 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 17:41:22.666  1233  1713 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 17:41:22.676  1233  1713 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-31 17:41:22.696  3270  3328 I jxcore-log: # 3. emits routerPortConnectionFailed
03-31 17:41:22.696  3270  3328 I jxcore-log: 
,03-31 17:41:22.697  3163  3696 E Babel   : Unexpected exception while authenticating.
03-31 17:41:22.698  3163  3696 E Babel   : eej: User intervention required. Notification has been pushed.
03-31 17:41:22.698  3163  3696 E Babel   : 	at eeg.b(Unknown Source)
03-31 17:41:22.698  3163  3696 E Babel   : 	at eeg.b(Unknown Source)
03-31 17:41:22.698  3163  3696 E Babel   : 	at g.a(Unknown Source)
03-31 17:41:22.698  3163  3696 E Babel   : 	at cae.b(SourceFile:1146)
03-31 17:41:22.698  3163  3696 E Babel   : 	at dcg.run(SourceFile:5617)
03-31 17:41:22.698  3163  3696 E Babel   : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 17:41:22.698  3163  3696 E Babel   : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 17:41:22.698  3163  3696 E Babel   : 	at java.lang.Thread.run(Thread.java:818)
,03-31 17:41:22.845  3270  3328 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 17:41:22.845  3270  3328 I jxcore-log: 
,03-31 17:41:22.847  3270  3328 I jxcore-log: DEBUG createNativeListener: listening 34228
03-31 17:41:22.847  3270  3328 I jxcore-log: 
,03-31 17:41:22.853  3270  3328 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 17:41:22.853  3270  3328 I jxcore-log: 
,03-31 17:41:22.854  3270  3328 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 17:41:22.854  3270  3328 I jxcore-log: 
,03-31 17:41:22.856  3270  3328 I jxcore-log: DEBUG createNativeListener: new mux
03-31 17:41:22.856  3270  3328 I jxcore-log: 
,03-31 17:41:22.879  3270  3328 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 17:41:22.879  3270  3328 I jxcore-log: 
,03-31 17:41:22.882  3270  3328 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 17:41:22.882  3270  3328 I jxcore-log: 
,03-31 17:41:22.886  3270  3328 I jxcore-log: DEBUG createNativeListener: 
03-31 17:41:22.886  3270  3328 I jxcore-log: 
,03-31 17:41:22.887  3270  3328 I jxcore-log: ok 4 tried to connect to right port
03-31 17:41:22.887  3270  3328 I jxcore-log: 
03-31 17:41:22.888  3270  3328 I jxcore-log: ok 5 failed due to refused connection
03-31 17:41:22.888  3270  3328 I jxcore-log: 
,03-31 17:41:22.888  3270  3328 I jxcore-log: ok 6 routerPortConnectionFailed is emitted
03-31 17:41:22.888  3270  3328 I jxcore-log: 
,03-31 17:41:22.892  3270  3328 I jxcore-log: # teardown
03-31 17:41:22.892  3270  3328 I jxcore-log: 
,03-31 17:41:22.894  3270  3328 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 17:41:22.894  3270  3328 I jxcore-log: 
,03-31 17:41:23.049  3270  3328 I jxcore-log: DEBUG createNativeListener: mux close
03-31 17:41:23.049  3270  3328 I jxcore-log: 
,03-31 17:41:23.054  3270  3328 I jxcore-log: # setup
03-31 17:41:23.054  3270  3328 I jxcore-log: 
,03-31 17:41:23.055  3270  3328 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 17:41:23.055  3270  3328 I jxcore-log: 
,03-31 17:41:23.182  3270  3328 I jxcore-log: # 4. native server connections all up
03-31 17:41:23.182  3270  3328 I jxcore-log: 
,03-31 17:41:23.415  3270  3328 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 17:41:23.415  3270  3328 I jxcore-log: 
,03-31 17:41:23.424  3270  3328 I jxcore-log: DEBUG createNativeListener: listening 52684
03-31 17:41:23.424  3270  3328 I jxcore-log: 
,03-31 17:41:23.431  3270  3328 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 17:41:23.431  3270  3328 I jxcore-log: 
,03-31 17:41:23.432  3270  3328 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 17:41:23.432  3270  3328 I jxcore-log: 
,03-31 17:41:23.434  3270  3328 I jxcore-log: DEBUG createNativeListener: new mux
03-31 17:41:23.434  3270  3328 I jxcore-log: 
,03-31 17:41:23.472  3270  3328 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 17:41:23.472  3270  3328 I jxcore-log: 
,03-31 17:41:23.478  3270  3328 I jxcore-log: DEBUG createNativeListener: new outgoing socket
,03-31 17:41:23.478  3270  3328 I jxcore-log: 
,03-31 17:41:23.488  3270  3328 I jxcore-log: DEBUG createNativeListener: new stream: 
,03-31 17:41:23.488  3270  3328 I jxcore-log: 
,03-31 17:41:23.495  3270  3328 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 17:41:23.495  3270  3328 I jxcore-log: 
,03-31 17:41:23.530  1233  1233 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 17:41:23.541  3270  3328 I jxcore-log: ok 7 Send/recvd #1 should be equal length
03-31 17:41:23.541  3270  3328 I jxcore-log: 
03-31 17:41:23.541  3270  3328 I jxcore-log: ok 8 Send/recvd #1 should be same
03-31 17:41:23.541  3270  3328 I jxcore-log: 
,03-31 17:41:23.544  3270  3328 I jxcore-log: ok 9 Send/recvd #2 should be equal length
03-31 17:41:23.544  3270  3328 I jxcore-log: 
,03-31 17:41:23.544  3270  3328 I jxcore-log: ok 10 Send/recvd #2 should be same
03-31 17:41:23.544  3270  3328 I jxcore-log: 
,03-31 17:41:23.547  3270  3328 I jxcore-log: ok 11 Should be exactly 2 client sockets
,03-31 17:41:23.547  3270  3328 I jxcore-log: 
,03-31 17:41:23.559  3270  3328 I jxcore-log: # teardown
03-31 17:41:23.559  3270  3328 I jxcore-log: 
,03-31 17:41:23.596  3674  3674 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
03-31 17:41:23.596  3674  3674 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,03-31 17:41:23.665  3270  3328 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 17:41:23.665  3270  3328 I jxcore-log: 
,03-31 17:41:23.668  3270  3328 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 17:41:23.668  3270  3328 I jxcore-log: 
,03-31 17:41:23.672  3270  3328 I jxcore-log: DEBUG createNativeListener: mux close
03-31 17:41:23.672  3270  3328 I jxcore-log: 
03-31 17:41:23.674  1233  3703 I VacuumService: Vacuum at: now=1459438883673 tag=VacuumService
03-31 17:41:23.675  3270  3328 I jxcore-log: # setup
03-31 17:41:23.675  3270  3328 I jxcore-log: 
03-31 17:41:23.676  3270  3328 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 17:41:23.676  3270  3328 I jxcore-log: 
,03-31 17:41:23.691  3383  3700 V GoogleAuthProtoRequest: [340] a.<init>: mAccountName set to: thalitester@gmail.com
,03-31 17:41:23.813  3270  3328 I jxcore-log: # 5. native server - closing incoming stream cleans outgoing socket
03-31 17:41:23.813  3270  3328 I jxcore-log: 
,03-31 17:41:23.848  3674  3704 E SQLiteLog: (284) automatic index on view_events(_id)
,03-31 17:41:23.867  1233  3705 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,03-31 17:41:23.874  1233  3087 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,03-31 17:41:23.874  1233  3087 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 17:41:23.874  1233  3087 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-31 17:41:23.874  1233  3087 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 17:41:23.879  1233  3087 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 17:41:23.900  3383  3700 W ExperimentUpdateService: [340] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,03-31 17:41:23.902  3383  3700 W ExperimentUpdateService: [340] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-31 17:41:23.902  3383  3700 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-31 17:41:23.902  3383  3700 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
,03-31 17:41:23.902  3383  3700 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-31 17:41:23.902  3383  3700 W ExperimentUpdateService: 	,at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-31 17:41:23.902  3383  3700 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-31 17:41:23.902  3383  3700 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
,03-31 17:41:23.902  3383  3700 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-31 17:41:23.902  3383  3700 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-31 17:41:23.902  3383  3700 W ExperimentUpdateService: 	,at com.a.a.a.a.a(SourceFile:93)
,03-31 17:41:23.902  3383  3700 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-31 17:41:23.914  1233  3705 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog,
03-31 17:41:23.914  1233  3705 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 17:41:23.914  1233  3705 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-31 17:41:23.914  1233  3705 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 17:41:23.919  1233  3705 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 17:41:23.955  1233  3705 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-31 17:41:23.955  1233  3705 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-31 17:41:23.955  1233  3705 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-31 17:41:23.955  1233  3705 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-31 17:41:23.955  1233  3705 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-31 17:41:23.955  1233  3705 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-31 17:41:23.955  1233  3705 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-31 17:41:23.955  1233  3705 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-31 17:41:23.955  1233  3705 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-31 17:41:23.955  1233  3705 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-31 17:41:23.955  1233  3705 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-31 17:41:23.955  1233  3705 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-31 17:41:23.955  1233  3705 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-31 17:41:23.969  3270  3328 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 17:41:23.969  3270  3328 I jxcore-log: 
,03-31 17:41:23.972  3270  3328 I jxcore-log: DEBUG createNativeListener: listening 44359
03-31 17:41:23.972  3270  3328 I jxcore-log: 
,03-31 17:41:23.978  3270  3328 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 17:41:23.978  3270  3328 I jxcore-log: 
,03-31 17:41:23.979  3270  3328 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 17:41:23.979  3270  3328 I jxcore-log: 
,03-31 17:41:23.981  3270  3328 I jxcore-log: DEBUG createNativeListener: new mux
03-31 17:41:23.981  3270  3328 I jxcore-log: 
,03-31 17:41:23.994  3270  3328 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 17:41:23.994  3270  3328 I jxcore-log: 
,03-31 17:41:23.998  3270  3328 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 17:41:23.998  3270  3328 I jxcore-log: 
,03-31 17:41:24.011  3270  3328 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 17:41:24.011  3270  3328 I jxcore-log: 
,03-31 17:41:24.023  3270  3328 I jxcore-log: ok 12 socket shouldn't close until after stream
03-31 17:41:24.023  3270  3328 I jxcore-log: 
,03-31 17:41:24.023  3270  3328 I jxcore-log: ok 13 incoming remains open
03-31 17:41:24.023  3270  3328 I jxcore-log: 
,03-31 17:41:24.029  3270  3328 I jxcore-log: # teardown
03-31 17:41:24.029  3270  3328 I jxcore-log: 
,03-31 17:41:24.155  3270  3328 I jxcore-log: DEBUG createNativeListener: mux close
03-31 17:41:24.155  3270  3328 I jxcore-log: 
,03-31 17:41:24.163  3270  3328 I jxcore-log: # setup
03-31 17:41:24.163  3270  3328 I jxcore-log: 
,03-31 17:41:24.165  3270  3328 I jxcore-log: DEBUG createNativeListener: incoming socket close
,03-31 17:41:24.165  3270  3328 I jxcore-log: 
,03-31 17:41:24.266  3270  3328 I jxcore-log: # 6. native server - closing incoming connection cleans outgoing socket
03-31 17:41:24.266  3270  3328 I jxcore-log: 
,03-31 17:41:24.444  3270  3328 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 17:41:24.444  3270  3328 I jxcore-log: 
,03-31 17:41:24.447  3270  3328 I jxcore-log: DEBUG createNativeListener: listening 49040
03-31 17:41:24.447  3270  3328 I jxcore-log: 
,03-31 17:41:24.452  3270  3328 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 17:41:24.452  3270  3328 I jxcore-log: 
,03-31 17:41:24.453  3270  3328 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 17:41:24.453  3270  3328 I jxcore-log: 
,03-31 17:41:24.454  3270  3328 I jxcore-log: DEBUG createNativeListener: new mux
03-31 17:41:24.454  3270  3328 I jxcore-log: 
,03-31 17:41:24.462  3270  3328 I jxcore-log: ok 14 we should not have gotten an error
03-31 17:41:24.462  3270  3328 I jxcore-log: 
03-31 17:41:24.466  3270  3328 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 17:41:24.466  3270  3328 I jxcore-log: 
03-31 17:41:24.468  3270  3328 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 17:41:24.468  3270  3328 I jxcore-log: 
,03-31 17:41:24.476  3270  3328 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 17:41:24.476  3270  3328 I jxcore-log: 
,03-31 17:41:24.478  3270  3328 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 17:41:24.478  3270  3328 I jxcore-log: 
,03-31 17:41:24.485  3270  3328 I jxcore-log: ok 15 socket shouldn't close until after incoming
03-31 17:41:24.485  3270  3328 I jxcore-log: 
03-31 17:41:24.486  3270  3328 I jxcore-log: ok 16 incoming is cleaned up
03-31 17:41:24.486  3270  3328 I jxcore-log: 
,03-31 17:41:24.490  3270  3328 I jxcore-log: # teardown
03-31 17:41:24.490  3270  3328 I jxcore-log: 
,03-31 17:41:24.526  1233  3705 W Uploader: No account for auth token provided
,03-31 17:41:24.631  1233  3705 W Uploader: No account for auth token provided
,03-31 17:41:24.657  3270  3328 I jxcore-log: # setup
03-31 17:41:24.657  3270  3328 I jxcore-log: 
,03-31 17:41:24.752  1233  3705 W Uploader: No account for auth token provided
,03-31 17:41:24.805  3270  3328 I jxcore-log: # 7. native server - closing outgoing socket cleans associated mux stream
03-31 17:41:24.805  3270  3328 I jxcore-log: ,
,03-31 17:41:24.903  3270  3328 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 17:41:24.903  3270  3328 I jxcore-log: 
03-31 17:41:24.906  3270  3328 I jxcore-log: DEBUG createNativeListener: listening 37155
03-31 17:41:24.906  3270  3328 I jxcore-log: 
,03-31 17:41:24.911  3270  3328 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 17:41:24.911  3270  3328 I jxcore-log: 
,03-31 17:41:24.913  3270  3328 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 17:41:24.913  3270  3328 I jxcore-log: 
,03-31 17:41:24.916  3270  3328 I jxcore-log: DEBUG createNativeListener: new mux
03-31 17:41:24.916  3270  3328 I jxcore-log: 
,03-31 17:41:24.928  3270  3328 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 17:41:24.928  3270  3328 I jxcore-log: 
,03-31 17:41:24.930  3270  3328 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 17:41:24.930  3270  3328 I jxcore-log: 
,03-31 17:41:24.945  3270  3328 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 17:41:24.945  3270  3328 I jxcore-log: 
,03-31 17:41:24.949  1233  3705 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
03-31 17:41:24.950  1233  3705 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 17:41:24.950  1233  3705 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 17:41:24.950  1233  3705 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 17:41:24.955  3270  3328 I jxcore-log: ok 17 stream was closed
03-31 17:41:24.955  3270  3328 I jxcore-log: 
,03-31 17:41:24.956  3270  3328 I jxcore-log: ok 18 incoming should survive,
03-31 17:41:24.956  3270  3328 I jxcore-log: 
03-31 17:41:24.956  3270  3328 I jxcore-log: ok 19 mux should have no streams
03-31 17:41:24.956  3270  3328 I jxcore-log: 
03-31 17:41:24.959  1233  3705 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 17:41:24.963  3270  3328 I jxcore-log: # teardown,
03-31 17:41:24.963  3270  3328 I jxcore-log: 
,03-31 17:41:25.012  1233  3705 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.,
03-31 17:41:25.012  1233  3705 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-31 17:41:25.012  1233  3705 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-31 17:41:25.012  1233  3705 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-31 17:41:25.012  1233  3705 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-31 17:41:25.012  1233  3705 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-31 17:41:25.012  1233  3705 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508),
03-31 17:41:25.012  1233  3705 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-31 17:41:25.012  1233  3705 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-31 17:41:25.012  1233  3705 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-31 17:41:25.012  1233  3705 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-31 17:41:25.012  1233  3705 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-31 17:41:25.012  1233  3705 E Uploader: 	,at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-31 17:41:25.052  3270  3328 I jxcore-log: DEBUG createNativeListener: mux close
03-31 17:41:25.052  3270  3328 I jxcore-log: 
,03-31 17:41:25.056  3515  3586 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,03-31 17:41:25.063  3270  3328 I jxcore-log: # setup
,03-31 17:41:25.063  3270  3328 I jxcore-log: 
,03-31 17:41:25.064  3270  3328 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 17:41:25.064  3270  3328 I jxcore-log: 
,03-31 17:41:25.148  1233  3705 W Uploader: No account for auth token provided
,03-31 17:41:25.232  3270  3328 I jxcore-log: # 8. native server - closing the whole server cleans everything up
,03-31 17:41:25.232  3270  3328 I jxcore-log: 
,03-31 17:41:25.268  1233  3705 W Uploader: No account for auth token provided
,03-31 17:41:25.342  3270  3328 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 17:41:25.342  3270  3328 I jxcore-log: 
03-31 17:41:25.349  3270  3328 I jxcore-log: DEBUG createNativeListener: listening 40398
03-31 17:41:25.349  3270  3328 I jxcore-log: 
,03-31 17:41:25.358  3270  3328 I jxcore-log: DEBUG createNativeListener: new incoming socket,
03-31 17:41:25.358  3270  3328 I jxcore-log: 
03-31 17:41:25.359  3270  3328 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 17:41:25.359  3270  3328 I jxcore-log: 
,03-31 17:41:25.361  3270  3328 I jxcore-log: DEBUG createNativeListener: new mux
,03-31 17:41:25.361  3270  3328 I jxcore-log: 
,03-31 17:41:25.373  3270  3328 I jxcore-log: ok 20 we should not have gotten an error
03-31 17:41:25.373  3270  3328 I jxcore-log: 
,03-31 17:41:25.379  3270  3328 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 17:41:25.379  3270  3328 I jxcore-log: 
,03-31 17:41:25.383  3270  3328 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 17:41:25.383  3270  3328 I jxcore-log: 
,03-31 17:41:25.388  1233  3705 W Uploader: No account for auth token provided
,03-31 17:41:25.392  3270  3328 I jxcore-log: ok 21 Buffers are identical
03-31 17:41:25.392  3270  3328 I jxcore-log: 
,03-31 17:41:25.394  3270  3328 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 17:41:25.394  3270  3328 I jxcore-log: 
,03-31 17:41:25.398  3270  3328 I jxcore-log: DEBUG createNativeListener: mux close
03-31 17:41:25.398  3270  3328 I jxcore-log: 
,03-31 17:41:25.401  3270  3328 I jxcore-log: ok 22 native server is nulled out
03-31 17:41:25.401  3270  3328 I jxcore-log: 
,03-31 17:41:25.402  3270  3328 I jxcore-log: ok 23 native server should be closed
03-31 17:41:25.402  3270  3328 I jxcore-log: 
,03-31 17:41:25.402  3270  3328 I jxcore-log: ok 24 incoming has been removed
03-31 17:41:25.402  3270  3328 I jxcore-log: 
03-31 17:41:25.402  3270  3328 I jxcore-log: ok 25 Incoming should be done
03-31 17:41:25.402  3270  3328 I jxcore-log: 
03-31 17:41:25.403  3270  3328 I jxcore-log: ok 26 The mux object should be closed
03-31 17:41:25.403  3270  3328 I jxcore-log: 
03-31 17:41:25.403  3270  3328 I jxcore-log: ok 27 The mux stream should be closed
03-31 17:41:25.403  3270  3328 I jxcore-log: 
03-31 17:41:25.404  3270  3328 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 17:41:25.404  3270  3328 I jxcore-log: 
,03-31 17:41:25.418  3270  3328 I jxcore-log: # teardown
03-31 17:41:25.418  3270  3328 I jxcore-log: 
,03-31 17:41:25.515  3270  3328 I jxcore-log: # setup
03-31 17:41:25.515  3270  3328 I jxcore-log: 
,03-31 17:41:25.527  1233  3705 W Uploader: No account for auth token provided
,03-31 17:41:25.669  1233  3705 W Uploader: No account for auth token provided
,03-31 17:41:25.727  3270  3328 I jxcore-log: # 9. native server - we can get a ton of connections and data through and still clean up the server completely
03-31 17:41:25.727  3270  3328 I jxcore-log: 
,03-31 17:41:25.779  1233  3705 W Uploader:  no longer exists, so no auth token.
,03-31 17:41:25.851  3270  3328 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 17:41:25.851  3270  3328 I jxcore-log: 
,03-31 17:41:25.855  3270  3328 I jxcore-log: DEBUG createNativeListener: listening 46792
03-31 17:41:25.855  3270  3328 I jxcore-log: 
,03-31 17:41:25.877  3270  3328 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 17:41:25.877  3270  3328 I jxcore-log: 
,03-31 17:41:25.878  3270  3328 I jxcore-log: DEBUG createNativeListener: creating incoming mux,
03-31 17:41:25.878  3270  3328 I jxcore-log: 
03-31 17:41:25.879  3270  3328 I jxcore-log: DEBUG createNativeListener: new mux
03-31 17:41:25.879  3270  3328 I jxcore-log: ,
,03-31 17:41:25.888  3270  3328 I jxcore-log: DEBUG createNativeListener: new incoming socket,
03-31 17:41:25.888  3270  3328 I jxcore-log: 
,03-31 17:41:25.889  3270  3328 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 17:41:25.889  3270  3328 I jxcore-log: 
,03-31 17:41:25.891  3270  3328 I jxcore-log: DEBUG createNativeListener: new mux
03-31 17:41:25.891  3270  3328 I jxcore-log: 
03-31 17:41:25.894  3270  3328 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 17:41:25.894  3270  3328 I jxcore-log: 
,03-31 17:41:25.894  3270  3328 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 17:41:25.894  3270  3328 I jxcore-log: 
03-31 17:41:25.895  3270  3328 I jxcore-log: DEBUG createNativeListener: new mux
03-31 17:41:25.895  3270  3328 I jxcore-log: 
03-31 17:41:25.898  3270  3328 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 17:41:25.898  3270  3328 I jxcore-log: 
,03-31 17:41:25.899  3270  3328 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 17:41:25.899  3270  3328 I jxcore-log: 
03-31 17:41:25.900  3270  3328 I jxcore-log: DEBUG createNativeListener: new mux
03-31 17:41:25.900  3270  3328 I jxcore-log: 
,03-31 17:41:25.903  3270  3328 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 17:41:25.903  3270  3328 I jxcore-log: 
,03-31 17:41:25.904  3270  3328 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 17:41:25.904  3270  3328 I jxcore-log: 
,03-31 17:41:25.905  3270  3328 I jxcore-log: DEBUG createNativeListener: new mux
03-31 17:41:25.905  3270  3328 I jxcore-log: 
,03-31 17:41:25.907  3270  3328 I jxcore-log: DEBUG createNativeListener: new incoming socket,
03-31 17:41:25.907  3270  3328 I jxcore-log: 
,03-31 17:41:25.908  3270  3328 I jxcore-log: DEBUG createNativeListener: creating incoming mux,
03-31 17:41:25.908  3270  3328 I jxcore-log: 
03-31 17:41:25.909  3270  3328 I jxcore-log: DEBUG createNativeListener: new mux
03-31 17:41:25.909  3270  3328 I jxcore-log: 
03-31 17:41:25.912  3270  3328 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 17:41:25.912  3270  3328 I jxcore-log: 
,03-31 17:41:25.912  3270  3328 I jxcore-log: DEBUG createNativeListener: creating incoming mux,
03-31 17:41:25.912  3270  3328 I jxcore-log: 
03-31 17:41:25.914  3270  3328 I jxcore-log: DEBUG createNativeListener: new mux
03-31 17:41:25.914  3270  3328 I jxcore-log: 
03-31 17:41:25.916  3270  3328 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 17:41:25.916  3270  3328 I jxcore-log: ,
03-31 17:41:25.916  3270  3328 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 17:41:25.916  3270  3328 I jxcore-log: 
03-31 17:41:25.917  3270  3328 I jxcore-log: DEBUG createNativeListener: new mux
03-31 17:41:25.917  3270  3328 I jxcore-log: 
,03-31 17:41:25.919  3270  3328 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 17:41:25.919  3270  3328 I jxcore-log: 
03-31 17:41:25.920  3270  3328 I jxcore-log: DEBUG createNativeListener: creating incoming mux
,03-31 17:41:25.920  3270  3328 I jxcore-log: 
03-31 17:41:25.921  3270  3328 I jxcore-log: DEBUG createNativeListener: new mux
03-31 17:41:25.921  3270  3328 I jxcore-log: 
,03-31 17:41:25.923  3270  3328 I jxcore-log: DEBUG createNativeListener: new incoming socket,
03-31 17:41:25.923  3270  3328 I jxcore-log: 
,03-31 17:41:25.923  3270  3328 I jxcore-log: DEBUG createNativeListener: creating incoming mux,
03-31 17:41:25.923  3270  3328 I jxcore-log: 
03-31 17:41:25.924  3270  3328 I jxcore-log: DEBUG createNativeListener: new mux,
03-31 17:41:25.924  3270  3328 I jxcore-log: 
,03-31 17:41:25.943  1233  3705 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog,
03-31 17:41:25.943  1233  3705 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-31 17:41:25.944  1233  3705 I GLSUser : [GLSUser] Extracting token using key: Auth,
03-31 17:41:25.944  1233  3705 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 17:41:25.951  1233  3705 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 17:41:26.010  3270  3328 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 17:41:26.010  3270  3328 I jxcore-log: 
,03-31 17:41:26.013  3270  3328 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 17:41:26.013  3270  3328 I jxcore-log: 
,03-31 17:41:26.015  3270  3328 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 17:41:26.015  3270  3328 I jxcore-log: 
,03-31 17:41:26.016  1233  3705 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.,
03-31 17:41:26.016  1233  3705 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-31 17:41:26.016  1233  3705 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-31 17:41:26.016  1233  3705 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-31 17:41:26.016  1233  3705 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-31 17:41:26.016  1233  3705 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-31 17:41:26.016  1233  3705 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-31 17:41:26.016  1233  3705 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-31 17:41:26.016  1233  3705 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-31 17:41:26.016  1233  3705 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-31 17:41:26.016  1233  3705 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-31 17:41:26.016  1233  3705 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-31 17:41:26.016  1233  3705 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
03-31 17:41:26.017  3270  3328 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 17:41:26.017  3270  3328 I jxcore-log: 
03-31 17:41:26.018  3270  3328 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 17:41:26.018  3270  3328 I jxcore-log: 
03-31 17:41:26.020  3270  3328 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 17:41:26.020  3270  3328 I jxcore-log: 
,03-31 17:41:26.023  3270  3328 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 17:41:26.023  3270  3328 I jxcore-log: 
,03-31 17:41:26.025  3270  3328 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 17:41:26.025  3270  3328 I jxcore-log: 
,03-31 17:41:26.027  3270  3328 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 17:41:26.027  3270  3328 I jxcore-log: 
,03-31 17:41:26.029  3270  3328 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 17:41:26.029  3270  3328 I jxcore-log: 
,03-31 17:41:26.030  3270  3328 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 17:41:26.030  3270  3328 I jxcore-log: 
,03-31 17:41:26.032  3270  3328 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 17:41:26.032  3270  3328 I jxcore-log: 
,03-31 17:41:26.034  3270  3328 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 17:41:26.034  3270  3328 I jxcore-log: 
,03-31 17:41:26.035  3270  3328 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 17:41:26.035  3270  3328 I jxcore-log: 
,03-31 17:41:26.036  3270  3328 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 17:41:26.036  3270  3328 I jxcore-log: 
,03-31 17:41:26.038  3270  3328 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 17:41:26.038  3270  3328 I jxcore-log: 
,03-31 17:41:26.040  3270  3328 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 17:41:26.040  3270  3328 I jxcore-log: 
,03-31 17:41:26.041  3270  3328 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 17:41:26.041  3270  3328 I jxcore-log: 
,03-31 17:41:26.043  3270  3328 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 17:41:26.043  3270  3328 I jxcore-log: 
,03-31 17:41:26.046  3270  3328 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 17:41:26.046  3270  3328 I jxcore-log: 
,03-31 17:41:26.047  3270  3328 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 17:41:26.047  3270  3328 I jxcore-log: 
,03-31 17:41:26.049  3270  3328 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 17:41:26.049  3270  3328 I jxcore-log: 
,03-31 17:41:26.050  3270  3328 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 17:41:26.050  3270  3328 I jxcore-log: 
,03-31 17:41:26.052  3270  3328 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 17:41:26.052  3270  3328 I jxcore-log: 
,03-31 17:41:26.054  3270  3328 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 17:41:26.054  3270  3328 I jxcore-log: 
,03-31 17:41:26.055  3270  3328 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 17:41:26.055  3270  3328 I jxcore-log: 
,03-31 17:41:26.056  3270  3328 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 17:41:26.056  3270  3328 I jxcore-log: 
,03-31 17:41:26.058  3270  3328 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 17:41:26.058  3270  3328 I jxcore-log: 
,03-31 17:41:26.059  3270  3328 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 17:41:26.059  3270  3328 I jxcore-log: 
,03-31 17:41:26.060  3270  3328 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 17:41:26.060  3270  3328 I jxcore-log: 
,03-31 17:41:26.062  3270  3328 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 17:41:26.062  3270  3328 I jxcore-log: 
,03-31 17:41:26.063  3270  3328 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 17:41:26.063  3270  3328 I jxcore-log: 
,03-31 17:41:26.065  3270  3328 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 17:41:26.065  3270  3328 I jxcore-log: 
,03-31 17:41:26.066  3270  3328 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 17:41:26.066  3270  3328 I jxcore-log: 
,03-31 17:41:26.067  3270  3328 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 17:41:26.067  3270  3328 I jxcore-log: 
,03-31 17:41:26.069  3270  3328 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 17:41:26.069  3270  3328 I jxcore-log: 
,03-31 17:41:26.070  3270  3328 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 17:41:26.070  3270  3328 I jxcore-log: 
,03-31 17:41:26.071  3270  3328 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 17:41:26.071  3270  3328 I jxcore-log: 
,03-31 17:41:26.072  3270  3328 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 17:41:26.072  3270  3328 I jxcore-log: 
,03-31 17:41:26.074  3270  3328 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 17:41:26.074  3270  3328 I jxcore-log: 
,03-31 17:41:26.075  3270  3328 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 17:41:26.075  3270  3328 I jxcore-log: 
,03-31 17:41:26.077  3270  3328 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 17:41:26.077  3270  3328 I jxcore-log: 
,03-31 17:41:26.078  3270  3328 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 17:41:26.078  3270  3328 I jxcore-log: 
,03-31 17:41:26.079  3270  3328 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 17:41:26.079  3270  3328 I jxcore-log: 
,03-31 17:41:26.081  3270  3328 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 17:41:26.081  3270  3328 I jxcore-log: 
,03-31 17:41:26.083  3270  3328 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 17:41:26.083  3270  3328 I jxcore-log: 
,03-31 17:41:26.084  3270  3328 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 17:41:26.084  3270  3328 I jxcore-log: 
,03-31 17:41:26.085  3270  3328 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 17:41:26.085  3270  3328 I jxcore-log: 
,03-31 17:41:26.093  3270  3328 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 17:41:26.093  3270  3328 I jxcore-log: 
,03-31 17:41:26.095  3270  3328 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 17:41:26.095  3270  3328 I jxcore-log: 
,03-31 17:41:26.096  3270  3328 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 17:41:26.096  3270  3328 I jxcore-log: 
,03-31 17:41:26.098  3270  3328 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 17:41:26.098  3270  3328 I jxcore-log: 
,03-31 17:41:26.099  3270  3328 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 17:41:26.099  3270  3328 I jxcore-log: 
,03-31 17:41:26.101  3270  3328 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 17:41:26.101  3270  3328 I jxcore-log: 
,03-31 17:41:26.102  3270  3328 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 17:41:26.102  3270  3328 I jxcore-log: 
,03-31 17:41:26.103  3270  3328 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 17:41:26.103  3270  3328 I jxcore-log: 
,03-31 17:41:26.106  3270  3328 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 17:41:26.106  3270  3328 I jxcore-log: 
,03-31 17:41:26.108  3270  3328 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 17:41:26.108  3270  3328 I jxcore-log: 
,03-31 17:41:26.110  3270  3328 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 17:41:26.110  3270  3328 I jxcore-log: 
,03-31 17:41:26.111  3270  3328 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 17:41:26.111  3270  3328 I jxcore-log: 
,03-31 17:41:26.113  3270  3328 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 17:41:26.113  3270  3328 I jxcore-log: 
,03-31 17:41:26.114  3270  3328 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 17:41:26.114  3270  3328 I jxcore-log: 
,03-31 17:41:26.115  3270  3328 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 17:41:26.115  3270  3328 I jxcore-log: 
,03-31 17:41:26.117  3270  3328 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 17:41:26.117  3270  3328 I jxcore-log: 
,03-31 17:41:26.119  3270  3328 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 17:41:26.119  3270  3328 I jxcore-log: 
,03-31 17:41:26.120  3270  3328 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 17:41:26.120  3270  3328 I jxcore-log: 
,03-31 17:41:26.122  3270  3328 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 17:41:26.122  3270  3328 I jxcore-log: 
,03-31 17:41:26.123  3270  3328 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 17:41:26.123  3270  3328 I jxcore-log: 
,03-31 17:41:26.124  3270  3328 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 17:41:26.124  3270  3328 I jxcore-log: 
,03-31 17:41:26.126  3270  3328 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 17:41:26.126  3270  3328 I jxcore-log: 
,03-31 17:41:26.127  3270  3328 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 17:41:26.127  3270  3328 I jxcore-log: 
,03-31 17:41:26.129  3270  3328 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 17:41:26.129  3270  3328 I jxcore-log: 
,03-31 17:41:26.131  3270  3328 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 17:41:26.131  3270  3328 I jxcore-log: 
,03-31 17:41:26.132  3270  3328 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 17:41:26.132  3270  3328 I jxcore-log: 
,03-31 17:41:26.134  3270  3328 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 17:41:26.134  3270  3328 I jxcore-log: 
,03-31 17:41:26.135  3270  3328 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 17:41:26.135  3270  3328 I jxcore-log: 
,03-31 17:41:26.136  3270  3328 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 17:41:26.136  3270  3328 I jxcore-log: 
,03-31 17:41:26.138  3270  3328 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 17:41:26.138  3270  3328 I jxcore-log: 
,03-31 17:41:26.139  3270  3328 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 17:41:26.139  3270  3328 I jxcore-log: 
,03-31 17:41:26.141  3270  3328 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 17:41:26.141  3270  3328 I jxcore-log: 
,03-31 17:41:26.218  3270  3328 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 17:41:26.218  3270  3328 I jxcore-log: 
,03-31 17:41:26.219  3270  3328 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 17:41:26.219  3270  3328 I jxcore-log: 
03-31 17:41:26.219  1233  3705 W Uploader: No account for auth token provided
,03-31 17:41:26.221  3270  3328 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 17:41:26.221  3270  3328 I jxcore-log: 
,03-31 17:41:26.224  3270  3328 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 17:41:26.224  3270  3328 I jxcore-log: 
,03-31 17:41:26.225  3270  3328 I jxcore-log: DEBUG createNativeListener: mux close
03-31 17:41:26.225  3270  3328 I jxcore-log: 
,03-31 17:41:26.227  3270  3328 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 17:41:26.227  3270  3328 I jxcore-log: 
,03-31 17:41:26.228  3270  3328 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 17:41:26.228  3270  3328 I jxcore-log: 
,03-31 17:41:26.229  3270  3328 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 17:41:26.229  3270  3328 I jxcore-log: 
,03-31 17:41:26.231  3270  3328 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 17:41:26.231  3270  3328 I jxcore-log: 
,03-31 17:41:26.232  3270  3328 I jxcore-log: DEBUG createNativeListener: mux close
03-31 17:41:26.232  3270  3328 I jxcore-log: 
,03-31 17:41:26.235  3270  3328 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 17:41:26.235  3270  3328 I jxcore-log: 
03-31 17:41:26.236  3270  3328 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 17:41:26.236  3270  3328 I jxcore-log: 
03-31 17:41:26.237  3270  3328 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 17:41:26.237  3270  3328 I jxcore-log: 
,03-31 17:41:26.238  3270  3328 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 17:41:26.238  3270  3328 I jxcore-log: 
03-31 17:41:26.239  3270  3328 I jxcore-log: DEBUG createNativeListener: mux close
03-31 17:41:26.239  3270  3328 I jxcore-log: 
03-31 17:41:26.240  3270  3328 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 17:41:26.240  3270  3328 I jxcore-log: 
03-31 17:41:26.241  3270  3328 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 17:41:26.241  3270  3328 I jxcore-log: 
,03-31 17:41:26.242  3270  3328 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 17:41:26.242  3270  3328 I jxcore-log: 
,03-31 17:41:26.244  3270  3328 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 17:41:26.244  3270  3328 I jxcore-log: 
,03-31 17:41:26.245  3270  3328 I jxcore-log: DEBUG createNativeListener: mux close
03-31 17:41:26.245  3270  3328 I jxcore-log: 
,03-31 17:41:26.246  3270  3328 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 17:41:26.246  3270  3328 I jxcore-log: 
,03-31 17:41:26.247  3270  3328 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 17:41:26.247  3270  3328 I jxcore-log: 
,03-31 17:41:26.248  3270  3328 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 17:41:26.248  3270  3328 I jxcore-log: 
,03-31 17:41:26.250  3270  3328 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 17:41:26.250  3270  3328 I jxcore-log: 
,03-31 17:41:26.251  3270  3328 I jxcore-log: DEBUG createNativeListener: mux close
03-31 17:41:26.251  3270  3328 I jxcore-log: 
03-31 17:41:26.252  3270  3328 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 17:41:26.252  3270  3328 I jxcore-log: 
,03-31 17:41:26.253  3270  3328 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 17:41:26.253  3270  3328 I jxcore-log: 
,03-31 17:41:26.254  3270  3328 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 17:41:26.254  3270  3328 I jxcore-log: 
03-31 17:41:26.254  3270  3328 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 17:41:26.254  3270  3328 I jxcore-log: 
,03-31 17:41:26.255  3270  3328 I jxcore-log: DEBUG createNativeListener: mux close
03-31 17:41:26.255  3270  3328 I jxcore-log: 
03-31 17:41:26.256  3270  3328 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 17:41:26.256  3270  3328 I jxcore-log: 
03-31 17:41:26.257  3270  3328 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 17:41:26.257  3270  3328 I jxcore-log: 
,03-31 17:41:26.258  3270  3328 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 17:41:26.258  3270  3328 I jxcore-log: 
03-31 17:41:26.258  3270  3328 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 17:41:26.258  3270  3328 I jxcore-log: 
,03-31 17:41:26.259  3270  3328 I jxcore-log: DEBUG createNativeListener: mux close
03-31 17:41:26.259  3270  3328 I jxcore-log: 
03-31 17:41:26.260  3270  3328 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 17:41:26.260  3270  3328 I jxcore-log: 
03-31 17:41:26.261  3270  3328 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 17:41:26.261  3270  3328 I jxcore-log: 
,03-31 17:41:26.262  3270  3328 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 17:41:26.262  3270  3328 I jxcore-log: 
03-31 17:41:26.262  3270  3328 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 17:41:26.262  3270  3328 I jxcore-log: 
03-31 17:41:26.263  3270  3328 I jxcore-log: DEBUG createNativeListener: mux close
03-31 17:41:26.263  3270  3328 I jxcore-log: 
,03-31 17:41:26.264  3270  3328 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 17:41:26.264  3270  3328 I jxcore-log: 
03-31 17:41:26.265  3270  3328 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 17:41:26.265  3270  3328 I jxcore-log: 
03-31 17:41:26.265  3270  3328 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 17:41:26.265  3270  3328 I jxcore-log: 
,03-31 17:41:26.266  3270  3328 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 17:41:26.266  3270  3328 I jxcore-log: 
03-31 17:41:26.267  3270  3328 I jxcore-log: DEBUG createNativeListener: mux close
03-31 17:41:26.267  3270  3328 I jxcore-log: 
03-31 17:41:26.268  3270  3328 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 17:41:26.268  3270  3328 I jxcore-log: 
,03-31 17:41:26.268  3270  3328 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 17:41:26.268  3270  3328 I jxcore-log: 
03-31 17:41:26.269  3270  3328 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 17:41:26.269  3270  3328 I jxcore-log: 
03-31 17:41:26.270  3270  3328 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 17:41:26.270  3270  3328 I jxcore-log: 
,03-31 17:41:26.271  3270  3328 I jxcore-log: DEBUG createNativeListener: mux close
03-31 17:41:26.271  3270  3328 I jxcore-log: 
03-31 17:41:26.273  3270  3328 I jxcore-log: ok 28 native server is nulled out
03-31 17:41:26.273  3270  3328 I jxcore-log: 
03-31 17:41:26.274  3270  3328 I jxcore-log: ok 29 native server should be closed
03-31 17:41:26.274  3270  3328 I jxcore-log: 
,03-31 17:41:26.274  3270  3328 I jxcore-log: ok 30 incoming has been removed
03-31 17:41:26.274  3270  3328 I jxcore-log: 
03-31 17:41:26.275  3270  3328 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 17:41:26.275  3270  3328 I jxcore-log: 
03-31 17:41:26.275  3270  3328 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 17:41:26.275  3270  3328 I jxcore-log: 
,03-31 17:41:26.276  3270  3328 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 17:41:26.276  3270  3328 I jxcore-log: 
03-31 17:41:26.276  3270  3328 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 17:41:26.276  3270  3328 I jxcore-log: 
03-31 17:41:26.277  3270  3328 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 17:41:26.277  3270  3328 I jxcore-log: 
,03-31 17:41:26.277  3270  3328 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 17:41:26.277  3270  3328 I jxcore-log: 
03-31 17:41:26.277  3270  3328 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 17:41:26.277  3270  3328 I jxcore-log: 
03-31 17:41:26.278  3270  3328 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 17:41:26.278  3270  3328 I jxcore-log: 
,03-31 17:41:26.278  3270  3328 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 17:41:26.278  3270  3328 I jxcore-log: 
03-31 17:41:26.278  3270  3328 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 17:41:26.278  3270  3328 I jxcore-log: 
,03-31 17:41:26.376  3270  3328 I jxcore-log: # teardown
03-31 17:41:26.376  3270  3328 I jxcore-log: 
,03-31 17:41:26.431  1233  3705 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
03-31 17:41:26.431  1233  3705 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 17:41:26.431  1233  3705 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-31 17:41:26.431  1233  3705 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 17:41:26.439  1233  3705 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 17:41:26.517  1233  1233 I art     : Explicit concurrent mark sweep GC freed 47387(2MB) AllocSpace objects, 2(75KB) LOS objects, 36% free, 27MB/43MB, paused 2.135ms total 68.934ms
,03-31 17:41:26.529  3270  3328 I jxcore-log: # setup
03-31 17:41:26.529  3270  3328 I jxcore-log: 
,03-31 17:41:26.587  1233  3705 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-31 17:41:26.587  1233  3705 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-31 17:41:26.587  1233  3705 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-31 17:41:26.587  1233  3705 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-31 17:41:26.587  1233  3705 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-31 17:41:26.587  1233  3705 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-31 17:41:26.587  1233  3705 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-31 17:41:26.587  1233  3705 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-31 17:41:26.587  1233  3705 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-31 17:41:26.587  1233  3705 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-31 17:41:26.587  1233  3705 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-31 17:41:26.587  1233  3705 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-31 17:41:26.587  1233  3705 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-31 17:41:26.723  3270  3328 I jxcore-log: # 10. native server - simulate mux failure, make sure everything is cleaned up
03-31 17:41:26.723  3270  3328 I jxcore-log: 
,03-31 17:41:26.777  1233  3705 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,03-31 17:41:26.778  1233  3705 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 17:41:26.778  1233  3705 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 17:41:26.778  1233  3705 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 17:41:26.791  1233  3705 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 17:41:26.868  1233  3705 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-31 17:41:26.868  1233  3705 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-31 17:41:26.868  1233  3705 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-31 17:41:26.868  1233  3705 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-31 17:41:26.868  1233  3705 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-31 17:41:26.868  1233  3705 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-31 17:41:26.868  1233  3705 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-31 17:41:26.868  1233  3705 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-31 17:41:26.868  1233  3705 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-31 17:41:26.868  1233  3705 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-31 17:41:26.868  1233  3705 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-31 17:41:26.868  1233  3705 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-31 17:41:26.868  1233  3705 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-31 17:41:26.881  3270  3328 I jxcore-log: DEBUG createNativeListener: creating native server,
03-31 17:41:26.881  3270  3328 I jxcore-log: 
,03-31 17:41:26.886  3270  3328 I jxcore-log: DEBUG createNativeListener: listening 33592
03-31 17:41:26.886  3270  3328 I jxcore-log: 
,03-31 17:41:26.894  3270  3328 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 17:41:26.894  3270  3328 I jxcore-log: 
,03-31 17:41:26.896  3270  3328 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 17:41:26.896  3270  3328 I jxcore-log: 
,03-31 17:41:26.897  3270  3328 I jxcore-log: DEBUG createNativeListener: new mux
03-31 17:41:26.897  3270  3328 I jxcore-log: 
,03-31 17:41:26.904  3270  3328 I jxcore-log: ok 31 we should not have gotten an error
03-31 17:41:26.904  3270  3328 I jxcore-log: 
,03-31 17:41:26.908  3270  3328 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 17:41:26.908  3270  3328 I jxcore-log: 
,03-31 17:41:26.911  3270  3328 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 17:41:26.911  3270  3328 I jxcore-log: 
,03-31 17:41:26.918  3270  3328 I jxcore-log: ok 32 Buffers are identical
03-31 17:41:26.918  3270  3328 I jxcore-log: 
,03-31 17:41:26.918  3270  3328 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 17:41:26.918  3270  3328 I jxcore-log: 
,03-31 17:41:26.920  3270  3328 I jxcore-log: DEBUG createNativeListener: mux close
03-31 17:41:26.920  3270  3328 I jxcore-log: 
,03-31 17:41:26.931  3270  3328 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 17:41:26.931  3270  3328 I jxcore-log: 
,03-31 17:41:26.932  3270  3328 I jxcore-log: ok 33 server should be fine
03-31 17:41:26.932  3270  3328 I jxcore-log: 
,03-31 17:41:26.933  3270  3328 I jxcore-log: ok 34 server should be open
03-31 17:41:26.933  3270  3328 I jxcore-log: 
03-31 17:41:26.933  3270  3328 I jxcore-log: ok 35 incoming has been removed
03-31 17:41:26.933  3270  3328 I jxcore-log: 
,03-31 17:41:26.934  3270  3328 I jxcore-log: ok 36 The mux object should be closed
03-31 17:41:26.934  3270  3328 I jxcore-log: 
03-31 17:41:26.934  3270  3328 I jxcore-log: ok 37 The mux stream should be closed
03-31 17:41:26.934  3270  3328 I jxcore-log: 
,03-31 17:41:26.942  3270  3328 I jxcore-log: # teardown
03-31 17:41:26.942  3270  3328 I jxcore-log: 
,03-31 17:41:26.977  1233  3705 W Uploader: No account for auth token provided
,03-31 17:41:27.016  3270  3328 I jxcore-log: # setup
03-31 17:41:27.016  3270  3328 I jxcore-log: 
,03-31 17:41:27.175  3270  3328 I jxcore-log: # 11. native server - timing out the incoming connection cleans everything up
03-31 17:41:27.175  3270  3328 I jxcore-log: 
,03-31 17:41:27.302  3270  3328 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 17:41:27.302  3270  3328 I jxcore-log: 
,03-31 17:41:27.306  3270  3328 I jxcore-log: DEBUG createNativeListener: listening 53435
03-31 17:41:27.306  3270  3328 I jxcore-log: 
,03-31 17:41:27.311  3270  3328 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 17:41:27.311  3270  3328 I jxcore-log: 
,03-31 17:41:27.313  3270  3328 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 17:41:27.313  3270  3328 I jxcore-log: 
03-31 17:41:27.314  3270  3328 I jxcore-log: DEBUG createNativeListener: new mux
03-31 17:41:27.314  3270  3328 I jxcore-log: 
,03-31 17:41:27.321  3270  3328 I jxcore-log: ok 38 we should not have gotten an error
03-31 17:41:27.321  3270  3328 I jxcore-log: 
,03-31 17:41:27.328  3270  3328 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 17:41:27.328  3270  3328 I jxcore-log: 
,03-31 17:41:27.333  3270  3328 I jxcore-log: DEBUG createNativeListener: new outgoing socket
,03-31 17:41:27.333  3270  3328 I jxcore-log: 
,03-31 17:41:27.340  3270  3328 I jxcore-log: ok 39 Buffers are identical
,03-31 17:41:27.340  3270  3328 I jxcore-log: 
,03-31 17:41:27.345  3270  3328 I jxcore-log: DEBUG createNativeListener: incoming socket timeout
03-31 17:41:27.345  3270  3328 I jxcore-log: 
,03-31 17:41:27.346  3270  3328 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 17:41:27.346  3270  3328 I jxcore-log: 
,03-31 17:41:27.348  3270  3328 I jxcore-log: DEBUG createNativeListener: mux close
03-31 17:41:27.348  3270  3328 I jxcore-log: 
,03-31 17:41:27.353  3270  3328 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 17:41:27.353  3270  3328 I jxcore-log: 
,03-31 17:41:27.354  3270  3328 I jxcore-log: ok 40 server should be fine
03-31 17:41:27.354  3270  3328 I jxcore-log: 
,03-31 17:41:27.354  3270  3328 I jxcore-log: ok 41 server should be open
03-31 17:41:27.354  3270  3328 I jxcore-log: 
03-31 17:41:27.354  3270  3328 I jxcore-log: ok 42 incoming has been removed
03-31 17:41:27.354  3270  3328 I jxcore-log: 
,03-31 17:41:27.355  3270  3328 I jxcore-log: ok 43 The mux object should be closed
03-31 17:41:27.355  3270  3328 I jxcore-log: 
03-31 17:41:27.355  3270  3328 I jxcore-log: ok 44 The mux stream should be closed
03-31 17:41:27.355  3270  3328 I jxcore-log: 
03-31 17:41:27.362  3270  3328 I jxcore-log: # teardown
03-31 17:41:27.362  3270  3328 I jxcore-log: 
,03-31 17:41:27.523  3270  3328 I jxcore-log: # setup
03-31 17:41:27.523  3270  3328 I jxcore-log: 
,03-31 17:41:28.731   823   842 I ActivityManager: Killing 1546:com.google.android.googlequicksearchbox:search/u0a28 (adj 15): empty #17,
,03-31 17:41:28.858   823  1022 D WifiService: Client connection lost with reason: 4
,03-31 17:41:30.088  3270  3328 I jxcore-log: # 12. closeAll can close even when connections open
03-31 17:41:30.088  3270  3328 I jxcore-log: 
,03-31 17:41:30.134  2737  2753 D Finsky  : [250] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,03-31 17:41:30.151  1233  1233 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 17:41:30.208  1233  1640 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,03-31 17:41:30.209  1233  1640 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-31 17:41:30.209  1233  1640 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 17:41:30.209  1233  1640 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 17:41:30.220  1233  1640 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 17:41:30.254  2737  2753 D Finsky  : [250] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,03-31 17:41:30.331  3270  3328 I jxcore-log: ok 45 not possible to connect to the server anymore
03-31 17:41:30.331  3270  3328 I jxcore-log: 
,03-31 17:41:30.336  3270  3328 I jxcore-log: # teardown
03-31 17:41:30.336  3270  3328 I jxcore-log: 
,03-31 17:41:30.451  3270  3328 I jxcore-log: # setup
03-31 17:41:30.451  3270  3328 I jxcore-log: 
,03-31 17:41:30.641  3270  3328 I jxcore-log: # 13. closeAll with promise
03-31 17:41:30.641  3270  3328 I jxcore-log: 
,03-31 17:41:30.791  3270  3328 I jxcore-log: ok 46 not possible to connect to the server anymore
03-31 17:41:30.791  3270  3328 I jxcore-log: 
,03-31 17:41:30.796  3270  3328 I jxcore-log: # teardown
03-31 17:41:30.796  3270  3328 I jxcore-log: 
,03-31 17:41:30.916  3270  3328 I jxcore-log: # setup
03-31 17:41:30.916  3270  3328 I jxcore-log: 
,03-31 17:41:31.075  3270  3328 I jxcore-log: # 14. closeAll properly throws when closing a non open server with eatNotRunning set to false
03-31 17:41:31.075  3270  3328 I jxcore-log: 
,03-31 17:41:31.312  3270  3328 I jxcore-log: ok 47 Got the right error
03-31 17:41:31.312  3270  3328 I jxcore-log: 
,03-31 17:41:31.317  3270  3328 I jxcore-log: # teardown
03-31 17:41:31.317  3270  3328 I jxcore-log: 
,03-31 17:41:31.464  3270  3328 I jxcore-log: # setup
03-31 17:41:31.464  3270  3328 I jxcore-log: 
,03-31 17:41:31.626  3270  3328 I jxcore-log: # 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true
03-31 17:41:31.626  3270  3328 I jxcore-log: 
,03-31 17:41:31.824  3270  3328 I jxcore-log: # teardown
03-31 17:41:31.824  3270  3328 I jxcore-log: 
,03-31 17:41:32.007  3270  3328 I jxcore-log: # setup
03-31 17:41:32.007  3270  3328 I jxcore-log: 
,03-31 17:41:32.119  3270  3328 I jxcore-log: # 16. multiplex can send data
03-31 17:41:32.119  3270  3328 I jxcore-log: 
,03-31 17:41:32.347  3270  3328 I jxcore-log: ok 48 String should be length:200
03-31 17:41:32.347  3270  3328 I jxcore-log: 
,03-31 17:41:32.356  3270  3328 I jxcore-log: # teardown
03-31 17:41:32.356  3270  3328 I jxcore-log: 
,03-31 17:41:32.462  3270  3328 I jxcore-log: # setup
03-31 17:41:32.462  3270  3328 I jxcore-log: 
,03-31 17:41:32.564  3270  3328 I jxcore-log: # 17. enqueue and run in order,
03-31 17:41:32.564  3270  3328 I jxcore-log: 
,03-31 17:41:32.774  3270  3328 I jxcore-log: ok 49 firstPromise setTimeout
03-31 17:41:32.774  3270  3328 I jxcore-log: 
,03-31 17:41:32.778  3270  3328 I jxcore-log: ok 50 firstPromise result,
03-31 17:41:32.778  3270  3328 I jxcore-log: 
03-31 17:41:32.779  3270  3328 I jxcore-log: ok 51 firstPromise testValue
03-31 17:41:32.779  3270  3328 I jxcore-log: 
,03-31 17:41:32.883  3270  3328 I jxcore-log: ok 52 secondPromise setTimeout
03-31 17:41:32.883  3270  3328 I jxcore-log: 
,03-31 17:41:32.887  3270  3328 I jxcore-log: ok 53 secondPromise result
03-31 17:41:32.887  3270  3328 I jxcore-log: 
03-31 17:41:32.888  3270  3328 I jxcore-log: ok 54 secondPromise testValue
03-31 17:41:32.888  3270  3328 I jxcore-log: 
,03-31 17:41:32.892  3270  3328 I jxcore-log: ok 55 thirdPromise in promise
03-31 17:41:32.892  3270  3328 I jxcore-log: 
03-31 17:41:32.895  3270  3328 I jxcore-log: ok 56 thirdPromise result
03-31 17:41:32.895  3270  3328 I jxcore-log: 
,03-31 17:41:32.897  3270  3328 I jxcore-log: ok 57 thirdPromise testValue
03-31 17:41:32.897  3270  3328 I jxcore-log: 
,03-31 17:41:32.912  3270  3328 I jxcore-log: # teardown
03-31 17:41:32.912  3270  3328 I jxcore-log: 
,03-31 17:41:33.084  3270  3328 I jxcore-log: # setup
03-31 17:41:33.084  3270  3328 I jxcore-log: 
,03-31 17:41:33.243  3270  3328 I jxcore-log: # 18. enqueueAtTop and run backwards
03-31 17:41:33.243  3270  3328 I jxcore-log: 
,03-31 17:41:33.357  3270  3328 I jxcore-log: ok 58 thirdPromise - first to run
03-31 17:41:33.357  3270  3328 I jxcore-log: 
,03-31 17:41:33.362  3270  3328 I jxcore-log: ok 59 thirdPromise - in resolve
03-31 17:41:33.362  3270  3328 I jxcore-log: 
,03-31 17:41:33.365  3270  3328 I jxcore-log: ok 60 secondPromise - second to run
03-31 17:41:33.365  3270  3328 I jxcore-log: 
,03-31 17:41:33.367  3270  3328 I jxcore-log: ok 61 secondPromise - in catch
03-31 17:41:33.367  3270  3328 I jxcore-log: 
,03-31 17:41:33.370  3270  3328 I jxcore-log: ok 62 firstPromise - third to run
03-31 17:41:33.370  3270  3328 I jxcore-log: 
,03-31 17:41:33.372  3270  3328 I jxcore-log: ok 63 firstPromise - in then
03-31 17:41:33.372  3270  3328 I jxcore-log: 
,03-31 17:41:33.373  3270  3328 I jxcore-log: ok 64 testing promises
03-31 17:41:33.373  3270  3328 I jxcore-log: 
,03-31 17:41:33.375  3270  3328 I jxcore-log: # teardown
03-31 17:41:33.375  3270  3328 I jxcore-log: 
,03-31 17:41:33.527  3270  3328 I jxcore-log: # setup
03-31 17:41:33.527  3270  3328 I jxcore-log: 
,03-31 17:41:33.618  3270  3328 I jxcore-log: # 19. mix enqueue and enqueueAtTop
03-31 17:41:33.618  3270  3328 I jxcore-log: 
,03-31 17:41:33.748  3270  3328 I jxcore-log: ok 65 fourth,
03-31 17:41:33.748  3270  3328 I jxcore-log: 
,03-31 17:41:33.752  3270  3328 I jxcore-log: ok 66 fourth
03-31 17:41:33.752  3270  3328 I jxcore-log: 
,03-31 17:41:33.753  3270  3328 I jxcore-log: ok 67 second
03-31 17:41:33.753  3270  3328 I jxcore-log: 
03-31 17:41:33.754  3270  3328 I jxcore-log: ok 68 secondPromise - in then
03-31 17:41:33.754  3270  3328 I jxcore-log: 
,03-31 17:41:33.857  3270  3328 I jxcore-log: ok 69 first
03-31 17:41:33.857  3270  3328 I jxcore-log: 
,03-31 17:41:33.860  3270  3328 I jxcore-log: ok 70 firstPromise - in catch
03-31 17:41:33.860  3270  3328 I jxcore-log: 
,03-31 17:41:33.863  3270  3328 I jxcore-log: ok 71 third
03-31 17:41:33.863  3270  3328 I jxcore-log: 
,03-31 17:41:33.865  3270  3328 I jxcore-log: ok 72 thirdPromise - in then
03-31 17:41:33.865  3270  3328 I jxcore-log: 
,03-31 17:41:33.867  3270  3328 I jxcore-log: ok 73 testingPromises
03-31 17:41:33.867  3270  3328 I jxcore-log: 
,03-31 17:41:33.881  3270  3328 I jxcore-log: # teardown
03-31 17:41:33.881  3270  3328 I jxcore-log: 
,03-31 17:41:34.009  3270  3328 I jxcore-log: # setup
03-31 17:41:34.009  3270  3328 I jxcore-log: 
,03-31 17:41:34.143  3270  3328 I jxcore-log: # 20. queues handled independently
03-31 17:41:34.143  3270  3328 I jxcore-log: 
,03-31 17:41:34.317  3270  3328 I jxcore-log: ok 74 all short operations completed before the long resolves
03-31 17:41:34.317  3270  3328 I jxcore-log: 
,03-31 17:41:34.322  3270  3328 I jxcore-log: # teardown
03-31 17:41:34.322  3270  3328 I jxcore-log: 
,03-31 17:41:34.679  1233  1233 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 17:41:34.763  1233  1640 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,03-31 17:41:34.763  1233  1640 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-31 17:41:34.764  1233  1640 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-31 17:41:34.764  1233  1640 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 17:41:34.773  3270  3328 I jxcore-log: # setup
03-31 17:41:34.773  3270  3328 I jxcore-log: 
,03-31 17:41:34.778  1233  1640 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 17:41:34.808  2737  2737 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,03-31 17:41:34.809  2737  2737 D Finsky  : [1] 5.onFinished: Installation state replication failed.
,03-31 17:41:34.810  2737  2737 D Finsky  : [1] 5.onFinished: Giving up after 6 failures.
,03-31 17:41:35.441  3270  3328 I jxcore-log: # 21. basic
03-31 17:41:35.441  3270  3328 I jxcore-log: 
,03-31 17:41:38.015  2163  2210 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-31 17:41:40.313  3270  3328 I jxcore-log: ok 75 sane,
03-31 17:41:40.313  3270  3328 I jxcore-log: 
,03-31 17:41:40.322  3270  3328 I jxcore-log: # teardown,
03-31 17:41:40.322  3270  3328 I jxcore-log: 
,03-31 17:41:40.622  3270  3328 I jxcore-log: # setup,
03-31 17:41:40.622  3270  3328 I jxcore-log: 
,03-31 17:41:41.044  3270  3328 I jxcore-log: # 22. another
03-31 17:41:41.044  3270  3328 I jxcore-log: 
,03-31 17:41:42.463  3270  3328 I jxcore-log: ok 76 sane
03-31 17:41:42.463  3270  3328 I jxcore-log: 
,03-31 17:41:42.471  3270  3328 I jxcore-log: # teardown
03-31 17:41:42.471  3270  3328 I jxcore-log: 
,03-31 17:41:42.652  3270  3328 I jxcore-log: # setup
03-31 17:41:42.652  3270  3328 I jxcore-log: 
,03-31 17:41:42.759  3270  3328 I jxcore-log: # 23. can pass data in setup
03-31 17:41:42.759  3270  3328 I jxcore-log: 
,03-31 17:41:42.850  3270  3328 I jxcore-log: [{"uuid":"09df9b58-c00e-441d-95dd-ac84f3a5a575","data":"custom data"},{"uuid":"7e0fbac2-01ae-4b38-8d07-95fc9ca257ca","data":"custom data"},{"uuid":"7c0b9993-3f94-46a9-bcae-bea2585a8ff8","data":"custom data"}]
03-31 17:41:42.850  3270  3328 I jxcore-log: 
,03-31 17:41:42.853  3270  3328 I jxcore-log: ok 77 test participant has uuid
03-31 17:41:42.853  3270  3328 I jxcore-log: 
,03-31 17:41:42.855  3270  3328 I jxcore-log: ok 78 participant data matches
03-31 17:41:42.855  3270  3328 I jxcore-log: 
,03-31 17:41:42.859  3270  3328 I jxcore-log: ok 79 test participant has uuid
03-31 17:41:42.859  3270  3328 I jxcore-log: 
,03-31 17:41:42.861  3270  3328 I jxcore-log: ok 80 participant data matches
03-31 17:41:42.861  3270  3328 I jxcore-log: 
,03-31 17:41:42.862  3270  3328 I jxcore-log: ok 81 test participant has uuid
03-31 17:41:42.862  3270  3328 I jxcore-log: 
,03-31 17:41:42.863  3270  3328 I jxcore-log: ok 82 participant data matches
03-31 17:41:42.863  3270  3328 I jxcore-log: 
03-31 17:41:42.863  3270  3328 I jxcore-log: ok 83 own UUID is found from the participants list
03-31 17:41:42.863  3270  3328 I jxcore-log: 
03-31 17:41:42.865  3270  3328 I jxcore-log: # teardown
03-31 17:41:42.865  3270  3328 I jxcore-log: 
,03-31 17:41:43.031  3270  3328 I jxcore-log: # setup
03-31 17:41:43.031  3270  3328 I jxcore-log: 
,03-31 17:41:43.261  3270  3328 I jxcore-log: # 24. #startListeningForAdvertisements should fail if start not called
03-31 17:41:43.261  3270  3328 I jxcore-log: 
,03-31 17:41:43.440  3270  3328 I jxcore-log: ok 84 specific error should be returned
03-31 17:41:43.440  3270  3328 I jxcore-log: 
,03-31 17:41:43.444  3270  3328 I jxcore-log: # teardown
03-31 17:41:43.444  3270  3328 I jxcore-log: 
,03-31 17:41:43.596  3270  3328 I jxcore-log: ok 85 error should be null
03-31 17:41:43.596  3270  3328 I jxcore-log: 
,03-31 17:41:43.598  3270  3328 I jxcore-log: ok 86 error should be null
03-31 17:41:43.598  3270  3328 I jxcore-log: 
,03-31 17:41:43.603  3270  3328 I jxcore-log: # setup
03-31 17:41:43.603  3270  3328 I jxcore-log: 
,03-31 17:41:43.807  3270  3328 I jxcore-log: # 25. #startUpdateAdvertisingAndListening should fail if start not called
03-31 17:41:43.807  3270  3328 I jxcore-log: 
,03-31 17:41:43.962  3270  3328 I jxcore-log: ok 87 specific error should be returned
03-31 17:41:43.962  3270  3328 I jxcore-log: 
,03-31 17:41:43.964  3270  3328 I jxcore-log: # teardown
03-31 17:41:43.964  3270  3328 I jxcore-log: 
,03-31 17:41:44.109  3270  3328 I jxcore-log: ok 88 error should be null
03-31 17:41:44.109  3270  3328 I jxcore-log: 
,03-31 17:41:44.111  3270  3328 I jxcore-log: ok 89 error should be null
03-31 17:41:44.111  3270  3328 I jxcore-log: 
,03-31 17:41:44.117  3270  3328 I jxcore-log: # setup
03-31 17:41:44.117  3270  3328 I jxcore-log: 
,03-31 17:41:44.242  3270  3328 I jxcore-log: # 26. should be able to call #stopListeningForAdvertisements many times
03-31 17:41:44.242  3270  3328 I jxcore-log: 
,03-31 17:41:44.447  3270  3328 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 17:41:44.447  3270  3328 I jxcore-log: 
,03-31 17:41:44.449  3270  3328 I jxcore-log: DEBUG createNativeListener: listening 52939
03-31 17:41:44.449  3270  3328 I jxcore-log: 
,03-31 17:41:44.452  3270  3328 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-31 17:41:44.452  3270  3328 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 17:41:44.452  3270  3328 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 17:41:44.456  3270  3328 I jxcore-log: ok 90 error should be null
03-31 17:41:44.456  3270  3328 I jxcore-log: 
,03-31 17:41:44.457  3270  3328 I jxcore-log: ok 91 error should be null
03-31 17:41:44.457  3270  3328 I jxcore-log: 
,03-31 17:41:44.458  3270  3328 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-31 17:41:44.458  3270  3328 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-31 17:41:44.458  3270  3328 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-31 17:41:44.460  3270  3328 I jxcore-log: ok 92 error should be null
03-31 17:41:44.460  3270  3328 I jxcore-log: 
03-31 17:41:44.461  3270  3328 I jxcore-log: ok 93 error should be null
03-31 17:41:44.461  3270  3328 I jxcore-log: 
,03-31 17:41:44.465  3270  3328 I jxcore-log: # teardown
03-31 17:41:44.465  3270  3328 I jxcore-log: 
,03-31 17:41:44.933  3270  3328 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 17:41:44.933  3270  3328 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 17:41:44.933  3270  3328 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 17:41:44.936  3270  3328 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-31 17:41:44.936  3270  3328 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 17:41:44.936  3270  3328 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-31 17:41:44.941  3270  3328 I jxcore-log: ok 94 error should be null
03-31 17:41:44.941  3270  3328 I jxcore-log: 
,03-31 17:41:44.941  3270  3328 I jxcore-log: ok 95 error should be null
03-31 17:41:44.941  3270  3328 I jxcore-log: 
,03-31 17:41:44.947  3270  3328 I jxcore-log: # setup
03-31 17:41:44.947  3270  3328 I jxcore-log: 
,03-31 17:41:45.133  3270  3328 I jxcore-log: # 27. should be able to call #startListeningForAdvertisements many times
03-31 17:41:45.133  3270  3328 I jxcore-log: 
,03-31 17:41:45.318  3270  3328 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 17:41:45.318  3270  3328 I jxcore-log: 
,03-31 17:41:45.320  3270  3328 I jxcore-log: DEBUG createNativeListener: listening 41816
03-31 17:41:45.320  3270  3328 I jxcore-log: 
,03-31 17:41:45.330  3270  3328 I io.jxcore.node.ConnectionHelper: start: Port number: 0, start advertisements: false
,03-31 17:41:45.330  3270  3328 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 17:41:45.330  3270  3328 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-31 17:41:45.330  3270  3328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-31 17:41:45.330  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 17:41:45.330  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-31 17:41:45.341  3270  3328 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-31 17:41:45.342   823   841 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 17:41:45.357  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-31 17:41:45.372  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-31 17:41:45.373  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-31 17:41:45.373  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-31 17:41:45.373  3270  3328 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 17:41:45.384  2163  2183 D BtGatt.GattService: registerClient() - UUID=d552875a-4dc8-4d17-9b73-8294c589bc5b
,03-31 17:41:45.389  2163  2207 D BtGatt.GattService: onClientRegistered() - UUID=d552875a-4dc8-4d17-9b73-8294c589bc5b, clientIf=5
03-31 17:41:45.391  3270  3287 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-31 17:41:45.392  2163  2209 D BtGatt.GattService: start scan with filters
,03-31 17:41:45.394  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-31 17:41:45.395  2163  2218 D BtGatt.ScanManager: handling starting scan
,03-31 17:41:45.395  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 17:41:45.395  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-31 17:41:45.398  3270  3328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-31 17:41:45.398  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 17:41:45.399  2163  2218 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a4d9362
03-31 17:41:45.399  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-31 17:41:45.399  3270  3270 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 17:41:45.399   823  1393 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 17:41:45.403  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-31 17:41:45.404  3270  3328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-31 17:41:45.406  3270  3328 I io.jxcore.node.ConnectionHelper: start: OK
,03-31 17:41:45.406  3270  3270 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-31 17:41:45.406  3270  3270 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-31 17:41:45.407  3270  3270 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-31 17:41:45.412  2163  2207 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-31 17:41:45.412  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 17:41:45.415  2163  2207 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-31 17:41:45.415  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:41:45.415  2163  2218 D BtGatt.ScanManager: Starting BLE batch scan
,03-31 17:41:45.415  2163  2218 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-31 17:41:45.416  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 17:41:45.416  3270  3328 I jxcore-log: 
03-31 17:41:45.417  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 17:41:45.417  3270  3328 I jxcore-log: 
03-31 17:41:45.418  2163  2207 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-31 17:41:45.418  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 17:41:45.419  3270  3328 I jxcore-log: ok 96 error should be null
03-31 17:41:45.419  3270  3328 I jxcore-log: 
,03-31 17:41:45.420  2163  2207 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-31 17:41:45.420  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
03-31 17:41:45.421  3270  3328 I jxcore-log: ok 97 error should be null
03-31 17:41:45.421  3270  3328 I jxcore-log: 
,03-31 17:41:45.427  3270  3328 I io.jxcore.node.ConnectionHelper: start: Port number: 0, start advertisements: false
,03-31 17:41:45.427  3270  3328 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 17:41:45.427  3270  3328 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-31 17:41:45.427  3270  3328 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-31 17:41:45.427  3270  3328 I io.jxcore.node.ConnectionHelper: start: OK
,03-31 17:41:45.429  3270  3328 I jxcore-log: ok 98 error should be null
03-31 17:41:45.429  3270  3328 I jxcore-log: 
03-31 17:41:45.429  3270  3328 I jxcore-log: ok 99 error should be null
03-31 17:41:45.429  3270  3328 I jxcore-log: 
,03-31 17:41:45.436  3270  3328 I jxcore-log: # teardown
03-31 17:41:45.436  3270  3328 I jxcore-log: 
,03-31 17:41:45.731  3270  3328 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-31 17:41:45.731  3270  3328 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
03-31 17:41:45.731  3270  3328 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,03-31 17:41:45.731  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-31 17:41:45.731  3270  3328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-31 17:41:45.731  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-31 17:41:45.732  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-31 17:41:45.733  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-31 17:41:45.733  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-31 17:41:45.735  2163  2958 D BtGatt.GattService: stopScan() - queue size =1
03-31 17:41:45.736  2163  2183 D BtGatt.GattService: unregisterClient() - clientIf=5
03-31 17:41:45.737  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 17:41:45.737  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 17:41:45.737  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-31 17:41:45.737  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-31 17:41:45.737  3270  3328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-31 17:41:45.737  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-31 17:41:45.740  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-31 17:41:45.740  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-31 17:41:45.740  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...,
03-31 17:41:45.741  2163  2207 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-31 17:41:45.741  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 17:41:45.741  2163  2218 D BtGatt.ScanManager: stopping BLe Batch
,03-31 17:41:45.741  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-31 17:41:45.742  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 17:41:45.742  3270  3270 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 17:41:45.742  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 17:41:45.742  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-31 17:41:45.744  2163  2207 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0,
,03-31 17:41:45.744  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
,03-31 17:41:45.745  2163  2218 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5,
,03-31 17:41:45.748  2163  2207 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,03-31 17:41:45.748  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 17:41:45.749  3270  3328 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).,
03-31 17:41:45.749  3270  3328 I jxcore-log: 
,03-31 17:41:45.765  3270  3270 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-31 17:41:45.765   823  1150 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 17:41:45.773  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-31 17:41:45.774  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-31 17:41:45.774  3270  3270 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-31 17:41:45.779  3270  3270 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 17:41:45.779  3270  3270 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-31 17:41:45.779  3270  3270 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 17:41:45.779  3270  3270 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 17:41:45.781  3270  3328 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-31 17:41:45.781  3270  3328 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 17:41:45.781  3270  3328 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-31 17:41:45.782  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 17:41:45.782  3270  3328 I jxcore-log: 
,03-31 17:41:45.783  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 17:41:45.783  3270  3328 I jxcore-log: 
,03-31 17:41:45.786  3270  3328 I jxcore-log: ok 100 error should be null
03-31 17:41:45.786  3270  3328 I jxcore-log: 
,03-31 17:41:45.787  3270  3328 I jxcore-log: ok 101 error should be null
03-31 17:41:45.787  3270  3328 I jxcore-log: 
,03-31 17:41:45.792  3270  3328 I jxcore-log: # setup
03-31 17:41:45.792  3270  3328 I jxcore-log: 
,03-31 17:41:46.063  3270  3328 I jxcore-log: # 28. should be able to call #startUpdateAdvertisingAndListening many times
03-31 17:41:46.063  3270  3328 I jxcore-log: ,
,03-31 17:41:46.199  3270  3328 I jxcore-log: DEBUG createNativeListener: creating native server,
03-31 17:41:46.199  3270  3328 I jxcore-log: 
,03-31 17:41:46.201  3270  3328 I jxcore-log: DEBUG createNativeListener: listening 41605
03-31 17:41:46.201  3270  3328 I jxcore-log: 
,03-31 17:41:46.228  3270  3328 I io.jxcore.node.ConnectionHelper: start: Port number: 41605, start advertisements: true
03-31 17:41:46.228  3270  3328 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 17:41:46.228  3270  3328 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,03-31 17:41:46.228  3270  3328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-31 17:41:46.232  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-31 17:41:46.232  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-31 17:41:46.232  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true,
,03-31 17:41:46.232  3270  3328 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null],
,03-31 17:41:46.236  2163  2958 D BtGatt.GattService: registerClient() - UUID=37e0364e-f79b-4d52-ba46-8afc8598786a
03-31 17:41:46.237  2163  2207 D BtGatt.GattService: onClientRegistered() - UUID=37e0364e-f79b-4d52-ba46-8afc8598786a, clientIf=5
03-31 17:41:46.238  3270  3288 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-31 17:41:46.238  2163  2183 D BtGatt.GattService: start scan with filters
03-31 17:41:46.239  2163  2218 D BtGatt.ScanManager: handling starting scan
,03-31 17:41:46.240  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-31 17:41:46.240  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 17:41:46.240  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-31 17:41:46.240  3270  3328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-31 17:41:46.240  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
,03-31 17:41:46.240  3270  3270 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-31 17:41:46.240  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-31 17:41:46.240  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-31 17:41:46.241  3270  3328 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
,03-31 17:41:46.242  2163  2207 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,03-31 17:41:46.242  3270  3328 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false],
,03-31 17:41:46.243  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 17:41:46.243  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false],
03-31 17:41:46.243  3270  3328 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-31 17:41:46.245  2163  2207 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-31 17:41:46.245  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:41:46.245  2163  2218 D BtGatt.ScanManager: Starting BLE batch scan
03-31 17:41:46.245  2163  2218 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-31 17:41:46.248  2163  2183 D BtGatt.GattService: registerClient() - UUID=fad97830-058a-4922-a5b0-016e918c4591
,03-31 17:41:46.249  2163  2207 D BtGatt.GattService: onClientRegistered() - UUID=fad97830-058a-4922-a5b0-016e918c4591, clientIf=6
03-31 17:41:46.249  3270  3287 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-31 17:41:46.250  2163  2207 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-31 17:41:46.250  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:41:46.252  2163  2207 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-31 17:41:46.252  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:41:46.252  2163  2217 D BtGatt.AdvertiseManager: message : 0
03-31 17:41:46.258  2163  2217 D BtGatt.AdvertiseManager: starting multi advertising
03-31 17:41:46.261  2163  2207 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-31 17:41:46.264  2163  2207 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-31 17:41:46.265  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-31 17:41:46.266  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-31 17:41:46.266   823  1412 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 17:41:46.269  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 17:41:46.269  3270  3328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-31 17:41:46.269  3270  3328 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-31 17:41:46.269  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 17:41:46.270  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-31 17:41:46.271  3270  3328 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-31 17:41:46.271  3270  3328 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-31 17:41:46.272  3270  3328 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,03-31 17:41:46.272  3270  3270 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-31 17:41:46.272  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,03-31 17:41:46.272  3270  3270 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-31 17:41:46.272  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-31 17:41:46.272  3270  3270 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-31 17:41:46.272  3270  3270 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-31 17:41:46.272  3270  3270 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-31 17:41:46.272  3270  3270 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 17:41:46.272  3270  3270 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-31 17:41:46.272  3270  3270 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-31 17:41:46.273  3270  3270 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-31 17:41:46.273  3270  3270 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-31 17:41:46.273  3270  3328 I io.jxcore.node.ConnectionHelper: start: OK
03-31 17:41:46.278   823  1370 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 17:41:46.280  3270  3715 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-31 17:41:46.284  3270  3715 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-31 17:41:46.288  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 17:41:46.288  3270  3328 I jxcore-log: 
,03-31 17:41:46.289  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 17:41:46.289  3270  3328 I jxcore-log: 
,03-31 17:41:46.290  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-31 17:41:46.290  3270  3328 I jxcore-log: 
,03-31 17:41:46.293  3270  3328 I jxcore-log: ok 102 error should be null
03-31 17:41:46.293  3270  3328 I jxcore-log: 
,03-31 17:41:46.293  3270  3328 I jxcore-log: ok 103 error should be null
03-31 17:41:46.293  3270  3328 I jxcore-log: 
,03-31 17:41:46.301  3270  3328 I io.jxcore.node.ConnectionHelper: start: Port number: 41605, start advertisements: true
,03-31 17:41:46.301  3270  3328 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-31 17:41:46.301  3270  3328 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-31 17:41:46.301  3270  3328 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-31 17:41:46.302  3270  3328 I io.jxcore.node.ConnectionHelper: start: OK
,03-31 17:41:46.313  3270  3328 I jxcore-log: ok 104 error should be null
03-31 17:41:46.313  3270  3328 I jxcore-log: 
,03-31 17:41:46.313  3270  3328 I jxcore-log: ok 105 error should be null
03-31 17:41:46.313  3270  3328 I jxcore-log: 
,03-31 17:41:46.328  3270  3328 I jxcore-log: # teardown
03-31 17:41:46.328  3270  3328 I jxcore-log: 
,03-31 17:41:46.705  3270  3328 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections,
03-31 17:41:46.705  3270  3328 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-31 17:41:46.705  3270  3328 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,03-31 17:41:46.705  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-31 17:41:46.705  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-31 17:41:46.706  3270  3328 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-31 17:41:46.706  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
03-31 17:41:46.706  3270  3328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-31 17:41:46.706  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-31 17:41:46.706  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode,
03-31 17:41:46.706  3270  3715 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-31 17:41:46.706  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-31 17:41:46.706  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...,
03-31 17:41:46.706  3270  3715 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-31 17:41:46.706  3270  3715 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-31 17:41:46.708  2163  2209 D BtGatt.GattService: stopScan() - queue size =1
,03-31 17:41:46.709  2163  2958 D BtGatt.GattService: unregisterClient() - clientIf=5
03-31 17:41:46.709  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 17:41:46.709  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-31 17:41:46.710  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-31 17:41:46.710  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-31 17:41:46.710  3270  3328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
,03-31 17:41:46.710  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-31 17:41:46.710  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-31 17:41:46.714  2163  2217 D BtGatt.AdvertiseManager: message : 1,
,03-31 17:41:46.716  2163  2217 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-31 17:41:46.718  2163  2207 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,03-31 17:41:46.718  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:41:46.718  2163  2218 D BtGatt.ScanManager: stopping BLe Batch
03-31 17:41:46.720  2163  2207 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,03-31 17:41:46.720  2163  2207 D BtGatt.GattService: Client app is not null!
03-31 17:41:46.721  2163  2209 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-31 17:41:46.722  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
,03-31 17:41:46.722  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED,
03-31 17:41:46.722  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,03-31 17:41:46.723  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-31 17:41:46.723  3270  3328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,03-31 17:41:46.723  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 17:41:46.723  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-31 17:41:46.723  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-31 17:41:46.725  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
03-31 17:41:46.725  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 17:41:46.725  3270  3270 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 17:41:46.725  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 17:41:46.726  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-31 17:41:46.729  2163  2207 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-31 17:41:46.729  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:41:46.729  2163  2218 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-31 17:41:46.733  2163  2207 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
03-31 17:41:46.734  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 17:41:46.734  2163  2207 D BtGatt.GattService: current time is 196153689351
03-31 17:41:46.734  2163  2207 D BtGatt.GattService: Batch record : [90, 76, -29, -57, 84, 83, 1, -128, -64, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -63, 7, 0, 0, 0, -127, -59, 40, 32, -73, -32, 1, -128, -68, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-31 17:41:46.735  2163  2207 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-31 17:41:46.736  2163  2207 D BtGatt.GattService: ScanRecord : []
03-31 17:41:46.736  2163  2207 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-31 17:41:46.737  3270  3270 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-31 17:41:46.738   823  1370 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 17:41:46.747  3270  3328 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).,
03-31 17:41:46.747  3270  3328 I jxcore-log: 
,03-31 17:41:46.749  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-31 17:41:46.751  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0,
03-31 17:41:46.752  3270  3270 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-31 17:41:46.758  3270  3270 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-31 17:41:46.758  3270  3270 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,03-31 17:41:46.758  3270  3270 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-31 17:41:46.758  3270  3270 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 17:41:46.758  3270  3270 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 17:41:46.759  3270  3270 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 17:41:46.760  3270  3270 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-31 17:41:46.760  3270  3270 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-31 17:41:46.761  3270  3328 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-31 17:41:46.762  3270  3328 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 17:41:46.762  3270  3328 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-31 17:41:46.763  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-31 17:41:46.763  3270  3328 I jxcore-log: 
03-31 17:41:46.764  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 17:41:46.764  3270  3328 I jxcore-log: 
03-31 17:41:46.765  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 17:41:46.765  3270  3328 I jxcore-log: 
,03-31 17:41:46.770  3270  3328 I jxcore-log: ok 106 error should be null
,03-31 17:41:46.770  3270  3328 I jxcore-log: 
,03-31 17:41:46.772  3270  3328 I jxcore-log: ok 107 error should be null
03-31 17:41:46.772  3270  3328 I jxcore-log: 
,03-31 17:41:46.779  3270  3328 I jxcore-log: # setup
,03-31 17:41:46.779  3270  3328 I jxcore-log: 
,03-31 17:41:46.949  3270  3328 I jxcore-log: # 29. should be able to call #stopAdvertisingAndListening many times
03-31 17:41:46.949  3270  3328 I jxcore-log: 
,03-31 17:41:47.131  3270  3328 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 17:41:47.131  3270  3328 I jxcore-log: 
,03-31 17:41:47.133  3270  3328 I jxcore-log: DEBUG createNativeListener: listening 51059
03-31 17:41:47.133  3270  3328 I jxcore-log: 
,03-31 17:41:47.138  3270  3328 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 17:41:47.139  3270  3328 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 17:41:47.139  3270  3328 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 17:41:47.142  3270  3328 I jxcore-log: ok 108 error should be null
03-31 17:41:47.142  3270  3328 I jxcore-log: 
,03-31 17:41:47.143  3270  3328 I jxcore-log: ok 109 error should be null
03-31 17:41:47.143  3270  3328 I jxcore-log: 
,03-31 17:41:47.145  3270  3328 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-31 17:41:47.145  3270  3328 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-31 17:41:47.145  3270  3328 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 17:41:47.150  3270  3328 I jxcore-log: ok 110 error should be null
03-31 17:41:47.150  3270  3328 I jxcore-log: 
,03-31 17:41:47.150  3270  3328 I jxcore-log: ok 111 error should be null
03-31 17:41:47.150  3270  3328 I jxcore-log: 
03-31 17:41:47.156  3270  3328 I jxcore-log: # teardown
03-31 17:41:47.156  3270  3328 I jxcore-log: 
,03-31 17:41:47.281  3270  3328 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 17:41:47.282  3270  3328 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-31 17:41:47.282  3270  3328 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-31 17:41:47.285  3270  3328 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-31 17:41:47.285  3270  3328 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-31 17:41:47.285  3270  3328 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 17:41:47.291  3270  3328 I jxcore-log: ok 112 error should be null
,03-31 17:41:47.291  3270  3328 I jxcore-log: 
03-31 17:41:47.292  3270  3328 I jxcore-log: ok 113 error should be null
03-31 17:41:47.292  3270  3328 I jxcore-log: 
03-31 17:41:47.297  3270  3328 I jxcore-log: # setup
03-31 17:41:47.297  3270  3328 I jxcore-log: 
,03-31 17:41:47.465  3270  3328 I jxcore-log: # 30. #start should fail if called twice in a row
03-31 17:41:47.465  3270  3328 I jxcore-log: 
,03-31 17:41:47.654  3270  3328 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 17:41:47.654  3270  3328 I jxcore-log: 
,03-31 17:41:47.656  3270  3328 I jxcore-log: DEBUG createNativeListener: listening 56875
03-31 17:41:47.656  3270  3328 I jxcore-log: 
,03-31 17:41:47.659  3270  3328 I jxcore-log: ok 114 first call should succeed
03-31 17:41:47.659  3270  3328 I jxcore-log: 
,03-31 17:41:47.660  3270  3328 I jxcore-log: ok 115 first call should succeed
03-31 17:41:47.660  3270  3328 I jxcore-log: 
,03-31 17:41:47.663  3270  3328 I jxcore-log: ok 116 specific error should be returned
03-31 17:41:47.663  3270  3328 I jxcore-log: 
,03-31 17:41:47.665  3270  3328 I jxcore-log: # teardown
03-31 17:41:47.665  3270  3328 I jxcore-log: 
,03-31 17:41:47.842  3270  3328 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-31 17:41:47.842  3270  3328 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-31 17:41:47.842  3270  3328 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-31 17:41:47.843  3270  3328 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-31 17:41:47.843  3270  3328 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 17:41:47.843  3270  3328 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-31 17:41:47.847  3270  3328 I jxcore-log: ok 117 error should be null
03-31 17:41:47.847  3270  3328 I jxcore-log: 
,03-31 17:41:47.848  3270  3328 I jxcore-log: ok 118 error should be null
03-31 17:41:47.848  3270  3328 I jxcore-log: 
03-31 17:41:47.853  3270  3328 I jxcore-log: # setup
03-31 17:41:47.853  3270  3328 I jxcore-log: 
,03-31 17:41:47.994  3270  3328 I jxcore-log: # 31. does not emit duplicate discoveryAdvertisingStateUpdate
03-31 17:41:47.994  3270  3328 I jxcore-log: 
,03-31 17:41:48.175  3270  3328 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 17:41:48.175  3270  3328 I jxcore-log: 
,03-31 17:41:48.178  3270  3328 I jxcore-log: DEBUG createNativeListener: listening 58613
03-31 17:41:48.178  3270  3328 I jxcore-log: 
,03-31 17:41:48.188  3270  3328 I io.jxcore.node.ConnectionHelper: start: Port number: 41605, start advertisements: false
,03-31 17:41:48.188  3270  3328 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 17:41:48.188  3270  3328 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-31 17:41:48.188  3270  3328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-31 17:41:48.192  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-31 17:41:48.192  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-31 17:41:48.192  3270  3328 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 17:41:48.196  2163  2181 D BtGatt.GattService: registerClient() - UUID=f47fc0db-26c9-4495-970e-b99c87adc559
03-31 17:41:48.196  2163  2207 D BtGatt.GattService: onClientRegistered() - UUID=f47fc0db-26c9-4495-970e-b99c87adc559, clientIf=5
03-31 17:41:48.197  3270  3287 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-31 17:41:48.197  2163  2209 D BtGatt.GattService: start scan with filters
03-31 17:41:48.198  2163  2218 D BtGatt.ScanManager: handling starting scan
,03-31 17:41:48.199  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
03-31 17:41:48.199  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 17:41:48.199  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,03-31 17:41:48.199  3270  3328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-31 17:41:48.199  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 17:41:48.200  3270  3270 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 17:41:48.201  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK,
,03-31 17:41:48.202   823  1393 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 17:41:48.206  2163  2207 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1,
,03-31 17:41:48.206  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:41:48.209  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
,03-31 17:41:48.209  3270  3328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-31 17:41:48.210  2163  2207 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15,
03-31 17:41:48.210  3270  3270 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only,
03-31 17:41:48.210  3270  3270 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 17:41:48.210  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:41:48.211  2163  2218 D BtGatt.ScanManager: Starting BLE batch scan
03-31 17:41:48.211  2163  2218 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-31 17:41:48.211  3270  3270 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 17:41:48.211  3270  3328 I io.jxcore.node.ConnectionHelper: start: OK
03-31 17:41:48.214  2163  2207 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-31 17:41:48.215  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:41:48.218  2163  2207 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-31 17:41:48.219  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 17:41:48.221  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 17:41:48.221  3270  3328 I jxcore-log: 
,03-31 17:41:48.222  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 17:41:48.222  3270  3328 I jxcore-log: 
,03-31 17:41:48.236  3270  3328 I io.jxcore.node.ConnectionHelper: start: Port number: 58613, start advertisements: true
03-31 17:41:48.236  3270  3328 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 17:41:48.236  3270  3328 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,03-31 17:41:48.236  3270  3328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-31 17:41:48.239  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
03-31 17:41:48.239  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
03-31 17:41:48.239  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,03-31 17:41:48.239  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-31 17:41:48.239  3270  3328 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-31 17:41:48.239  3270  3328 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 17:41:48.239  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 17:41:48.239  3270  3328 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-31 17:41:48.243  2163  2209 D BtGatt.GattService: registerClient() - UUID=d55d320a-3601-4eb1-8820-ca45ccadce3b
,03-31 17:41:48.243  2163  2207 D BtGatt.GattService: onClientRegistered() - UUID=d55d320a-3601-4eb1-8820-ca45ccadce3b, clientIf=6
,03-31 17:41:48.245  3270  3288 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-31 17:41:48.246  2163  2217 D BtGatt.AdvertiseManager: message : 0
,03-31 17:41:48.248  2163  2217 D BtGatt.AdvertiseManager: starting multi advertising
,03-31 17:41:48.251  2163  2207 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-31 17:41:48.253  2163  2207 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-31 17:41:48.254  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-31 17:41:48.254  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-31 17:41:48.254  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-31 17:41:48.254  3270  3270 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-31 17:41:48.254  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-31 17:41:48.254  3270  3270 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-31 17:41:48.255  3270  3270 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-31 17:41:48.255   823  1412 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 17:41:48.258  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-31 17:41:48.258  3270  3328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-31 17:41:48.258  3270  3270 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-31 17:41:48.258  3270  3328 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-31 17:41:48.258  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-31 17:41:48.259  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-31 17:41:48.259  3270  3328 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true,
03-31 17:41:48.259  3270  3328 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING,
03-31 17:41:48.259  3270  3328 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK,
,03-31 17:41:48.260  3270  3270 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,03-31 17:41:48.260  3270  3270 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-31 17:41:48.260  3270  3270 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,03-31 17:41:48.260  3270  3328 I io.jxcore.node.ConnectionHelper: start: OK
,03-31 17:41:48.261   823  1409 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
03-31 17:41:48.262  3270  3716 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback,
03-31 17:41:48.265  3270  3716 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-31 17:41:48.268  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
,03-31 17:41:48.268  3270  3328 I jxcore-log: 
,03-31 17:41:48.273  3270  3328 I jxcore-log: ok 119 called only once
03-31 17:41:48.273  3270  3328 I jxcore-log: 
,03-31 17:41:48.273  3270  3328 I jxcore-log: ok 120 discovery state matches
03-31 17:41:48.273  3270  3328 I jxcore-log: 
03-31 17:41:48.274  3270  3328 I jxcore-log: ok 121 advertising state matches
03-31 17:41:48.274  3270  3328 I jxcore-log: 
,03-31 17:41:48.283  3270  3328 I jxcore-log: # teardown
03-31 17:41:48.283  3270  3328 I jxcore-log: 
,03-31 17:41:48.605  3270  3328 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-31 17:41:48.605  3270  3328 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-31 17:41:48.605  3270  3328 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,03-31 17:41:48.605  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-31 17:41:48.605  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-31 17:41:48.605  3270  3328 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-31 17:41:48.605  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-31 17:41:48.605  3270  3328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-31 17:41:48.605  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-31 17:41:48.605  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-31 17:41:48.606  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-31 17:41:48.606  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-31 17:41:48.606  3270  3716 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-31 17:41:48.606  3270  3716 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-31 17:41:48.606  3270  3716 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-31 17:41:48.607  2163  2181 D BtGatt.GattService: stopScan() - queue size =1
,03-31 17:41:48.609  2163  2209 D BtGatt.GattService: unregisterClient() - clientIf=5
03-31 17:41:48.609  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 17:41:48.609  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 17:41:48.609  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-31 17:41:48.610  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-31 17:41:48.610  3270  3328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-31 17:41:48.610  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-31 17:41:48.610  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-31 17:41:48.611  2163  2207 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-31 17:41:48.611  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:41:48.612  2163  2218 D BtGatt.ScanManager: stopping BLe Batch
,03-31 17:41:48.614  2163  2207 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-31 17:41:48.614  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 17:41:48.614  2163  2217 D BtGatt.AdvertiseManager: message : 1
03-31 17:41:48.614  2163  2218 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-31 17:41:48.615  2163  2217 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-31 17:41:48.619  2163  2207 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-31 17:41:48.619  2163  2207 D BtGatt.GattService: Client app is not null!
03-31 17:41:48.620  2163  2181 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-31 17:41:48.621  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
03-31 17:41:48.621  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-31 17:41:48.621  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-31 17:41:48.621  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-31 17:41:48.621  3270  3328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,03-31 17:41:48.621  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 17:41:48.621  2163  2207 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-31 17:41:48.621  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:41:48.621  2163  2207 D BtGatt.GattService: current time is 198041149715
03-31 17:41:48.621  2163  2207 D BtGatt.GattService: Batch record : [-28, 71, 95, -29, 121, 84, 1, -128, -59, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -52, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
,03-31 17:41:48.622  2163  2207 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-31 17:41:48.622  2163  2207 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-31 17:41:48.622  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-31 17:41:48.622  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-31 17:41:48.623  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-31 17:41:48.623  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 17:41:48.623  3270  3270 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 17:41:48.623  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 17:41:48.624  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-31 17:41:48.634  3270  3270 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-31 17:41:48.634   823  1411 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 17:41:48.636  3270  3328 I jxcore-log: INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
03-31 17:41:48.636  3270  3328 I jxcore-log: 
,03-31 17:41:48.640  3270  3328 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-31 17:41:48.640  3270  3328 I jxcore-log: 
03-31 17:41:48.642  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-31 17:41:48.642  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-31 17:41:48.642  3270  3270 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-31 17:41:48.646  3270  3270 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-31 17:41:48.646  3270  3270 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-31 17:41:48.646  3270  3270 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-31 17:41:48.646  3270  3270 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 17:41:48.646  3270  3270 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 17:41:48.647  3270  3270 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 17:41:48.647  3270  3270 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 17:41:48.647  3270  3270 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-31 17:41:48.648  3270  3328 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-31 17:41:48.648  3270  3328 I jxcore-log: 
,03-31 17:41:48.651  3270  3328 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-31 17:41:48.651  3270  3328 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 17:41:48.651  3270  3328 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 17:41:48.652  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-31 17:41:48.652  3270  3328 I jxcore-log: 
,03-31 17:41:48.654  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 17:41:48.654  3270  3328 I jxcore-log: 
,03-31 17:41:48.655  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 17:41:48.655  3270  3328 I jxcore-log: 
,03-31 17:41:48.659  3270  3328 I jxcore-log: ok 122 error should be null
03-31 17:41:48.659  3270  3328 I jxcore-log: 
,03-31 17:41:48.660  3270  3328 I jxcore-log: ok 123 error should be null
03-31 17:41:48.660  3270  3328 I jxcore-log: 
,03-31 17:41:48.666  3270  3328 I jxcore-log: # setup
03-31 17:41:48.666  3270  3328 I jxcore-log: 
,03-31 17:41:48.855  3270  3328 I jxcore-log: # 32. does not send duplicate availability changes
03-31 17:41:48.855  3270  3328 I jxcore-log: 
,03-31 17:41:49.056  3270  3328 I jxcore-log: ok 124 should be called once
03-31 17:41:49.056  3270  3328 I jxcore-log: 
,03-31 17:41:49.059  3270  3328 I jxcore-log: ok 125 should not have been called more than once
03-31 17:41:49.059  3270  3328 I jxcore-log: 
,03-31 17:41:49.061  3270  3328 I jxcore-log: # teardown
,03-31 17:41:49.061  3270  3328 I jxcore-log: 
,03-31 17:41:49.213  3270  3328 I jxcore-log: ok 126 error should be null
03-31 17:41:49.213  3270  3328 I jxcore-log: 
,03-31 17:41:49.214  3270  3328 I jxcore-log: ok 127 error should be null
03-31 17:41:49.214  3270  3328 I jxcore-log: 
03-31 17:41:49.216  3270  3328 I jxcore-log: # setup
03-31 17:41:49.216  3270  3328 I jxcore-log: 
,03-31 17:41:49.346  3270  3328 I jxcore-log: # 33. can get the network status
03-31 17:41:49.346  3270  3328 I jxcore-log: 
,03-31 17:41:49.493  3270  3328 I jxcore-log: ok 128 network status should have certain non-empty properties,
03-31 17:41:49.493  3270  3328 I jxcore-log: 
,03-31 17:41:49.495  3270  3328 I jxcore-log: # teardown
03-31 17:41:49.495  3270  3328 I jxcore-log: 
,03-31 17:41:49.633  3270  3328 I jxcore-log: ok 129 error should be null,
03-31 17:41:49.633  3270  3328 I jxcore-log: 
03-31 17:41:49.634  3270  3328 I jxcore-log: ok 130 error should be null
03-31 17:41:49.634  3270  3328 I jxcore-log: 
,03-31 17:41:49.636  3270  3328 I jxcore-log: # setup
03-31 17:41:49.636  3270  3328 I jxcore-log: 
,03-31 17:41:49.758  3270  3328 I jxcore-log: # 34. wifi peer is marked unavailable if announcements stop
03-31 17:41:49.758  3270  3328 I jxcore-log: 
,03-31 17:41:49.920  3270  3328 I jxcore-log: ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined
03-31 17:41:49.920  3270  3328 I jxcore-log: 
,03-31 17:41:49.944  3270  3328 I jxcore-log: ok 131 host address should match
03-31 17:41:49.944  3270  3328 I jxcore-log: 
,03-31 17:41:49.945  3270  3328 I jxcore-log: ok 132 port should match
03-31 17:41:49.945  3270  3328 I jxcore-log: 
,03-31 17:41:51.729  1233  2542 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-31 17:41:51.729  1233  2542 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 17:41:51.729  1233  2542 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 17:41:51.729  1233  2542 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 17:41:51.734  1233  2542 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 17:41:51.767  3104  3718 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
03-31 17:41:51.767  3104  3718 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-31 17:41:51.767  3104  3718 E HttpOperation: 	at jdm.a(PG:82)
03-31 17:41:51.767  3104  3718 E HttpOperation: 	at jcs.o(PG:406)
03-31 17:41:51.767  3104  3718 E HttpOperation: 	at jcn.a(PG:1379)
03-31 17:41:51.767  3104  3718 E HttpOperation: 	at jcs.i(PG:143)
03-31 17:41:51.767  3104  3718 E HttpOperation: 	at blb.a(PG:3937)
03-31 17:41:51.767  3104  3718 E HttpOperation: 	at czp.a(PG:18188)
03-31 17:41:51.767  3104  3718 E HttpOperation: 	at czp.a(PG:9081)
03-31 17:41:51.767  3104  3718 E HttpOperation: 	at czq.run(PG:1686)
03-31 17:41:51.767  3104  3718 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-31 17:41:51.767  3104  3718 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-31 17:41:51.767  3104  3718 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 17:41:51.767  3104  3718 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 17:41:51.767  3104  3718 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-31 17:41:51.767  3104  3718 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-31 17:41:51.767  3104  3718 E HttpOperation: 	at jdj.a(PG:4091)
03-31 17:41:51.767  3104  3718 E HttpOperation: 	at jdj.a(PG:1125)
03-31 17:41:51.767  3104  3718 E HttpOperation: 	at jdm.a(PG:77)
03-31 17:41:51.767  3104  3718 E HttpOperation: 	... 12 more
03-31 17:41:51.767  3104  3718 E HttpOperation: Caused by: faj: BadAuthentication
03-31 17:41:51.767  3104  3718 E HttpOperation: 	at fal.a(PG:38)
03-31 17:41:51.767  3104  3718 E HttpOperation: 	at jdj.a(PG:4089)
03-31 17:41:51.767  3104  3718 E HttpOperation: 	... 14 more
,03-31 17:41:51.813  1233  1921 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,03-31 17:41:51.813  1233  1921 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-31 17:41:51.813  1233  1921 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 17:41:51.814  1233  1921 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 17:41:51.817  1233  1921 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 17:41:51.844  3104  3718 E HttpOperation: [getmobileexperiments] Unexpected exception
03-31 17:41:51.844  3104  3718 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-31 17:41:51.844  3104  3718 E HttpOperation: 	at jdm.a(PG:82)
03-31 17:41:51.844  3104  3718 E HttpOperation: 	at jcs.o(PG:406)
03-31 17:41:51.844  3104  3718 E HttpOperation: 	at jcn.a(PG:1379)
03-31 17:41:51.844  3104  3718 E HttpOperation: 	at jcs.i(PG:143)
03-31 17:41:51.844  3104  3718 E HttpOperation: 	at hec.a(PG:42)
03-31 17:41:51.844  3104  3718 E HttpOperation: 	at hee.a(PG:102)
03-31 17:41:51.844  3104  3718 E HttpOperation: 	at czr.a(PG:65)
03-31 17:41:51.844  3104  3718 E HttpOperation: 	at kka.a(PG:108)
03-31 17:41:51.844  3104  3718 E HttpOperation: 	at czp.a(PG:19176)
03-31 17:41:51.844  3104  3718 E HttpOperation: 	at czp.a(PG:9081)
03-31 17:41:51.844  3104  3718 E HttpOperation: 	at czq.run(PG:1686)
03-31 17:41:51.844  3104  3718 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-31 17:41:51.844  3104  3718 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-31 17:41:51.844  3104  3718 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 17:41:51.844  3104  3718 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 17:41:51.844  3104  3718 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-31 17:41:51.844  3104  3718 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-31 17:41:51.844  3104  3718 E HttpOperation: 	at jdj.a(PG:4091)
03-31 17:41:51.844  3104  3718 E HttpOperation: 	at jdj.a(PG:1125)
03-31 17:41:51.844  3104  3718 E HttpOperation: 	at jdm.a(PG:77)
03-31 17:41:51.844  3104  3718 E HttpOperation: 	... 15 more
03-31 17:41:51.844  3104  3718 E HttpOperation: Caused by: faj: BadAuthentication
03-31 17:41:51.844  3104  3718 E HttpOperation: 	at fal.a(PG:38)
03-31 17:41:51.844  3104  3718 E HttpOperation: 	at jdj.a(PG:4089)
03-31 17:41:51.844  3104  3718 E HttpOperation: 	... 17 more
03-31 17:41:51.844  3104  3718 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
03-31 17:41:51.844  3104  3718 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
03-31 17:41:51.844  3104  3718 E ExperimentLoader: 	at jdm.a(PG:82)
03-31 17:41:51.844  3104  3718 E ExperimentLoader: 	at jcs.o(PG:406)
03-31 17:41:51.844  3104  3718 E ExperimentLoader: 	at jcn.a(PG:1379)
03-31 17:41:51.844  3104  3718 E ExperimentLoader: 	at jcs.i(PG:143)
03-31 17:41:51.844  3104  3718 E ExperimentLoader: 	at hec.a(PG:42)
03-31 17:41:51.844  3104  3718 E ExperimentLoader: 	at hee.a(PG:102)
03-31 17:41:51.844  3104  3718 E ExperimentLoader: 	at czr.a(PG:65)
03-31 17:41:51.844  3104  3718 E ExperimentLoader: 	at kka.a(PG:108)
03-31 17:41:51.844  3104  3718 E ExperimentLoader: 	at czp.a(PG:19176)
03-31 17:41:51.844  3104  3718 E ExperimentLoader: 	at czp.a(PG:9081)
03-31 17:41:51.844  3104  3718 E ExperimentLoader: 	at czq.run(PG:1686)
03-31 17:41:51.844  3104  3718 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-31 17:41:51.844  3104  3718 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-31 17:41:51.844  3104  3718 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 17:41:51.844  3104  3718 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 17:41:51.844  3104  3718 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
03-31 17:41:51.844  3104  3718 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-31 17:41:51.844  3104  3718 E ExperimentLoader: 	at jdj.a(PG:4091)
03-31 17:41:51.844  3104  3718 E ExperimentLoader: 	at jdj.a(PG:1,125)
03-31 17:41:51.844  3104  3718 E ExperimentLoader: 	at jdm.a(PG:77)
03-31 17:41:51.844  3104  3718 E ExperimentLoader: 	... 15 more
03-31 17:41:51.844  3104  3718 E ExperimentLoader: Caused by: faj: BadAuthentication
03-31 17:41:51.844  3104  3718 E ExperimentLoader: 	at fal.a(PG:38)
03-31 17:41:51.844  3104  3718 E ExperimentLoader: 	at jdj.a(PG:4089)
03-31 17:41:51.844  3104  3718 E ExperimentLoader: 	... 17 more
,03-31 17:41:51.926  3270  3328 I jxcore-log: ok 133 host address should be null
03-31 17:41:51.926  3270  3328 I jxcore-log: 
,03-31 17:41:51.927  3270  3328 I jxcore-log: ok 134 port should should be null
03-31 17:41:51.927  3270  3328 I jxcore-log: 
,03-31 17:41:51.944  3270  3328 I jxcore-log: # teardown
03-31 17:41:51.944  3270  3328 I jxcore-log: 
,03-31 17:41:51.976   823   856 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 200870, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,03-31 17:41:52.055  3270  3328 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-31 17:41:52.055  3270  3328 I jxcore-log: 
,03-31 17:41:52.061  3270  3328 I jxcore-log: ok 135 error should be null
03-31 17:41:52.061  3270  3328 I jxcore-log: 
,03-31 17:41:52.061  3270  3328 I jxcore-log: ok 136 error should be null
03-31 17:41:52.061  3270  3328 I jxcore-log: 
03-31 17:41:52.063  3270  3328 I jxcore-log: # setup
03-31 17:41:52.063  3270  3328 I jxcore-log: 
,03-31 17:41:52.173  3270  3328 I jxcore-log: # 35. Can call start/stopListeningForAdvertisements
03-31 17:41:52.173  3270  3328 I jxcore-log: 
,03-31 17:41:52.323  3270  3328 I io.jxcore.node.ConnectionHelper: start: Port number: 58613, start advertisements: false
,03-31 17:41:52.323  3270  3328 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 17:41:52.324  3270  3328 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-31 17:41:52.324  3270  3328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-31 17:41:52.328  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-31 17:41:52.329  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-31 17:41:52.329  3270  3328 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 17:41:52.335  2163  2209 D BtGatt.GattService: registerClient() - UUID=fa114ed0-285c-4e62-bbeb-41a17fce1099
,03-31 17:41:52.335  2163  2207 D BtGatt.GattService: onClientRegistered() - UUID=fa114ed0-285c-4e62-bbeb-41a17fce1099, clientIf=5
03-31 17:41:52.336  3270  3288 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-31 17:41:52.336  2163  2183 D BtGatt.GattService: start scan with filters
,03-31 17:41:52.338  2163  2218 D BtGatt.ScanManager: handling starting scan
03-31 17:41:52.338  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-31 17:41:52.338  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 17:41:52.339  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-31 17:41:52.339  3270  3328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-31 17:41:52.339  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 17:41:52.339  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-31 17:41:52.339  3270  3270 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-31 17:41:52.340   823  1411 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 17:41:52.345  2163  2207 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-31 17:41:52.345  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 17:41:52.346  2163  2207 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-31 17:41:52.346  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:41:52.346  2163  2218 D BtGatt.ScanManager: Starting BLE batch scan
03-31 17:41:52.347  2163  2218 D BtGatt.ScanManager: configuring batch scan storage, appIf 5,
03-31 17:41:52.349  2163  2207 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,03-31 17:41:52.349  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:41:52.350  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-31 17:41:52.351  3270  3328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-31 17:41:52.351  2163  2207 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-31 17:41:52.351  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:41:52.351  3270  3270 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-31 17:41:52.351  3270  3328 I io.jxcore.node.ConnectionHelper: start: OK
03-31 17:41:52.351  3270  3270 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 17:41:52.352  3270  3270 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-31 17:41:52.358  3270  3328 I jxcore-log: ok 137 Can call startListeningForAdvertisements without error
03-31 17:41:52.358  3270  3328 I jxcore-log: 
,03-31 17:41:52.360  3270  3328 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-31 17:41:52.360  3270  3328 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 17:41:52.360  3270  3328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-31 17:41:52.360  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-31 17:41:52.363  2163  2209 D BtGatt.GattService: stopScan() - queue size =1
,03-31 17:41:52.366  2163  2207 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,03-31 17:41:52.366  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:41:52.366  2163  2218 D BtGatt.ScanManager: stopping BLe Batch
03-31 17:41:52.366  2163  2183 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-31 17:41:52.368  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
03-31 17:41:52.368  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 17:41:52.368  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-31 17:41:52.368  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-31 17:41:52.368  3270  3328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-31 17:41:52.368  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 17:41:52.369  3270  3270 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 17:41:52.369  3270  3270 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 17:41:52.369  3270  3270 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-31 17:41:52.369  2163  2207 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-31 17:41:52.369  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:41:52.369  2163  2218 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-31 17:41:52.371  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 17:41:52.371  3270  3328 I jxcore-log: 
03-31 17:41:52.372  2163  2207 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-31 17:41:52.372  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:41:52.372  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 17:41:52.372  3270  3328 I jxcore-log: 
,03-31 17:41:52.374  3270  3328 I jxcore-log: ok 138 Can call stopListeningForAdvertisements without error
03-31 17:41:52.374  3270  3328 I jxcore-log: 
03-31 17:41:52.379  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 17:41:52.379  3270  3328 I jxcore-log: 
03-31 17:41:52.381  3270  3328 I jxcore-log: # teardown
03-31 17:41:52.381  3270  3328 I jxcore-log: 
,03-31 17:41:52.569  3270  3328 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-31 17:41:52.569  3270  3328 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 17:41:52.569  3270  3328 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 17:41:52.576  3270  3328 I jxcore-log: ok 139 Should be able to call stopListeningForAdvertisments in teardown
03-31 17:41:52.576  3270  3328 I jxcore-log: 
,03-31 17:41:52.578  3270  3328 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections,
,03-31 17:41:52.579  3270  3328 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
03-31 17:41:52.579  3270  3328 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
03-31 17:41:52.579  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-31 17:41:52.579  3270  3328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,03-31 17:41:52.579  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-31 17:41:52.579  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-31 17:41:52.581  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-31 17:41:52.582  3270  3328 D BluetoothLeScanner: could not find callback wrapper
03-31 17:41:52.582  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-31 17:41:52.583  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-31 17:41:52.583  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-31 17:41:52.583  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-31 17:41:52.584  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-31 17:41:52.584  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 17:41:52.584  3270  3270 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-31 17:41:52.585  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 17:41:52.585  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-31 17:41:52.594  3270  3270 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
03-31 17:41:52.595   823  1410 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 17:41:52.607  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
,03-31 17:41:52.608  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-31 17:41:52.609  3270  3270 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-31 17:41:52.615  3270  3270 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-31 17:41:52.615  3270  3270 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 17:41:52.616  3270  3270 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-31 17:41:52.618  3270  3328 I jxcore-log: ok 140 Should be able to call stopAdvertisingAndListening in teardown
,03-31 17:41:52.618  3270  3328 I jxcore-log: 
,03-31 17:41:52.635  3270  3328 I jxcore-log: # setup
03-31 17:41:52.635  3270  3328 I jxcore-log: 
,03-31 17:41:52.639  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 17:41:52.639  3270  3328 I jxcore-log: 
,03-31 17:41:52.748  3270  3328 I jxcore-log: # 36. Calling startListeningForAdvertisements twice is NOT an error
03-31 17:41:52.748  3270  3328 I jxcore-log: 
,03-31 17:41:52.858  3270  3328 I io.jxcore.node.ConnectionHelper: start: Port number: 58613, start advertisements: false
,03-31 17:41:52.859  3270  3328 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 17:41:52.859  3270  3328 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-31 17:41:52.859  3270  3328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-31 17:41:52.868  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-31 17:41:52.868  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 17:41:52.868  3270  3328 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 17:41:52.878  2163  2958 D BtGatt.GattService: registerClient() - UUID=6bdfbdd0-f424-4ddc-9403-9d93b21f8f62
,03-31 17:41:52.879  2163  2207 D BtGatt.GattService: onClientRegistered() - UUID=6bdfbdd0-f424-4ddc-9403-9d93b21f8f62, clientIf=5
03-31 17:41:52.880  3270  3288 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-31 17:41:52.881  2163  2209 D BtGatt.GattService: start scan with filters
,03-31 17:41:52.883  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-31 17:41:52.883  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-31 17:41:52.883  2163  2218 D BtGatt.ScanManager: handling starting scan,
03-31 17:41:52.883  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,03-31 17:41:52.883  3270  3328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,03-31 17:41:52.884  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
,03-31 17:41:52.885  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-31 17:41:52.885  3270  3270 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-31 17:41:52.886   823  1093 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-31 17:41:52.888  2163  2207 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-31 17:41:52.888  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:41:52.891  2163  2207 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-31 17:41:52.891  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
03-31 17:41:52.892  2163  2218 D BtGatt.ScanManager: Starting BLE batch scan
03-31 17:41:52.892  2163  2218 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-31 17:41:52.895  2163  2207 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-31 17:41:52.896  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 17:41:52.898  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 17:41:52.898  3270  3328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-31 17:41:52.899  2163  2207 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-31 17:41:52.899  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:41:52.899  3270  3328 I io.jxcore.node.ConnectionHelper: start: OK
,03-31 17:41:52.899  3270  3270 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-31 17:41:52.900  3270  3270 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-31 17:41:52.900  3270  3270 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 17:41:52.904  3270  3328 I jxcore-log: ok 141 Can call startListeningForAdvertisements without error
03-31 17:41:52.904  3270  3328 I jxcore-log: 
,03-31 17:41:52.912  3270  3328 I io.jxcore.node.ConnectionHelper: start: Port number: 58613, start advertisements: false
03-31 17:41:52.912  3270  3328 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-31 17:41:52.912  3270  3328 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-31 17:41:52.912  3270  3328 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
03-31 17:41:52.912  3270  3328 I io.jxcore.node.ConnectionHelper: start: OK
03-31 17:41:52.915  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 17:41:52.915  3270  3328 I jxcore-log: 
03-31 17:41:52.917  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 17:41:52.917  3270  3328 I jxcore-log: 
,03-31 17:41:52.921  3270  3328 I jxcore-log: ok 142 Can call startListeningForAdvertisements twice without error
03-31 17:41:52.921  3270  3328 I jxcore-log: 
,03-31 17:41:52.936  3270  3328 I jxcore-log: # teardown
03-31 17:41:52.936  3270  3328 I jxcore-log: 
,03-31 17:41:53.136  3270  3328 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-31 17:41:53.136  3270  3328 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-31 17:41:53.136  3270  3328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-31 17:41:53.137  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-31 17:41:53.141  2163  2181 D BtGatt.GattService: stopScan() - queue size =1
,03-31 17:41:53.144  2163  2207 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-31 17:41:53.144  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:41:53.144  2163  2958 D BtGatt.GattService: unregisterClient() - clientIf=5
03-31 17:41:53.145  2163  2218 D BtGatt.ScanManager: stopping BLe Batch
03-31 17:41:53.145  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 17:41:53.145  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 17:41:53.146  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-31 17:41:53.146  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED],
03-31 17:41:53.146  3270  3328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-31 17:41:53.146  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 17:41:53.146  3270  3270 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 17:41:53.147  3270  3270 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-31 17:41:53.147  3270  3270 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 17:41:53.149  2163  2207 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-31 17:41:53.150  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:41:53.150  2163  2218 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-31 17:41:53.151  3270  3328 I jxcore-log: ok 143 Should be able to call stopListeningForAdvertisments in teardown
03-31 17:41:53.151  3270  3328 I jxcore-log: 
,03-31 17:41:53.152  2163  2207 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,03-31 17:41:53.153  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:41:53.154  3270  3328 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-31 17:41:53.154  3270  3328 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 17:41:53.154  3270  3328 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
03-31 17:41:53.154  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-31 17:41:53.154  3270  3328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-31 17:41:53.154  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-31 17:41:53.154  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-31 17:41:53.155  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-31 17:41:53.157  3270  3328 D BluetoothLeScanner: could not find callback wrapper
03-31 17:41:53.157  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-31 17:41:53.159  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-31 17:41:53.159  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,03-31 17:41:53.159  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-31 17:41:53.161  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-31 17:41:53.161  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 17:41:53.161  3270  3270 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 17:41:53.161  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 17:41:53.161  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-31 17:41:53.164  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 17:41:53.164  3270  3328 I jxcore-log: 
,03-31 17:41:53.173  3270  3270 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
03-31 17:41:53.173   823  1411 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 17:41:53.182  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-31 17:41:53.184  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-31 17:41:53.185  3270  3270 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-31 17:41:53.189  3270  3270 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-31 17:41:53.189  3270  3270 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 17:41:53.190  3270  3270 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 17:41:53.191  3270  3328 I jxcore-log: ok 144 Should be able to call stopAdvertisingAndListening in teardown
03-31 17:41:53.191  3270  3328 I jxcore-log: 
,03-31 17:41:53.197  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 17:41:53.197  3270  3328 I jxcore-log: 
,03-31 17:41:53.198  3270  3328 I jxcore-log: # setup
03-31 17:41:53.198  3270  3328 I jxcore-log: 
,03-31 17:41:53.333  3270  3328 I jxcore-log: # 37. Can call start/stopUpdateAdvertisingAndListening
,03-31 17:41:53.333  3270  3328 I jxcore-log: 
,03-31 17:41:53.465  3270  3328 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: true
,03-31 17:41:53.465  3270  3328 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 17:41:53.465  3270  3328 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-31 17:41:53.465  3270  3328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-31 17:41:53.475  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-31 17:41:53.475  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-31 17:41:53.475  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-31 17:41:53.476  3270  3328 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 17:41:53.485  2163  2183 D BtGatt.GattService: registerClient() - UUID=ad686e66-a55a-4939-a7d6-62bd81fab264
,03-31 17:41:53.486  2163  2207 D BtGatt.GattService: onClientRegistered() - UUID=ad686e66-a55a-4939-a7d6-62bd81fab264, clientIf=5
03-31 17:41:53.487  3270  3288 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-31 17:41:53.488  2163  2181 D BtGatt.GattService: start scan with filters
,03-31 17:41:53.489  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
,03-31 17:41:53.489  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true,
03-31 17:41:53.490  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING],
03-31 17:41:53.490  3270  3328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-31 17:41:53.490  2163  2218 D BtGatt.ScanManager: handling starting scan
,03-31 17:41:53.490  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 17:41:53.491  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-31 17:41:53.491  3270  3270 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 17:41:53.491  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,03-31 17:41:53.491  3270  3328 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-31 17:41:53.492  3270  3328 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 17:41:53.492  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-31 17:41:53.492  3270  3328 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-31 17:41:53.501  2163  2207 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-31 17:41:53.501  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:41:53.504  2163  2207 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-31 17:41:53.504  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:41:53.504  2163  2218 D BtGatt.ScanManager: Starting BLE batch scan
03-31 17:41:53.504  2163  2218 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-31 17:41:53.505  2163  2181 D BtGatt.GattService: registerClient() - UUID=cf2054f4-4886-4960-9b31-bc88009100f7,
03-31 17:41:53.506  2163  2207 D BtGatt.GattService: onClientRegistered() - UUID=cf2054f4-4886-4960-9b31-bc88009100f7, clientIf=6
,03-31 17:41:53.507  3270  3287 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-31 17:41:53.510  2163  2207 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,03-31 17:41:53.510  2163  2217 D BtGatt.AdvertiseManager: message : 0
03-31 17:41:53.510  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 17:41:53.513  2163  2207 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-31 17:41:53.513  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:41:53.516  2163  2217 D BtGatt.AdvertiseManager: starting multi advertising,
,03-31 17:41:53.519  2163  2207 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-31 17:41:53.521  2163  2207 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-31 17:41:53.522  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-31 17:41:53.522  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-31 17:41:53.523   823  1411 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 17:41:53.529  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-31 17:41:53.529  3270  3328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-31 17:41:53.529  3270  3328 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-31 17:41:53.529  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-31 17:41:53.531  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-31 17:41:53.531  3270  3328 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-31 17:41:53.531  3270  3328 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-31 17:41:53.531  3270  3328 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-31 17:41:53.532  3270  3328 I io.jxcore.node.ConnectionHelper: start: OK
03-31 17:41:53.532  3270  3270 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-31 17:41:53.532  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-31 17:41:53.532  3270  3270 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-31 17:41:53.532  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-31 17:41:53.532  3270  3270 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-31 17:41:53.532  3270  3270 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-31 17:41:53.532  3270  3270 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-31 17:41:53.532  3270  3270 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 17:41:53.532  3270  3270 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-31 17:41:53.532  3270  3270 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 17:41:53.533  3270  3270 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-31 17:41:53.533   823  1393 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-31 17:41:53.533  3270  3270 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-31 17:41:53.535  3270  3721 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-31 17:41:53.538  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 17:41:53.538  3270  3328 I jxcore-log: 
,03-31 17:41:53.539  3270  3721 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-31 17:41:53.540  3270  3328 I jxcore-log: ok 145 Can call startUpdateAdvertisingAndListening without error
,03-31 17:41:53.540  3270  3328 I jxcore-log: 
03-31 17:41:53.541  3270  3328 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 17:41:53.541  3270  3328 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-31 17:41:53.541  3270  3328 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-31 17:41:53.541  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,03-31 17:41:53.541  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-31 17:41:53.542  3270  3328 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-31 17:41:53.542  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-31 17:41:53.542  3270  3328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,03-31 17:41:53.542  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-31 17:41:53.542  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,03-31 17:41:53.542  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-31 17:41:53.542  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-31 17:41:53.544  2163  2183 D BtGatt.GattService: stopScan() - queue size =1
,03-31 17:41:53.546  2163  2181 D BtGatt.GattService: unregisterClient() - clientIf=5
03-31 17:41:53.546  3270  3721 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
,03-31 17:41:53.546  3270  3721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,03-31 17:41:53.546  3270  3721 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-31 17:41:53.546  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 17:41:53.546  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 17:41:53.546  2163  2207 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-31 17:41:53.546  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-31 17:41:53.546  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 17:41:53.546  2163  2218 D BtGatt.ScanManager: stopping BLe Batch
03-31 17:41:53.547  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-31 17:41:53.547  3270  3328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-31 17:41:53.547  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-31 17:41:53.547  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-31 17:41:53.548  2163  2217 D BtGatt.AdvertiseManager: message : 1
03-31 17:41:53.549  2163  2217 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-31 17:41:53.550  2163  2207 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-31 17:41:53.550  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
03-31 17:41:53.550  2163  2218 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-31 17:41:53.551  2163  2207 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
03-31 17:41:53.551  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:41:53.553  2163  2207 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,03-31 17:41:53.553  2163  2207 D BtGatt.GattService: Client app is not null!
03-31 17:41:53.553  2163  2183 D BtGatt.GattService: unregisterClient() - clientIf=6
03-31 17:41:53.554  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-31 17:41:53.554  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-31 17:41:53.554  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,03-31 17:41:53.554  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-31 17:41:53.554  3270  3328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-31 17:41:53.554  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 17:41:53.554  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,03-31 17:41:53.554  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-31 17:41:53.555  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-31 17:41:53.555  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 17:41:53.555  3270  3270 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 17:41:53.555  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 17:41:53.555  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-31 17:41:53.560  3270  3270 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-31 17:41:53.560  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 17:41:53.560  3270  3328 I jxcore-log: 
03-31 17:41:53.560   823  1370 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-31 17:41:53.562  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-31 17:41:53.562  3270  3328 I jxcore-log: 
,03-31 17:41:53.565  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-31 17:41:53.566  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-31 17:41:53.566  3270  3270 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-31 17:41:53.569  3270  3270 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-31 17:41:53.569  3270  3270 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-31 17:41:53.569  3270  3270 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-31 17:41:53.569  3270  3270 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 17:41:53.569  3270  3270 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 17:41:53.569  3270  3270 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 17:41:53.570  3270  3270 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-31 17:41:53.570  3270  3270 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-31 17:41:53.571  3270  3328 I jxcore-log: ok 146 Can call stopAdvertisingAndListening without error
03-31 17:41:53.571  3270  3328 I jxcore-log: 
,03-31 17:41:53.577  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-31 17:41:53.577  3270  3328 I jxcore-log: 
,03-31 17:41:53.578  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 17:41:53.578  3270  3328 I jxcore-log: 
03-31 17:41:53.579  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 17:41:53.579  3270  3328 I jxcore-log: 
,03-31 17:41:53.580  3270  3328 I jxcore-log: # teardown
03-31 17:41:53.580  3270  3328 I jxcore-log: 
,03-31 17:41:53.864  3270  3328 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-31 17:41:53.864  3270  3328 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 17:41:53.864  3270  3328 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 17:41:53.869  3270  3328 I jxcore-log: ok 147 Should be able to call stopListeningForAdvertisments in teardown
03-31 17:41:53.869  3270  3328 I jxcore-log: 
,03-31 17:41:53.873  3270  3328 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-31 17:41:53.873  3270  3328 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 17:41:53.873  3270  3328 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-31 17:41:53.877  3270  3328 I jxcore-log: ok 148 Should be able to call stopAdvertisingAndListening in teardown
03-31 17:41:53.877  3270  3328 I jxcore-log: 
,03-31 17:41:53.892  3270  3328 I jxcore-log: # setup
03-31 17:41:53.892  3270  3328 I jxcore-log: ,
,03-31 17:41:53.975  3270  3328 I jxcore-log: # 38. Calling startUpdateAdvertisingAndListening twice is NOT an error
03-31 17:41:53.975  3270  3328 I jxcore-log: 
,03-31 17:41:54.084  3270  3328 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: true
,03-31 17:41:54.085  3270  3328 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 17:41:54.085  3270  3328 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-31 17:41:54.085  3270  3328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-31 17:41:54.094  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
03-31 17:41:54.094  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-31 17:41:54.094  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 17:41:54.094  3270  3328 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 17:41:54.099  2163  2183 D BtGatt.GattService: registerClient() - UUID=2e2efe33-3793-449a-89d1-6c4c855611f4
,03-31 17:41:54.100  2163  2207 D BtGatt.GattService: onClientRegistered() - UUID=2e2efe33-3793-449a-89d1-6c4c855611f4, clientIf=5
03-31 17:41:54.101  3270  3287 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-31 17:41:54.101  2163  2181 D BtGatt.GattService: start scan with filters
03-31 17:41:54.102  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-31 17:41:54.102  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-31 17:41:54.102  2163  2218 D BtGatt.ScanManager: handling starting scan
03-31 17:41:54.103  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-31 17:41:54.103  3270  3328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-31 17:41:54.103  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 17:41:54.103  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-31 17:41:54.103  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-31 17:41:54.103  3270  3328 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-31 17:41:54.103  3270  3270 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 17:41:54.103  3270  3328 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 17:41:54.103  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 17:41:54.103  3270  3328 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-31 17:41:54.108  2163  2207 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1,
,03-31 17:41:54.109  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
03-31 17:41:54.111  2163  2207 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-31 17:41:54.111  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:41:54.111  2163  2218 D BtGatt.ScanManager: Starting BLE batch scan
03-31 17:41:54.111  2163  2218 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-31 17:41:54.112  2163  2958 D BtGatt.GattService: registerClient() - UUID=7267d943-b2eb-4beb-b617-c354399c9109
03-31 17:41:54.113  2163  2207 D BtGatt.GattService: onClientRegistered() - UUID=7267d943-b2eb-4beb-b617-c354399c9109, clientIf=6
03-31 17:41:54.114  3270  3288 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-31 17:41:54.114  2163  2207 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0,
03-31 17:41:54.115  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 17:41:54.117  2163  2217 D BtGatt.AdvertiseManager: message : 0
03-31 17:41:54.117  2163  2207 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-31 17:41:54.117  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 17:41:54.122  2163  2217 D BtGatt.AdvertiseManager: starting multi advertising
,03-31 17:41:54.126  2163  2207 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-31 17:41:54.130  2163  2207 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0,
,03-31 17:41:54.131  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING,
03-31 17:41:54.131  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-31 17:41:54.132   823  1149 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 17:41:54.137  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
03-31 17:41:54.137  3270  3328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-31 17:41:54.137  3270  3328 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,03-31 17:41:54.138  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 17:41:54.139  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-31 17:41:54.139  3270  3328 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,03-31 17:41:54.139  3270  3328 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-31 17:41:54.139  3270  3328 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-31 17:41:54.140  3270  3328 I io.jxcore.node.ConnectionHelper: start: OK
03-31 17:41:54.140  3270  3270 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,03-31 17:41:54.141  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-31 17:41:54.141  3270  3270 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-31 17:41:54.141  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-31 17:41:54.141  3270  3270 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-31 17:41:54.142  3270  3270 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-31 17:41:54.142  3270  3270 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-31 17:41:54.143   823  1370 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-31 17:41:54.143  3270  3270 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 17:41:54.143  3270  3270 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-31 17:41:54.143  3270  3270 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 17:41:54.143  3270  3270 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,03-31 17:41:54.144  3270  3270 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-31 17:41:54.144  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 17:41:54.144  3270  3328 I jxcore-log: 
03-31 17:41:54.146  3270  3722 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-31 17:41:54.150  3270  3722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-31 17:41:54.150  3270  3328 I jxcore-log: ok 149 Can call startUpdateAdvertisingAndListening without error
03-31 17:41:54.150  3270  3328 I jxcore-log: 
,03-31 17:41:54.164  3270  3328 I io.jxcore.node.ConnectionHelper: start: Port number: 4243, start advertisements: true
03-31 17:41:54.164  3270  3328 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 17:41:54.164  3270  3328 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-31 17:41:54.164  3270  3328 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 17:41:54.165  3270  3328 I io.jxcore.node.ConnectionHelper: start: OK
,03-31 17:41:54.168  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 17:41:54.168  3270  3328 I jxcore-log: 
,03-31 17:41:54.174  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-31 17:41:54.174  3270  3328 I jxcore-log: 
,03-31 17:41:54.178  3270  3328 I jxcore-log: ok 150 Can call startUpdateAdvertisingAndListening twice without error
03-31 17:41:54.178  3270  3328 I jxcore-log: 
,03-31 17:41:54.192  3270  3328 I jxcore-log: # teardown
03-31 17:41:54.192  3270  3328 I jxcore-log: 
,03-31 17:41:54.620  2163  2163 D BtGatt.ScanManager: awakened up at time 204039
,03-31 17:41:54.621  2163  2218 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5,
,03-31 17:41:54.674  3270  3328 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-31 17:41:54.674  3270  3328 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
03-31 17:41:54.675  3270  3328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-31 17:41:54.675  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-31 17:41:54.679   823  1393 I art     : Explicit concurrent mark sweep GC freed 26511(1236KB) AllocSpace objects, 3(236KB) LOS objects, 31% free, 34MB/50MB, paused 1.333ms total 55.027ms
03-31 17:41:54.680  2163  2183 D BtGatt.GattService: stopScan() - queue size =1
03-31 17:41:54.682  2163  2207 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-31 17:41:54.682  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:41:54.682  2163  2183 D BtGatt.GattService: unregisterClient() - clientIf=5
03-31 17:41:54.682  2163  2207 D BtGatt.GattService: current time is 204101694348
03-31 17:41:54.682  2163  2207 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -64, 4, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0, -28, 80, -7, -51, -93, 103, 1, -128, -80, 5, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,03-31 17:41:54.682  2163  2207 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-31 17:41:54.682  2163  2207 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-31 17:41:54.682  2163  2207 E BtGatt.ContextMap: Context not found for ID 5
,03-31 17:41:54.683  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 17:41:54.683  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 17:41:54.683  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-31 17:41:54.683  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-31 17:41:54.684  3270  3328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
,03-31 17:41:54.685  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-31 17:41:54.685  3270  3270 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-31 17:41:54.685  3270  3270 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
03-31 17:41:54.685  3270  3270 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-31 17:41:54.688  3270  3328 I jxcore-log: ok 151 Should be able to call stopListeningForAdvertisments in teardown
03-31 17:41:54.688  3270  3328 I jxcore-log: 
,03-31 17:41:54.689  2163  2207 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,03-31 17:41:54.689  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:41:54.689  2163  2218 D BtGatt.ScanManager: stopping BLe Batch
,03-31 17:41:54.691  3270  3328 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 17:41:54.691  3270  3328 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
03-31 17:41:54.691  3270  3328 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,03-31 17:41:54.691  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-31 17:41:54.691  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-31 17:41:54.691  2163  2207 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-31 17:41:54.691  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:41:54.691  2163  2218 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-31 17:41:54.692  3270  3328 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-31 17:41:54.692  3270  3722 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-31 17:41:54.692  3270  3722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-31 17:41:54.692  3270  3722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-31 17:41:54.692  3270  3270 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-31 17:41:54.692  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-31 17:41:54.692  3270  3328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-31 17:41:54.692  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-31 17:41:54.692  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-31 17:41:54.692  2163  2207 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-31 17:41:54.692  3270  3270 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,03-31 17:41:54.692  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:41:54.692  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-31 17:41:54.693  3270  3328 D BluetoothLeScanner: could not find callback wrapper
03-31 17:41:54.693  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 17:41:54.693  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...,
,03-31 17:41:54.699  2163  2217 D BtGatt.AdvertiseManager: message : 1
,03-31 17:41:54.700  2163  2217 D BtGatt.AdvertiseManager: stop advertise for client 6,
,03-31 17:41:54.704  2163  2207 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0,
03-31 17:41:54.704  2163  2207 D BtGatt.GattService: Client app is not null!
,03-31 17:41:54.705  2163  2209 D BtGatt.GattService: unregisterClient() - clientIf=6,
03-31 17:41:54.705  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-31 17:41:54.705  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-31 17:41:54.705  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-31 17:41:54.705  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,03-31 17:41:54.706  3270  3328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-31 17:41:54.706  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 17:41:54.706  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-31 17:41:54.706  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-31 17:41:54.711  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-31 17:41:54.711  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,03-31 17:41:54.712  3270  3270 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 17:41:54.712  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 17:41:54.712  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-31 17:41:54.712  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-31 17:41:54.712  3270  3328 I jxcore-log: 
,03-31 17:41:54.715  3270  3270 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-31 17:41:54.715   823  1409 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 17:41:54.718  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-31 17:41:54.719  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-31 17:41:54.719  3270  3270 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-31 17:41:54.722  3270  3270 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-31 17:41:54.722  3270  3270 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 17:41:54.722  3270  3270 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 17:41:54.722  3270  3270 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 17:41:54.723  3270  3270 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-31 17:41:54.723  3270  3328 I jxcore-log: ok 152 Should be able to call stopAdvertisingAndListening in teardown
03-31 17:41:54.723  3270  3328 I jxcore-log: 
,03-31 17:41:54.728  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 17:41:54.728  3270  3328 I jxcore-log: 
,03-31 17:41:54.730  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 17:41:54.730  3270  3328 I jxcore-log: 
,03-31 17:41:54.731  3270  3328 I jxcore-log: # setup
03-31 17:41:54.731  3270  3328 I jxcore-log: 
,03-31 17:41:54.838  3270  3328 I jxcore-log: # 39. peerAvailabilityChange is called
03-31 17:41:54.838  3270  3328 I jxcore-log: 
,03-31 17:41:54.940  3270  3328 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: true
03-31 17:41:54.941  3270  3328 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-31 17:41:54.941  3270  3328 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-31 17:41:54.941  3270  3328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-31 17:41:54.949  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
03-31 17:41:54.949  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-31 17:41:54.950  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 17:41:54.950  3270  3328 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 17:41:54.960  2163  2209 D BtGatt.GattService: registerClient() - UUID=8c6de18f-8851-4a32-b088-9eb1fd191f74
,03-31 17:41:54.961  2163  2207 D BtGatt.GattService: onClientRegistered() - UUID=8c6de18f-8851-4a32-b088-9eb1fd191f74, clientIf=5
03-31 17:41:54.962  3270  3287 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-31 17:41:54.963  2163  2183 D BtGatt.GattService: start scan with filters
,03-31 17:41:54.965  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-31 17:41:54.965  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 17:41:54.965  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-31 17:41:54.966  3270  3328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-31 17:41:54.966  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
,03-31 17:41:54.966  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-31 17:41:54.966  3270  3270 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 17:41:54.966  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-31 17:41:54.967  3270  3328 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
,03-31 17:41:54.967  3270  3328 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 17:41:54.967  2163  2218 D BtGatt.ScanManager: handling starting scan
03-31 17:41:54.967  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 17:41:54.967  3270  3328 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-31 17:41:54.974  2163  2207 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,03-31 17:41:54.974  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:41:54.977  2163  2207 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-31 17:41:54.977  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:41:54.978  2163  2218 D BtGatt.ScanManager: Starting BLE batch scan
,03-31 17:41:54.978  2163  2218 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-31 17:41:54.983  2163  2207 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-31 17:41:54.983  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 17:41:54.986  2163  2207 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1,
03-31 17:41:54.986  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:41:54.987  2163  2183 D BtGatt.GattService: registerClient() - UUID=fbfaad83-325a-4359-8e93-66f53f9b3855
03-31 17:41:54.988  2163  2207 D BtGatt.GattService: onClientRegistered() - UUID=fbfaad83-325a-4359-8e93-66f53f9b3855, clientIf=6
03-31 17:41:54.989  3270  3288 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-31 17:41:54.993  2163  2217 D BtGatt.AdvertiseManager: message : 0
,03-31 17:41:54.998  2163  2217 D BtGatt.AdvertiseManager: starting multi advertising
,03-31 17:41:55.002  2163  2207 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-31 17:41:55.005  2163  2207 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-31 17:41:55.006  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-31 17:41:55.006  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-31 17:41:55.006   823   841 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 17:41:55.014  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-31 17:41:55.014  3270  3328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-31 17:41:55.014  3270  3328 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-31 17:41:55.014  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-31 17:41:55.016  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-31 17:41:55.016  3270  3328 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-31 17:41:55.016  3270  3328 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-31 17:41:55.016  3270  3328 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,03-31 17:41:55.017  3270  3270 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-31 17:41:55.017  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-31 17:41:55.017  3270  3270 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-31 17:41:55.017  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-31 17:41:55.017  3270  3270 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-31 17:41:55.017  3270  3270 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-31 17:41:55.017  3270  3270 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-31 17:41:55.017  3270  3270 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 17:41:55.018  3270  3270 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-31 17:41:55.018  3270  3270 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-31 17:41:55.018  3270  3270 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-31 17:41:55.018  3270  3270 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-31 17:41:55.018  3270  3328 I io.jxcore.node.ConnectionHelper: start: OK
03-31 17:41:55.021   823  1410 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 17:41:55.023  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false},
03-31 17:41:55.023  3270  3328 I jxcore-log: 
03-31 17:41:55.024  3270  3725 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-31 17:41:55.024  3270  3328 I jxcore-log: ok 153 Can call startUpdateAdvertisingAndListeningwithout error
03-31 17:41:55.024  3270  3328 I jxcore-log: 
,03-31 17:41:55.028  3270  3328 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: false,
03-31 17:41:55.028  3270  3328 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 17:41:55.028  3270  3328 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should affect listening to advertisements only
03-31 17:41:55.028  3270  3328 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-31 17:41:55.029  3270  3328 I io.jxcore.node.ConnectionHelper: start: OK
03-31 17:41:55.029  3270  3725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
03-31 17:41:55.030  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 17:41:55.030  3270  3328 I jxcore-log: 
,03-31 17:41:55.031  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-31 17:41:55.031  3270  3328 I jxcore-log: 
,03-31 17:41:55.033  3270  3328 I jxcore-log: ok 154 Can call startListeningForAdvertisements without error
03-31 17:41:55.033  3270  3328 I jxcore-log: 
,03-31 17:41:55.699  2163  2163 D BtGatt.ScanManager: awakened up at time 205118
03-31 17:41:55.701  2163  2218 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-31 17:41:55.711  2163  2207 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-31 17:41:55.711  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:41:55.712  2163  2207 D BtGatt.GattService: current time is 205131734764
,03-31 17:41:55.712  2163  2207 D BtGatt.GattService: Batch record : [12, -114, -64, -79, -107, 123, 1, -128, -81, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -59, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-31 17:41:55.713  2163  2207 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81],
03-31 17:41:55.714  2163  2207 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64],
,03-31 17:41:55.724  3270  3270 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> E0:DB:10:14:E2:C0], added - the peer count is 1
,03-31 17:41:55.725  3270  3270 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 2
03-31 17:41:55.726  3270  3270 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> E0:DB:10:14:E2:C0], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 
,03-31 17:41:55.727  3270  3270 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
,03-31 17:41:55.732  3270  3328 I jxcore-log: ok 155 peers must be an array
03-31 17:41:55.732  3270  3328 I jxcore-log: 
,03-31 17:41:55.734  3270  3328 I jxcore-log: ok 156 peers must not be zero-length
03-31 17:41:55.734  3270  3328 I jxcore-log: 
,03-31 17:41:55.735  3270  3328 I jxcore-log: ok 157 peer must have peerIdentifier
03-31 17:41:55.735  3270  3328 I jxcore-log: 
,03-31 17:41:55.737  3270  3328 I jxcore-log: ok 158 peerIdentifier must be a string
03-31 17:41:55.737  3270  3328 I jxcore-log: 
03-31 17:41:55.738  3270  3328 I jxcore-log: ok 159 peer must have peerAvailable
03-31 17:41:55.738  3270  3328 I jxcore-log: 
,03-31 17:41:55.740  3270  3328 I jxcore-log: ok 160 peer must have pleaseConnect
03-31 17:41:55.740  3270  3328 I jxcore-log: 
,03-31 17:41:55.747  3270  3328 I jxcore-log: # teardown
03-31 17:41:55.747  3270  3328 I jxcore-log: 
,03-31 17:41:56.400  3270  3328 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-31 17:41:56.401  3270  3328 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
03-31 17:41:56.401  3270  3328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-31 17:41:56.401  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-31 17:41:56.405  2163  2181 D BtGatt.GattService: stopScan() - queue size =1
,03-31 17:41:56.407  2163  2958 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-31 17:41:56.409  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-31 17:41:56.409  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 17:41:56.409  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-31 17:41:56.410  2163  2207 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-31 17:41:56.410  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:41:56.410  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
,03-31 17:41:56.410  3270  3328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-31 17:41:56.410  2163  2218 D BtGatt.ScanManager: stopping BLe Batch
03-31 17:41:56.410  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-31 17:41:56.411  3270  3270 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-31 17:41:56.413  3270  3270 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
03-31 17:41:56.413  3270  3270 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 17:41:56.414  2163  2207 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-31 17:41:56.414  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:41:56.414  2163  2218 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-31 17:41:56.418  2163  2207 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-31 17:41:56.418  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:41:56.418  2163  2207 D BtGatt.GattService: current time is 205838095076
03-31 17:41:56.418  2163  2207 D BtGatt.GattService: Batch record : [12, -114, -64, -79, -107, 123, 1, -128, -81, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -68, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-31 17:41:56.419  2163  2207 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-31 17:41:56.419  2163  2207 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
,03-31 17:41:56.436  3270  3328 I jxcore-log: ok 161 Should be able to call stopListeningForAdvertisments in teardown
03-31 17:41:56.436  3270  3328 I jxcore-log: 
,03-31 17:41:56.437  3270  3328 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 17:41:56.437  3270  3328 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
03-31 17:41:56.437  3270  3328 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-31 17:41:56.437  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-31 17:41:56.437  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-31 17:41:56.437  3270  3328 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-31 17:41:56.437  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-31 17:41:56.437  3270  3328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-31 17:41:56.437  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-31 17:41:56.437  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-31 17:41:56.437  3270  3725 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
,03-31 17:41:56.437  3270  3725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-31 17:41:56.438  3270  3725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-31 17:41:56.438  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-31 17:41:56.439  3270  3328 D BluetoothLeScanner: could not find callback wrapper
03-31 17:41:56.439  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 17:41:56.439  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,03-31 17:41:56.441  2163  2217 D BtGatt.AdvertiseManager: message : 1
03-31 17:41:56.441  2163  2217 D BtGatt.AdvertiseManager: stop advertise for client 6
03-31 17:41:56.444  2163  2207 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-31 17:41:56.444  2163  2207 D BtGatt.GattService: Client app is not null!
03-31 17:41:56.445  2163  2958 D BtGatt.GattService: unregisterClient() - clientIf=6
03-31 17:41:56.446  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-31 17:41:56.446  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-31 17:41:56.446  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,03-31 17:41:56.446  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-31 17:41:56.446  3270  3328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-31 17:41:56.447  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 17:41:56.447  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-31 17:41:56.448  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-31 17:41:56.449  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,03-31 17:41:56.449  3270  3328 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-31 17:41:56.449  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 17:41:56.450  3270  3270 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 17:41:56.450  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 17:41:56.450  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-31 17:41:56.455  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-31 17:41:56.455  3270  3328 I jxcore-log: 
03-31 17:41:56.458  3270  3270 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-31 17:41:56.459   823  1410 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 17:41:56.464  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-31 17:41:56.465  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-31 17:41:56.465  3270  3270 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-31 17:41:56.465  3270  3270 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-31 17:41:56.465  3270  3270 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 17:41:56.468  3270  3270 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-31 17:41:56.468  3270  3270 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-31 17:41:56.468  3270  3270 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-31 17:41:56.468  3270  3270 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 17:41:56.468  3270  3270 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-31 17:41:56.471  3270  3328 I jxcore-log: ok 162 Should be able to call stopAdvertisingAndListening in teardown
03-31 17:41:56.471  3270  3328 I jxcore-log: 
,03-31 17:41:56.479  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 17:41:56.479  3270  3328 I jxcore-log: 
,03-31 17:41:56.480  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 17:41:56.480  3270  3328 I jxcore-log: 
,03-31 17:41:56.482  3270  3328 I jxcore-log: # setup
03-31 17:41:56.482  3270  3328 I jxcore-log: 
,03-31 17:41:56.849  2163  2210 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-31 17:41:57.012  3270  3328 I jxcore-log: # 40. Can connect to a remote peer
03-31 17:41:57.012  3270  3328 I jxcore-log: 
,03-31 17:41:57.104  3270  3328 I io.jxcore.node.ConnectionHelper: start: Port number: 58148, start advertisements: true
03-31 17:41:57.104  3270  3328 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 17:41:57.104  3270  3328 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,03-31 17:41:57.104  3270  3328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-31 17:41:57.112  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
03-31 17:41:57.112  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-31 17:41:57.112  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 17:41:57.112  3270  3328 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 17:41:57.120  2163  2209 D BtGatt.GattService: registerClient() - UUID=de4a24ff-8316-458a-bcc5-b007c4fabe94
,03-31 17:41:57.121  2163  2207 D BtGatt.GattService: onClientRegistered() - UUID=de4a24ff-8316-458a-bcc5-b007c4fabe94, clientIf=5
,03-31 17:41:57.121  3270  3287 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5,
,03-31 17:41:57.122  2163  2183 D BtGatt.GattService: start scan with filters,
,03-31 17:41:57.124  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-31 17:41:57.124  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 17:41:57.124  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-31 17:41:57.124  3270  3328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-31 17:41:57.124  2163  2218 D BtGatt.ScanManager: handling starting scan
03-31 17:41:57.125  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false,
03-31 17:41:57.126  3270  3270 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false,
03-31 17:41:57.126  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-31 17:41:57.126  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61",
03-31 17:41:57.126  3270  3328 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-31 17:41:57.127  3270  3328 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 17:41:57.131  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-31 17:41:57.131  3270  3328 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-31 17:41:57.134  2163  2207 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1,
03-31 17:41:57.134  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:41:57.137  2163  2207 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,03-31 17:41:57.137  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 17:41:57.138  2163  2218 D BtGatt.ScanManager: Starting BLE batch scan,
,03-31 17:41:57.138  2163  2218 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-31 17:41:57.141  2163  2207 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-31 17:41:57.141  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 17:41:57.143  2163  2207 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-31 17:41:57.143  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 17:41:57.146  2163  2183 D BtGatt.GattService: registerClient() - UUID=26ab8e93-af43-4270-8831-a2098b45da29
,03-31 17:41:57.146  2163  2207 D BtGatt.GattService: onClientRegistered() - UUID=26ab8e93-af43-4270-8831-a2098b45da29, clientIf=6
03-31 17:41:57.147  3270  3288 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-31 17:41:57.151  2163  2217 D BtGatt.AdvertiseManager: message : 0,
,03-31 17:41:57.157  2163  2217 D BtGatt.AdvertiseManager: starting multi advertising,
,03-31 17:41:57.161  2163  2207 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-31 17:41:57.164  2163  2207 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-31 17:41:57.166  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-31 17:41:57.166  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-31 17:41:57.167   823  1411 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 17:41:57.172  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 17:41:57.173  3270  3328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-31 17:41:57.173  3270  3328 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-31 17:41:57.173  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-31 17:41:57.175  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-31 17:41:57.175  3270  3328 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-31 17:41:57.175  3270  3328 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-31 17:41:57.175  3270  3328 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-31 17:41:57.175  3270  3328 I io.jxcore.node.ConnectionHelper: start: OK
03-31 17:41:57.176  3270  3270 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,03-31 17:41:57.176  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-31 17:41:57.176  3270  3270 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING,
03-31 17:41:57.176  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-31 17:41:57.176  3270  3270 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-31 17:41:57.176  3270  3270 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-31 17:41:57.177  3270  3270 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-31 17:41:57.177  3270  3270 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-31 17:41:57.177  3270  3270 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-31 17:41:57.177  3270  3270 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 17:41:57.177  3270  3270 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-31 17:41:57.178  3270  3270 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-31 17:41:57.178  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 17:41:57.178  3270  3328 I jxcore-log: 
03-31 17:41:57.179   823  1409 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 17:41:57.181  3270  3726 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-31 17:41:57.189  3270  3328 I jxcore-log: ok 163 Can call startUpdateAdvertisingAndListening without error
03-31 17:41:57.189  3270  3328 I jxcore-log: 
,03-31 17:41:57.195  3270  3328 I io.jxcore.node.ConnectionHelper: start: Port number: 58148, start advertisements: false,
,03-31 17:41:57.195  3270  3328 V io.jxcore.node.ConnectivityMonitor: start: Already started,
,03-31 17:41:57.195  3270  3328 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should affect listening to advertisements only
,03-31 17:41:57.195  3270  3328 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-31 17:41:57.195  3270  3726 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
03-31 17:41:57.195  3270  3328 I io.jxcore.node.ConnectionHelper: start: OK
,03-31 17:41:57.203  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false},
03-31 17:41:57.203  3270  3328 I jxcore-log: 
,03-31 17:41:57.205  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true},
03-31 17:41:57.205  3270  3328 I jxcore-log: 
03-31 17:41:57.206  3270  3328 I jxcore-log: ok 164 Can call startListeningForAdvertisements without error
03-31 17:41:57.206  3270  3328 I jxcore-log: 
,03-31 17:41:57.213  3383  3727 V GoogleAuthProtoRequest: [341] a.<init>: mAccountName set to: thalitester@gmail.com,
,03-31 17:41:57.247  1233  1250 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
03-31 17:41:57.248  1233  1250 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 17:41:57.248  1233  1250 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-31 17:41:57.248  1233  1250 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 17:41:57.254  1233  1250 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 17:41:57.267  3383  3727 W ExperimentUpdateService: [341] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
03-31 17:41:57.268  3383  3727 W ExperimentUpdateService: [341] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-31 17:41:57.268  3383  3727 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-31 17:41:57.268  3383  3727 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-31 17:41:57.268  3383  3727 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-31 17:41:57.268  3383  3727 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-31 17:41:57.268  3383  3727 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-31 17:41:57.268  3383  3727 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-31 17:41:57.268  3383  3727 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-31 17:41:57.268  3383  3727 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-31 17:41:57.268  3383  3727 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-31 17:41:57.268  3383  3727 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-31 17:41:57.649  2163  2163 D BtGatt.ScanManager: awakened up at time 207068
,03-31 17:41:57.651  2163  2218 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-31 17:41:57.657  2163  2207 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-31 17:41:57.657  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:41:57.657  2163  2207 D BtGatt.GattService: current time is 207077259451
,03-31 17:41:57.658  2163  2207 D BtGatt.GattService: Batch record : [8, -14, 34, -27, 106, 87, 1, -128, -81, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -64, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0],
03-31 17:41:57.658  2163  2207 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-31 17:41:57.659  2163  2207 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-31 17:41:57.662  3270  3270 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 1
,03-31 17:41:57.663  3270  3270 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> E0:DB:10:14:E2:C0], added - the peer count is 2
03-31 17:41:57.663  3270  3270 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
03-31 17:41:57.664  3270  3270 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> E0:DB:10:14:E2:C0], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 
,03-31 17:41:57.667  3270  3328 I jxcore-log: INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"pleaseConnect":false}],
03-31 17:41:57.667  3270  3328 I jxcore-log: 
,03-31 17:41:57.674  3270  3328 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID F8:95:C7:87:3C:51
,03-31 17:41:57.674  3270  3328 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> F8:95:C7:87:3C:51]
,03-31 17:41:57.678  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address F8:95:C7:87:3C:51
03-31 17:41:57.679  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
03-31 17:41:57.679  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
03-31 17:41:57.679  3270  3328 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null F8:95:C7:87:3C:51
03-31 17:41:57.679  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address F8:95:C7:87:3C:51
03-31 17:41:57.679  3270  3328 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: F8:95:C7:87:3C:51)
03-31 17:41:57.681  3270  3328 I jxcore-log: INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"E0:DB:10:14:E2:C0","peerAvailable":true,"pleaseConnect":false}]
03-31 17:41:57.681  3270  3328 I jxcore-log: 
,03-31 17:41:57.683  3270  3728 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address F8:95:C7:87:3C:51 (thread ID: 356)
,03-31 17:41:57.684  3270  3728 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-31 17:41:57.688  2163  2209 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,03-31 17:42:01.455  2163  2219 W bt-btif : info:x10
03-31 17:42:01.456  2163  2207 D         : remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,03-31 17:42:01.456  2163  2207 E BluetoothRemoteDevices: aclStateChangeCallback: Device is NULL
,03-31 17:42:01.491  2163  2219 W bt-sdp  : process_service_search_attr_rsp
,03-31 17:42:01.961  2163  2207 D btif_config: btif_get_device_type: Device [f8:95:c7:87:3c:51] type 1
,03-31 17:42:01.971  2163  2207 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
,03-31 17:42:01.972  2163  2207 E bt-btif : check_cod: remote_cod = 0x5a020c
,03-31 17:42:01.975  2163  2208 I BluetoothBondStateMachine: Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
,03-31 17:42:01.976  2163  2208 I BluetoothBondStateMachine: Entering PendingCommandState State
,03-31 17:42:02.053   823   857 I ActivityManager: Start proc 3729:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.BluetoothPairingRequest
,03-31 17:42:02.092  2163  2207 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,03-31 17:42:02.092  2163  2208 D BluetoothAdapterProperties: Failed to remove device: F8:95:C7:87:3C:51
,03-31 17:42:02.097  2163  2208 I BluetoothBondStateMachine: Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,03-31 17:42:02.132  2163  2208 I BluetoothBondStateMachine: StableState(): Entering Off State
,03-31 17:42:02.149   823   861 D BluetoothManagerService: Message: 20,
03-31 17:42:02.149   823   861 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1a99ef13:true
,03-31 17:42:02.153   823  1149 I ActivityManager: Killing 2922:com.google.android.music:main/u0a66 (adj 15): empty #17
,03-31 17:42:02.177  2163  2219 W bt-btif : new conn_srvc id:26, app_id:1
03-31 17:42:02.178  2163  2219 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:1
03-31 17:42:02.178  2163  2219 W bt-btif : bta_dm_pm_ssr:2, lat:1200
,03-31 17:42:02.178  3270  3728 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onSocketConnected: [<no peer name> F8:95:C7:87:3C:51] (thread ID: 356)
03-31 17:42:02.178  3270  3728 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 356)
,03-31 17:42:02.180  3270  3728 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesWritten: 15 bytes successfully written (thread ID: 357)
03-31 17:42:02.180  3270  3728 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Outgoing connection initialized (*handshake* thread ID: 357)
03-31 17:42:02.180  3270  3728 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 356)
03-31 17:42:02.181  3270  3748 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 357)
,03-31 17:42:02.212  3270  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesRead: Read 15 bytes successfully (thread ID: 357)
,03-31 17:42:02.216  3270  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Handshake succeeded with [<no peer name> F8:95:C7:87:3C:51]
,03-31 17:42:02.216  3270  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onHandshakeSucceeded: [<no peer name> F8:95:C7:87:3C:51] (thread ID: 356)
03-31 17:42:02.216  3270  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: handleSuccessfulClientThread: [<no peer name> F8:95:C7:87:3C:51] (thread ID: 356)
,03-31 17:42:02.218  3270  3270 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> F8:95:C7:87:3C:51]
,03-31 17:42:02.219  3270  3748 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 357)
03-31 17:42:02.220  3270  3270 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing connection to peer [<no peer name> F8:95:C7:87:3C:51]
03-31 17:42:02.221  3270  3270 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2,
,03-31 17:42:02.226  3270  3270 I io.jxcore.node.ConnectionHelper: lowerBleDiscoveryPowerAndStartResetTimer: Lowering the power settings,
03-31 17:42:02.227  3270  3270 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 2 -> 0
03-31 17:42:02.228  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-31 17:42:02.228  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-31 17:42:02.228  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-31 17:42:02.228  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-31 17:42:02.228  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
,03-31 17:42:02.228  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-31 17:42:02.235  2163  2217 D BtGatt.AdvertiseManager: message : 1,
03-31 17:42:02.237  2163  2217 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-31 17:42:02.241  2163  2207 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-31 17:42:02.242  2163  2207 D BtGatt.GattService: Client app is not null!
,03-31 17:42:02.243  2163  2958 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-31 17:42:02.243  3270  3270 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-31 17:42:02.243  3270  3270 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-31 17:42:02.243  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 3, timeout: 0, is connectable: false
03-31 17:42:02.243  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-31 17:42:02.243  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-31 17:42:02.244  3270  3270 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-31 17:42:02.244  3270  3270 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 17:42:02.244  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 17:42:02.244  3270  3270 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...,
,03-31 17:42:02.251  2163  2958 D BtGatt.GattService: registerClient() - UUID=53fcc923-759b-4753-84c1-f848cd1fe27a
,03-31 17:42:02.251  2163  2207 D BtGatt.GattService: onClientRegistered() - UUID=53fcc923-759b-4753-84c1-f848cd1fe27a, clientIf=6
03-31 17:42:02.252  3270  3288 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-31 17:42:02.255  2163  2217 D BtGatt.AdvertiseManager: message : 0
,03-31 17:42:02.257  2163  2217 D BtGatt.AdvertiseManager: starting multi advertising,
,03-31 17:42:02.260  2163  2207 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0,
,03-31 17:42:02.264  2163  2207 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
03-31 17:42:02.265  3270  3270 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-31 17:42:02.267  2163  2181 D BtGatt.GattService: stopScan() - queue size =1
,03-31 17:42:02.272  2163  2958 D BtGatt.GattService: unregisterClient() - clientIf=5
03-31 17:42:02.272  2163  2207 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,03-31 17:42:02.273  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:42:02.273  3270  3270 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 17:42:02.273  3270  3270 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 17:42:02.273  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-31 17:42:02.273  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-31 17:42:02.273  3270  3270 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 17:42:02.273  3270  3270 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-31 17:42:02.273  2163  2218 D BtGatt.ScanManager: stopping BLe Batch
,03-31 17:42:02.276  2163  2207 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-31 17:42:02.276  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:42:02.276  2163  2218 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-31 17:42:02.279  2163  2207 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-31 17:42:02.279  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:42:02.279  2163  2207 D BtGatt.GattService: current time is 211699177678
,03-31 17:42:02.279  2163  2207 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -56, 46, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0, 8, -14, 34, -27, 106, 87, 1, -128, -76, 45, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-31 17:42:02.279  2163  2207 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-31 17:42:02.280  2163  2207 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-31 17:42:02.281  2163  2958 D BtGatt.GattService: registerClient() - UUID=24199570-0172-48c2-a299-47530ef86e76
03-31 17:42:02.281  2163  2207 D BtGatt.GattService: onClientRegistered() - UUID=24199570-0172-48c2-a299-47530ef86e76, clientIf=5
03-31 17:42:02.281  3270  3288 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-31 17:42:02.282  2163  2209 D BtGatt.GattService: start scan with filters
,03-31 17:42:02.282  3270  3270 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-31 17:42:02.282  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 17:42:02.283  3270  3270 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 3 -> 1
03-31 17:42:02.283  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-31 17:42:02.283  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-31 17:42:02.283  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-31 17:42:02.283  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-31 17:42:02.283  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-31 17:42:02.283  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-31 17:42:02.284  2163  2217 D BtGatt.AdvertiseManager: message : 1
03-31 17:42:02.285  2163  2217 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-31 17:42:02.287  2163  2207 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-31 17:42:02.287  2163  2207 D BtGatt.GattService: Client app is not null!
03-31 17:42:02.287  2163  2218 D BtGatt.ScanManager: handling starting scan
03-31 17:42:02.288  2163  2209 D BtGatt.GattService: unregisterClient() - clientIf=6
03-31 17:42:02.288  3270  3270 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-31 17:42:02.288  3270  3270 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-31 17:42:02.288  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-31 17:42:02.288  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,03-31 17:42:02.288  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-31 17:42:02.288  3270  3270 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-31 17:42:02.289  3270  3270 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 17:42:02.289  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 17:42:02.289  3270  3270 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-31 17:42:02.289  2163  2207 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-31 17:42:02.289  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:42:02.291  2163  2207 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,03-31 17:42:02.291  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:42:02.291  2163  2218 D BtGatt.ScanManager: Starting BLE batch scan
03-31 17:42:02.291  2163  2218 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-31 17:42:02.292  2163  2207 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-31 17:42:02.292  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:42:02.293  2163  2207 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-31 17:42:02.293  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 17:42:02.295  2163  2958 D BtGatt.GattService: registerClient() - UUID=81025f05-0a57-4a2f-acc8-4368d7f96cf9
03-31 17:42:02.295  2163  2207 D BtGatt.GattService: onClientRegistered() - UUID=81025f05-0a57-4a2f-acc8-4368d7f96cf9, clientIf=6
,03-31 17:42:02.296  3270  3288 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-31 17:42:02.296  2163  2217 D BtGatt.AdvertiseManager: message : 0
,03-31 17:42:02.298  2163  2217 D BtGatt.AdvertiseManager: starting multi advertising
,03-31 17:42:02.301  2163  2207 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-31 17:42:02.303  2163  2207 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-31 17:42:02.303  3270  3270 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-31 17:42:02.305  2163  2209 D BtGatt.GattService: stopScan() - queue size =1
03-31 17:42:02.306  2163  2958 D BtGatt.GattService: unregisterClient() - clientIf=5
03-31 17:42:02.306  3270  3270 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 17:42:02.306  3270  3270 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 17:42:02.306  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-31 17:42:02.306  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-31 17:42:02.306  3270  3270 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 17:42:02.306  3270  3270 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 17:42:02.307  2163  2207 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-31 17:42:02.307  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:42:02.307  2163  2218 D BtGatt.ScanManager: stopping BLe Batch
,03-31 17:42:02.310  2163  2958 D BtGatt.GattService: registerClient() - UUID=7c362132-f439-47f8-9c78-7e5ab38ce7fe
,03-31 17:42:02.310  2163  2207 D BtGatt.GattService: onClientRegistered() - UUID=7c362132-f439-47f8-9c78-7e5ab38ce7fe, clientIf=5
03-31 17:42:02.310  2163  2207 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-31 17:42:02.310  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:42:02.310  2163  2218 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-31 17:42:02.311  3270  3288 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-31 17:42:02.311  2163  2181 D BtGatt.GattService: start scan with filters
03-31 17:42:02.311  2163  2207 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-31 17:42:02.311  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:42:02.312  3270  3270 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-31 17:42:02.312  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 17:42:02.312  3270  3270 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 2 -> 0
03-31 17:42:02.312  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-31 17:42:02.312  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-31 17:42:02.312  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-31 17:42:02.312  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-31 17:42:02.312  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-31 17:42:02.312  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-31 17:42:02.314  2163  2217 D BtGatt.AdvertiseManager: message : 1
03-31 17:42:02.314  2163  2217 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-31 17:42:02.315  2163  2218 D BtGatt.ScanManager: handling starting scan
03-31 17:42:02.316  2163  2207 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-31 17:42:02.316  2163  2207 D BtGatt.GattService: Client app is not null!
,03-31 17:42:02.316  2163  2958 D BtGatt.GattService: unregisterClient() - clientIf=6
03-31 17:42:02.317  3270  3270 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-31 17:42:02.317  3270  3270 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-31 17:42:02.317  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-31 17:42:02.317  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,03-31 17:42:02.317  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-31 17:42:02.317  3270  3270 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-31 17:42:02.317  3270  3270 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 17:42:02.317  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 17:42:02.317  3270  3270 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-31 17:42:02.318  2163  2207 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-31 17:42:02.318  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:42:02.319  2163  2207 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-31 17:42:02.319  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:42:02.319  2163  2218 D BtGatt.ScanManager: Starting BLE batch scan
03-31 17:42:02.319  2163  2218 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-31 17:42:02.321  2163  2207 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,03-31 17:42:02.321  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:42:02.322  2163  2207 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-31 17:42:02.322  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:42:02.323  2163  2958 D BtGatt.GattService: registerClient() - UUID=e6cbba47-9f36-4ed8-bc3a-c1400f84dc29
03-31 17:42:02.323  2163  2207 D BtGatt.GattService: onClientRegistered() - UUID=e6cbba47-9f36-4ed8-bc3a-c1400f84dc29, clientIf=6
03-31 17:42:02.323  3270  3288 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-31 17:42:02.324  2163  2217 D BtGatt.AdvertiseManager: message : 0,
,03-31 17:42:02.326  2163  2217 D BtGatt.AdvertiseManager: starting multi advertising
,03-31 17:42:02.328  2163  2207 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-31 17:42:02.330  2163  2207 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0,
03-31 17:42:02.330  3270  3270 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-31 17:42:02.332  2163  2958 D BtGatt.GattService: stopScan() - queue size =1
03-31 17:42:02.332  2163  2183 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-31 17:42:02.333  3270  3270 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 17:42:02.333  3270  3270 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 17:42:02.333  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-31 17:42:02.333  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-31 17:42:02.333  2163  2207 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-31 17:42:02.333  3270  3270 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 17:42:02.333  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:42:02.333  3270  3270 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-31 17:42:02.333  2163  2218 D BtGatt.ScanManager: stopping BLe Batch
,03-31 17:42:02.334  2163  2207 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-31 17:42:02.334  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:42:02.335  2163  2218 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-31 17:42:02.335  2163  2207 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-31 17:42:02.335  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 17:42:02.337  2163  2183 D BtGatt.GattService: registerClient() - UUID=a4a62f55-2ad0-4d2f-8bec-b2d504cf2d81,
03-31 17:42:02.337  2163  2207 D BtGatt.GattService: onClientRegistered() - UUID=a4a62f55-2ad0-4d2f-8bec-b2d504cf2d81, clientIf=5
03-31 17:42:02.337  3270  3288 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-31 17:42:02.338  2163  2181 D BtGatt.GattService: start scan with filters
03-31 17:42:02.339  3270  3270 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-31 17:42:02.339  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-31 17:42:02.339  3270  3270 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing socket thread, for peer [<no peer name> F8:95:C7:87:3C:51], created successfully
03-31 17:42:02.339  3270  3270 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 1
03-31 17:42:02.339  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-31 17:42:02.339  3270  3270 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-31 17:42:02.339  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-31 17:42:02.339  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-31 17:42:02.339  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-31 17:42:02.340  3270  3750 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 358),
03-31 17:42:02.340  2163  2218 D BtGatt.ScanManager: handling starting scan
03-31 17:42:02.341  3270  3750 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 35917
03-31 17:42:02.341  3270  3750 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
03-31 17:42:02.341  3270  3750 I io.jxcore.node.ConnectionHelper: onListeningForIncomingConnections: Outgoing connection is using port 35917 (peer ID: F8:95:C7:87:3C:51)
03-31 17:42:02.341  3270  3750 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "F8:95:C7:87:3C:51" removed
,03-31 17:42:02.342  2163  2207 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-31 17:42:02.342  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 17:42:02.343  2163  2207 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-31 17:42:02.343  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:42:02.343  2163  2218 D BtGatt.ScanManager: Starting BLE batch scan
03-31 17:42:02.343  2163  2218 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-31 17:42:02.345  2163  2207 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,03-31 17:42:02.345  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:42:02.346  2163  2207 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-31 17:42:02.346  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 17:42:02.346  3270  3328 I jxcore-log: INFO testThaliMobileNative: 
03-31 17:42:02.346  3270  3328 I jxcore-log: 
,03-31 17:42:02.347  3270  3328 I jxcore-log: ok 165 Must have listeningPort
03-31 17:42:02.347  3270  3328 I jxcore-log: 
03-31 17:42:02.347  3270  3328 I jxcore-log: ok 166 listeningPort must be a number
03-31 17:42:02.347  3270  3328 I jxcore-log: 
03-31 17:42:02.348  3270  3328 I jxcore-log: ok 167 Connection must have clientPort
03-31 17:42:02.348  3270  3328 I jxcore-log: 
03-31 17:42:02.348  3270  3328 I jxcore-log: ok 168 clientPort must be a number
03-31 17:42:02.348  3270  3328 I jxcore-log: 
03-31 17:42:02.348  3270  3328 I jxcore-log: ok 169 Connection must have serverPort
03-31 17:42:02.348  3270  3328 I jxcore-log: 
03-31 17:42:02.348  3270  3328 I jxcore-log: ok 170 serverPort must be a number
03-31 17:42:02.348  3270  3328 I jxcore-log: 
03-31 17:42:02.349  3270  3328 I jxcore-log: ok 171 forward connection must have clientPort == 0
03-31 17:42:02.349  3270  3328 I jxcore-log: 
03-31 17:42:02.349  3270  3328 I jxcore-log: ok 172 forward connection must have serverPort == 0
03-31 17:42:02.349  3270  3328 I jxcore-log: 
03-31 17:42:02.355  3270  3328 I jxcore-log: # teardown
03-31 17:42:02.355  3270  3328 I jxcore-log: 
,03-31 17:42:07.140  2163  2219 W bt-btif : dm_pm_timer expires
,03-31 17:42:07.140  2163  2219 W bt-btif : dm_pm_timer expires 0
03-31 17:42:07.140  2163  2219 W bt-btif : proc dm_pm_timer expires
,03-31 17:42:07.260  2163  2163 D BtGatt.ScanManager: awakened up at time 216679
03-31 17:42:07.262  2163  2218 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-31 17:42:07.267  2163  2207 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,03-31 17:42:07.267  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 17:42:07.458  2163  2205 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new,
,03-31 17:42:08.282  2163  2163 D BtGatt.ScanManager: awakened up at time 217702
,03-31 17:42:08.284  2163  2218 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-31 17:42:08.291  2163  2207 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-31 17:42:08.291  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 17:42:09.308  2163  2163 D BtGatt.ScanManager: awakened up at time 218728,
,03-31 17:42:09.310  2163  2218 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-31 17:42:09.321  2163  2207 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,03-31 17:42:09.321  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 17:42:10.336  2163  2163 D BtGatt.ScanManager: awakened up at time 219755
03-31 17:42:10.338  2163  2218 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-31 17:42:10.346  2163  2207 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,03-31 17:42:10.346  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 17:42:11.362  2163  2163 D BtGatt.ScanManager: awakened up at time 220781
,03-31 17:42:11.364  2163  2218 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-31 17:42:11.374  2163  2207 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,03-31 17:42:11.374  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 17:42:12.063  3270  3328 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-31 17:42:12.063  3270  3328 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
03-31 17:42:12.063  3270  3328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,03-31 17:42:12.063  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-31 17:42:12.065  2163  2181 D BtGatt.GattService: stopScan() - queue size =1
03-31 17:42:12.066  2163  2209 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-31 17:42:12.066  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-31 17:42:12.067  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED,
03-31 17:42:12.067  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-31 17:42:12.067  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-31 17:42:12.067  3270  3328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-31 17:42:12.067  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true,
,03-31 17:42:12.068  3270  3270 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-31 17:42:12.069  2163  2207 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-31 17:42:12.069  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:42:12.069  3270  3270 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
03-31 17:42:12.069  3270  3270 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 17:42:12.069  2163  2218 D BtGatt.ScanManager: stopping BLe Batch
03-31 17:42:12.072  2163  2207 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-31 17:42:12.072  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:42:12.072  3270  3328 I jxcore-log: ok 173 Should be able to call stopListeningForAdvertisments in teardown
03-31 17:42:12.072  3270  3328 I jxcore-log: 
03-31 17:42:12.073  2163  2218 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-31 17:42:12.074  3270  3328 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-31 17:42:12.074  3270  3328 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> F8:95:C7:87:3C:51]
03-31 17:42:12.074  3270  3328 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 358)
03-31 17:42:12.074  3270  3328 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 358)
03-31 17:42:12.075  3270  3328 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
03-31 17:42:12.075  3270  3328 D io.jxcore.node.OutgoingSocketThread: closeLocalSocketAndStreams: Nothing to close (thread ID: 358)
03-31 17:42:12.075  3270  3328 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 358)
03-31 17:42:12.076  2163  2207 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-31 17:42:12.076  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:42:12.076  3270  3750 D io.jxcore.node.OutgoingSocketThread: Exiting thread (ID: 358)
03-31 17:42:12.077  3270  3328 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,03-31 17:42:12.077  3270  3328 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-31 17:42:12.077  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-31 17:42:12.078  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-31 17:42:12.079  3270  3328 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed,
03-31 17:42:12.079  3270  3726 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-31 17:42:12.079  3270  3726 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-31 17:42:12.080  3270  3726 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-31 17:42:12.080  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-31 17:42:12.080  3270  3270 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-31 17:42:12.080  3270  3328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-31 17:42:12.080  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-31 17:42:12.080  3270  3270 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-31 17:42:12.080  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,03-31 17:42:12.081  3270  3270 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-31 17:42:12.081  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-31 17:42:12.083  3270  3328 D BluetoothLeScanner: could not find callback wrapper
03-31 17:42:12.083  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 17:42:12.083  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,03-31 17:42:12.092  2163  2217 D BtGatt.AdvertiseManager: message : 1
03-31 17:42:12.093  2163  2217 D BtGatt.AdvertiseManager: stop advertise for client 6
03-31 17:42:12.098  2163  2207 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,03-31 17:42:12.098  2163  2207 D BtGatt.GattService: Client app is not null!
03-31 17:42:12.100  2163  2958 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-31 17:42:12.102  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-31 17:42:12.102  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,03-31 17:42:12.102  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,03-31 17:42:12.102  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-31 17:42:12.103  3270  3328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-31 17:42:12.103  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 17:42:12.103  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-31 17:42:12.104  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-31 17:42:12.106  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-31 17:42:12.106  3270  3328 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-31 17:42:12.106  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 17:42:12.107  3270  3270 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 17:42:12.107  3270  3270 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 17:42:12.107  3270  3270 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-31 17:42:12.107  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 17:42:12.107  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-31 17:42:12.110  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-31 17:42:12.110  3270  3328 I jxcore-log: 
03-31 17:42:12.112  3270  3328 I jxcore-log: ok 174 Should be able to call stopAdvertisingAndListening in teardown
03-31 17:42:12.112  3270  3328 I jxcore-log: 
,03-31 17:42:12.119  3270  3328 I jxcore-log: # setup
,03-31 17:42:12.119  3270  3328 I jxcore-log: 
03-31 17:42:12.119  3270  3270 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-31 17:42:12.120   823  1412 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 17:42:12.127  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
,03-31 17:42:12.128  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-31 17:42:12.128  3270  3270 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-31 17:42:12.133  3270  3270 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-31 17:42:12.133  3270  3270 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-31 17:42:12.135  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 17:42:12.135  3270  3328 I jxcore-log: 
03-31 17:42:12.135  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 17:42:12.135  3270  3328 I jxcore-log: 
,03-31 17:42:12.984  2163  2219 W bt-btif : bta_jv_rfc_port_to_cb(port_handle:0xd):jv handle:0x0 not FOUND
,03-31 17:42:14.459  1251  1474 I Keyboard.Facilitator.LanguageModelFlusher: run()
,03-31 17:42:14.459  1251  1474 I Keyboard.Facilitator: flushDynamicLanguageModels()
,03-31 17:42:14.498  1233  1233 I ConfigService: onCreate
,03-31 17:42:17.340  3270  3270 I io.jxcore.node.ConnectionHelper: restoreDefaultBleDiscoverySettings: Powering the BLE discovery back up
03-31 17:42:17.340  3270  3270 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 0 -> 2
03-31 17:42:17.341  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-31 17:42:17.341  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-31 17:42:17.341  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-31 17:42:17.341  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-31 17:42:17.341  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
,03-31 17:42:17.341  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-31 17:42:17.342  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 1, timeout: 0, is connectable: false
,03-31 17:42:17.342  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
,03-31 17:42:17.342  3270  3270 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 1 -> 3,
03-31 17:42:17.342  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-31 17:42:17.342  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-31 17:42:17.342  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-31 17:42:17.342  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-31 17:42:17.342  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-31 17:42:17.342  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-31 17:42:17.343  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-31 17:42:17.343  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-31 17:42:17.343  3270  3270 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 0 -> 2
03-31 17:42:17.343  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-31 17:42:17.343  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-31 17:42:17.343  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-31 17:42:17.343  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-31 17:42:17.343  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2,
03-31 17:42:17.343  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-31 17:42:17.343  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-31 17:42:17.344  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-31 17:42:17.447  2163  2219 E bt-btm  : btm_sec_disconnected - Clearing Pending flag,
,03-31 17:42:17.453  2163  2163 D BluetoothMapService: onReceive,
,03-31 17:42:17.560   823  1093 I ActivityManager: Start proc 3755:com.google.android.googlequicksearchbox:search/u0a28 for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver
,03-31 17:42:17.577   371   371 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 358us total 16.304ms
,03-31 17:42:17.593   371   371 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 363us total 15.161ms
,03-31 17:42:17.607   371   371 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 242us total 13.925ms
,03-31 17:42:17.712   823   861 D BluetoothManagerService: Message: 20
03-31 17:42:17.712   823   861 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@129e2d8b:true
,03-31 17:42:17.727  3755  3755 I BTConnectionReceiver: onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,03-31 17:42:17.919   823  1409 I ActivityManager: Start proc 3777:com.google.android.partnersetup/u0a16 for content provider com.google.android.partnersetup/.RlzAppProvider
,03-31 17:42:17.928  3755  3755 I BluetoothClassifier: Bluetooth Device Name: G4-1
,03-31 17:42:17.935   823  1393 I ActivityManager: Killing 3417:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,03-31 17:42:18.048   823  1093 I ActivityManager: Killing 3480:com.google.android.apps.magazines/u0a67 (adj 15): empty #17
,03-31 17:42:19.587  1233  1233 I ConfigService: onDestroy
,03-31 17:42:21.530  3515  3802 I BooksSync: Starting books sync for 61035162, extras: ade
,03-31 17:42:21.575  3515  3803 I BooksConfig: GmsCore Version = 7.8.99 (2134222-430)
,03-31 17:42:21.593  3448  3801 V KeepSync: Connecting to GoogleApiClient
,03-31 17:42:21.656  1233  1713 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-31 17:42:21.656  1233  1713 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-31 17:42:21.656  1233  1713 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 17:42:21.656  1233  1713 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 17:42:21.660  1233  1713 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,03-31 17:42:21.690  1233  2543 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata,
03-31 17:42:21.690  1233  2543 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 17:42:21.690  1233  2543 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 17:42:21.690  1233  2543 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 17:42:21.696  1233  2543 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 17:42:21.716  1766  3805 E ClientConnectionOperation: Handling authorization failure
03-31 17:42:21.716  1766  3805 E ClientConnectionOperation: com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
03-31 17:42:21.716  1766  3805 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
03-31 17:42:21.716  1766  3805 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
03-31 17:42:21.716  1766  3805 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
03-31 17:42:21.716  1766  3805 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
03-31 17:42:21.716  1766  3805 E ClientConnectionOperation: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-31 17:42:21.716  1766  3805 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 17:42:21.716  1766  3805 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 17:42:21.716  1766  3805 E ClientConnectionOperation: 	at java.lang.Thread.run(Thread.java:818)
03-31 17:42:21.716  1766  3805 E ClientConnectionOperation: Caused by: com.google.android.gms.auth.ad: BadAuthentication
03-31 17:42:21.716  1766  3805 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.b(SourceFile:442)
03-31 17:42:21.716  1766  3805 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:365)
03-31 17:42:21.716  1766  3805 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:310)
03-31 17:42:21.716  1766  3805 E ClientConnectionOperation: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
03-31 17:42:21.716  1766  3805 E ClientConnectionOperation: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
03-31 17:42:21.716  1766  3805 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:30)
03-31 17:42:21.716  1766  3805 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:370)
03-31 17:42:21.716  1766  3805 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:340)
03-31 17:42:21.716  1766  3805 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:319)
03-31 17:42:21.716  1766  3805 E ClientConnectionOperation: 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
03-31 17:42:21.716  1766  3805 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
03-31 17:42:21.716  1766  3805 E ClientConnectionOperation: 	... 7 more
,03-31 17:42:21.718  3448  3801 V KeepSync: GoogleApiClient failed to connect with error code: 4
,03-31 17:42:21.722  3448  3801 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-31 17:42:21.729  3448  3801 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-31 17:42:21.731  3448  3801 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-31 17:42:21.743  1233  1640 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,03-31 17:42:21.743  1233  1640 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 17:42:21.743  1233  1640 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 17:42:21.743  1233  1640 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 17:42:21.746  1233  1640 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 17:42:21.758  3515  3803 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,03-31 17:42:21.759  3515  3802 E BooksSync: Soft error
03-31 17:42:21.759  3515  3802 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-31 17:42:21.759  3515  3802 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-31 17:42:21.759  3515  3802 E BooksSync: Sync error
03-31 17:42:21.759  3515  3802 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-31 17:42:21.759  3515  3802 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,03-31 17:42:21.759  3515  3802 I BooksSync: Finished books sync
,03-31 17:42:21.764   823   856 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 202412, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-31 17:42:21.801  1233  1921 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,03-31 17:42:21.801  1233  1921 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 17:42:21.801  1233  1921 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 17:42:21.802  1233  1921 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 17:42:21.805  1233  1921 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 17:42:21.841  3448  3801 E KeepSync: IOException
03-31 17:42:21.841  3448  3801 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
03-31 17:42:21.841  3448  3801 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
03-31 17:42:21.841  3448  3801 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
03-31 17:42:21.841  3448  3801 E KeepSync: 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
03-31 17:42:21.841  3448  3801 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
03-31 17:42:21.841  3448  3801 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
03-31 17:42:21.841  3448  3801 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
03-31 17:42:21.841  3448  3801 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
03-31 17:42:21.841  3448  3801 E KeepSync: 	at com.google.android.keep.util.m.a(SourceFile:207)
03-31 17:42:21.841  3448  3801 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
03-31 17:42:21.841  3448  3801 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
03-31 17:42:21.841  3448  3801 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
03-31 17:42:21.841  3448  3801 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
03-31 17:42:21.841  3448  3801 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
03-31 17:42:21.841  3448  3801 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
03-31 17:42:21.841  3448  3801 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
03-31 17:42:21.841  3448  3801 E KeepSync: 	... 10 more
,03-31 17:42:21.842  3448  3801 W KeepSync: Sync result 2
,03-31 17:42:21.860   823   856 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 201758, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-31 17:42:27.018  3270  3328 I jxcore-log: # 41. Can shift large amounts of data
03-31 17:42:27.018  3270  3328 I jxcore-log: 
,03-31 17:42:31.190  3270  3328 I io.jxcore.node.ConnectionHelper: start: Port number: 54014, start advertisements: true
03-31 17:42:31.190  3270  3328 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 17:42:31.190  3270  3328 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-31 17:42:31.190  3270  3328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-31 17:42:31.194  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
03-31 17:42:31.194  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-31 17:42:31.194  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 17:42:31.194  3270  3328 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 17:42:31.197  2163  2183 D BtGatt.GattService: registerClient() - UUID=072b3ffd-1c6b-44c6-b891-b9d0a9780d39
03-31 17:42:31.198  2163  2207 D BtGatt.GattService: onClientRegistered() - UUID=072b3ffd-1c6b-44c6-b891-b9d0a9780d39, clientIf=5
03-31 17:42:31.198  3270  3288 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-31 17:42:31.198  2163  2209 D BtGatt.GattService: start scan with filters
,03-31 17:42:31.199  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-31 17:42:31.199  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 17:42:31.199  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-31 17:42:31.199  3270  3328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-31 17:42:31.199  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 17:42:31.199  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-31 17:42:31.199  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-31 17:42:31.199  3270  3328 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-31 17:42:31.199  3270  3270 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 17:42:31.199  3270  3328 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 17:42:31.199  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 17:42:31.199  2163  2218 D BtGatt.ScanManager: handling starting scan
03-31 17:42:31.199  3270  3328 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-31 17:42:31.224  2163  2209 D BtGatt.GattService: registerClient() - UUID=d1c52f8d-2ae1-4314-982b-fd5881ef55ba
03-31 17:42:31.225  2163  2207 D BtGatt.GattService: onClientRegistered() - UUID=d1c52f8d-2ae1-4314-982b-fd5881ef55ba, clientIf=6
,03-31 17:42:31.225  3270  3287 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-31 17:42:31.226  2163  2217 D BtGatt.AdvertiseManager: message : 0
,03-31 17:42:31.228  2163  2217 D BtGatt.AdvertiseManager: starting multi advertising
,03-31 17:42:31.230  2163  2207 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-31 17:42:31.231  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 17:42:31.232  2163  2207 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
03-31 17:42:31.233  2163  2207 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,03-31 17:42:31.233  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:42:31.233  2163  2218 D BtGatt.ScanManager: Starting BLE batch scan
03-31 17:42:31.233  2163  2218 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-31 17:42:31.234  2163  2207 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
03-31 17:42:31.234  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-31 17:42:31.234  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-31 17:42:31.235   823  1149 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-31 17:42:31.235  2163  2207 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-31 17:42:31.235  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 17:42:31.237  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 17:42:31.237  3270  3328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-31 17:42:31.237  3270  3328 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-31 17:42:31.237  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-31 17:42:31.237  2163  2207 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-31 17:42:31.237  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 17:42:31.237  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-31 17:42:31.237  3270  3328 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-31 17:42:31.237  3270  3328 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-31 17:42:31.237  3270  3328 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,03-31 17:42:31.238  3270  3328 I io.jxcore.node.ConnectionHelper: start: OK
03-31 17:42:31.238  3270  3270 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-31 17:42:31.238  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-31 17:42:31.238  3270  3270 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-31 17:42:31.238  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-31 17:42:31.238  3270  3270 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-31 17:42:31.238  3270  3270 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-31 17:42:31.238  3270  3270 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-31 17:42:31.238  3270  3270 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-31 17:42:31.238  3270  3270 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-31 17:42:31.238  3270  3270 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 17:42:31.238  3270  3270 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-31 17:42:31.238  3270  3270 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-31 17:42:31.239  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 17:42:31.239  3270  3328 I jxcore-log: 
03-31 17:42:31.239   823  1150 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-31 17:42:31.240  3270  3809 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-31 17:42:31.242  3270  3809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-31 17:42:31.244  3270  3328 I jxcore-log: ok 175 Can call startUpdateAdvertisingAndListening without error
03-31 17:42:31.244  3270  3328 I jxcore-log: 
,03-31 17:42:31.247  3270  3328 I io.jxcore.node.ConnectionHelper: start: Port number: 54014, start advertisements: false
,03-31 17:42:31.247  3270  3328 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 17:42:31.247  3270  3328 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should affect listening to advertisements only
03-31 17:42:31.247  3270  3328 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-31 17:42:31.247  3270  3328 I io.jxcore.node.ConnectionHelper: start: OK
,03-31 17:42:31.248  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 17:42:31.248  3270  3328 I jxcore-log: 
03-31 17:42:31.248  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-31 17:42:31.248  3270  3328 I jxcore-log: 
,03-31 17:42:31.249  3270  3328 I jxcore-log: ok 176 Can call startListeningForAdvertisements without error
03-31 17:42:31.249  3270  3328 I jxcore-log: 
,03-31 17:42:32.243  2163  2163 D BtGatt.ScanManager: awakened up at time 241662
,03-31 17:42:32.244  2163  2218 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-31 17:42:32.254  2163  2207 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
03-31 17:42:32.255  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:42:32.255  2163  2207 D BtGatt.GattService: current time is 241674926417
03-31 17:42:32.255  2163  2207 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -78, 15, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-31 17:42:32.256  2163  2207 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
,03-31 17:42:32.258  3270  3270 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> E0:DB:10:14:E2:C0], added - the peer count is 1
,03-31 17:42:32.259  3270  3270 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> E0:DB:10:14:E2:C0], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 
,03-31 17:42:32.271  3270  3328 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID E0:DB:10:14:E2:C0
03-31 17:42:32.271  3270  3328 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> E0:DB:10:14:E2:C0]
,03-31 17:42:32.275  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address E0:DB:10:14:E2:C0
,03-31 17:42:32.275  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
03-31 17:42:32.275  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
03-31 17:42:32.276  3270  3328 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null E0:DB:10:14:E2:C0
03-31 17:42:32.276  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address E0:DB:10:14:E2:C0
03-31 17:42:32.276  3270  3328 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: E0:DB:10:14:E2:C0)
,03-31 17:42:32.278  3270  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address E0:DB:10:14:E2:C0 (thread ID: 360),
03-31 17:42:32.278  3270  3810 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-31 17:42:32.282  2163  2183 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,03-31 17:42:35.970  2163  2219 W bt-btif : info:x10
03-31 17:42:35.970  2163  2207 D         : remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,03-31 17:42:35.972  2163  2207 E BluetoothRemoteDevices: aclStateChangeCallback: Device is NULL
,03-31 17:42:36.056  2163  2219 W bt-sdp  : process_service_search_attr_rsp
,03-31 17:42:36.288  2163  2207 D btif_config: btif_get_device_type: Device [e0:db:10:14:e2:c0] type 1,
,03-31 17:42:36.291  2163  2207 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 1
03-31 17:42:36.291  2163  2207 E bt-btif : check_cod: remote_cod = 0x5a020c
,03-31 17:42:36.294  2163  2208 I BluetoothBondStateMachine: Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 10 NewState: 11
03-31 17:42:36.295  2163  2208 I BluetoothBondStateMachine: Entering PendingCommandState State
,03-31 17:42:36.338  2163  2207 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 0,
,03-31 17:42:36.339  2163  2208 D BluetoothAdapterProperties: Failed to remove device: E0:DB:10:14:E2:C0
,03-31 17:42:36.342  2163  2208 I BluetoothBondStateMachine: Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 11 NewState: 10
,03-31 17:42:36.361  2163  2208 I BluetoothBondStateMachine: StableState(): Entering Off State
,03-31 17:42:36.393  2163  2219 W bt-btif : new conn_srvc id:26, app_id:1
,03-31 17:42:36.393  2163  2219 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:1
03-31 17:42:36.393  2163  2219 W bt-btif : bta_dm_pm_ssr:2, lat:1200
,03-31 17:42:36.394  3270  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onSocketConnected: [<no peer name> E0:DB:10:14:E2:C0] (thread ID: 360)
03-31 17:42:36.395  3270  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 360)
03-31 17:42:36.395  3270  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesWritten: 15 bytes successfully written (thread ID: 361)
,03-31 17:42:36.396  3270  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Outgoing connection initialized (*handshake* thread ID: 361)
03-31 17:42:36.396  3270  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 360)
03-31 17:42:36.399  3270  3812 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 361)
,03-31 17:42:36.427  3270  3812 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesRead: Read 15 bytes successfully (thread ID: 361)
,03-31 17:42:36.430  3270  3812 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Handshake succeeded with [<no peer name> E0:DB:10:14:E2:C0]
,03-31 17:42:36.430  3270  3812 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onHandshakeSucceeded: [<no peer name> E0:DB:10:14:E2:C0] (thread ID: 360)
03-31 17:42:36.431  3270  3812 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: handleSuccessfulClientThread: [<no peer name> E0:DB:10:14:E2:C0] (thread ID: 360)
03-31 17:42:36.431  3270  3270 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> E0:DB:10:14:E2:C0]
,03-31 17:42:36.432  3270  3270 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing connection to peer [<no peer name> E0:DB:10:14:E2:C0]
03-31 17:42:36.432  3270  3270 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> E0:DB:10:14:E2:C0] updated - the peer count is 1
03-31 17:42:36.432  3270  3270 I io.jxcore.node.ConnectionHelper: lowerBleDiscoveryPowerAndStartResetTimer: Lowering the power settings
03-31 17:42:36.433  3270  3270 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 2 -> 0
03-31 17:42:36.433  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-31 17:42:36.433  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-31 17:42:36.433  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-31 17:42:36.433  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-31 17:42:36.433  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-31 17:42:36.433  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-31 17:42:36.437  3270  3812 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 361)
,03-31 17:42:36.438  2163  2217 D BtGatt.AdvertiseManager: message : 1
,03-31 17:42:36.440  2163  2217 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-31 17:42:36.444  2163  2207 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0,
03-31 17:42:36.444  2163  2207 D BtGatt.GattService: Client app is not null!
03-31 17:42:36.445  2163  2958 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-31 17:42:36.446  3270  3270 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-31 17:42:36.446  3270  3270 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,03-31 17:42:36.446  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 3, timeout: 0, is connectable: false
03-31 17:42:36.446  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-31 17:42:36.446  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-31 17:42:36.447  3270  3270 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-31 17:42:36.447  3270  3270 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 17:42:36.447  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 17:42:36.447  3270  3270 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-31 17:42:36.454  2163  2209 D BtGatt.GattService: registerClient() - UUID=e39fedb0-948b-4b0e-a8b1-649785728fb1
03-31 17:42:36.455  2163  2207 D BtGatt.GattService: onClientRegistered() - UUID=e39fedb0-948b-4b0e-a8b1-649785728fb1, clientIf=6
03-31 17:42:36.455  3270  3287 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-31 17:42:36.456  2163  2217 D BtGatt.AdvertiseManager: message : 0
,03-31 17:42:36.462  2163  2217 D BtGatt.AdvertiseManager: starting multi advertising
,03-31 17:42:36.464  2163  2207 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-31 17:42:36.467  2163  2207 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
03-31 17:42:36.468  3270  3270 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-31 17:42:36.469  2163  2958 D BtGatt.GattService: stopScan() - queue size =1
03-31 17:42:36.470  2163  2209 D BtGatt.GattService: unregisterClient() - clientIf=5
03-31 17:42:36.471  3270  3270 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 17:42:36.471  3270  3270 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 17:42:36.471  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-31 17:42:36.471  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-31 17:42:36.471  3270  3270 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 17:42:36.471  3270  3270 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-31 17:42:36.471  2163  2207 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-31 17:42:36.471  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:42:36.472  2163  2218 D BtGatt.ScanManager: stopping BLe Batch
03-31 17:42:36.474  2163  2207 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,03-31 17:42:36.474  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:42:36.474  2163  2218 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-31 17:42:36.476  2163  2207 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-31 17:42:36.476  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:42:36.476  2163  2207 D BtGatt.GattService: current time is 245896257874
03-31 17:42:36.476  2163  2207 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -67, 39, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0, 38, 41, -49, 65, -77, 87, 1, -128, -95, 70, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-31 17:42:36.477  2163  2207 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-31 17:42:36.477  2163  2207 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-31 17:42:36.477  2163  2209 D BtGatt.GattService: registerClient() - UUID=5e65a745-c457-4620-862b-a46aba13d6a7
03-31 17:42:36.477  2163  2207 D BtGatt.GattService: onClientRegistered() - UUID=5e65a745-c457-4620-862b-a46aba13d6a7, clientIf=5
03-31 17:42:36.478  3270  3287 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-31 17:42:36.478  2163  2183 D BtGatt.GattService: start scan with filters
03-31 17:42:36.479  3270  3270 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-31 17:42:36.479  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true,
03-31 17:42:36.479  3270  3270 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 3 -> 1
,03-31 17:42:36.479  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-31 17:42:36.479  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-31 17:42:36.479  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-31 17:42:36.479  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-31 17:42:36.479  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-31 17:42:36.479  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-31 17:42:36.480  2163  2218 D BtGatt.ScanManager: handling starting scan
03-31 17:42:36.482  2163  2217 D BtGatt.AdvertiseManager: message : 1
03-31 17:42:36.482  2163  2207 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-31 17:42:36.482  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:42:36.483  2163  2217 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-31 17:42:36.483  2163  2207 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-31 17:42:36.483  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 17:42:36.483  2163  2218 D BtGatt.ScanManager: Starting BLE batch scan
,03-31 17:42:36.483  2163  2218 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-31 17:42:36.487  2163  2207 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-31 17:42:36.487  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:42:36.488  2163  2207 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-31 17:42:36.488  2163  2207 D BtGatt.GattService: Client app is not null!
03-31 17:42:36.489  2163  2183 D BtGatt.GattService: unregisterClient() - clientIf=6
03-31 17:42:36.490  3270  3270 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-31 17:42:36.490  3270  3270 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-31 17:42:36.490  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-31 17:42:36.490  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-31 17:42:36.490  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-31 17:42:36.490  3270  3270 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-31 17:42:36.490  3270  3270 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 17:42:36.491  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 17:42:36.491  3270  3270 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-31 17:42:36.491  2163  2207 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-31 17:42:36.491  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:42:36.496  2163  2958 D BtGatt.GattService: registerClient() - UUID=3eb84bc0-185b-4b1a-8a4c-89a2c9b40a49
03-31 17:42:36.496  2163  2207 D BtGatt.GattService: onClientRegistered() - UUID=3eb84bc0-185b-4b1a-8a4c-89a2c9b40a49, clientIf=6
03-31 17:42:36.497  3270  3287 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-31 17:42:36.500  2163  2217 D BtGatt.AdvertiseManager: message : 0
,03-31 17:42:36.503  2163  2217 D BtGatt.AdvertiseManager: starting multi advertising
,03-31 17:42:36.506  2163  2207 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-31 17:42:36.508  2163  2207 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-31 17:42:36.508  3270  3270 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-31 17:42:36.510  2163  2181 D BtGatt.GattService: stopScan() - queue size =1
03-31 17:42:36.511  2163  2958 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-31 17:42:36.511  3270  3270 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-31 17:42:36.511  3270  3270 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 17:42:36.511  2163  2207 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,03-31 17:42:36.511  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-31 17:42:36.511  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:42:36.512  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-31 17:42:36.512  3270  3270 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-31 17:42:36.512  2163  2218 D BtGatt.ScanManager: stopping BLe Batch
03-31 17:42:36.512  3270  3270 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-31 17:42:36.514  2163  2207 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-31 17:42:36.514  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 17:42:36.514  2163  2218 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-31 17:42:36.515  2163  2207 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-31 17:42:36.515  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:42:36.516  2163  2958 D BtGatt.GattService: registerClient() - UUID=bfe8a4a1-d385-4ffa-95fb-b60f118e6b4f
03-31 17:42:36.516  2163  2207 D BtGatt.GattService: onClientRegistered() - UUID=bfe8a4a1-d385-4ffa-95fb-b60f118e6b4f, clientIf=5
03-31 17:42:36.516  3270  3287 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-31 17:42:36.517  2163  2209 D BtGatt.GattService: start scan with filters
03-31 17:42:36.517  3270  3270 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-31 17:42:36.517  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true,
03-31 17:42:36.517  3270  3270 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 2 -> 0
03-31 17:42:36.518  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-31 17:42:36.518  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-31 17:42:36.518  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
,03-31 17:42:36.518  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-31 17:42:36.518  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-31 17:42:36.518  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-31 17:42:36.519  2163  2217 D BtGatt.AdvertiseManager: message : 1
,03-31 17:42:36.520  2163  2217 D BtGatt.AdvertiseManager: stop advertise for client 6
03-31 17:42:36.523  2163  2207 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,03-31 17:42:36.523  2163  2207 D BtGatt.GattService: Client app is not null!
03-31 17:42:36.524  2163  2218 D BtGatt.ScanManager: handling starting scan
03-31 17:42:36.524  2163  2958 D BtGatt.GattService: unregisterClient() - clientIf=6
03-31 17:42:36.525  3270  3270 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-31 17:42:36.525  3270  3270 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-31 17:42:36.525  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-31 17:42:36.525  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-31 17:42:36.525  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-31 17:42:36.525  3270  3270 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-31 17:42:36.525  3270  3270 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 17:42:36.526  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 17:42:36.526  3270  3270 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-31 17:42:36.526  2163  2207 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-31 17:42:36.527  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 17:42:36.528  2163  2207 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-31 17:42:36.528  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:42:36.528  2163  2218 D BtGatt.ScanManager: Starting BLE batch scan
03-31 17:42:36.528  2163  2218 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-31 17:42:36.530  2163  2207 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-31 17:42:36.530  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:42:36.532  2163  2958 D BtGatt.GattService: registerClient() - UUID=04e274a5-bb0a-4a55-b4cd-5eed22a5383f
,03-31 17:42:36.532  2163  2207 D BtGatt.GattService: onClientRegistered() - UUID=04e274a5-bb0a-4a55-b4cd-5eed22a5383f, clientIf=6
03-31 17:42:36.532  2163  2207 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-31 17:42:36.532  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 17:42:36.532  3270  3287 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-31 17:42:36.533  2163  2217 D BtGatt.AdvertiseManager: message : 0
,03-31 17:42:36.536  2163  2217 D BtGatt.AdvertiseManager: starting multi advertising
,03-31 17:42:36.539  2163  2207 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-31 17:42:36.542  2163  2207 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0,
,03-31 17:42:36.542  3270  3270 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-31 17:42:36.543  2163  2181 D BtGatt.GattService: stopScan() - queue size =1,
,03-31 17:42:36.545  2163  2958 D BtGatt.GattService: unregisterClient() - clientIf=5
03-31 17:42:36.545  3270  3270 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 17:42:36.545  2163  2207 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,03-31 17:42:36.545  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:42:36.545  3270  3270 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED,
03-31 17:42:36.545  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-31 17:42:36.545  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-31 17:42:36.545  3270  3270 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 17:42:36.545  3270  3270 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-31 17:42:36.545  2163  2218 D BtGatt.ScanManager: stopping BLe Batch
03-31 17:42:36.548  2163  2207 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-31 17:42:36.548  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:42:36.548  2163  2218 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-31 17:42:36.549  2163  2207 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-31 17:42:36.549  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 17:42:36.550  2163  2958 D BtGatt.GattService: registerClient() - UUID=a049a39a-7b34-48f3-a32d-3441eda5c613
03-31 17:42:36.550  2163  2207 D BtGatt.GattService: onClientRegistered() - UUID=a049a39a-7b34-48f3-a32d-3441eda5c613, clientIf=5
,03-31 17:42:36.550  3270  3287 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-31 17:42:36.551  2163  2209 D BtGatt.GattService: start scan with filters
,03-31 17:42:36.551  3270  3270 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-31 17:42:36.552  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-31 17:42:36.552  3270  3270 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing socket thread, for peer [<no peer name> E0:DB:10:14:E2:C0], created successfully
03-31 17:42:36.552  3270  3270 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 1
03-31 17:42:36.552  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-31 17:42:36.552  3270  3270 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-31 17:42:36.552  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,03-31 17:42:36.552  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-31 17:42:36.552  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-31 17:42:36.553  2163  2218 D BtGatt.ScanManager: handling starting scan
03-31 17:42:36.554  3270  3813 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 362)
03-31 17:42:36.555  2163  2207 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,03-31 17:42:36.555  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:42:36.556  3270  3813 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 55127
03-31 17:42:36.556  3270  3813 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,03-31 17:42:36.556  3270  3813 I io.jxcore.node.ConnectionHelper: onListeningForIncomingConnections: Outgoing connection is using port 55127 (peer ID: E0:DB:10:14:E2:C0)
03-31 17:42:36.557  2163  2207 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-31 17:42:36.557  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:42:36.557  2163  2218 D BtGatt.ScanManager: Starting BLE batch scan
03-31 17:42:36.557  2163  2218 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-31 17:42:36.557  3270  3813 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "E0:DB:10:14:E2:C0" removed
,03-31 17:42:36.558  2163  2207 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-31 17:42:36.559  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 17:42:36.559  3270  3328 I jxcore-log: INFO testThaliMobileNative: ,
03-31 17:42:36.559  3270  3328 I jxcore-log: 
03-31 17:42:36.560  2163  2207 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1,
03-31 17:42:36.560  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:42:36.561  3270  3328 I jxcore-log: INFO testThaliMobileNative: Forward connection
03-31 17:42:36.561  3270  3328 I jxcore-log: 
,03-31 17:42:36.566  3270  3328 I jxcore-log: INFO testThaliMobileNative: forwardSend
03-31 17:42:36.566  3270  3328 I jxcore-log: ,
03-31 17:42:36.567  3270  3813 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 55127
,03-31 17:42:36.568  3270  3813 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
03-31 17:42:36.568  3270  3813 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-31 17:42:36.569  3270  3813 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
,03-31 17:42:36.570  3270  3814 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 363, name: Sender),
03-31 17:42:36.570  3270  3813 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 362)
03-31 17:42:36.570  3270  3813 D io.jxcore.node.OutgoingSocketThread: Exiting thread (ID: 362)
,03-31 17:42:36.573  3270  3815 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 364, name: Receiver),
,03-31 17:42:36.696  3270  3328 I jxcore-log: INFO testThaliMobileNative: forwardData
03-31 17:42:36.696  3270  3328 I jxcore-log: 
,03-31 17:42:36.767  3270  3328 I jxcore-log: INFO testThaliMobileNative: forwardData
03-31 17:42:36.767  3270  3328 I jxcore-log: 
,03-31 17:42:36.863  3270  3328 I jxcore-log: INFO testThaliMobileNative: forwardData
03-31 17:42:36.863  3270  3328 I jxcore-log: 
,03-31 17:42:36.912  3270  3328 I jxcore-log: INFO testThaliMobileNative: forwardData
03-31 17:42:36.912  3270  3328 I jxcore-log: 
,03-31 17:42:36.985  3270  3328 I jxcore-log: INFO testThaliMobileNative: forwardData
03-31 17:42:36.985  3270  3328 I jxcore-log: 
03-31 17:42:36.987  3270  3328 I jxcore-log: ok 177 received should match sent forward
03-31 17:42:36.987  3270  3328 I jxcore-log: 
,03-31 17:42:37.003  3270  3328 I jxcore-log: # teardown
03-31 17:42:37.003  3270  3328 I jxcore-log: 
,03-31 17:42:37.185  3270  3328 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-31 17:42:37.185  3270  3328 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
03-31 17:42:37.185  3270  3328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-31 17:42:37.185  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-31 17:42:37.189  2163  2181 D BtGatt.GattService: stopScan() - queue size =1
,03-31 17:42:37.193  2163  2209 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-31 17:42:37.193  2163  2207 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-31 17:42:37.193  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:42:37.193  2163  2218 D BtGatt.ScanManager: stopping BLe Batch
,03-31 17:42:37.194  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 17:42:37.195  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 17:42:37.195  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,03-31 17:42:37.195  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
,03-31 17:42:37.195  3270  3328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING],
03-31 17:42:37.195  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-31 17:42:37.196  3270  3270 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-31 17:42:37.196  3270  3270 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
03-31 17:42:37.196  3270  3270 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-31 17:42:37.198  2163  2207 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0,
03-31 17:42:37.198  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:42:37.198  2163  2218 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-31 17:42:37.199  3270  3328 I jxcore-log: ok 178 Should be able to call stopListeningForAdvertisments in teardown
03-31 17:42:37.199  3270  3328 I jxcore-log: 
,03-31 17:42:37.201  3270  3328 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-31 17:42:37.201  3270  3328 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> E0:DB:10:14:E2:C0]
03-31 17:42:37.201  3270  3328 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 362)
,03-31 17:42:37.201  3270  3328 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 362)
03-31 17:42:37.201  3270  3815 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 364, thread name: Receiver): bt socket closed, read return: -1
03-31 17:42:37.201  3270  3328 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
03-31 17:42:37.202  3270  3328 D io.jxcore.node.OutgoingSocketThread: close: Stopping receiving thread...,
03-31 17:42:37.202  2163  2207 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-31 17:42:37.202  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 17:42:37.202  3270  3328 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 364
03-31 17:42:37.202  2163  2207 D BtGatt.GattService: current time is 246621825321
03-31 17:42:37.202  3270  3328 D io.jxcore.node.OutgoingSocketThread: close: Stopping sending thread...
,03-31 17:42:37.202  2163  2207 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -71, 9, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0, 38, 41, -49, 65, -77, 87, 1, -128, -91, 3, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-31 17:42:37.202  3270  3328 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 363
03-31 17:42:37.202  3270  3328 D io.jxcore.node.OutgoingSocketThread: closeLocalSocketAndStreams: Closing... (thread ID: 362)
,03-31 17:42:37.202  2163  2207 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-31 17:42:37.202  2163  2207 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-31 17:42:37.202  3270  3815 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 364, name: Receiver),
03-31 17:42:37.203  3270  3814 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 363, thread name: Sender): Socket closed
03-31 17:42:37.203  3270  3814 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 363, name: Sender)
03-31 17:42:37.204  3270  3328 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 362)
03-31 17:42:37.205  3270  3328 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
03-31 17:42:37.205  3270  3328 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,03-31 17:42:37.205  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-31 17:42:37.205  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-31 17:42:37.207  3270  3328 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-31 17:42:37.207  3270  3809 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-31 17:42:37.207  3270  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,03-31 17:42:37.207  3270  3809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-31 17:42:37.207  3270  3270 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-31 17:42:37.208  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-31 17:42:37.209  3270  3270 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,03-31 17:42:37.209  3270  3270 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-31 17:42:37.209  3270  3328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-31 17:42:37.209  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,03-31 17:42:37.209  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-31 17:42:37.209  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-31 17:42:37.211  3270  3328 D BluetoothLeScanner: could not find callback wrapper
,03-31 17:42:37.211  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 17:42:37.211  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-31 17:42:37.214  2163  2217 D BtGatt.AdvertiseManager: message : 1
03-31 17:42:37.214  2163  2217 D BtGatt.AdvertiseManager: stop advertise for client 6
03-31 17:42:37.217  2163  2207 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-31 17:42:37.217  2163  2207 D BtGatt.GattService: Client app is not null!
03-31 17:42:37.218  2163  2209 D BtGatt.GattService: unregisterClient() - clientIf=6
03-31 17:42:37.219  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-31 17:42:37.219  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-31 17:42:37.220  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-31 17:42:37.220  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-31 17:42:37.221  3270  3328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-31 17:42:37.221  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 17:42:37.221  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-31 17:42:37.221  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-31 17:42:37.223  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-31 17:42:37.224  3270  3328 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-31 17:42:37.224  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 17:42:37.224  3270  3270 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 17:42:37.224  3270  3270 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 17:42:37.224  3270  3270 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
03-31 17:42:37.225  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 17:42:37.225  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-31 17:42:37.233  3270  3270 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-31 17:42:37.234   823  1150 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 17:42:37.237  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-31 17:42:37.237  3270  3328 I jxcore-log: 
,03-31 17:42:37.239  3270  3328 I jxcore-log: ok 179 Should be able to call stopAdvertisingAndListening in teardown
03-31 17:42:37.239  3270  3328 I jxcore-log: 
,03-31 17:42:37.245  3270  3328 I jxcore-log: # setup,
03-31 17:42:37.245  3270  3328 I jxcore-log: 
03-31 17:42:37.245  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
,03-31 17:42:37.246  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-31 17:42:37.246  3270  3270 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-31 17:42:37.252  3270  3270 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-31 17:42:37.252  3270  3270 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-31 17:42:37.254  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 17:42:37.254  3270  3328 I jxcore-log: 
,03-31 17:42:37.255  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 17:42:37.255  3270  3328 I jxcore-log: 
,03-31 17:42:37.419  2163  2219 W bt-btif : bta_jv_rfc_port_to_cb(port_handle:0xf):jv handle:0x0 not FOUND
,03-31 17:42:37.793  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 17:42:37.793  3270  3328 I jxcore-log: ,
03-31 17:42:37.795  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 17:42:37.795  3270  3328 I jxcore-log: 
,03-31 17:42:37.801  3270  3328 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 17:42:37.801  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 17:42:37.801  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
,03-31 17:42:37.801  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 17:42:37.801  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 17:42:37.801  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 17:42:37.801  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 17:42:37.801  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 17:42:37.805  3270  3328 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
03-31 17:42:37.807  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 17:42:37.807  3270  3328 I jxcore-log: 
,03-31 17:42:37.808  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 17:42:37.808  3270  3328 I jxcore-log: 
,03-31 17:42:37.811  3270  3328 I jxcore-log: # 42. #startListeningForAdvertisements should fail if start not called
03-31 17:42:37.811  3270  3328 I jxcore-log: 
,03-31 17:42:37.814  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 17:42:37.814  3270  3328 I jxcore-log: 
,03-31 17:42:38.016  2163  2210 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-31 17:42:38.092  3270  3328 I jxcore-log: ok 180 specific error should be returned
03-31 17:42:38.092  3270  3328 I jxcore-log: 
,03-31 17:42:38.099  3270  3328 I jxcore-log: # teardown
03-31 17:42:38.099  3270  3328 I jxcore-log: 
,03-31 17:42:39.406  3270  3328 I jxcore-log: ok 181 must be stopped
03-31 17:42:39.406  3270  3328 I jxcore-log: 
,03-31 17:42:39.412  3270  3328 I jxcore-log: # setup
03-31 17:42:39.412  3270  3328 I jxcore-log: 
,03-31 17:42:39.594  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 17:42:39.594  3270  3328 I jxcore-log: 
,03-31 17:42:39.598  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 17:42:39.598  3270  3328 I jxcore-log: 
,03-31 17:42:39.611  3270  3328 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 17:42:39.611  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 17:42:39.611  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 17:42:39.611  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 17:42:39.611  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 17:42:39.611  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 17:42:39.611  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 17:42:39.611  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 17:42:39.616  3270  3328 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 17:42:39.620  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 17:42:39.620  3270  3328 I jxcore-log: 
,03-31 17:42:39.623  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 17:42:39.623  3270  3328 I jxcore-log: 
,03-31 17:42:39.629  3270  3328 I jxcore-log: # 43. #startUpdateAdvertisingAndListening should fail if start not called
03-31 17:42:39.629  3270  3328 I jxcore-log: 
,03-31 17:42:39.633  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 17:42:39.633  3270  3328 I jxcore-log: 
,03-31 17:42:41.972  2163  2205 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,03-31 17:42:42.375  2163  2219 E bt-btm  : btm_sec_disconnected - Clearing Pending flag
,03-31 17:42:42.381  2163  2163 D BluetoothMapService: onReceive
,03-31 17:42:42.412  3755  3755 I BTConnectionReceiver: onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,03-31 17:42:42.417  3755  3755 I BluetoothClassifier: Bluetooth Device Name: Note4-1
,03-31 17:42:42.481  3270  3328 I jxcore-log: ok 182 specific error should be returned
03-31 17:42:42.481  3270  3328 I jxcore-log: 
03-31 17:42:42.483  3270  3328 I jxcore-log: # teardown
03-31 17:42:42.483  3270  3328 I jxcore-log: 
,03-31 17:42:42.664  3270  3328 I jxcore-log: ok 183 must be stopped
03-31 17:42:42.664  3270  3328 I jxcore-log: 
,03-31 17:42:42.672  3270  3328 I jxcore-log: # setup
,03-31 17:42:42.672  3270  3328 I jxcore-log: 
,03-31 17:42:43.293  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,03-31 17:42:43.293  3270  3328 I jxcore-log: 
03-31 17:42:43.294  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 17:42:43.294  3270  3328 I jxcore-log: 
,03-31 17:42:43.304  3270  3328 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 17:42:43.304  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 17:42:43.304  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 17:42:43.304  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 17:42:43.304  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 17:42:43.304  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 17:42:43.304  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 17:42:43.304  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 17:42:43.306  3270  3328 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
03-31 17:42:43.308  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 17:42:43.308  3270  3328 I jxcore-log: 
03-31 17:42:43.309  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 17:42:43.309  3270  3328 I jxcore-log: 
,03-31 17:42:43.318  3270  3328 I jxcore-log: # 44. should be able to call #stopListeningForAdvertisements many times,
03-31 17:42:43.318  3270  3328 I jxcore-log: 
,03-31 17:42:43.322  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"},
03-31 17:42:43.322  3270  3328 I jxcore-log: 
,03-31 17:42:43.519  3270  3328 I jxcore-log: DEBUG createNativeListener: creating native server,
03-31 17:42:43.519  3270  3328 I jxcore-log: 
,03-31 17:42:43.521  3270  3328 I jxcore-log: DEBUG createNativeListener: listening 42829,
03-31 17:42:43.521  3270  3328 I jxcore-log: 
03-31 17:42:43.523  3270  3328 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements,
03-31 17:42:43.523  3270  3328 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 17:42:43.523  3270  3328 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
03-31 17:42:43.525  3270  3328 I jxcore-log: ok 184 no errors,
03-31 17:42:43.525  3270  3328 I jxcore-log: 
03-31 17:42:43.526  3270  3328 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-31 17:42:43.526  3270  3328 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only,
03-31 17:42:43.526  3270  3328 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-31 17:42:43.528  3270  3328 I jxcore-log: ok 185 still no errors
03-31 17:42:43.528  3270  3328 I jxcore-log: ,
03-31 17:42:43.535  3270  3328 I jxcore-log: # teardown
03-31 17:42:43.535  3270  3328 I jxcore-log: 
,03-31 17:42:44.530  3270  3328 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 17:42:44.531  3270  3328 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 17:42:44.531  3270  3328 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 17:42:44.532  3270  3328 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements,
03-31 17:42:44.532  3270  3328 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 17:42:44.532  3270  3328 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 17:42:44.537  3270  3328 I jxcore-log: ok 186 must be stopped
03-31 17:42:44.537  3270  3328 I jxcore-log: 
03-31 17:42:44.543  3270  3328 I jxcore-log: # setup
03-31 17:42:44.543  3270  3328 I jxcore-log: 
,03-31 17:42:44.728  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 17:42:44.728  3270  3328 I jxcore-log: 
,03-31 17:42:44.732  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 17:42:44.732  3270  3328 I jxcore-log: 
,03-31 17:42:44.740  3270  3328 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 17:42:44.740  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 17:42:44.740  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 17:42:44.740  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 17:42:44.740  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 17:42:44.740  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 17:42:44.740  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 17:42:44.740  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 17:42:44.745  3270  3328 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 17:42:44.746  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 17:42:44.746  3270  3328 I jxcore-log: 
03-31 17:42:44.748  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 17:42:44.748  3270  3328 I jxcore-log: 
,03-31 17:42:44.751  3270  3328 I jxcore-log: # 45. should be able to call #startListeningForAdvertisements many times
03-31 17:42:44.751  3270  3328 I jxcore-log: 
,03-31 17:42:44.752  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 17:42:44.752  3270  3328 I jxcore-log: 
,03-31 17:42:44.882  3270  3328 I jxcore-log: DEBUG createNativeListener: creating native server,
03-31 17:42:44.882  3270  3328 I jxcore-log: 
03-31 17:42:44.884  3270  3328 I jxcore-log: DEBUG createNativeListener: listening 53479
03-31 17:42:44.884  3270  3328 I jxcore-log: 
,03-31 17:42:44.890  3270  3328 I io.jxcore.node.ConnectionHelper: start: Port number: 54014, start advertisements: false
03-31 17:42:44.890  3270  3328 I io.jxcore.node.ConnectionHelper: restoreDefaultBleDiscoverySettings: Powering the BLE discovery back up
,03-31 17:42:44.890  3270  3328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 0 -> 2
03-31 17:42:44.890  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-31 17:42:44.890  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-31 17:42:44.890  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-31 17:42:44.890  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-31 17:42:44.890  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-31 17:42:44.890  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-31 17:42:44.890  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 1, timeout: 0, is connectable: false
03-31 17:42:44.890  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-31 17:42:44.891  3270  3328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 1 -> 3
03-31 17:42:44.891  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-31 17:42:44.891  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-31 17:42:44.891  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-31 17:42:44.891  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-31 17:42:44.891  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-31 17:42:44.891  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-31 17:42:44.891  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-31 17:42:44.891  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-31 17:42:44.891  3270  3328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 0 -> 2
03-31 17:42:44.891  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-31 17:42:44.891  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-31 17:42:44.891  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-31 17:42:44.891  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-31 17:42:44.891  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-31 17:42:44.891  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-31 17:42:44.891  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-31 17:42:44.891  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-31 17:42:44.891  3270  3328 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 17:42:44.891  3270  3328 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-31 17:42:44.891  3270  3328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-31 17:42:44.898  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-31 17:42:44.898  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 17:42:44.899  3270  3328 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 17:42:44.906  2163  2183 D BtGatt.GattService: registerClient() - UUID=b25035ad-8097-47ca-aaa3-7b7728e8107e
,03-31 17:42:44.906  2163  2207 D BtGatt.GattService: onClientRegistered() - UUID=b25035ad-8097-47ca-aaa3-7b7728e8107e, clientIf=5
03-31 17:42:44.907  3270  3287 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-31 17:42:44.909  2163  2181 D BtGatt.GattService: start scan with filters
,03-31 17:42:44.910  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-31 17:42:44.911  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 17:42:44.911  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-31 17:42:44.911  3270  3328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-31 17:42:44.911  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 17:42:44.911  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-31 17:42:44.911   823  1412 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 17:42:44.911  3270  3270 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-31 17:42:44.912  2163  2218 D BtGatt.ScanManager: handling starting scan
,03-31 17:42:44.916  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-31 17:42:44.916  3270  3328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-31 17:42:44.917  3270  3328 I io.jxcore.node.ConnectionHelper: start: OK
03-31 17:42:44.918  3270  3270 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only,
03-31 17:42:44.918  3270  3270 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-31 17:42:44.918  3270  3270 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false,
03-31 17:42:44.920  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 17:42:44.920  3270  3328 I jxcore-log: 
03-31 17:42:44.922  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 17:42:44.922  3270  3328 I jxcore-log: 
03-31 17:42:44.923  3270  3328 I jxcore-log: ok 187 no errors
,03-31 17:42:44.923  3270  3328 I jxcore-log: 
03-31 17:42:44.924  2163  2207 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-31 17:42:44.924  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:42:44.926  2163  2207 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-31 17:42:44.927  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
03-31 17:42:44.927  2163  2218 D BtGatt.ScanManager: Starting BLE batch scan
03-31 17:42:44.927  2163  2218 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-31 17:42:44.928  3270  3328 I io.jxcore.node.ConnectionHelper: start: Port number: 54014, start advertisements: false
03-31 17:42:44.928  3270  3328 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 17:42:44.928  3270  3328 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-31 17:42:44.928  3270  3328 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-31 17:42:44.928  3270  3328 I io.jxcore.node.ConnectionHelper: start: OK
03-31 17:42:44.930  3270  3328 I jxcore-log: ok 188 still no errors
03-31 17:42:44.930  3270  3328 I jxcore-log: 
03-31 17:42:44.931  2163  2207 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0,
03-31 17:42:44.931  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:42:44.933  2163  2207 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-31 17:42:44.933  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 17:42:44.938  3270  3328 I jxcore-log: # teardown,
03-31 17:42:44.938  3270  3328 I jxcore-log: 
,03-31 17:42:45.318  3270  3328 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 17:42:45.318  3270  3328 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
03-31 17:42:45.319  3270  3328 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
03-31 17:42:45.319  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-31 17:42:45.319  3270  3328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-31 17:42:45.319  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-31 17:42:45.319  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode,
03-31 17:42:45.319  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-31 17:42:45.319  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-31 17:42:45.324  2163  2183 D BtGatt.GattService: stopScan() - queue size =1
03-31 17:42:45.326  2163  2181 D BtGatt.GattService: unregisterClient() - clientIf=5
03-31 17:42:45.327  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 17:42:45.327  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-31 17:42:45.327  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-31 17:42:45.328  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-31 17:42:45.328  3270  3328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-31 17:42:45.328  2163  2207 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-31 17:42:45.328  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 17:42:45.328  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 17:42:45.328  2163  2218 D BtGatt.ScanManager: stopping BLe Batch
03-31 17:42:45.332  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-31 17:42:45.332  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-31 17:42:45.332  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...,
,03-31 17:42:45.333  2163  2207 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-31 17:42:45.334  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:42:45.334  2163  2218 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-31 17:42:45.336  2163  2207 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-31 17:42:45.336  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:42:45.336  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-31 17:42:45.336  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 17:42:45.336  3270  3270 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 17:42:45.336  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-31 17:42:45.336  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-31 17:42:45.347  3270  3270 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
03-31 17:42:45.348   823   841 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 17:42:45.355  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-31 17:42:45.356  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-31 17:42:45.356  3270  3270 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-31 17:42:45.360  3270  3270 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-31 17:42:45.361  3270  3270 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 17:42:45.361  3270  3270 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 17:42:45.361  3270  3270 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-31 17:42:45.362  3270  3328 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-31 17:42:45.362  3270  3328 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 17:42:45.362  3270  3328 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-31 17:42:45.363  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 17:42:45.363  3270  3328 I jxcore-log: 
,03-31 17:42:45.364  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 17:42:45.364  3270  3328 I jxcore-log: 
03-31 17:42:45.368  3270  3328 I jxcore-log: ok 189 must be stopped
03-31 17:42:45.368  3270  3328 I jxcore-log: 
,03-31 17:42:45.374  3270  3328 I jxcore-log: # setup
,03-31 17:42:45.374  3270  3328 I jxcore-log: 
,03-31 17:42:45.701  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 17:42:45.701  3270  3328 I jxcore-log: 
03-31 17:42:45.702  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 17:42:45.702  3270  3328 I jxcore-log: 
,03-31 17:42:45.710  3270  3328 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 17:42:45.710  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 17:42:45.710  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 17:42:45.710  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 17:42:45.710  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 17:42:45.710  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 17:42:45.710  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 17:42:45.710  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 17:42:45.715  3270  3328 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 17:42:45.716  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 17:42:45.716  3270  3328 I jxcore-log: 
,03-31 17:42:45.718  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 17:42:45.718  3270  3328 I jxcore-log: 
,03-31 17:42:45.721  3270  3328 I jxcore-log: # 46. should be able to call #startUpdateAdvertisingAndListening many times
03-31 17:42:45.721  3270  3328 I jxcore-log: 
,03-31 17:42:45.723  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 17:42:45.723  3270  3328 I jxcore-log: 
,03-31 17:42:48.173  3270  3328 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 17:42:48.173  3270  3328 I jxcore-log: 
03-31 17:42:48.175  3270  3328 I jxcore-log: DEBUG createNativeListener: listening 52827
03-31 17:42:48.175  3270  3328 I jxcore-log: 
,03-31 17:42:48.182  3270  3328 I io.jxcore.node.ConnectionHelper: start: Port number: 52827, start advertisements: true
03-31 17:42:48.182  3270  3328 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 17:42:48.182  3270  3328 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-31 17:42:48.182  3270  3328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-31 17:42:48.187  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser,
03-31 17:42:48.187  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-31 17:42:48.187  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-31 17:42:48.188  3270  3328 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-31 17:42:48.192  2163  2181 D BtGatt.GattService: registerClient() - UUID=bf15d854-027d-4798-9549-07675f2a436f
,03-31 17:42:48.192  2163  2207 D BtGatt.GattService: onClientRegistered() - UUID=bf15d854-027d-4798-9549-07675f2a436f, clientIf=5
03-31 17:42:48.193  3270  3287 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-31 17:42:48.193  2163  2209 D BtGatt.GattService: start scan with filters
,03-31 17:42:48.194  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-31 17:42:48.194  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-31 17:42:48.194  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,03-31 17:42:48.194  3270  3328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-31 17:42:48.194  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 17:42:48.194  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...,
03-31 17:42:48.194  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-31 17:42:48.194  2163  2218 D BtGatt.ScanManager: handling starting scan
03-31 17:42:48.194  3270  3328 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61,
03-31 17:42:48.194  3270  3270 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false,
03-31 17:42:48.195  3270  3328 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-31 17:42:48.195  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 17:42:48.195  3270  3328 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...,
03-31 17:42:48.201  2163  2209 D BtGatt.GattService: registerClient() - UUID=614cf17a-69bb-4e0c-9c71-4b804b39b758
03-31 17:42:48.204  2163  2207 D BtGatt.GattService: onClientRegistered() - UUID=614cf17a-69bb-4e0c-9c71-4b804b39b758, clientIf=6
03-31 17:42:48.204  3270  3288 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-31 17:42:48.205  2163  2217 D BtGatt.AdvertiseManager: message : 0
,03-31 17:42:48.205  2163  2207 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,03-31 17:42:48.206  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:42:48.208  2163  2207 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-31 17:42:48.208  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:42:48.208  2163  2218 D BtGatt.ScanManager: Starting BLE batch scan
,03-31 17:42:48.208  2163  2218 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-31 17:42:48.211  2163  2207 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-31 17:42:48.211  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 17:42:48.215  2163  2207 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,03-31 17:42:48.216  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:42:48.217  2163  2217 D BtGatt.AdvertiseManager: starting multi advertising
,03-31 17:42:48.221  2163  2207 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-31 17:42:48.223  2163  2207 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-31 17:42:48.223  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-31 17:42:48.223  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-31 17:42:48.224   823  1149 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 17:42:48.226  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-31 17:42:48.226  3270  3328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-31 17:42:48.227  3270  3328 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-31 17:42:48.227  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 17:42:48.227  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-31 17:42:48.228  3270  3328 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,03-31 17:42:48.228  3270  3328 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-31 17:42:48.228  3270  3328 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-31 17:42:48.228  3270  3328 I io.jxcore.node.ConnectionHelper: start: OK
03-31 17:42:48.228  3270  3270 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,03-31 17:42:48.228  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-31 17:42:48.228  3270  3270 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-31 17:42:48.228  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,03-31 17:42:48.228  3270  3270 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-31 17:42:48.228  3270  3270 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-31 17:42:48.228  3270  3270 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-31 17:42:48.229  3270  3270 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 17:42:48.229  3270  3270 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-31 17:42:48.229  3270  3270 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 17:42:48.229  3270  3270 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-31 17:42:48.229   823  1411 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 17:42:48.229  3270  3270 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-31 17:42:48.230  3270  3818 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-31 17:42:48.232  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 17:42:48.232  3270  3328 I jxcore-log: 
03-31 17:42:48.232  3270  3818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
03-31 17:42:48.235  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 17:42:48.235  3270  3328 I jxcore-log: 
03-31 17:42:48.235  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-31 17:42:48.235  3270  3328 I jxcore-log: 
03-31 17:42:48.237  3270  3328 I jxcore-log: ok 190 no errors
03-31 17:42:48.237  3270  3328 I jxcore-log: 
,03-31 17:42:48.241  3270  3328 I io.jxcore.node.ConnectionHelper: start: Port number: 52827, start advertisements: true
03-31 17:42:48.241  3270  3328 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-31 17:42:48.241  3270  3328 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-31 17:42:48.241  3270  3328 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 17:42:48.241  3270  3328 I io.jxcore.node.ConnectionHelper: start: OK
,03-31 17:42:48.243  3270  3328 I jxcore-log: ok 191 still no errors
03-31 17:42:48.243  3270  3328 I jxcore-log: 
03-31 17:42:48.249  3270  3328 I jxcore-log: # teardown
03-31 17:42:48.249  3270  3328 I jxcore-log: 
,03-31 17:42:49.221  2163  2163 D BtGatt.ScanManager: awakened up at time 258641
,03-31 17:42:49.223  2163  2218 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-31 17:42:49.233  2163  2207 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-31 17:42:49.233  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:42:49.233  2163  2207 D BtGatt.GattService: current time is 258653178650
03-31 17:42:49.233  2163  2207 D BtGatt.GattService: Batch record : [-98, -84, 121, -15, -46, 101, 1, -128, -77, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -70, 8, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-31 17:42:49.234  2163  2207 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,03-31 17:42:49.235  2163  2207 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-31 17:42:49.238  3270  3270 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> E0:DB:10:14:E2:C0], added - the peer count is 1
03-31 17:42:49.239  3270  3270 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 2
03-31 17:42:49.239  3270  3270 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> E0:DB:10:14:E2:C0], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 
03-31 17:42:49.240  3270  3270 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
,03-31 17:42:49.244  3270  3328 I jxcore-log: DEBUG createPeerListener: createPeerListener
03-31 17:42:49.244  3270  3328 I jxcore-log: 
03-31 17:42:49.248  3270  3328 I jxcore-log: DEBUG createPeerListener: pleaseConnect= false
03-31 17:42:49.248  3270  3328 I jxcore-log: 
03-31 17:42:49.251  3270  3328 I jxcore-log: DEBUG createPeerListener: createPeerListener
03-31 17:42:49.251  3270  3328 I jxcore-log: 
,03-31 17:42:49.254  3270  3328 I jxcore-log: DEBUG createPeerListener: pleaseConnect= false
03-31 17:42:49.254  3270  3328 I jxcore-log: 
,03-31 17:42:49.374  3270  3328 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 17:42:49.374  3270  3328 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-31 17:42:49.375  3270  3328 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-31 17:42:49.375  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,03-31 17:42:49.375  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-31 17:42:49.375  3270  3328 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-31 17:42:49.375  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-31 17:42:49.375  3270  3818 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
,03-31 17:42:49.375  3270  3328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-31 17:42:49.376  3270  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-31 17:42:49.376  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-31 17:42:49.376  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,03-31 17:42:49.376  3270  3818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-31 17:42:49.376  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-31 17:42:49.376  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-31 17:42:49.382  2163  2181 D BtGatt.GattService: stopScan() - queue size =1
03-31 17:42:49.385  2163  2181 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-31 17:42:49.387  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-31 17:42:49.387  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 17:42:49.387  2163  2207 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-31 17:42:49.387  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-31 17:42:49.387  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:42:49.387  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-31 17:42:49.388  3270  3328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-31 17:42:49.388  2163  2218 D BtGatt.ScanManager: stopping BLe Batch
03-31 17:42:49.388  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-31 17:42:49.388  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-31 17:42:49.391  2163  2207 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-31 17:42:49.391  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
03-31 17:42:49.391  2163  2217 D BtGatt.AdvertiseManager: message : 1,
03-31 17:42:49.393  2163  2218 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5,
03-31 17:42:49.394  2163  2217 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-31 17:42:49.396  2163  2207 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,03-31 17:42:49.396  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:42:49.396  2163  2207 D BtGatt.GattService: current time is 258816272192
,03-31 17:42:49.396  2163  2207 D BtGatt.GattService: Batch record : [-98, -84, 121, -15, -46, 101, 1, -128, -77, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,03-31 17:42:49.397  2163  2207 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81],
03-31 17:42:49.398  2163  2207 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-31 17:42:49.398  2163  2207 D BtGatt.GattService: Client app is not null!,
03-31 17:42:49.399  2163  2209 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-31 17:42:49.399  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-31 17:42:49.399  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-31 17:42:49.399  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-31 17:42:49.400  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-31 17:42:49.400  3270  3328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-31 17:42:49.400  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 17:42:49.400  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-31 17:42:49.400  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-31 17:42:49.401  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-31 17:42:49.401  3270  3328 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-31 17:42:49.401  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 17:42:49.402  3270  3270 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 17:42:49.402  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 17:42:49.402  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-31 17:42:49.412  3270  3270 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-31 17:42:49.413   823   842 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 17:42:49.426  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-31 17:42:49.427  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-31 17:42:49.427  3270  3270 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-31 17:42:49.427  3270  3270 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-31 17:42:49.427  3270  3270 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-31 17:42:49.432  3270  3270 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-31 17:42:49.432  3270  3270 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-31 17:42:49.432  3270  3270 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-31 17:42:49.432  3270  3270 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-31 17:42:49.432  3270  3270 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 17:42:49.432  3270  3270 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-31 17:42:49.433  3270  3328 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-31 17:42:49.433  3270  3328 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 17:42:49.433  3270  3328 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-31 17:42:49.435  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-31 17:42:49.435  3270  3328 I jxcore-log: 
03-31 17:42:49.436  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 17:42:49.436  3270  3328 I jxcore-log: 
,03-31 17:42:49.436  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 17:42:49.436  3270  3328 I jxcore-log: 
03-31 17:42:49.442  3270  3328 I jxcore-log: ok 192 must be stopped
03-31 17:42:49.442  3270  3328 I jxcore-log: 
,03-31 17:42:49.448  3270  3328 I jxcore-log: # setup
03-31 17:42:49.448  3270  3328 I jxcore-log: 
,03-31 17:42:50.053  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 17:42:50.053  3270  3328 I jxcore-log: 
,03-31 17:42:50.054  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 17:42:50.054  3270  3328 I jxcore-log: 
,03-31 17:42:50.062  3270  3328 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
03-31 17:42:50.062  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 17:42:50.062  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 17:42:50.062  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 17:42:50.062  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 17:42:50.062  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 17:42:50.062  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 17:42:50.062  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 17:42:50.066  3270  3328 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
,03-31 17:42:50.069  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,03-31 17:42:50.069  3270  3328 I jxcore-log: 
,03-31 17:42:50.073  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,03-31 17:42:50.073  3270  3328 I jxcore-log: 
,03-31 17:42:50.079  3270  3328 I jxcore-log: # 47. should be able to call #stopAdvertisingAndListening many times
,03-31 17:42:50.079  3270  3328 I jxcore-log: 
,03-31 17:42:50.083  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
,03-31 17:42:50.083  3270  3328 I jxcore-log: 
,03-31 17:42:50.230  3270  3328 I jxcore-log: DEBUG createNativeListener: creating native server,
03-31 17:42:50.230  3270  3328 I jxcore-log: 
03-31 17:42:50.233  3270  3328 I jxcore-log: DEBUG createNativeListener: listening 59359
03-31 17:42:50.233  3270  3328 I jxcore-log: 
,03-31 17:42:50.237  3270  3328 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-31 17:42:50.237  3270  3328 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 17:42:50.237  3270  3328 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 17:42:50.241  3270  3328 I jxcore-log: ok 193 no errors
03-31 17:42:50.241  3270  3328 I jxcore-log: 
,03-31 17:42:50.243  3270  3328 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-31 17:42:50.244  3270  3328 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-31 17:42:50.244  3270  3328 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-31 17:42:50.246  3270  3328 I jxcore-log: ok 194 still no errors
03-31 17:42:50.246  3270  3328 I jxcore-log: 
,03-31 17:42:50.252  3270  3328 I jxcore-log: # teardown,
03-31 17:42:50.252  3270  3328 I jxcore-log: 
,03-31 17:42:50.361  3270  3328 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 17:42:50.361  3270  3328 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 17:42:50.361  3270  3328 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
03-31 17:42:50.362  3270  3328 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-31 17:42:50.362  3270  3328 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 17:42:50.362  3270  3328 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
,03-31 17:42:50.368  3270  3328 I jxcore-log: ok 195 must be stopped,
03-31 17:42:50.368  3270  3328 I jxcore-log: 
,03-31 17:42:50.377  3270  3328 I jxcore-log: # setup
03-31 17:42:50.377  3270  3328 I jxcore-log: ,
,03-31 17:42:50.519  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,03-31 17:42:50.519  3270  3328 I jxcore-log: 
03-31 17:42:50.522  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 17:42:50.522  3270  3328 I jxcore-log: 
,03-31 17:42:50.532  3270  3328 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 17:42:50.532  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true,
03-31 17:42:50.532  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 17:42:50.532  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 17:42:50.532  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 17:42:50.532  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 17:42:50.532  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 17:42:50.532  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 17:42:50.538  3270  3328 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 17:42:50.542  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,03-31 17:42:50.542  3270  3328 I jxcore-log: 
,03-31 17:42:50.546  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,03-31 17:42:50.546  3270  3328 I jxcore-log: 
,03-31 17:42:50.553  3270  3328 I jxcore-log: # 48. can get the network status before starting
,03-31 17:42:50.553  3270  3328 I jxcore-log: 
,03-31 17:42:50.557  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
,03-31 17:42:50.557  3270  3328 I jxcore-log: 
,03-31 17:42:50.682  3270  3328 I jxcore-log: ok 196 network status should have certain non-empty properties
03-31 17:42:50.682  3270  3328 I jxcore-log: 
,03-31 17:42:50.684  3270  3328 I jxcore-log: # teardown
03-31 17:42:50.684  3270  3328 I jxcore-log: 
,03-31 17:42:50.840  3270  3328 I jxcore-log: ok 197 must be stopped
03-31 17:42:50.840  3270  3328 I jxcore-log: 
,03-31 17:42:50.843  3270  3328 I jxcore-log: # setup
03-31 17:42:50.843  3270  3328 I jxcore-log: 
,03-31 17:42:50.958  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 17:42:50.958  3270  3328 I jxcore-log: 
,03-31 17:42:50.962  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native,
03-31 17:42:50.962  3270  3328 I jxcore-log: 
,03-31 17:42:50.970  3270  3328 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 17:42:50.970  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 17:42:50.970  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 17:42:50.970  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 17:42:50.970  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 17:42:50.970  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 17:42:50.970  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 17:42:50.970  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 17:42:50.974  3270  3328 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
,03-31 17:42:50.975  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native,
,03-31 17:42:50.975  3270  3328 I jxcore-log: 
,03-31 17:42:50.977  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native,
03-31 17:42:50.977  3270  3328 I jxcore-log: ,
03-31 17:42:50.980  3270  3328 I jxcore-log: # 49. error returned with bad router
,03-31 17:42:50.980  3270  3328 I jxcore-log: 
03-31 17:42:50.981  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 17:42:50.981  3270  3328 I jxcore-log: 
,03-31 17:42:51.128  3270  3328 I jxcore-log: ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a string
03-31 17:42:51.128  3270  3328 I jxcore-log: 
,03-31 17:42:51.131  3270  3328 I jxcore-log: ok 198 specific error expected
03-31 17:42:51.131  3270  3328 I jxcore-log: 
,03-31 17:42:51.134  3270  3328 I jxcore-log: # teardown
03-31 17:42:51.134  3270  3328 I jxcore-log: 
,03-31 17:42:51.253  3270  3328 I jxcore-log: ok 199 must be stopped
03-31 17:42:51.253  3270  3328 I jxcore-log: 
,03-31 17:42:51.261  3270  3328 I jxcore-log: # setup
03-31 17:42:51.261  3270  3328 I jxcore-log: 
,03-31 17:42:51.368  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 17:42:51.368  3270  3328 I jxcore-log: 
,03-31 17:42:51.372  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 17:42:51.372  3270  3328 I jxcore-log: 
,03-31 17:42:51.384  3270  3328 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
,03-31 17:42:51.384  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 17:42:51.384  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 17:42:51.384  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 17:42:51.384  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 17:42:51.384  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 17:42:51.384  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 17:42:51.384  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 17:42:51.387  3270  3328 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 17:42:51.389  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 17:42:51.389  3270  3328 I jxcore-log: 
,03-31 17:42:51.390  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 17:42:51.390  3270  3328 I jxcore-log: 
,03-31 17:42:51.393  3270  3328 I jxcore-log: # 50. all services are stopped when we call stop
03-31 17:42:51.393  3270  3328 I jxcore-log: 
03-31 17:42:51.395  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 17:42:51.395  3270  3328 I jxcore-log: 
,03-31 17:42:51.590  3270  3328 I jxcore-log: DEBUG createNativeListener: creating native server
,03-31 17:42:51.590  3270  3328 I jxcore-log: 
,03-31 17:42:51.593  3270  3328 I jxcore-log: DEBUG createNativeListener: listening 50270
,03-31 17:42:51.593  3270  3328 I jxcore-log: 
,03-31 17:42:51.602  3270  3328 I io.jxcore.node.ConnectionHelper: start: Port number: 52827, start advertisements: false
,03-31 17:42:51.602  3270  3328 V io.jxcore.node.ConnectivityMonitor: start: Already started,
,03-31 17:42:51.602  3270  3328 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,03-31 17:42:51.602  3270  3328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-31 17:42:51.607  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...,
03-31 17:42:51.607  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 17:42:51.608  3270  3328 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 17:42:51.614  2163  2958 D BtGatt.GattService: registerClient() - UUID=29943e2a-5442-478f-8e50-b4d174016981
,03-31 17:42:51.614  2163  2207 D BtGatt.GattService: onClientRegistered() - UUID=29943e2a-5442-478f-8e50-b4d174016981, clientIf=5
,03-31 17:42:51.615  3270  3287 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5,
03-31 17:42:51.616  2163  2209 D BtGatt.GattService: start scan with filters
,03-31 17:42:51.618  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-31 17:42:51.618  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 17:42:51.618  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,03-31 17:42:51.618  3270  3328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-31 17:42:51.618  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 17:42:51.618  2163  2218 D BtGatt.ScanManager: handling starting scan
03-31 17:42:51.619  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-31 17:42:51.619  3270  3270 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-31 17:42:51.620   823  1150 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 17:42:51.627  2163  2207 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,03-31 17:42:51.627  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-31 17:42:51.627  3270  3328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-31 17:42:51.627  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:42:51.628  3270  3328 I io.jxcore.node.ConnectionHelper: start: OK
,03-31 17:42:51.628  3270  3270 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,03-31 17:42:51.628  3270  3270 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 17:42:51.628  3270  3270 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-31 17:42:51.629  2163  2207 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-31 17:42:51.630  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:42:51.630  2163  2218 D BtGatt.ScanManager: Starting BLE batch scan
,03-31 17:42:51.630  2163  2218 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-31 17:42:51.630  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 17:42:51.630  3270  3328 I jxcore-log: ,
03-31 17:42:51.631  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 17:42:51.631  3270  3328 I jxcore-log: 
03-31 17:42:51.633  2163  2207 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0,
03-31 17:42:51.633  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:42:51.635  2163  2207 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,03-31 17:42:51.635  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 17:42:51.642  3270  3328 I io.jxcore.node.ConnectionHelper: start: Port number: 50270, start advertisements: true,
03-31 17:42:51.642  3270  3328 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 17:42:51.643  3270  3328 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,03-31 17:42:51.643  3270  3328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-31 17:42:51.648  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-31 17:42:51.649  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
,03-31 17:42:51.649  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...,
03-31 17:42:51.649  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-31 17:42:51.649  3270  3328 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-31 17:42:51.649  3270  3328 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-31 17:42:51.650  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 17:42:51.650  3270  3328 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-31 17:42:51.657  2163  2209 D BtGatt.GattService: registerClient() - UUID=a8571214-df1b-4406-b2cd-7d7175393c80
,03-31 17:42:51.658  2163  2207 D BtGatt.GattService: onClientRegistered() - UUID=a8571214-df1b-4406-b2cd-7d7175393c80, clientIf=6
,03-31 17:42:51.658  3270  3288 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-31 17:42:51.660  2163  2217 D BtGatt.AdvertiseManager: message : 0
,03-31 17:42:51.666  2163  2217 D BtGatt.AdvertiseManager: starting multi advertising
,03-31 17:42:51.671  2163  2207 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-31 17:42:51.675  2163  2207 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-31 17:42:51.676  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-31 17:42:51.676  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-31 17:42:51.676  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,03-31 17:42:51.676  3270  3270 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-31 17:42:51.676  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-31 17:42:51.676  3270  3270 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
,03-31 17:42:51.676  3270  3270 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-31 17:42:51.677   823  1411 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 17:42:51.684  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true,
,03-31 17:42:51.685  3270  3328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-31 17:42:51.685  3270  3328 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections,
03-31 17:42:51.685  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-31 17:42:51.685  3270  3270 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-31 17:42:51.687  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-31 17:42:51.687  3270  3328 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,03-31 17:42:51.687  3270  3328 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-31 17:42:51.688  3270  3328 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-31 17:42:51.688  3270  3328 I io.jxcore.node.ConnectionHelper: start: OK
,03-31 17:42:51.688  3270  3270 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-31 17:42:51.688  3270  3270 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 17:42:51.688  3270  3270 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,03-31 17:42:51.692   823  1150 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-31 17:42:51.694  3270  3819 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-31 17:42:51.698  3270  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-31 17:42:51.699  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-31 17:42:51.699  3270  3328 I jxcore-log: 
,03-31 17:42:51.711  3270  3328 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 17:42:51.711  3270  3328 I jxcore-log: 
,03-31 17:42:51.717  3270  3328 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 17:42:51.717  3270  3328 I jxcore-log: 
,03-31 17:42:51.721  3270  3328 I jxcore-log: DEBUG createNativeListener: new mux
03-31 17:42:51.721  3270  3328 I jxcore-log: 
,03-31 17:42:51.725  3270  3328 I jxcore-log: ok 200 connection to servers manager should succeed after starting,
03-31 17:42:51.725  3270  3328 I jxcore-log: 
,03-31 17:42:51.745  3270  3328 I jxcore-log: ok 201 connection to router server should succeed after starting
,03-31 17:42:51.745  3270  3328 I jxcore-log: 
,03-31 17:42:51.747  3270  3328 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 17:42:51.747  3270  3328 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-31 17:42:51.747  3270  3328 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-31 17:42:51.747  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-31 17:42:51.747  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-31 17:42:51.747  3270  3328 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-31 17:42:51.747  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-31 17:42:51.748  3270  3328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-31 17:42:51.748  3270  3819 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-31 17:42:51.748  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,03-31 17:42:51.748  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-31 17:42:51.748  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-31 17:42:51.748  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-31 17:42:51.748  3270  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-31 17:42:51.748  3270  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,03-31 17:42:51.750  2163  2958 D BtGatt.GattService: stopScan() - queue size =1
03-31 17:42:51.753  2163  2207 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-31 17:42:51.753  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:42:51.753  2163  2218 D BtGatt.ScanManager: stopping BLe Batch
03-31 17:42:51.753  2163  2183 D BtGatt.GattService: unregisterClient() - clientIf=5
03-31 17:42:51.754  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-31 17:42:51.754  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 17:42:51.754  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false,
03-31 17:42:51.754  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
,03-31 17:42:51.755  3270  3328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-31 17:42:51.755  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-31 17:42:51.755  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-31 17:42:51.756  2163  2207 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0,
03-31 17:42:51.756  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:42:51.756  2163  2218 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-31 17:42:51.757  2163  2217 D BtGatt.AdvertiseManager: message : 1
03-31 17:42:51.757  2163  2217 D BtGatt.AdvertiseManager: stop advertise for client 6
03-31 17:42:51.760  2163  2207 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,03-31 17:42:51.760  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:42:51.762  2163  2207 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-31 17:42:51.762  2163  2207 D BtGatt.GattService: Client app is not null!,
03-31 17:42:51.763  2163  2209 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-31 17:42:51.764  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-31 17:42:51.765  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,03-31 17:42:51.765  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-31 17:42:51.765  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-31 17:42:51.765  3270  3328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED],
03-31 17:42:51.765  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 17:42:51.765  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,03-31 17:42:51.765  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-31 17:42:51.766  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,03-31 17:42:51.766  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 17:42:51.766  3270  3270 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 17:42:51.766  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 17:42:51.766  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener,
03-31 17:42:51.771  3270  3328 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 17:42:51.771  3270  3328 I jxcore-log: 
,03-31 17:42:51.772  3270  3270 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-31 17:42:51.773   823   842 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 17:42:51.779  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
,03-31 17:42:51.780  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0,
03-31 17:42:51.780  3270  3270 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-31 17:42:51.784  3270  3270 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false,
03-31 17:42:51.784  3270  3270 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-31 17:42:51.784  3270  3270 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true,
03-31 17:42:51.784  3270  3270 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 17:42:51.785  3270  3270 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed,
03-31 17:42:51.785  3270  3270 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 17:42:51.785  3270  3270 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-31 17:42:51.785  3270  3270 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-31 17:42:51.788  3270  3328 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements,
03-31 17:42:51.788  3270  3328 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 17:42:51.788  3270  3328 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
03-31 17:42:51.790  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-31 17:42:51.790  3270  3328 I jxcore-log: 
,03-31 17:42:51.791  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 17:42:51.791  3270  3328 I jxcore-log: 
,03-31 17:42:51.792  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 17:42:51.792  3270  3328 I jxcore-log: 
,03-31 17:42:51.797  3270  3328 I jxcore-log: ok 202 is stopped after calling stop
03-31 17:42:51.797  3270  3328 I jxcore-log: 
,03-31 17:42:51.802  3270  3328 I jxcore-log: ok 203 connection to servers manager should fail after stopping
03-31 17:42:51.802  3270  3328 I jxcore-log: 
,03-31 17:42:51.806  3270  3328 I jxcore-log: ok 204 connection to router server should fail after stopping
03-31 17:42:51.806  3270  3328 I jxcore-log: 
,03-31 17:42:51.811  3270  3328 I jxcore-log: # teardown
03-31 17:42:51.811  3270  3328 I jxcore-log: 
,03-31 17:42:52.306  3270  3328 I jxcore-log: ok 205 must be stopped
03-31 17:42:52.306  3270  3328 I jxcore-log: 
,03-31 17:42:52.313  3270  3328 I jxcore-log: # setup
03-31 17:42:52.313  3270  3328 I jxcore-log: 
,03-31 17:42:52.454  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 17:42:52.454  3270  3328 I jxcore-log: 
,03-31 17:42:52.458  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 17:42:52.458  3270  3328 I jxcore-log: 
,03-31 17:42:52.468  3270  3328 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 17:42:52.468  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 17:42:52.468  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 17:42:52.468  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 17:42:52.468  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 17:42:52.468  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 17:42:52.468  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 17:42:52.468  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 17:42:52.471  3270  3328 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 17:42:52.472  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 17:42:52.472  3270  3328 I jxcore-log: 
03-31 17:42:52.474  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 17:42:52.474  3270  3328 I jxcore-log: 
,03-31 17:42:52.477  3270  3328 I jxcore-log: # 51. make sure terminateConnection is properly hooked up
03-31 17:42:52.477  3270  3328 I jxcore-log: 
,03-31 17:42:52.479  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 17:42:52.479  3270  3328 I jxcore-log: 
,03-31 17:42:52.577  3270  3328 I jxcore-log: ok 206 called with right arguments
03-31 17:42:52.577  3270  3328 I jxcore-log: 
,03-31 17:42:52.582  3270  3328 I jxcore-log: # teardown
03-31 17:42:52.582  3270  3328 I jxcore-log: 
,03-31 17:42:52.687  3270  3328 I jxcore-log: ok 207 must be stopped
03-31 17:42:52.687  3270  3328 I jxcore-log: 
,03-31 17:42:52.693  3270  3328 I jxcore-log: # setup
03-31 17:42:52.693  3270  3328 I jxcore-log: 
,03-31 17:42:52.898  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 17:42:52.898  3270  3328 I jxcore-log: 
,03-31 17:42:52.904  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 17:42:52.904  3270  3328 I jxcore-log: 
,03-31 17:42:52.917  3270  3328 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 17:42:52.917  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 17:42:52.917  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 17:42:52.917  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 17:42:52.917  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 17:42:52.917  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 17:42:52.917  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 17:42:52.917  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 17:42:52.920  3270  3328 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 17:42:52.922  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 17:42:52.922  3270  3328 I jxcore-log: 
,03-31 17:42:52.924  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 17:42:52.924  3270  3328 I jxcore-log: 
,03-31 17:42:52.928  3270  3328 I jxcore-log: # 52. make sure terminateListener is properly hooked up
03-31 17:42:52.928  3270  3328 I jxcore-log: 
,03-31 17:42:52.930  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 17:42:52.930  3270  3328 I jxcore-log: 
,03-31 17:42:53.233  3270  3328 I jxcore-log: ok 208 called with right arguments
03-31 17:42:53.233  3270  3328 I jxcore-log: 
,03-31 17:42:53.236  3270  3328 I jxcore-log: # teardown
03-31 17:42:53.236  3270  3328 I jxcore-log: 
,03-31 17:42:53.416  3270  3328 I jxcore-log: ok 209 must be stopped
03-31 17:42:53.416  3270  3328 I jxcore-log: 
,03-31 17:42:53.418  3270  3328 I jxcore-log: # setup
03-31 17:42:53.418  3270  3328 I jxcore-log: 
,03-31 17:42:53.577  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 17:42:53.577  3270  3328 I jxcore-log: 
,03-31 17:42:53.581  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 17:42:53.581  3270  3328 I jxcore-log: 
,03-31 17:42:53.595  3270  3328 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 17:42:53.595  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 17:42:53.595  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 17:42:53.595  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 17:42:53.595  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 17:42:53.595  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 17:42:53.595  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 17:42:53.595  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 17:42:53.601  3270  3328 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 17:42:53.605  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 17:42:53.605  3270  3328 I jxcore-log: 
,03-31 17:42:53.608  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 17:42:53.608  3270  3328 I jxcore-log: 
,03-31 17:42:53.615  3270  3328 I jxcore-log: # 53. make sure we actually call kill connections properly
03-31 17:42:53.615  3270  3328 I jxcore-log: 
03-31 17:42:53.619  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 17:42:53.619  3270  3328 I jxcore-log: 
,03-31 17:42:53.815  3270  3328 I jxcore-log: ok 210 specific error expected
03-31 17:42:53.815  3270  3328 I jxcore-log: 
,03-31 17:42:53.817  3270  3328 I jxcore-log: # teardown
03-31 17:42:53.817  3270  3328 I jxcore-log: 
,03-31 17:42:53.970  3270  3328 I jxcore-log: ok 211 must be stopped
03-31 17:42:53.970  3270  3328 I jxcore-log: 
,03-31 17:42:53.973  3270  3328 I jxcore-log: # setup
03-31 17:42:53.973  3270  3328 I jxcore-log: 
,03-31 17:42:54.184  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 17:42:54.184  3270  3328 I jxcore-log: 
,03-31 17:42:54.188  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 17:42:54.188  3270  3328 I jxcore-log: 
,03-31 17:42:54.197  3270  3328 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
03-31 17:42:54.197  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 17:42:54.197  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 17:42:54.197  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 17:42:54.197  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 17:42:54.197  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 17:42:54.197  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 17:42:54.197  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 17:42:54.200  3270  3328 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 17:42:54.202  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 17:42:54.202  3270  3328 I jxcore-log: 
03-31 17:42:54.204  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 17:42:54.204  3270  3328 I jxcore-log: 
,03-31 17:42:54.207  3270  3328 I jxcore-log: # 54. thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
03-31 17:42:54.207  3270  3328 I jxcore-log: 
,03-31 17:42:54.208  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 17:42:54.208  3270  3328 I jxcore-log: 
,03-31 17:42:54.430  3270  3328 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 17:42:54.430  3270  3328 I jxcore-log: 
,03-31 17:42:54.433  3270  3328 I jxcore-log: DEBUG createNativeListener: listening 54735
03-31 17:42:54.433  3270  3328 I jxcore-log: 
,03-31 17:42:54.435  3270  3328 I jxcore-log: INFO thaliMobileNativeWrapper: routerPortConnectionFailed - {"routerPort":51246,"error":{}}
03-31 17:42:54.435  3270  3328 I jxcore-log: 
,03-31 17:42:54.436  3270  3328 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-31 17:42:54.436  3270  3328 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 17:42:54.436  3270  3328 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 17:42:54.437  3270  3328 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-31 17:42:54.437  3270  3328 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 17:42:54.437  3270  3328 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 17:42:54.446  3270  3328 I jxcore-log: ok 212 failure reason is as expected
03-31 17:42:54.446  3270  3328 I jxcore-log: 
,03-31 17:42:54.447  3270  3328 I jxcore-log: ok 213 error description is as expected
03-31 17:42:54.447  3270  3328 I jxcore-log: 
03-31 17:42:54.447  3270  3328 I jxcore-log: ok 214 must be stopped
03-31 17:42:54.447  3270  3328 I jxcore-log: 
,03-31 17:42:54.452  3270  3328 I jxcore-log: # teardown
03-31 17:42:54.452  3270  3328 I jxcore-log: 
,03-31 17:42:55.173  3270  3328 I jxcore-log: ok 215 must be stopped
03-31 17:42:55.173  3270  3328 I jxcore-log: ,
03-31 17:42:55.174  3270  3328 I jxcore-log: # setup
03-31 17:42:55.174  3270  3328 I jxcore-log: 
,03-31 17:42:55.303  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 17:42:55.303  3270  3328 I jxcore-log: 
,03-31 17:42:55.307  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 17:42:55.307  3270  3328 I jxcore-log: 
,03-31 17:42:55.316  3270  3328 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 17:42:55.316  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 17:42:55.316  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 17:42:55.316  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 17:42:55.316  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 17:42:55.316  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 17:42:55.316  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 17:42:55.316  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 17:42:55.318  3270  3328 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 17:42:55.320  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 17:42:55.320  3270  3328 I jxcore-log: 
,03-31 17:42:55.321  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 17:42:55.321  3270  3328 I jxcore-log: 
,03-31 17:42:55.324  3270  3328 I jxcore-log: # 55. We repeat failedConnection event when we get it from thaliTcpServersManager
03-31 17:42:55.324  3270  3328 I jxcore-log: 
,03-31 17:42:55.326  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 17:42:55.326  3270  3328 I jxcore-log: 
,03-31 17:42:55.479  3270  3328 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 17:42:55.479  3270  3328 I jxcore-log: 
,03-31 17:42:55.481  3270  3328 I jxcore-log: DEBUG createNativeListener: listening 34242
03-31 17:42:55.481  3270  3328 I jxcore-log: 
,03-31 17:42:55.484  3270  3328 I jxcore-log: ok 216 peerIdentifier matches
03-31 17:42:55.484  3270  3328 I jxcore-log: 
,03-31 17:42:55.485  3270  3328 I jxcore-log: ok 217 error description matches
,03-31 17:42:55.485  3270  3328 I jxcore-log: 
03-31 17:42:55.488  3270  3328 I jxcore-log: # teardown
03-31 17:42:55.488  3270  3328 I jxcore-log: 
,03-31 17:42:55.634  3270  3328 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 17:42:55.635  3270  3328 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-31 17:42:55.635  3270  3328 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 17:42:55.638  3270  3328 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-31 17:42:55.638  3270  3328 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 17:42:55.638  3270  3328 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 17:42:55.648  3270  3328 I jxcore-log: ok 218 must be stopped
03-31 17:42:55.648  3270  3328 I jxcore-log: 
,03-31 17:42:55.665  3270  3328 I jxcore-log: # setup
03-31 17:42:55.665  3270  3328 I jxcore-log: 
,03-31 17:42:55.798  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 17:42:55.798  3270  3328 I jxcore-log: 
,03-31 17:42:55.800  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 17:42:55.800  3270  3328 I jxcore-log: 
,03-31 17:42:55.810  3270  3328 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 17:42:55.810  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 17:42:55.810  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 17:42:55.810  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 17:42:55.810  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 17:42:55.810  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 17:42:55.810  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 17:42:55.810  3270  3328 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 17:42:55.815  3270  3328 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 17:42:55.818  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,03-31 17:42:55.818  3270  3328 I jxcore-log: 
,03-31 17:42:55.822  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,03-31 17:42:55.822  3270  3328 I jxcore-log: 
,03-31 17:42:55.829  3270  3328 I jxcore-log: # 56. we successfully receive and replay discoveryAdvertisingStateUpdate
,03-31 17:42:55.829  3270  3328 I jxcore-log: 
,03-31 17:42:55.833  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
,03-31 17:42:55.833  3270  3328 I jxcore-log: 
,03-31 17:42:55.961  3270  3328 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 17:42:55.961  3270  3328 I jxcore-log: 
,03-31 17:42:55.964  3270  3328 I jxcore-log: DEBUG createNativeListener: listening 50059
03-31 17:42:55.964  3270  3328 I jxcore-log: 
,03-31 17:42:55.970  3270  3328 I io.jxcore.node.ConnectionHelper: start: Port number: 50270, start advertisements: false
03-31 17:42:55.971  3270  3328 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 17:42:55.971  3270  3328 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,03-31 17:42:55.971  3270  3328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-31 17:42:55.977  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-31 17:42:55.977  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-31 17:42:55.977  3270  3328 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 17:42:55.981  2163  2181 D BtGatt.GattService: registerClient() - UUID=b68ea6d2-01a9-444e-8461-ed573fd46209
,03-31 17:42:55.982  2163  2207 D BtGatt.GattService: onClientRegistered() - UUID=b68ea6d2-01a9-444e-8461-ed573fd46209, clientIf=5
,03-31 17:42:55.984  3270  3288 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-31 17:42:55.984  2163  2183 D BtGatt.GattService: start scan with filters
,03-31 17:42:55.986  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-31 17:42:55.986  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 17:42:55.986  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-31 17:42:55.986  3270  3328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,03-31 17:42:55.986  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 17:42:55.986  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-31 17:42:55.986  3270  3270 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 17:42:55.987  2163  2218 D BtGatt.ScanManager: handling starting scan
03-31 17:42:55.987   823  1149 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 17:42:55.992  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 17:42:55.992  3270  3328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-31 17:42:55.992  3270  3328 I io.jxcore.node.ConnectionHelper: start: OK
03-31 17:42:55.993  3270  3270 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-31 17:42:55.993  3270  3270 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 17:42:55.993  3270  3270 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 17:42:55.995  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 17:42:55.995  3270  3328 I jxcore-log: 
03-31 17:42:55.996  3270  3328 I jxcore-log: ok 219 discoveryActive matches
03-31 17:42:55.996  3270  3328 I jxcore-log: 
,03-31 17:42:55.997  3270  3328 I jxcore-log: ok 220 advertisingActive matches
03-31 17:42:55.997  3270  3328 I jxcore-log: 
03-31 17:42:55.997  2163  2207 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-31 17:42:55.997  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:42:55.999  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
,03-31 17:42:55.999  3270  3328 I jxcore-log: 
03-31 17:42:56.000  3270  3328 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-31 17:42:56.000  3270  3328 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,03-31 17:42:56.000  3270  3328 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
03-31 17:42:56.000  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-31 17:42:56.000  3270  3328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,03-31 17:42:56.000  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-31 17:42:56.000  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode,
03-31 17:42:56.000  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser,
03-31 17:42:56.000  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-31 17:42:56.002  2163  2207 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,03-31 17:42:56.002  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:42:56.002  2163  2218 D BtGatt.ScanManager: Starting BLE batch scan
,03-31 17:42:56.002  2163  2218 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-31 17:42:56.005  2163  2207 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-31 17:42:56.006  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 17:42:56.007  2163  2181 D BtGatt.GattService: stopScan() - queue size =1
03-31 17:42:56.007  2163  2207 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-31 17:42:56.008  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:42:56.008  2163  2958 D BtGatt.GattService: unregisterClient() - clientIf=5
03-31 17:42:56.009  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 17:42:56.009  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 17:42:56.009  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-31 17:42:56.009  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-31 17:42:56.009  3270  3328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-31 17:42:56.009  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 17:42:56.011  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-31 17:42:56.011  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-31 17:42:56.011  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-31 17:42:56.012  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-31 17:42:56.012  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 17:42:56.012  3270  3270 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-31 17:42:56.012  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 17:42:56.012  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-31 17:42:56.013  2163  2207 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-31 17:42:56.013  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 17:42:56.013  2163  2218 D BtGatt.ScanManager: stopping BLe Batch
03-31 17:42:56.016  2163  2207 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-31 17:42:56.016  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 17:42:56.016  2163  2218 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-31 17:42:56.018  2163  2207 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-31 17:42:56.018  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:42:56.023  3270  3270 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
03-31 17:42:56.024   823  1093 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 17:42:56.029  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
,03-31 17:42:56.031  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0,
,03-31 17:42:56.031  3270  3270 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-31 17:42:56.033  3270  3270 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-31 17:42:56.033  3270  3270 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 17:42:56.033  3270  3270 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 17:42:56.034  3270  3270 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-31 17:42:56.035  3270  3328 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-31 17:42:56.035  3270  3328 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 17:42:56.035  3270  3328 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 17:42:56.036  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 17:42:56.036  3270  3328 I jxcore-log: 
,03-31 17:42:56.037  3270  3328 I jxcore-log: ok 221 discoveryActive matches
03-31 17:42:56.037  3270  3328 I jxcore-log: 
,03-31 17:42:56.037  3270  3328 I jxcore-log: ok 222 advertisingActive matches
03-31 17:42:56.037  3270  3328 I jxcore-log: ,
03-31 17:42:56.039  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 17:42:56.039  3270  3328 I jxcore-log: 
,03-31 17:42:56.053  3270  3328 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 17:42:56.053  3270  3328 I jxcore-log: 
,03-31 17:42:56.055  3270  3328 I jxcore-log: DEBUG createNativeListener: listening 40108
03-31 17:42:56.055  3270  3328 I jxcore-log: 
,03-31 17:42:56.061  3270  3328 I io.jxcore.node.ConnectionHelper: start: Port number: 40108, start advertisements: true
,03-31 17:42:56.061  3270  3328 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 17:42:56.061  3270  3328 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-31 17:42:56.061  3270  3328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-31 17:42:56.063  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
03-31 17:42:56.063  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-31 17:42:56.063  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-31 17:42:56.063  3270  3328 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 17:42:56.067  2163  2958 D BtGatt.GattService: registerClient() - UUID=f69fb1c4-9a37-4778-bb16-be187b1614d6,
,03-31 17:42:56.067  2163  2207 D BtGatt.GattService: onClientRegistered() - UUID=f69fb1c4-9a37-4778-bb16-be187b1614d6, clientIf=5
03-31 17:42:56.068  3270  3288 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-31 17:42:56.068  2163  2183 D BtGatt.GattService: start scan with filters
03-31 17:42:56.069  2163  2218 D BtGatt.ScanManager: handling starting scan,
,03-31 17:42:56.069  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
03-31 17:42:56.069  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 17:42:56.069  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-31 17:42:56.069  3270  3328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-31 17:42:56.069  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
,03-31 17:42:56.070  3270  3270 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false,
03-31 17:42:56.070  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-31 17:42:56.070  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-31 17:42:56.070  3270  3328 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-31 17:42:56.070  2163  2207 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-31 17:42:56.070  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:42:56.070  3270  3328 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-31 17:42:56.071  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-31 17:42:56.071  3270  3328 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-31 17:42:56.072  2163  2207 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-31 17:42:56.072  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:42:56.072  2163  2218 D BtGatt.ScanManager: Starting BLE batch scan
03-31 17:42:56.072  2163  2218 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-31 17:42:56.074  2163  2207 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-31 17:42:56.074  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:42:56.076  2163  2207 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-31 17:42:56.076  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:42:56.077  2163  2183 D BtGatt.GattService: registerClient() - UUID=3ce67f4e-1b95-4413-a7d6-e6e16d70b7ce
03-31 17:42:56.077  2163  2207 D BtGatt.GattService: onClientRegistered() - UUID=3ce67f4e-1b95-4413-a7d6-e6e16d70b7ce, clientIf=6
03-31 17:42:56.078  3270  3287 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-31 17:42:56.079  2163  2217 D BtGatt.AdvertiseManager: message : 0
,03-31 17:42:56.082  2163  2217 D BtGatt.AdvertiseManager: starting multi advertising
,03-31 17:42:56.084  2163  2207 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-31 17:42:56.088  2163  2207 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0,
03-31 17:42:56.088  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING,
03-31 17:42:56.088  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-31 17:42:56.089   823  1149 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 17:42:56.091  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-31 17:42:56.091  3270  3328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-31 17:42:56.091  3270  3328 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,03-31 17:42:56.091  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-31 17:42:56.092  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-31 17:42:56.092  3270  3328 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-31 17:42:56.092  3270  3328 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-31 17:42:56.092  3270  3328 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,03-31 17:42:56.092  3270  3328 I io.jxcore.node.ConnectionHelper: start: OK
03-31 17:42:56.092  3270  3270 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-31 17:42:56.093  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-31 17:42:56.093  3270  3270 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,03-31 17:42:56.093  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-31 17:42:56.093  3270  3270 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
,03-31 17:42:56.093  3270  3270 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-31 17:42:56.093  3270  3270 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-31 17:42:56.093  3270  3270 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 17:42:56.093  3270  3270 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-31 17:42:56.093  3270  3270 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed,
03-31 17:42:56.093  3270  3270 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-31 17:42:56.094  3270  3270 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-31 17:42:56.094  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 17:42:56.094  3270  3328 I jxcore-log: 
,03-31 17:42:56.095   823  1409 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-31 17:42:56.096  3270  3821 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-31 17:42:56.098  3270  3821 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-31 17:42:56.103  3270  3328 I jxcore-log: not ok 223 discoveryActive matches
03-31 17:42:56.103  3270  3328 I jxcore-log: 
03-31 17:42:56.103  3270  3328 I jxcore-log:   ---
03-31 17:42:56.103  3270  3328 I jxcore-log: 
,03-31 17:42:56.103  3270  3328 I jxcore-log:     operator: equal
03-31 17:42:56.103  3270  3328 I jxcore-log: 
,03-31 17:42:56.103  3270  3328 I jxcore-log:     expected: false
03-31 17:42:56.103  3270  3328 I jxcore-log: 
03-31 17:42:56.104  3270  3328 I jxcore-log:     actual:   true
03-31 17:42:56.104  3270  3328 I jxcore-log: 
03-31 17:42:56.104  3270  3328 I jxcore-log:   ...
03-31 17:42:56.104  3270  3328 I jxcore-log: 
,03-31 17:42:56.107  3270  3328 I jxcore-log: not ok 224 advertisingActive matches
03-31 17:42:56.107  3270  3328 I jxcore-log: 
03-31 17:42:56.107  3270  3328 I jxcore-log:   ---
03-31 17:42:56.107  3270  3328 I jxcore-log: 
03-31 17:42:56.107  3270  3328 I jxcore-log:     operator: equal
,03-31 17:42:56.107  3270  3328 I jxcore-log: 
03-31 17:42:56.107  3270  3328 I jxcore-log:     expected: true
03-31 17:42:56.107  3270  3328 I jxcore-log: 
03-31 17:42:56.107  3270  3328 I jxcore-log:     actual:   false
,03-31 17:42:56.107  3270  3328 I jxcore-log: 
03-31 17:42:56.107  3270  3328 I jxcore-log:   ...
03-31 17:42:56.107  3270  3328 I jxcore-log: 
03-31 17:42:56.109  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
,03-31 17:42:56.109  3270  3328 I jxcore-log: 
03-31 17:42:56.111  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-31 17:42:56.111  3270  3328 I jxcore-log: 
03-31 17:42:56.113  3270  3328 I jxcore-log: not ok 225 discoveryActive matches
,03-31 17:42:56.113  3270  3328 I jxcore-log: 
03-31 17:42:56.114  3270  3328 I jxcore-log:   ---
03-31 17:42:56.114  3270  3328 I jxcore-log: 
03-31 17:42:56.114  3270  3328 I jxcore-log:     operator: equal
03-31 17:42:56.114  3270  3328 I jxcore-log: 
,03-31 17:42:56.114  3270  3328 I jxcore-log:     expected: false
03-31 17:42:56.114  3270  3328 I jxcore-log: 
03-31 17:42:56.114  3270  3328 I jxcore-log:     actual:   true
03-31 17:42:56.114  3270  3328 I jxcore-log: 
,03-31 17:42:56.114  3270  3328 I jxcore-log:   ...
03-31 17:42:56.114  3270  3328 I jxcore-log: 
03-31 17:42:56.117  3270  3328 I jxcore-log: not ok 226 advertisingActive matches
03-31 17:42:56.117  3270  3328 I jxcore-log: 
,03-31 17:42:56.117  3270  3328 I jxcore-log:   ---
03-31 17:42:56.117  3270  3328 I jxcore-log: 
,03-31 17:42:56.117  3270  3328 I jxcore-log:     operator: equal
03-31 17:42:56.117  3270  3328 I jxcore-log: 
03-31 17:42:56.117  3270  3328 I jxcore-log:     expected: false
03-31 17:42:56.117  3270  3328 I jxcore-log: 
,03-31 17:42:56.117  3270  3328 I jxcore-log:     actual:   true
03-31 17:42:56.117  3270  3328 I jxcore-log: 
03-31 17:42:56.117  3270  3328 I jxcore-log:   ...
03-31 17:42:56.117  3270  3328 I jxcore-log: 
,03-31 17:42:56.119  3270  3328 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-31 17:42:56.119  3270  3328 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-31 17:42:56.119  3270  3328 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,03-31 17:42:56.119  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-31 17:42:56.119  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-31 17:42:56.119  3270  3328 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed,
03-31 17:42:56.119  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-31 17:42:56.119  3270  3821 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
,03-31 17:42:56.119  3270  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-31 17:42:56.119  3270  3821 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-31 17:42:56.120  3270  3328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-31 17:42:56.120  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart,
03-31 17:42:56.120  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-31 17:42:56.120  3270  3270 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-31 17:42:56.120  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-31 17:42:56.120  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-31 17:42:56.120  3270  3270 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-31 17:42:56.121  2163  2958 D BtGatt.GattService: stopScan() - queue size =1
03-31 17:42:56.122  2163  2183 D BtGatt.GattService: unregisterClient() - clientIf=5
03-31 17:42:56.123  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-31 17:42:56.123  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 17:42:56.123  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-31 17:42:56.123  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-31 17:42:56.123  3270  3328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-31 17:42:56.123  2163  2207 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-31 17:42:56.123  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:42:56.123  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-31 17:42:56.123  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-31 17:42:56.123  2163  2218 D BtGatt.ScanManager: stopping BLe Batch
03-31 17:42:56.124  2163  2217 D BtGatt.AdvertiseManager: message : 1
03-31 17:42:56.125  2163  2217 D BtGatt.AdvertiseManager: stop advertise for client 6
03-31 17:42:56.126  2163  2207 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-31 17:42:56.126  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 17:42:56.126  2163  2218 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-31 17:42:56.127  2163  2207 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-31 17:42:56.127  2163  2207 D BtGatt.GattService: Client app is not null!
03-31 17:42:56.128  2163  2958 D BtGatt.GattService: unregisterClient() - clientIf=6
03-31 17:42:56.128  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-31 17:42:56.128  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-31 17:42:56.128  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-31 17:42:56.128  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-31 17:42:56.128  3270  3328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-31 17:42:56.129  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 17:42:56.129  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-31 17:42:56.129  3270  3328 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-31 17:42:56.129  2163  2207 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-31 17:42:56.130  2163  2207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 17:42:56.130  3270  3328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-31 17:42:56.130  3270  3328 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,03-31 17:42:56.131  3270  3270 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 17:42:56.131  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 17:42:56.131  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-31 17:42:56.136  3270  3270 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-31 17:42:56.136   823  1093 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 17:42:56.142  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-31 17:42:56.143  3270  3270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-31 17:42:56.143  3270  3270 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-31 17:42:56.146  3270  3270 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-31 17:42:56.146  3270  3270 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-31 17:42:56.146  3270  3270 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 17:42:56.146  3270  3270 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-31 17:42:56.146  3270  3270 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 17:42:56.147  3270  3270 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-31 17:42:56.147  3270  3328 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-31 17:42:56.147  3270  3328 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 17:42:56.147  3270  3328 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-31 17:42:56.149  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-31 17:42:56.149  3270  3328 I jxcore-log: 
,03-31 17:42:56.150  3270  3328 I jxcore-log: ok 227 discoveryActive matches
03-31 17:42:56.150  3270  3328 I jxcore-log: 
,03-31 17:42:56.153  3270  3328 I jxcore-log: not ok 228 advertisingActive matches
03-31 17:42:56.153  3270  3328 I jxcore-log: 
,03-31 17:42:56.153  3270  3328 I jxcore-log:   ---
03-31 17:42:56.153  3270  3328 I jxcore-log: 
03-31 17:42:56.153  3270  3328 I jxcore-log:     operator: equal
03-31 17:42:56.153  3270  3328 I jxcore-log: 
03-31 17:42:56.153  3270  3328 I jxcore-log:     expected: false
03-31 17:42:56.153  3270  3328 I jxcore-log: 
,03-31 17:42:56.153  3270  3328 I jxcore-log:     actual:   true
03-31 17:42:56.153  3270  3328 I jxcore-log: 
03-31 17:42:56.153  3270  3328 I jxcore-log:   ...
03-31 17:42:56.153  3270  3328 I jxcore-log: 
03-31 17:42:56.155  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 17:42:56.155  3270  3328 I jxcore-log: 
,03-31 17:42:56.156  3270  3328 I jxcore-log: ok 229 discoveryActive matches
03-31 17:42:56.156  3270  3328 I jxcore-log: 
03-31 17:42:56.156  3270  3328 I jxcore-log: ok 230 advertisingActive matches
03-31 17:42:56.156  3270  3328 I jxcore-log: 
03-31 17:42:56.158  3270  3328 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 17:42:56.158  3270  3328 I jxcore-log: 
,03-31 17:42:56.169  3270  3328 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 17:42:56.169  3270  3328 I jxcore-log: 
,03-31 17:42:56.171  3270  3328 I jxcore-log: DEBUG createNativeListener: listening 49323
03-31 17:42:56.171  3270  3328 I jxcore-log: 
,03-31 17:42:56.184  3270  3328 E jxcore-log: Trace: [Error: Call Stop!]
03-31 17:42:56.184  3270  3328 E jxcore-log:     at $3.prototype.trace@console.js:139:8
03-31 17:42:56.184  3270  3328 E jxcore-log:     at @/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:38:3
03-31 17:42:56.184  3270  3328 E jxcore-log:     at emit@events.js:98:1
03-31 17:42:56.184  3270  3328 E jxcore-log:     at handlers.reject/<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/thali/node_modules/lie/lib/index.js:128:11
03-31 17:42:56.184  3270  3328 E jxcore-log:     at nextTick@/data/data/com.test.thalitest/files/www/jxcore/node_modules/immediate/lib/index.js:61:7
03-31 17:42:56.184  3270  3328 E jxcore-log:     at $0a@node.js:917:1
03-31 17:42:56.184  3270  3328 E jxcore-log: 
03-31 17:42:56.184  3270  3328 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
03-31 17:42:56.184  3270  3328 I jxcore-log: 
03-31 17:42:56.187  3270  3328 I jxcore-log: # teardown
03-31 17:42:56.187  3270  3328 I jxcore-log: 
,03-31 17:42:56.452  3822  3822 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,03-31 17:42:56.455  3822  3822 D AndroidRuntime: CheckJNI is OFF
,03-31 17:42:56.570  3822  3822 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,03-31 17:42:56.583   823   857 I ActivityManager: Force stopping com.test.thalitest appid=10095 user=-1: uninstall pkg
03-31 17:42:56.583   823   857 I ActivityManager: Killing 3270:com.test.thalitest/u0a95 (adj 0): stop com.test.thalitest
,03-31 17:42:56.652   823   867 W PackageSettings: Skipping PackageSetting{303aba39 com.example.hello/10273} due to missing metadata
,03-31 17:42:56.795   823   857 E libprocessgroup: failed to kill 1 processes for processgroup 3270
03-31 17:42:56.797   823   857 W ActivityManager: Force removing ActivityRecord{1fd41ac8 u0 com.test.thalitest/.MainActivity t17}: app died, no saved state
03-31 17:42:56.798   823   857 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,03-31 17:42:56.810   823  1022 D WifiService: Client connection lost with reason: 4
,03-31 17:42:56.821   823  1412 W WindowManager: Failed looking up window
03-31 17:42:56.821   823  1412 W WindowManager: java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@3eac0079 does not exist
03-31 17:42:56.821   823  1412 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8539)
03-31 17:42:56.821   823  1412 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8530)
03-31 17:42:56.821   823  1412 W WindowManager: 	at com.android.server.wm.WindowState$DeathRecipient.binderDied(WindowState.java:1142)
03-31 17:42:56.821   823  1412 W WindowManager: 	at android.os.BinderProxy.sendDeathNotice(Binder.java:551)
,03-31 17:42:56.821   823  1412 I WindowState: WIN DEATH: null
,03-31 17:42:56.839   823   823 V ActivityManager: Display changed displayId=0
,03-31 17:42:56.850   823   867 I ActivityManager: Force stopping com.test.thalitest appid=10095 user=0: pkg removed
,03-31 17:42:56.882   823  1041 D TaskPersister: removeObsoleteFile: deleting file=17_task.xml
,03-31 17:42:56.885  1251  1251 I Keyboard.Facilitator: resetDictionaries() : en_US
,03-31 17:42:56.895   823   999 I InputReader: Reconfiguring input devices.  changes=0x00000010
,03-31 17:42:56.923   823  1370 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3270 uid 10095
03-31 17:42:56.925  2973  2973 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,03-31 17:42:56.940  1061  1061 I art     : Explicit concurrent mark sweep GC freed 49882(2MB) AllocSpace objects, 0(0B) LOS objects, 20% free, 61MB/77MB, paused 943us total 58.715ms
,03-31 17:42:56.954  1251  1251 I Keyboard.Facilitator: onFinishInput()
03-31 17:42:56.954  1251  3837 I Keyboard.Facilitator.DecoderInitializer: run()
,03-31 17:42:56.962   823  1412 I ActivityManager: Start proc 3838:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,03-31 17:42:56.968   823   823 I art     : Explicit concurrent mark sweep GC freed 37308(2MB) AllocSpace objects, 11(741KB) LOS objects, 32% free, 33MB/49MB, paused 1.515ms total 96.493ms
,03-31 17:42:56.969   823   867 I art     : WaitForGcToComplete blocked for 87.846ms for cause Explicit
,03-31 17:42:56.986  1251  3837 I Decoder : createOrResetDecoder
,03-31 17:42:56.992  1376  1376 I art     : Explicit concurrent mark sweep GC freed 4985(364KB) AllocSpace objects, 12(1408KB) LOS objects, 31% free, 35MB/51MB, paused 781us total 25.325ms
,03-31 17:42:57.016  1233  1233 I ConfigService: onCreate
,03-31 17:42:57.042  1251  3837 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,03-31 17:42:57.063   823   823 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
03-31 17:42:57.063   823   823 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,03-31 17:42:57.065  2163  2210 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-31 17:42:57.069  1251  3837 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
03-31 17:42:57.070  1251  3837 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
03-31 17:42:57.070  1251  3837 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,03-31 17:42:57.072  1251  3837 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
03-31 17:42:57.072  1251  3837 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
03-31 17:42:57.072  1251  3837 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
03-31 17:42:57.072  1251  3837 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,03-31 17:42:57.073  1251  3837 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
03-31 17:42:57.073  1251  3837 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
03-31 17:42:57.073  1251  3837 I Keyboard.Facilitator.Delight2FileSweeper: run()
03-31 17:42:57.073  1251  3837 I Keyboard.Facilitator.RecurringTaskScheduler: run()
03-31 17:42:57.073  1251  3837 I StatsUtilsManager: startPeriodStatsRecorder() : Success
03-31 17:42:57.073  1251  3837 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,03-31 17:42:57.093   823   867 I art     : Explicit concurrent mark sweep GC freed 4848(234KB) AllocSpace objects, 0(0B) LOS objects, 32% free, 33MB/49MB, paused 3.404ms total 122.034ms
,03-31 17:42:57.100  3838  3870 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,03-31 17:42:57.126   823  1411 I ActivityManager: Start proc 3871:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,03-31 17:42:57.154  3822  3822 I art     : System.exit called, status: 0
03-31 17:42:57.154  3822  3822 I AndroidRuntime: VM exiting with result code 0.
,03-31 17:42:57.169   823  1409 I ActivityManager: Start proc 3892:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,03-31 17:42:57.185  3838  3867 I ContactLocale: AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,03-31 17:42:57.196   823   867 I ActivityManager: Start proc 3909:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,03-31 17:42:57.201   823  1411 I ActivityManager: Killing 3566:com.android.chrome/u0a40 (adj 15): empty #17
,03-31 17:42:57.206  3755  3755 W LocationOracleImpl: Best location was null
,03-31 17:42:57.221  3755  3755 I VS.Container: create_recognizer
,03-31 17:42:57.225  1376  1376 D Launcher.Workspace: 11683562 - stripEmptyScreens()
03-31 17:42:57.225  1376  1376 D Launcher.Workspace: 11683562 - stripEmptyScreens()
03-31 17:42:57.226  3892  3892 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
,03-31 17:42:57.269  1233  1233 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
03-31 17:42:57.269  1233  1233 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,03-31 17:42:57.289  3892  3936 E SQLiteDatabase: Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
03-31 17:42:57.289  3892  3936 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-31 17:42:57.289  3892  3936 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-31 17:42:57.289  3892  3936 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-31 17:42:57.289  3892  3936 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-31 17:42:57.289  3892  3936 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-31 17:42:57.289  3892  3936 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-31 17:42:57.289  3892  3936 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-31 17:42:57.289  3892  3936 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-31 17:42:57.289  3892  3936 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-31 17:42:57.289  3892  3936 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-31 17:42:57.289  3892  3936 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-31 17:42:57.289  3892  3936 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-31 17:42:57.289  3892  3936 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-31 17:42:57.289  3892  3936 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-31 17:42:57.289  3892  3936 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
03-31 17:42:57.289  3892  3936 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
03-31 17:42:57.289  3892  3936 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-31 17:42:57.289  3892  3936 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-31 17:42:57.289  3892  3936 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
03-31 17:42:57.289  3892  3936 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
--------- beginning of crash
03-31 17:42:57.290  3892  3936 E AndroidRuntime: FATAL EXCEPTION: IntentService[KeyChainService]
03-31 17:42:57.290  3892  3936 E AndroidRuntime: Process: com.android.keychain, PID: 3892
03-31 17:42:57.290  3892  3936 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-31 17:42:57.290  3892  3936 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-31 17:42:57.290  3892  3936 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-31 17:42:57.290  3892  3936 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-31 17:42:57.290  3892  3936 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-31 17:42:57.290  3892  3936 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-31 17:42:57.290  3892  3936 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-31 17:42:57.290  3892  3936 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-31 17:42:57.290  3892  3936 E AndroidRuntime: 	at android.database.sqlite.SQLiteD,atabase.open(SQLiteDatabase.java:791)
03-31 17:42:57.290  3892  3936 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-31 17:42:57.290  3892  3936 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-31 17:42:57.290  3892  3936 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-31 17:42:57.290  3892  3936 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-31 17:42:57.290  3892  3936 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-31 17:42:57.290  3892  3936 E AndroidRuntime: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
03-31 17:42:57.290  3892  3936 E AndroidRuntime: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
03-31 17:42:57.290  3892  3936 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-31 17:42:57.290  3892  3936 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-31 17:42:57.290  3892  3936 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
03-31 17:42:57.290  3892  3936 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-31 17:42:57.294  3755  3943 I HotwordRecognitionRnr: Starting hotword detection.
03-31 17:42:57.298  3755  3944 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.u@34bbc5ad
03-31 17:42:57.301   359  1020 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
03-31 17:42:57.302   359  3946 I AudioFlinger: AudioFlinger's thread 0xb40ec000 ready to run
03-31 17:42:57.303  3755  3944 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.u@34bbc5ad
03-31 17:42:57.313   359  3946 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
03-31 17:42:57.313   359  3946 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
03-31 17:42:57.313   359  3946 E ACDB-LOADER: Error: ACDB AudProc vol returned = -19
03-31 17:42:57.313   359  3946 D audio_hw_primary: enable_snd_device: snd_device(55: voice-rec-mic)
03-31 17:42:57.313  3838  3867 E SQLiteLog: (3850) statement aborts at 22: [DELETE FROM deleted_contacts WHERE contact_deleted_timestamp < ?] disk I/O error
03-31 17:42:57.315   823  3947 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
03-31 17:42:57.315  3838  3867 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
03-31 17:42:57.315  3838  3867 E AndroidRuntime: Process: android.process.acore, PID: 3838
03-31 17:42:57.315  3838  3867 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-31 17:42:57.315  3838  3867 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
03-31 17:42:57.315  3838  3867 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
03-31 17:42:57.315  3838  3867 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
03-31 17:42:57.315  3838  3867 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
03-31 17:42:57.315  3838  3867 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
03-31 17:42:57.315  3838  3867 E AndroidRuntime: 	at com.android.providers.contacts.database.DeletedContactsTableUtil.deleteOldLogs(DeletedContactsTableUtil.java:78)
03-31 17:42:57.315  3838  3867 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1730)
03-31 17:42:57.315  3838  3867 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1492)
03-31 17:42:57.315  3838  3867 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-31 17:42:57.315  3838  3867 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
03-31 17:42:57.315  3838  3867 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-31 17:42:57.315   823   857 D Atlas   : Validating map...
03-31 17:42:57.319   359  3946 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
03-31 17:42:57.323   823  3942 E DropBoxManagerService: Can't write: system_app_crash
03-31 17:42:57.323   823  3942 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop95.tmp: open failed: EROFS (Read-only file system)
03-31 17:42:57.323   823  3942 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-31 17:42:57.323   823  3942 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-31 17:42:57.323   823  3942 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-31 17:42:57.323   823  3942 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-31 17:42:57.323   823  3942 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-31 17:42:57.323   823  3942 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
03-31 17:42:57.323   823  3942 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-31 17:42:57.323   823  3942 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-31 17:42:57.323   823  3942 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-31 17:42:57.323   823  3942 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-31 17:42:57.323   823  3942 E DropBoxManagerService: 	... 5 more
03-31 17:42:57.325   823   841 I ActivityManager: Killing 3625:com.qualcomm.timeservice/1000 (adj 15): empty #17
,03-31 17:42:57.453   823  3949 E DropBoxManagerService: Can't write: system_app_crash
03-31 17:42:57.453   823  3949 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop97.tmp: open failed: EROFS (Read-only file system)
03-31 17:42:57.453   823  3949 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-31 17:42:57.453   823  3949 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-31 17:42:57.453   823  3949 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-31 17:42:57.453   823  3949 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-31 17:42:57.453   823  3949 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-31 17:42:57.453   823  3949 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
03-31 17:42:57.453   823  3949 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-31 17:42:57.453   823  3949 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-31 17:42:57.453   823  3949 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-31 17:42:57.453   823  3949 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-31 17:42:57.453   823  3949 E DropBoxManagerService: 	... 5 more
,03-31 17:42:57.465  1766  1766 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
03-31 17:42:57.465  1766  1766 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,03-31 17:42:57.466  1766  3950 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,03-31 17:42:57.467  1766  3950 D AccountUtils: Clearing selected account for com.test.thalitest
,03-31 17:42:57.472   823  3947 I OpenGLRenderer: Initialized EGL, version 1.4
,03-31 17:42:57.475  1766  1766 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
03-31 17:42:57.475  1766  1766 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,03-31 17:42:57.484   823  3947 D OpenGLRenderer: Enabling debug mode 0
,03-31 17:42:57.490  1766  3952 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,03-31 17:42:57.497  1766  3950 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,03-31 17:42:57.506  1766  3952 E AndroidRuntime: FATAL EXCEPTION: PlayGamesAsyncThread1
03-31 17:42:57.506  1766  3952 E AndroidRuntime: Process: com.google.android.gms, PID: 1766
03-31 17:42:57.506  1766  3952 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-31 17:42:57.506  1766  3952 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-31 17:42:57.506  1766  3952 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-31 17:42:57.506  1766  3952 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-31 17:42:57.506  1766  3952 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-31 17:42:57.506  1766  3952 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-31 17:42:57.506  1766  3952 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
03-31 17:42:57.506  1766  3952 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
03-31 17:42:57.506  1766  3952 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
03-31 17:42:57.506  1766  3952 E AndroidRuntime: 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
03-31 17:42:57.506  1766  3952 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
03-31 17:42:57.506  1766  3952 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
03-31 17:42:57.506  1766  3952 E AndroidRuntime: 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3044)
03-31 17:42:57.506  1766  3952 E AndroidRuntime: 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
03-31 17:42:57.506  1766  3952 E AndroidRuntime: 	at com.google.android.gms.games.service.PlayGamesAsyncService$OperationAdapter.execute(PlayGamesAsyncService.java:920)
03-31 17:42:57.506  1766  3952 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
03-31 17:42:57.506  1766  3952 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 17:42:57.506  1766  3952 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 17:42:57.506  1766  3952 E AndroidRuntime: 	at java.lang.Thread.run(Thread.java:818)
,03-31 17:42:57.508  1766  3954 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
03-31 17:42:57.508  1766  3954 E DriveAsyncService: disk I/O error (code 3850)
03-31 17:42:57.508  1766  3954 E DriveAsyncService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-31 17:42:57.508  1766  3954 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-31 17:42:57.508  1766  3954 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-31 17:42:57.508  1766  3954 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-31 17:42:57.508  1766  3954 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-31 17:42:57.508  1766  3954 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-31 17:42:57.508  1766  3954 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-31 17:42:57.508  1766  3954 E DriveAsyncService: 	at com.google.android.gms.drive.database.k.l(SourceFile:596)
03-31 17:42:57.508  1766  3954 E DriveAsyncService: 	at com.google.android.gms.drive.database.k.b(SourceFile:570)
03-31 17:42:57.508  1766  3954 E DriveAsyncService: 	at com.google.android.gms.drive.database.f.h(SourceFile:1473)
03-31 17:42:57.508  1766  3954 E DriveAsyncService: 	at com.google.android.gms.drive.api.a.bc.a(SourceFile:16)
03-31 17:42:57.508  1766  3954 E DriveAsyncService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-31 17:42:57.508  1766  3954 E DriveAsyncService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 17:42:57.508  1766  3954 E DriveAsyncService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 17:42:57.508  1766  3954 E DriveAsyncService: 	at java.lang.Thread.run(Thread.java:818)
,03-31 17:42:57.516  1766  3955 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
03-31 17:42:57.516  1766  3955 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-31 17:42:57.516  1766  3955 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-31 17:42:57.516  1766  3955 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-31 17:42:57.516  1766  3955 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-31 17:42:57.516  1766  3955 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-31 17:42:57.516  1766  3955 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-31 17:42:57.516  1766  3955 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-31 17:42:57.516  1766  3955 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-31 17:42:57.516  1766  3955 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-31 17:42:57.516  1766  3955 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-31 17:42:57.516  1766  3955 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-31 17:42:57.516  1766  3955 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-31 17:42:57.516  1766  3955 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-31 17:42:57.516  1766  3955 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
03-31 17:42:57.516  1766  3955 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
03-31 17:42:57.516  1766  3955 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
03-31 17:42:57.516  1766  3955 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
03-31 17:42:57.516  1766  3955 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
03-31 17:42:57.516  1766  3955 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-31 17:42:57.516  1766  3955 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-31 17:42:57.516  1766  3955 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
03-31 17:42:57.516  1766  3955 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-31 17:42:57.517  1766  3955 E SQLiteOpenHelper: Couldn't open metrics.db for writing (will try read-only):
03-31 17:42:57.517  1766  3955 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-31 17:42:57.517  1766  3955 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-31 17:42:57.517  1766  3955 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-31 17:42:57.517  1766  3955 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-31 17:42:57.517  1766  3955 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-31 17:42:57.517  1766  3955 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-31 17:42:57.517  1766  3955 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-31 17:42:57.517  1766  3955 E SQLiteOpenHelper: 	at android.databas,e.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-31 17:42:57.517  1766  3955 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-31 17:42:57.517  1766  3955 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-31 17:42:57.517  1766  3955 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-31 17:42:57.517  1766  3955 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-31 17:42:57.517  1766  3955 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-31 17:42:57.517  1766  3955 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
03-31 17:42:57.517  1766  3955 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
03-31 17:42:57.517  1766  3955 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
03-31 17:42:57.517  1766  3955 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
03-31 17:42:57.517  1766  3955 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
03-31 17:42:57.517  1766  3955 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-31 17:42:57.517  1766  3955 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-31 17:42:57.517  1766  3955 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:135)
03-31 17:42:57.517  1766  3955 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-31 17:42:57.519  1766  3955 W SQLiteOpenHelper: Opened metrics.db in read-only mode
03-31 17:42:57.519  1766  3955 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
03-31 17:42:57.519  1766  3955 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,03-31 17:42:57.519  1766  3955 E SQLiteLog: (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
03-31 17:42:57.520  1766  3955 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
03-31 17:42:57.520  1766  3955 I Process : Sending signal. PID: 1766 SIG: 9
,03-31 17:42:57.524   823  3956 E DropBoxManagerService: Can't write: system_app_crash
03-31 17:42:57.524   823  3956 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop98.tmp: open failed: EROFS (Read-only file system)
03-31 17:42:57.524   823  3956 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-31 17:42:57.524   823  3956 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-31 17:42:57.524   823  3956 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-31 17:42:57.524   823  3956 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-31 17:42:57.524   823  3956 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-31 17:42:57.524   823  3956 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
03-31 17:42:57.524   823  3956 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-31 17:42:57.524   823  3956 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-31 17:42:57.524   823  3956 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-31 17:42:57.524   823  3956 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-31 17:42:57.524   823  3956 E DropBoxManagerService: 	... 5 more
,03-31 17:42:57.548   823  1409 I ActivityManager: Start proc 3959:com.google.android.gms.wearable/u0a11 for service com.google.android.gms/.wearable.service.WearableControlService
,03-31 17:42:57.585   823  1022 D WifiService: Client connection lost with reason: 4
,03-31 17:42:57.590  3959  3959 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-31 17:42:57.590  3959  3959 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-31 17:42:57.595  3755  3755 I HotwordWorker: onReady
,03-31 17:42:57.611  3959  3959 I MultiDex: VM with version 2.1.0 has multidex support
03-31 17:42:57.611  3959  3959 I MultiDex: install
03-31 17:42:57.611  3959  3959 I MultiDex: VM has multidex support, MultiDex support library is disabled.
03-31 17:42:57.611   823   841 I ActivityManager: Process com.google.android.gms (pid 1766) has died
03-31 17:42:57.612   823   841 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 1000ms
03-31 17:42:57.612   823   841 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 1000ms
03-31 17:42:57.612   823   841 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 1000ms
03-31 17:42:57.612   823   841 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 11000ms
03-31 17:42:57.612   823   841 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 21000ms
03-31 17:42:57.612   823   841 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 21000ms
03-31 17:42:57.612   823   841 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 21000ms
,03-31 17:42:57.626  3959  3959 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,03-31 17:42:57.656  3755  3982 E Search.SharedPreferencesProto: Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
03-31 17:42:57.659  3959  3959 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-31 17:42:57.661  3755  3755 W GmsClient: service died
03-31 17:42:57.661  3755  3755 W GmsClient: service died
03-31 17:42:57.662  3755  3798 E Search.IcingConnection: Could not connect to Icing. Error code 8.
03-31 17:42:57.665  1376  1376 W Launcher: setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@12e1c4dc new=com.google.android.velvet.VelvetApplication@12e1c4dc
,03-31 17:42:57.667  3755  3928 W FileUtils: Failed to chmod(/data/data/com.google.android.googlequicksearchbox/files): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
03-31 17:42:57.668  3755  3928 E FileBytesWriter: Failed to write new file: loracle.new
,03-31 17:42:57.674  3755  3985 E Search.SharedPreferencesProto: Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,03-31 17:42:57.680  1376  1591 E SQLiteLog: (3850) statement aborts at 24: [DELETE FROM shortcut_and_widget_previews WHERE name LIKE ? OR name LIKE ?] disk I/O error
,03-31 17:42:57.686   258   315 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
