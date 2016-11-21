#### Test 94626375b5fe2b0_thali07_Huawei-Nexus 6P Logs


```
--------- beginning of main
11-21 17:39:05.216   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:39:05.704  5584  5584 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-21 17:39:05.709  5584  5584 D AndroidRuntime: CheckJNI is OFF
11-21 17:39:05.737  5584  5584 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-21 17:39:05.785  5584  5584 I Radio-JNI: register_android_hardware_Radio DONE
11-21 17:39:05.800  5584  5584 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
11-21 17:39:05.804   930   941 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
11-21 17:39:05.821  5584  5584 D AndroidRuntime: Shutting down VM
11-21 17:39:05.825  3946  5574 W SearchService: Abort, client detached.
11-21 17:39:05.834  3946  3946 I HotwordDetector: Closing mic
11-21 17:39:05.834  3946  4157 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@f80e8a6
11-21 17:39:05.835  3946  4175 E AudioRecord-JNI: Error -4 during AudioRecord native read
11-21 17:39:05.858   930  3824 I ActivityManager: Start proc 5593:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
11-21 17:39:05.904   514  4180 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
11-21 17:39:05.906   514  4180 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
11-21 17:39:05.914   514  4180 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
11-21 17:39:05.915   514  4180 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
11-21 17:39:05.916   514  2983 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-21 17:39:05.918  3946  4171 I MicroRecognitionRnrImpl: Detection finished
11-21 17:39:05.919  3946  4158 I MicroRecognitionRnrImpl: Stopping hotword detection.
11-21 17:39:05.957  5593  5593 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
11-21 17:39:05.976  5593  5593 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
11-21 17:39:06.000  5593  5593 I LibraryLoader: Time to load native libraries: 20 ms (timestamps 5253-5273)
11-21 17:39:06.000  5593  5593 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-21 17:39:06.027  5593  5593 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {f003cc3}
11-21 17:39:06.028  5593  5593 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-21 17:39:06.028  5593  5593 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
11-21 17:39:06.031  5593  5593 I BrowserStartupController: Initializing chromium process, singleProcess=true
11-21 17:39:06.032  5593  5593 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-21 17:39:06.066  5593  5593 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-21 17:39:06.074  5593  5593 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-21 17:39:06.075  5593  5593 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-21 17:39:06.075  5593  5593 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-21 17:39:06.075  5593  5593 I Adreno  : Build Date                       : 12/06/15
11-21 17:39:06.075  5593  5593 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-21 17:39:06.075  5593  5593 I Adreno  : Local Branch                     : mybranch17112971
11-21 17:39:06.075  5593  5593 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-21 17:39:06.075  5593  5593 I Adreno  : Remote Branch                    : NONE
11-21 17:39:06.075  5593  5593 I Adreno  : Reconstruct Branch               : NOTHING
,11-21 17:39:06.122   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f6d6d75:true
,11-21 17:39:06.162   407   407 W Binder_1: type=1400 audit(0.0:99): avc: denied { ioctl } for path="socket:[32843]" dev="sockfs" ino=32843 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-21 17:39:06.162   407   407 W Binder_1: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[32843]" dev="sockfs" ino=32843 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-21 17:39:06.175  5593  5593 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-21 17:39:06.184  5593  5593 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-21 17:39:06.212   407   407 W Binder_1: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[31514]" dev="sockfs" ino=31514 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-21 17:39:06.212   407   407 W Binder_1: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[31514]" dev="sockfs" ino=31514 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-21 17:39:06.213  5593  5630 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-21 17:39:06.216   537   537 I ServiceManager: Waiting for service AtCmdFwd...
11-21 17:39:06.215  3833  3833 W Binder_A: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[32848]" dev="sockfs" ino=32848 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-21 17:39:06.215  3833  3833 W Binder_A: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[32848]" dev="sockfs" ino=32848 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-21 17:39:06.217  5593  5617 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-21 17:39:06.242  5593  5630 I OpenGLRenderer: Initialized EGL, version 1.4
,11-21 17:39:06.322  3521  3521 W Binder_5: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[32079]" dev="sockfs" ino=32079 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-21 17:39:06.322  3521  3521 W Binder_5: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[32079]" dev="sockfs" ino=32079 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-21 17:39:06.322  3802  3802 W Binder_7: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[32078]" dev="sockfs" ino=32078 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-21 17:39:06.325   930   948 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +494ms
11-21 17:39:06.328  3652  3652 I Keyboard.Facilitator: onFinishInput()
11-21 17:39:06.325  3802  3802 W Binder_7: type=1400 audit(0.0:108): avc: denied { ioctl } for path="socket:[32078]" dev="sockfs" ino=32078 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-21 17:39:06.385  5593  5593 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5593
,11-21 17:39:06.495  5593  5593 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,11-21 17:39:06.646   930  3521 I ActivityManager: Killing 5262:com.android.settings/1000 (adj 15): empty #17
,11-21 17:39:06.667   930  3521 I ActivityManager: Killing 5224:org.codeaurora.ims/1001 (adj 15): empty #18
,11-21 17:39:06.770  5593  5632 D jxcore_app_log: JniHelper::setJavaVM(0xf507c000), pthread_self() = -581437136
,11-21 17:39:06.778  5593  5632 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-21 17:39:06.778  5593  5632 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-21 17:39:06.778  5593  5632 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-21 17:39:06.778  5593  5632 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-21 17:39:06.778  5593  5632 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,11-21 17:39:06.779  5593  5632 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e50d56 added. We now have 1 listener(s)
,11-21 17:39:06.784  5593  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:D4
,11-21 17:39:06.785  5593  5632 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-21 17:39:06.787  5593  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-21 17:39:06.788  5593  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-21 17:39:06.793  5593  5632 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-21 17:39:06.793  5593  5632 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-21 17:39:06.793  5593  5632 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-21 17:39:06.793  5593  5632 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:D4
11-21 17:39:06.793  5593  5632 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-21 17:39:06.793  5593  5632 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-21 17:39:06.793  5593  5632 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-21 17:39:06.793  5593  5632 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-21 17:39:06.793  5593  5632 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-21 17:39:06.793  5593  5632 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-21 17:39:06.793  5593  5632 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-21 17:39:06.793  5593  5632 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-21 17:39:06.793  5593  5632 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-21 17:39:06.793  5593  5632 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,11-21 17:39:06.793  5593  5632 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bbfbdad added. We now have 1 listener(s)
11-21 17:39:06.794  5593  5632 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-21 17:39:06.799   930  2985 D WifiService: New client listening to asynchronous messages
,11-21 17:39:06.800  5593  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-21 17:39:06.800  5593  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
11-21 17:39:06.800  5593  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 51
11-21 17:39:06.800  5593  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
11-21 17:39:06.801  5593  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
11-21 17:39:06.801  5593  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
11-21 17:39:06.801  5593  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 51
,11-21 17:39:06.803  5593  5632 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-21 17:39:06.976  5593  5593 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,11-21 17:39:07.217   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:39:07.299  5593  5602 I art     : Background sticky concurrent mark sweep GC freed 77539(7MB) AllocSpace objects, 16(1476KB) LOS objects, 26% free, 24MB/32MB, paused 1.543ms total 249.793ms
,11-21 17:39:08.218   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:39:08.487  5593  5641 W jxcore-log: Initializing JXcore engine
,11-21 17:39:08.488  5593  5641 W jxcore-log: JXcore engine is ready
,11-21 17:39:08.515  5641  5641 W Thread-58: type=1400 audit(0.0:109): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12099 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
11-21 17:39:08.515  5641  5641 W Thread-58: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[17609]" dev="sockfs" ino=17609 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,11-21 17:39:08.515  5641  5641 W Thread-58: type=1400 audit(0.0:111): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
11-21 17:39:08.515  5641  5641 W Thread-58: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[31479]" dev="sockfs" ino=31479 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,11-21 17:39:08.527  5593  5641 W jxcore-log: Starting JXcore engine
,11-21 17:39:08.577  5593  5641 W jxcore-log: Platform android
11-21 17:39:08.577  5593  5641 W jxcore-log: 
,11-21 17:39:08.577  5593  5641 W jxcore-log: Process ARCH arm
11-21 17:39:08.577  5593  5641 W jxcore-log: 
,11-21 17:39:08.723  5593  5641 I jxcore-log: JXcore Cordova bridge is ready!
11-21 17:39:08.723  5593  5641 I jxcore-log: 
,11-21 17:39:08.723  5593  5641 W jxcore-log: JXcore engine is started
,11-21 17:39:08.734  5593  5632 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,11-21 17:39:08.739  5593  5593 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-21 17:39:09.219   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:39:10.220   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-21 17:39:16.450  4082  4445 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,11-21 17:39:17.510  3544  5646 I VacuumService: Vacuum at: now=1479746357510 tag=VacuumService
,11-21 17:39:17.517  3946  5642 W CronetSyncConnectionRcs: Upload content type not set.
,11-21 17:39:17.519   930  2985 D WifiService: New client listening to asynchronous messages
,11-21 17:39:17.552  3544  5656 D GetConfigurationSnapshotOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,11-21 17:39:17.578  3544  5647 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,11-21 17:39:17.581  3544  5647 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,11-21 17:39:17.602  3544  5647 W Uploader:  no longer exists, so no auth token.
,11-21 17:39:17.608  3544  5656 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-21 17:39:17.937  3544  5647 W Uploader:  no longer exists, so no auth token.
,11-21 17:39:17.944  3544  5660 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-21 17:39:18.222  3544  5656 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-21 17:39:18.300  3544  5660 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-21 17:39:18.333  5593  5641 I jxcore-log: 2016-11-21 16:39:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-21 17:39:18.333  5593  5641 I jxcore-log: 
,11-21 17:39:18.335  5593  5641 I jxcore-log: 2016-11-21 16:39:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-21 17:39:18.335  5593  5641 I jxcore-log: 
,11-21 17:39:18.335  5593  5641 I jxcore-log: 2016-11-21 16:39:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
11-21 17:39:18.335  5593  5641 I jxcore-log: 
,11-21 17:39:18.339  5593  5641 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
11-21 17:39:18.339  5593  5641 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-21 17:39:18.339  5593  5641 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-21 17:39:18.339  5593  5641 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-21 17:39:18.339  5593  5641 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-21 17:39:18.339  5593  5641 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-21 17:39:18.339  5593  5641 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-21 17:39:18.339  5593  5641 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-21 17:39:18.339  5593  5641 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-21 17:39:18.339  5593  5641 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-21 17:39:18.341  5593  5641 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-21 17:39:18.342  5593  5641 I jxcore-log: 2016-11-21 16:39:18 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
11-21 17:39:18.342  5593  5641 I jxcore-log: 
,11-21 17:39:18.344  5593  5641 I jxcore-log: 2016-11-21 16:39:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
11-21 17:39:18.344  5593  5641 I jxcore-log: 
,11-21 17:39:18.345  5593  5641 I jxcore-log: 2016-11-21 16:39:18 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-21 17:39:18.345  5593  5641 I jxcore-log: 
,11-21 17:39:18.391  3544  5656 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-21 17:39:18.583  5593  5641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-21 17:39:18.584  5593  5641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@47d7 added. We now have 2 listener(s)
11-21 17:39:18.584  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-21 17:39:18.584  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-21 17:39:18.584  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-21 17:39:18.585  5593  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-21 17:39:18.585  5593  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d4c48c4 added. We now have 2 listener(s)
11-21 17:39:18.585  5593  5641 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-21 17:39:18.585  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-21 17:39:18.586  5593  5641 D ExecuteNativeTests: Running unit tests
,11-21 17:39:18.587  5593  5641 D BluetoothAdapter: enable(): BT is already enabled..!
,11-21 17:39:18.587   930  3802 D WifiService: setWifiEnabled: true pid=5593, uid=10077
11-21 17:39:18.587   930  3802 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-21 17:39:20.253   930  2982 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-21 17:39:22.564   930  5331 D NetlinkSocketObserver: NeighborEvent{elapsedMs=161837, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-21 17:39:25.221   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:39:26.223   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:39:27.224   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:39:28.226   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:39:28.594  5593  5641 I com.test.thalitest.ThaliTestRunner: Running UT
,11-21 17:39:28.658  5593  5641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-21 17:39:28.658  5593  5641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8553cb6 added. We now have 3 listener(s)
,11-21 17:39:28.659  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-21 17:39:28.659  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-21 17:39:28.659  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-21 17:39:28.659  5593  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-21 17:39:28.659  5593  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f8e7db7 added. We now have 3 listener(s)
11-21 17:39:28.659  5593  5641 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-21 17:39:28.660  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-21 17:39:28.664  5593  5641 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionTimeout
,11-21 17:39:28.664  5593  5641 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-21 17:39:28.664  5593  5641 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-21 17:39:28.664  5593  5641 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-21 17:39:28.664  5593  5641 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-21 17:39:28.665  5593  5641 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
11-21 17:39:28.666  5593  5641 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-21 17:39:28.666  5593  5641 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-21 17:39:28.666  5593  5641 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-21 17:39:28.666  5593  5641 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-21 17:39:28.666  5593  5641 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-21 17:39:28.667  5593  5641 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnBluetoothMacAddressResolved
11-21 17:39:28.667  5593  5641 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,11-21 17:39:28.668  5593  5641 I io.jxcore.node.ConnectionHelperTest: Starting test: testHasMaximumNumberOfConnections
11-21 17:39:28.670  5593  5641 I io.jxcore.node.ConnectionHelperTest: Starting test: testStart
11-21 17:39:28.670  5593  5641 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-21 17:39:28.672  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-21 17:39:28.672  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-21 17:39:28.682  5593  5641 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-21 17:39:28.682  5593  5641 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-21 17:39:28.682  5593  5641 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-21 17:39:28.682  5593  5641 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-21 17:39:28.682  5593  5641 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-21 17:39:28.682  5593  5641 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-21 17:39:28.682  5593  5641 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-21 17:39:28.682  5593  5641 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-21 17:39:28.682  5593  5641 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-21 17:39:28.683  5593  5641 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-21 17:39:28.683  5593  5641 D io.jxcore.node.ConnectivityMonitor: start: OK
11-21 17:39:28.684  5593  5641 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
11-21 17:39:28.684  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
11-21 17:39:28.684  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:28.684  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-58,5,main], id: 58
,11-21 17:39:28.684  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:28.684  5593  5641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-21 17:39:28.684  5593  5641 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-21 17:39:28.684  5593  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,11-21 17:39:28.684  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-21 17:39:28.685  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-21 17:39:28.685  5593  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-21 17:39:28.685  5593  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-21 17:39:28.692  4607  4607 W Binder_1: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[33805]" dev="sockfs" ino=33805 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-21 17:39:28.685  5593  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,11-21 17:39:28.685  5593  5641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-21 17:39:28.686  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-21 17:39:28.686  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-21 17:39:28.686  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-21 17:39:28.686  5593  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-21 17:39:28.689  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-21 17:39:28.689  5593  5666 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-21 17:39:28.692  4607  4607 W Binder_1: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[33805]" dev="sockfs" ino=33805 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-21 17:39:28.690  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-21 17:39:28.690  5593  5641 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-21 17:39:28.690  5593  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-21 17:39:28.692  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-58,5,main], id: 58
,11-21 17:39:28.692  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-21 17:39:28.694  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-21 17:39:28.694  5593  5593 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-21 17:39:28.694  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-21 17:39:28.695  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-21 17:39:28.695  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 1
11-21 17:39:28.695  5593  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-21 17:39:28.696  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-58,5,main], id: 58
,11-21 17:39:28.696  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:28.696  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-21 17:39:28.696  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-21 17:39:28.696  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-21 17:39:28.696  5593  5641 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 60 83 34 25 D7 D4
11-21 17:39:28.697  5593  5641 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 17:39:28.697  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 17:39:28.697  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:28.697  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-21 17:39:28.697  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 17:39:28.697  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:28.697  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:28.697  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:28.698  5593  5641 D BluetoothAdapter: STATE_ON
11-21 17:39:28.701  4596  4607 D BtGatt.GattService: registerClient() - UUID=927f1205-2e78-4e16-be93-063a987658f3
11-21 17:39:28.702  4596  4658 D BtGatt.GattService: onClientRegistered() - UUID=927f1205-2e78-4e16-be93-063a987658f3, clientIf=5
,11-21 17:39:28.703  5593  5604 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-21 17:39:28.706  4596  4660 D BtGatt.AdvertiseManager: message : 0
,11-21 17:39:28.708  4596  4660 D BtGatt.AdvertiseManager: starting multi advertising
,11-21 17:39:28.724  4596  4658 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-21 17:39:28.731  4596  4658 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-21 17:39:28.733  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-58,5,main], id: 58
,11-21 17:39:28.733  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:28.733  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-21 17:39:28.733  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-58,5,main], id: 58
,11-21 17:39:28.733  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:28.733  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:28.733  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:28.733  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:28.733  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-21 17:39:28.734  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-21 17:39:28.734  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:28.734  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:28.734  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:28.734  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:28.735  5593  5641 I io.jxcore.node.ConnectionHelper: start: OK
11-21 17:39:28.735  5593  5593 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,11-21 17:39:28.735  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
,11-21 17:39:28.735  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-21 17:39:28.735  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-21 17:39:28.736  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-21 17:39:28.736  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-21 17:39:28.736  5593  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-21 17:39:28.736  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-21 17:39:28.736  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-21 17:39:28.737  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-21 17:39:28.737  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-21 17:39:28.737  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-21 17:39:28.737  5593  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-21 17:39:28.737  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-21 17:39:28.740  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-21 17:39:28.740  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-21 17:39:28.741  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-21 17:39:28.741  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-21 17:39:28.741  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-21 17:39:28.741  5593  5593 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-21 17:39:29.235   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:39:29.238  5593  5641 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-21 17:39:29.238  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,11-21 17:39:29.238  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-21 17:39:29.238  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,11-21 17:39:29.238  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-21 17:39:29.238  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,11-21 17:39:29.238  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-21 17:39:29.239  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,11-21 17:39:29.239  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-21 17:39:29.239  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-21 17:39:29.239  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-21 17:39:29.239  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,11-21 17:39:29.239  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,11-21 17:39:29.240  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-21 17:39:29.240  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-21 17:39:29.240  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-21 17:39:29.240  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-21 17:39:29.240  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,11-21 17:39:29.240  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-21 17:39:29.240  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-21 17:39:29.240  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-21 17:39:29.240  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-21 17:39:29.241  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-21 17:39:29.241  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-21 17:39:29.241  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-21 17:39:29.241  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-21 17:39:29.241  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-21 17:39:29.241  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-21 17:39:29.241  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-21 17:39:29.241  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-21 17:39:29.242  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-21 17:39:29.242  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-21 17:39:29.242  5593  5641 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-21 17:39:29.242  5593  5641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
11-21 17:39:29.242  5593  5641 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-21 17:39:29.242  5593  5641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-21 17:39:29.243  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-21 17:39:29.243  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-21 17:39:29.243  5593  5593 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-21 17:39:29.243  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-21 17:39:29.243  5593  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-21 17:39:29.243  5593  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-21 17:39:29.244  5593  5641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-21 17:39:29.244  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-21 17:39:29.244  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-21 17:39:29.244  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-21 17:39:29.244  5593  5666 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-21 17:39:29.244  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:29.244  5593  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-21 17:39:29.245  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:29.245  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-58,5,main], id: 58
,11-21 17:39:29.245  5593  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-21 17:39:29.245  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:29.246  5593  5641 D BluetoothAdapter: STATE_ON
11-21 17:39:29.246  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,11-21 17:39:29.247  5593  5641 D BluetoothAdapter: STATE_ON
11-21 17:39:29.247  5593  5641 D BluetoothLeScanner: could not find callback wrapper
11-21 17:39:29.248  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-21 17:39:29.248  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:29.248  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-58,5,main], id: 58
,11-21 17:39:29.248  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:29.248  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-21 17:39:29.248  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:29.249  4596  4660 D BtGatt.AdvertiseManager: message : 1
11-21 17:39:29.251  4596  4660 D BtGatt.AdvertiseManager: stop advertise for client 5
11-21 17:39:29.266  4596  4658 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-21 17:39:29.267  4596  4658 D BtGatt.GattService: Client app is not null!
11-21 17:39:29.268  4596  4806 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-21 17:39:29.270  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-21 17:39:29.270  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:29.271  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,11-21 17:39:29.271  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:29.271  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:29.271  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:29.271  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-21 17:39:29.272  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-21 17:39:29.274  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-21 17:39:29.274  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
,11-21 17:39:29.276  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:29.276  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-21 17:39:29.276  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:29.276  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:29.277  5593  5593 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-21 17:39:29.277  5593  5593 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-21 17:39:29.279  5593  5593 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-21 17:39:29.279  5593  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-21 17:39:29.280  5593  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-21 17:39:29.280  5593  5593 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-21 17:39:29.280  5593  5593 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-21 17:39:29.280  5593  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-21 17:39:29.280  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-21 17:39:29.281  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-21 17:39:29.281  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-21 17:39:29.281  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-21 17:39:29.281  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-21 17:39:29.281  5593  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-21 17:39:29.281  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-21 17:39:29.282  5593  5641 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-21 17:39:29.282  5593  5641 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-21 17:39:29.282  5593  5641 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
11-21 17:39:29.282  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
11-21 17:39:29.282  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:29.282  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:29.283  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:29.283  5593  5641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-21 17:39:29.283  5593  5641 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-21 17:39:29.283  5593  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-21 17:39:29.283  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-21 17:39:29.285  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-21 17:39:29.285  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-21 17:39:29.285  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-21 17:39:29.285  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-21 17:39:29.286  5593  5593 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-21 17:39:29.287  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-21 17:39:29.288  5593  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-21 17:39:29.288  5593  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-21 17:39:29.288  5593  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-21 17:39:29.288  5593  5641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-21 17:39:29.288  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-21 17:39:29.288  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-21 17:39:29.289  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-21 17:39:29.289  5593  5593 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-21 17:39:29.290  5593  5669 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-21 17:39:29.291  5593  5669 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-21 17:39:29.292  4607  4607 W Binder_1: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[33812]" dev="sockfs" ino=33812 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-21 17:39:29.292  4607  4607 W Binder_1: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[33812]" dev="sockfs" ino=33812 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-21 17:39:29.297  5593  5669 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-21 17:39:29.297  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-21 17:39:29.297  5593  5641 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-21 17:39:29.297  5593  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-21 17:39:29.301  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:29.302  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-21 17:39:29.303  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-21 17:39:29.303  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-21 17:39:29.303  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 2
11-21 17:39:29.307  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:29.308  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:29.308  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-21 17:39:29.308  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-21 17:39:29.308  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-21 17:39:29.308  5593  5641 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 60 83 34 25 D7 D4
11-21 17:39:29.308  5593  5641 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 17:39:29.308  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 17:39:29.309  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:29.309  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-21 17:39:29.309  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 17:39:29.309  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:29.309  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:29.309  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:29.311  5593  5641 D BluetoothAdapter: STATE_ON
,11-21 17:39:29.314  4596  4609 D BtGatt.GattService: registerClient() - UUID=e576addc-ecb9-41d5-89e2-cb6de7cb6b21
11-21 17:39:29.315  4596  4658 D BtGatt.GattService: onClientRegistered() - UUID=e576addc-ecb9-41d5-89e2-cb6de7cb6b21, clientIf=5
11-21 17:39:29.315  5593  5604 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-21 17:39:29.316  4596  4660 D BtGatt.AdvertiseManager: message : 0
11-21 17:39:29.319  4596  4660 D BtGatt.AdvertiseManager: starting multi advertising
11-21 17:39:29.332  4596  4658 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
11-21 17:39:29.339  4596  4658 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
11-21 17:39:29.340  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:29.340  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:29.340  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-21 17:39:29.340  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:29.341  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:29.341  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:29.341  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:29.341  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:29.341  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-21 17:39:29.342  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-21 17:39:29.343  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:29.344  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:29.344  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:29.344  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:29.344  5593  5641 I io.jxcore.node.ConnectionHelper: start: OK
11-21 17:39:29.345  5593  5593 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-21 17:39:29.345  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-21 17:39:29.345  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-21 17:39:29.345  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-21 17:39:29.345  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-21 17:39:29.345  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-21 17:39:29.345  5593  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-21 17:39:29.346  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-21 17:39:29.346  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-21 17:39:29.346  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-21 17:39:29.346  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-21 17:39:29.346  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-21 17:39:29.346  5593  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-21 17:39:29.346  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-21 17:39:29.349  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-21 17:39:29.349  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-21 17:39:29.350  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-21 17:39:29.350  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-21 17:39:29.350  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-21 17:39:29.350  5593  5593 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-21 17:39:29.849  5593  5641 I io.jxcore.node.ConnectionHelperTest: Starting test: testStop
11-21 17:39:29.849  5593  5641 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-21 17:39:29.849  5593  5641 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-21 17:39:29.849  5593  5641 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-21 17:39:29.850  5593  5641 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
,11-21 17:39:29.850  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
11-21 17:39:29.850  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:29.851  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:29.851  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:29.851  5593  5593 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-21 17:39:29.854  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
11-21 17:39:29.854  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
11-21 17:39:29.854  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
11-21 17:39:29.854  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 3
11-21 17:39:29.854  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
11-21 17:39:29.854  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
11-21 17:39:29.854  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
11-21 17:39:29.854  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
11-21 17:39:29.854  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
11-21 17:39:29.854  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:29.854  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 3
11-21 17:39:29.856  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: advertiserWasStarted true Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:29.856  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: stop advertiser Current thread: Thread[Thread-58,5,main], id: 58
,11-21 17:39:29.856  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:29.858  4596  4660 D BtGatt.AdvertiseManager: message : 1
,11-21 17:39:29.860  4596  4660 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-21 17:39:29.874  4596  4658 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-21 17:39:29.874  4596  4658 D BtGatt.GattService: Client app is not null!
,11-21 17:39:29.876  4596  4607 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-21 17:39:29.877  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-21 17:39:29.877  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:29.877  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-21 17:39:29.878  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:29.878  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:29.878  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-58,5,main], id: 58
,11-21 17:39:29.878  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-21 17:39:29.878  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start advertiser Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:29.879  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:29.879  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:29.879  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,11-21 17:39:29.879  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-21 17:39:29.879  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-21 17:39:29.879  5593  5641 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 60 83 34 25 D7 D4
,11-21 17:39:29.881  5593  5641 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 17:39:29.882  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 17:39:29.882  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:29.882  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-21 17:39:29.882  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 17:39:29.882  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-58,5,main], id: 58
,11-21 17:39:29.883  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:29.883  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:29.885  5593  5641 D BluetoothAdapter: STATE_ON
11-21 17:39:29.889  4596  4607 D BtGatt.GattService: registerClient() - UUID=32fac81b-8b9b-4a5e-aaa9-9b778e2f4672
,11-21 17:39:29.890  4596  4658 D BtGatt.GattService: onClientRegistered() - UUID=32fac81b-8b9b-4a5e-aaa9-9b778e2f4672, clientIf=5
11-21 17:39:29.891  5593  5603 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-21 17:39:29.893  4596  4660 D BtGatt.AdvertiseManager: message : 0
,11-21 17:39:29.897  4596  4660 D BtGatt.AdvertiseManager: starting multi advertising
,11-21 17:39:29.911  4596  4658 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-21 17:39:29.919  4596  4658 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
11-21 17:39:29.920  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-58,5,main], id: 58
,11-21 17:39:29.920  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:29.920  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-21 17:39:29.921  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:29.921  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:29.921  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-58,5,main], id: 58
,11-21 17:39:29.921  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:29.921  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-58,5,main], id: 58
,11-21 17:39:29.921  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start advertiser started = true Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:29.921  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-21 17:39:29.921  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: scannerWasStarted false Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:29.921  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-21 17:39:29.921  5593  5641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-21 17:39:29.922  5593  5641 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-21 17:39:29.922  5593  5641 I io.jxcore.node.ConnectionHelper: start: OK
,11-21 17:39:29.922  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-21 17:39:29.922  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-21 17:39:29.922  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-21 17:39:29.922  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-21 17:39:29.923  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-21 17:39:29.923  5593  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-21 17:39:29.923  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-21 17:39:29.923  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-21 17:39:29.923  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-21 17:39:29.923  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-21 17:39:29.923  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-21 17:39:29.923  5593  5641 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-21 17:39:29.923  5593  5641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
11-21 17:39:29.924  5593  5641 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,11-21 17:39:29.924  5593  5641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-21 17:39:29.924  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-21 17:39:29.924  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-21 17:39:29.924  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-21 17:39:29.924  5593  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-21 17:39:29.924  5593  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-21 17:39:29.924  5593  5641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-21 17:39:29.924  5593  5669 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-21 17:39:29.924  5593  5669 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,11-21 17:39:29.924  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-21 17:39:29.924  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-21 17:39:29.924  5593  5669 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-21 17:39:29.924  5593  5593 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,11-21 17:39:29.924  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-21 17:39:29.925  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:29.925  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:29.925  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-58,5,main], id: 58
,11-21 17:39:29.925  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:29.926  5593  5641 D BluetoothAdapter: STATE_ON
11-21 17:39:29.926  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-21 17:39:29.927  5593  5641 D BluetoothAdapter: STATE_ON
11-21 17:39:29.927  5593  5641 D BluetoothLeScanner: could not find callback wrapper
11-21 17:39:29.927  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-21 17:39:29.927  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:29.927  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:29.927  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:29.927  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,11-21 17:39:29.927  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:29.928  4596  4660 D BtGatt.AdvertiseManager: message : 1
11-21 17:39:29.929  4596  4660 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-21 17:39:29.937  4596  4658 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,11-21 17:39:29.937  4596  4658 D BtGatt.GattService: Client app is not null!
,11-21 17:39:29.938  4596  4806 D BtGatt.GattService: unregisterClient() - clientIf=5
11-21 17:39:29.939  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-21 17:39:29.939  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-58,5,main], id: 58
,11-21 17:39:29.939  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-21 17:39:29.940  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:29.940  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:29.940  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:29.940  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-21 17:39:29.940  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-21 17:39:29.941  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-21 17:39:29.941  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
,11-21 17:39:29.942  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:29.943  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-21 17:39:29.943  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
,11-21 17:39:29.943  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:29.943  5593  5593 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-21 17:39:29.943  5593  5593 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-21 17:39:29.943  5593  5593 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,11-21 17:39:29.943  5593  5593 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-21 17:39:29.944  5593  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-21 17:39:29.944  5593  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-21 17:39:29.944  5593  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-21 17:39:29.944  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-21 17:39:29.944  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-21 17:39:29.944  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-21 17:39:29.944  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-21 17:39:29.944  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-21 17:39:29.944  5593  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-21 17:39:29.944  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-21 17:39:29.945  5593  5641 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPeerReadyToProvideBluetoothMacAddress
11-21 17:39:29.945  5593  5641 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,11-21 17:39:29.946  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-21 17:39:29.946  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-21 17:39:29.946  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-21 17:39:29.946  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-21 17:39:29.946  5593  5593 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-21 17:39:29.947  5593  5641 I io.jxcore.node.ConnectionHelperTest: Starting test: testKillAllConnections
11-21 17:39:29.948  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-21 17:39:29.948  5593  5641 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionManagerStateChanged
11-21 17:39:29.949  5593  5641 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,11-21 17:39:29.950  5593  5641 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPermissionCheckRequired
11-21 17:39:29.950  5593  5641 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
11-21 17:39:29.951  5593  5641 I io.jxcore.node.ConnectionHelperTest: Starting test: testToggleBetweenSystemDecidedAndAlternativeInsecureRfcommPortNumber
11-21 17:39:29.951  5593  5641 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-21 17:39:29.951  5593  5641 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-21 17:39:29.951  5593  5641 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-21 17:39:29.951  5593  5641 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-21 17:39:29.951  5593  5641 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-21 17:39:29.951  5593  5641 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-21 17:39:29.951  5593  5641 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-21 17:39:29.952  5593  5641 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-21 17:39:29.952  5593  5641 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,11-21 17:39:29.952  5593  5641 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-21 17:39:29.952  5593  5641 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-21 17:39:29.952  5593  5641 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-21 17:39:29.953  5593  5641 I io.jxcore.node.ConnectionHelperTest: Starting test: testConnect
11-21 17:39:29.953  5593  5641 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-21 17:39:29.953  5593  5641 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,11-21 17:39:29.953  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,11-21 17:39:29.957  5593  5641 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-21 17:39:29.957  5593  5641 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
11-21 17:39:29.957  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,11-21 17:39:29.957  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-21 17:39:29.957  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-21 17:39:29.957  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-21 17:39:29.957  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-21 17:39:29.957  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-21 17:39:29.957  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-21 17:39:29.958  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-21 17:39:29.958  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-21 17:39:29.958  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-21 17:39:29.958  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-21 17:39:29.958  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-21 17:39:29.958  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-21 17:39:29.958  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,11-21 17:39:29.958  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-21 17:39:29.958  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-21 17:39:29.958  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-21 17:39:29.958  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-21 17:39:29.958  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-21 17:39:29.958  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-21 17:39:29.958  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-21 17:39:29.958  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-21 17:39:29.958  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-21 17:39:29.959  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-21 17:39:29.959  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-21 17:39:29.959  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,11-21 17:39:29.959  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-21 17:39:29.959  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-21 17:39:29.959  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-21 17:39:29.959  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-21 17:39:29.959  5593  5641 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
11-21 17:39:29.959  5593  5641 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-21 17:39:29.961  5593  5641 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
11-21 17:39:29.961  5593  5641 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-21 17:39:29.961  5593  5641 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-21 17:39:29.961  5593  5641 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
11-21 17:39:29.961  5593  5641 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-21 17:39:29.961  5593  5641 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-21 17:39:29.961  5593  5641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,11-21 17:39:29.966  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,11-21 17:39:29.966  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port 1
,11-21 17:39:29.967  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
11-21 17:39:29.968  5593  5641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
11-21 17:39:29.969  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
11-21 17:39:29.969  5593  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 130)
11-21 17:39:29.969  5593  5641 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
11-21 17:39:29.969  5593  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
11-21 17:39:29.969  5593  5641 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-21 17:39:29.969  5593  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
,11-21 17:39:29.969  5593  5641 E io.jxcore.node.ConnectionHelper: connect: Callback is null
11-21 17:39:29.970  5593  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: given port
11-21 17:39:29.970  5593  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: createBluetoothSocketToServiceRecord: Socket created with channel/port 1
11-21 17:39:29.970  5593  5673 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
11-21 17:39:29.970  5593  5673 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-21 17:39:29.971  5593  5641 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnProvideBluetoothMacAddressRequest
,11-21 17:39:29.969  4805  4805 W Binder_3: type=1400 audit(0.0:117): avc: denied { ioctl } for path="socket:[28549]" dev="sockfs" ino=28549 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-21 17:39:29.972  5593  5641 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
11-21 17:39:29.974  5593  5641 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnDiscoveryManagerStateChanged
11-21 17:39:29.974  5593  5641 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
11-21 17:39:29.975  5593  5641 I io.jxcore.node.ConnectionHelperTest: Starting test: testDisconnectOutgoingConnection
11-21 17:39:29.975  5593  5641 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
11-21 17:39:29.975  5593  5641 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
11-21 17:39:29.975  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-21 17:39:29.975  5593  5641 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
,11-21 17:39:29.975  5593  5641 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-21 17:39:29.969  4805  4805 W Binder_3: type=1400 audit(0.0:118): avc: denied { ioctl } for path="socket:[28549]" dev="sockfs" ino=28549 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-21 17:39:29.976  5593  5641 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
11-21 17:39:29.976  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-21 17:39:29.976  5593  5641 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
11-21 17:39:29.976  5593  5641 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-21 17:39:29.982  4607  4607 W Binder_1: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[31587]" dev="sockfs" ino=31587 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-21 17:39:29.982  4607  4607 W Binder_1: type=1400 audit(0.0:120): avc: denied { ioctl } for path="socket:[31587]" dev="sockfs" ino=31587 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-21 17:39:29.976  5593  5641 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
11-21 17:39:29.976  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-21 17:39:29.976  5593  5641 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
11-21 17:39:29.977  5593  5641 I io.jxcore.node.ConnectionHelperTest: Starting test: testDispose
11-21 17:39:29.977  5593  5641 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-21 17:39:29.977  5593  5641 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-21 17:39:29.977  5593  5641 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
11-21 17:39:29.977  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
11-21 17:39:29.978  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:29.978  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:29.978  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:29.978  5593  5641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-21 17:39:29.978  5593  5641 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-21 17:39:29.978  5593  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-21 17:39:29.978  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-21 17:39:29.979  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-21 17:39:29.979  5593  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-21 17:39:29.979  5593  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-21 17:39:29.979  5593  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-21 17:39:29.980  5593  5641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-21 17:39:29.980  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-21 17:39:29.980  5593  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-21 17:39:29.980  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-21 17:39:29.980  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-21 17:39:29.980  5593  5593 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-21 17:39:29.982  5593  5674 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-21 17:39:29.983  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-21 17:39:29.983  5593  5641 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-21 17:39:29.983  5593  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-21 17:39:29.985  5593  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-21 17:39:29.986  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:29.986  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-21 17:39:29.987  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-21 17:39:29.987  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-21 17:39:29.987  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 4
11-21 17:39:29.989  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:29.989  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:29.989  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-21 17:39:29.989  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-21 17:39:29.989  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-21 17:39:29.989  5593  5641 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 60 83 34 25 D7 D4
11-21 17:39:29.989  5593  5641 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 17:39:29.989  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 17:39:29.989  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:29.989  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-21 17:39:29.989  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 17:39:29.989  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:29.990  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:29.990  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:29.990  5593  5641 D BluetoothAdapter: STATE_ON
11-21 17:39:29.992  4596  4806 D BtGatt.GattService: registerClient() - UUID=c143d9f7-57e6-460f-a7f1-27c0040c77c5
11-21 17:39:29.993  4596  4658 D BtGatt.GattService: onClientRegistered() - UUID=c143d9f7-57e6-460f-a7f1-27c0040c77c5, clientIf=5
11-21 17:39:29.993  5593  5604 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-21 17:39:29.994  4596  4660 D BtGatt.AdvertiseManager: message : 0
11-21 17:39:29.996  4596  4660 D BtGatt.AdvertiseManager: starting multi advertising
,11-21 17:39:30.007  4596  4658 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-21 17:39:30.013  4596  4658 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-21 17:39:30.013  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:30.014  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:30.014  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-21 17:39:30.014  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:30.014  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:30.014  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-58,5,main], id: 58
,11-21 17:39:30.014  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:30.014  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:30.014  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-21 17:39:30.015  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-21 17:39:30.015  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
,11-21 17:39:30.017  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
,11-21 17:39:30.017  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:30.017  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:30.017  5593  5641 I io.jxcore.node.ConnectionHelper: start: OK
11-21 17:39:30.017  5593  5593 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-21 17:39:30.017  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-21 17:39:30.017  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-21 17:39:30.017  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-21 17:39:30.018  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-21 17:39:30.018  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-21 17:39:30.018  5593  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,11-21 17:39:30.018  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-21 17:39:30.018  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-21 17:39:30.018  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-21 17:39:30.018  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-21 17:39:30.018  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-21 17:39:30.018  5593  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-21 17:39:30.018  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-21 17:39:30.020  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-21 17:39:30.020  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-21 17:39:30.020  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-21 17:39:30.020  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-21 17:39:30.021  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-21 17:39:30.021  5593  5593 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-21 17:39:30.236   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-21 17:39:30.518  5593  5641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-21 17:39:30.518  5593  5641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,11-21 17:39:30.518  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,11-21 17:39:30.518  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-21 17:39:30.519  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-21 17:39:30.519  5593  5674 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-21 17:39:30.519  5593  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-21 17:39:30.519  5593  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-21 17:39:30.519  5593  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,11-21 17:39:30.519  5593  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-21 17:39:30.520  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-21 17:39:30.520  5593  5593 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,11-21 17:39:30.520  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
11-21 17:39:30.520  5593  5593 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-21 17:39:30.520  5593  5593 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-21 17:39:30.520  5593  5593 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,11-21 17:39:30.522  5593  5641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8553cb6 removed from the list
11-21 17:39:30.522  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-21 17:39:30.522  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-21 17:39:30.522  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,11-21 17:39:30.522  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-21 17:39:30.523  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:30.523  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:30.523  5593  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 130
,11-21 17:39:30.523  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:30.524  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:30.524  5593  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close
11-21 17:39:30.524  5593  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 130)
,11-21 17:39:30.525  4596  4792 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 7, channel: 1
11-21 17:39:30.525  5593  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 130)
11-21 17:39:30.525  5593  5673 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, read failed, socket might closed or timeout, read ret: -1
11-21 17:39:30.525  5593  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
11-21 17:39:30.526  5593  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 130)
,11-21 17:39:30.526  5593  5641 D BluetoothAdapter: STATE_ON
11-21 17:39:30.526  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-21 17:39:30.528  5593  5641 D BluetoothAdapter: STATE_ON
11-21 17:39:30.528  5593  5641 D BluetoothLeScanner: could not find callback wrapper
11-21 17:39:30.528  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,11-21 17:39:30.529  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:30.529  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:30.529  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:30.529  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-21 17:39:30.529  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-58,5,main], id: 58
,11-21 17:39:30.531  4596  4660 D BtGatt.AdvertiseManager: message : 1
11-21 17:39:30.532  4596  4660 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-21 17:39:30.544  4596  4658 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-21 17:39:30.544  4596  4658 D BtGatt.GattService: Client app is not null!
,11-21 17:39:30.545  4596  4609 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-21 17:39:30.545  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-21 17:39:30.546  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:30.546  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-21 17:39:30.546  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:30.546  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:30.546  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:30.546  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,11-21 17:39:30.547  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-21 17:39:30.548  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-21 17:39:30.548  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:30.549  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
,11-21 17:39:30.550  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-21 17:39:30.550  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:30.550  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:30.550  5593  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f8e7db7 removed from the list
11-21 17:39:30.550  5593  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-21 17:39:30.550  5593  5641 D io.jxcore.node.ConnectivityMonitor: stop
11-21 17:39:30.550  5593  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-21 17:39:30.550  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-21 17:39:30.551  5593  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-21 17:39:30.551  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-21 17:39:30.551  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-21 17:39:30.551  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-21 17:39:30.551  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-21 17:39:30.551  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-21 17:39:30.551  5593  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-21 17:39:30.551  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-21 17:39:30.553  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-21 17:39:30.554  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-21 17:39:30.554  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-21 17:39:30.554  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-21 17:39:30.554  5593  5593 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-21 17:39:31.055  5593  5593 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-21 17:39:35.101  4596  4790 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,11-21 17:39:35.101  4596  4790 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 7
,11-21 17:39:35.555  5593  5641 I io.jxcore.node.ConnectionHelperTest: Starting test: testIsRunning
,11-21 17:39:35.559  5593  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,11-21 17:39:35.560  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-21 17:39:35.560  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-21 17:39:35.568  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-21 17:39:35.569  5593  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,11-21 17:39:35.569  5593  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-21 17:39:35.569  5593  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,11-21 17:39:35.569  5593  5641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,11-21 17:39:35.569  5593  5641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-21 17:39:35.570  5593  5593 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-21 17:39:35.570  5593  5676 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-21 17:39:35.571  5593  5641 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionFailed
,11-21 17:39:35.572  5593  5676 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-21 17:39:35.573  5593  5641 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
11-21 17:39:35.573  5593  5641 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-21 17:39:35.573  5593  5641 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,11-21 17:39:35.574  5593  5641 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-21 17:39:35.574  5593  5641 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-21 17:39:35.575  5593  5641 I io.jxcore.node.ConnectionHelperTest: Starting test: testGetConnectivityMonitorGetDiscoveryManagerGetConnectionModelGetBluetoothName
,11-21 17:39:35.579  4806  4806 W Binder_4: type=1400 audit(0.0:121): avc: denied { ioctl } for path="socket:[33835]" dev="sockfs" ino=33835 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-21 17:39:35.581  5593  5676 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-21 17:39:35.579  4806  4806 W Binder_4: type=1400 audit(0.0:122): avc: denied { ioctl } for path="socket:[33835]" dev="sockfs" ino=33835 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-21 17:39:35.583  5593  5641 I io.jxcore.node.ConnectionHelperTest: Starting test: testConstructor
11-21 17:39:35.583  5593  5641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-21 17:39:35.584  5593  5641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-21 17:39:35.584  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-21 17:39:35.584  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-21 17:39:35.584  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-21 17:39:35.584  5593  5676 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-21 17:39:35.584  5593  5676 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,11-21 17:39:35.585  5593  5676 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-21 17:39:35.585  5593  5593 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,11-21 17:39:35.586  5593  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-21 17:39:35.586  5593  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-21 17:39:35.587  5593  5641 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8553cb6 not in the list
11-21 17:39:35.587  5593  5593 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-21 17:39:35.588  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-21 17:39:35.588  5593  5593 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-21 17:39:35.588  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-21 17:39:35.588  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-21 17:39:35.588  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-21 17:39:35.588  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:35.591  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:35.591  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-21 17:39:35.591  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:35.591  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
,11-21 17:39:35.591  5593  5641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f8e7db7 not in the list
11-21 17:39:35.591  5593  5641 D io.jxcore.node.ConnectivityMonitor: stop
11-21 17:39:35.591  5593  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-21 17:39:35.591  5593  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-21 17:39:35.591  5593  5593 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-21 17:39:35.592  5593  5641 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentOutgoingConnections
11-21 17:39:35.593  5593  5641 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,11-21 17:39:35.593  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-21 17:39:35.593  5593  5641 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
,11-21 17:39:35.593  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-21 17:39:35.593  5593  5641 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
11-21 17:39:35.593  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-21 17:39:35.594  5593  5641 I io.jxcore.node.ConnectionModelTest: Starting test: constructorTest
11-21 17:39:35.595  5593  5641 I io.jxcore.node.ConnectionModelTest: Starting test: testHasIncomingConnection
11-21 17:39:35.596  5593  5641 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentConnections
11-21 17:39:35.597  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-21 17:39:35.597  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,11-21 17:39:35.597  5593  5641 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentIncomingConnections
11-21 17:39:35.598  5593  5641 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
11-21 17:39:35.598  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-21 17:39:35.598  5593  5641 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
11-21 17:39:35.598  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-21 17:39:35.598  5593  5641 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
11-21 17:39:35.598  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
11-21 17:39:35.598  5593  5641 I io.jxcore.node.ConnectionModelTest: Starting test: testGetOutgoingConnectionCallbackByBluetoothMacAddress
,11-21 17:39:35.599  5593  5641 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
11-21 17:39:35.599  5593  5641 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
11-21 17:39:35.599  5593  5641 I io.jxcore.node.ConnectionModelTest: Starting test: testHasConnection
11-21 17:39:35.599  5593  5641 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
11-21 17:39:35.599  5593  5641 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
11-21 17:39:35.599  5593  5641 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
11-21 17:39:35.599  5593  5641 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
11-21 17:39:35.600  5593  5641 I io.jxcore.node.ConnectionModelTest: Starting test: testHasOutgoingConnection
11-21 17:39:35.601  5593  5641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-21 17:39:35.601  5593  5641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@561e2fd added. We now have 3 listener(s)
11-21 17:39:35.602  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-21 17:39:35.602  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-21 17:39:35.602  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-21 17:39:35.603  5593  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-21 17:39:35.603  5593  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a84ebf2 added. We now have 3 listener(s)
11-21 17:39:35.604  5593  5641 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-21 17:39:35.604  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-21 17:39:35.607  5593  5641 D BluetoothAdapter: enable(): BT is already enabled..!
11-21 17:39:35.608   930  3833 D WifiService: setWifiEnabled: true pid=5593, uid=10077
11-21 17:39:35.608   930  3833 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-21 17:39:35.610  5593  5641 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBleMultipleAdvertisementSupported
,11-21 17:39:35.612  5593  5641 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothSupported
11-21 17:39:35.613  5593  5641 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiDirectSupported
11-21 17:39:35.614  5593  5641 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothEnabled
11-21 17:39:35.619  5593  5641 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-21 17:39:35.619  5593  5641 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-21 17:39:35.619  5593  5641 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-21 17:39:35.619  5593  5641 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-21 17:39:35.619  5593  5641 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-21 17:39:35.619  5593  5641 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-21 17:39:35.619  5593  5641 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-21 17:39:35.619  5593  5641 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-21 17:39:35.619  5593  5641 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-21 17:39:35.619  4596  4654 D BluetoothAdapterState: Current state: ON, message: 23
11-21 17:39:35.619  4596  4654 D BluetoothAdapterProperties: Setting state to 13
11-21 17:39:35.619  4596  4654 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-21 17:39:35.620  5593  5641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-21 17:39:35.620  4596  4654 D BluetoothAdapterProperties: onBluetoothDisable()
11-21 17:39:35.620  5593  5641 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-21 17:39:35.620  4596  4654 I BluetoothAdapterState: Entering PendingCommandState
,11-21 17:39:35.622  4596  4658 D BluetoothAdapterProperties: Scan Mode:20
,11-21 17:39:35.622  4596  4654 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,11-21 17:39:35.623  4596  4596 D BluetoothMapService: onReceive
11-21 17:39:35.623  4596  4596 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,11-21 17:39:35.623  4596  4596 D BluetoothMapService: STATE_TURNING_OFF
11-21 17:39:35.624  4596  4596 D BluetoothMapService: MAP Service closeService in
11-21 17:39:35.624  4596  4596 D BluetoothMapMasInstance0: MAP Service shutdown
11-21 17:39:35.624  4596  4596 D ObexServerSockets0: shutdown(block = true)
11-21 17:39:35.624  4596  4596 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-21 17:39:35.624  4596  4808 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
11-21 17:39:35.625  4596  4596 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-21 17:39:35.625  4596  4809 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-21 17:39:35.625  4596  4792 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-21 17:39:35.627  4596  4596 I BtOppRfcommListener: stopping Accept Thread
11-21 17:39:35.628  4596  5286 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-21 17:39:35.628  4596  5286 I BtOppRfcommListener: BluetoothSocket listen thread finished
,11-21 17:39:35.639   930   943 I ActivityManager: Start proc 5679:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,11-21 17:39:35.641  4596  4596 D HeadsetService: Received stop request...Stopping profile...
,11-21 17:39:35.642   930   930 D BluetoothHeadset: Proxy object disconnected
11-21 17:39:35.642   930   930 D BluetoothHeadset: Proxy object disconnected
11-21 17:39:35.643  3101  3122 D BluetoothHeadset: Proxy object disconnected
,11-21 17:39:35.643   930   930 D BluetoothHeadset: Proxy object disconnected
,11-21 17:39:35.644  3752  3767 D BluetoothHeadset: Proxy object disconnected
11-21 17:39:35.644  3101  3101 D HeadsetProfile: Bluetooth service disconnected
11-21 17:39:35.647  4596  4596 D A2dpService: Received stop request...Stopping profile...
11-21 17:39:35.647  4596  4796 D A2dpStateMachine: Exit Disconnected: -1
11-21 17:39:35.648   930   930 D BluetoothA2dp: Proxy object disconnected
,11-21 17:39:35.649  3101  3101 D BluetoothA2dp: Proxy object disconnected
11-21 17:39:35.649  4596  4596 V BluetoothAdapterState: isTurningOff()=true
11-21 17:39:35.649  4596  4596 V BluetoothAdapterState: isTurningOn()=false
11-21 17:39:35.649  4596  4596 V BluetoothAdapterState: isBleTurningOn()=false
11-21 17:39:35.649  4596  4596 V BluetoothAdapterState: isBleTurningOff()=false
,11-21 17:39:35.650  4596  4596 D HidService: Received stop request...Stopping profile...
11-21 17:39:35.650  4596  4596 D HidService: Stopping Bluetooth HidService
11-21 17:39:35.651  3101  3101 D BluetoothInputDevice: Proxy object disconnected
11-21 17:39:35.651  3101  3101 D HidProfile: Bluetooth service disconnected
,11-21 17:39:35.654  4596  4596 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-21 17:39:35.654  4596  4596 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-21 17:39:35.654  4596  4658 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-21 17:39:35.655  4596  4790 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-21 17:39:35.655  4596  4790 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-21 17:39:35.655  4596  4790 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-21 17:39:35.655  4596  4658 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,11-21 17:39:35.655  4596  4596 D HealthService: Received stop request...Stopping profile...
11-21 17:39:35.658  4596  4596 D PanService: Received stop request...Stopping profile...
11-21 17:39:35.659  3101  3101 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-21 17:39:35.659  3101  3101 D PanProfile: Bluetooth service disconnected
,11-21 17:39:35.659  4596  4596 V BluetoothAdapterState: isTurningOff()=true
,11-21 17:39:35.659  4596  4596 V BluetoothAdapterState: isTurningOn()=false
,11-21 17:39:35.659  4596  4596 V BluetoothAdapterState: isBleTurningOn()=false
11-21 17:39:35.659  4596  4596 V BluetoothAdapterState: isBleTurningOff()=false
11-21 17:39:35.660  4596  4596 D BluetoothMapService: Received stop request...Stopping profile...
11-21 17:39:35.660  4596  4596 D BluetoothMapService: stop()
11-21 17:39:35.660  4596  4596 D BluetoothMapAppObserver: deinitObservers()
,11-21 17:39:35.661  4596  4596 D BluetoothMapAppObserver: removeReceiver()
11-21 17:39:35.662  3101  3101 D BluetoothMap: Proxy object disconnected
11-21 17:39:35.662  3101  3101 D MapProfile: Bluetooth service disconnected
11-21 17:39:35.662  4596  4596 D SapService: Received stop request...Stopping profile...
11-21 17:39:35.662  4596  4596 V SapService: stop()
11-21 17:39:35.665  4596  4790 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-21 17:39:35.665  4596  4790 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-21 17:39:35.665  4596  4596 V BluetoothAdapterState: isTurningOff()=true
11-21 17:39:35.665  4596  4596 V BluetoothAdapterState: isTurningOn()=false
11-21 17:39:35.665  4596  4596 V BluetoothAdapterState: isBleTurningOn()=false
11-21 17:39:35.665  4596  4658 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-21 17:39:35.665  4596  4596 V BluetoothAdapterState: isBleTurningOff()=false
11-21 17:39:35.666  4596  4790 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,11-21 17:39:35.666  4596  4790 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,11-21 17:39:35.666  4596  4596 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-21 17:39:35.666  4596  4790 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,11-21 17:39:35.666  4596  4596 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-21 17:39:35.666  4596  4790 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,11-21 17:39:35.666  4596  4658 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-21 17:39:35.666  4596  4596 V BluetoothAdapterState: isTurningOff()=true
11-21 17:39:35.666  4596  4596 V BluetoothAdapterState: isTurningOn()=false
11-21 17:39:35.666  4596  4596 V BluetoothAdapterState: isBleTurningOn()=false
11-21 17:39:35.666  4596  4596 V BluetoothAdapterState: isBleTurningOff()=false
11-21 17:39:35.666  4596  4596 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-21 17:39:35.667  4596  4658 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-21 17:39:35.667  4596  4596 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-21 17:39:35.668  4596  4596 V BluetoothAdapterState: isTurningOff()=true
11-21 17:39:35.668  4596  4596 V BluetoothAdapterState: isTurningOn()=false
11-21 17:39:35.668  4596  4596 V BluetoothAdapterState: isBleTurningOn()=false
11-21 17:39:35.668  4596  4596 V BluetoothAdapterState: isBleTurningOff()=false
11-21 17:39:35.668  4596  4596 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-21 17:39:35.668  4596  4596 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-21 17:39:35.670  4596  4596 D BluetoothMapService: MAP Service closeService in
,11-21 17:39:35.670  4596  4596 V BluetoothAdapterState: isTurningOff()=true
11-21 17:39:35.670  4596  4596 V BluetoothAdapterState: isTurningOn()=false
11-21 17:39:35.670  4596  4596 V BluetoothAdapterState: isBleTurningOn()=false
11-21 17:39:35.670  4596  4596 V BluetoothAdapterState: isBleTurningOff()=false
11-21 17:39:35.671  4596  4596 D BluetoothMapService: cleanup()
11-21 17:39:35.671  4596  4596 D BluetoothMapService: MAP Service closeService in
11-21 17:39:35.671  4596  4596 V BluetoothAdapterState: isTurningOff()=true
11-21 17:39:35.671  4596  4596 V BluetoothAdapterState: isTurningOn()=false
11-21 17:39:35.671  4596  4596 V BluetoothAdapterState: isBleTurningOn()=false
11-21 17:39:35.671  4596  4596 V BluetoothAdapterState: isBleTurningOff()=false
11-21 17:39:35.672  4596  4654 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-21 17:39:35.672  4596  4654 D BluetoothAdapterProperties: Setting state to 15
11-21 17:39:35.672  4596  4654 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-21 17:39:35.674  4596  4654 I BluetoothAdapterState: Entering BleOnState
,11-21 17:39:35.674  3101  3328 D BluetoothA2dp: onBluetoothStateChange: up=false
11-21 17:39:35.675  3101  3117 D BluetoothHeadset: onBluetoothStateChange: up=false
11-21 17:39:35.676  3752  3978 D BluetoothHeadset: onBluetoothStateChange: up=false
11-21 17:39:35.676  3101  3122 D BluetoothMap: onBluetoothStateChange: up=false
,11-21 17:39:35.676   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
11-21 17:39:35.677   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
11-21 17:39:35.677  3101  3328 D BluetoothPan: onBluetoothStateChange on: false
,11-21 17:39:35.680  3101  3117 D BluetoothInputDevice: onBluetoothStateChange: up=false
,11-21 17:39:35.681   930   947 D BluetoothA2dp: onBluetoothStateChange: up=false
11-21 17:39:35.681   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
11-21 17:39:35.681  3101  3122 D BluetoothPbap: onBluetoothStateChange: up=false
11-21 17:39:35.682  4596  4654 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-21 17:39:35.682  4596  4654 D BluetoothAdapterProperties: Setting state to 16
11-21 17:39:35.682  4596  4654 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-21 17:39:35.683  4596  4654 D BluetoothAdapterProperties: onBleDisable
11-21 17:39:35.683  4596  4654 I BluetoothAdapterState: Entering PendingCommandState
,11-21 17:39:35.683  4596  4655 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-21 17:39:35.684  4596  4658 D BluetoothAdapterProperties: Scan Mode:20
11-21 17:39:35.685  4596  4790 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-21 17:39:35.685  4596  4790 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-21 17:39:35.697  5679  5679 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,11-21 17:39:35.710  5679  5679 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-21 17:39:35.715   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5287c58:true
,11-21 17:39:35.723  3544  3544 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-21 17:39:35.734  5679  5679 D LocalBluetoothProfileManager: Adding local MAP profile
,11-21 17:39:35.736  5679  5679 D BluetoothMap: Create BluetoothMap proxy object
,11-21 17:39:35.743  5679  5679 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,11-21 17:39:35.750  5679  5679 D DockEventReceiver: finishStartingService: stopping service
,11-21 17:39:35.753  5679  5679 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-21 17:39:35.759  3544  3544 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-21 17:39:35.759  5679  5679 D DockEventReceiver: finishStartingService: stopping service
,11-21 17:39:35.761   930  3521 I ActivityManager: Killing 5358:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,11-21 17:39:35.895  4596  4658 I bt_hci  : shut_down
,11-21 17:39:35.899  4596  4662 D bt_hwcfg: hw_epilog_process
11-21 17:39:35.900  4596  4662 I bt_vendor: low_power_mode_cb
,11-21 17:39:35.903  4596  4662 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
11-21 17:39:35.903  4596  4662 I bt_vendor: epilog_cb
11-21 17:39:35.903  4596  4662 I bt_hci  : epilog_finished_callback
11-21 17:39:35.906  4596  4658 I bt_hci_h4: hal_close
,11-21 17:39:35.907  4596  4658 I bt_userial_vendor: device fd = 54 close
,11-21 17:39:36.018  4596  4655 D bt_stack_manager: event_shut_down_stack finished.
,11-21 17:39:36.019  4596  4654 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-21 17:39:36.025  4596  4654 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,11-21 17:39:36.026  4596  4596 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-21 17:39:36.028  4596  4596 D BtGatt.GattService: Received stop request...Stopping profile...
,11-21 17:39:36.028  4596  4596 D BtGatt.GattService: stop()
11-21 17:39:36.028  4596  4596 D BtGatt.AdvertiseManager: advertise clients cleared
11-21 17:39:36.033  4596  4596 V BluetoothAdapterState: isTurningOff()=false
,11-21 17:39:36.033  4596  4596 V BluetoothAdapterState: isTurningOn()=false
11-21 17:39:36.033  4596  4596 V BluetoothAdapterState: isBleTurningOn()=false
,11-21 17:39:36.033  4596  4596 V BluetoothAdapterState: isBleTurningOff()=true
,11-21 17:39:36.034  4596  4654 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,11-21 17:39:36.034  4596  4654 D BluetoothAdapterProperties: Setting state to 10
,11-21 17:39:36.035  4596  4654 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-21 17:39:36.036  4596  4654 I BluetoothAdapterState: Entering OffState
11-21 17:39:36.038   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,11-21 17:39:36.057  4596  4596 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-21 17:39:36.057  4596  4596 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-21 17:39:36.057  4596  4596 I BluetoothServiceJni: cleanupNative: return from cleanup
11-21 17:39:36.059  4596  4655 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-21 17:39:36.067  4596  4596 I art     : System.exit called, status: 0
,11-21 17:39:36.067  4596  4596 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-21 17:39:36.092  5593  5593 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-21 17:39:36.095   930  3826 I ActivityManager: Process com.android.bluetooth (pid 4596) has died
,11-21 17:39:36.121  5593  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-21 17:39:36.121  5593  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-21 17:39:36.121  5593  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-21 17:39:36.121  5593  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-21 17:39:36.121  5593  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-21 17:39:36.121  5593  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-21 17:39:36.121  5593  5677 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-21 17:39:36.121  5593  5677 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-21 17:39:36.121  5593  5677 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-21 17:39:36.121  5593  5677 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-21 17:39:36.121  5593  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-21 17:39:36.121  5593  5677 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-21 17:39:36.125  5593  5641 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-21 17:39:36.138   930   947 I ActivityManager: Start proc 5697:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-21 17:39:36.197  5697  5697 D AdapterServiceConfig: Adding HeadsetService
11-21 17:39:36.197  5697  5697 D AdapterServiceConfig: Adding A2dpService
11-21 17:39:36.197  5697  5697 D AdapterServiceConfig: Adding HidService
11-21 17:39:36.197  5697  5697 D AdapterServiceConfig: Adding HealthService
11-21 17:39:36.198  5697  5697 D AdapterServiceConfig: Adding PanService
11-21 17:39:36.198  5697  5697 D AdapterServiceConfig: Adding GattService
11-21 17:39:36.198  5697  5697 D AdapterServiceConfig: Adding BluetoothMapService
11-21 17:39:36.198  5697  5697 D AdapterServiceConfig: Adding SapService
,11-21 17:39:36.209   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e582bd2:true
,11-21 17:39:36.209  5697  5697 D BluetoothAdapterState: make() - Creating AdapterState
,11-21 17:39:36.212  5697  5697 I bt_bluedroid: init
,11-21 17:39:36.214  5697  5709 I BluetoothAdapterState: Entering OffState
,11-21 17:39:36.216  5697  5710 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-21 17:39:36.216  5697  5710 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-21 17:39:36.216  5697  5710 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-21 17:39:36.217  5697  5710 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-21 17:39:36.218  5697  5697 I bt_bluedroid: get_profile_interface socket
,11-21 17:39:36.219  5697  5713 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-21 17:39:36.219  5697  5697 I bt_bluedroid: get_profile_interface sdp
,11-21 17:39:36.220  5697  5713 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-21 17:39:36.223  5697  5708 I bt_bluedroid: config_hci_snoop_log
11-21 17:39:36.224   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-21 17:39:36.229  5697  5709 D BluetoothAdapterState: Current state: OFF, message: 0
11-21 17:39:36.229  5697  5709 D BluetoothAdapterProperties: Setting state to 14
11-21 17:39:36.229  5697  5709 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-21 17:39:36.230  5697  5709 D BluetoothBondStateMachine: make
,11-21 17:39:36.232  5697  5714 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-21 17:39:36.235  5697  5709 I BluetoothAdapterState: Entering PendingCommandState
,11-21 17:39:36.236  5697  5697 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-21 17:39:36.238  5697  5697 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c0cbca
11-21 17:39:36.239  5697  5697 D BtGatt.DebugUtils: handleDebugAction() action=null
11-21 17:39:36.239  5697  5697 D BtGatt.GattService: Received start request. Starting profile...
11-21 17:39:36.239  5697  5697 D BtGatt.GattService: start()
,11-21 17:39:36.239  5697  5697 I bt_bluedroid: get_profile_interface gatt
,11-21 17:39:36.240  5697  5697 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c0cbca
11-21 17:39:36.240  5697  5697 D BtGatt.AdvertiseManager: advertise manager created
,11-21 17:39:36.245  5697  5697 V BluetoothAdapterState: isTurningOff()=false
11-21 17:39:36.245  5697  5697 V BluetoothAdapterState: isTurningOn()=false
11-21 17:39:36.245  5697  5697 V BluetoothAdapterState: isBleTurningOn()=true
11-21 17:39:36.246  5697  5697 V BluetoothAdapterState: isBleTurningOff()=false
,11-21 17:39:36.246  5697  5709 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-21 17:39:36.247  5697  5709 I bt_bluedroid: bt_bluedroid
11-21 17:39:36.247  5697  5710 D bt_stack_manager: event_start_up_stack is bringing up the stack.
11-21 17:39:36.248  5697  5710 I bt_hci  : start_up
,11-21 17:39:36.253  5697  5710 I bt_vendor: alloc value 0xf3d48871
11-21 17:39:36.253  5697  5710 I bt_vendor: init
11-21 17:39:36.253  5697  5710 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-21 17:39:36.253  5697  5710 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-21 17:39:36.364  5697  5710 D bt_hci  : start_up starting async portion
,11-21 17:39:36.365  5697  5717 I bt_hci  : event_finish_startup
11-21 17:39:36.365  5697  5717 I bt_hci_h4: hal_open
,11-21 17:39:36.366  5697  5717 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-21 17:39:36.365  5718  5718 W irq/448-msm_hs_: type=1400 audit(0.0:123): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-21 17:39:36.386  5697  5717 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-21 17:39:36.390  5697  5717 D bt_hwcfg: Chipset BCM4358A3
,11-21 17:39:36.390  5697  5717 D bt_hwcfg: Target name = [BCM4358A3]
11-21 17:39:36.390  5697  5717 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-21 17:39:36.632  5697  5709 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,11-21 17:39:36.917  5697  5717 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-21 17:39:36.917  5697  5717 D bt_hwcfg: Settlement delay -- 100 ms
,11-21 17:39:36.917  5697  5717 I bt_hwcfg: Setting fw settlement delay to 100 
,11-21 17:39:37.043  5697  5717 I bt_hwcfg: bt vendor lib: set UART baud 3000000
11-21 17:39:37.044  5697  5717 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
,11-21 17:39:37.046  5697  5717 I bt_hwcfg: vendor lib fwcfg completed
,11-21 17:39:37.046  5697  5717 I bt_vendor: firmware callback
,11-21 17:39:37.046  5697  5717 I bt_hci  : firmware_config_callback
,11-21 17:39:37.055  5697  5720 I bt_btu  : btu_task pending for preload complete event
,11-21 17:39:37.056  5697  5720 I bt_btu_task: Bluetooth chip preload is complete
,11-21 17:39:37.056  5697  5720 I bt_btu  : btu_task received preload complete event
,11-21 17:39:37.066  5697  5720 I         : BTE_InitTraceLevels -- TRC_HCI
11-21 17:39:37.066  5697  5720 I         : BTE_InitTraceLevels -- TRC_L2CAP
,11-21 17:39:37.066  5697  5720 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-21 17:39:37.066  5697  5720 I         : BTE_InitTraceLevels -- TRC_AVDT
11-21 17:39:37.067  5697  5720 I         : BTE_InitTraceLevels -- TRC_AVRC
11-21 17:39:37.067  5697  5720 I         : BTE_InitTraceLevels -- TRC_A2D
,11-21 17:39:37.067  5697  5720 I         : BTE_InitTraceLevels -- TRC_BNEP
11-21 17:39:37.067  5697  5720 I         : BTE_InitTraceLevels -- TRC_BTM
,11-21 17:39:37.067  5697  5720 I         : BTE_InitTraceLevels -- TRC_GAP
11-21 17:39:37.067  5697  5720 I         : BTE_InitTraceLevels -- TRC_PAN
,11-21 17:39:37.067  5697  5720 I         : BTE_InitTraceLevels -- TRC_SDP
11-21 17:39:37.067  5697  5720 I         : BTE_InitTraceLevels -- TRC_GATT
,11-21 17:39:37.067  5697  5720 I         : BTE_InitTraceLevels -- TRC_SMP
11-21 17:39:37.067  5697  5720 I         : BTE_InitTraceLevels -- TRC_BTAPP
,11-21 17:39:37.067  5697  5720 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-21 17:39:37.138  5697  5709 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,11-21 17:39:37.161  5697  5720 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3cc6549
,11-21 17:39:37.162  5697  5720 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3cc6549 
,11-21 17:39:37.185  5697  5713 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-21 17:39:37.187  5697  5713 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-21 17:39:37.188  5697  5713 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-21 17:39:37.191  5697  5713 D BluetoothAdapterProperties: Name is: Nexus 6P
11-21 17:39:37.194  5697  5713 D BluetoothAdapterProperties: Scan Mode:20
11-21 17:39:37.195  5697  5713 D BluetoothAdapterProperties: Discoverable Timeout:120
11-21 17:39:37.195  5697  5713 D bt_hci  : do_postload posting postload work item
,11-21 17:39:37.195  5697  5717 I bt_hci  : event_postload
11-21 17:39:37.195  5697  5717 I bt_vendor: sco_config_cb
11-21 17:39:37.195  5697  5717 I bt_hci  : sco_config_callback postload finished.
11-21 17:39:37.199  5697  5713 D bt_bte_conf: Device ID record 1 : primary
11-21 17:39:37.199  5697  5713 D bt_bte_conf:   vendorId            = 000f
11-21 17:39:37.199  5697  5713 D bt_bte_conf:   vendorIdSource      = 0001
11-21 17:39:37.199  5697  5713 D bt_bte_conf:   product             = 1200
11-21 17:39:37.199  5697  5713 D bt_bte_conf:   version             = 1436
11-21 17:39:37.199  5697  5713 D bt_bte_conf:   clientExecutableURL = 
11-21 17:39:37.200  5697  5713 D bt_bte_conf:   serviceDescription  = 
11-21 17:39:37.200  5697  5713 D bt_bte_conf:   documentationURL    = 
,11-21 17:39:37.200  5697  5713 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-21 17:39:37.200  5697  5710 D bt_stack_manager: event_start_up_stack finished
11-21 17:39:37.201  5697  5709 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-21 17:39:37.203  5697  5709 D BluetoothAdapterProperties: Setting state to 15
11-21 17:39:37.203  5697  5709 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-21 17:39:37.204  5697  5709 I BluetoothAdapterState: Entering BleOnState
,11-21 17:39:37.207  5697  5717 I bt_vendor: low_power_mode_cb
,11-21 17:39:37.208  5697  5709 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-21 17:39:37.208  5697  5709 D BluetoothAdapterProperties: Setting state to 11
,11-21 17:39:37.208  5697  5709 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
11-21 17:39:37.213  5697  5697 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c0cbca
11-21 17:39:37.214  5697  5697 D HeadsetService: Received start request. Starting profile...
,11-21 17:39:37.222  5697  5697 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,11-21 17:39:37.223  5697  5697 D HeadsetStateMachine: make
,11-21 17:39:37.233  5697  5697 D HeadsetStateMachine: max_hf_connections = 1
,11-21 17:39:37.233  5697  5697 I bt_bluedroid: get_profile_interface handsfree
11-21 17:39:37.233  5697  5709 I BluetoothAdapterState: Entering PendingCommandState
11-21 17:39:37.233  5697  5713 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-21 17:39:37.234  5697  5713 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,11-21 17:39:37.236  5697  5697 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c0cbca
11-21 17:39:37.237  5697  5697 D A2dpService: Received start request. Starting profile...
,11-21 17:39:37.237  5697  5697 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,11-21 17:39:37.238  5697  5697 I bt_bluedroid: get_profile_interface avrcp
,11-21 17:39:37.244  5697  5697 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-21 17:39:37.244  5697  5697 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-21 17:39:37.244  5697  5697 D A2dpStateMachine: make
11-21 17:39:37.245  5697  5697 I bt_bluedroid: get_profile_interface a2dp
,11-21 17:39:37.246  5697  5713 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
11-21 17:39:37.247  5697  5729 D A2dpStateMachine: Enter Disconnected: -2
,11-21 17:39:37.247  5697  5697 I BluetoothHidServiceJni: classInitNative: succeeds
11-21 17:39:37.248  5697  5697 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c0cbca
,11-21 17:39:37.250  5697  5697 D HidService: Received start request. Starting profile...
,11-21 17:39:37.250  5697  5697 I bt_bluedroid: get_profile_interface hidhost
11-21 17:39:37.250  5679  5679 D BluetoothInputDevice: Proxy object connected
11-21 17:39:37.250  5697  5697 D HidService: setHidService(): set to: null
11-21 17:39:37.250  5697  5713 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3ca756d
11-21 17:39:37.251  5697  5713 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-21 17:39:37.251  5697  5697 I BluetoothHealthServiceJni: classInitNative: succeeds
11-21 17:39:37.251  5679  5679 D HidProfile: Bluetooth service connected
11-21 17:39:37.251  5697  5697 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c0cbca
11-21 17:39:37.252  5697  5697 D HealthService: Received start request. Starting profile...
11-21 17:39:37.253  5697  5697 I bt_bluedroid: get_profile_interface health
11-21 17:39:37.254  5697  5697 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-21 17:39:37.255  5697  5697 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c0cbca
11-21 17:39:37.255  5679  5679 D BluetoothPan: BluetoothPAN Proxy object connected
11-21 17:39:37.256  5697  5697 D PanService: Received start request. Starting profile...
11-21 17:39:37.256  5697  5697 D BluetoothPanServiceJni: initializeNative(L110): pan
11-21 17:39:37.256  5697  5697 I bt_bluedroid: get_profile_interface pan
11-21 17:39:37.256  5679  5679 D PanProfile: Bluetooth service connected
11-21 17:39:37.256  5697  5713 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
11-21 17:39:37.260  5697  5697 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c0cbca
11-21 17:39:37.261  3544  3544 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-21 17:39:37.262  5697  5697 D BluetoothMapService: Received start request. Starting profile...
11-21 17:39:37.262  5697  5697 D BluetoothMapService: start()
11-21 17:39:37.262  5679  5679 D BluetoothMap: Proxy object connected
11-21 17:39:37.264  5679  5679 D MapProfile: Bluetooth service connected
11-21 17:39:37.264  5679  5679 D BluetoothMap: getConnectedDevices()
11-21 17:39:37.264  5679  5679 D BluetoothMap: Bluetooth is Not enabled
11-21 17:39:37.266  5697  5697 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
11-21 17:39:37.267  5697  5697 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-21 17:39:37.267  5697  5697 D BluetoothMapAppObserver: createReceiver()
11-21 17:39:37.268  5697  5697 D BluetoothMapAppObserver: initObservers()
11-21 17:39:37.268  5697  5697 D BluetoothMapAppObserver: getEnabledAccountItems()
11-21 17:39:37.274  5697  5697 V SapService: SapBinder()
11-21 17:39:37.274  5697  5697 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c0cbca
11-21 17:39:37.275  5697  5697 D SapService: Received start request. Starting profile...
11-21 17:39:37.275  5697  5697 V SapService: start()
11-21 17:39:37.276  5697  5697 V BluetoothAdapterState: isTurningOff()=false
11-21 17:39:37.276  5697  5697 V BluetoothAdapterState: isTurningOn()=true
11-21 17:39:37.276  5697  5697 V BluetoothAdapterState: isBleTurningOn()=false
11-21 17:39:37.276  5697  5697 V BluetoothAdapterState: isBleTurningOff()=false
11-21 17:39:37.276  5697  5697 V BluetoothAdapterState: isTurningOff()=false
11-21 17:39:37.276  5697  5697 V BluetoothAdapterState: isTurningOn()=true
11-21 17:39:37.276  5697  5697 V BluetoothAdapterState: isBleTurningOn()=false
11-21 17:39:37.276  5697  5697 V BluetoothAdapterState: isBleTurningOff()=false
11-21 17:39:37.276  5697  5727 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-21 17:39:37.276  5697  5697 V BluetoothAdapterState: isTurningOff()=false
11-21 17:39:37.277  5697  5697 V BluetoothAdapterState: isTurningOn()=true
11-21 17:39:37.277  5697  5697 V BluetoothAdapterState: isBleTurningOn()=false
11-21 17:39:37.277  5697  5697 V BluetoothAdapterState: isBleTurningOff()=false
11-21 17:39:37.277  5697  5697 V BluetoothAdapterState: isTurningOff()=false
11-21 17:39:37.277  5697  5697 V BluetoothAdapterState: isTurningOn()=true
11-21 17:39:37.277  5697  5697 V BluetoothAdapterState: isBleTurningOn()=false
11-21 17:39:37.277  5697  5697 V BluetoothAdapterState: isBleTurningOff()=false
11-21 17:39:37.277  5697  5697 V BluetoothAdapterState: isTurningOff()=false
11-21 17:39:37.277  5697  5697 V BluetoothAdapterState: isTurningOn()=true
11-21 17:39:37.277  5697  5697 V BluetoothAdapterState: isBleTurningOn()=false
11-21 17:39:37.277  5697  5697 V BluetoothAdapterState: isBleTurningOff()=false
11-21 17:39:37.278  5697  5697 V BluetoothAdapterState: isTurningOff()=false
11-21 17:39:37.278  5697  5697 V BluetoothAdapterState: isTurningOn()=true
11-21 17:39:37.278  5697  5697 V BluetoothAdapterState: isBleTurningOn()=false
11-21 17:39:37.278  5697  5697 V BluetoothAdapterState: isBleTurningOff()=false
11-21 17:39:37.278  5697  5697 V BluetoothAdapterState: isTurningOff()=false
11-21 17:39:37.278  5697  5697 V BluetoothAdapterState: isTurningOn()=true
11-21 17:39:37.278  5697  5697 V BluetoothAdapterState: isBleTurningOn()=false
11-21 17:39:37.278  5697  5697 V BluetoothAdapterState: isBleTurningOff()=false
11-21 17:39:37.279  5697  5709 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-21 17:39:37.279  5697  5709 D BluetoothAdapterProperties: ScanMode =  20
11-21 17:39:37.279  5697  5709 D BluetoothAdapterProperties: State =  11
11-21 17:39:37.279  5697  5709 D BluetoothAdapterProperties: Setting state to 12
11-21 17:39:37.279  5697  5709 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-21 17:39:37.280  3101  3117 D BluetoothA2dp: onBluetoothStateChange: up=true
11-21 17:39:37.281  5697  5713 D BluetoothAdapterProperties: Scan Mode:21
11-21 17:39:37.281  5697  5713 D BluetoothAdapterProperties: Discoverable Timeout:120
11-21 17:39:37.282  5697  5709 I BluetoothAdapterState: Entering OnState
11-21 17:39:37.283  3101  3328 D BluetoothHeadset: onBluetoothStateChange: up=true
11-21 17:39:37.283  3101  3101 D BluetoothA2dp: Proxy object connected
11-21 17:39:37.283  3752  3978 D BluetoothHeadset: onBluetoothStateChange: up=true
11-21 17:39:37.284  5679  5689 D BluetoothPbap: onBluetoothStateChange: up=true
11-21 17:39:37.285  3101  3122 D BluetoothMap: onBluetoothStateChange: up=true
11-21 17:39:37.286   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
11-21 17:39:37.286  3101  3101 D BluetoothMap: Proxy object connected
11-21 17:39:37.286  3101  3101 D MapProfile: Bluetooth service connected
11-21 17:39:37.286   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
11-21 17:39:37.286  3101  3101 D BluetoothMap: getConnectedDevices()
11-21 17:39:37.286  3101  3117 D BluetoothPan: onBluetoothStateChange on: true
11-21 17:39:37.288  3101  3101 D BluetoothPan: BluetoothPAN Proxy object connected
11-21 17:39:37.288  3101  3101 D PanProfile: Bluetooth service connected
,11-21 17:39:37.288  3101  3122 D BluetoothInputDevice: onBluetoothStateChange: up=true
,11-21 17:39:37.290  3101  3101 D BluetoothInputDevice: Proxy object connected
,11-21 17:39:37.290  3101  3101 D HidProfile: Bluetooth service connected
11-21 17:39:37.290  5679  5690 D BluetoothPan: onBluetoothStateChange on: true
11-21 17:39:37.290   930   947 D BluetoothA2dp: onBluetoothStateChange: up=true
,11-21 17:39:37.291   930   930 D BluetoothA2dp: Proxy object connected
11-21 17:39:37.291  5679  5689 D BluetoothInputDevice: onBluetoothStateChange: up=true
,11-21 17:39:37.293   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-21 17:39:37.293  5679  5690 D BluetoothMap: onBluetoothStateChange: up=true
11-21 17:39:37.294  5697  5697 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-21 17:39:37.294  3101  3117 D BluetoothPbap: onBluetoothStateChange: up=true
11-21 17:39:37.294  5697  5697 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-21 17:39:37.295  5697  5697 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-21 17:39:37.296   930   930 I Telecom : BluetoothPhoneService: queryPhoneState
,11-21 17:39:37.298  5697  5697 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-21 17:39:37.299  5679  5679 D LocalBluetoothProfileManager: Adding local A2DP profile
,11-21 17:39:37.300  5697  5697 D ObexServerSockets: Succeed to create listening sockets 
11-21 17:39:37.300  5697  5697 D ObexServerSockets0: startAccept()
11-21 17:39:37.300  5697  5697 D ObexServerSockets0: prepareForNewConnect()
11-21 17:39:37.302  5697  5697 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-21 17:39:37.302  5697  5697 D BluetoothSdpJni: SDP Create record success - handle: 0
11-21 17:39:37.302  5697  5735 D ObexServerSockets0: Accepting socket connection...
11-21 17:39:37.302  5697  5697 D BluetoothMapService: onReceive
11-21 17:39:37.302  5697  5697 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-21 17:39:37.302  5697  5697 D BluetoothMapService: STATE_ON
11-21 17:39:37.303  5697  5736 D ObexServerSockets0: Accepting socket connection...
11-21 17:39:37.303  5679  5679 D LocalBluetoothProfileManager: Adding local HEADSET profile
11-21 17:39:37.304  5697  5737 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-21 17:39:37.306  5697  5737 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-21 17:39:37.306  5697  5737 D BluetoothSdpJni: SDP Create record success - handle: 1
11-21 17:39:37.309  5679  5679 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-21 17:39:37.311  5679  5679 D BluetoothA2dp: Proxy object connected
,11-21 17:39:37.316  3544  3544 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-21 17:39:37.320  5679  5679 D DockEventReceiver: finishStartingService: stopping service
11-21 17:39:37.322  3101  3101 D BluetoothPbap: Proxy object connected
11-21 17:39:37.322  5679  5679 D BluetoothPbap: Proxy object connected
11-21 17:39:37.322  3101  3101 D PbapServerProfile: Bluetooth service connected
11-21 17:39:37.322  5679  5679 D PbapServerProfile: Bluetooth service connected
,11-21 17:39:37.328  5697  5697 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-21 17:39:37.328  5697  5697 D ObexServerSockets0: prepareForNewConnect()
11-21 17:39:37.329  5697  5741 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-21 17:39:37.342  5697  5745 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-21 17:39:37.343  5697  5745 I BtOppRfcommListener: Accept thread started.
,11-21 17:39:37.385   930   930 D BluetoothHeadset: Proxy object connected
11-21 17:39:37.385   930   930 D BluetoothHeadset: Proxy object connected
11-21 17:39:37.385  3101  3117 D BluetoothHeadset: Proxy object connected
11-21 17:39:37.386  3101  3101 D HeadsetProfile: Bluetooth service connected
,11-21 17:39:37.386   930   930 D BluetoothHeadset: Proxy object connected
11-21 17:39:37.386   930   947 D BluetoothHeadset: Proxy object connected
11-21 17:39:37.386  3752  3768 D BluetoothHeadset: Proxy object connected
,11-21 17:39:37.387   930   947 D BluetoothHeadset: Proxy object connected
,11-21 17:39:37.393   930   947 D BluetoothHeadset: Proxy object connected
,11-21 17:39:37.405  5679  5690 D BluetoothHeadset: Proxy object connected
,11-21 17:39:37.407  5679  5679 D HeadsetProfile: Bluetooth service connected
,11-21 17:39:37.650  5593  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-21 17:39:37.650  5593  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-21 17:39:37.650  5593  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-21 17:39:37.650  5593  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-21 17:39:37.650  5593  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-21 17:39:37.650  5593  5677 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-21 17:39:37.650  5593  5677 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-21 17:39:37.650  5593  5677 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-21 17:39:37.650  5593  5677 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-21 17:39:37.655  5593  5677 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-21 17:39:37.659  5593  5641 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiEnabled
11-21 17:39:37.662   930  3833 D WifiService: setWifiEnabled: false pid=5593, uid=10077
11-21 17:39:37.662   930  3833 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-21 17:39:37.667   930  2982 D WifiStateMachine: WifiStateMachine: Leaving Connected state
11-21 17:39:37.668   930  2982 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-21 17:39:37.668   930  2982 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-21 17:39:37.668   930  2982 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-21 17:39:37.674  5593  5641 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-21 17:39:37.689   930  5332 D DhcpClient: Clearing IP address
,11-21 17:39:37.689   509   924 D CommandListener: Clearing all IP addresses on wlan0
,11-21 17:39:37.697   509   924 D CommandListener: Setting iface cfg
,11-21 17:39:37.704   930  5333 D DhcpClient: Receive thread stopped
,11-21 17:39:37.706  3544  5383 V NativeCrypto: Read error: ssl=0x7f67c4b380: I/O error during system call, Connection timed out
,11-21 17:39:37.709  3544  5383 V NativeCrypto: SSL shutdown failed: ssl=0x7f67c4b380: I/O error during system call, Broken pipe
,11-21 17:39:37.712   930  3187 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
,11-21 17:39:37.712   930  5330 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
,11-21 17:39:37.714   930  2986 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,11-21 17:39:37.714   930  2986 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
11-21 17:39:37.717   930  5330 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
11-21 17:39:37.718   535   535 E Parcel  : Reading a NULL string not supported here.
11-21 17:39:37.723   930   930 D RttService: SCAN_AVAILABLE : 1
11-21 17:39:37.723   930  3036 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,11-21 17:39:37.726   930  2986 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
11-21 17:39:37.728  3721  3843 W QCNEJ   : |CORE| network lost: 100
11-21 17:39:37.729  3721  3843 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,11-21 17:39:37.752   930  2982 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,11-21 17:39:37.754   509   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-21 17:39:37.767   930  2982 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-21 17:39:37.778   509   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-21 17:39:37.778   509   924 D CommandListener: Clearing all IP addresses on wlan0
,11-21 17:39:37.779   930  2986 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
11-21 17:39:37.780   930  2986 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-21 17:39:37.782   930   947 D Tethering: MasterInitialState.processMessage what=3
,11-21 17:39:37.784  5242  5242 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@bfed8e and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,11-21 17:39:37.784   930  2982 D DhcpClient: doQuit
11-21 17:39:37.785   930  2982 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-21 17:39:37.786   930  5332 D DhcpClient: onQuitting
11-21 17:39:37.786  3434  3434 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-21 17:39:37.795  3946  3946 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
11-21 17:39:37.796  4933  4948 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-21 17:39:37.796  4933  4948 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
,11-21 17:39:37.796  4933  4948 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
11-21 17:39:37.796  4933  4948 E SarControlService: no key has been found,reset the power
11-21 17:39:37.796  4933  4973 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-21 17:39:37.796  4933  4973 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-21 17:39:37.797  4933  4973 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-21 17:39:37.797  4959  4959 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,11-21 17:39:37.797  4959  4959 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-21 17:39:37.800  3920  3920 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-21 17:39:37.802  4933  4973 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-21 17:39:37.802  4933  4973 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-21 17:39:37.803  4933  4973 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-21 17:39:37.803  4959  4959 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-21 17:39:37.803  4959  4959 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,11-21 17:39:37.805  3434  3434 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-21 17:39:37.808  4959  4975 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@da0d164 HexData = [00000000ea03000000000000ffffffff]
,11-21 17:39:37.808  4959  4975 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-21 17:39:37.808  4959  4975 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
11-21 17:39:37.808  4959  4959 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-21 17:39:37.808  4933  4943 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-21 17:39:37.810  3920  3920 D SystemUpdateService: onCreate
11-21 17:39:37.812  3434  3434 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
11-21 17:39:37.814  3920  3920 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
11-21 17:39:37.815  4959  4975 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@da0d164 HexData = [00000000eb03000000000000ffffffff]
11-21 17:39:37.815  4959  4975 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-21 17:39:37.815  4959  4975 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
11-21 17:39:37.816  4959  4959 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-21 17:39:37.816  4933  4944 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-21 17:39:37.820  3920  5755 I SystemUpdateService: active receiver: enabled
,11-21 17:39:37.824  3920  3920 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-21 17:39:37.829  3920  5356 I iu.UploadsManager: num queued entries: 0
,11-21 17:39:37.832  3920  3920 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
11-21 17:39:37.833  3920  3920 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-21 17:39:37.834  3920  5755 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-21 17:39:37.835  3920  5356 I iu.UploadsManager: num updated entries: 0
11-21 17:39:37.836  3920  5356 I iu.SyncManager: NEXT; no task
,11-21 17:39:37.838  3920  5755 I SystemUpdateService: network: null; metered: false; mobile allowed: true
11-21 17:39:37.839  3920  5755 I SystemUpdateService: now status is 0 (complete)
11-21 17:39:37.839  3920  5755 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-21 17:39:37.839  3920  5755 I SystemUpdateService: file has been verified
11-21 17:39:37.839  3920  5755 I SystemUpdateService: OTA package size = 21989297
,11-21 17:39:37.844   509   924 E Netd    : netlink response contains error (No such file or directory)
,11-21 17:39:37.845   930  2986 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
11-21 17:39:37.845  3920  5755 I SystemUpdateService: showing system update notification
11-21 17:39:37.845   930  2986 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-21 17:39:37.849  3434  3434 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-21 17:39:37.849   930  3824 I ActivityManager: Start proc 5758:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,11-21 17:39:37.857  3434  3434 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
11-21 17:39:37.859   930   930 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-21 17:39:37.860  3920  3920 D SystemUpdateService: onDestroy
,11-21 17:39:37.879  5758  5758 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,11-21 17:39:37.882  5758  5758 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-21 17:39:37.889  5758  5758 D SprintDMHelper: simOperator: 
11-21 17:39:37.889  5758  5758 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-21 17:39:37.900  4348  5770 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,11-21 17:39:37.904   930  3521 I ActivityManager: Killing 5242:com.google.android.music:main/u0a59 (adj 15): empty #17
,11-21 17:39:37.933   930   941 I ActivityManager: Start proc 5771:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,11-21 17:39:37.958  5771  5771 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,11-21 17:39:37.961   930  2982 D wifi    : In wifi stop Hal
,11-21 17:39:37.961  4348  4348 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-21 17:39:37.961   930  2982 D wifi    : halHandle = 0x7f65e2a400, mVM = 0x7f8240d140, mCls = 0x100a02
11-21 17:39:37.962   930  3433 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-21 17:39:37.962   930  3433 D WifiHAL : Got a signal to exit!!!
,11-21 17:39:37.962   930  3433 I WifiHAL : Exit wifi_event_loop
11-21 17:39:37.962   930  2982 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-21 17:39:37.963   930  2982 E WifiHAL : Event processing terminated
11-21 17:39:37.963   930  2982 D wifi    : In wifi cleaned up handler
,11-21 17:39:37.963   930  2982 I WifiHAL : Internal cleanup completed
11-21 17:39:37.963  4082  4197 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-21 17:39:37.967   930  3187 I ActivityManager: Killing 5429:com.android.defcontainer/u0a7 (adj 15): empty #17
,11-21 17:39:37.983   930  3433 D wifi    : set interface wlan0 flags (DOWN)
11-21 17:39:37.983   930  2982 D WifiNative-HAL: HAL event thread stopped successfully
,11-21 17:39:38.049   509   924 E Netd    : netlink response contains error (No such file or directory)
,11-21 17:39:38.178  5593  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-21 17:39:38.178  5593  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-21 17:39:38.178  5593  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-21 17:39:38.178  5593  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-21 17:39:38.178  5593  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-21 17:39:38.178  5593  5677 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-21 17:39:38.178  5593  5677 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-21 17:39:38.178  5593  5677 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-21 17:39:38.178  5593  5677 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-21 17:39:38.185  5593  5677 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-21 17:39:38.189   930   947 D Tethering: InitialState.processMessage what=4
,11-21 17:39:38.190   930  3091 D WifiService: setWifiEnabled: true pid=5593, uid=10077
11-21 17:39:38.190   930  3091 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-21 17:39:38.191  5593  5641 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-21 17:39:38.193   509   924 D SoftapController: Softap fwReload - Ok
,11-21 17:39:38.194   930   947 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-21 17:39:38.196   509   924 D CommandListener: Setting iface cfg
11-21 17:39:38.196   509   924 D CommandListener: Trying to bring down wlan0
,11-21 17:39:38.197   509   924 D CommandListener: Clearing all IP addresses on wlan0
,11-21 17:39:38.200   930  2982 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-21 17:39:38.693   930  3824 D WifiService: setWifiEnabled: true pid=5593, uid=10077
,11-21 17:39:38.700   930  3824 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-21 17:39:38.810   930  2982 D wifi    : set interface wlan0 flags (UP)
,11-21 17:39:38.810   930  2982 I WifiHAL : Initializing wifi
11-21 17:39:38.811   930  2982 I WifiHAL : Creating socket
,11-21 17:39:38.819   930  2982 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-21 17:39:38.819   930   947 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-21 17:39:38.819   930  2982 D wifi    : Did set static halHandle = 0x7f65e2a400
,11-21 17:39:38.822   930  2982 D wifi    : halHandle = 0x7f65e2a400, mVM = 0x7f8240d140, mCls = 0x201432
,11-21 17:39:38.822   930  2982 D wifi    : array field set
,11-21 17:39:38.822   930  2982 I WifiNative-HAL: interface[0] = wlan0
11-21 17:39:38.825   930  5794 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547170198528
,11-21 17:39:38.825   930  5794 D wifi    : waitForHalEvents called, vm = 0x7f8240d140, obj = 0x201432, env = 0x7f674d3280
,11-21 17:39:38.903  5795  5795 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-21 17:39:38.925   930  2982 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-21 17:39:38.965  5795  5795 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-21 17:39:38.975  5795  5795 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-21 17:39:38.975  5795  5795 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-21 17:39:38.984   930  2982 D WifiConfigStore: Loading config and enabling all networks 
,11-21 17:39:38.996   930  2982 D WifiConfigStore: loaded 0 passpoint configs
,11-21 17:39:38.997   930  2982 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
11-21 17:39:38.997   930  2982 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,11-21 17:39:38.998   930  2982 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
11-21 17:39:38.998   930  2982 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
,11-21 17:39:38.998   930  2982 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
11-21 17:39:38.998   930  2982 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,11-21 17:39:38.999   930  2982 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
,11-21 17:39:38.999   930  2982 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-21 17:39:38.999   930  2982 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
11-21 17:39:38.999   930  2982 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-21 17:39:38.999   930  2982 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
,11-21 17:39:38.999   930  2982 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-21 17:39:39.000   930  2982 D WifiNative-HAL: Setting external_sim to 1
,11-21 17:39:39.001   930  2982 D wifi    : setting dfs flag to true, 0x7f6b842000
11-21 17:39:39.001   930  2982 D WifiStateMachine: Setting OUI to DA-A1-19
11-21 17:39:39.001   930  2982 D wifi    : setting scan oui 0x7f6b842000
11-21 17:39:39.001   930  2982 D WifiHAL : Sending mac address OUI
,11-21 17:39:39.001  4348  4348 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-21 17:39:39.004   930  2982 E native  : do suspend false
,11-21 17:39:39.010   930  2982 D wifi    : android_net_wifi_setLinkLayerStats: 1
,11-21 17:39:39.010   930   930 D RttService: SCAN_AVAILABLE : 3
,11-21 17:39:39.010   930  3036 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,11-21 17:39:39.013   509   924 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,11-21 17:39:39.015   509   924 D CommandListener: Setting iface cfg
,11-21 17:39:39.016   930  2975 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '124 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 124 Failed to set address (No such device)'
,11-21 17:39:39.017   930  2975 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-21 17:39:39.022   930  2975 D WifiNative-HAL: p2pGetDeviceAddress
,11-21 17:39:39.022   930  2975 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-21 17:39:39.028   930   945 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=178301 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=13 mControllerEnergyUsed=49 }
,11-21 17:39:39.208  5593  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-21 17:39:39.208  5593  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-21 17:39:39.208  5593  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-21 17:39:39.208  5593  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-21 17:39:39.208  5593  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-21 17:39:39.208  5593  5677 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-21 17:39:39.208  5593  5677 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-21 17:39:39.208  5593  5677 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-21 17:39:39.208  5593  5677 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-21 17:39:39.211  5593  5677 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-21 17:39:39.214  5593  5641 D BluetoothAdapter: enable(): BT is already enabled..!
,11-21 17:39:39.215   930  3187 D WifiService: setWifiEnabled: true pid=5593, uid=10077
,11-21 17:39:39.215   930  3187 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-21 17:39:39.217  5593  5641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-21 17:39:39.217  5593  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-21 17:39:39.217  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-21 17:39:39.218  5593  5641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@561e2fd removed from the list
11-21 17:39:39.218  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-21 17:39:39.218  5593  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a84ebf2 removed from the list
11-21 17:39:39.218  5593  5641 D io.jxcore.node.ConnectivityMonitor: stop
11-21 17:39:39.222  5593  5641 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testSetTcpPortNumber
,11-21 17:39:39.224  5593  5641 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetTcpPortNumber
,11-21 17:39:39.226  5593  5641 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetLocalHostPort
,11-21 17:39:39.228  5593  5641 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testConstructor
,11-21 17:39:39.230  5593  5641 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityCreated
11-21 17:39:39.231  5593  5641 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
11-21 17:39:39.232  5593  5641 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityResumed
,11-21 17:39:39.232  5593  5641 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
11-21 17:39:39.232  5593  5641 I io.jxcore.node.LifeCycleMonitorTest: Starting test: constructor
11-21 17:39:39.235  5593  5641 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivitySaveInstanceState
,11-21 17:39:39.235  5593  5641 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@9e95b1 Bundle[{}]
11-21 17:39:39.236  5593  5641 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testStartStop
11-21 17:39:39.236  5593  5641 I io.jxcore.node.LifeCycleMonitor: start: OK
11-21 17:39:39.236  5593  5641 I io.jxcore.node.LifeCycleMonitor: stop: OK
,11-21 17:39:39.237  5593  5641 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStarted
11-21 17:39:39.237  5593  5641 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
11-21 17:39:39.238  5593  5641 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStopped
,11-21 17:39:39.238  5593  5641 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
11-21 17:39:39.239  5593  5641 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityDestroyed
11-21 17:39:39.241  5593  5641 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
11-21 17:39:39.242  5593  5641 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityPaused
,11-21 17:39:39.244  5593  5641 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,11-21 17:39:39.246  5593  5641 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToString
,11-21 17:39:39.247  5593  5641 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToJsonObject
,11-21 17:39:39.248  5593  5641 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testConstructorWithParameters
11-21 17:39:39.248  5593  5641 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testSetListeningOnPortNumber
11-21 17:39:39.249  5593  5641 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testGetListeningOnPortNumber
11-21 17:39:39.249  5593  5641 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testDefaultConstructor
,11-21 17:39:39.251  5593  5641 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testClose
,11-21 17:39:39.252  5593  5641 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testNoAvailablePorts
,11-21 17:39:40.254   930  2982 D WifiStateMachine: Disconnected CMD_START_SCAN source -2 10, 11 -> obsolete
,11-21 17:39:40.257  5593  5641 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testGetListeningOnPortNumber
,11-21 17:39:40.259  5593  5641 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testConstructor
,11-21 17:39:40.262  5593  5641 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetListener
,11-21 17:39:40.264  5593  5641 I io.jxcore.node.SocketThreadBaseTest: Starting test: testSetPeerProperties
,11-21 17:39:40.265  5593  5641 I io.jxcore.node.SocketThreadBaseTest: Starting test: testClose
,11-21 17:39:40.266  5593  5641 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 173)
,11-21 17:39:40.267  5593  5641 I io.jxcore.node.SocketThreadBaseTest: Starting test: testCloseLocalSocketAndStreams
11-21 17:39:40.268  5593  5641 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,11-21 17:39:40.268  5593  5641 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 174)
,11-21 17:39:40.270  5593  5641 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetPeerProperties
,11-21 17:39:40.271  5593  5641 I io.jxcore.node.SocketThreadBaseTest: Starting test: testEquals
,11-21 17:39:40.273  5593  5641 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetLocalHostAddressAsString
11-21 17:39:40.274  5593  5641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-21 17:39:40.274  5593  5641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d7470c0 added. We now have 3 listener(s)
,11-21 17:39:40.276  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-21 17:39:40.276  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-21 17:39:40.276  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-21 17:39:40.277  5593  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-21 17:39:40.277  5593  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@96eb1f9 added. We now have 3 listener(s)
11-21 17:39:40.277  5593  5641 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-21 17:39:40.277  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-21 17:39:40.282  5593  5641 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCancelCurrentOperation
,11-21 17:39:40.283  5593  5641 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStopOperation
11-21 17:39:40.283  5593  5641 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
11-21 17:39:40.283  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
11-21 17:39:40.283  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:40.283  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:40.283  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:40.284  5593  5641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,11-21 17:39:40.284  5593  5641 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-21 17:39:40.284  5593  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-21 17:39:40.284  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-21 17:39:40.284  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-21 17:39:40.287  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-21 17:39:40.287  5593  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-21 17:39:40.288  5593  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-21 17:39:40.288  5593  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-21 17:39:40.288  5593  5641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,11-21 17:39:40.288  5593  5593 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-21 17:39:40.288  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-21 17:39:40.288  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-21 17:39:40.288  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-21 17:39:40.290  5593  5808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-21 17:39:40.291  5593  5808 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-21 17:39:40.292  5708  5708 W Binder_2: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[33971]" dev="sockfs" ino=33971 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-21 17:39:40.292  5708  5708 W Binder_2: type=1400 audit(0.0:125): avc: denied { ioctl } for path="socket:[33971]" dev="sockfs" ino=33971 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-21 17:39:40.294  5593  5808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,11-21 17:39:40.295  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-21 17:39:40.295  5593  5641 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-21 17:39:40.295  5593  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-21 17:39:40.299  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-58,5,main], id: 58
,11-21 17:39:40.299  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-21 17:39:40.299  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-21 17:39:40.300  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-21 17:39:40.300  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 5
,11-21 17:39:40.302  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-58,5,main], id: 58
,11-21 17:39:40.302  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:40.303  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-21 17:39:40.303  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-21 17:39:40.303  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-21 17:39:40.303  5593  5641 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 60 83 34 25 D7 D4
11-21 17:39:40.303  5593  5641 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 17:39:40.303  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 17:39:40.303  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:40.303  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
,11-21 17:39:40.303  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 17:39:40.303  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:40.303  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:40.304  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:40.304  5593  5641 D BluetoothAdapter: STATE_ON
11-21 17:39:40.307  5697  5734 D BtGatt.GattService: registerClient() - UUID=cfed87e9-55ea-40be-9525-7b2447e1e640
,11-21 17:39:40.308  5697  5713 D BtGatt.GattService: onClientRegistered() - UUID=cfed87e9-55ea-40be-9525-7b2447e1e640, clientIf=5
,11-21 17:39:40.309  5593  5603 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-21 17:39:40.311  5697  5715 D BtGatt.AdvertiseManager: message : 0
,11-21 17:39:40.314  5697  5715 D BtGatt.AdvertiseManager: starting multi advertising
,11-21 17:39:40.325  5697  5713 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-21 17:39:40.331  5697  5713 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-21 17:39:40.332  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-58,5,main], id: 58
,11-21 17:39:40.332  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:40.332  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-21 17:39:40.332  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:40.332  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:40.332  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:40.332  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-58,5,main], id: 58
,11-21 17:39:40.332  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:40.332  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-21 17:39:40.334  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-21 17:39:40.335  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
,11-21 17:39:40.336  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
,11-21 17:39:40.336  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:40.336  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:40.336  5593  5593 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-21 17:39:40.337  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-21 17:39:40.337  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
,11-21 17:39:40.337  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-21 17:39:40.337  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-21 17:39:40.337  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
,11-21 17:39:40.337  5593  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,11-21 17:39:40.337  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-21 17:39:40.337  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-21 17:39:40.337  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-21 17:39:40.337  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-21 17:39:40.337  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-21 17:39:40.337  5593  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,11-21 17:39:40.337  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-21 17:39:40.340  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-21 17:39:40.340  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-21 17:39:40.340  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-21 17:39:40.341  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-21 17:39:40.341  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-21 17:39:40.341  5593  5593 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-21 17:39:40.842  5593  5593 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,11-21 17:39:40.842  5593  5593 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-21 17:39:40.842  5593  5593 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-21 17:39:42.068  5795  5795 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-21 17:39:42.073  5795  5795 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-21 17:39:42.079  5795  5795 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-21 17:39:42.124   930  2982 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
11-21 17:39:42.126   930  2982 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-21 17:39:42.126   930  2982 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-21 17:39:42.138   930  2982 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-21 17:39:42.167   930  2982 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-21 17:39:42.173  5795  5795 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-21 17:39:42.597  5795  5795 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-21 17:39:42.631  5795  5795 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-21 17:39:42.632  5795  5795 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-21 17:39:42.646   930  2982 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-21 17:39:42.647   930  2982 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-21 17:39:42.647   930  2986 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-21 17:39:42.661   930  2982 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-21 17:39:42.674   509   924 D CommandListener: Setting iface cfg
,11-21 17:39:42.679   930  2982 D WifiStateMachine: Start Dhcp Watchdog 2
,11-21 17:39:42.685   930  5813 D DhcpClient: Receive thread started
,11-21 17:39:42.688   930  2986 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-21 17:39:42.688   930  2982 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
11-21 17:39:42.688   930  2986 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,11-21 17:39:42.769   930  2982 E native  : do suspend false
,11-21 17:39:42.778   930  5812 D DhcpClient: Broadcasting DHCPDISCOVER
,11-21 17:39:42.794   930  5813 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.109, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172657, domain null
,11-21 17:39:42.795   930  5812 D DhcpClient: Got pending lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172657 seconds
,11-21 17:39:42.797   930  5812 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.109 serverid=192.168.1.1
,11-21 17:39:42.814   930  5813 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.109, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-21 17:39:42.815   930  5812 D DhcpClient: Confirmed lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-21 17:39:42.818   509   924 D CommandListener: Setting iface cfg
,11-21 17:39:42.822   930  2982 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-21 17:39:42.829   930  5812 D DhcpClient: Scheduling renewal in 86399s
,11-21 17:39:42.838   930  2982 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-21 17:39:42.840   930  2982 D WifiConfigStore: No blacklist allowed without epno enabled
,11-21 17:39:42.842   930  2986 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,11-21 17:39:42.853   930  2982 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-21 17:39:42.854   930  2986 D ConnectivityService: Adding iface wlan0 to network 101
,11-21 17:39:42.898   930  2986 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-21 17:39:42.898   930  2986 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,11-21 17:39:42.900   930  2986 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,11-21 17:39:42.902   930  2986 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,11-21 17:39:42.903   930  2986 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,11-21 17:39:42.909   930  2986 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-21 17:39:42.913   930  2986 D ConnectivityService: scheduleUnvalidatedPrompt 101
,11-21 17:39:42.914   930  2986 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
11-21 17:39:42.914   930  2986 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
11-21 17:39:42.914   930  2982 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-21 17:39:42.914   930  2986 D ConnectivityService:    accepting network in place of null
11-21 17:39:42.914   930  2982 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-21 17:39:42.914   930  2986 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -51]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-21 17:39:42.931   930  5811 D NetlinkSocketObserver: NeighborEvent{elapsedMs=182204, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-21 17:39:42.936   509   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-21 17:39:42.957   509   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-21 17:39:42.961   930  2986 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
11-21 17:39:42.961   930  2986 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-21 17:39:42.961  3721  3843 W QCNEJ   : |CORE| network available: 101
11-21 17:39:42.962   930  2986 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
11-21 17:39:42.964  3721  3843 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-21 17:39:42.965   930   947 D Tethering: MasterInitialState.processMessage what=3
11-21 17:39:42.965  3721  3843 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-21 17:39:42.966  3721  3843 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-21 17:39:42.975  4933  4948 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,11-21 17:39:42.975  4933  4948 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-21 17:39:42.976  4933  4948 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
11-21 17:39:42.976  4933  4948 E SarControlService: no key has been found,reset the power
11-21 17:39:42.976  4933  4973 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-21 17:39:42.976  4933  4973 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-21 17:39:42.976  4933  4973 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-21 17:39:42.977  4959  4959 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-21 17:39:42.977  4959  4959 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-21 17:39:42.978  4933  4973 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-21 17:39:42.978  4933  4973 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
,11-21 17:39:42.978  4933  4973 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-21 17:39:42.979  4959  4959 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-21 17:39:42.979  4959  4959 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,11-21 17:39:42.982  3946  3946 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,11-21 17:39:42.983  4959  4975 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@da0d164 HexData = [00000000ec03000000000000ffffffff]
,11-21 17:39:42.984  4959  4975 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-21 17:39:42.984  4959  4975 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
11-21 17:39:42.984  4959  4959 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-21 17:39:42.984  4933  4943 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,11-21 17:39:42.987  3920  3920 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-21 17:39:42.990  3920  3920 D SystemUpdateService: onCreate
11-21 17:39:42.994  3920  3920 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
11-21 17:39:42.995  4959  4975 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@da0d164 HexData = [00000000ed03000000000000ffffffff]
11-21 17:39:42.996  4959  4975 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-21 17:39:42.996  4959  4975 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
11-21 17:39:42.996  4959  4959 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,11-21 17:39:42.996  4933  4944 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-21 17:39:43.003   930  5810 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,11-21 17:39:43.007  3920  3920 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-21 17:39:43.015  3920  5356 I iu.UploadsManager: num queued entries: 0
11-21 17:39:43.015  3920  5356 I iu.UploadsManager: num updated entries: 0
11-21 17:39:43.016  3920  5356 I iu.SyncManager: NEXT; no task
,11-21 17:39:43.027  3920  3920 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
11-21 17:39:43.029  3920  3920 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
11-21 17:39:43.030  5758  5758 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
11-21 17:39:43.034  5758  5758 D SprintDMHelper: simOperator: 
11-21 17:39:43.034  5758  5758 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-21 17:39:43.044  3920  5823 I SystemUpdateService: active receiver: enabled
,11-21 17:39:43.054   930  5810 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 21 Nov 2016 16:39:43 GMT], X-Android-Received-Millis=[1479746383053], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1479746383028]}
,11-21 17:39:43.054   930  2986 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-21 17:39:43.054   930  2986 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,11-21 17:39:43.054   930  2986 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
11-21 17:39:43.055   930  2986 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-21 17:39:43.077  3920  5823 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-21 17:39:43.080  3920  5823 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-21 17:39:43.080  3920  5823 I SystemUpdateService: now status is 0 (complete)
11-21 17:39:43.081  3920  5823 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-21 17:39:43.081  3920  5823 I SystemUpdateService: file has been verified
11-21 17:39:43.081  3920  5823 I SystemUpdateService: OTA package size = 21989297
,11-21 17:39:43.088  3920  5823 I SystemUpdateService: showing system update notification
,11-21 17:39:43.099   930   930 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-21 17:39:43.100  3920  3920 D SystemUpdateService: onDestroy
,11-21 17:39:43.145  4348  5828 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,11-21 17:39:43.341  5593  5641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,11-21 17:39:43.341  5593  5641 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-21 17:39:43.341  5593  5641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-21 17:39:43.341  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-21 17:39:43.341  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-21 17:39:43.342  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-21 17:39:43.342  5593  5808 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-21 17:39:43.342  5593  5808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-21 17:39:43.342  5593  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,11-21 17:39:43.342  5593  5808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-21 17:39:43.342  5593  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-21 17:39:43.342  5593  5593 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-21 17:39:43.342  5593  5641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-21 17:39:43.342  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-21 17:39:43.342  5593  5593 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-21 17:39:43.342  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-21 17:39:43.342  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-21 17:39:43.342  5593  5593 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-21 17:39:43.343  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:43.343  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-58,5,main], id: 58
,11-21 17:39:43.343  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:43.343  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-58,5,main], id: 58
,11-21 17:39:43.349  5593  5641 D BluetoothAdapter: STATE_ON
,11-21 17:39:43.350  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-21 17:39:43.352  5593  5641 D BluetoothAdapter: STATE_ON
11-21 17:39:43.353  5593  5641 D BluetoothLeScanner: could not find callback wrapper
,11-21 17:39:43.353  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-21 17:39:43.353  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:43.354  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:43.354  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:43.354  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-21 17:39:43.354  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:43.356  5697  5715 D BtGatt.AdvertiseManager: message : 1
11-21 17:39:43.357  5697  5715 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-21 17:39:43.369  5697  5713 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,11-21 17:39:43.369  5697  5713 D BtGatt.GattService: Client app is not null!
,11-21 17:39:43.370  5697  5708 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-21 17:39:43.371  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-21 17:39:43.372  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:43.372  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-21 17:39:43.372  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:43.373  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:43.373  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:43.373  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-21 17:39:43.373  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-21 17:39:43.374  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-21 17:39:43.375  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:43.376  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:43.377  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-21 17:39:43.377  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:43.377  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:43.377  5593  5593 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-21 17:39:43.377  5593  5593 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-21 17:39:43.378  5593  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-21 17:39:43.378  5593  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-21 17:39:43.378  5593  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
,11-21 17:39:43.378  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-21 17:39:43.378  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-21 17:39:43.378  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
,11-21 17:39:43.378  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-21 17:39:43.378  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-21 17:39:43.378  5593  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-21 17:39:43.378  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-21 17:39:43.380  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-21 17:39:43.380  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,11-21 17:39:43.381  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-21 17:39:43.381  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-21 17:39:43.381  5593  5593 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-21 17:39:43.384  5593  5641 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCheckCurrentOperationStatus
,11-21 17:39:43.384  5593  5641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-21 17:39:43.385  5593  5641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-21 17:39:43.385  5593  5641 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-21 17:39:43.385  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-21 17:39:43.385  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-21 17:39:43.385  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-21 17:39:43.387  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-21 17:39:43.391  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-21 17:39:43.391  5593  5641 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-21 17:39:43.391  5593  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-21 17:39:43.395  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-58,5,main], id: 58
,11-21 17:39:43.395  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-21 17:39:43.396  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-21 17:39:43.396  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-21 17:39:43.396  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 5
,11-21 17:39:43.400  5593  5641 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,11-21 17:39:43.403  5593  5641 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
11-21 17:39:43.403  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:43.403  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...,
11-21 17:39:43.403  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-21 17:39:43.404  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-21 17:39:43.404  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-21 17:39:43.404  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-58,5,main], id: 58
,11-21 17:39:43.405  5593  5641 D BluetoothAdapter: STATE_ON
11-21 17:39:43.408  5697  5725 D BtGatt.GattService: registerClient() - UUID=22ff776b-46a3-4e23-9203-a7b4aafcaf6c
,11-21 17:39:43.409  5697  5713 D BtGatt.GattService: onClientRegistered() - UUID=22ff776b-46a3-4e23-9203-a7b4aafcaf6c, clientIf=5
,11-21 17:39:43.409  5593  5637 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-21 17:39:43.410  5697  5707 D BtGatt.GattService: start scan with filters
,11-21 17:39:43.414  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-21 17:39:43.414  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:43.414  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-21 17:39:43.414  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:43.415  5697  5716 D BtGatt.ScanManager: handling starting scan
11-21 17:39:43.415  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-21 17:39:43.415  5593  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-21 17:39:43.415  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-21 17:39:43.415  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-21 17:39:43.415  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-21 17:39:43.415  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-21 17:39:43.415  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-21 17:39:43.415  5593  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,11-21 17:39:43.416  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,11-21 17:39:43.416  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:43.417  5697  5716 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c0cbca
11-21 17:39:43.419  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:43.419  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-21 17:39:43.419  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:43.419  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:43.419  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-21 17:39:43.421  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-21 17:39:43.421  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-21 17:39:43.421  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-21 17:39:43.421  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-21 17:39:43.422  5593  5593 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-21 17:39:43.423  5697  5713 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-21 17:39:43.423  5697  5713 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-21 17:39:43.424  5697  5716 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-21 17:39:43.429  5697  5713 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-21 17:39:43.429  5697  5713 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-21 17:39:43.429  5697  5716 D BtGatt.ScanManager: Starting BLE batch scan
11-21 17:39:43.430  5697  5716 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-21 17:39:43.438  5697  5713 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-21 17:39:43.438  5697  5713 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-21 17:39:43.443  5697  5713 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-21 17:39:43.444  5697  5713 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-21 17:39:43.923  5593  5593 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-21 17:39:43.923  5593  5593 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-21 17:39:43.923  5593  5593 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-21 17:39:43.963   930  2986 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,11-21 17:39:44.648   930  2982 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{4}, ntable=[192.168.1.1/NUD_REACHABLE]
,11-21 17:39:44.662   930  2986 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-21 17:39:44.668  3721  3843 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [192.168.1.109/24,fe80::6283:34ff:fe25:d770/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
,11-21 17:39:44.669  3721  3843 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [192.168.1.109/24,fe80::6283:34ff:fe25:d770/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-21 17:39:45.706   930  2986 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-21 17:39:46.421  5593  5641 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStartOperation
11-21 17:39:46.422  5593  5641 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 6
11-21 17:39:46.422  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 5 -> 6
11-21 17:39:46.423  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:46.423  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-58,5,main], id: 58
,11-21 17:39:46.423  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:46.424  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
11-21 17:39:46.424  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
11-21 17:39:46.424  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
11-21 17:39:46.424  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 6
11-21 17:39:46.424  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
11-21 17:39:46.424  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
11-21 17:39:46.424  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
11-21 17:39:46.424  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
11-21 17:39:46.424  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
11-21 17:39:46.424  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:46.424  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 6
,11-21 17:39:46.424  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: advertiserWasStarted false Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:46.424  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:46.424  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-21 17:39:46.425  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-21 17:39:46.427  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: scannerWasStarted true Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:46.427  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: stop scanner Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:46.428  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:46.430  5593  5641 D BluetoothAdapter: STATE_ON
11-21 17:39:46.431  5697  5707 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-21 17:39:46.431  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-21 17:39:46.433  5697  5716 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-21 17:39:46.433  5593  5641 D BluetoothAdapter: STATE_ON
11-21 17:39:46.435  5697  5726 D BtGatt.GattService: stopScan() - queue size =1
11-21 17:39:46.437  5697  5734 D BtGatt.GattService: unregisterClient() - clientIf=5
11-21 17:39:46.438  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-21 17:39:46.438  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:46.438  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-21 17:39:46.438  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:46.438  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-21 17:39:46.438  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start scanner Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:46.438  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:46.439  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-21 17:39:46.439  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,11-21 17:39:46.439  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
,11-21 17:39:46.439  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-21 17:39:46.439  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:46.441  5697  5697 D BtGatt.ScanManager: awakened up at time 185714
11-21 17:39:46.442  5593  5641 D BluetoothAdapter: STATE_ON
11-21 17:39:46.447  5697  5708 D BtGatt.GattService: registerClient() - UUID=d5cc02ea-c6a5-49a1-b339-6f71dc8fceed
,11-21 17:39:46.449  5697  5713 D BtGatt.GattService: onClientRegistered() - UUID=d5cc02ea-c6a5-49a1-b339-6f71dc8fceed, clientIf=5
,11-21 17:39:46.450  5593  5637 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-21 17:39:46.450  5697  5707 D BtGatt.GattService: start scan with filters
11-21 17:39:46.453  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-21 17:39:46.453  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
,11-21 17:39:46.453  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-21 17:39:46.454  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:46.454  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start scanner started = true Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:46.454  5593  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-21 17:39:46.454  5593  5641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-21 17:39:46.454  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-21 17:39:46.454  5593  5641 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-21 17:39:46.454  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-21 17:39:46.454  5593  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-21 17:39:46.454  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-21 17:39:46.454  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-21 17:39:46.454  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-21 17:39:46.454  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-21 17:39:46.455  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-21 17:39:46.456  5593  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-21 17:39:46.456  5697  5713 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
11-21 17:39:46.456  5697  5713 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-21 17:39:46.456  5593  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,11-21 17:39:46.456  5593  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-21 17:39:46.456  5697  5713 D BtGatt.GattService: current time is 185729712000
,11-21 17:39:46.455  5726  5726 W Binder_4: type=1400 audit(0.0:126): avc: denied { ioctl } for path="socket:[35889]" dev="sockfs" ino=35889 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-21 17:39:46.457  5593  5836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,11-21 17:39:46.457  5593  5836 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-21 17:39:46.457  5697  5713 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -80, 41, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -91, 39, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -82, 36, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0, 35, 97, 126, -92, 22, -56, 1, -128, -83, 34, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0]
11-21 17:39:46.458  5593  5641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-21 17:39:46.458  5593  5593 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-21 17:39:46.458  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
11-21 17:39:46.459  5593  5836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-21 17:39:46.455  5726  5726 W Binder_4: type=1400 audit(0.0:127): avc: denied { ioctl } for path="socket:[35889]" dev="sockfs" ino=35889 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-21 17:39:46.460  5697  5713 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,11-21 17:39:46.462  5697  5713 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-21 17:39:46.462  5697  5713 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
11-21 17:39:46.462  5697  5713 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
11-21 17:39:46.463  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-21 17:39:46.463  5593  5641 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-21 17:39:46.467  5697  5713 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-21 17:39:46.467  5697  5713 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-21 17:39:46.467  5697  5716 D BtGatt.ScanManager: stopping BLe Batch
11-21 17:39:46.468  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser : Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:46.468  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:46.468  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:46.468  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-21 17:39:46.468  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-21 17:39:46.468  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-21 17:39:46.468  5593  5641 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 06 60 83 34 25 D7 D4
11-21 17:39:46.468  5593  5641 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 17:39:46.468  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 17:39:46.468  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:46.468  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-21 17:39:46.469  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 17:39:46.469  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:46.469  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:46.469  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:46.472  5593  5641 D BluetoothAdapter: STATE_ON
,11-21 17:39:46.472  5697  5713 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-21 17:39:46.472  5697  5713 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-21 17:39:46.472  5697  5716 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-21 17:39:46.476  5697  5726 D BtGatt.GattService: registerClient() - UUID=0fd28b05-62f2-47a2-83f1-6e720068b05a
,11-21 17:39:46.477  5697  5713 D BtGatt.GattService: onClientRegistered() - UUID=0fd28b05-62f2-47a2-83f1-6e720068b05a, clientIf=6
11-21 17:39:46.477  5593  5603 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
11-21 17:39:46.478  5697  5715 D BtGatt.AdvertiseManager: message : 0
11-21 17:39:46.478  5697  5713 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-21 17:39:46.478  5697  5713 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-21 17:39:46.481  5697  5715 D BtGatt.AdvertiseManager: starting multi advertising
,11-21 17:39:46.481  5697  5716 D BtGatt.ScanManager: handling starting scan
,11-21 17:39:46.491  5697  5713 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,11-21 17:39:46.495  5697  5713 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,11-21 17:39:46.495  5697  5713 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-21 17:39:46.495  5697  5716 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-21 17:39:46.499  5697  5713 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,11-21 17:39:46.500  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:46.500  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:46.500  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-21 17:39:46.500  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:46.500  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:46.500  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:46.500  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:46.500  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:46.501  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: advertiser is started. Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:46.501  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:46.501  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:46.501  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
11-21 17:39:46.501  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: adv = true, disc = true
11-21 17:39:46.501  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-21 17:39:46.502  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-21 17:39:46.502  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:46.504  5697  5713 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-21 17:39:46.504  5697  5713 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-21 17:39:46.504  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:46.504  5697  5716 D BtGatt.ScanManager: Starting BLE batch scan
11-21 17:39:46.504  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:46.504  5697  5716 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-21 17:39:46.504  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:46.504  5593  5593 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-21 17:39:46.504  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-21 17:39:46.505  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-21 17:39:46.505  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-21 17:39:46.505  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-21 17:39:46.505  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-21 17:39:46.505  5593  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-21 17:39:46.505  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-21 17:39:46.505  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING, ADVERTISING]
,11-21 17:39:46.505  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-21 17:39:46.505  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-21 17:39:46.505  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-21 17:39:46.505  5593  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
11-21 17:39:46.505  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-21 17:39:46.508  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-21 17:39:46.508  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
11-21 17:39:46.508  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-21 17:39:46.508  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-21 17:39:46.508  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-21 17:39:46.508  5593  5593 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,11-21 17:39:46.513  5697  5713 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-21 17:39:46.513  5697  5713 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-21 17:39:46.518  5697  5713 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-21 17:39:46.518  5697  5713 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-21 17:39:47.009  5593  5593 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: true
,11-21 17:39:47.009  5593  5593 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-21 17:39:47.009  5593  5593 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-21 17:39:49.511  5593  5641 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testConstructor
,11-21 17:39:49.511  5593  5641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-21 17:39:49.511  5593  5641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,11-21 17:39:49.512  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-21 17:39:49.512  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-21 17:39:49.512  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-21 17:39:49.512  5593  5836 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-21 17:39:49.512  5593  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,11-21 17:39:49.512  5593  5836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,11-21 17:39:49.513  5593  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,11-21 17:39:49.513  5593  5836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-21 17:39:49.513  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-21 17:39:49.513  5593  5593 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-21 17:39:49.513  5593  5641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d7470c0 removed from the list
11-21 17:39:49.513  5593  5593 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-21 17:39:49.513  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-21 17:39:49.514  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-21 17:39:49.514  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-21 17:39:49.514  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-21 17:39:49.514  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:49.514  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:49.514  5593  5593 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-21 17:39:49.515  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:49.515  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-21 17:39:49.515  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:49.519  5593  5641 D BluetoothAdapter: STATE_ON
11-21 17:39:49.520  5697  5734 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-21 17:39:49.522  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-21 17:39:49.522  5697  5716 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-21 17:39:49.525  5593  5641 D BluetoothAdapter: STATE_ON
11-21 17:39:49.526  5697  5707 D BtGatt.GattService: stopScan() - queue size =1
,11-21 17:39:49.527  5697  5725 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-21 17:39:49.528  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-21 17:39:49.528  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
,11-21 17:39:49.529  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-21 17:39:49.529  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:49.529  5697  5697 D BtGatt.ScanManager: awakened up at time 188802
11-21 17:39:49.529  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:49.529  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:49.529  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-21 17:39:49.529  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:49.531  5697  5715 D BtGatt.AdvertiseManager: message : 1
11-21 17:39:49.532  5697  5715 D BtGatt.AdvertiseManager: stop advertise for client 6
,11-21 17:39:49.544  5697  5713 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
11-21 17:39:49.544  5697  5713 D BtGatt.GattService: Client app is not null!
,11-21 17:39:49.546  5697  5708 D BtGatt.GattService: unregisterClient() - clientIf=6
,11-21 17:39:49.546  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-21 17:39:49.547  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-58,5,main], id: 58
,11-21 17:39:49.547  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-21 17:39:49.547  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:49.547  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:49.547  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-58,5,main], id: 58
,11-21 17:39:49.547  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-21 17:39:49.547  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-21 17:39:49.548  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-21 17:39:49.549  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:49.551  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:49.551  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-21 17:39:49.551  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:49.551  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:39:49.551  5593  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@96eb1f9 removed from the list
11-21 17:39:49.551  5593  5641 D io.jxcore.node.ConnectivityMonitor: stop
11-21 17:39:49.551  5593  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-21 17:39:49.552  5593  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-21 17:39:49.552  5593  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-21 17:39:49.552  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-21 17:39:49.552  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-21 17:39:49.552  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING, ADVERTISING]
11-21 17:39:49.552  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-21 17:39:49.552  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-21 17:39:49.552  5593  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [NOT_STARTED]
11-21 17:39:49.553  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-21 17:39:49.553  5593  5641 I io.jxcore.node.StartStopOperationTest: Starting test: testIsTargetState
11-21 17:39:49.553  5593  5641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-21 17:39:49.553  5593  5641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-21 17:39:49.554  5593  5641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-21 17:39:49.554  5593  5641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-21 17:39:49.554  5593  5641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
11-21 17:39:49.554  5593  5641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-21 17:39:49.554  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-21 17:39:49.555  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-21 17:39:49.555  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-21 17:39:49.555  5593  5641 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStartOperation
11-21 17:39:49.555  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-21 17:39:49.555  5593  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-21 17:39:49.555  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-21 17:39:49.555  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-21 17:39:49.555  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-21 17:39:49.555  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-21 17:39:49.555  5593  5593 D org.thalipr,oject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-21 17:39:49.555  5593  5593 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-21 17:39:49.556  5593  5641 I io.jxcore.node.StartStopOperationTest: Starting test: testGetShouldStartOrStopListeningToAdvertisementsOnly
,11-21 17:39:49.558  5593  5641 I io.jxcore.node.StartStopOperationTest: Starting test: testIsStartOperation
11-21 17:39:49.559  5593  5641 I io.jxcore.node.StartStopOperationTest: Starting test: testToString
11-21 17:39:49.560  5593  5641 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStopOperation
,11-21 17:39:49.561  5593  5641 I io.jxcore.node.StartStopOperationTest: Starting test: testSetOperationExecutedTime
,11-21 17:39:49.562  5593  5641 I io.jxcore.node.StartStopOperationTest: Starting test: testGetOperationExecutedTime
11-21 17:39:49.563  5593  5641 I io.jxcore.node.StartStopOperationTest: Starting test: testGetCallback
,11-21 17:39:49.571  5697  5713 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,11-21 17:39:49.571  5697  5713 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-21 17:39:49.571  5697  5713 D BtGatt.GattService: current time is 188845076239
11-21 17:39:49.572  5697  5713 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -84, 20, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -79, 57, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -79, 56, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -79, 56, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -89, 26, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-21 17:39:49.572  5697  5713 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-21 17:39:49.572  5697  5713 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,11-21 17:39:49.572  5697  5713 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-21 17:39:49.572  5697  5713 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-21 17:39:49.573  5697  5713 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,11-21 17:39:49.578  5697  5713 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-21 17:39:49.578  5697  5713 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-21 17:39:49.579  5697  5716 D BtGatt.ScanManager: stopping BLe Batch
,11-21 17:39:49.584  5697  5713 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-21 17:39:49.584  5697  5713 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-21 17:39:49.584  5697  5716 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-21 17:39:49.589  5697  5713 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-21 17:39:49.589  5697  5713 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-21 17:39:50.056  5593  5593 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-21 17:39:50.238   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:39:50.919   930  2986 D ConnectivityService: handlePromptUnvalidated 101
,11-21 17:39:51.239   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:39:51.568  5593  5641 I StreamCopyingThreadTest: Starting test: testCopyDataAndCloseConnection
,11-21 17:39:51.705  5593  5838 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 187, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-21 17:39:51.705  5593  5838 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-21 17:39:52.240   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:39:52.510  5593  5838 W !!      : call onHalfStreamCopied
,11-21 17:39:52.510  5593  5838 I testCopyDataAndClose: closing input stream
,11-21 17:39:53.241   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:39:53.288  5593  5838 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 187, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-21 17:39:53.288  5593  5838 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-21 17:39:53.289  5593  5838 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-21 17:39:53.289  5593  5838 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-21 17:39:53.289  5593  5838 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-21 17:39:53.289  5593  5838 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-21 17:39:53.289  5593  5838 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-21 17:39:53.289  5593  5838 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,11-21 17:39:53.289  5593  5838 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-21 17:39:53.289  5593  5838 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 187, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-21 17:39:53.289  5593  5838 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-21 17:39:54.031   930  2982 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 12 -> obsolete
,11-21 17:39:54.242   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:39:55.242   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-21 17:39:57.783   930  2986 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-21 17:39:57.801  5593  5641 I StreamCopyingThreadTest: Starting test: testCopyBigData
,11-21 17:39:57.883  5593  5839 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 190, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-21 17:39:57.883  5593  5839 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-21 17:39:59.503  5593  5839 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 190, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-21 17:39:59.503  5593  5839 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-21 17:39:59.503  5593  5839 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-21 17:39:59.503  5593  5839 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-21 17:39:59.503  5593  5839 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,11-21 17:39:59.503  5593  5839 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,11-21 17:39:59.503  5593  5839 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-21 17:39:59.503  5593  5839 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,11-21 17:39:59.503  5593  5839 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-21 17:39:59.503  5593  5839 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 190, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-21 17:39:59.503  5593  5839 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-21 17:40:03.811  5593  5641 I StreamCopyingThreadTest: Starting test: testRunNotify
,11-21 17:40:03.814  5593  5840 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 192, name: My test thread name). Connection data: Peer properties: [null null].
11-21 17:40:03.814  5593  5840 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-21 17:40:03.815  5593  5840 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 192, thread name: My test thread name). Connection data: Peer properties: [null null].
11-21 17:40:03.815  5593  5840 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-21 17:40:03.815  5593  5840 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-21 17:40:03.815  5593  5840 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-21 17:40:03.815  5593  5840 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-21 17:40:03.815  5593  5840 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-21 17:40:03.815  5593  5840 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-21 17:40:03.815  5593  5840 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-21 17:40:03.815  5593  5840 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-21 17:40:03.816  5593  5840 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 192, name: My test thread name). Connection data: Peer properties: [null null].
11-21 17:40:03.816  5593  5840 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
11-21 17:40:03.818  5593  5641 I StreamCopyingThreadTest: Starting test: testSetBufferSize
,11-21 17:40:03.818  5593  5641 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,11-21 17:40:03.819  5593  5641 I StreamCopyingThreadTest: Starting test: testRunWithException
,11-21 17:40:03.821  5593  5841 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 196, name: My test thread name). Connection data: Peer properties: [null null].
11-21 17:40:03.821  5593  5841 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-21 17:40:03.822  5593  5841 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 196, thread name: My test thread name): Test exception.
11-21 17:40:03.822  5593  5841 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 196, name: My test thread name). Connection data: Peer properties: [null null].
11-21 17:40:03.822  5593  5841 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,11-21 17:40:03.822  5593  5841 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
11-21 17:40:03.823  5593  5841 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 196, name: My test thread name). Connection data: Peer properties: [null null].
11-21 17:40:03.823  5593  5841 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,11-21 17:40:03.825  5593  5641 I jxcore-log: 2016-11-21 16:40:03 - DEBUG UnitTest_app: 'Running unit tests'
11-21 17:40:03.825  5593  5641 I jxcore-log: 
11-21 17:40:03.826  5593  5641 I jxcore-log: *Native tests were executed*
11-21 17:40:03.826  5593  5641 I jxcore-log: 
11-21 17:40:03.826  5593  5641 I jxcore-log: Total number of executed tests:  81
11-21 17:40:03.826  5593  5641 I jxcore-log: 
11-21 17:40:03.826  5593  5641 I jxcore-log: Number of passed tests:  79
11-21 17:40:03.826  5593  5641 I jxcore-log: 
,11-21 17:40:03.826  5593  5641 I jxcore-log: Number of failed tests:  0
11-21 17:40:03.826  5593  5641 I jxcore-log: 
11-21 17:40:03.826  5593  5641 I jxcore-log: Number of ignored tests:  2
11-21 17:40:03.826  5593  5641 I jxcore-log: 
11-21 17:40:03.826  5593  5641 I jxcore-log: Total duration:  35168
11-21 17:40:03.826  5593  5641 I jxcore-log: 
11-21 17:40:03.827  5593  5641 I jxcore-log: 2016-11-21 16:40:03 - DEBUG UnitTest_app: 'Unit Test app is loaded'
11-21 17:40:03.827  5593  5641 I jxcore-log: 
11-21 17:40:03.830  5593  5641 I jxcore-log: 2016-11-21 16:40:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-21 17:40:03.830  5593  5641 I jxcore-log: 
11-21 17:40:03.831  5593  5641 I jxcore-log: 2016-11-21 16:40:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-21 17:40:03.831  5593  5641 I jxcore-log: 
,11-21 17:40:03.832  5593  5641 I jxcore-log: 2016-11-21 16:40:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-21 17:40:03.832  5593  5641 I jxcore-log: 
11-21 17:40:03.833  5593  5641 I jxcore-log: 2016-11-21 16:40:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-21 17:40:03.833  5593  5641 I jxcore-log: 
11-21 17:40:03.833  5593  5641 I jxcore-log: 2016-11-21 16:40:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-21 17:40:03.833  5593  5641 I jxcore-log: 
,11-21 17:40:03.833  5593  5641 I jxcore-log: 2016-11-21 16:40:03 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-21 17:40:03.833  5593  5641 I jxcore-log: 
11-21 17:40:03.834  5593  5641 I jxcore-log: 2016-11-21 16:40:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-21 17:40:03.834  5593  5641 I jxcore-log: 
11-21 17:40:03.834  5593  5641 I jxcore-log: 2016-11-21 16:40:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-21 17:40:03.834  5593  5641 I jxcore-log: 
11-21 17:40:03.834  5593  5641 I jxcore-log: 2016-11-21 16:40:03 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-21 17:40:03.834  5593  5641 I jxcore-log: 
11-21 17:40:03.835  5593  5641 I jxcore-log: 2016-11-21 16:40:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-21 17:40:03.835  5593  5641 I jxcore-log: 
,11-21 17:40:03.835  5593  5641 I jxcore-log: 2016-11-21 16:40:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-21 17:40:03.835  5593  5641 I jxcore-log: 
,11-21 17:40:03.835  5593  5641 I jxcore-log: 2016-11-21 16:40:03 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-21 17:40:03.835  5593  5641 I jxcore-log: 
,11-21 17:40:03.835  5593  5641 I jxcore-log: 2016-11-21 16:40:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-21 17:40:03.835  5593  5641 I jxcore-log: 
11-21 17:40:03.835  5593  5641 I jxcore-log: 2016-11-21 16:40:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-21 17:40:03.835  5593  5641 I jxcore-log: 
11-21 17:40:03.836  5593  5641 I jxcore-log: 2016-11-21 16:40:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-21 17:40:03.836  5593  5641 I jxcore-log: 
11-21 17:40:03.836  5593  5641 I jxcore-log: 2016-11-21 16:40:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-21 17:40:03.836  5593  5641 I jxcore-log: 
,11-21 17:40:03.836  5593  5641 I jxcore-log: 2016-11-21 16:40:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-21 17:40:03.836  5593  5641 I jxcore-log: 
11-21 17:40:03.836  5593  5641 I jxcore-log: 2016-11-21 16:40:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-21 17:40:03.836  5593  5641 I jxcore-log: 
11-21 17:40:03.836  5593  5641 I jxcore-log: 2016-11-21 16:40:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-21 17:40:03.836  5593  5641 I jxcore-log: 
11-21 17:40:03.837  5593  5641 I jxcore-log: 2016-11-21 16:40:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-21 17:40:03.837  5593  5641 I jxcore-log: 
,11-21 17:40:03.837  5593  5641 I jxcore-log: 2016-11-21 16:40:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-21 17:40:03.837  5593  5641 I jxcore-log: 
11-21 17:40:03.837  5593  5641 I jxcore-log: 2016-11-21 16:40:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-21 17:40:03.837  5593  5641 I jxcore-log: 
11-21 17:40:03.837  5593  5641 I jxcore-log: 2016-11-21 16:40:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-21 17:40:03.837  5593  5641 I jxcore-log: 
11-21 17:40:03.838  5593  5641 I jxcore-log: 2016-11-21 16:40:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-21 17:40:03.838  5593  5641 I jxcore-log: 
11-21 17:40:03.838  5593  5641 I jxcore-log: 2016-11-21 16:40:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-21 17:40:03.838  5593  5641 I jxcore-log: 
,11-21 17:40:03.838  5593  5641 I jxcore-log: 2016-11-21 16:40:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-21 17:40:03.838  5593  5641 I jxcore-log: 
11-21 17:40:03.838  5593  5641 I jxcore-log: 2016-11-21 16:40:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-21 17:40:03.838  5593  5641 I jxcore-log: 
11-21 17:40:03.839  5593  5641 I jxcore-log: 2016-11-21 16:40:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-21 17:40:03.839  5593  5641 I jxcore-log: 
11-21 17:40:03.840  5593  5641 I jxcore-log: 2016-11-21 16:40:03 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-21 17:40:03.840  5593  5641 I jxcore-log: 
11-21 17:40:03.840  5593  5641 I jxcore-log: 2016-11-21 16:40:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-21 17:40:03.840  5593  5641 I jxcore-log: 
,11-21 17:40:03.840  5593  5641 I jxcore-log: 2016-11-21 16:40:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-21 17:40:03.840  5593  5641 I jxcore-log: 
11-21 17:40:03.841  5593  5641 I jxcore-log: 2016-11-21 16:40:03 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-21 17:40:03.841  5593  5641 I jxcore-log: 
11-21 17:40:03.841  5593  5641 I jxcore-log: 2016-11-21 16:40:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-21 17:40:03.841  5593  5641 I jxcore-log: 
11-21 17:40:03.841  5593  5641 I jxcore-log: 2016-11-21 16:40:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
11-21 17:40:03.841  5593  5641 I jxcore-log: 
11-21 17:40:03.841  5593  5641 I jxcore-log: 2016-11-21 16:40:03 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-21 17:40:03.841  5593  5641 I jxcore-log: 
,11-21 17:40:03.841  5593  5641 I jxcore-log: 2016-11-21 16:40:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-21 17:40:03.841  5593  5641 I jxcore-log: 
11-21 17:40:03.842  5593  5641 I jxcore-log: 2016-11-21 16:40:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-21 17:40:03.842  5593  5641 I jxcore-log: 
11-21 17:40:03.842  5593  5641 I jxcore-log: 2016-11-21 16:40:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-21 17:40:03.842  5593  5641 I jxcore-log: 
11-21 17:40:03.847  5593  5641 I jxcore-log: 2016-11-21 16:40:03 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
11-21 17:40:03.847  5593  5641 I jxcore-log: 
11-21 17:40:03.847  5593  5641 I jxcore-log: 2016-11-21 16:40:03 - WARN testUtils: 'myNameCallback not set!'
11-21 17:40:03.847  5593  5641 I jxcore-log: 
,11-21 17:40:03.854  5593  5593 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,11-21 17:40:05.117   930  5811 D NetlinkSocketObserver: NeighborEvent{elapsedMs=204390, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-21 17:40:05.921  5593  5641 I jxcore-log: 2016-11-21 16:40:05 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
11-21 17:40:05.921  5593  5641 I jxcore-log: 
,11-21 17:40:05.923  5593  5641 I jxcore-log: 2016-11-21 16:40:05 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
11-21 17:40:05.923  5593  5641 I jxcore-log: 
,11-21 17:40:06.266  5593  5641 I jxcore-log: 2016-11-21 16:40:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
11-21 17:40:06.266  5593  5641 I jxcore-log: 
,11-21 17:40:06.280  5593  5641 I jxcore-log: 2016-11-21 16:40:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
11-21 17:40:06.280  5593  5641 I jxcore-log: 
,11-21 17:40:06.328  3652  3829 I Keyboard.Facilitator.LanguageModelFlusher: run()
,11-21 17:40:06.329  3652  3829 I Keyboard.Facilitator: flushDynamicLanguageModels()
,11-21 17:40:06.360  3544  3544 I ConfigService: onCreate
,11-21 17:40:06.859   930  2986 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-21 17:40:07.355  5593  5641 I jxcore-log: 2016-11-21 16:40:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
11-21 17:40:07.355  5593  5641 I jxcore-log: 
,11-21 17:40:07.522  5593  5641 I jxcore-log: 2016-11-21 16:40:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
11-21 17:40:07.522  5593  5641 I jxcore-log: 
,11-21 17:40:07.527  5593  5641 I jxcore-log: 2016-11-21 16:40:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
11-21 17:40:07.527  5593  5641 I jxcore-log: 
,11-21 17:40:07.539  5593  5641 I jxcore-log: 2016-11-21 16:40:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
11-21 17:40:07.539  5593  5641 I jxcore-log: 
,11-21 17:40:08.030  5593  5641 I jxcore-log: 2016-11-21 16:40:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
11-21 17:40:08.030  5593  5641 I jxcore-log: 
,11-21 17:40:08.075  5593  5641 I jxcore-log: 2016-11-21 16:40:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
11-21 17:40:08.075  5593  5641 I jxcore-log: 
,11-21 17:40:08.088  5593  5641 I jxcore-log: 2016-11-21 16:40:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
11-21 17:40:08.088  5593  5641 I jxcore-log: 
,11-21 17:40:08.092  5593  5641 I jxcore-log: 2016-11-21 16:40:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
11-21 17:40:08.092  5593  5641 I jxcore-log: 
,11-21 17:40:08.370  5593  5641 I jxcore-log: 2016-11-21 16:40:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
11-21 17:40:08.370  5593  5641 I jxcore-log: 
,11-21 17:40:08.496  5593  5641 I jxcore-log: 2016-11-21 16:40:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
11-21 17:40:08.496  5593  5641 I jxcore-log: 
,11-21 17:40:08.868  5593  5641 I jxcore-log: 2016-11-21 16:40:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
11-21 17:40:08.868  5593  5641 I jxcore-log: 
,11-21 17:40:08.874  5593  5641 I jxcore-log: 2016-11-21 16:40:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
11-21 17:40:08.874  5593  5641 I jxcore-log: 
,11-21 17:40:08.879  5593  5641 I jxcore-log: 2016-11-21 16:40:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
11-21 17:40:08.879  5593  5641 I jxcore-log: 
,11-21 17:40:08.882  5593  5641 I jxcore-log: 2016-11-21 16:40:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
11-21 17:40:08.882  5593  5641 I jxcore-log: 
,11-21 17:40:08.888  5593  5641 I jxcore-log: 2016-11-21 16:40:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
11-21 17:40:08.888  5593  5641 I jxcore-log: 
,11-21 17:40:08.926  5593  5641 I jxcore-log: 2016-11-21 16:40:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
11-21 17:40:08.926  5593  5641 I jxcore-log: 
,11-21 17:40:08.932  5593  5641 I jxcore-log: 2016-11-21 16:40:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
11-21 17:40:08.932  5593  5641 I jxcore-log: 
,11-21 17:40:08.961  5593  5641 I jxcore-log: 2016-11-21 16:40:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
11-21 17:40:08.961  5593  5641 I jxcore-log: 
,11-21 17:40:09.000  5593  5641 I jxcore-log: 2016-11-21 16:40:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
11-21 17:40:09.000  5593  5641 I jxcore-log: 
,11-21 17:40:09.008  5593  5641 I jxcore-log: 2016-11-21 16:40:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
11-21 17:40:09.008  5593  5641 I jxcore-log: 
,11-21 17:40:09.014  5593  5641 I jxcore-log: 2016-11-21 16:40:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
11-21 17:40:09.014  5593  5641 I jxcore-log: 
,11-21 17:40:09.029  5593  5641 I jxcore-log: 2016-11-21 16:40:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
11-21 17:40:09.029  5593  5641 I jxcore-log: 
,11-21 17:40:09.044  5593  5641 I jxcore-log: 2016-11-21 16:40:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
11-21 17:40:09.044  5593  5641 I jxcore-log: 
,11-21 17:40:09.050  5593  5641 I jxcore-log: 2016-11-21 16:40:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
11-21 17:40:09.050  5593  5641 I jxcore-log: 
,11-21 17:40:09.055  5593  5641 I jxcore-log: 2016-11-21 16:40:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
11-21 17:40:09.055  5593  5641 I jxcore-log: 
,11-21 17:40:09.069  5593  5641 I jxcore-log: 2016-11-21 16:40:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
11-21 17:40:09.069  5593  5641 I jxcore-log: 
,11-21 17:40:09.086  5593  5641 I jxcore-log: 2016-11-21 16:40:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
11-21 17:40:09.086  5593  5641 I jxcore-log: 
,11-21 17:40:09.101  5593  5641 I jxcore-log: 2016-11-21 16:40:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
11-21 17:40:09.101  5593  5641 I jxcore-log: 
,11-21 17:40:09.112  5593  5641 I jxcore-log: 2016-11-21 16:40:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
11-21 17:40:09.112  5593  5641 I jxcore-log: 
,11-21 17:40:09.124  5593  5641 I jxcore-log: 2016-11-21 16:40:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
11-21 17:40:09.124  5593  5641 I jxcore-log: 
,11-21 17:40:09.135  5593  5641 I jxcore-log: 2016-11-21 16:40:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
11-21 17:40:09.135  5593  5641 I jxcore-log: 
,11-21 17:40:09.148  5593  5641 I jxcore-log: 2016-11-21 16:40:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
11-21 17:40:09.148  5593  5641 I jxcore-log: 
,11-21 17:40:09.158  5593  5641 I jxcore-log: 2016-11-21 16:40:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
11-21 17:40:09.158  5593  5641 I jxcore-log: 
,11-21 17:40:09.165  5593  5641 I jxcore-log: 2016-11-21 16:40:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
11-21 17:40:09.165  5593  5641 I jxcore-log: 
,11-21 17:40:09.186  5593  5641 I jxcore-log: 2016-11-21 16:40:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testUsn.js'
11-21 17:40:09.186  5593  5641 I jxcore-log: 
,11-21 17:40:09.192  5593  5641 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,11-21 17:40:09.193  5593  5641 I jxcore-log: 2016-11-21 16:40:09 - INFO testUtils: 'BLE multiple advertisement supported'
11-21 17:40:09.193  5593  5641 I jxcore-log: 
,11-21 17:40:09.447  5593  5641 I jxcore-log: 2016-11-21 16:40:09 - DEBUG CoordinatedClient: 'connected to the test server'
11-21 17:40:09.447  5593  5641 I jxcore-log: 
,11-21 17:40:11.396  3544  3544 I ConfigService: onDestroy
,11-21 17:40:14.270   930  5811 D NetlinkSocketObserver: NeighborEvent{elapsedMs=213543, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-21 17:40:15.941   930  2986 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-21 17:40:18.971   930  2986 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-21 17:40:20.243   537   537 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-21 17:40:20.243   537   537 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-21 17:40:22.858   930  2982 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-21 17:40:30.245   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:40:31.017   930  5811 D NetlinkSocketObserver: NeighborEvent{elapsedMs=230290, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-21 17:40:31.069   930  2986 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-21 17:40:31.246   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:40:32.248   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:40:33.249   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:40:34.250   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:40:35.251   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-21 17:40:37.126   930  2986 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-21 17:40:39.444   930  5811 D NetlinkSocketObserver: NeighborEvent{elapsedMs=238717, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-21 17:40:40.252   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:40:41.254   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:40:42.255   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:40:43.256   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:40:44.258   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:40:45.258   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-21 17:40:49.207   930  2986 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-21 17:40:55.260   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:40:55.267   930  2986 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-21 17:40:56.084   930  5811 D NetlinkSocketObserver: NeighborEvent{elapsedMs=255357, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-21 17:40:56.261   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:40:57.263   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:40:58.264   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:40:58.298   930  2986 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-21 17:40:59.265   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:41:00.266   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-21 17:41:01.335   930  2986 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-21 17:41:02.861   930  2982 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-21 17:41:04.470   930  5811 D NetlinkSocketObserver: NeighborEvent{elapsedMs=263744, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-21 17:41:10.414   930  2986 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-21 17:41:15.267   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:41:16.268   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:41:16.468   930  2986 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-21 17:41:17.269   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:41:18.270   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:41:19.272   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:41:20.273   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-21 17:41:21.630   930  5811 D NetlinkSocketObserver: NeighborEvent{elapsedMs=280903, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-21 17:41:22.521   930  2986 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-21 17:41:22.862   930  2982 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-21 17:41:25.549   930  2986 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-21 17:41:28.582   930  2986 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-21 17:41:29.977   930  5811 D NetlinkSocketObserver: NeighborEvent{elapsedMs=289250, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-21 17:41:34.644   930  2986 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-21 17:41:37.672   930  2986 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-21 17:41:40.274   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:41:41.275   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:41:42.277   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:41:43.278   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:41:44.279   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:41:45.280   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-21 17:41:46.644   930  5811 D NetlinkSocketObserver: NeighborEvent{elapsedMs=305917, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-21 17:41:46.722   930  2986 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-21 17:41:55.004   930  5811 D NetlinkSocketObserver: NeighborEvent{elapsedMs=314277, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-21 17:41:55.806   930  2986 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-21 17:42:01.862   930  2986 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-21 17:42:02.867   930  2982 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-21 17:42:10.280   537   537 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-21 17:42:10.281   537   537 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-21 17:42:10.947   930  2986 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-21 17:42:11.657   930  5811 D NetlinkSocketObserver: NeighborEvent{elapsedMs=330930, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-21 17:42:13.978   930  2986 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-21 17:42:20.057   930  5811 D NetlinkSocketObserver: NeighborEvent{elapsedMs=339330, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-21 17:42:22.871   930  2982 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-21 17:42:23.040   930  2986 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-21 17:42:25.282   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:42:26.283   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:42:27.284   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:42:28.285   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:42:29.287   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:42:30.287   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-21 17:42:32.115   930  2986 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-21 17:42:35.145   930  2986 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-21 17:42:35.288   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:42:36.289   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:42:36.724   930  5811 D NetlinkSocketObserver: NeighborEvent{elapsedMs=355997, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-21 17:42:37.291   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:42:38.175   930  2986 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-21 17:42:38.292   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:42:39.293   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:42:40.294   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-21 17:42:42.871   930  2982 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-21 17:42:44.235   930  2986 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-21 17:42:45.084   930  5811 D NetlinkSocketObserver: NeighborEvent{elapsedMs=364357, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-21 17:42:50.295   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:42:51.297   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:42:52.298   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:42:53.299   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:42:53.313   930  2986 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-21 17:42:54.300   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:42:55.301   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-21 17:42:56.339   930  2986 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-21 17:42:59.370   930  2986 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-21 17:43:01.737   930  5811 D NetlinkSocketObserver: NeighborEvent{elapsedMs=381010, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-21 17:43:05.425   930  2986 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-21 17:43:10.110   930  5811 D NetlinkSocketObserver: NeighborEvent{elapsedMs=389383, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-21 17:43:10.302   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:43:11.303   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:43:11.485   930  2986 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-21 17:43:12.305   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:43:13.306   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:43:14.308   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:43:15.309   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-21 17:43:17.545   930  2986 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-21 17:43:20.573   930  2986 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-21 17:43:22.875   930  2982 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-21 17:43:26.803   930  5811 D NetlinkSocketObserver: NeighborEvent{elapsedMs=406077, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-21 17:43:35.178   930  5811 D NetlinkSocketObserver: NeighborEvent{elapsedMs=414451, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-21 17:43:35.310   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:43:35.704   930  2986 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-21 17:43:36.311   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:43:37.312   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:43:38.314   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:43:39.315   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:43:40.316   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-21 17:43:41.756   930  2986 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-21 17:43:42.877   930  2982 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-21 17:43:44.785   930  2986 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-21 17:43:47.811   930  2986 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-21 17:43:50.839   930  2986 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-21 17:43:52.564   930  5811 D NetlinkSocketObserver: NeighborEvent{elapsedMs=431837, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-21 17:43:53.875   930  2986 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-21 17:44:00.924   930  5811 D NetlinkSocketObserver: NeighborEvent{elapsedMs=440197, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-21 17:44:02.880   930  2982 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-21 17:44:05.316   537   537 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-21 17:44:05.317   537   537 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-21 17:44:05.964   930  2986 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-21 17:44:09.834  5593  5641 I jxcore-log: 2016-11-21 16:44:09 - DEBUG CoordinatedClient: 'device disconnected from the test server'
11-21 17:44:09.834  5593  5641 I jxcore-log: 
,11-21 17:44:10.101  5593  5641 I jxcore-log: 2016-11-21 16:44:10 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-21 17:44:10.101  5593  5641 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-21 17:44:10.101  5593  5641 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-21 17:44:10.101  5593  5641 I jxcore-log: emit@events.js:82:1
11-21 17:44:10.101  5593  5641 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-21 17:44:10.101  5593  5641 I jxcore-log: emit@events.js:82:1'
11-21 17:44:10.101  5593  5641 I jxcore-log: 
,11-21 17:44:10.105  5593  5641 I jxcore-log: 2016-11-21 16:44:10 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-21 17:44:10.105  5593  5641 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-21 17:44:10.105  5593  5641 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-21 17:44:10.105  5593  5641 I jxcore-log: emit@events.js:82:1
11-21 17:44:10.105  5593  5641 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-21 17:44:10.105  5593  5641 I jxcore-log: emit@events.js:82:1'
11-21 17:44:10.105  5593  5641 I jxcore-log: 
,11-21 17:44:10.611  5593  5641 I jxcore-log: 2016-11-21 16:44:10 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-21 17:44:10.611  5593  5641 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-21 17:44:10.611  5593  5641 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-21 17:44:10.611  5593  5641 I jxcore-log: emit@events.js:82:1
11-21 17:44:10.611  5593  5641 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-21 17:44:10.611  5593  5641 I jxcore-log: emit@events.js:82:1'
11-21 17:44:10.611  5593  5641 I jxcore-log: 
,11-21 17:44:10.615  5593  5641 I jxcore-log: 2016-11-21 16:44:10 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-21 17:44:10.615  5593  5641 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-21 17:44:10.615  5593  5641 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-21 17:44:10.615  5593  5641 I jxcore-log: emit@events.js:82:1
11-21 17:44:10.615  5593  5641 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-21 17:44:10.615  5593  5641 I jxcore-log: emit@events.js:82:1'
11-21 17:44:10.615  5593  5641 I jxcore-log: 
,11-21 17:44:11.965  5593  5641 I jxcore-log: 2016-11-21 16:44:11 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-21 17:44:11.965  5593  5641 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-21 17:44:11.965  5593  5641 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-21 17:44:11.965  5593  5641 I jxcore-log: emit@events.js:82:1
11-21 17:44:11.965  5593  5641 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-21 17:44:11.965  5593  5641 I jxcore-log: emit@events.js:82:1'
11-21 17:44:11.965  5593  5641 I jxcore-log: 
,11-21 17:44:11.972  5593  5641 I jxcore-log: 2016-11-21 16:44:11 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-21 17:44:11.972  5593  5641 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-21 17:44:11.972  5593  5641 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-21 17:44:11.972  5593  5641 I jxcore-log: emit@events.js:82:1
11-21 17:44:11.972  5593  5641 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-21 17:44:11.972  5593  5641 I jxcore-log: emit@events.js:82:1'
11-21 17:44:11.972  5593  5641 I jxcore-log: 
,11-21 17:44:13.003  5593  5641 I jxcore-log: 2016-11-21 16:44:13 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-21 17:44:13.003  5593  5641 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-21 17:44:13.003  5593  5641 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-21 17:44:13.003  5593  5641 I jxcore-log: emit@events.js:82:1
11-21 17:44:13.003  5593  5641 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-21 17:44:13.003  5593  5641 I jxcore-log: emit@events.js:82:1'
11-21 17:44:13.003  5593  5641 I jxcore-log: 
,11-21 17:44:13.008  5593  5641 I jxcore-log: 2016-11-21 16:44:13 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-21 17:44:13.008  5593  5641 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-21 17:44:13.008  5593  5641 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-21 17:44:13.008  5593  5641 I jxcore-log: emit@events.js:82:1
11-21 17:44:13.008  5593  5641 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-21 17:44:13.008  5593  5641 I jxcore-log: emit@events.js:82:1'
11-21 17:44:13.008  5593  5641 I jxcore-log: 
,11-21 17:44:14.046  5593  5641 I jxcore-log: 2016-11-21 16:44:14 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-21 17:44:14.046  5593  5641 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-21 17:44:14.046  5593  5641 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-21 17:44:14.046  5593  5641 I jxcore-log: emit@events.js:82:1
11-21 17:44:14.046  5593  5641 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-21 17:44:14.046  5593  5641 I jxcore-log: emit@events.js:82:1'
11-21 17:44:14.046  5593  5641 I jxcore-log: 
,11-21 17:44:14.049  5593  5641 I jxcore-log: 2016-11-21 16:44:14 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-21 17:44:14.049  5593  5641 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-21 17:44:14.049  5593  5641 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-21 17:44:14.049  5593  5641 I jxcore-log: emit@events.js:82:1
11-21 17:44:14.049  5593  5641 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-21 17:44:14.049  5593  5641 I jxcore-log: emit@events.js:82:1'
11-21 17:44:14.049  5593  5641 I jxcore-log: 
,11-21 17:44:15.011   930  2986 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-21 17:44:15.085  5593  5641 I jxcore-log: 2016-11-21 16:44:15 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-21 17:44:15.085  5593  5641 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-21 17:44:15.085  5593  5641 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-21 17:44:15.085  5593  5641 I jxcore-log: emit@events.js:82:1
11-21 17:44:15.085  5593  5641 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-21 17:44:15.085  5593  5641 I jxcore-log: emit@events.js:82:1'
11-21 17:44:15.085  5593  5641 I jxcore-log: 
,11-21 17:44:15.089  5593  5641 I jxcore-log: 2016-11-21 16:44:15 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-21 17:44:15.089  5593  5641 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-21 17:44:15.089  5593  5641 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-21 17:44:15.089  5593  5641 I jxcore-log: emit@events.js:82:1
11-21 17:44:15.089  5593  5641 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-21 17:44:15.089  5593  5641 I jxcore-log: emit@events.js:82:1'
11-21 17:44:15.089  5593  5641 I jxcore-log: 
,11-21 17:44:16.122  5593  5641 I jxcore-log: 2016-11-21 16:44:16 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-21 17:44:16.122  5593  5641 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-21 17:44:16.122  5593  5641 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-21 17:44:16.122  5593  5641 I jxcore-log: emit@events.js:82:1
11-21 17:44:16.122  5593  5641 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-21 17:44:16.122  5593  5641 I jxcore-log: emit@events.js:82:1'
11-21 17:44:16.122  5593  5641 I jxcore-log: 
,11-21 17:44:16.127  5593  5641 I jxcore-log: 2016-11-21 16:44:16 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-21 17:44:16.127  5593  5641 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-21 17:44:16.127  5593  5641 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-21 17:44:16.127  5593  5641 I jxcore-log: emit@events.js:82:1
11-21 17:44:16.127  5593  5641 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-21 17:44:16.127  5593  5641 I jxcore-log: emit@events.js:82:1'
11-21 17:44:16.127  5593  5641 I jxcore-log: 
,11-21 17:44:17.164  5593  5641 I jxcore-log: 2016-11-21 16:44:17 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-21 17:44:17.164  5593  5641 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-21 17:44:17.164  5593  5641 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-21 17:44:17.164  5593  5641 I jxcore-log: emit@events.js:82:1
11-21 17:44:17.164  5593  5641 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-21 17:44:17.164  5593  5641 I jxcore-log: emit@events.js:82:1'
11-21 17:44:17.164  5593  5641 I jxcore-log: 
,11-21 17:44:17.170  5593  5641 I jxcore-log: 2016-11-21 16:44:17 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-21 17:44:17.170  5593  5641 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-21 17:44:17.170  5593  5641 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-21 17:44:17.170  5593  5641 I jxcore-log: emit@events.js:82:1
11-21 17:44:17.170  5593  5641 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-21 17:44:17.170  5593  5641 I jxcore-log: emit@events.js:82:1'
11-21 17:44:17.170  5593  5641 I jxcore-log: 
,11-21 17:44:17.630   930  5811 D NetlinkSocketObserver: NeighborEvent{elapsedMs=456903, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-21 17:44:18.205  5593  5641 I jxcore-log: 2016-11-21 16:44:18 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-21 17:44:18.205  5593  5641 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-21 17:44:18.205  5593  5641 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-21 17:44:18.205  5593  5641 I jxcore-log: emit@events.js:82:1
11-21 17:44:18.205  5593  5641 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-21 17:44:18.205  5593  5641 I jxcore-log: emit@events.js:82:1'
11-21 17:44:18.205  5593  5641 I jxcore-log: 
11-21 17:44:18.209  5593  5641 I jxcore-log: 2016-11-21 16:44:18 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-21 17:44:18.209  5593  5641 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-21 17:44:18.209  5593  5641 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-21 17:44:18.209  5593  5641 I jxcore-log: emit@events.js:82:1
11-21 17:44:18.209  5593  5641 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-21 17:44:18.209  5593  5641 I jxcore-log: emit@events.js:82:1'
11-21 17:44:18.209  5593  5641 I jxcore-log: 
,11-21 17:44:19.275  5593  5641 I jxcore-log: 2016-11-21 16:44:19 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-21 17:44:19.275  5593  5641 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-21 17:44:19.275  5593  5641 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-21 17:44:19.275  5593  5641 I jxcore-log: emit@events.js:82:1
11-21 17:44:19.275  5593  5641 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-21 17:44:19.275  5593  5641 I jxcore-log: emit@events.js:82:1'
11-21 17:44:19.275  5593  5641 I jxcore-log: 
,11-21 17:44:19.280  5593  5641 I jxcore-log: 2016-11-21 16:44:19 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-21 17:44:19.280  5593  5641 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-21 17:44:19.280  5593  5641 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-21 17:44:19.280  5593  5641 I jxcore-log: emit@events.js:82:1
11-21 17:44:19.280  5593  5641 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-21 17:44:19.280  5593  5641 I jxcore-log: emit@events.js:82:1'
11-21 17:44:19.280  5593  5641 I jxcore-log: 
,11-21 17:44:20.320  5593  5641 I jxcore-log: 2016-11-21 16:44:20 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-21 17:44:20.320  5593  5641 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-21 17:44:20.320  5593  5641 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-21 17:44:20.320  5593  5641 I jxcore-log: emit@events.js:82:1
11-21 17:44:20.320  5593  5641 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-21 17:44:20.320  5593  5641 I jxcore-log: emit@events.js:82:1'
11-21 17:44:20.320  5593  5641 I jxcore-log: 
,11-21 17:44:20.324  5593  5641 I jxcore-log: 2016-11-21 16:44:20 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-21 17:44:20.324  5593  5641 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-21 17:44:20.324  5593  5641 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-21 17:44:20.324  5593  5641 I jxcore-log: emit@events.js:82:1
11-21 17:44:20.324  5593  5641 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-21 17:44:20.324  5593  5641 I jxcore-log: emit@events.js:82:1'
11-21 17:44:20.324  5593  5641 I jxcore-log: 
,11-21 17:44:21.891  5593  5641 I jxcore-log: 2016-11-21 16:44:21 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-21 17:44:21.891  5593  5641 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-21 17:44:21.891  5593  5641 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-21 17:44:21.891  5593  5641 I jxcore-log: emit@events.js:82:1
11-21 17:44:21.891  5593  5641 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-21 17:44:21.891  5593  5641 I jxcore-log: emit@events.js:82:1'
11-21 17:44:21.891  5593  5641 I jxcore-log: 
,11-21 17:44:21.897  5593  5641 I jxcore-log: 2016-11-21 16:44:21 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-21 17:44:21.897  5593  5641 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-21 17:44:21.897  5593  5641 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-21 17:44:21.897  5593  5641 I jxcore-log: emit@events.js:82:1
11-21 17:44:21.897  5593  5641 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-21 17:44:21.897  5593  5641 I jxcore-log: emit@events.js:82:1'
11-21 17:44:21.897  5593  5641 I jxcore-log: 
,11-21 17:44:22.882   930  2982 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-21 17:44:22.921  5593  5641 I jxcore-log: 2016-11-21 16:44:22 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-21 17:44:22.921  5593  5641 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-21 17:44:22.921  5593  5641 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-21 17:44:22.921  5593  5641 I jxcore-log: emit@events.js:82:1
11-21 17:44:22.921  5593  5641 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-21 17:44:22.921  5593  5641 I jxcore-log: emit@events.js:82:1'
11-21 17:44:22.921  5593  5641 I jxcore-log: 
,11-21 17:44:22.925  5593  5641 I jxcore-log: 2016-11-21 16:44:22 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-21 17:44:22.925  5593  5641 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-21 17:44:22.925  5593  5641 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-21 17:44:22.925  5593  5641 I jxcore-log: emit@events.js:82:1
11-21 17:44:22.925  5593  5641 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-21 17:44:22.925  5593  5641 I jxcore-log: emit@events.js:82:1'
11-21 17:44:22.925  5593  5641 I jxcore-log: 
,11-21 17:44:23.204   930  5811 D NetlinkSocketObserver: NeighborEvent{elapsedMs=462477, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,11-21 17:44:23.964  5593  5641 I jxcore-log: 2016-11-21 16:44:23 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-21 17:44:23.964  5593  5641 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-21 17:44:23.964  5593  5641 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-21 17:44:23.964  5593  5641 I jxcore-log: emit@events.js:82:1
11-21 17:44:23.964  5593  5641 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-21 17:44:23.964  5593  5641 I jxcore-log: emit@events.js:82:1'
11-21 17:44:23.964  5593  5641 I jxcore-log: 
,11-21 17:44:23.968  5593  5641 I jxcore-log: 2016-11-21 16:44:23 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-21 17:44:23.968  5593  5641 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-21 17:44:23.968  5593  5641 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-21 17:44:23.968  5593  5641 I jxcore-log: emit@events.js:82:1
11-21 17:44:23.968  5593  5641 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-21 17:44:23.968  5593  5641 I jxcore-log: emit@events.js:82:1'
11-21 17:44:23.968  5593  5641 I jxcore-log: 
,11-21 17:44:25.001  5593  5641 I jxcore-log: 2016-11-21 16:44:25 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-21 17:44:25.001  5593  5641 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-21 17:44:25.001  5593  5641 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-21 17:44:25.001  5593  5641 I jxcore-log: emit@events.js:82:1
11-21 17:44:25.001  5593  5641 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-21 17:44:25.001  5593  5641 I jxcore-log: emit@events.js:82:1'
11-21 17:44:25.001  5593  5641 I jxcore-log: 
,11-21 17:44:25.010  5593  5641 E jxcore  : Error!: error is undefined
11-21 17:44:25.010  5593  5641 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js","_functionName":"CoordinatedClient.prototype._error","_lineNumber":"223","_columnNumber":"1","_msg":"    at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:223:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.emit","_lineNumber":"133","_columnNumber":"5","_msg":"    at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.emitAll","_lineNumber":"81","_columnNumber":"7","_msg":"    at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect","_lineNumber":"507","_columnNumber":"5","_msg":"    at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect/timer</<","_lineNumber":"528","_columnNumber":"11","_msg":"    at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.connect/errorSub<","_lineNumber":"235","_columnNumber":"7","_msg":"    at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js","_functionName":"Socket.prototype.onError","_lineNumber":"670","_columnNumber":"3","_msg":"    at Socket.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3"}]
,11-21 17:44:25.013  5593  5641 I jxcore-log: 2016-11-21 16:44:25 - ERROR TestsProcess: 'uncaught exception, error: 'TypeError: error is undefined', stack: 'TypeError: error is undefined
11-21 17:44:25.013  5593  5641 I jxcore-log:     at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:223:1
11-21 17:44:25.013  5593  5641 I jxcore-log:     at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7
11-21 17:44:25.013  5593  5641 I jxcore-log:     at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5
11-21 17:44:25.013  5593  5641 I jxcore-log:     at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7
11-21 17:44:25.013  5593  5641 I jxcore-log:     at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5
11-21 17:44:25.013  5593  5641 I jxcore-log:     at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11
11-21 17:44:25.013  5593  5641 I jxcore-log:     at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/sock
,11-21 17:44:25.015  5593  5641 I jxcore-log: 2016-11-21 16:44:25 - ERROR TestsProcess: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
11-21 17:44:25.015  5593  5641 I jxcore-log: 
11-21 17:44:25.016  5593  5641 E jxcore-log: TypeError: 
11-21 17:44:25.017  5593  5641 E jxcore-log: error is undefined
11-21 17:44:25.017  5593  5641 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js 223:0)
11-21 17:44:25.017  5593  5641 E jxcore-log: 
,11-21 17:44:25.088   930  2944 W InputDispatcher: channel '5759de5 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
11-21 17:44:25.088   930  2944 E InputDispatcher: channel '5759de5 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
,11-21 17:44:25.098   930  3833 D GraphicsStats: Buffer count: 2
11-21 17:44:25.098   930  3521 I WindowState: WIN DEATH: Window{5759de5 u0 com.test.thalitest/com.test.thalitest.MainActivity}
11-21 17:44:25.098   930  3521 W InputDispatcher: Attempted to unregister already unregistered input channel '5759de5 com.test.thalitest/com.test.thalitest.MainActivity (server)'
11-21 17:44:25.100   930  2985 D WifiService: Client connection lost with reason: 4
,11-21 17:44:25.117   529   529 I Zygote  : Process 5593 exited cleanly (139)
,11-21 17:44:25.123   930  3833 I ActivityManager: Process com.test.thalitest (pid 5593) has died
,11-21 17:44:25.124   930  3833 W ActivityManager: Force removing ActivityRecord{e957002 u0 com.test.thalitest/.MainActivity t70}: app died, no saved state
,11-21 17:44:25.161   930  3604 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5593 uid 10077
,11-21 17:44:25.159  3604  3604 W Binder_6: type=1400 audit(0.0:128): avc: denied { ioctl } for path="socket:[29713]" dev="sockfs" ino=29713 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-21 17:44:25.162  3652  3652 I Keyboard.Facilitator: onFinishInput()
11-21 17:44:25.159  3604  3604 W Binder_6: type=1400 audit(0.0:129): avc: denied { ioctl } for path="socket:[29713]" dev="sockfs" ino=29713 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-21 17:44:25.235  3946  5859 I MicroRecognitionRnrImpl: Starting detection.
,11-21 17:44:25.240  3946  5860 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.x@5b71717
,11-21 17:44:25.244   514  5862 I AudioFlinger: AudioFlinger's thread 0xf2200000 ready to run
,11-21 17:44:25.249   514  2983 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-21 17:44:25.251  3946  5860 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.x@5b71717
,11-21 17:44:25.261   514  5862 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(63: voice-rec-mic)
,11-21 17:44:25.261   514  5862 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(63) acdb_id(62)
11-21 17:44:25.261   514  5862 I ACDB-LOADER: ACDB AFE returned = -19
11-21 17:44:25.261   514  5862 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 1
11-21 17:44:25.261   514  5862 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 1, rx 0, concurrency session_allowed 0
11-21 17:44:25.261   514  5862 D audio_hw_primary: enable_snd_device: snd_device(63: voice-rec-mic)
,11-21 17:44:25.267   514  5862 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,11-21 17:44:25.317   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:44:25.340  3946  3946 I HotwordWorkerImpl: onReady
,11-21 17:44:25.506  5853  5853 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,11-21 17:44:25.510  5853  5853 D AndroidRuntime: CheckJNI is OFF
,11-21 17:44:25.533  5853  5853 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,11-21 17:44:25.565  5853  5853 I Radio-JNI: register_android_hardware_Radio DONE
,11-21 17:44:25.581  5853  5853 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-21 17:44:25.590   930   943 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,11-21 17:44:25.710  3779  4010 W OpenGLRenderer: Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,11-21 17:44:25.742   930   953 I art     : Starting a blocking GC Explicit
,11-21 17:44:25.844   930   953 I art     : Explicit concurrent mark sweep GC freed 150376(10MB) AllocSpace objects, 79(2MB) LOS objects, 33% free, 29MB/43MB, paused 1.501ms total 102.031ms
,11-21 17:44:25.865   930   953 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,11-21 17:44:25.868  5853  5853 I art     : System.exit called, status: 0
,11-21 17:44:25.868  5853  5853 I AndroidRuntime: VM exiting with result code 0.
,11-21 17:44:25.883   930   953 I ActivityManager: Start proc 5876:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
11-21 17:44:25.884   930   953 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,11-21 17:44:25.891  5697  5697 D BluetoothMapAppObserver: onReceive
,11-21 17:44:25.891  5697  5697 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,11-21 17:44:25.894  4082  4156 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
11-21 17:44:25.898   930  2945 I InputReader: Reconfiguring input devices.  changes=0x00000010
11-21 17:44:25.900  3652  3652 I Keyboard.Facilitator: resetDictionaries() : en_US
,11-21 17:44:25.917  3652  5886 I Keyboard.Facilitator.DecoderInitializer: run()
,11-21 17:44:25.925  3652  5886 I Decoder : createOrResetDecoder
,11-21 17:44:25.944  3752  3752 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,11-21 17:44:25.970  3388  5891 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,11-21 17:44:25.978  3544  3544 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,11-21 17:44:25.978  3544  3544 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
11-21 17:44:25.979    28    28 W kworker/2:1: type=1400 audit(0.0:130): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-21 17:44:25.982    28    28 W kworker/2:1: type=1400 audit(0.0:131): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-21 17:44:25.985   930   930 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,11-21 17:44:25.985    28    28 W kworker/2:1: type=1400 audit(0.0:132): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-21 17:44:25.995   930   942 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
11-21 17:44:25.995  3779  3876 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,11-21 17:44:25.995   930   942 E PackageManager: Failed to write settings, restoring backup
11-21 17:44:25.995   930   942 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
11-21 17:44:25.995   930   942 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
11-21 17:44:25.995   930   942 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
11-21 17:44:25.995   930   942 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
11-21 17:44:25.995   930   942 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
11-21 17:44:25.995   930   942 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-21 17:44:25.995   930   942 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
11-21 17:44:25.995   930   942 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-21 17:44:25.999   930   943 E DropBoxManagerService: Can't write: system_server_wtf
11-21 17:44:25.999   930   943 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
11-21 17:44:25.999   930   943 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-21 17:44:25.999   930   943 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-21 17:44:25.999   930   943 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-21 17:44:25.999   930   943 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-21 17:44:25.999   930   943 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-21 17:44:25.999   930   943 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-21 17:44:25.999   930   943 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12561)
11-21 17:44:25.999   930   943 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12374)
11-21 17:44:25.999   930   943 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12346)
11-21 17:44:25.999   930   943 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
11-21 17:44:25.999   930   943 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-21 17:44:25.999   930   943 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
11-21 17:44:25.999   930   943 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-21 17:44:25.999   930   943 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
11-21 17:44:25.999   930   943 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-21 17:44:25.999   930   943 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-21 17:44:25.999   930   943 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-21 17:44:25.999   930   943 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-21 17:44:25.999   930   943 E DropBoxManagerService: 	... 13 more
,11-21 17:44:26.008   930  3091 I ActivityManager: Start proc 5896:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
11-21 17:44:26.009  3779  3876 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
11-21 17:44:26.009  3779  3876 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3779
11-21 17:44:26.009  3779  3876 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-21 17:44:26.009  3779  3876 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-21 17:44:26.009  3779  3876 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-21 17:44:26.009  3779  3876 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-21 17:44:26.009  3779  3876 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-21 17:44:26.009  3779  3876 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-21 17:44:26.009  3779  3876 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
11-21 17:44:26.009  3779  3876 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
11-21 17:44:26.009  3779  3876 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
11-21 17:44:26.009  3779  3876 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-21 17:44:26.009  3779  3876 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-21 17:44:26.009  3779  3876 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-21 17:44:26.013  3544  3544 I ConfigService: onCreate
,11-21 17:44:26.016   930  5904 E DropBoxManagerService: Can't write: system_app_crash
11-21 17:44:26.016   930  5904 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop112.tmp: open failed: EROFS (Read-only file system)
11-21 17:44:26.016   930  5904 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-21 17:44:26.016   930  5904 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-21 17:44:26.016   930  5904 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-21 17:44:26.016   930  5904 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-21 17:44:26.016   930  5904 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-21 17:44:26.016   930  5904 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-21 17:44:26.016   930  5904 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-21 17:44:26.016   930  5904 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-21 17:44:26.016   930  5904 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-21 17:44:26.016   930  5904 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-21 17:44:26.016   930  5904 E DropBoxManagerService: 	... 5 more
,11-21 17:44:26.016  3544  5907 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
11-21 17:44:26.016  3544  5907 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-21 17:44:26.016  3544  5907 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-21 17:44:26.016  3544  5907 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-21 17:44:26.016  3544  5907 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-21 17:44:26.016  3544  5907 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-21 17:44:26.016  3544  5907 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-21 17:44:26.016  3544  5907 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-21 17:44:26.016  3544  5907 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-21 17:44:26.016  3544  5907 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-21 17:44:26.016  3544  5907 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-21 17:44:26.016  3544  5907 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-21 17:44:26.016  3544  5907 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-21 17:44:26.016  3544  5907 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-21 17:44:26.016  3544  5907 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-21 17:44:26.016  3544  5907 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
11-21 17:44:26.016  3544  5907 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
11-21 17:44:26.016  3544  5907 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
11-21 17:44:26.016   930  3521 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
11-21 17:44:26.017  3544  5907 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
11-21 17:44:26.017  3544  5907 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-21 17:44:26.017  3544  5907 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-21 17:44:26.017  3544  5907 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-21 17:44:26.017  3544  5907 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-21 17:44:26.017  3544  5907 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-21 17:44:26.017  3544  5907 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-21 17:44:26.017  3544  5907 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-21 17:44:26.017  3544  5907 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-21 17:44:26.017  3544  5907 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-21 17:44:26.017  3544  5907 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-21 17:44:26.017  3544  5907 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-21 17:44:26.017  3544  5907 E ,SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-21 17:44:26.017  3544  5907 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-21 17:44:26.017  3544  5907 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-21 17:44:26.017  3544  5907 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
11-21 17:44:26.017  3544  5907 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
11-21 17:44:26.017  3544  5907 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
11-21 17:44:26.017  3920  5906 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
11-21 17:44:26.018  3920  5906 D AccountUtils: Clearing selected account for com.test.thalitest
11-21 17:44:26.019  3388  5891 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
11-21 17:44:26.019  3544  5907 W SQLiteOpenHelper: Opened config.db in read-only mode
11-21 17:44:26.019  3946  3966 W SearchService: Abort, client detached.
11-21 17:44:26.022  3946  3946 I HotwordDetector: Closing mic
11-21 17:44:26.022  3946  4157 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@5b71717
11-21 17:44:26.023  3946  5860 E AudioRecord-JNI: Error -4 during AudioRecord native read
11-21 17:44:26.024  3388  5891 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
11-21 17:44:26.024  3388  5891 E AndroidRuntime: Process: android.process.acore, PID: 3388
11-21 17:44:26.024  3388  5891 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-21 17:44:26.024  3388  5891 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-21 17:44:26.024  3388  5891 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-21 17:44:26.024  3388  5891 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-21 17:44:26.024  3388  5891 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-21 17:44:26.024  3388  5891 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-21 17:44:26.024  3388  5891 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
11-21 17:44:26.024  3388  5891 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
11-21 17:44:26.024  3388  5891 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
11-21 17:44:26.024  3388  5891 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
11-21 17:44:26.024  3388  5891 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
11-21 17:44:26.024  3388  5891 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
11-21 17:44:26.024  3388  5891 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
11-21 17:44:26.024  3388  5891 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-21 17:44:26.024  3388  5891 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-21 17:44:26.024  3388  5891 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-21 17:44:26.024  3388  5891 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-21 17:44:26.025   769   769 W Binder_3: type=1400 audit(0.0:133): avc: denied { ioctl } for path="socket:[32917]" dev="sockfs" ino=32917 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-21 17:44:26.029   769   769 W Binder_3: type=1400 audit(0.0:134): avc: denied { ioctl } for path="socket:[32917]" dev="sockfs" ino=32917 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-21 17:44:26.032   930  5912 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
11-21 17:44:26.029   410   410 W Binder_2: type=1400 audit(0.0:135): avc: denied { ioctl } for path="socket:[35957]" dev="sockfs" ino=35957 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-21 17:44:26.029   410   410 W Binder_2: type=1400 audit(0.0:136): avc: denied { ioctl } for path="socket:[35957]" dev="sockfs" ino=35957 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-21 17:44:26.052  3920  5906 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
11-21 17:44:26.052   930  5915 E DropBoxManagerService: Can't write: system_app_crash
11-21 17:44:26.052   930  5915 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop115.tmp: open failed: EROFS (Read-only file system)
11-21 17:44:26.052   930  5915 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-21 17:44:26.052   930  5915 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-21 17:44:26.052   930  5915 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-21 17:44:26.052   930  5915 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-21 17:44:26.052   930  5915 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-21 17:44:26.052   930  5915 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-21 17:44:26.052   930  5915 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-21 17:44:26.052   930  5915 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-21 17:44:26.052   930  5915 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-21 17:44:26.052   930  5915 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-21 17:44:26.052   930  5915 E DropBoxManagerService: 	... 5 more
11-21 17:44:26.067  3652  5886 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,11-21 17:44:26.092  3920  5906 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
11-21 17:44:26.092  3920  5906 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-21 17:44:26.092  3920  5906 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-21 17:44:26.092  3920  5906 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-21 17:44:26.092  3920  5906 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-21 17:44:26.092  3920  5906 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-21 17:44:26.092  3920  5906 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-21 17:44:26.092  3920  5906 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-21 17:44:26.092  3920  5906 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-21 17:44:26.092  3920  5906 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-21 17:44:26.092  3920  5906 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-21 17:44:26.092  3920  5906 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-21 17:44:26.092  3920  5906 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-21 17:44:26.092  3920  5906 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-21 17:44:26.092  3920  5906 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-21 17:44:26.092  3920  5906 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-21 17:44:26.092  3920  5906 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
11-21 17:44:26.092  3920  5906 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-21 17:44:26.092  3920  5906 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-21 17:44:26.092  3920  5906 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
11-21 17:44:26.092  3920  5906 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-21 17:44:26.093  3920  5906 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
11-21 17:44:26.093  3920  5906 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-21 17:44:26.093  3920  5906 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-21 17:44:26.093  3920  5906 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-21 17:44:26.093  3920  5906 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-21 17:44:26.093  3920  5906 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-21 17:44:26.093  3920  5906 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-21 17:44:26.093  3920  5906 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-21 17:44:26.093  3920  5906 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-21 17:44:26.093  3920  5906 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-21 17:44:26.093  3920  5906 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-21 17:44:26.093  3920  5906 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-21 17:44:26.093  3920  5906 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-21 17:44:26.093  3920  5906 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-21 17:44:26.093  3920  5906 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-21 17:44:26.093  3920  5906 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-21 17:44:26.093  3920  5906 E SQLiteOpenHelper: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
11-21 17:44:26.093  3920  5906 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-21 17:44:26.093  3920  5906 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-21 17:44:26.093  3920  5906 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
11-21 17:44:26.093  3920  5906 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-21 17:44:26.094  3920  5906 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
11-21 17:44:26.097   514  5862 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
,11-21 17:44:26.098   514  5862 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
11-21 17:44:26.103   514  5862 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
11-21 17:44:26.103   514  5862 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
11-21 17:44:26.104   514  2983 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,11-21 17:44:26.109  3946  5859 I MicroRecognitionRnrImpl: Detection finished
,11-21 17:44:26.110  3946  4158 I MicroRecognitionRnrImpl: Stopping hotword detection.
,11-21 17:44:26.197  3920  5923 I GMPM-SVC: App measurement is starting up
,11-21 17:44:26.205  3920  5923 E GMPM-SVC: AppMeasurementService not registered/enabled
11-21 17:44:26.205  3920  5923 E GMPM-SVC: Uploading is not possible. App measurement disabled
,11-21 17:44:26.318   537   537 I ServiceManager: Waiting for service AtCmdFwd...

```
