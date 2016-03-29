#### Test 639808779d5bfaa_thali08_motorola-Nexus 6 Logs


```
--------- beginning of main
03-29 11:06:54.694  2152  2220 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-29 11:06:55.190  3245  3245 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
03-29 11:06:55.193  3245  3245 D AndroidRuntime: CheckJNI is OFF
03-29 11:06:55.315  3245  3245 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
03-29 11:06:55.320   823   841 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
03-29 11:06:55.346   823   841 V WindowManager: addAppToken: AppWindowToken{29bcc0f2 token=Token{23efebfd ActivityRecord{27960054 u0 com.test.thalitest/.MainActivity t17}}} to stack=1 task=17 at 0
03-29 11:06:55.356   823   862 V WindowManager: Adding window Window{3a059db5 u0 Starting com.test.thalitest} at 2 of 7 (after Window{19dae190 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
03-29 11:06:55.357  3245  3245 D AndroidRuntime: Shutting down VM
03-29 11:06:55.362  1536  1796 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.u@2151c588
03-29 11:06:55.362  1536  1536 I HotwordDetector: Closing mic
03-29 11:06:55.398   823  1388 I ActivityManager: Start proc 3259:com.test.thalitest/u0a95 for activity com.test.thalitest/.MainActivity
03-29 11:06:55.413   359  1803 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
03-29 11:06:55.415   359  1803 D audio_hw_primary: disable_snd_device: snd_device(55: voice-rec-mic)
03-29 11:06:55.430   359  1031 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
03-29 11:06:55.436  1536  1798 I HotwordRecognitionRnr: Stopping hotword detection.
03-29 11:06:55.436  1536  1799 I HotwordRecognitionRnr: Hotword detection finished
03-29 11:06:55.458   823  1098 I ActivityManager: Killing 2950:com.google.android.partnersetup/u0a16 (adj 15): empty #17
03-29 11:06:55.511   823  1098 I ActivityManager: Killing 2874:com.google.android.apps.messaging/u0a75 (adj 15): empty #18
,03-29 11:06:55.699  3259  3259 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,03-29 11:06:55.727   823  1291 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1658418451
03-29 11:06:55.727   823  1291 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,03-29 11:06:55.735  3259  3259 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 7789-7793)
03-29 11:06:55.736  3259  3259 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-29 11:06:55.753  3259  3259 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3d5ecdcb}
,03-29 11:06:55.754  3259  3259 I LibraryLoader: Expected native library version number "",actual native library version number "",
,03-29 11:06:55.754  3259  3259 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,03-29 11:06:55.770  3259  3259 I BrowserStartupController: Initializing chromium process, singleProcess=true
,03-29 11:06:55.771  3259  3259 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-29 11:06:55.773  3259  3259 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-29 11:06:55.792  3259  3282 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,03-29 11:06:55.813   873   873 I kickstart: STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
03-29 11:06:55.813   873   873 I kickstart: STATUS: Wrote to /sys/power/wake_lock
03-29 11:06:55.814  3259  3259 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,03-29 11:06:55.831  3259  3259 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-29 11:06:55.831  3259  3259 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-29 11:06:55.832  3259  3259 I Adreno  : EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,03-29 11:06:55.854   873   873 E kickstart: ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2
,03-29 11:06:55.854   873   873 I kickstart: STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2' for writing
,03-29 11:06:55.911   823   861 D BluetoothManagerService: Message: 20
,03-29 11:06:55.912   823   861 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3f078bfa:true
,03-29 11:06:56.008  3259  3259 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-29 11:06:56.018  3259  3259 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-29 11:06:56.037  3259  3259 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,03-29 11:06:56.047  3259  3259 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-29 11:06:56.047  3259  3259 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-29 11:06:56.132  3259  3305 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,03-29 11:06:56.138  3259  3259 D Atlas   : Validating map...
,03-29 11:06:56.146   823   841 V WindowManager: Adding window Window{2e5ae7aa u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{3a059db5 u0 Starting com.test.thalitest})
,03-29 11:06:56.154  3259  3292 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,03-29 11:06:56.204  3259  3305 I OpenGLRenderer: Initialized EGL, version 1.4
,03-29 11:06:56.219  3259  3305 D OpenGLRenderer: Enabling debug mode 0
,03-29 11:06:56.300   823   862 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +940ms
,03-29 11:06:56.302  1258  1258 I Keyboard.Facilitator: onFinishInput()
,03-29 11:06:56.329  3259  3259 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3259
,03-29 11:06:56.500  3259  3259 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-29 11:06:56.622  3259  3307 D jxcore_app_log: JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576322048
,03-29 11:06:56.626  3259  3307 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-29 11:06:56.626  3259  3307 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-29 11:06:56.626  3259  3307 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-29 11:06:56.626  3259  3307 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-29 11:06:56.626  3259  3307 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-29 11:06:56.626  3259  3307 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@274c84dd added. We now have 1 listener(s)
,03-29 11:06:56.626   823   842 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-29 11:06:56.629  3259  3307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,03-29 11:06:56.631  3259  3307 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,03-29 11:06:56.631  3259  3307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66,
03-29 11:06:56.631  3259  3307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,03-29 11:06:56.635  3259  3307 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: ,
03-29 11:06:56.635  3259  3307 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-29 11:06:56.635  3259  3307 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-29 11:06:56.635  3259  3307 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
03-29 11:06:56.635  3259  3307 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-29 11:06:56.635  3259  3307 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-29 11:06:56.635  3259  3307 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
03-29 11:06:56.635  3259  3307 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-29 11:06:56.635  3259  3307 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-29 11:06:56.635  3259  3307 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-29 11:06:56.635  3259  3307 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-29 11:06:56.635  3259  3307 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1996420 added. We now have 1 listener(s)
03-29 11:06:56.635  3259  3307 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-29 11:06:56.639   823  1013 D WifiService: New client listening to asynchronous messages,
,03-29 11:06:56.641  3259  3307 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,03-29 11:06:56.643  3259  3307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,03-29 11:06:56.643  3259  3307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
03-29 11:06:56.643  3259  3307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
03-29 11:06:56.643  3259  3307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,03-29 11:06:56.645  3259  3307 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-29 11:06:56.645   823   842 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-29 11:06:56.647  3259  3307 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61,
,03-29 11:06:56.650  3259  3307 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-29 11:06:56.650  3259  3307 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-29 11:06:56.650  3259  3307 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-29 11:06:56.650  3259  3307 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-29 11:06:56.650  3259  3307 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-29 11:06:56.650  3259  3307 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
03-29 11:06:56.650  3259  3307 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
03-29 11:06:56.650  3259  3307 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,03-29 11:06:56.651  3259  3307 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,03-29 11:06:56.651  3259  3307 D io.jxcore.node.ConnectivityMonitor: start: OK
03-29 11:06:56.651  3259  3307 I io.jxcore.node.LifeCycleMonitor: start: OK
,03-29 11:06:56.753  3259  3259 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-29 11:06:56.755  3259  3259 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-29 11:06:56.836   873   873 I kickstart: STATUS: Received file 'm9kefs2'
03-29 11:06:56.836   873   873 I kickstart: STATUS: 950272 bytes transferred in 0.981530 seconds
03-29 11:06:56.836   873   873 I kickstart: STATUS: Successfully downloaded files from target 
03-29 11:06:56.836   873   873 I kickstart: STATUS: Wrote to /sys/power/wake_unlock
,03-29 11:06:56.840   873   873 I kickstart: STATUS: Sahara protocol completed,
,03-29 11:06:57.264  3259  3315 W jxcore-log: Initializing JXcore engine
03-29 11:06:57.264  3259  3315 W jxcore-log: JXcore engine is ready
,03-29 11:06:57.283  3315  3315 W Thread-345: type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[13003]" dev="sockfs" ino=13003 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
03-29 11:06:57.293  3315  3315 W Thread-345: type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,03-29 11:06:57.293  3315  3315 W Thread-345: type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[13117]" dev="sockfs" ino=13117 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0,
03-29 11:06:57.293  3315  3315 W Thread-345: type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[21007]" dev="sockfs" ino=21007 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,03-29 11:06:57.314  3259  3315 W jxcore-log: Starting JXcore engine
,03-29 11:06:57.415  3259  3315 W jxcore-log: Platform android
,03-29 11:06:57.415  3259  3315 W jxcore-log: 
03-29 11:06:57.416  3259  3315 W jxcore-log: Process ARCH arm
03-29 11:06:57.416  3259  3315 W jxcore-log: ,
,03-29 11:06:57.620  3259  3315 I jxcore-log: JXcore Cordova bridge is ready!
03-29 11:06:57.620  3259  3315 I jxcore-log: 
03-29 11:06:57.621  3259  3315 W jxcore-log: JXcore engine is started
,03-29 11:06:57.634  3259  3307 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-29 11:06:57.638  3259  3259 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,03-29 11:06:58.597  1240  1240 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 11:06:58.657  1240  2551 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
03-29 11:06:58.657  1240  2551 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 11:06:58.658  1240  2551 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 11:06:58.658  1240  2551 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 11:06:58.666  1240  2551 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 11:06:58.714  2747  2747 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
03-29 11:06:58.714  2747  2747 D Finsky  : [1] 5.onFinished: Installation state replication failed.
03-29 11:06:58.715  2747  2747 D Finsky  : [1] 5.onFinished: Scheduling replication attempt 4.
,03-29 11:07:06.989  3259  3315 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-29 11:07:06.989  3259  3315 I jxcore-log: 
,03-29 11:07:06.992  3259  3315 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-29 11:07:06.992  3259  3315 I jxcore-log: 
,03-29 11:07:07.005  3259  3315 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-29 11:07:07.005  3259  3315 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-29 11:07:07.005  3259  3315 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-29 11:07:07.005  3259  3315 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-29 11:07:07.005  3259  3315 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-29 11:07:07.005  3259  3315 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
03-29 11:07:07.005  3259  3315 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
03-29 11:07:07.005  3259  3315 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,03-29 11:07:07.010  3259  3315 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,03-29 11:07:07.012  3259  3315 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-29 11:07:07.012  3259  3315 I jxcore-log: 
,03-29 11:07:07.014  3259  3315 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-29 11:07:07.014  3259  3315 I jxcore-log: 
,03-29 11:07:07.544  3259  3315 I jxcore-log: Unit Test app is loaded
03-29 11:07:07.544  3259  3315 I jxcore-log: 
,03-29 11:07:07.549  3259  3315 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
03-29 11:07:07.549  3259  3315 I jxcore-log: 
,03-29 11:07:07.571  3259  3259 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,03-29 11:07:07.572  3259  3315 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,03-29 11:07:07.581  3259  3315 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
03-29 11:07:07.581  3259  3315 I jxcore-log: 
,03-29 11:07:07.584  3259  3315 I jxcore-log: My device name is: motorola-Nexus 6
03-29 11:07:07.584  3259  3315 I jxcore-log: 
,03-29 11:07:11.399  3259  3315 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
03-29 11:07:11.399  3259  3315 I jxcore-log: 
,03-29 11:07:11.746  3259  3315 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
03-29 11:07:11.746  3259  3315 I jxcore-log: 
,03-29 11:07:11.759  3259  3315 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
03-29 11:07:11.759  3259  3315 I jxcore-log: 
,03-29 11:07:11.763  3259  3315 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
03-29 11:07:11.763  3259  3315 I jxcore-log: 
,03-29 11:07:11.801  3259  3315 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
03-29 11:07:11.801  3259  3315 I jxcore-log: 
,03-29 11:07:11.818  3259  3315 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
03-29 11:07:11.818  3259  3315 I jxcore-log: 
,03-29 11:07:11.822  3259  3315 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
03-29 11:07:11.822  3259  3315 I jxcore-log: 
,03-29 11:07:12.541   823   864 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,03-29 11:07:12.552   823   864 I Adreno  : EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,03-29 11:07:12.595   258   345 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (185 us)
,03-29 11:07:13.165   823   862 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
03-29 11:07:13.166   823   823 V ActivityManager: Display changed displayId=0
,03-29 11:07:13.173   258   258 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6482000
03-29 11:07:13.173   258   258 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,03-29 11:07:13.439   258   315 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,03-29 11:07:13.443   258   258 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,03-29 11:07:13.443   823  1046 D SurfaceControl: Excessive delay in setPowerMode(): 276ms
,03-29 11:07:13.449   823   864 I DreamManagerService: Entering dreamland.
03-29 11:07:13.450   823   864 I PowerManagerService: Dozing...
03-29 11:07:13.450   823   859 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,03-29 11:07:13.474   359  1032 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
03-29 11:07:13.474   359  1032 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,03-29 11:07:13.484   823  1012 E WifiStateMachine: cancelDelayedScan -> 16
03-29 11:07:13.487   823  1012 E native  : do suspend false
,03-29 11:07:13.507   823  1012 E WifiStateMachine: WifiStateMachine Disconnected CMD_START_SCAN source -2 15, 17 -> obsolete
,03-29 11:07:13.529  1258  1258 I Keyboard.Facilitator: onFinishInput()
,03-29 11:07:13.540   823  1012 E WifiStateMachine: cancelDelayedScan -> 18
,03-29 11:07:13.595   823  1012 E native  : do suspend true
,03-29 11:07:13.655   359  1033 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,03-29 11:07:13.655   359  1033 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,03-29 11:07:13.693   823  1012 E WifiStateMachine: WifiStateMachine Disconnected CMD_START_SCAN source -2 17, 18 -> obsolete,
,03-29 11:07:13.973  3259  3315 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
03-29 11:07:13.973  3259  3315 I jxcore-log: 
,03-29 11:07:13.990  3259  3315 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js,
03-29 11:07:13.990  3259  3315 I jxcore-log: 
,03-29 11:07:13.998  3259  3315 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js,
03-29 11:07:13.998  3259  3315 I jxcore-log: 
,03-29 11:07:14.247  3259  3315 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js,
03-29 11:07:14.247  3259  3315 I jxcore-log: 
,03-29 11:07:14.318  3259  3315 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
03-29 11:07:14.318  3259  3315 I jxcore-log: ,
,03-29 11:07:14.373  3259  3315 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
03-29 11:07:14.373  3259  3315 I jxcore-log: 
,03-29 11:07:14.380  3259  3315 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
03-29 11:07:14.380  3259  3315 I jxcore-log: 
,03-29 11:07:14.390  3259  3315 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
03-29 11:07:14.390  3259  3315 I jxcore-log: 
,03-29 11:07:14.395  3259  3315 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
03-29 11:07:14.395  3259  3315 I jxcore-log: 
,03-29 11:07:14.401  3259  3315 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
03-29 11:07:14.401  3259  3315 I jxcore-log: 
,03-29 11:07:14.417  3259  3315 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
03-29 11:07:14.417  3259  3315 I jxcore-log: 
,03-29 11:07:14.436  3259  3315 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
03-29 11:07:14.436  3259  3315 I jxcore-log: 
,03-29 11:07:14.520  3259  3315 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
03-29 11:07:14.520  3259  3315 I jxcore-log: 
,03-29 11:07:14.525  3259  3315 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
03-29 11:07:14.525  3259  3315 I jxcore-log: 
,03-29 11:07:14.551  3259  3315 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
03-29 11:07:14.551  3259  3315 I jxcore-log: 
,03-29 11:07:15.947  1172  1172 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,03-29 11:07:16.372  1172  1172 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,03-29 11:07:16.410  1172  1172 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
03-29 11:07:16.410  1172  1172 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,03-29 11:07:16.448   823  1012 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} },
03-29 11:07:16.449   823  1012 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,03-29 11:07:16.450   823  1014 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,03-29 11:07:16.460   823  1012 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,03-29 11:07:16.473   355   817 D CommandListener: Setting iface cfg,
,03-29 11:07:16.484   823  1012 E WifiStateMachine: Start Dhcp Watchdog 1
,03-29 11:07:16.489   823  1012 E WifiStateMachine:  WifiLinkLayerStats: 
03-29 11:07:16.489   823  1012 E WifiStateMachine:  my bss beacon rx: 1
03-29 11:07:16.489   823  1012 E WifiStateMachine:  RSSI mgmt: -43
,03-29 11:07:16.489   823  1012 E WifiStateMachine:  BE :  rx=0 tx=4 lost=0 retries=0
03-29 11:07:16.489   823  1012 E WifiStateMachine:  BK :  rx=0 tx=0 lost=0 retries=0
03-29 11:07:16.489   823  1012 E WifiStateMachine:  VI :  rx=0 tx=0 lost=0 retries=0
03-29 11:07:16.489   823  1012 E WifiStateMachine:  VO :  rx=2 tx=0 lost=0 retries=0
03-29 11:07:16.489   823  1012 E WifiStateMachine:  on_time : 520 tx_time=63 rx_time=87 scan_time=0
,03-29 11:07:16.599   823  1012 E native  : do suspend false
,03-29 11:07:16.612   823  1012 E WifiStateMachine: scanCount==0 - aborting
,03-29 11:07:16.859  3329  3329 I dhcpcd  : version 5.5.6 starting
,03-29 11:07:16.954  3329  3329 I dhcpcd  : wlan0: rebinding lease of 192.168.1.125
,03-29 11:07:17.035  3329  3329 I dhcpcd  : wlan0: acknowledged 192.168.1.125 from 192.168.1.1
,03-29 11:07:17.082  3329  3329 I dhcpcd  : wlan0: leased 192.168.1.125 for 172800 seconds
,03-29 11:07:17.434   823  1012 E native  : do suspend true
,03-29 11:07:17.479   823  1014 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,03-29 11:07:17.484   823  1014 D ConnectivityService: Adding iface wlan0 to network 100
,03-29 11:07:17.490   823  1012 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,03-29 11:07:17.507   823  1014 E ConnectivityService: Unexpected mtu value: 0, wlan0
03-29 11:07:17.507   823  1014 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 100
,03-29 11:07:17.508   823  1014 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,03-29 11:07:17.509   823  1014 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,03-29 11:07:17.510   823  1014 D ConnectivityService: Setting Dns servers for network 100 to [/192.168.1.1]
,03-29 11:07:17.518   823  1014 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,03-29 11:07:17.523   823  1014 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
,03-29 11:07:17.523   823  3327 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
,03-29 11:07:17.523   823  3327 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Connected
03-29 11:07:17.524   823  3327 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
03-29 11:07:17.524   823  3327 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,03-29 11:07:17.529   823  1014 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
,03-29 11:07:17.530   823  1014 D ConnectivityService:    accepting network in place of null
,03-29 11:07:17.531   823  1014 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.125/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
,03-29 11:07:17.532   823  1014 D ConnectivityService: Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
,03-29 11:07:17.536   823  1014 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,03-29 11:07:17.537   823  1014 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,03-29 11:07:17.537  1067  1562 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
03-29 11:07:17.537   823  1014 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
03-29 11:07:17.539   823  1014 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
03-29 11:07:17.542   823   861 D Tethering: MasterInitialState.processMessage what=3
,03-29 11:07:17.549   823  1213 V BackupManagerService: Scheduling immediate backup pass
,03-29 11:07:17.550  3067  3067 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,03-29 11:07:17.553   823   823 V BackupManagerService: Running a backup pass
,03-29 11:07:17.554   823  1045 V BackupManagerService: clearing pending backups
,03-29 11:07:17.561  3259  3259 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
03-29 11:07:17.561  3259  3259 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-29 11:07:17.561  3259  3259 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-29 11:07:17.561  3259  3259 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-29 11:07:17.561  3259  3259 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-29 11:07:17.561  3259  3259 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-29 11:07:17.561  3259  3259 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-29 11:07:17.561  3259  3259 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-29 11:07:17.562  1360  1387 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
03-29 11:07:17.562  1360  1387 E PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
03-29 11:07:17.563  1536  1536 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,03-29 11:07:17.563   823   856 D TelephonyManager: getDataEnabled: retVal=false
,03-29 11:07:17.567  3259  3259 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
03-29 11:07:17.568  3067  3067 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,03-29 11:07:17.568  3259  3315 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-29 11:07:17.568  3259  3315 I jxcore-log: 
,03-29 11:07:17.571   823  1045 V PerformBackupTask: Beginning backup of 14 targets
,03-29 11:07:17.575   823  1045 D PerformBackupTask: invokeAgentForBackup on @pm@
,03-29 11:07:17.580   823  1045 V BackupServiceBinder: doBackup() invoked
,03-29 11:07:17.582   823   856 E GpsLocationProvider: No APN found to select.
,03-29 11:07:17.583   823  1045 I PMBA    : Previous metadata 1570415 mismatch vs 1860966 - rewriting
,03-29 11:07:17.600   823  1045 I BackupRestoreController: Getting widget state for user: 0
,03-29 11:07:17.626   823  1448 I ActivityManager: Start proc 3369:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.steen.receiver.ConnectivityChangeReceiver
,03-29 11:07:17.689   823  3389 D GpsLocationProvider: NTP server returned: 1459242437445 (Tue Mar 29 11:07:17 GMT+02:00 2016) reference: 169746 certainty: 20 system time offset: -244
03-29 11:07:17.689   823  1305 D AlarmManagerService: Setting time of day to sec=1459242437
03-29 11:07:17.445   823  1305 W AlarmManagerService: Unable to set rtc to 1459242437: Invalid argument
,03-29 11:07:17.482  1842  1857 W GmsBackupTransport: Unknown package in backup request: @pm@
,03-29 11:07:17.487  1842  1857 V GmsBackupTransport: starting performBackup for @pm@
,03-29 11:07:17.502  1842  1857 V GmsBackupTransport: performBackup done for @pm@
,03-29 11:07:17.510  1240  1240 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 11:07:17.540  1240  1257 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: android
03-29 11:07:17.540  1240  1257 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> android without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 11:07:17.540  1240  1257 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 11:07:17.540  1240  1257 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 11:07:17.545  1805  3391 E Auth.Api.Credentials: [CredentialSyncAdapter] Unknown sync event.
,03-29 11:07:17.546  1240  1257 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 11:07:17.580   823  1448 I ActivityManager: Start proc 3403:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,03-29 11:07:17.590   371   371 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 223us total 10.245ms
,03-29 11:07:17.603   371   371 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 189us total 11.368ms
,03-29 11:07:17.610   823  3327 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 29 Mar 2016 09:07:17 GMT], X-Android-Received-Millis=[1459242437609], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1459242437539]}
03-29 11:07:17.610   823  3327 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Validated
03-29 11:07:17.610   823  1014 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
03-29 11:07:17.610   823  1014 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 100]
03-29 11:07:17.610   823  1014 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
03-29 11:07:17.611   823  1014 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
03-29 11:07:17.611   823  1014 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,03-29 11:07:17.612   823  1014 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
03-29 11:07:17.612  1067  1562 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,03-29 11:07:17.614   371   371 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 307us total 10.502ms
,03-29 11:07:17.625  3403  3403 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,03-29 11:07:17.635  3403  3403 D SprintDMHelper: simOperator:  IMSI: null
,03-29 11:07:17.635  3403  3403 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,03-29 11:07:17.655  1805  3423 W DriveInitializer: Background init thread started
03-29 11:07:17.656  1805  1805 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,03-29 11:07:17.660   823  1449 I art     : Explicit concurrent mark sweep GC freed 62594(3MB) AllocSpace objects, 4(64KB) LOS objects, 32% free, 33MB/49MB, paused 1.370ms total 61.718ms
,03-29 11:07:17.671  1240  1257 W GLSActivity: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-29 11:07:17.671  1240  1257 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-29 11:07:17.671  1240  1257 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-29 11:07:17.671  1240  1257 W GLSActivity: 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
03-29 11:07:17.671  1240  1257 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
03-29 11:07:17.671  1240  1257 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
03-29 11:07:17.671  1240  1257 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:446)
,03-29 11:07:17.673  1805  1805 D SystemUpdateService: onCreate
,03-29 11:07:17.674  1842  1858 W GmsBackupTransport: Error sending final backup to server: 
03-29 11:07:17.674  1842  1858 W GmsBackupTransport: com.google.android.gms.backup.d.d: Can not get client auth token
03-29 11:07:17.674  1842  1858 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:1080)
03-29 11:07:17.674  1842  1858 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:65)
03-29 11:07:17.674  1842  1858 W GmsBackupTransport: 	at com.google.android.gms.backup.aa.finishBackup(SourceFile:409)
03-29 11:07:17.674  1842  1858 W GmsBackupTransport: 	at android.app.backup.BackupTransport$TransportImpl.finishBackup(BackupTransport.java:547)
03-29 11:07:17.674  1842  1858 W GmsBackupTransport: 	at com.android.internal.backup.IBackupTransport$Stub.onTransact(IBackupTransport.java:162)
03-29 11:07:17.674  1842  1858 W GmsBackupTransport: 	at android.os.Binder.execTransact(Binder.java:446)
03-29 11:07:17.674  1842  1858 W GmsBackupTransport: Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
03-29 11:07:17.674  1842  1858 W GmsBackupTransport: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
03-29 11:07:17.674  1842  1858 W GmsBackupTransport: 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
03-29 11:07:17.674  1842  1858 W GmsBackupTransport: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
03-29 11:07:17.674  1842  1858 W GmsBackupTransport: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
03-29 11:07:17.674  1842  1858 W GmsBackupTransport: 	... 1 more
,03-29 11:07:17.675   823  1045 D BackupManagerService: Now staging backup of com.google.android.talk
,03-29 11:07:17.680  1805  1805 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,03-29 11:07:17.687  1805  3424 W DriveInitializer: Awaiting to be initialized
,03-29 11:07:17.688   823  1045 D BackupManagerService: Now staging backup of com.google.android.dialer
,03-29 11:07:17.690  1805  3426 I SystemUpdateService: active receiver: enabled
,03-29 11:07:17.693   823  1045 D BackupManagerService: Now staging backup of com.android.providers.settings
03-29 11:07:17.694  1805  3426 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,03-29 11:07:17.696  1805  3426 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]; metered: false; mobile allowed: true
03-29 11:07:17.696  1805  3426 I SystemUpdateService: now status is 0 (complete)
03-29 11:07:17.696  1805  3426 I SystemUpdateService: processDownloadedFile /data/data/com.google.android.gms/app_download/update.zip
03-29 11:07:17.696  1805  3426 I SystemUpdateService: file has been verified
03-29 11:07:17.696  1805  3426 I SystemUpdateService: OTA package size = 25802302
,03-29 11:07:17.701   823  1045 D BackupManagerService: Now staging backup of com.android.sharedstoragebackup
,03-29 11:07:17.703  1805  3426 I SystemUpdateService: showing system update notification
,03-29 11:07:17.706   823  1045 D BackupManagerService: Now staging backup of com.google.android.gm
,03-29 11:07:17.710   823  1045 D BackupManagerService: Now staging backup of com.android.providers.userdictionary
,03-29 11:07:17.713   823  1045 D BackupManagerService: Now staging backup of com.android.nfc
,03-29 11:07:17.716   823  1045 D BackupManagerService: Now staging backup of com.google.android.apps.genie.geniewidget
,03-29 11:07:17.719   823  1045 D BackupManagerService: Now staging backup of com.google.android.marvin.talkback
,03-29 11:07:17.721   823  1045 D BackupManagerService: Now staging backup of com.google.android.inputmethod.latin
,03-29 11:07:17.732  1805  3435 I iu.SyncManager: SYNC; picasa accounts
,03-29 11:07:17.732   823   823 I ValidateNoPeople: skipping global notification
,03-29 11:07:17.737   823  1045 D BackupManagerService: Now staging backup of com.google.android.calendar
,03-29 11:07:17.741  1805  1805 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,03-29 11:07:17.743  1805  1805 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,03-29 11:07:17.748   823  1045 D BackupManagerService: Now staging backup of com.android.vending
03-29 11:07:17.750   823  1045 D BackupManagerService: Now staging backup of android
03-29 11:07:17.751   823  1045 D BackupManagerService: Now staging backup of com.google.android.googlequicksearchbox
,03-29 11:07:17.754  1842  1858 I GmsBackupTransport: Next backup will happen in 43199918 millis.
,03-29 11:07:17.758  1805  1805 D SystemUpdateService: onDestroy
,03-29 11:07:17.760   823  1045 I BackupManagerService: Backup pass finished.
,03-29 11:07:17.762  1805  3435 I iu.UploadsManager: num queued entries: 0
,03-29 11:07:17.764  1805  3435 I iu.UploadsManager: num updated entries: 0
,03-29 11:07:17.766  1805  3435 I iu.SyncManager: NEXT; no task
,03-29 11:07:17.768  1805  1805 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,03-29 11:07:17.769  1805  1805 I Kids    : [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
,03-29 11:07:17.779  1240  1256 I art     : Explicit concurrent mark sweep GC freed 20573(1115KB) AllocSpace objects, 0(0B) LOS objects, 38% free, 26MB/42MB, paused 3.244ms total 74.605ms
,03-29 11:07:17.800   823  1449 I ActivityManager: Start proc 3446:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,03-29 11:07:17.810  1805  3423 W DriveInitializer: Background init thread ended
,03-29 11:07:17.823  1240  2551 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-29 11:07:17.824  1240  2551 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 11:07:17.824  1240  2551 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 11:07:17.824  1240  2551 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 11:07:17.826  1240  2551 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 11:07:17.839  3037  3421 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
03-29 11:07:17.839  3037  3421 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-29 11:07:17.839  3037  3421 E HttpOperation: 	at jdm.a(PG:82)
03-29 11:07:17.839  3037  3421 E HttpOperation: 	at jcs.o(PG:406)
03-29 11:07:17.839  3037  3421 E HttpOperation: 	at jcn.a(PG:1379)
03-29 11:07:17.839  3037  3421 E HttpOperation: 	at jcs.i(PG:143)
03-29 11:07:17.839  3037  3421 E HttpOperation: 	at blb.a(PG:3937)
03-29 11:07:17.839  3037  3421 E HttpOperation: 	at czp.a(PG:18188)
03-29 11:07:17.839  3037  3421 E HttpOperation: 	at czp.a(PG:9081)
03-29 11:07:17.839  3037  3421 E HttpOperation: 	at czq.run(PG:1686)
03-29 11:07:17.839  3037  3421 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-29 11:07:17.839  3037  3421 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-29 11:07:17.839  3037  3421 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 11:07:17.839  3037  3421 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 11:07:17.839  3037  3421 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-29 11:07:17.839  3037  3421 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-29 11:07:17.839  3037  3421 E HttpOperation: 	at jdj.a(PG:4091)
03-29 11:07:17.839  3037  3421 E HttpOperation: 	at jdj.a(PG:1125)
03-29 11:07:17.839  3037  3421 E HttpOperation: 	at jdm.a(PG:77)
03-29 11:07:17.839  3037  3421 E HttpOperation: 	... 12 more
03-29 11:07:17.839  3037  3421 E HttpOperation: Caused by: faj: BadAuthentication
03-29 11:07:17.839  3037  3421 E HttpOperation: 	at fal.a(PG:38)
03-29 11:07:17.839  3037  3421 E HttpOperation: 	at jdj.a(PG:4089)
03-29 11:07:17.839  3037  3421 E HttpOperation: 	... 14 more
,03-29 11:07:17.874  1240  2551 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-29 11:07:17.874  1240  2551 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 11:07:17.874  1240  2551 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 11:07:17.874  1240  2551 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 11:07:17.877  1240  2551 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 11:07:17.886  3037  3421 E HttpOperation: [getmobileexperiments] Unexpected exception
03-29 11:07:17.886  3037  3421 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-29 11:07:17.886  3037  3421 E HttpOperation: 	at jdm.a(PG:82)
03-29 11:07:17.886  3037  3421 E HttpOperation: 	at jcs.o(PG:406)
03-29 11:07:17.886  3037  3421 E HttpOperation: 	at jcn.a(PG:1379)
03-29 11:07:17.886  3037  3421 E HttpOperation: 	at jcs.i(PG:143)
03-29 11:07:17.886  3037  3421 E HttpOperation: 	at hec.a(PG:42)
03-29 11:07:17.886  3037  3421 E HttpOperation: 	at hee.a(PG:102)
03-29 11:07:17.886  3037  3421 E HttpOperation: 	at czr.a(PG:65)
03-29 11:07:17.886  3037  3421 E HttpOperation: 	at kka.a(PG:108)
03-29 11:07:17.886  3037  3421 E HttpOperation: 	at czp.a(PG:19176)
03-29 11:07:17.886  3037  3421 E HttpOperation: 	at czp.a(PG:9081)
03-29 11:07:17.886  3037  3421 E HttpOperation: 	at czq.run(PG:1686)
03-29 11:07:17.886  3037  3421 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-29 11:07:17.886  3037  3421 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-29 11:07:17.886  3037  3421 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 11:07:17.886  3037  3421 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 11:07:17.886  3037  3421 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-29 11:07:17.886  3037  3421 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-29 11:07:17.886  3037  3421 E HttpOperation: 	at jdj.a(PG:4091)
03-29 11:07:17.886  3037  3421 E HttpOperation: 	at jdj.a(PG:1125)
03-29 11:07:17.886  3037  3421 E HttpOperation: 	at jdm.a(PG:77)
03-29 11:07:17.886  3037  3421 E HttpOperation: 	... 15 more
03-29 11:07:17.886  3037  3421 E HttpOperation: Caused by: faj: BadAuthentication
03-29 11:07:17.886  3037  3421 E HttpOperation: 	at fal.a(PG:38)
03-29 11:07:17.886  3037  3421 E HttpOperation: 	at jdj.a(PG:4089)
03-29 11:07:17.886  3037  3421 E HttpOperation: 	... 17 more
03-29 11:07:17.887  3037  3421 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
03-29 11:07:17.887  3037  3421 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
03-29 11:07:17.887  3037  3421 E ExperimentLoader: 	at jdm.a(PG:82)
03-29 11:07:17.887  3037  3421 E ExperimentLoader: 	at jcs.o(PG:406)
03-29 11:07:17.887  3037  3421 E ExperimentLoader: 	at jcn.a(PG:1379)
03-29 11:07:17.887  3037  3421 E ExperimentLoader: 	at jcs.i(PG:143)
03-29 11:07:17.887  3037  3421 E ExperimentLoader: 	at hec.a(PG:42)
03-29 11:07:17.887  3037  3421 E ExperimentLoader: 	at hee.a(PG:102)
03-29 11:07:17.887  3037  3421 E ExperimentLoader: 	at czr.a(PG:65)
03-29 11:07:17.887  3037  3421 E ExperimentLoader: 	at kka.a(PG:108)
03-29 11:07:17.887  3037  3421 E ExperimentLoader: 	at czp.a(PG:19176)
03-29 11:07:17.887  3037  3421 E ExperimentLoader: 	at czp.a(PG:9081)
03-29 11:07:17.887  3037  3421 E ExperimentLoader: 	at czq.run(PG:1686)
03-29 11:07:17.887  3037  3421 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-29 11:07:17.887  3037  3421 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-29 11:07:17.887  3037  3421 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 11:07:17.887  3037  3421 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 11:07:17.887  3037  3421 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
03-29 11:07:17.887  3037  3421 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-29 11:07:17.887  3037  3421 E ExperimentLoader: 	at jdj.a(PG:4091)
03-29 11:07:17.887  3037  3421 E ExperimentLoader: 	at jdj.a(PG:1,125)
03-29 11:07:17.887  3037  3421 E ExperimentLoader: 	at jdm.a(PG:77)
03-29 11:07:17.887  3037  3421 E ExperimentLoader: 	... 15 more
03-29 11:07:17.887  3037  3421 E ExperimentLoader: Caused by: faj: BadAuthentication
03-29 11:07:17.887  3037  3421 E ExperimentLoader: 	at fal.a(PG:38)
03-29 11:07:17.887  3037  3421 E ExperimentLoader: 	at jdj.a(PG:4089)
03-29 11:07:17.887  3037  3421 E ExperimentLoader: 	... 17 more
,03-29 11:07:17.938   823   856 I ActivityManager: Start proc 3470:com.google.android.keep/u0a79 for service com.google.android.keep/.syncadapter.KeepSyncAdapterService
,03-29 11:07:17.949  3446  3446 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
03-29 11:07:17.949  3446  3446 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-29 11:07:17.949  3446  3446 I GAv4    :   adb logcat -s GAv4
,03-29 11:07:17.963  3446  3446 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,03-29 11:07:17.972  3446  3446 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,03-29 11:07:17.978  3446  3492 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,03-29 11:07:17.980  3146  3443 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,03-29 11:07:17.983   823  1213 I ActivityManager: Killing 2970:com.android.musicfx/u0a18 (adj 15): empty #17
,03-29 11:07:18.047   823  1098 I ActivityManager: Killing 3000:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,03-29 11:07:18.050   823   856 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 39531, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,03-29 11:07:18.137  1240  3491 D GCM     : Connected
,03-29 11:07:18.201  1240  3491 D GCM     : Message class com.google.f.a.a.p
,03-29 11:07:18.214   823   856 I ActivityManager: Start proc 3496:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,03-29 11:07:18.376  3446  3446 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,03-29 11:07:18.384  3446  3446 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 686-687)
03-29 11:07:18.384  3446  3446 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-29 11:07:18.387  3446  3446 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1fe4f44e}
,03-29 11:07:18.388  3446  3446 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-29 11:07:18.388  3446  3446 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
03-29 11:07:18.395  3446  3446 I BrowserStartupController: Initializing chromium process, singleProcess=true
,03-29 11:07:18.395  3446  3446 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-29 11:07:18.396  3446  3446 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-29 11:07:18.408  3446  3446 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,03-29 11:07:18.414  3446  3446 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-29 11:07:18.414  3446  3446 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-29 11:07:18.414  3446  3446 I Adreno  : EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,03-29 11:07:18.420  3470  3529 V KeepSync: Connecting to GoogleApiClient
,03-29 11:07:18.476  3446  3446 I NSApplication: Starting up...
,03-29 11:07:18.484  3446  3545 W AudioManagerAndroid: Requires BLUETOOTH permission
,03-29 11:07:18.507   823  1448 I ActivityManager: Start proc 3550:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,03-29 11:07:18.517  1805  3537 W BaseAppContext: Using Auth Proxy for data requests.
03-29 11:07:18.526  1805  3537 W BaseAppContext: Using Auth Proxy for data requests.
,03-29 11:07:18.552  1240  2551 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,03-29 11:07:18.552  1240  2551 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 11:07:18.552  1240  2551 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 11:07:18.552  1240  2551 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 11:07:18.556  1240  2551 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 11:07:18.574  1805  3537 E ClientConnectionOperation: Handling authorization failure
03-29 11:07:18.574  1805  3537 E ClientConnectionOperation: com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
03-29 11:07:18.574  1805  3537 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
03-29 11:07:18.574  1805  3537 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
03-29 11:07:18.574  1805  3537 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
03-29 11:07:18.574  1805  3537 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
03-29 11:07:18.574  1805  3537 E ClientConnectionOperation: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-29 11:07:18.574  1805  3537 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 11:07:18.574  1805  3537 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 11:07:18.574  1805  3537 E ClientConnectionOperation: 	at java.lang.Thread.run(Thread.java:818)
03-29 11:07:18.574  1805  3537 E ClientConnectionOperation: Caused by: com.google.android.gms.auth.ad: BadAuthentication
03-29 11:07:18.574  1805  3537 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.b(SourceFile:442)
03-29 11:07:18.574  1805  3537 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:365)
03-29 11:07:18.574  1805  3537 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:310)
03-29 11:07:18.574  1805  3537 E ClientConnectionOperation: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
03-29 11:07:18.574  1805  3537 E ClientConnectionOperation: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
03-29 11:07:18.574  1805  3537 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:30)
03-29 11:07:18.574  1805  3537 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:370)
03-29 11:07:18.574  1805  3537 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:340)
03-29 11:07:18.574  1805  3537 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:319)
03-29 11:07:18.574  1805  3537 E ClientConnectionOperation: 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
03-29 11:07:18.574  1805  3537 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
03-29 11:07:18.574  1805  3537 E ClientConnectionOperation: 	... 7 more
03-29 11:07:18.576  3470  3529 V KeepSync: GoogleApiClient failed to connect with error code: 4
03-29 11:07:18.582  3470  3529 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-29 11:07:18.593  3470  3529 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
03-29 11:07:18.594  3470  3529 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-29 11:07:18.669  1240  1257 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
03-29 11:07:18.670  1240  1257 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 11:07:18.670  1240  1257 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 11:07:18.670  1240  1257 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 11:07:18.674  1240  1257 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 11:07:18.702  3470  3529 E KeepSync: IOException
03-29 11:07:18.702  3470  3529 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
03-29 11:07:18.702  3470  3529 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
03-29 11:07:18.702  3470  3529 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
03-29 11:07:18.702  3470  3529 E KeepSync: 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
03-29 11:07:18.702  3470  3529 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
03-29 11:07:18.702  3470  3529 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
03-29 11:07:18.702  3470  3529 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
03-29 11:07:18.702  3470  3529 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
03-29 11:07:18.702  3470  3529 E KeepSync: 	at com.google.android.keep.util.m.a(SourceFile:207)
03-29 11:07:18.702  3470  3529 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
03-29 11:07:18.702  3470  3529 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
03-29 11:07:18.702  3470  3529 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
03-29 11:07:18.702  3470  3529 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
03-29 11:07:18.702  3470  3529 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
03-29 11:07:18.702  3470  3529 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
03-29 11:07:18.702  3470  3529 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
03-29 11:07:18.702  3470  3529 E KeepSync: 	... 10 more
03-29 11:07:18.702  3470  3529 W KeepSync: Sync result 2
,03-29 11:07:18.708   823   856 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 39537, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
03-29 11:07:18.709   823   842 I ActivityManager: Killing 2789:com.google.android.gms:car/u0a11 (adj 15): empty #17
,03-29 11:07:18.875  3496  3496 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,03-29 11:07:18.883  3496  3496 I BooksApp: Created application version: 3.6.8 (30608)
,03-29 11:07:18.939  1240  2551 I art     : Explicit concurrent mark sweep GC freed 16651(943KB) AllocSpace objects, 5(362KB) LOS objects, 38% free, 26MB/42MB, paused 1.113ms total 31.957ms
,03-29 11:07:18.958   823  1356 I ActivityManager: Start proc 3581:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,03-29 11:07:18.987  3496  3598 I BooksSync: Starting books sync for 61035162, extras: ade
,03-29 11:07:19.008  1240  1240 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 11:07:19.025  1240  1256 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
03-29 11:07:19.025  1240  1256 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 11:07:19.025  1240  1256 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 11:07:19.025  1240  1256 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 11:07:19.028  1240  1256 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 11:07:19.038  2747  2747 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,03-29 11:07:19.038  2747  2747 D Finsky  : [1] 5.onFinished: Installation state replication failed.
03-29 11:07:19.038  2747  2747 D Finsky  : [1] 5.onFinished: Scheduling replication attempt 5.
,03-29 11:07:19.044   823  1450 I ActivityManager: Killing 2910:com.android.settings/1000 (adj 15): empty #17
,03-29 11:07:19.153   823  1250 I art     : Explicit concurrent mark sweep GC freed 31875(1441KB) AllocSpace objects, 5(121KB) LOS objects, 32% free, 33MB/49MB, paused 1.316ms total 52.975ms
,03-29 11:07:19.201  3496  3604 I BooksConfig: GmsCore Version = 7.8.99 (2134222-430)
,03-29 11:07:19.262  1240  1256 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,03-29 11:07:19.262  1240  1256 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-29 11:07:19.263  1240  1256 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-29 11:07:19.263  1240  1256 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 11:07:19.269  1240  1256 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 11:07:19.317  1240  1750 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-29 11:07:19.317  1240  1750 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 11:07:19.317  1240  1750 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 11:07:19.317  1240  1750 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 11:07:19.321  1240  1750 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 11:07:19.344  3496  3604 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,03-29 11:07:19.345  3496  3598 E BooksSync: Soft error
03-29 11:07:19.345  3496  3598 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-29 11:07:19.345  3496  3598 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,03-29 11:07:19.346  3496  3598 E BooksSync: Sync error
03-29 11:07:19.346  3496  3598 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-29 11:07:19.346  3496  3598 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-29 11:07:19.346  3496  3598 I BooksSync: Finished books sync
,03-29 11:07:19.350   823   856 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 39537, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-29 11:07:19.351   823  1449 I ActivityManager: Killing 1473:android.process.acore/u0a5 (adj 15): empty #17
,03-29 11:07:19.456   823  1449 I ActivityManager: Killing 2447:com.google.android.apps.maps/u0a65 (adj 15): empty #18
,03-29 11:07:19.678   823  1388 I ActivityManager: Killing 2809:com.google.android.gm/u0a78 (adj 15): empty #17
,03-29 11:07:19.983   823  1448 I ActivityManager: Start proc 3606:com.qualcomm.timeservice/1000 for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver
,03-29 11:07:20.055  3606  3606 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1459242440055
03-29 11:07:20.055  3606  3606 D         : TimeServiceNative: User Time to be set is 1459242440055
03-29 11:07:20.055  3606  3606 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
,03-29 11:07:20.055  3606  3606 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
03-29 11:07:20.055  3606  3606 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1459242440055
03-29 11:07:20.056   374   881 D QC-time-services: Daemon: Connection accepted:time_genoff
03-29 11:07:20.056  3606  3606 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
,03-29 11:07:20.056   374  3623 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1459242440055
03-29 11:07:20.056   374  3623 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1459242440055, operation = 0
03-29 11:07:20.057   374  3623 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS7/15/70 5:19:0
03-29 11:07:20.057   374  3623 D QC-time-services: Daemon:Value read from RTC seconds = 19545540000
,03-29 11:07:20.057   374  3623 D QC-time-services: Daemon:new time 1459242440055 
03-29 11:07:20.057   374  3623 D QC-time-services: Daemon: delta 1439696900055 genoff 1439696900055 
03-29 11:07:20.057   374  3623 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1439696900055 to memory
03-29 11:07:20.057   374  3623 D QC-time-services: Daemon:Opening File: /data/time/ats_2
03-29 11:07:20.057   374  3623 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,03-29 11:07:20.060   374  3623 D QC-time-services: Updating the TOD offset
03-29 11:07:20.060   374  3623 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1439696900055 to memory
03-29 11:07:20.060   374  3623 D QC-time-services: Daemon:Opening File: /data/time/ats_1
,03-29 11:07:20.060   374  3623 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,03-29 11:07:20.064   374  3623 E QC-time-services: Daemon:Update to modem bit set
03-29 11:07:20.064  3606  3606 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
03-29 11:07:20.064   374  3623 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
03-29 11:07:20.064   374  3623 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1143277640055
,03-29 11:07:20.108  3259  3315 I jxcore-log: Reconnected to the test server
03-29 11:07:20.108  3259  3315 I jxcore-log: 
,03-29 11:07:20.135   374   881 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection,
,03-29 11:07:20.140   374   879 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,03-29 11:07:20.229   823  1450 I ActivityManager: Start proc 3633:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver
,03-29 11:07:20.248   823  1388 I ActivityManager: Killing 1880:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,03-29 11:07:20.520  3633  3633 I GAv4    : Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
03-29 11:07:20.520  3633  3633 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-29 11:07:20.520  3633  3633 I GAv4    :   adb logcat -s GAv4
,03-29 11:07:20.535  3633  3633 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,03-29 11:07:20.562  3633  3633 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,03-29 11:07:20.571  3633  3652 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,03-29 11:07:20.611   823  1250 I ActivityManager: Killing 3120:com.android.providers.calendar/u0a3 (adj 15): empty #17
,03-29 11:07:20.914  1805  1805 V Herrevad: NQAS connected
,03-29 11:07:20.933  3146  3146 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-29 11:07:20.933  3146  3146 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-29 11:07:20.960  1805  3655 I art     : Explicit concurrent mark sweep GC freed 14909(1145KB) AllocSpace objects, 17(272KB) LOS objects, 35% free, 28MB/44MB, paused 1.993ms total 34.785ms
,03-29 11:07:20.961   823  1013 D WifiService: New client listening to asynchronous messages
,03-29 11:07:20.978   823  1388 I ActivityManager: Start proc 3663:com.android.providers.calendar/u0a3 for content provider com.android.providers.calendar/.CalendarProvider2
,03-29 11:07:21.005  3663  3663 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,03-29 11:07:21.048  3663  3663 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@2b7b309a(com.android.providers.calendar.CalendarProvider2@3d5ecdcb)
,03-29 11:07:21.081  3259  3315 I jxcore-log: TAP version 13
03-29 11:07:21.081  3259  3315 I jxcore-log: 
,03-29 11:07:21.085  3259  3315 I jxcore-log: # setup
03-29 11:07:21.085  3259  3315 I jxcore-log: 
,03-29 11:07:21.114  1240  2551 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
,03-29 11:07:21.114  1240  2551 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 11:07:21.114  1240  2551 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 11:07:21.114  1240  2551 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 11:07:21.116  1240  2551 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 11:07:21.123  3146  3661 E Babel   : UserRecoverableAuthException.
,03-29 11:07:21.124  3146  3661 E Babel   : eei: BadAuthentication
03-29 11:07:21.124  3146  3661 E Babel   : 	at eeg.a(Unknown Source)
03-29 11:07:21.124  3146  3661 E Babel   : 	at eeg.a(Unknown Source)
03-29 11:07:21.124  3146  3661 E Babel   : 	at eeg.a(Unknown Source)
03-29 11:07:21.124  3146  3661 E Babel   : 	at g.a(Unknown Source)
03-29 11:07:21.124  3146  3661 E Babel   : 	at cae.a(SourceFile:3089)
03-29 11:07:21.124  3146  3661 E Babel   : 	at cae.a(SourceFile:1131)
03-29 11:07:21.124  3146  3661 E Babel   : 	at cws.a(SourceFile:4333)
03-29 11:07:21.124  3146  3661 E Babel   : 	at cws.a(SourceFile:1419)
03-29 11:07:21.124  3146  3661 E Babel   : 	at crl.a(SourceFile:492)
03-29 11:07:21.124  3146  3661 E Babel   : 	at crl.a(SourceFile:1468)
03-29 11:07:21.124  3146  3661 E Babel   : 	at cqu.a(SourceFile:4416)
03-29 11:07:21.124  3146  3661 E Babel   : 	at cas.b(SourceFile:106)
03-29 11:07:21.124  3146  3661 E Babel   : 	at cap.d(SourceFile:335)
03-29 11:07:21.124  3146  3661 E Babel   : 	at caq.run(SourceFile:81)
,03-29 11:07:21.124  3146  3661 E Babel   : Error getting auth token
03-29 11:07:21.124  3146  3661 E Babel   : dvm
03-29 11:07:21.124  3146  3661 E Babel   : 	at g.a(Unknown Source)
03-29 11:07:21.124  3146  3661 E Babel   : 	at cae.a(SourceFile:3089)
03-29 11:07:21.124  3146  3661 E Babel   : 	at cae.a(SourceFile:1131)
03-29 11:07:21.124  3146  3661 E Babel   : 	at cws.a(SourceFile:4333)
03-29 11:07:21.124  3146  3661 E Babel   : 	at cws.a(SourceFile:1419)
03-29 11:07:21.124  3146  3661 E Babel   : 	at crl.a(SourceFile:492)
03-29 11:07:21.124  3146  3661 E Babel   : 	at crl.a(SourceFile:1468)
03-29 11:07:21.124  3146  3661 E Babel   : 	at cqu.a(SourceFile:4416)
03-29 11:07:21.124  3146  3661 E Babel   : 	at cas.b(SourceFile:106)
03-29 11:07:21.124  3146  3661 E Babel   : 	at cap.d(SourceFile:335)
03-29 11:07:21.124  3146  3661 E Babel   : 	at caq.run(SourceFile:81)
,03-29 11:07:21.126  3146  3661 E Babel   : Account registration failed 1-Redacted-21
03-29 11:07:21.126  3146  3661 E Babel   : cyp: null -- null
03-29 11:07:21.126  3146  3661 E Babel   : 	at cae.a(SourceFile:3121)
03-29 11:07:21.126  3146  3661 E Babel   : 	at cae.a(SourceFile:1131)
03-29 11:07:21.126  3146  3661 E Babel   : 	at cws.a(SourceFile:4333)
03-29 11:07:21.126  3146  3661 E Babel   : 	at cws.a(SourceFile:1419)
03-29 11:07:21.126  3146  3661 E Babel   : 	at crl.a(SourceFile:492)
03-29 11:07:21.126  3146  3661 E Babel   : 	at crl.a(SourceFile:1468)
03-29 11:07:21.126  3146  3661 E Babel   : 	at cqu.a(SourceFile:4416)
03-29 11:07:21.126  3146  3661 E Babel   : 	at cas.b(SourceFile:106)
03-29 11:07:21.126  3146  3661 E Babel   : 	at cap.d(SourceFile:335)
03-29 11:07:21.126  3146  3661 E Babel   : 	at caq.run(SourceFile:81)
,03-29 11:07:21.132  3146  3661 I art     : Note: end time exceeds epoch: 
,03-29 11:07:21.145  1240  1257 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
,03-29 11:07:21.145  1240  1257 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 11:07:21.145  1240  1257 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 11:07:21.145  1240  1257 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 11:07:21.148  1240  1257 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 11:07:21.157  1240  1257 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.,
,03-29 11:07:21.171  3146  3687 E Babel   : Unexpected exception while authenticating.
,03-29 11:07:21.171  3146  3687 E Babel   : eej: User intervention required. Notification has been pushed.
03-29 11:07:21.171  3146  3687 E Babel   : 	at eeg.b(Unknown Source)
03-29 11:07:21.171  3146  3687 E Babel   : 	at eeg.b(Unknown Source)
03-29 11:07:21.171  3146  3687 E Babel   : 	at g.a(Unknown Source)
03-29 11:07:21.171  3146  3687 E Babel   : 	at cae.b(SourceFile:1146)
03-29 11:07:21.171  3146  3687 E Babel   : 	at dcg.run(SourceFile:5617)
03-29 11:07:21.171  3146  3687 E Babel   : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 11:07:21.171  3146  3687 E Babel   : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 11:07:21.171  3146  3687 E Babel   : 	at java.lang.Thread.run(Thread.java:818)
,03-29 11:07:21.527  3259  3315 I jxcore-log: # 1. calling createNativeListener directly rejects
03-29 11:07:21.527  3259  3315 I jxcore-log: 
,03-29 11:07:22.062  3663  3663 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
03-29 11:07:22.063  3663  3663 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,03-29 11:07:22.286  3259  3315 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 11:07:22.286  3259  3315 I jxcore-log: 
,03-29 11:07:22.296  3259  3315 I jxcore-log: DEBUG createNativeListener: listening 32792
,03-29 11:07:22.296  3259  3315 I jxcore-log: 
,03-29 11:07:22.310  3259  3315 I jxcore-log: ok 1 Should throw
03-29 11:07:22.310  3259  3315 I jxcore-log: ,
,03-29 11:07:22.312  3259  3315 I jxcore-log: # teardown
,03-29 11:07:22.312  3259  3315 I jxcore-log: 
,03-29 11:07:22.462  3259  3315 I jxcore-log: # setup
03-29 11:07:22.462  3259  3315 I jxcore-log: 
,03-29 11:07:22.485  3663  3691 E SQLiteLog: (284) automatic index on view_events(_id)
,03-29 11:07:23.101  3259  3315 I jxcore-log: # 2. emits incomingConnectionState
03-29 11:07:23.101  3259  3315 I jxcore-log: 
,03-29 11:07:23.304  3259  3315 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 11:07:23.304  3259  3315 I jxcore-log: 
,03-29 11:07:23.310  3259  3315 I jxcore-log: DEBUG createNativeListener: listening 58066
03-29 11:07:23.310  3259  3315 I jxcore-log: 
,03-29 11:07:23.319  3259  3315 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-29 11:07:23.319  3259  3315 I jxcore-log: 
,03-29 11:07:23.322  3259  3315 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-29 11:07:23.322  3259  3315 I jxcore-log: 
,03-29 11:07:23.330  3259  3315 I jxcore-log: DEBUG createNativeListener: new mux
03-29 11:07:23.330  3259  3315 I jxcore-log: 
,03-29 11:07:23.335  3259  3315 I jxcore-log: ok 2 initial connection state should be CONNECTED
03-29 11:07:23.335  3259  3315 I jxcore-log: 
,03-29 11:07:23.348  3259  3315 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-29 11:07:23.348  3259  3315 I jxcore-log: 
,03-29 11:07:23.348  3259  3315 I jxcore-log: ok 3 final connection state should be DISCONNECTED
03-29 11:07:23.348  3259  3315 I jxcore-log: 
,03-29 11:07:23.355  3259  3315 I jxcore-log: # teardown
,03-29 11:07:23.355  3259  3315 I jxcore-log: 
,03-29 11:07:23.609  3259  3315 I jxcore-log: # setup
,03-29 11:07:23.609  3259  3315 I jxcore-log: 
,03-29 11:07:23.760  3259  3315 I jxcore-log: # 3. emits routerPortConnectionFailed
03-29 11:07:23.760  3259  3315 I jxcore-log: 
,03-29 11:07:23.892  3496  3575 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,03-29 11:07:23.894  3259  3315 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 11:07:23.894  3259  3315 I jxcore-log: 
,03-29 11:07:23.897  3259  3315 I jxcore-log: DEBUG createNativeListener: listening 59023
03-29 11:07:23.897  3259  3315 I jxcore-log: 
,03-29 11:07:23.903  3259  3315 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-29 11:07:23.903  3259  3315 I jxcore-log: 
,03-29 11:07:23.905  3259  3315 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-29 11:07:23.905  3259  3315 I jxcore-log: 
,03-29 11:07:23.907  3259  3315 I jxcore-log: DEBUG createNativeListener: new mux
03-29 11:07:23.907  3259  3315 I jxcore-log: 
,03-29 11:07:23.931  3259  3315 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 11:07:23.931  3259  3315 I jxcore-log: 
,03-29 11:07:23.934  3259  3315 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 11:07:23.934  3259  3315 I jxcore-log: 
,03-29 11:07:23.939  3259  3315 I jxcore-log: DEBUG createNativeListener: 
,03-29 11:07:23.939  3259  3315 I jxcore-log: 
03-29 11:07:23.940  3259  3315 I jxcore-log: ok 4 tried to connect to right port
,03-29 11:07:23.940  3259  3315 I jxcore-log: 
,03-29 11:07:23.942  3259  3315 I jxcore-log: ok 5 failed due to refused connection
03-29 11:07:23.942  3259  3315 I jxcore-log: 
,03-29 11:07:23.944  3259  3315 I jxcore-log: ok 6 routerPortConnectionFailed is emitted
,03-29 11:07:23.944  3259  3315 I jxcore-log: 
,03-29 11:07:23.948  3259  3315 I jxcore-log: # teardown
03-29 11:07:23.948  3259  3315 I jxcore-log: ,
,03-29 11:07:23.952  3259  3315 I jxcore-log: DEBUG createNativeListener: stream close:
,03-29 11:07:23.952  3259  3315 I jxcore-log: 
,03-29 11:07:24.042  3259  3315 I jxcore-log: DEBUG createNativeListener: mux close
03-29 11:07:24.042  3259  3315 I jxcore-log: 
,03-29 11:07:24.047  3259  3315 I jxcore-log: # setup,
03-29 11:07:24.047  3259  3315 I jxcore-log: 
,03-29 11:07:24.048  3259  3315 I jxcore-log: DEBUG createNativeListener: incoming socket close,
03-29 11:07:24.048  3259  3315 I jxcore-log: ,
,03-29 11:07:24.172  3259  3315 I jxcore-log: # 4. native server connections all up,
03-29 11:07:24.172  3259  3315 I jxcore-log: 
,03-29 11:07:24.291  3259  3315 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 11:07:24.291  3259  3315 I jxcore-log: ,
,03-29 11:07:24.301  3259  3315 I jxcore-log: DEBUG createNativeListener: listening 35965
03-29 11:07:24.301  3259  3315 I jxcore-log: 
,03-29 11:07:24.315  3259  3315 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-29 11:07:24.315  3259  3315 I jxcore-log: 
,03-29 11:07:24.318  3259  3315 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-29 11:07:24.318  3259  3315 I jxcore-log: 
,03-29 11:07:24.320  3259  3315 I jxcore-log: DEBUG createNativeListener: new mux
03-29 11:07:24.320  3259  3315 I jxcore-log: 
,03-29 11:07:24.347  3259  3315 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 11:07:24.347  3259  3315 I jxcore-log: 
,03-29 11:07:24.349  3259  3315 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 11:07:24.349  3259  3315 I jxcore-log: 
,03-29 11:07:24.353  3259  3315 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 11:07:24.353  3259  3315 I jxcore-log: 
,03-29 11:07:24.355  3259  3315 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 11:07:24.355  3259  3315 I jxcore-log: 
,03-29 11:07:24.388  3259  3315 I jxcore-log: ok 7 Send/recvd #1 should be equal length
03-29 11:07:24.388  3259  3315 I jxcore-log: 
,03-29 11:07:24.389  3259  3315 I jxcore-log: ok 8 Send/recvd #1 should be same,
03-29 11:07:24.389  3259  3315 I jxcore-log: 
03-29 11:07:24.391  3259  3315 I jxcore-log: ok 9 Send/recvd #2 should be equal length
03-29 11:07:24.391  3259  3315 I jxcore-log: 
,03-29 11:07:24.391  3259  3315 I jxcore-log: ok 10 Send/recvd #2 should be same
03-29 11:07:24.391  3259  3315 I jxcore-log: 
03-29 11:07:24.394  3259  3315 I jxcore-log: ok 11 Should be exactly 2 client sockets
03-29 11:07:24.394  3259  3315 I jxcore-log: 
,03-29 11:07:24.402  3259  3315 I jxcore-log: # teardown
03-29 11:07:24.402  3259  3315 I jxcore-log: 
,03-29 11:07:24.551  3259  3315 I jxcore-log: DEBUG createNativeListener: stream close:,
03-29 11:07:24.551  3259  3315 I jxcore-log: 
,03-29 11:07:24.559  3259  3315 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 11:07:24.559  3259  3315 I jxcore-log: 
,03-29 11:07:24.561  3259  3315 I jxcore-log: DEBUG createNativeListener: mux close
03-29 11:07:24.561  3259  3315 I jxcore-log: 
,03-29 11:07:24.565  3259  3315 I jxcore-log: # setup
03-29 11:07:24.565  3259  3315 I jxcore-log: 
,03-29 11:07:24.566  3259  3315 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-29 11:07:24.566  3259  3315 I jxcore-log: 
,03-29 11:07:24.730  3259  3315 I jxcore-log: # 5. native server - closing incoming stream cleans outgoing socket
03-29 11:07:24.730  3259  3315 I jxcore-log: 
,03-29 11:07:24.851  3259  3315 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 11:07:24.851  3259  3315 I jxcore-log: 
,03-29 11:07:24.859  3259  3315 I jxcore-log: DEBUG createNativeListener: listening 59966
03-29 11:07:24.859  3259  3315 I jxcore-log: 
,03-29 11:07:24.867  3259  3315 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-29 11:07:24.867  3259  3315 I jxcore-log: 
,03-29 11:07:24.868  3259  3315 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-29 11:07:24.868  3259  3315 I jxcore-log: 
,03-29 11:07:24.870  3259  3315 I jxcore-log: DEBUG createNativeListener: new mux
03-29 11:07:24.870  3259  3315 I jxcore-log: 
,03-29 11:07:24.882  3259  3315 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 11:07:24.882  3259  3315 I jxcore-log: 
,03-29 11:07:24.885  3259  3315 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 11:07:24.885  3259  3315 I jxcore-log: 
,03-29 11:07:24.898  3259  3315 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 11:07:24.898  3259  3315 I jxcore-log: 
,03-29 11:07:24.912  3259  3315 I jxcore-log: ok 12 socket shouldn't close until after stream
03-29 11:07:24.912  3259  3315 I jxcore-log: 
,03-29 11:07:24.913  3259  3315 I jxcore-log: ok 13 incoming remains open
03-29 11:07:24.913  3259  3315 I jxcore-log: 
,03-29 11:07:24.919  3259  3315 I jxcore-log: # teardown
03-29 11:07:24.919  3259  3315 I jxcore-log: 
,03-29 11:07:25.115  3259  3315 I jxcore-log: DEBUG createNativeListener: mux close
03-29 11:07:25.115  3259  3315 I jxcore-log: 
,03-29 11:07:25.121  3259  3315 I jxcore-log: # setup
03-29 11:07:25.121  3259  3315 I jxcore-log: 
,03-29 11:07:25.122  3259  3315 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-29 11:07:25.122  3259  3315 I jxcore-log: 
,03-29 11:07:25.325  3259  3315 I jxcore-log: # 6. native server - closing incoming connection cleans outgoing socket
03-29 11:07:25.325  3259  3315 I jxcore-log: 
,03-29 11:07:25.428  3259  3315 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 11:07:25.428  3259  3315 I jxcore-log: 
03-29 11:07:25.436  3259  3315 I jxcore-log: DEBUG createNativeListener: listening 44935
03-29 11:07:25.436  3259  3315 I jxcore-log: 
,03-29 11:07:25.444  3259  3315 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-29 11:07:25.444  3259  3315 I jxcore-log: 
,03-29 11:07:25.445  3259  3315 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-29 11:07:25.445  3259  3315 I jxcore-log: 
03-29 11:07:25.447  3259  3315 I jxcore-log: DEBUG createNativeListener: new mux
03-29 11:07:25.447  3259  3315 I jxcore-log: 
,03-29 11:07:25.457  3259  3315 I jxcore-log: ok 14 we should not have gotten an error
03-29 11:07:25.457  3259  3315 I jxcore-log: 
,03-29 11:07:25.462  3259  3315 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 11:07:25.462  3259  3315 I jxcore-log: 
,03-29 11:07:25.465  3259  3315 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 11:07:25.465  3259  3315 I jxcore-log: 
,03-29 11:07:25.476  3259  3315 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 11:07:25.476  3259  3315 I jxcore-log: 
,03-29 11:07:25.479  3259  3315 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-29 11:07:25.479  3259  3315 I jxcore-log: 
,03-29 11:07:25.487  3259  3315 I jxcore-log: ok 15 socket shouldn't close until after incoming
03-29 11:07:25.487  3259  3315 I jxcore-log: 
,03-29 11:07:25.488  3259  3315 I jxcore-log: ok 16 incoming is cleaned up
03-29 11:07:25.488  3259  3315 I jxcore-log: 
03-29 11:07:25.493  3259  3315 I jxcore-log: # teardown
03-29 11:07:25.493  3259  3315 I jxcore-log: 
,03-29 11:07:25.640  3259  3315 I jxcore-log: # setup
03-29 11:07:25.640  3259  3315 I jxcore-log: 
,03-29 11:07:25.674  1240  1240 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 11:07:25.773  3259  3315 I jxcore-log: # 7. native server - closing outgoing socket cleans associated mux stream
03-29 11:07:25.773  3259  3315 I jxcore-log: 
,03-29 11:07:25.829   823  1250 I ActivityManager: Start proc 3695:com.google.android.youtube/u0a86 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,03-29 11:07:25.912  3369  3712 V GoogleAuthProtoRequest: [335] a.<init>: mAccountName set to: thalitester@gmail.com
,03-29 11:07:25.947  3695  3713 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-29 11:07:25.948  3695  3713 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-29 11:07:25.952  3259  3315 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 11:07:25.952  3259  3315 I jxcore-log: 
,03-29 11:07:25.955  3259  3315 I jxcore-log: DEBUG createNativeListener: listening 49182
03-29 11:07:25.955  3259  3315 I jxcore-log: 
,03-29 11:07:25.961  3259  3315 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-29 11:07:25.961  3259  3315 I jxcore-log: 
03-29 11:07:25.962  3259  3315 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-29 11:07:25.962  3259  3315 I jxcore-log: 
,03-29 11:07:25.966  3259  3315 I jxcore-log: DEBUG createNativeListener: new mux
03-29 11:07:25.966  3259  3315 I jxcore-log: 
,03-29 11:07:25.978  3259  3315 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 11:07:25.978  3259  3315 I jxcore-log: 
,03-29 11:07:25.982  3259  3315 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 11:07:25.982  3259  3315 I jxcore-log: 
,03-29 11:07:25.996  3695  3713 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,03-29 11:07:25.999  1240  2551 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
03-29 11:07:25.999  1240  2551 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 11:07:25.999  1240  2551 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 11:07:25.999  1240  2551 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 11:07:26.004  1240  2551 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 11:07:26.006  3259  3315 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 11:07:26.006  3259  3315 I jxcore-log: 
,03-29 11:07:26.015  3259  3315 I jxcore-log: ok 17 stream was closed
03-29 11:07:26.015  3259  3315 I jxcore-log: 
,03-29 11:07:26.018  3259  3315 I jxcore-log: ok 18 incoming should survive
03-29 11:07:26.018  3259  3315 I jxcore-log: 
03-29 11:07:26.018  3259  3315 I jxcore-log: ok 19 mux should have no streams
03-29 11:07:26.018  3259  3315 I jxcore-log: 
,03-29 11:07:26.023  3259  3315 I jxcore-log: # teardown
03-29 11:07:26.023  3259  3315 I jxcore-log: 
,03-29 11:07:26.039  3695  3713 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-29 11:07:26.074   823  1098 I art     : Explicit concurrent mark sweep GC freed 16081(732KB) AllocSpace objects, 3(236KB) LOS objects, 32% free, 33MB/49MB, paused 1.496ms total 52.015ms
,03-29 11:07:26.080  3369  3712 W ExperimentUpdateService: [335] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,03-29 11:07:26.081  3369  3712 W ExperimentUpdateService: [335] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-29 11:07:26.081  3369  3712 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-29 11:07:26.081  3369  3712 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-29 11:07:26.081  3369  3712 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-29 11:07:26.081  3369  3712 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-29 11:07:26.081  3369  3712 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-29 11:07:26.081  3369  3712 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-29 11:07:26.081  3369  3712 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-29 11:07:26.081  3369  3712 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-29 11:07:26.081  3369  3712 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-29 11:07:26.081  3369  3712 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-29 11:07:26.102  3725  3725 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads-207517899.jar --oat-fd=24 --oat-location=/data/data/com.google.android.youtube/cache/ads-207517899.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,03-29 11:07:26.117  3695  3695 E YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,03-29 11:07:26.131  3725  3725 I dex2oat : dex2oat took 28.027ms (threads: 4) arena alloc=165KB java alloc=12KB native alloc=1091KB free=6MB
,03-29 11:07:26.199  3259  3315 I jxcore-log: DEBUG createNativeListener: mux close
03-29 11:07:26.199  3259  3315 I jxcore-log: 
,03-29 11:07:26.204  3259  3315 I jxcore-log: # setup
03-29 11:07:26.204  3259  3315 I jxcore-log: 
,03-29 11:07:26.205  3259  3315 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-29 11:07:26.205  3259  3315 I jxcore-log: 
,03-29 11:07:26.231  3695  3695 W InstanceID/Rpc: Found 10011
,03-29 11:07:26.353  3259  3315 I jxcore-log: # 8. native server - closing the whole server cleans everything up
03-29 11:07:26.353  3259  3315 I jxcore-log: 
,03-29 11:07:26.512  3259  3315 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 11:07:26.512  3259  3315 I jxcore-log: 
03-29 11:07:26.515  3259  3315 I jxcore-log: DEBUG createNativeListener: listening 40385
03-29 11:07:26.515  3259  3315 I jxcore-log: 
,03-29 11:07:26.523  3259  3315 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-29 11:07:26.523  3259  3315 I jxcore-log: 
03-29 11:07:26.524  3259  3315 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-29 11:07:26.524  3259  3315 I jxcore-log: 
03-29 11:07:26.526  3259  3315 I jxcore-log: DEBUG createNativeListener: new mux
03-29 11:07:26.526  3259  3315 I jxcore-log: 
,03-29 11:07:26.539  3259  3315 I jxcore-log: ok 20 we should not have gotten an error
03-29 11:07:26.539  3259  3315 I jxcore-log: ,
,03-29 11:07:26.548  3259  3315 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 11:07:26.548  3259  3315 I jxcore-log: ,
03-29 11:07:26.551  3259  3315 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 11:07:26.551  3259  3315 I jxcore-log: ,
,03-29 11:07:26.563  3259  3315 I jxcore-log: ok 21 Buffers are identical
,03-29 11:07:26.563  3259  3315 I jxcore-log: 
03-29 11:07:26.565  3259  3315 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 11:07:26.565  3259  3315 I jxcore-log: 
,03-29 11:07:26.570  3259  3315 I jxcore-log: DEBUG createNativeListener: mux close,
03-29 11:07:26.570  3259  3315 I jxcore-log: 
,03-29 11:07:26.575  3259  3315 I jxcore-log: ok 22 native server is nulled out
03-29 11:07:26.575  3259  3315 I jxcore-log: ,
03-29 11:07:26.575  3259  3315 I jxcore-log: ok 23 native server should be closed
03-29 11:07:26.575  3259  3315 I jxcore-log: 
,03-29 11:07:26.576  3259  3315 I jxcore-log: ok 24 incoming has been removed
03-29 11:07:26.576  3259  3315 I jxcore-log: 
03-29 11:07:26.577  3259  3315 I jxcore-log: ok 25 Incoming should be done,
03-29 11:07:26.577  3259  3315 I jxcore-log: 
,03-29 11:07:26.578  3259  3315 I jxcore-log: ok 26 The mux object should be closed
,03-29 11:07:26.578  3259  3315 I jxcore-log: 
03-29 11:07:26.579  3259  3315 I jxcore-log: ok 27 The mux stream should be closed
03-29 11:07:26.579  3259  3315 I jxcore-log: 
03-29 11:07:26.579  3259  3315 I jxcore-log: DEBUG createNativeListener: incoming socket close
,03-29 11:07:26.579  3259  3315 I jxcore-log: 
,03-29 11:07:26.593  3259  3315 I jxcore-log: # teardown
,03-29 11:07:26.593  3259  3315 I jxcore-log: 
,03-29 11:07:26.762  3259  3315 I jxcore-log: # setup
03-29 11:07:26.762  3259  3315 I jxcore-log: 
,03-29 11:07:26.878  3259  3315 I jxcore-log: # 9. native server - we can get a ton of connections and data through and still clean up the server completely
03-29 11:07:26.878  3259  3315 I jxcore-log: 
,03-29 11:07:27.033  3259  3315 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 11:07:27.033  3259  3315 I jxcore-log: 
,03-29 11:07:27.041  3259  3315 I jxcore-log: DEBUG createNativeListener: listening 39739
03-29 11:07:27.041  3259  3315 I jxcore-log: 
,03-29 11:07:27.073  3259  3315 I jxcore-log: DEBUG createNativeListener: new incoming socket,
03-29 11:07:27.073  3259  3315 I jxcore-log: 
,03-29 11:07:27.080  3259  3315 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-29 11:07:27.080  3259  3315 I jxcore-log: 
,03-29 11:07:27.082  3259  3315 I jxcore-log: DEBUG createNativeListener: new mux
03-29 11:07:27.082  3259  3315 I jxcore-log: 
,03-29 11:07:27.087  3259  3315 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-29 11:07:27.087  3259  3315 I jxcore-log: ,
03-29 11:07:27.088  3259  3315 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-29 11:07:27.088  3259  3315 I jxcore-log: 
,03-29 11:07:27.091  3259  3315 I jxcore-log: DEBUG createNativeListener: new mux
,03-29 11:07:27.091  3259  3315 I jxcore-log: 
,03-29 11:07:27.095  3259  3315 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-29 11:07:27.095  3259  3315 I jxcore-log: 
,03-29 11:07:27.096  3259  3315 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-29 11:07:27.096  3259  3315 I jxcore-log: 
,03-29 11:07:27.099  3259  3315 I jxcore-log: DEBUG createNativeListener: new mux
03-29 11:07:27.099  3259  3315 I jxcore-log: 
,03-29 11:07:27.103  3259  3315 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-29 11:07:27.103  3259  3315 I jxcore-log: 
03-29 11:07:27.103  3259  3315 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-29 11:07:27.103  3259  3315 I jxcore-log: 
03-29 11:07:27.105  3259  3315 I jxcore-log: DEBUG createNativeListener: new mux
03-29 11:07:27.105  3259  3315 I jxcore-log: 
,03-29 11:07:27.108  3259  3315 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-29 11:07:27.108  3259  3315 I jxcore-log: 
,03-29 11:07:27.109  3259  3315 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-29 11:07:27.109  3259  3315 I jxcore-log: 
,03-29 11:07:27.110  3259  3315 I jxcore-log: DEBUG createNativeListener: new mux
03-29 11:07:27.110  3259  3315 I jxcore-log: 
,03-29 11:07:27.114  3259  3315 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-29 11:07:27.114  3259  3315 I jxcore-log: 
,03-29 11:07:27.115  3259  3315 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-29 11:07:27.115  3259  3315 I jxcore-log: 
,03-29 11:07:27.115  1240  3786 I VacuumService: Vacuum at: now=1459242447115 tag=VacuumService
03-29 11:07:27.116  3259  3315 I jxcore-log: DEBUG createNativeListener: new mux
03-29 11:07:27.116  3259  3315 I jxcore-log: 
,03-29 11:07:27.120  3259  3315 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-29 11:07:27.120  3259  3315 I jxcore-log: 
03-29 11:07:27.121  3259  3315 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-29 11:07:27.121  3259  3315 I jxcore-log: 
,03-29 11:07:27.122  3259  3315 I jxcore-log: DEBUG createNativeListener: new mux
03-29 11:07:27.122  3259  3315 I jxcore-log: 
03-29 11:07:27.125  3259  3315 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-29 11:07:27.125  3259  3315 I jxcore-log: 
,03-29 11:07:27.125  1240  3787 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,03-29 11:07:27.125  3259  3315 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-29 11:07:27.125  3259  3315 I jxcore-log: 
03-29 11:07:27.126  3259  3315 I jxcore-log: DEBUG createNativeListener: new mux
03-29 11:07:27.126  3259  3315 I jxcore-log: 
,03-29 11:07:27.131  3259  3315 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-29 11:07:27.131  3259  3315 I jxcore-log: 
03-29 11:07:27.132  3259  3315 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-29 11:07:27.132  3259  3315 I jxcore-log: 
,03-29 11:07:27.134  3259  3315 I jxcore-log: DEBUG createNativeListener: new mux
03-29 11:07:27.134  3259  3315 I jxcore-log: 
03-29 11:07:27.136  3259  3315 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-29 11:07:27.136  3259  3315 I jxcore-log: 
03-29 11:07:27.137  3259  3315 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-29 11:07:27.137  3259  3315 I jxcore-log: 
,03-29 11:07:27.138  3259  3315 I jxcore-log: DEBUG createNativeListener: new mux
03-29 11:07:27.138  3259  3315 I jxcore-log: 
,03-29 11:07:27.155  1240  3787 W Uploader: No account for auth token provided
,03-29 11:07:27.202   823  1450 I ActivityManager: Killing 3067:com.google.android.music:main/u0a66 (adj 15): empty #17
,03-29 11:07:27.229  3259  3315 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 11:07:27.229  3259  3315 I jxcore-log: 
,03-29 11:07:27.231  3259  3315 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 11:07:27.231  3259  3315 I jxcore-log: 
,03-29 11:07:27.233  3259  3315 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 11:07:27.233  3259  3315 I jxcore-log: 
,03-29 11:07:27.235  3259  3315 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 11:07:27.235  3259  3315 I jxcore-log: 
03-29 11:07:27.236  3259  3315 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 11:07:27.236  3259  3315 I jxcore-log: 
,03-29 11:07:27.237  3259  3315 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 11:07:27.237  3259  3315 I jxcore-log: 
,03-29 11:07:27.239  3259  3315 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 11:07:27.239  3259  3315 I jxcore-log: 
,03-29 11:07:27.240  3259  3315 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 11:07:27.240  3259  3315 I jxcore-log: 
,03-29 11:07:27.242  3259  3315 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 11:07:27.242  3259  3315 I jxcore-log: 
,03-29 11:07:27.244  3259  3315 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 11:07:27.244  3259  3315 I jxcore-log: 
,03-29 11:07:27.245  3259  3315 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 11:07:27.245  3259  3315 I jxcore-log: 
,03-29 11:07:27.246  3259  3315 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 11:07:27.246  3259  3315 I jxcore-log: 
,03-29 11:07:27.247  3259  3315 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 11:07:27.247  3259  3315 I jxcore-log: 
,03-29 11:07:27.249  3259  3315 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 11:07:27.249  3259  3315 I jxcore-log: 
,03-29 11:07:27.250  3259  3315 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 11:07:27.250  3259  3315 I jxcore-log: 
,03-29 11:07:27.252  3259  3315 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 11:07:27.252  3259  3315 I jxcore-log: 
,03-29 11:07:27.254  3259  3315 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 11:07:27.254  3259  3315 I jxcore-log: 
,03-29 11:07:27.255  3259  3315 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 11:07:27.255  3259  3315 I jxcore-log: 
,03-29 11:07:27.259  3259  3315 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 11:07:27.259  3259  3315 I jxcore-log: 
,03-29 11:07:27.260  3259  3315 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 11:07:27.260  3259  3315 I jxcore-log: 
,03-29 11:07:27.262  3259  3315 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 11:07:27.262  3259  3315 I jxcore-log: 
,03-29 11:07:27.263  3259  3315 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 11:07:27.263  3259  3315 I jxcore-log: 
,03-29 11:07:27.265  3259  3315 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 11:07:27.265  3259  3315 I jxcore-log: 
,03-29 11:07:27.266  3259  3315 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 11:07:27.266  3259  3315 I jxcore-log: 
,03-29 11:07:27.268  3259  3315 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 11:07:27.268  3259  3315 I jxcore-log: 
,03-29 11:07:27.270  3259  3315 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 11:07:27.270  3259  3315 I jxcore-log: 
,03-29 11:07:27.271  3259  3315 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 11:07:27.271  3259  3315 I jxcore-log: 
,03-29 11:07:27.273  3259  3315 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 11:07:27.273  3259  3315 I jxcore-log: 
,03-29 11:07:27.274  3259  3315 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 11:07:27.274  3259  3315 I jxcore-log: 
,03-29 11:07:27.276  3259  3315 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 11:07:27.276  3259  3315 I jxcore-log: 
,03-29 11:07:27.277  3259  3315 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 11:07:27.277  3259  3315 I jxcore-log: 
,03-29 11:07:27.279  3259  3315 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 11:07:27.279  3259  3315 I jxcore-log: 
,03-29 11:07:27.281  3259  3315 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 11:07:27.281  3259  3315 I jxcore-log: 
,03-29 11:07:27.283  3259  3315 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 11:07:27.283  3259  3315 I jxcore-log: 
,03-29 11:07:27.284  3259  3315 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 11:07:27.284  3259  3315 I jxcore-log: 
,03-29 11:07:27.286  3259  3315 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 11:07:27.286  3259  3315 I jxcore-log: 
,03-29 11:07:27.287  3259  3315 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 11:07:27.287  3259  3315 I jxcore-log: 
,03-29 11:07:27.289  3259  3315 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 11:07:27.289  3259  3315 I jxcore-log: 
,03-29 11:07:27.290  3259  3315 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 11:07:27.290  3259  3315 I jxcore-log: 
,03-29 11:07:27.292  3259  3315 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 11:07:27.292  3259  3315 I jxcore-log: 
,03-29 11:07:27.294  3259  3315 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 11:07:27.294  3259  3315 I jxcore-log: 
,03-29 11:07:27.295  3259  3315 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 11:07:27.295  3259  3315 I jxcore-log: 
,03-29 11:07:27.296  3259  3315 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 11:07:27.296  3259  3315 I jxcore-log: 
,03-29 11:07:27.298  3259  3315 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 11:07:27.298  3259  3315 I jxcore-log: 
,03-29 11:07:27.299  3259  3315 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 11:07:27.299  3259  3315 I jxcore-log: 
,03-29 11:07:27.301  3259  3315 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 11:07:27.301  3259  3315 I jxcore-log: 
,03-29 11:07:27.302  3259  3315 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 11:07:27.302  3259  3315 I jxcore-log: 
,03-29 11:07:27.304  3259  3315 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 11:07:27.304  3259  3315 I jxcore-log: 
,03-29 11:07:27.308   823  1450 I ActivityManager: Killing 1536:com.google.android.googlequicksearchbox:search/u0a28 (adj 15): empty #18
,03-29 11:07:27.313  3259  3315 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 11:07:27.313  3259  3315 I jxcore-log: 
,03-29 11:07:27.315  3259  3315 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 11:07:27.315  3259  3315 I jxcore-log: 
03-29 11:07:27.316  3259  3315 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 11:07:27.316  3259  3315 I jxcore-log: 
,03-29 11:07:27.317  3259  3315 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 11:07:27.317  3259  3315 I jxcore-log: 
03-29 11:07:27.318  3259  3315 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 11:07:27.318  3259  3315 I jxcore-log: 
,03-29 11:07:27.320  3259  3315 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 11:07:27.320  3259  3315 I jxcore-log: 
,03-29 11:07:27.321  3259  3315 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 11:07:27.321  3259  3315 I jxcore-log: 
,03-29 11:07:27.322  3259  3315 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 11:07:27.322  3259  3315 I jxcore-log: 
,03-29 11:07:27.326  3259  3315 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 11:07:27.326  3259  3315 I jxcore-log: 
,03-29 11:07:27.328  3259  3315 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 11:07:27.328  3259  3315 I jxcore-log: 
,03-29 11:07:27.329  3259  3315 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 11:07:27.329  3259  3315 I jxcore-log: ,
03-29 11:07:27.330  3259  3315 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 11:07:27.330  3259  3315 I jxcore-log: 
,03-29 11:07:27.332  3259  3315 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 11:07:27.332  3259  3315 I jxcore-log: ,
,03-29 11:07:27.333  3259  3315 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 11:07:27.333  3259  3315 I jxcore-log: 
,03-29 11:07:27.335  3259  3315 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 11:07:27.335  3259  3315 I jxcore-log: 
,03-29 11:07:27.336  3259  3315 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 11:07:27.336  3259  3315 I jxcore-log: 
,03-29 11:07:27.339  3259  3315 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 11:07:27.339  3259  3315 I jxcore-log: 
03-29 11:07:27.340  3259  3315 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 11:07:27.340  3259  3315 I jxcore-log: 
03-29 11:07:27.341  3259  3315 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 11:07:27.341  3259  3315 I jxcore-log: 
03-29 11:07:27.345  3259  3315 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 11:07:27.345  3259  3315 I jxcore-log: 
03-29 11:07:27.346  3259  3315 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 11:07:27.346  3259  3315 I jxcore-log: 
,03-29 11:07:27.348  3259  3315 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 11:07:27.348  3259  3315 I jxcore-log: 
,03-29 11:07:27.351  3259  3315 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 11:07:27.351  3259  3315 I jxcore-log: 
,03-29 11:07:27.353  3259  3315 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 11:07:27.353  3259  3315 I jxcore-log: 
,03-29 11:07:27.356  3259  3315 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 11:07:27.356  3259  3315 I jxcore-log: 
,03-29 11:07:27.358  3259  3315 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 11:07:27.358  3259  3315 I jxcore-log: 
,03-29 11:07:27.359  3259  3315 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 11:07:27.359  3259  3315 I jxcore-log: 
,03-29 11:07:27.360  3259  3315 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 11:07:27.360  3259  3315 I jxcore-log: 
,03-29 11:07:27.362  3259  3315 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 11:07:27.362  3259  3315 I jxcore-log: 
,03-29 11:07:27.363  3259  3315 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 11:07:27.363  3259  3315 I jxcore-log: 
,03-29 11:07:27.364  3259  3315 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 11:07:27.364  3259  3315 I jxcore-log: 
,03-29 11:07:27.366  3259  3315 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 11:07:27.366  3259  3315 I jxcore-log: 
,03-29 11:07:27.438  3259  3315 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 11:07:27.438  3259  3315 I jxcore-log: 
,03-29 11:07:27.439  3259  3315 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 11:07:27.439  3259  3315 I jxcore-log: 
,03-29 11:07:27.440  3259  3315 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 11:07:27.440  3259  3315 I jxcore-log: 
,03-29 11:07:27.442  3259  3315 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 11:07:27.442  3259  3315 I jxcore-log: 
03-29 11:07:27.447  3259  3315 I jxcore-log: DEBUG createNativeListener: mux close
03-29 11:07:27.447  3259  3315 I jxcore-log: 
03-29 11:07:27.448  3259  3315 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 11:07:27.448  3259  3315 I jxcore-log: 
03-29 11:07:27.449  3259  3315 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 11:07:27.449  3259  3315 I jxcore-log: 
03-29 11:07:27.450  3259  3315 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 11:07:27.450  3259  3315 I jxcore-log: 
03-29 11:07:27.451  3259  3315 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 11:07:27.451  3259  3315 I jxcore-log: 
03-29 11:07:27.451  3259  3315 I jxcore-log: DEBUG createNativeListener: mux close
03-29 11:07:27.451  3259  3315 I jxcore-log: 
,03-29 11:07:27.453  3259  3315 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 11:07:27.453  3259  3315 I jxcore-log: 
03-29 11:07:27.454  3259  3315 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 11:07:27.454  3259  3315 I jxcore-log: 
03-29 11:07:27.455  3259  3315 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 11:07:27.455  3259  3315 I jxcore-log: 
03-29 11:07:27.456  3259  3315 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 11:07:27.456  3259  3315 I jxcore-log: 
03-29 11:07:27.478   823  1013 D WifiService: Client connection lost with reason: 4
,03-29 11:07:27.478  3259  3315 I jxcore-log: DEBUG createNativeListener: mux close
03-29 11:07:27.478  3259  3315 I jxcore-log: 
03-29 11:07:27.481  3259  3315 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 11:07:27.481  3259  3315 I jxcore-log: 
,03-29 11:07:27.482  3259  3315 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 11:07:27.482  3259  3315 I jxcore-log: 
,03-29 11:07:27.483  3259  3315 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 11:07:27.483  3259  3315 I jxcore-log: 
03-29 11:07:27.484  3259  3315 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 11:07:27.484  3259  3315 I jxcore-log: 
,03-29 11:07:27.486  3259  3315 I jxcore-log: DEBUG createNativeListener: mux close
03-29 11:07:27.486  3259  3315 I jxcore-log: 
03-29 11:07:27.488  3259  3315 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 11:07:27.488  3259  3315 I jxcore-log: 
,03-29 11:07:27.489  3259  3315 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 11:07:27.489  3259  3315 I jxcore-log: 
03-29 11:07:27.490  3259  3315 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 11:07:27.490  3259  3315 I jxcore-log: 
03-29 11:07:27.491  3259  3315 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 11:07:27.491  3259  3315 I jxcore-log: 
03-29 11:07:27.493  3259  3315 I jxcore-log: DEBUG createNativeListener: mux close
03-29 11:07:27.493  3259  3315 I jxcore-log: 
,03-29 11:07:27.495  3259  3315 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 11:07:27.495  3259  3315 I jxcore-log: 
03-29 11:07:27.496  3259  3315 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 11:07:27.496  3259  3315 I jxcore-log: 
03-29 11:07:27.497  3259  3315 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 11:07:27.497  3259  3315 I jxcore-log: 
03-29 11:07:27.498  3259  3315 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 11:07:27.498  3259  3315 I jxcore-log: 
03-29 11:07:27.500  3259  3315 I jxcore-log: DEBUG createNativeListener: mux close
03-29 11:07:27.500  3259  3315 I jxcore-log: 
03-29 11:07:27.501  3259  3315 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 11:07:27.501  3259  3315 I jxcore-log: 
,03-29 11:07:27.502  3259  3315 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 11:07:27.502  3259  3315 I jxcore-log: 
,03-29 11:07:27.504  3259  3315 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 11:07:27.504  3259  3315 I jxcore-log: 
,03-29 11:07:27.505  3259  3315 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 11:07:27.505  3259  3315 I jxcore-log: 
,03-29 11:07:27.507  3259  3315 I jxcore-log: DEBUG createNativeListener: mux close
03-29 11:07:27.507  3259  3315 I jxcore-log: 
,03-29 11:07:27.508  3259  3315 I jxcore-log: DEBUG createNativeListener: stream close:,
03-29 11:07:27.508  3259  3315 I jxcore-log: 
03-29 11:07:27.509  3259  3315 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 11:07:27.509  3259  3315 I jxcore-log: ,
03-29 11:07:27.511  3259  3315 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 11:07:27.511  3259  3315 I jxcore-log: 
,03-29 11:07:27.512  3259  3315 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 11:07:27.512  3259  3315 I jxcore-log: 
,03-29 11:07:27.513  3259  3315 I jxcore-log: DEBUG createNativeListener: mux close
03-29 11:07:27.513  3259  3315 I jxcore-log: 
03-29 11:07:27.514  3259  3315 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 11:07:27.514  3259  3315 I jxcore-log: ,
03-29 11:07:27.515  3259  3315 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 11:07:27.515  3259  3315 I jxcore-log: 
03-29 11:07:27.516  3259  3315 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 11:07:27.516  3259  3315 I jxcore-log: ,
03-29 11:07:27.518  3259  3315 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 11:07:27.518  3259  3315 I jxcore-log: 
03-29 11:07:27.520  3259  3315 I jxcore-log: DEBUG createNativeListener: mux close,
03-29 11:07:27.520  3259  3315 I jxcore-log: 
,03-29 11:07:27.522  3259  3315 I jxcore-log: DEBUG createNativeListener: stream close:,
03-29 11:07:27.522  3259  3315 I jxcore-log: 
03-29 11:07:27.524  3259  3315 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 11:07:27.524  3259  3315 I jxcore-log: 
,03-29 11:07:27.527  3259  3315 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 11:07:27.527  3259  3315 I jxcore-log: 
,03-29 11:07:27.528  3259  3315 I jxcore-log: DEBUG createNativeListener: stream close:,
03-29 11:07:27.528  3259  3315 I jxcore-log: 
,03-29 11:07:27.530  3259  3315 I jxcore-log: DEBUG createNativeListener: mux close,
03-29 11:07:27.530  3259  3315 I jxcore-log: 
,03-29 11:07:27.534  3259  3315 I jxcore-log: ok 28 native server is nulled out
,03-29 11:07:27.534  3259  3315 I jxcore-log: 
03-29 11:07:27.535  3259  3315 I jxcore-log: ok 29 native server should be closed
03-29 11:07:27.535  3259  3315 I jxcore-log: 
03-29 11:07:27.535  3259  3315 I jxcore-log: ok 30 incoming has been removed
03-29 11:07:27.535  3259  3315 I jxcore-log: 
,03-29 11:07:27.536  3259  3315 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-29 11:07:27.536  3259  3315 I jxcore-log: 
03-29 11:07:27.536  3259  3315 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-29 11:07:27.536  3259  3315 I jxcore-log: 
03-29 11:07:27.537  3259  3315 I jxcore-log: DEBUG createNativeListener: incoming socket close,
03-29 11:07:27.537  3259  3315 I jxcore-log: 
03-29 11:07:27.537  3259  3315 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-29 11:07:27.537  3259  3315 I jxcore-log: 
03-29 11:07:27.538  3259  3315 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-29 11:07:27.538  3259  3315 I jxcore-log: ,
03-29 11:07:27.538  3259  3315 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-29 11:07:27.538  3259  3315 I jxcore-log: 
03-29 11:07:27.539  3259  3315 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-29 11:07:27.539  3259  3315 I jxcore-log: 
03-29 11:07:27.540  3259  3315 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-29 11:07:27.540  3259  3315 I jxcore-log: 
,03-29 11:07:27.540  3259  3315 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-29 11:07:27.540  3259  3315 I jxcore-log: 
03-29 11:07:27.541  3259  3315 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-29 11:07:27.541  3259  3315 I jxcore-log: 
,03-29 11:07:27.644  3259  3315 I jxcore-log: # teardown
,03-29 11:07:27.644  3259  3315 I jxcore-log: 
,03-29 11:07:27.786  1240  3787 W Uploader: No account for auth token provided
,03-29 11:07:27.786  3259  3315 I jxcore-log: # setup
03-29 11:07:27.786  3259  3315 I jxcore-log: 
,03-29 11:07:27.968  1240  3787 W Uploader: No account for auth token provided
,03-29 11:07:27.981  3259  3315 I jxcore-log: # 10. native server - simulate mux failure, make sure everything is cleaned up
,03-29 11:07:27.981  3259  3315 I jxcore-log: 
,03-29 11:07:28.138  3259  3315 I jxcore-log: DEBUG createNativeListener: creating native server
,03-29 11:07:28.138  3259  3315 I jxcore-log: 
,03-29 11:07:28.142  3259  3315 I jxcore-log: DEBUG createNativeListener: listening 44874
,03-29 11:07:28.142  3259  3315 I jxcore-log: 
,03-29 11:07:28.148  3259  3315 I jxcore-log: DEBUG createNativeListener: new incoming socket
,03-29 11:07:28.148  3259  3315 I jxcore-log: 
,03-29 11:07:28.150  3259  3315 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-29 11:07:28.150  3259  3315 I jxcore-log: 
,03-29 11:07:28.151  3259  3315 I jxcore-log: DEBUG createNativeListener: new mux
03-29 11:07:28.151  3259  3315 I jxcore-log: 
,03-29 11:07:28.158  3259  3315 I jxcore-log: ok 31 we should not have gotten an error
03-29 11:07:28.158  3259  3315 I jxcore-log: 
,03-29 11:07:28.162  3259  3315 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 11:07:28.162  3259  3315 I jxcore-log: 
,03-29 11:07:28.164  3259  3315 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 11:07:28.164  3259  3315 I jxcore-log: 
,03-29 11:07:28.173  3259  3315 I jxcore-log: ok 32 Buffers are identical
03-29 11:07:28.173  3259  3315 I jxcore-log: 
,03-29 11:07:28.173  3259  3315 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 11:07:28.173  3259  3315 I jxcore-log: 
,03-29 11:07:28.175  3259  3315 I jxcore-log: DEBUG createNativeListener: mux close
03-29 11:07:28.175  3259  3315 I jxcore-log: 
,03-29 11:07:28.185  3259  3315 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-29 11:07:28.185  3259  3315 I jxcore-log: 
03-29 11:07:28.186  3259  3315 I jxcore-log: ok 33 server should be fine
03-29 11:07:28.186  3259  3315 I jxcore-log: 
,03-29 11:07:28.186  3259  3315 I jxcore-log: ok 34 server should be open
03-29 11:07:28.186  3259  3315 I jxcore-log: 
03-29 11:07:28.186  3259  3315 I jxcore-log: ok 35 incoming has been removed
03-29 11:07:28.186  3259  3315 I jxcore-log: 
03-29 11:07:28.187  3259  3315 I jxcore-log: ok 36 The mux object should be closed
03-29 11:07:28.187  3259  3315 I jxcore-log: 
,03-29 11:07:28.187  3259  3315 I jxcore-log: ok 37 The mux stream should be closed
03-29 11:07:28.187  3259  3315 I jxcore-log: 
03-29 11:07:28.189  1240  3787 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
03-29 11:07:28.189  1240  3787 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 11:07:28.189  1240  3787 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 11:07:28.189  1240  3787 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 11:07:28.197  3259  3315 I jxcore-log: # teardown
03-29 11:07:28.197  3259  3315 I jxcore-log: 
,03-29 11:07:28.198  1240  3787 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 11:07:28.249  1240  3787 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-29 11:07:28.249  1240  3787 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-29 11:07:28.249  1240  3787 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-29 11:07:28.249  1240  3787 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-29 11:07:28.249  1240  3787 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-29 11:07:28.249  1240  3787 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-29 11:07:28.249  1240  3787 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-29 11:07:28.249  1240  3787 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-29 11:07:28.249  1240  3787 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-29 11:07:28.249  1240  3787 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-29 11:07:28.249  1240  3787 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-29 11:07:28.249  1240  3787 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-29 11:07:28.249  1240  3787 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-29 11:07:28.399  3259  3315 I jxcore-log: # setup
03-29 11:07:28.399  3259  3315 I jxcore-log: 
,03-29 11:07:28.460  1240  3787 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,03-29 11:07:28.461  1240  3787 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 11:07:28.461  1240  3787 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-29 11:07:28.462  1240  3787 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 11:07:28.473  1240  3787 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 11:07:28.557  1240  3787 I art     : Explicit concurrent mark sweep GC freed 40151(2MB) AllocSpace objects, 5(385KB) LOS objects, 37% free, 27MB/43MB, paused 1.572ms total 57.162ms
,03-29 11:07:28.566  3259  3315 I jxcore-log: # 11. native server - timing out the incoming connection cleans everything up
03-29 11:07:28.566  3259  3315 I jxcore-log: 
,03-29 11:07:28.587  1240  3787 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-29 11:07:28.587  1240  3787 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-29 11:07:28.587  1240  3787 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-29 11:07:28.587  1240  3787 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-29 11:07:28.587  1240  3787 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-29 11:07:28.587  1240  3787 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-29 11:07:28.587  1240  3787 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-29 11:07:28.587  1240  3787 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-29 11:07:28.587  1240  3787 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-29 11:07:28.587  1240  3787 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-29 11:07:28.587  1240  3787 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-29 11:07:28.587  1240  3787 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-29 11:07:28.587  1240  3787 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-29 11:07:28.761  3259  3315 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 11:07:28.761  3259  3315 I jxcore-log: 
,03-29 11:07:28.765  1240  3787 W Uploader: No account for auth token provided,
03-29 11:07:28.765  3259  3315 I jxcore-log: DEBUG createNativeListener: listening 47341
03-29 11:07:28.765  3259  3315 I jxcore-log: 
,03-29 11:07:28.771  3259  3315 I jxcore-log: DEBUG createNativeListener: new incoming socket,
03-29 11:07:28.771  3259  3315 I jxcore-log: 
,03-29 11:07:28.773  3259  3315 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-29 11:07:28.773  3259  3315 I jxcore-log: 
,03-29 11:07:28.774  3259  3315 I jxcore-log: DEBUG createNativeListener: new mux
03-29 11:07:28.774  3259  3315 I jxcore-log: 
,03-29 11:07:28.781  3259  3315 I jxcore-log: ok 38 we should not have gotten an error
03-29 11:07:28.781  3259  3315 I jxcore-log: 
,03-29 11:07:28.785  3259  3315 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 11:07:28.785  3259  3315 I jxcore-log: ,
03-29 11:07:28.787  3259  3315 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 11:07:28.787  3259  3315 I jxcore-log: 
,03-29 11:07:28.795  3259  3315 I jxcore-log: ok 39 Buffers are identical
03-29 11:07:28.795  3259  3315 I jxcore-log: 
,03-29 11:07:28.799  3259  3315 I jxcore-log: DEBUG createNativeListener: incoming socket timeout
03-29 11:07:28.799  3259  3315 I jxcore-log: 
,03-29 11:07:28.800  3259  3315 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 11:07:28.800  3259  3315 I jxcore-log: 
,03-29 11:07:28.802  3259  3315 I jxcore-log: DEBUG createNativeListener: mux close
03-29 11:07:28.802  3259  3315 I jxcore-log: 
,03-29 11:07:28.807  3259  3315 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-29 11:07:28.807  3259  3315 I jxcore-log: 
,03-29 11:07:28.807  3259  3315 I jxcore-log: ok 40 server should be fine
03-29 11:07:28.807  3259  3315 I jxcore-log: 
,03-29 11:07:28.808  3259  3315 I jxcore-log: ok 41 server should be open
03-29 11:07:28.808  3259  3315 I jxcore-log: 
03-29 11:07:28.808  3259  3315 I jxcore-log: ok 42 incoming has been removed
03-29 11:07:28.808  3259  3315 I jxcore-log: 
03-29 11:07:28.809  3259  3315 I jxcore-log: ok 43 The mux object should be closed
03-29 11:07:28.809  3259  3315 I jxcore-log: 
,03-29 11:07:28.809  3259  3315 I jxcore-log: ok 44 The mux stream should be closed
03-29 11:07:28.809  3259  3315 I jxcore-log: 
03-29 11:07:28.817  3259  3315 I jxcore-log: # teardown
03-29 11:07:28.817  3259  3315 I jxcore-log: 
,03-29 11:07:28.890  1240  3787 W Uploader: No account for auth token provided
,03-29 11:07:28.968  2747  2762 D Finsky  : [249] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,03-29 11:07:29.001  1240  1240 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 11:07:29.005  3259  3315 I jxcore-log: # setup
03-29 11:07:29.005  3259  3315 I jxcore-log: 
,03-29 11:07:29.055  1240  1749 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
03-29 11:07:29.055  1240  3787 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
03-29 11:07:29.056  1240  1749 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 11:07:29.056  1240  1749 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 11:07:29.056  1240  1749 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
03-29 11:07:29.056  1240  3787 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 11:07:29.056  1240  3787 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 11:07:29.056  1240  3787 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 11:07:29.062  1240  1749 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,03-29 11:07:29.067  1240  3787 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,03-29 11:07:29.085  2747  2762 D Finsky  : [249] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,03-29 11:07:29.109  3259  3315 I jxcore-log: # 12. closeAll can close even when connections open
03-29 11:07:29.109  3259  3315 I jxcore-log: 
,03-29 11:07:29.120  1240  3787 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-29 11:07:29.120  1240  3787 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-29 11:07:29.120  1240  3787 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-29 11:07:29.120  1240  3787 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-29 11:07:29.120  1240  3787 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-29 11:07:29.120  1240  3787 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-29 11:07:29.120  1240  3787 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-29 11:07:29.120  1240  3787 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-29 11:07:29.120  1240  3787 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-29 11:07:29.120  1240  3787 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-29 11:07:29.120  1240  3787 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-29 11:07:29.120  1240  3787 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-29 11:07:29.120  1240  3787 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-29 11:07:29.291  1240  3787 W Uploader: No account for auth token provided
,03-29 11:07:29.296  3259  3315 I jxcore-log: ok 45 not possible to connect to the server anymore
,03-29 11:07:29.296  3259  3315 I jxcore-log: 
,03-29 11:07:29.302  3259  3315 I jxcore-log: # teardown
03-29 11:07:29.302  3259  3315 I jxcore-log: 
,03-29 11:07:29.450  1240  3787 W Uploader: No account for auth token provided
,03-29 11:07:29.451  3259  3315 I jxcore-log: # setup
03-29 11:07:29.451  3259  3315 I jxcore-log: 
,03-29 11:07:29.596  1240  3787 W Uploader: No account for auth token provided
,03-29 11:07:29.628  3259  3315 I jxcore-log: # 13. closeAll with promise
03-29 11:07:29.628  3259  3315 I jxcore-log: 
,03-29 11:07:29.764  1240  3787 W Uploader:  no longer exists, so no auth token.
,03-29 11:07:29.798  3259  3315 I jxcore-log: ok 46 not possible to connect to the server anymore
,03-29 11:07:29.798  3259  3315 I jxcore-log: 
,03-29 11:07:29.804  3259  3315 I jxcore-log: # teardown
,03-29 11:07:29.804  3259  3315 I jxcore-log: 
,03-29 11:07:29.922  1240  3787 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
03-29 11:07:29.922  1240  3787 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 11:07:29.922  1240  3787 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-29 11:07:29.923  1240  3787 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 11:07:29.934  1240  3787 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 11:07:29.942  3259  3315 I jxcore-log: # setup,
03-29 11:07:29.942  3259  3315 I jxcore-log: 
,03-29 11:07:29.985  1240  3787 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-29 11:07:29.985  1240  3787 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-29 11:07:29.985  1240  3787 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-29 11:07:29.985  1240  3787 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-29 11:07:29.985  1240  3787 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-29 11:07:29.985  1240  3787 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-29 11:07:29.985  1240  3787 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-29 11:07:29.985  1240  3787 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-29 11:07:29.985  1240  3787 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-29 11:07:29.985  1240  3787 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-29 11:07:29.985  1240  3787 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-29 11:07:29.985  1240  3787 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-29 11:07:29.985  1240  3787 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-29 11:07:30.110  3259  3315 I jxcore-log: # 14. closeAll properly throws when closing a non open server with eatNotRunning set to false
03-29 11:07:30.110  3259  3315 I jxcore-log: 
,03-29 11:07:30.166  1240  3787 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,03-29 11:07:30.166  1240  3787 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 11:07:30.167  1240  3787 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 11:07:30.167  1240  3787 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 11:07:30.178  1240  3787 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,03-29 11:07:30.251  1240  3787 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-29 11:07:30.251  1240  3787 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-29 11:07:30.251  1240  3787 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-29 11:07:30.251  1240  3787 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-29 11:07:30.251  1240  3787 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-29 11:07:30.251  1240  3787 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-29 11:07:30.251  1240  3787 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-29 11:07:30.251  1240  3787 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-29 11:07:30.251  1240  3787 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-29 11:07:30.251  1240  3787 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-29 11:07:30.251  1240  3787 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-29 11:07:30.251  1240  3787 E Uploader: 	,at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-29 11:07:30.251  1240  3787 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
03-29 11:07:30.253  3259  3315 I jxcore-log: ok 47 Got the right error
,03-29 11:07:30.253  3259  3315 I jxcore-log: 
03-29 11:07:30.255  3259  3315 I jxcore-log: # teardown
03-29 11:07:30.255  3259  3315 I jxcore-log: 
,03-29 11:07:30.380  3259  3315 I jxcore-log: # setup
03-29 11:07:30.380  3259  3315 I jxcore-log: 
,03-29 11:07:30.468  1240  3787 W Uploader: No account for auth token provided
,03-29 11:07:30.618  3259  3315 I jxcore-log: # 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true
03-29 11:07:30.618  3259  3315 I jxcore-log: 
,03-29 11:07:30.627  1240  3787 W Uploader: No account for auth token provided
,03-29 11:07:30.756  3259  3315 I jxcore-log: # teardown
03-29 11:07:30.756  3259  3315 I jxcore-log: 
,03-29 11:07:30.899  3259  3315 I jxcore-log: # setup
03-29 11:07:30.899  3259  3315 I jxcore-log: 
,03-29 11:07:31.163  3259  3315 I jxcore-log: # 16. multiplex can send data
03-29 11:07:31.163  3259  3315 I jxcore-log: 
,03-29 11:07:31.464  3259  3315 I jxcore-log: ok 48 String should be length:200
03-29 11:07:31.464  3259  3315 I jxcore-log: 
,03-29 11:07:31.472  3259  3315 I jxcore-log: # teardown
03-29 11:07:31.472  3259  3315 I jxcore-log: 
,03-29 11:07:34.931  3259  3315 I jxcore-log: # setup
03-29 11:07:34.931  3259  3315 I jxcore-log: 
,03-29 11:07:35.268  2152  2220 D HeadsetStateMachine: Disconnected process message: 10, size: 0,
,03-29 11:07:38.460  3259  3315 I jxcore-log: # 17. enqueue and run in order
03-29 11:07:38.460  3259  3315 I jxcore-log: 
,03-29 11:07:39.381  1240  1240 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 11:07:39.478  1240  2583 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
03-29 11:07:39.479  1240  2583 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 11:07:39.479  1240  2583 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 11:07:39.479  1240  2583 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 11:07:39.492  1240  2583 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 11:07:39.537  2747  2747 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,03-29 11:07:39.538  2747  2747 D Finsky  : [1] 5.onFinished: Installation state replication failed.
,03-29 11:07:39.539  2747  2747 D Finsky  : [1] 5.onFinished: Giving up after 6 failures.
,03-29 11:07:40.058  3259  3315 I jxcore-log: ok 49 firstPromise setTimeout
03-29 11:07:40.058  3259  3315 I jxcore-log: 
,03-29 11:07:40.071  3259  3315 I jxcore-log: ok 50 firstPromise result,
03-29 11:07:40.071  3259  3315 I jxcore-log: 
03-29 11:07:40.071  3259  3315 I jxcore-log: ok 51 firstPromise testValue
03-29 11:07:40.071  3259  3315 I jxcore-log: 
,03-29 11:07:40.174  3259  3315 I jxcore-log: ok 52 secondPromise setTimeout,
03-29 11:07:40.174  3259  3315 I jxcore-log: 
,03-29 11:07:40.179  3259  3315 I jxcore-log: ok 53 secondPromise result
03-29 11:07:40.179  3259  3315 I jxcore-log: 
,03-29 11:07:40.180  3259  3315 I jxcore-log: ok 54 secondPromise testValue
03-29 11:07:40.180  3259  3315 I jxcore-log: 
,03-29 11:07:40.183  3259  3315 I jxcore-log: ok 55 thirdPromise in promise
03-29 11:07:40.183  3259  3315 I jxcore-log: 
,03-29 11:07:40.186  3259  3315 I jxcore-log: ok 56 thirdPromise result
03-29 11:07:40.186  3259  3315 I jxcore-log: 
03-29 11:07:40.188  3259  3315 I jxcore-log: ok 57 thirdPromise testValue
03-29 11:07:40.188  3259  3315 I jxcore-log: 
,03-29 11:07:40.202  3259  3315 I jxcore-log: # teardown
03-29 11:07:40.202  3259  3315 I jxcore-log: 
,03-29 11:07:42.474  3259  3315 I jxcore-log: # setup
03-29 11:07:42.474  3259  3315 I jxcore-log: ,
,03-29 11:07:45.239  3259  3315 I jxcore-log: # 18. enqueueAtTop and run backwards,
03-29 11:07:45.239  3259  3315 I jxcore-log: 
,03-29 11:07:48.424  3259  3315 I jxcore-log: ok 58 thirdPromise - first to run
03-29 11:07:48.424  3259  3315 I jxcore-log: 
,03-29 11:07:48.430  3259  3315 I jxcore-log: ok 59 thirdPromise - in resolve,
03-29 11:07:48.430  3259  3315 I jxcore-log: 
,03-29 11:07:48.432  3259  3315 I jxcore-log: ok 60 secondPromise - second to run
03-29 11:07:48.432  3259  3315 I jxcore-log: 
,03-29 11:07:48.435  3259  3315 I jxcore-log: ok 61 secondPromise - in catch
03-29 11:07:48.435  3259  3315 I jxcore-log: 
,03-29 11:07:48.438  3259  3315 I jxcore-log: ok 62 firstPromise - third to run
03-29 11:07:48.438  3259  3315 I jxcore-log: 
,03-29 11:07:48.439  3259  3315 I jxcore-log: ok 63 firstPromise - in then
03-29 11:07:48.439  3259  3315 I jxcore-log: 
,03-29 11:07:48.440  3259  3315 I jxcore-log: ok 64 testing promises
03-29 11:07:48.440  3259  3315 I jxcore-log: 
03-29 11:07:48.442  3259  3315 I jxcore-log: # teardown
03-29 11:07:48.442  3259  3315 I jxcore-log: 
,03-29 11:07:51.364  3259  3315 I jxcore-log: # setup
03-29 11:07:51.364  3259  3315 I jxcore-log: 
,03-29 11:07:52.899  3259  3315 I jxcore-log: # 19. mix enqueue and enqueueAtTop
03-29 11:07:52.899  3259  3315 I jxcore-log: 
,03-29 11:07:54.609  2152  2220 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-29 11:07:57.109  3259  3315 I jxcore-log: ok 65 fourth
03-29 11:07:57.109  3259  3315 I jxcore-log: 
,03-29 11:07:57.112  3259  3315 I jxcore-log: ok 66 fourth
03-29 11:07:57.112  3259  3315 I jxcore-log: 
,03-29 11:07:57.115  3259  3315 I jxcore-log: ok 67 second
03-29 11:07:57.115  3259  3315 I jxcore-log: ,
,03-29 11:07:57.119  3259  3315 I jxcore-log: ok 68 secondPromise - in then
,03-29 11:07:57.119  3259  3315 I jxcore-log: 
,03-29 11:07:57.222  3259  3315 I jxcore-log: ok 69 first
03-29 11:07:57.222  3259  3315 I jxcore-log: 
,03-29 11:07:57.225  3259  3315 I jxcore-log: ok 70 firstPromise - in catch
03-29 11:07:57.225  3259  3315 I jxcore-log: 
,03-29 11:07:57.227  3259  3315 I jxcore-log: ok 71 third
03-29 11:07:57.227  3259  3315 I jxcore-log: 
,03-29 11:07:57.230  3259  3315 I jxcore-log: ok 72 thirdPromise - in then
03-29 11:07:57.230  3259  3315 I jxcore-log: 
,03-29 11:07:57.232  3259  3315 I jxcore-log: ok 73 testingPromises
03-29 11:07:57.232  3259  3315 I jxcore-log: 
,03-29 11:07:57.241  3259  3315 I jxcore-log: # teardown
03-29 11:07:57.241  3259  3315 I jxcore-log: 
,03-29 11:08:00.838  3369  3802 V GoogleAuthProtoRequest: [336] a.<init>: mAccountName set to: thalitester@gmail.com
,03-29 11:08:00.896  1240  1257 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
03-29 11:08:00.896  1240  1257 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 11:08:00.896  1240  1257 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 11:08:00.896  1240  1257 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 11:08:00.901  1240  1257 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,03-29 11:08:00.913  3369  3802 W ExperimentUpdateService: [336] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
03-29 11:08:00.913  3369  3802 W ExperimentUpdateService: [336] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-29 11:08:00.913  3369  3802 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-29 11:08:00.913  3369  3802 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-29 11:08:00.913  3369  3802 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
,03-29 11:08:00.913  3369  3802 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-29 11:08:00.913  3369  3802 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-29 11:08:00.913  3369  3802 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-29 11:08:00.913  3369  3802 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-29 11:08:00.913  3369  3802 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-29 11:08:00.913  3369  3802 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-29 11:08:00.913  3369  3802 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-29 11:08:00.932  3259  3315 I jxcore-log: # setup
03-29 11:08:00.932  3259  3315 I jxcore-log: 
,03-29 11:08:09.895  3259  3315 I jxcore-log: # 20. queues handled independently
03-29 11:08:09.895  3259  3315 I jxcore-log: 
,03-29 11:08:13.325  1258  1472 I Keyboard.Facilitator.LanguageModelFlusher: run()
03-29 11:08:13.325  1258  1472 I Keyboard.Facilitator: flushDynamicLanguageModels()
,03-29 11:08:13.367  1240  1240 I ConfigService: onCreate
,03-29 11:08:17.540  3470  3809 V KeepSync: Connecting to GoogleApiClient
,03-29 11:08:17.656  1240  1256 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
03-29 11:08:17.656  1240  1256 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 11:08:17.656  1240  1256 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 11:08:17.656  1240  1256 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 11:08:17.662  1240  1256 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,03-29 11:08:17.691  1805  3811 E ClientConnectionOperation: Handling authorization failure
03-29 11:08:17.691  1805  3811 E ClientConnectionOperation: com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
03-29 11:08:17.691  1805  3811 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
03-29 11:08:17.691  1805  3811 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
03-29 11:08:17.691  1805  3811 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
03-29 11:08:17.691  1805  3811 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
03-29 11:08:17.691  1805  3811 E ClientConnectionOperation: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-29 11:08:17.691  1805  3811 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 11:08:17.691  1805  3811 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 11:08:17.691  1805  3811 E ClientConnectionOperation: 	at java.lang.Thread.run(Thread.java:818)
03-29 11:08:17.691  1805  3811 E ClientConnectionOperation: Caused by: com.google.android.gms.auth.ad: BadAuthentication
03-29 11:08:17.691  1805  3811 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.b(SourceFile:442)
03-29 11:08:17.691  1805  3811 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:365)
03-29 11:08:17.691  1805  3811 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:310)
03-29 11:08:17.691  1805  3811 E ClientConnectionOperation: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
03-29 11:08:17.691  1805  3811 E ClientConnectionOperation: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
03-29 11:08:17.691  1805  3811 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:30)
03-29 11:08:17.691  1805  3811 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:370)
03-29 11:08:17.691  1805  3811 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:340)
03-29 11:08:17.691  1805  3811 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:319)
03-29 11:08:17.691  1805  3811 E ClientConnectionOperation: 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
03-29 11:08:17.691  1805  3811 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
03-29 11:08:17.691  1805  3811 E ClientConnectionOperation: 	... 7 more
,03-29 11:08:17.694  3470  3809 V KeepSync: GoogleApiClient failed to connect with error code: 4
,03-29 11:08:17.697  3470  3809 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-29 11:08:17.702  3470  3809 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
03-29 11:08:17.702  3470  3809 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-29 11:08:17.709  1240  1257 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-29 11:08:17.709  1240  1257 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 11:08:17.709  1240  1257 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 11:08:17.709  1240  1257 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 11:08:17.718  1240  1257 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 11:08:17.742  3037  3808 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
03-29 11:08:17.742  3037  3808 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-29 11:08:17.742  3037  3808 E HttpOperation: 	at jdm.a(PG:82)
03-29 11:08:17.742  3037  3808 E HttpOperation: 	at jcs.o(PG:406)
03-29 11:08:17.742  3037  3808 E HttpOperation: 	at jcn.a(PG:1379)
03-29 11:08:17.742  3037  3808 E HttpOperation: 	at jcs.i(PG:143)
03-29 11:08:17.742  3037  3808 E HttpOperation: 	at blb.a(PG:3937)
03-29 11:08:17.742  3037  3808 E HttpOperation: 	at czp.a(PG:18188)
03-29 11:08:17.742  3037  3808 E HttpOperation: 	at czp.a(PG:9081)
03-29 11:08:17.742  3037  3808 E HttpOperation: 	at czq.run(PG:1686)
03-29 11:08:17.742  3037  3808 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-29 11:08:17.742  3037  3808 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-29 11:08:17.742  3037  3808 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 11:08:17.742  3037  3808 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 11:08:17.742  3037  3808 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-29 11:08:17.742  3037  3808 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-29 11:08:17.742  3037  3808 E HttpOperation: 	at jdj.a(PG:4091)
03-29 11:08:17.742  3037  3808 E HttpOperation: 	at jdj.a(PG:1125)
03-29 11:08:17.742  3037  3808 E HttpOperation: 	at jdm.a(PG:77)
03-29 11:08:17.742  3037  3808 E HttpOperation: 	... 12 more
03-29 11:08:17.742  3037  3808 E HttpOperation: Caused by: faj: BadAuthentication
03-29 11:08:17.742  3037  3808 E HttpOperation: 	at fal.a(PG:38)
03-29 11:08:17.742  3037  3808 E HttpOperation: 	at jdj.a(PG:4089)
03-29 11:08:17.742  3037  3808 E HttpOperation: 	... 14 more
,03-29 11:08:17.836   823  1388 I art     : Explicit concurrent mark sweep GC freed 26888(1172KB) AllocSpace objects, 2(220KB) LOS objects, 31% free, 34MB/50MB, paused 2.678ms total 87.125ms
,03-29 11:08:17.868  1240  1256 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-29 11:08:17.868  1240  1256 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 11:08:17.868  1240  1256 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 11:08:17.868  1240  1256 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 11:08:17.871  1240  1256 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 11:08:17.883  1240  2583 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
03-29 11:08:17.884  1240  2583 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 11:08:17.884  1240  2583 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 11:08:17.884  1240  2583 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 11:08:17.885  3037  3808 E HttpOperation: [getmobileexperiments] Unexpected exception
03-29 11:08:17.885  3037  3808 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-29 11:08:17.885  3037  3808 E HttpOperation: 	at jdm.a(PG:82)
03-29 11:08:17.885  3037  3808 E HttpOperation: 	at jcs.o(PG:406)
03-29 11:08:17.885  3037  3808 E HttpOperation: 	at jcn.a(PG:1379)
03-29 11:08:17.885  3037  3808 E HttpOperation: 	at jcs.i(PG:143)
03-29 11:08:17.885  3037  3808 E HttpOperation: 	at hec.a(PG:42)
03-29 11:08:17.885  3037  3808 E HttpOperation: 	at hee.a(PG:102)
03-29 11:08:17.885  3037  3808 E HttpOperation: 	at czr.a(PG:65)
03-29 11:08:17.885  3037  3808 E HttpOperation: 	at kka.a(PG:108)
03-29 11:08:17.885  3037  3808 E HttpOperation: 	at czp.a(PG:19176)
03-29 11:08:17.885  3037  3808 E HttpOperation: 	at czp.a(PG:9081)
03-29 11:08:17.885  3037  3808 E HttpOperation: 	at czq.run(PG:1686)
03-29 11:08:17.885  3037  3808 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-29 11:08:17.885  3037  3808 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-29 11:08:17.885  3037  3808 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 11:08:17.885  3037  3808 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 11:08:17.885  3037  3808 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-29 11:08:17.885  3037  3808 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-29 11:08:17.885  3037  3808 E HttpOperation: 	at jdj.a(PG:4091)
03-29 11:08:17.885  3037  3808 E HttpOperation: 	at jdj.a(PG:1125)
03-29 11:08:17.885  3037  3808 E HttpOperation: 	at jdm.a(PG:77)
03-29 11:08:17.885  3037  3808 E HttpOperation: 	... 15 more
03-29 11:08:17.885  3037  3808 E HttpOperation: Caused by: faj: BadAuthentication
03-29 11:08:17.885  3037  3808 E HttpOperation: 	at fal.a(PG:38)
03-29 11:08:17.885  3037  3808 E HttpOperation: 	at jdj.a(PG:4089)
03-29 11:08:17.885  3037  3808 E HttpOperation: 	... 17 more
03-29 11:08:17.886  3037  3808 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
03-29 11:08:17.886  3037  3808 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
03-29 11:08:17.886  3037  3808 E ExperimentLoader: 	at jdm.a(PG:82)
03-29 11:08:17.886  3037  3808 E ExperimentLoader: 	at jcs.o(PG:406)
03-29 11:08:17.886  3037  3808 E ExperimentLoader: 	at jcn.a(PG:1379)
03-29 11:08:17.886  3037  3808 E ExperimentLoader: 	at jcs.i(PG:143)
03-29 11:08:17.886  3037  3808 E ExperimentLoader: 	at hec.a(PG:42)
03-29 11:08:17.886  3037  3808 E ExperimentLoader: 	at hee.a(PG:102)
03-29 11:08:17.886  3037  3808 E ExperimentLoader: 	at czr.a(PG:65)
03-29 11:08:17.886  3037  3808 E ExperimentLoader: 	at kka.a(PG:108)
03-29 11:08:17.886  3037  3808 E ExperimentLoader: 	at czp.a(PG:19176)
03-29 11:08:17.886  3037  3808 E ExperimentLoader: 	at czp.a(PG:9081)
03-29 11:08:17.886  3037  3808 E ExperimentLoader: 	at czq.run(PG:1686)
03-29 11:08:17.886  3037  3808 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-29 11:08:17.886  3037  3808 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-29 11:08:17.886  3037  3808 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 11:08:17.886  3037  3808 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 11:08:17.886  3037  3808 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
03-29 11:08:17.886  3037  3808 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-29 11:08:17.886  3037  3808 E ExperimentLoader: 	at jdj.a(PG:4091)
03-29 11:08:17.886  3037  3808 E ExperimentLoader: 	at jdj.a(PG:1,125)
03-29 11:08:17.886  3037  3808 E ExperimentLoader: 	at jdm.a(PG:77)
03-29 11:08:17.886  3037  3808 E ExperimentLoader: 	... 15 more
03-29 11:08:17.886  3037  3808 E ExperimentLoader: Caused by: faj: BadAuthentication
03-29 11:08:17.886  3037  3808 E ExperimentLoader: 	at fal.a(PG:38)
03-29 11:08:17.886  3037  3808 E ExperimentLoader: 	at jdj.a(PG:4089)
03-29 11:08:17.886  3037  3808 E ExperimentLoader: 	... 17 more
03-29 11:08:17.889  1240  2583 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 11:08:17.927  3470  3809 E KeepSync: IOException
03-29 11:08:17.927  3470  3809 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
03-29 11:08:17.927  3470  3809 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
03-29 11:08:17.927  3470  3809 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
03-29 11:08:17.927  3470  3809 E KeepSync: 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
03-29 11:08:17.927  3470  3809 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
03-29 11:08:17.927  3470  3809 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
03-29 11:08:17.927  3470  3809 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
03-29 11:08:17.927  3470  3809 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
03-29 11:08:17.927  3470  3809 E KeepSync: 	at com.google.android.keep.util.m.a(SourceFile:207)
03-29 11:08:17.927  3470  3809 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
03-29 11:08:17.927  3470  3809 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
03-29 11:08:17.927  3470  3809 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
03-29 11:08:17.927  3470  3809 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
03-29 11:08:17.927  3470  3809 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
03-29 11:08:17.927  3470  3809 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
03-29 11:08:17.927  3470  3809 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
03-29 11:08:17.927  3470  3809 E KeepSync: 	... 10 more
03-29 11:08:17.927  3470  3809 W KeepSync: Sync result 2
,03-29 11:08:17.936   823   856 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 202035, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-29 11:08:17.984  3496  3814 I BooksSync: Starting books sync for 61035162, extras: ade
,03-29 11:08:17.991   823   856 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 200694, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,03-29 11:08:18.001  3496  3815 I BooksConfig: GmsCore Version = 7.8.99 (2134222-430)
,03-29 11:08:18.030  1240  2551 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,03-29 11:08:18.031  1240  2551 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 11:08:18.031  1240  2551 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-29 11:08:18.031  1240  2551 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 11:08:18.037  1240  2551 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 11:08:18.123  1240  1256 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-29 11:08:18.123  1240  1256 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-29 11:08:18.124  1240  1256 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 11:08:18.124  1240  1256 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 11:08:18.129  1240  1256 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 11:08:18.147  3496  3815 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,03-29 11:08:18.149  3496  3814 E BooksSync: Soft error
03-29 11:08:18.149  3496  3814 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-29 11:08:18.149  3496  3814 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-29 11:08:18.150  3496  3814 E BooksSync: Sync error
03-29 11:08:18.150  3496  3814 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-29 11:08:18.150  3496  3814 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-29 11:08:18.150  3496  3814 I BooksSync: Finished books sync
,03-29 11:08:18.166   823   856 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 204015, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-29 11:08:18.447  1240  1240 I ConfigService: onDestroy,
,03-29 11:08:22.451  3259  3315 I jxcore-log: ok 74 all short operations completed before the long resolves
03-29 11:08:22.451  3259  3315 I jxcore-log: 
,03-29 11:08:22.456  3259  3315 I jxcore-log: # teardown
03-29 11:08:22.456  3259  3315 I jxcore-log: 
,03-29 11:08:32.953  3259  3315 I jxcore-log: # setup
03-29 11:08:32.953  3259  3315 I jxcore-log: 
,03-29 11:08:54.773  2152  2220 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-29 11:09:00.977  3369  3823 V GoogleAuthProtoRequest: [337] a.<init>: mAccountName set to: thalitester@gmail.com
,03-29 11:09:01.035  1240  2551 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
03-29 11:09:01.035  1240  2551 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 11:09:01.035  1240  2551 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 11:09:01.035  1240  2551 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 11:09:01.041  1240  2551 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 11:09:01.056  3369  3823 W ExperimentUpdateService: [337] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
03-29 11:09:01.056  3369  3823 W ExperimentUpdateService: [337] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-29 11:09:01.056  3369  3823 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-29 11:09:01.056  3369  3823 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-29 11:09:01.056  3369  3823 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-29 11:09:01.056  3369  3823 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-29 11:09:01.056  3369  3823 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-29 11:09:01.056  3369  3823 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-29 11:09:01.056  3369  3823 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-29 11:09:01.056  3369  3823 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-29 11:09:01.056  3369  3823 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-29 11:09:01.056  3369  3823 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-29 11:09:35.269  2152  2220 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-29 11:09:39.809  3259  3315 I jxcore-log: Disconnected from the test server
03-29 11:09:39.809  3259  3315 I jxcore-log: 
,03-29 11:09:40.792  3259  3315 I jxcore-log: Reconnected to the test server,
03-29 11:09:40.792  3259  3315 I jxcore-log: 
,03-29 11:09:47.736  3470  3833 V KeepSync: Connecting to GoogleApiClient
,03-29 11:09:47.815  1240  1257 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
03-29 11:09:47.816  1240  1257 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 11:09:47.816  1240  1257 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-29 11:09:47.816  1240  1257 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 11:09:47.819  1240  1257 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 11:09:47.819  1240  1750 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-29 11:09:47.819  1240  1750 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 11:09:47.819  1240  1750 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-29 11:09:47.820  1240  1750 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 11:09:47.824  1240  1750 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 11:09:47.835  1805  3836 E ClientConnectionOperation: Handling authorization failure
03-29 11:09:47.835  1805  3836 E ClientConnectionOperation: com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
03-29 11:09:47.835  1805  3836 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
03-29 11:09:47.835  1805  3836 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
03-29 11:09:47.835  1805  3836 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
03-29 11:09:47.835  1805  3836 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
03-29 11:09:47.835  1805  3836 E ClientConnectionOperation: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-29 11:09:47.835  1805  3836 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 11:09:47.835  1805  3836 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 11:09:47.835  1805  3836 E ClientConnectionOperation: 	at java.lang.Thread.run(Thread.java:818)
03-29 11:09:47.835  1805  3836 E ClientConnectionOperation: Caused by: com.google.android.gms.auth.ad: BadAuthentication
03-29 11:09:47.835  1805  3836 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.b(SourceFile:442)
03-29 11:09:47.835  1805  3836 E ClientConnectionOperation: ,	at com.google.android.gms.auth.p.a(SourceFile:365)
03-29 11:09:47.835  1805  3836 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:310)
03-29 11:09:47.835  1805  3836 E ClientConnectionOperation: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
03-29 11:09:47.835  1805  3836 E ClientConnectionOperation: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
03-29 11:09:47.835  1805  3836 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:30)
03-29 11:09:47.835  1805  3836 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:370)
03-29 11:09:47.835  1805  3836 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:340)
03-29 11:09:47.835  1805  3836 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:319)
03-29 11:09:47.835  1805  3836 E ClientConnectionOperation: 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
03-29 11:09:47.835  1805  3836 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
03-29 11:09:47.835  1805  3836 E ClientConnectionOperation: 	... 7 more
,03-29 11:09:47.838  3037  3834 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
03-29 11:09:47.838  3037  3834 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-29 11:09:47.838  3037  3834 E HttpOperation: 	at jdm.a(PG:82)
03-29 11:09:47.838  3037  3834 E HttpOperation: 	at jcs.o(PG:406)
03-29 11:09:47.838  3037  3834 E HttpOperation: 	at jcn.a(PG:1379)
03-29 11:09:47.838  3037  3834 E HttpOperation: 	at jcs.i(PG:143)
03-29 11:09:47.838  3037  3834 E HttpOperation: 	at blb.a(PG:3937)
03-29 11:09:47.838  3037  3834 E HttpOperation: 	at czp.a(PG:18188)
03-29 11:09:47.838  3037  3834 E HttpOperation: 	at czp.a(PG:9087)
03-29 11:09:47.838  3037  3834 E HttpOperation: 	at czq.run(PG:1686)
03-29 11:09:47.838  3037  3834 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-29 11:09:47.838  3037  3834 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-29 11:09:47.838  3037  3834 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 11:09:47.838  3037  3834 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 11:09:47.838  3037  3834 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-29 11:09:47.838  3037  3834 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-29 11:09:47.838  3037  3834 E HttpOperation: 	at jdj.a(PG:4091)
03-29 11:09:47.838  3037  3834 E HttpOperation: 	at jdj.a(PG:1125)
03-29 11:09:47.838  3037  3834 E HttpOperation: 	at jdm.a(PG:77)
03-29 11:09:47.838  3037  3834 E HttpOperation: 	... 12 more
03-29 11:09:47.838  3037  3834 E HttpOperation: Caused by: faj: BadAuthentication
03-29 11:09:47.838  3037  3834 E HttpOperation: 	at fal.a(PG:38)
03-29 11:09:47.838  3037  3834 E HttpOperation: 	at jdj.a(PG:4089)
03-29 11:09:47.838  3037  3834 E HttpOperation: 	... 14 more
,03-29 11:09:47.840  3470  3833 V KeepSync: GoogleApiClient failed to connect with error code: 4
,03-29 11:09:47.844  3470  3833 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-29 11:09:47.855  3470  3833 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-29 11:09:47.855  3470  3833 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-29 11:09:47.945  1240  1256 I art     : Explicit concurrent mark sweep GC freed 56056(3MB) AllocSpace objects, 10(1033KB) LOS objects, 36% free, 27MB/43MB, paused 1.251ms total 49.961ms
,03-29 11:09:47.963  1240  1749 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
03-29 11:09:47.964  1240  1749 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 11:09:47.964  1240  1749 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 11:09:47.964  1240  1749 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 11:09:47.967  1240  1749 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 11:09:47.997  3470  3833 E KeepSync: IOException
03-29 11:09:47.997  3470  3833 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
03-29 11:09:47.997  3470  3833 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
03-29 11:09:47.997  3470  3833 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
03-29 11:09:47.997  3470  3833 E KeepSync: 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
03-29 11:09:47.997  3470  3833 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
03-29 11:09:47.997  3470  3833 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
03-29 11:09:47.997  3470  3833 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
03-29 11:09:47.997  3470  3833 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
03-29 11:09:47.997  3470  3833 E KeepSync: 	at com.google.android.keep.util.m.a(SourceFile:207)
03-29 11:09:47.997  3470  3833 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
03-29 11:09:47.997  3470  3833 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
03-29 11:09:47.997  3470  3833 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
03-29 11:09:47.997  3470  3833 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
03-29 11:09:47.997  3470  3833 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
03-29 11:09:47.997  3470  3833 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
03-29 11:09:47.997  3470  3833 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
03-29 11:09:47.997  3470  3833 E KeepSync: 	... 10 more
03-29 11:09:47.997  3470  3833 W KeepSync: Sync result 2
,03-29 11:09:48.004   823   856 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 292286, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-29 11:09:48.017  1240  1256 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-29 11:09:48.017  1240  1256 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 11:09:48.017  1240  1256 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 11:09:48.017  1240  1256 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 11:09:48.020  1240  1256 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 11:09:48.033  3037  3840 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
03-29 11:09:48.033  3037  3840 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-29 11:09:48.033  3037  3840 E HttpOperation: 	at jdm.a(PG:82)
03-29 11:09:48.033  3037  3840 E HttpOperation: 	at jcs.o(PG:406)
03-29 11:09:48.033  3037  3840 E HttpOperation: 	at jcn.a(PG:1379)
03-29 11:09:48.033  3037  3840 E HttpOperation: 	at jcs.i(PG:143)
03-29 11:09:48.033  3037  3840 E HttpOperation: 	at blb.a(PG:3937)
03-29 11:09:48.033  3037  3840 E HttpOperation: 	at czp.a(PG:18188)
03-29 11:09:48.033  3037  3840 E HttpOperation: 	at czp.a(PG:9081)
03-29 11:09:48.033  3037  3840 E HttpOperation: 	at czq.run(PG:1686)
03-29 11:09:48.033  3037  3840 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-29 11:09:48.033  3037  3840 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-29 11:09:48.033  3037  3840 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 11:09:48.033  3037  3840 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 11:09:48.033  3037  3840 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-29 11:09:48.033  3037  3840 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-29 11:09:48.033  3037  3840 E HttpOperation: 	at jdj.a(PG:4091)
03-29 11:09:48.033  3037  3840 E HttpOperation: 	at jdj.a(PG:1125)
03-29 11:09:48.033  3037  3840 E HttpOperation: 	at jdm.a(PG:77)
03-29 11:09:48.033  3037  3840 E HttpOperation: 	... 12 more
03-29 11:09:48.033  3037  3840 E HttpOperation: Caused by: faj: BadAuthentication
03-29 11:09:48.033  3037  3840 E HttpOperation: 	at fal.a(PG:38)
03-29 11:09:48.033  3037  3840 E HttpOperation: 	at jdj.a(PG:4089)
03-29 11:09:48.033  3037  3840 E HttpOperation: 	... 14 more
,03-29 11:09:48.038  3496  3841 I BooksSync: Starting books sync for 61035162, extras: ade
,03-29 11:09:48.053  3496  3842 I BooksConfig: GmsCore Version = 7.8.99 (2134222-430)
,03-29 11:09:48.059  1240  2583 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-29 11:09:48.059  1240  2583 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 11:09:48.059  1240  2583 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 11:09:48.060  1240  2583 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 11:09:48.062  1240  2583 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 11:09:48.074  3037  3840 E HttpOperation: [getmobileexperiments] Unexpected exception
03-29 11:09:48.074  3037  3840 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-29 11:09:48.074  3037  3840 E HttpOperation: 	at jdm.a(PG:82)
03-29 11:09:48.074  3037  3840 E HttpOperation: 	at jcs.o(PG:406)
03-29 11:09:48.074  3037  3840 E HttpOperation: 	at jcn.a(PG:1379)
03-29 11:09:48.074  3037  3840 E HttpOperation: 	at jcs.i(PG:143)
03-29 11:09:48.074  3037  3840 E HttpOperation: 	at hec.a(PG:42)
03-29 11:09:48.074  3037  3840 E HttpOperation: 	at hee.a(PG:102)
03-29 11:09:48.074  3037  3840 E HttpOperation: 	at czr.a(PG:65)
03-29 11:09:48.074  3037  3840 E HttpOperation: 	at kka.a(PG:108)
03-29 11:09:48.074  3037  3840 E HttpOperation: 	at czp.a(PG:19176)
03-29 11:09:48.074  3037  3840 E HttpOperation: 	at czp.a(PG:9081)
03-29 11:09:48.074  3037  3840 E HttpOperation: 	at czq.run(PG:1686)
03-29 11:09:48.074  3037  3840 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-29 11:09:48.074  3037  3840 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-29 11:09:48.074  3037  3840 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 11:09:48.074  3037  3840 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 11:09:48.074  3037  3840 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-29 11:09:48.074  3037  3840 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-29 11:09:48.074  3037  3840 E HttpOperation: 	at jdj.a(PG:4091)
03-29 11:09:48.074  3037  3840 E HttpOperation: 	at jdj.a(PG:1125)
03-29 11:09:48.074  3037  3840 E HttpOperation: 	at jdm.a(PG:77)
03-29 11:09:48.074  3037  3840 E HttpOperation: 	... 15 more
03-29 11:09:48.074  3037  3840 E HttpOperation: Caused by: faj: BadAuthentication
03-29 11:09:48.074  3037  3840 E HttpOperation: 	at fal.a(PG:38)
03-29 11:09:48.074  3037  3840 E HttpOperation: 	at jdj.a(PG:4089)
03-29 11:09:48.074  3037  3840 E HttpOperation: 	... 17 more
,03-29 11:09:48.074  3037  3840 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
03-29 11:09:48.074  3037  3840 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
03-29 11:09:48.074  3037  3840 E ExperimentLoader: 	at jdm.a(PG:82)
03-29 11:09:48.074  3037  3840 E ExperimentLoader: 	at jcs.o(PG:406)
03-29 11:09:48.074  3037  3840 E ExperimentLoader: 	at jcn.a(PG:1379)
03-29 11:09:48.074  3037  3840 E ExperimentLoader: 	at jcs.i(PG:143)
03-29 11:09:48.074  3037  3840 E ExperimentLoader: 	at hec.a(PG:42)
,03-29 11:09:48.074  3037  3840 E ExperimentLoader: 	at hee.a(PG:102)
03-29 11:09:48.074  3037  3840 E ExperimentLoader: 	at czr.a(PG:65)
03-29 11:09:48.074  3037  3840 E ExperimentLoader: 	at kka.a(PG:108)
03-29 11:09:48.074  3037  3840 E ExperimentLoader: 	at czp.a(PG:19176)
03-29 11:09:48.074  3037  3840 E ExperimentLoader: 	at czp.a(PG:9081)
03-29 11:09:48.074  3037  3840 E ExperimentLoader: 	at czq.run(PG:1686)
03-29 11:09:48.074  3037  3840 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-29 11:09:48.074  3037  3840 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-29 11:09:48.074  3037  3840 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 11:09:48.074  3037  3840 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 11:09:48.074  3037  3840 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
03-29 11:09:48.074  3037  3840 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-29 11:09:48.074  3037  3840 E ExperimentLoader: 	at jdj.a(PG:4091)
03-29 11:09:48.074  3037  3840 E ExperimentLoader: 	at jdj.a(PG:1125)
03-29 11:09:48.074  3037  3840 E ExperimentLoader: 	,at jdm.a(PG:77)
03-29 11:09:48.074  3037  3840 E ExperimentLoader: 	... 15 more
03-29 11:09:48.074  3037  3840 E ExperimentLoader: Caused by: faj: BadAuthentication
03-29 11:09:48.074  3037  3840 E ExperimentLoader: 	at fal.a(PG:38)
03-29 11:09:48.074  3037  3840 E ExperimentLoader: 	at jdj.a(PG:4089)
03-29 11:09:48.074  3037  3840 E ExperimentLoader: 	... 17 more
,03-29 11:09:48.083  1240  1256 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-29 11:09:48.083  1240  1256 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 11:09:48.083  1240  1256 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 11:09:48.083  1240  1256 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 11:09:48.088  1240  1256 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 11:09:48.140  1240  2583 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,03-29 11:09:48.140  1240  2583 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 11:09:48.140  1240  2583 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 11:09:48.140  1240  2583 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 11:09:48.144  1240  2583 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 11:09:48.156  3496  3842 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,03-29 11:09:48.158  3496  3841 E BooksSync: Soft error
03-29 11:09:48.158  3496  3841 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-29 11:09:48.158  3496  3841 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,03-29 11:09:48.159  3496  3841 E BooksSync: Sync error
03-29 11:09:48.159  3496  3841 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-29 11:09:48.159  3496  3841 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-29 11:09:48.159  3496  3841 I BooksSync: Finished books sync
,03-29 11:09:48.164   823   856 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 295195, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1],
,03-29 11:09:48.173   823   856 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 230295, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,03-29 11:09:54.928  2152  2220 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-29 11:10:01.071   823  1388 D WifiService: acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@32537d6c}
,03-29 11:10:01.078   823  1012 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=1.00 rxSuccessRate=0.50 targetRoamBSSID=any RSSI=-127
,03-29 11:10:02.686   823  1356 I art     : Explicit concurrent mark sweep GC freed 42244(1883KB) AllocSpace objects, 15(711KB) LOS objects, 31% free, 34MB/50MB, paused 1.614ms total 84.699ms
,03-29 11:10:02.722   823   842 D WifiService: releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@32537d6c}
,03-29 11:10:02.779   823  1291 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::injectLocation(GpsExtLocation):857]: error! inject position failed
,03-29 11:10:02.854   873   873 I kickstart: STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000,
03-29 11:10:02.854   873   873 I kickstart: STATUS: Wrote to /sys/power/wake_lock
,03-29 11:10:02.895   873   873 E kickstart: ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1,
03-29 11:10:02.896   873   873 I kickstart: STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1' for writing
,03-29 11:10:03.870   873   873 I kickstart: STATUS: Received file 'm9kefs1'
,03-29 11:10:03.870   873   873 I kickstart: STATUS: 950272 bytes transferred in 0.973768 seconds
03-29 11:10:03.870   873   873 I kickstart: STATUS: Successfully downloaded files from target 
03-29 11:10:03.870   873   873 I kickstart: STATUS: Wrote to /sys/power/wake_unlock
,03-29 11:10:03.873   873   873 I kickstart: STATUS: Sahara protocol completed
,03-29 11:10:18.688  1240  1240 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 11:10:18.764  1240  2583 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
03-29 11:10:18.764  1240  2583 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 11:10:18.765  1240  2583 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 11:10:18.765  1240  2583 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 11:10:18.776  1240  2583 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 11:10:18.853  1240  2583 W GLSActivity: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-29 11:10:18.853  1240  2583 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-29 11:10:18.853  1240  2583 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-29 11:10:18.853  1240  2583 W GLSActivity: 	,at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
03-29 11:10:18.853  1240  2583 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
03-29 11:10:18.853  1240  2583 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
03-29 11:10:18.853  1240  2583 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:446),
03-29 11:10:18.857  2747  2787 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
03-29 11:10:18.857  2747  2787 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
03-29 11:10:18.857  2747  2787 E PlayEventLogger: ,	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
03-29 11:10:18.857  2747  2787 E PlayEventLogger: 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
03-29 11:10:18.857  2747  2787 E PlayEventLogger: 	,at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
03-29 11:10:18.857  2747  2787 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
03-29 11:10:18.857  2747  2787 E PlayEventLogger: 	,at android.os.Binder.execTransact(Binder.java:446)
,03-29 11:10:18.943  2747  2787 W System  : Ignoring header User-Agent because its value was null.
,03-29 11:10:35.265  2152  2220 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-29 11:10:47.951  1240  1749 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-29 11:10:47.951  1240  1749 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 11:10:47.951  1240  1749 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 11:10:47.951  1240  1749 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 11:10:47.957  1240  1749 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 11:10:47.987  3037  3858 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
03-29 11:10:47.987  3037  3858 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-29 11:10:47.987  3037  3858 E HttpOperation: 	at jdm.a(PG:82)
03-29 11:10:47.987  3037  3858 E HttpOperation: 	at jcs.o(PG:406)
03-29 11:10:47.987  3037  3858 E HttpOperation: 	at jcn.a(PG:1379)
03-29 11:10:47.987  3037  3858 E HttpOperation: 	at jcs.i(PG:143)
03-29 11:10:47.987  3037  3858 E HttpOperation: 	at blb.a(PG:3937)
03-29 11:10:47.987  3037  3858 E HttpOperation: 	at czp.a(PG:18188)
03-29 11:10:47.987  3037  3858 E HttpOperation: 	at czp.a(PG:9081)
03-29 11:10:47.987  3037  3858 E HttpOperation: 	at czq.run(PG:1686)
03-29 11:10:47.987  3037  3858 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-29 11:10:47.987  3037  3858 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-29 11:10:47.987  3037  3858 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 11:10:47.987  3037  3858 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 11:10:47.987  3037  3858 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-29 11:10:47.987  3037  3858 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-29 11:10:47.987  3037  3858 E HttpOperation: 	at jdj.a(PG:4091)
03-29 11:10:47.987  3037  3858 E HttpOperation: 	at jdj.a(PG:1125)
03-29 11:10:47.987  3037  3858 E HttpOperation: 	at jdm.a(PG:77)
03-29 11:10:47.987  3037  3858 E HttpOperation: 	... 12 more
03-29 11:10:47.987  3037  3858 E HttpOperation: Caused by: faj: BadAuthentication
03-29 11:10:47.987  3037  3858 E HttpOperation: 	at fal.a(PG:38)
03-29 11:10:47.987  3037  3858 E HttpOperation: 	at jdj.a(PG:4089)
03-29 11:10:47.987  3037  3858 E HttpOperation: 	... 14 more
,03-29 11:10:48.052  1240  1750 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-29 11:10:48.052  1240  1750 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 11:10:48.052  1240  1750 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 11:10:48.052  1240  1750 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 11:10:48.056  1240  1750 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 11:10:48.076  3037  3858 E HttpOperation: [getmobileexperiments] Unexpected exception
03-29 11:10:48.076  3037  3858 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-29 11:10:48.076  3037  3858 E HttpOperation: ,	at jdm.a(PG:82)
03-29 11:10:48.076  3037  3858 E HttpOperation: 	at jcs.o(PG:406)
03-29 11:10:48.076  3037  3858 E HttpOperation: 	at jcn.a(PG:1379)
03-29 11:10:48.076  3037  3858 E HttpOperation: 	at jcs.i(PG:143)
03-29 11:10:48.076  3037  3858 E HttpOperation: 	at hec.a(PG:42)
03-29 11:10:48.076  3037  3858 E HttpOperation: 	at hee.a(PG:102)
03-29 11:10:48.076  3037  3858 E HttpOperation: 	at czr.a(PG:65)
03-29 11:10:48.076  3037  3858 E HttpOperation: 	at kka.a(PG:108)
03-29 11:10:48.076  3037  3858 E HttpOperation: 	at czp.a(PG:19176)
03-29 11:10:48.076  3037  3858 E HttpOperation: 	at czp.a(PG:9081)
03-29 11:10:48.076  3037  3858 E HttpOperation: 	at czq.run(PG:1686)
03-29 11:10:48.076  3037  3858 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-29 11:10:48.076  3037  3858 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-29 11:10:48.076  3037  3858 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 11:10:48.076  3037  3858 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 11:10:48.076  3037  3858 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-29 11:10:48.076  3037  3858 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-29 11:10:48.076  3037  3858 E HttpOperation: 	at jdj.a(PG:4091)
03-29 11:10:48.076  3037  3858 E HttpOperation: 	at jdj.a(PG:1125)
03-29 11:10:48.076  3037  3858 E HttpOperation: 	at jdm.a(PG:77)
03-29 11:10:48.076  3037  3858 E HttpOperation: 	... 15 more
03-29 11:10:48.076  3037  3858 E HttpOperation: Caused by: faj: BadAuthentication,
03-29 11:10:48.076  3037  3858 E HttpOperation: 	at fal.a(PG:38)
03-29 11:10:48.076  3037  3858 E HttpOperation: 	at jdj.a(PG:4089)
03-29 11:10:48.076  3037  3858 E HttpOperation: 	... 17 more
03-29 11:10:48.078  3037  3858 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
03-29 11:10:48.078  3037  3858 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
03-29 11:10:48.078  3037  3858 E ExperimentLoader: 	at jdm.a(PG:82)
03-29 11:10:48.078  3037  3858 E ExperimentLoader: 	at jcs.o(PG:406)
03-29 11:10:48.078  3037  3858 E ExperimentLoader: 	at jcn.a(PG:1379)
03-29 11:10:48.078  3037  3858 E ExperimentLoader: 	at jcs.i(PG:143)
03-29 11:10:48.078  3037  3858 E ExperimentLoader: 	at hec.a(PG:42)
03-29 11:10:48.078  3037  3858 E ExperimentLoader: 	at hee.a(PG:102)
03-29 11:10:48.078  3037  3858 E ExperimentLoader: 	at czr.a(PG:65)
03-29 11:10:48.078  3037  3858 E ExperimentLoader: 	,at kka.a(PG:108)
03-29 11:10:48.078  3037  3858 E ExperimentLoader: 	at czp.a(PG:19176)
03-29 11:10:48.078  3037  3858 E ExperimentLoader: 	at czp.a(PG:9081)
03-29 11:10:48.078  3037  3858 E ExperimentLoader: 	at czq.run(PG:1686)
03-29 11:10:48.078  3037  3858 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-29 11:10:48.078  3037  3858 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-29 11:10:48.078  3037  3858 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 11:10:48.078  3037  3858 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 11:10:48.078  3037  3858 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
03-29 11:10:48.078  3037  3858 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-29 11:10:48.078  3037  3858 E ExperimentLoader: 	at jdj.a(PG:4091)
03-29 11:10:48.078  3037  3858 E ExperimentLoader: 	at jdj.a(PG:1125)
03-29 11:10:48.078  3037  3858 E ExperimentLoader: 	at jdm.a(PG:77)
03-29 11:10:48.078  3037  3858 E ExperimentLoader: 	... 15 more
03-29 11:10:48.078  3037  3858 E ExperimentLoader: Caused by: faj: BadAuthentication
03-29 11:10:48.078  3037  3858 E ExperimentLoader: 	at fal.a(PG:38)
03-29 11:10:48.078  3037  3858 E ExperimentLoader: 	at jdj.a(PG:4089)
03-29 11:10:48.078  3037  3858 E ExperimentLoader: 	... 17 more
,03-29 11:10:48.171   823   856 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 352156, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,03-29 11:10:55.088  2152  2220 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-29 11:11:01.144  3369  3861 V GoogleAuthProtoRequest: [338] a.<init>: mAccountName set to: thalitester@gmail.com
,03-29 11:11:01.262  1240  2551 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
03-29 11:11:01.263  1240  2551 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-29 11:11:01.263  1240  2551 I GLSUser : [GLSUser] Extracting token using key: Auth,
03-29 11:11:01.263  1240  2551 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,03-29 11:11:01.280  1240  2551 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 11:11:01.302  3369  3861 W ExperimentUpdateService: [338] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
03-29 11:11:01.303  3369  3861 W ExperimentUpdateService: [338] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-29 11:11:01.303  3369  3861 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-29 11:11:01.303  3369  3861 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-29 11:11:01.303  3369  3861 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-29 11:11:01.303  3369  3861 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-29 11:11:01.303  3369  3861 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-29 11:11:01.303  3369  3861 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-29 11:11:01.303  3369  3861 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-29 11:11:01.303  3369  3861 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-29 11:11:01.303  3369  3861 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-29 11:11:01.303  3369  3861 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-29 11:11:35.266  2152  2220 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-29 11:11:51.803  1240  1749 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,03-29 11:11:51.804  1240  1749 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 11:11:51.804  1240  1749 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 11:11:51.804  1240  1749 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 11:11:51.815  1240  1749 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 11:11:51.839  3037  3873 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
03-29 11:11:51.839  3037  3873 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-29 11:11:51.839  3037  3873 E HttpOperation: 	at jdm.a(PG:82)
03-29 11:11:51.839  3037  3873 E HttpOperation: 	at jcs.o(PG:406)
03-29 11:11:51.839  3037  3873 E HttpOperation: 	at jcn.a(PG:1379)
03-29 11:11:51.839  3037  3873 E HttpOperation: 	at jcs.i(PG:143)
03-29 11:11:51.839  3037  3873 E HttpOperation: 	at blb.a(PG:3937)
03-29 11:11:51.839  3037  3873 E HttpOperation: 	at czp.a(PG:18188)
03-29 11:11:51.839  3037  3873 E HttpOperation: 	at czp.a(PG:9081)
03-29 11:11:51.839  3037  3873 E HttpOperation: 	at czq.run(PG:1686)
03-29 11:11:51.839  3037  3873 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-29 11:11:51.839  3037  3873 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-29 11:11:51.839  3037  3873 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 11:11:51.839  3037  3873 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 11:11:51.839  3037  3873 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-29 11:11:51.839  3037  3873 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-29 11:11:51.839  3037  3873 E HttpOperation: 	at jdj.a(PG:4091)
03-29 11:11:51.839  3037  3873 E HttpOperation: 	at jdj.a(PG:1125)
03-29 11:11:51.839  3037  3873 E HttpOperation: 	at jdm.a(PG:77)
03-29 11:11:51.839  3037  3873 E HttpOperation: 	... 12 more
03-29 11:11:51.839  3037  3873 E HttpOperation: Caused by: faj: BadAuthentication
03-29 11:11:51.839  3037  3873 E HttpOperation: 	at fal.a(PG:38)
03-29 11:11:51.839  3037  3873 E HttpOperation: 	at jdj.a(PG:4089)
03-29 11:11:51.839  3037  3873 E HttpOperation: 	... 14 more
,03-29 11:11:51.914  1240  2583 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-29 11:11:51.915  1240  2583 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-29 11:11:51.915  1240  2583 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 11:11:51.915  1240  2583 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 11:11:51.922  1240  2583 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 11:11:51.943  3037  3873 E HttpOperation: [getmobileexperiments] Unexpected exception
03-29 11:11:51.943  3037  3873 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-29 11:11:51.943  3037  3873 E HttpOperation: 	at jdm.a(PG:82)
03-29 11:11:51.943  3037  3873 E HttpOperation: 	at jcs.o(PG:406)
03-29 11:11:51.943  3037  3873 E HttpOperation: 	at jcn.a(PG:1379)
03-29 11:11:51.943  3037  3873 E HttpOperation: 	at jcs.i(PG:143)
03-29 11:11:51.943  3037  3873 E HttpOperation: 	at hec.a(PG:42)
03-29 11:11:51.943  3037  3873 E HttpOperation: 	at hee.a(PG:102)
03-29 11:11:51.943  3037  3873 E HttpOperation: 	at czr.a(PG:65)
03-29 11:11:51.943  3037  3873 E HttpOperation: 	at kka.a(PG:108)
03-29 11:11:51.943  3037  3873 E HttpOperation: 	at czp.a(PG:19176)
03-29 11:11:51.943  3037  3873 E HttpOperation: 	at czp.a(PG:9081)
03-29 11:11:51.943  3037  3873 E HttpOperation: 	at czq.run(PG:1686)
03-29 11:11:51.943  3037  3873 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-29 11:11:51.943  3037  3873 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-29 11:11:51.943  3037  3873 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 11:11:51.943  3037  3873 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 11:11:51.943  3037  3873 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-29 11:11:51.943  3037  3873 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-29 11:11:51.943  3037  3873 E HttpOperation: 	at jdj.a(PG:4091)
03-29 11:11:51.943  3037  3873 E HttpOperation: 	at jdj.a(PG:1125)
03-29 11:11:51.943  3037  3873 E HttpOperation: 	at jdm.a(PG:77)
03-29 11:11:51.943  3037  3873 E HttpOperation: 	... 15 more
03-29 11:11:51.943  3037  3873 E HttpOperation: Caused by: faj: BadAuthentication
03-29 11:11:51.943  3037  3873 E HttpOperation: 	at fal.a(PG:38)
03-29 11:11:51.943  3037  3873 E HttpOperation: 	at jdj.a(PG:4089)
03-29 11:11:51.943  3037  3873 E HttpOperation: 	... 17 more
,03-29 11:11:51.945  3037  3873 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
03-29 11:11:51.945  3037  3873 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
03-29 11:11:51.945  3037  3873 E ExperimentLoader: ,	at jdm.a(PG:82)
03-29 11:11:51.945  3037  3873 E ExperimentLoader: 	,at jcs.o(PG:406)
03-29 11:11:51.945  3037  3873 E ExperimentLoader: 	at jcn.a(PG:1379)
,03-29 11:11:51.945  3037  3873 E ExperimentLoader: 	at jcs.i(PG:143)
03-29 11:11:51.945  3037  3873 E ExperimentLoader: 	at hec.a(PG:42),
03-29 11:11:51.945  3037  3873 E ExperimentLoader: 	at hee.a(PG:102)
,03-29 11:11:51.945  3037  3873 E ExperimentLoader: 	at czr.a(PG:65)
03-29 11:11:51.945  3037  3873 E ExperimentLoader: ,	at kka.a(PG:108)
03-29 11:11:51.945  3037  3873 E ExperimentLoader: 	at czp.a(PG:19176)
03-29 11:11:51.945  3037  3873 E ExperimentLoader: 	at czp.a(PG:9081)
03-29 11:11:51.945  3037  3873 E ExperimentLoader: 	at czq.run(PG:1686)
03-29 11:11:51.945  3037  3873 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-29 11:11:51.945  3037  3873 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-29 11:11:51.945  3037  3873 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 11:11:51.945  3037  3873 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 11:11:51.945  3037  3873 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
03-29 11:11:51.945  3037  3873 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-29 11:11:51.945  3037  3873 E ExperimentLoader: 	at jdj.a(PG:4091)
03-29 11:11:51.945  3037  3873 E ExperimentLoader: 	at jdj.a(PG:1125)
03-29 11:11:51.945  3037  3873 E ExperimentLoader: 	at jdm.a(PG:77)
03-29 11:11:51.945  3037  3873 E ExperimentLoader: 	... 15 more
03-29 11:11:51.945  3037  3873 E ExperimentLoader: Caused by: faj: BadAuthentication
03-29 11:11:51.945  3037  3873 E ExperimentLoader: 	at fal.a(PG:38)
03-29 11:11:51.945  3037  3873 E ExperimentLoader: 	at jdj.a(PG:4089)
03-29 11:11:51.945  3037  3873 E ExperimentLoader: 	... 17 more
,03-29 11:11:52.073   823   856 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 443835, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,03-29 11:12:21.612  3496  3882 I BooksSync: Starting books sync for 61035162, extras: ade
,03-29 11:12:21.633  3470  3881 V KeepSync: Connecting to GoogleApiClient
,03-29 11:12:21.670  3496  3884 I BooksConfig: GmsCore Version = 7.8.99 (2134222-430)
,03-29 11:12:21.754  1240  1256 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,03-29 11:12:21.755  1240  1256 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 11:12:21.755  1240  1256 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 11:12:21.755  1240  1256 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 11:12:21.765  1240  1256 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 11:12:21.778  1240  2551 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
03-29 11:12:21.779  1240  2551 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 11:12:21.779  1240  2551 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 11:12:21.779  1240  2551 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 11:12:21.789  1240  2551 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 11:12:21.824  1805  3886 E ClientConnectionOperation: Handling authorization failure
03-29 11:12:21.824  1805  3886 E ClientConnectionOperation: com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
03-29 11:12:21.824  1805  3886 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
03-29 11:12:21.824  1805  3886 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
03-29 11:12:21.824  1805  3886 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
03-29 11:12:21.824  1805  3886 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
03-29 11:12:21.824  1805  3886 E ClientConnectionOperation: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-29 11:12:21.824  1805  3886 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 11:12:21.824  1805  3886 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587),
03-29 11:12:21.824  1805  3886 E ClientConnectionOperation: 	at java.lang.Thread.run(Thread.java:818)
03-29 11:12:21.824  1805  3886 E ClientConnectionOperation: Caused by: com.google.android.gms.auth.ad: BadAuthentication
03-29 11:12:21.824  1805  3886 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.b(SourceFile:442)
03-29 11:12:21.824  1805  3886 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:365)
03-29 11:12:21.824  1805  3886 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:310)
03-29 11:12:21.824  1805  3886 E ClientConnectionOperation: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
03-29 11:12:21.824  1805  3886 E ClientConnectionOperation: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
03-29 11:12:21.824  1805  3886 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:30)
03-29 11:12:21.824  1805  3886 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:370)
03-29 11:12:21.824  1805  3886 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:340)
03-29 11:12:21.824  1805  3886 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:319)
03-29 11:12:21.824  1805  3886 E ClientConnectionOperation: 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
03-29 11:12:21.824  1805  3886 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
03-29 11:12:21.824  1805  3886 E ClientConnectionOperation: 	... 7 more
,03-29 11:12:21.830  3470  3881 V KeepSync: GoogleApiClient failed to connect with error code: 4
,03-29 11:12:21.839  3470  3881 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-29 11:12:21.854  3470  3881 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-29 11:12:21.856  3470  3881 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-29 11:12:21.878  1240  1257 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-29 11:12:21.878  1240  1257 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 11:12:21.878  1240  1257 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 11:12:21.878  1240  1257 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 11:12:21.882  1240  1257 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 11:12:21.893  3496  3884 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,03-29 11:12:21.895  3496  3882 E BooksSync: Soft error
03-29 11:12:21.895  3496  3882 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-29 11:12:21.895  3496  3882 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,03-29 11:12:21.895  3496  3882 E BooksSync: Sync error
03-29 11:12:21.895  3496  3882 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-29 11:12:21.895  3496  3882 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,03-29 11:12:21.895  3496  3882 I BooksSync: Finished books sync
,03-29 11:12:21.903   823   856 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 449918, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-29 11:12:21.915  1240  2583 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
03-29 11:12:21.915  1240  2583 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 11:12:21.915  1240  2583 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-29 11:12:21.915  1240  2583 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 11:12:21.918  1240  2583 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 11:12:21.969  1240  1240 I art     : Explicit concurrent mark sweep GC freed 48942(2MB) AllocSpace objects, 15(1653KB) LOS objects, 36% free, 27MB/43MB, paused 1.249ms total 46.659ms
,03-29 11:12:22.021  3470  3881 E KeepSync: IOException
03-29 11:12:22.021  3470  3881 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
03-29 11:12:22.021  3470  3881 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
03-29 11:12:22.021  3470  3881 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
03-29 11:12:22.021  3470  3881 E KeepSync: 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
03-29 11:12:22.021  3470  3881 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
03-29 11:12:22.021  3470  3881 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
03-29 11:12:22.021  3470  3881 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
03-29 11:12:22.021  3470  3881 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
03-29 11:12:22.021  3470  3881 E KeepSync: 	at com.google.android.keep.util.m.a(SourceFile:207)
03-29 11:12:22.021  3470  3881 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
03-29 11:12:22.021  3470  3881 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
03-29 11:12:22.021  3470  3881 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
03-29 11:12:22.021  3470  3881 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
03-29 11:12:22.021  3470  3881 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
03-29 11:12:22.021  3470  3881 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
03-29 11:12:22.021  3470  3881 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
03-29 11:12:22.021  3470  3881 E KeepSync: 	... 10 more
03-29 11:12:22.022  3470  3881 W KeepSync: Sync result 2
,03-29 11:12:22.030   823   856 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 444402, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-29 11:12:35.268  2152  2220 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-29 11:13:55.567  2152  2220 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-29 11:13:59.054  1240  2551 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-29 11:13:59.054  1240  2551 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 11:13:59.054  1240  2551 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 11:13:59.054  1240  2551 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 11:13:59.061  1240  2551 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 11:13:59.145   823  1448 I art     : Explicit concurrent mark sweep GC freed 37497(1621KB) AllocSpace objects, 9(521KB) LOS objects, 31% free, 34MB/50MB, paused 1.703ms total 77.923ms
,03-29 11:13:59.200  3037  3910 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
03-29 11:13:59.200  3037  3910 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-29 11:13:59.200  3037  3910 E HttpOperation: 	at jdm.a(PG:82)
03-29 11:13:59.200  3037  3910 E HttpOperation: 	at jcs.o(PG:406)
03-29 11:13:59.200  3037  3910 E HttpOperation: 	at jcn.a(PG:1379)
03-29 11:13:59.200  3037  3910 E HttpOperation: 	at jcs.i(PG:143)
03-29 11:13:59.200  3037  3910 E HttpOperation: 	at blb.a(PG:3937)
03-29 11:13:59.200  3037  3910 E HttpOperation: 	at czp.a(PG:18188)
03-29 11:13:59.200  3037  3910 E HttpOperation: 	at czp.a(PG:9081)
03-29 11:13:59.200  3037  3910 E HttpOperation: 	at czq.run(PG:1686)
03-29 11:13:59.200  3037  3910 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-29 11:13:59.200  3037  3910 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-29 11:13:59.200  3037  3910 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 11:13:59.200  3037  3910 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 11:13:59.200  3037  3910 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-29 11:13:59.200  3037  3910 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-29 11:13:59.200  3037  3910 E HttpOperation: 	at jdj.a(PG:4091)
03-29 11:13:59.200  3037  3910 E HttpOperation: 	at jdj.a(PG:1125)
03-29 11:13:59.200  3037  3910 E HttpOperation: 	at jdm.a(PG:77)
03-29 11:13:59.200  3037  3910 E HttpOperation: 	... 12 more
03-29 11:13:59.200  3037  3910 E HttpOperation: Caused by: faj: BadAuthentication
03-29 11:13:59.200  3037  3910 E HttpOperation: 	at fal.a(PG:38)
03-29 11:13:59.200  3037  3910 E HttpOperation: 	at jdj.a(PG:4089)
03-29 11:13:59.200  3037  3910 E HttpOperation: 	... 14 more
,03-29 11:13:59.230  1240  1256 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,03-29 11:13:59.230  1240  1256 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 11:13:59.230  1240  1256 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 11:13:59.231  1240  1256 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 11:13:59.234  1240  1256 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,03-29 11:13:59.244  3037  3910 E HttpOperation: [getmobileexperiments] Unexpected exception,
03-29 11:13:59.244  3037  3910 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-29 11:13:59.244  3037  3910 E HttpOperation: 	at jdm.a(PG:82)
03-29 11:13:59.244  3037  3910 E HttpOperation: 	at jcs.o(PG:406)
03-29 11:13:59.244  3037  3910 E HttpOperation: 	at jcn.a(PG:1379)
03-29 11:13:59.244  3037  3910 E HttpOperation: 	at jcs.i(PG:143)
03-29 11:13:59.244  3037  3910 E HttpOperation: 	at hec.a(PG:42)
03-29 11:13:59.244  3037  3910 E HttpOperation: 	at hee.a(PG:102),
03-29 11:13:59.244  3037  3910 E HttpOperation: 	at czr.a(PG:65)
03-29 11:13:59.244  3037  3910 E HttpOperation: 	at kka.a(PG:108)
03-29 11:13:59.244  3037  3910 E HttpOperation: 	at czp.a(PG:19176)
03-29 11:13:59.244  3037  3910 E HttpOperation: 	at czp.a(PG:9081)
03-29 11:13:59.244  3037  3910 E HttpOperation: 	at czq.run(PG:1686)
03-29 11:13:59.244  3037  3910 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-29 11:13:59.244  3037  3910 E HttpOperation: 	,at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-29 11:13:59.244  3037  3910 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 11:13:59.244  3037  3910 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 11:13:59.244  3037  3910 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-29 11:13:59.244  3037  3910 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-29 11:13:59.244  3037  3910 E HttpOperation: 	at jdj.a(PG:4091)
03-29 11:13:59.244  3037  3910 E HttpOperation: 	at jdj.a(PG:1125)
03-29 11:13:59.244  3037  3910 E HttpOperation: ,	at jdm.a(PG:77)
03-29 11:13:59.244  3037  3910 E HttpOperation: 	... 15 more
03-29 11:13:59.244  3037  3910 E HttpOperation: Caused by: faj: BadAuthentication
03-29 11:13:59.244  3037  3910 E HttpOperation: 	at fal.a(PG:38)
03-29 11:13:59.244  3037  3910 E HttpOperation: 	at jdj.a(PG:4089)
03-29 11:13:59.244  3037  3910 E HttpOperation: 	... 17 more
03-29 11:13:59.244  3037  3910 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
03-29 11:13:59.244  3037  3910 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
03-29 11:13:59.244  3037  3910 E ExperimentLoader: 	at jdm.a(PG:82)
03-29 11:13:59.244  3037  3910 E ExperimentLoader: 	at jcs.o(PG:406)
03-29 11:13:59.244  3037  3910 E ExperimentLoader: 	at jcn.a(PG:1379)
03-29 11:13:59.244  3037  3910 E ExperimentLoader: ,	at jcs.i(PG:143)
03-29 11:13:59.244  3037  3910 E ExperimentLoader: 	at hec.a(PG:42)
03-29 11:13:59.244  3037  3910 E ExperimentLoader: 	at hee.a(PG:102)
03-29 11:13:59.244  3037  3910 E ExperimentLoader: 	at czr.a(PG:65)
03-29 11:13:59.244  3037  3910 E ExperimentLoader: 	at kka.a(PG:108)
03-29 11:13:59.244  3037  3910 E ExperimentLoader: 	at czp.a(PG:19176)
03-29 11:13:59.244  3037  3910 E ExperimentLoader: 	at czp.a(PG:9081)
03-29 11:13:59.244  3037  3910 E ExperimentLoader: 	at czq.run(PG:1686)
03-29 11:13:59.244  3037  3910 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-29 11:13:59.244  3037  3910 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-29 11:13:59.244  3037  3910 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 11:13:59.244  3037  3910 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 11:13:59.244  3037  3910 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
03-29 11:13:59.244  3037  3910 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-29 11:13:59.244  3037  3910 E ExperimentLoader: 	at jdj.a(PG:4091)
03-29 11:13:59.244  3037  3910 E ExperimentLoader: 	at jdj.a(PG:1125)
03-29 11:13:59.244  3037  3910 E ExperimentLoader: 	at jdm.a(PG:77)
03-29 11:13:59.244  3037  3910 E ExperimentLoader: 	... 15 more
,03-29 11:13:59.244  3037  3910 E ExperimentLoader: Caused by: faj: BadAuthentication
03-29 11:13:59.244  3037  3910 E ExperimentLoader: 	at fal.a(PG:38)
03-29 11:13:59.244  3037  3910 E ExperimentLoader: 	at jdj.a(PG:4089)
03-29 11:13:59.244  3037  3910 E ExperimentLoader: 	... 17 more
,03-29 11:13:59.336   823   856 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 571099, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,03-29 11:14:35.267  2152  2220 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-29 11:14:55.726  2152  2220 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-29 11:15:01.521  3369  3925 V GoogleAuthProtoRequest: [339] a.<init>: mAccountName set to: thalitester@gmail.com
,03-29 11:15:01.641  1240  2551 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
03-29 11:15:01.642  1240  2551 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-29 11:15:01.642  1240  2551 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 11:15:01.642  1240  2551 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 11:15:01.659  1240  2551 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 11:15:01.684  3369  3925 W ExperimentUpdateService: [339] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,03-29 11:15:01.685  3369  3925 W ExperimentUpdateService: [339] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-29 11:15:01.685  3369  3925 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-29 11:15:01.685  3369  3925 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-29 11:15:01.685  3369  3925 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-29 11:15:01.685  3369  3925 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-29 11:15:01.685  3369  3925 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-29 11:15:01.685  3369  3925 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-29 11:15:01.685  3369  3925 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-29 11:15:01.685  3369  3925 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-29 11:15:01.685  3369  3925 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-29 11:15:01.685  3369  3925 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-29 11:15:27.936  2747  2747 D Finsky  : [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,03-29 11:15:27.951  1240  1240 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 11:15:28.003  1240  2583 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
03-29 11:15:28.003  1240  2583 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 11:15:28.003  1240  2583 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 11:15:28.003  1240  2583 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 11:15:28.013  1240  2583 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 11:15:28.049  2747  2747 W Finsky  : [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.,
,03-29 11:15:28.064  1240  1240 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 11:15:28.141  1240  2551 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,03-29 11:15:28.142  1240  2551 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 11:15:28.142  1240  2551 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 11:15:28.142  1240  2551 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 11:15:28.156  1240  2551 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 11:15:28.219  1240  1240 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 11:15:28.303  1240  1750 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
03-29 11:15:28.303  1240  1750 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 11:15:28.303  1240  1750 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 11:15:28.304  1240  1750 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 11:15:28.315  1240  1750 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 11:15:28.358  2747  2747 W Finsky  : [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,03-29 11:15:28.702  1240  1240 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 11:15:28.764  1240  2583 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,03-29 11:15:28.765  1240  2583 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 11:15:28.765  1240  2583 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 11:15:28.765  1240  2583 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 11:15:28.779  1240  2583 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 11:15:28.811  2747  2747 W Finsky  : [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,03-29 11:15:28.813  2747  2747 D Finsky  : [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,03-29 11:15:28.824  2747  2747 D Finsky  : [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,03-29 11:15:28.828  2747  2747 D Finsky  : [1] DailyHygiene.reschedule: Scheduling new run in 30 minutes (failures=2),
,03-29 11:15:28.841  1842  1858 D DeviceConnectionService: client connected with version: 7571000
,03-29 11:15:35.265  2152  2220 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-29 11:15:43.603  1240  1240 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 11:15:43.632  1240  1750 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,03-29 11:15:43.632  1240  1750 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 11:15:43.632  1240  1750 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 11:15:43.632  1240  1750 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 11:15:43.636  1240  1750 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 11:15:43.651  2747  2747 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
03-29 11:15:43.652  2747  2747 D Finsky  : [1] 5.onFinished: Installation state replication failed.
03-29 11:15:43.652  2747  2747 D Finsky  : [1] 5.onFinished: Scheduling replication attempt 1.
,03-29 11:16:03.944  1240  1240 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 11:16:04.004  1240  2551 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure,
03-29 11:16:04.004  1240  2551 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 11:16:04.004  1240  2551 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-29 11:16:04.005  1240  2551 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 11:16:04.014  1240  2551 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 11:16:04.048  2747  2747 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.,
,03-29 11:16:04.049  2747  2747 D Finsky  : [1] 5.onFinished: Installation state replication failed.
,03-29 11:16:04.050  2747  2747 D Finsky  : [1] 5.onFinished: Scheduling replication attempt 2.
,03-29 11:16:24.370  1240  1240 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 11:16:24.435  1240  1256 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,03-29 11:16:24.436  1240  1256 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 11:16:24.436  1240  1256 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 11:16:24.436  1240  1256 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 11:16:24.445  1240  1256 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 11:16:24.478  2747  2747 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,03-29 11:16:24.480  2747  2747 D Finsky  : [1] 5.onFinished: Installation state replication failed.
,03-29 11:16:24.481  2747  2747 D Finsky  : [1] 5.onFinished: Scheduling replication attempt 3.
,03-29 11:16:30.276  3470  3945 V KeepSync: Connecting to GoogleApiClient
,03-29 11:16:30.458  1240  1256 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,03-29 11:16:30.458  1240  1256 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 11:16:30.459  1240  1256 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 11:16:30.459  1240  1256 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 11:16:30.472  1240  1256 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,03-29 11:16:30.514  1805  3947 E ClientConnectionOperation: Handling authorization failure
03-29 11:16:30.514  1805  3947 E ClientConnectionOperation: com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
03-29 11:16:30.514  1805  3947 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
03-29 11:16:30.514  1805  3947 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
03-29 11:16:30.514  1805  3947 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
03-29 11:16:30.514  1805  3947 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
03-29 11:16:30.514  1805  3947 E ClientConnectionOperation: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-29 11:16:30.514  1805  3947 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 11:16:30.514  1805  3947 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 11:16:30.514  1805  3947 E ClientConnectionOperation: 	at java.lang.Thread.run(Thread.java:818)
03-29 11:16:30.514  1805  3947 E ClientConnectionOperation: Caused by: com.google.android.gms.auth.ad: BadAuthentication
03-29 11:16:30.514  1805  3947 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.b(SourceFile:442)
03-29 11:16:30.514  1805  3947 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:365)
03-29 11:16:30.514  1805  3947 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:310)
03-29 11:16:30.514  1805  3947 E ClientConnectionOperation: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
03-29 11:16:30.514  1805  3947 E ClientConnectionOperation: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
03-29 11:16:30.514  1805  3947 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:30)
03-29 11:16:30.514  1805  3947 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:370)
03-29 11:16:30.514  1805  3947 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:340)
03-29 11:16:30.514  1805  3947 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:319)
03-29 11:16:30.514  1805  3947 E ClientConnectionOperation: 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
03-29 11:16:30.514  1805  3947 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
03-29 11:16:30.514  1805  3947 E ClientConnectionOperation: 	... 7 more
,03-29 11:16:30.520  3470  3945 V KeepSync: GoogleApiClient failed to connect with error code: 4
,03-29 11:16:30.530  3470  3945 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-29 11:16:30.543  3470  3945 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
03-29 11:16:30.543  3470  3945 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-29 11:16:30.683   823  1213 I art     : Explicit concurrent mark sweep GC freed 25497(1087KB) AllocSpace objects, 4(346KB) LOS objects, 32% free, 33MB/49MB, paused 2.537ms total 87.078ms
,03-29 11:16:30.733  1240  2551 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,03-29 11:16:30.734  1240  2551 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
03-29 11:16:30.734  1240  2551 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-29 11:16:30.734  1240  2551 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 11:16:30.740  1240  2551 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,03-29 11:16:30.767  3470  3945 E KeepSync: IOException
,03-29 11:16:30.767  3470  3945 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
03-29 11:16:30.767  3470  3945 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
03-29 11:16:30.767  3470  3945 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
03-29 11:16:30.767  3470  3945 E KeepSync: 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
03-29 11:16:30.767  3470  3945 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858),
03-29 11:16:30.767  3470  3945 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
03-29 11:16:30.767  3470  3945 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
03-29 11:16:30.767  3470  3945 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
03-29 11:16:30.767  3470  3945 E KeepSync: 	at com.google.android.keep.util.m.a(SourceFile:207),
03-29 11:16:30.767  3470  3945 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
03-29 11:16:30.767  3470  3945 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198),
03-29 11:16:30.767  3470  3945 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
03-29 11:16:30.767  3470  3945 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
03-29 11:16:30.767  3470  3945 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
03-29 11:16:30.767  3470  3945 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
03-29 11:16:30.767  3470  3945 E KeepSync: ,	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
03-29 11:16:30.767  3470  3945 E KeepSync: 	... 10 more
,03-29 11:16:30.767  3470  3945 W KeepSync: Sync result 2
,03-29 11:16:30.777   823   856 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 722525, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1],
,03-29 11:16:35.281  2152  2220 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-29 11:16:44.724  1240  1240 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 11:16:44.799  1240  1750 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
03-29 11:16:44.800  1240  1750 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 11:16:44.800  1240  1750 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 11:16:44.800  1240  1750 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 11:16:44.811  1240  1750 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 11:16:44.898  1240  1750 I art     : Explicit concurrent mark sweep GC freed 49683(2MB) AllocSpace objects, 11(1213KB) LOS objects, 37% free, 26MB/42MB, paused 1.655ms total 66.508ms
,03-29 11:16:44.920  2747  2747 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
03-29 11:16:44.921  2747  2747 D Finsky  : [1] 5.onFinished: Installation state replication failed.
03-29 11:16:44.922  2747  2747 D Finsky  : [1] 5.onFinished: Scheduling replication attempt 4.
,03-29 11:17:00.303  3496  3954 I BooksSync: Starting books sync for 61035162, extras: ade
,03-29 11:17:00.337  3496  3955 I BooksConfig: GmsCore Version = 7.8.99 (2134222-430)
,03-29 11:17:00.421  1240  1256 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,03-29 11:17:00.422  1240  1256 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 11:17:00.422  1240  1256 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 11:17:00.422  1240  1256 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 11:17:00.433  1240  1256 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 11:17:00.569  1240  2583 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,03-29 11:17:00.570  1240  2583 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-29 11:17:00.570  1240  2583 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 11:17:00.570  1240  2583 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 11:17:00.580  1240  2583 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 11:17:00.612  3496  3955 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,03-29 11:17:00.615  3496  3954 E BooksSync: Soft error
03-29 11:17:00.615  3496  3954 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-29 11:17:00.615  3496  3954 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,03-29 11:17:00.616  3496  3954 E BooksSync: Sync error
03-29 11:17:00.616  3496  3954 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-29 11:17:00.616  3496  3954 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,03-29 11:17:00.617  3496  3954 I BooksSync: Finished books sync
,03-29 11:17:00.631   823   856 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 733109, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-29 11:17:05.196  1240  1240 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 11:17:05.272  1240  1749 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,03-29 11:17:05.273  1240  1749 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 11:17:05.273  1240  1749 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 11:17:05.274  1240  1749 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 11:17:05.283  1240  1749 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 11:17:05.308  2747  2747 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,03-29 11:17:05.308  2747  2747 D Finsky  : [1] 5.onFinished: Installation state replication failed.
,03-29 11:17:05.310  2747  2747 D Finsky  : [1] 5.onFinished: Scheduling replication attempt 5.
,03-29 11:17:25.657  1240  1240 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 11:17:25.744  1240  1257 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
03-29 11:17:25.745  1240  1257 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 11:17:25.745  1240  1257 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 11:17:25.746  1240  1257 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 11:17:25.757  1240  1257 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,03-29 11:17:25.817  2747  2747 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,03-29 11:17:25.818  2747  2747 D Finsky  : [1] 5.onFinished: Installation state replication failed.
03-29 11:17:25.818  2747  2747 D Finsky  : [1] 5.onFinished: Giving up after 6 failures.
,03-29 11:17:35.266  2152  2220 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-29 11:18:12.989  1240  2551 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,03-29 11:18:12.989  1240  2551 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 11:18:12.990  1240  2551 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-29 11:18:12.990  1240  2551 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 11:18:13.006  1240  2551 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 11:18:13.050  3037  3975 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception,
03-29 11:18:13.050  3037  3975 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-29 11:18:13.050  3037  3975 E HttpOperation: 	at jdm.a(PG:82)
03-29 11:18:13.050  3037  3975 E HttpOperation: 	at jcs.o(PG:406)
03-29 11:18:13.050  3037  3975 E HttpOperation: 	at jcn.a(PG:1379)
03-29 11:18:13.050  3037  3975 E HttpOperation: 	at jcs.i(PG:143)
03-29 11:18:13.050  3037  3975 E HttpOperation: 	at blb.a(PG:3937)
03-29 11:18:13.050  3037  3975 E HttpOperation: 	at czp.a(PG:18188)
03-29 11:18:13.050  3037  3975 E HttpOperation: 	at czp.a(PG:9081)
03-29 11:18:13.050  3037  3975 E HttpOperation: 	at czq.run(PG:1686)
03-29 11:18:13.050  3037  3975 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-29 11:18:13.050  3037  3975 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-29 11:18:13.050  3037  3975 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 11:18:13.050  3037  3975 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 11:18:13.050  3037  3975 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-29 11:18:13.050  3037  3975 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-29 11:18:13.050  3037  3975 E HttpOperation: 	at jdj.a(PG:4091)
03-29 11:18:13.050  3037  3975 E HttpOperation: 	at jdj.a(PG:1125)
03-29 11:18:13.050  3037  3975 E HttpOperation: 	at jdm.a(PG:77)
03-29 11:18:13.050  3037  3975 E HttpOperation: 	... 12 more,
03-29 11:18:13.050  3037  3975 E HttpOperation: Caused by: faj: BadAuthentication
03-29 11:18:13.050  3037  3975 E HttpOperation: 	at fal.a(PG:38)
03-29 11:18:13.050  3037  3975 E HttpOperation: 	at jdj.a(PG:4089)
03-29 11:18:13.050  3037  3975 E HttpOperation: 	... 14 more
,03-29 11:18:13.138  1240  2583 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-29 11:18:13.139  1240  2583 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 11:18:13.139  1240  2583 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 11:18:13.139  1240  2583 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 11:18:13.147  1240  2583 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 11:18:13.182  3037  3975 E HttpOperation: [getmobileexperiments] Unexpected exception
03-29 11:18:13.182  3037  3975 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-29 11:18:13.182  3037  3975 E HttpOperation: 	at jdm.a(PG:82)
03-29 11:18:13.182  3037  3975 E HttpOperation: 	at jcs.o(PG:406)
03-29 11:18:13.182  3037  3975 E HttpOperation: 	at jcn.a(PG:1379)
03-29 11:18:13.182  3037  3975 E HttpOperation: 	at jcs.i(PG:143)
03-29 11:18:13.182  3037  3975 E HttpOperation: 	at hec.a(PG:42)
03-29 11:18:13.182  3037  3975 E HttpOperation: 	at hee.a(PG:102)
03-29 11:18:13.182  3037  3975 E HttpOperation: 	at czr.a(PG:65)
03-29 11:18:13.182  3037  3975 E HttpOperation: 	at kka.a(PG:108)
03-29 11:18:13.182  3037  3975 E HttpOperation: 	at czp.a(PG:19176)
03-29 11:18:13.182  3037  3975 E HttpOperation: 	at czp.a(PG:9081)
03-29 11:18:13.182  3037  3975 E HttpOperation: 	at czq.run(PG:1686)
03-29 11:18:13.182  3037  3975 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-29 11:18:13.182  3037  3975 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-29 11:18:13.182  3037  3975 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 11:18:13.182  3037  3975 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 11:18:13.182  3037  3975 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-29 11:18:13.182  3037  3975 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-29 11:18:13.182  3037  3975 E HttpOperation: 	at jdj.a(PG:4091)
03-29 11:18:13.182  3037  3975 E HttpOperation: 	at jdj.a(PG:1125)
03-29 11:18:13.182  3037  3975 E HttpOperation: 	at jdm.a(PG:77)
03-29 11:18:13.182  3037  3975 E HttpOperation: 	... 15 more
03-29 11:18:13.182  3037  3975 E HttpOperation: Caused by: faj: BadAuthentication
03-29 11:18:13.182  3037  3975 E HttpOperation: 	at fal.a(PG:38)
03-29 11:18:13.182  3037  3975 E HttpOperation: 	at jdj.a(PG:4089)
03-29 11:18:13.182  3037  3975 E HttpOperation: 	... 17 more
,03-29 11:18:13.184  3037  3975 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
,03-29 11:18:13.184  3037  3975 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
03-29 11:18:13.184  3037  3975 E ExperimentLoader: 	at jdm.a(PG:82)
03-29 11:18:13.184  3037  3975 E ExperimentLoader: 	at jcs.o(PG:406)
03-29 11:18:13.184  3037  3975 E ExperimentLoader: 	at jcn.a(PG:1379)
,03-29 11:18:13.184  3037  3975 E ExperimentLoader: 	at jcs.i(PG:143)
,03-29 11:18:13.184  3037  3975 E ExperimentLoader: 	at hec.a(PG:42)
03-29 11:18:13.184  3037  3975 E ExperimentLoader: 	at hee.a(PG:102)
03-29 11:18:13.184  3037  3975 E ExperimentLoader: 	at czr.a(PG:65)
03-29 11:18:13.184  3037  3975 E ExperimentLoader: 	at kka.a(PG:108)
03-29 11:18:13.184  3037  3975 E ExperimentLoader: 	at czp.a(PG:19176)
03-29 11:18:13.184  3037  3975 E ExperimentLoader: 	,at czp.a(PG:9081)
03-29 11:18:13.184  3037  3975 E ExperimentLoader: 	at czq.run(PG:1686)
03-29 11:18:13.184  3037  3975 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-29 11:18:13.184  3037  3975 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-29 11:18:13.184  3037  3975 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 11:18:13.184  3037  3975 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 11:18:13.184  3037  3975 E ExperimentLoader: 	,at java.lang.Thread.run(Thread.java:818)
03-29 11:18:13.184  3037  3975 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-29 11:18:13.184  3037  3975 E ExperimentLoader: 	at jdj.a(PG:4091)
03-29 11:18:13.184  3037  3975 E ExperimentLoader: 	at jdj.a(PG:1125)
03-29 11:18:13.184  3037  3975 E ExperimentLoader: 	at jdm.a(PG:77)
03-29 11:18:13.184  3037  3975 E ExperimentLoader: 	... 15 more
03-29 11:18:13.184  3037  39,75 E ExperimentLoader: Caused by: faj: BadAuthentication
03-29 11:18:13.184  3037  3975 E ExperimentLoader: 	at fal.a(PG:38)
03-29 11:18:13.184  3037  3975 E ExperimentLoader: 	at jdj.a(PG:4089)
03-29 11:18:13.184  3037  3975 E ExperimentLoader: 	... 17 more
,03-29 11:18:13.339   823   856 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 825087, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,03-29 11:18:35.270  2152  2220 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-29 11:19:35.266  2152  2220 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-29 11:19:56.526  2152  2220 D HeadsetStateMachine: Disconnected process message: 10, size: 0,
,03-29 11:20:20.550  2152  2232 W bt-btm  : Stopping oneshot timer
,03-29 11:20:35.266  2152  2220 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-29 11:21:35.266  2152  2220 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-29 11:21:56.849  2152  2220 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-29 11:22:57.010  2152  2220 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-29 11:23:09.892  1805  4027 I EventLogService: Opted in for usage reporting
,03-29 11:23:09.894  1805  4027 I EventLogService: Aggregate from 1459241476924 (log), 1459241476924 (data)
,03-29 11:23:09.907  3369  4028 V GoogleAuthProtoRequest: [340] a.<init>: mAccountName set to: thalitester@gmail.com
,03-29 11:23:09.923  1240  3491 D GCM     : Message class com.google.f.a.a.i
,03-29 11:23:10.010  1240  1749 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,03-29 11:23:10.010  1240  1749 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 11:23:10.011  1240  1749 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 11:23:10.011  1240  1749 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 11:23:10.017  1240  1749 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 11:23:10.042  3369  4028 W ExperimentUpdateService: [340] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
03-29 11:23:10.042  3369  4028 W ExperimentUpdateService: [340] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-29 11:23:10.042  3369  4028 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-29 11:23:10.042  3369  4028 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-29 11:23:10.042  3369  4028 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-29 11:23:10.042  3369  4028 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-29 11:23:10.042  3369  4028 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-29 11:23:10.042  3369  4028 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-29 11:23:10.042  3369  4028 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-29 11:23:10.042  3369  4028 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-29 11:23:10.042  3369  4028 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-29 11:23:10.042  3369  4028 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-29 11:23:10.084  1805  4027 W EventLogAggregator: Unknown tag: snet_gcore
,03-29 11:23:10.084  1805  4027 W EventLogAggregator: Unknown tag: snet_launch_service
,03-29 11:23:10.163   823  1448 I art     : Explicit concurrent mark sweep GC freed 39935(1923KB) AllocSpace objects, 4(64KB) LOS objects, 31% free, 34MB/50MB, paused 1.505ms total 53.019ms
,03-29 11:23:10.167  1805  4027 I ServiceDumpSys: dumping service [account]
,03-29 11:23:35.267  2152  2220 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-29 11:23:57.173  2152  2220 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-29 11:24:35.266  2152  2220 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-29 11:24:47.246  3470  4047 V KeepSync: Connecting to GoogleApiClient
,03-29 11:24:47.362  1240  1750 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
03-29 11:24:47.363  1240  1750 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 11:24:47.363  1240  1750 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-29 11:24:47.363  1240  1750 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 11:24:47.374  1240  1750 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 11:24:47.401  1805  4049 E ClientConnectionOperation: Handling authorization failure
03-29 11:24:47.401  1805  4049 E ClientConnectionOperation: com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
03-29 11:24:47.401  1805  4049 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
03-29 11:24:47.401  1805  4049 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
03-29 11:24:47.401  1805  4049 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
03-29 11:24:47.401  1805  4049 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
03-29 11:24:47.401  1805  4049 E ClientConnectionOperation: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-29 11:24:47.401  1805  4049 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 11:24:47.401  1805  4049 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 11:24:47.401  1805  4049 E ClientConnectionOperation: 	at java.lang.Thread.run(Thread.java:818)
03-29 11:24:47.401  1805  4049 E ClientConnectionOperation: Caused by: com.google.android.gms.auth.ad: BadAuthentication
03-29 11:24:47.401  1805  4049 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.b(SourceFile:442)
03-29 11:24:47.401  1805  4049 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:365)
03-29 11:24:47.401  1805  4049 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:310)
03-29 11:24:47.401  1805  4049 E ClientConnectionOperation: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
03-29 11:24:47.401  1805  4049 E ClientConnectionOperation: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
03-29 11:24:47.401  1805  4049 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:30)
03-29 11:24:47.401  1805  4049 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:370)
03-29 11:24:47.401  1805  4049 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:340)
03-29 11:24:47.401  1805  4049 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:319)
03-29 11:24:47.401  1805  4049 E ClientConnectionOperation: 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
03-29 11:24:47.401  1805  4049 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
03-29 11:24:47.401  1805  4049 E ClientConnectionOperation: 	... 7 more
,03-29 11:24:47.405  3470  4047 V KeepSync: GoogleApiClient failed to connect with error code: 4
,03-29 11:24:47.421  3470  4047 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-29 11:24:47.436  3470  4047 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-29 11:24:47.439  3470  4047 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-29 11:24:47.546  1240  2583 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,03-29 11:24:47.546  1240  2583 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 11:24:47.547  1240  2583 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 11:24:47.547  1240  2583 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 11:24:47.560  1240  2583 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 11:24:47.655  3470  4047 E KeepSync: IOException
03-29 11:24:47.655  3470  4047 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
03-29 11:24:47.655  3470  4047 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
03-29 11:24:47.655  3470  4047 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
03-29 11:24:47.655  3470  4047 E KeepSync: 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
03-29 11:24:47.655  3470  4047 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
03-29 11:24:47.655  3470  4047 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
03-29 11:24:47.655  3470  4047 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
03-29 11:24:47.655  3470  4047 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
03-29 11:24:47.655  3470  4047 E KeepSync: 	at com.google.android.keep.util.m.a(SourceFile:207)
03-29 11:24:47.655  3470  4047 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
03-29 11:24:47.655  3470  4047 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
03-29 11:24:47.655  3470  4047 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
03-29 11:24:47.655  3470  4047 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
03-29 11:24:47.655  3470  4047 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
03-29 11:24:47.655  3470  4047 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
03-29 11:24:47.655  3470  4047 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
03-29 11:24:47.655  3470  4047 E KeepSync: 	... 10 more
03-29 11:24:47.655  3470  4047 W KeepSync: Sync result 2
,03-29 11:24:47.670   823   856 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 1219463, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-29 11:24:57.329  2152  2220 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-29 11:24:59.763   823   856 I UsageStatsService: User[0] Flushing usage stats to disk
,03-29 11:25:10.182  1240  2078 I art     : Explicit concurrent mark sweep GC freed 58868(2MB) AllocSpace objects, 5(551KB) LOS objects, 37% free, 27MB/43MB, paused 2.325ms total 59.082ms
,03-29 11:25:35.268  2152  2220 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-29 11:25:47.428  3496  4062 I BooksSync: Starting books sync for 61035162, extras: ade
,03-29 11:25:47.477  3496  4063 I BooksConfig: GmsCore Version = 7.8.99 (2134222-430)
,03-29 11:25:47.579  1240  2583 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,03-29 11:25:47.580  1240  2583 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 11:25:47.580  1240  2583 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 11:25:47.581  1240  2583 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 11:25:47.594  1240  2583 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 11:25:47.730  1240  1750 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-29 11:25:47.730  1240  1750 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 11:25:47.730  1240  1750 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 11:25:47.731  1240  1750 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 11:25:47.738  1240  1750 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 11:25:47.765  3496  4063 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,03-29 11:25:47.767  3496  4062 E BooksSync: Soft error
03-29 11:25:47.767  3496  4062 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-29 11:25:47.767  3496  4062 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-29 11:25:47.767  3496  4062 E BooksSync: Sync error
03-29 11:25:47.767  3496  4062 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-29 11:25:47.767  3496  4062 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,03-29 11:25:47.767  3496  4062 I BooksSync: Finished books sync
,03-29 11:25:47.782   823   856 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1270742, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-29 11:26:35.269  2152  2220 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-29 11:26:47.626  1240  2583 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-29 11:26:47.627  1240  2583 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 11:26:47.627  1240  2583 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 11:26:47.627  1240  2583 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 11:26:47.635  1240  2583 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 11:26:47.656  3037  4075 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
03-29 11:26:47.656  3037  4075 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-29 11:26:47.656  3037  4075 E HttpOperation: 	at jdm.a(PG:82)
03-29 11:26:47.656  3037  4075 E HttpOperation: 	at jcs.o(PG:406)
03-29 11:26:47.656  3037  4075 E HttpOperation: 	at jcn.a(PG:1379)
03-29 11:26:47.656  3037  4075 E HttpOperation: 	at jcs.i(PG:143)
03-29 11:26:47.656  3037  4075 E HttpOperation: 	at blb.a(PG:3937)
03-29 11:26:47.656  3037  4075 E HttpOperation: 	at czp.a(PG:18188)
03-29 11:26:47.656  3037  4075 E HttpOperation: 	at czp.a(PG:9081)
03-29 11:26:47.656  3037  4075 E HttpOperation: 	at czq.run(PG:1686)
03-29 11:26:47.656  3037  4075 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-29 11:26:47.656  3037  4075 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-29 11:26:47.656  3037  4075 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 11:26:47.656  3037  4075 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 11:26:47.656  3037  4075 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-29 11:26:47.656  3037  4075 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-29 11:26:47.656  3037  4075 E HttpOperation: 	at jdj.a(PG:4091)
03-29 11:26:47.656  3037  4075 E HttpOperation: 	at jdj.a(PG:1125)
03-29 11:26:47.656  3037  4075 E HttpOperation: 	at jdm.a(PG:77)
03-29 11:26:47.656  3037  4075 E HttpOperation: 	... 12 more
03-29 11:26:47.656  3037  4075 E HttpOperation: Caused by: faj: BadAuthentication
03-29 11:26:47.656  3037  4075 E HttpOperation: 	at fal.a(PG:38)
03-29 11:26:47.656  3037  4075 E HttpOperation: 	at jdj.a(PG:4089)
03-29 11:26:47.656  3037  4075 E HttpOperation: 	... 14 more
,03-29 11:26:47.733  1240  2583 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,03-29 11:26:47.734  1240  2583 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 11:26:47.734  1240  2583 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-29 11:26:47.734  1240  2583 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 11:26:47.744  1240  2583 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 11:26:47.769  3037  4075 E HttpOperation: [getmobileexperiments] Unexpected exception
03-29 11:26:47.769  3037  4075 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-29 11:26:47.769  3037  4075 E HttpOperation: 	,at jdm.a(PG:82)
03-29 11:26:47.769  3037  4075 E HttpOperation: 	at jcs.o(PG:406)
03-29 11:26:47.769  3037  4075 E HttpOperation: 	at jcn.a(PG:1379)
03-29 11:26:47.769  3037  4075 E HttpOperation: 	at jcs.i(PG:143)
03-29 11:26:47.769  3037  4075 E HttpOperation: 	at hec.a(PG:42)
03-29 11:26:47.769  3037  4075 E HttpOperation: 	at hee.a(PG:102)
,03-29 11:26:47.769  3037  4075 E HttpOperation: 	at czr.a(PG:65)
03-29 11:26:47.769  3037  4075 E HttpOperation: 	at kka.a(PG:108)
03-29 11:26:47.769  3037  4075 E HttpOperation: 	at czp.a(PG:19176)
03-29 11:26:47.769  3037  4075 E HttpOperation: 	at czp.a(PG:9081)
03-29 11:26:47.769  3037  4075 E HttpOperation: 	at czq.run(PG:1686)
,03-29 11:26:47.769  3037  4075 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-29 11:26:47.769  3037  4075 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-29 11:26:47.769  3037  4075 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 11:26:47.769  3037  4075 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 11:26:47.769  3037  4075 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818),
03-29 11:26:47.769  3037  4075 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-29 11:26:47.769  3037  4075 E HttpOperation: 	at jdj.a(PG:4091)
03-29 11:26:47.769  3037  4075 E HttpOperation: 	at jdj.a(PG:1125)
03-29 11:26:47.769  3037  4075 E HttpOperation: 	at jdm.a(PG:77)
03-29 11:26:47.769  3037  4075 E HttpOperation: ,	... 15 more
03-29 11:26:47.769  3037  4075 E HttpOperation: Caused by: faj: BadAuthentication
03-29 11:26:47.769  3037  4075 E HttpOperation: 	at fal.a(PG:38)
03-29 11:26:47.769  3037  4075 E HttpOperation: 	at jdj.a(PG:4089)
03-29 11:26:47.769  3037  4075 E HttpOperation: 	... 17 more
,03-29 11:26:47.773  3037  4075 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
03-29 11:26:47.773  3037  4075 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
03-29 11:26:47.773  3037  4075 E ExperimentLoader: 	at jdm.a(PG:82)
03-29 11:26:47.773  3037  4075 E ExperimentLoader: 	at jcs.o(PG:406)
03-29 11:26:47.773  3037  4075 E ExperimentLoader: 	at jcn.a(PG:1379)
03-29 11:26:47.773  3037  4075 E ExperimentLoader: 	at jcs.i(PG:143)
03-29 11:26:47.773  3037  4075 E ExperimentLoader: 	at hec.a(PG:42)
03-29 11:26:47.773  3037  4075 E ExperimentLoader: 	at hee.a(PG:102)
03-29 11:26:47.773  3037  4075 E ExperimentLoader: 	at czr.a(PG:65)
03-29 11:26:47.773  3037  4075 E ExperimentLoader: 	at kka.a(PG:108)
03-29 11:26:47.773  3037  4075 E ExperimentLoader: 	at czp.a(PG:19176)
03-29 11:26:47.773  3037  4075 E ExperimentLoader: 	at czp.a(PG:9081)
03-29 11:26:47.773  3037  4075 E ExperimentLoader: 	,at czq.run(PG:1686)
03-29 11:26:47.773  3037  4075 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-29 11:26:47.773  3037  4075 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-29 11:26:47.773  3037  4075 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 11:26:47.773  3037  4075 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 11:26:47.773  3037  4075 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
,03-29 11:26:47.773  3037  4075 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-29 11:26:47.773  3037  4075 E ExperimentLoader: 	at jdj.a(PG:4091)
03-29 11:26:47.773  3037  4075 E ExperimentLoader: 	at jdj.a(PG:1125)
03-29 11:26:47.773  3037  4075 E ExperimentLoader: 	at jdm.a(PG:77)
03-29 11:26:47.773  3037  4075 E ExperimentLoader: 	... 15 more,
03-29 11:26:47.773  3037  4075 E ExperimentLoader: Caused by: faj: BadAuthentication
03-29 11:26:47.773  3037  4075 E ExperimentLoader: 	at fal.a(PG:38)
03-29 11:26:47.773  3037  4075 E ExperimentLoader: 	at jdj.a(PG:4089)
03-29 11:26:47.773  3037  4075 E ExperimentLoader: 	,... 17 more
,03-29 11:26:47.882   823   856 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 1332538, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,03-29 11:26:57.648  2152  2220 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-29 11:27:35.267  2152  2220 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-29 11:27:57.807  2152  2220 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-29 11:28:35.268  2152  2220 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-29 11:29:35.266  2152  2220 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-29 11:29:58.128  2152  2220 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,TIME-OUT KILL (timeout was 1400000ms)
```
