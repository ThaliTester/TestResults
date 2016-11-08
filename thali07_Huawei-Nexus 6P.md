#### Test 896247960fcbde9_thali07_Huawei-Nexus 6P Logs


```
--------- beginning of main
11-08 11:17:00.663  3890  4111 I Icing   : Indexing 3C763AF371F9E97B4ECFEA01A338ADB468C38476 from com.google.android.googlequicksearchbox
,11-08 11:17:00.734  3890  4111 I Icing   : Indexing done 3C763AF371F9E97B4ECFEA01A338ADB468C38476
11-08 11:17:01.106  5535  5535 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-08 11:17:01.112  5535  5535 D AndroidRuntime: CheckJNI is OFF
11-08 11:17:01.140  5535  5535 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-08 11:17:01.169  5535  5535 I Radio-JNI: register_android_hardware_Radio DONE
11-08 11:17:01.184  5535  5535 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
11-08 11:17:01.187   934  3515 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
11-08 11:17:01.205  5535  5535 D AndroidRuntime: Shutting down VM
11-08 11:17:01.210  3871  3883 W SearchService: Abort, client detached.
11-08 11:17:01.218  3871  3871 I HotwordDetector: Closing mic
11-08 11:17:01.218  3871  4095 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@2541f35
11-08 11:17:01.219  3871  4113 E AudioRecord-JNI: Error -4 during AudioRecord native read
11-08 11:17:01.235   934  3068 I ActivityManager: Start proc 5544:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
11-08 11:17:01.304   515  4115 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
11-08 11:17:01.305   515  4115 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
11-08 11:17:01.309   515  4115 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
11-08 11:17:01.309   515  4115 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
11-08 11:17:01.309   515  2923 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-08 11:17:01.310  3871  4102 I MicroRecognitionRnrImpl: Stopping hotword detection.
11-08 11:17:01.311  3871  4112 I MicroRecognitionRnrImpl: Detection finished
11-08 11:17:01.328  5544  5544 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
11-08 11:17:01.347  5544  5544 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
11-08 11:17:01.407  5544  5544 I LibraryLoader: Time to load native libraries: 56 ms (timestamps 5203-5259)
11-08 11:17:01.407  5544  5544 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-08 11:17:01.435  5544  5544 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {259ca3c}
11-08 11:17:01.435  5544  5544 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-08 11:17:01.435  5544  5544 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,11-08 11:17:01.439  5544  5544 I BrowserStartupController: Initializing chromium process, singleProcess=true
,11-08 11:17:01.439  5544  5544 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-08 11:17:01.495  5544  5544 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-08 11:17:01.508  5544  5544 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-08 11:17:01.509  5544  5544 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-08 11:17:01.509  5544  5544 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-08 11:17:01.509  5544  5544 I Adreno  : Build Date                       : 12/06/15
11-08 11:17:01.509  5544  5544 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-08 11:17:01.509  5544  5544 I Adreno  : Local Branch                     : mybranch17112971
11-08 11:17:01.509  5544  5544 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-08 11:17:01.509  5544  5544 I Adreno  : Remote Branch                    : NONE
11-08 11:17:01.509  5544  5544 I Adreno  : Reconstruct Branch               : NOTHING
,11-08 11:17:01.546   934   951 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6669ee4:true
,11-08 11:17:01.577   406   406 W Binder_1: type=1400 audit(0.0:99): avc: denied { ioctl } for path="socket:[16257]" dev="sockfs" ino=16257 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-08 11:17:01.577   406   406 W Binder_1: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[16257]" dev="sockfs" ino=16257 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-08 11:17:01.589  5544  5544 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-08 11:17:01.598  5544  5544 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-08 11:17:01.627   408   408 W Binder_2: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[32415]" dev="sockfs" ino=32415 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-08 11:17:01.627   408   408 W Binder_2: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[32415]" dev="sockfs" ino=32415 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-08 11:17:01.627  5544  5581 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-08 11:17:01.630  3515  3515 W Binder_6: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[16268]" dev="sockfs" ino=16268 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-08 11:17:01.630  3515  3515 W Binder_6: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[16268]" dev="sockfs" ino=16268 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-08 11:17:01.632  5544  5568 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-08 11:17:01.658  5544  5581 I OpenGLRenderer: Initialized EGL, version 1.4
,11-08 11:17:01.727  3516  3516 W Binder_7: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[32419]" dev="sockfs" ino=32419 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-08 11:17:01.730  3516  3516 W Binder_7: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[32419]" dev="sockfs" ino=32419 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-08 11:17:01.731   934   952 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +519ms
,11-08 11:17:01.734  3515  3515 W Binder_6: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[32418]" dev="sockfs" ino=32418 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-08 11:17:01.734  3515  3515 W Binder_6: type=1400 audit(0.0:108): avc: denied { ioctl } for path="socket:[32418]" dev="sockfs" ino=32418 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-08 11:17:01.735  3578  3578 I Keyboard.Facilitator: onFinishInput()
,11-08 11:17:01.775  5544  5544 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5544
,11-08 11:17:01.876  5544  5544 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,11-08 11:17:02.225  5544  5583 D jxcore_app_log: JniHelper::setJavaVM(0xf4fbc000), pthread_self() = -565708496
,11-08 11:17:02.238  5544  5583 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-08 11:17:02.238  5544  5583 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-08 11:17:02.238  5544  5583 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-08 11:17:02.238  5544  5583 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-08 11:17:02.238  5544  5583 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,11-08 11:17:02.238  5544  5583 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fff2832 added. We now have 1 listener(s)
,11-08 11:17:02.240  5544  5583 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:D4
,11-08 11:17:02.241  5544  5583 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-08 11:17:02.241  5544  5583 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-08 11:17:02.241  5544  5583 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-08 11:17:02.246  5544  5583 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-08 11:17:02.246  5544  5583 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-08 11:17:02.246  5544  5583 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-08 11:17:02.246  5544  5583 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:D4
11-08 11:17:02.246  5544  5583 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-08 11:17:02.246  5544  5583 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-08 11:17:02.246  5544  5583 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-08 11:17:02.246  5544  5583 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-08 11:17:02.246  5544  5583 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-08 11:17:02.246  5544  5583 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-08 11:17:02.246  5544  5583 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-08 11:17:02.246  5544  5583 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-08 11:17:02.246  5544  5583 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-08 11:17:02.246  5544  5583 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
11-08 11:17:02.246  5544  5583 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@85a4b39 added. We now have 1 listener(s)
,11-08 11:17:02.247  5544  5583 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-08 11:17:02.259   934  2876 D WifiService: New client listening to asynchronous messages
,11-08 11:17:02.265  5544  5583 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-08 11:17:02.266  5544  5583 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
11-08 11:17:02.266  5544  5583 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,11-08 11:17:02.266  5544  5583 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
11-08 11:17:02.267  5544  5583 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,11-08 11:17:02.270  5544  5583 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-08 11:17:02.270  5544  5583 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-08 11:17:02.285  5544  5583 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
11-08 11:17:02.285  5544  5583 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-08 11:17:02.285  5544  5583 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 11:17:02.285  5544  5583 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 11:17:02.285  5544  5583 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 11:17:02.285  5544  5583 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 11:17:02.285  5544  5583 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-08 11:17:02.285  5544  5583 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-08 11:17:02.285  5544  5583 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-08 11:17:02.285  5544  5583 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,11-08 11:17:02.285  5544  5583 D io.jxcore.node.ConnectivityMonitor: start: OK
,11-08 11:17:02.286  5544  5583 I io.jxcore.node.LifeCycleMonitor: start: OK
11-08 11:17:02.290  5544  5544 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 11:17:02.296  5544  5544 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 11:17:02.510  5544  5544 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,11-08 11:17:02.756  5544  5592 W jxcore-log: Initializing JXcore engine
11-08 11:17:02.756  5544  5592 W jxcore-log: JXcore engine is ready
,11-08 11:17:02.780  5592  5592 W Thread-66: type=1400 audit(0.0:109): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12426 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,11-08 11:17:02.780  5592  5592 W Thread-66: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[14441]" dev="sockfs" ino=14441 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,11-08 11:17:02.780  5592  5592 W Thread-66: type=1400 audit(0.0:111): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=696 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
11-08 11:17:02.780  5592  5592 W Thread-66: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[30397]" dev="sockfs" ino=30397 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,11-08 11:17:02.789  5544  5592 W jxcore-log: Starting JXcore engine
,11-08 11:17:02.845  5544  5592 W jxcore-log: Platform android
11-08 11:17:02.845  5544  5592 W jxcore-log: 
,11-08 11:17:02.845  5544  5592 W jxcore-log: Process ARCH arm
11-08 11:17:02.845  5544  5592 W jxcore-log: 
,11-08 11:17:02.984  5544  5592 I jxcore-log: JXcore Cordova bridge is ready!
11-08 11:17:02.984  5544  5592 I jxcore-log: 
,11-08 11:17:02.985  5544  5592 W jxcore-log: JXcore engine is started
,11-08 11:17:02.994  5544  5583 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,11-08 11:17:02.999  5544  5544 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-08 11:17:04.815  3502  3502 I ConfigService: onDestroy
,11-08 11:17:06.228   934  3068 I ActivityManager: Killing 4989:com.google.android.apps.maps/u0a58 (adj 15): empty #17
,11-08 11:17:07.726   934  2875 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-08 11:17:10.149   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 11:17:11.150   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 11:17:11.263   934  2865 I ActivityManager: Killing 5336:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17,
,11-08 11:17:11.479   934  2876 D WifiService: New client listening to asynchronous messages
,11-08 11:17:11.483  3871  5593 W CronetSyncConnectionRcs: Upload content type not set.
,11-08 11:17:12.151   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 11:17:12.640  5544  5592 I jxcore-log: 2016-11-08 10:17:12 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-08 11:17:12.640  5544  5592 I jxcore-log: 
,11-08 11:17:12.642  5544  5592 I jxcore-log: 2016-11-08 10:17:12 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-08 11:17:12.642  5544  5592 I jxcore-log: 
,11-08 11:17:12.646  5544  5592 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-08 11:17:12.646  5544  5592 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 11:17:12.646  5544  5592 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 11:17:12.646  5544  5592 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 11:17:12.646  5544  5592 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 11:17:12.646  5544  5592 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-08 11:17:12.646  5544  5592 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-08 11:17:12.646  5544  5592 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-08 11:17:12.648  5544  5592 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-08 11:17:12.649  5544  5592 I jxcore-log: 2016-11-08 10:17:12 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
11-08 11:17:12.649  5544  5592 I jxcore-log: 
,11-08 11:17:12.651  5544  5592 I jxcore-log: 2016-11-08 10:17:12 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-08 11:17:12.651  5544  5592 I jxcore-log: 
,11-08 11:17:12.900  5544  5592 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-08 11:17:12.900  5544  5592 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a02c59f added. We now have 2 listener(s)
,11-08 11:17:12.901  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-08 11:17:12.901  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-08 11:17:12.901  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-08 11:17:12.901  5544  5592 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-08 11:17:12.901  5544  5592 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35ec6ec added. We now have 2 listener(s)
,11-08 11:17:12.902  5544  5592 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-08 11:17:12.902  5544  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-08 11:17:12.904  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-08 11:17:12.907  5544  5592 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-08 11:17:12.907  5544  5592 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 11:17:12.907  5544  5592 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 11:17:12.907  5544  5592 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 11:17:12.907  5544  5592 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 11:17:12.907  5544  5592 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-08 11:17:12.907  5544  5592 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-08 11:17:12.907  5544  5592 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-08 11:17:12.908  5544  5592 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-08 11:17:12.908  5544  5592 D io.jxcore.node.ConnectivityMonitor: start: OK
11-08 11:17:12.909  5544  5592 D ExecuteNativeTests: Running unit tests
11-08 11:17:12.909  5544  5592 D BluetoothAdapter: enable(): BT is already enabled..!
11-08 11:17:12.909   934   944 D WifiService: setWifiEnabled: true pid=5544, uid=10077
11-08 11:17:12.909   934   944 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-08 11:17:12.915  5544  5544 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 11:17:12.921  5544  5544 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 11:17:13.153   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 11:17:14.154   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 11:17:14.449  4801  4847 D Finsky  : [188] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,11-08 11:17:14.450  4801  4801 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,11-08 11:17:15.155   546   546 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-08 11:17:22.915  5544  5592 I com.test.thalitest.ThaliTestRunner: Running UT
,11-08 11:17:22.982  5544  5592 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-08 11:17:22.983  5544  5592 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@779889e added. We now have 3 listener(s)
,11-08 11:17:22.984  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-08 11:17:22.984  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-08 11:17:22.984  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-08 11:17:22.984  5544  5592 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-08 11:17:22.984  5544  5592 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e937f7f added. We now have 3 listener(s)
11-08 11:17:22.984  5544  5592 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-08 11:17:22.985  5544  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-08 11:17:22.988  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-08 11:17:22.993  5544  5592 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-08 11:17:22.993  5544  5592 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 11:17:22.993  5544  5592 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 11:17:22.993  5544  5592 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 11:17:22.993  5544  5592 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 11:17:22.993  5544  5592 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-08 11:17:22.993  5544  5592 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-08 11:17:22.993  5544  5592 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-08 11:17:22.994  5544  5592 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-08 11:17:22.994  5544  5592 D io.jxcore.node.ConnectivityMonitor: start: OK
,11-08 11:17:22.999  5544  5592 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionTimeout
11-08 11:17:22.999  5544  5592 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-08 11:17:23.000  5544  5592 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-08 11:17:23.000  5544  5592 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-08 11:17:23.000  5544  5592 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-08 11:17:23.001  5544  5592 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
11-08 11:17:23.001  5544  5592 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,11-08 11:17:23.001  5544  5592 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-08 11:17:23.002  5544  5592 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-08 11:17:23.002  5544  5592 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-08 11:17:23.002  5544  5592 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-08 11:17:23.002  5544  5592 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnBluetoothMacAddressResolved
11-08 11:17:23.003  5544  5592 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,11-08 11:17:23.004  5544  5592 I io.jxcore.node.ConnectionHelperTest: Starting test: testHasMaximumNumberOfConnections
11-08 11:17:23.005  5544  5592 I io.jxcore.node.ConnectionHelperTest: Starting test: testStart
11-08 11:17:23.005  5544  5592 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,11-08 11:17:23.009  5544  5544 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 11:17:23.009  5544  5592 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-08 11:17:23.009  5544  5592 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
,11-08 11:17:23.009  5544  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
11-08 11:17:23.009  5544  5592 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-08 11:17:23.009  5544  5592 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-08 11:17:23.010  5544  5592 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-08 11:17:23.010  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-08 11:17:23.011  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-08 11:17:23.013  5544  5592 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-08 11:17:23.014  5544  5592 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-08 11:17:23.014  5544  5592 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-08 11:17:23.014  5544  5592 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-08 11:17:23.014  5544  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-08 11:17:23.014  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-08 11:17:23.014  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-08 11:17:23.016  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-08 11:17:23.016  5544  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,11-08 11:17:23.016  5544  5592 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-08 11:17:23.016  5544  5592 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-08 11:17:23.018  5544  5544 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 11:17:23.018  5544  5544 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,11-08 11:17:23.019  5544  5606 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-08 11:17:23.020  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-08 11:17:23.022  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-08 11:17:23.022  5544  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,11-08 11:17:23.020  4620  4620 W Binder_1: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[16280]" dev="sockfs" ino=16280 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-08 11:17:23.020  4620  4620 W Binder_1: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[16280]" dev="sockfs" ino=16280 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-08 11:17:23.022  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,11-08 11:17:23.023  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:23.023  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-08 11:17:23.023  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-08 11:17:23.023  5544  5592 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 60 83 34 25 D7 D4
11-08 11:17:23.024  5544  5592 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-08 11:17:23.024  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:23.024  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:23.024  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-66,5,main], id: 66
,11-08 11:17:23.024  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:23.024  5544  5592 D BluetoothAdapter: STATE_ON
11-08 11:17:23.028  4608  4823 D BtGatt.GattService: registerClient() - UUID=c8710f0a-295b-4ae7-b303-dbecd4d19184
11-08 11:17:23.028  4608  4679 D BtGatt.GattService: onClientRegistered() - UUID=c8710f0a-295b-4ae7-b303-dbecd4d19184, clientIf=5
11-08 11:17:23.029  5544  5584 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-08 11:17:23.031  4608  4682 D BtGatt.AdvertiseManager: message : 0
,11-08 11:17:23.034  4608  4682 D BtGatt.AdvertiseManager: starting multi advertising
,11-08 11:17:23.048  4608  4679 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-08 11:17:23.055  4608  4679 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-08 11:17:23.057  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:23.057  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:23.057  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-08 11:17:23.057  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:23.057  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:23.057  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-66,5,main], id: 66
,11-08 11:17:23.057  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:23.057  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:23.057  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-08 11:17:23.058  5544  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-08 11:17:23.058  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:23.058  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:23.058  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-66,5,main], id: 66
,11-08 11:17:23.058  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:23.059  5544  5592 I io.jxcore.node.ConnectionHelper: start: OK
,11-08 11:17:23.059  5544  5544 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-08 11:17:23.059  5544  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-08 11:17:23.059  5544  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-08 11:17:23.059  5544  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-08 11:17:23.059  5544  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged true. Current thread: Thread[main,5,main], id: 1
,11-08 11:17:23.060  5544  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-08 11:17:23.060  5544  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-08 11:17:23.060  5544  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-08 11:17:23.060  5544  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,11-08 11:17:23.060  5544  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-08 11:17:23.060  5544  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-08 11:17:23.060  5544  5544 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-08 11:17:23.060  5544  5544 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-08 11:17:23.064  5544  5544 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-08 11:17:23.064  5544  5544 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-08 11:17:23.064  5544  5544 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-08 11:17:23.064  5544  5544 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-08 11:17:23.064  5544  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-08 11:17:23.064  5544  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-08 11:17:23.065  5544  5544 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-08 11:17:23.562  5544  5592 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-08 11:17:23.562  5544  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,11-08 11:17:23.562  5544  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-08 11:17:23.562  5544  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-08 11:17:23.562  5544  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-08 11:17:23.563  5544  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-08 11:17:23.563  5544  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-08 11:17:23.563  5544  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-08 11:17:23.563  5544  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-08 11:17:23.563  5544  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-08 11:17:23.563  5544  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-08 11:17:23.563  5544  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-08 11:17:23.563  5544  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-08 11:17:23.563  5544  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-08 11:17:23.563  5544  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-08 11:17:23.564  5544  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-08 11:17:23.564  5544  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-08 11:17:23.564  5544  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-08 11:17:23.564  5544  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,11-08 11:17:23.564  5544  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-08 11:17:23.564  5544  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-08 11:17:23.564  5544  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-08 11:17:23.564  5544  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-08 11:17:23.564  5544  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-08 11:17:23.564  5544  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-08 11:17:23.565  5544  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-08 11:17:23.565  5544  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-08 11:17:23.565  5544  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,11-08 11:17:23.565  5544  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-08 11:17:23.565  5544  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-08 11:17:23.565  5544  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-08 11:17:23.565  5544  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,11-08 11:17:23.565  5544  5592 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-08 11:17:23.565  5544  5592 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
11-08 11:17:23.566  5544  5592 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-08 11:17:23.566  5544  5592 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-08 11:17:23.566  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-08 11:17:23.566  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-08 11:17:23.566  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
11-08 11:17:23.566  5544  5592 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-08 11:17:23.566  5544  5592 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-08 11:17:23.567  5544  5592 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-08 11:17:23.567  5544  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-08 11:17:23.567  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-08 11:17:23.567  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-08 11:17:23.567  5544  5544 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-08 11:17:23.567  5544  5606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-08 11:17:23.567  5544  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-08 11:17:23.568  5544  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-08 11:17:23.568  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:23.568  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:23.569  5544  5592 D BluetoothAdapter: STATE_ON
11-08 11:17:23.570  5544  5592 D BluetoothLeScanner: could not find callback wrapper
11-08 11:17:23.570  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-08 11:17:23.570  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:23.570  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:23.570  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,11-08 11:17:23.571  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:23.572  4608  4682 D BtGatt.AdvertiseManager: message : 1
11-08 11:17:23.573  4608  4682 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-08 11:17:23.588  4608  4679 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-08 11:17:23.589  4608  4679 D BtGatt.GattService: Client app is not null!
,11-08 11:17:23.590  4608  4815 D BtGatt.GattService: unregisterClient() - clientIf=5
11-08 11:17:23.591  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-08 11:17:23.591  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-66,5,main], id: 66
,11-08 11:17:23.591  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-08 11:17:23.592  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged false. Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:23.592  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:23.592  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-66,5,main], id: 66
,11-08 11:17:23.592  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-08 11:17:23.592  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-08 11:17:23.592  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:23.592  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[Thread-66,5,main], id: 66
,11-08 11:17:23.592  5544  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-08 11:17:23.592  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:23.594  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:23.594  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-08 11:17:23.594  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-66,5,main], id: 66
,11-08 11:17:23.594  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:23.594  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:23.594  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:23.594  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:23.594  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-08 11:17:23.595  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-08 11:17:23.595  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
11-08 11:17:23.595  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:23.597  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-66,5,main], id: 66
,11-08 11:17:23.597  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-66,5,main], id: 66
,11-08 11:17:23.597  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:23.597  5544  5544 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-08 11:17:23.597  5544  5544 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-08 11:17:23.598  5544  5544 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-08 11:17:23.599  5544  5544 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-08 11:17:23.599  5544  5544 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-08 11:17:23.599  5544  5592 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-08 11:17:23.599  5544  5544 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-08 11:17:23.599  5544  5592 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-08 11:17:23.599  5544  5544 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-08 11:17:23.599  5544  5592 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
,11-08 11:17:23.599  5544  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
11-08 11:17:23.599  5544  5544 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-08 11:17:23.599  5544  5592 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-08 11:17:23.599  5544  5592 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-08 11:17:23.600  5544  5592 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-08 11:17:23.600  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-08 11:17:23.601  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-08 11:17:23.602  5544  5592 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-08 11:17:23.602  5544  5592 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-08 11:17:23.602  5544  5592 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-08 11:17:23.602  5544  5592 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-08 11:17:23.602  5544  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,11-08 11:17:23.602  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-08 11:17:23.602  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-08 11:17:23.602  5544  5544 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,11-08 11:17:23.612  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-08 11:17:23.613  5544  5592 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-08 11:17:23.613  5544  5592 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-08 11:17:23.615  5544  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,11-08 11:17:23.616  5544  5609 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-08 11:17:23.618  5544  5609 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,11-08 11:17:23.617  4823  4823 W Binder_4: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[32896]" dev="sockfs" ino=32896 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-08 11:17:23.617  4823  4823 W Binder_4: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[32896]" dev="sockfs" ino=32896 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-08 11:17:23.618  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-08 11:17:23.619  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-08 11:17:23.619  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,11-08 11:17:23.622  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:23.623  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-08 11:17:23.623  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-08 11:17:23.623  5544  5592 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 60 83 34 25 D7 D4
11-08 11:17:23.623  5544  5592 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-08 11:17:23.623  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:23.623  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:23.623  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:23.623  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-66,5,main], id: 66
,11-08 11:17:23.624  5544  5592 D BluetoothAdapter: STATE_ON
11-08 11:17:23.627  4608  4815 D BtGatt.GattService: registerClient() - UUID=76530b8a-b067-4615-b5d5-27cb4642a533
11-08 11:17:23.628  4608  4679 D BtGatt.GattService: onClientRegistered() - UUID=76530b8a-b067-4615-b5d5-27cb4642a533, clientIf=5
11-08 11:17:23.628  5544  5555 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-08 11:17:23.629  4608  4682 D BtGatt.AdvertiseManager: message : 0
11-08 11:17:23.632  4608  4682 D BtGatt.AdvertiseManager: starting multi advertising
11-08 11:17:23.644  4608  4679 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
11-08 11:17:23.650  4608  4679 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
11-08 11:17:23.650  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:23.650  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:23.650  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-08 11:17:23.650  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:23.650  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:23.651  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:23.651  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:23.651  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:23.651  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-08 11:17:23.652  5544  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-08 11:17:23.652  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:23.653  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:23.653  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:23.653  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:23.653  5544  5592 I io.jxcore.node.ConnectionHelper: start: OK
11-08 11:17:23.653  5544  5544 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-08 11:17:23.654  5544  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-08 11:17:23.654  5544  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-08 11:17:23.654  5544  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-08 11:17:23.654  5544  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged true. Current thread: Thread[main,5,main], id: 1
11-08 11:17:23.654  5544  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-08 11:17:23.654  5544  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-08 11:17:23.654  5544  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-08 11:17:23.654  5544  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-08 11:17:23.654  5544  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-08 11:17:23.654  5544  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-08 11:17:23.654  5544  5544 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-08 11:17:23.654  5544  5544 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-08 11:17:23.657  5544  5544 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-08 11:17:23.657  5544  5544 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-08 11:17:23.657  5544  5544 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-08 11:17:23.657  5544  5544 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-08 11:17:23.657  5544  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-08 11:17:23.657  5544  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-08 11:17:23.657  5544  5544 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-08 11:17:24.158  5544  5592 I io.jxcore.node.ConnectionHelperTest: Starting test: testStop
,11-08 11:17:24.158  5544  5592 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-08 11:17:24.158  5544  5592 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-08 11:17:24.158  5544  5592 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-08 11:17:24.158  5544  5592 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
,11-08 11:17:24.159  5544  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
11-08 11:17:24.159  5544  5544 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-08 11:17:24.159  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
11-08 11:17:24.159  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
11-08 11:17:24.159  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
11-08 11:17:24.159  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 3
11-08 11:17:24.159  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
11-08 11:17:24.159  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
11-08 11:17:24.159  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
11-08 11:17:24.159  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
11-08 11:17:24.159  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
11-08 11:17:24.159  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:24.161  4608  4682 D BtGatt.AdvertiseManager: message : 1
11-08 11:17:24.163  4608  4682 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-08 11:17:24.177  4608  4679 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,11-08 11:17:24.177  4608  4679 D BtGatt.GattService: Client app is not null!
11-08 11:17:24.178  4608  4621 D BtGatt.GattService: unregisterClient() - clientIf=5
11-08 11:17:24.179  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-08 11:17:24.179  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:24.179  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,11-08 11:17:24.180  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-66,5,main], id: 66
,11-08 11:17:24.181  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-66,5,main], id: 66
,11-08 11:17:24.181  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-08 11:17:24.181  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-66,5,main], id: 66
,11-08 11:17:24.181  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-08 11:17:24.181  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-08 11:17:24.182  5544  5592 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 60 83 34 25 D7 D4
11-08 11:17:24.182  5544  5592 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-08 11:17:24.182  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:24.183  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:24.183  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:24.183  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:24.184  5544  5592 D BluetoothAdapter: STATE_ON
11-08 11:17:24.189  4608  4823 D BtGatt.GattService: registerClient() - UUID=a3b2bd73-3d52-469d-8b0d-3dfdb8be8a14
11-08 11:17:24.190  4608  4679 D BtGatt.GattService: onClientRegistered() - UUID=a3b2bd73-3d52-469d-8b0d-3dfdb8be8a14, clientIf=5
,11-08 11:17:24.190  5544  5554 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-08 11:17:24.192  4608  4682 D BtGatt.AdvertiseManager: message : 0
,11-08 11:17:24.197  4608  4682 D BtGatt.AdvertiseManager: starting multi advertising
,11-08 11:17:24.213  4608  4679 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-08 11:17:24.222  4608  4679 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-08 11:17:24.223  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:24.223  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:24.224  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,11-08 11:17:24.224  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:24.224  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:24.224  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:24.224  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:24.224  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[Thread-66,5,main], id: 66
,11-08 11:17:24.225  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-08 11:17:24.225  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-08 11:17:24.225  5544  5592 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-08 11:17:24.225  5544  5592 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-08 11:17:24.225  5544  5592 I io.jxcore.node.ConnectionHelper: start: OK
11-08 11:17:24.225  5544  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-08 11:17:24.226  5544  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
,11-08 11:17:24.226  5544  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-08 11:17:24.226  5544  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged true. Current thread: Thread[main,5,main], id: 1
11-08 11:17:24.226  5544  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-08 11:17:24.226  5544  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-08 11:17:24.226  5544  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
,11-08 11:17:24.226  5544  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-08 11:17:24.226  5544  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-08 11:17:24.226  5544  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-08 11:17:24.227  5544  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-08 11:17:24.227  5544  5592 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-08 11:17:24.227  5544  5592 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,11-08 11:17:24.227  5544  5592 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-08 11:17:24.227  5544  5592 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-08 11:17:24.227  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-08 11:17:24.227  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-08 11:17:24.228  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,11-08 11:17:24.228  5544  5609 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-08 11:17:24.228  5544  5592 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-08 11:17:24.228  5544  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-08 11:17:24.228  5544  5592 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-08 11:17:24.228  5544  5609 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,11-08 11:17:24.228  5544  5544 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-08 11:17:24.229  5544  5592 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-08 11:17:24.230  5544  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-08 11:17:24.230  5544  5544 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-08 11:17:24.230  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-08 11:17:24.230  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-08 11:17:24.230  5544  5544 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-08 11:17:24.230  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:24.230  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:24.231  5544  5592 D BluetoothAdapter: STATE_ON
11-08 11:17:24.231  5544  5592 D BluetoothLeScanner: could not find callback wrapper
,11-08 11:17:24.231  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-08 11:17:24.231  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:24.232  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:24.232  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-08 11:17:24.232  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:24.233  4608  4682 D BtGatt.AdvertiseManager: message : 1
11-08 11:17:24.233  4608  4682 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-08 11:17:24.242  4608  4679 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,11-08 11:17:24.242  4608  4679 D BtGatt.GattService: Client app is not null!
,11-08 11:17:24.243  4608  4823 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-08 11:17:24.244  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-08 11:17:24.244  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:24.244  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,11-08 11:17:24.244  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged false. Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:24.244  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:24.244  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:24.244  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-08 11:17:24.245  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
,11-08 11:17:24.245  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:24.245  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:24.245  5544  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-08 11:17:24.245  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-66,5,main], id: 66
,11-08 11:17:24.247  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-66,5,main], id: 66
,11-08 11:17:24.247  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-08 11:17:24.247  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:24.247  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-66,5,main], id: 66
,11-08 11:17:24.247  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:24.247  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:24.247  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:24.248  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-08 11:17:24.248  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-08 11:17:24.248  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
11-08 11:17:24.248  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:24.250  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-66,5,main], id: 66
,11-08 11:17:24.250  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:24.250  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:24.250  5544  5544 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-08 11:17:24.250  5544  5544 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-08 11:17:24.250  5544  5544 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-08 11:17:24.250  5544  5544 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-08 11:17:24.250  5544  5544 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-08 11:17:24.252  5544  5592 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPeerReadyToProvideBluetoothMacAddress
11-08 11:17:24.253  5544  5592 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
11-08 11:17:24.254  5544  5592 I io.jxcore.node.ConnectionHelperTest: Starting test: testKillAllConnections
,11-08 11:17:24.255  5544  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-08 11:17:24.255  5544  5592 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionManagerStateChanged
11-08 11:17:24.255  5544  5592 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
11-08 11:17:24.256  5544  5592 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPermissionCheckRequired
11-08 11:17:24.256  5544  5592 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
11-08 11:17:24.257  5544  5592 I io.jxcore.node.ConnectionHelperTest: Starting test: testToggleBetweenSystemDecidedAndAlternativeInsecureRfcommPortNumber
11-08 11:17:24.257  5544  5592 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-08 11:17:24.257  5544  5592 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-08 11:17:24.257  5544  5592 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-08 11:17:24.257  5544  5592 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-08 11:17:24.257  5544  5592 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-08 11:17:24.258  5544  5592 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-08 11:17:24.258  5544  5592 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-08 11:17:24.258  5544  5592 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-08 11:17:24.258  5544  5592 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-08 11:17:24.258  5544  5592 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-08 11:17:24.258  5544  5592 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-08 11:17:24.258  5544  5592 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-08 11:17:24.259  5544  5592 I io.jxcore.node.ConnectionHelperTest: Starting test: testConnect
11-08 11:17:24.259  5544  5592 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-08 11:17:24.259  5544  5592 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
11-08 11:17:24.262  5544  5592 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnProvideBluetoothMacAddressRequest
11-08 11:17:24.262  5544  5592 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
11-08 11:17:24.263  5544  5592 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnDiscoveryManagerStateChanged
11-08 11:17:24.263  5544  5592 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
11-08 11:17:24.264  5544  5592 I io.jxcore.node.ConnectionHelperTest: Starting test: testDisconnectOutgoingConnection
11-08 11:17:24.264  5544  5592 E io.jxcore.node.ConnectionModel: addConnectionThread: A matching thread for outgoing connection already exists
11-08 11:17:24.264  5544  5592 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
11-08 11:17:24.264  5544  5592 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
11-08 11:17:24.265  5544  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-08 11:17:24.265  5544  5592 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
11-08 11:17:24.265  5544  5592 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-08 11:17:24.265  5544  5592 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
11-08 11:17:24.265  5544  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-08 11:17:24.265  5544  5592 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
11-08 11:17:24.265  5544  5592 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-08 11:17:24.265  5544  5592 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
11-08 11:17:24.265  5544  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-08 11:17:24.265  5544  5592 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
11-08 11:17:24.266  5544  5592 I io.jxcore.node.ConnectionHelperTest: Starting test: testDispose
11-08 11:17:24.266  5544  5592 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-08 11:17:24.266  5544  5592 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-08 11:17:24.266  5544  5592 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
,11-08 11:17:24.266  5544  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
11-08 11:17:24.266  5544  5592 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-08 11:17:24.266  5544  5592 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-08 11:17:24.266  5544  5592 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-08 11:17:24.266  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-08 11:17:24.268  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-08 11:17:24.268  5544  5592 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-08 11:17:24.268  5544  5592 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-08 11:17:24.268  5544  5592 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-08 11:17:24.268  5544  5592 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-08 11:17:24.268  5544  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-08 11:17:24.268  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-08 11:17:24.268  5544  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-08 11:17:24.268  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-08 11:17:24.269  5544  5544 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-08 11:17:24.269  5544  5613 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-08 11:17:24.270  4823  4823 W Binder_4: type=1400 audit(0.0:117): avc: denied { ioctl } for path="socket:[31076]" dev="sockfs" ino=31076 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-08 11:17:24.273  5544  5613 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-08 11:17:24.270  4823  4823 W Binder_4: type=1400 audit(0.0:118): avc: denied { ioctl } for path="socket:[31076]" dev="sockfs" ino=31076 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-08 11:17:24.274  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-08 11:17:24.274  5544  5592 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,11-08 11:17:24.274  5544  5592 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-08 11:17:24.278  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-08 11:17:24.279  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-08 11:17:24.279  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,11-08 11:17:24.282  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-66,5,main], id: 66
,11-08 11:17:24.282  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-08 11:17:24.282  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-08 11:17:24.282  5544  5592 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 60 83 34 25 D7 D4
11-08 11:17:24.282  5544  5592 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-08 11:17:24.282  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:24.282  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:24.283  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:24.283  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-66,5,main], id: 66
,11-08 11:17:24.283  5544  5592 D BluetoothAdapter: STATE_ON
,11-08 11:17:24.286  4608  4621 D BtGatt.GattService: registerClient() - UUID=db5342ee-8d8d-449f-992e-fceee3f6069d
,11-08 11:17:24.286  4608  4679 D BtGatt.GattService: onClientRegistered() - UUID=db5342ee-8d8d-449f-992e-fceee3f6069d, clientIf=5
11-08 11:17:24.287  5544  5584 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-08 11:17:24.288  4608  4682 D BtGatt.AdvertiseManager: message : 0
,11-08 11:17:24.290  4608  4682 D BtGatt.AdvertiseManager: starting multi advertising
,11-08 11:17:24.299  4608  4679 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-08 11:17:24.304  4608  4679 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-08 11:17:24.305  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:24.305  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:24.305  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-08 11:17:24.305  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:24.305  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:24.305  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-66,5,main], id: 66
,11-08 11:17:24.306  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:24.306  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:24.306  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-08 11:17:24.307  5544  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-08 11:17:24.307  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:24.308  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:24.308  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:24.308  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:24.308  5544  5592 I io.jxcore.node.ConnectionHelper: start: OK
11-08 11:17:24.308  5544  5544 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,11-08 11:17:24.309  5544  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-08 11:17:24.309  5544  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-08 11:17:24.309  5544  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-08 11:17:24.309  5544  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged true. Current thread: Thread[main,5,main], id: 1
11-08 11:17:24.309  5544  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-08 11:17:24.309  5544  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-08 11:17:24.309  5544  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-08 11:17:24.309  5544  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-08 11:17:24.309  5544  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-08 11:17:24.309  5544  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-08 11:17:24.309  5544  5544 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-08 11:17:24.309  5544  5544 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-08 11:17:24.311  5544  5544 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-08 11:17:24.312  5544  5544 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-08 11:17:24.312  5544  5544 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-08 11:17:24.312  5544  5544 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-08 11:17:24.312  5544  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-08 11:17:24.312  5544  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-08 11:17:24.312  5544  5544 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-08 11:17:24.810  5544  5592 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-08 11:17:24.810  5544  5592 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,11-08 11:17:24.810  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-08 11:17:24.810  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-08 11:17:24.811  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
11-08 11:17:24.811  5544  5592 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-08 11:17:24.811  5544  5592 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,11-08 11:17:24.811  5544  5613 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-08 11:17:24.811  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-08 11:17:24.811  5544  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,11-08 11:17:24.812  5544  5613 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-08 11:17:24.812  5544  5544 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-08 11:17:24.812  5544  5592 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@779889e removed from the list
11-08 11:17:24.812  5544  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-08 11:17:24.812  5544  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-08 11:17:24.812  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-08 11:17:24.812  5544  5544 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-08 11:17:24.812  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-08 11:17:24.812  5544  5544 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-08 11:17:24.813  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-66,5,main], id: 66
,11-08 11:17:24.813  5544  5544 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-08 11:17:24.813  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:24.815  5544  5592 D BluetoothAdapter: STATE_ON
11-08 11:17:24.815  5544  5592 D BluetoothLeScanner: could not find callback wrapper
,11-08 11:17:24.816  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-08 11:17:24.816  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:24.816  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-66,5,main], id: 66
,11-08 11:17:24.816  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-08 11:17:24.816  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:24.818  4608  4682 D BtGatt.AdvertiseManager: message : 1
11-08 11:17:24.819  4608  4682 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-08 11:17:24.832  4608  4679 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-08 11:17:24.832  4608  4679 D BtGatt.GattService: Client app is not null!
,11-08 11:17:24.834  4608  4815 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-08 11:17:24.835  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-08 11:17:24.836  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:24.836  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-08 11:17:24.836  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged false. Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:24.836  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[Thread-66,5,main], id: 66
,11-08 11:17:24.836  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:24.836  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,11-08 11:17:24.836  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-08 11:17:24.837  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:24.837  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[Thread-66,5,main], id: 66
,11-08 11:17:24.837  5544  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-08 11:17:24.837  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-66,5,main], id: 66
,11-08 11:17:24.839  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:24.839  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,11-08 11:17:24.839  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:24.839  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-66,5,main], id: 66
,11-08 11:17:24.840  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:24.840  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:24.840  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:24.840  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-08 11:17:24.840  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-08 11:17:24.844  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
11-08 11:17:24.844  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:24.847  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:24.847  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:24.847  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:24.847  5544  5592 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e937f7f removed from the list
,11-08 11:17:24.848  5544  5544 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-08 11:17:24.848  5544  5592 D io.jxcore.node.ConnectivityMonitor: stop
11-08 11:17:24.848  5544  5544 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-08 11:17:24.848  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-08 11:17:24.848  5544  5544 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-08 11:17:25.349  5544  5544 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-08 11:17:29.851  5544  5592 I io.jxcore.node.ConnectionHelperTest: Starting test: testIsRunning
11-08 11:17:29.854  5544  5592 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,11-08 11:17:29.854  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-08 11:17:29.856  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-08 11:17:29.857  5544  5592 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,11-08 11:17:29.858  5544  5592 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,11-08 11:17:29.858  5544  5592 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,11-08 11:17:29.858  5544  5592 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-08 11:17:29.858  5544  5592 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-08 11:17:29.858  5544  5544 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,11-08 11:17:29.858  5544  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-08 11:17:29.860  5544  5614 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-08 11:17:29.862  5544  5592 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionFailed
11-08 11:17:29.865  5544  5592 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
11-08 11:17:29.865  5544  5614 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,11-08 11:17:29.865  5544  5592 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-08 11:17:29.866  5544  5592 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-08 11:17:29.866  5544  5592 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-08 11:17:29.866  5544  5592 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-08 11:17:29.869  5544  5592 I io.jxcore.node.ConnectionHelperTest: Starting test: testGetConnectivityMonitorGetDiscoveryManagerGetConnectionModelGetBluetoothName
11-08 11:17:29.864  4815  4815 W Binder_3: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[31081]" dev="sockfs" ino=31081 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-08 11:17:29.864  4815  4815 W Binder_3: type=1400 audit(0.0:120): avc: denied { ioctl } for path="socket:[31081]" dev="sockfs" ino=31081 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-08 11:17:29.877  5544  5592 I io.jxcore.node.ConnectionHelperTest: Starting test: testConstructor
,11-08 11:17:29.878  5544  5592 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-08 11:17:29.878  5544  5592 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-08 11:17:29.878  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-08 11:17:29.878  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-08 11:17:29.879  5544  5614 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-08 11:17:29.879  5544  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,11-08 11:17:29.879  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-08 11:17:29.879  5544  5614 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-08 11:17:29.879  5544  5592 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-08 11:17:29.879  5544  5592 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,11-08 11:17:29.879  5544  5544 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-08 11:17:29.879  5544  5592 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@779889e not in the list
11-08 11:17:29.879  5544  5544 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-08 11:17:29.879  5544  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-08 11:17:29.879  5544  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-08 11:17:29.879  5544  5544 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-08 11:17:29.879  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-08 11:17:29.879  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-08 11:17:29.880  5544  5592 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-08 11:17:29.880  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-08 11:17:29.880  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:29.883  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:29.883  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,11-08 11:17:29.883  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:29.884  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:29.884  5544  5544 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-08 11:17:29.884  5544  5544 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-08 11:17:29.884  5544  5592 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e937f7f not in the list
11-08 11:17:29.884  5544  5592 D io.jxcore.node.ConnectivityMonitor: stop
11-08 11:17:29.884  5544  5544 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-08 11:17:29.884  5544  5592 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-08 11:17:29.885  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-08 11:17:29.888  5544  5592 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentOutgoingConnections
,11-08 11:17:29.889  5544  5592 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
11-08 11:17:29.889  5544  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-08 11:17:29.889  5544  5592 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
11-08 11:17:29.889  5544  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-08 11:17:29.889  5544  5592 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
,11-08 11:17:29.889  5544  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-08 11:17:29.890  5544  5592 I io.jxcore.node.ConnectionModelTest: Starting test: constructorTest
,11-08 11:17:29.892  5544  5592 I io.jxcore.node.ConnectionModelTest: Starting test: testHasIncomingConnection
,11-08 11:17:29.894  5544  5592 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentConnections
11-08 11:17:29.895  5544  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-08 11:17:29.895  5544  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
11-08 11:17:29.895  5544  5592 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentIncomingConnections
11-08 11:17:29.896  5544  5592 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
11-08 11:17:29.896  5544  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,11-08 11:17:29.897  5544  5592 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
11-08 11:17:29.897  5544  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-08 11:17:29.897  5544  5592 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
11-08 11:17:29.897  5544  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
11-08 11:17:29.898  5544  5592 I io.jxcore.node.ConnectionModelTest: Starting test: testGetOutgoingConnectionCallbackByBluetoothMacAddress
11-08 11:17:29.899  5544  5592 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
,11-08 11:17:29.899  5544  5592 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,11-08 11:17:29.900  5544  5592 I io.jxcore.node.ConnectionModelTest: Starting test: testHasConnection
,11-08 11:17:29.901  5544  5592 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
11-08 11:17:29.901  5544  5592 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
,11-08 11:17:29.901  5544  5592 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
11-08 11:17:29.901  5544  5592 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,11-08 11:17:29.902  5544  5592 I io.jxcore.node.ConnectionModelTest: Starting test: testHasOutgoingConnection
,11-08 11:17:29.903  5544  5592 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-08 11:17:29.903  5544  5592 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5d1466f added. We now have 3 listener(s)
,11-08 11:17:29.906  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-08 11:17:29.906  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-08 11:17:29.906  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-08 11:17:29.906  5544  5592 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-08 11:17:29.906  5544  5592 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@66aff7c added. We now have 3 listener(s)
11-08 11:17:29.906  5544  5592 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-08 11:17:29.907  5544  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-08 11:17:29.911  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-08 11:17:29.916  5544  5592 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-08 11:17:29.916  5544  5592 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 11:17:29.916  5544  5592 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 11:17:29.916  5544  5592 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 11:17:29.916  5544  5592 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 11:17:29.916  5544  5592 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-08 11:17:29.916  5544  5592 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-08 11:17:29.916  5544  5592 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-08 11:17:29.918  5544  5592 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-08 11:17:29.918  5544  5592 D io.jxcore.node.ConnectivityMonitor: start: OK
,11-08 11:17:29.920  5544  5592 D BluetoothAdapter: enable(): BT is already enabled..!
11-08 11:17:29.920   934  3515 D WifiService: setWifiEnabled: true pid=5544, uid=10077
11-08 11:17:29.920   934  3515 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-08 11:17:29.921  5544  5544 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 11:17:29.921  5544  5592 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBleMultipleAdvertisementSupported
,11-08 11:17:29.924  5544  5544 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 11:17:29.924  5544  5592 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothSupported
,11-08 11:17:29.925  5544  5592 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testStartStop
,11-08 11:17:29.928   934  3068 D WifiService: setWifiEnabled: false pid=5544, uid=10077
,11-08 11:17:29.928   934  3068 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-08 11:17:29.931   934  2875 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,11-08 11:17:29.931   934  2875 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,11-08 11:17:29.931   934  2875 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-08 11:17:29.931   934  2875 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-08 11:17:29.939   934  5307 D DhcpClient: Clearing IP address
11-08 11:17:29.939   510   927 D CommandListener: Clearing all IP addresses on wlan0
,11-08 11:17:29.942   510   927 D CommandListener: Setting iface cfg
,11-08 11:17:29.943   934  5308 D DhcpClient: Receive thread stopped
,11-08 11:17:29.954  3502  5362 V NativeCrypto: Read error: ssl=0x7f81a44e00: I/O error during system call, Connection timed out
,11-08 11:17:29.957   934  2877 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
11-08 11:17:29.957  3502  5362 V NativeCrypto: SSL shutdown failed: ssl=0x7f81a44e00: I/O error during system call, Broken pipe
11-08 11:17:29.960   934  2877 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
11-08 11:17:29.960   544   544 E Parcel  : Reading a NULL string not supported here.
,11-08 11:17:29.962   934   934 D RttService: SCAN_AVAILABLE : 1
11-08 11:17:29.962   934  2987 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
11-08 11:17:29.966   934  2877 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,11-08 11:17:29.969   934  2875 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,11-08 11:17:29.970  3634  3761 W QCNEJ   : |CORE| network lost: 100
11-08 11:17:29.971  3634  3761 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
11-08 11:17:29.972   934  3673 I ActivityManager: Killing 5348:com.android.chrome/u0a39 (adj 15): empty #17
11-08 11:17:29.974   934  2875 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-08 11:17:29.996   510   927 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-08 11:17:30.014   510   927 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-08 11:17:30.014   510   927 D CommandListener: Clearing all IP addresses on wlan0
,11-08 11:17:30.015   934  2877 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
11-08 11:17:30.015   510   927 D TetherController: Setting IP forward enable = 0
,11-08 11:17:30.015   934  2877 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-08 11:17:30.018   934   951 D Tethering: MasterInitialState.processMessage what=3
11-08 11:17:30.020   934  2875 D DhcpClient: doQuit
11-08 11:17:30.020   934  2875 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-08 11:17:30.021   934  5307 D DhcpClient: onQuitting
11-08 11:17:30.021  3377  3377 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-08 11:17:30.025  5544  5544 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 11:17:30.025  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 11:17:30.025  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 11:17:30.025  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 11:17:30.025  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 11:17:30.025  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 11:17:30.025  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 11:17:30.025  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-08 11:17:30.027  5544  5544 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-08 11:17:30.032  5188  5188 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@75b62e8 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,11-08 11:17:30.032  5544  5544 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 11:17:30.032  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 11:17:30.032  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 11:17:30.032  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-08 11:17:30.032  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 11:17:30.032  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 11:17:30.032  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 11:17:30.032  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-08 11:17:30.033  3871  3871 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
11-08 11:17:30.035  5544  5544 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,11-08 11:17:30.037  3890  3890 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-08 11:17:30.039  5544  5544 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 11:17:30.039  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 11:17:30.039  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 11:17:30.039  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-08 11:17:30.039  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 11:17:30.039  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 11:17:30.039  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 11:17:30.039  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-08 11:17:30.042  5544  5544 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
11-08 11:17:30.045  3377  3377 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-08 11:17:30.045  5544  5544 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 11:17:30.045  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 11:17:30.045  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 11:17:30.045  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-08 11:17:30.045  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 11:17:30.045  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 11:17:30.045  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 11:17:30.045  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-08 11:17:30.047  5544  5544 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,11-08 11:17:30.049  5544  5544 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 11:17:30.050  5544  5544 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 11:17:30.051  3890  3890 D SystemUpdateService: onCreate
11-08 11:17:30.051  3377  3377 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
11-08 11:17:30.054  3890  3890 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-08 11:17:30.061  3890  5635 I SystemUpdateService: active receiver: enabled
,11-08 11:17:30.063  3890  3890 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-08 11:17:30.068  3890  4234 I iu.UploadsManager: num queued entries: 0
,11-08 11:17:30.068  3890  4234 I iu.UploadsManager: num updated entries: 0
11-08 11:17:30.069  3890  4234 I iu.SyncManager: NEXT; no task
,11-08 11:17:30.072  3890  3890 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-08 11:17:30.073   510   920 W SocketClient: write error (Broken pipe)
11-08 11:17:30.073   510   920 W SocketClient: Unable to send msg '600 Iface linkstate wlan0 up'
11-08 11:17:30.073   510   920 W SocketListener: Error sending broadcast (Broken pipe)
11-08 11:17:30.074  3890  3890 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-08 11:17:30.077  3890  5635 I SystemUpdateService: Already downloaded, skipping offpeak checks.
11-08 11:17:30.079  3890  5635 I SystemUpdateService: network: null; metered: false; mobile allowed: true
11-08 11:17:30.079  3890  5635 I SystemUpdateService: now status is 0 (complete)
11-08 11:17:30.079  3890  5635 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-08 11:17:30.079  3890  5635 I SystemUpdateService: file has been verified
11-08 11:17:30.079  3890  5635 I SystemUpdateService: OTA package size = 21989297
,11-08 11:17:30.084  3890  5635 I SystemUpdateService: showing system update notification
,11-08 11:17:30.087   510   927 E Netd    : netlink response contains error (No such file or directory)
,11-08 11:17:30.088   510   927 D TetherController: Setting IP forward enable = 0
11-08 11:17:30.088   934  3687 I ActivityManager: Start proc 5638:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
11-08 11:17:30.088   934  2877 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
11-08 11:17:30.089  3377  3377 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-08 11:17:30.098   934   934 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-08 11:17:30.099  3890  3890 D SystemUpdateService: onDestroy
,11-08 11:17:30.111  3377  3377 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-08 11:17:30.125  5638  5638 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,11-08 11:17:30.129  5638  5638 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-08 11:17:30.136  5638  5638 D SprintDMHelper: simOperator: 
11-08 11:17:30.136  5638  5638 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-08 11:17:30.147   934  3122 I ActivityManager: Start proc 5652:com.android.chrome/u0a39 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,11-08 11:17:30.148   934  3122 I ActivityManager: Killing 4432:com.google.android.calendar/u0a36 (adj 15): empty #17
,11-08 11:17:30.215  4952  4952 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-08 11:17:30.215   934  2875 D wifi    : In wifi stop Hal
,11-08 11:17:30.216   934  2875 D wifi    : halHandle = 0x7f7fc48680, mVM = 0x7f9c2cd140, mCls = 0x100a02
11-08 11:17:30.216   934  3375 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-08 11:17:30.216   934  3375 D WifiHAL : Got a signal to exit!!!
,11-08 11:17:30.216   934  3375 I WifiHAL : Exit wifi_event_loop
11-08 11:17:30.216   934  2875 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 11
,11-08 11:17:30.216   934  2875 E WifiHAL : Event processing terminated
11-08 11:17:30.217   934  2875 D wifi    : In wifi cleaned up handler
,11-08 11:17:30.217   934  2875 I WifiHAL : Internal cleanup completed
11-08 11:17:30.218  4024  4152 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-08 11:17:30.218  5544  5544 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 11:17:30.220  5544  5544 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 11:17:30.222  5544  5544 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 11:17:30.239   934  3375 D wifi    : set interface wlan0 flags (DOWN)
11-08 11:17:30.240   934  2875 D WifiNative-HAL: HAL event thread stopped successfully
,11-08 11:17:30.243   934   944 I ActivityManager: Killing 5052:com.google.android.deskclock/u0a66 (adj 15): empty #17
,11-08 11:17:30.271   934   944 I ActivityManager: Start proc 5667:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,11-08 11:17:30.301  5667  5667 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,11-08 11:17:30.308   934   944 I ActivityManager: Killing 5378:com.qualcomm.timeservice/1000 (adj 15): empty #17
,11-08 11:17:30.385  5544  5544 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-08 11:17:30.434  5544  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 11:17:30.438   934  3342 D WifiService: setWifiEnabled: true pid=5544, uid=10077
,11-08 11:17:30.438   934  3342 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-08 11:17:30.447   934   951 D Tethering: InitialState.processMessage what=4
,11-08 11:17:30.448   510   927 D SoftapController: Softap fwReload - Ok
,11-08 11:17:30.453   510   927 D CommandListener: Setting iface cfg
,11-08 11:17:30.453   510   927 D CommandListener: Trying to bring down wlan0
,11-08 11:17:30.454   934   951 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
11-08 11:17:30.456   510   927 D CommandListener: Clearing all IP addresses on wlan0
,11-08 11:17:30.462   934  2875 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-08 11:17:30.945   934  3122 D WifiService: setWifiEnabled: true pid=5544, uid=10077
,11-08 11:17:30.948   934  3122 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-08 11:17:31.060   934  2875 D wifi    : set interface wlan0 flags (UP)
,11-08 11:17:31.060   934  2875 I WifiHAL : Initializing wifi
,11-08 11:17:31.060   934  2875 I WifiHAL : Creating socket
,11-08 11:17:31.066   934  2875 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-08 11:17:31.066   934   951 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-08 11:17:31.066   934  2875 D wifi    : Did set static halHandle = 0x7f7fc48680
11-08 11:17:31.067   934  2875 D wifi    : halHandle = 0x7f7fc48680, mVM = 0x7f9c2cd140, mCls = 0x145e
,11-08 11:17:31.067   934  2875 D wifi    : array field set
11-08 11:17:31.069   934  2875 I WifiNative-HAL: interface[0] = wlan0
,11-08 11:17:31.072   934  5682 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547604432512
11-08 11:17:31.072   934  5682 D wifi    : waitForHalEvents called, vm = 0x7f9c2cd140, obj = 0x145e, env = 0x7f805d0800
,11-08 11:17:31.156  5683  5683 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-08 11:17:31.173   934  2875 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-08 11:17:31.182  5544  5544 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 11:17:31.184  5544  5544 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 11:17:31.185  5544  5544 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 11:17:31.238  5683  5683 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-08 11:17:31.266  5683  5683 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-08 11:17:31.266  5683  5683 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-08 11:17:31.280   934  2875 D WifiConfigStore: Loading config and enabling all networks 
,11-08 11:17:31.291  5544  5544 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 11:17:31.291  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 11:17:31.291  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 11:17:31.291  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 11:17:31.291  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 11:17:31.291  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 11:17:31.291  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 11:17:31.291  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-08 11:17:31.295  5544  5544 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-08 11:17:31.298  5544  5544 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 11:17:31.298  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 11:17:31.298  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 11:17:31.298  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 11:17:31.298  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 11:17:31.298  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 11:17:31.298  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 11:17:31.298  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-08 11:17:31.298   934  2875 D WifiConfigStore: loaded 0 passpoint configs
11-08 11:17:31.299   934  2875 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
,11-08 11:17:31.299   934  2875 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
11-08 11:17:31.300   934  2875 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
11-08 11:17:31.300   934  2875 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
,11-08 11:17:31.300  5544  5544 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-08 11:17:31.300   934  2875 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
11-08 11:17:31.301   934  2875 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
11-08 11:17:31.301   934  2875 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-08 11:17:31.301   934  2875 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
,11-08 11:17:31.301   934  2875 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
11-08 11:17:31.301   934  2875 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-08 11:17:31.301   934  2875 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-08 11:17:31.301   934  2875 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-08 11:17:31.303   934  2875 D WifiNative-HAL: Setting external_sim to 1
11-08 11:17:31.303   934  2875 D wifi    : setting dfs flag to true, 0x7f805ffbc0
11-08 11:17:31.304   934  2875 D WifiStateMachine: Setting OUI to DA-A1-19
11-08 11:17:31.304   934  2875 D wifi    : setting scan oui 0x7f805ffbc0
,11-08 11:17:31.304   934  2875 D WifiHAL : Sending mac address OUI
11-08 11:17:31.305  5544  5544 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 11:17:31.305  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 11:17:31.305  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 11:17:31.305  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 11:17:31.305  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 11:17:31.305  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 11:17:31.305  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 11:17:31.305  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-08 11:17:31.305  4952  4952 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-08 11:17:31.307   934  2875 E native  : do suspend false
,11-08 11:17:31.308  5544  5544 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-08 11:17:31.314   934  2875 D wifi    : android_net_wifi_setLinkLayerStats: 1
,11-08 11:17:31.314   934   934 D RttService: SCAN_AVAILABLE : 3
11-08 11:17:31.314   934  2987 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
11-08 11:17:31.314   510   927 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,11-08 11:17:31.315   510   927 D CommandListener: Setting iface cfg
,11-08 11:17:31.319   934  2874 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '120 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 120 Failed to set address (No such device)'
,11-08 11:17:31.319   934  2874 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-08 11:17:31.326   934  2874 D WifiNative-HAL: p2pGetDeviceAddress
,11-08 11:17:31.327   934  2874 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-08 11:17:31.331   934   949 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=105184 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=13 mControllerEnergyUsed=49 }
,11-08 11:17:31.454  5544  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 11:17:31.466  4608  4673 D BluetoothAdapterState: Current state: ON, message: 23
,11-08 11:17:31.468  4608  4673 D BluetoothAdapterProperties: Setting state to 13
11-08 11:17:31.468  4608  4673 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,11-08 11:17:31.469  4608  4673 D BluetoothAdapterProperties: onBluetoothDisable()
11-08 11:17:31.471  4608  4673 I BluetoothAdapterState: Entering PendingCommandState
,11-08 11:17:31.474  4608  4679 D BluetoothAdapterProperties: Scan Mode:20
11-08 11:17:31.475  4608  4673 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,11-08 11:17:31.480  4608  4608 D HeadsetService: Received stop request...Stopping profile...
,11-08 11:17:31.481  5544  5544 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-08 11:17:31.481  5544  5544 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 11:17:31.481  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 11:17:31.481  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 11:17:31.481  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 11:17:31.481  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-08 11:17:31.481  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 11:17:31.481  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 11:17:31.481  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-08 11:17:31.483   934   934 D BluetoothHeadset: Proxy object disconnected
11-08 11:17:31.483   934   934 D BluetoothHeadset: Proxy object disconnected
11-08 11:17:31.483   934   934 D BluetoothHeadset: Proxy object disconnected
,11-08 11:17:31.484  3057  3071 D BluetoothHeadset: Proxy object disconnected
11-08 11:17:31.484  3057  3057 D HeadsetProfile: Bluetooth service disconnected
,11-08 11:17:31.485  4608  4608 D A2dpService: Received stop request...Stopping profile...
11-08 11:17:31.485  4608  4818 D A2dpStateMachine: Exit Disconnected: -1
11-08 11:17:31.485  5544  5544 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-08 11:17:31.485  5544  5544 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-08 11:17:31.487  3674  3924 D BluetoothHeadset: Proxy object disconnected
11-08 11:17:31.490  5544  5544 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-08 11:17:31.491  5544  5544 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 11:17:31.491  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 11:17:31.491  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 11:17:31.491  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 11:17:31.491  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-08 11:17:31.491  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 11:17:31.491  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 11:17:31.491  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-08 11:17:31.493  5544  5544 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-08 11:17:31.496   934   934 D BluetoothA2dp: Proxy object disconnected
11-08 11:17:31.496  3057  3057 D BluetoothA2dp: Proxy object disconnected
11-08 11:17:31.496  4608  4608 V BluetoothAdapterState: isTurningOff()=true
,11-08 11:17:31.496  4608  4608 V BluetoothAdapterState: isTurningOn()=false
11-08 11:17:31.497  4608  4608 V BluetoothAdapterState: isBleTurningOn()=false
11-08 11:17:31.497  4608  4608 V BluetoothAdapterState: isBleTurningOff()=false
11-08 11:17:31.498  5544  5544 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-08 11:17:31.501  4608  4608 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,11-08 11:17:31.501  4608  4608 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-08 11:17:31.501  4608  4799 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-08 11:17:31.502  4608  4799 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-08 11:17:31.502  4608  4799 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-08 11:17:31.502  4608  4679 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-08 11:17:31.502  4608  4608 D HidService: Received stop request...Stopping profile...
11-08 11:17:31.502  4608  4679 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-08 11:17:31.502  4608  4608 D HidService: Stopping Bluetooth HidService
11-08 11:17:31.503  3057  3057 D BluetoothInputDevice: Proxy object disconnected
11-08 11:17:31.503  3057  3057 D HidProfile: Bluetooth service disconnected
11-08 11:17:31.504  4608  4608 D HealthService: Received stop request...Stopping profile...
11-08 11:17:31.505  5544  5544 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-08 11:17:31.505  5544  5544 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 11:17:31.505  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 11:17:31.505  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 11:17:31.505  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 11:17:31.505  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-08 11:17:31.505  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 11:17:31.505  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 11:17:31.505  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-08 11:17:31.506  5544  5544 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-08 11:17:31.506  5544  5544 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-08 11:17:31.506  4608  4608 D PanService: Received stop request...Stopping profile...
11-08 11:17:31.507  3057  3057 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-08 11:17:31.508  3057  3057 D PanProfile: Bluetooth service disconnected
,11-08 11:17:31.509  4608  4608 D BluetoothMapService: Received stop request...Stopping profile...
11-08 11:17:31.509  4608  4608 D BluetoothMapService: stop()
11-08 11:17:31.511  4608  4608 D BluetoothMapAppObserver: deinitObservers()
11-08 11:17:31.511  4608  4608 D BluetoothMapAppObserver: removeReceiver()
11-08 11:17:31.512  4608  4608 V BluetoothAdapterState: isTurningOff()=true
11-08 11:17:31.513  4608  4608 V BluetoothAdapterState: isTurningOn()=false
11-08 11:17:31.513  4608  4608 V BluetoothAdapterState: isBleTurningOn()=false
11-08 11:17:31.513  4608  4608 V BluetoothAdapterState: isBleTurningOff()=false
11-08 11:17:31.514  3057  3057 D BluetoothMap: Proxy object disconnected
11-08 11:17:31.514  3057  3057 D MapProfile: Bluetooth service disconnected
11-08 11:17:31.514  4608  4679 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-08 11:17:31.514  4608  4799 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-08 11:17:31.514  4608  4799 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-08 11:17:31.515  4608  4799 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-08 11:17:31.515  4608  4799 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-08 11:17:31.515  4608  4799 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-08 11:17:31.515  4608  4799 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-08 11:17:31.515  4608  4608 D SapService: Received stop request...Stopping profile...
11-08 11:17:31.515  4608  4608 V SapService: stop()
11-08 11:17:31.517  4608  4608 V BluetoothAdapterState: isTurningOff()=true
11-08 11:17:31.517  4608  4608 V BluetoothAdapterState: isTurningOn()=false
11-08 11:17:31.517  4608  4608 V BluetoothAdapterState: isBleTurningOn()=false
11-08 11:17:31.517  4608  4608 V BluetoothAdapterState: isBleTurningOff()=false
11-08 11:17:31.517  4608  4608 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-08 11:17:31.517  4608  4608 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-08 11:17:31.518  4608  4608 V BluetoothAdapterState: isTurningOff()=true
11-08 11:17:31.518  4608  4608 V BluetoothAdapterState: isTurningOn()=false
11-08 11:17:31.518  4608  4608 V BluetoothAdapterState: isBleTurningOn()=false
11-08 11:17:31.518  4608  4608 V BluetoothAdapterState: isBleTurningOff()=false
11-08 11:17:31.518  4608  4608 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-08 11:17:31.520  4608  4679 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-08 11:17:31.521  4608  4608 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-08 11:17:31.521  4608  4679 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-08 11:17:31.521  4608  4608 V BluetoothAdapterState: isTurningOff()=true
11-08 11:17:31.522  4608  4608 V BluetoothAdapterState: isTurningOn()=false
11-08 11:17:31.522  4608  4608 V BluetoothAdapterState: isBleTurningOn()=false
11-08 11:17:31.522  4608  4608 V BluetoothAdapterState: isBleTurningOff()=false
11-08 11:17:31.522  4608  4608 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-08 11:17:31.522  4608  4608 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-08 11:17:31.524  5544  5544 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 11:17:31.525  4608  4608 D BluetoothMapService: MAP Service closeService in
11-08 11:17:31.525  4608  4608 D BluetoothMapMasInstance0: MAP Service shutdown
11-08 11:17:31.525  4608  4608 D ObexServerSockets0: shutdown(block = true)
11-08 11:17:31.526  4608  4608 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-08 11:17:31.526  4608  4825 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
11-08 11:17:31.527  4608  4608 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-08 11:17:31.527  4608  4813 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-08 11:17:31.527  5544  5544 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 11:17:31.528  4608  4826 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-08 11:17:31.528  4608  4608 V BluetoothAdapterState: isTurningOff()=true
11-08 11:17:31.528  4608  4608 V BluetoothAdapterState: isTurningOn()=false
11-08 11:17:31.528  4608  4608 V BluetoothAdapterState: isBleTurningOn()=false
11-08 11:17:31.528  4608  4608 V BluetoothAdapterState: isBleTurningOff()=false
11-08 11:17:31.528  4608  4608 D BluetoothMapService: cleanup()
11-08 11:17:31.528  4608  4608 D BluetoothMapService: MAP Service closeService in
11-08 11:17:31.529  5544  5544 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 11:17:31.529  4608  4608 V BluetoothAdapterState: isTurningOff()=true
11-08 11:17:31.529  4608  4608 V BluetoothAdapterState: isTurningOn()=false
11-08 11:17:31.529  4608  4608 V BluetoothAdapterState: isBleTurningOn()=false
11-08 11:17:31.529  4608  4608 V BluetoothAdapterState: isBleTurningOff()=false
11-08 11:17:31.529  4608  4673 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-08 11:17:31.529  4608  4673 D BluetoothAdapterProperties: Setting state to 15
11-08 11:17:31.529  4608  4673 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-08 11:17:31.530  4608  4608 I BtOppRfcommListener: stopping Accept Thread
11-08 11:17:31.530  4608  5238 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-08 11:17:31.530  4608  5238 I BtOppRfcommListener: BluetoothSocket listen thread finished
11-08 11:17:31.530  4608  4673 I BluetoothAdapterState: Entering BleOnState
11-08 11:17:31.536   934   947 I ActivityManager: Start proc 5687:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
11-08 11:17:31.537  3057  3071 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-08 11:17:31.539  3674  3697 D BluetoothHeadset: onBluetoothStateChange: up=false
11-08 11:17:31.539  3057  3070 D BluetoothPbap: onBluetoothStateChange: up=false
11-08 11:17:31.541   934   951 D BluetoothHeadset: onBluetoothStateChange: up=false
11-08 11:17:31.541  3057  3809 D BluetoothMap: onBluetoothStateChange: up=false
11-08 11:17:31.542   934   951 D BluetoothA2dp: onBluetoothStateChange: up=false
11-08 11:17:31.542   934   951 D BluetoothHeadset: onBluetoothStateChange: up=false
11-08 11:17:31.542  3057  3071 D BluetoothPan: onBluetoothStateChange on: false
11-08 11:17:31.543  3057  3070 D BluetoothA2dp: onBluetoothStateChange: up=false
11-08 11:17:31.544  3057  3809 D BluetoothHeadset: onBluetoothStateChange: up=false
11-08 11:17:31.544   934   951 D BluetoothHeadset: onBluetoothStateChange: up=false
11-08 11:17:31.546  4608  4673 D BluetoothAdapterState: Current state: BLE ON, message: 20
,11-08 11:17:31.546  4608  4673 D BluetoothAdapterProperties: Setting state to 16
11-08 11:17:31.546  4608  4673 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-08 11:17:31.547  4608  4673 D BluetoothAdapterProperties: onBleDisable
11-08 11:17:31.547  4608  4673 I BluetoothAdapterState: Entering PendingCommandState
11-08 11:17:31.548  4608  4674 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,11-08 11:17:31.549  5544  5544 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 11:17:31.550  4608  4799 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,11-08 11:17:31.551  4608  4799 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-08 11:17:31.551  4608  4679 D BluetoothAdapterProperties: Scan Mode:20
11-08 11:17:31.555  5544  5544 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 11:17:31.558  5544  5544 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 11:17:31.559  5544  5544 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 11:17:31.561  5544  5544 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 11:17:31.563  5544  5544 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 11:17:31.587  5687  5687 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,11-08 11:17:31.598  5687  5687 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-08 11:17:31.602   934   951 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f9069d4:true
,11-08 11:17:31.604  3502  3502 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-08 11:17:31.617   934  3668 I ActivityManager: Start proc 5699:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,11-08 11:17:31.626  5687  5687 D LocalBluetoothProfileManager: Adding local MAP profile
,11-08 11:17:31.629  5687  5687 D BluetoothMap: Create BluetoothMap proxy object
,11-08 11:17:31.639  5687  5687 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,11-08 11:17:31.654  5699  5699 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,11-08 11:17:31.657  5687  5687 D DockEventReceiver: finishStartingService: stopping service
,11-08 11:17:31.660   934  3687 I ActivityManager: Killing 5188:com.google.android.music:main/u0a59 (adj 15): empty #17
,11-08 11:17:31.758  4608  4679 I bt_hci  : shut_down
,11-08 11:17:31.762  4608  4684 D bt_hwcfg: hw_epilog_process
,11-08 11:17:31.762  4608  4684 I bt_vendor: low_power_mode_cb
,11-08 11:17:31.765  4608  4684 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
11-08 11:17:31.765  4608  4684 I bt_vendor: epilog_cb
11-08 11:17:31.765  4608  4684 I bt_hci  : epilog_finished_callback
,11-08 11:17:31.768  4608  4679 I bt_hci_h4: hal_close
11-08 11:17:31.768  4608  4679 I bt_userial_vendor: device fd = 54 close
,11-08 11:17:31.878  4608  4674 D bt_stack_manager: event_shut_down_stack finished.
,11-08 11:17:31.878  4608  4673 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-08 11:17:31.880  4608  4673 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,11-08 11:17:31.881  4608  4608 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-08 11:17:31.881  4608  4608 D BtGatt.GattService: Received stop request...Stopping profile...
,11-08 11:17:31.881  4608  4608 D BtGatt.GattService: stop()
11-08 11:17:31.881  4608  4608 D BtGatt.AdvertiseManager: advertise clients cleared
11-08 11:17:31.884  4608  4608 V BluetoothAdapterState: isTurningOff()=false
11-08 11:17:31.884  4608  4608 V BluetoothAdapterState: isTurningOn()=false
,11-08 11:17:31.884  4608  4608 V BluetoothAdapterState: isBleTurningOn()=false
11-08 11:17:31.884  4608  4608 V BluetoothAdapterState: isBleTurningOff()=true
11-08 11:17:31.884  4608  4673 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-08 11:17:31.884  4608  4673 D BluetoothAdapterProperties: Setting state to 10
11-08 11:17:31.884  4608  4673 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-08 11:17:31.885  4608  4673 I BluetoothAdapterState: Entering OffState
,11-08 11:17:31.886   934   951 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,11-08 11:17:31.894  4608  4608 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-08 11:17:31.894  4608  4608 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-08 11:17:31.894  4608  4608 I BluetoothServiceJni: cleanupNative: return from cleanup
11-08 11:17:31.895  4608  4674 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-08 11:17:31.899  4608  4608 I art     : System.exit called, status: 0
,11-08 11:17:31.899  4608  4608 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-08 11:17:31.916  5699  5699 D StrictMode: StrictMode policy violation; ~duration=159 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-08 11:17:31.916  5699  5699 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-08 11:17:31.916  5699  5699 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-08 11:17:31.916  5699  5699 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-08 11:17:31.916  5699  5699 D StrictMode: 	at java.io.File.exists(File.java:361)
11-08 11:17:31.916  5699  5699 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-08 11:17:31.916  5699  5699 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-08 11:17:31.916  5699  5699 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
11-08 11:17:31.916  5699  5699 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-08 11:17:31.916  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-08 11:17:31.916  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-08 11:17:31.916  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-08 11:17:31.916  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-08 11:17:31.916  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-08 11:17:31.916  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-08 11:17:31.916  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-08 11:17:31.916  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-08 11:17:31.916  5699  5699 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-08 11:17:31.916  5699  5699 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-08 11:17:31.916  5699  5699 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-08 11:17:31.916  5699  5699 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-08 11:17:31.916  5699  5699 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-08 11:17:31.916  5699  5699 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-08 11:17:31.916  5699  5699 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-08 11:17:31.916  5699  5699 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-08 11:17:31.916  5699  5699 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-08 11:17:31.916  5699  5699 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-08 11:17:31.917  5699  5699 D StrictMode: StrictMode policy violation; ~duration=158 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-08 11:17:31.917  5699  5699 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-08 11:17:31.917  5699  5699 D StrictMode: StrictMode policy violation; ~duration=157 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-08 11:17:31.917  5699  5699 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-08 11:17:31.917  5699  5699 D StrictMode: StrictMode policy violation; ~duration=156 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-08 11:17:31.917  5699  5699 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at com.google.r.k.a(PG:2107)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-08 11:17:31.917  5,699  5699 D StrictMode: 	at com.google.r.e.b(PG:170)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-08 11:17:31.917  5699  5699 D StrictMode: StrictMode policy violation; ~duration=153 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-08 11:17:31.917  5699  5699 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at com.google.r.k.c(PG:18147)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at com.google.r.k.d(PG:583)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at com.google.r.e.b(PG:170)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-08 1,1:17:31.917  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-08 11:17:31.917  5699  5699 D StrictMode: StrictMode policy violation; ~duration=124 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-08 11:17:31.917  5699  5699 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at java.io.File.exists(File.java:361)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-08 11:17:31.917  5699  5699 D StrictMode: StrictMode policy violation; ~duration=123 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-08 11:17:31.917  5699  5699 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at java.io.File.exists(File.java:361)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-08 11:17:31.917  5699  5699 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-08 11:17:31.918  5699  5699 D StrictMode: StrictMode policy violation; ~duration=123 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-08 11:17:31.918  5699  5699 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-08 11:17:31.918  5699  5699 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
11-08 11:17:31.918  5699  5699 D StrictMode: 	at java.io.File.lastModified(File.java:569)
11-08 11:17:31.918  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
11-08 11:17:31.918  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-08 11:17:31.918  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-08 11:17:31.918  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-08 11:17:31.918  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-08 11:17:31.918  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-08 11:17:31.918  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-08 11:17:31.918  5699  5699 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-08 11:17:31.918  5699  5699 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-08 11:17:31.918  5699  5699 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-08 11:17:31.918  5699  5699 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-08 11:17:31.918  5699  5699 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-08 11:17:31.918  5699  5699 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-08 11:17:31.918  5699  5699 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-08 11:17:31.918  5699  5699 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-08 11:17:31.918  5699  5699 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-08 11:17:31.918  5699  5699 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-08 11:17:31.922  5687  5687 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-08 11:17:31.924   934  3515 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 76)
11-08 11:17:31.925   934  3515 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 1904)
11-08 11:17:31.925   934  3515 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapReceiver}
11-08 11:17:31.925   934  3515 W BroadcastQueue: android.os.DeadObjectException: Transaction failed on small parcel; remote process probably died
11-08 11:17:31.925   934  3515 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
11-08 11:17:31.925   934  3515 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:503)
11-08 11:17:31.925   934  3515 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:891)
11-08 11:17:31.925   934  3515 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:273)
11-08 11:17:31.925   934  3515 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1039)
11-08 11:17:31.925   934  3515 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:17151)
11-08 11:17:31.925   934  3515 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:496)
11-08 11:17:31.925   934  3515 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2489)
11-08 11:17:31.925   934  3515 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:453)
11-08 11:17:31.942   934  3515 I ActivityManager: Start proc 5730:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
11-08 11:17:31.943   934   944 W ActivityManager: Spurious death for ProcessRecord{4bbd9f4 5730:com.android.bluetooth/1002}, curProc for 4608: null
11-08 11:17:31.943  5687  5687 D DockEventReceiver: finishStartingService: stopping service
11-08 11:17:31.945   934  3122 I ActivityManager: Killing 3779:com.android.providers.calendar/u0a1 (adj 15): empty #17
,11-08 11:17:31.966  5544  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 11:17:32.013  5730  5730 D AdapterServiceConfig: Adding HeadsetService
,11-08 11:17:32.013  5730  5730 D AdapterServiceConfig: Adding A2dpService
11-08 11:17:32.013  5730  5730 D AdapterServiceConfig: Adding HidService
11-08 11:17:32.013  5730  5730 D AdapterServiceConfig: Adding HealthService
11-08 11:17:32.013  5730  5730 D AdapterServiceConfig: Adding PanService
11-08 11:17:32.013  5730  5730 D AdapterServiceConfig: Adding GattService
11-08 11:17:32.013  5730  5730 D AdapterServiceConfig: Adding BluetoothMapService
11-08 11:17:32.014  5730  5730 D AdapterServiceConfig: Adding SapService
,11-08 11:17:32.017  3502  3502 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-08 11:17:32.026   934   951 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@84f617a:true
,11-08 11:17:32.026  5730  5730 D BluetoothAdapterState: make() - Creating AdapterState
,11-08 11:17:32.029  5730  5730 I bt_bluedroid: init
,11-08 11:17:32.029  5730  5743 I BluetoothAdapterState: Entering OffState
,11-08 11:17:32.031  5730  5744 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-08 11:17:32.031  5730  5744 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-08 11:17:32.031  5730  5744 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-08 11:17:32.031  5730  5744 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-08 11:17:32.032  5730  5730 I bt_bluedroid: get_profile_interface socket
,11-08 11:17:32.033  5730  5730 I bt_bluedroid: get_profile_interface sdp
,11-08 11:17:32.033  5730  5747 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-08 11:17:32.035  5730  5747 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-08 11:17:32.038  5730  5740 I bt_bluedroid: config_hci_snoop_log
,11-08 11:17:32.039   934   951 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 9 receivers.
,11-08 11:17:32.042  5730  5743 D BluetoothAdapterState: Current state: OFF, message: 0
,11-08 11:17:32.042  5730  5743 D BluetoothAdapterProperties: Setting state to 14
11-08 11:17:32.042  5730  5743 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-08 11:17:32.043  5730  5743 D BluetoothBondStateMachine: make
11-08 11:17:32.044  5730  5748 I BluetoothBondStateMachine: StableState(): Entering Off State
11-08 11:17:32.047  5730  5743 I BluetoothAdapterState: Entering PendingCommandState
,11-08 11:17:32.048  5730  5730 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-08 11:17:32.049  5730  5730 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96bca27
11-08 11:17:32.050  5730  5730 D BtGatt.DebugUtils: handleDebugAction() action=null
11-08 11:17:32.050  5730  5730 D BtGatt.GattService: Received start request. Starting profile...
11-08 11:17:32.050  5730  5730 D BtGatt.GattService: start()
11-08 11:17:32.050  5730  5730 I bt_bluedroid: get_profile_interface gatt
,11-08 11:17:32.051  5730  5730 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96bca27
,11-08 11:17:32.052  5730  5730 D BtGatt.AdvertiseManager: advertise manager created
,11-08 11:17:32.056  5730  5730 V BluetoothAdapterState: isTurningOff()=false
,11-08 11:17:32.056  5730  5730 V BluetoothAdapterState: isTurningOn()=false
11-08 11:17:32.056  5730  5730 V BluetoothAdapterState: isBleTurningOn()=true
11-08 11:17:32.056  5730  5730 V BluetoothAdapterState: isBleTurningOff()=false
11-08 11:17:32.056  5730  5743 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-08 11:17:32.057  5730  5743 I bt_bluedroid: bt_bluedroid
11-08 11:17:32.057  5730  5744 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,11-08 11:17:32.058  5730  5744 I bt_hci  : start_up
,11-08 11:17:32.063  5730  5744 I bt_vendor: alloc value 0xf3c77871
,11-08 11:17:32.063  5730  5744 I bt_vendor: init
11-08 11:17:32.063  5730  5744 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-08 11:17:32.063  5730  5744 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-08 11:17:32.139  5699  5725 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,11-08 11:17:32.147   934   951 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@93cc6a3:true
,11-08 11:17:32.171  5730  5744 D bt_hci  : start_up starting async portion
11-08 11:17:32.171  5730  5751 I bt_hci  : event_finish_startup
,11-08 11:17:32.171  5730  5751 I bt_hci_h4: hal_open
11-08 11:17:32.171  5730  5751 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-08 11:17:32.172  5730  5751 I bt_userial_vendor: device fd = 54 open
11-08 11:17:32.170  5754  5754 W irq/448-msm_hs_: type=1400 audit(0.0:121): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-08 11:17:32.184  5730  5751 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-08 11:17:32.186  5730  5751 D bt_hwcfg: Chipset BCM4358A3
,11-08 11:17:32.186  5730  5751 D bt_hwcfg: Target name = [BCM4358A3]
11-08 11:17:32.186  5730  5751 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-08 11:17:32.484  5730  5743 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,11-08 11:17:32.568  5730  5751 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-08 11:17:32.568  5730  5751 D bt_hwcfg: Settlement delay -- 100 ms
,11-08 11:17:32.568  5730  5751 I bt_hwcfg: Setting fw settlement delay to 100 
,11-08 11:17:32.693  5730  5751 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-08 11:17:32.694  5730  5751 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
,11-08 11:17:32.695  5730  5751 I bt_hwcfg: vendor lib fwcfg completed
11-08 11:17:32.695  5730  5751 I bt_vendor: firmware callback
11-08 11:17:32.695  5730  5751 I bt_hci  : firmware_config_callback
,11-08 11:17:32.705  5730  5756 I bt_btu  : btu_task pending for preload complete event
,11-08 11:17:32.706  5730  5756 I bt_btu_task: Bluetooth chip preload is complete
11-08 11:17:32.706  5730  5756 I bt_btu  : btu_task received preload complete event
,11-08 11:17:32.713  5730  5756 I         : BTE_InitTraceLevels -- TRC_HCI
,11-08 11:17:32.713  5730  5756 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-08 11:17:32.714  5730  5756 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,11-08 11:17:32.714  5730  5756 I         : BTE_InitTraceLevels -- TRC_AVDT
11-08 11:17:32.714  5730  5756 I         : BTE_InitTraceLevels -- TRC_AVRC
,11-08 11:17:32.714  5730  5756 I         : BTE_InitTraceLevels -- TRC_A2D
11-08 11:17:32.714  5730  5756 I         : BTE_InitTraceLevels -- TRC_BNEP
11-08 11:17:32.714  5730  5756 I         : BTE_InitTraceLevels -- TRC_BTM
11-08 11:17:32.714  5730  5756 I         : BTE_InitTraceLevels -- TRC_GAP
,11-08 11:17:32.715  5730  5756 I         : BTE_InitTraceLevels -- TRC_PAN
11-08 11:17:32.715  5730  5756 I         : BTE_InitTraceLevels -- TRC_SDP
11-08 11:17:32.715  5730  5756 I         : BTE_InitTraceLevels -- TRC_GATT
,11-08 11:17:32.715  5730  5756 I         : BTE_InitTraceLevels -- TRC_SMP
11-08 11:17:32.715  5730  5756 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-08 11:17:32.715  5730  5756 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-08 11:17:32.798  5730  5756 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3bf5549
,11-08 11:17:32.799  5730  5756 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3bf5549 
,11-08 11:17:32.822  5730  5747 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-08 11:17:32.824  5730  5747 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-08 11:17:32.825  5730  5747 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
11-08 11:17:32.827  5730  5747 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-08 11:17:32.831  5730  5747 D BluetoothAdapterProperties: Scan Mode:20
,11-08 11:17:32.831  5730  5747 D BluetoothAdapterProperties: Discoverable Timeout:120
11-08 11:17:32.831  5730  5747 D bt_hci  : do_postload posting postload work item
11-08 11:17:32.831  5730  5751 I bt_hci  : event_postload
11-08 11:17:32.831  5730  5751 I bt_vendor: sco_config_cb
,11-08 11:17:32.832  5730  5751 I bt_hci  : sco_config_callback postload finished.
11-08 11:17:32.833  5730  5747 D bt_bte_conf: Device ID record 1 : primary
11-08 11:17:32.833  5730  5747 D bt_bte_conf:   vendorId            = 000f
11-08 11:17:32.833  5730  5747 D bt_bte_conf:   vendorIdSource      = 0001
11-08 11:17:32.833  5730  5747 D bt_bte_conf:   product             = 1200
11-08 11:17:32.833  5730  5747 D bt_bte_conf:   version             = 1436
11-08 11:17:32.833  5730  5747 D bt_bte_conf:   clientExecutableURL = 
11-08 11:17:32.833  5730  5747 D bt_bte_conf:   serviceDescription  = 
11-08 11:17:32.834  5730  5747 D bt_bte_conf:   documentationURL    = 
11-08 11:17:32.834  5730  5747 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-08 11:17:32.834  5730  5744 D bt_stack_manager: event_start_up_stack finished
11-08 11:17:32.835  5544  5544 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 11:17:32.835  5730  5743 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,11-08 11:17:32.835  5730  5743 D BluetoothAdapterProperties: Setting state to 15
11-08 11:17:32.835  5730  5743 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-08 11:17:32.836  5730  5743 I BluetoothAdapterState: Entering BleOnState
11-08 11:17:32.838  5544  5544 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 11:17:32.841  5730  5751 I bt_vendor: low_power_mode_cb
11-08 11:17:32.842  5544  5544 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 11:17:32.845  5730  5743 D BluetoothAdapterState: Current state: BLE ON, message: 1
,11-08 11:17:32.845  5730  5743 D BluetoothAdapterProperties: Setting state to 11
11-08 11:17:32.845  5730  5743 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-08 11:17:32.851  5730  5730 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96bca27
,11-08 11:17:32.854  5730  5730 D HeadsetService: Received start request. Starting profile...
,11-08 11:17:32.854  5544  5544 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 11:17:32.857  5730  5730 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-08 11:17:32.857  5730  5730 D HeadsetStateMachine: make
,11-08 11:17:32.860  5544  5544 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 11:17:32.862  5544  5544 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 11:17:32.869  5730  5743 I BluetoothAdapterState: Entering PendingCommandState
,11-08 11:17:32.872  5730  5730 D HeadsetStateMachine: max_hf_connections = 1
,11-08 11:17:32.872  5730  5730 I bt_bluedroid: get_profile_interface handsfree
11-08 11:17:32.874  5730  5747 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,11-08 11:17:32.875  5730  5747 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,11-08 11:17:32.876  5730  5730 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96bca27
,11-08 11:17:32.877  5730  5730 D A2dpService: Received start request. Starting profile...
11-08 11:17:32.878  5730  5730 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-08 11:17:32.878  5730  5730 I bt_bluedroid: get_profile_interface avrcp
,11-08 11:17:32.884  5730  5730 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-08 11:17:32.884  5730  5730 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-08 11:17:32.884  5730  5730 D A2dpStateMachine: make
11-08 11:17:32.885  5730  5730 I bt_bluedroid: get_profile_interface a2dp
,11-08 11:17:32.886  5730  5747 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-08 11:17:32.887  5730  5764 D A2dpStateMachine: Enter Disconnected: -2
,11-08 11:17:32.888  5730  5730 I BluetoothHidServiceJni: classInitNative: succeeds
11-08 11:17:32.889  5730  5730 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96bca27
,11-08 11:17:32.890  5730  5730 D HidService: Received start request. Starting profile...
,11-08 11:17:32.890  5730  5730 I bt_bluedroid: get_profile_interface hidhost
11-08 11:17:32.890  5687  5687 D BluetoothInputDevice: Proxy object connected
11-08 11:17:32.890  5730  5730 D HidService: setHidService(): set to: null
11-08 11:17:32.890  5730  5747 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3bd656d
11-08 11:17:32.890  5730  5747 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-08 11:17:32.891  5687  5687 D HidProfile: Bluetooth service connected
11-08 11:17:32.891  5730  5730 I BluetoothHealthServiceJni: classInitNative: succeeds
11-08 11:17:32.892  5730  5730 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96bca27
11-08 11:17:32.892  3502  3502 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-08 11:17:32.893  5730  5730 D HealthService: Received start request. Starting profile...
,11-08 11:17:32.895  5730  5730 I bt_bluedroid: get_profile_interface health
,11-08 11:17:32.896  5730  5730 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,11-08 11:17:32.896  5730  5730 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96bca27
,11-08 11:17:32.898  5687  5687 D BluetoothPan: BluetoothPAN Proxy object connected
,11-08 11:17:32.898  5730  5730 D PanService: Received start request. Starting profile...
11-08 11:17:32.898  5687  5687 D PanProfile: Bluetooth service connected
11-08 11:17:32.898  5730  5730 D BluetoothPanServiceJni: initializeNative(L110): pan
11-08 11:17:32.898  5730  5730 I bt_bluedroid: get_profile_interface pan
11-08 11:17:32.898  5730  5747 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,11-08 11:17:32.901  5730  5730 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96bca27
,11-08 11:17:32.902  5687  5687 D BluetoothMap: Proxy object connected
,11-08 11:17:32.902  5730  5730 D BluetoothMapService: Received start request. Starting profile...
11-08 11:17:32.902  5687  5687 D MapProfile: Bluetooth service connected
11-08 11:17:32.902  5730  5730 D BluetoothMapService: start()
11-08 11:17:32.902  5687  5687 D BluetoothMap: getConnectedDevices()
11-08 11:17:32.903  5687  5687 D BluetoothMap: Bluetooth is Not enabled
,11-08 11:17:32.905  5730  5730 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,11-08 11:17:32.905  5730  5730 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-08 11:17:32.905  5730  5730 D BluetoothMapAppObserver: createReceiver()
11-08 11:17:32.907  5730  5730 D BluetoothMapAppObserver: initObservers()
11-08 11:17:32.907  5730  5730 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-08 11:17:32.912  5730  5730 V SapService: SapBinder()
,11-08 11:17:32.912  5730  5730 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96bca27
,11-08 11:17:32.912  5730  5730 D SapService: Received start request. Starting profile...
11-08 11:17:32.912  5730  5730 V SapService: start()
,11-08 11:17:32.915  5730  5730 V BluetoothAdapterState: isTurningOff()=false
,11-08 11:17:32.915  5730  5730 V BluetoothAdapterState: isTurningOn()=true
11-08 11:17:32.915  5730  5730 V BluetoothAdapterState: isBleTurningOn()=false
11-08 11:17:32.916  5730  5730 V BluetoothAdapterState: isBleTurningOff()=false
,11-08 11:17:32.916  5730  5730 V BluetoothAdapterState: isTurningOff()=false
11-08 11:17:32.916  5730  5730 V BluetoothAdapterState: isTurningOn()=true
11-08 11:17:32.916  5730  5730 V BluetoothAdapterState: isBleTurningOn()=false
11-08 11:17:32.916  5730  5762 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-08 11:17:32.916  5730  5730 V BluetoothAdapterState: isBleTurningOff()=false
11-08 11:17:32.916  5730  5730 V BluetoothAdapterState: isTurningOff()=false
11-08 11:17:32.916  5730  5730 V BluetoothAdapterState: isTurningOn()=true
11-08 11:17:32.916  5730  5730 V BluetoothAdapterState: isBleTurningOn()=false
,11-08 11:17:32.917  5730  5730 V BluetoothAdapterState: isBleTurningOff()=false
11-08 11:17:32.917  5730  5730 V BluetoothAdapterState: isTurningOff()=false
11-08 11:17:32.917  5730  5730 V BluetoothAdapterState: isTurningOn()=true
11-08 11:17:32.917  5730  5730 V BluetoothAdapterState: isBleTurningOn()=false
11-08 11:17:32.917  5730  5730 V BluetoothAdapterState: isBleTurningOff()=false
,11-08 11:17:32.917  5730  5730 V BluetoothAdapterState: isTurningOff()=false
,11-08 11:17:32.918  5730  5730 V BluetoothAdapterState: isTurningOn()=true
11-08 11:17:32.918  5730  5730 V BluetoothAdapterState: isBleTurningOn()=false
11-08 11:17:32.918  5730  5730 V BluetoothAdapterState: isBleTurningOff()=false
11-08 11:17:32.918  5730  5730 V BluetoothAdapterState: isTurningOff()=false
11-08 11:17:32.918  5730  5730 V BluetoothAdapterState: isTurningOn()=true
11-08 11:17:32.918  5730  5730 V BluetoothAdapterState: isBleTurningOn()=false
11-08 11:17:32.918  5730  5730 V BluetoothAdapterState: isBleTurningOff()=false
11-08 11:17:32.919  5730  5730 V BluetoothAdapterState: isTurningOff()=false
11-08 11:17:32.919  5730  5730 V BluetoothAdapterState: isTurningOn()=true
11-08 11:17:32.919  5730  5730 V BluetoothAdapterState: isBleTurningOn()=false
11-08 11:17:32.919  5730  5730 V BluetoothAdapterState: isBleTurningOff()=false
,11-08 11:17:32.919  5730  5743 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-08 11:17:32.919  5730  5743 D BluetoothAdapterProperties: ScanMode =  20
11-08 11:17:32.920  5730  5743 D BluetoothAdapterProperties: State =  11
,11-08 11:17:32.921  5544  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-08 11:17:32.922  5544  5544 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-08 11:17:32.923  5730  5747 D BluetoothAdapterProperties: Scan Mode:21
11-08 11:17:32.923  5730  5743 D BluetoothAdapterProperties: Setting state to 12
11-08 11:17:32.923  5730  5743 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-08 11:17:32.923  5730  5747 D BluetoothAdapterProperties: Discoverable Timeout:120
,11-08 11:17:32.923  5687  5697 D BluetoothPan: onBluetoothStateChange on: true
,11-08 11:17:32.924  5730  5743 I BluetoothAdapterState: Entering OnState
11-08 11:17:32.924  3057  3071 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-08 11:17:32.925  5544  5544 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
11-08 11:17:32.926  3057  3057 D BluetoothInputDevice: Proxy object connected
11-08 11:17:32.926  3674  3691 D BluetoothHeadset: onBluetoothStateChange: up=true
11-08 11:17:32.926  3057  3057 D HidProfile: Bluetooth service connected
11-08 11:17:32.927  5687  5698 D BluetoothPbap: onBluetoothStateChange: up=true
,11-08 11:17:32.929  5544  5544 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 11:17:32.929  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 11:17:32.929  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 11:17:32.929  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 11:17:32.929  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 11:17:32.929  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 11:17:32.929  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 11:17:32.929  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-08 11:17:32.930  3057  3071 D BluetoothPbap: onBluetoothStateChange: up=true
,11-08 11:17:32.931  5544  5544 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-08 11:17:32.931  5730  5730 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-08 11:17:32.932  5730  5730 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-08 11:17:32.932   934   951 D BluetoothHeadset: onBluetoothStateChange: up=true
11-08 11:17:32.932  5687  5697 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-08 11:17:32.933  5730  5730 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-08 11:17:32.933  3057  3809 D BluetoothMap: onBluetoothStateChange: up=true
11-08 11:17:32.934  5544  5544 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 11:17:32.934  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 11:17:32.934  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 11:17:32.934  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 11:17:32.934  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 11:17:32.934  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 11:17:32.934  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 11:17:32.934  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-08 11:17:32.934  5730  5730 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-08 11:17:32.935   934   951 D BluetoothA2dp: onBluetoothStateChange: up=true
11-08 11:17:32.935  3057  3057 D BluetoothMap: Proxy object connected
11-08 11:17:32.935  3057  3057 D MapProfile: Bluetooth service connected
11-08 11:17:32.935  3057  3057 D BluetoothMap: getConnectedDevices()
11-08 11:17:32.935   934   951 D BluetoothHeadset: onBluetoothStateChange: up=true
11-08 11:17:32.936  3057  3071 D BluetoothPan: onBluetoothStateChange on: true
11-08 11:17:32.936  5544  5544 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-08 11:17:32.938  3057  3057 D BluetoothPan: BluetoothPAN Proxy object connected
11-08 11:17:32.938  3057  3057 D PanProfile: Bluetooth service connected
11-08 11:17:32.938  3057  3809 D BluetoothA2dp: onBluetoothStateChange: up=true
11-08 11:17:32.939  5544  5544 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 11:17:32.939  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 11:17:32.939  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 11:17:32.939  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 11:17:32.939  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 11:17:32.939  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 11:17:32.939  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 11:17:32.939  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-08 11:17:32.940  3057  3070 D BluetoothHeadset: onBluetoothStateChange: up=true
11-08 11:17:32.940  5687  5698 D BluetoothMap: onBluetoothStateChange: up=true
11-08 11:17:32.940  5730  5730 D ObexServerSockets: Succeed to create listening sockets 
11-08 11:17:32.940  5730  5730 D ObexServerSockets0: startAccept()
11-08 11:17:32.940  5730  5730 D ObexServerSockets0: prepareForNewConnect()
11-08 11:17:32.940   934   951 D BluetoothHeadset: onBluetoothStateChange: up=true
11-08 11:17:32.941  5544  5544 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-08 11:17:32.942   934   934 I Telecom : BluetoothPhoneService: queryPhoneState
11-08 11:17:32.942  5544  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-08 11:17:32.942  5730  5730 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-08 11:17:32.942  5730  5730 D BluetoothSdpJni: SDP Create record success - handle: 0
11-08 11:17:32.944   934   934 D BluetoothA2dp: Proxy object connected
,11-08 11:17:32.944  3057  3057 D BluetoothA2dp: Proxy object connected
11-08 11:17:32.944  5730  5771 D ObexServerSockets0: Accepting socket connection...
11-08 11:17:32.944  5730  5730 D BluetoothMapService: onReceive
11-08 11:17:32.944  5730  5730 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-08 11:17:32.944  5730  5730 D BluetoothMapService: STATE_ON
11-08 11:17:32.945  5544  5544 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,11-08 11:17:32.946  5687  5687 D LocalBluetoothProfileManager: Adding local A2DP profile
,11-08 11:17:32.948  5730  5770 D ObexServerSockets0: Accepting socket connection...,
11-08 11:17:32.948  5544  5544 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 11:17:32.950  5544  5544 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 11:17:32.950  5730  5773 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-08 11:17:32.950  5687  5687 D LocalBluetoothProfileManager: Adding local HEADSET profile
11-08 11:17:32.951  5544  5544 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 11:17:32.952  5730  5773 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-08 11:17:32.952  5730  5773 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-08 11:17:32.961  5687  5687 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-08 11:17:32.963  5687  5687 D BluetoothA2dp: Proxy object connected
,11-08 11:17:32.966  5730  5730 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-08 11:17:32.966  5730  5730 D ObexServerSockets0: prepareForNewConnect()
,11-08 11:17:32.967  3502  3502 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-08 11:17:32.975  3057  3057 D BluetoothPbap: Proxy object connected
,11-08 11:17:32.975  3057  3057 D PbapServerProfile: Bluetooth service connected
11-08 11:17:32.976  5687  5687 D DockEventReceiver: finishStartingService: stopping service
,11-08 11:17:32.977  5687  5687 D BluetoothPbap: Proxy object connected
,11-08 11:17:32.978  5687  5687 D PbapServerProfile: Bluetooth service connected
,11-08 11:17:32.983  5730  5777 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-08 11:17:32.985  5544  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 11:17:32.986  5544  5592 D io.jxcore.node.ConnectivityMonitor: stop
,11-08 11:17:32.986  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-08 11:17:32.987  5544  5592 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiDirectSupported
11-08 11:17:32.988  5544  5592 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothEnabled
11-08 11:17:32.989  5544  5592 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 11:17:32.991  5730  5743 D BluetoothAdapterState: Current state: ON, message: 23
,11-08 11:17:32.991  5730  5743 D BluetoothAdapterProperties: Setting state to 13
11-08 11:17:32.991  5730  5743 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-08 11:17:32.991  5730  5743 D BluetoothAdapterProperties: onBluetoothDisable()
11-08 11:17:32.992  5730  5743 I BluetoothAdapterState: Entering PendingCommandState
,11-08 11:17:32.995  5730  5747 D BluetoothAdapterProperties: Scan Mode:20
11-08 11:17:32.995  5730  5743 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,11-08 11:17:32.996  5544  5544 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-08 11:17:32.996  5544  5544 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 11:17:32.996  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 11:17:32.996  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 11:17:32.996  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 11:17:32.996  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-08 11:17:32.996  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 11:17:32.996  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 11:17:32.996  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-08 11:17:32.997  5544  5544 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-08 11:17:32.997  5544  5544 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-08 11:17:32.998  5687  5687 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-08 11:17:32.999  5544  5544 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-08 11:17:32.999  5544  5544 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 11:17:32.999  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 11:17:32.999  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 11:17:32.999  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 11:17:32.999  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-08 11:17:32.999  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 11:17:32.999  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 11:17:32.999  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-08 11:17:33.000  5544  5544 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-08 11:17:33.000  5544  5544 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-08 11:17:33.001  5544  5544 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 11:17:33.001  5730  5730 D BluetoothMapService: onReceive
11-08 11:17:33.001  5730  5730 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,11-08 11:17:33.001  5730  5730 D BluetoothMapService: STATE_TURNING_OFF
11-08 11:17:33.002  5730  5730 D HeadsetService: Received stop request...Stopping profile...
11-08 11:17:33.002  5687  5687 D DockEventReceiver: finishStartingService: stopping service
11-08 11:17:33.003  5544  5544 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 11:17:33.006  5730  5730 D A2dpService: Received stop request...Stopping profile...
11-08 11:17:33.006  5730  5764 D A2dpStateMachine: Exit Disconnected: -1
11-08 11:17:33.008   934   934 D BluetoothA2dp: Proxy object disconnected
,11-08 11:17:33.009  5730  5730 D HidService: Received stop request...Stopping profile...
11-08 11:17:33.009  5730  5730 D HidService: Stopping Bluetooth HidService
11-08 11:17:33.010  5730  5730 D HealthService: Received stop request...Stopping profile...
,11-08 11:17:33.011  3057  3057 D BluetoothA2dp: Proxy object disconnected
11-08 11:17:33.011  3057  3057 D BluetoothInputDevice: Proxy object disconnected
11-08 11:17:33.011  3057  3057 D HidProfile: Bluetooth service disconnected
,11-08 11:17:33.012  5730  5730 D PanService: Received stop request...Stopping profile...
,11-08 11:17:33.013  3057  3057 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-08 11:17:33.013  3057  3057 D PanProfile: Bluetooth service disconnected
11-08 11:17:33.013  5730  5730 D BluetoothMapService: MAP Service closeService in
11-08 11:17:33.013  5730  5730 D BluetoothMapMasInstance0: MAP Service shutdown
,11-08 11:17:33.013  5730  5730 D ObexServerSockets0: shutdown(block = true)
11-08 11:17:33.013  5730  5730 D ObexServerSockets0: shutdown called from another thread - interrupt().
,11-08 11:17:33.013  5730  5770 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,11-08 11:17:33.014  5730  5730 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-08 11:17:33.014  5730  5771 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-08 11:17:33.014  5730  5758 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-08 11:17:33.014  5687  5687 D BluetoothA2dp: Proxy object disconnected
11-08 11:17:33.014  5687  5687 D BluetoothInputDevice: Proxy object disconnected
11-08 11:17:33.014  5687  5687 D HidProfile: Bluetooth service disconnected
11-08 11:17:33.014  5687  5687 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-08 11:17:33.015  5687  5687 D PanProfile: Bluetooth service disconnected
11-08 11:17:33.016  5730  5730 D BluetoothMapService: Received stop request...Stopping profile...
11-08 11:17:33.016  5730  5730 D BluetoothMapService: stop()
,11-08 11:17:33.017  3502  3502 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-08 11:17:33.017  5730  5730 D BluetoothMapAppObserver: deinitObservers()
11-08 11:17:33.017  5730  5730 D BluetoothMapAppObserver: removeReceiver()
11-08 11:17:33.020  3057  3057 D BluetoothMap: Proxy object disconnected
11-08 11:17:33.020  3057  3057 D MapProfile: Bluetooth service disconnected
11-08 11:17:33.020  5730  5730 D SapService: Received stop request...Stopping profile...
,11-08 11:17:33.020  5730  5730 V SapService: stop()
,11-08 11:17:33.020  5687  5687 D BluetoothMap: Proxy object disconnected
11-08 11:17:33.020  5687  5687 D MapProfile: Bluetooth service disconnected
11-08 11:17:33.022  5730  5730 V BluetoothAdapterState: isTurningOff()=true
11-08 11:17:33.022  5730  5730 V BluetoothAdapterState: isTurningOn()=false
11-08 11:17:33.022  5730  5730 V BluetoothAdapterState: isBleTurningOn()=false
11-08 11:17:33.022  5730  5730 V BluetoothAdapterState: isBleTurningOff()=false
11-08 11:17:33.023  5730  5730 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-08 11:17:33.024  5730  5730 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-08 11:17:33.024  5730  5747 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-08 11:17:33.024  5730  5756 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-08 11:17:33.024  5730  5756 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-08 11:17:33.024  5730  5756 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-08 11:17:33.024  5730  5730 V BluetoothAdapterState: isTurningOff()=true
11-08 11:17:33.024  5730  5730 V BluetoothAdapterState: isTurningOn()=false
11-08 11:17:33.024  5730  5730 V BluetoothAdapterState: isBleTurningOn()=false
11-08 11:17:33.024  5730  5730 V BluetoothAdapterState: isBleTurningOff()=false
,11-08 11:17:33.025  5730  5730 V BluetoothAdapterState: isTurningOff()=true
11-08 11:17:33.026  5730  5730 V BluetoothAdapterState: isTurningOn()=false
11-08 11:17:33.026  5730  5730 V BluetoothAdapterState: isBleTurningOn()=false
11-08 11:17:33.026  5730  5730 V BluetoothAdapterState: isBleTurningOff()=false
11-08 11:17:33.026  5730  5730 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,11-08 11:17:33.026  5730  5730 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-08 11:17:33.026  5730  5730 V BluetoothAdapterState: isTurningOff()=true
11-08 11:17:33.026  5730  5730 V BluetoothAdapterState: isTurningOn()=false
11-08 11:17:33.026  5730  5730 V BluetoothAdapterState: isBleTurningOn()=false
11-08 11:17:33.026  5730  5730 V BluetoothAdapterState: isBleTurningOff()=false
11-08 11:17:33.026  5730  5730 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-08 11:17:33.027  5730  5730 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-08 11:17:33.027  5730  5730 V BluetoothAdapterState: isTurningOff()=true
11-08 11:17:33.027  5730  5730 V BluetoothAdapterState: isTurningOn()=false
11-08 11:17:33.027  5730  5730 V BluetoothAdapterState: isBleTurningOn()=false
11-08 11:17:33.027  5730  5730 V BluetoothAdapterState: isBleTurningOff()=false
11-08 11:17:33.027  5730  5730 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-08 11:17:33.027  5730  5730 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-08 11:17:33.027  5730  5747 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
11-08 11:17:33.028  5730  5747 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-08 11:17:33.028  5730  5756 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-08 11:17:33.028  5730  5747 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-08 11:17:33.028  5730  5756 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-08 11:17:33.028  5730  5747 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-08 11:17:33.028  5730  5756 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-08 11:17:33.028  5730  5756 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-08 11:17:33.028  5730  5756 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-08 11:17:33.028  5730  5756 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-08 11:17:33.030  3057  3057 D BluetoothPbap: Proxy object disconnected
11-08 11:17:33.030  3057  3057 D PbapServerProfile: Bluetooth service disconnected
11-08 11:17:33.030  5687  5687 D BluetoothPbap: Proxy object disconnected
11-08 11:17:33.030  5687  5687 D PbapServerProfile: Bluetooth service disconnected
11-08 11:17:33.031  5730  5730 D BluetoothMapService: MAP Service closeService in
11-08 11:17:33.031  5730  5730 V BluetoothAdapterState: isTurningOff()=true
11-08 11:17:33.031  5730  5730 V BluetoothAdapterState: isTurningOn()=false
11-08 11:17:33.031  5730  5730 V BluetoothAdapterState: isBleTurningOn()=false
11-08 11:17:33.031  5730  5730 V BluetoothAdapterState: isBleTurningOff()=false
11-08 11:17:33.031  5730  5730 D BluetoothMapService: cleanup()
11-08 11:17:33.031  5730  5730 D BluetoothMapService: MAP Service closeService in
11-08 11:17:33.031  5730  5730 V BluetoothAdapterState: isTurningOff()=true
11-08 11:17:33.031  5730  5730 V BluetoothAdapterState: isTurningOn()=false
11-08 11:17:33.031  5730  5730 V BluetoothAdapterState: isBleTurningOn()=false
11-08 11:17:33.031  5730  5730 V BluetoothAdapterState: isBleTurningOff()=false
11-08 11:17:33.032  5730  5743 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,11-08 11:17:33.032  5730  5743 D BluetoothAdapterProperties: Setting state to 15
11-08 11:17:33.032  5730  5743 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-08 11:17:33.032  5730  5743 I BluetoothAdapterState: Entering BleOnState
11-08 11:17:33.033  5687  5697 D BluetoothPan: onBluetoothStateChange on: false
,11-08 11:17:33.034  3057  3809 D BluetoothInputDevice: onBluetoothStateChange: up=false
,11-08 11:17:33.035  3674  3924 D BluetoothHeadset: onBluetoothStateChange: up=false
11-08 11:17:33.035  5687  5698 D BluetoothPbap: onBluetoothStateChange: up=false
11-08 11:17:33.035  3057  3070 D BluetoothPbap: onBluetoothStateChange: up=false
11-08 11:17:33.036   934   951 D BluetoothHeadset: onBluetoothStateChange: up=false
11-08 11:17:33.036  5687  5697 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-08 11:17:33.036  3057  3071 D BluetoothMap: onBluetoothStateChange: up=false
11-08 11:17:33.037  5687  5698 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-08 11:17:33.037   934   951 D BluetoothA2dp: onBluetoothStateChange: up=false
11-08 11:17:33.037   934   951 D BluetoothHeadset: onBluetoothStateChange: up=false
11-08 11:17:33.038  3057  3809 D BluetoothPan: onBluetoothStateChange on: false
,11-08 11:17:33.039  3057  3070 D BluetoothA2dp: onBluetoothStateChange: up=false
,11-08 11:17:33.039  5687  5697 D BluetoothA2dp: onBluetoothStateChange: up=false
,11-08 11:17:33.040  3057  3071 D BluetoothHeadset: onBluetoothStateChange: up=false
11-08 11:17:33.040  5687  5698 D BluetoothMap: onBluetoothStateChange: up=false
11-08 11:17:33.041   934   951 D BluetoothHeadset: onBluetoothStateChange: up=false
11-08 11:17:33.041  5730  5743 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-08 11:17:33.041  5730  5743 D BluetoothAdapterProperties: Setting state to 16
11-08 11:17:33.041  5730  5743 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-08 11:17:33.042  5730  5743 D BluetoothAdapterProperties: onBleDisable
11-08 11:17:33.042  5730  5743 I BluetoothAdapterState: Entering PendingCommandState
,11-08 11:17:33.042  5730  5744 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-08 11:17:33.043  5730  5756 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-08 11:17:33.043  5730  5756 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-08 11:17:33.044  5730  5747 D BluetoothAdapterProperties: Scan Mode:20
11-08 11:17:33.045  5687  5687 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-08 11:17:33.045  5544  5544 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 11:17:33.047  5544  5544 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 11:17:33.049  5544  5544 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 11:17:33.052  5544  5544 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 11:17:33.053  3502  3502 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-08 11:17:33.053  5687  5687 D DockEventReceiver: finishStartingService: stopping service
,11-08 11:17:33.243  5730  5747 I bt_hci  : shut_down
,11-08 11:17:33.243  5730  5751 D bt_hwcfg: hw_epilog_process
,11-08 11:17:33.244  5730  5751 I bt_vendor: low_power_mode_cb
,11-08 11:17:33.247  5730  5751 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,11-08 11:17:33.247  5730  5751 I bt_vendor: epilog_cb
11-08 11:17:33.247  5730  5751 I bt_hci  : epilog_finished_callback
11-08 11:17:33.247  5730  5747 I bt_hci_h4: hal_close
11-08 11:17:33.248  5730  5747 I bt_userial_vendor: device fd = 54 close
,11-08 11:17:33.356  5730  5744 D bt_stack_manager: event_shut_down_stack finished.
,11-08 11:17:33.356  5730  5743 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-08 11:17:33.361  5730  5743 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,11-08 11:17:33.361  5730  5730 D BtGatt.DebugUtils: handleDebugAction() action=null
11-08 11:17:33.362  5730  5730 D BtGatt.GattService: Received stop request...Stopping profile...
11-08 11:17:33.362  5730  5730 D BtGatt.GattService: stop()
,11-08 11:17:33.363  5730  5730 D BtGatt.AdvertiseManager: advertise clients cleared
,11-08 11:17:33.367  5730  5730 V BluetoothAdapterState: isTurningOff()=false
,11-08 11:17:33.367  5730  5730 V BluetoothAdapterState: isTurningOn()=false
11-08 11:17:33.367  5730  5730 V BluetoothAdapterState: isBleTurningOn()=false
11-08 11:17:33.367  5730  5730 V BluetoothAdapterState: isBleTurningOff()=true
11-08 11:17:33.368  5730  5743 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,11-08 11:17:33.368  5730  5743 D BluetoothAdapterProperties: Setting state to 10
11-08 11:17:33.368  5730  5743 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-08 11:17:33.369  5730  5743 I BluetoothAdapterState: Entering OffState
,11-08 11:17:33.369   934   951 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,11-08 11:17:33.376  5730  5730 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-08 11:17:33.376  5730  5730 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-08 11:17:33.376  5730  5730 I BluetoothServiceJni: cleanupNative: return from cleanup
11-08 11:17:33.378  5730  5744 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-08 11:17:33.381  5730  5730 I art     : System.exit called, status: 0
,11-08 11:17:33.382  5730  5730 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-08 11:17:33.406   934  3687 I ActivityManager: Process com.android.bluetooth (pid 5730) has died
,11-08 11:17:33.491  5544  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-08 11:17:33.492  5544  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 11:17:33.492  5544  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 11:17:33.492  5544  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 11:17:33.492  5544  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 11:17:33.492  5544  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-08 11:17:33.492  5544  5615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 11:17:33.492  5544  5615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 11:17:33.492  5544  5615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-08 11:17:33.492  5544  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-08 11:17:33.492  5544  5615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-08 11:17:33.493  5544  5592 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 11:17:33.515   934   951 I ActivityManager: Start proc 5786:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-08 11:17:33.586  5786  5786 D AdapterServiceConfig: Adding HeadsetService
,11-08 11:17:33.587  5786  5786 D AdapterServiceConfig: Adding A2dpService
11-08 11:17:33.587  5786  5786 D AdapterServiceConfig: Adding HidService
,11-08 11:17:33.588  5786  5786 D AdapterServiceConfig: Adding HealthService
,11-08 11:17:33.589  5786  5786 D AdapterServiceConfig: Adding PanService
,11-08 11:17:33.589  5786  5786 D AdapterServiceConfig: Adding GattService
,11-08 11:17:33.589  5786  5786 D AdapterServiceConfig: Adding BluetoothMapService
11-08 11:17:33.590  5786  5786 D AdapterServiceConfig: Adding SapService
,11-08 11:17:33.599   934   951 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1eb4e63:true
,11-08 11:17:33.600  5786  5786 D BluetoothAdapterState: make() - Creating AdapterState
,11-08 11:17:33.603  5786  5786 I bt_bluedroid: init
11-08 11:17:33.603  5786  5798 I BluetoothAdapterState: Entering OffState
,11-08 11:17:33.605  5786  5799 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-08 11:17:33.605  5786  5799 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-08 11:17:33.605  5786  5799 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-08 11:17:33.605  5786  5799 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-08 11:17:33.606  5786  5786 I bt_bluedroid: get_profile_interface socket
,11-08 11:17:33.607  5786  5802 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-08 11:17:33.608  5786  5786 I bt_bluedroid: get_profile_interface sdp
11-08 11:17:33.609  5786  5802 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-08 11:17:33.612  5786  5797 I bt_bluedroid: config_hci_snoop_log
11-08 11:17:33.613   934   951 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-08 11:17:33.617  5786  5798 D BluetoothAdapterState: Current state: OFF, message: 0
,11-08 11:17:33.617  5786  5798 D BluetoothAdapterProperties: Setting state to 14
11-08 11:17:33.617  5786  5798 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
11-08 11:17:33.618  5786  5798 D BluetoothBondStateMachine: make
,11-08 11:17:33.620  5786  5803 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-08 11:17:33.622  5786  5798 I BluetoothAdapterState: Entering PendingCommandState
,11-08 11:17:33.623  5786  5786 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-08 11:17:33.625  5786  5786 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96bca27
11-08 11:17:33.626  5786  5786 D BtGatt.DebugUtils: handleDebugAction() action=null
11-08 11:17:33.626  5786  5786 D BtGatt.GattService: Received start request. Starting profile...
11-08 11:17:33.626  5786  5786 D BtGatt.GattService: start()
11-08 11:17:33.626  5786  5786 I bt_bluedroid: get_profile_interface gatt
,11-08 11:17:33.627  5786  5786 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96bca27
11-08 11:17:33.628  5786  5786 D BtGatt.AdvertiseManager: advertise manager created
,11-08 11:17:33.632  5786  5786 V BluetoothAdapterState: isTurningOff()=false
11-08 11:17:33.633  5786  5786 V BluetoothAdapterState: isTurningOn()=false
11-08 11:17:33.633  5786  5786 V BluetoothAdapterState: isBleTurningOn()=true
11-08 11:17:33.633  5786  5786 V BluetoothAdapterState: isBleTurningOff()=false
11-08 11:17:33.633  5786  5798 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-08 11:17:33.634  5786  5798 I bt_bluedroid: bt_bluedroid
,11-08 11:17:33.634  5786  5799 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,11-08 11:17:33.634  5786  5799 I bt_hci  : start_up
,11-08 11:17:33.641  5786  5799 I bt_vendor: alloc value 0xf3c77871
,11-08 11:17:33.641  5786  5799 I bt_vendor: init
11-08 11:17:33.641  5786  5799 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-08 11:17:33.641  5786  5799 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-08 11:17:33.754  5786  5799 D bt_hci  : start_up starting async portion
11-08 11:17:33.754  5786  5806 I bt_hci  : event_finish_startup
,11-08 11:17:33.755  5786  5806 I bt_hci_h4: hal_open
11-08 11:17:33.755  5786  5806 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-08 11:17:33.757  5786  5806 I bt_userial_vendor: device fd = 54 open
11-08 11:17:33.754  5807  5807 W irq/448-msm_hs_: type=1400 audit(0.0:122): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-08 11:17:33.771  5786  5806 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-08 11:17:33.773  5786  5806 D bt_hwcfg: Chipset BCM4358A3
,11-08 11:17:33.774  5786  5806 D bt_hwcfg: Target name = [BCM4358A3]
11-08 11:17:33.774  5786  5806 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-08 11:17:34.002  5786  5798 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,11-08 11:17:34.169  5786  5806 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-08 11:17:34.170  5786  5806 D bt_hwcfg: Settlement delay -- 100 ms
,11-08 11:17:34.170  5786  5806 I bt_hwcfg: Setting fw settlement delay to 100 
,11-08 11:17:34.292  5786  5806 I bt_hwcfg: bt vendor lib: set UART baud 3000000
11-08 11:17:34.292  5786  5806 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
,11-08 11:17:34.294  5786  5806 I bt_hwcfg: vendor lib fwcfg completed
11-08 11:17:34.294  5786  5806 I bt_vendor: firmware callback
11-08 11:17:34.294  5786  5806 I bt_hci  : firmware_config_callback
,11-08 11:17:34.303  5786  5809 I bt_btu  : btu_task pending for preload complete event
,11-08 11:17:34.303  5786  5809 I bt_btu_task: Bluetooth chip preload is complete
,11-08 11:17:34.304  5786  5809 I bt_btu  : btu_task received preload complete event
11-08 11:17:34.310  5786  5809 I         : BTE_InitTraceLevels -- TRC_HCI
11-08 11:17:34.311  5786  5809 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-08 11:17:34.311  5786  5809 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,11-08 11:17:34.311  5786  5809 I         : BTE_InitTraceLevels -- TRC_AVDT
11-08 11:17:34.311  5786  5809 I         : BTE_InitTraceLevels -- TRC_AVRC
,11-08 11:17:34.311  5786  5809 I         : BTE_InitTraceLevels -- TRC_A2D
11-08 11:17:34.311  5786  5809 I         : BTE_InitTraceLevels -- TRC_BNEP
,11-08 11:17:34.311  5786  5809 I         : BTE_InitTraceLevels -- TRC_BTM
11-08 11:17:34.312  5786  5809 I         : BTE_InitTraceLevels -- TRC_GAP
11-08 11:17:34.312  5786  5809 I         : BTE_InitTraceLevels -- TRC_PAN
11-08 11:17:34.312  5786  5809 I         : BTE_InitTraceLevels -- TRC_SDP
11-08 11:17:34.312  5786  5809 I         : BTE_InitTraceLevels -- TRC_GATT
11-08 11:17:34.312  5786  5809 I         : BTE_InitTraceLevels -- TRC_SMP
11-08 11:17:34.312  5786  5809 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-08 11:17:34.312  5786  5809 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-08 11:17:34.397  5786  5809 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3bf5549
11-08 11:17:34.397  5786  5809 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3bf5549 
11-08 11:17:34.398  5683  5683 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-08 11:17:34.401  5683  5683 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-08 11:17:34.404  5683  5683 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
11-08 11:17:34.408  5683  5683 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-08 11:17:34.415  5786  5802 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-08 11:17:34.417  5786  5802 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-08 11:17:34.417  5786  5802 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-08 11:17:34.420  5786  5802 D BluetoothAdapterProperties: Name is: Nexus 6P
11-08 11:17:34.423  5786  5802 D BluetoothAdapterProperties: Scan Mode:20
11-08 11:17:34.423  5786  5802 D BluetoothAdapterProperties: Discoverable Timeout:120
11-08 11:17:34.423  5786  5802 D bt_hci  : do_postload posting postload work item
11-08 11:17:34.423  5786  5806 I bt_hci  : event_postload
11-08 11:17:34.423  5786  5806 I bt_vendor: sco_config_cb
11-08 11:17:34.423  5786  5806 I bt_hci  : sco_config_callback postload finished.
11-08 11:17:34.424  5786  5802 D bt_bte_conf: Device ID record 1 : primary
11-08 11:17:34.425  5786  5802 D bt_bte_conf:   vendorId            = 000f
11-08 11:17:34.425  5786  5802 D bt_bte_conf:   vendorIdSource      = 0001
11-08 11:17:34.425  5786  5802 D bt_bte_conf:   product             = 1200
,11-08 11:17:34.425  5786  5802 D bt_bte_conf:   version             = 1436
11-08 11:17:34.425  5786  5802 D bt_bte_conf:   clientExecutableURL = 
11-08 11:17:34.425  5786  5802 D bt_bte_conf:   serviceDescription  = 
11-08 11:17:34.425  5786  5802 D bt_bte_conf:   documentationURL    = 
11-08 11:17:34.425  5544  5544 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 11:17:34.425  5786  5802 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-08 11:17:34.425  5786  5799 D bt_stack_manager: event_start_up_stack finished
11-08 11:17:34.427  5544  5544 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 11:17:34.427  5786  5798 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-08 11:17:34.428  5786  5798 D BluetoothAdapterProperties: Setting state to 15
11-08 11:17:34.428  5786  5798 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-08 11:17:34.428  5786  5798 I BluetoothAdapterState: Entering BleOnState
11-08 11:17:34.431  5786  5798 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-08 11:17:34.431  5786  5798 D BluetoothAdapterProperties: Setting state to 11
,11-08 11:17:34.432  5786  5798 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-08 11:17:34.435  5786  5806 I bt_vendor: low_power_mode_cb
,11-08 11:17:34.436  5786  5786 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96bca27
,11-08 11:17:34.443  5544  5544 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 11:17:34.444   934   934 D BluetoothHeadset: Proxy object connected
11-08 11:17:34.445  5786  5786 D HeadsetService: Received start request. Starting profile...
11-08 11:17:34.445  5544  5544 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 11:17:34.445  5687  5698 D BluetoothHeadset: Proxy object connected
11-08 11:17:34.446   934   934 D BluetoothHeadset: Proxy object connected
11-08 11:17:34.446   934   934 D BluetoothHeadset: Proxy object connected
11-08 11:17:34.447  3057  3070 D BluetoothHeadset: Proxy object connected
,11-08 11:17:34.447  3674  3924 D BluetoothHeadset: Proxy object connected
11-08 11:17:34.447  5786  5786 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-08 11:17:34.448  5786  5786 D HeadsetStateMachine: make
11-08 11:17:34.448  5687  5687 D HeadsetProfile: Bluetooth service connected
11-08 11:17:34.450  3057  3057 D HeadsetProfile: Bluetooth service connected
11-08 11:17:34.452  5786  5798 I BluetoothAdapterState: Entering PendingCommandState
,11-08 11:17:34.457  5786  5786 D HeadsetStateMachine: max_hf_connections = 1
11-08 11:17:34.457  5786  5786 I bt_bluedroid: get_profile_interface handsfree
11-08 11:17:34.457  5786  5802 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-08 11:17:34.457  5786  5802 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,11-08 11:17:34.460  5786  5786 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96bca27
,11-08 11:17:34.460  5786  5786 D A2dpService: Received start request. Starting profile...
11-08 11:17:34.461  5786  5786 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-08 11:17:34.461  5786  5786 I bt_bluedroid: get_profile_interface avrcp
,11-08 11:17:34.467   934  2875 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-08 11:17:34.467  5786  5786 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
11-08 11:17:34.468  5786  5786 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-08 11:17:34.468   934  2875 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-08 11:17:34.468  5786  5786 D A2dpStateMachine: make
11-08 11:17:34.468   934  2875 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-08 11:17:34.469  5786  5786 I bt_bluedroid: get_profile_interface a2dp
,11-08 11:17:34.470  5786  5802 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-08 11:17:34.474  5786  5819 D A2dpStateMachine: Enter Disconnected: -2
,11-08 11:17:34.475  5786  5786 I BluetoothHidServiceJni: classInitNative: succeeds
,11-08 11:17:34.478  5786  5786 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96bca27
,11-08 11:17:34.478   934  2875 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-08 11:17:34.478  5786  5786 D HidService: Received start request. Starting profile...
11-08 11:17:34.478  5786  5786 I bt_bluedroid: get_profile_interface hidhost
11-08 11:17:34.478  5786  5786 D HidService: setHidService(): set to: null
11-08 11:17:34.478  5786  5802 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3bd656d
11-08 11:17:34.478  5786  5802 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,11-08 11:17:34.480  5786  5786 I BluetoothHealthServiceJni: classInitNative: succeeds
11-08 11:17:34.481  3502  3502 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-08 11:17:34.481  5786  5786 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96bca27
,11-08 11:17:34.482  5786  5786 D HealthService: Received start request. Starting profile...
,11-08 11:17:34.483  5786  5786 I bt_bluedroid: get_profile_interface health
,11-08 11:17:34.484  5786  5786 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,11-08 11:17:34.484  5786  5786 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96bca27
11-08 11:17:34.485  5786  5786 D PanService: Received start request. Starting profile...
11-08 11:17:34.485  5786  5786 D BluetoothPanServiceJni: initializeNative(L110): pan
11-08 11:17:34.485  5786  5786 I bt_bluedroid: get_profile_interface pan
11-08 11:17:34.485  5786  5802 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
11-08 11:17:34.487  5786  5786 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96bca27
,11-08 11:17:34.488  5786  5786 D BluetoothMapService: Received start request. Starting profile...
,11-08 11:17:34.488  5786  5786 D BluetoothMapService: start()
11-08 11:17:34.490  5786  5786 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
11-08 11:17:34.491  5786  5786 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-08 11:17:34.491  5786  5786 D BluetoothMapAppObserver: createReceiver()
11-08 11:17:34.492  5786  5786 D BluetoothMapAppObserver: initObservers()
11-08 11:17:34.492  5786  5786 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-08 11:17:34.499  5786  5786 V SapService: SapBinder()
,11-08 11:17:34.499  5786  5786 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96bca27
11-08 11:17:34.500  5786  5786 D SapService: Received start request. Starting profile...
,11-08 11:17:34.500  5786  5786 V SapService: start()
,11-08 11:17:34.503  5786  5786 V BluetoothAdapterState: isTurningOff()=false
,11-08 11:17:34.503  5786  5798 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
11-08 11:17:34.503  5786  5786 V BluetoothAdapterState: isTurningOn()=true
11-08 11:17:34.503  5786  5817 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-08 11:17:34.504  5786  5786 V BluetoothAdapterState: isBleTurningOn()=false
11-08 11:17:34.504  5786  5786 V BluetoothAdapterState: isBleTurningOff()=false
11-08 11:17:34.504  5786  5786 V BluetoothAdapterState: isTurningOff()=false
,11-08 11:17:34.504  5786  5786 V BluetoothAdapterState: isTurningOn()=true
11-08 11:17:34.504  5786  5786 V BluetoothAdapterState: isBleTurningOn()=false
11-08 11:17:34.504  5786  5786 V BluetoothAdapterState: isBleTurningOff()=false
11-08 11:17:34.504  5786  5786 V BluetoothAdapterState: isTurningOff()=false
11-08 11:17:34.504  5786  5786 V BluetoothAdapterState: isTurningOn()=true
11-08 11:17:34.504  5786  5786 V BluetoothAdapterState: isBleTurningOn()=false
,11-08 11:17:34.505  5786  5786 V BluetoothAdapterState: isBleTurningOff()=false
11-08 11:17:34.505  5786  5786 V BluetoothAdapterState: isTurningOff()=false
11-08 11:17:34.505  5786  5786 V BluetoothAdapterState: isTurningOn()=true
11-08 11:17:34.505  5786  5786 V BluetoothAdapterState: isBleTurningOn()=false
11-08 11:17:34.505  5786  5786 V BluetoothAdapterState: isBleTurningOff()=false
11-08 11:17:34.506  5786  5786 V BluetoothAdapterState: isTurningOff()=false
11-08 11:17:34.506  5786  5786 V BluetoothAdapterState: isTurningOn()=true
,11-08 11:17:34.506  5786  5786 V BluetoothAdapterState: isBleTurningOn()=false
11-08 11:17:34.506  5786  5786 V BluetoothAdapterState: isBleTurningOff()=false
11-08 11:17:34.506  5786  5786 V BluetoothAdapterState: isTurningOff()=false
11-08 11:17:34.506  5786  5786 V BluetoothAdapterState: isTurningOn()=true
11-08 11:17:34.506  5786  5786 V BluetoothAdapterState: isBleTurningOn()=false
11-08 11:17:34.506  5786  5786 V BluetoothAdapterState: isBleTurningOff()=false
,11-08 11:17:34.507  5786  5786 V BluetoothAdapterState: isTurningOff()=false
11-08 11:17:34.507  5786  5786 V BluetoothAdapterState: isTurningOn()=true
11-08 11:17:34.507  5786  5786 V BluetoothAdapterState: isBleTurningOn()=false
11-08 11:17:34.507  5786  5786 V BluetoothAdapterState: isBleTurningOff()=false
,11-08 11:17:34.508  5786  5798 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-08 11:17:34.508  5786  5798 D BluetoothAdapterProperties: ScanMode =  20
11-08 11:17:34.508  5786  5798 D BluetoothAdapterProperties: State =  11
11-08 11:17:34.509  5786  5802 D BluetoothAdapterProperties: Scan Mode:21
11-08 11:17:34.509  5786  5802 D BluetoothAdapterProperties: Discoverable Timeout:120
,11-08 11:17:34.509  5786  5798 D BluetoothAdapterProperties: Setting state to 12
11-08 11:17:34.509  5786  5798 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-08 11:17:34.509  5544  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-08 11:17:34.510  5786  5798 I BluetoothAdapterState: Entering OnState
11-08 11:17:34.510  5687  5697 D BluetoothPan: onBluetoothStateChange on: true
,11-08 11:17:34.512   934  2875 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-08 11:17:34.515  3057  3809 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-08 11:17:34.515  5544  5544 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 11:17:34.515  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 11:17:34.515  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 11:17:34.515  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 11:17:34.515  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 11:17:34.515  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 11:17:34.515  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 11:17:34.515  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-08 11:17:34.517  3674  3691 D BluetoothHeadset: onBluetoothStateChange: up=true
11-08 11:17:34.517  5544  5544 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-08 11:17:34.517  5687  5816 D BluetoothPbap: onBluetoothStateChange: up=true
11-08 11:17:34.518  5683  5683 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
11-08 11:17:34.518  3057  3057 D BluetoothInputDevice: Proxy object connected
11-08 11:17:34.519  3057  3057 D HidProfile: Bluetooth service connected
11-08 11:17:34.519  3057  3071 D BluetoothPbap: onBluetoothStateChange: up=true
,11-08 11:17:34.520  5786  5786 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-08 11:17:34.521  5786  5786 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-08 11:17:34.521   934   951 D BluetoothHeadset: onBluetoothStateChange: up=true
11-08 11:17:34.521  5687  5697 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-08 11:17:34.521  5544  5544 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 11:17:34.521  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 11:17:34.521  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 11:17:34.521  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 11:17:34.521  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 11:17:34.521  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 11:17:34.521  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 11:17:34.521  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-08 11:17:34.523  5544  5544 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-08 11:17:34.523  3057  3809 D BluetoothMap: onBluetoothStateChange: up=true
,11-08 11:17:34.524  5786  5786 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-08 11:17:34.525  5687  5816 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-08 11:17:34.525   934   951 D BluetoothA2dp: onBluetoothStateChange: up=true
11-08 11:17:34.526   934   951 D BluetoothHeadset: onBluetoothStateChange: up=true
11-08 11:17:34.526  5786  5786 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-08 11:17:34.526  3057  3070 D BluetoothPan: onBluetoothStateChange on: true
11-08 11:17:34.527  5786  5786 D ObexServerSockets: Succeed to create listening sockets 
11-08 11:17:34.527  5786  5786 D ObexServerSockets0: startAccept()
11-08 11:17:34.527  5786  5786 D ObexServerSockets0: prepareForNewConnect()
11-08 11:17:34.529  3057  3057 D BluetoothPan: BluetoothPAN Proxy object connected
11-08 11:17:34.529  3057  3071 D BluetoothA2dp: onBluetoothStateChange: up=true
11-08 11:17:34.529  5687  5687 D BluetoothPan: BluetoothPAN Proxy object connected
,11-08 11:17:34.529  3057  3057 D PanProfile: Bluetooth service connected
11-08 11:17:34.529  5687  5687 D PanProfile: Bluetooth service connected
11-08 11:17:34.529  5687  5687 D BluetoothInputDevice: Proxy object connected
11-08 11:17:34.529  5687  5687 D HidProfile: Bluetooth service connected
,11-08 11:17:34.530  5786  5786 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-08 11:17:34.530  5786  5786 D BluetoothSdpJni: SDP Create record success - handle: 0
11-08 11:17:34.531  5786  5824 D ObexServerSockets0: Accepting socket connection...
,11-08 11:17:34.531  5687  5698 D BluetoothA2dp: onBluetoothStateChange: up=true
11-08 11:17:34.532  5786  5825 D ObexServerSockets0: Accepting socket connection...
11-08 11:17:34.533  3057  3057 D BluetoothMap: Proxy object connected
11-08 11:17:34.533  3057  3057 D MapProfile: Bluetooth service connected
11-08 11:17:34.533  3057  3057 D BluetoothMap: getConnectedDevices()
11-08 11:17:34.533  3057  3071 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-08 11:17:34.534  5687  5697 D BluetoothMap: onBluetoothStateChange: up=true
11-08 11:17:34.535   934   934 D BluetoothA2dp: Proxy object connected
11-08 11:17:34.535  5687  5687 D BluetoothA2dp: Proxy object connected
11-08 11:17:34.536  3057  3057 D BluetoothA2dp: Proxy object connected
11-08 11:17:34.537   934   951 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-08 11:17:34.538   934   934 I Telecom : BluetoothPhoneService: queryPhoneState
11-08 11:17:34.538  5687  5687 D BluetoothMap: Proxy object connected
11-08 11:17:34.538  5687  5687 D MapProfile: Bluetooth service connected
11-08 11:17:34.538  5687  5687 D BluetoothMap: getConnectedDevices()
11-08 11:17:34.538   934   934 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,11-08 11:17:34.539  5544  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-08 11:17:34.539  5786  5786 D BluetoothMapService: onReceive
11-08 11:17:34.539  5786  5786 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-08 11:17:34.539  5786  5786 D BluetoothMapService: STATE_ON
,11-08 11:17:34.542  5786  5827 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-08 11:17:34.542  5544  5544 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 11:17:34.543  5544  5544 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 11:17:34.543  5786  5827 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-08 11:17:34.543  5786  5827 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-08 11:17:34.547  5687  5687 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-08 11:17:34.553  3502  3502 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-08 11:17:34.553  5687  5687 D DockEventReceiver: finishStartingService: stopping service
,11-08 11:17:34.560  5687  5687 D BluetoothPbap: Proxy object connected
,11-08 11:17:34.560  5687  5687 D PbapServerProfile: Bluetooth service connected
,11-08 11:17:34.567  5786  5786 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-08 11:17:34.567  5786  5786 D ObexServerSockets0: prepareForNewConnect()
,11-08 11:17:34.570  3057  3057 D BluetoothPbap: Proxy object connected
,11-08 11:17:34.570  3057  3057 D PbapServerProfile: Bluetooth service connected
,11-08 11:17:34.571  5786  5832 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-08 11:17:34.583  5786  5836 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-08 11:17:34.584  5786  5836 I BtOppRfcommListener: Accept thread started.
,11-08 11:17:34.967  5683  5683 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-08 11:17:35.001  5683  5683 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-08 11:17:35.002  5683  5683 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-08 11:17:35.013  5544  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 11:17:35.013  5544  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 11:17:35.013  5544  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 11:17:35.013  5544  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 11:17:35.013  5544  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 11:17:35.013  5544  5615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 11:17:35.013  5544  5615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 11:17:35.013  5544  5615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-08 11:17:35.017  5544  5615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-08 11:17:35.019  5544  5592 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiEnabled
,11-08 11:17:35.021   934  3122 D WifiService: setWifiEnabled: false pid=5544, uid=10077
11-08 11:17:35.021   934  3122 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-08 11:17:35.021   934  2875 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
11-08 11:17:35.021   934  2875 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-08 11:17:35.021   934  2877 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
11-08 11:17:35.021  5544  5592 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 11:17:35.040   934  2875 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-08 11:17:35.052   510   927 D CommandListener: Setting iface cfg
,11-08 11:17:35.057   934  2875 D WifiStateMachine: Start Dhcp Watchdog 2
,11-08 11:17:35.069   934  2875 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{1}, ntable=[]
,11-08 11:17:35.069   934  2877 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
11-08 11:17:35.069   934  2877 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,11-08 11:17:35.069   934  2875 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-08 11:17:35.070   934  2875 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-08 11:17:35.074   934  5841 D DhcpClient: Receive thread started
,11-08 11:17:35.081   510   927 D CommandListener: Clearing all IP addresses on wlan0
,11-08 11:17:35.087   934  5841 D DhcpClient: Receive thread stopped
11-08 11:17:35.088   934  2877 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED
,11-08 11:17:35.089   934  2877 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 0
,11-08 11:17:35.095   934   934 D RttService: SCAN_AVAILABLE : 1
11-08 11:17:35.095   934  2987 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,11-08 11:17:35.098   934  2877 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,11-08 11:17:35.099   934  2877 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
11-08 11:17:35.099   934  2875 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,11-08 11:17:35.102   934  2875 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-08 11:17:35.103   510   927 D CommandListener: Clearing all IP addresses on wlan0
,11-08 11:17:35.106   934  2875 D DhcpClient: doQuit
11-08 11:17:35.106   934  2875 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-08 11:17:35.106   934  5840 D DhcpClient: onQuitting
11-08 11:17:35.107  5683  5683 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,11-08 11:17:35.114  5544  5544 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 11:17:35.114  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 11:17:35.114  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 11:17:35.114  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-08 11:17:35.114  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 11:17:35.114  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 11:17:35.114  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 11:17:35.114  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-08 11:17:35.116  5683  5683 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-08 11:17:35.118  5544  5544 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,11-08 11:17:35.120  5683  5683 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,11-08 11:17:35.124  5544  5544 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 11:17:35.124  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 11:17:35.124  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 11:17:35.124  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-08 11:17:35.124  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 11:17:35.124  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 11:17:35.124  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 11:17:35.124  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-08 11:17:35.126  5544  5544 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,11-08 11:17:35.146  5683  5683 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-08 11:17:35.157  5683  5683 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-08 11:17:35.260   934  2875 D wifi    : In wifi stop Hal
,11-08 11:17:35.260  4952  4952 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-08 11:17:35.260   934  2875 D wifi    : halHandle = 0x7f7fc48680, mVM = 0x7f9c2cd140, mCls = 0x145e
11-08 11:17:35.260   934  5682 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-08 11:17:35.261   934  5682 D WifiHAL : Got a signal to exit!!!
,11-08 11:17:35.261   934  5682 I WifiHAL : Exit wifi_event_loop
11-08 11:17:35.262   934  2875 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 11
11-08 11:17:35.263   934  2875 E WifiHAL : Event processing terminated
11-08 11:17:35.263   934  2875 D wifi    : In wifi cleaned up handler
11-08 11:17:35.263   934  2875 I WifiHAL : Internal cleanup completed
11-08 11:17:35.265  4024  4152 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-08 11:17:35.267  5544  5544 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 11:17:35.269  5544  5544 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 11:17:35.298   934  5682 D wifi    : set interface wlan0 flags (DOWN)
11-08 11:17:35.298   934  2875 D WifiNative-HAL: HAL event thread stopped successfully
,11-08 11:17:35.504   934   951 D Tethering: InitialState.processMessage what=4
,11-08 11:17:35.512   934   951 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-08 11:17:35.531  5544  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 11:17:35.531  5544  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 11:17:35.531  5544  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 11:17:35.531  5544  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-08 11:17:35.531  5544  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 11:17:35.531  5544  5615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 11:17:35.531  5544  5615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 11:17:35.531  5544  5615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-08 11:17:35.535  5544  5615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,11-08 11:17:35.537   934  3122 D WifiService: setWifiEnabled: true pid=5544, uid=10077
,11-08 11:17:35.538   934  3122 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-08 11:17:35.539  5544  5592 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 11:17:35.543   510   927 D SoftapController: Softap fwReload - Ok
,11-08 11:17:35.547   510   927 D CommandListener: Setting iface cfg
,11-08 11:17:35.547   510   927 D CommandListener: Trying to bring down wlan0
,11-08 11:17:35.549   510   927 D CommandListener: Clearing all IP addresses on wlan0
,11-08 11:17:35.553   934  2875 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-08 11:17:36.042   934  3515 D WifiService: setWifiEnabled: true pid=5544, uid=10077
,11-08 11:17:36.046   934  3515 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-08 11:17:36.163   934  2875 D wifi    : set interface wlan0 flags (UP)
,11-08 11:17:36.163   934  2875 I WifiHAL : Initializing wifi
11-08 11:17:36.163   934  2875 I WifiHAL : Creating socket
,11-08 11:17:36.171   934  2875 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-08 11:17:36.171   934   951 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
11-08 11:17:36.171   934  2875 D wifi    : Did set static halHandle = 0x7f7fc48680
,11-08 11:17:36.172   934  2875 D wifi    : halHandle = 0x7f7fc48680, mVM = 0x7f9c2cd140, mCls = 0x201252
,11-08 11:17:36.172   934  2875 D wifi    : array field set
11-08 11:17:36.172   934  2875 I WifiNative-HAL: interface[0] = wlan0
11-08 11:17:36.174   934  5844 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547604432512
11-08 11:17:36.174   934  5844 D wifi    : waitForHalEvents called, vm = 0x7f9c2cd140, obj = 0x201252, env = 0x7f805d0b00
11-08 11:17:36.177   934  2875 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
11-08 11:17:36.178   934  2875 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,11-08 11:17:36.183  5544  5544 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 11:17:36.187  5544  5544 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 11:17:36.239  5845  5845 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-08 11:17:36.312  5845  5845 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-08 11:17:36.332  5845  5845 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-08 11:17:36.332  5845  5845 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-08 11:17:36.552   934  3068 D WifiService: setWifiEnabled: true pid=5544, uid=10077
,11-08 11:17:36.552   934  3068 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-08 11:17:37.055   934   944 D WifiService: setWifiEnabled: true pid=5544, uid=10077
,11-08 11:17:37.055   934   944 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-08 11:17:37.194   934  2875 D WifiConfigStore: Loading config and enabling all networks 
,11-08 11:17:37.202  5544  5544 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 11:17:37.202  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 11:17:37.202  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 11:17:37.202  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 11:17:37.202  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 11:17:37.202  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 11:17:37.202  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 11:17:37.202  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-08 11:17:37.209  5544  5544 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-08 11:17:37.215  5544  5544 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 11:17:37.215  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 11:17:37.215  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 11:17:37.215  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 11:17:37.215  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 11:17:37.215  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 11:17:37.215  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 11:17:37.215  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-08 11:17:37.219  5544  5544 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-08 11:17:37.238   934  2875 D WifiConfigStore: loaded 0 passpoint configs
,11-08 11:17:37.239   934  2875 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
11-08 11:17:37.240   934  2875 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
11-08 11:17:37.241   934  2875 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
11-08 11:17:37.241   934  2875 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
11-08 11:17:37.242   934  2875 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
11-08 11:17:37.243   934  2875 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,11-08 11:17:37.243   934  2875 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-08 11:17:37.244   934  2875 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-08 11:17:37.244   934  2875 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
11-08 11:17:37.244   934  2875 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-08 11:17:37.244   934  2875 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-08 11:17:37.244   934  2875 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-08 11:17:37.261  4952  4952 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-08 11:17:37.261   934  2875 D WifiNative-HAL: Setting external_sim to 1
11-08 11:17:37.262   934  2875 D wifi    : setting dfs flag to true, 0x7f85b3a240
11-08 11:17:37.263   934  2875 D WifiStateMachine: Setting OUI to DA-A1-19
11-08 11:17:37.263   934  2875 D wifi    : setting scan oui 0x7f85b3a240
11-08 11:17:37.263   934  2875 D WifiHAL : Sending mac address OUI
,11-08 11:17:37.267   934  2875 E native  : do suspend false
,11-08 11:17:37.276   934  2875 D wifi    : android_net_wifi_setLinkLayerStats: 1
11-08 11:17:37.276   510   927 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,11-08 11:17:37.277   934   934 D RttService: SCAN_AVAILABLE : 3
11-08 11:17:37.277   934  2987 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,11-08 11:17:37.278   510   927 D CommandListener: Setting iface cfg
,11-08 11:17:37.282   934  2874 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '137 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 137 Failed to set address (No such device)'
11-08 11:17:37.282   934  2874 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-08 11:17:37.293   934   949 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=111145 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=9 mControllerEnergyUsed=34 }
,11-08 11:17:37.294   934  2874 D WifiNative-HAL: p2pGetDeviceAddress
,11-08 11:17:37.295   934  2874 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-08 11:17:37.565  5544  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 11:17:37.565  5544  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 11:17:37.565  5544  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 11:17:37.565  5544  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 11:17:37.565  5544  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 11:17:37.565  5544  5615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 11:17:37.565  5544  5615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 11:17:37.565  5544  5615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-08 11:17:37.571  5544  5615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-08 11:17:37.574  5544  5592 D BluetoothAdapter: enable(): BT is already enabled..!
,11-08 11:17:37.575   934  3122 D WifiService: setWifiEnabled: true pid=5544, uid=10077
,11-08 11:17:37.576   934  3122 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-08 11:17:37.576  5544  5592 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-08 11:17:37.576  5544  5592 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-08 11:17:37.577  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-08 11:17:37.577  5544  5592 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-08 11:17:37.577  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-08 11:17:37.577  5544  5592 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5d1466f removed from the list
,11-08 11:17:37.577  5544  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-08 11:17:37.577  5544  5592 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@66aff7c removed from the list
11-08 11:17:37.577  5544  5592 D io.jxcore.node.ConnectivityMonitor: stop
11-08 11:17:37.577  5544  5592 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-08 11:17:37.577  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-08 11:17:37.579  5544  5592 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testSetTcpPortNumber
11-08 11:17:37.580  5544  5592 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetTcpPortNumber
11-08 11:17:37.581  5544  5592 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetLocalHostPort
11-08 11:17:37.582  5544  5592 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testConstructor
,11-08 11:17:37.583  5544  5592 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityCreated
11-08 11:17:37.584  5544  5592 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
11-08 11:17:37.585  5544  5592 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityResumed
11-08 11:17:37.585  5544  5592 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,11-08 11:17:37.585  5544  5592 I io.jxcore.node.LifeCycleMonitorTest: Starting test: constructor
11-08 11:17:37.589  5544  5592 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivitySaveInstanceState
11-08 11:17:37.589  5544  5592 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@db9b972 Bundle[{}]
11-08 11:17:37.590  5544  5592 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testStartStop
11-08 11:17:37.590  5544  5592 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-08 11:17:37.590  5544  5592 I io.jxcore.node.LifeCycleMonitor: stop: OK
11-08 11:17:37.591  5544  5592 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStarted
11-08 11:17:37.591  5544  5592 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,11-08 11:17:37.592  5544  5592 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStopped
11-08 11:17:37.593  5544  5592 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,11-08 11:17:37.593  5544  5592 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityDestroyed
11-08 11:17:37.593  5544  5592 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
11-08 11:17:37.594  5544  5592 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityPaused
11-08 11:17:37.595  5544  5592 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,11-08 11:17:37.597  5544  5592 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToString
11-08 11:17:37.599  5544  5592 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToJsonObject
11-08 11:17:37.600  5544  5592 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testConstructorWithParameters
11-08 11:17:37.600  5544  5592 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testSetListeningOnPortNumber
,11-08 11:17:37.601  5544  5592 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testGetListeningOnPortNumber
11-08 11:17:37.602  5544  5592 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testDefaultConstructor
,11-08 11:17:37.604  5544  5592 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testClose
11-08 11:17:37.606  5544  5592 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testGetListeningOnPortNumber
,11-08 11:17:37.606  5544  5592 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testConstructor
11-08 11:17:37.608  5544  5592 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetListener
,11-08 11:17:37.609  5544  5592 I io.jxcore.node.SocketThreadBaseTest: Starting test: testSetPeerProperties
,11-08 11:17:37.610  5544  5592 I io.jxcore.node.SocketThreadBaseTest: Starting test: testClose
11-08 11:17:37.611  5544  5592 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 146)
,11-08 11:17:37.612  5544  5592 I io.jxcore.node.SocketThreadBaseTest: Starting test: testCloseLocalSocketAndStreams
,11-08 11:17:37.612  5544  5592 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
11-08 11:17:37.612  5544  5592 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 147)
11-08 11:17:37.613  5544  5592 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetPeerProperties
11-08 11:17:37.614  5544  5592 I io.jxcore.node.SocketThreadBaseTest: Starting test: testEquals
,11-08 11:17:37.615  5544  5592 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetLocalHostAddressAsString
,11-08 11:17:37.615  5544  5592 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-08 11:17:37.616  5544  5592 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d5da8b added. We now have 3 listener(s)
,11-08 11:17:37.617  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-08 11:17:37.618  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-08 11:17:37.618  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-08 11:17:37.618  5544  5592 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-08 11:17:37.618  5544  5592 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d269768 added. We now have 3 listener(s)
11-08 11:17:37.618  5544  5592 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-08 11:17:37.619  5544  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-08 11:17:37.622  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-08 11:17:37.626  5544  5592 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-08 11:17:37.626  5544  5592 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 11:17:37.626  5544  5592 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 11:17:37.626  5544  5592 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 11:17:37.626  5544  5592 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 11:17:37.626  5544  5592 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 11:17:37.626  5544  5592 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 11:17:37.626  5544  5592 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-08 11:17:37.628  5544  5592 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-08 11:17:37.628  5544  5592 D io.jxcore.node.ConnectivityMonitor: start: OK
,11-08 11:17:37.631  5544  5544 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 11:17:37.633  5544  5544 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 11:17:37.633  5544  5592 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCancelCurrentOperation
,11-08 11:17:37.634  5544  5592 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStopOperation
11-08 11:17:37.635  5544  5592 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
,11-08 11:17:37.635  5544  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
11-08 11:17:37.635  5544  5592 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-08 11:17:37.635  5544  5592 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-08 11:17:37.635  5544  5592 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-08 11:17:37.635  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-08 11:17:37.636  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-08 11:17:37.637  5544  5592 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,11-08 11:17:37.638  5544  5847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-08 11:17:37.638  5544  5592 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,11-08 11:17:37.637  5796  5796 W Binder_1: type=1400 audit(0.0:123): avc: denied { ioctl } for path="socket:[33093]" dev="sockfs" ino=33093 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-08 11:17:37.640  5796  5796 W Binder_1: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[33093]" dev="sockfs" ino=33093 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-08 11:17:37.638  5544  5592 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,11-08 11:17:37.638  5544  5592 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-08 11:17:37.638  5544  5544 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-08 11:17:37.638  5544  5847 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-08 11:17:37.638  5544  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-08 11:17:37.639  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-08 11:17:37.639  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-08 11:17:37.641  5544  5847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-08 11:17:37.646  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-08 11:17:37.646  5544  5592 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-08 11:17:37.646  5544  5592 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-08 11:17:37.649  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-08 11:17:37.650  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-08 11:17:37.650  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,11-08 11:17:37.652  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-66,5,main], id: 66
,11-08 11:17:37.652  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-08 11:17:37.652  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-08 11:17:37.652  5544  5592 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 60 83 34 25 D7 D4
11-08 11:17:37.653  5544  5592 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-08 11:17:37.653  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:37.653  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:37.653  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-66,5,main], id: 66
,11-08 11:17:37.653  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:37.654  5544  5592 D BluetoothAdapter: STATE_ON
,11-08 11:17:37.657  5786  5796 D BtGatt.GattService: registerClient() - UUID=73fd7e93-5066-4192-804b-036c786b8da6
11-08 11:17:37.658  5786  5802 D BtGatt.GattService: onClientRegistered() - UUID=73fd7e93-5066-4192-804b-036c786b8da6, clientIf=5
,11-08 11:17:37.658  5544  5554 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-08 11:17:37.660  5786  5804 D BtGatt.AdvertiseManager: message : 0
11-08 11:17:37.662  5786  5804 D BtGatt.AdvertiseManager: starting multi advertising
,11-08 11:17:37.673  5786  5802 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-08 11:17:37.678  5786  5802 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-08 11:17:37.679  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-66,5,main], id: 66
,11-08 11:17:37.679  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:37.679  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-08 11:17:37.679  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:37.679  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:37.679  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:37.679  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:37.679  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[Thread-66,5,main], id: 66
,11-08 11:17:37.679  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-08 11:17:37.681  5544  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-08 11:17:37.681  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-66,5,main], id: 66
,11-08 11:17:37.683  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-66,5,main], id: 66
,11-08 11:17:37.683  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:37.683  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:37.683  5544  5544 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-08 11:17:37.683  5544  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-08 11:17:37.683  5544  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-08 11:17:37.683  5544  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-08 11:17:37.683  5544  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged true. Current thread: Thread[main,5,main], id: 1
11-08 11:17:37.683  5544  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,11-08 11:17:37.683  5544  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-08 11:17:37.684  5544  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-08 11:17:37.684  5544  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-08 11:17:37.684  5544  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-08 11:17:37.684  5544  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-08 11:17:37.684  5544  5544 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-08 11:17:37.684  5544  5544 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-08 11:17:37.686  5544  5544 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-08 11:17:37.687  5544  5544 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-08 11:17:37.687  5544  5544 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-08 11:17:37.687  5544  5544 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-08 11:17:37.687  5544  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-08 11:17:37.687  5544  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-08 11:17:37.687  5544  5544 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-08 11:17:38.188  5544  5544 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,11-08 11:17:38.188  5544  5544 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-08 11:17:38.188  5544  5544 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-08 11:17:40.156   546   546 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
11-08 11:17:40.156   546   546 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-08 11:17:40.299  5845  5845 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-08 11:17:40.306  5845  5845 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-08 11:17:40.312  5845  5845 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-08 11:17:40.349  5845  5845 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-08 11:17:40.395   934  2875 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-08 11:17:40.397   934  2875 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-08 11:17:40.397   934  2875 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-08 11:17:40.414   934  2875 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-08 11:17:40.447   934  2875 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-08 11:17:40.790  5845  5845 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-08 11:17:40.829  5845  5845 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-08 11:17:40.830  5845  5845 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-08 11:17:40.841   934  2875 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
11-08 11:17:40.841   934  2875 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-08 11:17:40.841   934  2877 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-08 11:17:40.860   934  2875 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-08 11:17:40.875   510   927 D CommandListener: Setting iface cfg
,11-08 11:17:40.882   934  2875 D WifiStateMachine: Start Dhcp Watchdog 3
,11-08 11:17:40.889   934  5852 D DhcpClient: Receive thread started
,11-08 11:17:40.895   934  2877 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-08 11:17:40.895   934  2875 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,11-08 11:17:40.895   934  2877 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,11-08 11:17:40.976   934  2875 E native  : do suspend false
,11-08 11:17:40.994   934  5851 D DhcpClient: Broadcasting DHCPDISCOVER
,11-08 11:17:41.008   934  5852 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.105, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172726, domain null
,11-08 11:17:41.009   934  5851 D DhcpClient: Got pending lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172726 seconds
,11-08 11:17:41.012   934  5851 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.105 serverid=192.168.1.1
,11-08 11:17:41.025   934  5852 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.105, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-08 11:17:41.026   934  5851 D DhcpClient: Confirmed lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-08 11:17:41.030   510   927 D CommandListener: Setting iface cfg
,11-08 11:17:41.034   934  2875 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-08 11:17:41.040   934  5851 D DhcpClient: Scheduling renewal in 86399s
,11-08 11:17:41.054   934  2875 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-08 11:17:41.054   934  2875 D WifiConfigStore: No blacklist allowed without epno enabled
,11-08 11:17:41.055   934  2877 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
11-08 11:17:41.057   934  2877 D ConnectivityService: Adding iface wlan0 to network 102
11-08 11:17:41.068   934  2875 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-08 11:17:41.122   934  2877 E ConnectivityService: Unexpected mtu value: 0, wlan0
11-08 11:17:41.122   934  2877 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,11-08 11:17:41.124   934  2877 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,11-08 11:17:41.126   934  2877 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,11-08 11:17:41.128   934  2877 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,11-08 11:17:41.138   934  2877 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-08 11:17:41.143   934  2877 D ConnectivityService: scheduleUnvalidatedPrompt 102
,11-08 11:17:41.143   934  2877 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
11-08 11:17:41.143   934  2877 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
,11-08 11:17:41.143   934  2877 D ConnectivityService:    accepting network in place of null
11-08 11:17:41.143   934  2875 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-08 11:17:41.143   934  2875 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-08 11:17:41.144   934  2877 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -48]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-08 11:17:41.167   510   927 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-08 11:17:41.181   934  5850 D NetlinkSocketObserver: NeighborEvent{elapsedMs=115034, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-08 11:17:41.185  5544  5592 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
11-08 11:17:41.185  5544  5592 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,11-08 11:17:41.185  5544  5592 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-08 11:17:41.185  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-08 11:17:41.185  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-08 11:17:41.185  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
11-08 11:17:41.186  5544  5847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-08 11:17:41.186  5544  5592 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-08 11:17:41.186  5544  5847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-08 11:17:41.186  5544  5592 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-08 11:17:41.186  5544  5847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-08 11:17:41.186  5544  5592 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-08 11:17:41.186  5544  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-08 11:17:41.186  5544  5544 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-08 11:17:41.186  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-08 11:17:41.186  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-08 11:17:41.186  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:41.186  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-66,5,main], id: 66
,11-08 11:17:41.187  5544  5592 D BluetoothAdapter: STATE_ON
,11-08 11:17:41.187  5544  5592 D BluetoothLeScanner: could not find callback wrapper
11-08 11:17:41.187  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,11-08 11:17:41.187  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-66,5,main], id: 66
,11-08 11:17:41.187  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-66,5,main], id: 66
,11-08 11:17:41.187  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-08 11:17:41.187  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:41.188  5786  5804 D BtGatt.AdvertiseManager: message : 1
11-08 11:17:41.189  5786  5804 D BtGatt.AdvertiseManager: stop advertise for client 5
11-08 11:17:41.190   510   927 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-08 11:17:41.194   934  2877 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
11-08 11:17:41.194   934  2877 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-08 11:17:41.195  3634  3761 W QCNEJ   : |CORE| network available: 102,
,11-08 11:17:41.196   934  2877 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,11-08 11:17:41.197  3634  3761 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-08 11:17:41.199   934   951 D Tethering: MasterInitialState.processMessage what=3
11-08 11:17:41.199  3634  3761 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
,11-08 11:17:41.200  3634  3761 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
11-08 11:17:41.201  5786  5802 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-08 11:17:41.201  5786  5802 D BtGatt.GattService: Client app is not null!
11-08 11:17:41.202  5786  5797 D BtGatt.GattService: unregisterClient() - clientIf=5
11-08 11:17:41.203  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-08 11:17:41.203  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:41.203  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-08 11:17:41.203  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged false. Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:41.203  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:41.203  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:41.203  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-08 11:17:41.203  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-08 11:17:41.203  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-66,5,main], id: 66
,11-08 11:17:41.203  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:41.203  5544  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,11-08 11:17:41.203  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:41.207  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:41.207  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-08 11:17:41.207  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:41.207  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:41.207  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:41.207  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:41.207  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:41.207  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-08 11:17:41.207  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-08 11:17:41.208  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
11-08 11:17:41.208  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:41.209  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:41.209  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:41.209  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:41.209  5544  5544 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-08 11:17:41.209  5544  5544 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-08 11:17:41.209  5544  5544 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-08 11:17:41.209  5544  5544 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-08 11:17:41.209  5544  5544 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-08 11:17:41.209  5544  5544 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-08 11:17:41.211  5544  5592 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCheckCurrentOperationStatus
11-08 11:17:41.211  5544  5592 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-08 11:17:41.212  5544  5592 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-08 11:17:41.212  5544  5592 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-08 11:17:41.212  5544  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,11-08 11:17:41.212  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-08 11:17:41.212  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-08 11:17:41.213  3871  3871 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
11-08 11:17:41.215  3890  3890 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-08 11:17:41.216  5544  5544 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 11:17:41.216  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 11:17:41.216  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 11:17:41.216  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 11:17:41.216  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 11:17:41.216  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-08 11:17:41.216  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-08 11:17:41.216  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-08 11:17:41.218  5544  5544 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-08 11:17:41.218  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-08 11:17:41.219  5544  5592 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-08 11:17:41.219  5544  5592 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-08 11:17:41.222  3890  3890 D SystemUpdateService: onCreate
,11-08 11:17:41.224  5544  5544 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 11:17:41.224  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 11:17:41.224  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 11:17:41.224  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 11:17:41.224  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 11:17:41.224  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-08 11:17:41.224  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-08 11:17:41.224  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-08 11:17:41.225  3890  3890 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-08 11:17:41.227  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-08 11:17:41.229  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-08 11:17:41.229  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-08 11:17:41.229  5544  5544 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-08 11:17:41.233  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-66,5,main], id: 66
,11-08 11:17:41.233  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-08 11:17:41.233  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-08 11:17:41.234  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-08 11:17:41.234  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-08 11:17:41.234  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:41.235  5544  5544 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 11:17:41.235  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 11:17:41.235  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 11:17:41.235  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 11:17:41.235  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 11:17:41.235  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-08 11:17:41.235  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-08 11:17:41.235  5544  5544 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-08 11:17:41.235  5544  5592 D BluetoothAdapter: STATE_ON
,11-08 11:17:41.238  5544  5544 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-08 11:17:41.239  5544  5544 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-08 11:17:41.239  5786  5796 D BtGatt.GattService: registerClient() - UUID=f6b2293d-3ce1-4d35-ac0e-9a6b92375d10
,11-08 11:17:41.239  3890  3890 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
11-08 11:17:41.240  5786  5802 D BtGatt.GattService: onClientRegistered() - UUID=f6b2293d-3ce1-4d35-ac0e-9a6b92375d10, clientIf=5
,11-08 11:17:41.240  5544  5584 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-08 11:17:41.241  5786  5828 D BtGatt.GattService: start scan with filters
,11-08 11:17:41.244  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-08 11:17:41.244  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:41.244  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-08 11:17:41.244  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:41.244  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:41.244  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-08 11:17:41.244  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-08 11:17:41.244  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:41.244  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:41.244  5544  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-08 11:17:41.245  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:41.245  5786  5805 D BtGatt.ScanManager: handling starting scan
11-08 11:17:41.233  3890  5864 I SystemUpdateService: active receiver: enabled
11-08 11:17:41.247  3890  4234 I iu.UploadsManager: num queued entries: 0
11-08 11:17:41.247  5786  5805 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96bca27
,11-08 11:17:41.249  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:41.249  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-08 11:17:41.249  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:41.249  5544  5544 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-08 11:17:41.249  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-66,5,main], id: 66
,11-08 11:17:41.249  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:41.249  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-08 11:17:41.250  5544  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-08 11:17:41.250  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:41.252  5786  5802 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-08 11:17:41.252  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:41.252  5786  5802 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-08 11:17:41.252  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:41.253  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:41.253  3890  3890 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
11-08 11:17:41.253  5786  5805 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-08 11:17:41.254  3890  3890 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-08 11:17:41.256  5638  5638 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-08 11:17:41.258  5786  5802 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-08 11:17:41.259  5786  5802 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-08 11:17:41.259  5786  5805 D BtGatt.ScanManager: Starting BLE batch scan
11-08 11:17:41.259  5786  5805 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-08 11:17:41.261  5638  5638 D SprintDMHelper: simOperator: 
11-08 11:17:41.261  5638  5638 D SprintDMReceiver: Not Sprint UICC, don't do anything.
11-08 11:17:41.263   934  5849 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
11-08 11:17:41.270  5786  5802 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-08 11:17:41.270  5786  5802 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-08 11:17:41.276  5786  5802 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-08 11:17:41.276  5786  5802 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-08 11:17:41.276  3890  5864 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-08 11:17:41.247  3890  4234 I iu.UploadsManager: num updated entries: 0
,11-08 11:17:41.287  3890  4234 I iu.SyncManager: NEXT; no task
,11-08 11:17:41.291  3890  5864 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-08 11:17:41.291  3890  5864 I SystemUpdateService: now status is 0 (complete)
11-08 11:17:41.292  3890  5864 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-08 11:17:41.292  3890  5864 I SystemUpdateService: file has been verified
11-08 11:17:41.292  3890  5864 I SystemUpdateService: OTA package size = 21989297
,11-08 11:17:41.298  3890  5864 I SystemUpdateService: showing system update notification
,11-08 11:17:41.305   934   934 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-08 11:17:41.309  3890  3890 D SystemUpdateService: onDestroy
,11-08 11:17:41.383   934  5849 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 08 Nov 2016 10:17:41 GMT], X-Android-Received-Millis=[1478600261382], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1478600261353]}
,11-08 11:17:41.384   934  2877 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-08 11:17:41.384   934  2877 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
11-08 11:17:41.384   934  2877 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
11-08 11:17:41.385   934  2877 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-08 11:17:41.749  5544  5544 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-08 11:17:41.749  5544  5544 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-08 11:17:41.750  5544  5544 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-08 11:17:41.780  5786  5786 D BtGatt.ScanManager: awakened up at time 115633
,11-08 11:17:41.782  5786  5805 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-08 11:17:41.798  5786  5802 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-08 11:17:41.798  5786  5802 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-08 11:17:41.800  5544  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: Current thread: Thread[main,5,main], id: 1
,11-08 11:17:42.196   934  2877 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,11-08 11:17:44.255  5544  5592 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStartOperation
,11-08 11:17:44.256  5544  5592 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 6
11-08 11:17:44.256  5544  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 5 -> 6
11-08 11:17:44.256  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
11-08 11:17:44.256  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
11-08 11:17:44.256  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
11-08 11:17:44.256  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 6
11-08 11:17:44.256  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
11-08 11:17:44.256  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
11-08 11:17:44.256  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
11-08 11:17:44.256  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
11-08 11:17:44.256  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
11-08 11:17:44.257  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-08 11:17:44.257  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-08 11:17:44.259  5544  5592 D BluetoothAdapter: STATE_ON
,11-08 11:17:44.262  5786  5797 D BtGatt.GattService: stopScan() - queue size =1
,11-08 11:17:44.272  5786  5814 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-08 11:17:44.273  5786  5786 D BtGatt.ScanManager: awakened up at time 118125
,11-08 11:17:44.273  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-08 11:17:44.273  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-66,5,main], id: 66
,11-08 11:17:44.273  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-08 11:17:44.274  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-08 11:17:44.274  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:44.274  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-08 11:17:44.274  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-08 11:17:44.274  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-08 11:17:44.275  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-08 11:17:44.275  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:44.278  5544  5592 D BluetoothAdapter: STATE_ON
11-08 11:17:44.279  5786  5802 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-08 11:17:44.279  5786  5802 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-08 11:17:44.280  5786  5805 D BtGatt.ScanManager: stopping BLe Batch
11-08 11:17:44.283  5786  5826 D BtGatt.GattService: registerClient() - UUID=f491ab6a-ad4f-444f-b3e0-0d646fb5c51b
11-08 11:17:44.284  5786  5802 D BtGatt.GattService: onClientRegistered() - UUID=f491ab6a-ad4f-444f-b3e0-0d646fb5c51b, clientIf=5
11-08 11:17:44.285  5544  5555 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-08 11:17:44.285  5786  5796 D BtGatt.GattService: start scan with filters
,11-08 11:17:44.289  5786  5802 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-08 11:17:44.290  5786  5802 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-08 11:17:44.290  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-08 11:17:44.290  5786  5805 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-08 11:17:44.290  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:44.290  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-08 11:17:44.290  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:44.290  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:44.291  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-08 11:17:44.291  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-08 11:17:44.291  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:44.291  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:44.291  5544  5592 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-08 11:17:44.291  5544  5592 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-08 11:17:44.291  5544  5592 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-08 11:17:44.291  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-08 11:17:44.293  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-08 11:17:44.293  5544  5592 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-08 11:17:44.293  5544  5592 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-08 11:17:44.293  5544  5592 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,11-08 11:17:44.293  5544  5592 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-08 11:17:44.293  5544  5544 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-08 11:17:44.293  5544  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
11-08 11:17:44.294  5544  5872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-08 11:17:44.295  5544  5872 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-08 11:17:44.295  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-08 11:17:44.295  5544  5592 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-08 11:17:44.294  5815  5815 W Binder_4: type=1400 audit(0.0:125): avc: denied { ioctl } for path="socket:[33925]" dev="sockfs" ino=33925 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-08 11:17:44.297  5544  5872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-08 11:17:44.294  5815  5815 W Binder_4: type=1400 audit(0.0:126): avc: denied { ioctl } for path="socket:[33925]" dev="sockfs" ino=33925 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-08 11:17:44.304  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser : Current thread: Thread[Thread-66,5,main], id: 66
,11-08 11:17:44.304  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:44.304  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-08 11:17:44.304  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-08 11:17:44.304  5544  5592 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 06 60 83 34 25 D7 D4
11-08 11:17:44.304  5544  5592 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-08 11:17:44.305  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:44.305  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:44.305  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:44.305  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:44.306  5544  5592 D BluetoothAdapter: STATE_ON
,11-08 11:17:44.306  5786  5802 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
11-08 11:17:44.306  5786  5802 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-08 11:17:44.306  5786  5802 D BtGatt.GattService: current time is 118159047384
11-08 11:17:44.306  5786  5802 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -87, 48, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0, 71, -122, -77, 84, 69, -12, 1, -128, -84, 48, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -83, 47, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -79, 36, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-08 11:17:44.308  5786  5805 D BtGatt.ScanManager: handling starting scan
11-08 11:17:44.308  5786  5796 D BtGatt.GattService: registerClient() - UUID=c38714f4-b6a5-45ea-bba7-0c660343b0c5
,11-08 11:17:44.311  5786  5802 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
,11-08 11:17:44.312  5786  5802 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-08 11:17:44.312  5786  5802 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-08 11:17:44.313  5786  5802 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-08 11:17:44.315  5786  5802 D BtGatt.GattService: onClientRegistered() - UUID=c38714f4-b6a5-45ea-bba7-0c660343b0c5, clientIf=6
11-08 11:17:44.316  5544  5554 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
11-08 11:17:44.317  5786  5804 D BtGatt.AdvertiseManager: message : 0
,11-08 11:17:44.319  5786  5802 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-08 11:17:44.319  5786  5802 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-08 11:17:44.319  5786  5805 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-08 11:17:44.320  5786  5804 D BtGatt.AdvertiseManager: starting multi advertising
,11-08 11:17:44.324  5786  5802 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-08 11:17:44.324  5786  5802 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-08 11:17:44.325  5786  5805 D BtGatt.ScanManager: Starting BLE batch scan
11-08 11:17:44.325  5786  5805 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-08 11:17:44.333  5786  5802 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,11-08 11:17:44.342  5786  5802 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-08 11:17:44.342  5786  5802 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-08 11:17:44.346  5786  5802 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,11-08 11:17:44.347  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:44.347  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:44.347  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-08 11:17:44.347  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:44.347  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:44.347  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:44.347  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:44.348  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[Thread-66,5,main], id: 66
,11-08 11:17:44.348  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: advertiser is started. Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:44.348  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:44.348  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:44.348  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
11-08 11:17:44.348  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: adv = true, disc = true
11-08 11:17:44.348  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-08 11:17:44.349  5544  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-08 11:17:44.349  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:44.351  5786  5802 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-08 11:17:44.351  5786  5802 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-08 11:17:44.351  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:44.351  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:44.351  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:44.352  5544  5544 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-08 11:17:44.352  5544  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: Current thread: Thread[main,5,main], id: 1
11-08 11:17:44.352  5544  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: 
,11-08 11:17:44.352  5544  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=C8:16:A4:7E:61:23, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-87, mTimestampNanos=115759588739}
,11-08 11:17:44.352  5544  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: 
11-08 11:17:44.352  5544  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=FB:F2:70:61:22:51, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-83, mTimestampNanos=115809588739}
11-08 11:17:44.353  5544  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: 
11-08 11:17:44.353  5544  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=F4:45:54:B3:86:47, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-84, mTimestampNanos=115759588739}
11-08 11:17:44.353  5544  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: 
11-08 11:17:44.353  5544  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=E3:EC:A5:91:D5:74, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-79, mTimestampNanos=116359588739}
11-08 11:17:44.354  5544  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-08 11:17:44.354  5544  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-08 11:17:44.354  5544  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-08 11:17:44.354  5544  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged true. Current thread: Thread[main,5,main], id: 1
11-08 11:17:44.354  5544  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-08 11:17:44.354  5544  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-08 11:17:44.354  5544  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING, ADVERTISING]
11-08 11:17:44.354  5544  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-08 11:17:44.354  5544  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-08 11:17:44.354  5544  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-08 11:17:44.354  5544  5544 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
11-08 11:17:44.354  5544  5544 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thr,ead: Thread[main,5,main], id: 1
11-08 11:17:44.356  5544  5544 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-08 11:17:44.356  5544  5544 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
11-08 11:17:44.356  5544  5544 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-08 11:17:44.356  5544  5544 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-08 11:17:44.356  5544  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-08 11:17:44.356  5544  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-08 11:17:44.357  5544  5544 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,11-08 11:17:44.857  5544  5544 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: true
,11-08 11:17:44.858  5544  5544 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,11-08 11:17:44.858  5544  5544 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-08 11:17:45.157   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 11:17:46.158   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 11:17:46.326   934  2875 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 8, 10 -> obsolete
,11-08 11:17:47.159   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 11:17:47.355  5544  5592 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testConstructor
,11-08 11:17:47.356  5544  5592 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-08 11:17:47.356  5544  5592 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,11-08 11:17:47.356  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-08 11:17:47.356  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,11-08 11:17:47.357  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
11-08 11:17:47.357  5544  5872 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,11-08 11:17:47.357  5544  5592 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,11-08 11:17:47.357  5544  5872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,11-08 11:17:47.357  5544  5592 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,11-08 11:17:47.357  5544  5872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-08 11:17:47.358  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-08 11:17:47.358  5544  5544 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-08 11:17:47.358  5544  5592 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d5da8b removed from the list
,11-08 11:17:47.358  5544  5544 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-08 11:17:47.358  5544  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-08 11:17:47.358  5544  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-08 11:17:47.358  5544  5544 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-08 11:17:47.358  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-08 11:17:47.358  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-08 11:17:47.359  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:47.359  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-66,5,main], id: 66
,11-08 11:17:47.359  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,11-08 11:17:47.386  5544  5592 D BluetoothAdapter: STATE_ON
,11-08 11:17:47.387  5786  5796 D BtGatt.GattService: stopScan() - queue size =1
,11-08 11:17:47.388  5786  5814 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-08 11:17:47.388  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,11-08 11:17:47.389  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-66,5,main], id: 66
,11-08 11:17:47.389  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-08 11:17:47.389  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:47.389  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:47.389  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-08 11:17:47.389  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING, ADVERTISING]
,11-08 11:17:47.389  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:47.389  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:47.390  5544  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
11-08 11:17:47.390  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:47.394  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:47.394  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-08 11:17:47.394  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:47.394  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:47.394  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:47.394  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:47.395  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-08 11:17:47.395  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-66,5,main], id: 66
,11-08 11:17:47.395  5786  5804 D BtGatt.AdvertiseManager: message : 1
11-08 11:17:47.396  5786  5786 D BtGatt.ScanManager: awakened up at time 121248
,11-08 11:17:47.396  5786  5804 D BtGatt.AdvertiseManager: stop advertise for client 6
,11-08 11:17:47.398  5786  5802 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-08 11:17:47.398  5786  5802 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-08 11:17:47.398  5786  5805 D BtGatt.ScanManager: stopping BLe Batch
,11-08 11:17:47.403  5786  5802 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
11-08 11:17:47.403  5786  5802 D BtGatt.GattService: Client app is not null!
,11-08 11:17:47.403  5786  5814 D BtGatt.GattService: unregisterClient() - clientIf=6
11-08 11:17:47.404  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-08 11:17:47.404  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-66,5,main], id: 66
,11-08 11:17:47.404  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-08 11:17:47.404  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged false. Current thread: Thread[Thread-66,5,main], id: 66
,11-08 11:17:47.404  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:47.405  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:47.405  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-08 11:17:47.405  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-08 11:17:47.405  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:47.405  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:47.405  5544  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-08 11:17:47.405  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:47.406  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-66,5,main], id: 66
,11-08 11:17:47.406  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-08 11:17:47.406  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:47.407  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:47.407  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:47.407  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:47.407  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:47.407  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-08 11:17:47.407  5544  5592 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-08 11:17:47.410  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,11-08 11:17:47.411  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:47.412  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:47.412  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:47.412  5544  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-66,5,main], id: 66
11-08 11:17:47.412  5544  5592 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d269768 removed from the list
11-08 11:17:47.412  5544  5544 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-08 11:17:47.412  5544  5592 D io.jxcore.node.ConnectivityMonitor: stop
11-08 11:17:47.412  5544  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-08 11:17:47.412  5544  5544 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-08 11:17:47.412  5544  5544 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
11-08 11:17:47.412  5544  5544 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-08 11:17:47.413  5786  5802 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-08 11:17:47.413  5786  5802 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-08 11:17:47.413  5786  5805 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-08 11:17:47.414  5544  5592 I io.jxcore.node.StartStopOperationTest: Starting test: testIsTargetState
11-08 11:17:47.414  5544  5592 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-08 11:17:47.414  5544  5592 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-08 11:17:47.415  5544  5592 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,11-08 11:17:47.415  5544  5592 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-08 11:17:47.415  5544  5592 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
11-08 11:17:47.415  5544  5592 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-08 11:17:47.415  5544  5592 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStartOperation
11-08 11:17:47.416  5544  5592 I io.jxcore.node.StartStopOperationTest: Starting test: testGetShouldStartOrStopListeningToAdvertisementsOnly
11-08 11:17:47.417  5544  5592 I io.jxcore.node.StartStopOperationTest: Starting test: testIsStartOperation
11-08 11:17:47.417  5544  5592 I io.jxcore.node.StartStopOperationTest: Starting test: testToString
11-08 11:17:47.418  5544  5592 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStopOperation
11-08 11:17:47.418  5544  5592 I io.jxcore.node.StartStopOperationTest: Starting test: testSetOperationExecutedTime
11-08 11:17:47.419  5544  5592 I io.jxcore.node.StartStopOperationTest: Starting test: testGetOperationExecutedTime
11-08 11:17:47.419  5544  5592 I io.jxcore.node.StartStopOperationTest: Starting test: testGetCallback
,11-08 11:17:47.430  5786  5802 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,11-08 11:17:47.430  5786  5802 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-08 11:17:47.430  5786  5802 D BtGatt.GattService: current time is 121283175909
11-08 11:17:47.430  5786  5802 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -79, 59, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -75, 41, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -88, 39, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -83, 30, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -83, 29, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-08 11:17:47.430  5786  5802 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-08 11:17:47.431  5786  5802 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-08 11:17:47.431  5786  5802 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-08 11:17:47.431  5786  5802 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,11-08 11:17:47.431  5786  5802 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,11-08 11:17:47.731   934  2875 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 7, 10 -> obsolete
,11-08 11:17:47.913  5544  5544 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-08 11:17:48.160   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 11:17:49.149   934  2877 D ConnectivityService: handlePromptUnvalidated 102
,11-08 11:17:49.161   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 11:17:49.297  5845  5845 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-08 11:17:49.424  5544  5592 I StreamCopyingThreadTest: Starting test: testCopyDataAndCloseConnection
,11-08 11:17:49.563  5544  5874 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 160, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-08 11:17:49.563  5544  5874 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-08 11:17:50.162   546   546 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-08 11:17:50.357  5544  5874 W !!      : call onHalfStreamCopied
,11-08 11:17:50.357  5544  5874 I testCopyDataAndClose: closing input stream
,11-08 11:17:51.134  5544  5874 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 160, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-08 11:17:51.134  5544  5874 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-08 11:17:51.134  5544  5874 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].,
11-08 11:17:51.134  5544  5874 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-08 11:17:51.134  5544  5874 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-08 11:17:51.134  5544  5874 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-08 11:17:51.134  5544  5874 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-08 11:17:51.134  5544  5874 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-08 11:17:51.134  5544  5874 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-08 11:17:51.134  5544  5874 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 160, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-08 11:17:51.134  5544  5874 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-08 11:17:52.297   934  2875 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 9, 10 -> obsolete
,11-08 11:17:55.163   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 11:17:55.572  5544  5592 I StreamCopyingThreadTest: Starting test: testRun
,11-08 11:17:55.578  5544  5875 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 163, name: My test thread name). Connection data: Peer properties: [null null].
11-08 11:17:55.578  5544  5875 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-08 11:17:56.164   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 11:17:57.165   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 11:17:58.167   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 11:17:59.169   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 11:18:00.170   546   546 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-08 11:18:00.245   934  5850 D NetlinkSocketObserver: NeighborEvent{elapsedMs=134097, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-08 11:18:00.586  5544  5876 E StreamCopyingThreadTest: StreamCopyingThread didn't close after 5s!
,11-08 11:18:00.588  5544  5592 I StreamCopyingThreadTest: Starting test: testCopyBigData
,11-08 11:18:00.709  5544  5877 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 166, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-08 11:18:00.709  5544  5877 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-08 11:18:01.736  3578  3751 I Keyboard.Facilitator.LanguageModelFlusher: run()
,11-08 11:18:01.736  3578  3751 I Keyboard.Facilitator: flushDynamicLanguageModels()
,11-08 11:18:01.768  3502  3502 I ConfigService: onCreate
,11-08 11:18:02.366  5544  5877 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 166, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-08 11:18:02.366  5544  5877 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-08 11:18:02.366  5544  5877 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-08 11:18:02.366  5544  5877 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-08 11:18:02.366  5544  5877 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-08 11:18:02.366  5544  5877 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-08 11:18:02.366  5544  5877 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-08 11:18:02.366  5544  5877 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-08 11:18:02.366  5544  5877 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-08 11:18:02.366  5544  5877 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 166, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-08 11:18:02.366  5544  5877 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-08 11:18:06.802  5544  5592 I StreamCopyingThreadTest: Starting test: testRunNotify
,11-08 11:18:06.804  3502  3502 I ConfigService: onDestroy
,11-08 11:18:06.805  5544  5879 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 168, name: My test thread name). Connection data: Peer properties: [null null].
11-08 11:18:06.805  5544  5879 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-08 11:18:06.805  5544  5879 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 168, thread name: My test thread name). Connection data: Peer properties: [null null].
11-08 11:18:06.805  5544  5879 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-08 11:18:06.805  5544  5879 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-08 11:18:06.805  5544  5879 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-08 11:18:06.806  5544  5879 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-08 11:18:06.806  5544  5879 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-08 11:18:06.806  5544  5879 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-08 11:18:06.806  5544  5879 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,11-08 11:18:06.806  5544  5879 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-08 11:18:06.806  5544  5879 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 168, name: My test thread name). Connection data: Peer properties: [null null].
11-08 11:18:06.806  5544  5879 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,11-08 11:18:06.808  5544  5592 I StreamCopyingThreadTest: Starting test: testSetBufferSize
11-08 11:18:06.808  5544  5592 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
11-08 11:18:06.809  5544  5592 I StreamCopyingThreadTest: Starting test: testRunWithException
11-08 11:18:06.810  5544  5880 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 172, name: My test thread name). Connection data: Peer properties: [null null].
11-08 11:18:06.810  5544  5880 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-08 11:18:06.810  5544  5880 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 172, thread name: My test thread name): Test exception.
11-08 11:18:06.810  5544  5880 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 172, name: My test thread name). Connection data: Peer properties: [null null].
11-08 11:18:06.810  5544  5880 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-08 11:18:06.810  5544  5880 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
11-08 11:18:06.810  5544  5880 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 172, name: My test thread name). Connection data: Peer properties: [null null].
11-08 11:18:06.810  5544  5880 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-08 11:18:06.811  5544  5592 E com.test.thalitest.ThaliTestRunner: testConnect(io.jxcore.node.ConnectionHelperTest)
11-08 11:18:06.811  5544  5592 E com.test.thalitest.ThaliTestRunner: 
11-08 11:18:06.811  5544  5592 E com.test.thalitest.ThaliTestRunner: Expected: is "We already have an outgoing connection to peer with ID 00:11:22:33:44:55"
11-08 11:18:06.811  5544  5592 E com.test.thalitest.ThaliTestRunner:      but: was "Already connect(ing/ed)"
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: 
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: Expected: is "We already have an outgoing connection to peer with ID 00:11:22:33:44:55"
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner:      but: was "Already connect(ing/ed)"
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:8)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.ConnectionHelperTest.testConnect(ConnectionHelperTest.java:551)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
11-08 11:18:06.812 , 5544  5592 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunAfters.evaluate(RunAfters.java:27)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
11-08 11:18:06.812  5544  5592 E com,.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: testRun(io.jxcore.node.StreamCopyingThreadTest)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: StreamCopyingThread should be closed
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: StreamCopyingThread should be closed
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.StreamCopyingThreadTest.testRun(StreamCopyingThreadTest.java:152)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.r,unChild(BlockJUnit4ClassRunner.java:78)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
11-08 11:18:06.81,2  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
11-08 11:18:06.812  5544  5592 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
11-08 11:18:06.814  5544  5592 I jxcore-log: 2016-11-08 10:18:06 - DEBUG UnitTest_app: 'Running unit tests'
11-08 11:18:06.814  5544  5592 I jxcore-log: 
11-08 11:18:06.814  5544  5592 I jxcore-log: *Native tests were executed*
11-08 11:18:06.814  5544  5592 I jxcore-log: 
11-08 11:18:06.814  5544  5592 I jxcore-log: Total number of executed tests:  82
11-08 11:18:06.814  5544  5592 I jxcore-log: 
11-08 11:18:06.814  5544  5592 I jxcore-log: Number of passed tests:  80
11-08 11:18:06.814  5544  5592 I jxcore-log: 
11-08 11:18:06.814  5544  5592 I jxcore-log: Number of failed tests:  2
11-08 11:18:06.814  5544  5592 I jxcore-log: 
11-08 11:18:06.814  5544  5592 I jxcore-log: Number of ignored tests:  0
11-08 11:18:06.814  5544  5592 I jxcore-log: 
11-08 11:18:06.815  5544  5592 I jxcore-log: Total duration:  43830
11-08 11:18:06.815  5544  5592 I jxcore-log: 
11-08 11:18:06.815  5544  5592 I jxcore-log: Failed to execute UT.
11-08 11:18:06.815  5544  5592 I jxcore-log: 
11-08 11:18:06.816  5544  5592 I jxcore-log: 2016-11-08 10:18:06 - DEBUG UnitTest_app: 'Failed to execute UT.'
11-08 11:18:06.816  5544  5592 I jxcore-log: 
,11-08 11:18:06.817  5544  5592 I jxcore-log: 2016-11-08 10:18:06 - DEBUG UnitTest_app: 'Unit Test app is loaded'
11-08 11:18:06.817  5544  5592 I jxcore-log: 
,11-08 11:18:06.819  5544  5592 I jxcore-log: 2016-11-08 10:18:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-08 11:18:06.819  5544  5592 I jxcore-log: 
,11-08 11:18:06.820  5544  5592 I jxcore-log: 2016-11-08 10:18:06 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 11:18:06.820  5544  5592 I jxcore-log: 
,11-08 11:18:06.821  5544  5592 I jxcore-log: 2016-11-08 10:18:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-08 11:18:06.821  5544  5592 I jxcore-log: 
,11-08 11:18:06.822  5544  5592 I jxcore-log: 2016-11-08 10:18:06 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 11:18:06.822  5544  5592 I jxcore-log: 
,11-08 11:18:06.822  5544  5592 I jxcore-log: 2016-11-08 10:18:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-08 11:18:06.822  5544  5592 I jxcore-log: 
11-08 11:18:06.822  5544  5592 I jxcore-log: 2016-11-08 10:18:06 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 11:18:06.822  5544  5592 I jxcore-log: 
,11-08 11:18:06.823  5544  5592 I jxcore-log: 2016-11-08 10:18:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-08 11:18:06.823  5544  5592 I jxcore-log: 
11-08 11:18:06.823  5544  5592 I jxcore-log: 2016-11-08 10:18:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-08 11:18:06.823  5544  5592 I jxcore-log: 
11-08 11:18:06.823  5544  5592 I jxcore-log: 2016-11-08 10:18:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-08 11:18:06.823  5544  5592 I jxcore-log: 
11-08 11:18:06.824  5544  5592 I jxcore-log: 2016-11-08 10:18:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-08 11:18:06.824  5544  5592 I jxcore-log: 
,11-08 11:18:06.824  5544  5592 I jxcore-log: 2016-11-08 10:18:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-08 11:18:06.824  5544  5592 I jxcore-log: 
11-08 11:18:06.824  5544  5592 I jxcore-log: 2016-11-08 10:18:06 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 11:18:06.824  5544  5592 I jxcore-log: 
11-08 11:18:06.824  5544  5592 I jxcore-log: 2016-11-08 10:18:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-08 11:18:06.824  5544  5592 I jxcore-log: 
11-08 11:18:06.824  5544  5592 I jxcore-log: 2016-11-08 10:18:06 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 11:18:06.824  5544  5592 I jxcore-log: 
11-08 11:18:06.825  5544  5592 I jxcore-log: 2016-11-08 10:18:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-08 11:18:06.825  5544  5592 I jxcore-log: 
11-08 11:18:06.825  5544  5592 I jxcore-log: 2016-11-08 10:18:06 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 11:18:06.825  5544  5592 I jxcore-log: 
11-08 11:18:06.825  5544  5592 I jxcore-log: 2016-11-08 10:18:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-08 11:18:06.825  5544  5592 I jxcore-log: 
11-08 11:18:06.825  5544  5592 I jxcore-log: 2016-11-08 10:18:06 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 11:18:06.825  5544  5592 I jxcore-log: 
11-08 11:18:06.826  5544  5592 I jxcore-log: 2016-11-08 10:18:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-08 11:18:06.826  5544  5592 I jxcore-log: 
,11-08 11:18:06.826  5544  5592 I jxcore-log: 2016-11-08 10:18:06 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 11:18:06.826  5544  5592 I jxcore-log: 
11-08 11:18:06.826  5544  5592 I jxcore-log: 2016-11-08 10:18:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-08 11:18:06.826  5544  5592 I jxcore-log: 
11-08 11:18:06.826  5544  5592 I jxcore-log: 2016-11-08 10:18:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-08 11:18:06.826  5544  5592 I jxcore-log: 
11-08 11:18:06.827  5544  5592 I jxcore-log: 2016-11-08 10:18:06 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 11:18:06.827  5544  5592 I jxcore-log: 
,11-08 11:18:06.827  5544  5592 I jxcore-log: 2016-11-08 10:18:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-08 11:18:06.827  5544  5592 I jxcore-log: 
11-08 11:18:06.827  5544  5592 I jxcore-log: 2016-11-08 10:18:06 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 11:18:06.827  5544  5592 I jxcore-log: 
11-08 11:18:06.827  5544  5592 I jxcore-log: 2016-11-08 10:18:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-08 11:18:06.827  5544  5592 I jxcore-log: 
,11-08 11:18:06.828  5544  5592 I jxcore-log: 2016-11-08 10:18:06 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 11:18:06.828  5544  5592 I jxcore-log: 
11-08 11:18:06.828  5544  5592 I jxcore-log: 2016-11-08 10:18:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-08 11:18:06.828  5544  5592 I jxcore-log: 
11-08 11:18:06.828  5544  5592 I jxcore-log: 2016-11-08 10:18:06 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 11:18:06.828  5544  5592 I jxcore-log: 
11-08 11:18:06.829  5544  5592 I jxcore-log: 2016-11-08 10:18:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-08 11:18:06.829  5544  5592 I jxcore-log: 
11-08 11:18:06.830  5544  5592 I jxcore-log: 2016-11-08 10:18:06 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 11:18:06.830  5544  5592 I jxcore-log: 
11-08 11:18:06.830  5544  5592 I jxcore-log: 2016-11-08 10:18:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-08 11:18:06.830  5544  5592 I jxcore-log: 
11-08 11:18:06.830  5544  5592 I jxcore-log: 2016-11-08 10:18:06 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 11:18:06.830  5544  5592 I jxcore-log: 
11-08 11:18:06.830  5544  5592 I jxcore-log: 2016-11-08 10:18:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-08 11:18:06.830  5544  5592 I jxcore-log: 
11-08 11:18:06.831  5544  5592 I jxcore-log: 2016-11-08 10:18:06 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 11:18:06.831  5544  5592 I jxcore-log: 
,11-08 11:18:06.831  5544  5592 I jxcore-log: 2016-11-08 10:18:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-08 11:18:06.831  5544  5592 I jxcore-log: 
11-08 11:18:06.831  5544  5592 I jxcore-log: 2016-11-08 10:18:06 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 11:18:06.831  5544  5592 I jxcore-log: 
11-08 11:18:06.831  5544  5592 I jxcore-log: 2016-11-08 10:18:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-08 11:18:06.831  5544  5592 I jxcore-log: 
11-08 11:18:06.831  5544  5592 I jxcore-log: 2016-11-08 10:18:06 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 11:18:06.831  5544  5592 I jxcore-log: 
,11-08 11:18:06.831  5544  5592 I jxcore-log: 2016-11-08 10:18:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-08 11:18:06.831  5544  5592 I jxcore-log: 
11-08 11:18:06.832  5544  5592 I jxcore-log: 2016-11-08 10:18:06 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 11:18:06.832  5544  5592 I jxcore-log: 
11-08 11:18:06.832  5544  5592 I jxcore-log: 2016-11-08 10:18:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-08 11:18:06.832  5544  5592 I jxcore-log: 
11-08 11:18:06.832  5544  5592 I jxcore-log: 2016-11-08 10:18:06 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 11:18:06.832  5544  5592 I jxcore-log: 
11-08 11:18:06.832  5544  5544 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
11-08 11:18:06.832  5544  5592 I jxcore-log: 2016-11-08 10:18:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-08 11:18:06.832  5544  5592 I jxcore-log: 
,11-08 11:18:06.832  5544  5592 I jxcore-log: 2016-11-08 10:18:06 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 11:18:06.832  5544  5592 I jxcore-log: 
11-08 11:18:06.833  5544  5592 I jxcore-log: 2016-11-08 10:18:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-08 11:18:06.833  5544  5592 I jxcore-log: 
11-08 11:18:06.833  5544  5592 I jxcore-log: 2016-11-08 10:18:06 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 11:18:06.833  5544  5592 I jxcore-log: 
11-08 11:18:06.833  5544  5592 I jxcore-log: 2016-11-08 10:18:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-08 11:18:06.833  5544  5592 I jxcore-log: 
,11-08 11:18:06.833  5544  5592 I jxcore-log: 2016-11-08 10:18:06 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 11:18:06.833  5544  5592 I jxcore-log: 
11-08 11:18:06.833  5544  5592 I jxcore-log: 2016-11-08 10:18:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-08 11:18:06.833  5544  5592 I jxcore-log: 
11-08 11:18:06.833  5544  5592 I jxcore-log: 2016-11-08 10:18:06 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 11:18:06.833  5544  5592 I jxcore-log: 
,11-08 11:18:06.834  5544  5592 I jxcore-log: 2016-11-08 10:18:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-08 11:18:06.834  5544  5592 I jxcore-log: 
11-08 11:18:06.834  5544  5592 I jxcore-log: 2016-11-08 10:18:06 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 11:18:06.834  5544  5592 I jxcore-log: 
11-08 11:18:06.834  5544  5592 I jxcore-log: 2016-11-08 10:18:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-08 11:18:06.834  5544  5592 I jxcore-log: 
11-08 11:18:06.834  5544  5592 I jxcore-log: 2016-11-08 10:18:06 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 11:18:06.834  5544  5592 I jxcore-log: 
,11-08 11:18:06.834  5544  5592 I jxcore-log: 2016-11-08 10:18:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-08 11:18:06.834  5544  5592 I jxcore-log: 
11-08 11:18:06.835  5544  5592 I jxcore-log: 2016-11-08 10:18:06 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 11:18:06.835  5544  5592 I jxcore-log: 
11-08 11:18:06.835  5544  5592 I jxcore-log: 2016-11-08 10:18:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-08 11:18:06.835  5544  5592 I jxcore-log: 
11-08 11:18:06.835  5544  5592 I jxcore-log: 2016-11-08 10:18:06 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 11:18:06.835  5544  5592 I jxcore-log: 
,11-08 11:18:06.835  5544  5592 I jxcore-log: 2016-11-08 10:18:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-08 11:18:06.835  5544  5592 I jxcore-log: 
11-08 11:18:06.835  5544  5592 I jxcore-log: 2016-11-08 10:18:06 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 11:18:06.835  5544  5592 I jxcore-log: 
11-08 11:18:06.836  5544  5592 I jxcore-log: 2016-11-08 10:18:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-08 11:18:06.836  5544  5592 I jxcore-log: 
,11-08 11:18:06.836  5544  5592 I jxcore-log: 2016-11-08 10:18:06 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 11:18:06.836  5544  5592 I jxcore-log: 
11-08 11:18:06.836  5544  5592 I jxcore-log: 2016-11-08 10:18:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-08 11:18:06.836  5544  5592 I jxcore-log: 
11-08 11:18:06.836  5544  5592 I jxcore-log: 2016-11-08 10:18:06 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 11:18:06.836  5544  5592 I jxcore-log: 
11-08 11:18:06.836  5544  5592 I jxcore-log: 2016-11-08 10:18:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-08 11:18:06.836  5544  5592 I jxcore-log: 
,11-08 11:18:06.837  5544  5592 I jxcore-log: 2016-11-08 10:18:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-08 11:18:06.837  5544  5592 I jxcore-log: 
11-08 11:18:06.837  5544  5592 I jxcore-log: 2016-11-08 10:18:06 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 11:18:06.837  5544  5592 I jxcore-log: 
11-08 11:18:06.837  5544  5592 I jxcore-log: 2016-11-08 10:18:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-08 11:18:06.837  5544  5592 I jxcore-log: 
11-08 11:18:06.837  5544  5592 I jxcore-log: 2016-11-08 10:18:06 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 11:18:06.837  5544  5592 I jxcore-log: 
11-08 11:18:06.837  5544  5592 I jxcore-log: 2016-11-08 10:18:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-08 11:18:06.837  5544  5592 I jxcore-log: 
11-08 11:18:06.838  5544  5592 I jxcore-log: 2016-11-08 10:18:06 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 11:18:06.838  5544  5592 I jxcore-log: 
,11-08 11:18:06.838  5544  5592 I jxcore-log: 2016-11-08 10:18:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-08 11:18:06.838  5544  5592 I jxcore-log: 
11-08 11:18:06.838  5544  5592 I jxcore-log: 2016-11-08 10:18:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
11-08 11:18:06.838  5544  5592 I jxcore-log: 
11-08 11:18:06.838  5544  5592 I jxcore-log: 2016-11-08 10:18:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-08 11:18:06.838  5544  5592 I jxcore-log: 
,11-08 11:18:06.843  5544  5592 I jxcore-log: 2016-11-08 10:18:06 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
11-08 11:18:06.843  5544  5592 I jxcore-log: 
,11-08 11:18:06.844  5544  5592 I jxcore-log: 2016-11-08 10:18:06 - WARN testUtils: 'myNameCallback not set!'
11-08 11:18:06.844  5544  5592 I jxcore-log: 
,11-08 11:18:06.844  5544  5592 E JX-Cordova: jxcore.CallJSMethod :{"isFulfilled":false,"isRejected":false}
11-08 11:18:06.845  5544  5592 I jxcore-log: 2016-11-08 10:18:06 - DEBUG UnitTest_app: 'Running for NATIVE network type'
11-08 11:18:06.845  5544  5592 I jxcore-log: 
,11-08 11:18:08.808  5544  5592 I jxcore-log: 2016-11-08 10:18:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
11-08 11:18:08.808  5544  5592 I jxcore-log: 
,11-08 11:18:09.129  5544  5592 I jxcore-log: 2016-11-08 10:18:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
11-08 11:18:09.129  5544  5592 I jxcore-log: 
,11-08 11:18:09.142  5544  5592 I jxcore-log: 2016-11-08 10:18:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
11-08 11:18:09.142  5544  5592 I jxcore-log: 
,11-08 11:18:10.171   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 11:18:10.212  5544  5592 I jxcore-log: 2016-11-08 10:18:10 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
11-08 11:18:10.212  5544  5592 I jxcore-log: 
,11-08 11:18:10.376  5544  5592 I jxcore-log: 2016-11-08 10:18:10 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
11-08 11:18:10.376  5544  5592 I jxcore-log: 
,11-08 11:18:10.382  5544  5592 I jxcore-log: 2016-11-08 10:18:10 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
11-08 11:18:10.382  5544  5592 I jxcore-log: 
,11-08 11:18:10.387  5544  5592 I jxcore-log: 2016-11-08 10:18:10 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
11-08 11:18:10.387  5544  5592 I jxcore-log: 
,11-08 11:18:10.861  5544  5592 I jxcore-log: 2016-11-08 10:18:10 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
11-08 11:18:10.861  5544  5592 I jxcore-log: 
,11-08 11:18:10.903  5544  5592 I jxcore-log: 2016-11-08 10:18:10 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
11-08 11:18:10.903  5544  5592 I jxcore-log: 
,11-08 11:18:10.916  5544  5592 I jxcore-log: 2016-11-08 10:18:10 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
11-08 11:18:10.916  5544  5592 I jxcore-log: 
,11-08 11:18:10.920  5544  5592 I jxcore-log: 2016-11-08 10:18:10 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
11-08 11:18:10.920  5544  5592 I jxcore-log: 
,11-08 11:18:11.172   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 11:18:11.197  5544  5592 I jxcore-log: 2016-11-08 10:18:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
11-08 11:18:11.197  5544  5592 I jxcore-log: 
,11-08 11:18:11.335  5544  5592 I jxcore-log: 2016-11-08 10:18:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
11-08 11:18:11.335  5544  5592 I jxcore-log: 
,11-08 11:18:11.696  5544  5592 I jxcore-log: 2016-11-08 10:18:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
11-08 11:18:11.696  5544  5592 I jxcore-log: 
,11-08 11:18:11.730  5544  5592 I jxcore-log: 2016-11-08 10:18:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
11-08 11:18:11.730  5544  5592 I jxcore-log: 
,11-08 11:18:11.737  5544  5592 I jxcore-log: 2016-11-08 10:18:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
11-08 11:18:11.737  5544  5592 I jxcore-log: 
,11-08 11:18:11.742  5544  5592 I jxcore-log: 2016-11-08 10:18:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
11-08 11:18:11.742  5544  5592 I jxcore-log: 
,11-08 11:18:11.749  5544  5592 I jxcore-log: 2016-11-08 10:18:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
11-08 11:18:11.749  5544  5592 I jxcore-log: 
,11-08 11:18:11.762  5544  5592 I jxcore-log: 2016-11-08 10:18:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
11-08 11:18:11.762  5544  5592 I jxcore-log: 
,11-08 11:18:11.768  5544  5592 I jxcore-log: 2016-11-08 10:18:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
11-08 11:18:11.768  5544  5592 I jxcore-log: 
,11-08 11:18:11.795  5544  5592 I jxcore-log: 2016-11-08 10:18:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
11-08 11:18:11.795  5544  5592 I jxcore-log: 
,11-08 11:18:11.833  5544  5592 I jxcore-log: 2016-11-08 10:18:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
11-08 11:18:11.833  5544  5592 I jxcore-log: 
,11-08 11:18:11.840  5544  5592 I jxcore-log: 2016-11-08 10:18:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
11-08 11:18:11.840  5544  5592 I jxcore-log: 
,11-08 11:18:11.846  5544  5592 I jxcore-log: 2016-11-08 10:18:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
11-08 11:18:11.846  5544  5592 I jxcore-log: 
,11-08 11:18:11.861  5544  5592 I jxcore-log: 2016-11-08 10:18:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
11-08 11:18:11.861  5544  5592 I jxcore-log: 
,11-08 11:18:11.865  5544  5592 I jxcore-log: 2016-11-08 10:18:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
11-08 11:18:11.865  5544  5592 I jxcore-log: 
,11-08 11:18:11.871  5544  5592 I jxcore-log: 2016-11-08 10:18:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
11-08 11:18:11.871  5544  5592 I jxcore-log: 
,11-08 11:18:11.876  5544  5592 I jxcore-log: 2016-11-08 10:18:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
11-08 11:18:11.876  5544  5592 I jxcore-log: 
,11-08 11:18:11.889  5544  5592 I jxcore-log: 2016-11-08 10:18:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
11-08 11:18:11.889  5544  5592 I jxcore-log: 
,11-08 11:18:11.896  5544  5592 I jxcore-log: 2016-11-08 10:18:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
11-08 11:18:11.896  5544  5592 I jxcore-log: 
,11-08 11:18:11.918  5544  5592 I jxcore-log: 2016-11-08 10:18:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
11-08 11:18:11.918  5544  5592 I jxcore-log: 
,11-08 11:18:11.929  5544  5592 I jxcore-log: 2016-11-08 10:18:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
11-08 11:18:11.929  5544  5592 I jxcore-log: 
,11-08 11:18:11.940  5544  5592 I jxcore-log: 2016-11-08 10:18:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
11-08 11:18:11.940  5544  5592 I jxcore-log: 
,11-08 11:18:11.950  5544  5592 I jxcore-log: 2016-11-08 10:18:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
11-08 11:18:11.950  5544  5592 I jxcore-log: 
,11-08 11:18:11.963  5544  5592 I jxcore-log: 2016-11-08 10:18:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
11-08 11:18:11.963  5544  5592 I jxcore-log: 
,11-08 11:18:11.973  5544  5592 I jxcore-log: 2016-11-08 10:18:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
11-08 11:18:11.973  5544  5592 I jxcore-log: 
,11-08 11:18:11.979  5544  5592 I jxcore-log: 2016-11-08 10:18:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
11-08 11:18:11.979  5544  5592 I jxcore-log: 
,11-08 11:18:11.985  5544  5592 I jxcore-log: 2016-11-08 10:18:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testUsn.js'
11-08 11:18:11.985  5544  5592 I jxcore-log: 
,11-08 11:18:11.991  5544  5592 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,11-08 11:18:11.992  5544  5592 I jxcore-log: 2016-11-08 10:18:11 - INFO testUtils: 'BLE multiple advertisement supported'
11-08 11:18:11.992  5544  5592 I jxcore-log: 
,11-08 11:18:12.069  5544  5592 I jxcore-log: 2016-11-08 10:18:12 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 11:18:12.069  5544  5592 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 11:18:12.069  5544  5592 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 11:18:12.069  5544  5592 I jxcore-log: emit@events.js:82:1
11-08 11:18:12.069  5544  5592 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 11:18:12.069  5544  5592 I jxcore-log: emit@events.js:82:1'
11-08 11:18:12.069  5544  5592 I jxcore-log: 
,11-08 11:18:12.172   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 11:18:12.337  5544  5592 I jxcore-log: 2016-11-08 10:18:12 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 11:18:12.337  5544  5592 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 11:18:12.337  5544  5592 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 11:18:12.337  5544  5592 I jxcore-log: emit@events.js:82:1
11-08 11:18:12.337  5544  5592 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 11:18:12.337  5544  5592 I jxcore-log: emit@events.js:82:1'
11-08 11:18:12.337  5544  5592 I jxcore-log: 
,11-08 11:18:12.340  5544  5592 I jxcore-log: 2016-11-08 10:18:12 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 11:18:12.340  5544  5592 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 11:18:12.340  5544  5592 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 11:18:12.340  5544  5592 I jxcore-log: emit@events.js:82:1
11-08 11:18:12.340  5544  5592 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 11:18:12.340  5544  5592 I jxcore-log: emit@events.js:82:1'
11-08 11:18:12.340  5544  5592 I jxcore-log: 
,11-08 11:18:12.889  5544  5592 I jxcore-log: 2016-11-08 10:18:12 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 11:18:12.889  5544  5592 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 11:18:12.889  5544  5592 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 11:18:12.889  5544  5592 I jxcore-log: emit@events.js:82:1
11-08 11:18:12.889  5544  5592 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 11:18:12.889  5544  5592 I jxcore-log: emit@events.js:82:1'
11-08 11:18:12.889  5544  5592 I jxcore-log: 
,11-08 11:18:12.894  5544  5592 I jxcore-log: 2016-11-08 10:18:12 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 11:18:12.894  5544  5592 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 11:18:12.894  5544  5592 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 11:18:12.894  5544  5592 I jxcore-log: emit@events.js:82:1
11-08 11:18:12.894  5544  5592 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 11:18:12.894  5544  5592 I jxcore-log: emit@events.js:82:1'
11-08 11:18:12.894  5544  5592 I jxcore-log: 
,11-08 11:18:13.173   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 11:18:13.534  5544  5592 I jxcore-log: 2016-11-08 10:18:13 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 11:18:13.534  5544  5592 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 11:18:13.534  5544  5592 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 11:18:13.534  5544  5592 I jxcore-log: emit@events.js:82:1
11-08 11:18:13.534  5544  5592 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 11:18:13.534  5544  5592 I jxcore-log: emit@events.js:82:1'
11-08 11:18:13.534  5544  5592 I jxcore-log: 
,11-08 11:18:13.537  5544  5592 I jxcore-log: 2016-11-08 10:18:13 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 11:18:13.537  5544  5592 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 11:18:13.537  5544  5592 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 11:18:13.537  5544  5592 I jxcore-log: emit@events.js:82:1
11-08 11:18:13.537  5544  5592 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 11:18:13.537  5544  5592 I jxcore-log: emit@events.js:82:1'
11-08 11:18:13.537  5544  5592 I jxcore-log: 
,11-08 11:18:14.175   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 11:18:14.568  5544  5592 I jxcore-log: 2016-11-08 10:18:14 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 11:18:14.568  5544  5592 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 11:18:14.568  5544  5592 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 11:18:14.568  5544  5592 I jxcore-log: emit@events.js:82:1
11-08 11:18:14.568  5544  5592 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 11:18:14.568  5544  5592 I jxcore-log: emit@events.js:82:1'
11-08 11:18:14.568  5544  5592 I jxcore-log: 
,11-08 11:18:14.575  5544  5592 I jxcore-log: 2016-11-08 10:18:14 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 11:18:14.575  5544  5592 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 11:18:14.575  5544  5592 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 11:18:14.575  5544  5592 I jxcore-log: emit@events.js:82:1
11-08 11:18:14.575  5544  5592 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 11:18:14.575  5544  5592 I jxcore-log: emit@events.js:82:1'
11-08 11:18:14.575  5544  5592 I jxcore-log: 
,11-08 11:18:15.175   546   546 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-08 11:18:15.614  5544  5592 I jxcore-log: 2016-11-08 10:18:15 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 11:18:15.614  5544  5592 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 11:18:15.614  5544  5592 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 11:18:15.614  5544  5592 I jxcore-log: emit@events.js:82:1
11-08 11:18:15.614  5544  5592 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 11:18:15.614  5544  5592 I jxcore-log: emit@events.js:82:1'
11-08 11:18:15.614  5544  5592 I jxcore-log: 
,11-08 11:18:15.618  5544  5592 I jxcore-log: 2016-11-08 10:18:15 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 11:18:15.618  5544  5592 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 11:18:15.618  5544  5592 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 11:18:15.618  5544  5592 I jxcore-log: emit@events.js:82:1
11-08 11:18:15.618  5544  5592 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 11:18:15.618  5544  5592 I jxcore-log: emit@events.js:82:1'
11-08 11:18:15.618  5544  5592 I jxcore-log: 
,11-08 11:18:16.654  5544  5592 I jxcore-log: 2016-11-08 10:18:16 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 11:18:16.654  5544  5592 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 11:18:16.654  5544  5592 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 11:18:16.654  5544  5592 I jxcore-log: emit@events.js:82:1
11-08 11:18:16.654  5544  5592 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 11:18:16.654  5544  5592 I jxcore-log: emit@events.js:82:1'
11-08 11:18:16.654  5544  5592 I jxcore-log: 
,11-08 11:18:16.657  5544  5592 I jxcore-log: 2016-11-08 10:18:16 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 11:18:16.657  5544  5592 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 11:18:16.657  5544  5592 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 11:18:16.657  5544  5592 I jxcore-log: emit@events.js:82:1
11-08 11:18:16.657  5544  5592 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 11:18:16.657  5544  5592 I jxcore-log: emit@events.js:82:1'
11-08 11:18:16.657  5544  5592 I jxcore-log: 
,11-08 11:18:17.064   934  5850 D NetlinkSocketObserver: NeighborEvent{elapsedMs=150917, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,11-08 11:18:17.691  5544  5592 I jxcore-log: 2016-11-08 10:18:17 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 11:18:17.691  5544  5592 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 11:18:17.691  5544  5592 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 11:18:17.691  5544  5592 I jxcore-log: emit@events.js:82:1
11-08 11:18:17.691  5544  5592 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 11:18:17.691  5544  5592 I jxcore-log: emit@events.js:82:1'
11-08 11:18:17.691  5544  5592 I jxcore-log: 
,11-08 11:18:17.694  5544  5592 I jxcore-log: 2016-11-08 10:18:17 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 11:18:17.694  5544  5592 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 11:18:17.694  5544  5592 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 11:18:17.694  5544  5592 I jxcore-log: emit@events.js:82:1
11-08 11:18:17.694  5544  5592 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 11:18:17.694  5544  5592 I jxcore-log: emit@events.js:82:1'
11-08 11:18:17.694  5544  5592 I jxcore-log: 
,11-08 11:18:18.318   934   954 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,11-08 11:18:18.324  3687  3687 W Binder_A: type=1400 audit(0.0:127): avc: denied { ioctl } for path="socket:[32418]" dev="sockfs" ino=32418 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-08 11:18:18.328  3578  3578 I Keyboard.Facilitator: onFinishInput()
11-08 11:18:18.327  3687  3687 W Binder_A: type=1400 audit(0.0:128): avc: denied { ioctl } for path="socket:[32418]" dev="sockfs" ino=32418 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-08 11:18:18.341   934   954 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-08 11:18:18.341   934   954 I Adreno  : Build Date                       : 12/06/15
11-08 11:18:18.341   934   954 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-08 11:18:18.341   934   954 I Adreno  : Local Branch                     : mybranch17112971
11-08 11:18:18.341   934   954 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-08 11:18:18.341   934   954 I Adreno  : Remote Branch                    : NONE
11-08 11:18:18.341   934   954 I Adreno  : Reconstruct Branch               : NOTHING
,11-08 11:18:18.369   383   408 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (171 us)
,11-08 11:18:18.724  5544  5592 I jxcore-log: 2016-11-08 10:18:18 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 11:18:18.724  5544  5592 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 11:18:18.724  5544  5592 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 11:18:18.724  5544  5592 I jxcore-log: emit@events.js:82:1
11-08 11:18:18.724  5544  5592 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 11:18:18.724  5544  5592 I jxcore-log: emit@events.js:82:1'
11-08 11:18:18.724  5544  5592 I jxcore-log: 
,11-08 11:18:18.729  5544  5592 I jxcore-log: 2016-11-08 10:18:18 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 11:18:18.729  5544  5592 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 11:18:18.729  5544  5592 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 11:18:18.729  5544  5592 I jxcore-log: emit@events.js:82:1
11-08 11:18:18.729  5544  5592 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 11:18:18.729  5544  5592 I jxcore-log: emit@events.js:82:1'
11-08 11:18:18.729  5544  5592 I jxcore-log: 
,11-08 11:18:19.032  5544  5544 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
11-08 11:18:19.032  5544  5544 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,11-08 11:18:19.060   934   954 I sensors : batch
,11-08 11:18:19.060   934   954 V KeyguardServiceDelegate: onScreenTurnedOff()
11-08 11:18:19.063   934   954 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
11-08 11:18:19.063  5544  5544 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@db9b972 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@42b3fac, 16908290=android.view.AbsSavedState$1@42b3fac}, android:focusedViewId=100}]}]
11-08 11:18:19.063  5544  5544 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
11-08 11:18:19.063   934   954 I sensors : activate
,11-08 11:18:19.064  5544  5544 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,11-08 11:18:19.064  5544  5544 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,11-08 11:18:19.064   934   952 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
11-08 11:18:19.066   383   383 D SurfaceFlinger: Set power mode=0, type=0 flinger=0x7fa9c43c00
11-08 11:18:19.066   383   383 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,11-08 11:18:19.069   934  2647 I hubconnection: sensorhub said: 'batch 31 flags:0, sampling_rate_Hz:15.00, max_report_latency_us:0'
11-08 11:18:19.071   934  2647 I hubconnection: sensorhub said: 'activate 7 enable:0'
,11-08 11:18:19.288   510   927 D TetherController: Setting IP forward enable = 1
,11-08 11:18:19.357   383   483 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,11-08 11:18:19.358   383   383 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,11-08 11:18:19.359   934  3014 D SurfaceControl: Excessive delay in setPowerMode(): 294ms
,11-08 11:18:19.362   934   954 I DreamManagerService: Entering dreamland.
,11-08 11:18:19.363   934   954 I PowerManagerService: Dozing...
11-08 11:18:19.364   934   949 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,11-08 11:18:19.380  3668  3668 W Binder_8: type=1400 audit(0.0:129): avc: denied { ioctl } for path="socket:[33160]" dev="sockfs" ino=33160 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-08 11:18:19.380  3668  3668 W Binder_8: type=1400 audit(0.0:130): avc: denied { ioctl } for path="socket:[33160]" dev="sockfs" ino=33160 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-08 11:18:19.383   934   945 I sensors : batch
11-08 11:18:19.383   934   945 I sensors : activate
,11-08 11:18:19.386   934  2647 I hubconnection: sensorhub said: 'batch 21 flags:0, sampling_rate_Hz:1000.00, max_report_latency_us:0'
,11-08 11:18:19.387   934  2647 I hubconnection: sensorhub said: 'activate 21 enable:1'
,11-08 11:18:19.391   515  2925 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,11-08 11:18:19.396   934  2875 E native  : do suspend false
,11-08 11:18:19.404   934  2875 D WifiConfigStore: No blacklist allowed without epno enabled
,11-08 11:18:19.412  3674  4694 D ScreenStateRecorder : ScreenStateRecorderHandler, handleMessage msg.what = 1
,11-08 11:18:19.412  3674  4694 D         : oem_qmi_lib:come into oem_qmi_common_stream_from_modem_len --->modem 
,11-08 11:18:19.413  3674  4694 D         : oem_qmi_lib:oem_qmi_cmd: Send to server  passed!!
11-08 11:18:19.413   528  1319 D         : oem-qmi: Connection accepted
11-08 11:18:19.413   528  1319 D         : oem-qmi: Waiting to accept connection
,11-08 11:18:19.415   934   934 I sensors : activate
11-08 11:18:19.416   515  2924 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
11-08 11:18:19.416  3674  4694 D         : oem_qmi_lib:output 0
11-08 11:18:19.416  3674  4694 D         : oem_qmi_lib:rapi_event_type=10057, qmi_ret=0, return_status=1. 
,11-08 11:18:19.418   934  2647 I hubconnection: sensorhub said: 'activate 31 enable:0'
,11-08 11:18:19.418   934  2875 E native  : do suspend true
,11-08 11:18:19.435  3674  4694 D ScreenStateRecorder : ScreenStateRecorderHandler, handleMessage msg.what = 2
,11-08 11:18:19.435  3674  4694 D         : oem_qmi_lib:come into oem_qmi_common_stream_from_modem_len --->modem 
11-08 11:18:19.436  3674  4694 D         : oem_qmi_lib:oem_qmi_cmd: Send to server  passed!!
11-08 11:18:19.436   528  1319 D         : oem-qmi: Connection accepted
11-08 11:18:19.436   528  1319 D         : oem-qmi: Waiting to accept connection
,11-08 11:18:19.438  3674  4694 D         : oem_qmi_lib:output 0
,11-08 11:18:19.438  3674  4694 D         : oem_qmi_lib:rapi_event_type=10057, qmi_ret=0, return_status=1. 
,11-08 11:18:19.813  5544  5592 I jxcore-log: 2016-11-08 10:18:19 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 11:18:19.813  5544  5592 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 11:18:19.813  5544  5592 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 11:18:19.813  5544  5592 I jxcore-log: emit@events.js:82:1
11-08 11:18:19.813  5544  5592 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 11:18:19.813  5544  5592 I jxcore-log: emit@events.js:82:1'
11-08 11:18:19.813  5544  5592 I jxcore-log: 
,11-08 11:18:19.818  5544  5592 I jxcore-log: 2016-11-08 10:18:19 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 11:18:19.818  5544  5592 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 11:18:19.818  5544  5592 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 11:18:19.818  5544  5592 I jxcore-log: emit@events.js:82:1
11-08 11:18:19.818  5544  5592 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 11:18:19.818  5544  5592 I jxcore-log: emit@events.js:82:1'
11-08 11:18:19.818  5544  5592 I jxcore-log: 
,11-08 11:18:19.894   934  2875 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 13, 14 -> obsolete
,11-08 11:18:20.894  5544  5592 I jxcore-log: 2016-11-08 10:18:20 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 11:18:20.894  5544  5592 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 11:18:20.894  5544  5592 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 11:18:20.894  5544  5592 I jxcore-log: emit@events.js:82:1
11-08 11:18:20.894  5544  5592 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 11:18:20.894  5544  5592 I jxcore-log: emit@events.js:82:1'
11-08 11:18:20.894  5544  5592 I jxcore-log: 
,11-08 11:18:20.899  5544  5592 I jxcore-log: 2016-11-08 10:18:20 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 11:18:20.899  5544  5592 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 11:18:20.899  5544  5592 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 11:18:20.899  5544  5592 I jxcore-log: emit@events.js:82:1
11-08 11:18:20.899  5544  5592 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 11:18:20.899  5544  5592 I jxcore-log: emit@events.js:82:1'
11-08 11:18:20.899  5544  5592 I jxcore-log: 
,11-08 11:18:21.121   934  2875 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
,11-08 11:18:21.945  5544  5592 I jxcore-log: 2016-11-08 10:18:21 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 11:18:21.945  5544  5592 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 11:18:21.945  5544  5592 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 11:18:21.945  5544  5592 I jxcore-log: emit@events.js:82:1
11-08 11:18:21.945  5544  5592 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 11:18:21.945  5544  5592 I jxcore-log: emit@events.js:82:1'
11-08 11:18:21.945  5544  5592 I jxcore-log: 
,11-08 11:18:21.949  5544  5592 I jxcore-log: 2016-11-08 10:18:21 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 11:18:21.949  5544  5592 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 11:18:21.949  5544  5592 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 11:18:21.949  5544  5592 I jxcore-log: emit@events.js:82:1
11-08 11:18:21.949  5544  5592 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 11:18:21.949  5544  5592 I jxcore-log: emit@events.js:82:1'
11-08 11:18:21.949  5544  5592 I jxcore-log: 
,11-08 11:18:22.995  5544  5592 I jxcore-log: 2016-11-08 10:18:22 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 11:18:22.995  5544  5592 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 11:18:22.995  5544  5592 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 11:18:22.995  5544  5592 I jxcore-log: emit@events.js:82:1
11-08 11:18:22.995  5544  5592 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 11:18:22.995  5544  5592 I jxcore-log: emit@events.js:82:1'
11-08 11:18:22.995  5544  5592 I jxcore-log: 
,11-08 11:18:23.000  5544  5592 I jxcore-log: 2016-11-08 10:18:22 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 11:18:23.000  5544  5592 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 11:18:23.000  5544  5592 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 11:18:23.000  5544  5592 I jxcore-log: emit@events.js:82:1
11-08 11:18:23.000  5544  5592 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 11:18:23.000  5544  5592 I jxcore-log: emit@events.js:82:1'
11-08 11:18:23.000  5544  5592 I jxcore-log: 
,11-08 11:18:23.600  4024  4430 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,11-08 11:18:24.034  5544  5592 I jxcore-log: 2016-11-08 10:18:24 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 11:18:24.034  5544  5592 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 11:18:24.034  5544  5592 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 11:18:24.034  5544  5592 I jxcore-log: emit@events.js:82:1
11-08 11:18:24.034  5544  5592 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 11:18:24.034  5544  5592 I jxcore-log: emit@events.js:82:1'
11-08 11:18:24.034  5544  5592 I jxcore-log: 
,11-08 11:18:24.038  5544  5592 I jxcore-log: 2016-11-08 10:18:24 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 11:18:24.038  5544  5592 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 11:18:24.038  5544  5592 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 11:18:24.038  5544  5592 I jxcore-log: emit@events.js:82:1
11-08 11:18:24.038  5544  5592 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 11:18:24.038  5544  5592 I jxcore-log: emit@events.js:82:1'
11-08 11:18:24.038  5544  5592 I jxcore-log: 
,11-08 11:18:25.074  5544  5592 I jxcore-log: 2016-11-08 10:18:25 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 11:18:25.074  5544  5592 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 11:18:25.074  5544  5592 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 11:18:25.074  5544  5592 I jxcore-log: emit@events.js:82:1
11-08 11:18:25.074  5544  5592 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 11:18:25.074  5544  5592 I jxcore-log: emit@events.js:82:1'
11-08 11:18:25.074  5544  5592 I jxcore-log: 
,11-08 11:18:25.079  5544  5592 I jxcore-log: 2016-11-08 10:18:25 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 11:18:25.079  5544  5592 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 11:18:25.079  5544  5592 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 11:18:25.079  5544  5592 I jxcore-log: emit@events.js:82:1
11-08 11:18:25.079  5544  5592 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 11:18:25.079  5544  5592 I jxcore-log: emit@events.js:82:1'
11-08 11:18:25.079  5544  5592 I jxcore-log: 
,11-08 11:18:26.126  5544  5592 I jxcore-log: 2016-11-08 10:18:26 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 11:18:26.126  5544  5592 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 11:18:26.126  5544  5592 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 11:18:26.126  5544  5592 I jxcore-log: emit@events.js:82:1
11-08 11:18:26.126  5544  5592 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 11:18:26.126  5544  5592 I jxcore-log: emit@events.js:82:1'
11-08 11:18:26.126  5544  5592 I jxcore-log: 
,11-08 11:18:26.136  5544  5592 E jxcore  : Error!: error is undefined
11-08 11:18:26.136  5544  5592 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js","_functionName":"CoordinatedClient.prototype._error","_lineNumber":"220","_columnNumber":"1","_msg":"    at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:220:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.emit","_lineNumber":"133","_columnNumber":"5","_msg":"    at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.emitAll","_lineNumber":"81","_columnNumber":"7","_msg":"    at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect","_lineNumber":"507","_columnNumber":"5","_msg":"    at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect/timer</<","_lineNumber":"528","_columnNumber":"11","_msg":"    at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.connect/errorSub<","_lineNumber":"235","_columnNumber":"7","_msg":"    at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js","_functionName":"Socket.prototype.onError","_lineNumber":"670","_columnNumber":"3","_msg":"    at Socket.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3"}]
,11-08 11:18:26.142  5544  5592 I jxcore-log: 2016-11-08 10:18:26 - ERROR TestsProcess: 'uncaught exception, error: 'TypeError: error is undefined', stack: 'TypeError: error is undefined
11-08 11:18:26.142  5544  5592 I jxcore-log:     at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:220:1
11-08 11:18:26.142  5544  5592 I jxcore-log:     at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7
11-08 11:18:26.142  5544  5592 I jxcore-log:     at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5
11-08 11:18:26.142  5544  5592 I jxcore-log:     at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7
11-08 11:18:26.142  5544  5592 I jxcore-log:     at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5
11-08 11:18:26.142  5544  5592 I jxcore-log:     at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11
11-08 11:18:26.142  5544  5592 I jxcore-log:     at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/sock
,11-08 11:18:26.144  5544  5592 I jxcore-log: 2016-11-08 10:18:26 - ERROR TestsProcess: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
11-08 11:18:26.144  5544  5592 I jxcore-log: 
,11-08 11:18:26.146  5544  5592 E jxcore-log: TypeError: 
11-08 11:18:26.146  5544  5592 E jxcore-log: error is undefined
11-08 11:18:26.146  5544  5592 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js 220:0)
11-08 11:18:26.146  5544  5592 E jxcore-log: 
,11-08 11:18:26.216   934  2866 W InputDispatcher: channel 'f28c303 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
,11-08 11:18:26.216   934  2866 E InputDispatcher: channel 'f28c303 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
,11-08 11:18:26.227   934   945 D GraphicsStats: Buffer count: 2
,11-08 11:18:26.227   934  3668 I WindowState: WIN DEATH: Window{f28c303 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,11-08 11:18:26.227   934  3668 W InputDispatcher: Attempted to unregister already unregistered input channel 'f28c303 com.test.thalitest/com.test.thalitest.MainActivity (server)'
,11-08 11:18:26.228   934  2876 D WifiService: Client connection lost with reason: 4
,11-08 11:18:26.232   530   530 I Zygote  : Process 5544 exited cleanly (139)
,11-08 11:18:26.234   934  3516 I ActivityManager: Process com.test.thalitest (pid 5544) has died
,11-08 11:18:26.259   934  3516 I ActivityManager: Start proc 5926:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
,11-08 11:18:26.344  5926  5926 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,11-08 11:18:26.366  5926  5926 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,11-08 11:18:26.372  5926  5926 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 223-225)
,11-08 11:18:26.372  5926  5926 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-08 11:18:26.383  5926  5926 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3e5842f}
,11-08 11:18:26.383  5926  5926 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-08 11:18:26.383  5926  5926 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,11-08 11:18:26.387  5926  5926 I BrowserStartupController: Initializing chromium process, singleProcess=true
,11-08 11:18:26.388  5926  5926 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-08 11:18:26.399  5926  5926 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-08 11:18:26.408  5926  5926 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-08 11:18:26.408  5926  5926 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-08 11:18:26.408  5926  5926 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-08 11:18:26.408  5926  5926 I Adreno  : Build Date                       : 12/06/15
11-08 11:18:26.408  5926  5926 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-08 11:18:26.408  5926  5926 I Adreno  : Local Branch                     : mybranch17112971
11-08 11:18:26.408  5926  5926 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-08 11:18:26.408  5926  5926 I Adreno  : Remote Branch                    : NONE
11-08 11:18:26.408  5926  5926 I Adreno  : Reconstruct Branch               : NOTHING
,11-08 11:18:26.440   934   951 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6149f5d:true
,11-08 11:18:26.454   406   406 W Binder_1: type=1400 audit(0.0:131): avc: denied { ioctl } for path="socket:[27347]" dev="sockfs" ino=27347 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-08 11:18:26.454   406   406 W Binder_1: type=1400 audit(0.0:132): avc: denied { ioctl } for path="socket:[27347]" dev="sockfs" ino=27347 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-08 11:18:26.466  5926  5926 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-08 11:18:26.474  5926  5926 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-08 11:18:26.497   406   406 W Binder_1: type=1400 audit(0.0:133): avc: denied { ioctl } for path="socket:[35679]" dev="sockfs" ino=35679 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-08 11:18:26.500  5926  5962 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-08 11:18:26.497   406   406 W Binder_1: type=1400 audit(0.0:134): avc: denied { ioctl } for path="socket:[35679]" dev="sockfs" ino=35679 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-08 11:18:26.500  3068  3068 W Binder_3: type=1400 audit(0.0:135): avc: denied { ioctl } for path="socket:[14938]" dev="sockfs" ino=14938 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-08 11:18:26.500  3068  3068 W Binder_3: type=1400 audit(0.0:136): avc: denied { ioctl } for path="socket:[14938]" dev="sockfs" ino=14938 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-08 11:18:26.505  5926  5949 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-08 11:18:26.547  5926  5962 I OpenGLRenderer: Initialized EGL, version 1.4
,11-08 11:18:26.575   934   944 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5544 uid 10077
,11-08 11:18:26.574   944   944 W Binder_1: type=1400 audit(0.0:137): avc: denied { ioctl } for path="socket:[35685]" dev="sockfs" ino=35685 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-08 11:18:26.574   944   944 W Binder_1: type=1400 audit(0.0:138): avc: denied { ioctl } for path="socket:[35685]" dev="sockfs" ino=35685 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-08 11:18:26.574  3668  3668 W Binder_8: type=1400 audit(0.0:139): avc: denied { ioctl } for path="socket:[35684]" dev="sockfs" ino=35684 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-08 11:18:26.577  3668  3668 W Binder_8: type=1400 audit(0.0:140): avc: denied { ioctl } for path="socket:[35684]" dev="sockfs" ino=35684 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-08 11:18:26.577   934   952 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +286ms (total +339ms)
,11-08 11:18:26.581  3578  3578 I Keyboard.Facilitator: onFinishInput()
,11-08 11:18:26.626  5926  5926 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5926
,11-08 11:18:26.660  5926  5926 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,11-08 11:18:26.691  5924  5924 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,11-08 11:18:26.709  5924  5924 D AndroidRuntime: CheckJNI is OFF
,11-08 11:18:26.731  5924  5924 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,11-08 11:18:26.753  5924  5924 I Radio-JNI: register_android_hardware_Radio DONE
,11-08 11:18:26.768  5924  5924 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-08 11:18:26.776   934   947 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
11-08 11:18:26.776   934   947 I ActivityManager: Killing 5926:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,11-08 11:18:26.819   934  3122 D GraphicsStats: Buffer count: 2
,11-08 11:18:26.819   934  3668 I WindowState: WIN DEATH: Window{db6f1d0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,11-08 11:18:26.881   934   947 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
11-08 11:18:26.882   934   947 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,11-08 11:18:26.882   934   947 E ActivityManager: Failure starting process com.test.thalitest
11-08 11:18:26.882   934   947 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
11-08 11:18:26.882   934   947 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
11-08 11:18:26.882   934   947 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
11-08 11:18:26.882   934   947 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
11-08 11:18:26.882   934   947 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
11-08 11:18:26.882   934   947 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
11-08 11:18:26.882   934   947 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
11-08 11:18:26.882   934   947 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
11-08 11:18:26.882   934   947 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
11-08 11:18:26.882   934   947 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
11-08 11:18:26.882   934   947 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
11-08 11:18:26.882   934   947 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
11-08 11:18:26.882   934   947 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
11-08 11:18:26.882   934   947 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
11-08 11:18:26.882   934   947 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
11-08 11:18:26.882   934   947 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-08 11:18:26.882   934   947 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
11-08 11:18:26.882   934   947 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-08 11:18:26.882   934   947 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,11-08 11:18:26.883   934   947 I ActivityManager:   Force finishing activity ActivityRecord{415cc08 u0 com.test.thalitest/.MainActivity t68}
11-08 11:18:26.883   934   957 I art     : Starting a blocking GC Explicit
,11-08 11:18:26.895   934  3342 W ActivityManager: Spurious death for ProcessRecord{6fc64ce 0:com.test.thalitest/u0a77}, curProc for 5926: null
,11-08 11:18:26.967   934   957 I art     : Explicit concurrent mark sweep GC freed 15881(1055KB) AllocSpace objects, 6(120KB) LOS objects, 33% free, 29MB/43MB, paused 1.917ms total 83.644ms
,11-08 11:18:26.992   934   957 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,11-08 11:18:26.997  5924  5924 I art     : System.exit called, status: 0
,11-08 11:18:26.997  5924  5924 I AndroidRuntime: VM exiting with result code 0.
,11-08 11:18:27.006   934   957 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,11-08 11:18:27.018   934   947 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,11-08 11:18:27.021  3578  3578 I Keyboard.Facilitator: resetDictionaries() : en_US
,11-08 11:18:27.025  5786  5786 D BluetoothMapAppObserver: onReceive
11-08 11:18:27.025  5786  5786 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,11-08 11:18:27.034  4024  4087 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,11-08 11:18:27.035   934  2867 I InputReader: Reconfiguring input devices.  changes=0x00000010
,11-08 11:18:27.059  3578  5978 I Keyboard.Facilitator.DecoderInitializer: run()
,11-08 11:18:27.065  3325  5980 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,11-08 11:18:27.086  3578  5978 I Decoder : createOrResetDecoder
,11-08 11:18:27.090  4576  4576 W kworker/1:3: type=1400 audit(0.0:141): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-08 11:18:27.093  3674  3674 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,11-08 11:18:27.094  4576  4576 W kworker/1:3: type=1400 audit(0.0:142): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-08 11:18:27.099   934   934 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,11-08 11:18:27.110  4576  4576 W kworker/1:3: type=1400 audit(0.0:143): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
11-08 11:18:27.115  3502  3502 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
11-08 11:18:27.116  3502  3502 D AndroidRuntime: Shutting down VM
--------- beginning of crash
11-08 11:18:27.116  3502  3502 E AndroidRuntime: FATAL EXCEPTION: main
11-08 11:18:27.116  3502  3502 E AndroidRuntime: Process: com.google.process.gapps, PID: 3502
11-08 11:18:27.116  3502  3502 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-08 11:18:27.116  3502  3502 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
11-08 11:18:27.116  3502  3502 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
11-08 11:18:27.116  3502  3502 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
11-08 11:18:27.116  3502  3502 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-08 11:18:27.116  3502  3502 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-08 11:18:27.116  3502  3502 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-08 11:18:27.116  3502  3502 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
11-08 11:18:27.116  3502  3502 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-08 11:18:27.116  3502  3502 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-08 11:18:27.116  3502  3502 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-08 11:18:27.116  3502  3502 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-08 11:18:27.116  3502  3502 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-08 11:18:27.116  3502  3502 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-08 11:18:27.116  3502  3502 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-08 11:18:27.116  3502  3502 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-08 11:18:27.116  3502  3502 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
11-08 11:18:27.116  3502  3502 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
11-08 11:18:27.116  3502  3502 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
11-08 11:18:27.116  3502  3502 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
11-08 11:18:27.116  3502  3502 E AndroidRuntime: 	... 8 more
,11-08 11:18:27.122  3695  3830 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
11-08 11:18:27.122   934   946 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
11-08 11:18:27.122   934   946 E PackageManager: Failed to write settings, restoring backup
11-08 11:18:27.122   934   946 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
11-08 11:18:27.122   934   946 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
11-08 11:18:27.122   934   946 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
11-08 11:18:27.122   934   946 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
11-08 11:18:27.122   934   946 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
11-08 11:18:27.122   934   946 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-08 11:18:27.122   934   946 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
11-08 11:18:27.122   934   946 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-08 11:18:27.123   934  5984 E DropBoxManagerService: Can't write: system_app_crash
11-08 11:18:27.123   934  5984 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop121.tmp: open failed: EROFS (Read-only file system)
11-08 11:18:27.123   934  5984 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-08 11:18:27.123   934  5984 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-08 11:18:27.123   934  5984 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-08 11:18:27.123   934  5984 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-08 11:18:27.123   934  5984 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-08 11:18:27.123   934  5984 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-08 11:18:27.123   934  5984 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-08 11:18:27.123   934  5984 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-08 11:18:27.123   934  5984 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-08 11:18:27.123   934  5984 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-08 11:18:27.123   934  5984 E DropBoxManagerService: 	... 5 more
11-08 11:18:27.124   934   947 E DropBoxManagerService: Can't write: system_server_wtf
11-08 11:18:27.124   934   947 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
11-08 11:18:27.124   934   947 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-08 11:18:27.124   934   947 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-08 11:18:27.124   934   947 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-08 11:18:27.124   934   947 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-08 11:18:27.124   934   947 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-08 11:18:27.124   934   947 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-08 11:18:27.124   934   947 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12561)
11-08 11:18:27.124   934   947 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12374)
11-08 11:18:27.124   934   947 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12346)
11-08 11:18:27.124   934   947 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
11-08 11:18:27.124   934   947 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-08 11:18:27.124   934   947 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
11-08 11:18:27.124   934   947 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-08 11:18:27.124   934   947 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
11-08 11:18:27.124   934   947 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-08 11:18:27.124   934   947 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-08 11:18:27.124   934   947 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-08 11:18:27.124   934   947 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-08 11:18:27.124   934   947 E DropBoxManagerService: 	... 13 more
11-08 11:18:27.130  3325  3350 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mjBCD7BE93B) - 
11-08 11:18:27.136   934  3673 I ActivityManager: Start proc 5985:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
11-08 11:18:27.137  3695  3830 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
11-08 11:18:27.137  3695  3830 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3695
11-08 11:18:27.137  3695  3830 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-08 11:18:27.137  3695  3830 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-08 11:18:27.137  3695  3830 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-08 11:18:27.137  3695  3830 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-08 11:18:27.137  3695  3830 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-08 11:18:27.137  3695  3830 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-08 11:18:27.137  3695  3830 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
11-08 11:18:27.137  3695  3830 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
11-08 11:18:27.137  3695  3830 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
11-08 11:18:27.137  3695  3830 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-08 11:18:27.137  3695  3830 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-08 11:18:27.137  3695  3830 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-08 11:18:27.139  3502  3502 I Process : Sending signal. PID: 3502 SIG: 9
11-08 11:18:27.140   934   947 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 2708)
11-08 11:18:27.141   934   947 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.google.android.gms/com.google.android.gms.app.receiver.SystemBroadcastReceiver}
11-08 11:18:27.141   934   947 W BroadcastQueue: android.os.DeadObjectException: Transaction failed on small parcel; remote process probably died
11-08 11:18:27.141   934   947 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
11-08 11:18:27.141   934   947 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:503)
11-08 11:18:27.141   934   947 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:891)
11-08 11:18:27.141   934   947 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:273)
11-08 11:18:27.141   934   947 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1039)
11-08 11:18:27.141   934   947 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue$BroadcastHandler.handleMessage(BroadcastQueue.java:168)
11-08 11:18:27.141   934   947 W BroadcastQueue: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-08 11:18:27.141   934   947 W BroadcastQueue: 	at android.os.Looper.loop(Looper.java:148)
11-08 11:18:27.141   934   947 W BroadcastQueue: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-08 11:18:27.141   934   947 W BroadcastQueue: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,11-08 11:18:27.166  3325  5980 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
11-08 11:18:27.167  3325  5980 I Process : Sending signal. PID: 3325 SIG: 9
11-08 11:18:27.186   934  2876 D WifiService: Client connection lost with reason: 4
11-08 11:18:27.189   934   947 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.tapandpay.hce.service.TpHceService in 1000ms
11-08 11:18:27.189   934   947 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 10999ms
11-08 11:18:27.189   934   947 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 20999ms
11-08 11:18:27.189   934   947 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 30999ms

```
