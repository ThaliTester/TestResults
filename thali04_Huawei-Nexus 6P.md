#### Test 8504691174f7534_thali04_Huawei-Nexus 6P Logs


```
--------- beginning of main
09-15 06:02:57.511   536   536 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
09-15 06:02:57.511   536   536 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-15 06:02:58.005  5573  5573 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-15 06:02:58.010  5573  5573 D AndroidRuntime: CheckJNI is OFF
09-15 06:02:58.038  5573  5573 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-15 06:02:58.074  5573  5573 I Radio-JNI: register_android_hardware_Radio DONE
09-15 06:02:58.092  5573  5573 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-15 06:02:58.097   926  3928 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-15 06:02:58.115  5573  5573 D AndroidRuntime: Shutting down VM
09-15 06:02:58.117  3753  3765 W SearchService: Abort, client detached.
09-15 06:02:58.126  3753  3753 I HotwordDetector: Closing mic
09-15 06:02:58.126  3753  5524 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@364491b
09-15 06:02:58.126  3753  5560 E AudioRecord-JNI: Error -4 during AudioRecord native read
09-15 06:02:58.148   926   937 I ActivityManager: Start proc 5584:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
09-15 06:02:58.205   513  5564 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
09-15 06:02:58.207   513  5564 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
09-15 06:02:58.214   513  5564 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
09-15 06:02:58.214   513  5564 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
09-15 06:02:58.216   513  3079 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
09-15 06:02:58.217  3753  5525 I MicroRecognitionRnrImpl: Stopping hotword detection.
09-15 06:02:58.217  3753  5559 I MicroRecognitionRnrImpl: Detection finished
09-15 06:02:58.236  5584  5584 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
09-15 06:02:58.257  5584  5584 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-15 06:02:58.278  5584  5584 I LibraryLoader: Time to load native libraries: 17 ms (timestamps 280-297)
09-15 06:02:58.278  5584  5584 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-15 06:02:58.293  5584  5584 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {83d4e60}
09-15 06:02:58.294  5584  5584 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-15 06:02:58.294  5584  5584 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-15 06:02:58.297  5584  5584 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-15 06:02:58.298  5584  5584 E SysUtils: ApplicationContext is null in ApplicationStatus
09-15 06:02:58.329  5584  5584 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-15 06:02:58.342  5584  5584 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-15 06:02:58.342  5584  5584 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-15 06:02:58.342  5584  5584 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
09-15 06:02:58.342  5584  5584 I Adreno  : Build Date                       : 12/06/15
09-15 06:02:58.342  5584  5584 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-15 06:02:58.342  5584  5584 I Adreno  : Local Branch                     : mybranch17112971
09-15 06:02:58.342  5584  5584 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
09-15 06:02:58.342  5584  5584 I Adreno  : Remote Branch                    : NONE
09-15 06:02:58.342  5584  5584 I Adreno  : Reconstruct Branch               : NOTHING
,09-15 06:02:58.378   926   943 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@51619b8:true
,09-15 06:02:58.402   408   408 W Binder_2: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[16975]" dev="sockfs" ino=16975 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-15 06:02:58.402   408   408 W Binder_2: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[16975]" dev="sockfs" ino=16975 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-15 06:02:58.415  5584  5584 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-15 06:02:58.424  5584  5584 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,09-15 06:02:58.448   406   406 W Binder_1: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[32399]" dev="sockfs" ino=32399 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-15 06:02:58.448   406   406 W Binder_1: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[32399]" dev="sockfs" ino=32399 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-15 06:02:58.452  5584  5622 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-15 06:02:58.452  3520  3520 W Binder_7: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[24324]" dev="sockfs" ino=24324 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-15 06:02:58.452  3520  3520 W Binder_7: type=1400 audit(0.0:117): avc: denied { ioctl } for path="socket:[24324]" dev="sockfs" ino=24324 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
09-15 06:02:58.455  5584  5609 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-15 06:02:58.480  5584  5622 I OpenGLRenderer: Initialized EGL, version 1.4
,09-15 06:02:58.535  4037  4037 W Binder_C: type=1400 audit(0.0:118): avc: denied { ioctl } for path="socket:[32402]" dev="sockfs" ino=32402 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-15 06:02:58.535  4037  4037 W Binder_C: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[32402]" dev="sockfs" ino=32402 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
09-15 06:02:58.539   926   944 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +419ms
09-15 06:02:58.538  3636  3636 W Binder_8: type=1400 audit(0.0:120): avc: denied { ioctl } for path="socket:[32401]" dev="sockfs" ino=32401 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
09-15 06:02:58.542  3502  3502 I Keyboard.Facilitator: onFinishInput()
09-15 06:02:58.538  3636  3636 W Binder_8: type=1400 audit(0.0:121): avc: denied { ioctl } for path="socket:[32401]" dev="sockfs" ino=32401 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-15 06:02:58.570  5584  5584 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5584
,09-15 06:02:58.664  5584  5584 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-15 06:02:58.788  5584  5625 D jxcore_app_log: JniHelper::setJavaVM(0xf4e3c000), pthread_self() = -587204304
,09-15 06:02:58.792  5584  5625 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-15 06:02:58.792  5584  5625 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-15 06:02:58.792  5584  5625 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-15 06:02:58.792  5584  5625 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-15 06:02:58.792  5584  5625 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-15 06:02:58.792  5584  5625 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@158fb76 added. We now have 1 listener(s)
,09-15 06:02:58.794  5584  5625 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
09-15 06:02:58.794  5584  5625 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-15 06:02:58.794  5584  5625 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-15 06:02:58.795  5584  5625 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-15 06:02:58.796  5584  5625 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-15 06:02:58.796  5584  5625 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-15 06:02:58.796  5584  5625 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-15 06:02:58.796  5584  5625 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
09-15 06:02:58.796  5584  5625 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-15 06:02:58.796  5584  5625 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-15 06:02:58.796  5584  5625 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-15 06:02:58.796  5584  5625 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-15 06:02:58.796  5584  5625 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-15 06:02:58.796  5584  5625 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-15 06:02:58.796  5584  5625 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-15 06:02:58.796  5584  5625 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-15 06:02:58.796  5584  5625 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-15 06:02:58.796  5584  5625 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-15 06:02:58.796  5584  5625 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c369a4d added. We now have 1 listener(s)
09-15 06:02:58.796  5584  5625 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-15 06:02:58.803   926  3057 D WifiService: New client listening to asynchronous messages
,09-15 06:02:58.804  5584  5625 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-15 06:02:58.804  5584  5625 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-15 06:02:58.804  5584  5625 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-15 06:02:58.804  5584  5625 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-15 06:02:58.804  5584  5625 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-15 06:02:58.806  5584  5625 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 06:02:58.806  5584  5625 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,09-15 06:02:58.810  5584  5625 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-15 06:02:58.811  5584  5625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 06:02:58.811  5584  5625 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 06:02:58.811  5584  5625 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 06:02:58.811  5584  5625 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 06:02:58.811  5584  5625 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 06:02:58.811  5584  5625 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 06:02:58.811  5584  5625 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 06:02:58.811  5584  5625 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-15 06:02:58.811  5584  5625 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-15 06:02:58.811  5584  5625 D io.jxcore.node.ConnectivityMonitor: start: OK
09-15 06:02:58.812  5584  5625 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-15 06:02:58.814  5584  5584 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 06:02:58.817  5584  5584 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 06:02:58.827  5584  5584 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-15 06:02:59.099  5584  5631 W jxcore-log: Initializing JXcore engine
,09-15 06:02:59.099  5584  5631 W jxcore-log: JXcore engine is ready
,09-15 06:02:59.122  5631  5631 W Thread-57: type=1400 audit(0.0:122): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=11902 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-15 06:02:59.122  5631  5631 W Thread-57: type=1400 audit(0.0:123): avc: denied { ioctl } for path="socket:[13423]" dev="sockfs" ino=13423 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-15 06:02:59.122  5631  5631 W Thread-57: type=1400 audit(0.0:124): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-15 06:02:59.122  5631  5631 W Thread-57: type=1400 audit(0.0:125): avc: denied { ioctl } for path="socket:[32373]" dev="sockfs" ino=32373 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,09-15 06:02:59.133  5584  5631 W jxcore-log: Starting JXcore engine
,09-15 06:02:59.182  5584  5631 W jxcore-log: Platform android
09-15 06:02:59.182  5584  5631 W jxcore-log: 
,09-15 06:02:59.182  5584  5631 W jxcore-log: Process ARCH arm
09-15 06:02:59.182  5584  5631 W jxcore-log: 
,09-15 06:02:59.279  5584  5631 I jxcore-log: JXcore Cordova bridge is ready!
09-15 06:02:59.279  5584  5631 I jxcore-log: 
,09-15 06:02:59.280  5584  5631 W jxcore-log: JXcore engine is started
,09-15 06:02:59.287  5584  5625 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-15 06:02:59.293  5584  5584 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-15 06:03:01.604   926  5222 D NetlinkSocketObserver: NeighborEvent{elapsedMs=223623, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-15 06:03:05.778  5584  5631 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-15 06:03:05.778  5584  5631 I jxcore-log: 
,09-15 06:03:05.779  5584  5631 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-15 06:03:05.779  5584  5631 I jxcore-log: 
,09-15 06:03:05.783  5584  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 06:03:05.783  5584  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 06:03:05.783  5584  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 06:03:05.783  5584  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 06:03:05.783  5584  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 06:03:05.783  5584  5631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 06:03:05.783  5584  5631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 06:03:05.783  5584  5631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-15 06:03:05.785  5584  5631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-15 06:03:05.786  5584  5631 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-15 06:03:05.786  5584  5631 I jxcore-log: 
,09-15 06:03:05.787  5584  5631 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-15 06:03:05.787  5584  5631 I jxcore-log: 
,09-15 06:03:06.129  5584  5631 D executeNativeTests: Running unit tests
,09-15 06:03:06.140  5584  5631 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 1
,09-15 06:03:06.140  5584  5631 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 1
09-15 06:03:06.140  5584  5631 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-15 06:03:06.140  5584  5631 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
,09-15 06:03:06.140  5584  5631 D com.test.thalitest.ThaliTestRunner: Total duration: 2 ms
09-15 06:03:06.141  5584  5631 I jxcore-log: *Native tests were executed*
09-15 06:03:06.141  5584  5631 I jxcore-log: 
,09-15 06:03:06.141  5584  5631 I jxcore-log: Total number of executed tests:  1
09-15 06:03:06.141  5584  5631 I jxcore-log: 
,09-15 06:03:06.141  5584  5631 I jxcore-log: Number of passed tests:  1
09-15 06:03:06.141  5584  5631 I jxcore-log: 
09-15 06:03:06.142  5584  5631 I jxcore-log: Number of failed tests:  0
09-15 06:03:06.142  5584  5631 I jxcore-log: 
09-15 06:03:06.142  5584  5631 I jxcore-log: Number of ignored tests:  0
09-15 06:03:06.142  5584  5631 I jxcore-log: 
,09-15 06:03:06.142  5584  5631 I jxcore-log: Total duration:  2
09-15 06:03:06.142  5584  5631 I jxcore-log: 
09-15 06:03:06.142  5584  5631 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-15 06:03:06.142  5584  5631 I jxcore-log: 
09-15 06:03:06.143  5584  5631 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-15 06:03:06.143  5584  5631 I jxcore-log: 
,09-15 06:03:06.166  5584  5584 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-15 06:03:06.646  5634  5634 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-15 06:03:06.652  5634  5634 D AndroidRuntime: CheckJNI is OFF
,09-15 06:03:06.682  5634  5634 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-15 06:03:06.716  5634  5634 I Radio-JNI: register_android_hardware_Radio DONE
,09-15 06:03:06.734  5634  5634 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-15 06:03:06.742   926   939 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
09-15 06:03:06.743   926   939 I ActivityManager: Killing 5584:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,09-15 06:03:06.823   926  3021 W InputDispatcher: channel '81f60e8 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
,09-15 06:03:06.823   926  3021 E InputDispatcher: channel '81f60e8 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
,09-15 06:03:06.829   926  3928 D GraphicsStats: Buffer count: 2
,09-15 06:03:06.829   926  3928 I WindowState: WIN DEATH: Window{81f60e8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-15 06:03:06.829   926  3928 W InputDispatcher: Attempted to unregister already unregistered input channel '81f60e8 com.test.thalitest/com.test.thalitest.MainActivity (server)'
,09-15 06:03:06.829   926  3057 D WifiService: Client connection lost with reason: 4
09-15 06:03:06.832   926   939 W ActivityManager: Force removing ActivityRecord{3557170 u0 com.test.thalitest/.MainActivity t2}: app died, no saved state
,09-15 06:03:06.870   926   949 I art     : Starting a blocking GC Explicit
,09-15 06:03:06.876   926  3236 W ActivityManager: Spurious death for ProcessRecord{d7598a 0:com.test.thalitest/u0a77}, curProc for 5584: null
,09-15 06:03:06.915   926  3235 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5584 uid 10077
,09-15 06:03:06.912  3235  3235 W Binder_3: type=1400 audit(0.0:126): avc: denied { ioctl } for path="socket:[31455]" dev="sockfs" ino=31455 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
09-15 06:03:06.912  3235  3235 W Binder_3: type=1400 audit(0.0:127): avc: denied { ioctl } for path="socket:[31455]" dev="sockfs" ino=31455 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-15 06:03:06.923  3502  3502 I Keyboard.Facilitator: onFinishInput()
,09-15 06:03:06.952   926   949 I art     : Explicit concurrent mark sweep GC freed 25383(1533KB) AllocSpace objects, 3(60KB) LOS objects, 33% free, 28MB/43MB, paused 2.073ms total 81.560ms
09-15 06:03:06.954  3753  3753 W LocationOracleImpl: Best location was null
,09-15 06:03:06.967  3710  4003 W GCoreFlp: No location to return for getLastLocation()
,09-15 06:03:06.975  3753  5650 I MicroRecognitionRnrImpl: Starting detection.
,09-15 06:03:06.978  3753  5651 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.x@5fe2c0
,09-15 06:03:06.980   513  5653 I AudioFlinger: AudioFlinger's thread 0xf20c0000 ready to run
,09-15 06:03:06.981   926   949 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
09-15 06:03:06.983   513  3079 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
09-15 06:03:06.983  5634  5634 I art     : System.exit called, status: 0
09-15 06:03:06.983  5634  5634 I AndroidRuntime: VM exiting with result code 0.
,09-15 06:03:06.985  3753  5651 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.x@5fe2c0
,09-15 06:03:06.989   926   949 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,09-15 06:03:06.995   513  5653 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(63: voice-rec-mic)
09-15 06:03:06.995   513  5653 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(63) acdb_id(62)
09-15 06:03:06.995   513  5653 I ACDB-LOADER: ACDB AFE returned = -19
09-15 06:03:06.995   513  5653 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 1
09-15 06:03:06.995   513  5653 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 1, rx 0, concurrency session_allowed 0
09-15 06:03:06.995   513  5653 D audio_hw_primary: enable_snd_device: snd_device(63: voice-rec-mic)
,09-15 06:03:07.001  3502  3502 I Keyboard.Facilitator: resetDictionaries() : en_US
09-15 06:03:07.001  4534  4534 D BluetoothMapAppObserver: onReceive
09-15 06:03:07.001  4534  4534 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,09-15 06:03:07.003   513  5653 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,09-15 06:03:07.011  3502  5658 I Keyboard.Facilitator.DecoderInitializer: run()
09-15 06:03:07.011   926  3022 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-15 06:03:07.015  3502  5658 I Decoder : createOrResetDecoder
,09-15 06:03:07.016  3710  4042 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-15 06:03:07.049  3710  4003 W GCoreFlp: No location to return for getLastLocation()
,09-15 06:03:07.063  3470  5662 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-15 06:03:07.072    29    29 W kworker/3:1: type=1400 audit(0.0:128): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-15 06:03:07.078    29    29 W kworker/3:1: type=1400 audit(0.0:129): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-15 06:03:07.081  3753  3753 I HotwordWorkerImpl: onReady
,09-15 06:03:07.084  3594  3594 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-15 06:03:07.088  3669  3669 I ConfigService: onCreate
,09-15 06:03:07.085    29    29 W kworker/3:1: type=1400 audit(0.0:130): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-15 06:03:07.092  3669  5663 W FileUtils: Failed to chmod(/data/user/0/com.google.android.gms/databases/config.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,09-15 06:03:07.095   926   926 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-15 06:03:07.097  3470  5662 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,09-15 06:03:07.110  3502  5658 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,09-15 06:03:07.112  3630  3776 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
09-15 06:03:07.113   926   938 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,09-15 06:03:07.114   926   938 E PackageManager: Failed to write settings, restoring backup
09-15 06:03:07.114   926   938 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
09-15 06:03:07.114   926   938 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
09-15 06:03:07.114   926   938 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
09-15 06:03:07.114   926   938 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-15 06:03:07.114   926   938 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-15 06:03:07.114   926   938 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 06:03:07.114   926   938 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-15 06:03:07.114   926   938 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-15 06:03:07.119   926   939 E DropBoxManagerService: Can't write: system_server_wtf
09-15 06:03:07.119   926   939 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
09-15 06:03:07.119   926   939 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-15 06:03:07.119   926   939 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-15 06:03:07.119   926   939 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-15 06:03:07.119   926   939 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-15 06:03:07.119   926   939 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-15 06:03:07.119   926   939 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-15 06:03:07.119   926   939 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12561)
09-15 06:03:07.119   926   939 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12374)
09-15 06:03:07.119   926   939 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12346)
09-15 06:03:07.119   926   939 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-15 06:03:07.119   926   939 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-15 06:03:07.119   926   939 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-15 06:03:07.119   926   939 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-15 06:03:07.119   926   939 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-15 06:03:07.119   926   939 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-15 06:03:07.119   926   939 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-15 06:03:07.119   926   939 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-15 06:03:07.119   926   939 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-15 06:03:07.119   926   939 E DropBoxManagerService: 	... 13 more
,--------- beginning of crash
09-15 06:03:07.119  3470  5662 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
09-15 06:03:07.119  3470  5662 E AndroidRuntime: Process: android.process.acore, PID: 3470
09-15 06:03:07.119  3470  5662 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-15 06:03:07.119  3470  5662 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-15 06:03:07.119  3470  5662 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-15 06:03:07.119  3470  5662 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-15 06:03:07.119  3470  5662 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-15 06:03:07.119  3470  5662 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-15 06:03:07.119  3470  5662 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
09-15 06:03:07.119  3470  5662 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
09-15 06:03:07.119  3470  5662 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-15 06:03:07.119  3470  5662 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-15 06:03:07.119  3470  5662 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-15 06:03:07.119  3470  5662 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-15 06:03:07.119  3470  5662 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-15 06:03:07.119  3470  5662 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-15 06:03:07.119  3470  5662 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 06:03:07.119  3470  5662 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-15 06:03:07.119  3470  5662 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-15 06:03:07.122  3669  3669 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,09-15 06:03:07.123  3669  3669 D AndroidRuntime: Shutting down VM
09-15 06:03:07.124  3669  3669 E AndroidRuntime: FATAL EXCEPTION: main
09-15 06:03:07.124  3669  3669 E AndroidRuntime: Process: com.google.process.gapps, PID: 3669
09-15 06:03:07.124  3669  3669 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-15 06:03:07.124  3669  3669 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
09-15 06:03:07.124  3669  3669 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
09-15 06:03:07.124  3669  3669 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
09-15 06:03:07.124  3669  3669 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 06:03:07.124  3669  3669 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-15 06:03:07.124  3669  3669 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-15 06:03:07.124  3669  3669 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-15 06:03:07.124  3669  3669 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-15 06:03:07.124  3669  3669 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-15 06:03:07.124  3669  3669 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-15 06:03:07.124  3669  3669 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-15 06:03:07.124  3669  3669 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-15 06:03:07.124  3669  3669 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-15 06:03:07.124  3669  3669 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-15 06:03:07.124  3669  3669 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-15 06:03:07.124  3669  3669 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
09-15 06:03:07.124  3669  3669 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
09-15 06:03:07.124  3669  3669 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
09-15 06:03:07.124  3669  3669 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
09-15 06:03:07.124  3669  3669 E AndroidRuntime: 	... 8 more
,09-15 06:03:07.132   926  4037 I ActivityManager: Start proc 5667:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
09-15 06:03:07.132  3630  3776 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-15 06:03:07.132  3630  3776 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3630
09-15 06:03:07.132  3630  3776 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-15 06:03:07.132  3630  3776 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-15 06:03:07.132  3630  3776 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-15 06:03:07.132  3630  3776 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-15 06:03:07.132  3630  3776 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-15 06:03:07.132  3630  3776 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-15 06:03:07.132  3630  3776 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-15 06:03:07.132  3630  3776 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-15 06:03:07.132  3630  3776 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-15 06:03:07.132  3630  3776 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-15 06:03:07.132  3630  3776 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-15 06:03:07.132  3630  3776 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-15 06:03:07.140   926  5678 E DropBoxManagerService: Can't write: system_app_crash
09-15 06:03:07.140   926  5678 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop110.tmp: open failed: EROFS (Read-only file system)
09-15 06:03:07.140   926  5678 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-15 06:03:07.140   926  5678 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-15 06:03:07.140   926  5678 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-15 06:03:07.140   926  5678 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-15 06:03:07.140   926  5678 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-15 06:03:07.140   926  5678 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-15 06:03:07.140   926  5678 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-15 06:03:07.140   926  5678 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-15 06:03:07.140   926  5678 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-15 06:03:07.140   926  5678 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-15 06:03:07.140   926  5678 E DropBoxManagerService: 	... 5 more
09-15 06:03:07.142   926  5676 E DropBoxManagerService: Can't write: system_app_crash
09-15 06:03:07.142   926  5676 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop109.tmp: open failed: EROFS (Read-only file system)
09-15 06:03:07.142   926  5676 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-15 06:03:07.142   926  5676 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-15 06:03:07.142   926  5676 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-15 06:03:07.142   926  5676 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-15 06:03:07.142   926  5676 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-15 06:03:07.142   926  5676 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-15 06:03:07.142   926  5676 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-15 06:03:07.142   926  5676 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-15 06:03:07.142   926  5676 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-15 06:03:07.142   926  5676 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-15 06:03:07.142   926  5676 E DropBoxManagerService: 	... 5 more
09-15 06:03:07.148  3020  3020 W Binder_5: type=1400 audit(0.0:131): avc: denied { ioctl } for path="socket:[24384]" dev="sockfs" ino=24384 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-15 06:03:07.148  3020  3020 W Binder_5: type=1400 audit(0.0:132): avc: denied { ioctl } for path="socket:[24384]" dev="sockfs" ino=24384 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-15 06:03:07.152  3020  3020 W Binder_5: type=1400 audit(0.0:133): avc: denied { ioctl } for path="socket:[33072]" dev="sockfs" ino=33072 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-15 06:03:07.152  3020  3020 W Binder_5: type=1400 audit(0.0:134): avc: denied { ioctl } for path="socket:[33072]" dev="sockfs" ino=33072 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-15 06:03:07.149  3502  5658 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
09-15 06:03:07.151  3502  5658 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
09-15 06:03:07.151  3502  5658 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
09-15 06:03:07.153  3502  5658 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
09-15 06:03:07.153  3502  5658 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
09-15 06:03:07.154   926  5682 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
09-15 06:03:07.154  3502  5658 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
09-15 06:03:07.154  3502  5658 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
09-15 06:03:07.155  3502  5658 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
09-15 06:03:07.155  3502  5658 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
09-15 06:03:07.155  3502  5658 I Keyboard.Facilitator.Delight2FileSweeper: run()
09-15 06:03:07.155  3502  5658 I Keyboard.Facilitator.RecurringTaskScheduler: run()
09-15 06:03:07.155  3502  5658 I StatsUtilsManager: startPeriodStatsRecorder() : Success
09-15 06:03:07.155  3502  5658 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
09-15 06:03:07.159   926  5683 E DropBoxManagerService: Can't write: system_app_crash
09-15 06:03:07.159   926  5683 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop112.tmp: open failed: EROFS (Read-only file system)
09-15 06:03:07.159   926  5683 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-15 06:03:07.159   926  5683 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-15 06:03:07.159   926  5683 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-15 06:03:07.159   926  5683 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-15 06:03:07.159   926  5683 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-15 06:03:07.159   926  5683 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-15 06:03:07.159   926  5683 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-15 06:03:07.159   926  5683 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-15 06:03:07.159   926  5683 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-15 06:03:07.159   926  5683 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-15 06:03:07.159   926  5683 E DropBoxManagerService: 	... 5 more
09-15 06:03:07.160   926  3927 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-15 06:03:07.162  3753  5486 W SearchService: Abort, client detached.
09-15 06:03:07.165  3753  3753 I HotwordDetector: Closing mic
09-15 06:03:07.165  3753  5524 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@5fe2c0
09-15 06:03:07.165  3753  5651 E AudioRecord-JNI: Error -4 during AudioRecord native read
09-15 06:03:07.176  3710  4003 W GCoreFlp: No location to return for getLastLocation()
,09-15 06:03:07.192  3710  4003 W GCoreFlp: No location to return for getLastLocation()
,09-15 06:03:07.233   513  5653 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
,09-15 06:03:07.234   513  5653 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
,09-15 06:03:07.237   513  5653 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
09-15 06:03:07.237   513  5653 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
,09-15 06:03:07.238   513  3079 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,09-15 06:03:07.240  3753  5650 I MicroRecognitionRnrImpl: Detection finished
,09-15 06:03:07.241  3753  5525 I MicroRecognitionRnrImpl: Stopping hotword detection.
,09-15 06:03:07.468   384   481 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
