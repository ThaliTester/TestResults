#### Test 9418709470ff331_thali07_Huawei-Nexus 6P Logs


```
--------- beginning of system
,11-22 14:01:17.801   933  3077 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
--------- beginning of main
11-22 14:01:17.821   933  3072 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
11-22 14:01:18.007  4104  4566 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
11-22 14:01:18.283  5696  5696 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-22 14:01:18.289  5696  5696 D AndroidRuntime: CheckJNI is OFF
11-22 14:01:18.320  5696  5696 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-22 14:01:18.356  5696  5696 I Radio-JNI: register_android_hardware_Radio DONE
11-22 14:01:18.371  5696  5696 D AndroidRuntime: Calling main entry com.android.commands.am.Am
11-22 14:01:18.376   933  3252 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
11-22 14:01:18.401  4067  4082 W SearchService: Abort, client detached.
11-22 14:01:18.405  5696  5696 D AndroidRuntime: Shutting down VM
11-22 14:01:18.411  4067  4308 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@79fe088
11-22 14:01:18.411  4067  4067 I HotwordDetector: Closing mic
11-22 14:01:18.411  4067  4335 E AudioRecord-JNI: Error -4 during AudioRecord native read
11-22 14:01:18.427   933  3931 I ActivityManager: Start proc 5705:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
11-22 14:01:18.484   507  4337 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
11-22 14:01:18.485   507  4337 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
11-22 14:01:18.488   507  4337 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
11-22 14:01:18.488   507  4337 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
11-22 14:01:18.489   507  3094 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-22 14:01:18.491  4067  4314 I MicroRecognitionRnrImpl: Stopping hotword detection.
11-22 14:01:18.491  4067  4334 I MicroRecognitionRnrImpl: Detection finished
11-22 14:01:18.532  5705  5705 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
11-22 14:01:18.552  5705  5705 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
11-22 14:01:18.571  5705  5705 I LibraryLoader: Time to load native libraries: 15 ms (timestamps 7718-7733)
11-22 14:01:18.571  5705  5705 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-22 14:01:18.586  5705  5705 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {32c38ea}
11-22 14:01:18.586  5705  5705 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-22 14:01:18.587  5705  5705 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
11-22 14:01:18.590  5705  5705 I BrowserStartupController: Initializing chromium process, singleProcess=true
11-22 14:01:18.590  5705  5705 E SysUtils: ApplicationContext is null in ApplicationStatus
11-22 14:01:18.618  5705  5705 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
11-22 14:01:18.627  5705  5705 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-22 14:01:18.627  5705  5705 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-22 14:01:18.627  5705  5705 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-22 14:01:18.627  5705  5705 I Adreno  : Build Date                       : 12/06/15
11-22 14:01:18.627  5705  5705 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-22 14:01:18.627  5705  5705 I Adreno  : Local Branch                     : mybranch17112971
11-22 14:01:18.627  5705  5705 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-22 14:01:18.627  5705  5705 I Adreno  : Remote Branch                    : NONE
11-22 14:01:18.627  5705  5705 I Adreno  : Reconstruct Branch               : NOTHING
,11-22 14:01:18.657   933   950 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@acab235:true
,11-22 14:01:18.689   406   406 W Binder_2: type=1400 audit(0.0:99): avc: denied { ioctl } for path="socket:[22288]" dev="sockfs" ino=22288 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-22 14:01:18.689   406   406 W Binder_2: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[22288]" dev="sockfs" ino=22288 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-22 14:01:18.700  5705  5705 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-22 14:01:18.710  5705  5705 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-22 14:01:18.735  5705  5742 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-22 14:01:18.732   406   406 W Binder_2: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[32881]" dev="sockfs" ino=32881 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-22 14:01:18.732   406   406 W Binder_2: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[32881]" dev="sockfs" ino=32881 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-22 14:01:18.735  3979  3979 W Binder_A: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[22300]" dev="sockfs" ino=22300 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-22 14:01:18.735  3979  3979 W Binder_A: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[22300]" dev="sockfs" ino=22300 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-22 14:01:18.739  5705  5729 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-22 14:01:18.764  5705  5742 I OpenGLRenderer: Initialized EGL, version 1.4
,11-22 14:01:18.825  3979  3979 W Binder_A: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[30681]" dev="sockfs" ino=30681 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-22 14:01:18.825  3979  3979 W Binder_A: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[30681]" dev="sockfs" ino=30681 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-22 14:01:18.829  3252  3252 W Binder_3: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[30680]" dev="sockfs" ino=30680 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-22 14:01:18.829  3252  3252 W Binder_3: type=1400 audit(0.0:108): avc: denied { ioctl } for path="socket:[30680]" dev="sockfs" ino=30680 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-22 14:01:18.831   933   951 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +422ms
11-22 14:01:18.836  3764  3764 I Keyboard.Facilitator: onFinishInput()
,11-22 14:01:18.875  5705  5705 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5705
,11-22 14:01:18.950  5705  5705 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,11-22 14:01:19.087  5705  5744 D jxcore_app_log: JniHelper::setJavaVM(0xf4efc000), pthread_self() = -586417872
,11-22 14:01:19.093  5705  5744 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-22 14:01:19.093  5705  5744 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-22 14:01:19.093  5705  5744 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-22 14:01:19.093  5705  5744 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-22 14:01:19.093  5705  5744 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,11-22 14:01:19.093  5705  5744 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@40b9550 added. We now have 1 listener(s)
,11-22 14:01:19.096  5705  5744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:D4
11-22 14:01:19.096  5705  5744 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-22 14:01:19.097  5705  5744 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-22 14:01:19.097  5705  5744 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-22 14:01:19.099  5705  5744 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-22 14:01:19.099  5705  5744 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-22 14:01:19.099  5705  5744 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-22 14:01:19.099  5705  5744 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:D4
11-22 14:01:19.099  5705  5744 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-22 14:01:19.099  5705  5744 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-22 14:01:19.099  5705  5744 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-22 14:01:19.099  5705  5744 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-22 14:01:19.099  5705  5744 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-22 14:01:19.099  5705  5744 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-22 14:01:19.099  5705  5744 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-22 14:01:19.099  5705  5744 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-22 14:01:19.099  5705  5744 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-22 14:01:19.099  5705  5744 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
11-22 14:01:19.099  5705  5744 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ceb796f added. We now have 1 listener(s)
11-22 14:01:19.099  5705  5744 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-22 14:01:19.103   933  3073 D WifiService: New client listening to asynchronous messages
,11-22 14:01:19.104  5705  5744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-22 14:01:19.104  5705  5744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
11-22 14:01:19.104  5705  5744 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
11-22 14:01:19.104  5705  5744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
11-22 14:01:19.104  5705  5744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
11-22 14:01:19.104  5705  5744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
11-22 14:01:19.104  5705  5744 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
,11-22 14:01:19.105  5705  5744 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-22 14:01:19.120  5705  5705 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,11-22 14:01:19.233   933  3947 I ActivityManager: Killing 5378:com.android.settings/1000 (adj 15): empty #17
,11-22 14:01:19.260   933  3947 I ActivityManager: Killing 5336:org.codeaurora.ims/1001 (adj 15): empty #18
,11-22 14:01:19.668  5705  5751 W jxcore-log: Initializing JXcore engine
,11-22 14:01:19.668  5705  5751 W jxcore-log: JXcore engine is ready
,11-22 14:01:19.689  5751  5751 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=11887 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,11-22 14:01:19.689  5751  5751 W Thread-61: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[14517]" dev="sockfs" ino=14517 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
11-22 14:01:19.689  5751  5751 W Thread-61: type=1400 audit(0.0:111): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,11-22 14:01:19.689  5751  5751 W Thread-61: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[32856]" dev="sockfs" ino=32856 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,11-22 14:01:19.700  5705  5751 W jxcore-log: Starting JXcore engine
,11-22 14:01:19.751  5705  5751 W jxcore-log: Platform android
11-22 14:01:19.751  5705  5751 W jxcore-log: 
,11-22 14:01:19.751  5705  5751 W jxcore-log: Process ARCH arm
11-22 14:01:19.751  5705  5751 W jxcore-log: 
,11-22 14:01:19.932  5705  5751 I jxcore-log: JXcore Cordova bridge is ready!
11-22 14:01:19.932  5705  5751 I jxcore-log: 
,11-22 14:01:19.932  5705  5751 W jxcore-log: JXcore engine is started
,11-22 14:01:19.942  5705  5744 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,11-22 14:01:19.948  5705  5705 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-22 14:01:20.823   933  3077 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-22 14:01:23.845   933  3077 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-22 14:01:24.967   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:01:25.968   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:01:26.866   933  3077 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-22 14:01:26.969   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:01:27.970   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:01:28.566  4067  5755 W CronetSyncConnectionRcs: Upload content type not set.
,11-22 14:01:28.611  3672  5760 I VacuumService: Vacuum at: now=1479819688611 tag=VacuumService
,11-22 14:01:28.635  3672  5763 D GetConfigurationSnapshotOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, ,
,11-22 14:01:28.670  3672  5761 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,11-22 14:01:28.673  3672  5761 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,11-22 14:01:28.692  3672  5761 W Uploader:  no longer exists, so no auth token.
,11-22 14:01:28.698  3672  5763 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-22 14:01:28.972   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:01:29.010  3672  5764 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-22 14:01:29.161  3672  5761 W Uploader:  no longer exists, so no auth token.
,11-22 14:01:29.169  3672  5763 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-22 14:01:29.241  3672  5764 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-22 14:01:29.402  3672  5763 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-22 14:01:29.498  3672  5764 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-22 14:01:29.574  5705  5751 I jxcore-log: 2016-11-22 13:01:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-22 14:01:29.574  5705  5751 I jxcore-log: 
,11-22 14:01:29.576  5705  5751 I jxcore-log: 2016-11-22 13:01:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-22 14:01:29.576  5705  5751 I jxcore-log: 
,11-22 14:01:29.580  5705  5751 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,11-22 14:01:29.581  5705  5751 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-22 14:01:29.581  5705  5751 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 14:01:29.581  5705  5751 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 14:01:29.581  5705  5751 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-22 14:01:29.581  5705  5751 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-22 14:01:29.581  5705  5751 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-22 14:01:29.581  5705  5751 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-22 14:01:29.581  5705  5751 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-22 14:01:29.581  5705  5751 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-22 14:01:29.582  5705  5751 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-22 14:01:29.583  5705  5751 I jxcore-log: 2016-11-22 13:01:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
11-22 14:01:29.583  5705  5751 I jxcore-log: 
,11-22 14:01:29.585  5705  5751 I jxcore-log: 2016-11-22 13:01:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-22 14:01:29.585  5705  5751 I jxcore-log: 
,11-22 14:01:29.827  5705  5751 I jxcore-log: 2016-11-22 13:01:29 - DEBUG UnitTest_app: 'Running unit tests'
11-22 14:01:29.827  5705  5751 I jxcore-log: 
,11-22 14:01:29.828  5705  5751 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-22 14:01:29.828  5705  5751 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@70b5ef5 added. We now have 2 listener(s)
,11-22 14:01:29.829  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-22 14:01:29.829  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-22 14:01:29.829  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-22 14:01:29.829  5705  5751 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-22 14:01:29.829  5705  5751 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d44448a added. We now have 2 listener(s)
11-22 14:01:29.829  5705  5751 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-22 14:01:29.830  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-22 14:01:29.831  5705  5751 D executeNativeTests: Running unit tests
,11-22 14:01:29.869  5705  5751 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-22 14:01:29.869  5705  5751 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ad08eb added. We now have 3 listener(s)
,11-22 14:01:29.869  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-22 14:01:29.869  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-22 14:01:29.870  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-22 14:01:29.870  5705  5751 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-22 14:01:29.870  5705  5751 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a269648 added. We now have 3 listener(s)
11-22 14:01:29.870  5705  5751 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-22 14:01:29.870  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-22 14:01:29.872  5705  5751 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,11-22 14:01:29.872  5705  5751 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-22 14:01:29.872  5705  5751 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-22 14:01:29.872  5705  5751 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-22 14:01:29.873  5705  5751 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,11-22 14:01:29.873  5705  5751 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-22 14:01:29.873  5705  5751 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-22 14:01:29.873  5705  5751 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-22 14:01:29.873  5705  5751 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-22 14:01:29.873  5705  5751 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-22 14:01:29.873  5705  5751 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 14:01:29.873  5705  5751 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-22 14:01:29.873  5705  5751 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 14:01:29.873  5705  5751 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 14:01:29.874  5705  5751 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-22 14:01:29.874  5705  5751 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-22 14:01:29.874  5705  5751 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ad08eb removed from the list
11-22 14:01:29.874  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:01:29.874  5705  5751 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a269648 removed from the list
11-22 14:01:29.874  5705  5751 D io.jxcore.node.ConnectivityMonitor: stop
,11-22 14:01:29.874  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:29.874  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:29.875  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:29.875  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:29.875  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:29.875  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 14:01:29.875  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 14:01:29.875  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:01:29.875  5705  5751 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a269648 not in the list
11-22 14:01:29.876  5705  5751 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
11-22 14:01:29.876  5705  5751 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 14:01:29.876  5705  5751 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 14:01:29.876  5705  5751 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 14:01:29.876  5705  5751 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 14:01:29.876  5705  5751 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-22 14:01:29.876  5705  5751 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ad08eb not in the list
11-22 14:01:29.876  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:01:29.876  5705  5751 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a269648 not in the list
11-22 14:01:29.876  5705  5751 D io.jxcore.node.ConnectivityMonitor: stop
11-22 14:01:29.876  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:29.876  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:29.877  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:29.877  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:29.877  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:29.877  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 14:01:29.877  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 14:01:29.877  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:01:29.877  5705  5751 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a269648 not in the list
11-22 14:01:29.880  5705  5751 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-22 14:01:29.880  5705  5751 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-22 14:01:29.880  5705  5751 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-22 14:01:29.880  5705  5751 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-22 14:01:29.880  5705  5751 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-22 14:01:29.880  5705  5751 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-22 14:01:29.880  5705  5751 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-22 14:01:29.880  5705  5751 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-22 14:01:29.880  5705  5751 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-22 14:01:29.880  5705  5751 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-22 14:01:29.880  5705  5751 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-22 14:01:29.880  5705  5751 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,11-22 14:01:29.880  5705  5751 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-22 14:01:29.880  5705  5751 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-22 14:01:29.880  5705  5751 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-22 14:01:29.880  5705  5751 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-22 14:01:29.880  5705  5751 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-22 14:01:29.880  5705  5751 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-22 14:01:29.880  5705  5751 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-22 14:01:29.880  5705  5751 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-22 14:01:29.880  5705  5751 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-22 14:01:29.880  5705  5751 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-22 14:01:29.880  5705  5751 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-22 14:01:29.880  5705  5751 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-22 14:01:29.880  5705  5751 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-22 14:01:29.880  5705  5751 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-22 14:01:29.880  5705  5751 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-22 14:01:29.880  5705  5751 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-22 14:01:29.880  5705  5751 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-22 14:01:29.880  5705  5751 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-22 14:01:29.880  5705  5751 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-22 14:01:29.880  5705  5751 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 14:01:29.881  5705  5751 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 14:01:29.881  5705  5751 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 14:01:29.881  5705  5751 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 14:01:29.881  5705  5751 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 14:01:29.881  5705  5751 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ad08eb not in the list
11-22 14:01:29.881  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:01:29.881  5705  5751 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a269648 not in the list
11-22 14:01:29.881  5705  5751 D io.jxcore.node.ConnectivityMonitor: stop
11-22 14:01:29.881  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:29.881  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:29.881  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:29.881  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:29.882  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:29.882  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 14:01:29.882  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 14:01:29.882  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:01:29.882  5705  5751 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a269648 not in the list
11-22 14:01:29.882  5705  5751 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
11-22 14:01:29.883  5705  5751 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-22 14:01:29.883  5705  5751 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-22 14:01:29.899  5705  5751 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-22 14:01:29.899  5705  5751 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 14:01:29.899  5705  5751 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 14:01:29.899  5705  5751 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-22 14:01:29.899  5705  5751 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-22 14:01:29.899  5705  5751 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-22 14:01:29.899  5705  5751 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-22 14:01:29.899  5705  5751 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-22 14:01:29.899  5705  5751 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-22 14:01:29.902  5705  5751 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-22 14:01:29.902  5705  5751 D io.jxcore.node.ConnectivityMonitor: start: OK
11-22 14:01:29.902  5705  5751 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-22 14:01:29.902  5705  5751 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-22 14:01:29.903  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-22 14:01:29.903  5705  5751 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-22 14:01:29.903  5705  5751 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-22 14:01:29.906  5705  5705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-22 14:01:29.909  5705  5705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-22 14:01:29.911  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-22 14:01:29.911  5705  5751 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-22 14:01:29.911  5705  5751 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-22 14:01:29.916  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:29.916  5705  5751 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-22 14:01:29.918  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-22 14:01:29.919  5705  5751 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-22 14:01:29.919  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-22 14:01:29.922  5705  5751 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
11-22 14:01:29.923  5705  5751 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
11-22 14:01:29.923  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:29.923  5705  5751 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-22 14:01:29.924  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-22 14:01:29.924  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-22 14:01:29.924  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-22 14:01:29.924  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:29.925  5705  5751 D BluetoothAdapter: STATE_ON
11-22 14:01:29.927  4731  4963 D BtGatt.GattService: registerClient() - UUID=182bff45-5e94-438f-8278-8cf3c918ef1f
11-22 14:01:29.927  4731  4807 D BtGatt.GattService: onClientRegistered() - UUID=182bff45-5e94-438f-8278-8cf3c918ef1f, clientIf=5
,11-22 14:01:29.928  5705  5716 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-22 14:01:29.930  4731  4745 D BtGatt.GattService: start scan with filters
11-22 14:01:29.936  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-22 14:01:29.936  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:29.936  4731  4810 D BtGatt.ScanManager: handling starting scan
11-22 14:01:29.936  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-22 14:01:29.937  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:29.937  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-22 14:01:29.937  5705  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-22 14:01:29.937  5705  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-22 14:01:29.937  5705  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-22 14:01:29.937  5705  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-22 14:01:29.937  5705  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-22 14:01:29.937  5705  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-22 14:01:29.938  4731  4810 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b705d8d
11-22 14:01:29.938  5705  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-22 14:01:29.938  5705  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-22 14:01:29.938  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-22 14:01:29.938  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:29.941  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:29.941  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-22 14:01:29.942  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:29.942  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:29.942  5705  5705 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-22 14:01:29.942  5705  5751 I io.jxcore.node.ConnectionHelper: start: OK
11-22 14:01:29.945  5705  5705 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-22 14:01:29.945  5705  5705 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-22 14:01:29.945  5705  5705 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-22 14:01:29.945  4731  4807 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-22 14:01:29.945  5705  5705 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-22 14:01:29.946  4731  4807 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 14:01:29.946  4731  4810 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-22 14:01:29.952  4731  4807 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-22 14:01:29.952  4731  4807 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 14:01:29.952  4731  4810 D BtGatt.ScanManager: Starting BLE batch scan
11-22 14:01:29.952  4731  4810 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-22 14:01:29.961  4731  4807 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-22 14:01:29.961  4731  4807 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 14:01:29.967  4731  4807 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-22 14:01:29.967  4731  4807 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 14:01:29.972   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-22 14:01:29.989   933   942 I art     : Background partial concurrent mark sweep GC freed 74824(5MB) AllocSpace objects, 24(584KB) LOS objects, 33% free, 29MB/43MB, paused 1.832ms total 104.591ms
,11-22 14:01:30.448  5705  5705 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
11-22 14:01:30.448  5705  5705 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,11-22 14:01:30.448  5705  5705 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-22 14:01:33.582   933  5507 D NetlinkSocketObserver: NeighborEvent{elapsedMs=172743, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-22 14:01:34.952  5705  5751 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-22 14:01:34.952  5705  5751 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,11-22 14:01:34.952  5705  5751 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,11-22 14:01:34.953  5705  5751 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-22 14:01:34.953  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-22 14:01:34.953  5705  5751 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 14:01:34.953  5705  5751 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-22 14:01:34.954  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-22 14:01:34.954  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:34.955  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-22 14:01:34.955  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-22 14:01:34.957  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
,11-22 14:01:34.958  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
,11-22 14:01:34.959  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:34.959  5705  5751 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,11-22 14:01:34.960  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
,11-22 14:01:34.963  5705  5751 D BluetoothAdapter: STATE_ON
,11-22 14:01:34.965  4731  4745 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-22 14:01:34.966  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-22 14:01:34.967  4731  4810 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-22 14:01:34.967  5705  5751 D BluetoothAdapter: STATE_ON
,11-22 14:01:34.969  4731  4744 D BtGatt.GattService: stopScan() - queue size =1
11-22 14:01:34.970  4731  4731 D BtGatt.ScanManager: awakened up at time 174132
11-22 14:01:34.971  4731  4745 D BtGatt.GattService: unregisterClient() - clientIf=5
11-22 14:01:34.972  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-22 14:01:34.972  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:34.973  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-22 14:01:34.973  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:34.974  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:34.974  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:34.974  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:34.975  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-22 14:01:34.975  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:34.976  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:34.976  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
,11-22 14:01:34.976  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,11-22 14:01:34.976  5705  5751 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-22 14:01:34.979  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-22 14:01:34.979  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:34.982  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:34.982  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-22 14:01:34.983  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:34.983  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:34.983  5705  5751 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 14:01:34.983  5705  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-22 14:01:34.983  5705  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-22 14:01:34.983  5705  5751 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-22 14:01:34.983  5705  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-22 14:01:34.984  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-22 14:01:34.984  5705  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-22 14:01:34.984  5705  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-22 14:01:34.984  5705  5751 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 14:01:34.984  5705  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-22 14:01:34.984  5705  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-22 14:01:34.984  5705  5751 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ad08eb not in the list
11-22 14:01:34.984  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-22 14:01:34.984  5705  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-22 14:01:34.984  5705  5751 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a269648 not in the list
11-22 14:01:34.984  5705  5751 D io.jxcore.node.ConnectivityMonitor: stop
11-22 14:01:34.984  5705  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-22 14:01:34.984  5705  5751 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-22 14:01:34.985  5705  5705 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-22 14:01:34.985  5705  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-22 14:01:34.985  5705  5705 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-22 14:01:34.987  5705  5705 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-22 14:01:34.987  5705  5705 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,11-22 14:01:34.988  5705  5705 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-22 14:01:35.002  4731  4807 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,11-22 14:01:35.002  4731  4807 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 14:01:35.002  4731  4807 D BtGatt.GattService: current time is 174165086871
11-22 14:01:35.003  4731  4807 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -80, 98, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -90, 97, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -92, 80, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -91, 75, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 71, -122, -77, 84, 69, -12, 1, -128, -79, 73, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -86, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-22 14:01:35.006  4731  4807 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-22 14:01:35.006  4731  4807 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-22 14:01:35.007  4731  4807 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-22 14:01:35.007  4731  4807 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
11-22 14:01:35.007  4731  4807 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-22 14:01:35.007  4731  4807 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-22 14:01:35.015  4731  4807 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-22 14:01:35.015  4731  4807 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 14:01:35.015  4731  4810 D BtGatt.ScanManager: stopping BLe Batch
,11-22 14:01:35.022  4731  4807 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-22 14:01:35.022  4731  4807 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 14:01:35.022  4731  4810 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-22 14:01:35.029  4731  4807 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-22 14:01:35.029  4731  4807 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-22 14:01:35.486  5705  5705 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-22 14:01:35.939   933  3077 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-22 14:01:38.966   933  3077 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-22 14:01:39.988  5705  5751 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,11-22 14:01:39.994  5705  5751 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-22 14:01:39.995  5705  5751 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-22 14:01:40.009  5705  5751 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-22 14:01:40.009  5705  5751 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 14:01:40.009  5705  5751 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 14:01:40.009  5705  5751 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-22 14:01:40.009  5705  5751 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-22 14:01:40.009  5705  5751 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-22 14:01:40.009  5705  5751 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-22 14:01:40.009  5705  5751 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-22 14:01:40.009  5705  5751 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-22 14:01:40.015  5705  5751 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-22 14:01:40.016  5705  5751 D io.jxcore.node.ConnectivityMonitor: start: OK
11-22 14:01:40.016  5705  5751 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-22 14:01:40.016  5705  5751 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,11-22 14:01:40.016  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-22 14:01:40.016  5705  5751 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-22 14:01:40.017  5705  5751 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-22 14:01:40.024  5705  5705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-22 14:01:40.026  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-22 14:01:40.027  5705  5751 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-22 14:01:40.027  5705  5751 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-22 14:01:40.031  5705  5705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-22 14:01:40.036  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-22 14:01:40.036  5705  5751 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-22 14:01:40.037  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-22 14:01:40.037  5705  5751 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-22 14:01:40.037  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-22 14:01:40.044  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:40.044  5705  5751 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,11-22 14:01:40.044  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-22 14:01:40.044  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-22 14:01:40.045  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,11-22 14:01:40.045  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:40.046  5705  5751 D BluetoothAdapter: STATE_ON
,11-22 14:01:40.051  4731  4744 D BtGatt.GattService: registerClient() - UUID=eebcb08a-f9b3-494a-bb61-145deae00449
,11-22 14:01:40.052  4731  4807 D BtGatt.GattService: onClientRegistered() - UUID=eebcb08a-f9b3-494a-bb61-145deae00449, clientIf=5
,11-22 14:01:40.052  5705  5752 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-22 14:01:40.053  4731  4963 D BtGatt.GattService: start scan with filters
,11-22 14:01:40.059  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-22 14:01:40.059  4731  4810 D BtGatt.ScanManager: handling starting scan
11-22 14:01:40.059  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:40.059  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-22 14:01:40.059  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:40.060  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-22 14:01:40.060  5705  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,11-22 14:01:40.060  5705  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-22 14:01:40.060  5705  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-22 14:01:40.060  5705  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-22 14:01:40.060  5705  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-22 14:01:40.060  5705  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
,11-22 14:01:40.060  5705  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-22 14:01:40.060  5705  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-22 14:01:40.062  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-22 14:01:40.062  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-22 14:01:40.066  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:40.066  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-22 14:01:40.067  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:40.067  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:40.067  5705  5751 I io.jxcore.node.ConnectionHelper: start: OK
11-22 14:01:40.067  5705  5705 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-22 14:01:40.071  4731  4807 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-22 14:01:40.072  4731  4807 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 14:01:40.072  4731  4810 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-22 14:01:40.074  5705  5705 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-22 14:01:40.074  5705  5705 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-22 14:01:40.074  5705  5705 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-22 14:01:40.074  5705  5705 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-22 14:01:40.075  5705  5751 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 14:01:40.075  5705  5751 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-22 14:01:40.075  5705  5751 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-22 14:01:40.075  5705  5751 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-22 14:01:40.075  5705  5751 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-22 14:01:40.075  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-22 14:01:40.075  5705  5751 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 14:01:40.075  5705  5751 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-22 14:01:40.075  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-22 14:01:40.075  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:40.075  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-22 14:01:40.075  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-22 14:01:40.076  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:40.076  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:40.076  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:40.076  5705  5751 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-22 14:01:40.076  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:40.078  5705  5751 D BluetoothAdapter: STATE_ON
11-22 14:01:40.078  4731  4963 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-22 14:01:40.078  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,11-22 14:01:40.079  5705  5751 D BluetoothAdapter: STATE_ON
11-22 14:01:40.080  4731  4744 D BtGatt.GattService: stopScan() - queue size =1
11-22 14:01:40.080  4731  4807 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-22 14:01:40.080  4731  4807 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 14:01:40.080  4731  4810 D BtGatt.ScanManager: Starting BLE batch scan
11-22 14:01:40.080  4731  4810 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-22 14:01:40.080  4731  4963 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-22 14:01:40.081  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,11-22 14:01:40.081  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:40.081  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,11-22 14:01:40.081  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:40.081  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
,11-22 14:01:40.081  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
,11-22 14:01:40.082  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:40.082  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-22 14:01:40.082  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
,11-22 14:01:40.082  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:40.082  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:40.082  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-22 14:01:40.082  5705  5751 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-22 14:01:40.083  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-22 14:01:40.083  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:40.085  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:40.085  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,11-22 14:01:40.085  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:40.085  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:40.085  5705  5751 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 14:01:40.085  5705  5751 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-22 14:01:40.085  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-22 14:01:40.086  5705  5751 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 14:01:40.086  5705  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-22 14:01:40.086  5705  5751 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ad08eb not in the list
11-22 14:01:40.086  5705  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-22 14:01:40.086  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:01:40.086  5705  5751 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a269648 not in the list
11-22 14:01:40.086  5705  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-22 14:01:40.086  5705  5751 D io.jxcore.node.ConnectivityMonitor: stop
,11-22 14:01:40.086  5705  5751 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-22 14:01:40.086  5705  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-22 14:01:40.086  5705  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,11-22 14:01:40.086  5705  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-22 14:01:40.086  5705  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-22 14:01:40.086  5705  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-22 14:01:40.086  5705  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-22 14:01:40.086  5705  5705 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-22 14:01:40.087  5705  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-22 14:01:40.087  5705  5705 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-22 14:01:40.088  5705  5705 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-22 14:01:40.089  5705  5705 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-22 14:01:40.089  5705  5705 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-22 14:01:40.089  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:40.089  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-22 14:01:40.091  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:40.091  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:40.091  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:40.092  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 14:01:40.092  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 14:01:40.092  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:01:40.092  5705  5751 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a269648 not in the list
11-22 14:01:40.093  5705  5751 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
11-22 14:01:40.094  4731  4807 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-22 14:01:40.094  4731  4807 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 14:01:40.095  5705  5751 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-22 14:01:40.095  5705  5751 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-22 14:01:40.102  4731  4807 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-22 14:01:40.102  4731  4807 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 14:01:40.103  5705  5751 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-22 14:01:40.103  5705  5751 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 14:01:40.103  5705  5751 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 14:01:40.103  5705  5751 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-22 14:01:40.103  5705  5751 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-22 14:01:40.103  5705  5751 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-22 14:01:40.103  5705  5751 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-22 14:01:40.103  5705  5751 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-22 14:01:40.103  5705  5751 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-22 14:01:40.104  4731  4810 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-22 14:01:40.108  5705  5751 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-22 14:01:40.108  5705  5751 D io.jxcore.node.ConnectivityMonitor: start: OK
,11-22 14:01:40.109  5705  5751 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-22 14:01:40.109  5705  5751 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-22 14:01:40.109  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-22 14:01:40.109  5705  5751 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-22 14:01:40.109  5705  5751 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-22 14:01:40.110  4731  4807 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-22 14:01:40.110  4731  4807 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 14:01:40.110  4731  4807 E BtGatt.ContextMap: Context not found for ID 5
11-22 14:01:40.111  5705  5705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-22 14:01:40.115  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-22 14:01:40.115  5705  5751 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-22 14:01:40.115  5705  5751 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-22 14:01:40.116  5705  5705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-22 14:01:40.118  4731  4807 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-22 14:01:40.118  4731  4807 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 14:01:40.119  4731  4810 D BtGatt.ScanManager: stopping BLe Batch
11-22 14:01:40.119  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:40.119  5705  5751 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-22 14:01:40.120  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-22 14:01:40.120  5705  5751 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,11-22 14:01:40.120  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-22 14:01:40.124  4731  4807 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-22 14:01:40.124  4731  4807 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 14:01:40.124  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:40.124  5705  5751 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-22 14:01:40.124  4731  4810 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-22 14:01:40.124  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-22 14:01:40.124  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-22 14:01:40.124  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-22 14:01:40.124  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:40.125  5705  5751 D BluetoothAdapter: STATE_ON
,11-22 14:01:40.127  4731  4744 D BtGatt.GattService: registerClient() - UUID=fc0dd9ca-aad3-4581-870e-4aa579479a06
11-22 14:01:40.127  4731  4807 D BtGatt.GattService: onClientRegistered() - UUID=fc0dd9ca-aad3-4581-870e-4aa579479a06, clientIf=5
11-22 14:01:40.128  5705  5716 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-22 14:01:40.128  4731  4963 D BtGatt.GattService: start scan with filters
11-22 14:01:40.129  4731  4807 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-22 14:01:40.129  4731  4807 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 14:01:40.131  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-22 14:01:40.132  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:40.132  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-22 14:01:40.132  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:40.132  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-22 14:01:40.132  5705  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-22 14:01:40.132  5705  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-22 14:01:40.132  5705  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-22 14:01:40.132  4731  4810 D BtGatt.ScanManager: handling starting scan
11-22 14:01:40.132  5705  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-22 14:01:40.132  5705  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-22 14:01:40.132  5705  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-22 14:01:40.132  5705  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-22 14:01:40.132  5705  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-22 14:01:40.133  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-22 14:01:40.133  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:40.135  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:40.135  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-22 14:01:40.135  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:40.135  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:40.136  5705  5751 I io.jxcore.node.ConnectionHelper: start: OK
11-22 14:01:40.136  5705  5705 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-22 14:01:40.138  5705  5705 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-22 14:01:40.138  5705  5705 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-22 14:01:40.138  4731  4807 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-22 14:01:40.138  5705  5705 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-22 14:01:40.138  4731  4807 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 14:01:40.138  5705  5705 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-22 14:01:40.138  4731  4810 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-22 14:01:40.143  4731  4807 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-22 14:01:40.143  4731  4807 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 14:01:40.144  4731  4810 D BtGatt.ScanManager: Starting BLE batch scan
11-22 14:01:40.144  4731  4810 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-22 14:01:40.153  4731  4807 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-22 14:01:40.153  4731  4807 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-22 14:01:40.158  4731  4807 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-22 14:01:40.158  4731  4807 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-22 14:01:40.640  5705  5705 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
11-22 14:01:40.640  5705  5705 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,11-22 14:01:40.640  5705  5705 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-22 14:01:42.001   933  3077 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-22 14:01:45.025   933  3077 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-22 14:01:45.136  5705  5751 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-22 14:01:45.137  5705  5751 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-22 14:01:45.137  5705  5751 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,11-22 14:01:45.137  5705  5751 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-22 14:01:45.137  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-22 14:01:45.137  5705  5751 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-22 14:01:45.138  5705  5751 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-22 14:01:45.138  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-22 14:01:45.138  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
,11-22 14:01:45.138  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-22 14:01:45.138  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-22 14:01:45.139  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
,11-22 14:01:45.139  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:45.139  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:45.139  5705  5751 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-22 14:01:45.139  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:45.142  5705  5751 D BluetoothAdapter: STATE_ON
11-22 14:01:45.144  4731  4745 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-22 14:01:45.145  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-22 14:01:45.146  4731  4810 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-22 14:01:45.147  5705  5751 D BluetoothAdapter: STATE_ON
11-22 14:01:45.149  4731  4744 D BtGatt.GattService: stopScan() - queue size =1
,11-22 14:01:45.152  4731  4963 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-22 14:01:45.153  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-22 14:01:45.154  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:45.154  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-22 14:01:45.155  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:45.155  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
,11-22 14:01:45.155  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:45.155  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:45.156  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-22 14:01:45.156  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
,11-22 14:01:45.156  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:45.156  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:45.156  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-22 14:01:45.156  5705  5751 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-22 14:01:45.157  4731  4731 D BtGatt.ScanManager: awakened up at time 184319
11-22 14:01:45.159  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-22 14:01:45.160  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-22 14:01:45.164  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:45.164  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-22 14:01:45.164  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:45.164  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-22 14:01:45.165  5705  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-22 14:01:45.165  5705  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-22 14:01:45.165  5705  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-22 14:01:45.165  5705  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-22 14:01:45.165  5705  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-22 14:01:45.166  5705  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-22 14:01:45.166  5705  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-22 14:01:45.166  5705  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
,11-22 14:01:45.166  5705  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-22 14:01:45.166  5705  5705 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-22 14:01:45.166  5705  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
,11-22 14:01:45.167  5705  5705 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-22 14:01:45.169  5705  5705 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-22 14:01:45.169  5705  5705 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-22 14:01:45.170  5705  5705 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-22 14:01:45.184  4731  4807 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,11-22 14:01:45.184  4731  4807 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 14:01:45.185  4731  4807 D BtGatt.GattService: current time is 184346631846
,11-22 14:01:45.185  4731  4807 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -81, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -80, 85, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -79, 83, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -79, 79, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -79, 77, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -89, 22, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-22 14:01:45.186  4731  4807 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-22 14:01:45.186  4731  4807 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-22 14:01:45.186  4731  4807 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,11-22 14:01:45.187  4731  4807 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-22 14:01:45.187  4731  4807 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-22 14:01:45.187  4731  4807 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,11-22 14:01:45.197  4731  4807 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-22 14:01:45.197  4731  4807 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 14:01:45.197  4731  4810 D BtGatt.ScanManager: stopping BLe Batch
,11-22 14:01:45.207  4731  4807 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-22 14:01:45.207  4731  4807 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 14:01:45.207  4731  4810 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-22 14:01:45.216  4731  4807 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-22 14:01:45.216  4731  4807 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-22 14:01:45.668  5705  5705 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-22 14:01:45.668  5705  5705 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 14:01:45.668  5705  5705 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-22 14:01:48.059   933  3077 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-22 14:01:49.973   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:01:50.166  5705  5751 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-22 14:01:50.166  5705  5751 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 14:01:50.167  5705  5751 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-22 14:01:50.168  5705  5751 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 14:01:50.168  5705  5751 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-22 14:01:50.168  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-22 14:01:50.168  5705  5751 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 14:01:50.169  5705  5751 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ad08eb not in the list
11-22 14:01:50.169  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-22 14:01:50.169  5705  5751 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a269648 not in the list
11-22 14:01:50.169  5705  5751 D io.jxcore.node.ConnectivityMonitor: stop
,11-22 14:01:50.169  5705  5751 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-22 14:01:50.173  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
,11-22 14:01:50.173  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-22 14:01:50.177  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-22 14:01:50.177  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:50.177  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:50.177  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 14:01:50.177  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-22 14:01:50.178  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:01:50.178  5705  5751 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a269648 not in the list
11-22 14:01:50.179  5705  5751 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,11-22 14:01:50.181  5705  5751 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 14:01:50.181  5705  5751 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 14:01:50.181  5705  5751 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 14:01:50.181  5705  5751 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 14:01:50.182  5705  5751 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 14:01:50.182  5705  5751 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ad08eb not in the list
11-22 14:01:50.182  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:01:50.182  5705  5751 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a269648 not in the list
11-22 14:01:50.182  5705  5751 D io.jxcore.node.ConnectivityMonitor: stop
11-22 14:01:50.183  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:50.183  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:50.187  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-22 14:01:50.188  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-22 14:01:50.188  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-22 14:01:50.188  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-22 14:01:50.188  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-22 14:01:50.188  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:01:50.188  5705  5751 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a269648 not in the list
11-22 14:01:50.190  5705  5751 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,11-22 14:01:50.190  5705  5751 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 14:01:50.190  5705  5751 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 14:01:50.191  5705  5751 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-22 14:01:50.191  5705  5751 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 14:01:50.191  5705  5751 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-22 14:01:50.191  5705  5751 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ad08eb not in the list
,11-22 14:01:50.191  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-22 14:01:50.191  5705  5751 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a269648 not in the list
11-22 14:01:50.191  5705  5751 D io.jxcore.node.ConnectivityMonitor: stop
11-22 14:01:50.191  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
,11-22 14:01:50.192  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:50.194  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-22 14:01:50.196  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-22 14:01:50.196  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-22 14:01:50.197  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 14:01:50.197  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-22 14:01:50.198  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:01:50.198  5705  5751 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a269648 not in the list
11-22 14:01:50.199  5705  5751 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,11-22 14:01:50.199  5705  5751 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 14:01:50.200  5705  5751 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 14:01:50.200  5705  5751 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 14:01:50.200  5705  5751 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 14:01:50.200  5705  5751 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 14:01:50.200  5705  5751 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ad08eb not in the list
11-22 14:01:50.200  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:01:50.200  5705  5751 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a269648 not in the list
11-22 14:01:50.200  5705  5751 D io.jxcore.node.ConnectivityMonitor: stop
11-22 14:01:50.201  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:50.201  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-22 14:01:50.203  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:50.203  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:50.203  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:50.203  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 14:01:50.203  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 14:01:50.203  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-22 14:01:50.203  5705  5751 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a269648 not in the list
11-22 14:01:50.205  5705  5751 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
11-22 14:01:50.205  5705  5751 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 14:01:50.205  5705  5751 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-22 14:01:50.205  5705  5751 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 14:01:50.205  5705  5751 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 14:01:50.205  5705  5751 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 14:01:50.206  5705  5751 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ad08eb not in the list
11-22 14:01:50.206  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-22 14:01:50.206  5705  5751 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a269648 not in the list
11-22 14:01:50.206  5705  5751 D io.jxcore.node.ConnectivityMonitor: stop
11-22 14:01:50.206  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:50.206  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-22 14:01:50.209  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:50.209  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:50.209  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:50.209  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-22 14:01:50.209  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 14:01:50.209  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:01:50.209  5705  5751 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a269648 not in the list
11-22 14:01:50.210  5705  5751 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,11-22 14:01:50.210  5705  5751 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-22 14:01:50.210  5705  5751 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-22 14:01:50.211  5705  5751 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-22 14:01:50.211  5705  5751 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-22 14:01:50.211  5705  5751 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-22 14:01:50.211  5705  5751 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-22 14:01:50.211  5705  5751 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-22 14:01:50.211  5705  5751 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-22 14:01:50.211  5705  5751 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 14:01:50.211  5705  5751 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 14:01:50.212  5705  5751 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 14:01:50.212  5705  5751 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 14:01:50.212  5705  5751 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-22 14:01:50.212  5705  5751 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ad08eb not in the list
11-22 14:01:50.212  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:01:50.212  5705  5751 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a269648 not in the list
11-22 14:01:50.212  5705  5751 D io.jxcore.node.ConnectivityMonitor: stop
,11-22 14:01:50.212  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:50.212  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:50.214  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:50.214  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:50.214  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:50.214  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 14:01:50.214  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 14:01:50.215  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:01:50.215  5705  5751 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a269648 not in the list
11-22 14:01:50.215  5705  5751 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-22 14:01:50.216  5705  5751 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,11-22 14:01:50.216  5705  5751 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-22 14:01:50.226  5705  5751 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-22 14:01:50.226  5705  5751 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
11-22 14:01:50.226  5705  5751 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-22 14:01:50.226  5705  5751 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-22 14:01:50.226  5705  5751 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-22 14:01:50.227  5705  5751 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,11-22 14:01:50.227  5705  5751 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-22 14:01:50.227  5705  5751 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-22 14:01:50.227  5705  5751 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-22 14:01:50.227  5705  5751 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-22 14:01:50.227  5705  5751 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-22 14:01:50.227  5705  5751 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-22 14:01:50.227  5705  5751 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,11-22 14:01:50.227  5705  5751 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-22 14:01:50.227  5705  5751 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-22 14:01:50.227  5705  5751 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-22 14:01:50.227  5705  5751 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-22 14:01:50.228  5705  5751 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-22 14:01:50.228  5705  5751 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-22 14:01:50.228  5705  5751 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-22 14:01:50.228  5705  5751 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,11-22 14:01:50.228  5705  5751 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-22 14:01:50.229  5705  5751 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-22 14:01:50.229  5705  5751 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-22 14:01:50.229  5705  5751 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-22 14:01:50.229  5705  5751 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-22 14:01:50.229  5705  5751 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-22 14:01:50.229  5705  5751 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,11-22 14:01:50.229  5705  5751 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-22 14:01:50.229  5705  5751 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-22 14:01:50.229  5705  5751 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-22 14:01:50.229  5705  5751 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-22 14:01:50.229  5705  5751 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
11-22 14:01:50.229  5705  5751 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-22 14:01:50.230  5705  5751 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
11-22 14:01:50.230  5705  5751 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,11-22 14:01:50.230  5705  5751 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-22 14:01:50.230  5705  5751 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
11-22 14:01:50.230  5705  5751 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-22 14:01:50.230  5705  5751 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-22 14:01:50.230  5705  5751 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,11-22 14:01:50.234  5705  5751 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,11-22 14:01:50.235  5705  5751 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
11-22 14:01:50.235  5705  5751 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,11-22 14:01:50.236  5705  5751 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
11-22 14:01:50.236  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
11-22 14:01:50.236  5705  5751 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
11-22 14:01:50.236  5705  5751 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-22 14:01:50.237  5705  5751 E io.jxcore.node.ConnectionHelper: connect: Callback is null
11-22 14:01:50.237  5705  5769 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 126)
11-22 14:01:50.237  5705  5769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
11-22 14:01:50.237  5705  5769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
11-22 14:01:50.237  5705  5769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
11-22 14:01:50.238  5705  5751 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 14:01:50.238  5705  5751 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-22 14:01:50.239  5705  5751 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 14:01:50.239  5705  5751 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 14:01:50.239  5705  5751 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-22 14:01:50.239  5705  5769 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
11-22 14:01:50.239  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
11-22 14:01:50.240  5705  5769 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-22 14:01:50.240  5705  5751 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ad08eb not in the list
11-22 14:01:50.240  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:01:50.241  5705  5751 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a269648 not in the list
11-22 14:01:50.241  5705  5751 D io.jxcore.node.ConnectivityMonitor: stop
11-22 14:01:50.241  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:50.241  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:50.241  5705  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 126
11-22 14:01:50.241  5705  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close
11-22 14:01:50.241  5705  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 126)
11-22 14:01:50.241  5705  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 126)
11-22 14:01:50.242  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:50.243  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:50.243  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:50.243  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 14:01:50.243  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 14:01:50.243  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:01:50.243  5705  5769 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, socket closed
11-22 14:01:50.243  5705  5751 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a269648 not in the list
11-22 14:01:50.243  5705  5769 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
11-22 14:01:50.243  5705  5769 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 126)
11-22 14:01:50.239  4963  4963 W Binder_4: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[35855]" dev="sockfs" ino=35855 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-22 14:01:50.244  5705  5751 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
11-22 14:01:50.245  5705  5751 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 14:01:50.245  5705  5751 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 14:01:50.245  5705  5751 V i,o.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 14:01:50.239  4963  4963 W Binder_4: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[35855]" dev="sockfs" ino=35855 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-22 14:01:50.246  5705  5751 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 14:01:50.246  5705  5751 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 14:01:50.246  5705  5751 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ad08eb not in the list
11-22 14:01:50.246  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:01:50.246  5705  5751 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a269648 not in the list
11-22 14:01:50.246  5705  5751 D io.jxcore.node.ConnectivityMonitor: stop
11-22 14:01:50.246  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:50.247  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:50.248  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:50.248  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:50.248  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:50.248  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 14:01:50.248  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 14:01:50.248  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:01:50.248  5705  5751 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a269648 not in the list
11-22 14:01:50.249  5705  5751 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
11-22 14:01:50.249  5705  5751 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 14:01:50.249  5705  5751 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 14:01:50.250  5705  5751 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 14:01:50.250  5705  5751 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 14:01:50.250  5705  5751 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-22 14:01:50.250  5705  5751 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ad08eb not in the list
11-22 14:01:50.250  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:01:50.250  5705  5751 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a269648 not in the list
11-22 14:01:50.250  5705  5751 D io.jxcore.node.ConnectivityMonitor: stop
11-22 14:01:50.250  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:50.250  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-22 14:01:50.252  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:50.252  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:50.252  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-22 14:01:50.252  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 14:01:50.252  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 14:01:50.252  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:01:50.252  5705  5751 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a269648 not in the list
,11-22 14:01:50.253  5705  5751 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
11-22 14:01:50.253  5705  5751 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
11-22 14:01:50.253  5705  5751 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-22 14:01:50.253  5705  5751 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
11-22 14:01:50.253  5705  5751 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-22 14:01:50.253  5705  5751 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
11-22 14:01:50.254  5705  5751 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-22 14:01:50.254  5705  5751 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
11-22 14:01:50.254  5705  5751 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-22 14:01:50.254  5705  5751 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
11-22 14:01:50.254  5705  5751 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,11-22 14:01:50.254  5705  5751 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
11-22 14:01:50.254  5705  5751 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 14:01:50.254  5705  5751 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 14:01:50.254  5705  5751 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 14:01:50.255  5705  5751 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 14:01:50.255  5705  5751 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 14:01:50.255  5705  5751 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ad08eb not in the list
11-22 14:01:50.255  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:01:50.255  5705  5751 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a269648 not in the list
11-22 14:01:50.255  5705  5751 D io.jxcore.node.ConnectivityMonitor: stop
11-22 14:01:50.255  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
,11-22 14:01:50.255  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-22 14:01:50.256  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:50.257  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:50.257  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:50.257  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-22 14:01:50.257  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 14:01:50.257  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:01:50.257  5705  5751 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a269648 not in the list
11-22 14:01:50.258  5705  5751 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 14:01:50.258  5705  5751 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 14:01:50.258  5705  5751 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ad08eb not in the list
11-22 14:01:50.258  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:01:50.258  5705  5751 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a269648 not in the list
11-22 14:01:50.258  5705  5751 D io.jxcore.node.ConnectivityMonitor: stop
,11-22 14:01:50.974   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:01:51.088   933  3077 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-22 14:01:51.976   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:01:52.977   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:01:53.048   933  5507 D NetlinkSocketObserver: NeighborEvent{elapsedMs=192210, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-22 14:01:53.978   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:01:54.978   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-22 14:01:55.259  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-22 14:01:55.259  5705  5751 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a269648 not in the list
,11-22 14:01:55.259  5705  5751 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-22 14:01:55.259  5705  5751 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-22 14:01:55.260  5705  5751 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ad08eb not in the list
11-22 14:01:55.260  5705  5751 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-22 14:01:55.260  5705  5751 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 14:01:55.260  5705  5751 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 14:01:55.260  5705  5751 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 14:01:55.261  5705  5751 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-22 14:01:55.261  5705  5751 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ad08eb not in the list
11-22 14:01:55.261  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:01:55.261  5705  5751 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a269648 not in the list
11-22 14:01:55.261  5705  5751 D io.jxcore.node.ConnectivityMonitor: stop
,11-22 14:01:55.262  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:55.262  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:55.265  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:55.266  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-22 14:01:55.266  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:55.266  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 14:01:55.266  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-22 14:01:55.266  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:01:55.266  5705  5751 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a269648 not in the list
11-22 14:01:55.269  5705  5751 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-22 14:01:55.270  5705  5751 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-22 14:01:55.270  5705  5751 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-22 14:01:55.275  5705  5751 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-22 14:01:55.276  5705  5751 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-22 14:01:55.277  5705  5751 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-22 14:01:55.277  5705  5751 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-22 14:01:55.278  5705  5751 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-22 14:01:55.278  5705  5705 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,11-22 14:01:55.278  5705  5751 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-22 14:01:55.278  5705  5771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-22 14:01:55.278  5705  5751 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 14:01:55.278  5705  5751 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,11-22 14:01:55.279  5705  5751 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-22 14:01:55.279  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-22 14:01:55.279  5705  5751 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-22 14:01:55.279  5705  5771 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-22 14:01:55.280  5705  5751 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,11-22 14:01:55.280  5705  5751 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-22 14:01:55.280  5705  5751 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ad08eb not in the list
11-22 14:01:55.279  4744  4744 W Binder_1: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[35861]" dev="sockfs" ino=35861 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-22 14:01:55.279  4744  4744 W Binder_1: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[35861]" dev="sockfs" ino=35861 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-22 14:01:55.280  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-22 14:01:55.280  5705  5705 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-22 14:01:55.280  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-22 14:01:55.281  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:55.281  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-22 14:01:55.281  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-22 14:01:55.281  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:55.284  5705  5771 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,11-22 14:01:55.284  5705  5771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-22 14:01:55.284  5705  5771 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-22 14:01:55.284  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-22 14:01:55.284  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-22 14:01:55.284  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:55.284  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-22 14:01:55.285  5705  5751 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a269648 not in the list
11-22 14:01:55.285  5705  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-22 14:01:55.285  5705  5751 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-22 14:01:55.285  5705  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-22 14:01:55.285  5705  5751 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-22 14:01:55.285  5705  5705 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-22 14:01:55.285  5705  5751 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 14:01:55.285  5705  5751 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-22 14:01:55.285  5705  5705 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-22 14:01:55.285  5705  5751 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-22 14:01:55.285  5705  5751 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ad08eb not in the list
,11-22 14:01:55.285  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:01:55.286  5705  5751 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a269648 not in the list
,11-22 14:01:55.286  5705  5751 D io.jxcore.node.ConnectivityMonitor: stop
11-22 14:01:55.286  5705  5705 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-22 14:01:55.286  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:55.286  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:55.288  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:55.288  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:55.288  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:55.288  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 14:01:55.288  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-22 14:01:55.289  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:01:55.289  5705  5751 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a269648 not in the list
11-22 14:01:55.290  5705  5751 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
11-22 14:01:55.291  5705  5751 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-22 14:01:55.291  5705  5751 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,11-22 14:01:55.291  5705  5751 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-22 14:01:55.292  5705  5751 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-22 14:01:55.292  5705  5751 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-22 14:01:55.292  5705  5751 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 14:01:55.292  5705  5751 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 14:01:55.292  5705  5751 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-22 14:01:55.292  5705  5751 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 14:01:55.292  5705  5751 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ad08eb not in the list
11-22 14:01:55.292  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-22 14:01:55.292  5705  5751 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a269648 not in the list
11-22 14:01:55.293  5705  5751 D io.jxcore.node.ConnectivityMonitor: stop
11-22 14:01:55.293  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:55.293  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:55.295  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:55.295  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-22 14:01:55.295  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:55.295  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 14:01:55.295  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 14:01:55.295  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-22 14:01:55.296  5705  5751 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a269648 not in the list
,11-22 14:01:55.302  5705  5751 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-22 14:01:55.302  5705  5751 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 14:01:55.302  5705  5751 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 14:01:55.302  5705  5751 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 14:01:55.302  5705  5751 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 14:01:55.302  5705  5751 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ad08eb not in the list
,11-22 14:01:55.302  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:01:55.302  5705  5751 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a269648 not in the list
11-22 14:01:55.302  5705  5751 D io.jxcore.node.ConnectivityMonitor: stop
11-22 14:01:55.302  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:55.302  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:55.304  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-22 14:01:55.304  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:55.304  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:55.304  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 14:01:55.304  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 14:01:55.304  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:01:55.304  5705  5751 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a269648 not in the list
,11-22 14:01:55.306  5705  5751 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 14:01:55.306  5705  5751 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 14:01:55.306  5705  5751 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 14:01:55.306  5705  5751 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 14:01:55.307  5705  5751 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 14:01:55.307  5705  5751 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ad08eb not in the list
,11-22 14:01:55.307  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:01:55.307  5705  5751 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a269648 not in the list
11-22 14:01:55.307  5705  5751 D io.jxcore.node.ConnectivityMonitor: stop
11-22 14:01:55.307  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:55.307  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-22 14:01:55.308  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-22 14:01:55.309  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:55.309  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:01:55.309  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 14:01:55.309  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 14:01:55.309  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:01:55.309  5705  5751 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a269648 not in the list
,11-22 14:01:55.310  5705  5751 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
11-22 14:01:55.310  5705  5751 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-22 14:01:55.310  5705  5751 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
11-22 14:01:55.310  5705  5751 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-22 14:01:55.310  5705  5751 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
11-22 14:01:55.311  5705  5751 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,11-22 14:01:55.313  5705  5751 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-22 14:01:55.313  5705  5751 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
11-22 14:01:55.314  5705  5751 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
11-22 14:01:55.314  5705  5751 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-22 14:01:55.314  5705  5751 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
11-22 14:01:55.314  5705  5751 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,11-22 14:01:55.314  5705  5751 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
11-22 14:01:55.314  5705  5751 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,11-22 14:01:55.315  5705  5751 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
11-22 14:01:55.315  5705  5751 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
11-22 14:01:55.315  5705  5751 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
11-22 14:01:55.316  5705  5751 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
11-22 14:01:55.316  5705  5751 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
,11-22 14:01:55.316  5705  5751 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
11-22 14:01:55.317  5705  5751 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-22 14:01:55.317  5705  5751 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@aa10051 added. We now have 3 listener(s)
11-22 14:01:55.317  5705  5751 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-22 14:01:55.319  5705  5751 D BluetoothAdapter: enable(): BT is already enabled..!
,11-22 14:01:55.320   933  3252 D WifiService: setWifiEnabled: true pid=5705, uid=10077
11-22 14:01:55.320   933  3252 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-22 14:01:55.370  4731  4932 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
11-22 14:01:55.370  4731  4952 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
,11-22 14:01:55.785  5705  5705 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-22 14:01:57.825   933  3072 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-22 14:02:00.325  5705  5751 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-22 14:02:00.326  5705  5751 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@44c00b6 added. We now have 4 listener(s)
11-22 14:02:00.326  5705  5751 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-22 14:02:00.338  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-22 14:02:00.339  5705  5751 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@44c00b6 removed from the list
,11-22 14:02:00.339  5705  5751 D io.jxcore.node.ConnectivityMonitor: stop
,11-22 14:02:00.340  5705  5751 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-22 14:02:00.342  5705  5751 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f57f1b7 added. We now have 4 listener(s)
,11-22 14:02:00.343  5705  5751 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-22 14:02:00.346  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-22 14:02:00.346  5705  5751 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f57f1b7 removed from the list
,11-22 14:02:00.347  5705  5751 D io.jxcore.node.ConnectivityMonitor: stop
,11-22 14:02:00.348  5705  5751 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-22 14:02:00.348  5705  5751 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ea1dd24 added. We now have 4 listener(s)
,11-22 14:02:00.348  5705  5751 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-22 14:02:00.353   933   944 D WifiService: setWifiEnabled: false pid=5705, uid=10077
11-22 14:02:00.353   933   944 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-22 14:02:00.363   933  3072 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,11-22 14:02:00.363   933  3072 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-22 14:02:00.363   933  3072 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-22 14:02:00.363   933  3072 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-22 14:02:00.368  4731  4803 D BluetoothAdapterState: Current state: ON, message: 23
11-22 14:02:00.368  4731  4803 D BluetoothAdapterProperties: Setting state to 13
11-22 14:02:00.368  4731  4803 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-22 14:02:00.371  4731  4803 D BluetoothAdapterProperties: onBluetoothDisable()
,11-22 14:02:00.372  5705  5751 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-22 14:02:00.372  5705  5751 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-22 14:02:00.374  4731  4803 I BluetoothAdapterState: Entering PendingCommandState
11-22 14:02:00.375   933  5508 D DhcpClient: Clearing IP address
11-22 14:02:00.375   502   927 D CommandListener: Clearing all IP addresses on wlan0
,11-22 14:02:00.375  4731  4731 D BluetoothMapService: onReceive
11-22 14:02:00.375  4731  4731 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-22 14:02:00.375  4731  4731 D BluetoothMapService: STATE_TURNING_OFF
11-22 14:02:00.376  4731  4731 D BluetoothMapService: MAP Service closeService in
11-22 14:02:00.376  4731  4731 D BluetoothMapMasInstance0: MAP Service shutdown
11-22 14:02:00.376  4731  4731 D ObexServerSockets0: shutdown(block = true)
11-22 14:02:00.377  4731  4731 D ObexServerSockets0: shutdown called from another thread - interrupt().
,11-22 14:02:00.377  4731  4731 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-22 14:02:00.377  4731  4965 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-22 14:02:00.378  4731  4952 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-22 14:02:00.378  4731  4964 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,11-22 14:02:00.384   502   927 D CommandListener: Setting iface cfg
,11-22 14:02:00.385  4731  4731 I BtOppRfcommListener: stopping Accept Thread
11-22 14:02:00.385  4731  5399 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-22 14:02:00.386  4731  5399 I BtOppRfcommListener: BluetoothSocket listen thread finished
,11-22 14:02:00.390  3672  5562 V NativeCrypto: Read error: ssl=0x7f72802000: I/O error during system call, Connection timed out
,11-22 14:02:00.391  3672  5562 V NativeCrypto: SSL shutdown failed: ssl=0x7f72802000: I/O error during system call, Broken pipe
11-22 14:02:00.393   933  3931 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
11-22 14:02:00.394   933  5506 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
11-22 14:02:00.395   933   946 I ActivityManager: Start proc 5775:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
11-22 14:02:00.396   933  5506 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,11-22 14:02:00.396   933  3077 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
11-22 14:02:00.396   933  3077 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
11-22 14:02:00.397  4731  4807 D BluetoothAdapterProperties: Scan Mode:20
11-22 14:02:00.397  4731  4803 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,11-22 14:02:00.397   933  3077 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
11-22 14:02:00.401  4731  4731 D HeadsetService: Received stop request...Stopping profile...
11-22 14:02:00.401   933  3077 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
11-22 14:02:00.401   933  3077 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
11-22 14:02:00.403   532   532 E Parcel  : Reading a NULL string not supported here.
11-22 14:02:00.405   933   933 D BluetoothHeadset: Proxy object disconnected
11-22 14:02:00.405  3227  3241 D BluetoothHeadset: Proxy object disconnected
,11-22 14:02:00.406   933   933 D BluetoothHeadset: Proxy object disconnected
11-22 14:02:00.406  4731  4731 D A2dpService: Received stop request...Stopping profile...
11-22 14:02:00.406  3891  4093 D BluetoothHeadset: Proxy object disconnected
11-22 14:02:00.406   933   933 D BluetoothHeadset: Proxy object disconnected
,11-22 14:02:00.407  4731  4958 D A2dpStateMachine: Exit Disconnected: -1
11-22 14:02:00.408  5705  5751 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-22 14:02:00.409  5705  5751 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-22 14:02:00.409  5705  5751 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 14:02:00.409  5705  5751 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 14:02:00.409  5705  5751 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-22 14:02:00.409  5705  5751 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-22 14:02:00.409  5705  5751 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-22 14:02:00.409  5705  5751 V io.jxcore.node.ConnectivityMonitor:     - SSID name: <unknown ssid>
11-22 14:02:00.409  5705  5751 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-22 14:02:00.409  5705  5751 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-22 14:02:00.410   933   933 D RttService: SCAN_AVAILABLE : 1
11-22 14:02:00.410   933  3180 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
11-22 14:02:00.410   933   933 D BluetoothA2dp: Proxy object disconnected
11-22 14:02:00.411   933  3077 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,11-22 14:02:00.411  4731  4731 V BluetoothAdapterState: isTurningOff()=true
11-22 14:02:00.411  4731  4731 V BluetoothAdapterState: isTurningOn()=false
11-22 14:02:00.411  5705  5751 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-22 14:02:00.411  4731  4731 V BluetoothAdapterState: isBleTurningOn()=false
11-22 14:02:00.411  5705  5751 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: <unknown ssid>
11-22 14:02:00.411  4731  4731 V BluetoothAdapterState: isBleTurningOff()=false
11-22 14:02:00.411  5705  5751 D io.jxcore.node.ConnectivityMonitor: start: OK
11-22 14:02:00.412  3867  3983 W QCNEJ   : |CORE| network lost: 100
,11-22 14:02:00.413  3867  3983 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,11-22 14:02:00.413   933  5509 D DhcpClient: Receive thread stopped
11-22 14:02:00.415  4731  4731 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-22 14:02:00.415  5705  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-22 14:02:00.415  4731  4731 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-22 14:02:00.415  5705  5705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-22 14:02:00.415  5705  5705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 14:02:00.415  5705  5705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 14:02:00.415  5705  5705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-22 14:02:00.415  5705  5705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-22 14:02:00.415  5705  5705 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-22 14:02:00.415  5705  5705 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-22 14:02:00.415  5705  5705 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-22 14:02:00.415  5705  5705 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-22 14:02:00.415  4731  4807 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-22 14:02:00.415  4731  4932 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-22 14:02:00.415  4731  4932 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-22 14:02:00.415  4731  4932 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-22 14:02:00.415  4731  4807 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-22 14:02:00.416  4731  4731 D HidService: Received stop request...Stopping profile...
11-22 14:02:00.416  4731  4731 D HidService: Stopping Bluetooth HidService
11-22 14:02:00.416  5705  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-22 14:02:00.416  5705  5705 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-22 14:02:00.417  4731  4731 D HealthService: Received stop request...Stopping profile...
,11-22 14:02:00.419  5705  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-22 14:02:00.419  5705  5705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-22 14:02:00.419  5705  5705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 14:02:00.419  5705  5705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 14:02:00.419  5705  5705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-22 14:02:00.419  5705  5705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-22 14:02:00.419  5705  5705 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-22 14:02:00.419  5705  5705 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-22 14:02:00.419  5705  5705 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-22 14:02:00.419  5705  5705 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-22 14:02:00.419  4731  4731 D PanService: Received stop request...Stopping profile...
11-22 14:02:00.420  4731  4731 V BluetoothAdapterState: isTurningOff()=true
11-22 14:02:00.421  5705  5705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-22 14:02:00.422  4731  4731 V BluetoothAdapterState: isTurningOn()=false
11-22 14:02:00.422  4731  4731 V BluetoothAdapterState: isBleTurningOn()=false
11-22 14:02:00.422  4731  4731 V BluetoothAdapterState: isBleTurningOff()=false
11-22 14:02:00.423  4731  4731 D BluetoothMapService: Received stop request...Stopping profile...
11-22 14:02:00.423  4731  4731 D BluetoothMapService: stop()
,11-22 14:02:00.424  4731  4731 D BluetoothMapAppObserver: deinitObservers()
,11-22 14:02:00.424  4731  4731 D BluetoothMapAppObserver: removeReceiver()
11-22 14:02:00.425  3227  3227 D HeadsetProfile: Bluetooth service disconnected
11-22 14:02:00.425  3227  3227 D BluetoothA2dp: Proxy object disconnected
11-22 14:02:00.426  3227  3227 D BluetoothInputDevice: Proxy object disconnected
11-22 14:02:00.426  3227  3227 D HidProfile: Bluetooth service disconnected
11-22 14:02:00.426  3227  3227 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-22 14:02:00.426  3227  3227 D PanProfile: Bluetooth service disconnected
11-22 14:02:00.427  4731  4932 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-22 14:02:00.427  4731  4932 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-22 14:02:00.427  4731  4932 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,11-22 14:02:00.427  4731  4731 D SapService: Received stop request...Stopping profile...
,11-22 14:02:00.427  4731  4932 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,11-22 14:02:00.427  4731  4731 V SapService: stop()
11-22 14:02:00.427  4731  4932 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-22 14:02:00.427  4731  4932 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-22 14:02:00.427  4731  4807 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-22 14:02:00.428   933  3072 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
11-22 14:02:00.428  4731  4731 V BluetoothAdapterState: isTurningOff()=true
11-22 14:02:00.428  4731  4731 V BluetoothAdapterState: isTurningOn()=false
11-22 14:02:00.428  4731  4731 V BluetoothAdapterState: isBleTurningOn()=false
11-22 14:02:00.428  4731  4731 V BluetoothAdapterState: isBleTurningOff()=false
11-22 14:02:00.429  4731  4731 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-22 14:02:00.429  4731  4731 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-22 14:02:00.429  4731  4807 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-22 14:02:00.429  4731  4731 V BluetoothAdapterState: isTurningOff()=true
11-22 14:02:00.429  4731  4731 V BluetoothAdapterState: isTurningOn()=false
11-22 14:02:00.429  4731  4731 V BluetoothAdapterState: isBleTurningOn()=false
11-22 14:02:00.429  4731  4731 V BluetoothAdapterState: isBleTurningOff()=false
11-22 14:02:00.429  4731  4731 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-22 14:02:00.429  4731  4807 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,11-22 14:02:00.430  4731  4731 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,11-22 14:02:00.430  4731  4731 V BluetoothAdapterState: isTurningOff()=true
11-22 14:02:00.430  4731  4731 V BluetoothAdapterState: isTurningOn()=false
11-22 14:02:00.430  4731  4731 V BluetoothAdapterState: isBleTurningOn()=false
11-22 14:02:00.430  4731  4731 V BluetoothAdapterState: isBleTurningOff()=false
11-22 14:02:00.430  4731  4731 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-22 14:02:00.430  4731  4731 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-22 14:02:00.432  4731  4731 D BluetoothMapService: MAP Service closeService in
11-22 14:02:00.432  4731  4731 V BluetoothAdapterState: isTurningOff()=true
11-22 14:02:00.432  4731  4731 V BluetoothAdapterState: isTurningOn()=false
11-22 14:02:00.432  4731  4731 V BluetoothAdapterState: isBleTurningOn()=false
,11-22 14:02:00.432  4731  4731 V BluetoothAdapterState: isBleTurningOff()=false
11-22 14:02:00.432  4731  4731 D BluetoothMapService: cleanup()
11-22 14:02:00.432  4731  4731 D BluetoothMapService: MAP Service closeService in
11-22 14:02:00.433  4731  4731 V BluetoothAdapterState: isTurningOff()=true
11-22 14:02:00.433  4731  4731 V BluetoothAdapterState: isTurningOn()=false
11-22 14:02:00.433  4731  4731 V BluetoothAdapterState: isBleTurningOn()=false
11-22 14:02:00.433  4731  4731 V BluetoothAdapterState: isBleTurningOff()=false
11-22 14:02:00.433  4731  4803 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-22 14:02:00.433  4731  4803 D BluetoothAdapterProperties: Setting state to 15
11-22 14:02:00.433  4731  4803 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-22 14:02:00.433  4731  4803 I BluetoothAdapterState: Entering BleOnState
11-22 14:02:00.434  3227  4084 D BluetoothPan: onBluetoothStateChange on: false
11-22 14:02:00.434  3227  3241 D BluetoothHeadset: onBluetoothStateChange: up=false
11-22 14:02:00.435  3227  3238 D BluetoothMap: onBluetoothStateChange: up=false
11-22 14:02:00.435  3227  4084 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-22 14:02:00.436   933   950 D BluetoothHeadset: onBluetoothStateChange: up=false
11-22 14:02:00.436  3227  3241 D BluetoothPbap: onBluetoothStateChange: up=false
11-22 14:02:00.437  3891  3912 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-22 14:02:00.437   933   950 D BluetoothHeadset: onBluetoothStateChange: up=false
11-22 14:02:00.437   933   950 D BluetoothA2dp: onBluetoothStateChange: up=false
11-22 14:02:00.438  3227  3238 D BluetoothA2dp: onBluetoothStateChange: up=false
11-22 14:02:00.438   502   927 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-22 14:02:00.439   933  3072 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-22 14:02:00.441   933   950 D BluetoothHeadset: onBluetoothStateChange: up=false
11-22 14:02:00.442  4731  4803 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-22 14:02:00.442  4731  4803 D BluetoothAdapterProperties: Setting state to 16
11-22 14:02:00.442  4731  4803 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-22 14:02:00.443  4731  4803 D BluetoothAdapterProperties: onBleDisable
11-22 14:02:00.443  4731  4803 I BluetoothAdapterState: Entering PendingCommandState
11-22 14:02:00.443  4731  4804 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-22 14:02:00.444  4731  4932 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-22 14:02:00.444  4731  4807 D BluetoothAdapterProperties: Scan Mode:20
11-22 14:02:00.444  4731  4932 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-22 14:02:00.445  5705  5705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-22 14:02:00.448  5705  5705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-22 14:02:00.460   502   927 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-22 14:02:00.460   502   927 D CommandListener: Clearing all IP addresses on wlan0
11-22 14:02:00.461   502   927 D TetherController: Setting IP forward enable = 0
11-22 14:02:00.462   933  3077 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
11-22 14:02:00.462   933  3077 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-22 14:02:00.465   933   950 D Tethering: MasterInitialState.processMessage what=3
11-22 14:02:00.466  5705  5705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-22 14:02:00.466  5353  5353 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@e02a4c7 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
11-22 14:02:00.467  4067  4067 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
11-22 14:02:00.471  5140  5164 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-22 14:02:00.471  5140  5164 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-22 14:02:00.471  5140  5164 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
11-22 14:02:00.471  5140  5164 E SarControlService: no key has been found,reset the power
11-22 14:02:00.472  5140  5176 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-22 14:02:00.472  5140  5176 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-22 14:02:00.472  5140  5176 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-22 14:02:00.472  5165  5165 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-22 14:02:00.472  5165  5165 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-22 14:02:00.474  5140  5176 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-22 14:02:00.474  5140  5176 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-22 14:02:00.475  5140  5176 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-22 14:02:00.476  5165  5179 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@3ebd1a5 HexData = [00000000ea03000000000000ffffffff]
11-22 14:02:00.476  5165  5179 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-22 14:02:00.476  5165  5179 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
11-22 14:02:00.478  5165  5165 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-22 14:02:00.478  5165  5165 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-22 14:02:00.479  5165  5165 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-22 14:02:00.479  5140  5150 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-22 14:02:00.483  5775  5775 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
11-22 14:02:00.486  5165  5179 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@3ebd1a5 HexData = [00000000eb03000000000000ffffffff]
11-22 14:02:00.486  5165  5179 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-22 14:02:00.486  5165  5179 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
11-22 14:02:00.487  5165  5165 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-22 14:02:00.488  5140  5151 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-22 14:02:00.498  5775  5775 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-22 14:02:00.504   933   950 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@154c3cf:true
,11-22 14:02:00.504  3672  3672 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-22 14:02:00.509   502   927 E Netd    : netlink response contains error (No such file or directory)
11-22 14:02:00.511   933  3077 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,11-22 14:02:00.511   933  3077 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-22 14:02:00.511   933  3072 D DhcpClient: doQuit
11-22 14:02:00.511   933  3072 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-22 14:02:00.512  3539  3539 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-22 14:02:00.512   933  5508 D DhcpClient: onQuitting
,11-22 14:02:00.516  5705  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-22 14:02:00.516  5705  5705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-22 14:02:00.516  5705  5705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 14:02:00.516  5705  5705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 14:02:00.516  5705  5705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-22 14:02:00.516  5705  5705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-22 14:02:00.516  5705  5705 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-22 14:02:00.516  5705  5705 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-22 14:02:00.516  5705  5705 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-22 14:02:00.516  5705  5705 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-22 14:02:00.517  5705  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-22 14:02:00.517  5705  5705 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-22 14:02:00.523  5775  5775 D LocalBluetoothProfileManager: Adding local MAP profile
,11-22 14:02:00.525  5775  5775 D BluetoothMap: Create BluetoothMap proxy object
,11-22 14:02:00.530  3539  3539 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-22 14:02:00.532  5775  5775 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,11-22 14:02:00.535  3539  3539 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,11-22 14:02:00.538  5775  5775 D DockEventReceiver: finishStartingService: stopping service
,11-22 14:02:00.541  5775  5775 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-22 14:02:00.545  3672  3672 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-22 14:02:00.546  5775  5775 D DockEventReceiver: finishStartingService: stopping service
,11-22 14:02:00.547   933   943 I ActivityManager: Killing 5353:com.google.android.music:main/u0a59 (adj 15): empty #17
,11-22 14:02:00.562  3539  3539 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-22 14:02:00.569  3539  3539 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-22 14:02:00.579  3816  3816 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-22 14:02:00.582  3816  3816 D SystemUpdateService: onCreate
,11-22 14:02:00.585  3816  3816 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-22 14:02:00.593  3816  3816 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-22 14:02:00.597  3816  5534 I iu.UploadsManager: num queued entries: 0
11-22 14:02:00.597  3816  5534 I iu.UploadsManager: num updated entries: 0
,11-22 14:02:00.599  3816  5808 I SystemUpdateService: active receiver: enabled
,11-22 14:02:00.600  3816  3816 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-22 14:02:00.602  3816  3816 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-22 14:02:00.603  5537  5537 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-22 14:02:00.607  5537  5537 D SprintDMHelper: simOperator: 
,11-22 14:02:00.607  5537  5537 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-22 14:02:00.622  3816  5534 I iu.SyncManager: NEXT; no task
,11-22 14:02:00.623  5089  5810 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,11-22 14:02:00.626  3816  5808 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-22 14:02:00.628  3816  5808 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,11-22 14:02:00.628  3816  5808 I SystemUpdateService: now status is 0 (complete)
11-22 14:02:00.628  3816  5808 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-22 14:02:00.628  3816  5808 I SystemUpdateService: file has been verified
11-22 14:02:00.628  3816  5808 I SystemUpdateService: OTA package size = 21989297
,11-22 14:02:00.634   933  3931 I ActivityManager: Start proc 5811:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,11-22 14:02:00.639  3816  5808 I SystemUpdateService: showing system update notification
,11-22 14:02:00.649   933   933 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-22 14:02:00.651  3816  3816 D SystemUpdateService: onDestroy
,11-22 14:02:00.654  4731  4807 I bt_hci  : shut_down
,11-22 14:02:00.660  4731  4811 D bt_hwcfg: hw_epilog_process
11-22 14:02:00.660  4731  4811 I bt_vendor: low_power_mode_cb
,11-22 14:02:00.662  4731  4811 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,11-22 14:02:00.662  4731  4811 I bt_vendor: epilog_cb
11-22 14:02:00.662  4731  4811 I bt_hci  : epilog_finished_callback
,11-22 14:02:00.664  4731  4807 I bt_hci_h4: hal_close
,11-22 14:02:00.665  4731  4807 I bt_userial_vendor: device fd = 54 close
,11-22 14:02:00.670  5811  5811 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
11-22 14:02:00.671   933  3072 D wifi    : In wifi stop Hal
11-22 14:02:00.671   933  3072 D wifi    : halHandle = 0x7f70c92300, mVM = 0x7f8d2cd140, mCls = 0x100a02
,11-22 14:02:00.672   933  3538 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-22 14:02:00.672  5089  5089 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-22 14:02:00.672   933  3538 D WifiHAL : Got a signal to exit!!!
11-22 14:02:00.672   933  3538 I WifiHAL : Exit wifi_event_loop
11-22 14:02:00.673   933  3072 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-22 14:02:00.673   933  3072 E WifiHAL : Event processing terminated
,11-22 14:02:00.673   933  3072 D wifi    : In wifi cleaned up handler
11-22 14:02:00.673   933  3072 I WifiHAL : Internal cleanup completed
11-22 14:02:00.674  5705  5705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-22 14:02:00.675  4104  4306 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-22 14:02:00.682   933  3495 I ActivityManager: Killing 3999:com.android.providers.calendar/u0a1 (adj 15): empty #17
,11-22 14:02:00.693   933  3538 D wifi    : set interface wlan0 flags (DOWN)
,11-22 14:02:00.693   933  3072 D WifiNative-HAL: HAL event thread stopped successfully
,11-22 14:02:00.771  4731  4804 D bt_stack_manager: event_shut_down_stack finished.
,11-22 14:02:00.771  4731  4803 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
11-22 14:02:00.773  4731  4803 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,11-22 14:02:00.773  4731  4731 D BtGatt.DebugUtils: handleDebugAction() action=null
11-22 14:02:00.773  4731  4731 D BtGatt.GattService: Received stop request...Stopping profile...
11-22 14:02:00.773  4731  4731 D BtGatt.GattService: stop()
11-22 14:02:00.773  4731  4731 D BtGatt.AdvertiseManager: advertise clients cleared
,11-22 14:02:00.776  4731  4731 V BluetoothAdapterState: isTurningOff()=false
11-22 14:02:00.776  4731  4731 V BluetoothAdapterState: isTurningOn()=false
,11-22 14:02:00.776  4731  4731 V BluetoothAdapterState: isBleTurningOn()=false
11-22 14:02:00.776  4731  4731 V BluetoothAdapterState: isBleTurningOff()=true
11-22 14:02:00.776  4731  4803 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,11-22 14:02:00.776  4731  4803 D BluetoothAdapterProperties: Setting state to 10
11-22 14:02:00.776  4731  4803 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-22 14:02:00.777  4731  4803 I BluetoothAdapterState: Entering OffState
,11-22 14:02:00.778   933   950 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,11-22 14:02:00.785  4731  4731 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-22 14:02:00.785  4731  4731 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-22 14:02:00.785  4731  4731 I BluetoothServiceJni: cleanupNative: return from cleanup
11-22 14:02:00.787  4731  4804 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-22 14:02:00.789  4731  4731 I art     : System.exit called, status: 0
,11-22 14:02:00.790  4731  4731 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-22 14:02:00.812   933  3964 I ActivityManager: Process com.android.bluetooth (pid 4731) has died
,11-22 14:02:00.897   933   950 D Tethering: InitialState.processMessage what=4
,11-22 14:02:00.902   933   950 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-22 14:02:01.539   502   927 D TetherController: Setting IP forward enable = 0
,11-22 14:02:05.414   933   944 D WifiService: setWifiEnabled: true pid=5705, uid=10077
,11-22 14:02:05.414   933   944 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-22 14:02:05.424   502   927 D SoftapController: Softap fwReload - Ok
,11-22 14:02:05.433   502   927 D CommandListener: Setting iface cfg
,11-22 14:02:05.433   502   927 D CommandListener: Trying to bring down wlan0
,11-22 14:02:05.435   502   927 D CommandListener: Clearing all IP addresses on wlan0
,11-22 14:02:05.440   933  3072 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-22 14:02:06.034   933  3072 D wifi    : set interface wlan0 flags (UP)
,11-22 14:02:06.038   933  3072 I WifiHAL : Initializing wifi
11-22 14:02:06.039   933  3072 I WifiHAL : Creating socket
11-22 14:02:06.042   933   950 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-22 14:02:06.044   933  3072 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-22 14:02:06.044   933  3072 D wifi    : Did set static halHandle = 0x7f70c92300
11-22 14:02:06.045   933  3072 D wifi    : halHandle = 0x7f70c92300, mVM = 0x7f8d2cd140, mCls = 0x10196e
11-22 14:02:06.045   933  3072 D wifi    : array field set
11-22 14:02:06.045   933  3072 I WifiNative-HAL: interface[0] = wlan0
11-22 14:02:06.047   933  5832 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547353076480
11-22 14:02:06.047   933  5832 D wifi    : waitForHalEvents called, vm = 0x7f8d2cd140, obj = 0x10196e, env = 0x7f6e821900
,11-22 14:02:06.130  5833  5833 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-22 14:02:06.149   933  3072 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-22 14:02:06.156  5705  5705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-22 14:02:06.195  5833  5833 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-22 14:02:06.206  5833  5833 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-22 14:02:06.206  5833  5833 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-22 14:02:06.217   933  3072 D WifiConfigStore: Loading config and enabling all networks 
,11-22 14:02:06.221  5705  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-22 14:02:06.221  5705  5705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-22 14:02:06.221  5705  5705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 14:02:06.221  5705  5705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 14:02:06.221  5705  5705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-22 14:02:06.221  5705  5705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-22 14:02:06.221  5705  5705 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-22 14:02:06.221  5705  5705 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-22 14:02:06.221  5705  5705 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-22 14:02:06.221  5705  5705 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-22 14:02:06.221  5705  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-22 14:02:06.221  5705  5705 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-22 14:02:06.232   933  3072 D WifiConfigStore: loaded 0 passpoint configs
,11-22 14:02:06.232   933  3072 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
11-22 14:02:06.233   933  3072 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,11-22 14:02:06.233   933  3072 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
11-22 14:02:06.233   933  3072 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
,11-22 14:02:06.234   933  3072 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
,11-22 14:02:06.234   933  3072 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
11-22 14:02:06.234   933  3072 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-22 14:02:06.235   933  3072 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-22 14:02:06.235   933  3072 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
11-22 14:02:06.235   933  3072 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-22 14:02:06.235   933  3072 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-22 14:02:06.235   933  3072 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-22 14:02:06.237   933  3072 D WifiNative-HAL: Setting external_sim to 1
,11-22 14:02:06.237   933  3072 D wifi    : setting dfs flag to true, 0x7f73e47d40
11-22 14:02:06.238   933  3072 D WifiStateMachine: Setting OUI to DA-A1-19
11-22 14:02:06.238   933  3072 D wifi    : setting scan oui 0x7f73e47d40
,11-22 14:02:06.238   933  3072 D WifiHAL : Sending mac address OUI
,11-22 14:02:06.239  5089  5089 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-22 14:02:06.241   933  3072 E native  : do suspend false
,11-22 14:02:06.248   933  3072 D wifi    : android_net_wifi_setLinkLayerStats: 1
,11-22 14:02:06.248   933   933 D RttService: SCAN_AVAILABLE : 3
11-22 14:02:06.249   933  3180 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
11-22 14:02:06.249   502   927 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,11-22 14:02:06.252   502   927 D CommandListener: Setting iface cfg
,11-22 14:02:06.254   933  3071 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '124 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 124 Failed to set address (No such device)'
11-22 14:02:06.254   933  3071 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-22 14:02:06.262   933  3071 D WifiNative-HAL: p2pGetDeviceAddress
,11-22 14:02:06.266   933   948 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=205428 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=12 mControllerEnergyUsed=45 }
11-22 14:02:06.266   933  3071 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-22 14:02:09.331  5833  5833 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-22 14:02:09.338  5833  5833 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-22 14:02:09.345  5833  5833 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-22 14:02:09.366   933  3072 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-22 14:02:09.367   933  3072 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,11-22 14:02:09.367   933  3072 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-22 14:02:09.379   933  3072 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-22 14:02:09.410   933  3072 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-22 14:02:09.415  5833  5833 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-22 14:02:09.858  5833  5833 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-22 14:02:09.900  5833  5833 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-22 14:02:09.900  5833  5833 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-22 14:02:09.907   933  3072 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-22 14:02:09.907   933  3072 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-22 14:02:09.907   933  3077 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-22 14:02:09.924   933  3072 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-22 14:02:09.936   502   927 D CommandListener: Setting iface cfg
,11-22 14:02:09.941   933  3072 D WifiStateMachine: Start Dhcp Watchdog 2
,11-22 14:02:09.946   933  5841 D DhcpClient: Receive thread started
,11-22 14:02:09.950   933  3077 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-22 14:02:09.950   933  3072 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
11-22 14:02:09.951   933  3077 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,11-22 14:02:10.031   933  3072 E native  : do suspend false
,11-22 14:02:10.045   933  5840 D DhcpClient: Broadcasting DHCPDISCOVER
,11-22 14:02:10.070   933  5841 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.109, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172648, domain null
,11-22 14:02:10.071   933  5840 D DhcpClient: Got pending lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172648 seconds
,11-22 14:02:10.072   933  5840 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.109 serverid=192.168.1.1
,11-22 14:02:10.156   933  5841 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.109, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-22 14:02:10.156   933  5840 D DhcpClient: Confirmed lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-22 14:02:10.159   502   927 D CommandListener: Setting iface cfg
11-22 14:02:10.164   933  3072 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-22 14:02:10.169   933  5840 D DhcpClient: Scheduling renewal in 86399s
,11-22 14:02:10.178   933  3072 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-22 14:02:10.179   933  3072 D WifiConfigStore: No blacklist allowed without epno enabled
,11-22 14:02:10.183   933  3077 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,11-22 14:02:10.185   933  3077 D ConnectivityService: Adding iface wlan0 to network 101
,11-22 14:02:10.189   933  3072 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-22 14:02:10.234   933  3077 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-22 14:02:10.235   933  3077 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,11-22 14:02:10.237   933  3077 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,11-22 14:02:10.239   933  3077 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,11-22 14:02:10.242   933  3077 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,11-22 14:02:10.252   933  3077 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-22 14:02:10.256   933  3077 D ConnectivityService: scheduleUnvalidatedPrompt 101
,11-22 14:02:10.256   933  3077 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
11-22 14:02:10.256   933  3077 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
11-22 14:02:10.256   933  3077 D ConnectivityService:    accepting network in place of null
11-22 14:02:10.256   933  3072 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,11-22 14:02:10.257   933  3072 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-22 14:02:10.257   933  3077 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -55]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-22 14:02:10.268   933  5839 D NetlinkSocketObserver: NeighborEvent{elapsedMs=209430, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-22 14:02:10.281   502   927 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-22 14:02:10.302   502   927 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-22 14:02:10.306   933  3077 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,11-22 14:02:10.306   933  3077 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-22 14:02:10.306  3867  3983 W QCNEJ   : |CORE| network available: 101
,11-22 14:02:10.307   933  3077 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,11-22 14:02:10.308   933   950 D Tethering: MasterInitialState.processMessage what=3
11-22 14:02:10.313  3867  3983 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-22 14:02:10.314  5705  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-22 14:02:10.314  5705  5705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-22 14:02:10.314  5705  5705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 14:02:10.314  5705  5705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 14:02:10.314  5705  5705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-22 14:02:10.314  5705  5705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-22 14:02:10.314  5705  5705 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-22 14:02:10.314  5705  5705 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-22 14:02:10.314  5705  5705 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-22 14:02:10.314  5705  5705 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-22 14:02:10.314  3867  3983 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-22 14:02:10.314  5705  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-22 14:02:10.314  5705  5705 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-22 14:02:10.314  3867  3983 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-22 14:02:10.323  5140  5164 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,11-22 14:02:10.323  5140  5164 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-22 14:02:10.323  5140  5164 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
11-22 14:02:10.324  5140  5164 E SarControlService: no key has been found,reset the power
11-22 14:02:10.324  5140  5176 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-22 14:02:10.324  5140  5176 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-22 14:02:10.324  5140  5176 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-22 14:02:10.324  5165  5165 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-22 14:02:10.325  5165  5165 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-22 14:02:10.328  4067  4067 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,11-22 14:02:10.329  5140  5176 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-22 14:02:10.329  5140  5176 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-22 14:02:10.329  5140  5176 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-22 14:02:10.329  5165  5165 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-22 14:02:10.329  5165  5165 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-22 14:02:10.332  3816  3816 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-22 14:02:10.333  5165  5179 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@3ebd1a5 HexData = [00000000ec03000000000000ffffffff]
11-22 14:02:10.333  5165  5179 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-22 14:02:10.333  5165  5179 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
11-22 14:02:10.333  5165  5165 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-22 14:02:10.334  5140  5150 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,11-22 14:02:10.335  5165  5179 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@3ebd1a5 HexData = [00000000ed03000000000000ffffffff]
11-22 14:02:10.335  5165  5179 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-22 14:02:10.335  5165  5179 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
,11-22 14:02:10.338  5165  5165 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,11-22 14:02:10.339  5140  5151 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-22 14:02:10.340  3816  3816 D SystemUpdateService: onCreate
,11-22 14:02:10.344   933  5838 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.22.46,2a00:1450:4001:81b::200e
11-22 14:02:10.345  3816  3816 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-22 14:02:10.355  3816  3816 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-22 14:02:10.360  3816  5534 I iu.UploadsManager: num queued entries: 0
11-22 14:02:10.360  3816  5534 I iu.UploadsManager: num updated entries: 0
11-22 14:02:10.360  3816  5534 I iu.SyncManager: NEXT; no task
,11-22 14:02:10.362  3816  5853 I SystemUpdateService: active receiver: enabled
,11-22 14:02:10.365  3816  3816 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
11-22 14:02:10.367  3816  3816 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-22 14:02:10.368  5537  5537 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-22 14:02:10.371  5537  5537 D SprintDMHelper: simOperator: 
11-22 14:02:10.372  5537  5537 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-22 14:02:10.392  3816  5853 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-22 14:02:10.406  3816  5853 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-22 14:02:10.406  3816  5853 I SystemUpdateService: now status is 0 (complete)
11-22 14:02:10.406  3816  5853 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-22 14:02:10.406  3816  5853 I SystemUpdateService: file has been verified
11-22 14:02:10.406  3816  5853 I SystemUpdateService: OTA package size = 21989297
,11-22 14:02:10.412  3816  5853 I SystemUpdateService: showing system update notification
,11-22 14:02:10.414   933  5838 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 22 Nov 2016 13:02:10 GMT], X-Android-Received-Millis=[1479819730414], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1479819730386]}
,11-22 14:02:10.415   933  3077 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-22 14:02:10.415   933  3077 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
11-22 14:02:10.415   933  3077 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
11-22 14:02:10.416   933  3077 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-22 14:02:10.421   933   933 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-22 14:02:10.423  3816  3816 D SystemUpdateService: onDestroy
11-22 14:02:10.425   933  3514 D WifiService: setWifiEnabled: false pid=5705, uid=10077
11-22 14:02:10.425   933  3514 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-22 14:02:10.427   933  3072 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,11-22 14:02:10.427   933  3072 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-22 14:02:10.427   933  3072 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-22 14:02:10.427   933  3072 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-22 14:02:10.438   933  5840 D DhcpClient: Clearing IP address
11-22 14:02:10.439   502   927 D CommandListener: Clearing all IP addresses on wlan0
,11-22 14:02:10.441   502   927 D CommandListener: Setting iface cfg
11-22 14:02:10.442   933  5841 D DhcpClient: Receive thread stopped
,11-22 14:02:10.452  5089  5857 W Babel_NetworkConnectionCheckingService: IO exceptions, probably not a captive portal 
,11-22 14:02:10.453   933  3513 D ConnectivityService: reportNetworkConnectivity(101, false) by 10012
,11-22 14:02:10.454   933  5838 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10012
,11-22 14:02:10.454   933  5838 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.22.46,2a00:1450:4001:81b::200e
11-22 14:02:10.456   933  3077 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
11-22 14:02:10.456   933  3077 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
11-22 14:02:10.458   532   532 E Parcel  : Reading a NULL string not supported here.
,11-22 14:02:10.460   933   933 D RttService: SCAN_AVAILABLE : 1
11-22 14:02:10.460   933  3180 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
11-22 14:02:10.461   933  3077 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
11-22 14:02:10.462  3867  3983 W QCNEJ   : |CORE| network lost: 101
11-22 14:02:10.462   933  3072 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
11-22 14:02:10.463  3867  3983 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
11-22 14:02:10.465   933  5838 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:4001:81b::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
11-22 14:02:10.465   933  3072 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-22 14:02:10.478  5089  5857 W Babel_NetworkConnectionCheckingService: java.net.SocketTimeoutException: failed to connect to clients3.google.com/172.217.22.110 (port 80) after 5000ms: isConnected failed: ETIMEDOUT (Connection timed out)
11-22 14:02:10.478  5089  5857 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.isConnected(IoBridge.java:232)
11-22 14:02:10.478  5089  5857 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.connectErrno(IoBridge.java:171)
11-22 14:02:10.478  5089  5857 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.connect(IoBridge.java:122)
11-22 14:02:10.478  5089  5857 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:183)
11-22 14:02:10.478  5089  5857 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:452)
11-22 14:02:10.478  5089  5857 W Babel_NetworkConnectionCheckingService: 	at java.net.Socket.connect(Socket.java:884)
11-22 14:02:10.478  5089  5857 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.Platform.connectSocket(Platform.java:117)
11-22 14:02:10.478  5089  5857 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.SocketConnector.connectRawSocket(SocketConnector.java:160)
11-22 14:02:10.478  5089  5857 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.SocketConnector.connectCleartext(SocketConnector.java:67)
11-22 14:02:10.478  5089  5857 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.Connection.connect(Connection.java:152)
11-22 14:02:10.478  5089  5857 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.Connection.connectAndSetOwner(Connection.java:185)
11-22 14:02:10.478  5089  5857 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.OkHttpClient$1.connectAndSetOwner(OkHttpClient.java:128)
11-22 14:02:10.478  5089  5857 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.nextConnection(HttpEngine.java:341)
11-22 14:02:10.478  5089  5857 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:330)
11-22 14:02:10.478  5089  5857 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:248)
11-22 14:02:10.478  5089  5857 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.execute(HttpURLConnectionImpl.java:437)
11-22 14:02:10.478  5089  5857 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.getResponse(HttpURLConnectionImpl.java:388)
11-22 14:02:10.478  5089  5857 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.getInputStream(HttpURLConnectionImpl.java:231)
11-22 14:02:10.478  5089  5857 W Babel_NetworkConnectionCheckingService: 	at com.google.android.apps.hangouts.service.NetworkConnectionCheckingService.a(SourceFile:129)
11-22 14:02:10.478  5089  5857 W Babel_NetworkConnectionCheckingService: 	at com.google.android.apps.hangouts.service.NetworkConnectionCheckingService.onHandleIntent(SourceFile:1100)
11-22 14:02:10.478  5089  5857 W Babel_NetworkConnectionCheckingService: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-22 14:02:10.478  5089  5857 W Babel_NetworkConnectionCheckingService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-22 14:02:10.478  5089  5857 W Babel_NetworkConnectionCheckingService: 	at android.os.Looper.loop(Looper.java:148)
11-22 14:02:10.478  5089  5857 W Babel_NetworkConnectionCheckingService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-22 14:02:10.478  5089  5857 W Babel_NetworkConnectionCheckingService: Caused by: android.system.ErrnoException: isConnected failed: ETIMEDOUT (Connection timed out)
11-22 14:02:10.478  5089  5857 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.isConne,cted(IoBridge.java:223)
11-22 14:02:10.478  5089  5857 W Babel_NetworkConnectionCheckingService: 	... 23 more
11-22 14:02:10.478  5089  5857 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,11-22 14:02:10.487   502   927 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-22 14:02:10.504   502   927 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-22 14:02:10.504   502   927 D CommandListener: Clearing all IP addresses on wlan0
11-22 14:02:10.504   933  3077 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,11-22 14:02:10.504   933  3077 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-22 14:02:10.506   933   950 D Tethering: MasterInitialState.processMessage what=3
11-22 14:02:10.507  5705  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-22 14:02:10.508  5705  5705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-22 14:02:10.508  5705  5705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 14:02:10.508  5705  5705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 14:02:10.508  5705  5705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-22 14:02:10.508  5705  5705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-22 14:02:10.508  5705  5705 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-22 14:02:10.508  5705  5705 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-22 14:02:10.508  5705  5705 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-22 14:02:10.508  5705  5705 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-22 14:02:10.508  5705  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-22 14:02:10.508  5705  5705 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-22 14:02:10.509   933  3072 D DhcpClient: doQuit
11-22 14:02:10.509   933  3072 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-22 14:02:10.509   933  5840 D DhcpClient: onQuitting
11-22 14:02:10.510  5833  5833 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-22 14:02:10.510  4067  4067 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,11-22 14:02:10.514  5705  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-22 14:02:10.514  5705  5705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-22 14:02:10.514  5705  5705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 14:02:10.514  5705  5705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 14:02:10.514  5705  5705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-22 14:02:10.514  5705  5705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-22 14:02:10.514  5705  5705 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-22 14:02:10.514  5705  5705 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-22 14:02:10.514  5705  5705 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-22 14:02:10.514  5705  5705 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-22 14:02:10.514  5705  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-22 14:02:10.514  5705  5705 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-22 14:02:10.515  3816  3816 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-22 14:02:10.517  5140  5164 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-22 14:02:10.517  5140  5164 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-22 14:02:10.517  5140  5164 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
11-22 14:02:10.517  5140  5164 E SarControlService: no key has been found,reset the power
11-22 14:02:10.517  5140  5176 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-22 14:02:10.517  5140  5176 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-22 14:02:10.517  5140  5176 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
,11-22 14:02:10.518  5165  5165 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-22 14:02:10.518  5165  5165 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-22 14:02:10.519  5140  5176 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-22 14:02:10.519  5140  5176 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-22 14:02:10.519  5140  5176 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-22 14:02:10.519  5165  5165 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-22 14:02:10.520  5165  5165 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-22 14:02:10.522  5833  5833 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
11-22 14:02:10.524  5165  5179 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@3ebd1a5 HexData = [00000000ee03000000000000ffffffff]
11-22 14:02:10.524  5165  5179 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-22 14:02:10.524  5165  5179 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
11-22 14:02:10.525  5165  5165 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-22 14:02:10.525  5140  5151 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-22 14:02:10.525  3816  3816 D SystemUpdateService: onCreate
11-22 14:02:10.526  5165  5179 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@3ebd1a5 HexData = [00000000ef03000000000000ffffffff]
11-22 14:02:10.526  5165  5179 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-22 14:02:10.526  5165  5179 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
11-22 14:02:10.527  5833  5833 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
11-22 14:02:10.528  5165  5165 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-22 14:02:10.528  5140  5150 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-22 14:02:10.531  3816  3816 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-22 14:02:10.538  3816  5873 I SystemUpdateService: active receiver: enabled
,11-22 14:02:10.540  3816  3816 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-22 14:02:10.545  3816  5534 I iu.UploadsManager: num queued entries: 0
,11-22 14:02:10.546  3816  5534 I iu.UploadsManager: num updated entries: 0
11-22 14:02:10.546  3816  5534 I iu.SyncManager: NEXT; no task
,11-22 14:02:10.549  3816  3816 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-22 14:02:10.550  3816  3816 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-22 14:02:10.552  5537  5537 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-22 14:02:10.556  5537  5537 D SprintDMHelper: simOperator: 
,11-22 14:02:10.556  5537  5537 D SprintDMReceiver: Not Sprint UICC, don't do anything.
11-22 14:02:10.556   502   927 E Netd    : netlink response contains error (No such file or directory)
11-22 14:02:10.557   933  3077 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
11-22 14:02:10.557   933  3077 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-22 14:02:10.560  5833  5833 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-22 14:02:10.563  3816  5873 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-22 14:02:10.567  5089  5877 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,11-22 14:02:10.572  3816  5873 I SystemUpdateService: network: null; metered: false; mobile allowed: true
11-22 14:02:10.572  3816  5873 I SystemUpdateService: now status is 0 (complete)
11-22 14:02:10.572  3816  5873 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-22 14:02:10.572  3816  5873 I SystemUpdateService: file has been verified
11-22 14:02:10.572  3816  5873 I SystemUpdateService: OTA package size = 21989297
11-22 14:02:10.572  5833  5833 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-22 14:02:10.589  3816  5873 I SystemUpdateService: showing system update notification
,11-22 14:02:10.595   933   933 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-22 14:02:10.596  3816  3816 D SystemUpdateService: onDestroy
,11-22 14:02:10.675   933  3072 D wifi    : In wifi stop Hal
11-22 14:02:10.675   933  3072 D wifi    : halHandle = 0x7f70c92300, mVM = 0x7f8d2cd140, mCls = 0x10196e
11-22 14:02:10.677   933  5832 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-22 14:02:10.677   933  5832 D WifiHAL : Got a signal to exit!!!
,11-22 14:02:10.677   933  5832 I WifiHAL : Exit wifi_event_loop
11-22 14:02:10.677  5089  5089 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-22 14:02:10.679   933  3072 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-22 14:02:10.679   933  3072 E WifiHAL : Event processing terminated
,11-22 14:02:10.679   933  3072 D wifi    : In wifi cleaned up handler
11-22 14:02:10.679  5705  5705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-22 14:02:10.679   933  3072 I WifiHAL : Internal cleanup completed
11-22 14:02:10.679  4104  4306 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-22 14:02:10.708   933  5832 D wifi    : set interface wlan0 flags (DOWN)
,11-22 14:02:10.708   933  3072 D WifiNative-HAL: HAL event thread stopped successfully
,11-22 14:02:10.914   933   950 D Tethering: InitialState.processMessage what=4
,11-22 14:02:10.920   933   950 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-22 14:02:11.306   933  3077 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,11-22 14:02:15.462   933   950 I ActivityManager: Start proc 5879:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-22 14:02:15.559  5879  5879 D AdapterServiceConfig: Adding HeadsetService
,11-22 14:02:15.560  5879  5879 D AdapterServiceConfig: Adding A2dpService
11-22 14:02:15.560  5879  5879 D AdapterServiceConfig: Adding HidService
11-22 14:02:15.560  5879  5879 D AdapterServiceConfig: Adding HealthService
11-22 14:02:15.560  5879  5879 D AdapterServiceConfig: Adding PanService
11-22 14:02:15.560  5879  5879 D AdapterServiceConfig: Adding GattService
11-22 14:02:15.561  5879  5879 D AdapterServiceConfig: Adding BluetoothMapService
,11-22 14:02:15.561  5879  5879 D AdapterServiceConfig: Adding SapService
,11-22 14:02:15.571   933   950 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@77fa550:true
,11-22 14:02:15.572  5879  5879 D BluetoothAdapterState: make() - Creating AdapterState
,11-22 14:02:15.575  5879  5879 I bt_bluedroid: init
11-22 14:02:15.575  5879  5891 I BluetoothAdapterState: Entering OffState
,11-22 14:02:15.577  5879  5892 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-22 14:02:15.577  5879  5892 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-22 14:02:15.577  5879  5892 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-22 14:02:15.577  5879  5892 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-22 14:02:15.578  5879  5879 I bt_bluedroid: get_profile_interface socket
,11-22 14:02:15.580  5879  5895 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-22 14:02:15.580  5879  5879 I bt_bluedroid: get_profile_interface sdp
11-22 14:02:15.581  5879  5895 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-22 14:02:15.585  5879  5890 I bt_bluedroid: config_hci_snoop_log
11-22 14:02:15.586   933   950 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-22 14:02:15.590  5879  5891 D BluetoothAdapterState: Current state: OFF, message: 0
,11-22 14:02:15.590  5879  5891 D BluetoothAdapterProperties: Setting state to 14
11-22 14:02:15.591  5879  5891 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
11-22 14:02:15.592  5879  5891 D BluetoothBondStateMachine: make
,11-22 14:02:15.594  5879  5896 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-22 14:02:15.597  5879  5891 I BluetoothAdapterState: Entering PendingCommandState
,11-22 14:02:15.598  5879  5879 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-22 14:02:15.600  5879  5879 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b705d8d
11-22 14:02:15.601  5879  5879 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-22 14:02:15.602  5879  5879 D BtGatt.GattService: Received start request. Starting profile...
,11-22 14:02:15.602  5879  5879 D BtGatt.GattService: start()
11-22 14:02:15.602  5879  5879 I bt_bluedroid: get_profile_interface gatt
,11-22 14:02:15.604  5879  5879 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b705d8d
11-22 14:02:15.604  5879  5879 D BtGatt.AdvertiseManager: advertise manager created
,11-22 14:02:15.609  5879  5879 V BluetoothAdapterState: isTurningOff()=false
,11-22 14:02:15.609  5879  5879 V BluetoothAdapterState: isTurningOn()=false
11-22 14:02:15.609  5879  5879 V BluetoothAdapterState: isBleTurningOn()=true
11-22 14:02:15.609  5879  5879 V BluetoothAdapterState: isBleTurningOff()=false
11-22 14:02:15.610  5879  5891 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-22 14:02:15.611  5879  5891 I bt_bluedroid: bt_bluedroid
,11-22 14:02:15.611  5879  5892 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,11-22 14:02:15.612  5879  5892 I bt_hci  : start_up
,11-22 14:02:15.618  5879  5892 I bt_vendor: alloc value 0xf3bad871
11-22 14:02:15.618  5879  5892 I bt_vendor: init
,11-22 14:02:15.618  5879  5892 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-22 14:02:15.619  5879  5892 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-22 14:02:15.731  5879  5892 D bt_hci  : start_up starting async portion
,11-22 14:02:15.731  5879  5899 I bt_hci  : event_finish_startup
,11-22 14:02:15.732  5879  5899 I bt_hci_h4: hal_open
,11-22 14:02:15.732  5879  5899 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-22 14:02:15.729  5900  5900 W irq/448-msm_hs_: type=1400 audit(0.0:117): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
11-22 14:02:15.735  5879  5899 I bt_userial_vendor: device fd = 54 open
,11-22 14:02:15.749  5879  5899 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-22 14:02:15.752  5879  5899 D bt_hwcfg: Chipset BCM4358A3
,11-22 14:02:15.752  5879  5899 D bt_hwcfg: Target name = [BCM4358A3]
11-22 14:02:15.753  5879  5899 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-22 14:02:16.130  5879  5899 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-22 14:02:16.131  5879  5899 D bt_hwcfg: Settlement delay -- 100 ms
,11-22 14:02:16.131  5879  5899 I bt_hwcfg: Setting fw settlement delay to 100 
,11-22 14:02:16.265  5879  5899 I bt_hwcfg: bt vendor lib: set UART baud 3000000
11-22 14:02:16.266  5879  5899 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
11-22 14:02:16.268  5879  5899 I bt_hwcfg: vendor lib fwcfg completed
11-22 14:02:16.268  5879  5899 I bt_vendor: firmware callback
11-22 14:02:16.268  5879  5899 I bt_hci  : firmware_config_callback
,11-22 14:02:16.277  5879  5902 I bt_btu  : btu_task pending for preload complete event
,11-22 14:02:16.277  5879  5902 I bt_btu_task: Bluetooth chip preload is complete
,11-22 14:02:16.277  5879  5902 I bt_btu  : btu_task received preload complete event
,11-22 14:02:16.285  5879  5902 I         : BTE_InitTraceLevels -- TRC_HCI
,11-22 14:02:16.285  5879  5902 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-22 14:02:16.285  5879  5902 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-22 14:02:16.285  5879  5902 I         : BTE_InitTraceLevels -- TRC_AVDT
,11-22 14:02:16.285  5879  5902 I         : BTE_InitTraceLevels -- TRC_AVRC
11-22 14:02:16.285  5879  5902 I         : BTE_InitTraceLevels -- TRC_A2D
11-22 14:02:16.285  5879  5902 I         : BTE_InitTraceLevels -- TRC_BNEP
11-22 14:02:16.285  5879  5902 I         : BTE_InitTraceLevels -- TRC_BTM
,11-22 14:02:16.286  5879  5902 I         : BTE_InitTraceLevels -- TRC_GAP
11-22 14:02:16.286  5879  5902 I         : BTE_InitTraceLevels -- TRC_PAN
,11-22 14:02:16.286  5879  5902 I         : BTE_InitTraceLevels -- TRC_SDP
11-22 14:02:16.286  5879  5902 I         : BTE_InitTraceLevels -- TRC_GATT
,11-22 14:02:16.286  5879  5902 I         : BTE_InitTraceLevels -- TRC_SMP
11-22 14:02:16.286  5879  5902 I         : BTE_InitTraceLevels -- TRC_BTAPP
,11-22 14:02:16.286  5879  5902 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-22 14:02:16.372  5879  5902 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3b2b549
11-22 14:02:16.372  5879  5902 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3b2b549 
,11-22 14:02:16.394  5879  5895 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-22 14:02:16.395  5879  5895 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-22 14:02:16.396  5879  5895 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-22 14:02:16.398  5879  5895 D BluetoothAdapterProperties: Name is: Nexus 6P
11-22 14:02:16.400  5879  5895 D BluetoothAdapterProperties: Scan Mode:20
11-22 14:02:16.400  5879  5895 D BluetoothAdapterProperties: Discoverable Timeout:120
11-22 14:02:16.400  5879  5895 D bt_hci  : do_postload posting postload work item
,11-22 14:02:16.400  5879  5899 I bt_hci  : event_postload
11-22 14:02:16.401  5879  5899 I bt_vendor: sco_config_cb
11-22 14:02:16.401  5879  5899 I bt_hci  : sco_config_callback postload finished.
,11-22 14:02:16.405  5705  5705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-22 14:02:16.406  5879  5895 D bt_bte_conf: Device ID record 1 : primary
11-22 14:02:16.407  5879  5895 D bt_bte_conf:   vendorId            = 000f
11-22 14:02:16.407  5879  5895 D bt_bte_conf:   vendorIdSource      = 0001
11-22 14:02:16.407  5879  5895 D bt_bte_conf:   product             = 1200
,11-22 14:02:16.407  5879  5895 D bt_bte_conf:   version             = 1436
11-22 14:02:16.407  5879  5895 D bt_bte_conf:   clientExecutableURL = 
11-22 14:02:16.407  5879  5895 D bt_bte_conf:   serviceDescription  = 
11-22 14:02:16.407  5879  5895 D bt_bte_conf:   documentationURL    = 
11-22 14:02:16.407  5879  5895 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-22 14:02:16.407  5879  5892 D bt_stack_manager: event_start_up_stack finished
,11-22 14:02:16.409  5879  5899 I bt_vendor: low_power_mode_cb
,11-22 14:02:16.409  5879  5891 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-22 14:02:16.409  5879  5891 D BluetoothAdapterProperties: Setting state to 15
11-22 14:02:16.409  5879  5891 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-22 14:02:16.412  5879  5891 I BluetoothAdapterState: Entering BleOnState
,11-22 14:02:16.415  5879  5891 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-22 14:02:16.415  5879  5891 D BluetoothAdapterProperties: Setting state to 11
11-22 14:02:16.415  5879  5891 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-22 14:02:16.419  5879  5879 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b705d8d
,11-22 14:02:16.422  5705  5705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-22 14:02:16.422  5879  5879 D HeadsetService: Received start request. Starting profile...
,11-22 14:02:16.426  5879  5879 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,11-22 14:02:16.426  5879  5879 D HeadsetStateMachine: make
,11-22 14:02:16.432  5879  5891 I BluetoothAdapterState: Entering PendingCommandState
,11-22 14:02:16.438  5879  5879 D HeadsetStateMachine: max_hf_connections = 1
11-22 14:02:16.438  5879  5879 I bt_bluedroid: get_profile_interface handsfree
11-22 14:02:16.438  5879  5895 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-22 14:02:16.438  5879  5895 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,11-22 14:02:16.440  5879  5879 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b705d8d
11-22 14:02:16.441  5879  5879 D A2dpService: Received start request. Starting profile...
11-22 14:02:16.442  5879  5879 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-22 14:02:16.442  5879  5879 I bt_bluedroid: get_profile_interface avrcp
,11-22 14:02:16.447  5879  5879 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-22 14:02:16.448  5879  5879 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-22 14:02:16.448  5879  5879 D A2dpStateMachine: make
,11-22 14:02:16.449  5879  5879 I bt_bluedroid: get_profile_interface a2dp
11-22 14:02:16.449  5879  5895 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-22 14:02:16.451  5879  5911 D A2dpStateMachine: Enter Disconnected: -2
,11-22 14:02:16.452  5879  5879 I BluetoothHidServiceJni: classInitNative: succeeds
,11-22 14:02:16.453  3672  3672 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-22 14:02:16.453  5879  5879 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b705d8d
,11-22 14:02:16.455  5879  5879 D HidService: Received start request. Starting profile...
,11-22 14:02:16.455  5775  5775 D BluetoothInputDevice: Proxy object connected
11-22 14:02:16.455  5879  5879 I bt_bluedroid: get_profile_interface hidhost
11-22 14:02:16.455  5879  5895 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3b0c56d
11-22 14:02:16.455  5879  5879 D HidService: setHidService(): set to: null
11-22 14:02:16.456  5879  5895 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-22 14:02:16.456  5775  5775 D HidProfile: Bluetooth service connected
11-22 14:02:16.456  5879  5879 I BluetoothHealthServiceJni: classInitNative: succeeds
11-22 14:02:16.457  5879  5879 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b705d8d
11-22 14:02:16.457  5879  5879 D HealthService: Received start request. Starting profile...
,11-22 14:02:16.458  5879  5879 I bt_bluedroid: get_profile_interface health
,11-22 14:02:16.459  5879  5879 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-22 14:02:16.460  5879  5879 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b705d8d
,11-22 14:02:16.461  5879  5879 D PanService: Received start request. Starting profile...
11-22 14:02:16.461  5879  5879 D BluetoothPanServiceJni: initializeNative(L110): pan
11-22 14:02:16.462  5879  5879 I bt_bluedroid: get_profile_interface pan
11-22 14:02:16.462  5879  5895 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,11-22 14:02:16.463  5775  5775 D BluetoothPan: BluetoothPAN Proxy object connected
11-22 14:02:16.464  5879  5879 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b705d8d
11-22 14:02:16.464  5775  5775 D PanProfile: Bluetooth service connected
11-22 14:02:16.465  5879  5879 D BluetoothMapService: Received start request. Starting profile...
11-22 14:02:16.465  5775  5775 D BluetoothMap: Proxy object connected
11-22 14:02:16.465  5879  5879 D BluetoothMapService: start()
11-22 14:02:16.467  5775  5775 D MapProfile: Bluetooth service connected
,11-22 14:02:16.467  5775  5775 D BluetoothMap: getConnectedDevices()
11-22 14:02:16.467  5879  5879 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
11-22 14:02:16.467  5775  5775 D BluetoothMap: Bluetooth is Not enabled
11-22 14:02:16.468  5879  5879 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-22 14:02:16.468  5879  5879 D BluetoothMapAppObserver: createReceiver()
,11-22 14:02:16.469  5879  5879 D BluetoothMapAppObserver: initObservers()
,11-22 14:02:16.469  5879  5879 D BluetoothMapAppObserver: getEnabledAccountItems()
11-22 14:02:16.475  5879  5879 V SapService: SapBinder()
11-22 14:02:16.475  5879  5879 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b705d8d
,11-22 14:02:16.475  5879  5879 D SapService: Received start request. Starting profile...
11-22 14:02:16.475  5879  5879 V SapService: start()
,11-22 14:02:16.478  5879  5879 V BluetoothAdapterState: isTurningOff()=false
11-22 14:02:16.478  5879  5879 V BluetoothAdapterState: isTurningOn()=true
11-22 14:02:16.478  5879  5879 V BluetoothAdapterState: isBleTurningOn()=false
,11-22 14:02:16.478  5879  5909 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-22 14:02:16.478  5879  5879 V BluetoothAdapterState: isBleTurningOff()=false
11-22 14:02:16.478  5879  5879 V BluetoothAdapterState: isTurningOff()=false
11-22 14:02:16.478  5879  5879 V BluetoothAdapterState: isTurningOn()=true
11-22 14:02:16.478  5879  5879 V BluetoothAdapterState: isBleTurningOn()=false
11-22 14:02:16.478  5879  5879 V BluetoothAdapterState: isBleTurningOff()=false
,11-22 14:02:16.479  5879  5879 V BluetoothAdapterState: isTurningOff()=false
11-22 14:02:16.479  5879  5879 V BluetoothAdapterState: isTurningOn()=true
11-22 14:02:16.479  5879  5879 V BluetoothAdapterState: isBleTurningOn()=false
11-22 14:02:16.479  5879  5879 V BluetoothAdapterState: isBleTurningOff()=false
11-22 14:02:16.480  5879  5879 V BluetoothAdapterState: isTurningOff()=false
11-22 14:02:16.480  5879  5879 V BluetoothAdapterState: isTurningOn()=true
11-22 14:02:16.480  5879  5879 V BluetoothAdapterState: isBleTurningOn()=false
11-22 14:02:16.480  5879  5879 V BluetoothAdapterState: isBleTurningOff()=false
11-22 14:02:16.480  5879  5879 V BluetoothAdapterState: isTurningOff()=false
,11-22 14:02:16.480  5879  5879 V BluetoothAdapterState: isTurningOn()=true
,11-22 14:02:16.488  5879  5879 V BluetoothAdapterState: isBleTurningOn()=false
11-22 14:02:16.488  5879  5879 V BluetoothAdapterState: isBleTurningOff()=false
11-22 14:02:16.488  5879  5879 V BluetoothAdapterState: isTurningOff()=false
11-22 14:02:16.488  5879  5879 V BluetoothAdapterState: isTurningOn()=true
11-22 14:02:16.489  5879  5879 V BluetoothAdapterState: isBleTurningOn()=false
11-22 14:02:16.489  5879  5879 V BluetoothAdapterState: isBleTurningOff()=false
,11-22 14:02:16.489  5879  5879 V BluetoothAdapterState: isTurningOff()=false
11-22 14:02:16.489  5879  5879 V BluetoothAdapterState: isTurningOn()=true
11-22 14:02:16.490  5879  5879 V BluetoothAdapterState: isBleTurningOn()=false
,11-22 14:02:16.490  5879  5879 V BluetoothAdapterState: isBleTurningOff()=false
,11-22 14:02:16.490  5879  5891 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,11-22 14:02:16.490  5879  5891 D BluetoothAdapterProperties: ScanMode =  20
11-22 14:02:16.490  5879  5891 D BluetoothAdapterProperties: State =  11
11-22 14:02:16.491  5879  5891 D BluetoothAdapterProperties: Setting state to 12
11-22 14:02:16.491  5879  5891 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-22 14:02:16.491  3227  3241 D BluetoothPan: onBluetoothStateChange on: true
11-22 14:02:16.491  5879  5895 D BluetoothAdapterProperties: Scan Mode:21
11-22 14:02:16.492  5879  5895 D BluetoothAdapterProperties: Discoverable Timeout:120
11-22 14:02:16.492  5705  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,11-22 14:02:16.493  5879  5891 I BluetoothAdapterState: Entering OnState
11-22 14:02:16.493  3227  3227 D BluetoothPan: BluetoothPAN Proxy object connected
11-22 14:02:16.493  3227  3227 D PanProfile: Bluetooth service connected
11-22 14:02:16.493  3227  4084 D BluetoothHeadset: onBluetoothStateChange: up=true
11-22 14:02:16.494  3227  3238 D BluetoothMap: onBluetoothStateChange: up=true
11-22 14:02:16.495  5879  5879 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-22 14:02:16.495  5879  5879 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-22 14:02:16.496  5705  5705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-22 14:02:16.496  5705  5705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 14:02:16.496  5705  5705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 14:02:16.496  5705  5705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-22 14:02:16.496  5705  5705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-22 14:02:16.496  5705  5705 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-22 14:02:16.496  5705  5705 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-22 14:02:16.496  5705  5705 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-22 14:02:16.496  5705  5705 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-22 14:02:16.496  3227  4084 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-22 14:02:16.496  3227  3227 D BluetoothMap: Proxy object connected
,11-22 14:02:16.496  3227  3227 D MapProfile: Bluetooth service connected
11-22 14:02:16.496  3227  3227 D BluetoothMap: getConnectedDevices()
11-22 14:02:16.497  5879  5879 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-22 14:02:16.498   933   950 D BluetoothHeadset: onBluetoothStateChange: up=true
11-22 14:02:16.498  5775  5789 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-22 14:02:16.499  5775  5795 D BluetoothMap: onBluetoothStateChange: up=true
,11-22 14:02:16.499  3227  3238 D BluetoothPbap: onBluetoothStateChange: up=true
,11-22 14:02:16.499  5879  5879 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-22 14:02:16.499  5705  5705 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-22 14:02:16.500  3227  3227 D BluetoothInputDevice: Proxy object connected
11-22 14:02:16.500  3227  3227 D HidProfile: Bluetooth service connected
11-22 14:02:16.500  3891  3912 D BluetoothHeadset: onBluetoothStateChange: up=true
11-22 14:02:16.502  5879  5879 D ObexServerSockets: Succeed to create listening sockets 
11-22 14:02:16.502  5879  5879 D ObexServerSockets0: startAccept()
11-22 14:02:16.502  5879  5879 D ObexServerSockets0: prepareForNewConnect()
11-22 14:02:16.503  5775  5789 D BluetoothPan: onBluetoothStateChange on: true
11-22 14:02:16.503   933   950 D BluetoothHeadset: onBluetoothStateChange: up=true
11-22 14:02:16.503   933   950 D BluetoothA2dp: onBluetoothStateChange: up=true
11-22 14:02:16.504  5879  5879 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-22 14:02:16.504  5879  5879 D BluetoothSdpJni: SDP Create record success - handle: 0
,11-22 14:02:16.504  3227  3241 D BluetoothA2dp: onBluetoothStateChange: up=true
11-22 14:02:16.505  5879  5916 D ObexServerSockets0: Accepting socket connection...
11-22 14:02:16.505  5879  5917 D ObexServerSockets0: Accepting socket connection...
11-22 14:02:16.505   933   933 D BluetoothA2dp: Proxy object connected
11-22 14:02:16.506   933   950 D BluetoothHeadset: onBluetoothStateChange: up=true
11-22 14:02:16.506  3227  3227 D BluetoothA2dp: Proxy object connected
11-22 14:02:16.506  5775  5795 D BluetoothPbap: onBluetoothStateChange: up=true
11-22 14:02:16.508   933   933 I Telecom : BluetoothPhoneService: queryPhoneState
11-22 14:02:16.509  5879  5879 D BluetoothMapService: onReceive
11-22 14:02:16.509  5879  5879 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-22 14:02:16.510  5879  5879 D BluetoothMapService: STATE_ON
,11-22 14:02:16.511  5705  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,11-22 14:02:16.512  5705  5705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-22 14:02:16.513  5775  5775 D LocalBluetoothProfileManager: Adding local A2DP profile
11-22 14:02:16.513  5879  5919 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-22 14:02:16.515  5879  5919 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-22 14:02:16.515  5879  5919 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-22 14:02:16.517  5775  5775 D LocalBluetoothProfileManager: Adding local HEADSET profile
,11-22 14:02:16.522  5775  5775 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-22 14:02:16.524  5775  5775 D BluetoothA2dp: Proxy object connected
,11-22 14:02:16.529  3672  3672 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-22 14:02:16.530  5775  5775 D DockEventReceiver: finishStartingService: stopping service
,11-22 14:02:16.538  5879  5879 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-22 14:02:16.538  3227  3227 D BluetoothPbap: Proxy object connected
11-22 14:02:16.538  5775  5775 D BluetoothPbap: Proxy object connected
11-22 14:02:16.538  5879  5879 D ObexServerSockets0: prepareForNewConnect()
11-22 14:02:16.538  3227  3227 D PbapServerProfile: Bluetooth service connected
11-22 14:02:16.538  5775  5775 D PbapServerProfile: Bluetooth service connected
,11-22 14:02:16.545  5879  5923 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-22 14:02:16.557  5879  5927 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-22 14:02:16.560  5879  5927 I BtOppRfcommListener: Accept thread started.
,11-22 14:02:16.595   933   933 D BluetoothHeadset: Proxy object connected
,11-22 14:02:16.596  3227  3241 D BluetoothHeadset: Proxy object connected
11-22 14:02:16.596  3227  3227 D HeadsetProfile: Bluetooth service connected
11-22 14:02:16.596   933   933 D BluetoothHeadset: Proxy object connected
11-22 14:02:16.596  3891  4092 D BluetoothHeadset: Proxy object connected
11-22 14:02:16.596   933   933 D BluetoothHeadset: Proxy object connected
11-22 14:02:16.597   933   950 D BluetoothHeadset: Proxy object connected
,11-22 14:02:16.603  3891  3914 D BluetoothHeadset: Proxy object connected
,11-22 14:02:16.604   933   950 D BluetoothHeadset: Proxy object connected
,11-22 14:02:16.606   933   950 D BluetoothHeadset: Proxy object connected
,11-22 14:02:16.620  5775  5795 D BluetoothHeadset: Proxy object connected
,11-22 14:02:16.622  5775  5775 D HeadsetProfile: Bluetooth service connected
,11-22 14:02:18.263   933  3077 D ConnectivityService: handlePromptUnvalidated 101
,11-22 14:02:18.837  3764  3973 I Keyboard.Facilitator.LanguageModelFlusher: run()
,11-22 14:02:18.837  3764  3973 I Keyboard.Facilitator: flushDynamicLanguageModels()
,11-22 14:02:18.864  3672  3672 I ConfigService: onCreate
,11-22 14:02:19.979   534   534 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-22 14:02:19.979   534   534 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-22 14:02:20.441  5879  5891 D BluetoothAdapterState: Current state: ON, message: 23
,11-22 14:02:20.441  5879  5891 D BluetoothAdapterProperties: Setting state to 13
11-22 14:02:20.441  5879  5891 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,11-22 14:02:20.443  5879  5891 D BluetoothAdapterProperties: onBluetoothDisable()
11-22 14:02:20.445  5879  5891 I BluetoothAdapterState: Entering PendingCommandState
,11-22 14:02:20.447  5879  5895 D BluetoothAdapterProperties: Scan Mode:20
,11-22 14:02:20.448  5879  5891 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,11-22 14:02:20.458  5879  5879 D BluetoothMapService: onReceive
,11-22 14:02:20.458  5879  5879 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-22 14:02:20.458  5705  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-22 14:02:20.458  5879  5879 D BluetoothMapService: STATE_TURNING_OFF
11-22 14:02:20.458  5705  5705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-22 14:02:20.458  5705  5705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 14:02:20.458  5705  5705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 14:02:20.458  5705  5705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-22 14:02:20.458  5705  5705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-22 14:02:20.458  5705  5705 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-22 14:02:20.458  5705  5705 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-22 14:02:20.458  5705  5705 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-22 14:02:20.458  5705  5705 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-22 14:02:20.459  5879  5879 D BluetoothMapService: MAP Service closeService in
11-22 14:02:20.459  5879  5879 D BluetoothMapMasInstance0: MAP Service shutdown
11-22 14:02:20.459  5879  5879 D ObexServerSockets0: shutdown(block = true)
11-22 14:02:20.460  5879  5879 D ObexServerSockets0: shutdown called from another thread - interrupt().
,11-22 14:02:20.460  5879  5916 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
11-22 14:02:20.460  5705  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-22 14:02:20.461  5705  5705 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-22 14:02:20.461  5879  5904 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,11-22 14:02:20.461  5879  5917 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,11-22 14:02:20.464  5879  5879 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-22 14:02:20.466  5705  5705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-22 14:02:20.468  5879  5879 I BtOppRfcommListener: stopping Accept Thread
11-22 14:02:20.468  5879  5927 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,11-22 14:02:20.468  5775  5775 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-22 14:02:20.469  5879  5927 I BtOppRfcommListener: BluetoothSocket listen thread finished
11-22 14:02:20.477  5879  5879 D HeadsetService: Received stop request...Stopping profile...
11-22 14:02:20.480  5775  5775 D DockEventReceiver: finishStartingService: stopping service
11-22 14:02:20.482   933   933 D BluetoothHeadset: Proxy object disconnected
11-22 14:02:20.482  3227  4084 D BluetoothHeadset: Proxy object disconnected
11-22 14:02:20.483   933   933 D BluetoothHeadset: Proxy object disconnected
,11-22 14:02:20.483  3891  4093 D BluetoothHeadset: Proxy object disconnected
11-22 14:02:20.483   933   933 D BluetoothHeadset: Proxy object disconnected
11-22 14:02:20.484  5775  5795 D BluetoothHeadset: Proxy object disconnected
11-22 14:02:20.485  3227  3227 D HeadsetProfile: Bluetooth service disconnected
11-22 14:02:20.485  5879  5879 D A2dpService: Received stop request...Stopping profile...
11-22 14:02:20.485  5879  5911 D A2dpStateMachine: Exit Disconnected: -1
,11-22 14:02:20.486  5775  5775 D HeadsetProfile: Bluetooth service disconnected
11-22 14:02:20.488   933   933 D BluetoothA2dp: Proxy object disconnected
11-22 14:02:20.489  3227  3227 D BluetoothA2dp: Proxy object disconnected
11-22 14:02:20.489  5879  5879 D HidService: Received stop request...Stopping profile...
11-22 14:02:20.489  5879  5879 D HidService: Stopping Bluetooth HidService
11-22 14:02:20.489  5775  5775 D BluetoothA2dp: Proxy object disconnected
11-22 14:02:20.490  3227  3227 D BluetoothInputDevice: Proxy object disconnected
,11-22 14:02:20.490  3227  3227 D HidProfile: Bluetooth service disconnected
11-22 14:02:20.490  5775  5775 D BluetoothInputDevice: Proxy object disconnected
11-22 14:02:20.490  5775  5775 D HidProfile: Bluetooth service disconnected
11-22 14:02:20.492  5879  5879 D HealthService: Received stop request...Stopping profile...
,11-22 14:02:20.496  5879  5879 D PanService: Received stop request...Stopping profile...
,11-22 14:02:20.497  3227  3227 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-22 14:02:20.497  5775  5775 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-22 14:02:20.497  3227  3227 D PanProfile: Bluetooth service disconnected
11-22 14:02:20.497  5775  5775 D PanProfile: Bluetooth service disconnected
11-22 14:02:20.498  5879  5879 D BluetoothMapService: Received stop request...Stopping profile...
,11-22 14:02:20.498  5879  5879 D BluetoothMapService: stop()
,11-22 14:02:20.499  5879  5879 D BluetoothMapAppObserver: deinitObservers()
,11-22 14:02:20.499  5879  5879 D BluetoothMapAppObserver: removeReceiver()
11-22 14:02:20.500  3227  3227 D BluetoothMap: Proxy object disconnected
11-22 14:02:20.500  3227  3227 D MapProfile: Bluetooth service disconnected
11-22 14:02:20.501  5775  5775 D BluetoothMap: Proxy object disconnected
,11-22 14:02:20.501  5775  5775 D MapProfile: Bluetooth service disconnected
11-22 14:02:20.501  5879  5879 V BluetoothAdapterState: isTurningOff()=true
11-22 14:02:20.501  5879  5879 V BluetoothAdapterState: isTurningOn()=false
,11-22 14:02:20.501  5879  5879 V BluetoothAdapterState: isBleTurningOn()=false
11-22 14:02:20.501  5879  5879 V BluetoothAdapterState: isBleTurningOff()=false
,11-22 14:02:20.505  3672  3672 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-22 14:02:20.506  5879  5879 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-22 14:02:20.506  5879  5879 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-22 14:02:20.506  5879  5902 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-22 14:02:20.506  5879  5902 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-22 14:02:20.506  5879  5902 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-22 14:02:20.507  5879  5895 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-22 14:02:20.507  5879  5879 D SapService: Received stop request...Stopping profile...
11-22 14:02:20.507  5879  5895 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-22 14:02:20.507  5879  5879 V SapService: stop()
,11-22 14:02:20.511  5879  5879 V BluetoothAdapterState: isTurningOff()=true
,11-22 14:02:20.512  5879  5879 V BluetoothAdapterState: isTurningOn()=false
11-22 14:02:20.512  5879  5879 V BluetoothAdapterState: isBleTurningOn()=false
11-22 14:02:20.512  5879  5879 V BluetoothAdapterState: isBleTurningOff()=false
,11-22 14:02:20.513  5879  5895 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,11-22 14:02:20.513  5879  5902 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-22 14:02:20.513  5879  5879 V BluetoothAdapterState: isTurningOff()=true
11-22 14:02:20.513  5879  5879 V BluetoothAdapterState: isTurningOn()=false
11-22 14:02:20.513  5879  5879 V BluetoothAdapterState: isBleTurningOn()=false
11-22 14:02:20.513  5879  5902 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-22 14:02:20.513  5879  5879 V BluetoothAdapterState: isBleTurningOff()=false
11-22 14:02:20.513  5879  5902 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-22 14:02:20.513  5879  5902 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,11-22 14:02:20.513  5879  5902 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-22 14:02:20.513  5879  5902 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-22 14:02:20.513  5879  5879 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-22 14:02:20.513  5879  5879 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-22 14:02:20.514  5879  5879 V BluetoothAdapterState: isTurningOff()=true
11-22 14:02:20.514  5879  5879 V BluetoothAdapterState: isTurningOn()=false
,11-22 14:02:20.514  5879  5879 V BluetoothAdapterState: isBleTurningOn()=false
11-22 14:02:20.514  5879  5879 V BluetoothAdapterState: isBleTurningOff()=false
11-22 14:02:20.514  5879  5879 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-22 14:02:20.515  5879  5895 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-22 14:02:20.515  5879  5879 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-22 14:02:20.515  5879  5895 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-22 14:02:20.515  5879  5879 V BluetoothAdapterState: isTurningOff()=true
11-22 14:02:20.515  5879  5879 V BluetoothAdapterState: isTurningOn()=false
11-22 14:02:20.515  5879  5879 V BluetoothAdapterState: isBleTurningOn()=false
11-22 14:02:20.515  5879  5879 V BluetoothAdapterState: isBleTurningOff()=false
,11-22 14:02:20.515  5879  5879 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-22 14:02:20.515  5879  5879 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-22 14:02:20.516  5879  5879 D BluetoothMapService: MAP Service closeService in
11-22 14:02:20.516  5879  5879 V BluetoothAdapterState: isTurningOff()=true
11-22 14:02:20.516  5879  5879 V BluetoothAdapterState: isTurningOn()=false
11-22 14:02:20.516  5879  5879 V BluetoothAdapterState: isBleTurningOn()=false
11-22 14:02:20.516  5879  5879 V BluetoothAdapterState: isBleTurningOff()=false
11-22 14:02:20.517  5879  5879 D BluetoothMapService: cleanup()
11-22 14:02:20.517  5879  5879 D BluetoothMapService: MAP Service closeService in
,11-22 14:02:20.519  3227  3227 D BluetoothPbap: Proxy object disconnected
,11-22 14:02:20.519  3227  3227 D PbapServerProfile: Bluetooth service disconnected
11-22 14:02:20.519  5879  5879 V BluetoothAdapterState: isTurningOff()=true
11-22 14:02:20.519  5879  5879 V BluetoothAdapterState: isTurningOn()=false
11-22 14:02:20.519  5879  5879 V BluetoothAdapterState: isBleTurningOn()=false
11-22 14:02:20.519  5879  5879 V BluetoothAdapterState: isBleTurningOff()=false
11-22 14:02:20.519  5879  5891 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-22 14:02:20.519  5879  5891 D BluetoothAdapterProperties: Setting state to 15
11-22 14:02:20.519  5879  5891 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,11-22 14:02:20.520  5879  5891 I BluetoothAdapterState: Entering BleOnState
,11-22 14:02:20.522  3227  4084 D BluetoothPan: onBluetoothStateChange on: false
,11-22 14:02:20.523  5775  5775 D BluetoothPbap: Proxy object disconnected
11-22 14:02:20.523  5775  5775 D PbapServerProfile: Bluetooth service disconnected
11-22 14:02:20.524  3227  3238 D BluetoothHeadset: onBluetoothStateChange: up=false
11-22 14:02:20.525  3227  3241 D BluetoothMap: onBluetoothStateChange: up=false
11-22 14:02:20.525  3227  4084 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-22 14:02:20.526   933   950 D BluetoothHeadset: onBluetoothStateChange: up=false
11-22 14:02:20.526  5775  5789 D BluetoothInputDevice: onBluetoothStateChange: up=false
,11-22 14:02:20.527  5775  5795 D BluetoothMap: onBluetoothStateChange: up=false
,11-22 14:02:20.527  3227  3238 D BluetoothPbap: onBluetoothStateChange: up=false
11-22 14:02:20.528  3891  3912 D BluetoothHeadset: onBluetoothStateChange: up=false
11-22 14:02:20.528  5775  5789 D BluetoothHeadset: onBluetoothStateChange: up=false
11-22 14:02:20.528  5775  5795 D BluetoothPan: onBluetoothStateChange on: false
11-22 14:02:20.529   933   950 D BluetoothHeadset: onBluetoothStateChange: up=false
11-22 14:02:20.529   933   950 D BluetoothA2dp: onBluetoothStateChange: up=false
11-22 14:02:20.529  3227  3241 D BluetoothA2dp: onBluetoothStateChange: up=false
11-22 14:02:20.530  5775  5789 D BluetoothA2dp: onBluetoothStateChange: up=false
,11-22 14:02:20.530   933   950 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-22 14:02:20.531  5775  5795 D BluetoothPbap: onBluetoothStateChange: up=false
,11-22 14:02:20.532  5879  5891 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-22 14:02:20.532  5879  5891 D BluetoothAdapterProperties: Setting state to 16
11-22 14:02:20.532  5879  5891 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,11-22 14:02:20.533  5879  5891 D BluetoothAdapterProperties: onBleDisable
11-22 14:02:20.533  5879  5891 I BluetoothAdapterState: Entering PendingCommandState
11-22 14:02:20.533  5879  5892 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-22 14:02:20.535  5879  5895 D BluetoothAdapterProperties: Scan Mode:20
11-22 14:02:20.536  5775  5775 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-22 14:02:20.541  5879  5902 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,11-22 14:02:20.541  5879  5902 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-22 14:02:20.546  5705  5705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-22 14:02:20.548  5705  5705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-22 14:02:20.549  3672  3672 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-22 14:02:20.549  5775  5775 D DockEventReceiver: finishStartingService: stopping service
,11-22 14:02:20.760  5879  5895 I bt_hci  : shut_down
,11-22 14:02:20.772  5879  5899 D bt_hwcfg: hw_epilog_process
,11-22 14:02:20.772  5879  5899 I bt_vendor: low_power_mode_cb
,11-22 14:02:20.775  5879  5899 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
11-22 14:02:20.775  5879  5899 I bt_vendor: epilog_cb
,11-22 14:02:20.775  5879  5899 I bt_hci  : epilog_finished_callback
,11-22 14:02:20.782  5879  5895 I bt_hci_h4: hal_close
,11-22 14:02:20.783  5879  5895 I bt_userial_vendor: device fd = 54 close
,11-22 14:02:20.904  5879  5892 D bt_stack_manager: event_shut_down_stack finished.
,11-22 14:02:20.905  5879  5891 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-22 14:02:20.909  5879  5891 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,11-22 14:02:20.909  5879  5879 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-22 14:02:20.910  5879  5879 D BtGatt.GattService: Received stop request...Stopping profile...
,11-22 14:02:20.910  5879  5879 D BtGatt.GattService: stop()
11-22 14:02:20.910  5879  5879 D BtGatt.AdvertiseManager: advertise clients cleared
11-22 14:02:20.914  5879  5879 V BluetoothAdapterState: isTurningOff()=false
11-22 14:02:20.915  5879  5879 V BluetoothAdapterState: isTurningOn()=false
11-22 14:02:20.915  5879  5879 V BluetoothAdapterState: isBleTurningOn()=false
,11-22 14:02:20.915  5879  5879 V BluetoothAdapterState: isBleTurningOff()=true
11-22 14:02:20.916  5879  5891 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-22 14:02:20.916  5879  5891 D BluetoothAdapterProperties: Setting state to 10
,11-22 14:02:20.917  5879  5891 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,11-22 14:02:20.918  5879  5891 I BluetoothAdapterState: Entering OffState
11-22 14:02:20.919   933   950 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,11-22 14:02:20.930  5879  5879 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-22 14:02:20.930  5879  5879 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-22 14:02:20.931  5879  5879 I BluetoothServiceJni: cleanupNative: return from cleanup
,11-22 14:02:20.933  5879  5892 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-22 14:02:20.940  5879  5879 I art     : System.exit called, status: 0
,11-22 14:02:20.940  5879  5879 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-22 14:02:20.969   933  3979 I ActivityManager: Process com.android.bluetooth (pid 5879) has died
,11-22 14:02:23.893  3672  3672 I ConfigService: onDestroy
,11-22 14:02:25.440  5705  5751 D io.jxcore.node.ConnectivityMonitor: stop
,11-22 14:02:25.441  5705  5751 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-22 14:02:25.447  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-22 14:02:25.447  5705  5751 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ea1dd24 removed from the list
11-22 14:02:25.447  5705  5751 D io.jxcore.node.ConnectivityMonitor: stop
,11-22 14:02:25.450  5705  5751 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-22 14:02:25.450  5705  5751 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@86ff253 added. We now have 4 listener(s)
,11-22 14:02:25.451  5705  5751 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-22 14:02:25.453  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:02:25.453  5705  5751 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@86ff253 removed from the list
,11-22 14:02:25.453  5705  5751 D io.jxcore.node.ConnectivityMonitor: stop
,11-22 14:02:25.455  5705  5751 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-22 14:02:25.455  5705  5751 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2b1a790 added. We now have 4 listener(s)
,11-22 14:02:25.456  5705  5751 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-22 14:02:29.981   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:02:30.468  5705  5751 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-22 14:02:30.503   933   950 I ActivityManager: Start proc 5938:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-22 14:02:30.600  5938  5938 D AdapterServiceConfig: Adding HeadsetService
,11-22 14:02:30.600  5938  5938 D AdapterServiceConfig: Adding A2dpService
11-22 14:02:30.600  5938  5938 D AdapterServiceConfig: Adding HidService
11-22 14:02:30.600  5938  5938 D AdapterServiceConfig: Adding HealthService
11-22 14:02:30.600  5938  5938 D AdapterServiceConfig: Adding PanService
11-22 14:02:30.601  5938  5938 D AdapterServiceConfig: Adding GattService
11-22 14:02:30.601  5938  5938 D AdapterServiceConfig: Adding BluetoothMapService
,11-22 14:02:30.601  5938  5938 D AdapterServiceConfig: Adding SapService
,11-22 14:02:30.616   933   950 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4604f3c:true
,11-22 14:02:30.616  5938  5938 D BluetoothAdapterState: make() - Creating AdapterState
,11-22 14:02:30.621  5938  5938 I bt_bluedroid: init
,11-22 14:02:30.622  5938  5950 I BluetoothAdapterState: Entering OffState
,11-22 14:02:30.625  5938  5951 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-22 14:02:30.625  5938  5951 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-22 14:02:30.625  5938  5951 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,11-22 14:02:30.625  5938  5951 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,11-22 14:02:30.626  5938  5938 I bt_bluedroid: get_profile_interface socket
,11-22 14:02:30.628  5938  5954 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-22 14:02:30.629  5938  5938 I bt_bluedroid: get_profile_interface sdp
,11-22 14:02:30.630  5938  5954 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-22 14:02:30.635  5938  5949 I bt_bluedroid: config_hci_snoop_log
11-22 14:02:30.636   933   950 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-22 14:02:30.642  5938  5950 D BluetoothAdapterState: Current state: OFF, message: 0
11-22 14:02:30.642  5938  5950 D BluetoothAdapterProperties: Setting state to 14
,11-22 14:02:30.642  5938  5950 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
11-22 14:02:30.644  5938  5950 D BluetoothBondStateMachine: make
,11-22 14:02:30.647  5938  5955 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-22 14:02:30.651  5938  5950 I BluetoothAdapterState: Entering PendingCommandState
,11-22 14:02:30.653  5938  5938 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-22 14:02:30.656  5938  5938 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b705d8d
,11-22 14:02:30.657  5938  5938 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-22 14:02:30.658  5938  5938 D BtGatt.GattService: Received start request. Starting profile...
11-22 14:02:30.658  5938  5938 D BtGatt.GattService: start()
11-22 14:02:30.658  5938  5938 I bt_bluedroid: get_profile_interface gatt
,11-22 14:02:30.659  5938  5938 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b705d8d
,11-22 14:02:30.660  5938  5938 D BtGatt.AdvertiseManager: advertise manager created
,11-22 14:02:30.667  5938  5938 V BluetoothAdapterState: isTurningOff()=false
,11-22 14:02:30.667  5938  5938 V BluetoothAdapterState: isTurningOn()=false
11-22 14:02:30.667  5938  5938 V BluetoothAdapterState: isBleTurningOn()=true
,11-22 14:02:30.667  5938  5938 V BluetoothAdapterState: isBleTurningOff()=false
11-22 14:02:30.667  5938  5950 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
11-22 14:02:30.669  5938  5950 I bt_bluedroid: bt_bluedroid
,11-22 14:02:30.669  5938  5951 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,11-22 14:02:30.670  5938  5951 I bt_hci  : start_up
,11-22 14:02:30.676  5938  5951 I bt_vendor: alloc value 0xf3bad871
11-22 14:02:30.676  5938  5951 I bt_vendor: init
,11-22 14:02:30.676  5938  5951 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-22 14:02:30.676  5938  5951 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-22 14:02:30.786  5938  5951 D bt_hci  : start_up starting async portion
,11-22 14:02:30.787  5938  5958 I bt_hci  : event_finish_startup
11-22 14:02:30.787  5938  5958 I bt_hci_h4: hal_open
11-22 14:02:30.787  5938  5958 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-22 14:02:30.785  5959  5959 W irq/448-msm_hs_: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-22 14:02:30.792  5938  5958 I bt_userial_vendor: device fd = 54 open
,11-22 14:02:30.808  5938  5958 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-22 14:02:30.812  5938  5958 D bt_hwcfg: Chipset BCM4358A3
11-22 14:02:30.812  5938  5958 D bt_hwcfg: Target name = [BCM4358A3]
11-22 14:02:30.813  5938  5958 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-22 14:02:30.982   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:02:31.319  5938  5958 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-22 14:02:31.319  5938  5958 D bt_hwcfg: Settlement delay -- 100 ms
,11-22 14:02:31.319  5938  5958 I bt_hwcfg: Setting fw settlement delay to 100 
,11-22 14:02:31.453  5938  5958 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-22 14:02:31.453  5938  5958 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
,11-22 14:02:31.455  5938  5958 I bt_hwcfg: vendor lib fwcfg completed
,11-22 14:02:31.455  5938  5958 I bt_vendor: firmware callback
,11-22 14:02:31.455  5938  5958 I bt_hci  : firmware_config_callback
,11-22 14:02:31.466  5938  5961 I bt_btu  : btu_task pending for preload complete event
11-22 14:02:31.467  5938  5961 I bt_btu_task: Bluetooth chip preload is complete
,11-22 14:02:31.467  5938  5961 I bt_btu  : btu_task received preload complete event
,11-22 14:02:31.475  5938  5961 I         : BTE_InitTraceLevels -- TRC_HCI
,11-22 14:02:31.476  5938  5961 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-22 14:02:31.476  5938  5961 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,11-22 14:02:31.476  5938  5961 I         : BTE_InitTraceLevels -- TRC_AVDT
,11-22 14:02:31.476  5938  5961 I         : BTE_InitTraceLevels -- TRC_AVRC
11-22 14:02:31.476  5938  5961 I         : BTE_InitTraceLevels -- TRC_A2D
,11-22 14:02:31.476  5938  5961 I         : BTE_InitTraceLevels -- TRC_BNEP
11-22 14:02:31.476  5938  5961 I         : BTE_InitTraceLevels -- TRC_BTM
,11-22 14:02:31.476  5938  5961 I         : BTE_InitTraceLevels -- TRC_GAP
11-22 14:02:31.476  5938  5961 I         : BTE_InitTraceLevels -- TRC_PAN
,11-22 14:02:31.476  5938  5961 I         : BTE_InitTraceLevels -- TRC_SDP
,11-22 14:02:31.476  5938  5961 I         : BTE_InitTraceLevels -- TRC_GATT
11-22 14:02:31.477  5938  5961 I         : BTE_InitTraceLevels -- TRC_SMP
11-22 14:02:31.477  5938  5961 I         : BTE_InitTraceLevels -- TRC_BTAPP
,11-22 14:02:31.477  5938  5961 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-22 14:02:31.574  5938  5961 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3b2b549
,11-22 14:02:31.574  5938  5961 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3b2b549 
,11-22 14:02:31.595  5938  5954 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-22 14:02:31.599  5938  5954 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-22 14:02:31.600  5938  5954 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-22 14:02:31.603  5938  5954 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-22 14:02:31.607  5938  5954 D BluetoothAdapterProperties: Scan Mode:20
11-22 14:02:31.608  5938  5954 D BluetoothAdapterProperties: Discoverable Timeout:120
,11-22 14:02:31.608  5938  5954 D bt_hci  : do_postload posting postload work item
11-22 14:02:31.608  5938  5958 I bt_hci  : event_postload
11-22 14:02:31.608  5938  5958 I bt_vendor: sco_config_cb
11-22 14:02:31.609  5938  5958 I bt_hci  : sco_config_callback postload finished.
11-22 14:02:31.610  5938  5954 D bt_bte_conf: Device ID record 1 : primary
11-22 14:02:31.610  5938  5954 D bt_bte_conf:   vendorId            = 000f
,11-22 14:02:31.610  5938  5954 D bt_bte_conf:   vendorIdSource      = 0001
11-22 14:02:31.610  5938  5954 D bt_bte_conf:   product             = 1200
11-22 14:02:31.610  5938  5954 D bt_bte_conf:   version             = 1436
11-22 14:02:31.610  5938  5954 D bt_bte_conf:   clientExecutableURL = 
11-22 14:02:31.610  5938  5954 D bt_bte_conf:   serviceDescription  = 
,11-22 14:02:31.611  5938  5954 D bt_bte_conf:   documentationURL    = 
11-22 14:02:31.611  5938  5954 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-22 14:02:31.611  5938  5951 D bt_stack_manager: event_start_up_stack finished
11-22 14:02:31.612  5938  5950 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-22 14:02:31.612  5938  5950 D BluetoothAdapterProperties: Setting state to 15
11-22 14:02:31.612  5938  5950 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-22 14:02:31.615  5938  5950 I BluetoothAdapterState: Entering BleOnState
,11-22 14:02:31.621  5938  5958 I bt_vendor: low_power_mode_cb
,11-22 14:02:31.622  5938  5950 D BluetoothAdapterState: Current state: BLE ON, message: 1
,11-22 14:02:31.622  5938  5950 D BluetoothAdapterProperties: Setting state to 11
,11-22 14:02:31.622  5938  5950 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-22 14:02:31.632  5938  5938 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b705d8d
,11-22 14:02:31.633  5938  5938 D HeadsetService: Received start request. Starting profile...
11-22 14:02:31.635  5938  5938 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-22 14:02:31.636  5938  5938 D HeadsetStateMachine: make
,11-22 14:02:31.648  5938  5950 I BluetoothAdapterState: Entering PendingCommandState
11-22 14:02:31.649  5938  5938 D HeadsetStateMachine: max_hf_connections = 1
11-22 14:02:31.649  5938  5938 I bt_bluedroid: get_profile_interface handsfree
,11-22 14:02:31.650  5938  5954 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,11-22 14:02:31.650  5938  5954 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,11-22 14:02:31.654  5938  5938 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b705d8d
11-22 14:02:31.654  5938  5938 D A2dpService: Received start request. Starting profile...
11-22 14:02:31.655  5938  5938 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-22 14:02:31.655  5938  5938 I bt_bluedroid: get_profile_interface avrcp
,11-22 14:02:31.660  5938  5938 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-22 14:02:31.661  5938  5938 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-22 14:02:31.661  5938  5938 D A2dpStateMachine: make
11-22 14:02:31.662  5938  5938 I bt_bluedroid: get_profile_interface a2dp
,11-22 14:02:31.665  5938  5954 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-22 14:02:31.666  5938  5969 D A2dpStateMachine: Enter Disconnected: -2
11-22 14:02:31.668  5938  5938 I BluetoothHidServiceJni: classInitNative: succeeds
11-22 14:02:31.668  5938  5938 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b705d8d
11-22 14:02:31.669  5938  5938 D HidService: Received start request. Starting profile...
11-22 14:02:31.670  5938  5938 I bt_bluedroid: get_profile_interface hidhost
11-22 14:02:31.670  5938  5938 D HidService: setHidService(): set to: null
11-22 14:02:31.670  5938  5938 I BluetoothHealthServiceJni: classInitNative: succeeds
11-22 14:02:31.671  3672  3672 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-22 14:02:31.671  5938  5954 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3b0c56d
,11-22 14:02:31.671  5938  5954 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-22 14:02:31.671  5938  5938 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b705d8d
11-22 14:02:31.671  5938  5938 D HealthService: Received start request. Starting profile...
,11-22 14:02:31.673  5938  5938 I bt_bluedroid: get_profile_interface health
,11-22 14:02:31.673  5938  5938 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-22 14:02:31.674  5938  5938 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b705d8d
,11-22 14:02:31.675  5938  5938 D PanService: Received start request. Starting profile...
11-22 14:02:31.675  5938  5938 D BluetoothPanServiceJni: initializeNative(L110): pan
11-22 14:02:31.675  5938  5938 I bt_bluedroid: get_profile_interface pan
11-22 14:02:31.675  5938  5954 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
11-22 14:02:31.677  5938  5938 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b705d8d
,11-22 14:02:31.678  5938  5938 D BluetoothMapService: Received start request. Starting profile...
,11-22 14:02:31.678  5938  5938 D BluetoothMapService: start()
11-22 14:02:31.680  5938  5938 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
11-22 14:02:31.681  5938  5938 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-22 14:02:31.681  5938  5938 D BluetoothMapAppObserver: createReceiver()
11-22 14:02:31.682  5938  5938 D BluetoothMapAppObserver: initObservers()
11-22 14:02:31.682  5938  5938 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-22 14:02:31.689  5938  5938 V SapService: SapBinder()
,11-22 14:02:31.689  5938  5938 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b705d8d
11-22 14:02:31.689  5938  5938 D SapService: Received start request. Starting profile...
11-22 14:02:31.689  5938  5938 V SapService: start()
,11-22 14:02:31.691  5938  5938 V BluetoothAdapterState: isTurningOff()=false
11-22 14:02:31.691  5938  5938 V BluetoothAdapterState: isTurningOn()=true
11-22 14:02:31.691  5938  5938 V BluetoothAdapterState: isBleTurningOn()=false
11-22 14:02:31.691  5938  5938 V BluetoothAdapterState: isBleTurningOff()=false
11-22 14:02:31.692  5938  5938 V BluetoothAdapterState: isTurningOff()=false
11-22 14:02:31.692  5938  5938 V BluetoothAdapterState: isTurningOn()=true
11-22 14:02:31.692  5938  5938 V BluetoothAdapterState: isBleTurningOn()=false
,11-22 14:02:31.692  5938  5938 V BluetoothAdapterState: isBleTurningOff()=false
11-22 14:02:31.692  5938  5966 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-22 14:02:31.692  5938  5938 V BluetoothAdapterState: isTurningOff()=false
11-22 14:02:31.692  5938  5938 V BluetoothAdapterState: isTurningOn()=true
11-22 14:02:31.692  5938  5938 V BluetoothAdapterState: isBleTurningOn()=false
11-22 14:02:31.692  5938  5938 V BluetoothAdapterState: isBleTurningOff()=false
11-22 14:02:31.693  5938  5938 V BluetoothAdapterState: isTurningOff()=false
11-22 14:02:31.693  5938  5938 V BluetoothAdapterState: isTurningOn()=true
11-22 14:02:31.693  5938  5938 V BluetoothAdapterState: isBleTurningOn()=false
11-22 14:02:31.693  5938  5938 V BluetoothAdapterState: isBleTurningOff()=false
,11-22 14:02:31.693  5938  5938 V BluetoothAdapterState: isTurningOff()=false
11-22 14:02:31.693  5938  5938 V BluetoothAdapterState: isTurningOn()=true
11-22 14:02:31.693  5938  5938 V BluetoothAdapterState: isBleTurningOn()=false
11-22 14:02:31.693  5938  5938 V BluetoothAdapterState: isBleTurningOff()=false
11-22 14:02:31.693  5938  5938 V BluetoothAdapterState: isTurningOff()=false
11-22 14:02:31.693  5938  5938 V BluetoothAdapterState: isTurningOn()=true
11-22 14:02:31.694  5938  5938 V BluetoothAdapterState: isBleTurningOn()=false
11-22 14:02:31.694  5938  5938 V BluetoothAdapterState: isBleTurningOff()=false
,11-22 14:02:31.695  5938  5938 V BluetoothAdapterState: isTurningOff()=false
11-22 14:02:31.695  5938  5938 V BluetoothAdapterState: isTurningOn()=true
11-22 14:02:31.695  5938  5938 V BluetoothAdapterState: isBleTurningOn()=false
11-22 14:02:31.695  5938  5938 V BluetoothAdapterState: isBleTurningOff()=false
,11-22 14:02:31.695  5938  5950 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,11-22 14:02:31.695  5938  5950 D BluetoothAdapterProperties: ScanMode =  20
11-22 14:02:31.695  5938  5950 D BluetoothAdapterProperties: State =  11
11-22 14:02:31.695  5938  5950 D BluetoothAdapterProperties: Setting state to 12
11-22 14:02:31.696  5938  5950 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-22 14:02:31.696  5938  5950 I BluetoothAdapterState: Entering OnState
11-22 14:02:31.696  3227  4084 D BluetoothPan: onBluetoothStateChange on: true
11-22 14:02:31.698  5938  5954 D BluetoothAdapterProperties: Scan Mode:21
11-22 14:02:31.698  5938  5954 D BluetoothAdapterProperties: Discoverable Timeout:120
11-22 14:02:31.698  3227  3241 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-22 14:02:31.699  3227  3241 D BluetoothMap: onBluetoothStateChange: up=true
11-22 14:02:31.699  3227  3227 D BluetoothPan: BluetoothPAN Proxy object connected
11-22 14:02:31.699  3227  3227 D PanProfile: Bluetooth service connected
11-22 14:02:31.701  3227  4084 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-22 14:02:31.702  3227  3227 D BluetoothMap: Proxy object connected
11-22 14:02:31.702  3227  3227 D MapProfile: Bluetooth service connected
11-22 14:02:31.702  3227  3227 D BluetoothMap: getConnectedDevices()
11-22 14:02:31.703   933   950 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-22 14:02:31.703  5775  5795 D BluetoothInputDevice: onBluetoothStateChange: up=true
,11-22 14:02:31.705  3227  3227 D BluetoothInputDevice: Proxy object connected
,11-22 14:02:31.705  3227  3227 D HidProfile: Bluetooth service connected
11-22 14:02:31.705  5775  5789 D BluetoothMap: onBluetoothStateChange: up=true
,11-22 14:02:31.707  5938  5938 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-22 14:02:31.707  3227  3241 D BluetoothPbap: onBluetoothStateChange: up=true
11-22 14:02:31.707  5938  5938 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-22 14:02:31.708  5938  5938 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-22 14:02:31.709  3891  3914 D BluetoothHeadset: onBluetoothStateChange: up=true
11-22 14:02:31.709  5775  5789 D BluetoothHeadset: onBluetoothStateChange: up=true
11-22 14:02:31.710  5775  5795 D BluetoothPan: onBluetoothStateChange on: true
11-22 14:02:31.710  5938  5938 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-22 14:02:31.711  5938  5938 D ObexServerSockets: Succeed to create listening sockets 
11-22 14:02:31.711  5938  5938 D ObexServerSockets0: startAccept()
11-22 14:02:31.711  5938  5938 D ObexServerSockets0: prepareForNewConnect()
,11-22 14:02:31.711   933   950 D BluetoothHeadset: onBluetoothStateChange: up=true
11-22 14:02:31.711   933   950 D BluetoothA2dp: onBluetoothStateChange: up=true
11-22 14:02:31.713  3227  4084 D BluetoothA2dp: onBluetoothStateChange: up=true
11-22 14:02:31.713  5938  5938 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-22 14:02:31.714  5938  5938 D BluetoothSdpJni: SDP Create record success - handle: 0
11-22 14:02:31.714  5938  5975 D ObexServerSockets0: Accepting socket connection...
11-22 14:02:31.714  5938  5976 D ObexServerSockets0: Accepting socket connection...
11-22 14:02:31.715  5775  5789 D BluetoothA2dp: onBluetoothStateChange: up=true
11-22 14:02:31.715   933   933 D BluetoothA2dp: Proxy object connected
11-22 14:02:31.715  3227  3227 D BluetoothA2dp: Proxy object connected
11-22 14:02:31.716  5775  5775 D BluetoothInputDevice: Proxy object connected
,11-22 14:02:31.716  5775  5775 D HidProfile: Bluetooth service connected
11-22 14:02:31.717   933   950 D BluetoothHeadset: onBluetoothStateChange: up=true
11-22 14:02:31.717  5775  5795 D BluetoothPbap: onBluetoothStateChange: up=true
11-22 14:02:31.720  5938  5938 D BluetoothMapService: onReceive
11-22 14:02:31.720  5938  5938 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-22 14:02:31.720   933   933 I Telecom : BluetoothPhoneService: queryPhoneState
11-22 14:02:31.720  5938  5938 D BluetoothMapService: STATE_ON
11-22 14:02:31.722  5775  5775 D BluetoothMap: Proxy object connected
11-22 14:02:31.722  5775  5775 D MapProfile: Bluetooth service connected
11-22 14:02:31.722  5775  5775 D BluetoothMap: getConnectedDevices()
11-22 14:02:31.723  5938  5978 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-22 14:02:31.723  5775  5775 D BluetoothPan: BluetoothPAN Proxy object connected
,11-22 14:02:31.723  5775  5775 D PanProfile: Bluetooth service connected
11-22 14:02:31.723  5775  5775 D BluetoothA2dp: Proxy object connected
11-22 14:02:31.724  5938  5978 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-22 14:02:31.724  5938  5978 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-22 14:02:31.729  5775  5775 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-22 14:02:31.733  5775  5775 D DockEventReceiver: finishStartingService: stopping service
,11-22 14:02:31.735  3672  3672 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-22 14:02:31.742  3227  3227 D BluetoothPbap: Proxy object connected
,11-22 14:02:31.742  3227  3227 D PbapServerProfile: Bluetooth service connected
,11-22 14:02:31.744  5775  5775 D BluetoothPbap: Proxy object connected
11-22 14:02:31.744  5775  5775 D PbapServerProfile: Bluetooth service connected
,11-22 14:02:31.746  5938  5938 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-22 14:02:31.746  5938  5938 D ObexServerSockets0: prepareForNewConnect()
,11-22 14:02:31.750  5938  5982 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-22 14:02:31.766  5938  5986 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-22 14:02:31.768  5938  5986 I BtOppRfcommListener: Accept thread started.
,11-22 14:02:31.801   933   933 D BluetoothHeadset: Proxy object connected
,11-22 14:02:31.801  3227  4084 D BluetoothHeadset: Proxy object connected
11-22 14:02:31.801   933   933 D BluetoothHeadset: Proxy object connected
11-22 14:02:31.802  3227  3227 D HeadsetProfile: Bluetooth service connected
11-22 14:02:31.802  3891  4093 D BluetoothHeadset: Proxy object connected
,11-22 14:02:31.803   933   933 D BluetoothHeadset: Proxy object connected
11-22 14:02:31.803   933   950 D BluetoothHeadset: Proxy object connected
11-22 14:02:31.803  5775  5795 D BluetoothHeadset: Proxy object connected
,11-22 14:02:31.805  5775  5775 D HeadsetProfile: Bluetooth service connected
,11-22 14:02:31.809  3891  3912 D BluetoothHeadset: Proxy object connected
,11-22 14:02:31.810  5775  5974 D BluetoothHeadset: Proxy object connected
11-22 14:02:31.810  5775  5775 D HeadsetProfile: Bluetooth service connected
11-22 14:02:31.811   933   950 D BluetoothHeadset: Proxy object connected
,11-22 14:02:31.817   933   950 D BluetoothHeadset: Proxy object connected
,11-22 14:02:31.983   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:02:32.984   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:02:33.985   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:02:34.986   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-22 14:02:35.483  5705  5751 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-22 14:02:35.483  5705  5751 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 14:02:35.483  5705  5751 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 14:02:35.483  5705  5751 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-22 14:02:35.483  5705  5751 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-22 14:02:35.483  5705  5751 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-22 14:02:35.483  5705  5751 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-22 14:02:35.483  5705  5751 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-22 14:02:35.483  5705  5751 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-22 14:02:35.488  5705  5751 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-22 14:02:35.489  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-22 14:02:35.490  5705  5751 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2b1a790 removed from the list
,11-22 14:02:35.490  5705  5751 D io.jxcore.node.ConnectivityMonitor: stop
,11-22 14:02:35.492  5705  5751 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-22 14:02:35.492  5705  5751 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@126889 added. We now have 4 listener(s)
,11-22 14:02:35.492  5705  5751 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-22 14:02:35.497   933  3947 D WifiService: setWifiEnabled: false pid=5705, uid=10077
,11-22 14:02:35.497   933  3947 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-22 14:02:39.987   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:02:40.507  5705  5751 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-22 14:02:40.508   933  3964 D WifiService: setWifiEnabled: true pid=5705, uid=10077
11-22 14:02:40.508   933  3964 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-22 14:02:40.516   502   927 D SoftapController: Softap fwReload - Ok
,11-22 14:02:40.522   502   927 D CommandListener: Setting iface cfg
11-22 14:02:40.522   502   927 D CommandListener: Trying to bring down wlan0
,11-22 14:02:40.525   502   927 D CommandListener: Clearing all IP addresses on wlan0
,11-22 14:02:40.531   933  3072 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-22 14:02:40.989   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:02:41.213   933  3072 D wifi    : set interface wlan0 flags (UP)
,11-22 14:02:41.213   933  3072 I WifiHAL : Initializing wifi
11-22 14:02:41.214   933  3072 I WifiHAL : Creating socket
11-22 14:02:41.219   933  3072 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-22 14:02:41.219   933  3072 D wifi    : Did set static halHandle = 0x7f70c92300
11-22 14:02:41.220   933  3072 D wifi    : halHandle = 0x7f70c92300, mVM = 0x7f8d2cd140, mCls = 0x2015ce
11-22 14:02:41.220   933  3072 D wifi    : array field set
11-22 14:02:41.220   933  3072 I WifiNative-HAL: interface[0] = wlan0
11-22 14:02:41.222   933  5992 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547353076480
11-22 14:02:41.222   933  5992 D wifi    : waitForHalEvents called, vm = 0x7f8d2cd140, obj = 0x2015ce, env = 0x7f6e823ac0
11-22 14:02:41.224   933   950 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-22 14:02:41.271  5993  5993 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-22 14:02:41.324   933  3072 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-22 14:02:41.340  5993  5993 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-22 14:02:41.425  5993  5993 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-22 14:02:41.425  5993  5993 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-22 14:02:41.454   933  3072 D WifiConfigStore: Loading config and enabling all networks 
,11-22 14:02:41.483   933  3072 D WifiConfigStore: loaded 0 passpoint configs
,11-22 14:02:41.485   933  3072 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
,11-22 14:02:41.485   933  3072 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,11-22 14:02:41.486   933  3072 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,11-22 14:02:41.487   933  3072 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
,11-22 14:02:41.488   933  3072 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
11-22 14:02:41.489   933  3072 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,11-22 14:02:41.489   933  3072 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-22 14:02:41.489   933  3072 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-22 14:02:41.489   933  3072 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
11-22 14:02:41.489   933  3072 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-22 14:02:41.490   933  3072 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-22 14:02:41.490   933  3072 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-22 14:02:41.493   933  3072 D WifiNative-HAL: Setting external_sim to 1
,11-22 14:02:41.493   933  3072 D wifi    : setting dfs flag to true, 0x7f6e861ea0
11-22 14:02:41.493   933  3072 D WifiStateMachine: Setting OUI to DA-A1-19
11-22 14:02:41.493  5089  5089 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-22 14:02:41.493   933  3072 D wifi    : setting scan oui 0x7f6e861ea0
11-22 14:02:41.493   933  3072 D WifiHAL : Sending mac address OUI
,11-22 14:02:41.497   933  3072 E native  : do suspend false
,11-22 14:02:41.506   933  3072 D wifi    : android_net_wifi_setLinkLayerStats: 1
11-22 14:02:41.506   933   933 D RttService: SCAN_AVAILABLE : 3
11-22 14:02:41.506   502   927 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
11-22 14:02:41.506   933  3180 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,11-22 14:02:41.507   502   927 D CommandListener: Setting iface cfg
,11-22 14:02:41.512   933  3071 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '157 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 157 Failed to set address (No such device)'
11-22 14:02:41.512   933  3071 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-22 14:02:41.522   933  3071 D WifiNative-HAL: p2pGetDeviceAddress
,11-22 14:02:41.528   933  3071 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
11-22 14:02:41.528   933   948 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=240690 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=16 mControllerEnergyUsed=60 }
,11-22 14:02:41.992   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:02:42.993   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:02:43.994   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:02:44.596  5993  5993 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-22 14:02:44.601  5993  5993 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-22 14:02:44.606  5993  5993 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-22 14:02:44.611  5993  5993 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-22 14:02:44.652   933  3072 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-22 14:02:44.653   933  3072 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-22 14:02:44.653   933  3072 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-22 14:02:44.663   933  3072 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-22 14:02:44.697   933  3072 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-22 14:02:44.702  5993  5993 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-22 14:02:44.994   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-22 14:02:45.132  5993  5993 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e,
,11-22 14:02:45.173  5993  5993 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-22 14:02:45.174  5993  5993 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-22 14:02:45.182   933  3072 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
11-22 14:02:45.183   933  3072 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-22 14:02:45.183   933  3077 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-22 14:02:45.202   933  3072 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-22 14:02:45.215   502   927 D CommandListener: Setting iface cfg
,11-22 14:02:45.221   933  3072 D WifiStateMachine: Start Dhcp Watchdog 3
,11-22 14:02:45.228   933  5998 D DhcpClient: Receive thread started
,11-22 14:02:45.233   933  3077 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-22 14:02:45.233   933  3072 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
11-22 14:02:45.233   933  3077 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,11-22 14:02:45.314   933  3072 E native  : do suspend false
,11-22 14:02:45.326   933  5997 D DhcpClient: Broadcasting DHCPDISCOVER
,11-22 14:02:45.343   933  5998 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.109, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,11-22 14:02:45.343   933  5997 D DhcpClient: Got pending lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
,11-22 14:02:45.345   933  5997 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.109 serverid=192.168.1.1
,11-22 14:02:45.420   933  5998 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.109, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-22 14:02:45.421   933  5997 D DhcpClient: Confirmed lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-22 14:02:45.423   502   927 D CommandListener: Setting iface cfg
11-22 14:02:45.428   933  3072 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-22 14:02:45.432   933  5997 D DhcpClient: Scheduling renewal in 86399s
,11-22 14:02:45.442   933  3072 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
11-22 14:02:45.443   933  3072 D WifiConfigStore: No blacklist allowed without epno enabled
,11-22 14:02:45.443   933  3077 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
11-22 14:02:45.445   933  3077 D ConnectivityService: Adding iface wlan0 to network 102
11-22 14:02:45.445   933  3072 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-22 14:02:45.491   933  3077 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-22 14:02:45.492   933  3077 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,11-22 14:02:45.494   933  3077 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,11-22 14:02:45.496   933  3077 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,11-22 14:02:45.499   933  3077 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,11-22 14:02:45.507   933  3077 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-22 14:02:45.512   933  3077 D ConnectivityService: scheduleUnvalidatedPrompt 102
,11-22 14:02:45.512   933  3077 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
11-22 14:02:45.512   933  3077 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
11-22 14:02:45.512   933  3077 D ConnectivityService:    accepting network in place of null
11-22 14:02:45.516   933  3077 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -55]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-22 14:02:45.521   933  3072 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-22 14:02:45.521   933  3072 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-22 14:02:45.523  5705  5751 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-22 14:02:45.523  5705  5751 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 14:02:45.523  5705  5751 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 14:02:45.523  5705  5751 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-22 14:02:45.523  5705  5751 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-22 14:02:45.523  5705  5751 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-22 14:02:45.523  5705  5751 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-22 14:02:45.523  5705  5751 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-22 14:02:45.523  5705  5751 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-22 14:02:45.526  5705  5751 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-22 14:02:45.526  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:02:45.526  5705  5751 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@126889 removed from the list
11-22 14:02:45.526  5705  5751 D io.jxcore.node.ConnectivityMonitor: stop
,11-22 14:02:45.531  5705  5751 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,11-22 14:02:45.532  5705  5751 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,11-22 14:02:45.534  5705  5751 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@2d890 Bundle[{}]
,11-22 14:02:45.535  5705  5751 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-22 14:02:45.535  5705  5751 I io.jxcore.node.LifeCycleMonitor: stop: OK
11-22 14:02:45.536  5705  5751 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
11-22 14:02:45.536  5705  5751 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
11-22 14:02:45.536  5705  5751 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
11-22 14:02:45.536   933  5996 D NetlinkSocketObserver: NeighborEvent{elapsedMs=244698, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
11-22 14:02:45.537  5705  5751 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,11-22 14:02:45.543  5705  5751 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 169)
,11-22 14:02:45.543   502   927 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-22 14:02:45.543  5705  5751 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
11-22 14:02:45.543  5705  5751 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 170)
,11-22 14:02:45.545  5705  5751 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-22 14:02:45.546  5705  5751 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6a6708e added. We now have 3 listener(s)
11-22 14:02:45.547  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-22 14:02:45.547  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-22 14:02:45.547  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-22 14:02:45.547  5705  5751 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-22 14:02:45.547  5705  5751 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6fd60af added. We now have 4 listener(s)
11-22 14:02:45.547  5705  5751 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-22 14:02:45.548  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-22 14:02:45.549  5705  5751 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-22 14:02:45.549  5705  5751 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b1acbc added. We now have 4 listener(s)
11-22 14:02:45.550  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-22 14:02:45.550  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-22 14:02:45.550  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-22 14:02:45.550  5705  5751 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-22 14:02:45.550  5705  5751 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ab00445 added. We now have 5 listener(s)
11-22 14:02:45.551  5705  5751 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-22 14:02:45.551  5705  5751 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 14:02:45.551  5705  5751 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 14:02:45.551  5705  5751 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-22 14:02:45.551  5705  5751 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 14:02:45.551  5705  5751 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 14:02:45.551  5705  5751 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-22 14:02:45.551  5705  5751 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6a6708e removed from the list
11-22 14:02:45.551  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:02:45.551  5705  5751 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6fd60af removed from the list
11-22 14:02:45.551  5705  5751 D io.jxcore.node.ConnectivityMonitor: stop
11-22 14:02:45.551  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.551  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-22 14:02:45.553  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.553  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.553  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.553  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 14:02:45.553  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 14:02:45.553  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:02:45.553  5705  5751 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6fd60af not in the list
11-22 14:02:45.553  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.553  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-22 14:02:45.555  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.555  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.555  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.555  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-22 14:02:45.555  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 14:02:45.555  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:02:45.555  5705  5751 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ab00445 removed from the list
11-22 14:02:45.555  5705  5751 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 14:02:45.555  5705  5751 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 14:02:45.555  5705  5751 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-22 14:02:45.555  5705  5751 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b1acbc removed from the list
11-22 14:02:45.556  5705  5751 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-22 14:02:45.556  5705  5751 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9d079a added. We now have 3 listener(s)
11-22 14:02:45.557  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-22 14:02:45.557  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-22 14:02:45.557  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-22 14:02:45.557  5705  5751 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-22 14:02:45.557  5705  5751 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@64958cb added. We now have 4 listener(s)
11-22 14:02:45.558  5705  5751 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-22 14:02:45.558  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-22 14:02:45.560  5705  5751 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-22 14:02:45.560  5705  5751 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e4ad8a8 added. We now have 4 listener(s)
,11-22 14:02:45.561  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-22 14:02:45.561  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-22 14:02:45.561  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-22 14:02:45.561  5705  5751 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-22 14:02:45.562  5705  5751 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dd19fc1 added. We now have 5 listener(s)
11-22 14:02:45.562  5705  5751 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-22 14:02:45.562  5705  5751 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-22 14:02:45.562  5705  5751 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-22 14:02:45.562  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-22 14:02:45.562  5705  5751 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-22 14:02:45.562  5705  5751 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-22 14:02:45.563  5705  5751 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-22 14:02:45.564   502   927 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-22 14:02:45.566  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-22 14:02:45.567  5705  5751 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-22 14:02:45.567  5705  5751 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-22 14:02:45.567   933  3077 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
11-22 14:02:45.567   933  3077 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-22 14:02:45.567  3867  3983 W QCNEJ   : |CORE| network available: 102
,11-22 14:02:45.568   933  3077 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
11-22 14:02:45.569   933   950 D Tethering: MasterInitialState.processMessage what=3
,11-22 14:02:45.574  3867  3983 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-22 14:02:45.574  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.574  5705  5751 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-22 14:02:45.575  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-22 14:02:45.575  5705  5751 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-22 14:02:45.575  3867  3983 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-22 14:02:45.575  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-22 14:02:45.576  3867  3983 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-22 14:02:45.581  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-22 14:02:45.581  5705  5751 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-22 14:02:45.581  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-22 14:02:45.581  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-22 14:02:45.581  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-22 14:02:45.581  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.581  5705  5751 D BluetoothAdapter: STATE_ON
,11-22 14:02:45.584  5938  5977 D BtGatt.GattService: registerClient() - UUID=3d392fe2-cbd1-4e4a-902b-61a4727c7b89
11-22 14:02:45.584  5938  5954 D BtGatt.GattService: onClientRegistered() - UUID=3d392fe2-cbd1-4e4a-902b-61a4727c7b89, clientIf=5
,11-22 14:02:45.585  5705  5716 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-22 14:02:45.586  5938  5967 D BtGatt.GattService: start scan with filters
11-22 14:02:45.588  5140  5164 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-22 14:02:45.588  5140  5164 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-22 14:02:45.588  5140  5164 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
11-22 14:02:45.588  5140  5164 E SarControlService: no key has been found,reset the power
11-22 14:02:45.588  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-22 14:02:45.588  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.588  5140  5176 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-22 14:02:45.588  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-22 14:02:45.588  5938  5957 D BtGatt.ScanManager: handling starting scan
11-22 14:02:45.588  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.588  5140  5176 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-22 14:02:45.588  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-22 14:02:45.588  5140  5176 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-22 14:02:45.588  5705  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,11-22 14:02:45.588  5705  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-22 14:02:45.588  5705  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-22 14:02:45.589  5705  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-22 14:02:45.589  5705  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-22 14:02:45.589  5705  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-22 14:02:45.589  5705  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-22 14:02:45.589  5165  5165 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-22 14:02:45.589  5705  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-22 14:02:45.589  5165  5165 D QcrilMsgTunnelSocket: [1008] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-22 14:02:45.589  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-22 14:02:45.589  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.590  5938  5957 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b705d8d
11-22 14:02:45.590  4067  4067 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
11-22 14:02:45.591  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.591  5140  5176 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
,11-22 14:02:45.591  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-22 14:02:45.592  5140  5176 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-22 14:02:45.592  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.592  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.592  5140  5176 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-22 14:02:45.592  5705  5751 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-22 14:02:45.592  5705  5705 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-22 14:02:45.592  5705  5751 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-22 14:02:45.592  5705  5751 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-22 14:02:45.592  5705  5751 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-22 14:02:45.592  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-22 14:02:45.592  5705  5751 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 14:02:45.592  5705  5751 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-22 14:02:45.592  5165  5165 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-22 14:02:45.592  5165  5165 D QcrilMsgTunnelSocket: [1009] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-22 14:02:45.595  3816  3816 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-22 14:02:45.595  5705  5705 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-22 14:02:45.596  5705  5705 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-22 14:02:45.596  5705  5705 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-22 14:02:45.596  5705  5705 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-22 14:02:45.596  5938  5954 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-22 14:02:45.596  5938  5954 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 14:02:45.596  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-22 14:02:45.596  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.596  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-22 14:02:45.596  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-22 14:02:45.596  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.596  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current th,read: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.596  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.596  5705  5751 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-22 14:02:45.596  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.597  5938  5957 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-22 14:02:45.597  5705  5751 D BluetoothAdapter: STATE_ON
11-22 14:02:45.597  5938  5967 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-22 14:02:45.597  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-22 14:02:45.598  5705  5751 D BluetoothAdapter: STATE_ON
11-22 14:02:45.599  5938  5977 D BtGatt.GattService: stopScan() - queue size =1
11-22 14:02:45.599  5165  5179 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@3ebd1a5 HexData = [00000000f003000000000000ffffffff]
11-22 14:02:45.599  5165  5179 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-22 14:02:45.599  5165  5179 D QcrilMsgTunnelSocket: [1008] < OEM_HOOK_RAW [null]
11-22 14:02:45.599  5165  5165 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-22 14:02:45.599  5140  5151 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-22 14:02:45.599  5938  5967 D BtGatt.GattService: unregisterClient() - clientIf=5
11-22 14:02:45.599  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-22 14:02:45.600  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.600  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-22 14:02:45.600  3816  3816 D SystemUpdateService: onCreate
11-22 14:02:45.600  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.600  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.600  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.600  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.600  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-22 14:02:45.600  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.600  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.600  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.600  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,11-22 14:02:45.600  5705  5751 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-22 14:02:45.601  5705  5751 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-22 14:02:45.601  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.602  5938  5954 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-22 14:02:45.602  5938  5954 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 14:02:45.602  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.602  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-22 14:02:45.602  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.602  5938  5957 D BtGatt.ScanManager: Starting BLE batch scan
11-22 14:02:45.602  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.602  5938  5957 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-22 14:02:45.602  5705  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-22 14:02:45.602  5705  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-22 14:02:45.602  5705  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-22 14:02:45.603  5705  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-22 14:02:45.603  5705  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-22 14:02:45.603  5705  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-22 14:02:45.603  5705  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-22 14:02:45.603  5705  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-22 14:02:45.603  5705  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-22 14:02:45.603  5705  5705 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-22 14:02:45.603  5705  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-22 14:02:45.603  5705  5705 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-22 14:02:45.604  5705  5705 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-22 14:02:45.605  5705  5705 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-22 14:02:45.605  5705  5705 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-22 14:02:45.606  5705  5751 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and k,illing connections
11-22 14:02:45.606  5705  5751 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 14:02:45.606  5705  5751 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 14:02:45.606  5705  5751 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 14:02:45.606  5705  5751 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 14:02:45.607  5705  5751 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-22 14:02:45.607  5705  5751 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9d079a removed from the list
11-22 14:02:45.607  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:02:45.607  5705  5751 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@64958cb removed from the list
11-22 14:02:45.607  5705  5751 D io.jxcore.node.ConnectivityMonitor: stop
11-22 14:02:45.607  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.607  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.608  3816  3816 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
11-22 14:02:45.608  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.608  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.608  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.608  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 14:02:45.608  5165  5179 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@3ebd1a5 HexData = [00000000f103000000000000ffffffff]
11-22 14:02:45.608  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 14:02:45.608  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:02:45.608  5165  5179 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-22 14:02:45.608  5165  5179 D QcrilMsgTunnelSocket: [1009] < OEM_HOOK_RAW [null]
11-22 14:02:45.608  5705  5751 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@64958cb not in the list
11-22 14:02:45.608  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.608  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.609  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.609  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.609  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.609  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 14:02:45.610  5705  5751 I org.tha,liproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 14:02:45.610  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:02:45.610  5705  5751 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dd19fc1 removed from the list
11-22 14:02:45.610  5705  5751 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 14:02:45.610  5705  5751 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 14:02:45.610  5705  5751 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-22 14:02:45.610  5705  5751 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e4ad8a8 removed from the list
11-22 14:02:45.612  5705  5751 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-22 14:02:45.612  5705  5751 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eceff2 added. We now have 3 listener(s)
11-22 14:02:45.612  5938  5954 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-22 14:02:45.612  5938  5954 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 14:02:45.613  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-22 14:02:45.613  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-22 14:02:45.613  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-22 14:02:45.613  5705  5751 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-22 14:02:45.613  5705  5751 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2a1643 added. We now have 4 listener(s)
11-22 14:02:45.613  5705  5751 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-22 14:02:45.614   933  5995 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.22.110,2a00:1450:4001:81d::200e
11-22 14:02:45.614  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-22 14:02:45.616  5705  5751 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-22 14:02:45.616  5705  5751 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@88614c0 added. We now have 4 listener(s)
11-22 14:02:45.616  5165  5165 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-22 14:02:45.616  5140  5150 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-22 14:02:45.617  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-22 14:02:45.617  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-22 14:02:45.617  5938  5954 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-22 14:02:45.617  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-22 14:02:45.617  5938  5954 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 14:02:45.617  5705  5751 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-22 14:02:45.617  5705  5751 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e985f9 added. We now have 5 listener(s)
11-22 14:02:45.618  5705  5751 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-22 14:02:45.618  5705  5751 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-22 14:02:45.619  5705  5751 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-22 14:02:45.619  5705  5751 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-22 14:02:45.619  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-22 14:02:45.619  5705  5751 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-22 14:02:45.619  5705  5751 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-22 14:02:45.621  5705  5751 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-22 14:02:45.621  5938  5957 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-22 14:02:45.628  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-22 14:02:45.628  5705  5751 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-22 14:02:45.628  5705  5751 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-22 14:02:45.628  5938  5954 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-22 14:02:45.628  5938  5954 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 14:02:45.629  3816  3816 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
11-22 14:02:45.629  5938  5954 E BtGatt.ContextMap: Context not found for ID 5
11-22 14:02:45.631  3816  5534 I iu.UploadsManager: num queued entries: 0
11-22 14:02:45.632  3816  5534 I iu.UploadsManager: num updated entries: 0
11-22 14:02:45.632  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.632  5705  5751 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-22 14:02:45.633  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-22 14:02:45.633  5705  5751 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-22 14:02:45.633  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-22 14:02:45.636  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.637  5705  5751 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-22 14:02:45.637  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-22 14:02:45.637  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-22 14:02:45.637  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-22 14:02:45.637  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.637  5705  5751 D BluetoothAdapter: STATE_ON
11-22 14:02:45.639  5938  5949 D BtGatt.GattService: registerClient() - UUID=c40cdb2e-8753-4bd4-a37e-a7fd9698e4a6
11-22 14:02:45.639  5938  5954 D BtGatt.GattService: onClientRegistered() - UUID=c40cdb2e-8753-4bd4-a37e-a7fd9698e4a6, clientIf=5
11-22 14:02:45.639  5705  5752 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-22 14:02:45.640  5938  5967 D BtGatt.GattService: start scan with filters
11-22 14:02:45.642  5938  5954 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-22 14:02:45.642  5938  5954 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 14:02:45.642  5938  5957 D BtGatt.ScanManager: stopping BLe Batch
11-22 14:02:45.643  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-22 14:02:45.643  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.643  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-22 14:02:45.643  3816  6010 I SystemUpdateService: active receiver: enabled
11-22 14:02:45.643  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.643  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-22 14:02:45.643  5705  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-22 14:02:45.643  5705  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-22 14:02:45.643  5705  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-22 14:02:45.643  5705  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-22 14:02:45.644  5705  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-22 14:02:45.644  5705  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-22 14:02:45.644  5705  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-22 14:02:45.644  5705  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-22 14:02:45.644  3816  5534 I iu.SyncManager: NEXT; no task
11-22 14:02:45.645  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-22 14:02:45.645  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.647  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.648  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-22 14:02:45.648  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.648  5938  5954 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-22 14:02:45.648  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.648  5938  5954 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 14:02:45.648  5705  5751 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-22 14:02:45.648  5705  5705 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-22 14:02:45.648  5705  5751 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-22 14:02:45.648  5705  5751 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 14:02:45.648  5938  5957 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-22 14:02:45.648  5705  5751 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 14:02:45.648  5705  5751 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 14:02:45.648  5705  5751 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 14:02:45.649  5705  5751 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-22 14:02:45.649  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-22 14:02:45.649  5705  5751 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 14:02:45.649  5705  5751 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-22 14:02:45.649  5705  5751 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eceff2 removed from the list
11-22 14:02:45.649  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:02:45.649  5705  5751 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2a1643 removed from the list
11-22 14:02:45.649  5705  5751 D io.jxcore.node.ConnectivityMonitor: stop
11-22 14:02:45.649  5705  5751 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-22 14:02:45.649  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-22 14:02:45.649  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.649  5705  5751 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
11-22 14:02:45.650  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-22 14:02:45.650  5705  5751 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-22 14:02:45.650  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-22 14:02:45.650  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.650  3816  3816 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
11-22 14:02:45.650  5705  5705 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-22 14:02:45.650  5705  5705 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-22 14:02:45.650  5705  5705 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-22 14:02:45.650  5705  5705 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-22 14:02:45.651  3816  6010 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-22 14:02:45.651  3816  3816 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
11-22 14:02:45.652  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.652  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.652  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.652  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 14:02:45.652  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 14:02:45.652  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:02:45.652  5705  5751 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2a1643 not in the list
11-22 14:02:45.652  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-22 14:02:45.652  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.652  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-22 14:02:45.652  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-22 14:02:45.653  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.653  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.653  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.653  5705  5751 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-22 14:02:45.653  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.653  5537  5537 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
11-22 14:02:45.654  5705  5751 D BluetoothAdapter: STATE_ON
11-22 14:02:45.654  5938  5948 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-22 14:02:45.654  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-22 14:02:45.655  5705  5751 D BluetoothAdapter: STATE_ON
11-22 14:02:45.655  5938  5977 D BtGatt.GattService: stopScan() - queue size =0
11-22 14:02:45.656  5938  5948 D BtGatt.GattService: unregisterClient() - clientIf=5
11-22 14:02:45.656  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-22 14:02:45.656  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.656  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-22 14:02:45.656  5938  5954 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-22 14:02:45.656  5938  5954 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 14:02:45.656  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.656  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.656  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.657  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.657  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-22 14:02:45.657  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.657  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.657  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.657  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-22 14:02:45.657  5705  5751 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-22 14:02:45.658  5705  5751 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-22 14:02:45.658  5938  5957 D BtGatt.ScanManager: handling starting scan
11-22 14:02:45.658  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.659  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.659  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-22 14:02:45.659  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.659  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.659  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 14:02:45.659  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 14:02:45.659  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:02:45.659  5705  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-22 14:02:45.659  5705  5751 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e985f9 removed from the list
11-22 14:02:45.659  5705  5751 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 14:02:45.659  5705  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-22 14:02:45.659  5705  5751 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 14:02:45.659  5705  5751 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-22 14:02:45.659  5705  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-22 14:02:45.659  5705  5751 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@88614c0 removed from the list
11-22 14:02:45.659  5705  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-22 14:02:45.659  5705  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-22 14:02:45.660  5705  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-22 14:02:45.660  5705  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-22 14:02:45.660  5705  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-22 14:02:45.660  5705  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-22 14:02:45.660  5705  5705 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-22 14:02:45.660  5705  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-22 14:02:45.660  5705  5705 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-22 14:02:45.660  5705  5751 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-22 14:02:45.660  5705  5751 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2968b4a added. We now have 3 listener(s)
11-22 14:02:45.660  5537  5537 D SprintDMHelper: simOperator: 
11-22 14:02:45.660  5537  5537 D SprintDMReceiver: Not Sprint UICC, don't do anything.
11-22 14:02:45.661  5705  5705 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-22 14:02:45.661  5705  5705 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-22 14:02:45.661  5705  5705 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-22 14:02:45.662  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-22 14:02:45.662  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-22 14:02:45.662  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-22 14:02:45.663  5705  5751 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-22 14:02:45.663  5705  5751 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dc60abb added. We now have 4 listener(s)
11-22 14:02:45.663  5705  5751 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-22 14:02:45.663  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-22 14:02:45.664  5705  5751 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-22 14:02:45.664  5705  5751 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c39bbd8 added. We now have 4 listener(s)
11-22 14:02:45.665  5938  5954 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-22 14:02:45.665  5938  5954 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 14:02:45.665  5938  5957 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-22 14:02:45.665  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-22 14:02:45.666  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-22 14:02:45.666  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-22 14:02:45.666  5705  5751 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-22 14:02:45.666  5705  5751 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ce0fb31 added. We now have 5 listener(s)
11-22 14:02:45.666  5705  5751 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-22 14:02:45.666  5705  5751 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-22 14:02:45.666  5705  5751 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-22 14:02:45.666  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-22 14:02:45.666  5705  5751 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-22 14:02:45.666  5705  5751 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-22 14:02:45.667  5705  5751 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-22 14:02:45.671  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-22 14:02:45.671  5705  5751 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-22 14:02:45.671  5705  5751 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-22 14:02:45.671  5938  5954 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-22 14:02:45.671  5938  5954 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 14:02:45.671  5938  5957 D BtGatt.ScanManager: Starting BLE batch scan
11-22 14:02:45.671  5938  5957 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-22 14:02:45.674  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.674  5705  5751 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-22 14:02:45.675  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-22 14:02:45.675  5705  5751 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-22 14:02:45.675  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-22 14:02:45.675  3816  6010 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
11-22 14:02:45.675  3816  6010 I SystemUpdateService: now status is 0 (complete)
11-22 14:02:45.681  3816  6010 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-22 14:02:45.681  3816  6010 I SystemUpdateService: file has been verified
11-22 14:02:45.681  3816  6010 I SystemUpdateService: OTA package size = 21989297
11-22 14:02:45.681  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.682  5938  5954 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-22 14:02:45.682  5705  5751 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-22 14:02:45.682  5938  5954 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-22 14:02:45.682  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-22 14:02:45.682  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-22 14:02:45.682  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-22 14:02:45.682  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.683  5705  5751 D BluetoothAdapter: STATE_ON
11-22 14:02:45.686  5938  5949 D BtGatt.GattService: registerClient() - UUID=b1f7fb46-e023-492e-b503-60c1da371430
11-22 14:02:45.687  5938  5954 D BtGatt.GattService: onClientRegistered() - UUID=b1f7fb46-e023-492e-b503-60c1da371430, clientIf=5
11-22 14:02:45.687  5938  5954 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-22 14:02:45.687  5938  5954 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-22 14:02:45.687  5705  5716 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-22 14:02:45.687  5938  5977 D BtGatt.GattService: start scan with filters
11-22 14:02:45.688  5938  5957 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-22 14:02:45.689  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-22 14:02:45.690  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.690  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-22 14:02:45.690  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.690  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-22 14:02:45.690  5705  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-22 14:02:45.690  5705  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-22 14:02:45.690  5705  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-22 14:02:45.690  5705  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-22 14:02:45.690  5705  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-22 14:02:45.690  5705  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-22 14:02:45.690  5705  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-22 14:02:45.690  5705  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-22 14:02:45.691  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-22 14:02:45.691  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.692  5938  5954 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-22 14:02:45.692  5938  5954 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 14:02:45.693  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.693  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-22 14:02:45.693  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.693  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.694  5705  5705 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-22 14:02:45.696  5705  5751 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 14:02:45.696  5705  5751 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 14:02:45.696  5705  5751 V io.jxcore.node.StartStopOperationHandler:, executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 14:02:45.696  5705  5751 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 14:02:45.696  5705  5751 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-22 14:02:45.696  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-22 14:02:45.696  5705  5751 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 14:02:45.696  5705  5751 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-22 14:02:45.696  5705  5751 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2968b4a removed from the list
11-22 14:02:45.696  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:02:45.696  5705  5751 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dc60abb removed from the list
11-22 14:02:45.696  5705  5751 D io.jxcore.node.ConnectivityMonitor: stop
11-22 14:02:45.696  5705  5751 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-22 14:02:45.696  5705  5705 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-22 14:02:45.696  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-22 14:02:45.696  5705  5705 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-22 14:02:45.696  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.696  5705  5705 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-22 14:02:45.696  5705  5751 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
11-22 14:02:45.696  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-22 14:02:45.696  5705  5751 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-22 14:02:45.696  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-22 14:02:45.696  5705  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: results count  = 0. Current thread: Thread[main,5,main], id: 1
11-22 14:02:45.697  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.697  5705  5705 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-22 14:02:45.697  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.697  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.698  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.698  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 14:02:45.698  5705  57,51 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 14:02:45.698  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:02:45.698  5705  5751 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dc60abb not in the list
11-22 14:02:45.698  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-22 14:02:45.698  5938  5954 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-22 14:02:45.698  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.698  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-22 14:02:45.698  5938  5954 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 14:02:45.698  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-22 14:02:45.698  5938  5957 D BtGatt.ScanManager: stopping BLe Batch
11-22 14:02:45.698  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.698  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.698  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.698  5705  5751 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-22 14:02:45.698  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.700  5705  5751 D BluetoothAdapter: STATE_ON
11-22 14:02:45.700  5938  5967 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-22 14:02:45.700  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-22 14:02:45.701  5705  5751 D BluetoothAdapter: STATE_ON
11-22 14:02:45.701  5938  5949 D BtGatt.GattService: stopScan() - queue size =0
11-22 14:02:45.702  5938  5967 D BtGatt.GattService: unregisterClient() - clientIf=5
11-22 14:02:45.702  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-22 14:02:45.702  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.702  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-22 14:02:45.702  5938  5954 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-22 14:02:45.702  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.702  5938  5954 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 14:02:45.702  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.702  5938  5957 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-22 14:02:45.702  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.702  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.702  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-22 14:02:45.703  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.703  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.703  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.703  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-22 14:02:45.703  5705  5751 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-22 14:02:45.704  5705  5751 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-22 14:02:45.705  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.705  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.705  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-22 14:02:45.706  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.706  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.706  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 14:02:45.706  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 14:02:45.706  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:02:45.706  5705  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-22 14:02:45.706  5705  5751 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ce0fb31 removed from the list
11-22 14:02:45.706  5705  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-22 14:02:45.706  5705  5751 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 14:02:45.706  5705  5751 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 14:02:45.706  5705  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-22 14:02:45.706  5705  5751 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-22 14:02:45.706  5705  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-22 14:02:45.706  5705  5751 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c39bbd8 removed from the list
11-22 14:02:45.706  5705  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-22 14:02:45.706  5705  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-22 14:02:45.706  5705  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-22 14:02:45.706  5705  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-22 14:02:45.706  5705  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-22 14:02:45.706  5705  5705 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-22 14:02:45.706  5705  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-22 14:02:45.707  5705  5705 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-22 14:02:45.707  5705  5751 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-22 14:02:45.707  5705  5751 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@abd39a2 added. We now have 3 listener(s)
11-22 14:02:45.707  5938  5954 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-22 14:02:45.707  5938  5954 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 14:02:45.708  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-22 14:02:45.708  5705  5705 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-22 14:02:45.708  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-22 14:02:45.708  5705  5705 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-22 14:02:45.708  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-22 14:02:45.709  5705  5705 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-22 14:02:45.709  5705  5751 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-22 14:02:45.709  5705  5751 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6d1633 added. We now have 4 listener(s)
11-22 14:02:45.709  5705  5751 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-22 14:02:45.709  3816  6010 I SystemUpdateService: showing system update notification
11-22 14:02:45.709  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-22 14:02:45.709  5938  5957 D BtGatt.ScanManager: handling starting scan
11-22 14:02:45.710  5705  5751 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-22 14:02:45.710  5705  5751 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ca82df0 added. We now have 4 listener(s)
11-22 14:02:45.712  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-22 14:02:45.712  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-22 14:02:45.713  5705  5751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-22 14:02:45.713  5705  5751 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-22 14:02:45.713  5705  5751 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@93adf69 added. We now have 5 listener(s)
11-22 14:02:45.713  5705  5751 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-22 14:02:45.713  5705  5751 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 14:02:45.713  5705  5751 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 14:02:45.713  5705  5751 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 14:02:45.714  5705  5751 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 14:02:45.714  5705  5751 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 14:02:45.714  5705  5751 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-22 14:02:45.714  5705  5751 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@abd39a2 removed from the list
11-22 14:02:45.714  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:02:45.714  5705  5751 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6d1633 removed from the list
11-22 14:02:45.714  5705  5751 D io.jxcore.node.ConnectivityMonitor: stop
11-22 14:02:45.714  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.714  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.714  5938  5954 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-22 14:02:45.715  5938  5954 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 14:02:45.715  5938  5957 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-22 14:02:45.716  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.716  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.716  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.716  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 14:02:45.716  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 14:02:45.716  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:02:45.716  5705  5751 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6d1633 not in the list
11-22 14:02:45.716  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.716  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.717   933  5995 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 22 Nov 2016 13:02:45 GMT], X-Android-Received-Millis=[1479819765716], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1479819765655]}
11-22 14:02:45.717   933  3077 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-22 14:02:45.718   933  3077 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
11-22 14:02:45.718   933  3077 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
11-22 14:02:45.719   933  3077 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
11-22 14:02:45.720   933   933 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
11-22 14:02:45.720  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.720  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.720  5705  5751 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:02:45.720  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 14:02:45.720  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 14:02:45.720  5705  5751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:02:45.720  5705  5751 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@93adf69 removed from the list
11-22 14:02:45.720  5705  5751 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 14:02:45.720  5705  5751 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 14:02:45.721  5705  5751 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-22 14:02:45.721  5705  5751 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ca82df0 removed from the list
11-22 14:02:45.721  5938  5954 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-22 14:02:45.721  5938  5954 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 14:02:45.722  5705  5751 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-22 14:02:45.722  5705  5751 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-22 14:02:45.722  5938  5957 D BtGatt.ScanManager: Starting BLE batch scan
11-22 14:02:45.722  5705  5751 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-22 14:02:45.722  5938  5957 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-22 14:02:45.722  5705  5751 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-22 14:02:45.722  3816  3816 D SystemUpdateService: onDestroy
11-22 14:02:45.722  5705  5751 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
11-22 14:02:45.722  5705  5751 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-22 14:02:45.731  5938  5954 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-22 14:02:45.731  5938  5954 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 14:02:45.735  5938  5954 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-22 14:02:45.735  5938  5954 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 14:02:45.737  5938  5957 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-22 14:02:45.741  5938  5954 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-22 14:02:45.741  5938  5954 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 14:02:45.741  5938  5954 E BtGatt.ContextMap: Context not found for ID 5
11-22 14:02:45.747  5938  5954 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-22 14:02:45.747  5938  5954 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 14:02:45.747  5938  5957 D BtGatt.ScanManager: stopping BLe Batch
11-22 14:02:45.751  5938  5954 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-22 14:02:45.752  5938  5954 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 14:02:45.752  5938  5957 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-22 14:02:45.756  5938  5954 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-22 14:02:45.757  5938  5954 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-22 14:02:45.821  5089  6015 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,11-22 14:02:46.103  5705  5705 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-22 14:02:46.160  5705  5705 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-22 14:02:46.207  5705  5705 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-22 14:02:47.854  5705  6022 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 178, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-22 14:02:47.854  5705  6022 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-22 14:02:48.248   933  3077 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-22 14:02:48.640  5705  6022 W !!      : call onHalfStreamCopied
,11-22 14:02:48.640  5705  6022 I testCopyDataAndClose: closing input stream
,11-22 14:02:49.396  5705  6022 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 178, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-22 14:02:49.396  5705  6022 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-22 14:02:49.396  5705  6022 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-22 14:02:49.396  5705  6022 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-22 14:02:49.396  5705  6022 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-22 14:02:49.396  5705  6022 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-22 14:02:49.396  5705  6022 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-22 14:02:49.396  5705  6022 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,11-22 14:02:49.396  5705  6022 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-22 14:02:49.396  5705  6022 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 178, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-22 14:02:49.396  5705  6022 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-22 14:02:53.517   933  3077 D ConnectivityService: handlePromptUnvalidated 102
,11-22 14:02:53.723  5705  6023 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 181, name: My test thread name). Connection data: Peer properties: [null null].
11-22 14:02:53.723  5705  6023 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-22 14:02:54.285   933  3077 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-22 14:02:54.996   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:02:55.722  5705  5751 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 181. Connection data: Peer properties: [null null].
11-22 14:02:55.722  5705  5751 I io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-22 14:02:55.723  5705  5751 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 181, name: My test thread name)
,11-22 14:02:55.825  5705  6023 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
,11-22 14:02:55.825  5705  6023 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 181, name: My test thread name). Connection data: Peer properties: [null null].
11-22 14:02:55.825  5705  6023 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 143 and the total number of bytes written 143
,11-22 14:02:55.897  5705  6024 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 183, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-22 14:02:55.897  5705  6024 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-22 14:02:55.998   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:02:56.524   933  3072 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 15, 16 -> obsolete
,11-22 14:02:56.999   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:02:57.518  5705  6024 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 183, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-22 14:02:57.518  5705  6024 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-22 14:02:57.518  5705  6024 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-22 14:02:57.518  5705  6024 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-22 14:02:57.518  5705  6024 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-22 14:02:57.519  5705  6024 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-22 14:02:57.519  5705  6024 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-22 14:02:57.519  5705  6024 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-22 14:02:57.519  5705  6024 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-22 14:02:57.519  5705  6024 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 183, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-22 14:02:57.519  5705  6024 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-22 14:02:58.000   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:02:59.002   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:03:00.002   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-22 14:03:01.759  5705  6025 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
11-22 14:03:01.759  5705  6025 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-22 14:03:01.759  5705  6025 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 185, thread name: My test thread name). Connection data: Peer properties: [null null].
11-22 14:03:01.759  5705  6025 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-22 14:03:01.760  5705  6025 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-22 14:03:01.760  5705  6025 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-22 14:03:01.760  5705  6025 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-22 14:03:01.760  5705  6025 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-22 14:03:01.760  5705  6025 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-22 14:03:01.760  5705  6025 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-22 14:03:01.760  5705  6025 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-22 14:03:01.760  5705  6025 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
11-22 14:03:01.760  5705  6025 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
11-22 14:03:01.762  5705  5751 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,11-22 14:03:01.765  5705  6026 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
11-22 14:03:01.765  5705  6026 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-22 14:03:01.766  5705  6026 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 189, thread name: My test thread name): Test exception.
11-22 14:03:01.766  5705  6026 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
11-22 14:03:01.766  5705  6026 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-22 14:03:01.766  5705  6026 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
11-22 14:03:01.766  5705  6026 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
11-22 14:03:01.766  5705  6026 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,11-22 14:03:01.771  5705  5751 I jxcore-log: 2016-11-22 13:03:01 - DEBUG UnitTest_app: 'Total number of executed tests:  82'
11-22 14:03:01.771  5705  5751 I jxcore-log: 
11-22 14:03:01.772  5705  5751 I jxcore-log: 2016-11-22 13:03:01 - DEBUG UnitTest_app: 'Number of passed tests:  82'
11-22 14:03:01.772  5705  5751 I jxcore-log: 
,11-22 14:03:01.772  5705  5751 I jxcore-log: 2016-11-22 13:03:01 - DEBUG UnitTest_app: 'Number of failed tests:  0'
11-22 14:03:01.772  5705  5751 I jxcore-log: 
11-22 14:03:01.772  5705  5751 I jxcore-log: 2016-11-22 13:03:01 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
11-22 14:03:01.772  5705  5751 I jxcore-log: 
,11-22 14:03:01.772  5705  5751 I jxcore-log: 2016-11-22 13:03:01 - DEBUG UnitTest_app: 'Total duration:  91899'
11-22 14:03:01.772  5705  5751 I jxcore-log: 
,11-22 14:03:01.774  5705  5751 I jxcore-log: 2016-11-22 13:03:01 - DEBUG UnitTest_app: 'Unit Test app is loaded'
11-22 14:03:01.774  5705  5751 I jxcore-log: 
11-22 14:03:01.778  5705  5751 I jxcore-log: 2016-11-22 13:03:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-22 14:03:01.778  5705  5751 I jxcore-log: 
,11-22 14:03:01.778  5705  5751 I jxcore-log: 2016-11-22 13:03:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-22 14:03:01.778  5705  5751 I jxcore-log: 
11-22 14:03:01.779  5705  5751 I jxcore-log: 2016-11-22 13:03:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-22 14:03:01.779  5705  5751 I jxcore-log: 
11-22 14:03:01.779  5705  5751 I jxcore-log: 2016-11-22 13:03:01 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-22 14:03:01.779  5705  5751 I jxcore-log: 
,11-22 14:03:01.779  5705  5751 I jxcore-log: 2016-11-22 13:03:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-22 14:03:01.779  5705  5751 I jxcore-log: 
11-22 14:03:01.780  5705  5751 I jxcore-log: 2016-11-22 13:03:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-22 14:03:01.780  5705  5751 I jxcore-log: 
11-22 14:03:01.780  5705  5751 I jxcore-log: 2016-11-22 13:03:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-22 14:03:01.780  5705  5751 I jxcore-log: 
11-22 14:03:01.780  5705  5751 I jxcore-log: 2016-11-22 13:03:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-22 14:03:01.780  5705  5751 I jxcore-log: 
11-22 14:03:01.780  5705  5751 I jxcore-log: 2016-11-22 13:03:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-22 14:03:01.780  5705  5751 I jxcore-log: 
11-22 14:03:01.781  5705  5751 I jxcore-log: 2016-11-22 13:03:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-22 14:03:01.781  5705  5751 I jxcore-log: 
,11-22 14:03:01.781  5705  5751 I jxcore-log: 2016-11-22 13:03:01 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-22 14:03:01.781  5705  5751 I jxcore-log: 
11-22 14:03:01.781  5705  5751 I jxcore-log: 2016-11-22 13:03:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-22 14:03:01.781  5705  5751 I jxcore-log: 
11-22 14:03:01.781  5705  5751 I jxcore-log: 2016-11-22 13:03:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-22 14:03:01.781  5705  5751 I jxcore-log: 
11-22 14:03:01.782  5705  5751 I jxcore-log: 2016-11-22 13:03:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-22 14:03:01.782  5705  5751 I jxcore-log: 
,11-22 14:03:01.782  5705  5751 I jxcore-log: 2016-11-22 13:03:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-22 14:03:01.782  5705  5751 I jxcore-log: 
11-22 14:03:01.782  5705  5751 I jxcore-log: 2016-11-22 13:03:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-22 14:03:01.782  5705  5751 I jxcore-log: 
,11-22 14:03:01.782  5705  5751 I jxcore-log: 2016-11-22 13:03:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-22 14:03:01.782  5705  5751 I jxcore-log: 
11-22 14:03:01.783  5705  5751 I jxcore-log: 2016-11-22 13:03:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","ssidName":"<unknown ssid>"}'
11-22 14:03:01.783  5705  5751 I jxcore-log: 
11-22 14:03:01.783  5705  5751 I jxcore-log: 2016-11-22 13:03:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-22 14:03:01.783  5705  5751 I jxcore-log: 
11-22 14:03:01.783  5705  5751 I jxcore-log: 2016-11-22 13:03:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-22 14:03:01.783  5705  5751 I jxcore-log: 
,11-22 14:03:01.783  5705  5751 I jxcore-log: 2016-11-22 13:03:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-22 14:03:01.783  5705  5751 I jxcore-log: 
11-22 14:03:01.784  5705  5751 I jxcore-log: 2016-11-22 13:03:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-22 14:03:01.784  5705  5751 I jxcore-log: 
11-22 14:03:01.784  5705  5751 I jxcore-log: 2016-11-22 13:03:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-22 14:03:01.784  5705  5751 I jxcore-log: 
11-22 14:03:01.784  5705  5751 I jxcore-log: 2016-11-22 13:03:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-22 14:03:01.784  5705  5751 I jxcore-log: 
,11-22 14:03:01.786  5705  5751 I jxcore-log: 2016-11-22 13:03:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-22 14:03:01.786  5705  5751 I jxcore-log: 
,11-22 14:03:01.786  5705  5751 I jxcore-log: 2016-11-22 13:03:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-22 14:03:01.786  5705  5751 I jxcore-log: 
11-22 14:03:01.786  5705  5751 I jxcore-log: 2016-11-22 13:03:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-22 14:03:01.786  5705  5751 I jxcore-log: 
11-22 14:03:01.787  5705  5751 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 14:03:01.787  5705  5751 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
11-22 14:03:01.787  5705  5751 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,11-22 14:03:01.787  5705  5751 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
11-22 14:03:01.787  5705  5751 I jxcore-log: 2016-11-22 13:03:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-22 14:03:01.787  5705  5751 I jxcore-log: 
11-22 14:03:01.787  5705  5751 I jxcore-log: 2016-11-22 13:03:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-22 14:03:01.787  5705  5751 I jxcore-log: 
11-22 14:03:01.788  5705  5751 I jxcore-log: 2016-11-22 13:03:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-22 14:03:01.788  5705  5751 I jxcore-log: 
,11-22 14:03:01.788  5705  5751 I jxcore-log: 2016-11-22 13:03:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-22 14:03:01.788  5705  5751 I jxcore-log: 
11-22 14:03:01.788  5705  5751 I jxcore-log: 2016-11-22 13:03:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-22 14:03:01.788  5705  5751 I jxcore-log: 
11-22 14:03:01.788  5705  5751 I jxcore-log: 2016-11-22 13:03:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-22 14:03:01.788  5705  5751 I jxcore-log: 
,11-22 14:03:01.793  5705  5751 I jxcore-log: 2016-11-22 13:03:01 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
11-22 14:03:01.793  5705  5751 I jxcore-log: 
11-22 14:03:01.794  5705  5751 I jxcore-log: 2016-11-22 13:03:01 - WARN testUtils: 'myNameCallback not set!'
11-22 14:03:01.794  5705  5751 I jxcore-log: 
,11-22 14:03:01.803  5705  5705 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,11-22 14:03:03.862  5705  5751 I jxcore-log: 2016-11-22 13:03:03 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
11-22 14:03:03.862  5705  5751 I jxcore-log: 
,11-22 14:03:03.864  5705  5751 I jxcore-log: 2016-11-22 13:03:03 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
11-22 14:03:03.864  5705  5751 I jxcore-log: 
,11-22 14:03:04.213  5705  5751 I jxcore-log: 2016-11-22 13:03:04 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
11-22 14:03:04.213  5705  5751 I jxcore-log: 
,11-22 14:03:04.226  5705  5751 I jxcore-log: 2016-11-22 13:03:04 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
11-22 14:03:04.226  5705  5751 I jxcore-log: 
,11-22 14:03:05.346  5705  5751 I jxcore-log: 2016-11-22 13:03:05 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
11-22 14:03:05.346  5705  5751 I jxcore-log: 
,11-22 14:03:05.539  5705  5751 I jxcore-log: 2016-11-22 13:03:05 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
11-22 14:03:05.539  5705  5751 I jxcore-log: 
,11-22 14:03:05.545  5705  5751 I jxcore-log: 2016-11-22 13:03:05 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
11-22 14:03:05.545  5705  5751 I jxcore-log: 
,11-22 14:03:05.549  5705  5751 I jxcore-log: 2016-11-22 13:03:05 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
11-22 14:03:05.549  5705  5751 I jxcore-log: 
,11-22 14:03:06.034  5705  5751 I jxcore-log: 2016-11-22 13:03:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
11-22 14:03:06.034  5705  5751 I jxcore-log: 
,11-22 14:03:06.079  5705  5751 I jxcore-log: 2016-11-22 13:03:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
11-22 14:03:06.079  5705  5751 I jxcore-log: 
,11-22 14:03:06.092  5705  5751 I jxcore-log: 2016-11-22 13:03:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
11-22 14:03:06.092  5705  5751 I jxcore-log: 
,11-22 14:03:06.096  5705  5751 I jxcore-log: 2016-11-22 13:03:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
11-22 14:03:06.096  5705  5751 I jxcore-log: 
,11-22 14:03:06.365  5705  5751 I jxcore-log: 2016-11-22 13:03:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
11-22 14:03:06.365  5705  5751 I jxcore-log: 
,11-22 14:03:06.494  5705  5751 I jxcore-log: 2016-11-22 13:03:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
11-22 14:03:06.494  5705  5751 I jxcore-log: 
,11-22 14:03:06.872  5705  5751 I jxcore-log: 2016-11-22 13:03:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
11-22 14:03:06.872  5705  5751 I jxcore-log: 
,11-22 14:03:06.880  5705  5751 I jxcore-log: 2016-11-22 13:03:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
11-22 14:03:06.880  5705  5751 I jxcore-log: 
,11-22 14:03:06.884  5705  5751 I jxcore-log: 2016-11-22 13:03:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
11-22 14:03:06.884  5705  5751 I jxcore-log: 
,11-22 14:03:06.890  5705  5751 I jxcore-log: 2016-11-22 13:03:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
11-22 14:03:06.890  5705  5751 I jxcore-log: 
,11-22 14:03:06.895  5705  5751 I jxcore-log: 2016-11-22 13:03:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
11-22 14:03:06.895  5705  5751 I jxcore-log: 
,11-22 14:03:06.923  5705  5751 I jxcore-log: 2016-11-22 13:03:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
11-22 14:03:06.923  5705  5751 I jxcore-log: 
,11-22 14:03:06.959  5705  5751 I jxcore-log: 2016-11-22 13:03:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
11-22 14:03:06.959  5705  5751 I jxcore-log: 
,11-22 14:03:06.966  5705  5751 I jxcore-log: 2016-11-22 13:03:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
11-22 14:03:06.966  5705  5751 I jxcore-log: 
,11-22 14:03:06.972  5705  5751 I jxcore-log: 2016-11-22 13:03:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
11-22 14:03:06.972  5705  5751 I jxcore-log: 
,11-22 14:03:06.988  5705  5751 I jxcore-log: 2016-11-22 13:03:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
11-22 14:03:06.988  5705  5751 I jxcore-log: 
,11-22 14:03:07.003  5705  5751 I jxcore-log: 2016-11-22 13:03:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
11-22 14:03:07.003  5705  5751 I jxcore-log: 
,11-22 14:03:07.010  5705  5751 I jxcore-log: 2016-11-22 13:03:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
11-22 14:03:07.010  5705  5751 I jxcore-log: 
,11-22 14:03:07.015  5705  5751 I jxcore-log: 2016-11-22 13:03:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
11-22 14:03:07.015  5705  5751 I jxcore-log: 
,11-22 14:03:07.028  5705  5751 I jxcore-log: 2016-11-22 13:03:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
11-22 14:03:07.028  5705  5751 I jxcore-log: 
,11-22 14:03:07.045  5705  5751 I jxcore-log: 2016-11-22 13:03:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
11-22 14:03:07.045  5705  5751 I jxcore-log: 
,11-22 14:03:07.059  5705  5751 I jxcore-log: 2016-11-22 13:03:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
11-22 14:03:07.059  5705  5751 I jxcore-log: 
,11-22 14:03:07.070  5705  5751 I jxcore-log: 2016-11-22 13:03:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
11-22 14:03:07.070  5705  5751 I jxcore-log: 
,11-22 14:03:07.082  5705  5751 I jxcore-log: 2016-11-22 13:03:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
11-22 14:03:07.082  5705  5751 I jxcore-log: 
,11-22 14:03:07.093  5705  5751 I jxcore-log: 2016-11-22 13:03:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
11-22 14:03:07.093  5705  5751 I jxcore-log: 
,11-22 14:03:07.106  5705  5751 I jxcore-log: 2016-11-22 13:03:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
11-22 14:03:07.106  5705  5751 I jxcore-log: 
,11-22 14:03:07.116  5705  5751 I jxcore-log: 2016-11-22 13:03:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
11-22 14:03:07.116  5705  5751 I jxcore-log: 
,11-22 14:03:07.123  5705  5751 I jxcore-log: 2016-11-22 13:03:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
11-22 14:03:07.123  5705  5751 I jxcore-log: 
,11-22 14:03:07.145  5705  5751 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,11-22 14:03:07.146  5705  5751 I jxcore-log: 2016-11-22 13:03:07 - INFO testUtils: 'BLE multiple advertisement supported'
11-22 14:03:07.146  5705  5751 I jxcore-log: 
,11-22 14:03:07.176  5705  5751 I jxcore-log: 2016-11-22 13:03:07 - INFO CoordinatedClient: 'Connecting to coordination server on http://85.14.110.168:3000/'
11-22 14:03:07.176  5705  5751 I jxcore-log: 
,11-22 14:03:07.914  5705  5751 I jxcore-log: 2016-11-22 13:03:07 - DEBUG CoordinatedClient: 'connected to the test server'
11-22 14:03:07.914  5705  5751 I jxcore-log: 
,11-22 14:03:12.421   933  3077 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-22 14:03:15.004   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:03:15.453   933  3077 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-22 14:03:16.005   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:03:17.007   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:03:18.008   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:03:18.489   933  3077 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-22 14:03:19.010   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:03:20.010   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-22 14:03:21.528   933  3077 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-22 14:03:25.495   933  3072 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-22 14:03:27.599   933  3077 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-22 14:03:31.342   933  5996 D NetlinkSocketObserver: NeighborEvent{elapsedMs=290503, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-22 14:03:37.929   933  5996 D NetlinkSocketObserver: NeighborEvent{elapsedMs=297090, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-22 14:03:40.012   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:03:41.013   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:03:42.015   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:03:43.016   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:03:44.018   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:03:45.019   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-22 14:03:48.786   933  3077 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-22 14:03:51.813   933  3077 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-22 14:03:56.409   933  5996 D NetlinkSocketObserver: NeighborEvent{elapsedMs=315570, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-22 14:04:02.955   933  5996 D NetlinkSocketObserver: NeighborEvent{elapsedMs=322117, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-22 14:04:05.501   933  3072 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-22 14:04:09.994   933  3077 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-22 14:04:10.020   534   534 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-22 14:04:10.020   534   534 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-22 14:04:13.017   933  3077 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-22 14:04:21.475   933  5996 D NetlinkSocketObserver: NeighborEvent{elapsedMs=340637, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-22 14:04:25.022   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:04:25.502   933  3072 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-22 14:04:26.023   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:04:27.024   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:04:27.982   933  5996 D NetlinkSocketObserver: NeighborEvent{elapsedMs=347144, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-22 14:04:28.026   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:04:29.027   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:04:30.028   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-22 14:04:34.212   933  3077 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-22 14:04:35.030   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:04:36.031   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:04:37.032   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:04:37.246   933  3077 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-22 14:04:38.033   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:04:39.034   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:04:40.035   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-22 14:04:46.489   933  5996 D NetlinkSocketObserver: NeighborEvent{elapsedMs=365650, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-22 14:04:50.036   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:04:51.038   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:04:52.039   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:04:53.009   933  5996 D NetlinkSocketObserver: NeighborEvent{elapsedMs=372171, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,11-22 14:04:53.040   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:04:54.042   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:04:55.043   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-22 14:05:05.506   933  3072 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-22 14:05:10.044   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:05:11.046   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:05:12.047   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:05:13.048   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:05:14.050   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:05:15.051   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-22 14:05:25.509   933  3072 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-22 14:05:35.052   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:05:36.053   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:05:36.569   933  5996 D NetlinkSocketObserver: NeighborEvent{elapsedMs=415730, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-22 14:05:37.055   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:05:38.056   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:05:39.058   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:05:40.059   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-22 14:05:43.049   933  5996 D NetlinkSocketObserver: NeighborEvent{elapsedMs=422210, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-22 14:05:43.819   933  3077 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-22 14:05:45.510   933  3072 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-22 14:05:46.849   933  3077 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-22 14:05:55.943   933  3077 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-22 14:05:58.981   933  3077 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-22 14:06:01.529   933  5996 D NetlinkSocketObserver: NeighborEvent{elapsedMs=440690, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-22 14:06:05.060   534   534 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-22 14:06:05.061   534   534 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-22 14:06:08.075   933  5996 D NetlinkSocketObserver: NeighborEvent{elapsedMs=447237, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-22 14:06:11.083   933  3077 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-22 14:06:14.111   933  3077 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-22 14:06:19.358  5705  5751 I jxcore-log: 2016-11-22 13:06:19 - DEBUG CoordinatedClient: 'device disconnected from the test server'
11-22 14:06:19.358  5705  5751 I jxcore-log: 
,11-22 14:06:19.548  5705  5751 I jxcore-log: 2016-11-22 13:06:19 - ERROR CoordinatedClient: 'connection error: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-22 14:06:19.548  5705  5751 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-22 14:06:19.548  5705  5751 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-22 14:06:19.548  5705  5751 I jxcore-log: emit@events.js:82:1
11-22 14:06:19.548  5705  5751 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-22 14:06:19.548  5705  5751 I jxcore-log: emit@events.js:82:1''
11-22 14:06:19.548  5705  5751 I jxcore-log: 
,11-22 14:06:19.549  5705  5751 I jxcore-log: 2016-11-22 13:06:19 - DEBUG CoordinatedClient: 'test client failed'
11-22 14:06:19.549  5705  5751 I jxcore-log: 
,11-22 14:06:19.558  5705  5751 I jxcore-log: 2016-11-22 13:06:19 - ERROR CoordinatedClient: 'connection error: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-22 14:06:19.558  5705  5751 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-22 14:06:19.558  5705  5751 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-22 14:06:19.558  5705  5751 I jxcore-log: emit@events.js:82:1
11-22 14:06:19.558  5705  5751 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-22 14:06:19.558  5705  5751 I jxcore-log: emit@events.js:82:1''
11-22 14:06:19.558  5705  5751 I jxcore-log: 
,11-22 14:06:19.559  5705  5751 I jxcore-log: 2016-11-22 13:06:19 - DEBUG CoordinatedClient: 'test client failed'
11-22 14:06:19.559  5705  5751 I jxcore-log: 
,11-22 14:06:19.562  5705  5751 I jxcore-log: 2016-11-22 13:06:19 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: websocket error', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-22 14:06:19.562  5705  5751 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
,11-22 14:06:19.562  5705  5751 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-22 14:06:19.562  5705  5751 I jxcore-log: emit@events.js:82:1
11-22 14:06:19.562  5705  5751 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-22 14:06:19.562  5705  5751 I jxcore-log: emit@events.js:82:1''
11-22 14:06:19.562  5705  5751 I jxcore-log: 
11-22 14:06:19.564  5705  5751 I jxcore-log: 2016-11-22 13:06:19 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
11-22 14:06:19.564  5705  5751 I jxcore-log: 
,11-22 14:06:20.031  6036  6036 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,11-22 14:06:20.037  6036  6036 D AndroidRuntime: CheckJNI is OFF
,11-22 14:06:20.065  6036  6036 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,11-22 14:06:20.091  6036  6036 I Radio-JNI: register_android_hardware_Radio DONE
,11-22 14:06:20.107  6036  6036 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-22 14:06:20.118   933   946 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,11-22 14:06:20.118   933   946 I ActivityManager: Killing 5705:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,11-22 14:06:20.162   933  3077 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-22 14:06:20.229   933  3514 I WindowState: WIN DEATH: Window{c0d92a5 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,11-22 14:06:20.229   933  3073 D WifiService: Client connection lost with reason: 4
11-22 14:06:20.229   933   944 D GraphicsStats: Buffer count: 2
,11-22 14:06:20.244   933   946 W ActivityManager: Force removing ActivityRecord{e174dc2 u0 com.test.thalitest/.MainActivity t70}: app died, no saved state
,11-22 14:06:20.270   933   956 I art     : Starting a blocking GC Explicit
,11-22 14:06:20.277   933  3513 W ActivityManager: Spurious death for ProcessRecord{aee83f2 0:com.test.thalitest/u0a77}, curProc for 5705: null
,11-22 14:06:20.314   933  3947 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5705 uid 10077
11-22 14:06:20.312  3947  3947 W Binder_8: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[28558]" dev="sockfs" ino=28558 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-22 14:06:20.312  3947  3947 W Binder_8: type=1400 audit(0.0:120): avc: denied { ioctl } for path="socket:[28558]" dev="sockfs" ino=28558 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-22 14:06:20.316  3764  3764 I Keyboard.Facilitator: onFinishInput()
,11-22 14:06:20.376   933   956 I art     : Explicit concurrent mark sweep GC freed 107879(7MB) AllocSpace objects, 59(1728KB) LOS objects, 33% free, 29MB/44MB, paused 1.701ms total 103.924ms
,11-22 14:06:20.394   933   956 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
11-22 14:06:20.394  4067  6048 I MicroRecognitionRnrImpl: Starting detection.
,11-22 14:06:20.396  4067  6049 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.x@a755927
11-22 14:06:20.396  6036  6036 I art     : System.exit called, status: 0
11-22 14:06:20.396  6036  6036 I AndroidRuntime: VM exiting with result code 0.
,11-22 14:06:20.397   507  6052 I AudioFlinger: AudioFlinger's thread 0xf20c0000 ready to run
,11-22 14:06:20.401   933   956 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,11-22 14:06:20.402   507  3094 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,11-22 14:06:20.407  4067  6049 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.x@a755927
11-22 14:06:20.408  5938  5938 D BluetoothMapAppObserver: onReceive
11-22 14:06:20.408  5938  5938 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,11-22 14:06:20.412  3764  3764 I Keyboard.Facilitator: resetDictionaries() : en_US
,11-22 14:06:20.415  3764  6054 I Keyboard.Facilitator.DecoderInitializer: run()
,11-22 14:06:20.417   933  3038 I InputReader: Reconfiguring input devices.  changes=0x00000010
11-22 14:06:20.417  4104  4262 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
11-22 14:06:20.418   507  6052 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(63: voice-rec-mic)
11-22 14:06:20.418   507  6052 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(63) acdb_id(62)
11-22 14:06:20.418   507  6052 I ACDB-LOADER: ACDB AFE returned = -19
11-22 14:06:20.418   507  6052 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 1
,11-22 14:06:20.418   507  6052 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 1, rx 0, concurrency session_allowed 0
11-22 14:06:20.418   507  6052 D audio_hw_primary: enable_snd_device: snd_device(63: voice-rec-mic)
11-22 14:06:20.418  3764  6054 I Decoder : createOrResetDecoder
,11-22 14:06:20.426   507  6052 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,11-22 14:06:20.479    13    13 W kworker/1:0: type=1400 audit(0.0:121): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-22 14:06:20.486  3496  6061 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,11-22 14:06:20.485    13    13 W kworker/1:0: type=1400 audit(0.0:122): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-22 14:06:20.491  3891  3891 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,11-22 14:06:20.496  3672  3672 I ConfigService: onCreate
,11-22 14:06:20.498  3672  6063 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
11-22 14:06:20.498  3672  6063 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-22 14:06:20.498  3672  6063 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-22 14:06:20.498  3672  6063 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-22 14:06:20.498  3672  6063 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-22 14:06:20.498  3672  6063 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-22 14:06:20.498  3672  6063 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-22 14:06:20.498  3672  6063 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-22 14:06:20.498  3672  6063 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-22 14:06:20.498  3672  6063 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-22 14:06:20.498  3672  6063 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-22 14:06:20.498  3672  6063 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-22 14:06:20.498  3672  6063 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-22 14:06:20.498  3672  6063 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-22 14:06:20.498  3672  6063 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-22 14:06:20.498  3672  6063 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
11-22 14:06:20.498  3672  6063 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
11-22 14:06:20.498  3672  6063 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
11-22 14:06:20.499  3672  6063 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
11-22 14:06:20.499  3672  6063 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-22 14:06:20.499  3672  6063 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-22 14:06:20.499  3672  6063 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-22 14:06:20.499  3672  6063 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-22 14:06:20.499  3672  6063 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-22 14:06:20.499  3672  6063 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-22 14:06:20.499  3672  6063 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-22 14:06:20.499  3672  6063 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-22 14:06:20.499  3672  6063 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-22 14:06:20.499  3672  6063 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-22 14:06:20.499  3672  6063 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-22 14:06:20.499  3672  6063 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-22 14:06:20.499  3672  6063 E SQLiteOpenHelper:, 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-22 14:06:20.499  3672  6063 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-22 14:06:20.499  3672  6063 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
11-22 14:06:20.499  3672  6063 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
11-22 14:06:20.499  3672  6063 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
11-22 14:06:20.500  3672  6063 W SQLiteOpenHelper: Opened config.db in read-only mode
11-22 14:06:20.489    13    13 W kworker/1:0: type=1400 audit(0.0:123): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-22 14:06:20.509  4067  4067 I HotwordWorkerImpl: onReady
,11-22 14:06:20.525   933   933 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,11-22 14:06:20.526  3764  6054 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,11-22 14:06:20.530  3929  4035 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,11-22 14:06:20.530   933   945 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,11-22 14:06:20.531   933   945 E PackageManager: Failed to write settings, restoring backup
11-22 14:06:20.531   933   945 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
11-22 14:06:20.531   933   945 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
11-22 14:06:20.531   933   945 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
11-22 14:06:20.531   933   945 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
11-22 14:06:20.531   933   945 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
11-22 14:06:20.531   933   945 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-22 14:06:20.531   933   945 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
11-22 14:06:20.531   933   945 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-22 14:06:20.536   933   946 E DropBoxManagerService: Can't write: system_server_wtf
11-22 14:06:20.536   933   946 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
11-22 14:06:20.536   933   946 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-22 14:06:20.536   933   946 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-22 14:06:20.536   933   946 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-22 14:06:20.536   933   946 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-22 14:06:20.536   933   946 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-22 14:06:20.536   933   946 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-22 14:06:20.536   933   946 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12561)
11-22 14:06:20.536   933   946 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12374)
11-22 14:06:20.536   933   946 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12346)
11-22 14:06:20.536   933   946 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
11-22 14:06:20.536   933   946 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-22 14:06:20.536   933   946 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
11-22 14:06:20.536   933   946 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-22 14:06:20.536   933   946 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
11-22 14:06:20.536   933   946 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-22 14:06:20.536   933   946 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-22 14:06:20.536   933   946 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-22 14:06:20.536   933   946 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-22 14:06:20.536   933   946 E DropBoxManagerService: 	... 13 more
,11-22 14:06:20.537  3496  6061 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,11-22 14:06:20.541  3672  3672 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,11-22 14:06:20.541  3672  3672 D AndroidRuntime: Shutting down VM
--------- beginning of crash
11-22 14:06:20.542  3672  3672 E AndroidRuntime: FATAL EXCEPTION: main
11-22 14:06:20.542  3672  3672 E AndroidRuntime: Process: com.google.process.gapps, PID: 3672
11-22 14:06:20.542  3672  3672 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-22 14:06:20.542  3672  3672 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
11-22 14:06:20.542  3672  3672 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
11-22 14:06:20.542  3672  3672 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
11-22 14:06:20.542  3672  3672 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-22 14:06:20.542  3672  3672 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-22 14:06:20.542  3672  3672 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-22 14:06:20.542  3672  3672 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
11-22 14:06:20.542  3672  3672 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-22 14:06:20.542  3672  3672 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-22 14:06:20.542  3672  3672 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-22 14:06:20.542  3672  3672 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-22 14:06:20.542  3672  3672 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-22 14:06:20.542  3672  3672 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-22 14:06:20.542  3672  3672 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-22 14:06:20.542  3672  3672 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-22 14:06:20.542  3672  3672 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
11-22 14:06:20.542  3672  3672 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
11-22 14:06:20.542  3672  3672 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
11-22 14:06:20.542  3672  3672 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
11-22 14:06:20.542  3672  3672 E AndroidRuntime: 	... 8 more
,11-22 14:06:20.543  3496  6061 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
11-22 14:06:20.543  3496  6061 E AndroidRuntime: Process: android.process.acore, PID: 3496
11-22 14:06:20.543  3496  6061 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-22 14:06:20.543  3496  6061 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-22 14:06:20.543  3496  6061 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-22 14:06:20.543  3496  6061 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-22 14:06:20.543  3496  6061 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-22 14:06:20.543  3496  6061 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-22 14:06:20.543  3496  6061 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
11-22 14:06:20.543  3496  6061 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
11-22 14:06:20.543  3496  6061 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
11-22 14:06:20.543  3496  6061 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
11-22 14:06:20.543  3496  6061 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
11-22 14:06:20.543  3496  6061 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
11-22 14:06:20.543  3496  6061 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
11-22 14:06:20.543  3496  6061 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-22 14:06:20.543  3496  6061 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-22 14:06:20.543  3496  6061 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-22 14:06:20.543  3496  6061 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-22 14:06:20.544   933  3964 I ActivityManager: Start proc 6067:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,11-22 14:06:20.546  3929  4035 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
11-22 14:06:20.546  3929  4035 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3929
11-22 14:06:20.546  3929  4035 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-22 14:06:20.546  3929  4035 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-22 14:06:20.546  3929  4035 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-22 14:06:20.546  3929  4035 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-22 14:06:20.546  3929  4035 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-22 14:06:20.546  3929  4035 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-22 14:06:20.546  3929  4035 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
11-22 14:06:20.546  3929  4035 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
11-22 14:06:20.546  3929  4035 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
11-22 14:06:20.546  3929  4035 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-22 14:06:20.546  3929  4035 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-22 14:06:20.546  3929  4035 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-22 14:06:20.552   933  6075 E DropBoxManagerService: Can't write: system_app_crash
11-22 14:06:20.552   933  6075 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop124.tmp: open failed: EROFS (Read-only file system)
11-22 14:06:20.552   933  6075 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-22 14:06:20.552   933  6075 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-22 14:06:20.552   933  6075 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-22 14:06:20.552   933  6075 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-22 14:06:20.552   933  6075 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-22 14:06:20.552   933  6075 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-22 14:06:20.552   933  6075 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-22 14:06:20.552   933  6075 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-22 14:06:20.552   933  6075 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-22 14:06:20.552   933  6075 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-22 14:06:20.552   933  6075 E DropBoxManagerService: 	... 5 more
,11-22 14:06:20.558   933  6080 E DropBoxManagerService: Can't write: system_app_crash
11-22 14:06:20.558   933  6080 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
11-22 14:06:20.558   933  6080 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-22 14:06:20.558   933  6080 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-22 14:06:20.558   933  6080 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-22 14:06:20.558   933  6080 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-22 14:06:20.558   933  6080 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-22 14:06:20.558   933  6080 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-22 14:06:20.558   933  6080 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-22 14:06:20.558   933  6080 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-22 14:06:20.558   933  6080 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-22 14:06:20.558   933  6080 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-22 14:06:20.558   933  6080 E DropBoxManagerService: 	... 5 more
,11-22 14:06:20.557   933  6078 E DropBoxManagerService: Can't write: system_app_crash
11-22 14:06:20.557   933  6078 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
11-22 14:06:20.557   933  6078 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-22 14:06:20.557   933  6078 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-22 14:06:20.557   933  6078 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-22 14:06:20.557   933  6078 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-22 14:06:20.557   933  6078 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-22 14:06:20.557   933  6078 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-22 14:06:20.557   933  6078 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-22 14:06:20.557   933  6078 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-22 14:06:20.557   933  6078 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-22 14:06:20.557   933  6078 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-22 14:06:20.557   933  6078 E DropBoxManagerService: 	... 5 more
11-22 14:06:20.557   933  3931 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
11-22 14:06:20.563  4067  4375 W SearchService: Abort, client detached.
11-22 14:06:20.565  4067  4067 I HotwordDetector: Closing mic
11-22 14:06:20.565  4067  4308 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@a755927
11-22 14:06:20.566  4067  6049 E AudioRecord-JNI: Error -4 during AudioRecord native read
11-22 14:06:20.575  3764  6054 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
11-22 14:06:20.577  3764  6054 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
11-22 14:06:20.577  3764  6054 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
11-22 14:06:20.579  3764  6054 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
11-22 14:06:20.579  3764  6054 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
11-22 14:06:20.579  3764  6054 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
11-22 14:06:20.580  3764  6054 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
11-22 14:06:20.580  3764  6054 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
11-22 14:06:20.580  3764  6054 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
11-22 14:06:20.580  3764  6054 I Keyboard.Facilitator.Delight2FileSweeper: run()
11-22 14:06:20.580  3764  6054 I Keyboard.Facilitator.RecurringTaskScheduler: run()
11-22 14:06:20.580  3764  6054 I StatsUtilsManager: startPeriodStatsRecorder() : Success
11-22 14:06:20.580  3764  6054 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
11-22 14:06:20.579   728   728 W Binder_4: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[22469]" dev="sockfs" ino=22469 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-22 14:06:20.579   728   728 W Binder_4: type=1400 audit(0.0:125): avc: denied { ioctl } for path="socket:[22469]" dev="sockfs" ino=22469 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-22 14:06:20.582   406   406 W Binder_2: type=1400 audit(0.0:126): avc: denied { ioctl } for path="socket:[33680]" dev="sockfs" ino=33680 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-22 14:06:20.582   406   406 W Binder_2: type=1400 audit(0.0:127): avc: denied { ioctl } for path="socket:[33680]" dev="sockfs" ino=33680 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-22 14:06:20.587   933  6083 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-22 14:06:20.629   507  6052 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
11-22 14:06:20.630   507  6052 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
,11-22 14:06:20.637   507  6052 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
,11-22 14:06:20.637   507  6052 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
11-22 14:06:20.638   507  3094 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,11-22 14:06:20.639  4067  4314 I MicroRecognitionRnrImpl: Stopping hotword detection.
11-22 14:06:20.639  4067  6048 I MicroRecognitionRnrImpl: Detection finished

```
